
# Convert `cmocean` colormaps to ".pal" files for ncWMS2

`cmocean` is a Python module that provides perceptually uniform colormaps broadly aimed at the earth, ocean and atmospheric sciences. You can read more here https://matplotlib.org/cmocean/.

A paper describing the motivation and selected colormaps can be found [here](http://tos.org/oceanography/assets/docs/29-3_thyng.pdf), which can be cited as:

> Thyng, K.M., C.A. Greene, R.D. Hetland, H.M. Zimmerle, and S.F. DiMarco. 2016. True colors of oceanography: Guidelines for effective and accurate colormap selection. Oceanography 29(3):9–13, http://dx.doi.org/10.5670/oceanog.2016.66.

*ncWMS2* is is an OGC Web Map Service designed to serve geospatial data stored in netCDF files to GIS and web map clients (https://reading-escience-centre.gitbooks.io/ncwms-user-guide/content/). It comes with a set of default colormaps, but we would like to leverage the work done in `cmocean` in addition to providing consistent colormaps with figures generated by Python.

The Java-based web service provides an easy way to add new styles to the server, and for colormaps we can simply add ".pal" files for each colormap where the name of the file will be the name of the colormap. Each ".pal" palette file contains one line for each color provided by the colormap (intermediate colors are interpolated by the server if necessary) which are expressed as hexadecimal colors (i.e. #RRGGBB).


## Install `cmocean`

```bash
# With pip
pip install cmocean

# or with conda using conda-forge channel
conda install -c conda-forge cmocean
```

## Generate ncWMS2 colormap files

1. Import `cmocean`


```python
import cmocean
cmocean.__version__
```




    '2.0'



2. How many individual colors do we have for each cmap?


```python
cmocean.cm.algae.N
```




    256



3. Apparently cmocean has an *rgb2hex* method that we can use for each color in a cmap:


```python
cmocean.cm.colors.rgb2hex(cmocean.cm.algae(254))
```




    '#122515'



4. Put this all together in a simple but perhaps not the most efficient way to loop through each color and create an ncWMS2 ".pal" file for each colormap in `cmocean`:


```python
for cname in cmocean.cm.cmapnames:
    print(cname)
    with open("cmo_{0}.pal".format(cname), "w") as f:
        cmap = cmocean.cm.__getattribute__(cname)
        for x in range(cmap.N):
            ahex = cmocean.cm.colors.rgb2hex(cmap(x))
            f.write("{0}\n".format(ahex))

```

    thermal
    haline
    solar
    ice
    gray
    oxy
    deep
    dense
    algae
    matter
    turbid
    speed
    amp
    tempo
    rain
    phase
    topo
    balance
    delta
    curl
    diff
    tarn


## Add to correct *ncWMS2* path

According to the *ncWMS2* documentation:

> The palette files can be placed in a directory named .palettes within the main config directory (i.e. ~/.ncWMS2/.palettes/ by default) and will be picked up automatically after a server restart.

Although they can be placed in other locations with [additional configuration.](https://reading-escience-centre.gitbooks.io/ncwms-user-guide/content/06-development.html#palettes)

```bash
# Copy generated colormap files to ncWMS2 palette path
cp cmo*.pal /path/to/.ncWMS2/.palettes/
```
