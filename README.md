<!DOCTYPE html>
<html data-markdown-preview-plus-context="html-export">
  <head>
    <meta charset="utf-8" />
    <title>README</title>
    <style>.emoji {
  max-width: 1em !important;
}
del {
  text-decoration: none;
  position: relative;
}
del::after {
  border-bottom: 1px solid black;
  content: '';
  left: 0;
  position: absolute;
  right: 0;
  top: 50%;
}
ul.contains-task-list li.task-list-item {
  position: relative;
  list-style-type: none;
}
ul.contains-task-list li.task-list-item input.task-list-item-checkbox {
  position: absolute;
  transform: translateX(-100%);
  width: 37px;
}
span.critic.comment {
  position: relative;
}
span.critic.comment::before {
  content: '\1f4ac';
  position: initial;
}
span.critic.comment > span {
  display: none;
}
span.critic.comment:hover > span {
  display: initial;
  position: absolute;
  top: 100%;
  left: 0;
  border: 1px solid;
  border-radius: 5px;
  max-height: 4em;
  overflow: auto;
}
span.critic.comment:focus > span {
  display: initial;
  text-decoration: underline;
  position: initial;
  top: auto;
  left: auto;
  border: initial;
  border-radius: initial;
}
table {
  border-collapse: collapse;
  border-spacing: 0;
  background-color: transparent;
}

body {
  overflow: initial !important;
  overflow: hidden;
  font-family: "Helvetica Neue", Helvetica, "Segoe UI", Arial, freesans, sans-serif;
  line-height: 1.6;
  word-wrap: break-word;
  padding: 30px;
  font-size: 16px;
  color: #333;
  background-color: #fff;
}
body > *:first-child {
  margin-top: 0 !important;
}
body > *:last-child {
  margin-bottom: 0 !important;
}
body a:not([href]) {
  color: inherit;
  text-decoration: none;
}
body .absent {
  color: #c00;
}
body .anchor {
  position: absolute;
  top: 0;
  left: 0;
  display: block;
  padding-right: 6px;
  padding-left: 30px;
  margin-left: -30px;
}
body .anchor:focus {
  outline: none;
}
body h1,
body h2,
body h3,
body h4,
body h5,
body h6 {
  position: relative;
  margin-top: 1em;
  margin-bottom: 16px;
  font-weight: bold;
  line-height: 1.4;
}
body h1 .octicon-link,
body h2 .octicon-link,
body h3 .octicon-link,
body h4 .octicon-link,
body h5 .octicon-link,
body h6 .octicon-link {
  display: none;
  color: #000;
  vertical-align: middle;
}
body h1:hover .anchor,
body h2:hover .anchor,
body h3:hover .anchor,
body h4:hover .anchor,
body h5:hover .anchor,
body h6:hover .anchor {
  padding-left: 8px;
  margin-left: -30px;
  text-decoration: none;
}
body h1:hover .anchor .octicon-link,
body h2:hover .anchor .octicon-link,
body h3:hover .anchor .octicon-link,
body h4:hover .anchor .octicon-link,
body h5:hover .anchor .octicon-link,
body h6:hover .anchor .octicon-link {
  display: inline-block;
}
body h1 tt,
body h2 tt,
body h3 tt,
body h4 tt,
body h5 tt,
body h6 tt,
body h1 code,
body h2 code,
body h3 code,
body h4 code,
body h5 code,
body h6 code {
  font-size: inherit;
}
body h1 {
  padding-bottom: 0.3em;
  font-size: 2.25em;
  line-height: 1.2;
  border-bottom: 1px solid #eee;
}
body h1 .anchor {
  line-height: 1;
}
body h2 {
  padding-bottom: 0.3em;
  font-size: 1.75em;
  line-height: 1.225;
  border-bottom: 1px solid #eee;
}
body h2 .anchor {
  line-height: 1;
}
body h3 {
  font-size: 1.5em;
  line-height: 1.43;
}
body h3 .anchor {
  line-height: 1.2;
}
body h4 {
  font-size: 1.25em;
}
body h4 .anchor {
  line-height: 1.2;
}
body h5 {
  font-size: 1em;
}
body h5 .anchor {
  line-height: 1.1;
}
body h6 {
  font-size: 1em;
  color: #777;
}
body h6 .anchor {
  line-height: 1.1;
}
body p,
body blockquote,
body ul,
body ol,
body dl,
body table,
body pre {
  margin-top: 0;
  margin-bottom: 16px;
}
body hr {
  height: 4px;
  padding: 0;
  margin: 16px 0;
  background-color: #e7e7e7;
  border: 0 none;
}
body ul,
body ol {
  padding-left: 2em;
}
body ul.no-list,
body ol.no-list {
  padding: 0;
  list-style-type: none;
}
body ul ul,
body ul ol,
body ol ol,
body ol ul {
  margin-top: 0;
  margin-bottom: 0;
}
body li > p {
  margin-top: 16px;
}
body dl {
  padding: 0;
}
body dl dt {
  padding: 0;
  margin-top: 16px;
  font-size: 1em;
  font-style: italic;
  font-weight: bold;
}
body dl dd {
  padding: 0 16px;
  margin-bottom: 16px;
}
body blockquote {
  padding: 0 15px;
  color: #777;
  border-left: 4px solid #ddd;
}
body blockquote > :first-child {
  margin-top: 0;
}
body blockquote > :last-child {
  margin-bottom: 0;
}
body table {
  display: block;
  width: 100%;
  overflow: auto;
  word-break: normal;
  word-break: keep-all;
}
body table th {
  font-weight: bold;
}
body table th,
body table td {
  padding: 6px 13px;
  border: 1px solid #ddd;
}
body table tr {
  background-color: #fff;
  border-top: 1px solid #ccc;
}
body table tr:nth-child(2n) {
  background-color: #f8f8f8;
}
body img {
  max-width: 100%;
  -moz-box-sizing: border-box;
  box-sizing: border-box;
}
body .emoji {
  max-width: none;
}
body span.frame {
  display: block;
  overflow: hidden;
}
body span.frame > span {
  display: block;
  float: left;
  width: auto;
  padding: 7px;
  margin: 13px 0 0;
  overflow: hidden;
  border: 1px solid #ddd;
}
body span.frame span img {
  display: block;
  float: left;
}
body span.frame span span {
  display: block;
  padding: 5px 0 0;
  clear: both;
  color: #333;
}
body span.align-center {
  display: block;
  overflow: hidden;
  clear: both;
}
body span.align-center > span {
  display: block;
  margin: 13px auto 0;
  overflow: hidden;
  text-align: center;
}
body span.align-center span img {
  margin: 0 auto;
  text-align: center;
}
body span.align-right {
  display: block;
  overflow: hidden;
  clear: both;
}
body span.align-right > span {
  display: block;
  margin: 13px 0 0;
  overflow: hidden;
  text-align: right;
}
body span.align-right span img {
  margin: 0;
  text-align: right;
}
body span.float-left {
  display: block;
  float: left;
  margin-right: 13px;
  overflow: hidden;
}
body span.float-left span {
  margin: 13px 0 0;
}
body span.float-right {
  display: block;
  float: right;
  margin-left: 13px;
  overflow: hidden;
}
body span.float-right > span {
  display: block;
  margin: 13px auto 0;
  overflow: hidden;
  text-align: right;
}
body code,
body tt {
  padding: 0;
  padding-top: 0.2em;
  padding-bottom: 0.2em;
  margin: 0;
  font-size: 85%;
  background-color: rgba(0, 0, 0, 0.04);
  border-radius: 3px;
}
body code:before,
body tt:before,
body code:after,
body tt:after {
  letter-spacing: -0.2em;
  content: "\00a0";
}
body code br,
body tt br {
  display: none;
}
body del code {
  text-decoration: inherit;
}
body pre > code {
  padding: 0;
  margin: 0;
  font-size: 100%;
  word-break: normal;
  white-space: pre;
  background: transparent;
  border: 0;
}
body .highlight {
  margin-bottom: 16px;
}
body .highlight pre,
body pre {
  padding: 16px;
  overflow: auto;
  font-size: 85%;
  line-height: 1.45;
  background-color: #f7f7f7;
  border-radius: 3px;
}
body .highlight pre {
  margin-bottom: 0;
  word-break: normal;
}
body pre {
  word-wrap: normal;
}
body pre code,
body pre tt {
  display: inline;
  max-width: initial;
  padding: 0;
  margin: 0;
  overflow: initial;
  line-height: inherit;
  word-wrap: normal;
  background-color: transparent;
  border: 0;
}
body pre code:before,
body pre tt:before,
body pre code:after,
body pre tt:after {
  content: normal;
}
body kbd {
  display: inline-block;
  padding: 3px 5px;
  font-size: 11px;
  line-height: 10px;
  color: #555;
  vertical-align: middle;
  background-color: #fcfcfc;
  border: solid 1px #ccc;
  border-bottom-color: #bbb;
  border-radius: 3px;
  box-shadow: inset 0 -1px 0 #bbb;
}
span.critic.comment > span {
  background-color: #fff;
}
a {
  color: #337ab7;
}

@keyframes RotatingBackground {
  0% {
    background-position-x: 0%;
  }
  100% {
    background-position-x: 100%;
  }
}

.debugger-breakpoint-icon::before,
.debugger-shadow-breakpoint-icon::before {
  font-family: 'Octicons Regular';
  font-weight: normal;
  font-style: normal;
  display: inline-block;
  line-height: 1;
  -webkit-font-smoothing: antialiased;
  text-decoration: none;
  font-size: 130%;
  width: 130%;
  height: 130%;
  content: "\f052";
}
.debugger-breakpoint-icon,
.debugger-breakpoint-icon-disabled,
.debugger-breakpoint-icon-unresolved,
.debugger-breakpoint-icon-conditional,
.debugger-shadow-breakpoint-icon {
  text-align: center;
  display: block;
  width: 0.8em;
  cursor: pointer;
}
.debugger-breakpoint-icon-nonconditional {
  color: #539afc;
}
.debugger-breakpoint-icon-conditional {
  color: #ebbf83;
}
.debugger-breakpoint-icon-disabled {
  position: relative;
  top: -4px;
  left: 2px;
}
.debugger-breakpoint-icon-disabled::before {
  font-family: 'Octicons Regular';
  font-weight: normal;
  font-style: normal;
  display: inline-block;
  line-height: 1;
  -webkit-font-smoothing: antialiased;
  text-decoration: none;
  font-size: 78%;
  width: 78%;
  height: 78%;
  content: "\f084";
}
.debugger-breakpoint-icon-unresolved {
  position: relative;
  top: -2px;
}
.debugger-breakpoint-icon-unresolved::before {
  font-family: 'Octicons Regular';
  font-weight: normal;
  font-style: normal;
  display: inline-block;
  line-height: 1;
  -webkit-font-smoothing: antialiased;
  text-decoration: none;
  font-size: 80%;
  width: 80%;
  height: 80%;
  content: "\f0e8";
}
.debugger-shadow-breakpoint-icon {
  color: rgba(83, 154, 252, 0.4);
}
.debugger-current-line-highlight {
  background: linear-gradient(to bottom, rgba(3, 77, 179, 0.8) 0%, rgba(3, 77, 179, 0.8) 5%, rgba(3, 77, 179, 0.3) 5%, rgba(3, 77, 179, 0.3) 95%, rgba(3, 77, 179, 0.8) 95%, rgba(3, 77, 179, 0.8) 100%);
}

.gutter[gutter-name=diagnostics-gutter] {
  width: 0.7em;
}
.diagnostics-gutter-ui-item {
  display: flex;
}
.diagnostics-gutter-ui-item .icon {
  display: flex;
  width: 0.7em;
  height: 0.7em;
  font-size: 0.7em;
  align-self: center;
}
.diagnostics-gutter-ui-item .icon::before {
  width: 1em;
  height: 1em;
  font-size: 1em;
  margin: 0;
  align-self: center;
}
.diagnostics-gutter-ui-item.diagnostics-gutter-ui-gutter-info,
.diagnostics-gutter-ui-item.diagnostics-gutter-ui-gutter-review {
  color: #539afc;
}
.diagnostics-gutter-ui-item.diagnostics-gutter-ui-gutter-error {
  color: #e27e8d;
}
.diagnostics-gutter-ui-item.diagnostics-gutter-ui-gutter-action,
.diagnostics-gutter-ui-item.diagnostics-gutter-ui-gutter-warning {
  color: #ebbf83;
}

.bracket-matcher .region {
  border-bottom: 1px dotted lime;
  position: absolute;
}
.line-number.bracket-matcher.bracket-matcher {
  color: #abb2bf;
  background-color: #3a3f4b;
}

.spell-check-misspelling .region {
  border-bottom: 2px dotted rgba(255, 51, 51, 0.75);
}
.spell-check-corrections {
  width: 25em !important;
}

pre.editor-colors {
  background-color: #282c34;
  color: #abb2bf;
}
pre.editor-colors .line.cursor-line {
  background-color: rgba(153, 187, 255, 0.04);
}
pre.editor-colors .invisible {
  color: #abb2bf;
}
pre.editor-colors .cursor {
  border-left: 2px solid #528bff;
}
pre.editor-colors .selection .region {
  background-color: #3e4451;
}
pre.editor-colors .bracket-matcher .region {
  border-bottom: 1px solid #528bff;
  box-sizing: border-box;
}
pre.editor-colors .invisible-character {
  color: rgba(171, 178, 191, 0.15);
}
pre.editor-colors .indent-guide {
  color: rgba(171, 178, 191, 0.15);
}
pre.editor-colors .wrap-guide {
  background-color: rgba(171, 178, 191, 0.15);
}
pre.editor-colors .find-result .region.region.region,
pre.editor-colors .current-result .region.region.region {
  border-radius: 2px;
  background-color: rgba(82, 139, 255, 0.24);
  transition: border-color 0.4s;
}
pre.editor-colors .find-result .region.region.region {
  border: 2px solid transparent;
}
pre.editor-colors .current-result .region.region.region {
  border: 2px solid #528bff;
  transition-duration: .1s;
}
pre.editor-colors .gutter .line-number {
  color: #636d83;
  -webkit-font-smoothing: antialiased;
}
pre.editor-colors .gutter .line-number.cursor-line {
  color: #abb2bf;
  background-color: #3a3f4b;
}
pre.editor-colors .gutter .line-number.cursor-line-no-selection {
  background-color: transparent;
}
pre.editor-colors .gutter .line-number .icon-right {
  color: #abb2bf;
}
pre.editor-colors .gutter:not(.git-diff-icon) .line-number.git-line-removed.git-line-removed::before {
  bottom: -3px;
}
pre.editor-colors .gutter:not(.git-diff-icon) .line-number.git-line-removed::after {
  content: "";
  position: absolute;
  left: 0px;
  bottom: 0px;
  width: 25px;
  border-bottom: 1px dotted rgba(224, 82, 82, 0.5);
  pointer-events: none;
}
pre.editor-colors .gutter .line-number.folded,
pre.editor-colors .gutter .line-number:after,
pre.editor-colors .fold-marker:after {
  color: #abb2bf;
}
.syntax--comment {
  color: #5c6370;
  font-style: italic;
}
.syntax--comment .syntax--markup.syntax--link {
  color: #5c6370;
}
.syntax--entity.syntax--name.syntax--type {
  color: #e5c07b;
}
.syntax--entity.syntax--other.syntax--inherited-class {
  color: #98c379;
}
.syntax--keyword {
  color: #c678dd;
}
.syntax--keyword.syntax--control {
  color: #c678dd;
}
.syntax--keyword.syntax--operator {
  color: #abb2bf;
}
.syntax--keyword.syntax--other.syntax--special-method {
  color: #61afef;
}
.syntax--keyword.syntax--other.syntax--unit {
  color: #d19a66;
}
.syntax--storage {
  color: #c678dd;
}
.syntax--storage.syntax--type.syntax--annotation,
.syntax--storage.syntax--type.syntax--primitive {
  color: #c678dd;
}
.syntax--storage.syntax--modifier.syntax--package,
.syntax--storage.syntax--modifier.syntax--import {
  color: #abb2bf;
}
.syntax--constant {
  color: #d19a66;
}
.syntax--constant.syntax--variable {
  color: #d19a66;
}
.syntax--constant.syntax--character.syntax--escape {
  color: #56b6c2;
}
.syntax--constant.syntax--numeric {
  color: #d19a66;
}
.syntax--constant.syntax--other.syntax--color {
  color: #56b6c2;
}
.syntax--constant.syntax--other.syntax--symbol {
  color: #56b6c2;
}
.syntax--variable {
  color: #e06c75;
}
.syntax--variable.syntax--interpolation {
  color: #be5046;
}
.syntax--variable.syntax--parameter {
  color: #abb2bf;
}
.syntax--string {
  color: #98c379;
}
.syntax--string > .syntax--source,
.syntax--string .syntax--embedded {
  color: #abb2bf;
}
.syntax--string.syntax--regexp {
  color: #56b6c2;
}
.syntax--string.syntax--regexp .syntax--source.syntax--ruby.syntax--embedded {
  color: #e5c07b;
}
.syntax--string.syntax--other.syntax--link {
  color: #e06c75;
}
.syntax--punctuation.syntax--definition.syntax--comment {
  color: #5c6370;
}
.syntax--punctuation.syntax--definition.syntax--method-parameters,
.syntax--punctuation.syntax--definition.syntax--function-parameters,
.syntax--punctuation.syntax--definition.syntax--parameters,
.syntax--punctuation.syntax--definition.syntax--separator,
.syntax--punctuation.syntax--definition.syntax--seperator,
.syntax--punctuation.syntax--definition.syntax--array {
  color: #abb2bf;
}
.syntax--punctuation.syntax--definition.syntax--heading,
.syntax--punctuation.syntax--definition.syntax--identity {
  color: #61afef;
}
.syntax--punctuation.syntax--definition.syntax--bold {
  color: #e5c07b;
  font-weight: bold;
}
.syntax--punctuation.syntax--definition.syntax--italic {
  color: #c678dd;
  font-style: italic;
}
.syntax--punctuation.syntax--section.syntax--embedded {
  color: #be5046;
}
.syntax--punctuation.syntax--section.syntax--method,
.syntax--punctuation.syntax--section.syntax--class,
.syntax--punctuation.syntax--section.syntax--inner-class {
  color: #abb2bf;
}
.syntax--support.syntax--class {
  color: #e5c07b;
}
.syntax--support.syntax--type {
  color: #56b6c2;
}
.syntax--support.syntax--function {
  color: #56b6c2;
}
.syntax--support.syntax--function.syntax--any-method {
  color: #61afef;
}
.syntax--entity.syntax--name.syntax--function {
  color: #61afef;
}
.syntax--entity.syntax--name.syntax--class,
.syntax--entity.syntax--name.syntax--type.syntax--class {
  color: #e5c07b;
}
.syntax--entity.syntax--name.syntax--section {
  color: #61afef;
}
.syntax--entity.syntax--name.syntax--tag {
  color: #e06c75;
}
.syntax--entity.syntax--other.syntax--attribute-name {
  color: #d19a66;
}
.syntax--entity.syntax--other.syntax--attribute-name.syntax--id {
  color: #61afef;
}
.syntax--meta.syntax--class {
  color: #e5c07b;
}
.syntax--meta.syntax--class.syntax--body {
  color: #abb2bf;
}
.syntax--meta.syntax--method-call,
.syntax--meta.syntax--method {
  color: #abb2bf;
}
.syntax--meta.syntax--definition.syntax--variable {
  color: #e06c75;
}
.syntax--meta.syntax--link {
  color: #d19a66;
}
.syntax--meta.syntax--require {
  color: #61afef;
}
.syntax--meta.syntax--selector {
  color: #c678dd;
}
.syntax--meta.syntax--separator {
  color: #abb2bf;
}
.syntax--meta.syntax--tag {
  color: #abb2bf;
}
.syntax--underline {
  text-decoration: underline;
}
.syntax--none {
  color: #abb2bf;
}
.syntax--invalid.syntax--deprecated {
  color: #523d14 !important;
  background-color: #e0c285 !important;
}
.syntax--invalid.syntax--illegal {
  color: white !important;
  background-color: #e05252 !important;
}
.syntax--markup.syntax--bold {
  color: #d19a66;
  font-weight: bold;
}
.syntax--markup.syntax--changed {
  color: #c678dd;
}
.syntax--markup.syntax--deleted {
  color: #e06c75;
}
.syntax--markup.syntax--italic {
  color: #c678dd;
  font-style: italic;
}
.syntax--markup.syntax--heading {
  color: #e06c75;
}
.syntax--markup.syntax--heading .syntax--punctuation.syntax--definition.syntax--heading {
  color: #61afef;
}
.syntax--markup.syntax--link {
  color: #56b6c2;
}
.syntax--markup.syntax--inserted {
  color: #98c379;
}
.syntax--markup.syntax--quote {
  color: #d19a66;
}
.syntax--markup.syntax--raw {
  color: #98c379;
}
.syntax--source.syntax--c .syntax--keyword.syntax--operator {
  color: #c678dd;
}
.syntax--source.syntax--cpp .syntax--keyword.syntax--operator {
  color: #c678dd;
}
.syntax--source.syntax--cs .syntax--keyword.syntax--operator {
  color: #c678dd;
}
.syntax--source.syntax--css .syntax--property-name,
.syntax--source.syntax--css .syntax--property-value {
  color: #828997;
}
.syntax--source.syntax--css .syntax--property-name.syntax--support,
.syntax--source.syntax--css .syntax--property-value.syntax--support {
  color: #abb2bf;
}
.syntax--source.syntax--elixir .syntax--source.syntax--embedded.syntax--source {
  color: #abb2bf;
}
.syntax--source.syntax--elixir .syntax--constant.syntax--language,
.syntax--source.syntax--elixir .syntax--constant.syntax--numeric,
.syntax--source.syntax--elixir .syntax--constant.syntax--definition {
  color: #61afef;
}
.syntax--source.syntax--elixir .syntax--variable.syntax--definition,
.syntax--source.syntax--elixir .syntax--variable.syntax--anonymous {
  color: #c678dd;
}
.syntax--source.syntax--elixir .syntax--parameter.syntax--variable.syntax--function {
  color: #d19a66;
  font-style: italic;
}
.syntax--source.syntax--elixir .syntax--quoted {
  color: #98c379;
}
.syntax--source.syntax--elixir .syntax--keyword.syntax--special-method,
.syntax--source.syntax--elixir .syntax--embedded.syntax--section,
.syntax--source.syntax--elixir .syntax--embedded.syntax--source.syntax--empty {
  color: #e06c75;
}
.syntax--source.syntax--elixir .syntax--readwrite.syntax--module .syntax--punctuation {
  color: #e06c75;
}
.syntax--source.syntax--elixir .syntax--regexp.syntax--section,
.syntax--source.syntax--elixir .syntax--regexp.syntax--string {
  color: #be5046;
}
.syntax--source.syntax--elixir .syntax--separator,
.syntax--source.syntax--elixir .syntax--keyword.syntax--operator {
  color: #d19a66;
}
.syntax--source.syntax--elixir .syntax--variable.syntax--constant {
  color: #e5c07b;
}
.syntax--source.syntax--elixir .syntax--array,
.syntax--source.syntax--elixir .syntax--scope,
.syntax--source.syntax--elixir .syntax--section {
  color: #828997;
}
.syntax--source.syntax--gfm .syntax--markup {
  -webkit-font-smoothing: auto;
}
.syntax--source.syntax--gfm .syntax--link .syntax--entity {
  color: #61afef;
}
.syntax--source.syntax--go .syntax--storage.syntax--type.syntax--string {
  color: #c678dd;
}
.syntax--source.syntax--ini .syntax--keyword.syntax--other.syntax--definition.syntax--ini {
  color: #e06c75;
}
.syntax--source.syntax--java .syntax--storage.syntax--modifier.syntax--import {
  color: #e5c07b;
}
.syntax--source.syntax--java .syntax--storage.syntax--type {
  color: #e5c07b;
}
.syntax--source.syntax--java .syntax--keyword.syntax--operator.syntax--instanceof {
  color: #c678dd;
}
.syntax--source.syntax--java-properties .syntax--meta.syntax--key-pair {
  color: #e06c75;
}
.syntax--source.syntax--java-properties .syntax--meta.syntax--key-pair > .syntax--punctuation {
  color: #abb2bf;
}
.syntax--source.syntax--js .syntax--keyword.syntax--operator {
  color: #56b6c2;
}
.syntax--source.syntax--js .syntax--keyword.syntax--operator.syntax--delete,
.syntax--source.syntax--js .syntax--keyword.syntax--operator.syntax--in,
.syntax--source.syntax--js .syntax--keyword.syntax--operator.syntax--of,
.syntax--source.syntax--js .syntax--keyword.syntax--operator.syntax--instanceof,
.syntax--source.syntax--js .syntax--keyword.syntax--operator.syntax--new,
.syntax--source.syntax--js .syntax--keyword.syntax--operator.syntax--typeof,
.syntax--source.syntax--js .syntax--keyword.syntax--operator.syntax--void {
  color: #c678dd;
}
.syntax--source.syntax--ts .syntax--keyword.syntax--operator {
  color: #56b6c2;
}
.syntax--source.syntax--flow .syntax--keyword.syntax--operator {
  color: #56b6c2;
}
.syntax--source.syntax--json .syntax--meta.syntax--structure.syntax--dictionary.syntax--json > .syntax--string.syntax--quoted.syntax--json {
  color: #e06c75;
}
.syntax--source.syntax--json .syntax--meta.syntax--structure.syntax--dictionary.syntax--json > .syntax--string.syntax--quoted.syntax--json > .syntax--punctuation.syntax--string {
  color: #e06c75;
}
.syntax--source.syntax--json .syntax--meta.syntax--structure.syntax--dictionary.syntax--json > .syntax--value.syntax--json > .syntax--string.syntax--quoted.syntax--json,
.syntax--source.syntax--json .syntax--meta.syntax--structure.syntax--array.syntax--json > .syntax--value.syntax--json > .syntax--string.syntax--quoted.syntax--json,
.syntax--source.syntax--json .syntax--meta.syntax--structure.syntax--dictionary.syntax--json > .syntax--value.syntax--json > .syntax--string.syntax--quoted.syntax--json > .syntax--punctuation,
.syntax--source.syntax--json .syntax--meta.syntax--structure.syntax--array.syntax--json > .syntax--value.syntax--json > .syntax--string.syntax--quoted.syntax--json > .syntax--punctuation {
  color: #98c379;
}
.syntax--source.syntax--json .syntax--meta.syntax--structure.syntax--dictionary.syntax--json > .syntax--constant.syntax--language.syntax--json,
.syntax--source.syntax--json .syntax--meta.syntax--structure.syntax--array.syntax--json > .syntax--constant.syntax--language.syntax--json {
  color: #56b6c2;
}
.syntax--ng.syntax--interpolation {
  color: #e06c75;
}
.syntax--ng.syntax--interpolation.syntax--begin,
.syntax--ng.syntax--interpolation.syntax--end {
  color: #61afef;
}
.syntax--ng.syntax--interpolation .syntax--function {
  color: #e06c75;
}
.syntax--ng.syntax--interpolation .syntax--function.syntax--begin,
.syntax--ng.syntax--interpolation .syntax--function.syntax--end {
  color: #61afef;
}
.syntax--ng.syntax--interpolation .syntax--bool {
  color: #d19a66;
}
.syntax--ng.syntax--interpolation .syntax--bracket {
  color: #abb2bf;
}
.syntax--ng.syntax--pipe,
.syntax--ng.syntax--operator {
  color: #abb2bf;
}
.syntax--ng.syntax--tag {
  color: #56b6c2;
}
.syntax--ng.syntax--attribute-with-value .syntax--attribute-name {
  color: #e5c07b;
}
.syntax--ng.syntax--attribute-with-value .syntax--string {
  color: #c678dd;
}
.syntax--ng.syntax--attribute-with-value .syntax--string.syntax--begin,
.syntax--ng.syntax--attribute-with-value .syntax--string.syntax--end {
  color: #abb2bf;
}
.syntax--source.syntax--ruby .syntax--constant.syntax--other.syntax--symbol > .syntax--punctuation {
  color: inherit;
}
.syntax--source.syntax--php .syntax--class.syntax--bracket {
  color: #abb2bf;
}
.syntax--source.syntax--python .syntax--keyword.syntax--operator.syntax--logical.syntax--python {
  color: #c678dd;
}
.syntax--source.syntax--python .syntax--variable.syntax--parameter {
  color: #d19a66;
}

/*
 * Your Stylesheet
 *
 * This stylesheet is loaded when Atom starts up and is reloaded automatically
 * when it is changed and saved.
 *
 * Add your own CSS or Less to fully customize Atom.
 * If you are unfamiliar with Less, you can read more about it here:
 * http://lesscss.org
 */
/*
 * Examples
 * (To see them, uncomment and save)
 */
</style>

  </head>
  <body>
    <h1>Convert <code style="font-family: Menlo, Consolas, &quot;DejaVu Sans Mono&quot;, monospace;">cmocean</code> colormaps to “.pal” files for ncWMS2</h1>
<p><code style="font-family: Menlo, Consolas, &quot;DejaVu Sans Mono&quot;, monospace;">cmocean</code> is a Python module that provides perceptually uniform colormaps broadly aimed at the earth, ocean and atmospheric sciences. You can read more here <a href="https://matplotlib.org/cmocean/">https://matplotlib.org/cmocean/</a>.</p>
<p>A paper describing the motivation and selected colormaps can be found <a href="http://tos.org/oceanography/assets/docs/29-3_thyng.pdf">here</a>, which can be cited as:</p>
<blockquote>
<p>Thyng, K.M., C.A. Greene, R.D. Hetland, H.M. Zimmerle, and S.F. DiMarco. 2016. True colors of oceanography: Guidelines for effective and accurate colormap selection. Oceanography 29(3):9–13, <a href="http://dx.doi.org/10.5670/oceanog.2016.66">http://dx.doi.org/10.5670/oceanog.2016.66</a>.</p>
</blockquote>
<p><em>ncWMS2</em> is is an OGC Web Map Service designed to serve geospatial data stored in netCDF files to GIS and web map clients (<a href="https://reading-escience-centre.gitbooks.io/ncwms-user-guide/content/">https://reading-escience-centre.gitbooks.io/ncwms-user-guide/content/</a>). It comes with a set of default colormaps, but we would like to leverage the work done in <code style="font-family: Menlo, Consolas, &quot;DejaVu Sans Mono&quot;, monospace;">cmocean</code> in addition to providing consistent colormaps with figures generated by Python.</p>
<p>The Java-based web service provides an easy way to add new styles to the server, and for colormaps we can simply add “.pal” files for each colormap where the name of the file will be the name of the colormap. Each “.pal” palette file contains one line for each color provided by the colormap (intermediate colors are interpolated by the server if necessary) which are expressed as hexadecimal colors (i.e. #RRGGBB).</p>
<p><strong>Note: Skip <a href="#Add-to-correct-ncWMS2-path">below</a> to use the files we have already generated.</strong></p>
<h2>Install <code style="font-family: Menlo, Consolas, &quot;DejaVu Sans Mono&quot;, monospace;">cmocean</code></h2>
<pre class="editor-colors lang-bash"><span><span class="syntax--source syntax--shell"><span class="syntax--comment syntax--block"># With pip</span></span></span>
<span class=""><span class="syntax--source syntax--shell"><span class="syntax--entity syntax--name syntax--function">pip</span> install cmocean</span></span>
<span class=""></span> 
<span class=""><span class="syntax--source syntax--shell"><span class="syntax--comment syntax--block"># or with conda using conda-forge channel</span></span></span>
<span class=""><span class="syntax--source syntax--shell"><span class="syntax--entity syntax--name syntax--function">conda</span> install <span class="syntax--entity syntax--other syntax--attribute-name">-c</span> conda-forge cmocean</span></span></pre>
<h2>Generate ncWMS2 colormap files</h2>
<ol>
<li>Import <code style="font-family: Menlo, Consolas, &quot;DejaVu Sans Mono&quot;, monospace;">cmocean</code></li>
</ol>
<pre class="editor-colors lang-python"><span><span class="syntax--source syntax--python"><span class="syntax--keyword syntax--control">import</span> cmocean</span></span>
<span class=""><span class="syntax--source syntax--python">cmocean.<span class="syntax--variable syntax--other syntax--object syntax--property">__version__</span></span></span></pre>
<pre class="editor-colors lang-text"><span><span class="syntax--text syntax--plain"><span class="syntax--meta syntax--paragraph syntax--text">'2.0'</span></span></span></pre>
<ol start="2">
<li>How many individual colors do we have for each cmap?</li>
</ol>
<pre class="editor-colors lang-python"><span class=""><span class="syntax--source syntax--python">cmocean.<span class="syntax--variable syntax--other syntax--object syntax--property">cm</span>.<span class="syntax--variable syntax--other syntax--object syntax--property">algae</span>.<span class="syntax--variable syntax--other syntax--object syntax--property">N</span></span></span></pre>
<pre class="editor-colors lang-text"><span><span class="syntax--text syntax--plain"><span class="syntax--meta syntax--paragraph syntax--text">256</span></span></span></pre>
<ol start="3">
<li>Apparently cmocean has an <em>rgb2hex</em> method that we can use for each color in a cmap:</li>
</ol>
<pre class="editor-colors lang-python"><span class=""><span class="syntax--source syntax--python">cmocean.<span class="syntax--variable syntax--other syntax--object syntax--property">cm</span>.<span class="syntax--variable syntax--other syntax--object syntax--property">colors</span>.<span class="syntax--entity syntax--name syntax--function">rgb2hex</span>(cmocean.<span class="syntax--variable syntax--other syntax--object syntax--property">cm</span>.<span class="syntax--entity syntax--name syntax--function">algae</span>(<span class="syntax--constant syntax--numeric">254</span>))</span></span></pre>
<pre class="editor-colors lang-text"><span><span class="syntax--text syntax--plain"><span class="syntax--meta syntax--paragraph syntax--text">'#122515'</span></span></span></pre>
<ol start="4">
<li>Put this all together in a simple but perhaps not the most efficient way to loop through each color and create an ncWMS2 “.pal” file for each colormap in <code style="font-family: Menlo, Consolas, &quot;DejaVu Sans Mono&quot;, monospace;">cmocean</code>:</li>
</ol>
<pre class="editor-colors lang-python"><span><span class="syntax--source syntax--python"><span class="syntax--keyword syntax--control">for</span> cname <span class="syntax--keyword syntax--operator syntax--logical syntax--python">in</span> cmocean.<span class="syntax--variable syntax--other syntax--object syntax--property">cm</span>.<span class="syntax--variable syntax--other syntax--object syntax--property">cmapnames</span>:</span></span>
<span class=""><span class="syntax--source syntax--python"><span class="leading-whitespace">    </span><span class="syntax--support syntax--function">print</span>(cname)</span></span>
<span class=""><span class="syntax--source syntax--python"><span class="leading-whitespace">    </span><span class="syntax--keyword syntax--control">with</span> <span class="syntax--support syntax--function">open</span>(<span class="syntax--string syntax--quoted">"cmo_{0}.pal"</span>.<span class="syntax--entity syntax--name syntax--function">format</span>(cname), <span class="syntax--string syntax--quoted">"w"</span>) <span class="syntax--keyword syntax--control">as</span> f:</span></span>
<span class=""><span class="syntax--source syntax--python"><span class="leading-whitespace">        </span>cmap <span class="syntax--keyword syntax--operator">=</span> cmocean.<span class="syntax--variable syntax--other syntax--object syntax--property">cm</span>.<span class="syntax--entity syntax--name syntax--function">__getattribute__</span>(cname)</span></span>
<span class=""><span class="syntax--source syntax--python"><span class="leading-whitespace">        </span><span class="syntax--keyword syntax--control">for</span> x <span class="syntax--keyword syntax--operator syntax--logical syntax--python">in</span> <span class="syntax--support syntax--function">range</span>(cmap.<span class="syntax--variable syntax--other syntax--object syntax--property">N</span>):</span></span>
<span class=""><span class="syntax--source syntax--python"><span class="leading-whitespace">            </span>ahex <span class="syntax--keyword syntax--operator">=</span> cmocean.<span class="syntax--variable syntax--other syntax--object syntax--property">cm</span>.<span class="syntax--variable syntax--other syntax--object syntax--property">colors</span>.<span class="syntax--entity syntax--name syntax--function">rgb2hex</span>(<span class="syntax--entity syntax--name syntax--function">cmap</span>(x))</span></span>
<span class=""><span class="syntax--source syntax--python"><span class="leading-whitespace">            </span>f.<span class="syntax--entity syntax--name syntax--function">write</span>(<span class="syntax--string syntax--quoted">"{0}<span class="syntax--constant syntax--character syntax--escape">\n</span>"</span>.<span class="syntax--entity syntax--name syntax--function">format</span>(ahex))</span></span>
<span class=""><span class="syntax--source syntax--python"><span class="trailing-whitespace">    </span></span></span></pre>
<pre class="editor-colors lang-text"><span><span class="syntax--text syntax--plain"><span class="syntax--meta syntax--paragraph syntax--text">thermal</span></span></span>
<span class=""><span class="syntax--text syntax--plain"><span class="syntax--meta syntax--paragraph syntax--text">haline</span></span></span>
<span><span class="syntax--text syntax--plain"><span class="syntax--meta syntax--paragraph syntax--text">solar</span></span></span>
<span><span class="syntax--text syntax--plain"><span class="syntax--meta syntax--paragraph syntax--text">ice</span></span></span>
<span><span class="syntax--text syntax--plain"><span class="syntax--meta syntax--paragraph syntax--text">gray</span></span></span>
<span><span class="syntax--text syntax--plain"><span class="syntax--meta syntax--paragraph syntax--text">oxy</span></span></span>
<span><span class="syntax--text syntax--plain"><span class="syntax--meta syntax--paragraph syntax--text">deep</span></span></span>
<span><span class="syntax--text syntax--plain"><span class="syntax--meta syntax--paragraph syntax--text">dense</span></span></span>
<span><span class="syntax--text syntax--plain"><span class="syntax--meta syntax--paragraph syntax--text">algae</span></span></span>
<span><span class="syntax--text syntax--plain"><span class="syntax--meta syntax--paragraph syntax--text">matter</span></span></span>
<span><span class="syntax--text syntax--plain"><span class="syntax--meta syntax--paragraph syntax--text">turbid</span></span></span>
<span><span class="syntax--text syntax--plain"><span class="syntax--meta syntax--paragraph syntax--text">speed</span></span></span>
<span><span class="syntax--text syntax--plain"><span class="syntax--meta syntax--paragraph syntax--text">amp</span></span></span>
<span><span class="syntax--text syntax--plain"><span class="syntax--meta syntax--paragraph syntax--text">tempo</span></span></span>
<span><span class="syntax--text syntax--plain"><span class="syntax--meta syntax--paragraph syntax--text">rain</span></span></span>
<span><span class="syntax--text syntax--plain"><span class="syntax--meta syntax--paragraph syntax--text">phase</span></span></span>
<span><span class="syntax--text syntax--plain"><span class="syntax--meta syntax--paragraph syntax--text">topo</span></span></span>
<span><span class="syntax--text syntax--plain"><span class="syntax--meta syntax--paragraph syntax--text">balance</span></span></span>
<span><span class="syntax--text syntax--plain"><span class="syntax--meta syntax--paragraph syntax--text">delta</span></span></span>
<span><span class="syntax--text syntax--plain"><span class="syntax--meta syntax--paragraph syntax--text">curl</span></span></span>
<span><span class="syntax--text syntax--plain"><span class="syntax--meta syntax--paragraph syntax--text">diff</span></span></span>
<span><span class="syntax--text syntax--plain"><span class="syntax--meta syntax--paragraph syntax--text">tarn</span></span></span></pre>
<ol start="5">
<li>Create the reverse colormaps and append <code style="font-family: Menlo, Consolas, &quot;DejaVu Sans Mono&quot;, monospace;">_r</code> to the name to be complete:</li>
</ol>
<pre class="editor-colors lang-python"><span><span class="syntax--source syntax--python"><span class="syntax--keyword syntax--control">for</span> cname <span class="syntax--keyword syntax--operator syntax--logical syntax--python">in</span> cmocean.<span class="syntax--variable syntax--other syntax--object syntax--property">cm</span>.<span class="syntax--variable syntax--other syntax--object syntax--property">cmapnames</span>:</span></span>
<span class=""><span class="syntax--source syntax--python"><span class="leading-whitespace">    </span><span class="syntax--support syntax--function">print</span>(<span class="syntax--string syntax--quoted">"{0}_r"</span>.<span class="syntax--entity syntax--name syntax--function">format</span>(cname))</span></span>
<span class=""><span class="syntax--source syntax--python"><span class="leading-whitespace">    </span><span class="syntax--keyword syntax--control">with</span> <span class="syntax--support syntax--function">open</span>(<span class="syntax--string syntax--quoted">"cmo_{0}_r.pal"</span>.<span class="syntax--entity syntax--name syntax--function">format</span>(cname), <span class="syntax--string syntax--quoted">"w"</span>) <span class="syntax--keyword syntax--control">as</span> f:</span></span>
<span class=""><span class="syntax--source syntax--python"><span class="leading-whitespace">        </span>cmap <span class="syntax--keyword syntax--operator">=</span> cmocean.<span class="syntax--variable syntax--other syntax--object syntax--property">cm</span>.<span class="syntax--entity syntax--name syntax--function">__getattribute__</span>(cname)</span></span>
<span class=""><span class="syntax--source syntax--python"><span class="leading-whitespace">        </span><span class="syntax--keyword syntax--control">for</span> x <span class="syntax--keyword syntax--operator syntax--logical syntax--python">in</span> <span class="syntax--support syntax--function">range</span>(cmap.<span class="syntax--variable syntax--other syntax--object syntax--property">N</span>, <span class="syntax--constant syntax--numeric">0</span>, <span class="syntax--keyword syntax--operator">-</span><span class="syntax--constant syntax--numeric">1</span>):</span></span>
<span class=""><span class="syntax--source syntax--python"><span class="leading-whitespace">            </span>ahex <span class="syntax--keyword syntax--operator">=</span> cmocean.<span class="syntax--variable syntax--other syntax--object syntax--property">cm</span>.<span class="syntax--variable syntax--other syntax--object syntax--property">colors</span>.<span class="syntax--entity syntax--name syntax--function">rgb2hex</span>(<span class="syntax--entity syntax--name syntax--function">cmap</span>(x))</span></span>
<span class=""><span class="syntax--source syntax--python"><span class="leading-whitespace">            </span>f.<span class="syntax--entity syntax--name syntax--function">write</span>(<span class="syntax--string syntax--quoted">"{0}<span class="syntax--constant syntax--character syntax--escape">\n</span>"</span>.<span class="syntax--entity syntax--name syntax--function">format</span>(ahex))</span></span></pre>
<pre class="editor-colors lang-text"><span><span class="syntax--text syntax--plain"><span class="syntax--meta syntax--paragraph syntax--text">thermal_r</span></span></span>
<span class=""><span class="syntax--text syntax--plain"><span class="syntax--meta syntax--paragraph syntax--text">haline_r</span></span></span>
<span><span class="syntax--text syntax--plain"><span class="syntax--meta syntax--paragraph syntax--text">solar_r</span></span></span>
<span><span class="syntax--text syntax--plain"><span class="syntax--meta syntax--paragraph syntax--text">ice_r</span></span></span>
<span><span class="syntax--text syntax--plain"><span class="syntax--meta syntax--paragraph syntax--text">gray_r</span></span></span>
<span><span class="syntax--text syntax--plain"><span class="syntax--meta syntax--paragraph syntax--text">oxy_r</span></span></span>
<span><span class="syntax--text syntax--plain"><span class="syntax--meta syntax--paragraph syntax--text">deep_r</span></span></span>
<span><span class="syntax--text syntax--plain"><span class="syntax--meta syntax--paragraph syntax--text">dense_r</span></span></span>
<span><span class="syntax--text syntax--plain"><span class="syntax--meta syntax--paragraph syntax--text">algae_r</span></span></span>
<span><span class="syntax--text syntax--plain"><span class="syntax--meta syntax--paragraph syntax--text">matter_r</span></span></span>
<span><span class="syntax--text syntax--plain"><span class="syntax--meta syntax--paragraph syntax--text">turbid_r</span></span></span>
<span><span class="syntax--text syntax--plain"><span class="syntax--meta syntax--paragraph syntax--text">speed_r</span></span></span>
<span><span class="syntax--text syntax--plain"><span class="syntax--meta syntax--paragraph syntax--text">amp_r</span></span></span>
<span><span class="syntax--text syntax--plain"><span class="syntax--meta syntax--paragraph syntax--text">tempo_r</span></span></span>
<span><span class="syntax--text syntax--plain"><span class="syntax--meta syntax--paragraph syntax--text">rain_r</span></span></span>
<span><span class="syntax--text syntax--plain"><span class="syntax--meta syntax--paragraph syntax--text">phase_r</span></span></span>
<span><span class="syntax--text syntax--plain"><span class="syntax--meta syntax--paragraph syntax--text">topo_r</span></span></span>
<span><span class="syntax--text syntax--plain"><span class="syntax--meta syntax--paragraph syntax--text">balance_r</span></span></span>
<span><span class="syntax--text syntax--plain"><span class="syntax--meta syntax--paragraph syntax--text">delta_r</span></span></span>
<span><span class="syntax--text syntax--plain"><span class="syntax--meta syntax--paragraph syntax--text">curl_r</span></span></span>
<span><span class="syntax--text syntax--plain"><span class="syntax--meta syntax--paragraph syntax--text">diff_r</span></span></span>
<span><span class="syntax--text syntax--plain"><span class="syntax--meta syntax--paragraph syntax--text">tarn_r</span></span></span></pre>
<p><a id="Add-to-correct-ncWMS2-path"></a></p>
<h2>Add to correct <em>ncWMS2</em> path</h2>
<p>According to the <em>ncWMS2</em> documentation:</p>
<blockquote>
<p>The palette files can be placed in a directory named .palettes within the main config directory (i.e. ~/.ncWMS2/.palettes/ by default) and will be picked up automatically after a server restart.</p>
</blockquote>
<p>Although they can be placed in other locations with <a href="https://reading-escience-centre.gitbooks.io/ncwms-user-guide/content/06-development.html#palettes">additional configuration.</a></p>
<pre class="editor-colors lang-bash"><span><span class="syntax--source syntax--shell"><span class="syntax--comment syntax--block"># Copy generated colormap files to ncWMS2 palette path</span></span></span>
<span class=""><span class="syntax--source syntax--shell"><span class="syntax--entity syntax--name syntax--function">cp</span> cmo*.pal /path/to/.ncWMS2/.palettes/</span></span></pre>

  </body>
</html>
