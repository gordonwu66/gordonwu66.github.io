<!DOCTYPE html>
<html>
<head><meta charset="utf-8" />

<title>Happiness Tutorial</title>

<script src="https://cdnjs.cloudflare.com/ajax/libs/require.js/2.1.10/require.min.js"></script>
<script src="https://cdnjs.cloudflare.com/ajax/libs/jquery/2.0.3/jquery.min.js"></script>



<style type="text/css">
    /*!
*
* Twitter Bootstrap
*
*/
/*!
 * Bootstrap v3.3.7 (http://getbootstrap.com)
 * Copyright 2011-2016 Twitter, Inc.
 * Licensed under MIT (https://github.com/twbs/bootstrap/blob/master/LICENSE)
 */
/*! normalize.css v3.0.3 | MIT License | github.com/necolas/normalize.css */
html {
  font-family: sans-serif;
  -ms-text-size-adjust: 100%;
  -webkit-text-size-adjust: 100%;
}
body {
  margin: 0;
}
article,
aside,
details,
figcaption,
figure,
footer,
header,
hgroup,
main,
menu,
nav,
section,
summary {
  display: block;
}
audio,
canvas,
progress,
video {
  display: inline-block;
  vertical-align: baseline;
}
audio:not([controls]) {
  display: none;
  height: 0;
}
[hidden],
template {
  display: none;
}
a {
  background-color: transparent;
}
a:active,
a:hover {
  outline: 0;
}
abbr[title] {
  border-bottom: 1px dotted;
}
b,
strong {
  font-weight: bold;
}
dfn {
  font-style: italic;
}
h1 {
  font-size: 2em;
  margin: 0.67em 0;
}
mark {
  background: #ff0;
  color: #000;
}
small {
  font-size: 80%;
}
sub,
sup {
  font-size: 75%;
  line-height: 0;
  position: relative;
  vertical-align: baseline;
}
sup {
  top: -0.5em;
}
sub {
  bottom: -0.25em;
}
img {
  border: 0;
}
svg:not(:root) {
  overflow: hidden;
}
figure {
  margin: 1em 40px;
}
hr {
  box-sizing: content-box;
  height: 0;
}
pre {
  overflow: auto;
}
code,
kbd,
pre,
samp {
  font-family: monospace, monospace;
  font-size: 1em;
}
button,
input,
optgroup,
select,
textarea {
  color: inherit;
  font: inherit;
  margin: 0;
}
button {
  overflow: visible;
}
button,
select {
  text-transform: none;
}
button,
html input[type="button"],
input[type="reset"],
input[type="submit"] {
  -webkit-appearance: button;
  cursor: pointer;
}
button[disabled],
html input[disabled] {
  cursor: default;
}
button::-moz-focus-inner,
input::-moz-focus-inner {
  border: 0;
  padding: 0;
}
input {
  line-height: normal;
}
input[type="checkbox"],
input[type="radio"] {
  box-sizing: border-box;
  padding: 0;
}
input[type="number"]::-webkit-inner-spin-button,
input[type="number"]::-webkit-outer-spin-button {
  height: auto;
}
input[type="search"] {
  -webkit-appearance: textfield;
  box-sizing: content-box;
}
input[type="search"]::-webkit-search-cancel-button,
input[type="search"]::-webkit-search-decoration {
  -webkit-appearance: none;
}
fieldset {
  border: 1px solid #c0c0c0;
  margin: 0 2px;
  padding: 0.35em 0.625em 0.75em;
}
legend {
  border: 0;
  padding: 0;
}
textarea {
  overflow: auto;
}
optgroup {
  font-weight: bold;
}
table {
  border-collapse: collapse;
  border-spacing: 0;
}
td,
th {
  padding: 0;
}
/*! Source: https://github.com/h5bp/html5-boilerplate/blob/master/src/css/main.css */
@media print {
  *,
  *:before,
  *:after {
    background: transparent !important;
    box-shadow: none !important;
    text-shadow: none !important;
  }
  a,
  a:visited {
    text-decoration: underline;
  }
  a[href]:after {
    content: " (" attr(href) ")";
  }
  abbr[title]:after {
    content: " (" attr(title) ")";
  }
  a[href^="#"]:after,
  a[href^="javascript:"]:after {
    content: "";
  }
  pre,
  blockquote {
    border: 1px solid #999;
    page-break-inside: avoid;
  }
  thead {
    display: table-header-group;
  }
  tr,
  img {
    page-break-inside: avoid;
  }
  img {
    max-width: 100% !important;
  }
  p,
  h2,
  h3 {
    orphans: 3;
    widows: 3;
  }
  h2,
  h3 {
    page-break-after: avoid;
  }
  .navbar {
    display: none;
  }
  .btn > .caret,
  .dropup > .btn > .caret {
    border-top-color: #000 !important;
  }
  .label {
    border: 1px solid #000;
  }
  .table {
    border-collapse: collapse !important;
  }
  .table td,
  .table th {
    background-color: #fff !important;
  }
  .table-bordered th,
  .table-bordered td {
    border: 1px solid #ddd !important;
  }
}
@font-face {
  font-family: 'Glyphicons Halflings';
  src: url('../components/bootstrap/fonts/glyphicons-halflings-regular.eot');
  src: url('../components/bootstrap/fonts/glyphicons-halflings-regular.eot?#iefix') format('embedded-opentype'), url('../components/bootstrap/fonts/glyphicons-halflings-regular.woff2') format('woff2'), url('../components/bootstrap/fonts/glyphicons-halflings-regular.woff') format('woff'), url('../components/bootstrap/fonts/glyphicons-halflings-regular.ttf') format('truetype'), url('../components/bootstrap/fonts/glyphicons-halflings-regular.svg#glyphicons_halflingsregular') format('svg');
}
.glyphicon {
  position: relative;
  top: 1px;
  display: inline-block;
  font-family: 'Glyphicons Halflings';
  font-style: normal;
  font-weight: normal;
  line-height: 1;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
}
.glyphicon-asterisk:before {
  content: "\002a";
}
.glyphicon-plus:before {
  content: "\002b";
}
.glyphicon-euro:before,
.glyphicon-eur:before {
  content: "\20ac";
}
.glyphicon-minus:before {
  content: "\2212";
}
.glyphicon-cloud:before {
  content: "\2601";
}
.glyphicon-envelope:before {
  content: "\2709";
}
.glyphicon-pencil:before {
  content: "\270f";
}
.glyphicon-glass:before {
  content: "\e001";
}
.glyphicon-music:before {
  content: "\e002";
}
.glyphicon-search:before {
  content: "\e003";
}
.glyphicon-heart:before {
  content: "\e005";
}
.glyphicon-star:before {
  content: "\e006";
}
.glyphicon-star-empty:before {
  content: "\e007";
}
.glyphicon-user:before {
  content: "\e008";
}
.glyphicon-film:before {
  content: "\e009";
}
.glyphicon-th-large:before {
  content: "\e010";
}
.glyphicon-th:before {
  content: "\e011";
}
.glyphicon-th-list:before {
  content: "\e012";
}
.glyphicon-ok:before {
  content: "\e013";
}
.glyphicon-remove:before {
  content: "\e014";
}
.glyphicon-zoom-in:before {
  content: "\e015";
}
.glyphicon-zoom-out:before {
  content: "\e016";
}
.glyphicon-off:before {
  content: "\e017";
}
.glyphicon-signal:before {
  content: "\e018";
}
.glyphicon-cog:before {
  content: "\e019";
}
.glyphicon-trash:before {
  content: "\e020";
}
.glyphicon-home:before {
  content: "\e021";
}
.glyphicon-file:before {
  content: "\e022";
}
.glyphicon-time:before {
  content: "\e023";
}
.glyphicon-road:before {
  content: "\e024";
}
.glyphicon-download-alt:before {
  content: "\e025";
}
.glyphicon-download:before {
  content: "\e026";
}
.glyphicon-upload:before {
  content: "\e027";
}
.glyphicon-inbox:before {
  content: "\e028";
}
.glyphicon-play-circle:before {
  content: "\e029";
}
.glyphicon-repeat:before {
  content: "\e030";
}
.glyphicon-refresh:before {
  content: "\e031";
}
.glyphicon-list-alt:before {
  content: "\e032";
}
.glyphicon-lock:before {
  content: "\e033";
}
.glyphicon-flag:before {
  content: "\e034";
}
.glyphicon-headphones:before {
  content: "\e035";
}
.glyphicon-volume-off:before {
  content: "\e036";
}
.glyphicon-volume-down:before {
  content: "\e037";
}
.glyphicon-volume-up:before {
  content: "\e038";
}
.glyphicon-qrcode:before {
  content: "\e039";
}
.glyphicon-barcode:before {
  content: "\e040";
}
.glyphicon-tag:before {
  content: "\e041";
}
.glyphicon-tags:before {
  content: "\e042";
}
.glyphicon-book:before {
  content: "\e043";
}
.glyphicon-bookmark:before {
  content: "\e044";
}
.glyphicon-print:before {
  content: "\e045";
}
.glyphicon-camera:before {
  content: "\e046";
}
.glyphicon-font:before {
  content: "\e047";
}
.glyphicon-bold:before {
  content: "\e048";
}
.glyphicon-italic:before {
  content: "\e049";
}
.glyphicon-text-height:before {
  content: "\e050";
}
.glyphicon-text-width:before {
  content: "\e051";
}
.glyphicon-align-left:before {
  content: "\e052";
}
.glyphicon-align-center:before {
  content: "\e053";
}
.glyphicon-align-right:before {
  content: "\e054";
}
.glyphicon-align-justify:before {
  content: "\e055";
}
.glyphicon-list:before {
  content: "\e056";
}
.glyphicon-indent-left:before {
  content: "\e057";
}
.glyphicon-indent-right:before {
  content: "\e058";
}
.glyphicon-facetime-video:before {
  content: "\e059";
}
.glyphicon-picture:before {
  content: "\e060";
}
.glyphicon-map-marker:before {
  content: "\e062";
}
.glyphicon-adjust:before {
  content: "\e063";
}
.glyphicon-tint:before {
  content: "\e064";
}
.glyphicon-edit:before {
  content: "\e065";
}
.glyphicon-share:before {
  content: "\e066";
}
.glyphicon-check:before {
  content: "\e067";
}
.glyphicon-move:before {
  content: "\e068";
}
.glyphicon-step-backward:before {
  content: "\e069";
}
.glyphicon-fast-backward:before {
  content: "\e070";
}
.glyphicon-backward:before {
  content: "\e071";
}
.glyphicon-play:before {
  content: "\e072";
}
.glyphicon-pause:before {
  content: "\e073";
}
.glyphicon-stop:before {
  content: "\e074";
}
.glyphicon-forward:before {
  content: "\e075";
}
.glyphicon-fast-forward:before {
  content: "\e076";
}
.glyphicon-step-forward:before {
  content: "\e077";
}
.glyphicon-eject:before {
  content: "\e078";
}
.glyphicon-chevron-left:before {
  content: "\e079";
}
.glyphicon-chevron-right:before {
  content: "\e080";
}
.glyphicon-plus-sign:before {
  content: "\e081";
}
.glyphicon-minus-sign:before {
  content: "\e082";
}
.glyphicon-remove-sign:before {
  content: "\e083";
}
.glyphicon-ok-sign:before {
  content: "\e084";
}
.glyphicon-question-sign:before {
  content: "\e085";
}
.glyphicon-info-sign:before {
  content: "\e086";
}
.glyphicon-screenshot:before {
  content: "\e087";
}
.glyphicon-remove-circle:before {
  content: "\e088";
}
.glyphicon-ok-circle:before {
  content: "\e089";
}
.glyphicon-ban-circle:before {
  content: "\e090";
}
.glyphicon-arrow-left:before {
  content: "\e091";
}
.glyphicon-arrow-right:before {
  content: "\e092";
}
.glyphicon-arrow-up:before {
  content: "\e093";
}
.glyphicon-arrow-down:before {
  content: "\e094";
}
.glyphicon-share-alt:before {
  content: "\e095";
}
.glyphicon-resize-full:before {
  content: "\e096";
}
.glyphicon-resize-small:before {
  content: "\e097";
}
.glyphicon-exclamation-sign:before {
  content: "\e101";
}
.glyphicon-gift:before {
  content: "\e102";
}
.glyphicon-leaf:before {
  content: "\e103";
}
.glyphicon-fire:before {
  content: "\e104";
}
.glyphicon-eye-open:before {
  content: "\e105";
}
.glyphicon-eye-close:before {
  content: "\e106";
}
.glyphicon-warning-sign:before {
  content: "\e107";
}
.glyphicon-plane:before {
  content: "\e108";
}
.glyphicon-calendar:before {
  content: "\e109";
}
.glyphicon-random:before {
  content: "\e110";
}
.glyphicon-comment:before {
  content: "\e111";
}
.glyphicon-magnet:before {
  content: "\e112";
}
.glyphicon-chevron-up:before {
  content: "\e113";
}
.glyphicon-chevron-down:before {
  content: "\e114";
}
.glyphicon-retweet:before {
  content: "\e115";
}
.glyphicon-shopping-cart:before {
  content: "\e116";
}
.glyphicon-folder-close:before {
  content: "\e117";
}
.glyphicon-folder-open:before {
  content: "\e118";
}
.glyphicon-resize-vertical:before {
  content: "\e119";
}
.glyphicon-resize-horizontal:before {
  content: "\e120";
}
.glyphicon-hdd:before {
  content: "\e121";
}
.glyphicon-bullhorn:before {
  content: "\e122";
}
.glyphicon-bell:before {
  content: "\e123";
}
.glyphicon-certificate:before {
  content: "\e124";
}
.glyphicon-thumbs-up:before {
  content: "\e125";
}
.glyphicon-thumbs-down:before {
  content: "\e126";
}
.glyphicon-hand-right:before {
  content: "\e127";
}
.glyphicon-hand-left:before {
  content: "\e128";
}
.glyphicon-hand-up:before {
  content: "\e129";
}
.glyphicon-hand-down:before {
  content: "\e130";
}
.glyphicon-circle-arrow-right:before {
  content: "\e131";
}
.glyphicon-circle-arrow-left:before {
  content: "\e132";
}
.glyphicon-circle-arrow-up:before {
  content: "\e133";
}
.glyphicon-circle-arrow-down:before {
  content: "\e134";
}
.glyphicon-globe:before {
  content: "\e135";
}
.glyphicon-wrench:before {
  content: "\e136";
}
.glyphicon-tasks:before {
  content: "\e137";
}
.glyphicon-filter:before {
  content: "\e138";
}
.glyphicon-briefcase:before {
  content: "\e139";
}
.glyphicon-fullscreen:before {
  content: "\e140";
}
.glyphicon-dashboard:before {
  content: "\e141";
}
.glyphicon-paperclip:before {
  content: "\e142";
}
.glyphicon-heart-empty:before {
  content: "\e143";
}
.glyphicon-link:before {
  content: "\e144";
}
.glyphicon-phone:before {
  content: "\e145";
}
.glyphicon-pushpin:before {
  content: "\e146";
}
.glyphicon-usd:before {
  content: "\e148";
}
.glyphicon-gbp:before {
  content: "\e149";
}
.glyphicon-sort:before {
  content: "\e150";
}
.glyphicon-sort-by-alphabet:before {
  content: "\e151";
}
.glyphicon-sort-by-alphabet-alt:before {
  content: "\e152";
}
.glyphicon-sort-by-order:before {
  content: "\e153";
}
.glyphicon-sort-by-order-alt:before {
  content: "\e154";
}
.glyphicon-sort-by-attributes:before {
  content: "\e155";
}
.glyphicon-sort-by-attributes-alt:before {
  content: "\e156";
}
.glyphicon-unchecked:before {
  content: "\e157";
}
.glyphicon-expand:before {
  content: "\e158";
}
.glyphicon-collapse-down:before {
  content: "\e159";
}
.glyphicon-collapse-up:before {
  content: "\e160";
}
.glyphicon-log-in:before {
  content: "\e161";
}
.glyphicon-flash:before {
  content: "\e162";
}
.glyphicon-log-out:before {
  content: "\e163";
}
.glyphicon-new-window:before {
  content: "\e164";
}
.glyphicon-record:before {
  content: "\e165";
}
.glyphicon-save:before {
  content: "\e166";
}
.glyphicon-open:before {
  content: "\e167";
}
.glyphicon-saved:before {
  content: "\e168";
}
.glyphicon-import:before {
  content: "\e169";
}
.glyphicon-export:before {
  content: "\e170";
}
.glyphicon-send:before {
  content: "\e171";
}
.glyphicon-floppy-disk:before {
  content: "\e172";
}
.glyphicon-floppy-saved:before {
  content: "\e173";
}
.glyphicon-floppy-remove:before {
  content: "\e174";
}
.glyphicon-floppy-save:before {
  content: "\e175";
}
.glyphicon-floppy-open:before {
  content: "\e176";
}
.glyphicon-credit-card:before {
  content: "\e177";
}
.glyphicon-transfer:before {
  content: "\e178";
}
.glyphicon-cutlery:before {
  content: "\e179";
}
.glyphicon-header:before {
  content: "\e180";
}
.glyphicon-compressed:before {
  content: "\e181";
}
.glyphicon-earphone:before {
  content: "\e182";
}
.glyphicon-phone-alt:before {
  content: "\e183";
}
.glyphicon-tower:before {
  content: "\e184";
}
.glyphicon-stats:before {
  content: "\e185";
}
.glyphicon-sd-video:before {
  content: "\e186";
}
.glyphicon-hd-video:before {
  content: "\e187";
}
.glyphicon-subtitles:before {
  content: "\e188";
}
.glyphicon-sound-stereo:before {
  content: "\e189";
}
.glyphicon-sound-dolby:before {
  content: "\e190";
}
.glyphicon-sound-5-1:before {
  content: "\e191";
}
.glyphicon-sound-6-1:before {
  content: "\e192";
}
.glyphicon-sound-7-1:before {
  content: "\e193";
}
.glyphicon-copyright-mark:before {
  content: "\e194";
}
.glyphicon-registration-mark:before {
  content: "\e195";
}
.glyphicon-cloud-download:before {
  content: "\e197";
}
.glyphicon-cloud-upload:before {
  content: "\e198";
}
.glyphicon-tree-conifer:before {
  content: "\e199";
}
.glyphicon-tree-deciduous:before {
  content: "\e200";
}
.glyphicon-cd:before {
  content: "\e201";
}
.glyphicon-save-file:before {
  content: "\e202";
}
.glyphicon-open-file:before {
  content: "\e203";
}
.glyphicon-level-up:before {
  content: "\e204";
}
.glyphicon-copy:before {
  content: "\e205";
}
.glyphicon-paste:before {
  content: "\e206";
}
.glyphicon-alert:before {
  content: "\e209";
}
.glyphicon-equalizer:before {
  content: "\e210";
}
.glyphicon-king:before {
  content: "\e211";
}
.glyphicon-queen:before {
  content: "\e212";
}
.glyphicon-pawn:before {
  content: "\e213";
}
.glyphicon-bishop:before {
  content: "\e214";
}
.glyphicon-knight:before {
  content: "\e215";
}
.glyphicon-baby-formula:before {
  content: "\e216";
}
.glyphicon-tent:before {
  content: "\26fa";
}
.glyphicon-blackboard:before {
  content: "\e218";
}
.glyphicon-bed:before {
  content: "\e219";
}
.glyphicon-apple:before {
  content: "\f8ff";
}
.glyphicon-erase:before {
  content: "\e221";
}
.glyphicon-hourglass:before {
  content: "\231b";
}
.glyphicon-lamp:before {
  content: "\e223";
}
.glyphicon-duplicate:before {
  content: "\e224";
}
.glyphicon-piggy-bank:before {
  content: "\e225";
}
.glyphicon-scissors:before {
  content: "\e226";
}
.glyphicon-bitcoin:before {
  content: "\e227";
}
.glyphicon-btc:before {
  content: "\e227";
}
.glyphicon-xbt:before {
  content: "\e227";
}
.glyphicon-yen:before {
  content: "\00a5";
}
.glyphicon-jpy:before {
  content: "\00a5";
}
.glyphicon-ruble:before {
  content: "\20bd";
}
.glyphicon-rub:before {
  content: "\20bd";
}
.glyphicon-scale:before {
  content: "\e230";
}
.glyphicon-ice-lolly:before {
  content: "\e231";
}
.glyphicon-ice-lolly-tasted:before {
  content: "\e232";
}
.glyphicon-education:before {
  content: "\e233";
}
.glyphicon-option-horizontal:before {
  content: "\e234";
}
.glyphicon-option-vertical:before {
  content: "\e235";
}
.glyphicon-menu-hamburger:before {
  content: "\e236";
}
.glyphicon-modal-window:before {
  content: "\e237";
}
.glyphicon-oil:before {
  content: "\e238";
}
.glyphicon-grain:before {
  content: "\e239";
}
.glyphicon-sunglasses:before {
  content: "\e240";
}
.glyphicon-text-size:before {
  content: "\e241";
}
.glyphicon-text-color:before {
  content: "\e242";
}
.glyphicon-text-background:before {
  content: "\e243";
}
.glyphicon-object-align-top:before {
  content: "\e244";
}
.glyphicon-object-align-bottom:before {
  content: "\e245";
}
.glyphicon-object-align-horizontal:before {
  content: "\e246";
}
.glyphicon-object-align-left:before {
  content: "\e247";
}
.glyphicon-object-align-vertical:before {
  content: "\e248";
}
.glyphicon-object-align-right:before {
  content: "\e249";
}
.glyphicon-triangle-right:before {
  content: "\e250";
}
.glyphicon-triangle-left:before {
  content: "\e251";
}
.glyphicon-triangle-bottom:before {
  content: "\e252";
}
.glyphicon-triangle-top:before {
  content: "\e253";
}
.glyphicon-console:before {
  content: "\e254";
}
.glyphicon-superscript:before {
  content: "\e255";
}
.glyphicon-subscript:before {
  content: "\e256";
}
.glyphicon-menu-left:before {
  content: "\e257";
}
.glyphicon-menu-right:before {
  content: "\e258";
}
.glyphicon-menu-down:before {
  content: "\e259";
}
.glyphicon-menu-up:before {
  content: "\e260";
}
* {
  -webkit-box-sizing: border-box;
  -moz-box-sizing: border-box;
  box-sizing: border-box;
}
*:before,
*:after {
  -webkit-box-sizing: border-box;
  -moz-box-sizing: border-box;
  box-sizing: border-box;
}
html {
  font-size: 10px;
  -webkit-tap-highlight-color: rgba(0, 0, 0, 0);
}
body {
  font-family: "Helvetica Neue", Helvetica, Arial, sans-serif;
  font-size: 13px;
  line-height: 1.42857143;
  color: #000;
  background-color: #fff;
}
input,
button,
select,
textarea {
  font-family: inherit;
  font-size: inherit;
  line-height: inherit;
}
a {
  color: #337ab7;
  text-decoration: none;
}
a:hover,
a:focus {
  color: #23527c;
  text-decoration: underline;
}
a:focus {
  outline: 5px auto -webkit-focus-ring-color;
  outline-offset: -2px;
}
figure {
  margin: 0;
}
img {
  vertical-align: middle;
}
.img-responsive,
.thumbnail > img,
.thumbnail a > img,
.carousel-inner > .item > img,
.carousel-inner > .item > a > img {
  display: block;
  max-width: 100%;
  height: auto;
}
.img-rounded {
  border-radius: 3px;
}
.img-thumbnail {
  padding: 4px;
  line-height: 1.42857143;
  background-color: #fff;
  border: 1px solid #ddd;
  border-radius: 2px;
  -webkit-transition: all 0.2s ease-in-out;
  -o-transition: all 0.2s ease-in-out;
  transition: all 0.2s ease-in-out;
  display: inline-block;
  max-width: 100%;
  height: auto;
}
.img-circle {
  border-radius: 50%;
}
hr {
  margin-top: 18px;
  margin-bottom: 18px;
  border: 0;
  border-top: 1px solid #eeeeee;
}
.sr-only {
  position: absolute;
  width: 1px;
  height: 1px;
  margin: -1px;
  padding: 0;
  overflow: hidden;
  clip: rect(0, 0, 0, 0);
  border: 0;
}
.sr-only-focusable:active,
.sr-only-focusable:focus {
  position: static;
  width: auto;
  height: auto;
  margin: 0;
  overflow: visible;
  clip: auto;
}
[role="button"] {
  cursor: pointer;
}
h1,
h2,
h3,
h4,
h5,
h6,
.h1,
.h2,
.h3,
.h4,
.h5,
.h6 {
  font-family: inherit;
  font-weight: 500;
  line-height: 1.1;
  color: inherit;
}
h1 small,
h2 small,
h3 small,
h4 small,
h5 small,
h6 small,
.h1 small,
.h2 small,
.h3 small,
.h4 small,
.h5 small,
.h6 small,
h1 .small,
h2 .small,
h3 .small,
h4 .small,
h5 .small,
h6 .small,
.h1 .small,
.h2 .small,
.h3 .small,
.h4 .small,
.h5 .small,
.h6 .small {
  font-weight: normal;
  line-height: 1;
  color: #777777;
}
h1,
.h1,
h2,
.h2,
h3,
.h3 {
  margin-top: 18px;
  margin-bottom: 9px;
}
h1 small,
.h1 small,
h2 small,
.h2 small,
h3 small,
.h3 small,
h1 .small,
.h1 .small,
h2 .small,
.h2 .small,
h3 .small,
.h3 .small {
  font-size: 65%;
}
h4,
.h4,
h5,
.h5,
h6,
.h6 {
  margin-top: 9px;
  margin-bottom: 9px;
}
h4 small,
.h4 small,
h5 small,
.h5 small,
h6 small,
.h6 small,
h4 .small,
.h4 .small,
h5 .small,
.h5 .small,
h6 .small,
.h6 .small {
  font-size: 75%;
}
h1,
.h1 {
  font-size: 33px;
}
h2,
.h2 {
  font-size: 27px;
}
h3,
.h3 {
  font-size: 23px;
}
h4,
.h4 {
  font-size: 17px;
}
h5,
.h5 {
  font-size: 13px;
}
h6,
.h6 {
  font-size: 12px;
}
p {
  margin: 0 0 9px;
}
.lead {
  margin-bottom: 18px;
  font-size: 14px;
  font-weight: 300;
  line-height: 1.4;
}
@media (min-width: 768px) {
  .lead {
    font-size: 19.5px;
  }
}
small,
.small {
  font-size: 92%;
}
mark,
.mark {
  background-color: #fcf8e3;
  padding: .2em;
}
.text-left {
  text-align: left;
}
.text-right {
  text-align: right;
}
.text-center {
  text-align: center;
}
.text-justify {
  text-align: justify;
}
.text-nowrap {
  white-space: nowrap;
}
.text-lowercase {
  text-transform: lowercase;
}
.text-uppercase {
  text-transform: uppercase;
}
.text-capitalize {
  text-transform: capitalize;
}
.text-muted {
  color: #777777;
}
.text-primary {
  color: #337ab7;
}
a.text-primary:hover,
a.text-primary:focus {
  color: #286090;
}
.text-success {
  color: #3c763d;
}
a.text-success:hover,
a.text-success:focus {
  color: #2b542c;
}
.text-info {
  color: #31708f;
}
a.text-info:hover,
a.text-info:focus {
  color: #245269;
}
.text-warning {
  color: #8a6d3b;
}
a.text-warning:hover,
a.text-warning:focus {
  color: #66512c;
}
.text-danger {
  color: #a94442;
}
a.text-danger:hover,
a.text-danger:focus {
  color: #843534;
}
.bg-primary {
  color: #fff;
  background-color: #337ab7;
}
a.bg-primary:hover,
a.bg-primary:focus {
  background-color: #286090;
}
.bg-success {
  background-color: #dff0d8;
}
a.bg-success:hover,
a.bg-success:focus {
  background-color: #c1e2b3;
}
.bg-info {
  background-color: #d9edf7;
}
a.bg-info:hover,
a.bg-info:focus {
  background-color: #afd9ee;
}
.bg-warning {
  background-color: #fcf8e3;
}
a.bg-warning:hover,
a.bg-warning:focus {
  background-color: #f7ecb5;
}
.bg-danger {
  background-color: #f2dede;
}
a.bg-danger:hover,
a.bg-danger:focus {
  background-color: #e4b9b9;
}
.page-header {
  padding-bottom: 8px;
  margin: 36px 0 18px;
  border-bottom: 1px solid #eeeeee;
}
ul,
ol {
  margin-top: 0;
  margin-bottom: 9px;
}
ul ul,
ol ul,
ul ol,
ol ol {
  margin-bottom: 0;
}
.list-unstyled {
  padding-left: 0;
  list-style: none;
}
.list-inline {
  padding-left: 0;
  list-style: none;
  margin-left: -5px;
}
.list-inline > li {
  display: inline-block;
  padding-left: 5px;
  padding-right: 5px;
}
dl {
  margin-top: 0;
  margin-bottom: 18px;
}
dt,
dd {
  line-height: 1.42857143;
}
dt {
  font-weight: bold;
}
dd {
  margin-left: 0;
}
@media (min-width: 541px) {
  .dl-horizontal dt {
    float: left;
    width: 160px;
    clear: left;
    text-align: right;
    overflow: hidden;
    text-overflow: ellipsis;
    white-space: nowrap;
  }
  .dl-horizontal dd {
    margin-left: 180px;
  }
}
abbr[title],
abbr[data-original-title] {
  cursor: help;
  border-bottom: 1px dotted #777777;
}
.initialism {
  font-size: 90%;
  text-transform: uppercase;
}
blockquote {
  padding: 9px 18px;
  margin: 0 0 18px;
  font-size: inherit;
  border-left: 5px solid #eeeeee;
}
blockquote p:last-child,
blockquote ul:last-child,
blockquote ol:last-child {
  margin-bottom: 0;
}
blockquote footer,
blockquote small,
blockquote .small {
  display: block;
  font-size: 80%;
  line-height: 1.42857143;
  color: #777777;
}
blockquote footer:before,
blockquote small:before,
blockquote .small:before {
  content: '\2014 \00A0';
}
.blockquote-reverse,
blockquote.pull-right {
  padding-right: 15px;
  padding-left: 0;
  border-right: 5px solid #eeeeee;
  border-left: 0;
  text-align: right;
}
.blockquote-reverse footer:before,
blockquote.pull-right footer:before,
.blockquote-reverse small:before,
blockquote.pull-right small:before,
.blockquote-reverse .small:before,
blockquote.pull-right .small:before {
  content: '';
}
.blockquote-reverse footer:after,
blockquote.pull-right footer:after,
.blockquote-reverse small:after,
blockquote.pull-right small:after,
.blockquote-reverse .small:after,
blockquote.pull-right .small:after {
  content: '\00A0 \2014';
}
address {
  margin-bottom: 18px;
  font-style: normal;
  line-height: 1.42857143;
}
code,
kbd,
pre,
samp {
  font-family: monospace;
}
code {
  padding: 2px 4px;
  font-size: 90%;
  color: #c7254e;
  background-color: #f9f2f4;
  border-radius: 2px;
}
kbd {
  padding: 2px 4px;
  font-size: 90%;
  color: #888;
  background-color: transparent;
  border-radius: 1px;
  box-shadow: inset 0 -1px 0 rgba(0, 0, 0, 0.25);
}
kbd kbd {
  padding: 0;
  font-size: 100%;
  font-weight: bold;
  box-shadow: none;
}
pre {
  display: block;
  padding: 8.5px;
  margin: 0 0 9px;
  font-size: 12px;
  line-height: 1.42857143;
  word-break: break-all;
  word-wrap: break-word;
  color: #333333;
  background-color: #f5f5f5;
  border: 1px solid #ccc;
  border-radius: 2px;
}
pre code {
  padding: 0;
  font-size: inherit;
  color: inherit;
  white-space: pre-wrap;
  background-color: transparent;
  border-radius: 0;
}
.pre-scrollable {
  max-height: 340px;
  overflow-y: scroll;
}
.container {
  margin-right: auto;
  margin-left: auto;
  padding-left: 0px;
  padding-right: 0px;
}
@media (min-width: 768px) {
  .container {
    width: 768px;
  }
}
@media (min-width: 992px) {
  .container {
    width: 940px;
  }
}
@media (min-width: 1200px) {
  .container {
    width: 1140px;
  }
}
.container-fluid {
  margin-right: auto;
  margin-left: auto;
  padding-left: 0px;
  padding-right: 0px;
}
.row {
  margin-left: 0px;
  margin-right: 0px;
}
.col-xs-1, .col-sm-1, .col-md-1, .col-lg-1, .col-xs-2, .col-sm-2, .col-md-2, .col-lg-2, .col-xs-3, .col-sm-3, .col-md-3, .col-lg-3, .col-xs-4, .col-sm-4, .col-md-4, .col-lg-4, .col-xs-5, .col-sm-5, .col-md-5, .col-lg-5, .col-xs-6, .col-sm-6, .col-md-6, .col-lg-6, .col-xs-7, .col-sm-7, .col-md-7, .col-lg-7, .col-xs-8, .col-sm-8, .col-md-8, .col-lg-8, .col-xs-9, .col-sm-9, .col-md-9, .col-lg-9, .col-xs-10, .col-sm-10, .col-md-10, .col-lg-10, .col-xs-11, .col-sm-11, .col-md-11, .col-lg-11, .col-xs-12, .col-sm-12, .col-md-12, .col-lg-12 {
  position: relative;
  min-height: 1px;
  padding-left: 0px;
  padding-right: 0px;
}
.col-xs-1, .col-xs-2, .col-xs-3, .col-xs-4, .col-xs-5, .col-xs-6, .col-xs-7, .col-xs-8, .col-xs-9, .col-xs-10, .col-xs-11, .col-xs-12 {
  float: left;
}
.col-xs-12 {
  width: 100%;
}
.col-xs-11 {
  width: 91.66666667%;
}
.col-xs-10 {
  width: 83.33333333%;
}
.col-xs-9 {
  width: 75%;
}
.col-xs-8 {
  width: 66.66666667%;
}
.col-xs-7 {
  width: 58.33333333%;
}
.col-xs-6 {
  width: 50%;
}
.col-xs-5 {
  width: 41.66666667%;
}
.col-xs-4 {
  width: 33.33333333%;
}
.col-xs-3 {
  width: 25%;
}
.col-xs-2 {
  width: 16.66666667%;
}
.col-xs-1 {
  width: 8.33333333%;
}
.col-xs-pull-12 {
  right: 100%;
}
.col-xs-pull-11 {
  right: 91.66666667%;
}
.col-xs-pull-10 {
  right: 83.33333333%;
}
.col-xs-pull-9 {
  right: 75%;
}
.col-xs-pull-8 {
  right: 66.66666667%;
}
.col-xs-pull-7 {
  right: 58.33333333%;
}
.col-xs-pull-6 {
  right: 50%;
}
.col-xs-pull-5 {
  right: 41.66666667%;
}
.col-xs-pull-4 {
  right: 33.33333333%;
}
.col-xs-pull-3 {
  right: 25%;
}
.col-xs-pull-2 {
  right: 16.66666667%;
}
.col-xs-pull-1 {
  right: 8.33333333%;
}
.col-xs-pull-0 {
  right: auto;
}
.col-xs-push-12 {
  left: 100%;
}
.col-xs-push-11 {
  left: 91.66666667%;
}
.col-xs-push-10 {
  left: 83.33333333%;
}
.col-xs-push-9 {
  left: 75%;
}
.col-xs-push-8 {
  left: 66.66666667%;
}
.col-xs-push-7 {
  left: 58.33333333%;
}
.col-xs-push-6 {
  left: 50%;
}
.col-xs-push-5 {
  left: 41.66666667%;
}
.col-xs-push-4 {
  left: 33.33333333%;
}
.col-xs-push-3 {
  left: 25%;
}
.col-xs-push-2 {
  left: 16.66666667%;
}
.col-xs-push-1 {
  left: 8.33333333%;
}
.col-xs-push-0 {
  left: auto;
}
.col-xs-offset-12 {
  margin-left: 100%;
}
.col-xs-offset-11 {
  margin-left: 91.66666667%;
}
.col-xs-offset-10 {
  margin-left: 83.33333333%;
}
.col-xs-offset-9 {
  margin-left: 75%;
}
.col-xs-offset-8 {
  margin-left: 66.66666667%;
}
.col-xs-offset-7 {
  margin-left: 58.33333333%;
}
.col-xs-offset-6 {
  margin-left: 50%;
}
.col-xs-offset-5 {
  margin-left: 41.66666667%;
}
.col-xs-offset-4 {
  margin-left: 33.33333333%;
}
.col-xs-offset-3 {
  margin-left: 25%;
}
.col-xs-offset-2 {
  margin-left: 16.66666667%;
}
.col-xs-offset-1 {
  margin-left: 8.33333333%;
}
.col-xs-offset-0 {
  margin-left: 0%;
}
@media (min-width: 768px) {
  .col-sm-1, .col-sm-2, .col-sm-3, .col-sm-4, .col-sm-5, .col-sm-6, .col-sm-7, .col-sm-8, .col-sm-9, .col-sm-10, .col-sm-11, .col-sm-12 {
    float: left;
  }
  .col-sm-12 {
    width: 100%;
  }
  .col-sm-11 {
    width: 91.66666667%;
  }
  .col-sm-10 {
    width: 83.33333333%;
  }
  .col-sm-9 {
    width: 75%;
  }
  .col-sm-8 {
    width: 66.66666667%;
  }
  .col-sm-7 {
    width: 58.33333333%;
  }
  .col-sm-6 {
    width: 50%;
  }
  .col-sm-5 {
    width: 41.66666667%;
  }
  .col-sm-4 {
    width: 33.33333333%;
  }
  .col-sm-3 {
    width: 25%;
  }
  .col-sm-2 {
    width: 16.66666667%;
  }
  .col-sm-1 {
    width: 8.33333333%;
  }
  .col-sm-pull-12 {
    right: 100%;
  }
  .col-sm-pull-11 {
    right: 91.66666667%;
  }
  .col-sm-pull-10 {
    right: 83.33333333%;
  }
  .col-sm-pull-9 {
    right: 75%;
  }
  .col-sm-pull-8 {
    right: 66.66666667%;
  }
  .col-sm-pull-7 {
    right: 58.33333333%;
  }
  .col-sm-pull-6 {
    right: 50%;
  }
  .col-sm-pull-5 {
    right: 41.66666667%;
  }
  .col-sm-pull-4 {
    right: 33.33333333%;
  }
  .col-sm-pull-3 {
    right: 25%;
  }
  .col-sm-pull-2 {
    right: 16.66666667%;
  }
  .col-sm-pull-1 {
    right: 8.33333333%;
  }
  .col-sm-pull-0 {
    right: auto;
  }
  .col-sm-push-12 {
    left: 100%;
  }
  .col-sm-push-11 {
    left: 91.66666667%;
  }
  .col-sm-push-10 {
    left: 83.33333333%;
  }
  .col-sm-push-9 {
    left: 75%;
  }
  .col-sm-push-8 {
    left: 66.66666667%;
  }
  .col-sm-push-7 {
    left: 58.33333333%;
  }
  .col-sm-push-6 {
    left: 50%;
  }
  .col-sm-push-5 {
    left: 41.66666667%;
  }
  .col-sm-push-4 {
    left: 33.33333333%;
  }
  .col-sm-push-3 {
    left: 25%;
  }
  .col-sm-push-2 {
    left: 16.66666667%;
  }
  .col-sm-push-1 {
    left: 8.33333333%;
  }
  .col-sm-push-0 {
    left: auto;
  }
  .col-sm-offset-12 {
    margin-left: 100%;
  }
  .col-sm-offset-11 {
    margin-left: 91.66666667%;
  }
  .col-sm-offset-10 {
    margin-left: 83.33333333%;
  }
  .col-sm-offset-9 {
    margin-left: 75%;
  }
  .col-sm-offset-8 {
    margin-left: 66.66666667%;
  }
  .col-sm-offset-7 {
    margin-left: 58.33333333%;
  }
  .col-sm-offset-6 {
    margin-left: 50%;
  }
  .col-sm-offset-5 {
    margin-left: 41.66666667%;
  }
  .col-sm-offset-4 {
    margin-left: 33.33333333%;
  }
  .col-sm-offset-3 {
    margin-left: 25%;
  }
  .col-sm-offset-2 {
    margin-left: 16.66666667%;
  }
  .col-sm-offset-1 {
    margin-left: 8.33333333%;
  }
  .col-sm-offset-0 {
    margin-left: 0%;
  }
}
@media (min-width: 992px) {
  .col-md-1, .col-md-2, .col-md-3, .col-md-4, .col-md-5, .col-md-6, .col-md-7, .col-md-8, .col-md-9, .col-md-10, .col-md-11, .col-md-12 {
    float: left;
  }
  .col-md-12 {
    width: 100%;
  }
  .col-md-11 {
    width: 91.66666667%;
  }
  .col-md-10 {
    width: 83.33333333%;
  }
  .col-md-9 {
    width: 75%;
  }
  .col-md-8 {
    width: 66.66666667%;
  }
  .col-md-7 {
    width: 58.33333333%;
  }
  .col-md-6 {
    width: 50%;
  }
  .col-md-5 {
    width: 41.66666667%;
  }
  .col-md-4 {
    width: 33.33333333%;
  }
  .col-md-3 {
    width: 25%;
  }
  .col-md-2 {
    width: 16.66666667%;
  }
  .col-md-1 {
    width: 8.33333333%;
  }
  .col-md-pull-12 {
    right: 100%;
  }
  .col-md-pull-11 {
    right: 91.66666667%;
  }
  .col-md-pull-10 {
    right: 83.33333333%;
  }
  .col-md-pull-9 {
    right: 75%;
  }
  .col-md-pull-8 {
    right: 66.66666667%;
  }
  .col-md-pull-7 {
    right: 58.33333333%;
  }
  .col-md-pull-6 {
    right: 50%;
  }
  .col-md-pull-5 {
    right: 41.66666667%;
  }
  .col-md-pull-4 {
    right: 33.33333333%;
  }
  .col-md-pull-3 {
    right: 25%;
  }
  .col-md-pull-2 {
    right: 16.66666667%;
  }
  .col-md-pull-1 {
    right: 8.33333333%;
  }
  .col-md-pull-0 {
    right: auto;
  }
  .col-md-push-12 {
    left: 100%;
  }
  .col-md-push-11 {
    left: 91.66666667%;
  }
  .col-md-push-10 {
    left: 83.33333333%;
  }
  .col-md-push-9 {
    left: 75%;
  }
  .col-md-push-8 {
    left: 66.66666667%;
  }
  .col-md-push-7 {
    left: 58.33333333%;
  }
  .col-md-push-6 {
    left: 50%;
  }
  .col-md-push-5 {
    left: 41.66666667%;
  }
  .col-md-push-4 {
    left: 33.33333333%;
  }
  .col-md-push-3 {
    left: 25%;
  }
  .col-md-push-2 {
    left: 16.66666667%;
  }
  .col-md-push-1 {
    left: 8.33333333%;
  }
  .col-md-push-0 {
    left: auto;
  }
  .col-md-offset-12 {
    margin-left: 100%;
  }
  .col-md-offset-11 {
    margin-left: 91.66666667%;
  }
  .col-md-offset-10 {
    margin-left: 83.33333333%;
  }
  .col-md-offset-9 {
    margin-left: 75%;
  }
  .col-md-offset-8 {
    margin-left: 66.66666667%;
  }
  .col-md-offset-7 {
    margin-left: 58.33333333%;
  }
  .col-md-offset-6 {
    margin-left: 50%;
  }
  .col-md-offset-5 {
    margin-left: 41.66666667%;
  }
  .col-md-offset-4 {
    margin-left: 33.33333333%;
  }
  .col-md-offset-3 {
    margin-left: 25%;
  }
  .col-md-offset-2 {
    margin-left: 16.66666667%;
  }
  .col-md-offset-1 {
    margin-left: 8.33333333%;
  }
  .col-md-offset-0 {
    margin-left: 0%;
  }
}
@media (min-width: 1200px) {
  .col-lg-1, .col-lg-2, .col-lg-3, .col-lg-4, .col-lg-5, .col-lg-6, .col-lg-7, .col-lg-8, .col-lg-9, .col-lg-10, .col-lg-11, .col-lg-12 {
    float: left;
  }
  .col-lg-12 {
    width: 100%;
  }
  .col-lg-11 {
    width: 91.66666667%;
  }
  .col-lg-10 {
    width: 83.33333333%;
  }
  .col-lg-9 {
    width: 75%;
  }
  .col-lg-8 {
    width: 66.66666667%;
  }
  .col-lg-7 {
    width: 58.33333333%;
  }
  .col-lg-6 {
    width: 50%;
  }
  .col-lg-5 {
    width: 41.66666667%;
  }
  .col-lg-4 {
    width: 33.33333333%;
  }
  .col-lg-3 {
    width: 25%;
  }
  .col-lg-2 {
    width: 16.66666667%;
  }
  .col-lg-1 {
    width: 8.33333333%;
  }
  .col-lg-pull-12 {
    right: 100%;
  }
  .col-lg-pull-11 {
    right: 91.66666667%;
  }
  .col-lg-pull-10 {
    right: 83.33333333%;
  }
  .col-lg-pull-9 {
    right: 75%;
  }
  .col-lg-pull-8 {
    right: 66.66666667%;
  }
  .col-lg-pull-7 {
    right: 58.33333333%;
  }
  .col-lg-pull-6 {
    right: 50%;
  }
  .col-lg-pull-5 {
    right: 41.66666667%;
  }
  .col-lg-pull-4 {
    right: 33.33333333%;
  }
  .col-lg-pull-3 {
    right: 25%;
  }
  .col-lg-pull-2 {
    right: 16.66666667%;
  }
  .col-lg-pull-1 {
    right: 8.33333333%;
  }
  .col-lg-pull-0 {
    right: auto;
  }
  .col-lg-push-12 {
    left: 100%;
  }
  .col-lg-push-11 {
    left: 91.66666667%;
  }
  .col-lg-push-10 {
    left: 83.33333333%;
  }
  .col-lg-push-9 {
    left: 75%;
  }
  .col-lg-push-8 {
    left: 66.66666667%;
  }
  .col-lg-push-7 {
    left: 58.33333333%;
  }
  .col-lg-push-6 {
    left: 50%;
  }
  .col-lg-push-5 {
    left: 41.66666667%;
  }
  .col-lg-push-4 {
    left: 33.33333333%;
  }
  .col-lg-push-3 {
    left: 25%;
  }
  .col-lg-push-2 {
    left: 16.66666667%;
  }
  .col-lg-push-1 {
    left: 8.33333333%;
  }
  .col-lg-push-0 {
    left: auto;
  }
  .col-lg-offset-12 {
    margin-left: 100%;
  }
  .col-lg-offset-11 {
    margin-left: 91.66666667%;
  }
  .col-lg-offset-10 {
    margin-left: 83.33333333%;
  }
  .col-lg-offset-9 {
    margin-left: 75%;
  }
  .col-lg-offset-8 {
    margin-left: 66.66666667%;
  }
  .col-lg-offset-7 {
    margin-left: 58.33333333%;
  }
  .col-lg-offset-6 {
    margin-left: 50%;
  }
  .col-lg-offset-5 {
    margin-left: 41.66666667%;
  }
  .col-lg-offset-4 {
    margin-left: 33.33333333%;
  }
  .col-lg-offset-3 {
    margin-left: 25%;
  }
  .col-lg-offset-2 {
    margin-left: 16.66666667%;
  }
  .col-lg-offset-1 {
    margin-left: 8.33333333%;
  }
  .col-lg-offset-0 {
    margin-left: 0%;
  }
}
table {
  background-color: transparent;
}
caption {
  padding-top: 8px;
  padding-bottom: 8px;
  color: #777777;
  text-align: left;
}
th {
  text-align: left;
}
.table {
  width: 100%;
  max-width: 100%;
  margin-bottom: 18px;
}
.table > thead > tr > th,
.table > tbody > tr > th,
.table > tfoot > tr > th,
.table > thead > tr > td,
.table > tbody > tr > td,
.table > tfoot > tr > td {
  padding: 8px;
  line-height: 1.42857143;
  vertical-align: top;
  border-top: 1px solid #ddd;
}
.table > thead > tr > th {
  vertical-align: bottom;
  border-bottom: 2px solid #ddd;
}
.table > caption + thead > tr:first-child > th,
.table > colgroup + thead > tr:first-child > th,
.table > thead:first-child > tr:first-child > th,
.table > caption + thead > tr:first-child > td,
.table > colgroup + thead > tr:first-child > td,
.table > thead:first-child > tr:first-child > td {
  border-top: 0;
}
.table > tbody + tbody {
  border-top: 2px solid #ddd;
}
.table .table {
  background-color: #fff;
}
.table-condensed > thead > tr > th,
.table-condensed > tbody > tr > th,
.table-condensed > tfoot > tr > th,
.table-condensed > thead > tr > td,
.table-condensed > tbody > tr > td,
.table-condensed > tfoot > tr > td {
  padding: 5px;
}
.table-bordered {
  border: 1px solid #ddd;
}
.table-bordered > thead > tr > th,
.table-bordered > tbody > tr > th,
.table-bordered > tfoot > tr > th,
.table-bordered > thead > tr > td,
.table-bordered > tbody > tr > td,
.table-bordered > tfoot > tr > td {
  border: 1px solid #ddd;
}
.table-bordered > thead > tr > th,
.table-bordered > thead > tr > td {
  border-bottom-width: 2px;
}
.table-striped > tbody > tr:nth-of-type(odd) {
  background-color: #f9f9f9;
}
.table-hover > tbody > tr:hover {
  background-color: #f5f5f5;
}
table col[class*="col-"] {
  position: static;
  float: none;
  display: table-column;
}
table td[class*="col-"],
table th[class*="col-"] {
  position: static;
  float: none;
  display: table-cell;
}
.table > thead > tr > td.active,
.table > tbody > tr > td.active,
.table > tfoot > tr > td.active,
.table > thead > tr > th.active,
.table > tbody > tr > th.active,
.table > tfoot > tr > th.active,
.table > thead > tr.active > td,
.table > tbody > tr.active > td,
.table > tfoot > tr.active > td,
.table > thead > tr.active > th,
.table > tbody > tr.active > th,
.table > tfoot > tr.active > th {
  background-color: #f5f5f5;
}
.table-hover > tbody > tr > td.active:hover,
.table-hover > tbody > tr > th.active:hover,
.table-hover > tbody > tr.active:hover > td,
.table-hover > tbody > tr:hover > .active,
.table-hover > tbody > tr.active:hover > th {
  background-color: #e8e8e8;
}
.table > thead > tr > td.success,
.table > tbody > tr > td.success,
.table > tfoot > tr > td.success,
.table > thead > tr > th.success,
.table > tbody > tr > th.success,
.table > tfoot > tr > th.success,
.table > thead > tr.success > td,
.table > tbody > tr.success > td,
.table > tfoot > tr.success > td,
.table > thead > tr.success > th,
.table > tbody > tr.success > th,
.table > tfoot > tr.success > th {
  background-color: #dff0d8;
}
.table-hover > tbody > tr > td.success:hover,
.table-hover > tbody > tr > th.success:hover,
.table-hover > tbody > tr.success:hover > td,
.table-hover > tbody > tr:hover > .success,
.table-hover > tbody > tr.success:hover > th {
  background-color: #d0e9c6;
}
.table > thead > tr > td.info,
.table > tbody > tr > td.info,
.table > tfoot > tr > td.info,
.table > thead > tr > th.info,
.table > tbody > tr > th.info,
.table > tfoot > tr > th.info,
.table > thead > tr.info > td,
.table > tbody > tr.info > td,
.table > tfoot > tr.info > td,
.table > thead > tr.info > th,
.table > tbody > tr.info > th,
.table > tfoot > tr.info > th {
  background-color: #d9edf7;
}
.table-hover > tbody > tr > td.info:hover,
.table-hover > tbody > tr > th.info:hover,
.table-hover > tbody > tr.info:hover > td,
.table-hover > tbody > tr:hover > .info,
.table-hover > tbody > tr.info:hover > th {
  background-color: #c4e3f3;
}
.table > thead > tr > td.warning,
.table > tbody > tr > td.warning,
.table > tfoot > tr > td.warning,
.table > thead > tr > th.warning,
.table > tbody > tr > th.warning,
.table > tfoot > tr > th.warning,
.table > thead > tr.warning > td,
.table > tbody > tr.warning > td,
.table > tfoot > tr.warning > td,
.table > thead > tr.warning > th,
.table > tbody > tr.warning > th,
.table > tfoot > tr.warning > th {
  background-color: #fcf8e3;
}
.table-hover > tbody > tr > td.warning:hover,
.table-hover > tbody > tr > th.warning:hover,
.table-hover > tbody > tr.warning:hover > td,
.table-hover > tbody > tr:hover > .warning,
.table-hover > tbody > tr.warning:hover > th {
  background-color: #faf2cc;
}
.table > thead > tr > td.danger,
.table > tbody > tr > td.danger,
.table > tfoot > tr > td.danger,
.table > thead > tr > th.danger,
.table > tbody > tr > th.danger,
.table > tfoot > tr > th.danger,
.table > thead > tr.danger > td,
.table > tbody > tr.danger > td,
.table > tfoot > tr.danger > td,
.table > thead > tr.danger > th,
.table > tbody > tr.danger > th,
.table > tfoot > tr.danger > th {
  background-color: #f2dede;
}
.table-hover > tbody > tr > td.danger:hover,
.table-hover > tbody > tr > th.danger:hover,
.table-hover > tbody > tr.danger:hover > td,
.table-hover > tbody > tr:hover > .danger,
.table-hover > tbody > tr.danger:hover > th {
  background-color: #ebcccc;
}
.table-responsive {
  overflow-x: auto;
  min-height: 0.01%;
}
@media screen and (max-width: 767px) {
  .table-responsive {
    width: 100%;
    margin-bottom: 13.5px;
    overflow-y: hidden;
    -ms-overflow-style: -ms-autohiding-scrollbar;
    border: 1px solid #ddd;
  }
  .table-responsive > .table {
    margin-bottom: 0;
  }
  .table-responsive > .table > thead > tr > th,
  .table-responsive > .table > tbody > tr > th,
  .table-responsive > .table > tfoot > tr > th,
  .table-responsive > .table > thead > tr > td,
  .table-responsive > .table > tbody > tr > td,
  .table-responsive > .table > tfoot > tr > td {
    white-space: nowrap;
  }
  .table-responsive > .table-bordered {
    border: 0;
  }
  .table-responsive > .table-bordered > thead > tr > th:first-child,
  .table-responsive > .table-bordered > tbody > tr > th:first-child,
  .table-responsive > .table-bordered > tfoot > tr > th:first-child,
  .table-responsive > .table-bordered > thead > tr > td:first-child,
  .table-responsive > .table-bordered > tbody > tr > td:first-child,
  .table-responsive > .table-bordered > tfoot > tr > td:first-child {
    border-left: 0;
  }
  .table-responsive > .table-bordered > thead > tr > th:last-child,
  .table-responsive > .table-bordered > tbody > tr > th:last-child,
  .table-responsive > .table-bordered > tfoot > tr > th:last-child,
  .table-responsive > .table-bordered > thead > tr > td:last-child,
  .table-responsive > .table-bordered > tbody > tr > td:last-child,
  .table-responsive > .table-bordered > tfoot > tr > td:last-child {
    border-right: 0;
  }
  .table-responsive > .table-bordered > tbody > tr:last-child > th,
  .table-responsive > .table-bordered > tfoot > tr:last-child > th,
  .table-responsive > .table-bordered > tbody > tr:last-child > td,
  .table-responsive > .table-bordered > tfoot > tr:last-child > td {
    border-bottom: 0;
  }
}
fieldset {
  padding: 0;
  margin: 0;
  border: 0;
  min-width: 0;
}
legend {
  display: block;
  width: 100%;
  padding: 0;
  margin-bottom: 18px;
  font-size: 19.5px;
  line-height: inherit;
  color: #333333;
  border: 0;
  border-bottom: 1px solid #e5e5e5;
}
label {
  display: inline-block;
  max-width: 100%;
  margin-bottom: 5px;
  font-weight: bold;
}
input[type="search"] {
  -webkit-box-sizing: border-box;
  -moz-box-sizing: border-box;
  box-sizing: border-box;
}
input[type="radio"],
input[type="checkbox"] {
  margin: 4px 0 0;
  margin-top: 1px \9;
  line-height: normal;
}
input[type="file"] {
  display: block;
}
input[type="range"] {
  display: block;
  width: 100%;
}
select[multiple],
select[size] {
  height: auto;
}
input[type="file"]:focus,
input[type="radio"]:focus,
input[type="checkbox"]:focus {
  outline: 5px auto -webkit-focus-ring-color;
  outline-offset: -2px;
}
output {
  display: block;
  padding-top: 7px;
  font-size: 13px;
  line-height: 1.42857143;
  color: #555555;
}
.form-control {
  display: block;
  width: 100%;
  height: 32px;
  padding: 6px 12px;
  font-size: 13px;
  line-height: 1.42857143;
  color: #555555;
  background-color: #fff;
  background-image: none;
  border: 1px solid #ccc;
  border-radius: 2px;
  -webkit-box-shadow: inset 0 1px 1px rgba(0, 0, 0, 0.075);
  box-shadow: inset 0 1px 1px rgba(0, 0, 0, 0.075);
  -webkit-transition: border-color ease-in-out .15s, box-shadow ease-in-out .15s;
  -o-transition: border-color ease-in-out .15s, box-shadow ease-in-out .15s;
  transition: border-color ease-in-out .15s, box-shadow ease-in-out .15s;
}
.form-control:focus {
  border-color: #66afe9;
  outline: 0;
  -webkit-box-shadow: inset 0 1px 1px rgba(0,0,0,.075), 0 0 8px rgba(102, 175, 233, 0.6);
  box-shadow: inset 0 1px 1px rgba(0,0,0,.075), 0 0 8px rgba(102, 175, 233, 0.6);
}
.form-control::-moz-placeholder {
  color: #999;
  opacity: 1;
}
.form-control:-ms-input-placeholder {
  color: #999;
}
.form-control::-webkit-input-placeholder {
  color: #999;
}
.form-control::-ms-expand {
  border: 0;
  background-color: transparent;
}
.form-control[disabled],
.form-control[readonly],
fieldset[disabled] .form-control {
  background-color: #eeeeee;
  opacity: 1;
}
.form-control[disabled],
fieldset[disabled] .form-control {
  cursor: not-allowed;
}
textarea.form-control {
  height: auto;
}
input[type="search"] {
  -webkit-appearance: none;
}
@media screen and (-webkit-min-device-pixel-ratio: 0) {
  input[type="date"].form-control,
  input[type="time"].form-control,
  input[type="datetime-local"].form-control,
  input[type="month"].form-control {
    line-height: 32px;
  }
  input[type="date"].input-sm,
  input[type="time"].input-sm,
  input[type="datetime-local"].input-sm,
  input[type="month"].input-sm,
  .input-group-sm input[type="date"],
  .input-group-sm input[type="time"],
  .input-group-sm input[type="datetime-local"],
  .input-group-sm input[type="month"] {
    line-height: 30px;
  }
  input[type="date"].input-lg,
  input[type="time"].input-lg,
  input[type="datetime-local"].input-lg,
  input[type="month"].input-lg,
  .input-group-lg input[type="date"],
  .input-group-lg input[type="time"],
  .input-group-lg input[type="datetime-local"],
  .input-group-lg input[type="month"] {
    line-height: 45px;
  }
}
.form-group {
  margin-bottom: 15px;
}
.radio,
.checkbox {
  position: relative;
  display: block;
  margin-top: 10px;
  margin-bottom: 10px;
}
.radio label,
.checkbox label {
  min-height: 18px;
  padding-left: 20px;
  margin-bottom: 0;
  font-weight: normal;
  cursor: pointer;
}
.radio input[type="radio"],
.radio-inline input[type="radio"],
.checkbox input[type="checkbox"],
.checkbox-inline input[type="checkbox"] {
  position: absolute;
  margin-left: -20px;
  margin-top: 4px \9;
}
.radio + .radio,
.checkbox + .checkbox {
  margin-top: -5px;
}
.radio-inline,
.checkbox-inline {
  position: relative;
  display: inline-block;
  padding-left: 20px;
  margin-bottom: 0;
  vertical-align: middle;
  font-weight: normal;
  cursor: pointer;
}
.radio-inline + .radio-inline,
.checkbox-inline + .checkbox-inline {
  margin-top: 0;
  margin-left: 10px;
}
input[type="radio"][disabled],
input[type="checkbox"][disabled],
input[type="radio"].disabled,
input[type="checkbox"].disabled,
fieldset[disabled] input[type="radio"],
fieldset[disabled] input[type="checkbox"] {
  cursor: not-allowed;
}
.radio-inline.disabled,
.checkbox-inline.disabled,
fieldset[disabled] .radio-inline,
fieldset[disabled] .checkbox-inline {
  cursor: not-allowed;
}
.radio.disabled label,
.checkbox.disabled label,
fieldset[disabled] .radio label,
fieldset[disabled] .checkbox label {
  cursor: not-allowed;
}
.form-control-static {
  padding-top: 7px;
  padding-bottom: 7px;
  margin-bottom: 0;
  min-height: 31px;
}
.form-control-static.input-lg,
.form-control-static.input-sm {
  padding-left: 0;
  padding-right: 0;
}
.input-sm {
  height: 30px;
  padding: 5px 10px;
  font-size: 12px;
  line-height: 1.5;
  border-radius: 1px;
}
select.input-sm {
  height: 30px;
  line-height: 30px;
}
textarea.input-sm,
select[multiple].input-sm {
  height: auto;
}
.form-group-sm .form-control {
  height: 30px;
  padding: 5px 10px;
  font-size: 12px;
  line-height: 1.5;
  border-radius: 1px;
}
.form-group-sm select.form-control {
  height: 30px;
  line-height: 30px;
}
.form-group-sm textarea.form-control,
.form-group-sm select[multiple].form-control {
  height: auto;
}
.form-group-sm .form-control-static {
  height: 30px;
  min-height: 30px;
  padding: 6px 10px;
  font-size: 12px;
  line-height: 1.5;
}
.input-lg {
  height: 45px;
  padding: 10px 16px;
  font-size: 17px;
  line-height: 1.3333333;
  border-radius: 3px;
}
select.input-lg {
  height: 45px;
  line-height: 45px;
}
textarea.input-lg,
select[multiple].input-lg {
  height: auto;
}
.form-group-lg .form-control {
  height: 45px;
  padding: 10px 16px;
  font-size: 17px;
  line-height: 1.3333333;
  border-radius: 3px;
}
.form-group-lg select.form-control {
  height: 45px;
  line-height: 45px;
}
.form-group-lg textarea.form-control,
.form-group-lg select[multiple].form-control {
  height: auto;
}
.form-group-lg .form-control-static {
  height: 45px;
  min-height: 35px;
  padding: 11px 16px;
  font-size: 17px;
  line-height: 1.3333333;
}
.has-feedback {
  position: relative;
}
.has-feedback .form-control {
  padding-right: 40px;
}
.form-control-feedback {
  position: absolute;
  top: 0;
  right: 0;
  z-index: 2;
  display: block;
  width: 32px;
  height: 32px;
  line-height: 32px;
  text-align: center;
  pointer-events: none;
}
.input-lg + .form-control-feedback,
.input-group-lg + .form-control-feedback,
.form-group-lg .form-control + .form-control-feedback {
  width: 45px;
  height: 45px;
  line-height: 45px;
}
.input-sm + .form-control-feedback,
.input-group-sm + .form-control-feedback,
.form-group-sm .form-control + .form-control-feedback {
  width: 30px;
  height: 30px;
  line-height: 30px;
}
.has-success .help-block,
.has-success .control-label,
.has-success .radio,
.has-success .checkbox,
.has-success .radio-inline,
.has-success .checkbox-inline,
.has-success.radio label,
.has-success.checkbox label,
.has-success.radio-inline label,
.has-success.checkbox-inline label {
  color: #3c763d;
}
.has-success .form-control {
  border-color: #3c763d;
  -webkit-box-shadow: inset 0 1px 1px rgba(0, 0, 0, 0.075);
  box-shadow: inset 0 1px 1px rgba(0, 0, 0, 0.075);
}
.has-success .form-control:focus {
  border-color: #2b542c;
  -webkit-box-shadow: inset 0 1px 1px rgba(0, 0, 0, 0.075), 0 0 6px #67b168;
  box-shadow: inset 0 1px 1px rgba(0, 0, 0, 0.075), 0 0 6px #67b168;
}
.has-success .input-group-addon {
  color: #3c763d;
  border-color: #3c763d;
  background-color: #dff0d8;
}
.has-success .form-control-feedback {
  color: #3c763d;
}
.has-warning .help-block,
.has-warning .control-label,
.has-warning .radio,
.has-warning .checkbox,
.has-warning .radio-inline,
.has-warning .checkbox-inline,
.has-warning.radio label,
.has-warning.checkbox label,
.has-warning.radio-inline label,
.has-warning.checkbox-inline label {
  color: #8a6d3b;
}
.has-warning .form-control {
  border-color: #8a6d3b;
  -webkit-box-shadow: inset 0 1px 1px rgba(0, 0, 0, 0.075);
  box-shadow: inset 0 1px 1px rgba(0, 0, 0, 0.075);
}
.has-warning .form-control:focus {
  border-color: #66512c;
  -webkit-box-shadow: inset 0 1px 1px rgba(0, 0, 0, 0.075), 0 0 6px #c0a16b;
  box-shadow: inset 0 1px 1px rgba(0, 0, 0, 0.075), 0 0 6px #c0a16b;
}
.has-warning .input-group-addon {
  color: #8a6d3b;
  border-color: #8a6d3b;
  background-color: #fcf8e3;
}
.has-warning .form-control-feedback {
  color: #8a6d3b;
}
.has-error .help-block,
.has-error .control-label,
.has-error .radio,
.has-error .checkbox,
.has-error .radio-inline,
.has-error .checkbox-inline,
.has-error.radio label,
.has-error.checkbox label,
.has-error.radio-inline label,
.has-error.checkbox-inline label {
  color: #a94442;
}
.has-error .form-control {
  border-color: #a94442;
  -webkit-box-shadow: inset 0 1px 1px rgba(0, 0, 0, 0.075);
  box-shadow: inset 0 1px 1px rgba(0, 0, 0, 0.075);
}
.has-error .form-control:focus {
  border-color: #843534;
  -webkit-box-shadow: inset 0 1px 1px rgba(0, 0, 0, 0.075), 0 0 6px #ce8483;
  box-shadow: inset 0 1px 1px rgba(0, 0, 0, 0.075), 0 0 6px #ce8483;
}
.has-error .input-group-addon {
  color: #a94442;
  border-color: #a94442;
  background-color: #f2dede;
}
.has-error .form-control-feedback {
  color: #a94442;
}
.has-feedback label ~ .form-control-feedback {
  top: 23px;
}
.has-feedback label.sr-only ~ .form-control-feedback {
  top: 0;
}
.help-block {
  display: block;
  margin-top: 5px;
  margin-bottom: 10px;
  color: #404040;
}
@media (min-width: 768px) {
  .form-inline .form-group {
    display: inline-block;
    margin-bottom: 0;
    vertical-align: middle;
  }
  .form-inline .form-control {
    display: inline-block;
    width: auto;
    vertical-align: middle;
  }
  .form-inline .form-control-static {
    display: inline-block;
  }
  .form-inline .input-group {
    display: inline-table;
    vertical-align: middle;
  }
  .form-inline .input-group .input-group-addon,
  .form-inline .input-group .input-group-btn,
  .form-inline .input-group .form-control {
    width: auto;
  }
  .form-inline .input-group > .form-control {
    width: 100%;
  }
  .form-inline .control-label {
    margin-bottom: 0;
    vertical-align: middle;
  }
  .form-inline .radio,
  .form-inline .checkbox {
    display: inline-block;
    margin-top: 0;
    margin-bottom: 0;
    vertical-align: middle;
  }
  .form-inline .radio label,
  .form-inline .checkbox label {
    padding-left: 0;
  }
  .form-inline .radio input[type="radio"],
  .form-inline .checkbox input[type="checkbox"] {
    position: relative;
    margin-left: 0;
  }
  .form-inline .has-feedback .form-control-feedback {
    top: 0;
  }
}
.form-horizontal .radio,
.form-horizontal .checkbox,
.form-horizontal .radio-inline,
.form-horizontal .checkbox-inline {
  margin-top: 0;
  margin-bottom: 0;
  padding-top: 7px;
}
.form-horizontal .radio,
.form-horizontal .checkbox {
  min-height: 25px;
}
.form-horizontal .form-group {
  margin-left: 0px;
  margin-right: 0px;
}
@media (min-width: 768px) {
  .form-horizontal .control-label {
    text-align: right;
    margin-bottom: 0;
    padding-top: 7px;
  }
}
.form-horizontal .has-feedback .form-control-feedback {
  right: 0px;
}
@media (min-width: 768px) {
  .form-horizontal .form-group-lg .control-label {
    padding-top: 11px;
    font-size: 17px;
  }
}
@media (min-width: 768px) {
  .form-horizontal .form-group-sm .control-label {
    padding-top: 6px;
    font-size: 12px;
  }
}
.btn {
  display: inline-block;
  margin-bottom: 0;
  font-weight: normal;
  text-align: center;
  vertical-align: middle;
  touch-action: manipulation;
  cursor: pointer;
  background-image: none;
  border: 1px solid transparent;
  white-space: nowrap;
  padding: 6px 12px;
  font-size: 13px;
  line-height: 1.42857143;
  border-radius: 2px;
  -webkit-user-select: none;
  -moz-user-select: none;
  -ms-user-select: none;
  user-select: none;
}
.btn:focus,
.btn:active:focus,
.btn.active:focus,
.btn.focus,
.btn:active.focus,
.btn.active.focus {
  outline: 5px auto -webkit-focus-ring-color;
  outline-offset: -2px;
}
.btn:hover,
.btn:focus,
.btn.focus {
  color: #333;
  text-decoration: none;
}
.btn:active,
.btn.active {
  outline: 0;
  background-image: none;
  -webkit-box-shadow: inset 0 3px 5px rgba(0, 0, 0, 0.125);
  box-shadow: inset 0 3px 5px rgba(0, 0, 0, 0.125);
}
.btn.disabled,
.btn[disabled],
fieldset[disabled] .btn {
  cursor: not-allowed;
  opacity: 0.65;
  filter: alpha(opacity=65);
  -webkit-box-shadow: none;
  box-shadow: none;
}
a.btn.disabled,
fieldset[disabled] a.btn {
  pointer-events: none;
}
.btn-default {
  color: #333;
  background-color: #fff;
  border-color: #ccc;
}
.btn-default:focus,
.btn-default.focus {
  color: #333;
  background-color: #e6e6e6;
  border-color: #8c8c8c;
}
.btn-default:hover {
  color: #333;
  background-color: #e6e6e6;
  border-color: #adadad;
}
.btn-default:active,
.btn-default.active,
.open > .dropdown-toggle.btn-default {
  color: #333;
  background-color: #e6e6e6;
  border-color: #adadad;
}
.btn-default:active:hover,
.btn-default.active:hover,
.open > .dropdown-toggle.btn-default:hover,
.btn-default:active:focus,
.btn-default.active:focus,
.open > .dropdown-toggle.btn-default:focus,
.btn-default:active.focus,
.btn-default.active.focus,
.open > .dropdown-toggle.btn-default.focus {
  color: #333;
  background-color: #d4d4d4;
  border-color: #8c8c8c;
}
.btn-default:active,
.btn-default.active,
.open > .dropdown-toggle.btn-default {
  background-image: none;
}
.btn-default.disabled:hover,
.btn-default[disabled]:hover,
fieldset[disabled] .btn-default:hover,
.btn-default.disabled:focus,
.btn-default[disabled]:focus,
fieldset[disabled] .btn-default:focus,
.btn-default.disabled.focus,
.btn-default[disabled].focus,
fieldset[disabled] .btn-default.focus {
  background-color: #fff;
  border-color: #ccc;
}
.btn-default .badge {
  color: #fff;
  background-color: #333;
}
.btn-primary {
  color: #fff;
  background-color: #337ab7;
  border-color: #2e6da4;
}
.btn-primary:focus,
.btn-primary.focus {
  color: #fff;
  background-color: #286090;
  border-color: #122b40;
}
.btn-primary:hover {
  color: #fff;
  background-color: #286090;
  border-color: #204d74;
}
.btn-primary:active,
.btn-primary.active,
.open > .dropdown-toggle.btn-primary {
  color: #fff;
  background-color: #286090;
  border-color: #204d74;
}
.btn-primary:active:hover,
.btn-primary.active:hover,
.open > .dropdown-toggle.btn-primary:hover,
.btn-primary:active:focus,
.btn-primary.active:focus,
.open > .dropdown-toggle.btn-primary:focus,
.btn-primary:active.focus,
.btn-primary.active.focus,
.open > .dropdown-toggle.btn-primary.focus {
  color: #fff;
  background-color: #204d74;
  border-color: #122b40;
}
.btn-primary:active,
.btn-primary.active,
.open > .dropdown-toggle.btn-primary {
  background-image: none;
}
.btn-primary.disabled:hover,
.btn-primary[disabled]:hover,
fieldset[disabled] .btn-primary:hover,
.btn-primary.disabled:focus,
.btn-primary[disabled]:focus,
fieldset[disabled] .btn-primary:focus,
.btn-primary.disabled.focus,
.btn-primary[disabled].focus,
fieldset[disabled] .btn-primary.focus {
  background-color: #337ab7;
  border-color: #2e6da4;
}
.btn-primary .badge {
  color: #337ab7;
  background-color: #fff;
}
.btn-success {
  color: #fff;
  background-color: #5cb85c;
  border-color: #4cae4c;
}
.btn-success:focus,
.btn-success.focus {
  color: #fff;
  background-color: #449d44;
  border-color: #255625;
}
.btn-success:hover {
  color: #fff;
  background-color: #449d44;
  border-color: #398439;
}
.btn-success:active,
.btn-success.active,
.open > .dropdown-toggle.btn-success {
  color: #fff;
  background-color: #449d44;
  border-color: #398439;
}
.btn-success:active:hover,
.btn-success.active:hover,
.open > .dropdown-toggle.btn-success:hover,
.btn-success:active:focus,
.btn-success.active:focus,
.open > .dropdown-toggle.btn-success:focus,
.btn-success:active.focus,
.btn-success.active.focus,
.open > .dropdown-toggle.btn-success.focus {
  color: #fff;
  background-color: #398439;
  border-color: #255625;
}
.btn-success:active,
.btn-success.active,
.open > .dropdown-toggle.btn-success {
  background-image: none;
}
.btn-success.disabled:hover,
.btn-success[disabled]:hover,
fieldset[disabled] .btn-success:hover,
.btn-success.disabled:focus,
.btn-success[disabled]:focus,
fieldset[disabled] .btn-success:focus,
.btn-success.disabled.focus,
.btn-success[disabled].focus,
fieldset[disabled] .btn-success.focus {
  background-color: #5cb85c;
  border-color: #4cae4c;
}
.btn-success .badge {
  color: #5cb85c;
  background-color: #fff;
}
.btn-info {
  color: #fff;
  background-color: #5bc0de;
  border-color: #46b8da;
}
.btn-info:focus,
.btn-info.focus {
  color: #fff;
  background-color: #31b0d5;
  border-color: #1b6d85;
}
.btn-info:hover {
  color: #fff;
  background-color: #31b0d5;
  border-color: #269abc;
}
.btn-info:active,
.btn-info.active,
.open > .dropdown-toggle.btn-info {
  color: #fff;
  background-color: #31b0d5;
  border-color: #269abc;
}
.btn-info:active:hover,
.btn-info.active:hover,
.open > .dropdown-toggle.btn-info:hover,
.btn-info:active:focus,
.btn-info.active:focus,
.open > .dropdown-toggle.btn-info:focus,
.btn-info:active.focus,
.btn-info.active.focus,
.open > .dropdown-toggle.btn-info.focus {
  color: #fff;
  background-color: #269abc;
  border-color: #1b6d85;
}
.btn-info:active,
.btn-info.active,
.open > .dropdown-toggle.btn-info {
  background-image: none;
}
.btn-info.disabled:hover,
.btn-info[disabled]:hover,
fieldset[disabled] .btn-info:hover,
.btn-info.disabled:focus,
.btn-info[disabled]:focus,
fieldset[disabled] .btn-info:focus,
.btn-info.disabled.focus,
.btn-info[disabled].focus,
fieldset[disabled] .btn-info.focus {
  background-color: #5bc0de;
  border-color: #46b8da;
}
.btn-info .badge {
  color: #5bc0de;
  background-color: #fff;
}
.btn-warning {
  color: #fff;
  background-color: #f0ad4e;
  border-color: #eea236;
}
.btn-warning:focus,
.btn-warning.focus {
  color: #fff;
  background-color: #ec971f;
  border-color: #985f0d;
}
.btn-warning:hover {
  color: #fff;
  background-color: #ec971f;
  border-color: #d58512;
}
.btn-warning:active,
.btn-warning.active,
.open > .dropdown-toggle.btn-warning {
  color: #fff;
  background-color: #ec971f;
  border-color: #d58512;
}
.btn-warning:active:hover,
.btn-warning.active:hover,
.open > .dropdown-toggle.btn-warning:hover,
.btn-warning:active:focus,
.btn-warning.active:focus,
.open > .dropdown-toggle.btn-warning:focus,
.btn-warning:active.focus,
.btn-warning.active.focus,
.open > .dropdown-toggle.btn-warning.focus {
  color: #fff;
  background-color: #d58512;
  border-color: #985f0d;
}
.btn-warning:active,
.btn-warning.active,
.open > .dropdown-toggle.btn-warning {
  background-image: none;
}
.btn-warning.disabled:hover,
.btn-warning[disabled]:hover,
fieldset[disabled] .btn-warning:hover,
.btn-warning.disabled:focus,
.btn-warning[disabled]:focus,
fieldset[disabled] .btn-warning:focus,
.btn-warning.disabled.focus,
.btn-warning[disabled].focus,
fieldset[disabled] .btn-warning.focus {
  background-color: #f0ad4e;
  border-color: #eea236;
}
.btn-warning .badge {
  color: #f0ad4e;
  background-color: #fff;
}
.btn-danger {
  color: #fff;
  background-color: #d9534f;
  border-color: #d43f3a;
}
.btn-danger:focus,
.btn-danger.focus {
  color: #fff;
  background-color: #c9302c;
  border-color: #761c19;
}
.btn-danger:hover {
  color: #fff;
  background-color: #c9302c;
  border-color: #ac2925;
}
.btn-danger:active,
.btn-danger.active,
.open > .dropdown-toggle.btn-danger {
  color: #fff;
  background-color: #c9302c;
  border-color: #ac2925;
}
.btn-danger:active:hover,
.btn-danger.active:hover,
.open > .dropdown-toggle.btn-danger:hover,
.btn-danger:active:focus,
.btn-danger.active:focus,
.open > .dropdown-toggle.btn-danger:focus,
.btn-danger:active.focus,
.btn-danger.active.focus,
.open > .dropdown-toggle.btn-danger.focus {
  color: #fff;
  background-color: #ac2925;
  border-color: #761c19;
}
.btn-danger:active,
.btn-danger.active,
.open > .dropdown-toggle.btn-danger {
  background-image: none;
}
.btn-danger.disabled:hover,
.btn-danger[disabled]:hover,
fieldset[disabled] .btn-danger:hover,
.btn-danger.disabled:focus,
.btn-danger[disabled]:focus,
fieldset[disabled] .btn-danger:focus,
.btn-danger.disabled.focus,
.btn-danger[disabled].focus,
fieldset[disabled] .btn-danger.focus {
  background-color: #d9534f;
  border-color: #d43f3a;
}
.btn-danger .badge {
  color: #d9534f;
  background-color: #fff;
}
.btn-link {
  color: #337ab7;
  font-weight: normal;
  border-radius: 0;
}
.btn-link,
.btn-link:active,
.btn-link.active,
.btn-link[disabled],
fieldset[disabled] .btn-link {
  background-color: transparent;
  -webkit-box-shadow: none;
  box-shadow: none;
}
.btn-link,
.btn-link:hover,
.btn-link:focus,
.btn-link:active {
  border-color: transparent;
}
.btn-link:hover,
.btn-link:focus {
  color: #23527c;
  text-decoration: underline;
  background-color: transparent;
}
.btn-link[disabled]:hover,
fieldset[disabled] .btn-link:hover,
.btn-link[disabled]:focus,
fieldset[disabled] .btn-link:focus {
  color: #777777;
  text-decoration: none;
}
.btn-lg,
.btn-group-lg > .btn {
  padding: 10px 16px;
  font-size: 17px;
  line-height: 1.3333333;
  border-radius: 3px;
}
.btn-sm,
.btn-group-sm > .btn {
  padding: 5px 10px;
  font-size: 12px;
  line-height: 1.5;
  border-radius: 1px;
}
.btn-xs,
.btn-group-xs > .btn {
  padding: 1px 5px;
  font-size: 12px;
  line-height: 1.5;
  border-radius: 1px;
}
.btn-block {
  display: block;
  width: 100%;
}
.btn-block + .btn-block {
  margin-top: 5px;
}
input[type="submit"].btn-block,
input[type="reset"].btn-block,
input[type="button"].btn-block {
  width: 100%;
}
.fade {
  opacity: 0;
  -webkit-transition: opacity 0.15s linear;
  -o-transition: opacity 0.15s linear;
  transition: opacity 0.15s linear;
}
.fade.in {
  opacity: 1;
}
.collapse {
  display: none;
}
.collapse.in {
  display: block;
}
tr.collapse.in {
  display: table-row;
}
tbody.collapse.in {
  display: table-row-group;
}
.collapsing {
  position: relative;
  height: 0;
  overflow: hidden;
  -webkit-transition-property: height, visibility;
  transition-property: height, visibility;
  -webkit-transition-duration: 0.35s;
  transition-duration: 0.35s;
  -webkit-transition-timing-function: ease;
  transition-timing-function: ease;
}
.caret {
  display: inline-block;
  width: 0;
  height: 0;
  margin-left: 2px;
  vertical-align: middle;
  border-top: 4px dashed;
  border-top: 4px solid \9;
  border-right: 4px solid transparent;
  border-left: 4px solid transparent;
}
.dropup,
.dropdown {
  position: relative;
}
.dropdown-toggle:focus {
  outline: 0;
}
.dropdown-menu {
  position: absolute;
  top: 100%;
  left: 0;
  z-index: 1000;
  display: none;
  float: left;
  min-width: 160px;
  padding: 5px 0;
  margin: 2px 0 0;
  list-style: none;
  font-size: 13px;
  text-align: left;
  background-color: #fff;
  border: 1px solid #ccc;
  border: 1px solid rgba(0, 0, 0, 0.15);
  border-radius: 2px;
  -webkit-box-shadow: 0 6px 12px rgba(0, 0, 0, 0.175);
  box-shadow: 0 6px 12px rgba(0, 0, 0, 0.175);
  background-clip: padding-box;
}
.dropdown-menu.pull-right {
  right: 0;
  left: auto;
}
.dropdown-menu .divider {
  height: 1px;
  margin: 8px 0;
  overflow: hidden;
  background-color: #e5e5e5;
}
.dropdown-menu > li > a {
  display: block;
  padding: 3px 20px;
  clear: both;
  font-weight: normal;
  line-height: 1.42857143;
  color: #333333;
  white-space: nowrap;
}
.dropdown-menu > li > a:hover,
.dropdown-menu > li > a:focus {
  text-decoration: none;
  color: #262626;
  background-color: #f5f5f5;
}
.dropdown-menu > .active > a,
.dropdown-menu > .active > a:hover,
.dropdown-menu > .active > a:focus {
  color: #fff;
  text-decoration: none;
  outline: 0;
  background-color: #337ab7;
}
.dropdown-menu > .disabled > a,
.dropdown-menu > .disabled > a:hover,
.dropdown-menu > .disabled > a:focus {
  color: #777777;
}
.dropdown-menu > .disabled > a:hover,
.dropdown-menu > .disabled > a:focus {
  text-decoration: none;
  background-color: transparent;
  background-image: none;
  filter: progid:DXImageTransform.Microsoft.gradient(enabled = false);
  cursor: not-allowed;
}
.open > .dropdown-menu {
  display: block;
}
.open > a {
  outline: 0;
}
.dropdown-menu-right {
  left: auto;
  right: 0;
}
.dropdown-menu-left {
  left: 0;
  right: auto;
}
.dropdown-header {
  display: block;
  padding: 3px 20px;
  font-size: 12px;
  line-height: 1.42857143;
  color: #777777;
  white-space: nowrap;
}
.dropdown-backdrop {
  position: fixed;
  left: 0;
  right: 0;
  bottom: 0;
  top: 0;
  z-index: 990;
}
.pull-right > .dropdown-menu {
  right: 0;
  left: auto;
}
.dropup .caret,
.navbar-fixed-bottom .dropdown .caret {
  border-top: 0;
  border-bottom: 4px dashed;
  border-bottom: 4px solid \9;
  content: "";
}
.dropup .dropdown-menu,
.navbar-fixed-bottom .dropdown .dropdown-menu {
  top: auto;
  bottom: 100%;
  margin-bottom: 2px;
}
@media (min-width: 541px) {
  .navbar-right .dropdown-menu {
    left: auto;
    right: 0;
  }
  .navbar-right .dropdown-menu-left {
    left: 0;
    right: auto;
  }
}
.btn-group,
.btn-group-vertical {
  position: relative;
  display: inline-block;
  vertical-align: middle;
}
.btn-group > .btn,
.btn-group-vertical > .btn {
  position: relative;
  float: left;
}
.btn-group > .btn:hover,
.btn-group-vertical > .btn:hover,
.btn-group > .btn:focus,
.btn-group-vertical > .btn:focus,
.btn-group > .btn:active,
.btn-group-vertical > .btn:active,
.btn-group > .btn.active,
.btn-group-vertical > .btn.active {
  z-index: 2;
}
.btn-group .btn + .btn,
.btn-group .btn + .btn-group,
.btn-group .btn-group + .btn,
.btn-group .btn-group + .btn-group {
  margin-left: -1px;
}
.btn-toolbar {
  margin-left: -5px;
}
.btn-toolbar .btn,
.btn-toolbar .btn-group,
.btn-toolbar .input-group {
  float: left;
}
.btn-toolbar > .btn,
.btn-toolbar > .btn-group,
.btn-toolbar > .input-group {
  margin-left: 5px;
}
.btn-group > .btn:not(:first-child):not(:last-child):not(.dropdown-toggle) {
  border-radius: 0;
}
.btn-group > .btn:first-child {
  margin-left: 0;
}
.btn-group > .btn:first-child:not(:last-child):not(.dropdown-toggle) {
  border-bottom-right-radius: 0;
  border-top-right-radius: 0;
}
.btn-group > .btn:last-child:not(:first-child),
.btn-group > .dropdown-toggle:not(:first-child) {
  border-bottom-left-radius: 0;
  border-top-left-radius: 0;
}
.btn-group > .btn-group {
  float: left;
}
.btn-group > .btn-group:not(:first-child):not(:last-child) > .btn {
  border-radius: 0;
}
.btn-group > .btn-group:first-child:not(:last-child) > .btn:last-child,
.btn-group > .btn-group:first-child:not(:last-child) > .dropdown-toggle {
  border-bottom-right-radius: 0;
  border-top-right-radius: 0;
}
.btn-group > .btn-group:last-child:not(:first-child) > .btn:first-child {
  border-bottom-left-radius: 0;
  border-top-left-radius: 0;
}
.btn-group .dropdown-toggle:active,
.btn-group.open .dropdown-toggle {
  outline: 0;
}
.btn-group > .btn + .dropdown-toggle {
  padding-left: 8px;
  padding-right: 8px;
}
.btn-group > .btn-lg + .dropdown-toggle {
  padding-left: 12px;
  padding-right: 12px;
}
.btn-group.open .dropdown-toggle {
  -webkit-box-shadow: inset 0 3px 5px rgba(0, 0, 0, 0.125);
  box-shadow: inset 0 3px 5px rgba(0, 0, 0, 0.125);
}
.btn-group.open .dropdown-toggle.btn-link {
  -webkit-box-shadow: none;
  box-shadow: none;
}
.btn .caret {
  margin-left: 0;
}
.btn-lg .caret {
  border-width: 5px 5px 0;
  border-bottom-width: 0;
}
.dropup .btn-lg .caret {
  border-width: 0 5px 5px;
}
.btn-group-vertical > .btn,
.btn-group-vertical > .btn-group,
.btn-group-vertical > .btn-group > .btn {
  display: block;
  float: none;
  width: 100%;
  max-width: 100%;
}
.btn-group-vertical > .btn-group > .btn {
  float: none;
}
.btn-group-vertical > .btn + .btn,
.btn-group-vertical > .btn + .btn-group,
.btn-group-vertical > .btn-group + .btn,
.btn-group-vertical > .btn-group + .btn-group {
  margin-top: -1px;
  margin-left: 0;
}
.btn-group-vertical > .btn:not(:first-child):not(:last-child) {
  border-radius: 0;
}
.btn-group-vertical > .btn:first-child:not(:last-child) {
  border-top-right-radius: 2px;
  border-top-left-radius: 2px;
  border-bottom-right-radius: 0;
  border-bottom-left-radius: 0;
}
.btn-group-vertical > .btn:last-child:not(:first-child) {
  border-top-right-radius: 0;
  border-top-left-radius: 0;
  border-bottom-right-radius: 2px;
  border-bottom-left-radius: 2px;
}
.btn-group-vertical > .btn-group:not(:first-child):not(:last-child) > .btn {
  border-radius: 0;
}
.btn-group-vertical > .btn-group:first-child:not(:last-child) > .btn:last-child,
.btn-group-vertical > .btn-group:first-child:not(:last-child) > .dropdown-toggle {
  border-bottom-right-radius: 0;
  border-bottom-left-radius: 0;
}
.btn-group-vertical > .btn-group:last-child:not(:first-child) > .btn:first-child {
  border-top-right-radius: 0;
  border-top-left-radius: 0;
}
.btn-group-justified {
  display: table;
  width: 100%;
  table-layout: fixed;
  border-collapse: separate;
}
.btn-group-justified > .btn,
.btn-group-justified > .btn-group {
  float: none;
  display: table-cell;
  width: 1%;
}
.btn-group-justified > .btn-group .btn {
  width: 100%;
}
.btn-group-justified > .btn-group .dropdown-menu {
  left: auto;
}
[data-toggle="buttons"] > .btn input[type="radio"],
[data-toggle="buttons"] > .btn-group > .btn input[type="radio"],
[data-toggle="buttons"] > .btn input[type="checkbox"],
[data-toggle="buttons"] > .btn-group > .btn input[type="checkbox"] {
  position: absolute;
  clip: rect(0, 0, 0, 0);
  pointer-events: none;
}
.input-group {
  position: relative;
  display: table;
  border-collapse: separate;
}
.input-group[class*="col-"] {
  float: none;
  padding-left: 0;
  padding-right: 0;
}
.input-group .form-control {
  position: relative;
  z-index: 2;
  float: left;
  width: 100%;
  margin-bottom: 0;
}
.input-group .form-control:focus {
  z-index: 3;
}
.input-group-lg > .form-control,
.input-group-lg > .input-group-addon,
.input-group-lg > .input-group-btn > .btn {
  height: 45px;
  padding: 10px 16px;
  font-size: 17px;
  line-height: 1.3333333;
  border-radius: 3px;
}
select.input-group-lg > .form-control,
select.input-group-lg > .input-group-addon,
select.input-group-lg > .input-group-btn > .btn {
  height: 45px;
  line-height: 45px;
}
textarea.input-group-lg > .form-control,
textarea.input-group-lg > .input-group-addon,
textarea.input-group-lg > .input-group-btn > .btn,
select[multiple].input-group-lg > .form-control,
select[multiple].input-group-lg > .input-group-addon,
select[multiple].input-group-lg > .input-group-btn > .btn {
  height: auto;
}
.input-group-sm > .form-control,
.input-group-sm > .input-group-addon,
.input-group-sm > .input-group-btn > .btn {
  height: 30px;
  padding: 5px 10px;
  font-size: 12px;
  line-height: 1.5;
  border-radius: 1px;
}
select.input-group-sm > .form-control,
select.input-group-sm > .input-group-addon,
select.input-group-sm > .input-group-btn > .btn {
  height: 30px;
  line-height: 30px;
}
textarea.input-group-sm > .form-control,
textarea.input-group-sm > .input-group-addon,
textarea.input-group-sm > .input-group-btn > .btn,
select[multiple].input-group-sm > .form-control,
select[multiple].input-group-sm > .input-group-addon,
select[multiple].input-group-sm > .input-group-btn > .btn {
  height: auto;
}
.input-group-addon,
.input-group-btn,
.input-group .form-control {
  display: table-cell;
}
.input-group-addon:not(:first-child):not(:last-child),
.input-group-btn:not(:first-child):not(:last-child),
.input-group .form-control:not(:first-child):not(:last-child) {
  border-radius: 0;
}
.input-group-addon,
.input-group-btn {
  width: 1%;
  white-space: nowrap;
  vertical-align: middle;
}
.input-group-addon {
  padding: 6px 12px;
  font-size: 13px;
  font-weight: normal;
  line-height: 1;
  color: #555555;
  text-align: center;
  background-color: #eeeeee;
  border: 1px solid #ccc;
  border-radius: 2px;
}
.input-group-addon.input-sm {
  padding: 5px 10px;
  font-size: 12px;
  border-radius: 1px;
}
.input-group-addon.input-lg {
  padding: 10px 16px;
  font-size: 17px;
  border-radius: 3px;
}
.input-group-addon input[type="radio"],
.input-group-addon input[type="checkbox"] {
  margin-top: 0;
}
.input-group .form-control:first-child,
.input-group-addon:first-child,
.input-group-btn:first-child > .btn,
.input-group-btn:first-child > .btn-group > .btn,
.input-group-btn:first-child > .dropdown-toggle,
.input-group-btn:last-child > .btn:not(:last-child):not(.dropdown-toggle),
.input-group-btn:last-child > .btn-group:not(:last-child) > .btn {
  border-bottom-right-radius: 0;
  border-top-right-radius: 0;
}
.input-group-addon:first-child {
  border-right: 0;
}
.input-group .form-control:last-child,
.input-group-addon:last-child,
.input-group-btn:last-child > .btn,
.input-group-btn:last-child > .btn-group > .btn,
.input-group-btn:last-child > .dropdown-toggle,
.input-group-btn:first-child > .btn:not(:first-child),
.input-group-btn:first-child > .btn-group:not(:first-child) > .btn {
  border-bottom-left-radius: 0;
  border-top-left-radius: 0;
}
.input-group-addon:last-child {
  border-left: 0;
}
.input-group-btn {
  position: relative;
  font-size: 0;
  white-space: nowrap;
}
.input-group-btn > .btn {
  position: relative;
}
.input-group-btn > .btn + .btn {
  margin-left: -1px;
}
.input-group-btn > .btn:hover,
.input-group-btn > .btn:focus,
.input-group-btn > .btn:active {
  z-index: 2;
}
.input-group-btn:first-child > .btn,
.input-group-btn:first-child > .btn-group {
  margin-right: -1px;
}
.input-group-btn:last-child > .btn,
.input-group-btn:last-child > .btn-group {
  z-index: 2;
  margin-left: -1px;
}
.nav {
  margin-bottom: 0;
  padding-left: 0;
  list-style: none;
}
.nav > li {
  position: relative;
  display: block;
}
.nav > li > a {
  position: relative;
  display: block;
  padding: 10px 15px;
}
.nav > li > a:hover,
.nav > li > a:focus {
  text-decoration: none;
  background-color: #eeeeee;
}
.nav > li.disabled > a {
  color: #777777;
}
.nav > li.disabled > a:hover,
.nav > li.disabled > a:focus {
  color: #777777;
  text-decoration: none;
  background-color: transparent;
  cursor: not-allowed;
}
.nav .open > a,
.nav .open > a:hover,
.nav .open > a:focus {
  background-color: #eeeeee;
  border-color: #337ab7;
}
.nav .nav-divider {
  height: 1px;
  margin: 8px 0;
  overflow: hidden;
  background-color: #e5e5e5;
}
.nav > li > a > img {
  max-width: none;
}
.nav-tabs {
  border-bottom: 1px solid #ddd;
}
.nav-tabs > li {
  float: left;
  margin-bottom: -1px;
}
.nav-tabs > li > a {
  margin-right: 2px;
  line-height: 1.42857143;
  border: 1px solid transparent;
  border-radius: 2px 2px 0 0;
}
.nav-tabs > li > a:hover {
  border-color: #eeeeee #eeeeee #ddd;
}
.nav-tabs > li.active > a,
.nav-tabs > li.active > a:hover,
.nav-tabs > li.active > a:focus {
  color: #555555;
  background-color: #fff;
  border: 1px solid #ddd;
  border-bottom-color: transparent;
  cursor: default;
}
.nav-tabs.nav-justified {
  width: 100%;
  border-bottom: 0;
}
.nav-tabs.nav-justified > li {
  float: none;
}
.nav-tabs.nav-justified > li > a {
  text-align: center;
  margin-bottom: 5px;
}
.nav-tabs.nav-justified > .dropdown .dropdown-menu {
  top: auto;
  left: auto;
}
@media (min-width: 768px) {
  .nav-tabs.nav-justified > li {
    display: table-cell;
    width: 1%;
  }
  .nav-tabs.nav-justified > li > a {
    margin-bottom: 0;
  }
}
.nav-tabs.nav-justified > li > a {
  margin-right: 0;
  border-radius: 2px;
}
.nav-tabs.nav-justified > .active > a,
.nav-tabs.nav-justified > .active > a:hover,
.nav-tabs.nav-justified > .active > a:focus {
  border: 1px solid #ddd;
}
@media (min-width: 768px) {
  .nav-tabs.nav-justified > li > a {
    border-bottom: 1px solid #ddd;
    border-radius: 2px 2px 0 0;
  }
  .nav-tabs.nav-justified > .active > a,
  .nav-tabs.nav-justified > .active > a:hover,
  .nav-tabs.nav-justified > .active > a:focus {
    border-bottom-color: #fff;
  }
}
.nav-pills > li {
  float: left;
}
.nav-pills > li > a {
  border-radius: 2px;
}
.nav-pills > li + li {
  margin-left: 2px;
}
.nav-pills > li.active > a,
.nav-pills > li.active > a:hover,
.nav-pills > li.active > a:focus {
  color: #fff;
  background-color: #337ab7;
}
.nav-stacked > li {
  float: none;
}
.nav-stacked > li + li {
  margin-top: 2px;
  margin-left: 0;
}
.nav-justified {
  width: 100%;
}
.nav-justified > li {
  float: none;
}
.nav-justified > li > a {
  text-align: center;
  margin-bottom: 5px;
}
.nav-justified > .dropdown .dropdown-menu {
  top: auto;
  left: auto;
}
@media (min-width: 768px) {
  .nav-justified > li {
    display: table-cell;
    width: 1%;
  }
  .nav-justified > li > a {
    margin-bottom: 0;
  }
}
.nav-tabs-justified {
  border-bottom: 0;
}
.nav-tabs-justified > li > a {
  margin-right: 0;
  border-radius: 2px;
}
.nav-tabs-justified > .active > a,
.nav-tabs-justified > .active > a:hover,
.nav-tabs-justified > .active > a:focus {
  border: 1px solid #ddd;
}
@media (min-width: 768px) {
  .nav-tabs-justified > li > a {
    border-bottom: 1px solid #ddd;
    border-radius: 2px 2px 0 0;
  }
  .nav-tabs-justified > .active > a,
  .nav-tabs-justified > .active > a:hover,
  .nav-tabs-justified > .active > a:focus {
    border-bottom-color: #fff;
  }
}
.tab-content > .tab-pane {
  display: none;
}
.tab-content > .active {
  display: block;
}
.nav-tabs .dropdown-menu {
  margin-top: -1px;
  border-top-right-radius: 0;
  border-top-left-radius: 0;
}
.navbar {
  position: relative;
  min-height: 30px;
  margin-bottom: 18px;
  border: 1px solid transparent;
}
@media (min-width: 541px) {
  .navbar {
    border-radius: 2px;
  }
}
@media (min-width: 541px) {
  .navbar-header {
    float: left;
  }
}
.navbar-collapse {
  overflow-x: visible;
  padding-right: 0px;
  padding-left: 0px;
  border-top: 1px solid transparent;
  box-shadow: inset 0 1px 0 rgba(255, 255, 255, 0.1);
  -webkit-overflow-scrolling: touch;
}
.navbar-collapse.in {
  overflow-y: auto;
}
@media (min-width: 541px) {
  .navbar-collapse {
    width: auto;
    border-top: 0;
    box-shadow: none;
  }
  .navbar-collapse.collapse {
    display: block !important;
    height: auto !important;
    padding-bottom: 0;
    overflow: visible !important;
  }
  .navbar-collapse.in {
    overflow-y: visible;
  }
  .navbar-fixed-top .navbar-collapse,
  .navbar-static-top .navbar-collapse,
  .navbar-fixed-bottom .navbar-collapse {
    padding-left: 0;
    padding-right: 0;
  }
}
.navbar-fixed-top .navbar-collapse,
.navbar-fixed-bottom .navbar-collapse {
  max-height: 340px;
}
@media (max-device-width: 540px) and (orientation: landscape) {
  .navbar-fixed-top .navbar-collapse,
  .navbar-fixed-bottom .navbar-collapse {
    max-height: 200px;
  }
}
.container > .navbar-header,
.container-fluid > .navbar-header,
.container > .navbar-collapse,
.container-fluid > .navbar-collapse {
  margin-right: 0px;
  margin-left: 0px;
}
@media (min-width: 541px) {
  .container > .navbar-header,
  .container-fluid > .navbar-header,
  .container > .navbar-collapse,
  .container-fluid > .navbar-collapse {
    margin-right: 0;
    margin-left: 0;
  }
}
.navbar-static-top {
  z-index: 1000;
  border-width: 0 0 1px;
}
@media (min-width: 541px) {
  .navbar-static-top {
    border-radius: 0;
  }
}
.navbar-fixed-top,
.navbar-fixed-bottom {
  position: fixed;
  right: 0;
  left: 0;
  z-index: 1030;
}
@media (min-width: 541px) {
  .navbar-fixed-top,
  .navbar-fixed-bottom {
    border-radius: 0;
  }
}
.navbar-fixed-top {
  top: 0;
  border-width: 0 0 1px;
}
.navbar-fixed-bottom {
  bottom: 0;
  margin-bottom: 0;
  border-width: 1px 0 0;
}
.navbar-brand {
  float: left;
  padding: 6px 0px;
  font-size: 17px;
  line-height: 18px;
  height: 30px;
}
.navbar-brand:hover,
.navbar-brand:focus {
  text-decoration: none;
}
.navbar-brand > img {
  display: block;
}
@media (min-width: 541px) {
  .navbar > .container .navbar-brand,
  .navbar > .container-fluid .navbar-brand {
    margin-left: 0px;
  }
}
.navbar-toggle {
  position: relative;
  float: right;
  margin-right: 0px;
  padding: 9px 10px;
  margin-top: -2px;
  margin-bottom: -2px;
  background-color: transparent;
  background-image: none;
  border: 1px solid transparent;
  border-radius: 2px;
}
.navbar-toggle:focus {
  outline: 0;
}
.navbar-toggle .icon-bar {
  display: block;
  width: 22px;
  height: 2px;
  border-radius: 1px;
}
.navbar-toggle .icon-bar + .icon-bar {
  margin-top: 4px;
}
@media (min-width: 541px) {
  .navbar-toggle {
    display: none;
  }
}
.navbar-nav {
  margin: 3px 0px;
}
.navbar-nav > li > a {
  padding-top: 10px;
  padding-bottom: 10px;
  line-height: 18px;
}
@media (max-width: 540px) {
  .navbar-nav .open .dropdown-menu {
    position: static;
    float: none;
    width: auto;
    margin-top: 0;
    background-color: transparent;
    border: 0;
    box-shadow: none;
  }
  .navbar-nav .open .dropdown-menu > li > a,
  .navbar-nav .open .dropdown-menu .dropdown-header {
    padding: 5px 15px 5px 25px;
  }
  .navbar-nav .open .dropdown-menu > li > a {
    line-height: 18px;
  }
  .navbar-nav .open .dropdown-menu > li > a:hover,
  .navbar-nav .open .dropdown-menu > li > a:focus {
    background-image: none;
  }
}
@media (min-width: 541px) {
  .navbar-nav {
    float: left;
    margin: 0;
  }
  .navbar-nav > li {
    float: left;
  }
  .navbar-nav > li > a {
    padding-top: 6px;
    padding-bottom: 6px;
  }
}
.navbar-form {
  margin-left: 0px;
  margin-right: 0px;
  padding: 10px 0px;
  border-top: 1px solid transparent;
  border-bottom: 1px solid transparent;
  -webkit-box-shadow: inset 0 1px 0 rgba(255, 255, 255, 0.1), 0 1px 0 rgba(255, 255, 255, 0.1);
  box-shadow: inset 0 1px 0 rgba(255, 255, 255, 0.1), 0 1px 0 rgba(255, 255, 255, 0.1);
  margin-top: -1px;
  margin-bottom: -1px;
}
@media (min-width: 768px) {
  .navbar-form .form-group {
    display: inline-block;
    margin-bottom: 0;
    vertical-align: middle;
  }
  .navbar-form .form-control {
    display: inline-block;
    width: auto;
    vertical-align: middle;
  }
  .navbar-form .form-control-static {
    display: inline-block;
  }
  .navbar-form .input-group {
    display: inline-table;
    vertical-align: middle;
  }
  .navbar-form .input-group .input-group-addon,
  .navbar-form .input-group .input-group-btn,
  .navbar-form .input-group .form-control {
    width: auto;
  }
  .navbar-form .input-group > .form-control {
    width: 100%;
  }
  .navbar-form .control-label {
    margin-bottom: 0;
    vertical-align: middle;
  }
  .navbar-form .radio,
  .navbar-form .checkbox {
    display: inline-block;
    margin-top: 0;
    margin-bottom: 0;
    vertical-align: middle;
  }
  .navbar-form .radio label,
  .navbar-form .checkbox label {
    padding-left: 0;
  }
  .navbar-form .radio input[type="radio"],
  .navbar-form .checkbox input[type="checkbox"] {
    position: relative;
    margin-left: 0;
  }
  .navbar-form .has-feedback .form-control-feedback {
    top: 0;
  }
}
@media (max-width: 540px) {
  .navbar-form .form-group {
    margin-bottom: 5px;
  }
  .navbar-form .form-group:last-child {
    margin-bottom: 0;
  }
}
@media (min-width: 541px) {
  .navbar-form {
    width: auto;
    border: 0;
    margin-left: 0;
    margin-right: 0;
    padding-top: 0;
    padding-bottom: 0;
    -webkit-box-shadow: none;
    box-shadow: none;
  }
}
.navbar-nav > li > .dropdown-menu {
  margin-top: 0;
  border-top-right-radius: 0;
  border-top-left-radius: 0;
}
.navbar-fixed-bottom .navbar-nav > li > .dropdown-menu {
  margin-bottom: 0;
  border-top-right-radius: 2px;
  border-top-left-radius: 2px;
  border-bottom-right-radius: 0;
  border-bottom-left-radius: 0;
}
.navbar-btn {
  margin-top: -1px;
  margin-bottom: -1px;
}
.navbar-btn.btn-sm {
  margin-top: 0px;
  margin-bottom: 0px;
}
.navbar-btn.btn-xs {
  margin-top: 4px;
  margin-bottom: 4px;
}
.navbar-text {
  margin-top: 6px;
  margin-bottom: 6px;
}
@media (min-width: 541px) {
  .navbar-text {
    float: left;
    margin-left: 0px;
    margin-right: 0px;
  }
}
@media (min-width: 541px) {
  .navbar-left {
    float: left !important;
    float: left;
  }
  .navbar-right {
    float: right !important;
    float: right;
    margin-right: 0px;
  }
  .navbar-right ~ .navbar-right {
    margin-right: 0;
  }
}
.navbar-default {
  background-color: #f8f8f8;
  border-color: #e7e7e7;
}
.navbar-default .navbar-brand {
  color: #777;
}
.navbar-default .navbar-brand:hover,
.navbar-default .navbar-brand:focus {
  color: #5e5e5e;
  background-color: transparent;
}
.navbar-default .navbar-text {
  color: #777;
}
.navbar-default .navbar-nav > li > a {
  color: #777;
}
.navbar-default .navbar-nav > li > a:hover,
.navbar-default .navbar-nav > li > a:focus {
  color: #333;
  background-color: transparent;
}
.navbar-default .navbar-nav > .active > a,
.navbar-default .navbar-nav > .active > a:hover,
.navbar-default .navbar-nav > .active > a:focus {
  color: #555;
  background-color: #e7e7e7;
}
.navbar-default .navbar-nav > .disabled > a,
.navbar-default .navbar-nav > .disabled > a:hover,
.navbar-default .navbar-nav > .disabled > a:focus {
  color: #ccc;
  background-color: transparent;
}
.navbar-default .navbar-toggle {
  border-color: #ddd;
}
.navbar-default .navbar-toggle:hover,
.navbar-default .navbar-toggle:focus {
  background-color: #ddd;
}
.navbar-default .navbar-toggle .icon-bar {
  background-color: #888;
}
.navbar-default .navbar-collapse,
.navbar-default .navbar-form {
  border-color: #e7e7e7;
}
.navbar-default .navbar-nav > .open > a,
.navbar-default .navbar-nav > .open > a:hover,
.navbar-default .navbar-nav > .open > a:focus {
  background-color: #e7e7e7;
  color: #555;
}
@media (max-width: 540px) {
  .navbar-default .navbar-nav .open .dropdown-menu > li > a {
    color: #777;
  }
  .navbar-default .navbar-nav .open .dropdown-menu > li > a:hover,
  .navbar-default .navbar-nav .open .dropdown-menu > li > a:focus {
    color: #333;
    background-color: transparent;
  }
  .navbar-default .navbar-nav .open .dropdown-menu > .active > a,
  .navbar-default .navbar-nav .open .dropdown-menu > .active > a:hover,
  .navbar-default .navbar-nav .open .dropdown-menu > .active > a:focus {
    color: #555;
    background-color: #e7e7e7;
  }
  .navbar-default .navbar-nav .open .dropdown-menu > .disabled > a,
  .navbar-default .navbar-nav .open .dropdown-menu > .disabled > a:hover,
  .navbar-default .navbar-nav .open .dropdown-menu > .disabled > a:focus {
    color: #ccc;
    background-color: transparent;
  }
}
.navbar-default .navbar-link {
  color: #777;
}
.navbar-default .navbar-link:hover {
  color: #333;
}
.navbar-default .btn-link {
  color: #777;
}
.navbar-default .btn-link:hover,
.navbar-default .btn-link:focus {
  color: #333;
}
.navbar-default .btn-link[disabled]:hover,
fieldset[disabled] .navbar-default .btn-link:hover,
.navbar-default .btn-link[disabled]:focus,
fieldset[disabled] .navbar-default .btn-link:focus {
  color: #ccc;
}
.navbar-inverse {
  background-color: #222;
  border-color: #080808;
}
.navbar-inverse .navbar-brand {
  color: #9d9d9d;
}
.navbar-inverse .navbar-brand:hover,
.navbar-inverse .navbar-brand:focus {
  color: #fff;
  background-color: transparent;
}
.navbar-inverse .navbar-text {
  color: #9d9d9d;
}
.navbar-inverse .navbar-nav > li > a {
  color: #9d9d9d;
}
.navbar-inverse .navbar-nav > li > a:hover,
.navbar-inverse .navbar-nav > li > a:focus {
  color: #fff;
  background-color: transparent;
}
.navbar-inverse .navbar-nav > .active > a,
.navbar-inverse .navbar-nav > .active > a:hover,
.navbar-inverse .navbar-nav > .active > a:focus {
  color: #fff;
  background-color: #080808;
}
.navbar-inverse .navbar-nav > .disabled > a,
.navbar-inverse .navbar-nav > .disabled > a:hover,
.navbar-inverse .navbar-nav > .disabled > a:focus {
  color: #444;
  background-color: transparent;
}
.navbar-inverse .navbar-toggle {
  border-color: #333;
}
.navbar-inverse .navbar-toggle:hover,
.navbar-inverse .navbar-toggle:focus {
  background-color: #333;
}
.navbar-inverse .navbar-toggle .icon-bar {
  background-color: #fff;
}
.navbar-inverse .navbar-collapse,
.navbar-inverse .navbar-form {
  border-color: #101010;
}
.navbar-inverse .navbar-nav > .open > a,
.navbar-inverse .navbar-nav > .open > a:hover,
.navbar-inverse .navbar-nav > .open > a:focus {
  background-color: #080808;
  color: #fff;
}
@media (max-width: 540px) {
  .navbar-inverse .navbar-nav .open .dropdown-menu > .dropdown-header {
    border-color: #080808;
  }
  .navbar-inverse .navbar-nav .open .dropdown-menu .divider {
    background-color: #080808;
  }
  .navbar-inverse .navbar-nav .open .dropdown-menu > li > a {
    color: #9d9d9d;
  }
  .navbar-inverse .navbar-nav .open .dropdown-menu > li > a:hover,
  .navbar-inverse .navbar-nav .open .dropdown-menu > li > a:focus {
    color: #fff;
    background-color: transparent;
  }
  .navbar-inverse .navbar-nav .open .dropdown-menu > .active > a,
  .navbar-inverse .navbar-nav .open .dropdown-menu > .active > a:hover,
  .navbar-inverse .navbar-nav .open .dropdown-menu > .active > a:focus {
    color: #fff;
    background-color: #080808;
  }
  .navbar-inverse .navbar-nav .open .dropdown-menu > .disabled > a,
  .navbar-inverse .navbar-nav .open .dropdown-menu > .disabled > a:hover,
  .navbar-inverse .navbar-nav .open .dropdown-menu > .disabled > a:focus {
    color: #444;
    background-color: transparent;
  }
}
.navbar-inverse .navbar-link {
  color: #9d9d9d;
}
.navbar-inverse .navbar-link:hover {
  color: #fff;
}
.navbar-inverse .btn-link {
  color: #9d9d9d;
}
.navbar-inverse .btn-link:hover,
.navbar-inverse .btn-link:focus {
  color: #fff;
}
.navbar-inverse .btn-link[disabled]:hover,
fieldset[disabled] .navbar-inverse .btn-link:hover,
.navbar-inverse .btn-link[disabled]:focus,
fieldset[disabled] .navbar-inverse .btn-link:focus {
  color: #444;
}
.breadcrumb {
  padding: 8px 15px;
  margin-bottom: 18px;
  list-style: none;
  background-color: #f5f5f5;
  border-radius: 2px;
}
.breadcrumb > li {
  display: inline-block;
}
.breadcrumb > li + li:before {
  content: "/\00a0";
  padding: 0 5px;
  color: #5e5e5e;
}
.breadcrumb > .active {
  color: #777777;
}
.pagination {
  display: inline-block;
  padding-left: 0;
  margin: 18px 0;
  border-radius: 2px;
}
.pagination > li {
  display: inline;
}
.pagination > li > a,
.pagination > li > span {
  position: relative;
  float: left;
  padding: 6px 12px;
  line-height: 1.42857143;
  text-decoration: none;
  color: #337ab7;
  background-color: #fff;
  border: 1px solid #ddd;
  margin-left: -1px;
}
.pagination > li:first-child > a,
.pagination > li:first-child > span {
  margin-left: 0;
  border-bottom-left-radius: 2px;
  border-top-left-radius: 2px;
}
.pagination > li:last-child > a,
.pagination > li:last-child > span {
  border-bottom-right-radius: 2px;
  border-top-right-radius: 2px;
}
.pagination > li > a:hover,
.pagination > li > span:hover,
.pagination > li > a:focus,
.pagination > li > span:focus {
  z-index: 2;
  color: #23527c;
  background-color: #eeeeee;
  border-color: #ddd;
}
.pagination > .active > a,
.pagination > .active > span,
.pagination > .active > a:hover,
.pagination > .active > span:hover,
.pagination > .active > a:focus,
.pagination > .active > span:focus {
  z-index: 3;
  color: #fff;
  background-color: #337ab7;
  border-color: #337ab7;
  cursor: default;
}
.pagination > .disabled > span,
.pagination > .disabled > span:hover,
.pagination > .disabled > span:focus,
.pagination > .disabled > a,
.pagination > .disabled > a:hover,
.pagination > .disabled > a:focus {
  color: #777777;
  background-color: #fff;
  border-color: #ddd;
  cursor: not-allowed;
}
.pagination-lg > li > a,
.pagination-lg > li > span {
  padding: 10px 16px;
  font-size: 17px;
  line-height: 1.3333333;
}
.pagination-lg > li:first-child > a,
.pagination-lg > li:first-child > span {
  border-bottom-left-radius: 3px;
  border-top-left-radius: 3px;
}
.pagination-lg > li:last-child > a,
.pagination-lg > li:last-child > span {
  border-bottom-right-radius: 3px;
  border-top-right-radius: 3px;
}
.pagination-sm > li > a,
.pagination-sm > li > span {
  padding: 5px 10px;
  font-size: 12px;
  line-height: 1.5;
}
.pagination-sm > li:first-child > a,
.pagination-sm > li:first-child > span {
  border-bottom-left-radius: 1px;
  border-top-left-radius: 1px;
}
.pagination-sm > li:last-child > a,
.pagination-sm > li:last-child > span {
  border-bottom-right-radius: 1px;
  border-top-right-radius: 1px;
}
.pager {
  padding-left: 0;
  margin: 18px 0;
  list-style: none;
  text-align: center;
}
.pager li {
  display: inline;
}
.pager li > a,
.pager li > span {
  display: inline-block;
  padding: 5px 14px;
  background-color: #fff;
  border: 1px solid #ddd;
  border-radius: 15px;
}
.pager li > a:hover,
.pager li > a:focus {
  text-decoration: none;
  background-color: #eeeeee;
}
.pager .next > a,
.pager .next > span {
  float: right;
}
.pager .previous > a,
.pager .previous > span {
  float: left;
}
.pager .disabled > a,
.pager .disabled > a:hover,
.pager .disabled > a:focus,
.pager .disabled > span {
  color: #777777;
  background-color: #fff;
  cursor: not-allowed;
}
.label {
  display: inline;
  padding: .2em .6em .3em;
  font-size: 75%;
  font-weight: bold;
  line-height: 1;
  color: #fff;
  text-align: center;
  white-space: nowrap;
  vertical-align: baseline;
  border-radius: .25em;
}
a.label:hover,
a.label:focus {
  color: #fff;
  text-decoration: none;
  cursor: pointer;
}
.label:empty {
  display: none;
}
.btn .label {
  position: relative;
  top: -1px;
}
.label-default {
  background-color: #777777;
}
.label-default[href]:hover,
.label-default[href]:focus {
  background-color: #5e5e5e;
}
.label-primary {
  background-color: #337ab7;
}
.label-primary[href]:hover,
.label-primary[href]:focus {
  background-color: #286090;
}
.label-success {
  background-color: #5cb85c;
}
.label-success[href]:hover,
.label-success[href]:focus {
  background-color: #449d44;
}
.label-info {
  background-color: #5bc0de;
}
.label-info[href]:hover,
.label-info[href]:focus {
  background-color: #31b0d5;
}
.label-warning {
  background-color: #f0ad4e;
}
.label-warning[href]:hover,
.label-warning[href]:focus {
  background-color: #ec971f;
}
.label-danger {
  background-color: #d9534f;
}
.label-danger[href]:hover,
.label-danger[href]:focus {
  background-color: #c9302c;
}
.badge {
  display: inline-block;
  min-width: 10px;
  padding: 3px 7px;
  font-size: 12px;
  font-weight: bold;
  color: #fff;
  line-height: 1;
  vertical-align: middle;
  white-space: nowrap;
  text-align: center;
  background-color: #777777;
  border-radius: 10px;
}
.badge:empty {
  display: none;
}
.btn .badge {
  position: relative;
  top: -1px;
}
.btn-xs .badge,
.btn-group-xs > .btn .badge {
  top: 0;
  padding: 1px 5px;
}
a.badge:hover,
a.badge:focus {
  color: #fff;
  text-decoration: none;
  cursor: pointer;
}
.list-group-item.active > .badge,
.nav-pills > .active > a > .badge {
  color: #337ab7;
  background-color: #fff;
}
.list-group-item > .badge {
  float: right;
}
.list-group-item > .badge + .badge {
  margin-right: 5px;
}
.nav-pills > li > a > .badge {
  margin-left: 3px;
}
.jumbotron {
  padding-top: 30px;
  padding-bottom: 30px;
  margin-bottom: 30px;
  color: inherit;
  background-color: #eeeeee;
}
.jumbotron h1,
.jumbotron .h1 {
  color: inherit;
}
.jumbotron p {
  margin-bottom: 15px;
  font-size: 20px;
  font-weight: 200;
}
.jumbotron > hr {
  border-top-color: #d5d5d5;
}
.container .jumbotron,
.container-fluid .jumbotron {
  border-radius: 3px;
  padding-left: 0px;
  padding-right: 0px;
}
.jumbotron .container {
  max-width: 100%;
}
@media screen and (min-width: 768px) {
  .jumbotron {
    padding-top: 48px;
    padding-bottom: 48px;
  }
  .container .jumbotron,
  .container-fluid .jumbotron {
    padding-left: 60px;
    padding-right: 60px;
  }
  .jumbotron h1,
  .jumbotron .h1 {
    font-size: 59px;
  }
}
.thumbnail {
  display: block;
  padding: 4px;
  margin-bottom: 18px;
  line-height: 1.42857143;
  background-color: #fff;
  border: 1px solid #ddd;
  border-radius: 2px;
  -webkit-transition: border 0.2s ease-in-out;
  -o-transition: border 0.2s ease-in-out;
  transition: border 0.2s ease-in-out;
}
.thumbnail > img,
.thumbnail a > img {
  margin-left: auto;
  margin-right: auto;
}
a.thumbnail:hover,
a.thumbnail:focus,
a.thumbnail.active {
  border-color: #337ab7;
}
.thumbnail .caption {
  padding: 9px;
  color: #000;
}
.alert {
  padding: 15px;
  margin-bottom: 18px;
  border: 1px solid transparent;
  border-radius: 2px;
}
.alert h4 {
  margin-top: 0;
  color: inherit;
}
.alert .alert-link {
  font-weight: bold;
}
.alert > p,
.alert > ul {
  margin-bottom: 0;
}
.alert > p + p {
  margin-top: 5px;
}
.alert-dismissable,
.alert-dismissible {
  padding-right: 35px;
}
.alert-dismissable .close,
.alert-dismissible .close {
  position: relative;
  top: -2px;
  right: -21px;
  color: inherit;
}
.alert-success {
  background-color: #dff0d8;
  border-color: #d6e9c6;
  color: #3c763d;
}
.alert-success hr {
  border-top-color: #c9e2b3;
}
.alert-success .alert-link {
  color: #2b542c;
}
.alert-info {
  background-color: #d9edf7;
  border-color: #bce8f1;
  color: #31708f;
}
.alert-info hr {
  border-top-color: #a6e1ec;
}
.alert-info .alert-link {
  color: #245269;
}
.alert-warning {
  background-color: #fcf8e3;
  border-color: #faebcc;
  color: #8a6d3b;
}
.alert-warning hr {
  border-top-color: #f7e1b5;
}
.alert-warning .alert-link {
  color: #66512c;
}
.alert-danger {
  background-color: #f2dede;
  border-color: #ebccd1;
  color: #a94442;
}
.alert-danger hr {
  border-top-color: #e4b9c0;
}
.alert-danger .alert-link {
  color: #843534;
}
@-webkit-keyframes progress-bar-stripes {
  from {
    background-position: 40px 0;
  }
  to {
    background-position: 0 0;
  }
}
@keyframes progress-bar-stripes {
  from {
    background-position: 40px 0;
  }
  to {
    background-position: 0 0;
  }
}
.progress {
  overflow: hidden;
  height: 18px;
  margin-bottom: 18px;
  background-color: #f5f5f5;
  border-radius: 2px;
  -webkit-box-shadow: inset 0 1px 2px rgba(0, 0, 0, 0.1);
  box-shadow: inset 0 1px 2px rgba(0, 0, 0, 0.1);
}
.progress-bar {
  float: left;
  width: 0%;
  height: 100%;
  font-size: 12px;
  line-height: 18px;
  color: #fff;
  text-align: center;
  background-color: #337ab7;
  -webkit-box-shadow: inset 0 -1px 0 rgba(0, 0, 0, 0.15);
  box-shadow: inset 0 -1px 0 rgba(0, 0, 0, 0.15);
  -webkit-transition: width 0.6s ease;
  -o-transition: width 0.6s ease;
  transition: width 0.6s ease;
}
.progress-striped .progress-bar,
.progress-bar-striped {
  background-image: -webkit-linear-gradient(45deg, rgba(255, 255, 255, 0.15) 25%, transparent 25%, transparent 50%, rgba(255, 255, 255, 0.15) 50%, rgba(255, 255, 255, 0.15) 75%, transparent 75%, transparent);
  background-image: -o-linear-gradient(45deg, rgba(255, 255, 255, 0.15) 25%, transparent 25%, transparent 50%, rgba(255, 255, 255, 0.15) 50%, rgba(255, 255, 255, 0.15) 75%, transparent 75%, transparent);
  background-image: linear-gradient(45deg, rgba(255, 255, 255, 0.15) 25%, transparent 25%, transparent 50%, rgba(255, 255, 255, 0.15) 50%, rgba(255, 255, 255, 0.15) 75%, transparent 75%, transparent);
  background-size: 40px 40px;
}
.progress.active .progress-bar,
.progress-bar.active {
  -webkit-animation: progress-bar-stripes 2s linear infinite;
  -o-animation: progress-bar-stripes 2s linear infinite;
  animation: progress-bar-stripes 2s linear infinite;
}
.progress-bar-success {
  background-color: #5cb85c;
}
.progress-striped .progress-bar-success {
  background-image: -webkit-linear-gradient(45deg, rgba(255, 255, 255, 0.15) 25%, transparent 25%, transparent 50%, rgba(255, 255, 255, 0.15) 50%, rgba(255, 255, 255, 0.15) 75%, transparent 75%, transparent);
  background-image: -o-linear-gradient(45deg, rgba(255, 255, 255, 0.15) 25%, transparent 25%, transparent 50%, rgba(255, 255, 255, 0.15) 50%, rgba(255, 255, 255, 0.15) 75%, transparent 75%, transparent);
  background-image: linear-gradient(45deg, rgba(255, 255, 255, 0.15) 25%, transparent 25%, transparent 50%, rgba(255, 255, 255, 0.15) 50%, rgba(255, 255, 255, 0.15) 75%, transparent 75%, transparent);
}
.progress-bar-info {
  background-color: #5bc0de;
}
.progress-striped .progress-bar-info {
  background-image: -webkit-linear-gradient(45deg, rgba(255, 255, 255, 0.15) 25%, transparent 25%, transparent 50%, rgba(255, 255, 255, 0.15) 50%, rgba(255, 255, 255, 0.15) 75%, transparent 75%, transparent);
  background-image: -o-linear-gradient(45deg, rgba(255, 255, 255, 0.15) 25%, transparent 25%, transparent 50%, rgba(255, 255, 255, 0.15) 50%, rgba(255, 255, 255, 0.15) 75%, transparent 75%, transparent);
  background-image: linear-gradient(45deg, rgba(255, 255, 255, 0.15) 25%, transparent 25%, transparent 50%, rgba(255, 255, 255, 0.15) 50%, rgba(255, 255, 255, 0.15) 75%, transparent 75%, transparent);
}
.progress-bar-warning {
  background-color: #f0ad4e;
}
.progress-striped .progress-bar-warning {
  background-image: -webkit-linear-gradient(45deg, rgba(255, 255, 255, 0.15) 25%, transparent 25%, transparent 50%, rgba(255, 255, 255, 0.15) 50%, rgba(255, 255, 255, 0.15) 75%, transparent 75%, transparent);
  background-image: -o-linear-gradient(45deg, rgba(255, 255, 255, 0.15) 25%, transparent 25%, transparent 50%, rgba(255, 255, 255, 0.15) 50%, rgba(255, 255, 255, 0.15) 75%, transparent 75%, transparent);
  background-image: linear-gradient(45deg, rgba(255, 255, 255, 0.15) 25%, transparent 25%, transparent 50%, rgba(255, 255, 255, 0.15) 50%, rgba(255, 255, 255, 0.15) 75%, transparent 75%, transparent);
}
.progress-bar-danger {
  background-color: #d9534f;
}
.progress-striped .progress-bar-danger {
  background-image: -webkit-linear-gradient(45deg, rgba(255, 255, 255, 0.15) 25%, transparent 25%, transparent 50%, rgba(255, 255, 255, 0.15) 50%, rgba(255, 255, 255, 0.15) 75%, transparent 75%, transparent);
  background-image: -o-linear-gradient(45deg, rgba(255, 255, 255, 0.15) 25%, transparent 25%, transparent 50%, rgba(255, 255, 255, 0.15) 50%, rgba(255, 255, 255, 0.15) 75%, transparent 75%, transparent);
  background-image: linear-gradient(45deg, rgba(255, 255, 255, 0.15) 25%, transparent 25%, transparent 50%, rgba(255, 255, 255, 0.15) 50%, rgba(255, 255, 255, 0.15) 75%, transparent 75%, transparent);
}
.media {
  margin-top: 15px;
}
.media:first-child {
  margin-top: 0;
}
.media,
.media-body {
  zoom: 1;
  overflow: hidden;
}
.media-body {
  width: 10000px;
}
.media-object {
  display: block;
}
.media-object.img-thumbnail {
  max-width: none;
}
.media-right,
.media > .pull-right {
  padding-left: 10px;
}
.media-left,
.media > .pull-left {
  padding-right: 10px;
}
.media-left,
.media-right,
.media-body {
  display: table-cell;
  vertical-align: top;
}
.media-middle {
  vertical-align: middle;
}
.media-bottom {
  vertical-align: bottom;
}
.media-heading {
  margin-top: 0;
  margin-bottom: 5px;
}
.media-list {
  padding-left: 0;
  list-style: none;
}
.list-group {
  margin-bottom: 20px;
  padding-left: 0;
}
.list-group-item {
  position: relative;
  display: block;
  padding: 10px 15px;
  margin-bottom: -1px;
  background-color: #fff;
  border: 1px solid #ddd;
}
.list-group-item:first-child {
  border-top-right-radius: 2px;
  border-top-left-radius: 2px;
}
.list-group-item:last-child {
  margin-bottom: 0;
  border-bottom-right-radius: 2px;
  border-bottom-left-radius: 2px;
}
a.list-group-item,
button.list-group-item {
  color: #555;
}
a.list-group-item .list-group-item-heading,
button.list-group-item .list-group-item-heading {
  color: #333;
}
a.list-group-item:hover,
button.list-group-item:hover,
a.list-group-item:focus,
button.list-group-item:focus {
  text-decoration: none;
  color: #555;
  background-color: #f5f5f5;
}
button.list-group-item {
  width: 100%;
  text-align: left;
}
.list-group-item.disabled,
.list-group-item.disabled:hover,
.list-group-item.disabled:focus {
  background-color: #eeeeee;
  color: #777777;
  cursor: not-allowed;
}
.list-group-item.disabled .list-group-item-heading,
.list-group-item.disabled:hover .list-group-item-heading,
.list-group-item.disabled:focus .list-group-item-heading {
  color: inherit;
}
.list-group-item.disabled .list-group-item-text,
.list-group-item.disabled:hover .list-group-item-text,
.list-group-item.disabled:focus .list-group-item-text {
  color: #777777;
}
.list-group-item.active,
.list-group-item.active:hover,
.list-group-item.active:focus {
  z-index: 2;
  color: #fff;
  background-color: #337ab7;
  border-color: #337ab7;
}
.list-group-item.active .list-group-item-heading,
.list-group-item.active:hover .list-group-item-heading,
.list-group-item.active:focus .list-group-item-heading,
.list-group-item.active .list-group-item-heading > small,
.list-group-item.active:hover .list-group-item-heading > small,
.list-group-item.active:focus .list-group-item-heading > small,
.list-group-item.active .list-group-item-heading > .small,
.list-group-item.active:hover .list-group-item-heading > .small,
.list-group-item.active:focus .list-group-item-heading > .small {
  color: inherit;
}
.list-group-item.active .list-group-item-text,
.list-group-item.active:hover .list-group-item-text,
.list-group-item.active:focus .list-group-item-text {
  color: #c7ddef;
}
.list-group-item-success {
  color: #3c763d;
  background-color: #dff0d8;
}
a.list-group-item-success,
button.list-group-item-success {
  color: #3c763d;
}
a.list-group-item-success .list-group-item-heading,
button.list-group-item-success .list-group-item-heading {
  color: inherit;
}
a.list-group-item-success:hover,
button.list-group-item-success:hover,
a.list-group-item-success:focus,
button.list-group-item-success:focus {
  color: #3c763d;
  background-color: #d0e9c6;
}
a.list-group-item-success.active,
button.list-group-item-success.active,
a.list-group-item-success.active:hover,
button.list-group-item-success.active:hover,
a.list-group-item-success.active:focus,
button.list-group-item-success.active:focus {
  color: #fff;
  background-color: #3c763d;
  border-color: #3c763d;
}
.list-group-item-info {
  color: #31708f;
  background-color: #d9edf7;
}
a.list-group-item-info,
button.list-group-item-info {
  color: #31708f;
}
a.list-group-item-info .list-group-item-heading,
button.list-group-item-info .list-group-item-heading {
  color: inherit;
}
a.list-group-item-info:hover,
button.list-group-item-info:hover,
a.list-group-item-info:focus,
button.list-group-item-info:focus {
  color: #31708f;
  background-color: #c4e3f3;
}
a.list-group-item-info.active,
button.list-group-item-info.active,
a.list-group-item-info.active:hover,
button.list-group-item-info.active:hover,
a.list-group-item-info.active:focus,
button.list-group-item-info.active:focus {
  color: #fff;
  background-color: #31708f;
  border-color: #31708f;
}
.list-group-item-warning {
  color: #8a6d3b;
  background-color: #fcf8e3;
}
a.list-group-item-warning,
button.list-group-item-warning {
  color: #8a6d3b;
}
a.list-group-item-warning .list-group-item-heading,
button.list-group-item-warning .list-group-item-heading {
  color: inherit;
}
a.list-group-item-warning:hover,
button.list-group-item-warning:hover,
a.list-group-item-warning:focus,
button.list-group-item-warning:focus {
  color: #8a6d3b;
  background-color: #faf2cc;
}
a.list-group-item-warning.active,
button.list-group-item-warning.active,
a.list-group-item-warning.active:hover,
button.list-group-item-warning.active:hover,
a.list-group-item-warning.active:focus,
button.list-group-item-warning.active:focus {
  color: #fff;
  background-color: #8a6d3b;
  border-color: #8a6d3b;
}
.list-group-item-danger {
  color: #a94442;
  background-color: #f2dede;
}
a.list-group-item-danger,
button.list-group-item-danger {
  color: #a94442;
}
a.list-group-item-danger .list-group-item-heading,
button.list-group-item-danger .list-group-item-heading {
  color: inherit;
}
a.list-group-item-danger:hover,
button.list-group-item-danger:hover,
a.list-group-item-danger:focus,
button.list-group-item-danger:focus {
  color: #a94442;
  background-color: #ebcccc;
}
a.list-group-item-danger.active,
button.list-group-item-danger.active,
a.list-group-item-danger.active:hover,
button.list-group-item-danger.active:hover,
a.list-group-item-danger.active:focus,
button.list-group-item-danger.active:focus {
  color: #fff;
  background-color: #a94442;
  border-color: #a94442;
}
.list-group-item-heading {
  margin-top: 0;
  margin-bottom: 5px;
}
.list-group-item-text {
  margin-bottom: 0;
  line-height: 1.3;
}
.panel {
  margin-bottom: 18px;
  background-color: #fff;
  border: 1px solid transparent;
  border-radius: 2px;
  -webkit-box-shadow: 0 1px 1px rgba(0, 0, 0, 0.05);
  box-shadow: 0 1px 1px rgba(0, 0, 0, 0.05);
}
.panel-body {
  padding: 15px;
}
.panel-heading {
  padding: 10px 15px;
  border-bottom: 1px solid transparent;
  border-top-right-radius: 1px;
  border-top-left-radius: 1px;
}
.panel-heading > .dropdown .dropdown-toggle {
  color: inherit;
}
.panel-title {
  margin-top: 0;
  margin-bottom: 0;
  font-size: 15px;
  color: inherit;
}
.panel-title > a,
.panel-title > small,
.panel-title > .small,
.panel-title > small > a,
.panel-title > .small > a {
  color: inherit;
}
.panel-footer {
  padding: 10px 15px;
  background-color: #f5f5f5;
  border-top: 1px solid #ddd;
  border-bottom-right-radius: 1px;
  border-bottom-left-radius: 1px;
}
.panel > .list-group,
.panel > .panel-collapse > .list-group {
  margin-bottom: 0;
}
.panel > .list-group .list-group-item,
.panel > .panel-collapse > .list-group .list-group-item {
  border-width: 1px 0;
  border-radius: 0;
}
.panel > .list-group:first-child .list-group-item:first-child,
.panel > .panel-collapse > .list-group:first-child .list-group-item:first-child {
  border-top: 0;
  border-top-right-radius: 1px;
  border-top-left-radius: 1px;
}
.panel > .list-group:last-child .list-group-item:last-child,
.panel > .panel-collapse > .list-group:last-child .list-group-item:last-child {
  border-bottom: 0;
  border-bottom-right-radius: 1px;
  border-bottom-left-radius: 1px;
}
.panel > .panel-heading + .panel-collapse > .list-group .list-group-item:first-child {
  border-top-right-radius: 0;
  border-top-left-radius: 0;
}
.panel-heading + .list-group .list-group-item:first-child {
  border-top-width: 0;
}
.list-group + .panel-footer {
  border-top-width: 0;
}
.panel > .table,
.panel > .table-responsive > .table,
.panel > .panel-collapse > .table {
  margin-bottom: 0;
}
.panel > .table caption,
.panel > .table-responsive > .table caption,
.panel > .panel-collapse > .table caption {
  padding-left: 15px;
  padding-right: 15px;
}
.panel > .table:first-child,
.panel > .table-responsive:first-child > .table:first-child {
  border-top-right-radius: 1px;
  border-top-left-radius: 1px;
}
.panel > .table:first-child > thead:first-child > tr:first-child,
.panel > .table-responsive:first-child > .table:first-child > thead:first-child > tr:first-child,
.panel > .table:first-child > tbody:first-child > tr:first-child,
.panel > .table-responsive:first-child > .table:first-child > tbody:first-child > tr:first-child {
  border-top-left-radius: 1px;
  border-top-right-radius: 1px;
}
.panel > .table:first-child > thead:first-child > tr:first-child td:first-child,
.panel > .table-responsive:first-child > .table:first-child > thead:first-child > tr:first-child td:first-child,
.panel > .table:first-child > tbody:first-child > tr:first-child td:first-child,
.panel > .table-responsive:first-child > .table:first-child > tbody:first-child > tr:first-child td:first-child,
.panel > .table:first-child > thead:first-child > tr:first-child th:first-child,
.panel > .table-responsive:first-child > .table:first-child > thead:first-child > tr:first-child th:first-child,
.panel > .table:first-child > tbody:first-child > tr:first-child th:first-child,
.panel > .table-responsive:first-child > .table:first-child > tbody:first-child > tr:first-child th:first-child {
  border-top-left-radius: 1px;
}
.panel > .table:first-child > thead:first-child > tr:first-child td:last-child,
.panel > .table-responsive:first-child > .table:first-child > thead:first-child > tr:first-child td:last-child,
.panel > .table:first-child > tbody:first-child > tr:first-child td:last-child,
.panel > .table-responsive:first-child > .table:first-child > tbody:first-child > tr:first-child td:last-child,
.panel > .table:first-child > thead:first-child > tr:first-child th:last-child,
.panel > .table-responsive:first-child > .table:first-child > thead:first-child > tr:first-child th:last-child,
.panel > .table:first-child > tbody:first-child > tr:first-child th:last-child,
.panel > .table-responsive:first-child > .table:first-child > tbody:first-child > tr:first-child th:last-child {
  border-top-right-radius: 1px;
}
.panel > .table:last-child,
.panel > .table-responsive:last-child > .table:last-child {
  border-bottom-right-radius: 1px;
  border-bottom-left-radius: 1px;
}
.panel > .table:last-child > tbody:last-child > tr:last-child,
.panel > .table-responsive:last-child > .table:last-child > tbody:last-child > tr:last-child,
.panel > .table:last-child > tfoot:last-child > tr:last-child,
.panel > .table-responsive:last-child > .table:last-child > tfoot:last-child > tr:last-child {
  border-bottom-left-radius: 1px;
  border-bottom-right-radius: 1px;
}
.panel > .table:last-child > tbody:last-child > tr:last-child td:first-child,
.panel > .table-responsive:last-child > .table:last-child > tbody:last-child > tr:last-child td:first-child,
.panel > .table:last-child > tfoot:last-child > tr:last-child td:first-child,
.panel > .table-responsive:last-child > .table:last-child > tfoot:last-child > tr:last-child td:first-child,
.panel > .table:last-child > tbody:last-child > tr:last-child th:first-child,
.panel > .table-responsive:last-child > .table:last-child > tbody:last-child > tr:last-child th:first-child,
.panel > .table:last-child > tfoot:last-child > tr:last-child th:first-child,
.panel > .table-responsive:last-child > .table:last-child > tfoot:last-child > tr:last-child th:first-child {
  border-bottom-left-radius: 1px;
}
.panel > .table:last-child > tbody:last-child > tr:last-child td:last-child,
.panel > .table-responsive:last-child > .table:last-child > tbody:last-child > tr:last-child td:last-child,
.panel > .table:last-child > tfoot:last-child > tr:last-child td:last-child,
.panel > .table-responsive:last-child > .table:last-child > tfoot:last-child > tr:last-child td:last-child,
.panel > .table:last-child > tbody:last-child > tr:last-child th:last-child,
.panel > .table-responsive:last-child > .table:last-child > tbody:last-child > tr:last-child th:last-child,
.panel > .table:last-child > tfoot:last-child > tr:last-child th:last-child,
.panel > .table-responsive:last-child > .table:last-child > tfoot:last-child > tr:last-child th:last-child {
  border-bottom-right-radius: 1px;
}
.panel > .panel-body + .table,
.panel > .panel-body + .table-responsive,
.panel > .table + .panel-body,
.panel > .table-responsive + .panel-body {
  border-top: 1px solid #ddd;
}
.panel > .table > tbody:first-child > tr:first-child th,
.panel > .table > tbody:first-child > tr:first-child td {
  border-top: 0;
}
.panel > .table-bordered,
.panel > .table-responsive > .table-bordered {
  border: 0;
}
.panel > .table-bordered > thead > tr > th:first-child,
.panel > .table-responsive > .table-bordered > thead > tr > th:first-child,
.panel > .table-bordered > tbody > tr > th:first-child,
.panel > .table-responsive > .table-bordered > tbody > tr > th:first-child,
.panel > .table-bordered > tfoot > tr > th:first-child,
.panel > .table-responsive > .table-bordered > tfoot > tr > th:first-child,
.panel > .table-bordered > thead > tr > td:first-child,
.panel > .table-responsive > .table-bordered > thead > tr > td:first-child,
.panel > .table-bordered > tbody > tr > td:first-child,
.panel > .table-responsive > .table-bordered > tbody > tr > td:first-child,
.panel > .table-bordered > tfoot > tr > td:first-child,
.panel > .table-responsive > .table-bordered > tfoot > tr > td:first-child {
  border-left: 0;
}
.panel > .table-bordered > thead > tr > th:last-child,
.panel > .table-responsive > .table-bordered > thead > tr > th:last-child,
.panel > .table-bordered > tbody > tr > th:last-child,
.panel > .table-responsive > .table-bordered > tbody > tr > th:last-child,
.panel > .table-bordered > tfoot > tr > th:last-child,
.panel > .table-responsive > .table-bordered > tfoot > tr > th:last-child,
.panel > .table-bordered > thead > tr > td:last-child,
.panel > .table-responsive > .table-bordered > thead > tr > td:last-child,
.panel > .table-bordered > tbody > tr > td:last-child,
.panel > .table-responsive > .table-bordered > tbody > tr > td:last-child,
.panel > .table-bordered > tfoot > tr > td:last-child,
.panel > .table-responsive > .table-bordered > tfoot > tr > td:last-child {
  border-right: 0;
}
.panel > .table-bordered > thead > tr:first-child > td,
.panel > .table-responsive > .table-bordered > thead > tr:first-child > td,
.panel > .table-bordered > tbody > tr:first-child > td,
.panel > .table-responsive > .table-bordered > tbody > tr:first-child > td,
.panel > .table-bordered > thead > tr:first-child > th,
.panel > .table-responsive > .table-bordered > thead > tr:first-child > th,
.panel > .table-bordered > tbody > tr:first-child > th,
.panel > .table-responsive > .table-bordered > tbody > tr:first-child > th {
  border-bottom: 0;
}
.panel > .table-bordered > tbody > tr:last-child > td,
.panel > .table-responsive > .table-bordered > tbody > tr:last-child > td,
.panel > .table-bordered > tfoot > tr:last-child > td,
.panel > .table-responsive > .table-bordered > tfoot > tr:last-child > td,
.panel > .table-bordered > tbody > tr:last-child > th,
.panel > .table-responsive > .table-bordered > tbody > tr:last-child > th,
.panel > .table-bordered > tfoot > tr:last-child > th,
.panel > .table-responsive > .table-bordered > tfoot > tr:last-child > th {
  border-bottom: 0;
}
.panel > .table-responsive {
  border: 0;
  margin-bottom: 0;
}
.panel-group {
  margin-bottom: 18px;
}
.panel-group .panel {
  margin-bottom: 0;
  border-radius: 2px;
}
.panel-group .panel + .panel {
  margin-top: 5px;
}
.panel-group .panel-heading {
  border-bottom: 0;
}
.panel-group .panel-heading + .panel-collapse > .panel-body,
.panel-group .panel-heading + .panel-collapse > .list-group {
  border-top: 1px solid #ddd;
}
.panel-group .panel-footer {
  border-top: 0;
}
.panel-group .panel-footer + .panel-collapse .panel-body {
  border-bottom: 1px solid #ddd;
}
.panel-default {
  border-color: #ddd;
}
.panel-default > .panel-heading {
  color: #333333;
  background-color: #f5f5f5;
  border-color: #ddd;
}
.panel-default > .panel-heading + .panel-collapse > .panel-body {
  border-top-color: #ddd;
}
.panel-default > .panel-heading .badge {
  color: #f5f5f5;
  background-color: #333333;
}
.panel-default > .panel-footer + .panel-collapse > .panel-body {
  border-bottom-color: #ddd;
}
.panel-primary {
  border-color: #337ab7;
}
.panel-primary > .panel-heading {
  color: #fff;
  background-color: #337ab7;
  border-color: #337ab7;
}
.panel-primary > .panel-heading + .panel-collapse > .panel-body {
  border-top-color: #337ab7;
}
.panel-primary > .panel-heading .badge {
  color: #337ab7;
  background-color: #fff;
}
.panel-primary > .panel-footer + .panel-collapse > .panel-body {
  border-bottom-color: #337ab7;
}
.panel-success {
  border-color: #d6e9c6;
}
.panel-success > .panel-heading {
  color: #3c763d;
  background-color: #dff0d8;
  border-color: #d6e9c6;
}
.panel-success > .panel-heading + .panel-collapse > .panel-body {
  border-top-color: #d6e9c6;
}
.panel-success > .panel-heading .badge {
  color: #dff0d8;
  background-color: #3c763d;
}
.panel-success > .panel-footer + .panel-collapse > .panel-body {
  border-bottom-color: #d6e9c6;
}
.panel-info {
  border-color: #bce8f1;
}
.panel-info > .panel-heading {
  color: #31708f;
  background-color: #d9edf7;
  border-color: #bce8f1;
}
.panel-info > .panel-heading + .panel-collapse > .panel-body {
  border-top-color: #bce8f1;
}
.panel-info > .panel-heading .badge {
  color: #d9edf7;
  background-color: #31708f;
}
.panel-info > .panel-footer + .panel-collapse > .panel-body {
  border-bottom-color: #bce8f1;
}
.panel-warning {
  border-color: #faebcc;
}
.panel-warning > .panel-heading {
  color: #8a6d3b;
  background-color: #fcf8e3;
  border-color: #faebcc;
}
.panel-warning > .panel-heading + .panel-collapse > .panel-body {
  border-top-color: #faebcc;
}
.panel-warning > .panel-heading .badge {
  color: #fcf8e3;
  background-color: #8a6d3b;
}
.panel-warning > .panel-footer + .panel-collapse > .panel-body {
  border-bottom-color: #faebcc;
}
.panel-danger {
  border-color: #ebccd1;
}
.panel-danger > .panel-heading {
  color: #a94442;
  background-color: #f2dede;
  border-color: #ebccd1;
}
.panel-danger > .panel-heading + .panel-collapse > .panel-body {
  border-top-color: #ebccd1;
}
.panel-danger > .panel-heading .badge {
  color: #f2dede;
  background-color: #a94442;
}
.panel-danger > .panel-footer + .panel-collapse > .panel-body {
  border-bottom-color: #ebccd1;
}
.embed-responsive {
  position: relative;
  display: block;
  height: 0;
  padding: 0;
  overflow: hidden;
}
.embed-responsive .embed-responsive-item,
.embed-responsive iframe,
.embed-responsive embed,
.embed-responsive object,
.embed-responsive video {
  position: absolute;
  top: 0;
  left: 0;
  bottom: 0;
  height: 100%;
  width: 100%;
  border: 0;
}
.embed-responsive-16by9 {
  padding-bottom: 56.25%;
}
.embed-responsive-4by3 {
  padding-bottom: 75%;
}
.well {
  min-height: 20px;
  padding: 19px;
  margin-bottom: 20px;
  background-color: #f5f5f5;
  border: 1px solid #e3e3e3;
  border-radius: 2px;
  -webkit-box-shadow: inset 0 1px 1px rgba(0, 0, 0, 0.05);
  box-shadow: inset 0 1px 1px rgba(0, 0, 0, 0.05);
}
.well blockquote {
  border-color: #ddd;
  border-color: rgba(0, 0, 0, 0.15);
}
.well-lg {
  padding: 24px;
  border-radius: 3px;
}
.well-sm {
  padding: 9px;
  border-radius: 1px;
}
.close {
  float: right;
  font-size: 19.5px;
  font-weight: bold;
  line-height: 1;
  color: #000;
  text-shadow: 0 1px 0 #fff;
  opacity: 0.2;
  filter: alpha(opacity=20);
}
.close:hover,
.close:focus {
  color: #000;
  text-decoration: none;
  cursor: pointer;
  opacity: 0.5;
  filter: alpha(opacity=50);
}
button.close {
  padding: 0;
  cursor: pointer;
  background: transparent;
  border: 0;
  -webkit-appearance: none;
}
.modal-open {
  overflow: hidden;
}
.modal {
  display: none;
  overflow: hidden;
  position: fixed;
  top: 0;
  right: 0;
  bottom: 0;
  left: 0;
  z-index: 1050;
  -webkit-overflow-scrolling: touch;
  outline: 0;
}
.modal.fade .modal-dialog {
  -webkit-transform: translate(0, -25%);
  -ms-transform: translate(0, -25%);
  -o-transform: translate(0, -25%);
  transform: translate(0, -25%);
  -webkit-transition: -webkit-transform 0.3s ease-out;
  -moz-transition: -moz-transform 0.3s ease-out;
  -o-transition: -o-transform 0.3s ease-out;
  transition: transform 0.3s ease-out;
}
.modal.in .modal-dialog {
  -webkit-transform: translate(0, 0);
  -ms-transform: translate(0, 0);
  -o-transform: translate(0, 0);
  transform: translate(0, 0);
}
.modal-open .modal {
  overflow-x: hidden;
  overflow-y: auto;
}
.modal-dialog {
  position: relative;
  width: auto;
  margin: 10px;
}
.modal-content {
  position: relative;
  background-color: #fff;
  border: 1px solid #999;
  border: 1px solid rgba(0, 0, 0, 0.2);
  border-radius: 3px;
  -webkit-box-shadow: 0 3px 9px rgba(0, 0, 0, 0.5);
  box-shadow: 0 3px 9px rgba(0, 0, 0, 0.5);
  background-clip: padding-box;
  outline: 0;
}
.modal-backdrop {
  position: fixed;
  top: 0;
  right: 0;
  bottom: 0;
  left: 0;
  z-index: 1040;
  background-color: #000;
}
.modal-backdrop.fade {
  opacity: 0;
  filter: alpha(opacity=0);
}
.modal-backdrop.in {
  opacity: 0.5;
  filter: alpha(opacity=50);
}
.modal-header {
  padding: 15px;
  border-bottom: 1px solid #e5e5e5;
}
.modal-header .close {
  margin-top: -2px;
}
.modal-title {
  margin: 0;
  line-height: 1.42857143;
}
.modal-body {
  position: relative;
  padding: 15px;
}
.modal-footer {
  padding: 15px;
  text-align: right;
  border-top: 1px solid #e5e5e5;
}
.modal-footer .btn + .btn {
  margin-left: 5px;
  margin-bottom: 0;
}
.modal-footer .btn-group .btn + .btn {
  margin-left: -1px;
}
.modal-footer .btn-block + .btn-block {
  margin-left: 0;
}
.modal-scrollbar-measure {
  position: absolute;
  top: -9999px;
  width: 50px;
  height: 50px;
  overflow: scroll;
}
@media (min-width: 768px) {
  .modal-dialog {
    width: 600px;
    margin: 30px auto;
  }
  .modal-content {
    -webkit-box-shadow: 0 5px 15px rgba(0, 0, 0, 0.5);
    box-shadow: 0 5px 15px rgba(0, 0, 0, 0.5);
  }
  .modal-sm {
    width: 300px;
  }
}
@media (min-width: 992px) {
  .modal-lg {
    width: 900px;
  }
}
.tooltip {
  position: absolute;
  z-index: 1070;
  display: block;
  font-family: "Helvetica Neue", Helvetica, Arial, sans-serif;
  font-style: normal;
  font-weight: normal;
  letter-spacing: normal;
  line-break: auto;
  line-height: 1.42857143;
  text-align: left;
  text-align: start;
  text-decoration: none;
  text-shadow: none;
  text-transform: none;
  white-space: normal;
  word-break: normal;
  word-spacing: normal;
  word-wrap: normal;
  font-size: 12px;
  opacity: 0;
  filter: alpha(opacity=0);
}
.tooltip.in {
  opacity: 0.9;
  filter: alpha(opacity=90);
}
.tooltip.top {
  margin-top: -3px;
  padding: 5px 0;
}
.tooltip.right {
  margin-left: 3px;
  padding: 0 5px;
}
.tooltip.bottom {
  margin-top: 3px;
  padding: 5px 0;
}
.tooltip.left {
  margin-left: -3px;
  padding: 0 5px;
}
.tooltip-inner {
  max-width: 200px;
  padding: 3px 8px;
  color: #fff;
  text-align: center;
  background-color: #000;
  border-radius: 2px;
}
.tooltip-arrow {
  position: absolute;
  width: 0;
  height: 0;
  border-color: transparent;
  border-style: solid;
}
.tooltip.top .tooltip-arrow {
  bottom: 0;
  left: 50%;
  margin-left: -5px;
  border-width: 5px 5px 0;
  border-top-color: #000;
}
.tooltip.top-left .tooltip-arrow {
  bottom: 0;
  right: 5px;
  margin-bottom: -5px;
  border-width: 5px 5px 0;
  border-top-color: #000;
}
.tooltip.top-right .tooltip-arrow {
  bottom: 0;
  left: 5px;
  margin-bottom: -5px;
  border-width: 5px 5px 0;
  border-top-color: #000;
}
.tooltip.right .tooltip-arrow {
  top: 50%;
  left: 0;
  margin-top: -5px;
  border-width: 5px 5px 5px 0;
  border-right-color: #000;
}
.tooltip.left .tooltip-arrow {
  top: 50%;
  right: 0;
  margin-top: -5px;
  border-width: 5px 0 5px 5px;
  border-left-color: #000;
}
.tooltip.bottom .tooltip-arrow {
  top: 0;
  left: 50%;
  margin-left: -5px;
  border-width: 0 5px 5px;
  border-bottom-color: #000;
}
.tooltip.bottom-left .tooltip-arrow {
  top: 0;
  right: 5px;
  margin-top: -5px;
  border-width: 0 5px 5px;
  border-bottom-color: #000;
}
.tooltip.bottom-right .tooltip-arrow {
  top: 0;
  left: 5px;
  margin-top: -5px;
  border-width: 0 5px 5px;
  border-bottom-color: #000;
}
.popover {
  position: absolute;
  top: 0;
  left: 0;
  z-index: 1060;
  display: none;
  max-width: 276px;
  padding: 1px;
  font-family: "Helvetica Neue", Helvetica, Arial, sans-serif;
  font-style: normal;
  font-weight: normal;
  letter-spacing: normal;
  line-break: auto;
  line-height: 1.42857143;
  text-align: left;
  text-align: start;
  text-decoration: none;
  text-shadow: none;
  text-transform: none;
  white-space: normal;
  word-break: normal;
  word-spacing: normal;
  word-wrap: normal;
  font-size: 13px;
  background-color: #fff;
  background-clip: padding-box;
  border: 1px solid #ccc;
  border: 1px solid rgba(0, 0, 0, 0.2);
  border-radius: 3px;
  -webkit-box-shadow: 0 5px 10px rgba(0, 0, 0, 0.2);
  box-shadow: 0 5px 10px rgba(0, 0, 0, 0.2);
}
.popover.top {
  margin-top: -10px;
}
.popover.right {
  margin-left: 10px;
}
.popover.bottom {
  margin-top: 10px;
}
.popover.left {
  margin-left: -10px;
}
.popover-title {
  margin: 0;
  padding: 8px 14px;
  font-size: 13px;
  background-color: #f7f7f7;
  border-bottom: 1px solid #ebebeb;
  border-radius: 2px 2px 0 0;
}
.popover-content {
  padding: 9px 14px;
}
.popover > .arrow,
.popover > .arrow:after {
  position: absolute;
  display: block;
  width: 0;
  height: 0;
  border-color: transparent;
  border-style: solid;
}
.popover > .arrow {
  border-width: 11px;
}
.popover > .arrow:after {
  border-width: 10px;
  content: "";
}
.popover.top > .arrow {
  left: 50%;
  margin-left: -11px;
  border-bottom-width: 0;
  border-top-color: #999999;
  border-top-color: rgba(0, 0, 0, 0.25);
  bottom: -11px;
}
.popover.top > .arrow:after {
  content: " ";
  bottom: 1px;
  margin-left: -10px;
  border-bottom-width: 0;
  border-top-color: #fff;
}
.popover.right > .arrow {
  top: 50%;
  left: -11px;
  margin-top: -11px;
  border-left-width: 0;
  border-right-color: #999999;
  border-right-color: rgba(0, 0, 0, 0.25);
}
.popover.right > .arrow:after {
  content: " ";
  left: 1px;
  bottom: -10px;
  border-left-width: 0;
  border-right-color: #fff;
}
.popover.bottom > .arrow {
  left: 50%;
  margin-left: -11px;
  border-top-width: 0;
  border-bottom-color: #999999;
  border-bottom-color: rgba(0, 0, 0, 0.25);
  top: -11px;
}
.popover.bottom > .arrow:after {
  content: " ";
  top: 1px;
  margin-left: -10px;
  border-top-width: 0;
  border-bottom-color: #fff;
}
.popover.left > .arrow {
  top: 50%;
  right: -11px;
  margin-top: -11px;
  border-right-width: 0;
  border-left-color: #999999;
  border-left-color: rgba(0, 0, 0, 0.25);
}
.popover.left > .arrow:after {
  content: " ";
  right: 1px;
  border-right-width: 0;
  border-left-color: #fff;
  bottom: -10px;
}
.carousel {
  position: relative;
}
.carousel-inner {
  position: relative;
  overflow: hidden;
  width: 100%;
}
.carousel-inner > .item {
  display: none;
  position: relative;
  -webkit-transition: 0.6s ease-in-out left;
  -o-transition: 0.6s ease-in-out left;
  transition: 0.6s ease-in-out left;
}
.carousel-inner > .item > img,
.carousel-inner > .item > a > img {
  line-height: 1;
}
@media all and (transform-3d), (-webkit-transform-3d) {
  .carousel-inner > .item {
    -webkit-transition: -webkit-transform 0.6s ease-in-out;
    -moz-transition: -moz-transform 0.6s ease-in-out;
    -o-transition: -o-transform 0.6s ease-in-out;
    transition: transform 0.6s ease-in-out;
    -webkit-backface-visibility: hidden;
    -moz-backface-visibility: hidden;
    backface-visibility: hidden;
    -webkit-perspective: 1000px;
    -moz-perspective: 1000px;
    perspective: 1000px;
  }
  .carousel-inner > .item.next,
  .carousel-inner > .item.active.right {
    -webkit-transform: translate3d(100%, 0, 0);
    transform: translate3d(100%, 0, 0);
    left: 0;
  }
  .carousel-inner > .item.prev,
  .carousel-inner > .item.active.left {
    -webkit-transform: translate3d(-100%, 0, 0);
    transform: translate3d(-100%, 0, 0);
    left: 0;
  }
  .carousel-inner > .item.next.left,
  .carousel-inner > .item.prev.right,
  .carousel-inner > .item.active {
    -webkit-transform: translate3d(0, 0, 0);
    transform: translate3d(0, 0, 0);
    left: 0;
  }
}
.carousel-inner > .active,
.carousel-inner > .next,
.carousel-inner > .prev {
  display: block;
}
.carousel-inner > .active {
  left: 0;
}
.carousel-inner > .next,
.carousel-inner > .prev {
  position: absolute;
  top: 0;
  width: 100%;
}
.carousel-inner > .next {
  left: 100%;
}
.carousel-inner > .prev {
  left: -100%;
}
.carousel-inner > .next.left,
.carousel-inner > .prev.right {
  left: 0;
}
.carousel-inner > .active.left {
  left: -100%;
}
.carousel-inner > .active.right {
  left: 100%;
}
.carousel-control {
  position: absolute;
  top: 0;
  left: 0;
  bottom: 0;
  width: 15%;
  opacity: 0.5;
  filter: alpha(opacity=50);
  font-size: 20px;
  color: #fff;
  text-align: center;
  text-shadow: 0 1px 2px rgba(0, 0, 0, 0.6);
  background-color: rgba(0, 0, 0, 0);
}
.carousel-control.left {
  background-image: -webkit-linear-gradient(left, rgba(0, 0, 0, 0.5) 0%, rgba(0, 0, 0, 0.0001) 100%);
  background-image: -o-linear-gradient(left, rgba(0, 0, 0, 0.5) 0%, rgba(0, 0, 0, 0.0001) 100%);
  background-image: linear-gradient(to right, rgba(0, 0, 0, 0.5) 0%, rgba(0, 0, 0, 0.0001) 100%);
  background-repeat: repeat-x;
  filter: progid:DXImageTransform.Microsoft.gradient(startColorstr='#80000000', endColorstr='#00000000', GradientType=1);
}
.carousel-control.right {
  left: auto;
  right: 0;
  background-image: -webkit-linear-gradient(left, rgba(0, 0, 0, 0.0001) 0%, rgba(0, 0, 0, 0.5) 100%);
  background-image: -o-linear-gradient(left, rgba(0, 0, 0, 0.0001) 0%, rgba(0, 0, 0, 0.5) 100%);
  background-image: linear-gradient(to right, rgba(0, 0, 0, 0.0001) 0%, rgba(0, 0, 0, 0.5) 100%);
  background-repeat: repeat-x;
  filter: progid:DXImageTransform.Microsoft.gradient(startColorstr='#00000000', endColorstr='#80000000', GradientType=1);
}
.carousel-control:hover,
.carousel-control:focus {
  outline: 0;
  color: #fff;
  text-decoration: none;
  opacity: 0.9;
  filter: alpha(opacity=90);
}
.carousel-control .icon-prev,
.carousel-control .icon-next,
.carousel-control .glyphicon-chevron-left,
.carousel-control .glyphicon-chevron-right {
  position: absolute;
  top: 50%;
  margin-top: -10px;
  z-index: 5;
  display: inline-block;
}
.carousel-control .icon-prev,
.carousel-control .glyphicon-chevron-left {
  left: 50%;
  margin-left: -10px;
}
.carousel-control .icon-next,
.carousel-control .glyphicon-chevron-right {
  right: 50%;
  margin-right: -10px;
}
.carousel-control .icon-prev,
.carousel-control .icon-next {
  width: 20px;
  height: 20px;
  line-height: 1;
  font-family: serif;
}
.carousel-control .icon-prev:before {
  content: '\2039';
}
.carousel-control .icon-next:before {
  content: '\203a';
}
.carousel-indicators {
  position: absolute;
  bottom: 10px;
  left: 50%;
  z-index: 15;
  width: 60%;
  margin-left: -30%;
  padding-left: 0;
  list-style: none;
  text-align: center;
}
.carousel-indicators li {
  display: inline-block;
  width: 10px;
  height: 10px;
  margin: 1px;
  text-indent: -999px;
  border: 1px solid #fff;
  border-radius: 10px;
  cursor: pointer;
  background-color: #000 \9;
  background-color: rgba(0, 0, 0, 0);
}
.carousel-indicators .active {
  margin: 0;
  width: 12px;
  height: 12px;
  background-color: #fff;
}
.carousel-caption {
  position: absolute;
  left: 15%;
  right: 15%;
  bottom: 20px;
  z-index: 10;
  padding-top: 20px;
  padding-bottom: 20px;
  color: #fff;
  text-align: center;
  text-shadow: 0 1px 2px rgba(0, 0, 0, 0.6);
}
.carousel-caption .btn {
  text-shadow: none;
}
@media screen and (min-width: 768px) {
  .carousel-control .glyphicon-chevron-left,
  .carousel-control .glyphicon-chevron-right,
  .carousel-control .icon-prev,
  .carousel-control .icon-next {
    width: 30px;
    height: 30px;
    margin-top: -10px;
    font-size: 30px;
  }
  .carousel-control .glyphicon-chevron-left,
  .carousel-control .icon-prev {
    margin-left: -10px;
  }
  .carousel-control .glyphicon-chevron-right,
  .carousel-control .icon-next {
    margin-right: -10px;
  }
  .carousel-caption {
    left: 20%;
    right: 20%;
    padding-bottom: 30px;
  }
  .carousel-indicators {
    bottom: 20px;
  }
}
.clearfix:before,
.clearfix:after,
.dl-horizontal dd:before,
.dl-horizontal dd:after,
.container:before,
.container:after,
.container-fluid:before,
.container-fluid:after,
.row:before,
.row:after,
.form-horizontal .form-group:before,
.form-horizontal .form-group:after,
.btn-toolbar:before,
.btn-toolbar:after,
.btn-group-vertical > .btn-group:before,
.btn-group-vertical > .btn-group:after,
.nav:before,
.nav:after,
.navbar:before,
.navbar:after,
.navbar-header:before,
.navbar-header:after,
.navbar-collapse:before,
.navbar-collapse:after,
.pager:before,
.pager:after,
.panel-body:before,
.panel-body:after,
.modal-header:before,
.modal-header:after,
.modal-footer:before,
.modal-footer:after,
.item_buttons:before,
.item_buttons:after {
  content: " ";
  display: table;
}
.clearfix:after,
.dl-horizontal dd:after,
.container:after,
.container-fluid:after,
.row:after,
.form-horizontal .form-group:after,
.btn-toolbar:after,
.btn-group-vertical > .btn-group:after,
.nav:after,
.navbar:after,
.navbar-header:after,
.navbar-collapse:after,
.pager:after,
.panel-body:after,
.modal-header:after,
.modal-footer:after,
.item_buttons:after {
  clear: both;
}
.center-block {
  display: block;
  margin-left: auto;
  margin-right: auto;
}
.pull-right {
  float: right !important;
}
.pull-left {
  float: left !important;
}
.hide {
  display: none !important;
}
.show {
  display: block !important;
}
.invisible {
  visibility: hidden;
}
.text-hide {
  font: 0/0 a;
  color: transparent;
  text-shadow: none;
  background-color: transparent;
  border: 0;
}
.hidden {
  display: none !important;
}
.affix {
  position: fixed;
}
@-ms-viewport {
  width: device-width;
}
.visible-xs,
.visible-sm,
.visible-md,
.visible-lg {
  display: none !important;
}
.visible-xs-block,
.visible-xs-inline,
.visible-xs-inline-block,
.visible-sm-block,
.visible-sm-inline,
.visible-sm-inline-block,
.visible-md-block,
.visible-md-inline,
.visible-md-inline-block,
.visible-lg-block,
.visible-lg-inline,
.visible-lg-inline-block {
  display: none !important;
}
@media (max-width: 767px) {
  .visible-xs {
    display: block !important;
  }
  table.visible-xs {
    display: table !important;
  }
  tr.visible-xs {
    display: table-row !important;
  }
  th.visible-xs,
  td.visible-xs {
    display: table-cell !important;
  }
}
@media (max-width: 767px) {
  .visible-xs-block {
    display: block !important;
  }
}
@media (max-width: 767px) {
  .visible-xs-inline {
    display: inline !important;
  }
}
@media (max-width: 767px) {
  .visible-xs-inline-block {
    display: inline-block !important;
  }
}
@media (min-width: 768px) and (max-width: 991px) {
  .visible-sm {
    display: block !important;
  }
  table.visible-sm {
    display: table !important;
  }
  tr.visible-sm {
    display: table-row !important;
  }
  th.visible-sm,
  td.visible-sm {
    display: table-cell !important;
  }
}
@media (min-width: 768px) and (max-width: 991px) {
  .visible-sm-block {
    display: block !important;
  }
}
@media (min-width: 768px) and (max-width: 991px) {
  .visible-sm-inline {
    display: inline !important;
  }
}
@media (min-width: 768px) and (max-width: 991px) {
  .visible-sm-inline-block {
    display: inline-block !important;
  }
}
@media (min-width: 992px) and (max-width: 1199px) {
  .visible-md {
    display: block !important;
  }
  table.visible-md {
    display: table !important;
  }
  tr.visible-md {
    display: table-row !important;
  }
  th.visible-md,
  td.visible-md {
    display: table-cell !important;
  }
}
@media (min-width: 992px) and (max-width: 1199px) {
  .visible-md-block {
    display: block !important;
  }
}
@media (min-width: 992px) and (max-width: 1199px) {
  .visible-md-inline {
    display: inline !important;
  }
}
@media (min-width: 992px) and (max-width: 1199px) {
  .visible-md-inline-block {
    display: inline-block !important;
  }
}
@media (min-width: 1200px) {
  .visible-lg {
    display: block !important;
  }
  table.visible-lg {
    display: table !important;
  }
  tr.visible-lg {
    display: table-row !important;
  }
  th.visible-lg,
  td.visible-lg {
    display: table-cell !important;
  }
}
@media (min-width: 1200px) {
  .visible-lg-block {
    display: block !important;
  }
}
@media (min-width: 1200px) {
  .visible-lg-inline {
    display: inline !important;
  }
}
@media (min-width: 1200px) {
  .visible-lg-inline-block {
    display: inline-block !important;
  }
}
@media (max-width: 767px) {
  .hidden-xs {
    display: none !important;
  }
}
@media (min-width: 768px) and (max-width: 991px) {
  .hidden-sm {
    display: none !important;
  }
}
@media (min-width: 992px) and (max-width: 1199px) {
  .hidden-md {
    display: none !important;
  }
}
@media (min-width: 1200px) {
  .hidden-lg {
    display: none !important;
  }
}
.visible-print {
  display: none !important;
}
@media print {
  .visible-print {
    display: block !important;
  }
  table.visible-print {
    display: table !important;
  }
  tr.visible-print {
    display: table-row !important;
  }
  th.visible-print,
  td.visible-print {
    display: table-cell !important;
  }
}
.visible-print-block {
  display: none !important;
}
@media print {
  .visible-print-block {
    display: block !important;
  }
}
.visible-print-inline {
  display: none !important;
}
@media print {
  .visible-print-inline {
    display: inline !important;
  }
}
.visible-print-inline-block {
  display: none !important;
}
@media print {
  .visible-print-inline-block {
    display: inline-block !important;
  }
}
@media print {
  .hidden-print {
    display: none !important;
  }
}
/*!
*
* Font Awesome
*
*/
/*!
 *  Font Awesome 4.7.0 by @davegandy - http://fontawesome.io - @fontawesome
 *  License - http://fontawesome.io/license (Font: SIL OFL 1.1, CSS: MIT License)
 */
/* FONT PATH
 * -------------------------- */
@font-face {
  font-family: 'FontAwesome';
  src: url('../components/font-awesome/fonts/fontawesome-webfont.eot?v=4.7.0');
  src: url('../components/font-awesome/fonts/fontawesome-webfont.eot?#iefix&v=4.7.0') format('embedded-opentype'), url('../components/font-awesome/fonts/fontawesome-webfont.woff2?v=4.7.0') format('woff2'), url('../components/font-awesome/fonts/fontawesome-webfont.woff?v=4.7.0') format('woff'), url('../components/font-awesome/fonts/fontawesome-webfont.ttf?v=4.7.0') format('truetype'), url('../components/font-awesome/fonts/fontawesome-webfont.svg?v=4.7.0#fontawesomeregular') format('svg');
  font-weight: normal;
  font-style: normal;
}
.fa {
  display: inline-block;
  font: normal normal normal 14px/1 FontAwesome;
  font-size: inherit;
  text-rendering: auto;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
}
/* makes the font 33% larger relative to the icon container */
.fa-lg {
  font-size: 1.33333333em;
  line-height: 0.75em;
  vertical-align: -15%;
}
.fa-2x {
  font-size: 2em;
}
.fa-3x {
  font-size: 3em;
}
.fa-4x {
  font-size: 4em;
}
.fa-5x {
  font-size: 5em;
}
.fa-fw {
  width: 1.28571429em;
  text-align: center;
}
.fa-ul {
  padding-left: 0;
  margin-left: 2.14285714em;
  list-style-type: none;
}
.fa-ul > li {
  position: relative;
}
.fa-li {
  position: absolute;
  left: -2.14285714em;
  width: 2.14285714em;
  top: 0.14285714em;
  text-align: center;
}
.fa-li.fa-lg {
  left: -1.85714286em;
}
.fa-border {
  padding: .2em .25em .15em;
  border: solid 0.08em #eee;
  border-radius: .1em;
}
.fa-pull-left {
  float: left;
}
.fa-pull-right {
  float: right;
}
.fa.fa-pull-left {
  margin-right: .3em;
}
.fa.fa-pull-right {
  margin-left: .3em;
}
/* Deprecated as of 4.4.0 */
.pull-right {
  float: right;
}
.pull-left {
  float: left;
}
.fa.pull-left {
  margin-right: .3em;
}
.fa.pull-right {
  margin-left: .3em;
}
.fa-spin {
  -webkit-animation: fa-spin 2s infinite linear;
  animation: fa-spin 2s infinite linear;
}
.fa-pulse {
  -webkit-animation: fa-spin 1s infinite steps(8);
  animation: fa-spin 1s infinite steps(8);
}
@-webkit-keyframes fa-spin {
  0% {
    -webkit-transform: rotate(0deg);
    transform: rotate(0deg);
  }
  100% {
    -webkit-transform: rotate(359deg);
    transform: rotate(359deg);
  }
}
@keyframes fa-spin {
  0% {
    -webkit-transform: rotate(0deg);
    transform: rotate(0deg);
  }
  100% {
    -webkit-transform: rotate(359deg);
    transform: rotate(359deg);
  }
}
.fa-rotate-90 {
  -ms-filter: "progid:DXImageTransform.Microsoft.BasicImage(rotation=1)";
  -webkit-transform: rotate(90deg);
  -ms-transform: rotate(90deg);
  transform: rotate(90deg);
}
.fa-rotate-180 {
  -ms-filter: "progid:DXImageTransform.Microsoft.BasicImage(rotation=2)";
  -webkit-transform: rotate(180deg);
  -ms-transform: rotate(180deg);
  transform: rotate(180deg);
}
.fa-rotate-270 {
  -ms-filter: "progid:DXImageTransform.Microsoft.BasicImage(rotation=3)";
  -webkit-transform: rotate(270deg);
  -ms-transform: rotate(270deg);
  transform: rotate(270deg);
}
.fa-flip-horizontal {
  -ms-filter: "progid:DXImageTransform.Microsoft.BasicImage(rotation=0, mirror=1)";
  -webkit-transform: scale(-1, 1);
  -ms-transform: scale(-1, 1);
  transform: scale(-1, 1);
}
.fa-flip-vertical {
  -ms-filter: "progid:DXImageTransform.Microsoft.BasicImage(rotation=2, mirror=1)";
  -webkit-transform: scale(1, -1);
  -ms-transform: scale(1, -1);
  transform: scale(1, -1);
}
:root .fa-rotate-90,
:root .fa-rotate-180,
:root .fa-rotate-270,
:root .fa-flip-horizontal,
:root .fa-flip-vertical {
  filter: none;
}
.fa-stack {
  position: relative;
  display: inline-block;
  width: 2em;
  height: 2em;
  line-height: 2em;
  vertical-align: middle;
}
.fa-stack-1x,
.fa-stack-2x {
  position: absolute;
  left: 0;
  width: 100%;
  text-align: center;
}
.fa-stack-1x {
  line-height: inherit;
}
.fa-stack-2x {
  font-size: 2em;
}
.fa-inverse {
  color: #fff;
}
/* Font Awesome uses the Unicode Private Use Area (PUA) to ensure screen
   readers do not read off random characters that represent icons */
.fa-glass:before {
  content: "\f000";
}
.fa-music:before {
  content: "\f001";
}
.fa-search:before {
  content: "\f002";
}
.fa-envelope-o:before {
  content: "\f003";
}
.fa-heart:before {
  content: "\f004";
}
.fa-star:before {
  content: "\f005";
}
.fa-star-o:before {
  content: "\f006";
}
.fa-user:before {
  content: "\f007";
}
.fa-film:before {
  content: "\f008";
}
.fa-th-large:before {
  content: "\f009";
}
.fa-th:before {
  content: "\f00a";
}
.fa-th-list:before {
  content: "\f00b";
}
.fa-check:before {
  content: "\f00c";
}
.fa-remove:before,
.fa-close:before,
.fa-times:before {
  content: "\f00d";
}
.fa-search-plus:before {
  content: "\f00e";
}
.fa-search-minus:before {
  content: "\f010";
}
.fa-power-off:before {
  content: "\f011";
}
.fa-signal:before {
  content: "\f012";
}
.fa-gear:before,
.fa-cog:before {
  content: "\f013";
}
.fa-trash-o:before {
  content: "\f014";
}
.fa-home:before {
  content: "\f015";
}
.fa-file-o:before {
  content: "\f016";
}
.fa-clock-o:before {
  content: "\f017";
}
.fa-road:before {
  content: "\f018";
}
.fa-download:before {
  content: "\f019";
}
.fa-arrow-circle-o-down:before {
  content: "\f01a";
}
.fa-arrow-circle-o-up:before {
  content: "\f01b";
}
.fa-inbox:before {
  content: "\f01c";
}
.fa-play-circle-o:before {
  content: "\f01d";
}
.fa-rotate-right:before,
.fa-repeat:before {
  content: "\f01e";
}
.fa-refresh:before {
  content: "\f021";
}
.fa-list-alt:before {
  content: "\f022";
}
.fa-lock:before {
  content: "\f023";
}
.fa-flag:before {
  content: "\f024";
}
.fa-headphones:before {
  content: "\f025";
}
.fa-volume-off:before {
  content: "\f026";
}
.fa-volume-down:before {
  content: "\f027";
}
.fa-volume-up:before {
  content: "\f028";
}
.fa-qrcode:before {
  content: "\f029";
}
.fa-barcode:before {
  content: "\f02a";
}
.fa-tag:before {
  content: "\f02b";
}
.fa-tags:before {
  content: "\f02c";
}
.fa-book:before {
  content: "\f02d";
}
.fa-bookmark:before {
  content: "\f02e";
}
.fa-print:before {
  content: "\f02f";
}
.fa-camera:before {
  content: "\f030";
}
.fa-font:before {
  content: "\f031";
}
.fa-bold:before {
  content: "\f032";
}
.fa-italic:before {
  content: "\f033";
}
.fa-text-height:before {
  content: "\f034";
}
.fa-text-width:before {
  content: "\f035";
}
.fa-align-left:before {
  content: "\f036";
}
.fa-align-center:before {
  content: "\f037";
}
.fa-align-right:before {
  content: "\f038";
}
.fa-align-justify:before {
  content: "\f039";
}
.fa-list:before {
  content: "\f03a";
}
.fa-dedent:before,
.fa-outdent:before {
  content: "\f03b";
}
.fa-indent:before {
  content: "\f03c";
}
.fa-video-camera:before {
  content: "\f03d";
}
.fa-photo:before,
.fa-image:before,
.fa-picture-o:before {
  content: "\f03e";
}
.fa-pencil:before {
  content: "\f040";
}
.fa-map-marker:before {
  content: "\f041";
}
.fa-adjust:before {
  content: "\f042";
}
.fa-tint:before {
  content: "\f043";
}
.fa-edit:before,
.fa-pencil-square-o:before {
  content: "\f044";
}
.fa-share-square-o:before {
  content: "\f045";
}
.fa-check-square-o:before {
  content: "\f046";
}
.fa-arrows:before {
  content: "\f047";
}
.fa-step-backward:before {
  content: "\f048";
}
.fa-fast-backward:before {
  content: "\f049";
}
.fa-backward:before {
  content: "\f04a";
}
.fa-play:before {
  content: "\f04b";
}
.fa-pause:before {
  content: "\f04c";
}
.fa-stop:before {
  content: "\f04d";
}
.fa-forward:before {
  content: "\f04e";
}
.fa-fast-forward:before {
  content: "\f050";
}
.fa-step-forward:before {
  content: "\f051";
}
.fa-eject:before {
  content: "\f052";
}
.fa-chevron-left:before {
  content: "\f053";
}
.fa-chevron-right:before {
  content: "\f054";
}
.fa-plus-circle:before {
  content: "\f055";
}
.fa-minus-circle:before {
  content: "\f056";
}
.fa-times-circle:before {
  content: "\f057";
}
.fa-check-circle:before {
  content: "\f058";
}
.fa-question-circle:before {
  content: "\f059";
}
.fa-info-circle:before {
  content: "\f05a";
}
.fa-crosshairs:before {
  content: "\f05b";
}
.fa-times-circle-o:before {
  content: "\f05c";
}
.fa-check-circle-o:before {
  content: "\f05d";
}
.fa-ban:before {
  content: "\f05e";
}
.fa-arrow-left:before {
  content: "\f060";
}
.fa-arrow-right:before {
  content: "\f061";
}
.fa-arrow-up:before {
  content: "\f062";
}
.fa-arrow-down:before {
  content: "\f063";
}
.fa-mail-forward:before,
.fa-share:before {
  content: "\f064";
}
.fa-expand:before {
  content: "\f065";
}
.fa-compress:before {
  content: "\f066";
}
.fa-plus:before {
  content: "\f067";
}
.fa-minus:before {
  content: "\f068";
}
.fa-asterisk:before {
  content: "\f069";
}
.fa-exclamation-circle:before {
  content: "\f06a";
}
.fa-gift:before {
  content: "\f06b";
}
.fa-leaf:before {
  content: "\f06c";
}
.fa-fire:before {
  content: "\f06d";
}
.fa-eye:before {
  content: "\f06e";
}
.fa-eye-slash:before {
  content: "\f070";
}
.fa-warning:before,
.fa-exclamation-triangle:before {
  content: "\f071";
}
.fa-plane:before {
  content: "\f072";
}
.fa-calendar:before {
  content: "\f073";
}
.fa-random:before {
  content: "\f074";
}
.fa-comment:before {
  content: "\f075";
}
.fa-magnet:before {
  content: "\f076";
}
.fa-chevron-up:before {
  content: "\f077";
}
.fa-chevron-down:before {
  content: "\f078";
}
.fa-retweet:before {
  content: "\f079";
}
.fa-shopping-cart:before {
  content: "\f07a";
}
.fa-folder:before {
  content: "\f07b";
}
.fa-folder-open:before {
  content: "\f07c";
}
.fa-arrows-v:before {
  content: "\f07d";
}
.fa-arrows-h:before {
  content: "\f07e";
}
.fa-bar-chart-o:before,
.fa-bar-chart:before {
  content: "\f080";
}
.fa-twitter-square:before {
  content: "\f081";
}
.fa-facebook-square:before {
  content: "\f082";
}
.fa-camera-retro:before {
  content: "\f083";
}
.fa-key:before {
  content: "\f084";
}
.fa-gears:before,
.fa-cogs:before {
  content: "\f085";
}
.fa-comments:before {
  content: "\f086";
}
.fa-thumbs-o-up:before {
  content: "\f087";
}
.fa-thumbs-o-down:before {
  content: "\f088";
}
.fa-star-half:before {
  content: "\f089";
}
.fa-heart-o:before {
  content: "\f08a";
}
.fa-sign-out:before {
  content: "\f08b";
}
.fa-linkedin-square:before {
  content: "\f08c";
}
.fa-thumb-tack:before {
  content: "\f08d";
}
.fa-external-link:before {
  content: "\f08e";
}
.fa-sign-in:before {
  content: "\f090";
}
.fa-trophy:before {
  content: "\f091";
}
.fa-github-square:before {
  content: "\f092";
}
.fa-upload:before {
  content: "\f093";
}
.fa-lemon-o:before {
  content: "\f094";
}
.fa-phone:before {
  content: "\f095";
}
.fa-square-o:before {
  content: "\f096";
}
.fa-bookmark-o:before {
  content: "\f097";
}
.fa-phone-square:before {
  content: "\f098";
}
.fa-twitter:before {
  content: "\f099";
}
.fa-facebook-f:before,
.fa-facebook:before {
  content: "\f09a";
}
.fa-github:before {
  content: "\f09b";
}
.fa-unlock:before {
  content: "\f09c";
}
.fa-credit-card:before {
  content: "\f09d";
}
.fa-feed:before,
.fa-rss:before {
  content: "\f09e";
}
.fa-hdd-o:before {
  content: "\f0a0";
}
.fa-bullhorn:before {
  content: "\f0a1";
}
.fa-bell:before {
  content: "\f0f3";
}
.fa-certificate:before {
  content: "\f0a3";
}
.fa-hand-o-right:before {
  content: "\f0a4";
}
.fa-hand-o-left:before {
  content: "\f0a5";
}
.fa-hand-o-up:before {
  content: "\f0a6";
}
.fa-hand-o-down:before {
  content: "\f0a7";
}
.fa-arrow-circle-left:before {
  content: "\f0a8";
}
.fa-arrow-circle-right:before {
  content: "\f0a9";
}
.fa-arrow-circle-up:before {
  content: "\f0aa";
}
.fa-arrow-circle-down:before {
  content: "\f0ab";
}
.fa-globe:before {
  content: "\f0ac";
}
.fa-wrench:before {
  content: "\f0ad";
}
.fa-tasks:before {
  content: "\f0ae";
}
.fa-filter:before {
  content: "\f0b0";
}
.fa-briefcase:before {
  content: "\f0b1";
}
.fa-arrows-alt:before {
  content: "\f0b2";
}
.fa-group:before,
.fa-users:before {
  content: "\f0c0";
}
.fa-chain:before,
.fa-link:before {
  content: "\f0c1";
}
.fa-cloud:before {
  content: "\f0c2";
}
.fa-flask:before {
  content: "\f0c3";
}
.fa-cut:before,
.fa-scissors:before {
  content: "\f0c4";
}
.fa-copy:before,
.fa-files-o:before {
  content: "\f0c5";
}
.fa-paperclip:before {
  content: "\f0c6";
}
.fa-save:before,
.fa-floppy-o:before {
  content: "\f0c7";
}
.fa-square:before {
  content: "\f0c8";
}
.fa-navicon:before,
.fa-reorder:before,
.fa-bars:before {
  content: "\f0c9";
}
.fa-list-ul:before {
  content: "\f0ca";
}
.fa-list-ol:before {
  content: "\f0cb";
}
.fa-strikethrough:before {
  content: "\f0cc";
}
.fa-underline:before {
  content: "\f0cd";
}
.fa-table:before {
  content: "\f0ce";
}
.fa-magic:before {
  content: "\f0d0";
}
.fa-truck:before {
  content: "\f0d1";
}
.fa-pinterest:before {
  content: "\f0d2";
}
.fa-pinterest-square:before {
  content: "\f0d3";
}
.fa-google-plus-square:before {
  content: "\f0d4";
}
.fa-google-plus:before {
  content: "\f0d5";
}
.fa-money:before {
  content: "\f0d6";
}
.fa-caret-down:before {
  content: "\f0d7";
}
.fa-caret-up:before {
  content: "\f0d8";
}
.fa-caret-left:before {
  content: "\f0d9";
}
.fa-caret-right:before {
  content: "\f0da";
}
.fa-columns:before {
  content: "\f0db";
}
.fa-unsorted:before,
.fa-sort:before {
  content: "\f0dc";
}
.fa-sort-down:before,
.fa-sort-desc:before {
  content: "\f0dd";
}
.fa-sort-up:before,
.fa-sort-asc:before {
  content: "\f0de";
}
.fa-envelope:before {
  content: "\f0e0";
}
.fa-linkedin:before {
  content: "\f0e1";
}
.fa-rotate-left:before,
.fa-undo:before {
  content: "\f0e2";
}
.fa-legal:before,
.fa-gavel:before {
  content: "\f0e3";
}
.fa-dashboard:before,
.fa-tachometer:before {
  content: "\f0e4";
}
.fa-comment-o:before {
  content: "\f0e5";
}
.fa-comments-o:before {
  content: "\f0e6";
}
.fa-flash:before,
.fa-bolt:before {
  content: "\f0e7";
}
.fa-sitemap:before {
  content: "\f0e8";
}
.fa-umbrella:before {
  content: "\f0e9";
}
.fa-paste:before,
.fa-clipboard:before {
  content: "\f0ea";
}
.fa-lightbulb-o:before {
  content: "\f0eb";
}
.fa-exchange:before {
  content: "\f0ec";
}
.fa-cloud-download:before {
  content: "\f0ed";
}
.fa-cloud-upload:before {
  content: "\f0ee";
}
.fa-user-md:before {
  content: "\f0f0";
}
.fa-stethoscope:before {
  content: "\f0f1";
}
.fa-suitcase:before {
  content: "\f0f2";
}
.fa-bell-o:before {
  content: "\f0a2";
}
.fa-coffee:before {
  content: "\f0f4";
}
.fa-cutlery:before {
  content: "\f0f5";
}
.fa-file-text-o:before {
  content: "\f0f6";
}
.fa-building-o:before {
  content: "\f0f7";
}
.fa-hospital-o:before {
  content: "\f0f8";
}
.fa-ambulance:before {
  content: "\f0f9";
}
.fa-medkit:before {
  content: "\f0fa";
}
.fa-fighter-jet:before {
  content: "\f0fb";
}
.fa-beer:before {
  content: "\f0fc";
}
.fa-h-square:before {
  content: "\f0fd";
}
.fa-plus-square:before {
  content: "\f0fe";
}
.fa-angle-double-left:before {
  content: "\f100";
}
.fa-angle-double-right:before {
  content: "\f101";
}
.fa-angle-double-up:before {
  content: "\f102";
}
.fa-angle-double-down:before {
  content: "\f103";
}
.fa-angle-left:before {
  content: "\f104";
}
.fa-angle-right:before {
  content: "\f105";
}
.fa-angle-up:before {
  content: "\f106";
}
.fa-angle-down:before {
  content: "\f107";
}
.fa-desktop:before {
  content: "\f108";
}
.fa-laptop:before {
  content: "\f109";
}
.fa-tablet:before {
  content: "\f10a";
}
.fa-mobile-phone:before,
.fa-mobile:before {
  content: "\f10b";
}
.fa-circle-o:before {
  content: "\f10c";
}
.fa-quote-left:before {
  content: "\f10d";
}
.fa-quote-right:before {
  content: "\f10e";
}
.fa-spinner:before {
  content: "\f110";
}
.fa-circle:before {
  content: "\f111";
}
.fa-mail-reply:before,
.fa-reply:before {
  content: "\f112";
}
.fa-github-alt:before {
  content: "\f113";
}
.fa-folder-o:before {
  content: "\f114";
}
.fa-folder-open-o:before {
  content: "\f115";
}
.fa-smile-o:before {
  content: "\f118";
}
.fa-frown-o:before {
  content: "\f119";
}
.fa-meh-o:before {
  content: "\f11a";
}
.fa-gamepad:before {
  content: "\f11b";
}
.fa-keyboard-o:before {
  content: "\f11c";
}
.fa-flag-o:before {
  content: "\f11d";
}
.fa-flag-checkered:before {
  content: "\f11e";
}
.fa-terminal:before {
  content: "\f120";
}
.fa-code:before {
  content: "\f121";
}
.fa-mail-reply-all:before,
.fa-reply-all:before {
  content: "\f122";
}
.fa-star-half-empty:before,
.fa-star-half-full:before,
.fa-star-half-o:before {
  content: "\f123";
}
.fa-location-arrow:before {
  content: "\f124";
}
.fa-crop:before {
  content: "\f125";
}
.fa-code-fork:before {
  content: "\f126";
}
.fa-unlink:before,
.fa-chain-broken:before {
  content: "\f127";
}
.fa-question:before {
  content: "\f128";
}
.fa-info:before {
  content: "\f129";
}
.fa-exclamation:before {
  content: "\f12a";
}
.fa-superscript:before {
  content: "\f12b";
}
.fa-subscript:before {
  content: "\f12c";
}
.fa-eraser:before {
  content: "\f12d";
}
.fa-puzzle-piece:before {
  content: "\f12e";
}
.fa-microphone:before {
  content: "\f130";
}
.fa-microphone-slash:before {
  content: "\f131";
}
.fa-shield:before {
  content: "\f132";
}
.fa-calendar-o:before {
  content: "\f133";
}
.fa-fire-extinguisher:before {
  content: "\f134";
}
.fa-rocket:before {
  content: "\f135";
}
.fa-maxcdn:before {
  content: "\f136";
}
.fa-chevron-circle-left:before {
  content: "\f137";
}
.fa-chevron-circle-right:before {
  content: "\f138";
}
.fa-chevron-circle-up:before {
  content: "\f139";
}
.fa-chevron-circle-down:before {
  content: "\f13a";
}
.fa-html5:before {
  content: "\f13b";
}
.fa-css3:before {
  content: "\f13c";
}
.fa-anchor:before {
  content: "\f13d";
}
.fa-unlock-alt:before {
  content: "\f13e";
}
.fa-bullseye:before {
  content: "\f140";
}
.fa-ellipsis-h:before {
  content: "\f141";
}
.fa-ellipsis-v:before {
  content: "\f142";
}
.fa-rss-square:before {
  content: "\f143";
}
.fa-play-circle:before {
  content: "\f144";
}
.fa-ticket:before {
  content: "\f145";
}
.fa-minus-square:before {
  content: "\f146";
}
.fa-minus-square-o:before {
  content: "\f147";
}
.fa-level-up:before {
  content: "\f148";
}
.fa-level-down:before {
  content: "\f149";
}
.fa-check-square:before {
  content: "\f14a";
}
.fa-pencil-square:before {
  content: "\f14b";
}
.fa-external-link-square:before {
  content: "\f14c";
}
.fa-share-square:before {
  content: "\f14d";
}
.fa-compass:before {
  content: "\f14e";
}
.fa-toggle-down:before,
.fa-caret-square-o-down:before {
  content: "\f150";
}
.fa-toggle-up:before,
.fa-caret-square-o-up:before {
  content: "\f151";
}
.fa-toggle-right:before,
.fa-caret-square-o-right:before {
  content: "\f152";
}
.fa-euro:before,
.fa-eur:before {
  content: "\f153";
}
.fa-gbp:before {
  content: "\f154";
}
.fa-dollar:before,
.fa-usd:before {
  content: "\f155";
}
.fa-rupee:before,
.fa-inr:before {
  content: "\f156";
}
.fa-cny:before,
.fa-rmb:before,
.fa-yen:before,
.fa-jpy:before {
  content: "\f157";
}
.fa-ruble:before,
.fa-rouble:before,
.fa-rub:before {
  content: "\f158";
}
.fa-won:before,
.fa-krw:before {
  content: "\f159";
}
.fa-bitcoin:before,
.fa-btc:before {
  content: "\f15a";
}
.fa-file:before {
  content: "\f15b";
}
.fa-file-text:before {
  content: "\f15c";
}
.fa-sort-alpha-asc:before {
  content: "\f15d";
}
.fa-sort-alpha-desc:before {
  content: "\f15e";
}
.fa-sort-amount-asc:before {
  content: "\f160";
}
.fa-sort-amount-desc:before {
  content: "\f161";
}
.fa-sort-numeric-asc:before {
  content: "\f162";
}
.fa-sort-numeric-desc:before {
  content: "\f163";
}
.fa-thumbs-up:before {
  content: "\f164";
}
.fa-thumbs-down:before {
  content: "\f165";
}
.fa-youtube-square:before {
  content: "\f166";
}
.fa-youtube:before {
  content: "\f167";
}
.fa-xing:before {
  content: "\f168";
}
.fa-xing-square:before {
  content: "\f169";
}
.fa-youtube-play:before {
  content: "\f16a";
}
.fa-dropbox:before {
  content: "\f16b";
}
.fa-stack-overflow:before {
  content: "\f16c";
}
.fa-instagram:before {
  content: "\f16d";
}
.fa-flickr:before {
  content: "\f16e";
}
.fa-adn:before {
  content: "\f170";
}
.fa-bitbucket:before {
  content: "\f171";
}
.fa-bitbucket-square:before {
  content: "\f172";
}
.fa-tumblr:before {
  content: "\f173";
}
.fa-tumblr-square:before {
  content: "\f174";
}
.fa-long-arrow-down:before {
  content: "\f175";
}
.fa-long-arrow-up:before {
  content: "\f176";
}
.fa-long-arrow-left:before {
  content: "\f177";
}
.fa-long-arrow-right:before {
  content: "\f178";
}
.fa-apple:before {
  content: "\f179";
}
.fa-windows:before {
  content: "\f17a";
}
.fa-android:before {
  content: "\f17b";
}
.fa-linux:before {
  content: "\f17c";
}
.fa-dribbble:before {
  content: "\f17d";
}
.fa-skype:before {
  content: "\f17e";
}
.fa-foursquare:before {
  content: "\f180";
}
.fa-trello:before {
  content: "\f181";
}
.fa-female:before {
  content: "\f182";
}
.fa-male:before {
  content: "\f183";
}
.fa-gittip:before,
.fa-gratipay:before {
  content: "\f184";
}
.fa-sun-o:before {
  content: "\f185";
}
.fa-moon-o:before {
  content: "\f186";
}
.fa-archive:before {
  content: "\f187";
}
.fa-bug:before {
  content: "\f188";
}
.fa-vk:before {
  content: "\f189";
}
.fa-weibo:before {
  content: "\f18a";
}
.fa-renren:before {
  content: "\f18b";
}
.fa-pagelines:before {
  content: "\f18c";
}
.fa-stack-exchange:before {
  content: "\f18d";
}
.fa-arrow-circle-o-right:before {
  content: "\f18e";
}
.fa-arrow-circle-o-left:before {
  content: "\f190";
}
.fa-toggle-left:before,
.fa-caret-square-o-left:before {
  content: "\f191";
}
.fa-dot-circle-o:before {
  content: "\f192";
}
.fa-wheelchair:before {
  content: "\f193";
}
.fa-vimeo-square:before {
  content: "\f194";
}
.fa-turkish-lira:before,
.fa-try:before {
  content: "\f195";
}
.fa-plus-square-o:before {
  content: "\f196";
}
.fa-space-shuttle:before {
  content: "\f197";
}
.fa-slack:before {
  content: "\f198";
}
.fa-envelope-square:before {
  content: "\f199";
}
.fa-wordpress:before {
  content: "\f19a";
}
.fa-openid:before {
  content: "\f19b";
}
.fa-institution:before,
.fa-bank:before,
.fa-university:before {
  content: "\f19c";
}
.fa-mortar-board:before,
.fa-graduation-cap:before {
  content: "\f19d";
}
.fa-yahoo:before {
  content: "\f19e";
}
.fa-google:before {
  content: "\f1a0";
}
.fa-reddit:before {
  content: "\f1a1";
}
.fa-reddit-square:before {
  content: "\f1a2";
}
.fa-stumbleupon-circle:before {
  content: "\f1a3";
}
.fa-stumbleupon:before {
  content: "\f1a4";
}
.fa-delicious:before {
  content: "\f1a5";
}
.fa-digg:before {
  content: "\f1a6";
}
.fa-pied-piper-pp:before {
  content: "\f1a7";
}
.fa-pied-piper-alt:before {
  content: "\f1a8";
}
.fa-drupal:before {
  content: "\f1a9";
}
.fa-joomla:before {
  content: "\f1aa";
}
.fa-language:before {
  content: "\f1ab";
}
.fa-fax:before {
  content: "\f1ac";
}
.fa-building:before {
  content: "\f1ad";
}
.fa-child:before {
  content: "\f1ae";
}
.fa-paw:before {
  content: "\f1b0";
}
.fa-spoon:before {
  content: "\f1b1";
}
.fa-cube:before {
  content: "\f1b2";
}
.fa-cubes:before {
  content: "\f1b3";
}
.fa-behance:before {
  content: "\f1b4";
}
.fa-behance-square:before {
  content: "\f1b5";
}
.fa-steam:before {
  content: "\f1b6";
}
.fa-steam-square:before {
  content: "\f1b7";
}
.fa-recycle:before {
  content: "\f1b8";
}
.fa-automobile:before,
.fa-car:before {
  content: "\f1b9";
}
.fa-cab:before,
.fa-taxi:before {
  content: "\f1ba";
}
.fa-tree:before {
  content: "\f1bb";
}
.fa-spotify:before {
  content: "\f1bc";
}
.fa-deviantart:before {
  content: "\f1bd";
}
.fa-soundcloud:before {
  content: "\f1be";
}
.fa-database:before {
  content: "\f1c0";
}
.fa-file-pdf-o:before {
  content: "\f1c1";
}
.fa-file-word-o:before {
  content: "\f1c2";
}
.fa-file-excel-o:before {
  content: "\f1c3";
}
.fa-file-powerpoint-o:before {
  content: "\f1c4";
}
.fa-file-photo-o:before,
.fa-file-picture-o:before,
.fa-file-image-o:before {
  content: "\f1c5";
}
.fa-file-zip-o:before,
.fa-file-archive-o:before {
  content: "\f1c6";
}
.fa-file-sound-o:before,
.fa-file-audio-o:before {
  content: "\f1c7";
}
.fa-file-movie-o:before,
.fa-file-video-o:before {
  content: "\f1c8";
}
.fa-file-code-o:before {
  content: "\f1c9";
}
.fa-vine:before {
  content: "\f1ca";
}
.fa-codepen:before {
  content: "\f1cb";
}
.fa-jsfiddle:before {
  content: "\f1cc";
}
.fa-life-bouy:before,
.fa-life-buoy:before,
.fa-life-saver:before,
.fa-support:before,
.fa-life-ring:before {
  content: "\f1cd";
}
.fa-circle-o-notch:before {
  content: "\f1ce";
}
.fa-ra:before,
.fa-resistance:before,
.fa-rebel:before {
  content: "\f1d0";
}
.fa-ge:before,
.fa-empire:before {
  content: "\f1d1";
}
.fa-git-square:before {
  content: "\f1d2";
}
.fa-git:before {
  content: "\f1d3";
}
.fa-y-combinator-square:before,
.fa-yc-square:before,
.fa-hacker-news:before {
  content: "\f1d4";
}
.fa-tencent-weibo:before {
  content: "\f1d5";
}
.fa-qq:before {
  content: "\f1d6";
}
.fa-wechat:before,
.fa-weixin:before {
  content: "\f1d7";
}
.fa-send:before,
.fa-paper-plane:before {
  content: "\f1d8";
}
.fa-send-o:before,
.fa-paper-plane-o:before {
  content: "\f1d9";
}
.fa-history:before {
  content: "\f1da";
}
.fa-circle-thin:before {
  content: "\f1db";
}
.fa-header:before {
  content: "\f1dc";
}
.fa-paragraph:before {
  content: "\f1dd";
}
.fa-sliders:before {
  content: "\f1de";
}
.fa-share-alt:before {
  content: "\f1e0";
}
.fa-share-alt-square:before {
  content: "\f1e1";
}
.fa-bomb:before {
  content: "\f1e2";
}
.fa-soccer-ball-o:before,
.fa-futbol-o:before {
  content: "\f1e3";
}
.fa-tty:before {
  content: "\f1e4";
}
.fa-binoculars:before {
  content: "\f1e5";
}
.fa-plug:before {
  content: "\f1e6";
}
.fa-slideshare:before {
  content: "\f1e7";
}
.fa-twitch:before {
  content: "\f1e8";
}
.fa-yelp:before {
  content: "\f1e9";
}
.fa-newspaper-o:before {
  content: "\f1ea";
}
.fa-wifi:before {
  content: "\f1eb";
}
.fa-calculator:before {
  content: "\f1ec";
}
.fa-paypal:before {
  content: "\f1ed";
}
.fa-google-wallet:before {
  content: "\f1ee";
}
.fa-cc-visa:before {
  content: "\f1f0";
}
.fa-cc-mastercard:before {
  content: "\f1f1";
}
.fa-cc-discover:before {
  content: "\f1f2";
}
.fa-cc-amex:before {
  content: "\f1f3";
}
.fa-cc-paypal:before {
  content: "\f1f4";
}
.fa-cc-stripe:before {
  content: "\f1f5";
}
.fa-bell-slash:before {
  content: "\f1f6";
}
.fa-bell-slash-o:before {
  content: "\f1f7";
}
.fa-trash:before {
  content: "\f1f8";
}
.fa-copyright:before {
  content: "\f1f9";
}
.fa-at:before {
  content: "\f1fa";
}
.fa-eyedropper:before {
  content: "\f1fb";
}
.fa-paint-brush:before {
  content: "\f1fc";
}
.fa-birthday-cake:before {
  content: "\f1fd";
}
.fa-area-chart:before {
  content: "\f1fe";
}
.fa-pie-chart:before {
  content: "\f200";
}
.fa-line-chart:before {
  content: "\f201";
}
.fa-lastfm:before {
  content: "\f202";
}
.fa-lastfm-square:before {
  content: "\f203";
}
.fa-toggle-off:before {
  content: "\f204";
}
.fa-toggle-on:before {
  content: "\f205";
}
.fa-bicycle:before {
  content: "\f206";
}
.fa-bus:before {
  content: "\f207";
}
.fa-ioxhost:before {
  content: "\f208";
}
.fa-angellist:before {
  content: "\f209";
}
.fa-cc:before {
  content: "\f20a";
}
.fa-shekel:before,
.fa-sheqel:before,
.fa-ils:before {
  content: "\f20b";
}
.fa-meanpath:before {
  content: "\f20c";
}
.fa-buysellads:before {
  content: "\f20d";
}
.fa-connectdevelop:before {
  content: "\f20e";
}
.fa-dashcube:before {
  content: "\f210";
}
.fa-forumbee:before {
  content: "\f211";
}
.fa-leanpub:before {
  content: "\f212";
}
.fa-sellsy:before {
  content: "\f213";
}
.fa-shirtsinbulk:before {
  content: "\f214";
}
.fa-simplybuilt:before {
  content: "\f215";
}
.fa-skyatlas:before {
  content: "\f216";
}
.fa-cart-plus:before {
  content: "\f217";
}
.fa-cart-arrow-down:before {
  content: "\f218";
}
.fa-diamond:before {
  content: "\f219";
}
.fa-ship:before {
  content: "\f21a";
}
.fa-user-secret:before {
  content: "\f21b";
}
.fa-motorcycle:before {
  content: "\f21c";
}
.fa-street-view:before {
  content: "\f21d";
}
.fa-heartbeat:before {
  content: "\f21e";
}
.fa-venus:before {
  content: "\f221";
}
.fa-mars:before {
  content: "\f222";
}
.fa-mercury:before {
  content: "\f223";
}
.fa-intersex:before,
.fa-transgender:before {
  content: "\f224";
}
.fa-transgender-alt:before {
  content: "\f225";
}
.fa-venus-double:before {
  content: "\f226";
}
.fa-mars-double:before {
  content: "\f227";
}
.fa-venus-mars:before {
  content: "\f228";
}
.fa-mars-stroke:before {
  content: "\f229";
}
.fa-mars-stroke-v:before {
  content: "\f22a";
}
.fa-mars-stroke-h:before {
  content: "\f22b";
}
.fa-neuter:before {
  content: "\f22c";
}
.fa-genderless:before {
  content: "\f22d";
}
.fa-facebook-official:before {
  content: "\f230";
}
.fa-pinterest-p:before {
  content: "\f231";
}
.fa-whatsapp:before {
  content: "\f232";
}
.fa-server:before {
  content: "\f233";
}
.fa-user-plus:before {
  content: "\f234";
}
.fa-user-times:before {
  content: "\f235";
}
.fa-hotel:before,
.fa-bed:before {
  content: "\f236";
}
.fa-viacoin:before {
  content: "\f237";
}
.fa-train:before {
  content: "\f238";
}
.fa-subway:before {
  content: "\f239";
}
.fa-medium:before {
  content: "\f23a";
}
.fa-yc:before,
.fa-y-combinator:before {
  content: "\f23b";
}
.fa-optin-monster:before {
  content: "\f23c";
}
.fa-opencart:before {
  content: "\f23d";
}
.fa-expeditedssl:before {
  content: "\f23e";
}
.fa-battery-4:before,
.fa-battery:before,
.fa-battery-full:before {
  content: "\f240";
}
.fa-battery-3:before,
.fa-battery-three-quarters:before {
  content: "\f241";
}
.fa-battery-2:before,
.fa-battery-half:before {
  content: "\f242";
}
.fa-battery-1:before,
.fa-battery-quarter:before {
  content: "\f243";
}
.fa-battery-0:before,
.fa-battery-empty:before {
  content: "\f244";
}
.fa-mouse-pointer:before {
  content: "\f245";
}
.fa-i-cursor:before {
  content: "\f246";
}
.fa-object-group:before {
  content: "\f247";
}
.fa-object-ungroup:before {
  content: "\f248";
}
.fa-sticky-note:before {
  content: "\f249";
}
.fa-sticky-note-o:before {
  content: "\f24a";
}
.fa-cc-jcb:before {
  content: "\f24b";
}
.fa-cc-diners-club:before {
  content: "\f24c";
}
.fa-clone:before {
  content: "\f24d";
}
.fa-balance-scale:before {
  content: "\f24e";
}
.fa-hourglass-o:before {
  content: "\f250";
}
.fa-hourglass-1:before,
.fa-hourglass-start:before {
  content: "\f251";
}
.fa-hourglass-2:before,
.fa-hourglass-half:before {
  content: "\f252";
}
.fa-hourglass-3:before,
.fa-hourglass-end:before {
  content: "\f253";
}
.fa-hourglass:before {
  content: "\f254";
}
.fa-hand-grab-o:before,
.fa-hand-rock-o:before {
  content: "\f255";
}
.fa-hand-stop-o:before,
.fa-hand-paper-o:before {
  content: "\f256";
}
.fa-hand-scissors-o:before {
  content: "\f257";
}
.fa-hand-lizard-o:before {
  content: "\f258";
}
.fa-hand-spock-o:before {
  content: "\f259";
}
.fa-hand-pointer-o:before {
  content: "\f25a";
}
.fa-hand-peace-o:before {
  content: "\f25b";
}
.fa-trademark:before {
  content: "\f25c";
}
.fa-registered:before {
  content: "\f25d";
}
.fa-creative-commons:before {
  content: "\f25e";
}
.fa-gg:before {
  content: "\f260";
}
.fa-gg-circle:before {
  content: "\f261";
}
.fa-tripadvisor:before {
  content: "\f262";
}
.fa-odnoklassniki:before {
  content: "\f263";
}
.fa-odnoklassniki-square:before {
  content: "\f264";
}
.fa-get-pocket:before {
  content: "\f265";
}
.fa-wikipedia-w:before {
  content: "\f266";
}
.fa-safari:before {
  content: "\f267";
}
.fa-chrome:before {
  content: "\f268";
}
.fa-firefox:before {
  content: "\f269";
}
.fa-opera:before {
  content: "\f26a";
}
.fa-internet-explorer:before {
  content: "\f26b";
}
.fa-tv:before,
.fa-television:before {
  content: "\f26c";
}
.fa-contao:before {
  content: "\f26d";
}
.fa-500px:before {
  content: "\f26e";
}
.fa-amazon:before {
  content: "\f270";
}
.fa-calendar-plus-o:before {
  content: "\f271";
}
.fa-calendar-minus-o:before {
  content: "\f272";
}
.fa-calendar-times-o:before {
  content: "\f273";
}
.fa-calendar-check-o:before {
  content: "\f274";
}
.fa-industry:before {
  content: "\f275";
}
.fa-map-pin:before {
  content: "\f276";
}
.fa-map-signs:before {
  content: "\f277";
}
.fa-map-o:before {
  content: "\f278";
}
.fa-map:before {
  content: "\f279";
}
.fa-commenting:before {
  content: "\f27a";
}
.fa-commenting-o:before {
  content: "\f27b";
}
.fa-houzz:before {
  content: "\f27c";
}
.fa-vimeo:before {
  content: "\f27d";
}
.fa-black-tie:before {
  content: "\f27e";
}
.fa-fonticons:before {
  content: "\f280";
}
.fa-reddit-alien:before {
  content: "\f281";
}
.fa-edge:before {
  content: "\f282";
}
.fa-credit-card-alt:before {
  content: "\f283";
}
.fa-codiepie:before {
  content: "\f284";
}
.fa-modx:before {
  content: "\f285";
}
.fa-fort-awesome:before {
  content: "\f286";
}
.fa-usb:before {
  content: "\f287";
}
.fa-product-hunt:before {
  content: "\f288";
}
.fa-mixcloud:before {
  content: "\f289";
}
.fa-scribd:before {
  content: "\f28a";
}
.fa-pause-circle:before {
  content: "\f28b";
}
.fa-pause-circle-o:before {
  content: "\f28c";
}
.fa-stop-circle:before {
  content: "\f28d";
}
.fa-stop-circle-o:before {
  content: "\f28e";
}
.fa-shopping-bag:before {
  content: "\f290";
}
.fa-shopping-basket:before {
  content: "\f291";
}
.fa-hashtag:before {
  content: "\f292";
}
.fa-bluetooth:before {
  content: "\f293";
}
.fa-bluetooth-b:before {
  content: "\f294";
}
.fa-percent:before {
  content: "\f295";
}
.fa-gitlab:before {
  content: "\f296";
}
.fa-wpbeginner:before {
  content: "\f297";
}
.fa-wpforms:before {
  content: "\f298";
}
.fa-envira:before {
  content: "\f299";
}
.fa-universal-access:before {
  content: "\f29a";
}
.fa-wheelchair-alt:before {
  content: "\f29b";
}
.fa-question-circle-o:before {
  content: "\f29c";
}
.fa-blind:before {
  content: "\f29d";
}
.fa-audio-description:before {
  content: "\f29e";
}
.fa-volume-control-phone:before {
  content: "\f2a0";
}
.fa-braille:before {
  content: "\f2a1";
}
.fa-assistive-listening-systems:before {
  content: "\f2a2";
}
.fa-asl-interpreting:before,
.fa-american-sign-language-interpreting:before {
  content: "\f2a3";
}
.fa-deafness:before,
.fa-hard-of-hearing:before,
.fa-deaf:before {
  content: "\f2a4";
}
.fa-glide:before {
  content: "\f2a5";
}
.fa-glide-g:before {
  content: "\f2a6";
}
.fa-signing:before,
.fa-sign-language:before {
  content: "\f2a7";
}
.fa-low-vision:before {
  content: "\f2a8";
}
.fa-viadeo:before {
  content: "\f2a9";
}
.fa-viadeo-square:before {
  content: "\f2aa";
}
.fa-snapchat:before {
  content: "\f2ab";
}
.fa-snapchat-ghost:before {
  content: "\f2ac";
}
.fa-snapchat-square:before {
  content: "\f2ad";
}
.fa-pied-piper:before {
  content: "\f2ae";
}
.fa-first-order:before {
  content: "\f2b0";
}
.fa-yoast:before {
  content: "\f2b1";
}
.fa-themeisle:before {
  content: "\f2b2";
}
.fa-google-plus-circle:before,
.fa-google-plus-official:before {
  content: "\f2b3";
}
.fa-fa:before,
.fa-font-awesome:before {
  content: "\f2b4";
}
.fa-handshake-o:before {
  content: "\f2b5";
}
.fa-envelope-open:before {
  content: "\f2b6";
}
.fa-envelope-open-o:before {
  content: "\f2b7";
}
.fa-linode:before {
  content: "\f2b8";
}
.fa-address-book:before {
  content: "\f2b9";
}
.fa-address-book-o:before {
  content: "\f2ba";
}
.fa-vcard:before,
.fa-address-card:before {
  content: "\f2bb";
}
.fa-vcard-o:before,
.fa-address-card-o:before {
  content: "\f2bc";
}
.fa-user-circle:before {
  content: "\f2bd";
}
.fa-user-circle-o:before {
  content: "\f2be";
}
.fa-user-o:before {
  content: "\f2c0";
}
.fa-id-badge:before {
  content: "\f2c1";
}
.fa-drivers-license:before,
.fa-id-card:before {
  content: "\f2c2";
}
.fa-drivers-license-o:before,
.fa-id-card-o:before {
  content: "\f2c3";
}
.fa-quora:before {
  content: "\f2c4";
}
.fa-free-code-camp:before {
  content: "\f2c5";
}
.fa-telegram:before {
  content: "\f2c6";
}
.fa-thermometer-4:before,
.fa-thermometer:before,
.fa-thermometer-full:before {
  content: "\f2c7";
}
.fa-thermometer-3:before,
.fa-thermometer-three-quarters:before {
  content: "\f2c8";
}
.fa-thermometer-2:before,
.fa-thermometer-half:before {
  content: "\f2c9";
}
.fa-thermometer-1:before,
.fa-thermometer-quarter:before {
  content: "\f2ca";
}
.fa-thermometer-0:before,
.fa-thermometer-empty:before {
  content: "\f2cb";
}
.fa-shower:before {
  content: "\f2cc";
}
.fa-bathtub:before,
.fa-s15:before,
.fa-bath:before {
  content: "\f2cd";
}
.fa-podcast:before {
  content: "\f2ce";
}
.fa-window-maximize:before {
  content: "\f2d0";
}
.fa-window-minimize:before {
  content: "\f2d1";
}
.fa-window-restore:before {
  content: "\f2d2";
}
.fa-times-rectangle:before,
.fa-window-close:before {
  content: "\f2d3";
}
.fa-times-rectangle-o:before,
.fa-window-close-o:before {
  content: "\f2d4";
}
.fa-bandcamp:before {
  content: "\f2d5";
}
.fa-grav:before {
  content: "\f2d6";
}
.fa-etsy:before {
  content: "\f2d7";
}
.fa-imdb:before {
  content: "\f2d8";
}
.fa-ravelry:before {
  content: "\f2d9";
}
.fa-eercast:before {
  content: "\f2da";
}
.fa-microchip:before {
  content: "\f2db";
}
.fa-snowflake-o:before {
  content: "\f2dc";
}
.fa-superpowers:before {
  content: "\f2dd";
}
.fa-wpexplorer:before {
  content: "\f2de";
}
.fa-meetup:before {
  content: "\f2e0";
}
.sr-only {
  position: absolute;
  width: 1px;
  height: 1px;
  padding: 0;
  margin: -1px;
  overflow: hidden;
  clip: rect(0, 0, 0, 0);
  border: 0;
}
.sr-only-focusable:active,
.sr-only-focusable:focus {
  position: static;
  width: auto;
  height: auto;
  margin: 0;
  overflow: visible;
  clip: auto;
}
.sr-only-focusable:active,
.sr-only-focusable:focus {
  position: static;
  width: auto;
  height: auto;
  margin: 0;
  overflow: visible;
  clip: auto;
}
/*!
*
* IPython base
*
*/
.modal.fade .modal-dialog {
  -webkit-transform: translate(0, 0);
  -ms-transform: translate(0, 0);
  -o-transform: translate(0, 0);
  transform: translate(0, 0);
}
code {
  color: #000;
}
pre {
  font-size: inherit;
  line-height: inherit;
}
label {
  font-weight: normal;
}
/* Make the page background atleast 100% the height of the view port */
/* Make the page itself atleast 70% the height of the view port */
.border-box-sizing {
  box-sizing: border-box;
  -moz-box-sizing: border-box;
  -webkit-box-sizing: border-box;
}
.corner-all {
  border-radius: 2px;
}
.no-padding {
  padding: 0px;
}
/* Flexible box model classes */
/* Taken from Alex Russell http://infrequently.org/2009/08/css-3-progress/ */
/* This file is a compatability layer.  It allows the usage of flexible box 
model layouts accross multiple browsers, including older browsers.  The newest,
universal implementation of the flexible box model is used when available (see
`Modern browsers` comments below).  Browsers that are known to implement this 
new spec completely include:

    Firefox 28.0+
    Chrome 29.0+
    Internet Explorer 11+ 
    Opera 17.0+

Browsers not listed, including Safari, are supported via the styling under the
`Old browsers` comments below.
*/
.hbox {
  /* Old browsers */
  display: -webkit-box;
  -webkit-box-orient: horizontal;
  -webkit-box-align: stretch;
  display: -moz-box;
  -moz-box-orient: horizontal;
  -moz-box-align: stretch;
  display: box;
  box-orient: horizontal;
  box-align: stretch;
  /* Modern browsers */
  display: flex;
  flex-direction: row;
  align-items: stretch;
}
.hbox > * {
  /* Old browsers */
  -webkit-box-flex: 0;
  -moz-box-flex: 0;
  box-flex: 0;
  /* Modern browsers */
  flex: none;
}
.vbox {
  /* Old browsers */
  display: -webkit-box;
  -webkit-box-orient: vertical;
  -webkit-box-align: stretch;
  display: -moz-box;
  -moz-box-orient: vertical;
  -moz-box-align: stretch;
  display: box;
  box-orient: vertical;
  box-align: stretch;
  /* Modern browsers */
  display: flex;
  flex-direction: column;
  align-items: stretch;
}
.vbox > * {
  /* Old browsers */
  -webkit-box-flex: 0;
  -moz-box-flex: 0;
  box-flex: 0;
  /* Modern browsers */
  flex: none;
}
.hbox.reverse,
.vbox.reverse,
.reverse {
  /* Old browsers */
  -webkit-box-direction: reverse;
  -moz-box-direction: reverse;
  box-direction: reverse;
  /* Modern browsers */
  flex-direction: row-reverse;
}
.hbox.box-flex0,
.vbox.box-flex0,
.box-flex0 {
  /* Old browsers */
  -webkit-box-flex: 0;
  -moz-box-flex: 0;
  box-flex: 0;
  /* Modern browsers */
  flex: none;
  width: auto;
}
.hbox.box-flex1,
.vbox.box-flex1,
.box-flex1 {
  /* Old browsers */
  -webkit-box-flex: 1;
  -moz-box-flex: 1;
  box-flex: 1;
  /* Modern browsers */
  flex: 1;
}
.hbox.box-flex,
.vbox.box-flex,
.box-flex {
  /* Old browsers */
  /* Old browsers */
  -webkit-box-flex: 1;
  -moz-box-flex: 1;
  box-flex: 1;
  /* Modern browsers */
  flex: 1;
}
.hbox.box-flex2,
.vbox.box-flex2,
.box-flex2 {
  /* Old browsers */
  -webkit-box-flex: 2;
  -moz-box-flex: 2;
  box-flex: 2;
  /* Modern browsers */
  flex: 2;
}
.box-group1 {
  /*  Deprecated */
  -webkit-box-flex-group: 1;
  -moz-box-flex-group: 1;
  box-flex-group: 1;
}
.box-group2 {
  /* Deprecated */
  -webkit-box-flex-group: 2;
  -moz-box-flex-group: 2;
  box-flex-group: 2;
}
.hbox.start,
.vbox.start,
.start {
  /* Old browsers */
  -webkit-box-pack: start;
  -moz-box-pack: start;
  box-pack: start;
  /* Modern browsers */
  justify-content: flex-start;
}
.hbox.end,
.vbox.end,
.end {
  /* Old browsers */
  -webkit-box-pack: end;
  -moz-box-pack: end;
  box-pack: end;
  /* Modern browsers */
  justify-content: flex-end;
}
.hbox.center,
.vbox.center,
.center {
  /* Old browsers */
  -webkit-box-pack: center;
  -moz-box-pack: center;
  box-pack: center;
  /* Modern browsers */
  justify-content: center;
}
.hbox.baseline,
.vbox.baseline,
.baseline {
  /* Old browsers */
  -webkit-box-pack: baseline;
  -moz-box-pack: baseline;
  box-pack: baseline;
  /* Modern browsers */
  justify-content: baseline;
}
.hbox.stretch,
.vbox.stretch,
.stretch {
  /* Old browsers */
  -webkit-box-pack: stretch;
  -moz-box-pack: stretch;
  box-pack: stretch;
  /* Modern browsers */
  justify-content: stretch;
}
.hbox.align-start,
.vbox.align-start,
.align-start {
  /* Old browsers */
  -webkit-box-align: start;
  -moz-box-align: start;
  box-align: start;
  /* Modern browsers */
  align-items: flex-start;
}
.hbox.align-end,
.vbox.align-end,
.align-end {
  /* Old browsers */
  -webkit-box-align: end;
  -moz-box-align: end;
  box-align: end;
  /* Modern browsers */
  align-items: flex-end;
}
.hbox.align-center,
.vbox.align-center,
.align-center {
  /* Old browsers */
  -webkit-box-align: center;
  -moz-box-align: center;
  box-align: center;
  /* Modern browsers */
  align-items: center;
}
.hbox.align-baseline,
.vbox.align-baseline,
.align-baseline {
  /* Old browsers */
  -webkit-box-align: baseline;
  -moz-box-align: baseline;
  box-align: baseline;
  /* Modern browsers */
  align-items: baseline;
}
.hbox.align-stretch,
.vbox.align-stretch,
.align-stretch {
  /* Old browsers */
  -webkit-box-align: stretch;
  -moz-box-align: stretch;
  box-align: stretch;
  /* Modern browsers */
  align-items: stretch;
}
div.error {
  margin: 2em;
  text-align: center;
}
div.error > h1 {
  font-size: 500%;
  line-height: normal;
}
div.error > p {
  font-size: 200%;
  line-height: normal;
}
div.traceback-wrapper {
  text-align: left;
  max-width: 800px;
  margin: auto;
}
div.traceback-wrapper pre.traceback {
  max-height: 600px;
  overflow: auto;
}
/**
 * Primary styles
 *
 * Author: Jupyter Development Team
 */
body {
  background-color: #fff;
  /* This makes sure that the body covers the entire window and needs to
       be in a different element than the display: box in wrapper below */
  position: absolute;
  left: 0px;
  right: 0px;
  top: 0px;
  bottom: 0px;
  overflow: visible;
}
body > #header {
  /* Initially hidden to prevent FLOUC */
  display: none;
  background-color: #fff;
  /* Display over codemirror */
  position: relative;
  z-index: 100;
}
body > #header #header-container {
  display: flex;
  flex-direction: row;
  justify-content: space-between;
  padding: 5px;
  padding-bottom: 5px;
  padding-top: 5px;
  box-sizing: border-box;
  -moz-box-sizing: border-box;
  -webkit-box-sizing: border-box;
}
body > #header .header-bar {
  width: 100%;
  height: 1px;
  background: #e7e7e7;
  margin-bottom: -1px;
}
@media print {
  body > #header {
    display: none !important;
  }
}
#header-spacer {
  width: 100%;
  visibility: hidden;
}
@media print {
  #header-spacer {
    display: none;
  }
}
#ipython_notebook {
  padding-left: 0px;
  padding-top: 1px;
  padding-bottom: 1px;
}
[dir="rtl"] #ipython_notebook {
  margin-right: 10px;
  margin-left: 0;
}
[dir="rtl"] #ipython_notebook.pull-left {
  float: right !important;
  float: right;
}
.flex-spacer {
  flex: 1;
}
#noscript {
  width: auto;
  padding-top: 16px;
  padding-bottom: 16px;
  text-align: center;
  font-size: 22px;
  color: red;
  font-weight: bold;
}
#ipython_notebook img {
  height: 28px;
}
#site {
  width: 100%;
  display: none;
  box-sizing: border-box;
  -moz-box-sizing: border-box;
  -webkit-box-sizing: border-box;
  overflow: auto;
}
@media print {
  #site {
    height: auto !important;
  }
}
/* Smaller buttons */
.ui-button .ui-button-text {
  padding: 0.2em 0.8em;
  font-size: 77%;
}
input.ui-button {
  padding: 0.3em 0.9em;
}
span#kernel_logo_widget {
  margin: 0 10px;
}
span#login_widget {
  float: right;
}
[dir="rtl"] span#login_widget {
  float: left;
}
span#login_widget > .button,
#logout {
  color: #333;
  background-color: #fff;
  border-color: #ccc;
}
span#login_widget > .button:focus,
#logout:focus,
span#login_widget > .button.focus,
#logout.focus {
  color: #333;
  background-color: #e6e6e6;
  border-color: #8c8c8c;
}
span#login_widget > .button:hover,
#logout:hover {
  color: #333;
  background-color: #e6e6e6;
  border-color: #adadad;
}
span#login_widget > .button:active,
#logout:active,
span#login_widget > .button.active,
#logout.active,
.open > .dropdown-togglespan#login_widget > .button,
.open > .dropdown-toggle#logout {
  color: #333;
  background-color: #e6e6e6;
  border-color: #adadad;
}
span#login_widget > .button:active:hover,
#logout:active:hover,
span#login_widget > .button.active:hover,
#logout.active:hover,
.open > .dropdown-togglespan#login_widget > .button:hover,
.open > .dropdown-toggle#logout:hover,
span#login_widget > .button:active:focus,
#logout:active:focus,
span#login_widget > .button.active:focus,
#logout.active:focus,
.open > .dropdown-togglespan#login_widget > .button:focus,
.open > .dropdown-toggle#logout:focus,
span#login_widget > .button:active.focus,
#logout:active.focus,
span#login_widget > .button.active.focus,
#logout.active.focus,
.open > .dropdown-togglespan#login_widget > .button.focus,
.open > .dropdown-toggle#logout.focus {
  color: #333;
  background-color: #d4d4d4;
  border-color: #8c8c8c;
}
span#login_widget > .button:active,
#logout:active,
span#login_widget > .button.active,
#logout.active,
.open > .dropdown-togglespan#login_widget > .button,
.open > .dropdown-toggle#logout {
  background-image: none;
}
span#login_widget > .button.disabled:hover,
#logout.disabled:hover,
span#login_widget > .button[disabled]:hover,
#logout[disabled]:hover,
fieldset[disabled] span#login_widget > .button:hover,
fieldset[disabled] #logout:hover,
span#login_widget > .button.disabled:focus,
#logout.disabled:focus,
span#login_widget > .button[disabled]:focus,
#logout[disabled]:focus,
fieldset[disabled] span#login_widget > .button:focus,
fieldset[disabled] #logout:focus,
span#login_widget > .button.disabled.focus,
#logout.disabled.focus,
span#login_widget > .button[disabled].focus,
#logout[disabled].focus,
fieldset[disabled] span#login_widget > .button.focus,
fieldset[disabled] #logout.focus {
  background-color: #fff;
  border-color: #ccc;
}
span#login_widget > .button .badge,
#logout .badge {
  color: #fff;
  background-color: #333;
}
.nav-header {
  text-transform: none;
}
#header > span {
  margin-top: 10px;
}
.modal_stretch .modal-dialog {
  /* Old browsers */
  display: -webkit-box;
  -webkit-box-orient: vertical;
  -webkit-box-align: stretch;
  display: -moz-box;
  -moz-box-orient: vertical;
  -moz-box-align: stretch;
  display: box;
  box-orient: vertical;
  box-align: stretch;
  /* Modern browsers */
  display: flex;
  flex-direction: column;
  align-items: stretch;
  min-height: 80vh;
}
.modal_stretch .modal-dialog .modal-body {
  max-height: calc(100vh - 200px);
  overflow: auto;
  flex: 1;
}
.modal-header {
  cursor: move;
}
@media (min-width: 768px) {
  .modal .modal-dialog {
    width: 700px;
  }
}
@media (min-width: 768px) {
  select.form-control {
    margin-left: 12px;
    margin-right: 12px;
  }
}
/*!
*
* IPython auth
*
*/
.center-nav {
  display: inline-block;
  margin-bottom: -4px;
}
[dir="rtl"] .center-nav form.pull-left {
  float: right !important;
  float: right;
}
[dir="rtl"] .center-nav .navbar-text {
  float: right;
}
[dir="rtl"] .navbar-inner {
  text-align: right;
}
[dir="rtl"] div.text-left {
  text-align: right;
}
/*!
*
* IPython tree view
*
*/
/* We need an invisible input field on top of the sentense*/
/* "Drag file onto the list ..." */
.alternate_upload {
  background-color: none;
  display: inline;
}
.alternate_upload.form {
  padding: 0;
  margin: 0;
}
.alternate_upload input.fileinput {
  position: absolute;
  display: block;
  width: 100%;
  height: 100%;
  overflow: hidden;
  cursor: pointer;
  opacity: 0;
  z-index: 2;
}
.alternate_upload .btn-xs > input.fileinput {
  margin: -1px -5px;
}
.alternate_upload .btn-upload {
  position: relative;
  height: 22px;
}
::-webkit-file-upload-button {
  cursor: pointer;
}
/**
 * Primary styles
 *
 * Author: Jupyter Development Team
 */
ul#tabs {
  margin-bottom: 4px;
}
ul#tabs a {
  padding-top: 6px;
  padding-bottom: 4px;
}
[dir="rtl"] ul#tabs.nav-tabs > li {
  float: right;
}
[dir="rtl"] ul#tabs.nav.nav-tabs {
  padding-right: 0;
}
ul.breadcrumb a:focus,
ul.breadcrumb a:hover {
  text-decoration: none;
}
ul.breadcrumb i.icon-home {
  font-size: 16px;
  margin-right: 4px;
}
ul.breadcrumb span {
  color: #5e5e5e;
}
.list_toolbar {
  padding: 4px 0 4px 0;
  vertical-align: middle;
}
.list_toolbar .tree-buttons {
  padding-top: 1px;
}
[dir="rtl"] .list_toolbar .tree-buttons .pull-right {
  float: left !important;
  float: left;
}
[dir="rtl"] .list_toolbar .col-sm-4,
[dir="rtl"] .list_toolbar .col-sm-8 {
  float: right;
}
.dynamic-buttons {
  padding-top: 3px;
  display: inline-block;
}
.list_toolbar [class*="span"] {
  min-height: 24px;
}
.list_header {
  font-weight: bold;
  background-color: #EEE;
}
.list_placeholder {
  font-weight: bold;
  padding-top: 4px;
  padding-bottom: 4px;
  padding-left: 7px;
  padding-right: 7px;
}
.list_container {
  margin-top: 4px;
  margin-bottom: 20px;
  border: 1px solid #ddd;
  border-radius: 2px;
}
.list_container > div {
  border-bottom: 1px solid #ddd;
}
.list_container > div:hover .list-item {
  background-color: red;
}
.list_container > div:last-child {
  border: none;
}
.list_item:hover .list_item {
  background-color: #ddd;
}
.list_item a {
  text-decoration: none;
}
.list_item:hover {
  background-color: #fafafa;
}
.list_header > div,
.list_item > div {
  padding-top: 4px;
  padding-bottom: 4px;
  padding-left: 7px;
  padding-right: 7px;
  line-height: 22px;
}
.list_header > div input,
.list_item > div input {
  margin-right: 7px;
  margin-left: 14px;
  vertical-align: text-bottom;
  line-height: 22px;
  position: relative;
  top: -1px;
}
.list_header > div .item_link,
.list_item > div .item_link {
  margin-left: -1px;
  vertical-align: baseline;
  line-height: 22px;
}
[dir="rtl"] .list_item > div input {
  margin-right: 0;
}
.new-file input[type=checkbox] {
  visibility: hidden;
}
.item_name {
  line-height: 22px;
  height: 24px;
}
.item_icon {
  font-size: 14px;
  color: #5e5e5e;
  margin-right: 7px;
  margin-left: 7px;
  line-height: 22px;
  vertical-align: baseline;
}
.item_modified {
  margin-right: 7px;
  margin-left: 7px;
}
[dir="rtl"] .item_modified.pull-right {
  float: left !important;
  float: left;
}
.item_buttons {
  line-height: 1em;
  margin-left: -5px;
}
.item_buttons .btn,
.item_buttons .btn-group,
.item_buttons .input-group {
  float: left;
}
.item_buttons > .btn,
.item_buttons > .btn-group,
.item_buttons > .input-group {
  margin-left: 5px;
}
.item_buttons .btn {
  min-width: 13ex;
}
.item_buttons .running-indicator {
  padding-top: 4px;
  color: #5cb85c;
}
.item_buttons .kernel-name {
  padding-top: 4px;
  color: #5bc0de;
  margin-right: 7px;
  float: left;
}
[dir="rtl"] .item_buttons.pull-right {
  float: left !important;
  float: left;
}
[dir="rtl"] .item_buttons .kernel-name {
  margin-left: 7px;
  float: right;
}
.toolbar_info {
  height: 24px;
  line-height: 24px;
}
.list_item input:not([type=checkbox]) {
  padding-top: 3px;
  padding-bottom: 3px;
  height: 22px;
  line-height: 14px;
  margin: 0px;
}
.highlight_text {
  color: blue;
}
#project_name {
  display: inline-block;
  padding-left: 7px;
  margin-left: -2px;
}
#project_name > .breadcrumb {
  padding: 0px;
  margin-bottom: 0px;
  background-color: transparent;
  font-weight: bold;
}
.sort_button {
  display: inline-block;
  padding-left: 7px;
}
[dir="rtl"] .sort_button.pull-right {
  float: left !important;
  float: left;
}
#tree-selector {
  padding-right: 0px;
}
#button-select-all {
  min-width: 50px;
}
[dir="rtl"] #button-select-all.btn {
  float: right ;
}
#select-all {
  margin-left: 7px;
  margin-right: 2px;
  margin-top: 2px;
  height: 16px;
}
[dir="rtl"] #select-all.pull-left {
  float: right !important;
  float: right;
}
.menu_icon {
  margin-right: 2px;
}
.tab-content .row {
  margin-left: 0px;
  margin-right: 0px;
}
.folder_icon:before {
  display: inline-block;
  font: normal normal normal 14px/1 FontAwesome;
  font-size: inherit;
  text-rendering: auto;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  content: "\f114";
}
.folder_icon:before.fa-pull-left {
  margin-right: .3em;
}
.folder_icon:before.fa-pull-right {
  margin-left: .3em;
}
.folder_icon:before.pull-left {
  margin-right: .3em;
}
.folder_icon:before.pull-right {
  margin-left: .3em;
}
.notebook_icon:before {
  display: inline-block;
  font: normal normal normal 14px/1 FontAwesome;
  font-size: inherit;
  text-rendering: auto;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  content: "\f02d";
  position: relative;
  top: -1px;
}
.notebook_icon:before.fa-pull-left {
  margin-right: .3em;
}
.notebook_icon:before.fa-pull-right {
  margin-left: .3em;
}
.notebook_icon:before.pull-left {
  margin-right: .3em;
}
.notebook_icon:before.pull-right {
  margin-left: .3em;
}
.running_notebook_icon:before {
  display: inline-block;
  font: normal normal normal 14px/1 FontAwesome;
  font-size: inherit;
  text-rendering: auto;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  content: "\f02d";
  position: relative;
  top: -1px;
  color: #5cb85c;
}
.running_notebook_icon:before.fa-pull-left {
  margin-right: .3em;
}
.running_notebook_icon:before.fa-pull-right {
  margin-left: .3em;
}
.running_notebook_icon:before.pull-left {
  margin-right: .3em;
}
.running_notebook_icon:before.pull-right {
  margin-left: .3em;
}
.file_icon:before {
  display: inline-block;
  font: normal normal normal 14px/1 FontAwesome;
  font-size: inherit;
  text-rendering: auto;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  content: "\f016";
  position: relative;
  top: -2px;
}
.file_icon:before.fa-pull-left {
  margin-right: .3em;
}
.file_icon:before.fa-pull-right {
  margin-left: .3em;
}
.file_icon:before.pull-left {
  margin-right: .3em;
}
.file_icon:before.pull-right {
  margin-left: .3em;
}
#notebook_toolbar .pull-right {
  padding-top: 0px;
  margin-right: -1px;
}
ul#new-menu {
  left: auto;
  right: 0;
}
#new-menu .dropdown-header {
  font-size: 10px;
  border-bottom: 1px solid #e5e5e5;
  padding: 0 0 3px;
  margin: -3px 20px 0;
}
.kernel-menu-icon {
  padding-right: 12px;
  width: 24px;
  content: "\f096";
}
.kernel-menu-icon:before {
  content: "\f096";
}
.kernel-menu-icon-current:before {
  content: "\f00c";
}
#tab_content {
  padding-top: 20px;
}
#running .panel-group .panel {
  margin-top: 3px;
  margin-bottom: 1em;
}
#running .panel-group .panel .panel-heading {
  background-color: #EEE;
  padding-top: 4px;
  padding-bottom: 4px;
  padding-left: 7px;
  padding-right: 7px;
  line-height: 22px;
}
#running .panel-group .panel .panel-heading a:focus,
#running .panel-group .panel .panel-heading a:hover {
  text-decoration: none;
}
#running .panel-group .panel .panel-body {
  padding: 0px;
}
#running .panel-group .panel .panel-body .list_container {
  margin-top: 0px;
  margin-bottom: 0px;
  border: 0px;
  border-radius: 0px;
}
#running .panel-group .panel .panel-body .list_container .list_item {
  border-bottom: 1px solid #ddd;
}
#running .panel-group .panel .panel-body .list_container .list_item:last-child {
  border-bottom: 0px;
}
.delete-button {
  display: none;
}
.duplicate-button {
  display: none;
}
.rename-button {
  display: none;
}
.move-button {
  display: none;
}
.download-button {
  display: none;
}
.shutdown-button {
  display: none;
}
.dynamic-instructions {
  display: inline-block;
  padding-top: 4px;
}
/*!
*
* IPython text editor webapp
*
*/
.selected-keymap i.fa {
  padding: 0px 5px;
}
.selected-keymap i.fa:before {
  content: "\f00c";
}
#mode-menu {
  overflow: auto;
  max-height: 20em;
}
.edit_app #header {
  -webkit-box-shadow: 0px 0px 12px 1px rgba(87, 87, 87, 0.2);
  box-shadow: 0px 0px 12px 1px rgba(87, 87, 87, 0.2);
}
.edit_app #menubar .navbar {
  /* Use a negative 1 bottom margin, so the border overlaps the border of the
    header */
  margin-bottom: -1px;
}
.dirty-indicator {
  display: inline-block;
  font: normal normal normal 14px/1 FontAwesome;
  font-size: inherit;
  text-rendering: auto;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  width: 20px;
}
.dirty-indicator.fa-pull-left {
  margin-right: .3em;
}
.dirty-indicator.fa-pull-right {
  margin-left: .3em;
}
.dirty-indicator.pull-left {
  margin-right: .3em;
}
.dirty-indicator.pull-right {
  margin-left: .3em;
}
.dirty-indicator-dirty {
  display: inline-block;
  font: normal normal normal 14px/1 FontAwesome;
  font-size: inherit;
  text-rendering: auto;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  width: 20px;
}
.dirty-indicator-dirty.fa-pull-left {
  margin-right: .3em;
}
.dirty-indicator-dirty.fa-pull-right {
  margin-left: .3em;
}
.dirty-indicator-dirty.pull-left {
  margin-right: .3em;
}
.dirty-indicator-dirty.pull-right {
  margin-left: .3em;
}
.dirty-indicator-clean {
  display: inline-block;
  font: normal normal normal 14px/1 FontAwesome;
  font-size: inherit;
  text-rendering: auto;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  width: 20px;
}
.dirty-indicator-clean.fa-pull-left {
  margin-right: .3em;
}
.dirty-indicator-clean.fa-pull-right {
  margin-left: .3em;
}
.dirty-indicator-clean.pull-left {
  margin-right: .3em;
}
.dirty-indicator-clean.pull-right {
  margin-left: .3em;
}
.dirty-indicator-clean:before {
  display: inline-block;
  font: normal normal normal 14px/1 FontAwesome;
  font-size: inherit;
  text-rendering: auto;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  content: "\f00c";
}
.dirty-indicator-clean:before.fa-pull-left {
  margin-right: .3em;
}
.dirty-indicator-clean:before.fa-pull-right {
  margin-left: .3em;
}
.dirty-indicator-clean:before.pull-left {
  margin-right: .3em;
}
.dirty-indicator-clean:before.pull-right {
  margin-left: .3em;
}
#filename {
  font-size: 16pt;
  display: table;
  padding: 0px 5px;
}
#current-mode {
  padding-left: 5px;
  padding-right: 5px;
}
#texteditor-backdrop {
  padding-top: 20px;
  padding-bottom: 20px;
}
@media not print {
  #texteditor-backdrop {
    background-color: #EEE;
  }
}
@media print {
  #texteditor-backdrop #texteditor-container .CodeMirror-gutter,
  #texteditor-backdrop #texteditor-container .CodeMirror-gutters {
    background-color: #fff;
  }
}
@media not print {
  #texteditor-backdrop #texteditor-container .CodeMirror-gutter,
  #texteditor-backdrop #texteditor-container .CodeMirror-gutters {
    background-color: #fff;
  }
}
@media not print {
  #texteditor-backdrop #texteditor-container {
    padding: 0px;
    background-color: #fff;
    -webkit-box-shadow: 0px 0px 12px 1px rgba(87, 87, 87, 0.2);
    box-shadow: 0px 0px 12px 1px rgba(87, 87, 87, 0.2);
  }
}
.CodeMirror-dialog {
  background-color: #fff;
}
/*!
*
* IPython notebook
*
*/
/* CSS font colors for translated ANSI escape sequences */
/* The color values are a mix of
   http://www.xcolors.net/dl/baskerville-ivorylight and
   http://www.xcolors.net/dl/euphrasia */
.ansi-black-fg {
  color: #3E424D;
}
.ansi-black-bg {
  background-color: #3E424D;
}
.ansi-black-intense-fg {
  color: #282C36;
}
.ansi-black-intense-bg {
  background-color: #282C36;
}
.ansi-red-fg {
  color: #E75C58;
}
.ansi-red-bg {
  background-color: #E75C58;
}
.ansi-red-intense-fg {
  color: #B22B31;
}
.ansi-red-intense-bg {
  background-color: #B22B31;
}
.ansi-green-fg {
  color: #00A250;
}
.ansi-green-bg {
  background-color: #00A250;
}
.ansi-green-intense-fg {
  color: #007427;
}
.ansi-green-intense-bg {
  background-color: #007427;
}
.ansi-yellow-fg {
  color: #DDB62B;
}
.ansi-yellow-bg {
  background-color: #DDB62B;
}
.ansi-yellow-intense-fg {
  color: #B27D12;
}
.ansi-yellow-intense-bg {
  background-color: #B27D12;
}
.ansi-blue-fg {
  color: #208FFB;
}
.ansi-blue-bg {
  background-color: #208FFB;
}
.ansi-blue-intense-fg {
  color: #0065CA;
}
.ansi-blue-intense-bg {
  background-color: #0065CA;
}
.ansi-magenta-fg {
  color: #D160C4;
}
.ansi-magenta-bg {
  background-color: #D160C4;
}
.ansi-magenta-intense-fg {
  color: #A03196;
}
.ansi-magenta-intense-bg {
  background-color: #A03196;
}
.ansi-cyan-fg {
  color: #60C6C8;
}
.ansi-cyan-bg {
  background-color: #60C6C8;
}
.ansi-cyan-intense-fg {
  color: #258F8F;
}
.ansi-cyan-intense-bg {
  background-color: #258F8F;
}
.ansi-white-fg {
  color: #C5C1B4;
}
.ansi-white-bg {
  background-color: #C5C1B4;
}
.ansi-white-intense-fg {
  color: #A1A6B2;
}
.ansi-white-intense-bg {
  background-color: #A1A6B2;
}
.ansi-default-inverse-fg {
  color: #FFFFFF;
}
.ansi-default-inverse-bg {
  background-color: #000000;
}
.ansi-bold {
  font-weight: bold;
}
.ansi-underline {
  text-decoration: underline;
}
/* The following styles are deprecated an will be removed in a future version */
.ansibold {
  font-weight: bold;
}
.ansi-inverse {
  outline: 0.5px dotted;
}
/* use dark versions for foreground, to improve visibility */
.ansiblack {
  color: black;
}
.ansired {
  color: darkred;
}
.ansigreen {
  color: darkgreen;
}
.ansiyellow {
  color: #c4a000;
}
.ansiblue {
  color: darkblue;
}
.ansipurple {
  color: darkviolet;
}
.ansicyan {
  color: steelblue;
}
.ansigray {
  color: gray;
}
/* and light for background, for the same reason */
.ansibgblack {
  background-color: black;
}
.ansibgred {
  background-color: red;
}
.ansibggreen {
  background-color: green;
}
.ansibgyellow {
  background-color: yellow;
}
.ansibgblue {
  background-color: blue;
}
.ansibgpurple {
  background-color: magenta;
}
.ansibgcyan {
  background-color: cyan;
}
.ansibggray {
  background-color: gray;
}
div.cell {
  /* Old browsers */
  display: -webkit-box;
  -webkit-box-orient: vertical;
  -webkit-box-align: stretch;
  display: -moz-box;
  -moz-box-orient: vertical;
  -moz-box-align: stretch;
  display: box;
  box-orient: vertical;
  box-align: stretch;
  /* Modern browsers */
  display: flex;
  flex-direction: column;
  align-items: stretch;
  border-radius: 2px;
  box-sizing: border-box;
  -moz-box-sizing: border-box;
  -webkit-box-sizing: border-box;
  border-width: 1px;
  border-style: solid;
  border-color: transparent;
  width: 100%;
  padding: 5px;
  /* This acts as a spacer between cells, that is outside the border */
  margin: 0px;
  outline: none;
  position: relative;
  overflow: visible;
}
div.cell:before {
  position: absolute;
  display: block;
  top: -1px;
  left: -1px;
  width: 5px;
  height: calc(100% +  2px);
  content: '';
  background: transparent;
}
div.cell.jupyter-soft-selected {
  border-left-color: #E3F2FD;
  border-left-width: 1px;
  padding-left: 5px;
  border-right-color: #E3F2FD;
  border-right-width: 1px;
  background: #E3F2FD;
}
@media print {
  div.cell.jupyter-soft-selected {
    border-color: transparent;
  }
}
div.cell.selected,
div.cell.selected.jupyter-soft-selected {
  border-color: #ababab;
}
div.cell.selected:before,
div.cell.selected.jupyter-soft-selected:before {
  position: absolute;
  display: block;
  top: -1px;
  left: -1px;
  width: 5px;
  height: calc(100% +  2px);
  content: '';
  background: #42A5F5;
}
@media print {
  div.cell.selected,
  div.cell.selected.jupyter-soft-selected {
    border-color: transparent;
  }
}
.edit_mode div.cell.selected {
  border-color: #66BB6A;
}
.edit_mode div.cell.selected:before {
  position: absolute;
  display: block;
  top: -1px;
  left: -1px;
  width: 5px;
  height: calc(100% +  2px);
  content: '';
  background: #66BB6A;
}
@media print {
  .edit_mode div.cell.selected {
    border-color: transparent;
  }
}
.prompt {
  /* This needs to be wide enough for 3 digit prompt numbers: In[100]: */
  min-width: 14ex;
  /* This padding is tuned to match the padding on the CodeMirror editor. */
  padding: 0.4em;
  margin: 0px;
  font-family: monospace;
  text-align: right;
  /* This has to match that of the the CodeMirror class line-height below */
  line-height: 1.21429em;
  /* Don't highlight prompt number selection */
  -webkit-touch-callout: none;
  -webkit-user-select: none;
  -khtml-user-select: none;
  -moz-user-select: none;
  -ms-user-select: none;
  user-select: none;
  /* Use default cursor */
  cursor: default;
}
@media (max-width: 540px) {
  .prompt {
    text-align: left;
  }
}
div.inner_cell {
  min-width: 0;
  /* Old browsers */
  display: -webkit-box;
  -webkit-box-orient: vertical;
  -webkit-box-align: stretch;
  display: -moz-box;
  -moz-box-orient: vertical;
  -moz-box-align: stretch;
  display: box;
  box-orient: vertical;
  box-align: stretch;
  /* Modern browsers */
  display: flex;
  flex-direction: column;
  align-items: stretch;
  /* Old browsers */
  -webkit-box-flex: 1;
  -moz-box-flex: 1;
  box-flex: 1;
  /* Modern browsers */
  flex: 1;
}
/* input_area and input_prompt must match in top border and margin for alignment */
div.input_area {
  border: 1px solid #cfcfcf;
  border-radius: 2px;
  background: #f7f7f7;
  line-height: 1.21429em;
}
/* This is needed so that empty prompt areas can collapse to zero height when there
   is no content in the output_subarea and the prompt. The main purpose of this is
   to make sure that empty JavaScript output_subareas have no height. */
div.prompt:empty {
  padding-top: 0;
  padding-bottom: 0;
}
div.unrecognized_cell {
  padding: 5px 5px 5px 0px;
  /* Old browsers */
  display: -webkit-box;
  -webkit-box-orient: horizontal;
  -webkit-box-align: stretch;
  display: -moz-box;
  -moz-box-orient: horizontal;
  -moz-box-align: stretch;
  display: box;
  box-orient: horizontal;
  box-align: stretch;
  /* Modern browsers */
  display: flex;
  flex-direction: row;
  align-items: stretch;
}
div.unrecognized_cell .inner_cell {
  border-radius: 2px;
  padding: 5px;
  font-weight: bold;
  color: red;
  border: 1px solid #cfcfcf;
  background: #eaeaea;
}
div.unrecognized_cell .inner_cell a {
  color: inherit;
  text-decoration: none;
}
div.unrecognized_cell .inner_cell a:hover {
  color: inherit;
  text-decoration: none;
}
@media (max-width: 540px) {
  div.unrecognized_cell > div.prompt {
    display: none;
  }
}
div.code_cell {
  /* avoid page breaking on code cells when printing */
}
@media print {
  div.code_cell {
    page-break-inside: avoid;
  }
}
/* any special styling for code cells that are currently running goes here */
div.input {
  page-break-inside: avoid;
  /* Old browsers */
  display: -webkit-box;
  -webkit-box-orient: horizontal;
  -webkit-box-align: stretch;
  display: -moz-box;
  -moz-box-orient: horizontal;
  -moz-box-align: stretch;
  display: box;
  box-orient: horizontal;
  box-align: stretch;
  /* Modern browsers */
  display: flex;
  flex-direction: row;
  align-items: stretch;
}
@media (max-width: 540px) {
  div.input {
    /* Old browsers */
    display: -webkit-box;
    -webkit-box-orient: vertical;
    -webkit-box-align: stretch;
    display: -moz-box;
    -moz-box-orient: vertical;
    -moz-box-align: stretch;
    display: box;
    box-orient: vertical;
    box-align: stretch;
    /* Modern browsers */
    display: flex;
    flex-direction: column;
    align-items: stretch;
  }
}
/* input_area and input_prompt must match in top border and margin for alignment */
div.input_prompt {
  color: #303F9F;
  border-top: 1px solid transparent;
}
div.input_area > div.highlight {
  margin: 0.4em;
  border: none;
  padding: 0px;
  background-color: transparent;
}
div.input_area > div.highlight > pre {
  margin: 0px;
  border: none;
  padding: 0px;
  background-color: transparent;
}
/* The following gets added to the <head> if it is detected that the user has a
 * monospace font with inconsistent normal/bold/italic height.  See
 * notebookmain.js.  Such fonts will have keywords vertically offset with
 * respect to the rest of the text.  The user should select a better font.
 * See: https://github.com/ipython/ipython/issues/1503
 *
 * .CodeMirror span {
 *      vertical-align: bottom;
 * }
 */
.CodeMirror {
  line-height: 1.21429em;
  /* Changed from 1em to our global default */
  font-size: 14px;
  height: auto;
  /* Changed to auto to autogrow */
  background: none;
  /* Changed from white to allow our bg to show through */
}
.CodeMirror-scroll {
  /*  The CodeMirror docs are a bit fuzzy on if overflow-y should be hidden or visible.*/
  /*  We have found that if it is visible, vertical scrollbars appear with font size changes.*/
  overflow-y: hidden;
  overflow-x: auto;
}
.CodeMirror-lines {
  /* In CM2, this used to be 0.4em, but in CM3 it went to 4px. We need the em value because */
  /* we have set a different line-height and want this to scale with that. */
  /* Note that this should set vertical padding only, since CodeMirror assumes
       that horizontal padding will be set on CodeMirror pre */
  padding: 0.4em 0;
}
.CodeMirror-linenumber {
  padding: 0 8px 0 4px;
}
.CodeMirror-gutters {
  border-bottom-left-radius: 2px;
  border-top-left-radius: 2px;
}
.CodeMirror pre {
  /* In CM3 this went to 4px from 0 in CM2. This sets horizontal padding only,
    use .CodeMirror-lines for vertical */
  padding: 0 0.4em;
  border: 0;
  border-radius: 0;
}
.CodeMirror-cursor {
  border-left: 1.4px solid black;
}
@media screen and (min-width: 2138px) and (max-width: 4319px) {
  .CodeMirror-cursor {
    border-left: 2px solid black;
  }
}
@media screen and (min-width: 4320px) {
  .CodeMirror-cursor {
    border-left: 4px solid black;
  }
}
/*

Original style from softwaremaniacs.org (c) Ivan Sagalaev <Maniac@SoftwareManiacs.Org>
Adapted from GitHub theme

*/
.highlight-base {
  color: #000;
}
.highlight-variable {
  color: #000;
}
.highlight-variable-2 {
  color: #1a1a1a;
}
.highlight-variable-3 {
  color: #333333;
}
.highlight-string {
  color: #BA2121;
}
.highlight-comment {
  color: #408080;
  font-style: italic;
}
.highlight-number {
  color: #080;
}
.highlight-atom {
  color: #88F;
}
.highlight-keyword {
  color: #008000;
  font-weight: bold;
}
.highlight-builtin {
  color: #008000;
}
.highlight-error {
  color: #f00;
}
.highlight-operator {
  color: #AA22FF;
  font-weight: bold;
}
.highlight-meta {
  color: #AA22FF;
}
/* previously not defined, copying from default codemirror */
.highlight-def {
  color: #00f;
}
.highlight-string-2 {
  color: #f50;
}
.highlight-qualifier {
  color: #555;
}
.highlight-bracket {
  color: #997;
}
.highlight-tag {
  color: #170;
}
.highlight-attribute {
  color: #00c;
}
.highlight-header {
  color: blue;
}
.highlight-quote {
  color: #090;
}
.highlight-link {
  color: #00c;
}
/* apply the same style to codemirror */
.cm-s-ipython span.cm-keyword {
  color: #008000;
  font-weight: bold;
}
.cm-s-ipython span.cm-atom {
  color: #88F;
}
.cm-s-ipython span.cm-number {
  color: #080;
}
.cm-s-ipython span.cm-def {
  color: #00f;
}
.cm-s-ipython span.cm-variable {
  color: #000;
}
.cm-s-ipython span.cm-operator {
  color: #AA22FF;
  font-weight: bold;
}
.cm-s-ipython span.cm-variable-2 {
  color: #1a1a1a;
}
.cm-s-ipython span.cm-variable-3 {
  color: #333333;
}
.cm-s-ipython span.cm-comment {
  color: #408080;
  font-style: italic;
}
.cm-s-ipython span.cm-string {
  color: #BA2121;
}
.cm-s-ipython span.cm-string-2 {
  color: #f50;
}
.cm-s-ipython span.cm-meta {
  color: #AA22FF;
}
.cm-s-ipython span.cm-qualifier {
  color: #555;
}
.cm-s-ipython span.cm-builtin {
  color: #008000;
}
.cm-s-ipython span.cm-bracket {
  color: #997;
}
.cm-s-ipython span.cm-tag {
  color: #170;
}
.cm-s-ipython span.cm-attribute {
  color: #00c;
}
.cm-s-ipython span.cm-header {
  color: blue;
}
.cm-s-ipython span.cm-quote {
  color: #090;
}
.cm-s-ipython span.cm-link {
  color: #00c;
}
.cm-s-ipython span.cm-error {
  color: #f00;
}
.cm-s-ipython span.cm-tab {
  background: url(data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAADAAAAAMCAYAAAAkuj5RAAAAAXNSR0IArs4c6QAAAGFJREFUSMft1LsRQFAQheHPowAKoACx3IgEKtaEHujDjORSgWTH/ZOdnZOcM/sgk/kFFWY0qV8foQwS4MKBCS3qR6ixBJvElOobYAtivseIE120FaowJPN75GMu8j/LfMwNjh4HUpwg4LUAAAAASUVORK5CYII=);
  background-position: right;
  background-repeat: no-repeat;
}
div.output_wrapper {
  /* this position must be relative to enable descendents to be absolute within it */
  position: relative;
  /* Old browsers */
  display: -webkit-box;
  -webkit-box-orient: vertical;
  -webkit-box-align: stretch;
  display: -moz-box;
  -moz-box-orient: vertical;
  -moz-box-align: stretch;
  display: box;
  box-orient: vertical;
  box-align: stretch;
  /* Modern browsers */
  display: flex;
  flex-direction: column;
  align-items: stretch;
  z-index: 1;
}
/* class for the output area when it should be height-limited */
div.output_scroll {
  /* ideally, this would be max-height, but FF barfs all over that */
  height: 24em;
  /* FF needs this *and the wrapper* to specify full width, or it will shrinkwrap */
  width: 100%;
  overflow: auto;
  border-radius: 2px;
  -webkit-box-shadow: inset 0 2px 8px rgba(0, 0, 0, 0.8);
  box-shadow: inset 0 2px 8px rgba(0, 0, 0, 0.8);
  display: block;
}
/* output div while it is collapsed */
div.output_collapsed {
  margin: 0px;
  padding: 0px;
  /* Old browsers */
  display: -webkit-box;
  -webkit-box-orient: vertical;
  -webkit-box-align: stretch;
  display: -moz-box;
  -moz-box-orient: vertical;
  -moz-box-align: stretch;
  display: box;
  box-orient: vertical;
  box-align: stretch;
  /* Modern browsers */
  display: flex;
  flex-direction: column;
  align-items: stretch;
}
div.out_prompt_overlay {
  height: 100%;
  padding: 0px 0.4em;
  position: absolute;
  border-radius: 2px;
}
div.out_prompt_overlay:hover {
  /* use inner shadow to get border that is computed the same on WebKit/FF */
  -webkit-box-shadow: inset 0 0 1px #000;
  box-shadow: inset 0 0 1px #000;
  background: rgba(240, 240, 240, 0.5);
}
div.output_prompt {
  color: #D84315;
}
/* This class is the outer container of all output sections. */
div.output_area {
  padding: 0px;
  page-break-inside: avoid;
  /* Old browsers */
  display: -webkit-box;
  -webkit-box-orient: horizontal;
  -webkit-box-align: stretch;
  display: -moz-box;
  -moz-box-orient: horizontal;
  -moz-box-align: stretch;
  display: box;
  box-orient: horizontal;
  box-align: stretch;
  /* Modern browsers */
  display: flex;
  flex-direction: row;
  align-items: stretch;
}
div.output_area .MathJax_Display {
  text-align: left !important;
}
div.output_area .rendered_html table {
  margin-left: 0;
  margin-right: 0;
}
div.output_area .rendered_html img {
  margin-left: 0;
  margin-right: 0;
}
div.output_area img,
div.output_area svg {
  max-width: 100%;
  height: auto;
}
div.output_area img.unconfined,
div.output_area svg.unconfined {
  max-width: none;
}
div.output_area .mglyph > img {
  max-width: none;
}
/* This is needed to protect the pre formating from global settings such
   as that of bootstrap */
.output {
  /* Old browsers */
  display: -webkit-box;
  -webkit-box-orient: vertical;
  -webkit-box-align: stretch;
  display: -moz-box;
  -moz-box-orient: vertical;
  -moz-box-align: stretch;
  display: box;
  box-orient: vertical;
  box-align: stretch;
  /* Modern browsers */
  display: flex;
  flex-direction: column;
  align-items: stretch;
}
@media (max-width: 540px) {
  div.output_area {
    /* Old browsers */
    display: -webkit-box;
    -webkit-box-orient: vertical;
    -webkit-box-align: stretch;
    display: -moz-box;
    -moz-box-orient: vertical;
    -moz-box-align: stretch;
    display: box;
    box-orient: vertical;
    box-align: stretch;
    /* Modern browsers */
    display: flex;
    flex-direction: column;
    align-items: stretch;
  }
}
div.output_area pre {
  margin: 0;
  padding: 1px 0 1px 0;
  border: 0;
  vertical-align: baseline;
  color: black;
  background-color: transparent;
  border-radius: 0;
}
/* This class is for the output subarea inside the output_area and after
   the prompt div. */
div.output_subarea {
  overflow-x: auto;
  padding: 0.4em;
  /* Old browsers */
  -webkit-box-flex: 1;
  -moz-box-flex: 1;
  box-flex: 1;
  /* Modern browsers */
  flex: 1;
  max-width: calc(100% - 14ex);
}
div.output_scroll div.output_subarea {
  overflow-x: visible;
}
/* The rest of the output_* classes are for special styling of the different
   output types */
/* all text output has this class: */
div.output_text {
  text-align: left;
  color: #000;
  /* This has to match that of the the CodeMirror class line-height below */
  line-height: 1.21429em;
}
/* stdout/stderr are 'text' as well as 'stream', but execute_result/error are *not* streams */
div.output_stderr {
  background: #fdd;
  /* very light red background for stderr */
}
div.output_latex {
  text-align: left;
}
/* Empty output_javascript divs should have no height */
div.output_javascript:empty {
  padding: 0;
}
.js-error {
  color: darkred;
}
/* raw_input styles */
div.raw_input_container {
  line-height: 1.21429em;
  padding-top: 5px;
}
pre.raw_input_prompt {
  /* nothing needed here. */
}
input.raw_input {
  font-family: monospace;
  font-size: inherit;
  color: inherit;
  width: auto;
  /* make sure input baseline aligns with prompt */
  vertical-align: baseline;
  /* padding + margin = 0.5em between prompt and cursor */
  padding: 0em 0.25em;
  margin: 0em 0.25em;
}
input.raw_input:focus {
  box-shadow: none;
}
p.p-space {
  margin-bottom: 10px;
}
div.output_unrecognized {
  padding: 5px;
  font-weight: bold;
  color: red;
}
div.output_unrecognized a {
  color: inherit;
  text-decoration: none;
}
div.output_unrecognized a:hover {
  color: inherit;
  text-decoration: none;
}
.rendered_html {
  color: #000;
  /* any extras will just be numbers: */
}
.rendered_html em {
  font-style: italic;
}
.rendered_html strong {
  font-weight: bold;
}
.rendered_html u {
  text-decoration: underline;
}
.rendered_html :link {
  text-decoration: underline;
}
.rendered_html :visited {
  text-decoration: underline;
}
.rendered_html h1 {
  font-size: 185.7%;
  margin: 1.08em 0 0 0;
  font-weight: bold;
  line-height: 1.0;
}
.rendered_html h2 {
  font-size: 157.1%;
  margin: 1.27em 0 0 0;
  font-weight: bold;
  line-height: 1.0;
}
.rendered_html h3 {
  font-size: 128.6%;
  margin: 1.55em 0 0 0;
  font-weight: bold;
  line-height: 1.0;
}
.rendered_html h4 {
  font-size: 100%;
  margin: 2em 0 0 0;
  font-weight: bold;
  line-height: 1.0;
}
.rendered_html h5 {
  font-size: 100%;
  margin: 2em 0 0 0;
  font-weight: bold;
  line-height: 1.0;
  font-style: italic;
}
.rendered_html h6 {
  font-size: 100%;
  margin: 2em 0 0 0;
  font-weight: bold;
  line-height: 1.0;
  font-style: italic;
}
.rendered_html h1:first-child {
  margin-top: 0.538em;
}
.rendered_html h2:first-child {
  margin-top: 0.636em;
}
.rendered_html h3:first-child {
  margin-top: 0.777em;
}
.rendered_html h4:first-child {
  margin-top: 1em;
}
.rendered_html h5:first-child {
  margin-top: 1em;
}
.rendered_html h6:first-child {
  margin-top: 1em;
}
.rendered_html ul:not(.list-inline),
.rendered_html ol:not(.list-inline) {
  padding-left: 2em;
}
.rendered_html ul {
  list-style: disc;
}
.rendered_html ul ul {
  list-style: square;
  margin-top: 0;
}
.rendered_html ul ul ul {
  list-style: circle;
}
.rendered_html ol {
  list-style: decimal;
}
.rendered_html ol ol {
  list-style: upper-alpha;
  margin-top: 0;
}
.rendered_html ol ol ol {
  list-style: lower-alpha;
}
.rendered_html ol ol ol ol {
  list-style: lower-roman;
}
.rendered_html ol ol ol ol ol {
  list-style: decimal;
}
.rendered_html * + ul {
  margin-top: 1em;
}
.rendered_html * + ol {
  margin-top: 1em;
}
.rendered_html hr {
  color: black;
  background-color: black;
}
.rendered_html pre {
  margin: 1em 2em;
  padding: 0px;
  background-color: #fff;
}
.rendered_html code {
  background-color: #eff0f1;
}
.rendered_html p code {
  padding: 1px 5px;
}
.rendered_html pre code {
  background-color: #fff;
}
.rendered_html pre,
.rendered_html code {
  border: 0;
  color: #000;
  font-size: 100%;
}
.rendered_html blockquote {
  margin: 1em 2em;
}
.rendered_html table {
  margin-left: auto;
  margin-right: auto;
  border: none;
  border-collapse: collapse;
  border-spacing: 0;
  color: black;
  font-size: 12px;
  table-layout: fixed;
}
.rendered_html thead {
  border-bottom: 1px solid black;
  vertical-align: bottom;
}
.rendered_html tr,
.rendered_html th,
.rendered_html td {
  text-align: right;
  vertical-align: middle;
  padding: 0.5em 0.5em;
  line-height: normal;
  white-space: normal;
  max-width: none;
  border: none;
}
.rendered_html th {
  font-weight: bold;
}
.rendered_html tbody tr:nth-child(odd) {
  background: #f5f5f5;
}
.rendered_html tbody tr:hover {
  background: rgba(66, 165, 245, 0.2);
}
.rendered_html * + table {
  margin-top: 1em;
}
.rendered_html p {
  text-align: left;
}
.rendered_html * + p {
  margin-top: 1em;
}
.rendered_html img {
  display: block;
  margin-left: auto;
  margin-right: auto;
}
.rendered_html * + img {
  margin-top: 1em;
}
.rendered_html img,
.rendered_html svg {
  max-width: 100%;
  height: auto;
}
.rendered_html img.unconfined,
.rendered_html svg.unconfined {
  max-width: none;
}
.rendered_html .alert {
  margin-bottom: initial;
}
.rendered_html * + .alert {
  margin-top: 1em;
}
[dir="rtl"] .rendered_html p {
  text-align: right;
}
div.text_cell {
  /* Old browsers */
  display: -webkit-box;
  -webkit-box-orient: horizontal;
  -webkit-box-align: stretch;
  display: -moz-box;
  -moz-box-orient: horizontal;
  -moz-box-align: stretch;
  display: box;
  box-orient: horizontal;
  box-align: stretch;
  /* Modern browsers */
  display: flex;
  flex-direction: row;
  align-items: stretch;
}
@media (max-width: 540px) {
  div.text_cell > div.prompt {
    display: none;
  }
}
div.text_cell_render {
  /*font-family: "Helvetica Neue", Arial, Helvetica, Geneva, sans-serif;*/
  outline: none;
  resize: none;
  width: inherit;
  border-style: none;
  padding: 0.5em 0.5em 0.5em 0.4em;
  color: #000;
  box-sizing: border-box;
  -moz-box-sizing: border-box;
  -webkit-box-sizing: border-box;
}
a.anchor-link:link {
  text-decoration: none;
  padding: 0px 20px;
  visibility: hidden;
}
h1:hover .anchor-link,
h2:hover .anchor-link,
h3:hover .anchor-link,
h4:hover .anchor-link,
h5:hover .anchor-link,
h6:hover .anchor-link {
  visibility: visible;
}
.text_cell.rendered .input_area {
  display: none;
}
.text_cell.rendered .rendered_html {
  overflow-x: auto;
  overflow-y: hidden;
}
.text_cell.rendered .rendered_html tr,
.text_cell.rendered .rendered_html th,
.text_cell.rendered .rendered_html td {
  max-width: none;
}
.text_cell.unrendered .text_cell_render {
  display: none;
}
.text_cell .dropzone .input_area {
  border: 2px dashed #bababa;
  margin: -1px;
}
.cm-header-1,
.cm-header-2,
.cm-header-3,
.cm-header-4,
.cm-header-5,
.cm-header-6 {
  font-weight: bold;
  font-family: "Helvetica Neue", Helvetica, Arial, sans-serif;
}
.cm-header-1 {
  font-size: 185.7%;
}
.cm-header-2 {
  font-size: 157.1%;
}
.cm-header-3 {
  font-size: 128.6%;
}
.cm-header-4 {
  font-size: 110%;
}
.cm-header-5 {
  font-size: 100%;
  font-style: italic;
}
.cm-header-6 {
  font-size: 100%;
  font-style: italic;
}
/*!
*
* IPython notebook webapp
*
*/
@media (max-width: 767px) {
  .notebook_app {
    padding-left: 0px;
    padding-right: 0px;
  }
}
#ipython-main-app {
  box-sizing: border-box;
  -moz-box-sizing: border-box;
  -webkit-box-sizing: border-box;
  height: 100%;
}
div#notebook_panel {
  margin: 0px;
  padding: 0px;
  box-sizing: border-box;
  -moz-box-sizing: border-box;
  -webkit-box-sizing: border-box;
  height: 100%;
}
div#notebook {
  font-size: 14px;
  line-height: 20px;
  overflow-y: hidden;
  overflow-x: auto;
  width: 100%;
  /* This spaces the page away from the edge of the notebook area */
  padding-top: 20px;
  margin: 0px;
  outline: none;
  box-sizing: border-box;
  -moz-box-sizing: border-box;
  -webkit-box-sizing: border-box;
  min-height: 100%;
}
@media not print {
  #notebook-container {
    padding: 15px;
    background-color: #fff;
    min-height: 0;
    -webkit-box-shadow: 0px 0px 12px 1px rgba(87, 87, 87, 0.2);
    box-shadow: 0px 0px 12px 1px rgba(87, 87, 87, 0.2);
  }
}
@media print {
  #notebook-container {
    width: 100%;
  }
}
div.ui-widget-content {
  border: 1px solid #ababab;
  outline: none;
}
pre.dialog {
  background-color: #f7f7f7;
  border: 1px solid #ddd;
  border-radius: 2px;
  padding: 0.4em;
  padding-left: 2em;
}
p.dialog {
  padding: 0.2em;
}
/* Word-wrap output correctly.  This is the CSS3 spelling, though Firefox seems
   to not honor it correctly.  Webkit browsers (Chrome, rekonq, Safari) do.
 */
pre,
code,
kbd,
samp {
  white-space: pre-wrap;
}
#fonttest {
  font-family: monospace;
}
p {
  margin-bottom: 0;
}
.end_space {
  min-height: 100px;
  transition: height .2s ease;
}
.notebook_app > #header {
  -webkit-box-shadow: 0px 0px 12px 1px rgba(87, 87, 87, 0.2);
  box-shadow: 0px 0px 12px 1px rgba(87, 87, 87, 0.2);
}
@media not print {
  .notebook_app {
    background-color: #EEE;
  }
}
kbd {
  border-style: solid;
  border-width: 1px;
  box-shadow: none;
  margin: 2px;
  padding-left: 2px;
  padding-right: 2px;
  padding-top: 1px;
  padding-bottom: 1px;
}
.jupyter-keybindings {
  padding: 1px;
  line-height: 24px;
  border-bottom: 1px solid gray;
}
.jupyter-keybindings input {
  margin: 0;
  padding: 0;
  border: none;
}
.jupyter-keybindings i {
  padding: 6px;
}
.well code {
  background-color: #ffffff;
  border-color: #ababab;
  border-width: 1px;
  border-style: solid;
  padding: 2px;
  padding-top: 1px;
  padding-bottom: 1px;
}
/* CSS for the cell toolbar */
.celltoolbar {
  border: thin solid #CFCFCF;
  border-bottom: none;
  background: #EEE;
  border-radius: 2px 2px 0px 0px;
  width: 100%;
  height: 29px;
  padding-right: 4px;
  /* Old browsers */
  display: -webkit-box;
  -webkit-box-orient: horizontal;
  -webkit-box-align: stretch;
  display: -moz-box;
  -moz-box-orient: horizontal;
  -moz-box-align: stretch;
  display: box;
  box-orient: horizontal;
  box-align: stretch;
  /* Modern browsers */
  display: flex;
  flex-direction: row;
  align-items: stretch;
  /* Old browsers */
  -webkit-box-pack: end;
  -moz-box-pack: end;
  box-pack: end;
  /* Modern browsers */
  justify-content: flex-end;
  display: -webkit-flex;
}
@media print {
  .celltoolbar {
    display: none;
  }
}
.ctb_hideshow {
  display: none;
  vertical-align: bottom;
}
/* ctb_show is added to the ctb_hideshow div to show the cell toolbar.
   Cell toolbars are only shown when the ctb_global_show class is also set.
*/
.ctb_global_show .ctb_show.ctb_hideshow {
  display: block;
}
.ctb_global_show .ctb_show + .input_area,
.ctb_global_show .ctb_show + div.text_cell_input,
.ctb_global_show .ctb_show ~ div.text_cell_render {
  border-top-right-radius: 0px;
  border-top-left-radius: 0px;
}
.ctb_global_show .ctb_show ~ div.text_cell_render {
  border: 1px solid #cfcfcf;
}
.celltoolbar {
  font-size: 87%;
  padding-top: 3px;
}
.celltoolbar select {
  display: block;
  width: 100%;
  height: 32px;
  padding: 6px 12px;
  font-size: 13px;
  line-height: 1.42857143;
  color: #555555;
  background-color: #fff;
  background-image: none;
  border: 1px solid #ccc;
  border-radius: 2px;
  -webkit-box-shadow: inset 0 1px 1px rgba(0, 0, 0, 0.075);
  box-shadow: inset 0 1px 1px rgba(0, 0, 0, 0.075);
  -webkit-transition: border-color ease-in-out .15s, box-shadow ease-in-out .15s;
  -o-transition: border-color ease-in-out .15s, box-shadow ease-in-out .15s;
  transition: border-color ease-in-out .15s, box-shadow ease-in-out .15s;
  height: 30px;
  padding: 5px 10px;
  font-size: 12px;
  line-height: 1.5;
  border-radius: 1px;
  width: inherit;
  font-size: inherit;
  height: 22px;
  padding: 0px;
  display: inline-block;
}
.celltoolbar select:focus {
  border-color: #66afe9;
  outline: 0;
  -webkit-box-shadow: inset 0 1px 1px rgba(0,0,0,.075), 0 0 8px rgba(102, 175, 233, 0.6);
  box-shadow: inset 0 1px 1px rgba(0,0,0,.075), 0 0 8px rgba(102, 175, 233, 0.6);
}
.celltoolbar select::-moz-placeholder {
  color: #999;
  opacity: 1;
}
.celltoolbar select:-ms-input-placeholder {
  color: #999;
}
.celltoolbar select::-webkit-input-placeholder {
  color: #999;
}
.celltoolbar select::-ms-expand {
  border: 0;
  background-color: transparent;
}
.celltoolbar select[disabled],
.celltoolbar select[readonly],
fieldset[disabled] .celltoolbar select {
  background-color: #eeeeee;
  opacity: 1;
}
.celltoolbar select[disabled],
fieldset[disabled] .celltoolbar select {
  cursor: not-allowed;
}
textarea.celltoolbar select {
  height: auto;
}
select.celltoolbar select {
  height: 30px;
  line-height: 30px;
}
textarea.celltoolbar select,
select[multiple].celltoolbar select {
  height: auto;
}
.celltoolbar label {
  margin-left: 5px;
  margin-right: 5px;
}
.tags_button_container {
  width: 100%;
  display: flex;
}
.tag-container {
  display: flex;
  flex-direction: row;
  flex-grow: 1;
  overflow: hidden;
  position: relative;
}
.tag-container > * {
  margin: 0 4px;
}
.remove-tag-btn {
  margin-left: 4px;
}
.tags-input {
  display: flex;
}
.cell-tag:last-child:after {
  content: "";
  position: absolute;
  right: 0;
  width: 40px;
  height: 100%;
  /* Fade to background color of cell toolbar */
  background: linear-gradient(to right, rgba(0, 0, 0, 0), #EEE);
}
.tags-input > * {
  margin-left: 4px;
}
.cell-tag,
.tags-input input,
.tags-input button {
  display: block;
  width: 100%;
  height: 32px;
  padding: 6px 12px;
  font-size: 13px;
  line-height: 1.42857143;
  color: #555555;
  background-color: #fff;
  background-image: none;
  border: 1px solid #ccc;
  border-radius: 2px;
  -webkit-box-shadow: inset 0 1px 1px rgba(0, 0, 0, 0.075);
  box-shadow: inset 0 1px 1px rgba(0, 0, 0, 0.075);
  -webkit-transition: border-color ease-in-out .15s, box-shadow ease-in-out .15s;
  -o-transition: border-color ease-in-out .15s, box-shadow ease-in-out .15s;
  transition: border-color ease-in-out .15s, box-shadow ease-in-out .15s;
  height: 30px;
  padding: 5px 10px;
  font-size: 12px;
  line-height: 1.5;
  border-radius: 1px;
  box-shadow: none;
  width: inherit;
  font-size: inherit;
  height: 22px;
  line-height: 22px;
  padding: 0px 4px;
  display: inline-block;
}
.cell-tag:focus,
.tags-input input:focus,
.tags-input button:focus {
  border-color: #66afe9;
  outline: 0;
  -webkit-box-shadow: inset 0 1px 1px rgba(0,0,0,.075), 0 0 8px rgba(102, 175, 233, 0.6);
  box-shadow: inset 0 1px 1px rgba(0,0,0,.075), 0 0 8px rgba(102, 175, 233, 0.6);
}
.cell-tag::-moz-placeholder,
.tags-input input::-moz-placeholder,
.tags-input button::-moz-placeholder {
  color: #999;
  opacity: 1;
}
.cell-tag:-ms-input-placeholder,
.tags-input input:-ms-input-placeholder,
.tags-input button:-ms-input-placeholder {
  color: #999;
}
.cell-tag::-webkit-input-placeholder,
.tags-input input::-webkit-input-placeholder,
.tags-input button::-webkit-input-placeholder {
  color: #999;
}
.cell-tag::-ms-expand,
.tags-input input::-ms-expand,
.tags-input button::-ms-expand {
  border: 0;
  background-color: transparent;
}
.cell-tag[disabled],
.tags-input input[disabled],
.tags-input button[disabled],
.cell-tag[readonly],
.tags-input input[readonly],
.tags-input button[readonly],
fieldset[disabled] .cell-tag,
fieldset[disabled] .tags-input input,
fieldset[disabled] .tags-input button {
  background-color: #eeeeee;
  opacity: 1;
}
.cell-tag[disabled],
.tags-input input[disabled],
.tags-input button[disabled],
fieldset[disabled] .cell-tag,
fieldset[disabled] .tags-input input,
fieldset[disabled] .tags-input button {
  cursor: not-allowed;
}
textarea.cell-tag,
textarea.tags-input input,
textarea.tags-input button {
  height: auto;
}
select.cell-tag,
select.tags-input input,
select.tags-input button {
  height: 30px;
  line-height: 30px;
}
textarea.cell-tag,
textarea.tags-input input,
textarea.tags-input button,
select[multiple].cell-tag,
select[multiple].tags-input input,
select[multiple].tags-input button {
  height: auto;
}
.cell-tag,
.tags-input button {
  padding: 0px 4px;
}
.cell-tag {
  background-color: #fff;
  white-space: nowrap;
}
.tags-input input[type=text]:focus {
  outline: none;
  box-shadow: none;
  border-color: #ccc;
}
.completions {
  position: absolute;
  z-index: 110;
  overflow: hidden;
  border: 1px solid #ababab;
  border-radius: 2px;
  -webkit-box-shadow: 0px 6px 10px -1px #adadad;
  box-shadow: 0px 6px 10px -1px #adadad;
  line-height: 1;
}
.completions select {
  background: white;
  outline: none;
  border: none;
  padding: 0px;
  margin: 0px;
  overflow: auto;
  font-family: monospace;
  font-size: 110%;
  color: #000;
  width: auto;
}
.completions select option.context {
  color: #286090;
}
#kernel_logo_widget .current_kernel_logo {
  display: none;
  margin-top: -1px;
  margin-bottom: -1px;
  width: 32px;
  height: 32px;
}
[dir="rtl"] #kernel_logo_widget {
  float: left !important;
  float: left;
}
.modal .modal-body .move-path {
  display: flex;
  flex-direction: row;
  justify-content: space;
  align-items: center;
}
.modal .modal-body .move-path .server-root {
  padding-right: 20px;
}
.modal .modal-body .move-path .path-input {
  flex: 1;
}
#menubar {
  box-sizing: border-box;
  -moz-box-sizing: border-box;
  -webkit-box-sizing: border-box;
  margin-top: 1px;
}
#menubar .navbar {
  border-top: 1px;
  border-radius: 0px 0px 2px 2px;
  margin-bottom: 0px;
}
#menubar .navbar-toggle {
  float: left;
  padding-top: 7px;
  padding-bottom: 7px;
  border: none;
}
#menubar .navbar-collapse {
  clear: left;
}
[dir="rtl"] #menubar .navbar-toggle {
  float: right;
}
[dir="rtl"] #menubar .navbar-collapse {
  clear: right;
}
[dir="rtl"] #menubar .navbar-nav {
  float: right;
}
[dir="rtl"] #menubar .nav {
  padding-right: 0px;
}
[dir="rtl"] #menubar .navbar-nav > li {
  float: right;
}
[dir="rtl"] #menubar .navbar-right {
  float: left !important;
}
[dir="rtl"] ul.dropdown-menu {
  text-align: right;
  left: auto;
}
[dir="rtl"] ul#new-menu.dropdown-menu {
  right: auto;
  left: 0;
}
.nav-wrapper {
  border-bottom: 1px solid #e7e7e7;
}
i.menu-icon {
  padding-top: 4px;
}
[dir="rtl"] i.menu-icon.pull-right {
  float: left !important;
  float: left;
}
ul#help_menu li a {
  overflow: hidden;
  padding-right: 2.2em;
}
ul#help_menu li a i {
  margin-right: -1.2em;
}
[dir="rtl"] ul#help_menu li a {
  padding-left: 2.2em;
}
[dir="rtl"] ul#help_menu li a i {
  margin-right: 0;
  margin-left: -1.2em;
}
[dir="rtl"] ul#help_menu li a i.pull-right {
  float: left !important;
  float: left;
}
.dropdown-submenu {
  position: relative;
}
.dropdown-submenu > .dropdown-menu {
  top: 0;
  left: 100%;
  margin-top: -6px;
  margin-left: -1px;
}
[dir="rtl"] .dropdown-submenu > .dropdown-menu {
  right: 100%;
  margin-right: -1px;
}
.dropdown-submenu:hover > .dropdown-menu {
  display: block;
}
.dropdown-submenu > a:after {
  display: inline-block;
  font: normal normal normal 14px/1 FontAwesome;
  font-size: inherit;
  text-rendering: auto;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  display: block;
  content: "\f0da";
  float: right;
  color: #333333;
  margin-top: 2px;
  margin-right: -10px;
}
.dropdown-submenu > a:after.fa-pull-left {
  margin-right: .3em;
}
.dropdown-submenu > a:after.fa-pull-right {
  margin-left: .3em;
}
.dropdown-submenu > a:after.pull-left {
  margin-right: .3em;
}
.dropdown-submenu > a:after.pull-right {
  margin-left: .3em;
}
[dir="rtl"] .dropdown-submenu > a:after {
  float: left;
  content: "\f0d9";
  margin-right: 0;
  margin-left: -10px;
}
.dropdown-submenu:hover > a:after {
  color: #262626;
}
.dropdown-submenu.pull-left {
  float: none;
}
.dropdown-submenu.pull-left > .dropdown-menu {
  left: -100%;
  margin-left: 10px;
}
#notification_area {
  float: right !important;
  float: right;
  z-index: 10;
}
[dir="rtl"] #notification_area {
  float: left !important;
  float: left;
}
.indicator_area {
  float: right !important;
  float: right;
  color: #777;
  margin-left: 5px;
  margin-right: 5px;
  width: 11px;
  z-index: 10;
  text-align: center;
  width: auto;
}
[dir="rtl"] .indicator_area {
  float: left !important;
  float: left;
}
#kernel_indicator {
  float: right !important;
  float: right;
  color: #777;
  margin-left: 5px;
  margin-right: 5px;
  width: 11px;
  z-index: 10;
  text-align: center;
  width: auto;
  border-left: 1px solid;
}
#kernel_indicator .kernel_indicator_name {
  padding-left: 5px;
  padding-right: 5px;
}
[dir="rtl"] #kernel_indicator {
  float: left !important;
  float: left;
  border-left: 0;
  border-right: 1px solid;
}
#modal_indicator {
  float: right !important;
  float: right;
  color: #777;
  margin-left: 5px;
  margin-right: 5px;
  width: 11px;
  z-index: 10;
  text-align: center;
  width: auto;
}
[dir="rtl"] #modal_indicator {
  float: left !important;
  float: left;
}
#readonly-indicator {
  float: right !important;
  float: right;
  color: #777;
  margin-left: 5px;
  margin-right: 5px;
  width: 11px;
  z-index: 10;
  text-align: center;
  width: auto;
  margin-top: 2px;
  margin-bottom: 0px;
  margin-left: 0px;
  margin-right: 0px;
  display: none;
}
.modal_indicator:before {
  width: 1.28571429em;
  text-align: center;
}
.edit_mode .modal_indicator:before {
  display: inline-block;
  font: normal normal normal 14px/1 FontAwesome;
  font-size: inherit;
  text-rendering: auto;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  content: "\f040";
}
.edit_mode .modal_indicator:before.fa-pull-left {
  margin-right: .3em;
}
.edit_mode .modal_indicator:before.fa-pull-right {
  margin-left: .3em;
}
.edit_mode .modal_indicator:before.pull-left {
  margin-right: .3em;
}
.edit_mode .modal_indicator:before.pull-right {
  margin-left: .3em;
}
.command_mode .modal_indicator:before {
  display: inline-block;
  font: normal normal normal 14px/1 FontAwesome;
  font-size: inherit;
  text-rendering: auto;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  content: ' ';
}
.command_mode .modal_indicator:before.fa-pull-left {
  margin-right: .3em;
}
.command_mode .modal_indicator:before.fa-pull-right {
  margin-left: .3em;
}
.command_mode .modal_indicator:before.pull-left {
  margin-right: .3em;
}
.command_mode .modal_indicator:before.pull-right {
  margin-left: .3em;
}
.kernel_idle_icon:before {
  display: inline-block;
  font: normal normal normal 14px/1 FontAwesome;
  font-size: inherit;
  text-rendering: auto;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  content: "\f10c";
}
.kernel_idle_icon:before.fa-pull-left {
  margin-right: .3em;
}
.kernel_idle_icon:before.fa-pull-right {
  margin-left: .3em;
}
.kernel_idle_icon:before.pull-left {
  margin-right: .3em;
}
.kernel_idle_icon:before.pull-right {
  margin-left: .3em;
}
.kernel_busy_icon:before {
  display: inline-block;
  font: normal normal normal 14px/1 FontAwesome;
  font-size: inherit;
  text-rendering: auto;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  content: "\f111";
}
.kernel_busy_icon:before.fa-pull-left {
  margin-right: .3em;
}
.kernel_busy_icon:before.fa-pull-right {
  margin-left: .3em;
}
.kernel_busy_icon:before.pull-left {
  margin-right: .3em;
}
.kernel_busy_icon:before.pull-right {
  margin-left: .3em;
}
.kernel_dead_icon:before {
  display: inline-block;
  font: normal normal normal 14px/1 FontAwesome;
  font-size: inherit;
  text-rendering: auto;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  content: "\f1e2";
}
.kernel_dead_icon:before.fa-pull-left {
  margin-right: .3em;
}
.kernel_dead_icon:before.fa-pull-right {
  margin-left: .3em;
}
.kernel_dead_icon:before.pull-left {
  margin-right: .3em;
}
.kernel_dead_icon:before.pull-right {
  margin-left: .3em;
}
.kernel_disconnected_icon:before {
  display: inline-block;
  font: normal normal normal 14px/1 FontAwesome;
  font-size: inherit;
  text-rendering: auto;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  content: "\f127";
}
.kernel_disconnected_icon:before.fa-pull-left {
  margin-right: .3em;
}
.kernel_disconnected_icon:before.fa-pull-right {
  margin-left: .3em;
}
.kernel_disconnected_icon:before.pull-left {
  margin-right: .3em;
}
.kernel_disconnected_icon:before.pull-right {
  margin-left: .3em;
}
.notification_widget {
  color: #777;
  z-index: 10;
  background: rgba(240, 240, 240, 0.5);
  margin-right: 4px;
  color: #333;
  background-color: #fff;
  border-color: #ccc;
}
.notification_widget:focus,
.notification_widget.focus {
  color: #333;
  background-color: #e6e6e6;
  border-color: #8c8c8c;
}
.notification_widget:hover {
  color: #333;
  background-color: #e6e6e6;
  border-color: #adadad;
}
.notification_widget:active,
.notification_widget.active,
.open > .dropdown-toggle.notification_widget {
  color: #333;
  background-color: #e6e6e6;
  border-color: #adadad;
}
.notification_widget:active:hover,
.notification_widget.active:hover,
.open > .dropdown-toggle.notification_widget:hover,
.notification_widget:active:focus,
.notification_widget.active:focus,
.open > .dropdown-toggle.notification_widget:focus,
.notification_widget:active.focus,
.notification_widget.active.focus,
.open > .dropdown-toggle.notification_widget.focus {
  color: #333;
  background-color: #d4d4d4;
  border-color: #8c8c8c;
}
.notification_widget:active,
.notification_widget.active,
.open > .dropdown-toggle.notification_widget {
  background-image: none;
}
.notification_widget.disabled:hover,
.notification_widget[disabled]:hover,
fieldset[disabled] .notification_widget:hover,
.notification_widget.disabled:focus,
.notification_widget[disabled]:focus,
fieldset[disabled] .notification_widget:focus,
.notification_widget.disabled.focus,
.notification_widget[disabled].focus,
fieldset[disabled] .notification_widget.focus {
  background-color: #fff;
  border-color: #ccc;
}
.notification_widget .badge {
  color: #fff;
  background-color: #333;
}
.notification_widget.warning {
  color: #fff;
  background-color: #f0ad4e;
  border-color: #eea236;
}
.notification_widget.warning:focus,
.notification_widget.warning.focus {
  color: #fff;
  background-color: #ec971f;
  border-color: #985f0d;
}
.notification_widget.warning:hover {
  color: #fff;
  background-color: #ec971f;
  border-color: #d58512;
}
.notification_widget.warning:active,
.notification_widget.warning.active,
.open > .dropdown-toggle.notification_widget.warning {
  color: #fff;
  background-color: #ec971f;
  border-color: #d58512;
}
.notification_widget.warning:active:hover,
.notification_widget.warning.active:hover,
.open > .dropdown-toggle.notification_widget.warning:hover,
.notification_widget.warning:active:focus,
.notification_widget.warning.active:focus,
.open > .dropdown-toggle.notification_widget.warning:focus,
.notification_widget.warning:active.focus,
.notification_widget.warning.active.focus,
.open > .dropdown-toggle.notification_widget.warning.focus {
  color: #fff;
  background-color: #d58512;
  border-color: #985f0d;
}
.notification_widget.warning:active,
.notification_widget.warning.active,
.open > .dropdown-toggle.notification_widget.warning {
  background-image: none;
}
.notification_widget.warning.disabled:hover,
.notification_widget.warning[disabled]:hover,
fieldset[disabled] .notification_widget.warning:hover,
.notification_widget.warning.disabled:focus,
.notification_widget.warning[disabled]:focus,
fieldset[disabled] .notification_widget.warning:focus,
.notification_widget.warning.disabled.focus,
.notification_widget.warning[disabled].focus,
fieldset[disabled] .notification_widget.warning.focus {
  background-color: #f0ad4e;
  border-color: #eea236;
}
.notification_widget.warning .badge {
  color: #f0ad4e;
  background-color: #fff;
}
.notification_widget.success {
  color: #fff;
  background-color: #5cb85c;
  border-color: #4cae4c;
}
.notification_widget.success:focus,
.notification_widget.success.focus {
  color: #fff;
  background-color: #449d44;
  border-color: #255625;
}
.notification_widget.success:hover {
  color: #fff;
  background-color: #449d44;
  border-color: #398439;
}
.notification_widget.success:active,
.notification_widget.success.active,
.open > .dropdown-toggle.notification_widget.success {
  color: #fff;
  background-color: #449d44;
  border-color: #398439;
}
.notification_widget.success:active:hover,
.notification_widget.success.active:hover,
.open > .dropdown-toggle.notification_widget.success:hover,
.notification_widget.success:active:focus,
.notification_widget.success.active:focus,
.open > .dropdown-toggle.notification_widget.success:focus,
.notification_widget.success:active.focus,
.notification_widget.success.active.focus,
.open > .dropdown-toggle.notification_widget.success.focus {
  color: #fff;
  background-color: #398439;
  border-color: #255625;
}
.notification_widget.success:active,
.notification_widget.success.active,
.open > .dropdown-toggle.notification_widget.success {
  background-image: none;
}
.notification_widget.success.disabled:hover,
.notification_widget.success[disabled]:hover,
fieldset[disabled] .notification_widget.success:hover,
.notification_widget.success.disabled:focus,
.notification_widget.success[disabled]:focus,
fieldset[disabled] .notification_widget.success:focus,
.notification_widget.success.disabled.focus,
.notification_widget.success[disabled].focus,
fieldset[disabled] .notification_widget.success.focus {
  background-color: #5cb85c;
  border-color: #4cae4c;
}
.notification_widget.success .badge {
  color: #5cb85c;
  background-color: #fff;
}
.notification_widget.info {
  color: #fff;
  background-color: #5bc0de;
  border-color: #46b8da;
}
.notification_widget.info:focus,
.notification_widget.info.focus {
  color: #fff;
  background-color: #31b0d5;
  border-color: #1b6d85;
}
.notification_widget.info:hover {
  color: #fff;
  background-color: #31b0d5;
  border-color: #269abc;
}
.notification_widget.info:active,
.notification_widget.info.active,
.open > .dropdown-toggle.notification_widget.info {
  color: #fff;
  background-color: #31b0d5;
  border-color: #269abc;
}
.notification_widget.info:active:hover,
.notification_widget.info.active:hover,
.open > .dropdown-toggle.notification_widget.info:hover,
.notification_widget.info:active:focus,
.notification_widget.info.active:focus,
.open > .dropdown-toggle.notification_widget.info:focus,
.notification_widget.info:active.focus,
.notification_widget.info.active.focus,
.open > .dropdown-toggle.notification_widget.info.focus {
  color: #fff;
  background-color: #269abc;
  border-color: #1b6d85;
}
.notification_widget.info:active,
.notification_widget.info.active,
.open > .dropdown-toggle.notification_widget.info {
  background-image: none;
}
.notification_widget.info.disabled:hover,
.notification_widget.info[disabled]:hover,
fieldset[disabled] .notification_widget.info:hover,
.notification_widget.info.disabled:focus,
.notification_widget.info[disabled]:focus,
fieldset[disabled] .notification_widget.info:focus,
.notification_widget.info.disabled.focus,
.notification_widget.info[disabled].focus,
fieldset[disabled] .notification_widget.info.focus {
  background-color: #5bc0de;
  border-color: #46b8da;
}
.notification_widget.info .badge {
  color: #5bc0de;
  background-color: #fff;
}
.notification_widget.danger {
  color: #fff;
  background-color: #d9534f;
  border-color: #d43f3a;
}
.notification_widget.danger:focus,
.notification_widget.danger.focus {
  color: #fff;
  background-color: #c9302c;
  border-color: #761c19;
}
.notification_widget.danger:hover {
  color: #fff;
  background-color: #c9302c;
  border-color: #ac2925;
}
.notification_widget.danger:active,
.notification_widget.danger.active,
.open > .dropdown-toggle.notification_widget.danger {
  color: #fff;
  background-color: #c9302c;
  border-color: #ac2925;
}
.notification_widget.danger:active:hover,
.notification_widget.danger.active:hover,
.open > .dropdown-toggle.notification_widget.danger:hover,
.notification_widget.danger:active:focus,
.notification_widget.danger.active:focus,
.open > .dropdown-toggle.notification_widget.danger:focus,
.notification_widget.danger:active.focus,
.notification_widget.danger.active.focus,
.open > .dropdown-toggle.notification_widget.danger.focus {
  color: #fff;
  background-color: #ac2925;
  border-color: #761c19;
}
.notification_widget.danger:active,
.notification_widget.danger.active,
.open > .dropdown-toggle.notification_widget.danger {
  background-image: none;
}
.notification_widget.danger.disabled:hover,
.notification_widget.danger[disabled]:hover,
fieldset[disabled] .notification_widget.danger:hover,
.notification_widget.danger.disabled:focus,
.notification_widget.danger[disabled]:focus,
fieldset[disabled] .notification_widget.danger:focus,
.notification_widget.danger.disabled.focus,
.notification_widget.danger[disabled].focus,
fieldset[disabled] .notification_widget.danger.focus {
  background-color: #d9534f;
  border-color: #d43f3a;
}
.notification_widget.danger .badge {
  color: #d9534f;
  background-color: #fff;
}
div#pager {
  background-color: #fff;
  font-size: 14px;
  line-height: 20px;
  overflow: hidden;
  display: none;
  position: fixed;
  bottom: 0px;
  width: 100%;
  max-height: 50%;
  padding-top: 8px;
  -webkit-box-shadow: 0px 0px 12px 1px rgba(87, 87, 87, 0.2);
  box-shadow: 0px 0px 12px 1px rgba(87, 87, 87, 0.2);
  /* Display over codemirror */
  z-index: 100;
  /* Hack which prevents jquery ui resizable from changing top. */
  top: auto !important;
}
div#pager pre {
  line-height: 1.21429em;
  color: #000;
  background-color: #f7f7f7;
  padding: 0.4em;
}
div#pager #pager-button-area {
  position: absolute;
  top: 8px;
  right: 20px;
}
div#pager #pager-contents {
  position: relative;
  overflow: auto;
  width: 100%;
  height: 100%;
}
div#pager #pager-contents #pager-container {
  position: relative;
  padding: 15px 0px;
  box-sizing: border-box;
  -moz-box-sizing: border-box;
  -webkit-box-sizing: border-box;
}
div#pager .ui-resizable-handle {
  top: 0px;
  height: 8px;
  background: #f7f7f7;
  border-top: 1px solid #cfcfcf;
  border-bottom: 1px solid #cfcfcf;
  /* This injects handle bars (a short, wide = symbol) for 
        the resize handle. */
}
div#pager .ui-resizable-handle::after {
  content: '';
  top: 2px;
  left: 50%;
  height: 3px;
  width: 30px;
  margin-left: -15px;
  position: absolute;
  border-top: 1px solid #cfcfcf;
}
.quickhelp {
  /* Old browsers */
  display: -webkit-box;
  -webkit-box-orient: horizontal;
  -webkit-box-align: stretch;
  display: -moz-box;
  -moz-box-orient: horizontal;
  -moz-box-align: stretch;
  display: box;
  box-orient: horizontal;
  box-align: stretch;
  /* Modern browsers */
  display: flex;
  flex-direction: row;
  align-items: stretch;
  line-height: 1.8em;
}
.shortcut_key {
  display: inline-block;
  width: 21ex;
  text-align: right;
  font-family: monospace;
}
.shortcut_descr {
  display: inline-block;
  /* Old browsers */
  -webkit-box-flex: 1;
  -moz-box-flex: 1;
  box-flex: 1;
  /* Modern browsers */
  flex: 1;
}
span.save_widget {
  height: 30px;
  margin-top: 4px;
  display: flex;
  justify-content: flex-start;
  align-items: baseline;
  width: 50%;
  flex: 1;
}
span.save_widget span.filename {
  height: 100%;
  line-height: 1em;
  margin-left: 16px;
  border: none;
  font-size: 146.5%;
  text-overflow: ellipsis;
  overflow: hidden;
  white-space: nowrap;
  border-radius: 2px;
}
span.save_widget span.filename:hover {
  background-color: #e6e6e6;
}
[dir="rtl"] span.save_widget.pull-left {
  float: right !important;
  float: right;
}
[dir="rtl"] span.save_widget span.filename {
  margin-left: 0;
  margin-right: 16px;
}
span.checkpoint_status,
span.autosave_status {
  font-size: small;
  white-space: nowrap;
  padding: 0 5px;
}
@media (max-width: 767px) {
  span.save_widget {
    font-size: small;
    padding: 0 0 0 5px;
  }
  span.checkpoint_status,
  span.autosave_status {
    display: none;
  }
}
@media (min-width: 768px) and (max-width: 991px) {
  span.checkpoint_status {
    display: none;
  }
  span.autosave_status {
    font-size: x-small;
  }
}
.toolbar {
  padding: 0px;
  margin-left: -5px;
  margin-top: 2px;
  margin-bottom: 5px;
  box-sizing: border-box;
  -moz-box-sizing: border-box;
  -webkit-box-sizing: border-box;
}
.toolbar select,
.toolbar label {
  width: auto;
  vertical-align: middle;
  margin-right: 2px;
  margin-bottom: 0px;
  display: inline;
  font-size: 92%;
  margin-left: 0.3em;
  margin-right: 0.3em;
  padding: 0px;
  padding-top: 3px;
}
.toolbar .btn {
  padding: 2px 8px;
}
.toolbar .btn-group {
  margin-top: 0px;
  margin-left: 5px;
}
.toolbar-btn-label {
  margin-left: 6px;
}
#maintoolbar {
  margin-bottom: -3px;
  margin-top: -8px;
  border: 0px;
  min-height: 27px;
  margin-left: 0px;
  padding-top: 11px;
  padding-bottom: 3px;
}
#maintoolbar .navbar-text {
  float: none;
  vertical-align: middle;
  text-align: right;
  margin-left: 5px;
  margin-right: 0px;
  margin-top: 0px;
}
.select-xs {
  height: 24px;
}
[dir="rtl"] .btn-group > .btn,
.btn-group-vertical > .btn {
  float: right;
}
.pulse,
.dropdown-menu > li > a.pulse,
li.pulse > a.dropdown-toggle,
li.pulse.open > a.dropdown-toggle {
  background-color: #F37626;
  color: white;
}
/**
 * Primary styles
 *
 * Author: Jupyter Development Team
 */
/** WARNING IF YOU ARE EDITTING THIS FILE, if this is a .css file, It has a lot
 * of chance of beeing generated from the ../less/[samename].less file, you can
 * try to get back the less file by reverting somme commit in history
 **/
/*
 * We'll try to get something pretty, so we
 * have some strange css to have the scroll bar on
 * the left with fix button on the top right of the tooltip
 */
@-moz-keyframes fadeOut {
  from {
    opacity: 1;
  }
  to {
    opacity: 0;
  }
}
@-webkit-keyframes fadeOut {
  from {
    opacity: 1;
  }
  to {
    opacity: 0;
  }
}
@-moz-keyframes fadeIn {
  from {
    opacity: 0;
  }
  to {
    opacity: 1;
  }
}
@-webkit-keyframes fadeIn {
  from {
    opacity: 0;
  }
  to {
    opacity: 1;
  }
}
/*properties of tooltip after "expand"*/
.bigtooltip {
  overflow: auto;
  height: 200px;
  -webkit-transition-property: height;
  -webkit-transition-duration: 500ms;
  -moz-transition-property: height;
  -moz-transition-duration: 500ms;
  transition-property: height;
  transition-duration: 500ms;
}
/*properties of tooltip before "expand"*/
.smalltooltip {
  -webkit-transition-property: height;
  -webkit-transition-duration: 500ms;
  -moz-transition-property: height;
  -moz-transition-duration: 500ms;
  transition-property: height;
  transition-duration: 500ms;
  text-overflow: ellipsis;
  overflow: hidden;
  height: 80px;
}
.tooltipbuttons {
  position: absolute;
  padding-right: 15px;
  top: 0px;
  right: 0px;
}
.tooltiptext {
  /*avoid the button to overlap on some docstring*/
  padding-right: 30px;
}
.ipython_tooltip {
  max-width: 700px;
  /*fade-in animation when inserted*/
  -webkit-animation: fadeOut 400ms;
  -moz-animation: fadeOut 400ms;
  animation: fadeOut 400ms;
  -webkit-animation: fadeIn 400ms;
  -moz-animation: fadeIn 400ms;
  animation: fadeIn 400ms;
  vertical-align: middle;
  background-color: #f7f7f7;
  overflow: visible;
  border: #ababab 1px solid;
  outline: none;
  padding: 3px;
  margin: 0px;
  padding-left: 7px;
  font-family: monospace;
  min-height: 50px;
  -moz-box-shadow: 0px 6px 10px -1px #adadad;
  -webkit-box-shadow: 0px 6px 10px -1px #adadad;
  box-shadow: 0px 6px 10px -1px #adadad;
  border-radius: 2px;
  position: absolute;
  z-index: 1000;
}
.ipython_tooltip a {
  float: right;
}
.ipython_tooltip .tooltiptext pre {
  border: 0;
  border-radius: 0;
  font-size: 100%;
  background-color: #f7f7f7;
}
.pretooltiparrow {
  left: 0px;
  margin: 0px;
  top: -16px;
  width: 40px;
  height: 16px;
  overflow: hidden;
  position: absolute;
}
.pretooltiparrow:before {
  background-color: #f7f7f7;
  border: 1px #ababab solid;
  z-index: 11;
  content: "";
  position: absolute;
  left: 15px;
  top: 10px;
  width: 25px;
  height: 25px;
  -webkit-transform: rotate(45deg);
  -moz-transform: rotate(45deg);
  -ms-transform: rotate(45deg);
  -o-transform: rotate(45deg);
}
ul.typeahead-list i {
  margin-left: -10px;
  width: 18px;
}
[dir="rtl"] ul.typeahead-list i {
  margin-left: 0;
  margin-right: -10px;
}
ul.typeahead-list {
  max-height: 80vh;
  overflow: auto;
}
ul.typeahead-list > li > a {
  /** Firefox bug **/
  /* see https://github.com/jupyter/notebook/issues/559 */
  white-space: normal;
}
ul.typeahead-list  > li > a.pull-right {
  float: left !important;
  float: left;
}
[dir="rtl"] .typeahead-list {
  text-align: right;
}
.cmd-palette .modal-body {
  padding: 7px;
}
.cmd-palette form {
  background: white;
}
.cmd-palette input {
  outline: none;
}
.no-shortcut {
  min-width: 20px;
  color: transparent;
}
[dir="rtl"] .no-shortcut.pull-right {
  float: left !important;
  float: left;
}
[dir="rtl"] .command-shortcut.pull-right {
  float: left !important;
  float: left;
}
.command-shortcut:before {
  content: "(command mode)";
  padding-right: 3px;
  color: #777777;
}
.edit-shortcut:before {
  content: "(edit)";
  padding-right: 3px;
  color: #777777;
}
[dir="rtl"] .edit-shortcut.pull-right {
  float: left !important;
  float: left;
}
#find-and-replace #replace-preview .match,
#find-and-replace #replace-preview .insert {
  background-color: #BBDEFB;
  border-color: #90CAF9;
  border-style: solid;
  border-width: 1px;
  border-radius: 0px;
}
[dir="ltr"] #find-and-replace .input-group-btn + .form-control {
  border-left: none;
}
[dir="rtl"] #find-and-replace .input-group-btn + .form-control {
  border-right: none;
}
#find-and-replace #replace-preview .replace .match {
  background-color: #FFCDD2;
  border-color: #EF9A9A;
  border-radius: 0px;
}
#find-and-replace #replace-preview .replace .insert {
  background-color: #C8E6C9;
  border-color: #A5D6A7;
  border-radius: 0px;
}
#find-and-replace #replace-preview {
  max-height: 60vh;
  overflow: auto;
}
#find-and-replace #replace-preview pre {
  padding: 5px 10px;
}
.terminal-app {
  background: #EEE;
}
.terminal-app #header {
  background: #fff;
  -webkit-box-shadow: 0px 0px 12px 1px rgba(87, 87, 87, 0.2);
  box-shadow: 0px 0px 12px 1px rgba(87, 87, 87, 0.2);
}
.terminal-app .terminal {
  width: 100%;
  float: left;
  font-family: monospace;
  color: white;
  background: black;
  padding: 0.4em;
  border-radius: 2px;
  -webkit-box-shadow: 0px 0px 12px 1px rgba(87, 87, 87, 0.4);
  box-shadow: 0px 0px 12px 1px rgba(87, 87, 87, 0.4);
}
.terminal-app .terminal,
.terminal-app .terminal dummy-screen {
  line-height: 1em;
  font-size: 14px;
}
.terminal-app .terminal .xterm-rows {
  padding: 10px;
}
.terminal-app .terminal-cursor {
  color: black;
  background: white;
}
.terminal-app #terminado-container {
  margin-top: 20px;
}
/*# sourceMappingURL=style.min.css.map */
    </style>
<style type="text/css">
    .highlight .hll { background-color: #ffffcc }
.highlight  { background: #f8f8f8; }
.highlight .c { color: #408080; font-style: italic } /* Comment */
.highlight .err { border: 1px solid #FF0000 } /* Error */
.highlight .k { color: #008000; font-weight: bold } /* Keyword */
.highlight .o { color: #666666 } /* Operator */
.highlight .ch { color: #408080; font-style: italic } /* Comment.Hashbang */
.highlight .cm { color: #408080; font-style: italic } /* Comment.Multiline */
.highlight .cp { color: #BC7A00 } /* Comment.Preproc */
.highlight .cpf { color: #408080; font-style: italic } /* Comment.PreprocFile */
.highlight .c1 { color: #408080; font-style: italic } /* Comment.Single */
.highlight .cs { color: #408080; font-style: italic } /* Comment.Special */
.highlight .gd { color: #A00000 } /* Generic.Deleted */
.highlight .ge { font-style: italic } /* Generic.Emph */
.highlight .gr { color: #FF0000 } /* Generic.Error */
.highlight .gh { color: #000080; font-weight: bold } /* Generic.Heading */
.highlight .gi { color: #00A000 } /* Generic.Inserted */
.highlight .go { color: #888888 } /* Generic.Output */
.highlight .gp { color: #000080; font-weight: bold } /* Generic.Prompt */
.highlight .gs { font-weight: bold } /* Generic.Strong */
.highlight .gu { color: #800080; font-weight: bold } /* Generic.Subheading */
.highlight .gt { color: #0044DD } /* Generic.Traceback */
.highlight .kc { color: #008000; font-weight: bold } /* Keyword.Constant */
.highlight .kd { color: #008000; font-weight: bold } /* Keyword.Declaration */
.highlight .kn { color: #008000; font-weight: bold } /* Keyword.Namespace */
.highlight .kp { color: #008000 } /* Keyword.Pseudo */
.highlight .kr { color: #008000; font-weight: bold } /* Keyword.Reserved */
.highlight .kt { color: #B00040 } /* Keyword.Type */
.highlight .m { color: #666666 } /* Literal.Number */
.highlight .s { color: #BA2121 } /* Literal.String */
.highlight .na { color: #7D9029 } /* Name.Attribute */
.highlight .nb { color: #008000 } /* Name.Builtin */
.highlight .nc { color: #0000FF; font-weight: bold } /* Name.Class */
.highlight .no { color: #880000 } /* Name.Constant */
.highlight .nd { color: #AA22FF } /* Name.Decorator */
.highlight .ni { color: #999999; font-weight: bold } /* Name.Entity */
.highlight .ne { color: #D2413A; font-weight: bold } /* Name.Exception */
.highlight .nf { color: #0000FF } /* Name.Function */
.highlight .nl { color: #A0A000 } /* Name.Label */
.highlight .nn { color: #0000FF; font-weight: bold } /* Name.Namespace */
.highlight .nt { color: #008000; font-weight: bold } /* Name.Tag */
.highlight .nv { color: #19177C } /* Name.Variable */
.highlight .ow { color: #AA22FF; font-weight: bold } /* Operator.Word */
.highlight .w { color: #bbbbbb } /* Text.Whitespace */
.highlight .mb { color: #666666 } /* Literal.Number.Bin */
.highlight .mf { color: #666666 } /* Literal.Number.Float */
.highlight .mh { color: #666666 } /* Literal.Number.Hex */
.highlight .mi { color: #666666 } /* Literal.Number.Integer */
.highlight .mo { color: #666666 } /* Literal.Number.Oct */
.highlight .sa { color: #BA2121 } /* Literal.String.Affix */
.highlight .sb { color: #BA2121 } /* Literal.String.Backtick */
.highlight .sc { color: #BA2121 } /* Literal.String.Char */
.highlight .dl { color: #BA2121 } /* Literal.String.Delimiter */
.highlight .sd { color: #BA2121; font-style: italic } /* Literal.String.Doc */
.highlight .s2 { color: #BA2121 } /* Literal.String.Double */
.highlight .se { color: #BB6622; font-weight: bold } /* Literal.String.Escape */
.highlight .sh { color: #BA2121 } /* Literal.String.Heredoc */
.highlight .si { color: #BB6688; font-weight: bold } /* Literal.String.Interpol */
.highlight .sx { color: #008000 } /* Literal.String.Other */
.highlight .sr { color: #BB6688 } /* Literal.String.Regex */
.highlight .s1 { color: #BA2121 } /* Literal.String.Single */
.highlight .ss { color: #19177C } /* Literal.String.Symbol */
.highlight .bp { color: #008000 } /* Name.Builtin.Pseudo */
.highlight .fm { color: #0000FF } /* Name.Function.Magic */
.highlight .vc { color: #19177C } /* Name.Variable.Class */
.highlight .vg { color: #19177C } /* Name.Variable.Global */
.highlight .vi { color: #19177C } /* Name.Variable.Instance */
.highlight .vm { color: #19177C } /* Name.Variable.Magic */
.highlight .il { color: #666666 } /* Literal.Number.Integer.Long */
    </style>


<style type="text/css">
/* Overrides of notebook CSS for static HTML export */
body {
  overflow: visible;
  padding: 8px;
}

div#notebook {
  overflow: visible;
  border-top: none;
}@media print {
  div.cell {
    display: block;
    page-break-inside: avoid;
  } 
  div.output_wrapper { 
    display: block;
    page-break-inside: avoid; 
  }
  div.output { 
    display: block;
    page-break-inside: avoid; 
  }
}
</style>

<!-- Custom stylesheet, it must be in the same directory as the html file -->
<link rel="stylesheet" href="custom.css">

<!-- Loading mathjax macro -->
<!-- Load mathjax -->
    <script src="https://cdnjs.cloudflare.com/ajax/libs/mathjax/2.7.5/latest.js?config=TeX-AMS_HTML"></script>
    <!-- MathJax configuration -->
    <script type="text/x-mathjax-config">
    MathJax.Hub.Config({
        tex2jax: {
            inlineMath: [ ['$','$'], ["\\(","\\)"] ],
            displayMath: [ ['$$','$$'], ["\\[","\\]"] ],
            processEscapes: true,
            processEnvironments: true
        },
        // Center justify equations in code and markdown cells. Elsewhere
        // we use CSS to left justify single line equations in code cells.
        displayAlign: 'center',
        "HTML-CSS": {
            styles: {'.MathJax_Display': {"margin": 0}},
            linebreaks: { automatic: true }
        }
    });
    </script>
    <!-- End of mathjax configuration --></head>
<body>
  <div tabindex="-1" id="notebook" class="border-box-sizing">
    <div class="container" id="notebook-container">

<div class="cell border-box-sizing text_cell rendered"><div class="prompt input_prompt">
</div><div class="inner_cell">
<div class="text_cell_render border-box-sizing rendered_html">
<p><h1><center> How Happy is Our World? </center></h1></p>
<p><h3><center> By: Annabelle Baer, Utsa Santhosh, and Gordon Wu </center></h3>
<img src="happy song.jpg"/></p>

</div>
</div>
</div>
<div class="cell border-box-sizing text_cell rendered"><div class="prompt input_prompt">
</div><div class="inner_cell">
<div class="text_cell_render border-box-sizing rendered_html">
<h2 id="Introduction">Introduction<a class="anchor-link" href="#Introduction">&#182;</a></h2>
</div>
</div>
</div>
<div class="cell border-box-sizing text_cell rendered"><div class="prompt input_prompt">
</div><div class="inner_cell">
<div class="text_cell_render border-box-sizing rendered_html">
<p>Throughout the years, the United Nations publishes a "World Happiness Report" that gives countries around the world a score that correlates to the quality of life of citizens in the nation. Although 2020 in our eyes might not be the happiest year in the record books, it would be interesting to know which factors impact a country's happiness score.</p>
<p>The report contains information about a country’s social and economical factors, which together all contribute to receiving a score about the overall happiness of the nation. Some of these factors include the country’s GPD, freedom score, and generosity. Currently, there is data available from 2015-2020, however since the 2020 report was already released, it does not indicate the dramatic effects that COVID has had on a country. This has resulted in some biased data. We will see the true impact of this tumultuous year on the happiness of a country when the 2021 report gets released next year.</p>
<p>Hopefully, through this tutorial, we can learn which factors are important in ensuring happiness in a nation. If you are looking to create your own country, move to a new country, or work to fix the country you are in, stay tuned to learn which important factors might just make you happy. We could all use more these days!</p>

</div>
</div>
</div>
<div class="cell border-box-sizing text_cell rendered"><div class="prompt input_prompt">
</div><div class="inner_cell">
<div class="text_cell_render border-box-sizing rendered_html">
<h2 id="Data-Importing">Data Importing<a class="anchor-link" href="#Data-Importing">&#182;</a></h2>
</div>
</div>
</div>
<div class="cell border-box-sizing text_cell rendered"><div class="prompt input_prompt">
</div><div class="inner_cell">
<div class="text_cell_render border-box-sizing rendered_html">
<p>We need to import data from the Happiness Report from 2015-2020. From there, we need to clean up the data so that all the column names remain consistent throughout the years to aid us when we are calculating our analysis on these countries. After that, we are going to merge all of the datasets from throughout the years together to get one dataset that we can use to determine the top 5 and bottom 5 happiest countries from 2015-2020.</p>

</div>
</div>
</div>
<div class="cell border-box-sizing text_cell rendered"><div class="prompt input_prompt">
</div><div class="inner_cell">
<div class="text_cell_render border-box-sizing rendered_html">
<p>This first block includes everything that we will need to import to find our analysis. Here is what we will use it all for:</p>
<ol>
<li>Pandas:</li>
<li>Numpy:</li>
<li>Matplotlib:</li>
<li>Sklearn:</li>
<li>Statsmodels:</li>
</ol>

</div>
</div>
</div>
<div class="cell border-box-sizing code_cell rendered">
<div class="input">
<div class="prompt input_prompt">In&nbsp;[7]:</div>
<div class="inner_cell">
    <div class="input_area">
<div class=" highlight hl-ipython3"><pre><span></span><span class="c1"># Imports</span>
<span class="kn">import</span> <span class="nn">pandas</span> <span class="k">as</span> <span class="nn">pd</span>
<span class="kn">import</span> <span class="nn">numpy</span> <span class="k">as</span> <span class="nn">num</span>
<span class="kn">import</span> <span class="nn">matplotlib.pyplot</span> <span class="k">as</span> <span class="nn">plt</span>
<span class="kn">from</span> <span class="nn">sklearn</span> <span class="kn">import</span> <span class="n">linear_model</span>
<span class="kn">import</span> <span class="nn">statsmodels.formula.api</span> <span class="k">as</span> <span class="nn">sm</span>
</pre></div>

    </div>
</div>
</div>

</div>
<div class="cell border-box-sizing text_cell rendered"><div class="prompt input_prompt">
</div><div class="inner_cell">
<div class="text_cell_render border-box-sizing rendered_html">
<p>Next we will need to read the csv files into dataframes for each year. The data that was given to us came in the form of a csv file, containing data specific to that year. By using pandas to import it into a dataframe, we are prepping the data to be able to be used together for our analysis.</p>

</div>
</div>
</div>
<div class="cell border-box-sizing code_cell rendered">
<div class="input">
<div class="prompt input_prompt">In&nbsp;[8]:</div>
<div class="inner_cell">
    <div class="input_area">
<div class=" highlight hl-ipython3"><pre><span></span><span class="c1"># reading in each csv</span>
<span class="n">df_2015</span> <span class="o">=</span> <span class="n">pd</span><span class="o">.</span><span class="n">read_csv</span><span class="p">(</span><span class="s1">&#39;Data/2015.csv&#39;</span><span class="p">)</span>
<span class="n">df_2016</span> <span class="o">=</span> <span class="n">pd</span><span class="o">.</span><span class="n">read_csv</span><span class="p">(</span><span class="s1">&#39;Data/2016.csv&#39;</span><span class="p">)</span>
<span class="n">df_2017</span> <span class="o">=</span> <span class="n">pd</span><span class="o">.</span><span class="n">read_csv</span><span class="p">(</span><span class="s1">&#39;Data/2017.csv&#39;</span><span class="p">)</span>
<span class="n">df_2018</span> <span class="o">=</span> <span class="n">pd</span><span class="o">.</span><span class="n">read_csv</span><span class="p">(</span><span class="s1">&#39;Data/2018.csv&#39;</span><span class="p">)</span>
<span class="n">df_2019</span> <span class="o">=</span> <span class="n">pd</span><span class="o">.</span><span class="n">read_csv</span><span class="p">(</span><span class="s1">&#39;Data/2019.csv&#39;</span><span class="p">)</span>
<span class="n">df_2020</span> <span class="o">=</span> <span class="n">pd</span><span class="o">.</span><span class="n">read_csv</span><span class="p">(</span><span class="s1">&#39;Data/2020.csv&#39;</span><span class="p">)</span>
</pre></div>

    </div>
</div>
</div>

</div>
<div class="cell border-box-sizing text_cell rendered"><div class="prompt input_prompt">
</div><div class="inner_cell">
<div class="text_cell_render border-box-sizing rendered_html">
<p>Before we go ahead and merge all of these dataframes together, to make life easier for ourselves later on we are going to rename columns in the dataframes from each year so that they remain consistent throughout the years. When we got our data, since the information was pulled from different years, they did not use the same names for columns (we saw "Happiness Score", "Happiness.score", "Score", etc all relating to the Happiness Score).</p>

</div>
</div>
</div>
<div class="cell border-box-sizing code_cell rendered">
<div class="input">
<div class="prompt input_prompt">In&nbsp;[9]:</div>
<div class="inner_cell">
    <div class="input_area">
<div class=" highlight hl-ipython3"><pre><span></span><span class="c1"># Rename to standardize columns for names that differ between datasets </span>
<span class="n">df_2015</span><span class="o">=</span><span class="n">df_2015</span><span class="o">.</span><span class="n">rename</span><span class="p">(</span><span class="n">columns</span><span class="o">=</span><span class="p">{</span><span class="s2">&quot;Economy&quot;</span><span class="p">:</span> <span class="s2">&quot;GDP&quot;</span><span class="p">,</span> <span class="s2">&quot;Health (Life Expectancy)&quot;</span><span class="p">:</span><span class="s2">&quot;Life Expectancy&quot;</span><span class="p">,</span> <span class="s2">&quot;Trust (Government Corruption)&quot;</span><span class="p">:</span><span class="s2">&quot;Trust&quot;</span><span class="p">})</span>
<span class="n">df_2016</span><span class="o">=</span><span class="n">df_2016</span><span class="o">.</span><span class="n">rename</span><span class="p">(</span><span class="n">columns</span><span class="o">=</span><span class="p">{</span><span class="s2">&quot;Economy (GDP per Capita)&quot;</span><span class="p">:</span> <span class="s2">&quot;GDP&quot;</span><span class="p">,</span> <span class="s2">&quot;Health (Life Expectancy)&quot;</span><span class="p">:</span><span class="s2">&quot;Life Expectancy&quot;</span><span class="p">,</span> <span class="s2">&quot;Trust (Government Corruption)&quot;</span><span class="p">:</span><span class="s2">&quot;Trust&quot;</span><span class="p">})</span>
<span class="n">df_2017</span><span class="o">=</span><span class="n">df_2017</span><span class="o">.</span><span class="n">rename</span><span class="p">(</span><span class="n">columns</span><span class="o">=</span><span class="p">{</span><span class="s2">&quot;Happiness.Score&quot;</span><span class="p">:</span> <span class="s2">&quot;Happiness Score&quot;</span><span class="p">,</span><span class="s2">&quot;Economy..GDP.per.Capita.&quot;</span><span class="p">:</span> <span class="s2">&quot;GDP&quot;</span><span class="p">,</span> <span class="s2">&quot;Health..Life.Expectancy.&quot;</span><span class="p">:</span><span class="s2">&quot;Life Expectancy&quot;</span><span class="p">,</span> <span class="s2">&quot;Trust..Government.Corruption.&quot;</span><span class="p">:</span><span class="s2">&quot;Trust&quot;</span><span class="p">})</span>
<span class="n">df_2018</span><span class="o">=</span><span class="n">df_2018</span><span class="o">.</span><span class="n">rename</span><span class="p">(</span><span class="n">columns</span><span class="o">=</span><span class="p">{</span><span class="s2">&quot;Score&quot;</span><span class="p">:</span> <span class="s2">&quot;Happiness Score&quot;</span><span class="p">,</span><span class="s2">&quot;Country or region&quot;</span><span class="p">:</span> <span class="s2">&quot;Country&quot;</span><span class="p">,</span><span class="s2">&quot;GDP per capita&quot;</span><span class="p">:</span> <span class="s2">&quot;GDP&quot;</span><span class="p">,</span><span class="s2">&quot;Social support&quot;</span><span class="p">:</span><span class="s2">&quot;Family&quot;</span><span class="p">,</span> <span class="s2">&quot;Healthy life expectancy&quot;</span><span class="p">:</span><span class="s2">&quot;Life Expectancy&quot;</span><span class="p">,</span> <span class="s2">&quot;Freedom to make life choices&quot;</span><span class="p">:</span><span class="s2">&quot;Freedom&quot;</span><span class="p">,</span> <span class="s2">&quot;Perceptions of corruption&quot;</span><span class="p">:</span><span class="s2">&quot;Trust&quot;</span><span class="p">})</span>
<span class="n">df_2019</span><span class="o">=</span><span class="n">df_2019</span><span class="o">.</span><span class="n">rename</span><span class="p">(</span><span class="n">columns</span><span class="o">=</span><span class="p">{</span><span class="s2">&quot;Score&quot;</span><span class="p">:</span> <span class="s2">&quot;Happiness Score&quot;</span><span class="p">,</span><span class="s2">&quot;Country or region&quot;</span><span class="p">:</span> <span class="s2">&quot;Country&quot;</span><span class="p">,</span><span class="s2">&quot;GDP per capita&quot;</span><span class="p">:</span> <span class="s2">&quot;GDP&quot;</span><span class="p">,</span><span class="s2">&quot;Social support&quot;</span><span class="p">:</span><span class="s2">&quot;Family&quot;</span><span class="p">,</span> <span class="s2">&quot;Healthy life expectancy&quot;</span><span class="p">:</span><span class="s2">&quot;Life Expectancy&quot;</span><span class="p">,</span> <span class="s2">&quot;Freedom to make life choices&quot;</span><span class="p">:</span><span class="s2">&quot;Freedom&quot;</span><span class="p">,</span> <span class="s2">&quot;Perceptions of corruption&quot;</span><span class="p">:</span><span class="s2">&quot;Trust&quot;</span><span class="p">})</span>
<span class="n">df_2020</span><span class="o">=</span><span class="n">df_2020</span><span class="o">.</span><span class="n">rename</span><span class="p">(</span><span class="n">columns</span><span class="o">=</span><span class="p">{</span><span class="s2">&quot;Ladder score&quot;</span><span class="p">:</span> <span class="s2">&quot;Happiness Score&quot;</span><span class="p">,</span><span class="s2">&quot;Country name&quot;</span><span class="p">:</span> <span class="s2">&quot;Country&quot;</span><span class="p">,</span><span class="s2">&quot;Logged GDP per capita&quot;</span><span class="p">:</span> <span class="s2">&quot;GDP&quot;</span><span class="p">,</span> <span class="s2">&quot;Social support&quot;</span><span class="p">:</span><span class="s2">&quot;Family&quot;</span><span class="p">,</span> <span class="s2">&quot;Healthy life expectancy&quot;</span><span class="p">:</span><span class="s2">&quot;Life Expectancy&quot;</span><span class="p">,</span> <span class="s2">&quot;Freedom to make life choices&quot;</span><span class="p">:</span><span class="s2">&quot;Freedom&quot;</span><span class="p">,</span> <span class="s2">&quot;Perceptions of corruption&quot;</span><span class="p">:</span><span class="s2">&quot;Trust&quot;</span><span class="p">})</span>
</pre></div>

    </div>
</div>
</div>

</div>
<div class="cell border-box-sizing text_cell rendered"><div class="prompt input_prompt">
</div><div class="inner_cell">
<div class="text_cell_render border-box-sizing rendered_html">
<p>Now we are finally going to go ahead and merge all of our dataframes together to form one large dataframe! When merging together, they are merging on "Country", meaning that the final dataset will only contain countries that have appeared in every Happiness report from 2015-2020. This can also lead to some bias since we are excluding countries that may only appear on reports from some years but not all, but since our goal is to see change in happiness score over time it is a good idea to merge them.</p>
<p>Also, seeing that we renamed our column names to be consistent in the last step, here when merging we see that column names will have the _year that they are from so that we can distinguish which data is from which year after we merge.</p>

</div>
</div>
</div>
<div class="cell border-box-sizing code_cell rendered">
<div class="input">
<div class="prompt input_prompt">In&nbsp;[4]:</div>
<div class="inner_cell">
    <div class="input_area">
<div class=" highlight hl-ipython3"><pre><span></span><span class="c1"># merging all of the dataframes together into 1</span>
<span class="c1"># columns that had the same name will have that name _year that they are from</span>
<span class="c1"># They merge on country, so they will only include the countries that appear on each year&#39;s csv</span>
<span class="c1"># not every year had the same number of countries, so only 138 countries appear on every year&#39;s csv</span>
<span class="n">df</span><span class="o">=</span><span class="n">pd</span><span class="o">.</span><span class="n">merge</span><span class="p">(</span><span class="n">df_2015</span><span class="p">,</span> <span class="n">df_2016</span><span class="p">,</span> <span class="n">on</span><span class="o">=</span><span class="s1">&#39;Country&#39;</span><span class="p">,</span> <span class="n">suffixes</span><span class="o">=</span><span class="p">(</span><span class="s1">&#39;_2015&#39;</span><span class="p">,</span> <span class="s1">&#39;_2016&#39;</span><span class="p">))</span>
<span class="n">df</span><span class="o">=</span><span class="n">pd</span><span class="o">.</span><span class="n">merge</span><span class="p">(</span><span class="n">df</span><span class="p">,</span> <span class="n">df_2017</span><span class="p">,</span> <span class="n">on</span><span class="o">=</span><span class="s1">&#39;Country&#39;</span><span class="p">,</span> <span class="n">suffixes</span><span class="o">=</span><span class="p">(</span><span class="s1">&#39;&#39;</span><span class="p">,</span> <span class="s1">&#39;_2017&#39;</span><span class="p">))</span>
<span class="n">df</span><span class="o">=</span><span class="n">pd</span><span class="o">.</span><span class="n">merge</span><span class="p">(</span><span class="n">df</span><span class="p">,</span> <span class="n">df_2017</span><span class="p">,</span> <span class="n">on</span><span class="o">=</span><span class="s1">&#39;Country&#39;</span><span class="p">,</span> <span class="n">suffixes</span><span class="o">=</span><span class="p">(</span><span class="s1">&#39;&#39;</span><span class="p">,</span> <span class="s1">&#39;_2017&#39;</span><span class="p">))</span>
<span class="n">df</span><span class="o">=</span><span class="n">pd</span><span class="o">.</span><span class="n">merge</span><span class="p">(</span><span class="n">df</span><span class="p">,</span> <span class="n">df_2018</span><span class="p">,</span> <span class="n">on</span><span class="o">=</span><span class="s1">&#39;Country&#39;</span><span class="p">,</span> <span class="n">suffixes</span><span class="o">=</span><span class="p">(</span><span class="s1">&#39;&#39;</span><span class="p">,</span> <span class="s1">&#39;_2018&#39;</span><span class="p">))</span>
<span class="n">df</span><span class="o">=</span><span class="n">pd</span><span class="o">.</span><span class="n">merge</span><span class="p">(</span><span class="n">df</span><span class="p">,</span> <span class="n">df_2019</span><span class="p">,</span> <span class="n">on</span><span class="o">=</span><span class="s1">&#39;Country&#39;</span><span class="p">,</span> <span class="n">suffixes</span><span class="o">=</span><span class="p">(</span><span class="s1">&#39;&#39;</span><span class="p">,</span> <span class="s1">&#39;_2019&#39;</span><span class="p">))</span>
<span class="n">df</span><span class="o">=</span><span class="n">pd</span><span class="o">.</span><span class="n">merge</span><span class="p">(</span><span class="n">df</span><span class="p">,</span> <span class="n">df_2020</span><span class="p">,</span> <span class="n">on</span><span class="o">=</span><span class="s1">&#39;Country&#39;</span><span class="p">,</span> <span class="n">suffixes</span><span class="o">=</span><span class="p">(</span><span class="s1">&#39;&#39;</span><span class="p">,</span> <span class="s1">&#39;_2020&#39;</span><span class="p">))</span>
</pre></div>

    </div>
</div>
</div>

</div>
<div class="cell border-box-sizing code_cell rendered">
<div class="input">
<div class="prompt input_prompt">In&nbsp;[5]:</div>
<div class="inner_cell">
    <div class="input_area">
<div class=" highlight hl-ipython3"><pre><span></span><span class="n">df</span><span class="o">.</span><span class="n">head</span><span class="p">()</span>
</pre></div>

    </div>
</div>
</div>

<div class="output_wrapper">
<div class="output">


<div class="output_area">

    <div class="prompt output_prompt">Out[5]:</div>



<div class="output_html rendered_html output_subarea output_execute_result">
<div>
<style scoped>
    .dataframe tbody tr th:only-of-type {
        vertical-align: middle;
    }

    .dataframe tbody tr th {
        vertical-align: top;
    }

    .dataframe thead th {
        text-align: right;
    }
</style>
<table border="1" class="dataframe">
  <thead>
    <tr style="text-align: right;">
      <th></th>
      <th>Country</th>
      <th>Region_2015</th>
      <th>Happiness Rank_2015</th>
      <th>Happiness Score_2015</th>
      <th>Standard Error</th>
      <th>Economy (GDP per Capita)</th>
      <th>Family_2015</th>
      <th>Life Expectancy_2015</th>
      <th>Freedom_2015</th>
      <th>Trust_2015</th>
      <th>...</th>
      <th>Generosity_2020</th>
      <th>Trust_2020</th>
      <th>Ladder score in Dystopia</th>
      <th>Explained by: Log GDP per capita</th>
      <th>Explained by: Social support</th>
      <th>Explained by: Healthy life expectancy</th>
      <th>Explained by: Freedom to make life choices</th>
      <th>Explained by: Generosity</th>
      <th>Explained by: Perceptions of corruption</th>
      <th>Dystopia + residual</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>0</td>
      <td>Switzerland</td>
      <td>Western Europe</td>
      <td>1</td>
      <td>7.587</td>
      <td>0.03411</td>
      <td>1.39651</td>
      <td>1.34951</td>
      <td>0.94143</td>
      <td>0.66557</td>
      <td>0.41978</td>
      <td>...</td>
      <td>0.105911</td>
      <td>0.303728</td>
      <td>1.972317</td>
      <td>1.390774</td>
      <td>1.472403</td>
      <td>1.040533</td>
      <td>0.628954</td>
      <td>0.269056</td>
      <td>0.407946</td>
      <td>2.350267</td>
    </tr>
    <tr>
      <td>1</td>
      <td>Iceland</td>
      <td>Western Europe</td>
      <td>2</td>
      <td>7.561</td>
      <td>0.04884</td>
      <td>1.30232</td>
      <td>1.40223</td>
      <td>0.94784</td>
      <td>0.62877</td>
      <td>0.14145</td>
      <td>...</td>
      <td>0.246944</td>
      <td>0.711710</td>
      <td>1.972317</td>
      <td>1.326502</td>
      <td>1.547567</td>
      <td>1.000843</td>
      <td>0.661981</td>
      <td>0.362330</td>
      <td>0.144541</td>
      <td>2.460688</td>
    </tr>
    <tr>
      <td>2</td>
      <td>Denmark</td>
      <td>Western Europe</td>
      <td>3</td>
      <td>7.527</td>
      <td>0.03328</td>
      <td>1.32548</td>
      <td>1.36058</td>
      <td>0.87464</td>
      <td>0.64938</td>
      <td>0.48357</td>
      <td>...</td>
      <td>0.066202</td>
      <td>0.168489</td>
      <td>1.972317</td>
      <td>1.326949</td>
      <td>1.503449</td>
      <td>0.979333</td>
      <td>0.665040</td>
      <td>0.242793</td>
      <td>0.495260</td>
      <td>2.432741</td>
    </tr>
    <tr>
      <td>3</td>
      <td>Norway</td>
      <td>Western Europe</td>
      <td>4</td>
      <td>7.522</td>
      <td>0.03880</td>
      <td>1.45900</td>
      <td>1.33095</td>
      <td>0.88521</td>
      <td>0.66973</td>
      <td>0.36503</td>
      <td>...</td>
      <td>0.134533</td>
      <td>0.263218</td>
      <td>1.972317</td>
      <td>1.424207</td>
      <td>1.495173</td>
      <td>1.008072</td>
      <td>0.670201</td>
      <td>0.287985</td>
      <td>0.434101</td>
      <td>2.168266</td>
    </tr>
    <tr>
      <td>4</td>
      <td>Canada</td>
      <td>North America</td>
      <td>5</td>
      <td>7.427</td>
      <td>0.03553</td>
      <td>1.32629</td>
      <td>1.32261</td>
      <td>0.90563</td>
      <td>0.63297</td>
      <td>0.32957</td>
      <td>...</td>
      <td>0.124771</td>
      <td>0.390843</td>
      <td>1.972317</td>
      <td>1.301648</td>
      <td>1.435392</td>
      <td>1.022502</td>
      <td>0.644028</td>
      <td>0.281529</td>
      <td>0.351702</td>
      <td>2.195269</td>
    </tr>
  </tbody>
</table>
<p>5 rows × 81 columns</p>
</div>
</div>

</div>

</div>
</div>

</div>
<div class="cell border-box-sizing text_cell rendered"><div class="prompt input_prompt">
</div><div class="inner_cell">
<div class="text_cell_render border-box-sizing rendered_html">
<h2 id="Determining-Happiest-and-Least-Happiest-Countries">Determining Happiest and Least Happiest Countries<a class="anchor-link" href="#Determining-Happiest-and-Least-Happiest-Countries">&#182;</a></h2>
</div>
</div>
</div>
<div class="cell border-box-sizing text_cell rendered"><div class="prompt input_prompt">
</div><div class="inner_cell">
<div class="text_cell_render border-box-sizing rendered_html">
<p>Seeing that there are over 100 countries that appear on the Happiness Report, we do not want to plot and analyze them all. Instead, we can focus on which factors contribute to countries being the happiest, and which contribute to the countries being the least happy. To do this, we are going to take the average Happiness Score from each country from each year, and then sort the countries by their happiness score to determine the top 5 happiest countries and bottom 5 least happy countries.</p>
<p>We are then going to add each country's average happiness score from 2015-2020 as a column in the dataframe, so that we can sort the entire dataframe by these values.</p>

</div>
</div>
</div>
<div class="cell border-box-sizing code_cell rendered">
<div class="input">
<div class="prompt input_prompt">In&nbsp;[10]:</div>
<div class="inner_cell">
    <div class="input_area">
<div class=" highlight hl-ipython3"><pre><span></span><span class="c1">#getting average happiness score</span>
<span class="n">countries</span> <span class="o">=</span> <span class="n">df</span><span class="p">[</span><span class="s1">&#39;Country&#39;</span><span class="p">]</span>
<span class="n">countryNames</span> <span class="o">=</span> <span class="n">countries</span><span class="o">.</span><span class="n">unique</span><span class="p">()</span>
<span class="n">averages</span> <span class="o">=</span> <span class="p">[]</span>
<span class="n">new_vals</span> <span class="o">=</span> <span class="n">pd</span><span class="o">.</span><span class="n">DataFrame</span><span class="p">(</span><span class="n">columns</span><span class="o">=</span><span class="p">[</span><span class="s1">&#39;Country&#39;</span><span class="p">,</span> <span class="s1">&#39;Average Happiness Score&#39;</span><span class="p">])</span>
<span class="k">for</span> <span class="n">country</span> <span class="ow">in</span> <span class="n">countryNames</span><span class="p">:</span>
    <span class="n">countryStats</span> <span class="o">=</span> <span class="n">df</span><span class="p">[</span><span class="n">df</span><span class="p">[</span><span class="s1">&#39;Country&#39;</span><span class="p">]</span> <span class="o">==</span> <span class="n">country</span><span class="p">]</span>
    <span class="n">x2015</span> <span class="o">=</span> <span class="n">countryStats</span><span class="o">.</span><span class="n">iloc</span><span class="p">[</span><span class="mi">0</span><span class="p">][</span><span class="s1">&#39;Happiness Score_2015&#39;</span><span class="p">]</span>
    <span class="n">x2016</span> <span class="o">=</span> <span class="n">countryStats</span><span class="o">.</span><span class="n">iloc</span><span class="p">[</span><span class="mi">0</span><span class="p">][</span><span class="s1">&#39;Happiness Score_2016&#39;</span><span class="p">]</span>
    <span class="n">x2017</span> <span class="o">=</span> <span class="n">countryStats</span><span class="o">.</span><span class="n">iloc</span><span class="p">[</span><span class="mi">0</span><span class="p">][</span><span class="s1">&#39;Happiness Score_2017&#39;</span><span class="p">]</span>
    <span class="n">x2018</span> <span class="o">=</span> <span class="n">countryStats</span><span class="o">.</span><span class="n">iloc</span><span class="p">[</span><span class="mi">0</span><span class="p">][</span><span class="s1">&#39;Happiness Score_2018&#39;</span><span class="p">]</span>
    <span class="n">x2019</span> <span class="o">=</span> <span class="n">countryStats</span><span class="o">.</span><span class="n">iloc</span><span class="p">[</span><span class="mi">0</span><span class="p">][</span><span class="s1">&#39;Happiness Score_2019&#39;</span><span class="p">]</span>
    <span class="n">x2020</span> <span class="o">=</span> <span class="n">countryStats</span><span class="o">.</span><span class="n">iloc</span><span class="p">[</span><span class="mi">0</span><span class="p">][</span><span class="s1">&#39;Happiness Score_2020&#39;</span><span class="p">]</span>
    <span class="n">sumHappy</span> <span class="o">=</span> <span class="n">x2015</span><span class="o">+</span><span class="n">x2016</span><span class="o">+</span><span class="n">x2017</span><span class="o">+</span><span class="n">x2018</span><span class="o">+</span><span class="n">x2018</span><span class="o">+</span><span class="n">x2020</span>
    <span class="n">avg</span> <span class="o">=</span> <span class="n">sumHappy</span><span class="o">/</span><span class="mf">6.0</span>
    
    <span class="n">averages</span><span class="o">.</span><span class="n">append</span><span class="p">(</span><span class="n">avg</span><span class="p">)</span>
<span class="c1"># adding average score to dataframe</span>
<span class="n">df</span><span class="p">[</span><span class="s1">&#39;Average Happiness&#39;</span><span class="p">]</span> <span class="o">=</span> <span class="n">averages</span>
</pre></div>

    </div>
</div>
</div>

</div>
<div class="cell border-box-sizing text_cell rendered"><div class="prompt input_prompt">
</div><div class="inner_cell">
<div class="text_cell_render border-box-sizing rendered_html">
<p>Now, we are going to go ahead and sort the entire dataframe by these average happiness scores to find out which countries have on average been the happiest from 2015-2020</p>

</div>
</div>
</div>
<div class="cell border-box-sizing code_cell rendered">
<div class="input">
<div class="prompt input_prompt">In&nbsp;[36]:</div>
<div class="inner_cell">
    <div class="input_area">
<div class=" highlight hl-ipython3"><pre><span></span><span class="c1"># sorting the new df based on the average happiness values (last column)</span>
<span class="n">df</span> <span class="o">=</span> <span class="n">df</span><span class="o">.</span><span class="n">sort_values</span><span class="p">(</span><span class="n">by</span><span class="o">=</span><span class="p">[</span><span class="s1">&#39;Average Happiness&#39;</span><span class="p">],</span> <span class="n">ascending</span><span class="o">=</span><span class="kc">False</span><span class="p">)</span>
</pre></div>

    </div>
</div>
</div>

</div>
<div class="cell border-box-sizing text_cell rendered"><div class="prompt input_prompt">
</div><div class="inner_cell">
<div class="text_cell_render border-box-sizing rendered_html">
<p>The .head() function of a dataframe gives the top 5 entries, and since we sorted our dataframe we are now able to get our top 5 happiest countries!</p>

</div>
</div>
</div>
<div class="cell border-box-sizing code_cell rendered">
<div class="input">
<div class="prompt input_prompt">In&nbsp;[37]:</div>
<div class="inner_cell">
    <div class="input_area">
<div class=" highlight hl-ipython3"><pre><span></span><span class="c1"># top 5 happiest countries</span>
<span class="n">df</span><span class="o">.</span><span class="n">head</span><span class="p">(</span><span class="n">n</span><span class="o">=</span><span class="mi">5</span><span class="p">)</span>
</pre></div>

    </div>
</div>
</div>

<div class="output_wrapper">
<div class="output">


<div class="output_area">

    <div class="prompt output_prompt">Out[37]:</div>



<div class="output_html rendered_html output_subarea output_execute_result">
<div>
<style scoped>
    .dataframe tbody tr th:only-of-type {
        vertical-align: middle;
    }

    .dataframe tbody tr th {
        vertical-align: top;
    }

    .dataframe thead th {
        text-align: right;
    }
</style>
<table border="1" class="dataframe">
  <thead>
    <tr style="text-align: right;">
      <th></th>
      <th>Country</th>
      <th>Region_2015</th>
      <th>Happiness Rank_2015</th>
      <th>Happiness Score_2015</th>
      <th>Standard Error</th>
      <th>Economy (GDP per Capita)</th>
      <th>Family_2015</th>
      <th>Life Expectancy_2015</th>
      <th>Freedom_2015</th>
      <th>Trust_2015</th>
      <th>...</th>
      <th>Trust_2020</th>
      <th>Ladder score in Dystopia</th>
      <th>Explained by: Log GDP per capita</th>
      <th>Explained by: Social support</th>
      <th>Explained by: Healthy life expectancy</th>
      <th>Explained by: Freedom to make life choices</th>
      <th>Explained by: Generosity</th>
      <th>Explained by: Perceptions of corruption</th>
      <th>Dystopia + residual</th>
      <th>Average Happiness</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <th>5</th>
      <td>Finland</td>
      <td>Western Europe</td>
      <td>6</td>
      <td>7.406</td>
      <td>0.03140</td>
      <td>1.29025</td>
      <td>1.31826</td>
      <td>0.88911</td>
      <td>0.64169</td>
      <td>0.41372</td>
      <td>...</td>
      <td>0.195445</td>
      <td>1.972317</td>
      <td>1.285190</td>
      <td>1.499526</td>
      <td>0.961271</td>
      <td>0.662317</td>
      <td>0.159670</td>
      <td>0.477857</td>
      <td>2.762835</td>
      <td>7.560117</td>
    </tr>
    <tr>
      <th>2</th>
      <td>Denmark</td>
      <td>Western Europe</td>
      <td>3</td>
      <td>7.527</td>
      <td>0.03328</td>
      <td>1.32548</td>
      <td>1.36058</td>
      <td>0.87464</td>
      <td>0.64938</td>
      <td>0.48357</td>
      <td>...</td>
      <td>0.168489</td>
      <td>1.972317</td>
      <td>1.326949</td>
      <td>1.503449</td>
      <td>0.979333</td>
      <td>0.665040</td>
      <td>0.242793</td>
      <td>0.495260</td>
      <td>2.432741</td>
      <td>7.555100</td>
    </tr>
    <tr>
      <th>3</th>
      <td>Norway</td>
      <td>Western Europe</td>
      <td>4</td>
      <td>7.522</td>
      <td>0.03880</td>
      <td>1.45900</td>
      <td>1.33095</td>
      <td>0.88521</td>
      <td>0.66973</td>
      <td>0.36503</td>
      <td>...</td>
      <td>0.263218</td>
      <td>1.972317</td>
      <td>1.424207</td>
      <td>1.495173</td>
      <td>1.008072</td>
      <td>0.670201</td>
      <td>0.287985</td>
      <td>0.434101</td>
      <td>2.168266</td>
      <td>7.538833</td>
    </tr>
    <tr>
      <th>0</th>
      <td>Switzerland</td>
      <td>Western Europe</td>
      <td>1</td>
      <td>7.587</td>
      <td>0.03411</td>
      <td>1.39651</td>
      <td>1.34951</td>
      <td>0.94143</td>
      <td>0.66557</td>
      <td>0.41978</td>
      <td>...</td>
      <td>0.303728</td>
      <td>1.972317</td>
      <td>1.390774</td>
      <td>1.472403</td>
      <td>1.040533</td>
      <td>0.628954</td>
      <td>0.269056</td>
      <td>0.407946</td>
      <td>2.350267</td>
      <td>7.520650</td>
    </tr>
    <tr>
      <th>1</th>
      <td>Iceland</td>
      <td>Western Europe</td>
      <td>2</td>
      <td>7.561</td>
      <td>0.04884</td>
      <td>1.30232</td>
      <td>1.40223</td>
      <td>0.94784</td>
      <td>0.62877</td>
      <td>0.14145</td>
      <td>...</td>
      <td>0.711710</td>
      <td>1.972317</td>
      <td>1.326502</td>
      <td>1.547567</td>
      <td>1.000843</td>
      <td>0.661981</td>
      <td>0.362330</td>
      <td>0.144541</td>
      <td>2.460688</td>
      <td>7.510083</td>
    </tr>
  </tbody>
</table>
<p>5 rows × 82 columns</p>
</div>
</div>

</div>

</div>
</div>

</div>
<div class="cell border-box-sizing text_cell rendered"><div class="prompt input_prompt">
</div><div class="inner_cell">
<div class="text_cell_render border-box-sizing rendered_html">
<p>On the contrary, the .tail() funciton gives the bottom entries of a dataframe. The n=5 signifies that we want the bottom 5 entries.</p>

</div>
</div>
</div>
<div class="cell border-box-sizing code_cell rendered">
<div class="input">
<div class="prompt input_prompt">In&nbsp;[38]:</div>
<div class="inner_cell">
    <div class="input_area">
<div class=" highlight hl-ipython3"><pre><span></span><span class="c1"># bottom 5 least happiest countries</span>
<span class="n">df</span><span class="o">.</span><span class="n">tail</span><span class="p">(</span><span class="n">n</span><span class="o">=</span><span class="mi">5</span><span class="p">)</span>
</pre></div>

    </div>
</div>
</div>

<div class="output_wrapper">
<div class="output">


<div class="output_area">

    <div class="prompt output_prompt">Out[38]:</div>



<div class="output_html rendered_html output_subarea output_execute_result">
<div>
<style scoped>
    .dataframe tbody tr th:only-of-type {
        vertical-align: middle;
    }

    .dataframe tbody tr th {
        vertical-align: top;
    }

    .dataframe thead th {
        text-align: right;
    }
</style>
<table border="1" class="dataframe">
  <thead>
    <tr style="text-align: right;">
      <th></th>
      <th>Country</th>
      <th>Region_2015</th>
      <th>Happiness Rank_2015</th>
      <th>Happiness Score_2015</th>
      <th>Standard Error</th>
      <th>Economy (GDP per Capita)</th>
      <th>Family_2015</th>
      <th>Life Expectancy_2015</th>
      <th>Freedom_2015</th>
      <th>Trust_2015</th>
      <th>...</th>
      <th>Trust_2020</th>
      <th>Ladder score in Dystopia</th>
      <th>Explained by: Log GDP per capita</th>
      <th>Explained by: Social support</th>
      <th>Explained by: Healthy life expectancy</th>
      <th>Explained by: Freedom to make life choices</th>
      <th>Explained by: Generosity</th>
      <th>Explained by: Perceptions of corruption</th>
      <th>Dystopia + residual</th>
      <th>Average Happiness</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <th>119</th>
      <td>Yemen</td>
      <td>Middle East and Northern Africa</td>
      <td>136</td>
      <td>4.077</td>
      <td>0.04367</td>
      <td>0.54649</td>
      <td>0.68093</td>
      <td>0.40064</td>
      <td>0.35571</td>
      <td>0.07854</td>
      <td>...</td>
      <td>0.800288</td>
      <td>1.972317</td>
      <td>0.392702</td>
      <td>1.177477</td>
      <td>0.415000</td>
      <td>0.243721</td>
      <td>0.094689</td>
      <td>0.087352</td>
      <td>1.116473</td>
      <td>3.605233</td>
    </tr>
    <tr>
      <th>127</th>
      <td>Tanzania</td>
      <td>Sub-Saharan Africa</td>
      <td>146</td>
      <td>3.781</td>
      <td>0.05061</td>
      <td>0.28520</td>
      <td>1.00268</td>
      <td>0.38215</td>
      <td>0.32878</td>
      <td>0.05747</td>
      <td>...</td>
      <td>0.619799</td>
      <td>1.972317</td>
      <td>0.457163</td>
      <td>0.872675</td>
      <td>0.442678</td>
      <td>0.509343</td>
      <td>0.271541</td>
      <td>0.203881</td>
      <td>0.718963</td>
      <td>3.479700</td>
    </tr>
    <tr>
      <th>134</th>
      <td>Rwanda</td>
      <td>Sub-Saharan Africa</td>
      <td>154</td>
      <td>3.465</td>
      <td>0.03464</td>
      <td>0.22208</td>
      <td>0.77370</td>
      <td>0.42864</td>
      <td>0.59201</td>
      <td>0.55191</td>
      <td>...</td>
      <td>0.183541</td>
      <td>1.972317</td>
      <td>0.343243</td>
      <td>0.522876</td>
      <td>0.572383</td>
      <td>0.604088</td>
      <td>0.235705</td>
      <td>0.485542</td>
      <td>0.548445</td>
      <td>3.429883</td>
    </tr>
    <tr>
      <th>133</th>
      <td>Afghanistan</td>
      <td>Southern Asia</td>
      <td>153</td>
      <td>3.575</td>
      <td>0.03084</td>
      <td>0.31982</td>
      <td>0.30285</td>
      <td>0.30335</td>
      <td>0.23414</td>
      <td>0.09719</td>
      <td>...</td>
      <td>0.933687</td>
      <td>1.972317</td>
      <td>0.300706</td>
      <td>0.356434</td>
      <td>0.266052</td>
      <td>0.000000</td>
      <td>0.135235</td>
      <td>0.001226</td>
      <td>1.507236</td>
      <td>3.426650</td>
    </tr>
    <tr>
      <th>136</th>
      <td>Burundi</td>
      <td>Sub-Saharan Africa</td>
      <td>157</td>
      <td>2.905</td>
      <td>0.08658</td>
      <td>0.01530</td>
      <td>0.41587</td>
      <td>0.22396</td>
      <td>0.11850</td>
      <td>0.10062</td>
      <td>...</td>
      <td>0.606935</td>
      <td>1.972317</td>
      <td>0.000000</td>
      <td>0.403575</td>
      <td>0.295213</td>
      <td>0.275399</td>
      <td>0.187402</td>
      <td>0.212187</td>
      <td>2.401507</td>
      <td>3.050050</td>
    </tr>
  </tbody>
</table>
<p>5 rows × 82 columns</p>
</div>
</div>

</div>

</div>
</div>

</div>
<div class="cell border-box-sizing text_cell rendered"><div class="prompt input_prompt">
</div><div class="inner_cell">
<div class="text_cell_render border-box-sizing rendered_html">
<h2 id="Determining-Factors-that-Contribute-to-Happiness">Determining Factors that Contribute to Happiness<a class="anchor-link" href="#Determining-Factors-that-Contribute-to-Happiness">&#182;</a></h2>
</div>
</div>
</div>
<div class="cell border-box-sizing text_cell rendered"><div class="prompt input_prompt">
</div><div class="inner_cell">
<div class="text_cell_render border-box-sizing rendered_html">
<p>Now, we want to explore any possible correlations between the top 5 happiest countries versus the lowest 5 happiest countries. We will take the average of the GDP, life expectency, freedom, trust, and generosity of the bottom 5 countries over 5 years and compare them to the same data using the top 5 countries over 5 years.
First, we want to take the 5 year average of each country in the top 5 and bottom 5 years and create a new dataframe for each.</p>

</div>
</div>
</div>
<div class="cell border-box-sizing text_cell rendered"><div class="prompt input_prompt">
</div><div class="inner_cell">
<div class="text_cell_render border-box-sizing rendered_html">
<p>We for each country in the bottom 5 countries, we average all 5 years of each of the 5 attributes. To better organize our data, we will make a new dataframe called bottom_averages and assign each column to a computed average.</p>

</div>
</div>
</div>
<div class="cell border-box-sizing code_cell rendered">
<div class="input">
<div class="prompt input_prompt">In&nbsp;[76]:</div>
<div class="inner_cell">
    <div class="input_area">
<div class=" highlight hl-ipython3"><pre><span></span><span class="n">bottom_averages</span> <span class="o">=</span> <span class="n">pd</span><span class="o">.</span><span class="n">DataFrame</span><span class="p">()</span> 
<span class="n">bottom_df</span> <span class="o">=</span> <span class="n">df</span><span class="o">.</span><span class="n">tail</span><span class="p">(</span><span class="n">n</span><span class="o">=</span><span class="mi">5</span><span class="p">)</span>
<span class="n">bottom_countries</span> <span class="o">=</span> <span class="n">bottom_df</span><span class="p">[</span><span class="s1">&#39;Country&#39;</span><span class="p">]</span>
<span class="n">bottom_averages</span><span class="p">[</span><span class="s1">&#39;Country&#39;</span><span class="p">]</span> <span class="o">=</span> <span class="n">bottom_countries</span>
<span class="n">gdp_averages</span> <span class="o">=</span> <span class="p">[]</span>
<span class="n">lifeExp_averages</span> <span class="o">=</span> <span class="p">[]</span>
<span class="n">freedom_averages</span> <span class="o">=</span> <span class="p">[]</span>
<span class="n">trust_averages</span> <span class="o">=</span> <span class="p">[]</span>
<span class="n">generosity_averages</span> <span class="o">=</span> <span class="p">[]</span>
<span class="k">for</span> <span class="n">country</span> <span class="ow">in</span> <span class="n">bottom_countries</span><span class="p">:</span>
    <span class="n">bottom</span> <span class="o">=</span> <span class="n">bottom_df</span><span class="p">[</span><span class="n">bottom_df</span><span class="p">[</span><span class="s1">&#39;Country&#39;</span><span class="p">]</span> <span class="o">==</span> <span class="n">country</span><span class="p">]</span>
    <span class="n">sumGDP</span> <span class="o">=</span> <span class="mi">0</span>
    <span class="n">x2015</span> <span class="o">=</span> <span class="n">bottom</span><span class="o">.</span><span class="n">iloc</span><span class="p">[</span><span class="mi">0</span><span class="p">][</span><span class="s1">&#39;Economy (GDP per Capita)&#39;</span><span class="p">]</span>
    <span class="n">x2016</span> <span class="o">=</span> <span class="n">bottom</span><span class="o">.</span><span class="n">iloc</span><span class="p">[</span><span class="mi">0</span><span class="p">][</span><span class="s1">&#39;GDP&#39;</span><span class="p">]</span>
    <span class="n">x2017</span> <span class="o">=</span> <span class="n">bottom</span><span class="o">.</span><span class="n">iloc</span><span class="p">[</span><span class="mi">0</span><span class="p">][</span><span class="s1">&#39;GDP_2017&#39;</span><span class="p">][</span><span class="mi">0</span><span class="p">]</span>
    <span class="n">x2018</span> <span class="o">=</span> <span class="n">bottom</span><span class="o">.</span><span class="n">iloc</span><span class="p">[</span><span class="mi">0</span><span class="p">][</span><span class="s1">&#39;GDP_2018&#39;</span><span class="p">]</span>
    <span class="n">x2019</span> <span class="o">=</span> <span class="n">bottom</span><span class="o">.</span><span class="n">iloc</span><span class="p">[</span><span class="mi">0</span><span class="p">][</span><span class="s1">&#39;GDP_2019&#39;</span><span class="p">]</span>
    <span class="n">x2020</span> <span class="o">=</span> <span class="n">bottom</span><span class="o">.</span><span class="n">iloc</span><span class="p">[</span><span class="mi">0</span><span class="p">][</span><span class="s1">&#39;GDP_2020&#39;</span><span class="p">]</span>
    <span class="n">sumGDP</span> <span class="o">=</span> <span class="n">x2015</span><span class="o">+</span><span class="n">x2016</span><span class="o">+</span><span class="n">x2017</span><span class="o">+</span><span class="n">x2018</span><span class="o">+</span><span class="n">x2018</span><span class="o">+</span><span class="n">x2020</span>
    <span class="n">GDPavg</span> <span class="o">=</span> <span class="n">sumGDP</span><span class="o">/</span><span class="mf">6.0</span>
    <span class="n">gdp_averages</span><span class="o">.</span><span class="n">append</span><span class="p">(</span><span class="n">GDPavg</span><span class="p">)</span>
    
    <span class="n">sumLifeExp</span> <span class="o">=</span> <span class="mi">0</span>
    <span class="n">x2015</span> <span class="o">=</span> <span class="n">bottom</span><span class="o">.</span><span class="n">iloc</span><span class="p">[</span><span class="mi">0</span><span class="p">][</span><span class="s1">&#39;Life Expectancy_2015&#39;</span><span class="p">]</span>
    <span class="n">x2016</span> <span class="o">=</span> <span class="n">bottom</span><span class="o">.</span><span class="n">iloc</span><span class="p">[</span><span class="mi">0</span><span class="p">][</span><span class="s1">&#39;Life Expectancy_2016&#39;</span><span class="p">]</span>
    <span class="n">x2017</span> <span class="o">=</span> <span class="n">bottom</span><span class="o">.</span><span class="n">iloc</span><span class="p">[</span><span class="mi">0</span><span class="p">][</span><span class="s1">&#39;Life Expectancy_2017&#39;</span><span class="p">]</span>
    <span class="n">x2018</span> <span class="o">=</span> <span class="n">bottom</span><span class="o">.</span><span class="n">iloc</span><span class="p">[</span><span class="mi">0</span><span class="p">][</span><span class="s1">&#39;Life Expectancy_2018&#39;</span><span class="p">]</span>
    <span class="n">x2019</span> <span class="o">=</span> <span class="n">bottom</span><span class="o">.</span><span class="n">iloc</span><span class="p">[</span><span class="mi">0</span><span class="p">][</span><span class="s1">&#39;Life Expectancy_2019&#39;</span><span class="p">]</span>
    <span class="n">x2020</span> <span class="o">=</span> <span class="n">bottom</span><span class="o">.</span><span class="n">iloc</span><span class="p">[</span><span class="mi">0</span><span class="p">][</span><span class="s1">&#39;Life Expectancy_2020&#39;</span><span class="p">]</span>
    <span class="n">sumLifeExp</span> <span class="o">=</span> <span class="n">x2015</span><span class="o">+</span><span class="n">x2016</span><span class="o">+</span><span class="n">x2017</span><span class="o">+</span><span class="n">x2018</span><span class="o">+</span><span class="n">x2018</span><span class="o">+</span><span class="n">x2020</span>
    <span class="n">lifeExp_avg</span> <span class="o">=</span> <span class="n">sumLifeExp</span><span class="o">/</span><span class="mf">6.0</span>
    <span class="n">lifeExp_averages</span><span class="o">.</span><span class="n">append</span><span class="p">(</span><span class="n">lifeExp_avg</span><span class="p">)</span>
    
    <span class="n">sumFreedom</span> <span class="o">=</span> <span class="mi">0</span>
    <span class="n">x2015</span> <span class="o">=</span> <span class="n">bottom</span><span class="o">.</span><span class="n">iloc</span><span class="p">[</span><span class="mi">0</span><span class="p">][</span><span class="s1">&#39;Freedom_2015&#39;</span><span class="p">]</span>
    <span class="n">x2016</span> <span class="o">=</span> <span class="n">bottom</span><span class="o">.</span><span class="n">iloc</span><span class="p">[</span><span class="mi">0</span><span class="p">][</span><span class="s1">&#39;Freedom_2016&#39;</span><span class="p">]</span>
    <span class="n">x2017</span> <span class="o">=</span> <span class="n">bottom</span><span class="o">.</span><span class="n">iloc</span><span class="p">[</span><span class="mi">0</span><span class="p">][</span><span class="s1">&#39;Freedom_2017&#39;</span><span class="p">]</span>
    <span class="n">x2018</span> <span class="o">=</span> <span class="n">bottom</span><span class="o">.</span><span class="n">iloc</span><span class="p">[</span><span class="mi">0</span><span class="p">][</span><span class="s1">&#39;Freedom_2018&#39;</span><span class="p">]</span>
    <span class="n">x2019</span> <span class="o">=</span> <span class="n">bottom</span><span class="o">.</span><span class="n">iloc</span><span class="p">[</span><span class="mi">0</span><span class="p">][</span><span class="s1">&#39;Freedom_2019&#39;</span><span class="p">]</span>
    <span class="n">x2020</span> <span class="o">=</span> <span class="n">bottom</span><span class="o">.</span><span class="n">iloc</span><span class="p">[</span><span class="mi">0</span><span class="p">][</span><span class="s1">&#39;Freedom_2020&#39;</span><span class="p">]</span>
    <span class="n">sumFreedom</span> <span class="o">=</span> <span class="n">x2015</span><span class="o">+</span><span class="n">x2016</span><span class="o">+</span><span class="n">x2017</span><span class="o">+</span><span class="n">x2018</span><span class="o">+</span><span class="n">x2018</span><span class="o">+</span><span class="n">x2020</span>
    <span class="n">freedom_avg</span> <span class="o">=</span> <span class="n">sumFreedom</span><span class="o">/</span><span class="mf">6.0</span>
    
    <span class="n">freedom_averages</span><span class="o">.</span><span class="n">append</span><span class="p">(</span><span class="n">freedom_avg</span><span class="p">)</span>
    
    <span class="n">sumTrust</span> <span class="o">=</span> <span class="mi">0</span>
    <span class="n">x2015</span> <span class="o">=</span> <span class="n">bottom</span><span class="o">.</span><span class="n">iloc</span><span class="p">[</span><span class="mi">0</span><span class="p">][</span><span class="s1">&#39;Trust_2015&#39;</span><span class="p">]</span>
    <span class="n">x2016</span> <span class="o">=</span> <span class="n">bottom</span><span class="o">.</span><span class="n">iloc</span><span class="p">[</span><span class="mi">0</span><span class="p">][</span><span class="s1">&#39;Trust_2016&#39;</span><span class="p">]</span>
    <span class="n">x2017</span> <span class="o">=</span> <span class="n">bottom</span><span class="o">.</span><span class="n">iloc</span><span class="p">[</span><span class="mi">0</span><span class="p">][</span><span class="s1">&#39;Trust_2017&#39;</span><span class="p">]</span>
    <span class="n">x2018</span> <span class="o">=</span> <span class="n">bottom</span><span class="o">.</span><span class="n">iloc</span><span class="p">[</span><span class="mi">0</span><span class="p">][</span><span class="s1">&#39;Trust_2018&#39;</span><span class="p">]</span>
    <span class="n">x2019</span> <span class="o">=</span> <span class="n">bottom</span><span class="o">.</span><span class="n">iloc</span><span class="p">[</span><span class="mi">0</span><span class="p">][</span><span class="s1">&#39;Trust_2019&#39;</span><span class="p">]</span>
    <span class="n">x2020</span> <span class="o">=</span> <span class="n">bottom</span><span class="o">.</span><span class="n">iloc</span><span class="p">[</span><span class="mi">0</span><span class="p">][</span><span class="s1">&#39;Trust_2020&#39;</span><span class="p">]</span>
    <span class="n">sumTrust</span> <span class="o">=</span> <span class="n">x2015</span><span class="o">+</span><span class="n">x2016</span><span class="o">+</span><span class="n">x2017</span><span class="o">+</span><span class="n">x2018</span><span class="o">+</span><span class="n">x2018</span><span class="o">+</span><span class="n">x2020</span>
    <span class="n">trust_avg</span> <span class="o">=</span> <span class="n">sumTrust</span><span class="o">/</span><span class="mf">6.0</span>
    
    <span class="n">trust_averages</span><span class="o">.</span><span class="n">append</span><span class="p">(</span><span class="n">trust_avg</span><span class="p">)</span>
    
    <span class="n">sumGenerosity</span> <span class="o">=</span> <span class="mi">0</span>
    <span class="n">x2015</span> <span class="o">=</span> <span class="n">bottom</span><span class="o">.</span><span class="n">iloc</span><span class="p">[</span><span class="mi">0</span><span class="p">][</span><span class="s1">&#39;Generosity_2015&#39;</span><span class="p">]</span>
    <span class="n">x2016</span> <span class="o">=</span> <span class="n">bottom</span><span class="o">.</span><span class="n">iloc</span><span class="p">[</span><span class="mi">0</span><span class="p">][</span><span class="s1">&#39;Generosity_2016&#39;</span><span class="p">]</span>
    <span class="n">x2017</span> <span class="o">=</span> <span class="n">bottom</span><span class="o">.</span><span class="n">iloc</span><span class="p">[</span><span class="mi">0</span><span class="p">][</span><span class="s1">&#39;Generosity_2017&#39;</span><span class="p">]</span>
    <span class="n">x2018</span> <span class="o">=</span> <span class="n">bottom</span><span class="o">.</span><span class="n">iloc</span><span class="p">[</span><span class="mi">0</span><span class="p">][</span><span class="s1">&#39;Generosity_2018&#39;</span><span class="p">]</span>
    <span class="n">x2019</span> <span class="o">=</span> <span class="n">bottom</span><span class="o">.</span><span class="n">iloc</span><span class="p">[</span><span class="mi">0</span><span class="p">][</span><span class="s1">&#39;Generosity_2019&#39;</span><span class="p">]</span>
    <span class="n">x2020</span> <span class="o">=</span> <span class="n">bottom</span><span class="o">.</span><span class="n">iloc</span><span class="p">[</span><span class="mi">0</span><span class="p">][</span><span class="s1">&#39;Generosity_2020&#39;</span><span class="p">]</span>
    <span class="n">sumGenerosity</span> <span class="o">=</span> <span class="n">x2015</span><span class="o">+</span><span class="n">x2016</span><span class="o">+</span><span class="n">x2017</span><span class="o">+</span><span class="n">x2018</span><span class="o">+</span><span class="n">x2018</span><span class="o">+</span><span class="n">x2020</span>
    <span class="n">generosity_avg</span> <span class="o">=</span> <span class="n">sumGenerosity</span><span class="o">/</span><span class="mf">6.0</span>
    
    <span class="n">generosity_averages</span><span class="o">.</span><span class="n">append</span><span class="p">(</span><span class="n">generosity_avg</span><span class="p">)</span>
    

<span class="n">bottom_averages</span><span class="p">[</span><span class="s1">&#39;Average GDP&#39;</span><span class="p">]</span> <span class="o">=</span> <span class="n">gdp_averages</span>
<span class="n">bottom_averages</span><span class="p">[</span><span class="s1">&#39;Average Life Expectancy&#39;</span><span class="p">]</span> <span class="o">=</span> <span class="n">lifeExp_averages</span>
<span class="n">bottom_averages</span><span class="p">[</span><span class="s1">&#39;Average Freedom&#39;</span><span class="p">]</span> <span class="o">=</span> <span class="n">freedom_averages</span>
<span class="n">bottom_averages</span><span class="p">[</span><span class="s1">&#39;Average Trust&#39;</span><span class="p">]</span> <span class="o">=</span> <span class="n">trust_averages</span>
<span class="n">bottom_averages</span><span class="p">[</span><span class="s1">&#39;Average Generosity&#39;</span><span class="p">]</span> <span class="o">=</span> <span class="n">generosity_averages</span>
<span class="n">bottom_averages</span><span class="o">.</span><span class="n">head</span><span class="p">()</span> 
</pre></div>

    </div>
</div>
</div>

<div class="output_wrapper">
<div class="output">


<div class="output_area">

    <div class="prompt output_prompt">Out[76]:</div>



<div class="output_html rendered_html output_subarea output_execute_result">
<div>
<style scoped>
    .dataframe tbody tr th:only-of-type {
        vertical-align: middle;
    }

    .dataframe tbody tr th {
        vertical-align: top;
    }

    .dataframe thead th {
        text-align: right;
    }
</style>
<table border="1" class="dataframe">
  <thead>
    <tr style="text-align: right;">
      <th></th>
      <th>Country</th>
      <th>Average GDP</th>
      <th>Average Life Expectancy</th>
      <th>Average Freedom</th>
      <th>Average Trust</th>
      <th>Average Generosity</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <th>119</th>
      <td>Yemen</td>
      <td>1.726874</td>
      <td>9.739081</td>
      <td>0.320299</td>
      <td>0.187086</td>
      <td>0.050318</td>
    </tr>
    <tr>
      <th>127</th>
      <td>Tanzania</td>
      <td>1.690925</td>
      <td>9.893622</td>
      <td>0.469990</td>
      <td>0.164716</td>
      <td>0.277069</td>
    </tr>
    <tr>
      <th>134</th>
      <td>Rwanda</td>
      <td>1.530565</td>
      <td>10.495427</td>
      <td>0.648274</td>
      <td>0.430647</td>
      <td>0.195007</td>
    </tr>
    <tr>
      <th>133</th>
      <td>Afghanistan</td>
      <td>1.538405</td>
      <td>8.959589</td>
      <td>0.178532</td>
      <td>0.205859</td>
      <td>0.212537</td>
    </tr>
    <tr>
      <th>136</th>
      <td>Burundi</td>
      <td>1.141646</td>
      <td>9.037174</td>
      <td>0.162992</td>
      <td>0.172982</td>
      <td>0.147509</td>
    </tr>
  </tbody>
</table>
</div>
</div>

</div>

</div>
</div>

</div>
<div class="cell border-box-sizing text_cell rendered"><div class="prompt input_prompt">
</div><div class="inner_cell">
<div class="text_cell_render border-box-sizing rendered_html">
<p>We repeat the previous step but use the top 5 averages.</p>

</div>
</div>
</div>
<div class="cell border-box-sizing code_cell rendered">
<div class="input">
<div class="prompt input_prompt">In&nbsp;[78]:</div>
<div class="inner_cell">
    <div class="input_area">
<div class=" highlight hl-ipython3"><pre><span></span><span class="n">top_averages</span> <span class="o">=</span> <span class="n">pd</span><span class="o">.</span><span class="n">DataFrame</span><span class="p">()</span> 
<span class="n">top_df</span> <span class="o">=</span> <span class="n">df</span><span class="o">.</span><span class="n">head</span><span class="p">(</span><span class="n">n</span><span class="o">=</span><span class="mi">5</span><span class="p">)</span>
<span class="n">top_countries</span> <span class="o">=</span> <span class="n">top_df</span><span class="p">[</span><span class="s1">&#39;Country&#39;</span><span class="p">]</span>
<span class="n">top_averages</span><span class="p">[</span><span class="s1">&#39;Country&#39;</span><span class="p">]</span> <span class="o">=</span> <span class="n">top_countries</span>
<span class="n">gdp_averages</span> <span class="o">=</span> <span class="p">[]</span>
<span class="n">lifeExp_averages</span> <span class="o">=</span> <span class="p">[]</span>
<span class="n">freedom_averages</span> <span class="o">=</span> <span class="p">[]</span>
<span class="n">trust_averages</span> <span class="o">=</span> <span class="p">[]</span>
<span class="n">generosity_averages</span> <span class="o">=</span> <span class="p">[]</span>
<span class="k">for</span> <span class="n">country</span> <span class="ow">in</span> <span class="n">top_countries</span><span class="p">:</span>
    <span class="n">top</span> <span class="o">=</span> <span class="n">top_df</span><span class="p">[</span><span class="n">top_df</span><span class="p">[</span><span class="s1">&#39;Country&#39;</span><span class="p">]</span> <span class="o">==</span> <span class="n">country</span><span class="p">]</span>
    <span class="n">sumGDP</span> <span class="o">=</span> <span class="mi">0</span>
    <span class="n">x2015</span> <span class="o">=</span> <span class="n">top</span><span class="o">.</span><span class="n">iloc</span><span class="p">[</span><span class="mi">0</span><span class="p">][</span><span class="s1">&#39;Economy (GDP per Capita)&#39;</span><span class="p">]</span>
    <span class="n">x2016</span> <span class="o">=</span> <span class="n">top</span><span class="o">.</span><span class="n">iloc</span><span class="p">[</span><span class="mi">0</span><span class="p">][</span><span class="s1">&#39;GDP&#39;</span><span class="p">]</span>
    <span class="n">x2017</span> <span class="o">=</span> <span class="n">top</span><span class="o">.</span><span class="n">iloc</span><span class="p">[</span><span class="mi">0</span><span class="p">][</span><span class="s1">&#39;GDP_2017&#39;</span><span class="p">][</span><span class="mi">0</span><span class="p">]</span>
    <span class="n">x2018</span> <span class="o">=</span> <span class="n">top</span><span class="o">.</span><span class="n">iloc</span><span class="p">[</span><span class="mi">0</span><span class="p">][</span><span class="s1">&#39;GDP_2018&#39;</span><span class="p">]</span>
    <span class="n">x2019</span> <span class="o">=</span> <span class="n">top</span><span class="o">.</span><span class="n">iloc</span><span class="p">[</span><span class="mi">0</span><span class="p">][</span><span class="s1">&#39;GDP_2019&#39;</span><span class="p">]</span>
    <span class="n">x2020</span> <span class="o">=</span> <span class="n">top</span><span class="o">.</span><span class="n">iloc</span><span class="p">[</span><span class="mi">0</span><span class="p">][</span><span class="s1">&#39;GDP_2020&#39;</span><span class="p">]</span>
    <span class="n">sumGDP</span> <span class="o">=</span> <span class="n">x2015</span><span class="o">+</span><span class="n">x2016</span><span class="o">+</span><span class="n">x2017</span><span class="o">+</span><span class="n">x2018</span><span class="o">+</span><span class="n">x2018</span><span class="o">+</span><span class="n">x2020</span>
    <span class="n">GDPavg</span> <span class="o">=</span> <span class="n">sumGDP</span><span class="o">/</span><span class="mf">6.0</span>
    
    <span class="n">gdp_averages</span><span class="o">.</span><span class="n">append</span><span class="p">(</span><span class="n">GDPavg</span><span class="p">)</span>
    
    <span class="n">sumLifeExp</span> <span class="o">=</span> <span class="mi">0</span>
    <span class="n">x2015</span> <span class="o">=</span> <span class="n">top</span><span class="o">.</span><span class="n">iloc</span><span class="p">[</span><span class="mi">0</span><span class="p">][</span><span class="s1">&#39;Life Expectancy_2015&#39;</span><span class="p">]</span>
    <span class="n">x2016</span> <span class="o">=</span> <span class="n">top</span><span class="o">.</span><span class="n">iloc</span><span class="p">[</span><span class="mi">0</span><span class="p">][</span><span class="s1">&#39;Life Expectancy_2016&#39;</span><span class="p">]</span>
    <span class="n">x2017</span> <span class="o">=</span> <span class="n">top</span><span class="o">.</span><span class="n">iloc</span><span class="p">[</span><span class="mi">0</span><span class="p">][</span><span class="s1">&#39;Life Expectancy_2017&#39;</span><span class="p">]</span>
    <span class="n">x2018</span> <span class="o">=</span> <span class="n">top</span><span class="o">.</span><span class="n">iloc</span><span class="p">[</span><span class="mi">0</span><span class="p">][</span><span class="s1">&#39;Life Expectancy_2018&#39;</span><span class="p">]</span>
    <span class="n">x2019</span> <span class="o">=</span> <span class="n">top</span><span class="o">.</span><span class="n">iloc</span><span class="p">[</span><span class="mi">0</span><span class="p">][</span><span class="s1">&#39;Life Expectancy_2019&#39;</span><span class="p">]</span>
    <span class="n">x2020</span> <span class="o">=</span> <span class="n">top</span><span class="o">.</span><span class="n">iloc</span><span class="p">[</span><span class="mi">0</span><span class="p">][</span><span class="s1">&#39;Life Expectancy_2020&#39;</span><span class="p">]</span>
    <span class="n">sumLifeExp</span> <span class="o">=</span> <span class="n">x2015</span><span class="o">+</span><span class="n">x2016</span><span class="o">+</span><span class="n">x2017</span><span class="o">+</span><span class="n">x2018</span><span class="o">+</span><span class="n">x2018</span><span class="o">+</span><span class="n">x2020</span>
    <span class="n">lifeExp_avg</span> <span class="o">=</span> <span class="n">sumLifeExp</span><span class="o">/</span><span class="mf">6.0</span>
    
    <span class="n">lifeExp_averages</span><span class="o">.</span><span class="n">append</span><span class="p">(</span><span class="n">lifeExp_avg</span><span class="p">)</span>
    
    <span class="n">sumFreedom</span> <span class="o">=</span> <span class="mi">0</span>
    <span class="n">x2015</span> <span class="o">=</span> <span class="n">top</span><span class="o">.</span><span class="n">iloc</span><span class="p">[</span><span class="mi">0</span><span class="p">][</span><span class="s1">&#39;Freedom_2015&#39;</span><span class="p">]</span>
    <span class="n">x2016</span> <span class="o">=</span> <span class="n">top</span><span class="o">.</span><span class="n">iloc</span><span class="p">[</span><span class="mi">0</span><span class="p">][</span><span class="s1">&#39;Freedom_2016&#39;</span><span class="p">]</span>
    <span class="n">x2017</span> <span class="o">=</span> <span class="n">top</span><span class="o">.</span><span class="n">iloc</span><span class="p">[</span><span class="mi">0</span><span class="p">][</span><span class="s1">&#39;Freedom_2017&#39;</span><span class="p">]</span>
    <span class="n">x2018</span> <span class="o">=</span> <span class="n">top</span><span class="o">.</span><span class="n">iloc</span><span class="p">[</span><span class="mi">0</span><span class="p">][</span><span class="s1">&#39;Freedom_2018&#39;</span><span class="p">]</span>
    <span class="n">x2019</span> <span class="o">=</span> <span class="n">top</span><span class="o">.</span><span class="n">iloc</span><span class="p">[</span><span class="mi">0</span><span class="p">][</span><span class="s1">&#39;Freedom_2019&#39;</span><span class="p">]</span>
    <span class="n">x2020</span> <span class="o">=</span> <span class="n">top</span><span class="o">.</span><span class="n">iloc</span><span class="p">[</span><span class="mi">0</span><span class="p">][</span><span class="s1">&#39;Freedom_2020&#39;</span><span class="p">]</span>
    <span class="n">sumFreedom</span> <span class="o">=</span> <span class="n">x2015</span><span class="o">+</span><span class="n">x2016</span><span class="o">+</span><span class="n">x2017</span><span class="o">+</span><span class="n">x2018</span><span class="o">+</span><span class="n">x2018</span><span class="o">+</span><span class="n">x2020</span>
    <span class="n">freedom_avg</span> <span class="o">=</span> <span class="n">sumFreedom</span><span class="o">/</span><span class="mf">6.0</span>
    
    <span class="n">freedom_averages</span><span class="o">.</span><span class="n">append</span><span class="p">(</span><span class="n">freedom_avg</span><span class="p">)</span>
    
    <span class="n">sumTrust</span> <span class="o">=</span> <span class="mi">0</span>
    <span class="n">x2015</span> <span class="o">=</span> <span class="n">top</span><span class="o">.</span><span class="n">iloc</span><span class="p">[</span><span class="mi">0</span><span class="p">][</span><span class="s1">&#39;Trust_2015&#39;</span><span class="p">]</span>
    <span class="n">x2016</span> <span class="o">=</span> <span class="n">top</span><span class="o">.</span><span class="n">iloc</span><span class="p">[</span><span class="mi">0</span><span class="p">][</span><span class="s1">&#39;Trust_2016&#39;</span><span class="p">]</span>
    <span class="n">x2017</span> <span class="o">=</span> <span class="n">top</span><span class="o">.</span><span class="n">iloc</span><span class="p">[</span><span class="mi">0</span><span class="p">][</span><span class="s1">&#39;Trust_2017&#39;</span><span class="p">]</span>
    <span class="n">x2018</span> <span class="o">=</span> <span class="n">top</span><span class="o">.</span><span class="n">iloc</span><span class="p">[</span><span class="mi">0</span><span class="p">][</span><span class="s1">&#39;Trust_2018&#39;</span><span class="p">]</span>
    <span class="n">x2019</span> <span class="o">=</span> <span class="n">top</span><span class="o">.</span><span class="n">iloc</span><span class="p">[</span><span class="mi">0</span><span class="p">][</span><span class="s1">&#39;Trust_2019&#39;</span><span class="p">]</span>
    <span class="n">x2020</span> <span class="o">=</span> <span class="n">top</span><span class="o">.</span><span class="n">iloc</span><span class="p">[</span><span class="mi">0</span><span class="p">][</span><span class="s1">&#39;Trust_2020&#39;</span><span class="p">]</span>
    <span class="n">sumTrust</span> <span class="o">=</span> <span class="n">x2015</span><span class="o">+</span><span class="n">x2016</span><span class="o">+</span><span class="n">x2017</span><span class="o">+</span><span class="n">x2018</span><span class="o">+</span><span class="n">x2018</span><span class="o">+</span><span class="n">x2020</span>
    <span class="n">trust_avg</span> <span class="o">=</span> <span class="n">sumTrust</span><span class="o">/</span><span class="mf">6.0</span>
    
    <span class="n">trust_averages</span><span class="o">.</span><span class="n">append</span><span class="p">(</span><span class="n">trust_avg</span><span class="p">)</span>
    
    <span class="n">sumGenerosity</span> <span class="o">=</span> <span class="mi">0</span>
    <span class="n">x2015</span> <span class="o">=</span> <span class="n">top</span><span class="o">.</span><span class="n">iloc</span><span class="p">[</span><span class="mi">0</span><span class="p">][</span><span class="s1">&#39;Generosity_2015&#39;</span><span class="p">]</span>
    <span class="n">x2016</span> <span class="o">=</span> <span class="n">top</span><span class="o">.</span><span class="n">iloc</span><span class="p">[</span><span class="mi">0</span><span class="p">][</span><span class="s1">&#39;Generosity_2016&#39;</span><span class="p">]</span>
    <span class="n">x2017</span> <span class="o">=</span> <span class="n">top</span><span class="o">.</span><span class="n">iloc</span><span class="p">[</span><span class="mi">0</span><span class="p">][</span><span class="s1">&#39;Generosity_2017&#39;</span><span class="p">]</span>
    <span class="n">x2018</span> <span class="o">=</span> <span class="n">top</span><span class="o">.</span><span class="n">iloc</span><span class="p">[</span><span class="mi">0</span><span class="p">][</span><span class="s1">&#39;Generosity_2018&#39;</span><span class="p">]</span>
    <span class="n">x2019</span> <span class="o">=</span> <span class="n">top</span><span class="o">.</span><span class="n">iloc</span><span class="p">[</span><span class="mi">0</span><span class="p">][</span><span class="s1">&#39;Generosity_2019&#39;</span><span class="p">]</span>
    <span class="n">x2020</span> <span class="o">=</span> <span class="n">top</span><span class="o">.</span><span class="n">iloc</span><span class="p">[</span><span class="mi">0</span><span class="p">][</span><span class="s1">&#39;Generosity_2020&#39;</span><span class="p">]</span>
    <span class="n">sumGenerosity</span> <span class="o">=</span> <span class="n">x2015</span><span class="o">+</span><span class="n">x2016</span><span class="o">+</span><span class="n">x2017</span><span class="o">+</span><span class="n">x2018</span><span class="o">+</span><span class="n">x2018</span><span class="o">+</span><span class="n">x2020</span>
    <span class="n">generosity_avg</span> <span class="o">=</span> <span class="n">sumGenerosity</span><span class="o">/</span><span class="mf">6.0</span>
    
    <span class="n">generosity_averages</span><span class="o">.</span><span class="n">append</span><span class="p">(</span><span class="n">generosity_avg</span><span class="p">)</span>

<span class="n">top_averages</span><span class="p">[</span><span class="s1">&#39;Average GDP&#39;</span><span class="p">]</span> <span class="o">=</span> <span class="n">gdp_averages</span>
<span class="n">top_averages</span><span class="p">[</span><span class="s1">&#39;Average Life Expectancy&#39;</span><span class="p">]</span> <span class="o">=</span> <span class="n">lifeExp_averages</span>
<span class="n">top_averages</span><span class="p">[</span><span class="s1">&#39;Average Freedom&#39;</span><span class="p">]</span> <span class="o">=</span> <span class="n">freedom_averages</span>
<span class="n">top_averages</span><span class="p">[</span><span class="s1">&#39;Average Trust&#39;</span><span class="p">]</span> <span class="o">=</span> <span class="n">trust_averages</span>
<span class="n">top_averages</span><span class="p">[</span><span class="s1">&#39;Average Generosity&#39;</span><span class="p">]</span> <span class="o">=</span> <span class="n">generosity_averages</span>
<span class="n">top_averages</span><span class="o">.</span><span class="n">head</span><span class="p">()</span>
</pre></div>

    </div>
</div>
</div>

<div class="output_wrapper">
<div class="output">


<div class="output_area">

    <div class="prompt output_prompt">Out[78]:</div>



<div class="output_html rendered_html output_subarea output_execute_result">
<div>
<style scoped>
    .dataframe tbody tr th:only-of-type {
        vertical-align: middle;
    }

    .dataframe tbody tr th {
        vertical-align: top;
    }

    .dataframe thead th {
        text-align: right;
    }
</style>
<table border="1" class="dataframe">
  <thead>
    <tr style="text-align: right;">
      <th></th>
      <th>Country</th>
      <th>Average GDP</th>
      <th>Average Life Expectancy</th>
      <th>Average Freedom</th>
      <th>Average Trust</th>
      <th>Average Generosity</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <th>5</th>
      <td>Finland</td>
      <td>2.898178</td>
      <td>12.693001</td>
      <td>0.690309</td>
      <td>0.364636</td>
      <td>0.179738</td>
    </tr>
    <tr>
      <th>2</th>
      <td>Denmark</td>
      <td>2.954274</td>
      <td>12.766792</td>
      <td>0.695373</td>
      <td>0.385560</td>
      <td>0.282097</td>
    </tr>
    <tr>
      <th>3</th>
      <td>Norway</td>
      <td>3.108785</td>
      <td>12.900075</td>
      <td>0.704832</td>
      <td>0.330329</td>
      <td>0.299081</td>
    </tr>
    <tr>
      <th>0</th>
      <td>Switzerland</td>
      <td>3.051459</td>
      <td>13.103173</td>
      <td>0.685425</td>
      <td>0.369424</td>
      <td>0.247678</td>
    </tr>
    <tr>
      <th>1</th>
      <td>Iceland</td>
      <td>2.944695</td>
      <td>12.912787</td>
      <td>0.687511</td>
      <td>0.238739</td>
      <td>0.390261</td>
    </tr>
  </tbody>
</table>
</div>
</div>

</div>

</div>
</div>

</div>
<div class="cell border-box-sizing text_cell rendered"><div class="prompt input_prompt">
</div><div class="inner_cell">
<div class="text_cell_render border-box-sizing rendered_html">
<p>Now we want to compare the average data from the top 5 years to the bottom 5 years and plot them. We will plot the top 5 and bottom 5 averages per country next to each other to best see the relation between the two. In order to plot both the data from the top and the bottom, we can call plt.scatter one after another and they will appear on the same graph. We put the country on the X axis and the average GDP on the Y axis. We do this by accessing the 'Country' and 'Average GDP' columns in the top_averages and bottom_averages dataframes created above and setting them to the x and y values.</p>

</div>
</div>
</div>
<div class="cell border-box-sizing text_cell rendered"><div class="prompt input_prompt">
</div><div class="inner_cell">
<div class="text_cell_render border-box-sizing rendered_html">
<p>Matplotlib's plt.scatter is one way of plotting data. Complete documentation can be found here: <a href="https://matplotlib.org/3.3.3/api/_as_gen/matplotlib.pyplot.scatter.html">https://matplotlib.org/3.3.3/api/_as_gen/matplotlib.pyplot.scatter.html</a></p>
<p>However, matplotlib provides many alternatives to plotting data. This can be explored here: <a href="https://matplotlib.org/">https://matplotlib.org/</a>.</p>

</div>
</div>
</div>
<div class="cell border-box-sizing code_cell rendered">
<div class="input">
<div class="prompt input_prompt">In&nbsp;[85]:</div>
<div class="inner_cell">
    <div class="input_area">
<div class=" highlight hl-ipython3"><pre><span></span><span class="c1"># for column in top_averages.columns.tolist()[1:]:</span>
<span class="n">plt</span><span class="o">.</span><span class="n">scatter</span><span class="p">(</span><span class="n">x</span> <span class="o">=</span> <span class="n">top_averages</span><span class="p">[</span><span class="s1">&#39;Country&#39;</span><span class="p">],</span> <span class="n">y</span> <span class="o">=</span> <span class="n">top_averages</span><span class="p">[</span><span class="s1">&#39;Average GDP&#39;</span><span class="p">])</span>
<span class="n">plt</span><span class="o">.</span><span class="n">scatter</span><span class="p">(</span><span class="n">x</span> <span class="o">=</span> <span class="n">bottom_averages</span><span class="p">[</span><span class="s1">&#39;Country&#39;</span><span class="p">],</span> <span class="n">y</span> <span class="o">=</span> <span class="n">bottom_averages</span><span class="p">[</span><span class="s1">&#39;Average GDP&#39;</span><span class="p">])</span>
<span class="n">plt</span><span class="o">.</span><span class="n">xlabel</span><span class="p">(</span><span class="s1">&#39;Country&#39;</span><span class="p">)</span>
<span class="n">plt</span><span class="o">.</span><span class="n">ylabel</span><span class="p">(</span><span class="s1">&#39;Average GDP&#39;</span><span class="p">)</span>
</pre></div>

    </div>
</div>
</div>

<div class="output_wrapper">
<div class="output">


<div class="output_area">

    <div class="prompt output_prompt">Out[85]:</div>




<div class="output_text output_subarea output_execute_result">
<pre>Text(0, 0.5, &#39;Average GDP&#39;)</pre>
</div>

</div>

<div class="output_area">

    <div class="prompt"></div>




<div class="output_png output_subarea ">
<img src="data:image/png;base64,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
"
>
</div>

</div>

</div>
</div>

</div>
<div class="cell border-box-sizing text_cell rendered"><div class="prompt input_prompt">
</div><div class="inner_cell">
<div class="text_cell_render border-box-sizing rendered_html">
<p>From this plot, we learned that the top 5 happiest countries average between 2.74 and 4.00 GDP while the bottom 5 countries average below 2.00. This is a simple visualization that allows us to recognize patterns such as this one.</p>

</div>
</div>
</div>
<div class="cell border-box-sizing text_cell rendered"><div class="prompt input_prompt">
</div><div class="inner_cell">
<div class="text_cell_render border-box-sizing rendered_html">
<p>You can see that the Y axis shows a scale of GDP and the X axis shows the countries. Since we used scatter using two different datasets (bottom and top), scatter divided the points into colors depending on the plot. We will now repeat this step for life expectancy, freedom, trust, and generosity.</p>

</div>
</div>
</div>
<div class="cell border-box-sizing code_cell rendered">
<div class="input">
<div class="prompt input_prompt">In&nbsp;[86]:</div>
<div class="inner_cell">
    <div class="input_area">
<div class=" highlight hl-ipython3"><pre><span></span><span class="n">plt</span><span class="o">.</span><span class="n">scatter</span><span class="p">(</span><span class="n">x</span> <span class="o">=</span> <span class="n">top_averages</span><span class="p">[</span><span class="s1">&#39;Country&#39;</span><span class="p">],</span> <span class="n">y</span> <span class="o">=</span> <span class="n">top_averages</span><span class="p">[</span><span class="s1">&#39;Average Life Expectancy&#39;</span><span class="p">])</span>
<span class="n">plt</span><span class="o">.</span><span class="n">scatter</span><span class="p">(</span><span class="n">x</span> <span class="o">=</span> <span class="n">bottom_averages</span><span class="p">[</span><span class="s1">&#39;Country&#39;</span><span class="p">],</span> <span class="n">y</span> <span class="o">=</span> <span class="n">bottom_averages</span><span class="p">[</span><span class="s1">&#39;Average Life Expectancy&#39;</span><span class="p">])</span>
<span class="n">plt</span><span class="o">.</span><span class="n">xlabel</span><span class="p">(</span><span class="s1">&#39;Country&#39;</span><span class="p">)</span>
<span class="n">plt</span><span class="o">.</span><span class="n">ylabel</span><span class="p">(</span><span class="s1">&#39;Average Life Expectancy&#39;</span><span class="p">)</span>
</pre></div>

    </div>
</div>
</div>

<div class="output_wrapper">
<div class="output">


<div class="output_area">

    <div class="prompt output_prompt">Out[86]:</div>




<div class="output_text output_subarea output_execute_result">
<pre>Text(0, 0.5, &#39;Average Life Expectancy&#39;)</pre>
</div>

</div>

<div class="output_area">

    <div class="prompt"></div>




<div class="output_png output_subarea ">
<img src="data:image/png;base64,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
"
>
</div>

</div>

</div>
</div>

</div>
<div class="cell border-box-sizing code_cell rendered">
<div class="input">
<div class="prompt input_prompt">In&nbsp;[87]:</div>
<div class="inner_cell">
    <div class="input_area">
<div class=" highlight hl-ipython3"><pre><span></span><span class="n">plt</span><span class="o">.</span><span class="n">scatter</span><span class="p">(</span><span class="n">x</span> <span class="o">=</span> <span class="n">top_averages</span><span class="p">[</span><span class="s1">&#39;Country&#39;</span><span class="p">],</span> <span class="n">y</span> <span class="o">=</span> <span class="n">top_averages</span><span class="p">[</span><span class="s1">&#39;Average Freedom&#39;</span><span class="p">])</span>
<span class="n">plt</span><span class="o">.</span><span class="n">scatter</span><span class="p">(</span><span class="n">x</span> <span class="o">=</span> <span class="n">bottom_averages</span><span class="p">[</span><span class="s1">&#39;Country&#39;</span><span class="p">],</span> <span class="n">y</span> <span class="o">=</span> <span class="n">bottom_averages</span><span class="p">[</span><span class="s1">&#39;Average Freedom&#39;</span><span class="p">])</span>
<span class="n">plt</span><span class="o">.</span><span class="n">xlabel</span><span class="p">(</span><span class="s1">&#39;Country&#39;</span><span class="p">)</span>
<span class="n">plt</span><span class="o">.</span><span class="n">ylabel</span><span class="p">(</span><span class="s1">&#39;Average Freedom&#39;</span><span class="p">)</span>
</pre></div>

    </div>
</div>
</div>

<div class="output_wrapper">
<div class="output">


<div class="output_area">

    <div class="prompt output_prompt">Out[87]:</div>




<div class="output_text output_subarea output_execute_result">
<pre>Text(0, 0.5, &#39;Average Freedom&#39;)</pre>
</div>

</div>

<div class="output_area">

    <div class="prompt"></div>




<div class="output_png output_subarea ">
<img src="data:image/png;base64,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
"
>
</div>

</div>

</div>
</div>

</div>
<div class="cell border-box-sizing code_cell rendered">
<div class="input">
<div class="prompt input_prompt">In&nbsp;[88]:</div>
<div class="inner_cell">
    <div class="input_area">
<div class=" highlight hl-ipython3"><pre><span></span><span class="n">plt</span><span class="o">.</span><span class="n">scatter</span><span class="p">(</span><span class="n">x</span> <span class="o">=</span> <span class="n">top_averages</span><span class="p">[</span><span class="s1">&#39;Country&#39;</span><span class="p">],</span> <span class="n">y</span> <span class="o">=</span> <span class="n">top_averages</span><span class="p">[</span><span class="s1">&#39;Average Trust&#39;</span><span class="p">])</span>
<span class="n">plt</span><span class="o">.</span><span class="n">scatter</span><span class="p">(</span><span class="n">x</span> <span class="o">=</span> <span class="n">bottom_averages</span><span class="p">[</span><span class="s1">&#39;Country&#39;</span><span class="p">],</span> <span class="n">y</span> <span class="o">=</span> <span class="n">bottom_averages</span><span class="p">[</span><span class="s1">&#39;Average Trust&#39;</span><span class="p">])</span>
<span class="n">plt</span><span class="o">.</span><span class="n">xlabel</span><span class="p">(</span><span class="s1">&#39;Country&#39;</span><span class="p">)</span>
<span class="n">plt</span><span class="o">.</span><span class="n">ylabel</span><span class="p">(</span><span class="s1">&#39;Average Trust&#39;</span><span class="p">)</span>
</pre></div>

    </div>
</div>
</div>

<div class="output_wrapper">
<div class="output">


<div class="output_area">

    <div class="prompt output_prompt">Out[88]:</div>




<div class="output_text output_subarea output_execute_result">
<pre>Text(0, 0.5, &#39;Average Trust&#39;)</pre>
</div>

</div>

<div class="output_area">

    <div class="prompt"></div>




<div class="output_png output_subarea ">
<img src="data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAAY0AAAEGCAYAAACZ0MnKAAAABHNCSVQICAgIfAhkiAAAAAlwSFlzAAALEgAACxIB0t1+/AAAADh0RVh0U29mdHdhcmUAbWF0cGxvdGxpYiB2ZXJzaW9uMy4yLjIsIGh0dHA6Ly9tYXRwbG90bGliLm9yZy+WH4yJAAAfj0lEQVR4nO3de5hcVZnv8e+PJkjkFiUtSgiGQYSTYcLFFi8wAiIEVASECSCKF44RR+ToCAijw+DleEaDl0FAjDyAMwNC0CQneCF4EEQFlA6BRDhEYwhDEpSAJFzsgSS888dald5pqrp3NV1du9O/z/P001Vr396qfXn3WnvX2ooIzMzMytii3QGYmdnI4aRhZmalOWmYmVlpThpmZlaak4aZmZW2ZbsDGErjx4+PSZMmtTsMM7MRY8GCBY9FRGfZ8TerpDFp0iS6u7vbHYaZ2Ygh6aFmxnfzlJmZleakYWZmpTlpmJlZaU4aZmZWmpOGmZmV5qRhZiPLolnw9b3hgnHp/6JZ7Y5oVNmsbrk1s83collww5mwrie9X/tweg8wZVr74hpFXNMws5Hj5s/3JoyadT2p3IaFk4aZjRxrVzRXbkPOScPMRo4ddmmu3Iack4aZjRyHnQ9jxm5aNmZsKrdh4aRhZiPHlGlw9EWww0RA6f/RF/ki+DDy3VNmNrJMmeYk0UauaZiZWWlOGmZmVpqThpmZleakYWZmpTlpmJlZaU4aZmZWmpOGmZmV5qRhZmalOWmYmVlpThpmZlaak4aZmZXmpGFmZqU5aZiZWWlOGmZmVpqThpmZldbSpCHpSElLJC2VdG4/471e0gZJJzQ7rZmZDZ+WJQ1JHcAlwFHAZOBkSZMbjPdlYH6z05qZ2fBqZU3jAGBpRCyLiOeAa4Fj6oz3ceAHwKODmNbMzIZRK5PGBODhwvsVuWwjSROA44DLmp22MI/pkrolda9evfpFB21mZo21MmmoTln0ef8N4NMRsWEQ06bCiJkR0RURXZ2dnYMI08zMytqyhfNeAUwsvN8FWNVnnC7gWkkA44G3S1pfclozMxtmrUwadwF7SNoNWAmcBLynOEJE7FZ7Lekq4IcRMVfSlgNNa2Zmw69lSSMi1ks6g3RXVAdwRUTcJ+n0PLzvdYwBp21VrGZmVo4i6l4qGJG6urqiu7u73WGYmY0YkhZERFfZ8f2LcDMzK81Jw8zMSmvlhXBrwtyFK5kxfwmr1vSw87ixnD11T47dr+5PU8zM2sZJowLmLlzJebMX07Mu/Vxl5Zoezpu9GMCJw8wqxc1TFTBj/pKNCaOmZ90GZsxf0qaIzMzqc9KogFVrepoqNzNrFyeNCth53Nimys3M2sVJowLOnronY8d0bFI2dkwHZ0/ds00RmZnV5wvhFVC72O27p8ys6pw0KuLY/SY4SZhZ5bl5yszMSnPSMDOz0pw0zMysNCcNMzMrzRfCrXLcD5dZdTlpWKW4Hy6zanPzlFWK++Eyq7ZRX9NwU0i1uB8us2ob1TWNWlPIyjU9BL1NIXMXrmx3aKOW++Eyq7ZRnTTcFFI97ofLrNpGdfOUm0Kqx/1wmVXbqE4aO48by8o6CcJNIe3lfrjMqmtUN0+5KcTMrDmjuqbhphAzs+aM6qQBbgoxM2vGqG6eMjOz5jhpmJlZaU4aZmZWWkuThqQjJS2RtFTSuXWGHyNpkaR7JHVLOqgwbLmkxbVhrYzTzMzKadmFcEkdwCXA4cAK4C5J8yLi/sJoNwPzIiIkTQFmAXsVhh8aEY+1KkYzM2tOK2saBwBLI2JZRDwHXAscUxwhIp6OiMhvtwECMzOrrFYmjQnAw4X3K3LZJiQdJ+kB4EfAhwqDArhJ0gJJ0xstRNL03LTVvXr16iEK3czM6mll0lCdshfUJCJiTkTsBRwLfKEw6MCI2B84CviYpLfUW0hEzIyIrojo6uzsHIq4zcysgVYmjRXAxML7XYBVjUaOiNuA3SWNz+9X5f+PAnNIzV1mZtZGrUwadwF7SNpN0lbAScC84giSXiNJ+fX+wFbA45K2kbRdLt8GOAL4bQtjNTOzElp291RErJd0BjAf6ACuiIj7JJ2eh18GHA+cKmkd0AOcmO+k2gmYk/PJlsA1EXFjq2I1M7Ny1Hvz0sjX1dUV3d3+SYeZWVmSFkREV9nxB2yekvSSMmVmZrb5K3NN446SZWZmtplreE1D0itJv6sYK2k/em+h3R546TDEZmZmFdPfhfCpwAdIt8p+ld6k8RTwj60Ny8zMqqhh0oiI7wLflXR8RPxgGGMyM7OKKnNNYxdJ2yu5XNLdko5oeWRmZlY5ZX6n8aGI+FdJU4FXAB8ErgRuamlkNuzmLlzp56WbWb/KJI3atYy3A1dGxL21X3Hb5mPuwpWcN3sxPes2ALByTQ/nzV4M4MRhZhuVaZ5aIOkmUtKYn7v3eL61YdlwmzF/ycaEUdOzbgMz5i9pU0RmVkVlahqnAfsCyyLiL5J2JDVR2WZk1ZqepsrNbHQqkzRqj2Cd4lapzdfO48aysk6C2Hnc2DZEY2ZVVSZpnF14vTWpi/IFwFtbEpG1xdlT99zkmgbA2DEdnD11zzZGZWZVM2DSiIiji+8lTQS+0rKIrC1qF7t995SZ9WcwXaOvAPYe6kCs/Y7db4KThJn1a8CkIemb9D6mdQvSRfF7WxmUmZlVU5maRvEBFeuB70XEr1oUj5mZVVi/SUNSB3B4RLx3mOIxM7MK6/fHfRGxAejMz/g2M7NRrr/naewaEf8JLAd+JWke8ExteER8rfXhmZlZlfTXPDUX2B9Ylf+2ALYbjqDMzKya+ksaAoiIzw1TLGZmVnH9JY0Jki5qNDAizmxBPGZmVmH9JY0eUnchZmZmQP9J4/H8yFczMzOg/1tunxu2KMzMbERomDQi4o3DGYiZmVVfmSf3mZmZAU4aZmbWhFJJQ9JBkj6YX3dK2q3kdEdKWiJpqaRz6ww/RtIiSfdI6pZ0UNlpzcxs+A2YNCT9M/Bp4LxcNAb4jxLTdQCXAEcBk4GTJU3uM9rNwD4RsS/wIeDyJqY1M7NhVqamcRzwLnK/UxGxinLdiRwALI2IZRHxHHAtcExxhIh4OiJqz+rYht7ndgw4rZmZDb8ySeO5fGAPAEnblJz3BODhwvsVuWwTko6T9ADwI1Jto/S0efrpuWmre/Xq1SVDMzOzwSiTNGZJ+jYwTtKHgf8HfKfEdKpTFi8oiJgTEXsBxwJfaGbaPP3MiOiKiK7Ozs4SYZmZ2WAN+OS+iLhQ0uHAk8CewPkR8dMS814BTCy834XUW26j5dwmaXdJ45ud1szMhkeZx72Sk0SZRFF0F7BHvtNqJXAS8J7iCJJeA/whIkLS/sBWwOPAmoGmNTOz4Tdg0pD0FC9sGlpLenb4pyJiWb3pImK9pDOA+UAHcEVE3Cfp9Dz8MuB44FRJ60gdJJ6Yr5/UnXZQn9DMzIaMem9eajCC9DlS09A1pGsNJwGvBJYAH42IQ1ocY2ldXV3R3d3d7jDMzEYMSQsioqvs+GUuhB8ZEd+OiKci4smImAm8PSKuA1426EjNzGzEKZM0npc0TdIW+W9aYVj/1RQzM9uslEkapwDvAx4F/pRfv1fSWOCMFsZmZmYVU+aW22XA0Q0G/3JowzEzsyorc/fU1sBpwF8DW9fKI+JDDScyM7PNUpnmqX8n3S01Ffg56Yd2T7UyKDMzq6YySeM1EfFPwDP5meHvAP6mtWGZmVkVlUka6/L/NZL2BnYAJrUsIjMzq6wy3YjMlPQy4LPAPGBb4J9aGpWZmVVSv0lD0hbAkxHxBHAb8FfDEpWZmVVSv81TEfE8/i2GmZllZa5p/FTSWZImSnp57a/lkZmZWeWUuaZR+z3GxwplgZuqzMxGnTK/CN9tOAIxM7PqG7B5StJLJX1W0sz8fg9J72x9aGZmVjVlrmlcCTwHvDm/XwF8sWURmZlZZZVJGrtHxFfIP/KLiB7Sw5jMzGyUKZM0nsvdoAeApN2BZ1salZmZVVKZu6cuAG4EJkq6GjgQ+EALYzIzs4oqc/fUTZIWAG8kNUv9r4h4rOWRmZlZ5ZR5nsY84HvAvIh4pvUhmZlZVZW5pvFV4G+B+yVdL+mE/GAmMzMbZco0T/0c+LmkDuCtwIeBK4DtWxybmZlVTJkL4eS7p44GTgT2B77byqDMzKyaylzTuA54A+kOqkuAW3Pvt2ZmNsqUqWlcCbwnIjYASDpQ0nsi4mMDTGdmZpuZMtc0bpS0r6STSc1TDwKzWx6ZmZlVTsOkIem1wEnAycDjwHWAIuLQYYrNzMwqpr9bbh8ADgOOjoiDIuKbwIZmZi7pSElLJC2VdG6d4adIWpT/bpe0T2HYckmLJd0jqbuZ5ZqZWWv01zx1PKmmcYukG4FraaKjwnyL7iXA4aSece+SNC8i7i+M9iBwcEQ8IekoYCbponvNof71uZlZdTSsaUTEnIg4EdgLuBX4JLCTpG9JOqLEvA8AlkbEsoh4jpR0jumzjNsj4on89k5gl0F8BjMzGyYD/iI8Ip6JiKsj4p2kg/o9wAuamuqYADxceL8ilzVyGvCT4qKBmyQtkDS9xPLMzKzFSv24ryYi/gx8O/8NpF5TVtQdUTqUlDQOKhQfGBGrJL0C+KmkByLitjrTTgemA+y6664lwjIzs8Eq0/fUYK0AJhbe7wKs6juSpCnA5cAxEfF4rTwiVuX/jwJzSM1dLxARMyOiKyK6Ojs7hzB8MzPrq5VJ4y5gD0m7SdqKdFF9XnEESbuSfvPxvoj4XaF8G0nb1V4DRwC/bWGsZmZWQlPNU82IiPWSzgDmAx3AFRFxn6TT8/DLgPOBHYFLJQGsj4guYCdgTi7bErgmIm5sVaxmZlaOIupeZhiRurq6orvbP+kwMytL0oJ8sl5Ky2oaZiPd3IUrmTF/CavW9LDzuLGcPXVPjt2vvxsAzTZ/ThpmdcxduJLzZi+mZ13qBGHlmh7Om70YwInDRrVWXgg3G7FmzF+yMWHU9KzbwIz5S9oUkVk1OGmY1bFqTU9T5WajhZOGWR07jxvbVLnZaOGkYVbH2VP3ZOyYjk3Kxo7p4Oype7YpIrNq8IVwszpqF7t995TZppw0zBo4dr8JThJmfbh5yszMSnPSMDOz0pw0zMysNCcNMzMrzUnDzMxKc9IwM7PSnDTMzKw0Jw0zMyvNScPMzEpz0jAzs9KcNMzMrDQnDTMzK81Jw8zMSnPSMDOz0pw0zMysNCcNMzMrzUnDzKxZi2bB1/eGC8al/4tmtTuiYeMn95mZNWPRLLjhTFjXk96vfTi9B5gyrX1xDRPXNMzMmnHz53sTRs26nlQ+CjhpmJk1Y+2K5so3M04aZmbN2GGX5so3My1NGpKOlLRE0lJJ59YZfoqkRfnvdkn7lJ3WzKwtDjsfxozdtGzM2FQ+CrQsaUjqAC4BjgImAydLmtxntAeBgyNiCvAFYGYT05qZDb8p0+Doi2CHiYDS/6MvGhUXwaG1d08dACyNiGUAkq4FjgHur40QEbcXxr8T2KXstGZmbTNl2qhJEn21snlqAvBw4f2KXNbIacBPmp1W0nRJ3ZK6V69e/SLCNTOzgbQyaahOWdQdUTqUlDQ+3ey0ETEzIroioquzs3NQgZqZWTmtbJ5aAUwsvN8FWNV3JElTgMuBoyLi8WamNTOz4dXKmsZdwB6SdpO0FXASMK84gqRdgdnA+yLid81Ma2Zmw69lNY2IWC/pDGA+0AFcERH3STo9D78MOB/YEbhUEsD63NRUd9pWxWpmZuUoou6lghGpq6sruru72x2GmdmIIWlBRHSVHd+/CDerulHco6pVj3u5NauyUd6jqlWPaxpmVTbKe1S16nHSMKuyUd6jqlWPk4ZZlY3yHlWtepw0zKpslPeoatXjpGFWZaO8R1WrHt89ZVZ1o7hHVase1zTMzKw0Jw0zMyvNScPMzEpz0jAzG6na0MWML4SbmY1EbepixjUNM7ORqE1dzDhpmJmNRG3qYsZJw8xsJGpTFzNOGmZmI1Gbuphx0jCzcvwwqGppUxczvnvKzAbmh0FVUxu6mHFNw8wG5odBWeakYWYD88OgLHPSMLOB+WFQljlpmNnA/DAoy5w0zGxgfhiUZb57yszK8cOgDNc0zMysCU4aZmZWmpOGmZmV5qRhZmalOWmYmVlpioh2xzBkJK0GHhrk5OOBx4YwnMGqQhxViAEcR1+OY1NViKMKMcCLi+PVEdFZduTNKmm8GJK6I6LLcVQjBsfhOEZCHFWIYbjjcPOUmZmV5qRhZmalOWn0mtnuALIqxFGFGMBx9OU4NlWFOKoQAwxjHL6mYWZmpbmmYWZmpTlpmJlZaZtF0pC0QdI9hb9Jkm4vMd2tkgZ1m1phmfdJulfSnyWVvte5VSSFpK9Kejq/P0vSBUM4/8/kz7wof/43lJjm85Lell9/QtJLhyiWCySdNcA4T5ec11WSTmhm3mXV5i3pl5KOKpRPk3TjUCyjwXJ3LOwTf5S0svB+q1Ytt0Esp0s6tbDf/FbSDZLGDfFyjsv7wF75faekX0taKOkv/Uy3yfp/kTFs3N4bDD9W0uTCd3GvpLslvXkolt8MSR+QdHF+fbqkUweaZnPpGr0nIvbtU9bqFbBxmZJeQfpR4dnAOS1e7kCeBd492IklbRkR6xsMexPwTmD/iHhW0nhgwINPRBSf1PMJ4D+Ahjtw2ThfzPRtcjpwvaRbgA7gfwNHtmphEfE4UNtGLwCejogLW7W8AWK5LMdxaWG/+S7wMdL3MFROBn4JnARcABwGPBAR7y97AvFi9dne6zkW+CGbHkOmAv8HOLjsciR1RMSGQQfaR20dlRlxxP+Rdoa6ZcAhwK3A94EHgKvpvQHgVqArv/4W0A3cB3yuMJ/lwOeAu4HFwF61+QM3AQuBbwMrgT8DIh0QZgB3AYuAj5SIZTnwJeCOHMf+wHzgD8DpeZxtgZsLsRyTyycB/x+4FNgAfBl4Lg87H3gYeAfw6jz9ovx/1zzOVcDXgFuAr+Z5j8uf5XHg1ML3dUde3i9yHA8At+bht5CS1lbA1sBTwLvy/E8AzgSey/O/JQ+7J/8tAR7M83kd8HNgQf4OXlVY/pfysE+RDgpn5WEfzt/3vcAPgJfm8nXARcDt+bM8lMf5F+Bi4PfAo8Da/B3W1m+ZeV9VmPcy4IRcrjzv+4EfAT8uDPsK8M+F/1fkeS8srM8PAHOBG4AHgTOAf8jj3Am8PI+3O3Bj/p5+UYj9BXHVPs8gPsvnC+toJXBlLp+bl3sfML2435GSwL051p2K32ceXothBWn7filp231XHncOcEV+fRrwxZLLXEzavt5E2i7fTtoe1wF/zOOdRlrnT5B+Qf04cEw/n3+gfe47OZ6bgLGF77I2/b+QtoNFwIWkk9k/5/W6Ia/DDwNLSdvgD4CppKRSi+kR0jZ6Auk4cT69ifFWeo9h44HlhW1oNmn7+D3wlcL39UHgd6T96DvAxX23+X6Pt+0+4A9R0thA74Y9p07SWAvsQmqOuwM4qE7SqO2IHbl8SuFg/vH8+u+By/Pr54Dz8+t3AAGsAXYCpgOfzcNeQkoCuw0Qy3Lgo/n11/NGth3QCTyay7cEti9sIEtJB6hJwPPAG0k7xvb5/WtIB8l/y9PcALw/v/4QMLewkf8Q6MjvL8ufaW/Szv2dXL40x/V7UqI8GNgLeDYPv5a0Mx5I2mGfzjFfRe9OtBwYX2cdziKddY4h7bidufxEeg8gtwKXFqa5gN4D+46F8i8W1tk64Pocz0LgD7n8VOCnpAPCgXndnQv8rIl5X5XnvQUwGViay9+d590B7JznXfv825AS5GLSmeV7c/k40o68DWmHX0rv+l9L74nD14FP5Nc3A3vk128oxP6CuOg9aDf1WQrj7pDX/ev67C9jgd/W5kvaD47Or79C735QW/7TwI75u7keuAb4OOkAOCOP+xvgzvz6SmBqmWUC780xfpa0Df2cdCvqxaRt6xnS9tcJvJyUaC/P30+jddnfPrce2Lew/b638F2ekJexhN4Tw3F9hteOW7/L6/h1eZ38K71J4/oc/z/mZS8Hzimsl1tpnDSW5fW2Nek4MBF4FfCf+TvYCvgVTSaNkVjFr6de81TRbyJiBYCke0gr/Jd9xpkmaTppI3kVacNZlIfNzv8X0Nv000FqZiEifiTpiVwGcAQwpdBGugOwBynR9BfLvPx/MbBtRDwFPCXpv3Lb7zPAlyS9hZQUJpCSFMBDEXGnJCLiSUnPkzaIH5DOUiCdgdXi/3fSTl1zffRWdX8BvIW0oX0LmC5pAums7M2kJpUvkRLPI8CWkv4H6QD5NHAU8DekHX+9JPoj6RzSOrxE0t6kZPXTPF1HXkbNdQ1ms7ekL5IOvtuSaig1c0nNFJeSalSQanKz8/tLctlHgP9qdt4R8Txwv6TaungL8L38fa6S9LPayBHxjKTrSN/TNODowrWTrYFd8+tbCut/LSnhQ9o2pkjalrQuri98vy8ZIK7BfBaUFnA18PWIWJCLz5R0XH49kbR9P07axn+YyxcAh2/6VTKWVAPZjfRdrwaeBL4AfELSZNKZ+cskvYq0zZ5Zcpk/JO1Dk0gnMF8G/g3Yj7S9X0hKJGtIyfevSCc92+a46n1+0XifezAi7il81kl9PuuT+TNeLulHhe+lpici9pV0MClR/Iq0rS8ujDM3fwer8nIfp/E+0NfNEbEWQNL9pJaG8aSWgdW5/DrgtSXnB2w+1zQG8mzh9Qb6fG5Ju5HOgl4fEU9Iuoq0A/edvu+0xR+5bJGHP0ra0D4eEcUdEkmHDBBLbdjzfcZ7Po93CukM4XURsU7S8kKcz7CpZ0lnrXsDP6O+YvzF6W8jnZntCnwGOI50ZvSLiNgg6fWkM+kvAu8n7UhHkc7qr8zj7pyH9UvSYcDfkQ60kL67+yLiTQ0m6fs5a64Cjo2IeyV9gFSrq3k2zzfy/6I1ecedDVwTEd8fxLw3fpzC6+J329fz+U/A8RGxpDgw31zQd/0Xt40tSdvbmn5OlhrFNZjPcgGwIiKuzPEdArwNeFNE/EXSrfRuh+sin7ZSZ18DenLZwaSmm4eArSNipaSXkU5IbiOdpU8jtRg8NdAy8/hvBQ4gJYCpNL7eVtuPZpBq4+8knZzU+/z97XN99+WxxYXkE6YDSCcsJ5GaGd9aJ56rSNc5biKdxBxVGPZsYXm1mIr7wHp6b2gqHrPqxVdbF/1tmwPaLO6eGgLbk1bE2nyGcdQA40NaCacASDqJVJu4PO8w84GPShqTh79W0jZDEOcOpKaqdZIOJZ05NBKkWkIXcFAuu5208ZJj71vbShNGPEw6I9kjIpbl8c4C/iBpjxzHI8A+pA11C9IF7jtIZ+27k3ageS+cO0+Rml2Q9GrS2f+0iOjJw5cAnfmiO5LGSPrrfj5nzXbAI/k7P6XO8JtINaOau0k76oOSPgwcmpe3zyDm3ddtwEmSOvLZ8qENxpsPfDyfySNpvxLzBiAinsyx/12eVg1i76upzyLpnaTawpmF4h2AJ/LBey9Ss2gztiM1cf4DcDy9B8M7SNvRbaTa7ln5f5llnkCqVXwU+H5ETCQ1ldb25VNICfdg4JWkGs5xpBOe/vajZva5TeTa4A4R8eP8uWoJfuM+kG1HOsHrIF3ne5rU0rEF6XrPYf0sZjmpWQvSdzCQXwOHKN1ZN4Z0wtaU0VLT6Fc+61pIuqC1jFRNHEgHcI6kz5BW8hrSmQukdtJJwN35gLCadIB6sa4GbpDUTWoLfWCA8S8k1RgmSfp70o5/haSzc0wf7GfaX9Pb3PYLUvv7EuC7wCtIO1sPaUd9I6nqfFtE/EnSo8CfC2ecRTOBn0h6hNQeuyMwJx83V0XE23Oz3kWSdiBto98grZv+/FOO+SFS9b64UxIRN0raF3hjbhb8MenANZVUY9qC1GTxHdJF3NLzrmMO6YxyMb0XHOv5Qv5si/J2spx01lvWKcC3JH2WdC3o2jqx99XsZ/kUqdb4m7yO5pEuOp8uaRFpm7iziZj7xvBHUlMVpO3siIhYKukheq87QLqg298yTybVXLYtlF2cl/UY6aJ7kJpVzyHVHp4lXdzvbz9qdp8r2g74v5K2JiXGT+bya0nb2Ta52aiHdGPIkjz/7UjXSD5CSh4L+1nGhcAsSe+jcYvCRhHxSL6T7g7Sid/d9O7npbgbERtSSr/BWEy6LXdtu+MxK5K0bUQ8nW/Zrt2lNafdcY0kbp6yIaP0g6YHgG86YVhFXZBrmr8l3fY6t83xjDiuaZiZWWmuaZiZWWlOGmZmVpqThpmZleakYdYPSa+UdK2kP0i6X9KPJTX1C9oB5n+I2tC7qdlgOWmYNZB/OzGH1O3C7hExmdQH0E79T9mUQ2jQI7NGZk++tplz0jBr7FBStxgbu4zOfQ39UtIMpWdCLJZ0ImysNWzsX0jSxbmrDiQtl/Q5pecmLJa0l6RJpO7SP6n0XIW/VXquw9eUuk+fIen3ys9pkbSFpKVKXdKbtYXPZMwa25vUEV1f7yZ1CbEPqbuVuyTdVmJ+j0XE/vnX+WdFxP+UdBmF51xIOo3Ugdzbcj9fa0i//P4Gqe+leyPisRf9ycwGyTUNs+YdRO7FNiL+ROom5PUlpiv2ljypn/GKPQ5fQerGHVLfWVc2H67Z0HHSMGvsPno7gytq1Nd7scdRaNzraL3eX4s29mKaO4/8k6S3kp6Z8ZP+AjZrNScNs8Z+Brwk94ILQO4W/gngxNyLbSepW/ffkDrgmyzpJbmzxf56J63p2+NpPZeTnt0yK4bw8Z5mg+GkYdZA7qX3OODwfMvtfaRnS1xDekDXvaTEck5E/DHXCmblYVfTf++kNTcAx9UuhDcYZx6p91Y3TVnbue8ps4qT1EV6al6jpGI2bHz3lFmFSTqX9GChMg9/Mms51zTMzKw0X9MwM7PSnDTMzKw0Jw0zMyvNScPMzEpz0jAzs9L+G6P58F+UXKJEAAAAAElFTkSuQmCC
"
>
</div>

</div>

</div>
</div>

</div>
<div class="cell border-box-sizing code_cell rendered">
<div class="input">
<div class="prompt input_prompt">In&nbsp;[89]:</div>
<div class="inner_cell">
    <div class="input_area">
<div class=" highlight hl-ipython3"><pre><span></span><span class="n">plt</span><span class="o">.</span><span class="n">scatter</span><span class="p">(</span><span class="n">x</span> <span class="o">=</span> <span class="n">top_averages</span><span class="p">[</span><span class="s1">&#39;Country&#39;</span><span class="p">],</span> <span class="n">y</span> <span class="o">=</span> <span class="n">top_averages</span><span class="p">[</span><span class="s1">&#39;Average Generosity&#39;</span><span class="p">])</span>
<span class="n">plt</span><span class="o">.</span><span class="n">scatter</span><span class="p">(</span><span class="n">x</span> <span class="o">=</span> <span class="n">bottom_averages</span><span class="p">[</span><span class="s1">&#39;Country&#39;</span><span class="p">],</span> <span class="n">y</span> <span class="o">=</span> <span class="n">bottom_averages</span><span class="p">[</span><span class="s1">&#39;Average Generosity&#39;</span><span class="p">])</span>
<span class="n">plt</span><span class="o">.</span><span class="n">xlabel</span><span class="p">(</span><span class="s1">&#39;Country&#39;</span><span class="p">)</span>
<span class="n">plt</span><span class="o">.</span><span class="n">ylabel</span><span class="p">(</span><span class="s1">&#39;Average Generosity&#39;</span><span class="p">)</span>
</pre></div>

    </div>
</div>
</div>

<div class="output_wrapper">
<div class="output">


<div class="output_area">

    <div class="prompt output_prompt">Out[89]:</div>




<div class="output_text output_subarea output_execute_result">
<pre>Text(0, 0.5, &#39;Average Generosity&#39;)</pre>
</div>

</div>

<div class="output_area">

    <div class="prompt"></div>




<div class="output_png output_subarea ">
<img src="data:image/png;base64,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
"
>
</div>

</div>

</div>
</div>

</div>
<div class="cell border-box-sizing text_cell rendered"><div class="prompt input_prompt">
</div><div class="inner_cell">
<div class="text_cell_render border-box-sizing rendered_html">
<p>Throughout the 5 graphs, we see that GDP and life expectancy show very clear disinctions between the top 5 and the bottom 5 countries. Though there is still a distinction between countries with freedom, trust, and generosity, there is much more overlap between the values in the top 5 and the bottom 5.</p>

</div>
</div>
</div>
<div class="cell border-box-sizing text_cell rendered"><div class="prompt input_prompt">
</div><div class="inner_cell">
<div class="text_cell_render border-box-sizing rendered_html">
<p>Here, there is a very clear distinction between the GDP in the top 5 countries vs the GDP in the bottom 5 countries. Becuase of this, we will run a regression to understand the relation between GDP and overall happiness. We run this on the entire dataframe to understand how all the values show relation.</p>

</div>
</div>
</div>
<div class="cell border-box-sizing code_cell rendered">
<div class="input">
<div class="prompt input_prompt">In&nbsp;[95]:</div>
<div class="inner_cell">
    <div class="input_area">
<div class=" highlight hl-ipython3"><pre><span></span><span class="n">df</span><span class="o">=</span><span class="n">df</span><span class="o">.</span><span class="n">rename</span><span class="p">(</span><span class="n">columns</span><span class="o">=</span><span class="p">{</span><span class="s1">&#39;Happiness Score&#39;</span><span class="p">:</span><span class="s1">&#39;Happiness&#39;</span><span class="p">})</span>

<span class="n">x</span> <span class="o">=</span> <span class="n">df</span><span class="p">[</span><span class="s1">&#39;GDP&#39;</span><span class="p">]</span><span class="o">.</span><span class="n">values</span><span class="o">.</span><span class="n">reshape</span><span class="p">(</span><span class="o">-</span><span class="mi">1</span><span class="p">,</span><span class="mi">1</span><span class="p">)</span>
<span class="n">y</span> <span class="o">=</span> <span class="n">df</span><span class="p">[</span><span class="s1">&#39;Happiness&#39;</span><span class="p">]</span><span class="o">.</span><span class="n">values</span>

<span class="n">reg</span> <span class="o">=</span> <span class="n">sm</span><span class="o">.</span><span class="n">ols</span><span class="p">(</span><span class="n">formula</span><span class="o">=</span><span class="s1">&#39;Happiness ~ GDP&#39;</span><span class="p">,</span> <span class="n">data</span><span class="o">=</span><span class="n">df</span><span class="p">)</span><span class="o">.</span><span class="n">fit</span><span class="p">()</span>

<span class="n">lm</span> <span class="o">=</span> <span class="n">linear_model</span><span class="o">.</span><span class="n">LinearRegression</span><span class="p">()</span>
<span class="n">lm</span><span class="o">.</span><span class="n">fit</span><span class="p">(</span><span class="n">x</span><span class="p">,</span> <span class="n">y</span><span class="p">)</span>

<span class="n">reg</span><span class="o">.</span><span class="n">summary</span><span class="p">()</span>
</pre></div>

    </div>
</div>
</div>

<div class="output_wrapper">
<div class="output">


<div class="output_area">

    <div class="prompt output_prompt">Out[95]:</div>



<div class="output_html rendered_html output_subarea output_execute_result">
<table class="simpletable">
<caption>OLS Regression Results</caption>
<tr>
  <th>Dep. Variable:</th>        <td>Happiness</td>    <th>  R-squared:         </th> <td>   0.682</td>
</tr>
<tr>
  <th>Model:</th>                   <td>OLS</td>       <th>  Adj. R-squared:    </th> <td>   0.679</td>
</tr>
<tr>
  <th>Method:</th>             <td>Least Squares</td>  <th>  F-statistic:       </th> <td>   291.1</td>
</tr>
<tr>
  <th>Date:</th>             <td>Fri, 18 Dec 2020</td> <th>  Prob (F-statistic):</th> <td>1.32e-35</td>
</tr>
<tr>
  <th>Time:</th>                 <td>16:44:50</td>     <th>  Log-Likelihood:    </th> <td> -131.87</td>
</tr>
<tr>
  <th>No. Observations:</th>      <td>   138</td>      <th>  AIC:               </th> <td>   267.7</td>
</tr>
<tr>
  <th>Df Residuals:</th>          <td>   136</td>      <th>  BIC:               </th> <td>   273.6</td>
</tr>
<tr>
  <th>Df Model:</th>              <td>     1</td>      <th>                     </th>     <td> </td>   
</tr>
<tr>
  <th>Covariance Type:</th>      <td>nonrobust</td>    <th>                     </th>     <td> </td>   
</tr>
</table>
<table class="simpletable">
<tr>
      <td></td>         <th>coef</th>     <th>std err</th>      <th>t</th>      <th>P>|t|</th>  <th>[0.025</th>    <th>0.975]</th>  
</tr>
<tr>
  <th>Intercept</th> <td>    3.2264</td> <td>    0.139</td> <td>   23.156</td> <td> 0.000</td> <td>    2.951</td> <td>    3.502</td>
</tr>
<tr>
  <th>GDP</th>       <td>    2.2842</td> <td>    0.134</td> <td>   17.062</td> <td> 0.000</td> <td>    2.019</td> <td>    2.549</td>
</tr>
</table>
<table class="simpletable">
<tr>
  <th>Omnibus:</th>       <td> 0.641</td> <th>  Durbin-Watson:     </th> <td>   1.296</td>
</tr>
<tr>
  <th>Prob(Omnibus):</th> <td> 0.726</td> <th>  Jarque-Bera (JB):  </th> <td>   0.761</td>
</tr>
<tr>
  <th>Skew:</th>          <td>-0.077</td> <th>  Prob(JB):          </th> <td>   0.684</td>
</tr>
<tr>
  <th>Kurtosis:</th>      <td> 2.670</td> <th>  Cond. No.          </th> <td>    4.97</td>
</tr>
</table><br/><br/>Warnings:<br/>[1] Standard Errors assume that the covariance matrix of the errors is correctly specified.
</div>

</div>

</div>
</div>

</div>
<div class="cell border-box-sizing text_cell rendered"><div class="prompt input_prompt">
</div><div class="inner_cell">
<div class="text_cell_render border-box-sizing rendered_html">
<p>We will print the p value of the regression which will show us how statistically significant the relationship between happiness and GDP is.</p>

</div>
</div>
</div>
<div class="cell border-box-sizing code_cell rendered">
<div class="input">
<div class="prompt input_prompt">In&nbsp;[96]:</div>
<div class="inner_cell">
    <div class="input_area">
<div class=" highlight hl-ipython3"><pre><span></span><span class="nb">print</span><span class="p">(</span><span class="s1">&#39;</span><span class="se">\t</span><span class="si">{}</span><span class="s1">&#39;</span><span class="o">.</span><span class="n">format</span><span class="p">(</span><span class="n">reg</span><span class="o">.</span><span class="n">pvalues</span><span class="p">[</span><span class="s1">&#39;GDP&#39;</span><span class="p">]))</span>
</pre></div>

    </div>
</div>
</div>

<div class="output_wrapper">
<div class="output">


<div class="output_area">

    <div class="prompt"></div>


<div class="output_subarea output_stream output_stdout output_text">
<pre>	1.3159381177526332e-35
</pre>
</div>
</div>

</div>
</div>

</div>
<div class="cell border-box-sizing text_cell rendered"><div class="prompt input_prompt">
</div><div class="inner_cell">
<div class="text_cell_render border-box-sizing rendered_html">
<p>Since the p value is very low, we recognize a high statistical significance between GDP and Happiness, which we assumed previously based on the plot.</p>

</div>
</div>
</div>
<div class="cell border-box-sizing text_cell rendered"><div class="prompt input_prompt">
</div><div class="inner_cell">
<div class="text_cell_render border-box-sizing rendered_html">
<h2 id="Plotting-Countries-over-Time">Plotting Countries over Time<a class="anchor-link" href="#Plotting-Countries-over-Time">&#182;</a></h2>
</div>
</div>
</div>
<div class="cell border-box-sizing text_cell rendered"><div class="prompt input_prompt">
</div><div class="inner_cell">
<div class="text_cell_render border-box-sizing rendered_html">
<p>Now we want to take a closer look at how factors for countries can change over time. We add a column for year for each of the datasets that we read in, spanning the interval from 2015 to 2020, and then combine these datasets so we can analyze changes over time. This way, the dataframe is set up to include all the information that we have read and sanitized from our intial datasets, with each row being key'd on both a country name and the year in which the data was collected. This is essential for being able to inspect changes for the same country over time, as well as setting up our regression analysis later.</p>

</div>
</div>
</div>
<div class="cell border-box-sizing code_cell rendered">
<div class="input">
<div class="prompt input_prompt">In&nbsp;[94]:</div>
<div class="inner_cell">
    <div class="input_area">
<div class=" highlight hl-ipython3"><pre><span></span><span class="n">df_2015</span><span class="p">[</span><span class="s1">&#39;Year&#39;</span><span class="p">]</span> <span class="o">=</span> <span class="mi">2015</span>
<span class="n">df_2016</span><span class="p">[</span><span class="s1">&#39;Year&#39;</span><span class="p">]</span> <span class="o">=</span> <span class="mi">2016</span>
<span class="n">df_2017</span><span class="p">[</span><span class="s1">&#39;Year&#39;</span><span class="p">]</span> <span class="o">=</span> <span class="mi">2017</span>
<span class="n">df_2018</span><span class="p">[</span><span class="s1">&#39;Year&#39;</span><span class="p">]</span> <span class="o">=</span> <span class="mi">2018</span>
<span class="n">df_2019</span><span class="p">[</span><span class="s1">&#39;Year&#39;</span><span class="p">]</span> <span class="o">=</span> <span class="mi">2019</span>
<span class="n">df_2020</span><span class="p">[</span><span class="s1">&#39;Year&#39;</span><span class="p">]</span> <span class="o">=</span> <span class="mi">2020</span>

<span class="n">yearly_df</span> <span class="o">=</span> <span class="n">df_2015</span><span class="o">.</span><span class="n">append</span><span class="p">(</span><span class="n">df_2016</span><span class="p">)</span><span class="o">.</span><span class="n">append</span><span class="p">(</span><span class="n">df_2017</span><span class="p">)</span><span class="o">.</span><span class="n">append</span><span class="p">(</span><span class="n">df_2018</span><span class="p">)</span><span class="o">.</span><span class="n">append</span><span class="p">(</span><span class="n">df_2019</span><span class="p">)</span><span class="o">.</span><span class="n">append</span><span class="p">(</span><span class="n">df_2020</span><span class="p">)</span>
<span class="n">yearly_df</span><span class="o">.</span><span class="n">head</span><span class="p">()</span>
</pre></div>

    </div>
</div>
</div>

<div class="output_wrapper">
<div class="output">


<div class="output_area">

    <div class="prompt output_prompt">Out[94]:</div>



<div class="output_html rendered_html output_subarea output_execute_result">
<div>
<style scoped>
    .dataframe tbody tr th:only-of-type {
        vertical-align: middle;
    }

    .dataframe tbody tr th {
        vertical-align: top;
    }

    .dataframe thead th {
        text-align: right;
    }
</style>
<table border="1" class="dataframe">
  <thead>
    <tr style="text-align: right;">
      <th></th>
      <th>Country</th>
      <th>Region</th>
      <th>Happiness Rank</th>
      <th>Happiness Score</th>
      <th>Standard Error</th>
      <th>GDP</th>
      <th>Family</th>
      <th>Life Expectancy</th>
      <th>Freedom</th>
      <th>Trust</th>
      <th>...</th>
      <th>upperwhisker</th>
      <th>lowerwhisker</th>
      <th>Ladder score in Dystopia</th>
      <th>Explained by: Log GDP per capita</th>
      <th>Explained by: Social support</th>
      <th>Explained by: Healthy life expectancy</th>
      <th>Explained by: Freedom to make life choices</th>
      <th>Explained by: Generosity</th>
      <th>Explained by: Perceptions of corruption</th>
      <th>Dystopia + residual</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <th>0</th>
      <td>Switzerland</td>
      <td>Western Europe</td>
      <td>1.0</td>
      <td>7.587</td>
      <td>0.03411</td>
      <td>1.39651</td>
      <td>1.34951</td>
      <td>0.94143</td>
      <td>0.66557</td>
      <td>0.41978</td>
      <td>...</td>
      <td>NaN</td>
      <td>NaN</td>
      <td>NaN</td>
      <td>NaN</td>
      <td>NaN</td>
      <td>NaN</td>
      <td>NaN</td>
      <td>NaN</td>
      <td>NaN</td>
      <td>NaN</td>
    </tr>
    <tr>
      <th>1</th>
      <td>Iceland</td>
      <td>Western Europe</td>
      <td>2.0</td>
      <td>7.561</td>
      <td>0.04884</td>
      <td>1.30232</td>
      <td>1.40223</td>
      <td>0.94784</td>
      <td>0.62877</td>
      <td>0.14145</td>
      <td>...</td>
      <td>NaN</td>
      <td>NaN</td>
      <td>NaN</td>
      <td>NaN</td>
      <td>NaN</td>
      <td>NaN</td>
      <td>NaN</td>
      <td>NaN</td>
      <td>NaN</td>
      <td>NaN</td>
    </tr>
    <tr>
      <th>2</th>
      <td>Denmark</td>
      <td>Western Europe</td>
      <td>3.0</td>
      <td>7.527</td>
      <td>0.03328</td>
      <td>1.32548</td>
      <td>1.36058</td>
      <td>0.87464</td>
      <td>0.64938</td>
      <td>0.48357</td>
      <td>...</td>
      <td>NaN</td>
      <td>NaN</td>
      <td>NaN</td>
      <td>NaN</td>
      <td>NaN</td>
      <td>NaN</td>
      <td>NaN</td>
      <td>NaN</td>
      <td>NaN</td>
      <td>NaN</td>
    </tr>
    <tr>
      <th>3</th>
      <td>Norway</td>
      <td>Western Europe</td>
      <td>4.0</td>
      <td>7.522</td>
      <td>0.03880</td>
      <td>1.45900</td>
      <td>1.33095</td>
      <td>0.88521</td>
      <td>0.66973</td>
      <td>0.36503</td>
      <td>...</td>
      <td>NaN</td>
      <td>NaN</td>
      <td>NaN</td>
      <td>NaN</td>
      <td>NaN</td>
      <td>NaN</td>
      <td>NaN</td>
      <td>NaN</td>
      <td>NaN</td>
      <td>NaN</td>
    </tr>
    <tr>
      <th>4</th>
      <td>Canada</td>
      <td>North America</td>
      <td>5.0</td>
      <td>7.427</td>
      <td>0.03553</td>
      <td>1.32629</td>
      <td>1.32261</td>
      <td>0.90563</td>
      <td>0.63297</td>
      <td>0.32957</td>
      <td>...</td>
      <td>NaN</td>
      <td>NaN</td>
      <td>NaN</td>
      <td>NaN</td>
      <td>NaN</td>
      <td>NaN</td>
      <td>NaN</td>
      <td>NaN</td>
      <td>NaN</td>
      <td>NaN</td>
    </tr>
  </tbody>
</table>
<p>5 rows × 32 columns</p>
</div>
</div>

</div>

</div>
</div>

</div>
<div class="cell border-box-sizing text_cell rendered"><div class="prompt input_prompt">
</div><div class="inner_cell">
<div class="text_cell_render border-box-sizing rendered_html">
<p>Using the previously found top and bottom 5 countries in average happiness rating over our time interval, we look at how this rating can fluctuate over a span of several years for this sample of countries. Before we looked at happiness rating and possible variables that could affect it as average values over our time interval and then comparing between different countries. Now we want to plot these changes across years for the same country, and we will include the top 5 and bottom 5 countries in happiness rating together on the same plots as they are more comparable.</p>

</div>
</div>
</div>
<div class="cell border-box-sizing code_cell rendered">
<div class="input">
<div class="prompt input_prompt">In&nbsp;[95]:</div>
<div class="inner_cell">
    <div class="input_area">
<div class=" highlight hl-ipython3"><pre><span></span><span class="c1"># Plotting happiness of countries over time</span>
<span class="n">happiness</span> <span class="o">=</span> <span class="n">yearly_df</span><span class="o">.</span><span class="n">pivot</span><span class="p">(</span><span class="n">index</span><span class="o">=</span><span class="s2">&quot;Year&quot;</span><span class="p">,</span> <span class="n">columns</span><span class="o">=</span><span class="s2">&quot;Country&quot;</span><span class="p">,</span><span class="n">values</span><span class="o">=</span><span class="s2">&quot;Happiness Score&quot;</span><span class="p">)</span>

<span class="n">top5</span> <span class="o">=</span> <span class="p">[</span><span class="s1">&#39;Finland&#39;</span><span class="p">,</span> <span class="s1">&#39;Denmark&#39;</span><span class="p">,</span> <span class="s1">&#39;Switzerland&#39;</span><span class="p">,</span> <span class="s1">&#39;Norway&#39;</span><span class="p">,</span> <span class="s1">&#39;Iceland&#39;</span><span class="p">]</span>
<span class="k">for</span> <span class="n">country</span> <span class="ow">in</span> <span class="n">top5</span><span class="p">:</span>
    <span class="n">plt</span><span class="o">.</span><span class="n">plot</span><span class="p">(</span><span class="n">happiness</span><span class="p">[</span><span class="n">country</span><span class="p">],</span> <span class="n">label</span><span class="o">=</span><span class="n">country</span><span class="p">)</span>
    <span class="n">plt</span><span class="o">.</span><span class="n">legend</span><span class="p">(</span><span class="n">country</span><span class="p">)</span>


<span class="n">yMax</span> <span class="o">=</span> <span class="n">plt</span><span class="o">.</span><span class="n">ylim</span><span class="p">()[</span><span class="mi">1</span><span class="p">]</span>
<span class="n">plt</span><span class="o">.</span><span class="n">title</span><span class="p">(</span><span class="s2">&quot;Distribution of Happiness Scores Across 5 Happiest Countries Over Time&quot;</span><span class="p">)</span>
<span class="n">plt</span><span class="o">.</span><span class="n">xlabel</span><span class="p">(</span><span class="s2">&quot;Year&quot;</span><span class="p">)</span>
<span class="n">plt</span><span class="o">.</span><span class="n">ylabel</span><span class="p">(</span><span class="s2">&quot;Happiness Score&quot;</span><span class="p">)</span>
<span class="n">plt</span><span class="o">.</span><span class="n">legend</span><span class="p">(</span><span class="n">bbox_to_anchor</span><span class="o">=</span><span class="p">(</span><span class="mf">0.03</span><span class="p">,</span><span class="mf">0.95</span><span class="p">),</span> <span class="n">loc</span><span class="o">=</span><span class="mi">2</span><span class="p">,</span> <span class="n">ncol</span><span class="o">=</span><span class="mi">5</span><span class="p">)</span>
<span class="n">plt</span><span class="o">.</span><span class="n">show</span><span class="p">()</span>
</pre></div>

    </div>
</div>
</div>

<div class="output_wrapper">
<div class="output">


<div class="output_area">

    <div class="prompt"></div>




<div class="output_png output_subarea ">
<img src="data:image/png;base64,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h3322WcHPbkPfpyxs+6Z4ynuFUvlUql22Lm+I1scLXxKmDdvXsQ333xTcf369bvCw8OdMTExvgBjx46tP3Xq1MOtW7fO+Omnn0LvvffeeqtXr97jOu/tt99+9tFHH40DePDBB2u9+eabVZ566qnTADExMf7r1q3btWnTpqAbb7yxyV133XX2k08+qbBv377A3bt3bz927Jh/69ato0aPHh1fnG3TRKGcyKvqwVXnzp2pU6cOwPk2DLkThXnz5jF16lSys7M5efIkO3bsOJ8o5NzVdezYkc8//xyAFStWnP970KBBVKxYrGqtciendGDx4sVs2bKFBQsWAJCYmMjevXsJCAgocD/nXLRat25NSkoK4eHhhIeHExQUREJCAqGhoTz55JOsWLECHx8fjh8/TkxMDAD169ena9eu52PJysqib9++vPPOO/Tq1eui7YPSFBYWxvr16/nll1/4+eefGTZsGK+88gpNmjRh586drFmzhkceeYQVK1bgcDjo2bNnkZb7r3/9i+DgYO677z62bdvGtm3bzidWDoeDmjVrnp922LBheS5j27ZtPP300yQkJJCSksLV/fpzPCGNxLQsOvcewJlz2URFRXEmPpYWNSOYvnkto+64neDAAIJr1eLqq692fweVMREREYwcOZJPPvnEPycxA9i4cWPod999tx/g3nvvPfP888/XyRl30003nfXzsy4rPXv2TFm+fHnYoUOHAsaOHXv6ww8/rHrw4EH/yMjI7MjISGd8fLzv3XffXX/Hjh3BPj4+HD58OBBg0KBBKQ899FD948eP+82aNavioEGDzl5q1RhLliyJuOOOO+LCw8OdANWrV3ckJib6bNy4MezWW29tnDNdZmbmBcVS69evD540aVLt5ORk39TUVN9evXol5owbMmRIgq+vLx07dkyPj4/3B1i+fHn40KFDz/j5+dGgQYOsbt26JRc3Xk0UiqmwO39vySnOBauhXu462IMHD/Laa6+xdu1aKlasyOjRo//U02TO/LnnLfXi02Le+ZeWAwcO4OvrS7Vq1TDG8NZbbzFw4MA/TbNs2bIC93POOB8fnz9N5+PjQ3Z2NrNmzSI2Npb169fj7+9PgwYNzn8HoaGhf1qXn58fHTt25IcffiiVRKGgO//S5OvrS+/evenduzetW7fm448/pmfPnnz33Xf4+/vTr18/Ro8ejcPh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
"
>
</div>

</div>

</div>
</div>

</div>
<div class="cell border-box-sizing code_cell rendered">
<div class="input">
<div class="prompt input_prompt">In&nbsp;[96]:</div>
<div class="inner_cell">
    <div class="input_area">
<div class=" highlight hl-ipython3"><pre><span></span><span class="n">bottom5</span> <span class="o">=</span> <span class="p">[</span><span class="s1">&#39;Yemen&#39;</span><span class="p">,</span> <span class="s1">&#39;Tanzania&#39;</span><span class="p">,</span> <span class="s1">&#39;Rwanda&#39;</span><span class="p">,</span> <span class="s1">&#39;Afghanistan&#39;</span><span class="p">,</span> <span class="s1">&#39;Burundi&#39;</span><span class="p">]</span>
<span class="k">for</span> <span class="n">country</span> <span class="ow">in</span> <span class="n">bottom5</span><span class="p">:</span>
    <span class="n">plt</span><span class="o">.</span><span class="n">plot</span><span class="p">(</span><span class="n">happiness</span><span class="p">[</span><span class="n">country</span><span class="p">],</span> <span class="n">label</span><span class="o">=</span><span class="n">country</span><span class="p">)</span>
    <span class="n">plt</span><span class="o">.</span><span class="n">legend</span><span class="p">(</span><span class="n">country</span><span class="p">)</span>


<span class="n">yMax</span> <span class="o">=</span> <span class="n">plt</span><span class="o">.</span><span class="n">ylim</span><span class="p">()[</span><span class="mi">1</span><span class="p">]</span>
<span class="n">plt</span><span class="o">.</span><span class="n">title</span><span class="p">(</span><span class="s2">&quot;Distribution of Happiness Scores Across 5 Least Happiest Countries Over Time&quot;</span><span class="p">)</span>
<span class="n">plt</span><span class="o">.</span><span class="n">xlabel</span><span class="p">(</span><span class="s2">&quot;Year&quot;</span><span class="p">)</span>
<span class="n">plt</span><span class="o">.</span><span class="n">ylabel</span><span class="p">(</span><span class="s2">&quot;Happiness Score&quot;</span><span class="p">)</span>
<span class="n">plt</span><span class="o">.</span><span class="n">legend</span><span class="p">(</span><span class="n">bbox_to_anchor</span><span class="o">=</span><span class="p">(</span><span class="mf">0.03</span><span class="p">,</span><span class="mf">0.95</span><span class="p">),</span> <span class="n">loc</span><span class="o">=</span><span class="mi">2</span><span class="p">,</span> <span class="n">ncol</span><span class="o">=</span><span class="mi">5</span><span class="p">)</span>
<span class="n">plt</span><span class="o">.</span><span class="n">show</span><span class="p">()</span>
</pre></div>

    </div>
</div>
</div>

<div class="output_wrapper">
<div class="output">


<div class="output_area">

    <div class="prompt"></div>




<div class="output_png output_subarea ">
<img src="data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAAh0AAAEWCAYAAADCTyW5AAAABHNCSVQICAgIfAhkiAAAAAlwSFlzAAALEgAACxIB0t1+/AAAADh0RVh0U29mdHdhcmUAbWF0cGxvdGxpYiB2ZXJzaW9uMy4yLjIsIGh0dHA6Ly9tYXRwbG90bGliLm9yZy+WH4yJAAAgAElEQVR4nOydd3gVxf6H38lJr5BCAgkQWiihhxJKKAKCBLgoKnhVFFBE7lVs14KA2O7PfhVBsYBeFeEqCipFAZHepErvJQkkpPd2zpnfH7sJh5Cek5wkzPs8eXJ2Z3bmu7Mzs5+dKqSUKBQKhUKhUFQ3drY2QKFQKBQKxc2BEh0KhUKhUChqBCU6FAqFQqFQ1AhKdCgUCoVCoagRlOhQKBQKhUJRIyjRoVAoFAqFokawiugQQiwUQsy2UljNhBAZQgiDfrxJCPGQNcLWw1srhHjAWuFVIN7XhBAJQojYmo67LIQQM4UQn9vaDoWitiKEiBBCnLS1HbUBIcRRIcQgW9tRUxR9JymqRpmiQwhxQQiRLYRIF0KkCCF2CCGmCSEKr5VSTpNSvlrOsIaW5kdKeUlK6S6lNJXvFkqNb64Q4psi4d8mpfxvVcOuoB1NgaeBDlLKgGLcBwkhoos5b1XBVRJSyn9LKas9nvIghGgghFgshIjV89wpIcRztrarLPRnlSyEcLK1LSUhhPhSCJGnV6AZpVWkJeXJarbttTL8SCFE6yLnbijj1YGUcquUsm1VwhBCBOv3YF+GvxAhxPf6R0qqEOIvIcRT1f3SK88zAJBShkopN1VD/A8KIQ4LIbL08v+xEKKBteMpJt4Ii/KQqT+jwjICYK13kqL8LR2jpZQeQHPgDeA5YJG1jSmrMNZhmgOJUsqrtjakDvAfwB1oD3gBY4Cz1ozA2vlMCBEMRAASzd7KhFFTef8tvQJ1VxVp7UMI0QrYDUQBnaSUXsBdQA/Aw8a2VVseFUI8DbwJ/Aut3Iej1ZvrhRCOVo7ruvvQBaW7lNIdCNVPN7AoI5esGf9Nj5Sy1D/gAjC0yLlegBnoqB9/Cbym//YFVgEpQBKwFU3cfK1fkw1kAM8CwWgV9RTgErDF4py9Ht4m4P+APUAq8BPgrbsNAqKLsxcYAeQB+Xp8hyzCe0j/bQfMAi4CV4GvAC/drcCOB3TbEoAXS0knL/36eD28WXr4Q/V7Nut2fFnMtTfcRzG2NtTTNR5I1n8HFfFbUjoV3MtU4DJwBXja4tq5wDfluW/9np5HEwKJwHcW8TgD3+jnU4A/AX/d7UHgHJAOnAfuLSEdjwBjS0nnUGA9Wt6KA2bq552A9/X7u6z/drJMXzSxHIuWFyt1HyXYNAfYDrwHrCri1hT4UX9uicB8i/TYjiaykoDXKCEP6f5bA5v1Z5sA/E8/L/Qwrupuf6GXy2Ls/BK9nJaj3A+imDypuzUBftDtPA88XqRu2Kmn2xVgPuBYmq1o+TIfrbxmAL+UEK8EWhc5Nxc97+rHH6C9sNOAfUBEEb/Lgf/p+XA/0KVI3fECcAytjH0BOBeXHuVIg726DXHAe/r5S/o9ZOh/fYq5x2+A1WU8mzHAUT2NNwHtS0ojrq+bB6GVg6f1Z3AFmKS7FfsM9DR5Tn9WuYA9Fu8ErFCOAE89zruLnHfX7Zysp3d2Qdi6eze0suCgH08GjuvP7jegeZF0+QdwGjhfStoGY/H+Ke6cnuavATsK0grwAZboz/xPINji+nZcq7NOFr3Pm+2vPJVPYQYrcv4S8GgxGfv/gIWAg/4XAYjiwrJ4mF8BboBLCQ84Bq1yckMr6AUvyEGUIDr033OxqJAswit4kU8GzgAt9Qz+I/B1Eds+0+3qglbo2peQTl+hveg99GtPAVNKsrPItcW6F7HVBxgHuOpxfA+sLOK3pHQquJelulsntMryhnQq676BJ4BdQBDai/4TYKnu9ghaAXQFDEAYWoXihlYY2+r+GgOhJaTF52gV6iSgTRE3D3TBhFaheQC9dbdXdLsaAX5oFcKrFulrRPuSctLvq8L3UcrzOwNM1/3lc01oGYBDaC9aN93m/rrbg7pNj6FV5C6UnoeWAi+iVfKW4QxHe7k2QHuptwcal2Dnl2gVX5J+zbhK5Ek7/do5gCNa2TkHDNfdw9C+Uu31ezgOPFGWrZRDEFE+0XEfWlmx1/NJLNeEw1z9+dyJVjc9gyYYCl5aF9BEb1PAG00UvlY0PcqRBjuB+/Xf7kB4kbJlX8o9xqILgRLcQ4BMYJh+D8+i5T/H4tKIG0WHEa2sOAAjgSygYUnPQE+Tg3qauBRTx1a5HKF9IBqLSxfgvxbhbQQetnB7G1io/x6rp0N7/dnPAnYUyTvr9efqUkr63vCMip5Dq2vPAK3QPhSOoZXVoXrcXwFf6H7d0ETwJN2tO5pQKrb+uxn+yvZQsujYhf4FXCRjv4JWcbYuKyyLh9myjAf8hoV7BzQ1bqDqouN3YLqFW1u0SqmgwpRc35qwB5hQzH0Z0F7MHSzOPQJs0n/fYGeR6wehtYSkFPkzFthazDVdgeQi91VSOhXcSzsL97eARUXTqaz7RnuJDLFwa2yRZpPRXvadi9jqpt/POEop8LpfF2AmWqWej1a4b9Pd7gEOlHDdWWCkxfFw4IJF+uahv3wqex8lxNtfv85XPz4BPKn/7oMm7oqrTB8ELlUgD30FfGr5XPTzt6BVeOHorSKl2Nqday/kkWhf+/1KyZPFiY7elnbr515Ar2SL8f8EsKIsWym/6Ejj+jKSQ5EyXuSaZPTWDLR8vsvCzQ5NxEboxxeAaRbuI4GzRdOjrDRAa7F9uSBPWPgJpmzRkQ+MKMV9NvBdkXuIAQZZpFFpoiOb61+oV7kmim54BnqaTC7mXEEdW+VyhCYUY0twewNYr/9+CNio/xZoL/MB+vFadIFukS5Z6K0derrcUpodJT2joufQ6lrL1t93gbUWx6OBg/rv8cDWInF8ArxUli319a8qs1cC0b6YivI22otinRDinBDi+XKEFVUB94toKt23XFaWThM9PMuw7QF/i3OWs02y0L5ciuKL9sVTNKzACthyWUrZwPIP2FbgKIRwFUJ8IoS4KIRIQ6vYGhQZXFZWOhV1b1KKPSXdd3NghT6oOAWt0jGhpdnXaM2ay4QQl4UQbwkhHKSUmWiFbxpwRQixWgjRrrhIpZTZUhvYGob2gvwO+F4I4Y32tVXS+I7inqXl/cVLKXMsjit8HyXE+wCwTkqZoB9/q59Dt/eilNJYwrWWz6OsPPQsWkW7R589MBlASrkRrQtjARAnhPhUCOFZXGRSyv1SykQppVFKuQatOfiOEmwrieZAk4J009NuJnqZ0QdBrtIHAqYB/9bvrUK2lkL3ImXkDUtHIcTTQojj+gDMFLQv0WLLgJTSjNbd0KQ4d0ouI6WmAVp3cQhwQgjxpxBiVAXuLxHtxV0S1+Vz/R6iKH9dk1gkP5ZUp1lSWv1sjXKUAPiWMGakse4OWtdYHyFEE2AAmhDYamHHBxZ2JKGVF8t0Kes9UxHiLH5nF3NsWV/2LpJX7gVumFBws1Ap0SGE6In2MLcVdZNSpkspn5ZStkRTfE8JIYYUOJcQZEnnC2hq8bsZmpJOQGtmdLWwy4DWtF7ecC+jZQrLsI1cn4HKQ4JuU9GwYioYTmk8jdYS01tK6YlW6EArWAWUlE4luV+uhB1RaC0PlgLJWUoZI6XMl1K+LKXsAPQFRgETAaSUv0kph6FVIifQum9KRUpZ8NJyA1rocbcqwXtxz9Ly/ormhUrdhyVCCBfgbmCg/pKNBZ4EugghuuhxNCtlAJ6lTaXmISllrJTyYSllE7QWkI8KZnJIKefpIi0U7WX3rxLiKy5+Uaav64lC6xO3TDcPKeVI3f1jtOfbRs+nMy3jKMXWsspqmQghItDGH9yN1mXQAG3sSLFlRGgz8IK4Pp+Up4yUmgZSytNSynvQuvreBJYLIdzKeY8b0FoES+K6fC6EELrNBXVNFhZ1IhV7uVWmfq5yOULrjsqliADW0+w2tBZppJQpwDq05/t3tG6XAtuigEeK2OEipdxRzvuoLqKAzUXscpdSPmoDW2oFFRIdQghPXbUvQ2vSPFyMn1FCiNZ6YUhDU70FI+Tj0Po/K8p9QogOQghXtO6b5VIbdX8KcBZCROoKehZav2IBcUCwsJjeW4SlwJNCiBZCCHe0F9z/SvkyLRbdlu+A14UQHkKI5sBTaIOorIUHmoJO0b/6XyrGT0npVMBsvcUkFK2P8X+VsGMh2n02BxBC+Akh/qb/HiyE6KSLvzS0l6hJCOEvhBijVyK5aIOvip01IYSYLYToKYRwFEI4AzPQmtFPog2eDRBCPCGEcNLTurd+6VJglm6PL1p/e2npX+H7KCaMsfr5DmjdXV3R+pS3olWue9Ca798QQrgJIZyFEP2KM6asPCSEuEsIEaR7T0arQE16WvXW838mWndDSWl7pxDCXQhhJ4S4Fa1Z++dS0gjd5sI//Z7ShBDPCSFchBAGIURH/UMEtHyaBmTorVmPWoRVmq2VrRss8UD7aIgH7IUQc9DGFFkSJoS4QxeCT6Dlx10W7v8QQgTpZWwmxZeRUtNACHGfEMJPb4VI0a8x6XaZy7jPl4C+Qoi3hRABenithRDfCG366HdApBBiiJ6OT+v3UPByPQj8XbdpBDCw9CS7jso8gyqXIyllKlp31IdCiBFCCAehzQj7Hq0l6msL79+ila1x+m9LO17Q6zaEEF5CiLsqeC/VwSogRAhxv35fDno5aG9rw2xFeUXHL0KIdDTV9iLaKP1JJfhtg6bWM9AU7Efy2pzu/0N7MaQIIZ6pgJ1fo/U3xqINonscCjPrdLTBhzFoFZnl2gLf6/8ThRD7iwl3sR72FrQBZTloA/sqw2N6/OfQWoC+1cO3Fu+jjXdIQKskfy3GT7HpZMFmtK6v34F3pJTrKmHHB2gvqnV6ntiF1scN2lfVcrQK5rge3zdo+exptK+0JLSKcHoJ4Uu0WQMJuv9hQKSUMkNKma4fj9bv8TQwWL/uNbQZA38Bh9FmJpS25kBl7qMoD6D141/SWyJipZSxaF0I96J9YY9Gm3lyCS1vji/FptLyUE9gt9DWDfgZmCGlPI/2Uv0MTYhcRGuef6eE8GeglZMUtG7Qh2Xp6y0Eogldy78W+j11RSszCWjlz0u/5hm0r9B03S7Ll3Zpti4COuh1w8pSbCqN39D69k/p4edwY5P6T2jPIBm4H7hDSplv4f4t2tf0Of3vhjykC8TS0mAEcFR/Vh+gjYfKkVJmAa8D2/X7DC8m7LNoY4GC9TBS0QaF7wXSpZQn0cTih3q8o9GWNMjTg5ihnytoxq9IWlbmGVijHCGlfAtN5L2j+y+YNjxESplr4fVntHdMnJTykMX1K9BalZYJrVvvCForiU3R66xbgQlo9Vks1wa035QUzCpR1HGEEJvQWp9uWFlU/2o4jzZKv0KtOApFfUEIMRdtkOV9JbhfQBu4vaEm7VIobibU3isKhUKhUChqBCU6FAqFQqFQ1Aiqe0WhUCgUCkWNoFo6FAqFQqFQ1Aj1dYO1asPX11cGBwfb2gyFQqGoU+zbty9BSulXtk9FfUaJjgoSHBzM3r17bW2GQqFQ1CmEEBfL9qWo76juFYVCoVAoFDWCEh0KhUKhUChqBCU6FAqFQqFQ1AhKdCgUCoVCoagRlOhQKBQKhUJRIyjRoVAoFAqFokZQokOhUCgUCkWNoERHDbHzbCJfbD+PWnZeoVAoFDcrSnTUED8djOHlX47xj2/3k5aTb2tzFAqFQqGocZToqCH+745OzBzZjt+OxjHmw20cvZxqa5MUCoVCoahRlOioIYQQTB3Qiv9NDScn38ztH+1g6Z5LqrtFoVAoFDcNSnTUMD2CvVn9eH96t/DmhR8P8/R3h8jKM9raLIVCoVAoqh0lOmyAj7sTX07qxZNDQ1hxMIa/zd/O6bh0W5ulUCgUCkW1okSHjTDYCWYMbcM3U3qTnJXHmPnbWXkgxtZmKRQKhUJRbQg1pqBi9OjRQ1Z2a/v8/Hyio6PJycm57rzJLEnKzCPXaMbNyUADFweEENYwV6FQKGoFMTExeX5+fldsbYei2jEDR4xG40NhYWFXizra28CgGkMIYQD2AjFSylFF3ATwATASyAIelFLur057oqOj8fDwIDg4+AZRIaUkNi2H+PRcHBwMNPN2xcnBUJ3mKBQKRY1hMpmMHTt2TLC1HYrqxWw2i/j4+A6xsbGfA2OKutf37pUZwPES3G4D2uh/U4GPq9uYnJwcfHx8im3FEELQ2MuFYB838kxmzlzNIDUrr7pNUigUCoXCatjZ2Uk/P79UoGOx7jVsT40hhAgCIoHPS/DyN+ArqbELaCCEaFwDdpXq7uniQJtG7jg5GLiYlMXllGzMqgtMoVAoFHUEOzs7SQn6ot6KDuB94Fm0/qXiCASiLI6j9XM3IISYKoTYK4TYGx8fb10ri8HR3kBLPzd83Z1IyMjlXHwmecaSbkOhUCgUirpBvRQdQohRwFUp5b7SvBVzrtgmBSnlp1LKHlLKHn5+flaxsSzshKBJAxeae7uSm2/i9NV00rKrtny6lJL+/fuzdu3awnPfffcdI0aMqKq5Nw2JiYl07dqVrl27EhAQQGBgYOFxXl7NdoctXLiQr776qkbjrGkMBgNdu3alY8eOjB49mpSUlBqL293dvcbisiUrVqxACMGJEycAiI+Pp3fv3nTr1o2tW7eWeN2DDz7I8uXLrWLDE0880WTlypUeJbl//fXXDfbt2+dslcjqMAaDIaxdu3Yd2rZt26FDhw7t169f71bTNsybN89n4sSJzQDeeustv/nz5/tU5Pr6OpC0HzBGCDEScAY8hRDfSCnvs/ATDTS1OA4CLtegjeXCy9URZ72r5UJiJo08nPD3dK7U7BYhBAsXLuSuu+5i8ODBmEwmXnzxRX799ddqsLx+4uPjw8GDBwGYO3cu7u7uPPPMMzaxZdq0aTaJtyZxcXEpTO8HHniABQsW8OKLL9rYqvrF0qVL6d+/P8uWLWPu3Ln8/vvvtGvXjv/+9781ZsP7779fat27cuXKBkajMTUsLCynNH/1HScnJ/OJEyeOAfzwww+eM2fODBo2bNjJ8l5vNBqxt7fea//ZZ5+tcNN/vWzpkFK+IKUMklIGAxOAjUUEB8DPwEShEQ6kSilr5XQuJwcDrf3c8XZz5Gp6LucSMsk3Va67peCL8c033+Tll1/mvvvu4/XXX6dnz55069aNn376CYAvv/ySsWPHMnr0aFq0aMH8+fN577336NatG+Hh4SQlJQFw9uxZRowYQVhYGBEREYVfSw8++CCPP/44ffv2pWXLllb7IqqNfPbZZ/Ts2ZMuXbowbtw4srKygJLTYM6cOYWtI4GBgUyaNAmAsWPHEhYWRmhoKJ9++mlh+O7u7rz44ot06dKF8PBw4uLiAE30vPPOO6XaUJ/o06cPMTHaWjbTp0/n559/BuD2229n8uTJACxatIhZs2YBFU/P8+fP06dPH3r27Mns2bML/WdkZDBkyBC6d+9Op06dCstIfSAjI4Pt27ezaNEili1bxsGDB3n22WdZs2YNXbt2JTs7m0WLFhESEsKgQYN4+OGH+ec//1l4/ZYtW27I3yWlV3R0tGjZsmXohAkTmrdu3Tq0X79+bTIyMgTAuHHjgr/44ouGANOnTw9s1apVaEhISIepU6cGrV+/3m3Dhg0NZs2aFdSuXbsOR48edXr33Xd9O3bs2L5t27Ydhg8f3io9Pd2uIJwHH3ywabdu3doFBQV1KgizPpKammrw8vIyAqxatcpj8ODBrQvcJk6c2GzevHk+AIGBgZ2eeeaZxmFhYW0XL17csFevXm23bNniCnDlyhX7wMDATqC1YNx6662tIiIi2jRv3rzjtGnTggrC++CDD3yCg4M79uzZs+2OHTsKmwCfeuqpJnPmzPGviN31taWjWIQQ0wCklAuBNWjTZc+gTZmdVJO2vPzLUY5dTqvwdUazJNdoQiBwsrfDYHetxaNDE09eGh1aZhgvvfQS3bt3x9HRkVGjRnHLLbewePFiUlJS6NWrF0OHDgXgyJEjHDhwgJycHFq3bs2bb77JgQMHePLJJ/nqq6944oknmDp1KgsXLqRNmzbs3r2b6dOns3HjRgCuXLnCtm3bOHHiBGPGjOHOO++s8P2WytrnIfawdcMM6AS3vVGhS+644w4efvhhAGbNmsWiRYt47LHHgOLT4JVXXuGVV14hNTWViIiIwkp88eLFeHt7k52dTc+ePRk3bhw+Pj5kZmYSHh7O66+/zrPPPstnn31W+GItjw3W4M09b3Ii6YTVwgNo592O53o9Vy6/JpOJ33//nSlTpgAwYMAAtm7dypgxY4iJieHKFe17Ydu2bUyYMAGoeHrOmDGDRx99lIkTJ7JgwYLCuJ2dnVmxYgWenp4kJCQQHh7OmDFjrLqWTuy//03uceumr1P7dgTMnFmqn5UrVzJixAhCQkLw9vbGbDbzyiuvsHfvXubPn8/ly5d59dVX2b9/Px4eHtxyyy106dKl8Pri8ndJ6QVw6dIl52+++eZc3759L44cObLlV1991XD69OlJBeHFxcUZ1qxZ0/DcuXNH7OzsSEhIMPj6+pqGDh2aMmrUqNRJkyYlA/j4+BiffvrpBIDHH3+8ybx583xffPHFq3oYDnv37j1x8OBB59tvv711wTXW5PevjjdNislwtWaY3oHuWUMmto8qzU9ubq5du3btOuTm5oqEhASHNWvWnCpP2M7OzuZ9+/adBPj8888bleTv2LFjrocOHTrm4uJibt26dcdnnnkmzsHBgTfeeKPJvn37jnt7e5v69u3btmPHjpX+qqn3okNKuQnYpP9eaHFeAv+wjVWVx95OYOdgIDffTE6+CUd7OxwMFWuwcnNzY/z48bi7u/Pdd9/xyy+/FH4x5+TkcOnSJQAGDx6Mh4cHHh4eeHl5MXr0aAA6derEX3/9RUZGBjt27OCuu+4qDDs3N7fw99ixY7Gzs6NDhw6FX5P1kSNHjjBr1ixSUlLIyMhg+PDhhW4lpYGUknvvvZcnn3ySsLAwAObNm8eKFSsAiIqK4vTp0/j4+BSKQ4CwsDDWr19fIRvqMtnZ2XTt2pULFy4QFhbGsGHDAIiIiOD999/n2LFjdOjQgeTkZK5cucLOnTuZN28eUPH03L59Oz/88AMA999/P889pwkiKSUzZ85ky5Yt2NnZERMTQ1xcHAEBATWaFtXB0qVLeeKJJwCYMGECS5cuJTT02ofLnj17GDhwIN7e3gDcddddnDp17T1XXP4uKb0AAgMDc/v27ZsN0K1bt6wLFy44Wdrj7e1tcnJyMk+YMKF5ZGRk6vjx44vdjnvfvn0uc+bMCUxPTzdkZmYaBg4cWOhvzJgxKQaDgbCwsJzExEQHa6RTbcGye2XDhg1ukyZNanHq1KmjZV03ceLEcgmv/v37p/n4+JgAWrdunXP27Fmnq1ev2oeHh6c3adLECHDHHXcknTp1qtLja+q96KitlKdFojRMZklMSjYpWXm4O9nTzNsV+wqIDzs7O+zs7JBS8sMPP9C2bdvr3Hfv3o2Tk9N1/guO7ezsMBqNmM1mGjRoUNjnXhTL66tl5dsKtkhUFw8++CArV66kS5cufPnll2zatKnQraQ0mDt3LkFBQYVdK5s2bWLDhg3s3LkTV1dXBg0aVLhyrYPDtRVqDQYDRuONGwSWZoM1KG+LhLUpGNORmprKqFGjWLBgAY8//jiBgYEkJyfz66+/MmDAAJKSkvjuu+9wd3fHw8Oj0ulZXOvFkiVLiI+PZ9++fTg4OBAcHHzDqsJVpawWieogMTGRjRs3cuTIEYQQmEwmhBC8/PLLhX7KKrfF5e/S0svR0bEwQIPBILOzs6+rtBwcHDh48ODxn3/+2XPZsmUNP/7440a7du264Wt+6tSpLZYvX36mT58+2fPmzfPZvHlz4SBUZ2fnwjiqa8XtslokaoKhQ4dmJicn21+5csXewcFBms3Xutxzc3Ovy8geHh6Fjvb29tJkMgGQlZV1nb+izyc/P19A2Us9VIR6OabjZsBgJ2ja0IXABi5k5pk4fTWDzNyK71Y7fPhwPvzww8LCeeDAgXJf6+npSYsWLfj+++8BrYAfOnSowjbUddLT02ncuDH5+fksWbKkTP+rVq1i/fr1hV/kAKmpqTRs2BBXV1dOnDjBrl27qtWGuoaXlxfz5s3jnXfeIT9fm8XVp08f3n//fQYMGEBERATvvPMOERERQOXSs1+/fixbtgzgujRMTU2lUaNGODg48Mcff3Dx4sVquMOaZ/ny5UycOJGLFy9y4cIFoqKiaNGiBdHR0YV+evXqxebNm0lOTsZoNBa2BJVGVdIrNTXVLikpyTB+/PjUhQsXRh0/ftwVwN3d3ZSWllb4vsrKyrJr1qxZfm5urli2bJl3hW68nnDgwAFns9mMv7+/sVWrVrlnzpxxyc7OFomJiYZt27Z5lnRd06ZNc/fs2eMGsGTJkjLHvAwYMCBz165dHrGxsYbc3FyxYsWKKo2TUaKjDiOEwMfdidZ+bggB5+IziU/PrZC6nz17Nvn5+XTu3JmOHTteN4CuPCxZsoRFixbRpUsXQkND69Ugu/Ly6quv0rt3b4YNG0a7du3K9P/uu+9y+fJlevXqRdeuXZkzZw4jRozAaDTSuXNnZs+eTXh4eLXaUBfp1q0bXbp0KRQGERERGI1GWrduTffu3UlKSioUHZVJzw8++IAFCxbQs2dPUlOvterfe++97N27lx49erBkyZJ6k75Lly7l9ttvv+7cuHHj+Pe//114HBgYyMyZM+nduzdDhw6lQ4cOeHl5lRpuVdIrJSXFMGLEiDYhISEdIiIi2r722mtRephJ8+bNC2jfvn2Ho0ePOj3//POXe/Xq1T4iIiKkTZs2N82MloIxHe3ateswYcKElh9//PEFe3t7WrdunT969Ojk9u3bh955550tQkNDSxxz8fzzz8ctWrTIr1u3bu0SEhLK7O1o3rx5/nPPPXc5PDy8ff/+/UM6d+5cpVHqasO3ClKVDd+OHz9O+/btrWyRhslsJjo5m9TsfDydHQhq6FKh7qVdLnEAACAASURBVBaFQqEojoyMDNzd3TEajYUzhYqKlfJw5MiRrI4dO5a0LYWinnHo0CHfLl26BBc9r95K9QSDnR3NvF1p4uVCeo6RM1czyMqreHeLQqFQWDJ37tzCBdpatGjB2LFjbW2Sog6jBpLWI4QQ+Ho44eJo4FJSFmfjM2ni5Yy3m6NVBwIpFIqbh4KZbQqFNVAtHTVMTXRnuTnZ06aRO+5O9sSkZBOVlI3JrLrRFAqFQlH9mM1mQQn7ninRUYM4OzuTmJhYI8LD3mBHsI8rAZ7OpGbnceZqBtn5pmqPV6FQKBQ3L2azWcTHx3sBR4pzV90rNUhQUBDR0dHUxE61lpiMJmIy84k+L/FyccDNST12hUJRs8TGxtqbTCZfW9uhqHbMwBGj0fhQcY7q7VODODg40KJFC5vEHZ+ey4xlB9hx9gp3hgXx6t864uJosIktCoXi5qNDhw6HpZQ9bG2Hwrao7pWbBD8PJ76e0pvHb2nND/ujGbtgO2fjM2xtlkKhUChuIpTouIkw2AmeurUtX07qRXxGLmM+3MYvh0rdUVqhUCgUCquhRMdNyMAQP1Y/3p92jT15bOkBZq88Qq5RDTJVKBQKRfWiRMdNSmMvF5ZNDWfqgJZ8vesid368k0uJVVrdVqFQKBSKUlGi4ybGwWDHzJHt+fT+MC4mZhL54VbWHY21tVkKhUKhqKco0aHg1tAAVj8eQbCPG1O/3sfrq4+Rbyp2XReFQqFQKCqNEh0KAJp6u7L80T7cH96cz7aeZ8Knu7iSmm1rsxQKhUJRj6i3okMI4SyE2COEOCSEOCqEeLkYP15CiF8s/Eyyha21BSd7A6+O7ci8e7px4koakfO2sflUzS5kplAoFIr6S70VHUAucIuUsgvQFRghhAgv4ucfwDHdzyDgXSGEY82aWfsY06UJPz/Wn0YeTjz4xR7eXXdS7d2iUCgUiipTb0WH1ChY/cpB/yv65pSAh9C2YHUHkgC1HzzQys+dFdP7cWf3ID7ceIb7Pt/N1fQcW5ulUCgUijpMvRUdAEIIgxDiIHAVWC+l3F3Ey3ygPXAZOAzMkFKqEZQ6Lo4G3r6rC2/d2ZkDUclEztvGrnOJtjarVpOxdSsZmzcj8/JsbYpCoVDUOuq16JBSmqSUXYEgoJcQomMRL8OBg0ATtC6Y+UIIz6LhCCGmCiH2CiH21vRmbbWBu3s0ZeU/+uHhZM/fP9vFgj/OYFbdLTeQuPgLoh6eStQj0zgdMYArc14ic/cepFnpWIVCoQAQNbHNem1ACPESkCmlfMfi3GrgDSnlVv14I/C8lHJPSeH06NFD7t27t+IGbHsfLu2C4H7QvB8EdAZD3dpvLyPXyAs/HuaXQ5cZ3NaP9+7uSkO3m34IDFJK4t//gMRPPsFjxAi8/jaGtDVrSf/9d2RWFvaNGuF52214jhqFc8dQtN48haJ6KLFOr8jpEsIQQiDsKpd/hRD71IZvirr11qsAQgg/IF9KmSKEcAGGAm8W8XYJGAJsFUL4A22Bc9VikJ0BEk7BqbXasZMnNAvXBEhwf2jctdaLEHcne+ZN6EqvFt68+ssxIudtZf693enerKGtTbMZ0mwm7rXXSP52KV53jqPxyy8jDAY8Bg/GnJVFxqZNpK5eQ/K335L03//i0LwZXpGReEZG4tSqla3NV1SCjOQcVr53gPSkYsY4FfOuLvGzroQXe/EioJzGVTN/e6IrQe28bW2Gog5Tb1s6hBCdgf8CBrRupO+klK8IIaYBSCkXCiGaAF8CjQGB1urxTWnhVrqlo4C0K3BxO1zYpv1POKWdd3SHpr21lpDgCGjSDQwOlY+nmvkrOoXpS/YTm5rDCyPbM7lf8E33BS/z87k880XSfvkF78mTafSvZ0pMA1NqKukbNpC6ahVZu/eA2YxT+/Z4RY7Ec+RIHJo0qWHrFZXlj6+Pc2J3LF2HNC05z5d0uqJlpGLBQwnhV6ZoFndNSK8APH1dKh4YqqVDoVFvRUd1UWXRUZT0OE18FAiR+BPaeQdXaNpLawVp3h8Cu4O9k/XitQKpWfk8s/wQ64/FMSI0gLfu6oync+0VStbEnJNDzBNPkrFpE35PPonP1IfL/UIxxseTtvZX0lavJvvQIQBcunfHM3IkniNGYO/jU52mK6pAcmwmS1/eTefBTel/dxtbm1OnUKJDAUp0VBiri46iZCboAkQXIVePauftnTUR0ry/1hoS2AMcnKvPjnIipeTzred549cTBDV0YcHfu9Mx0MvWZlUrpowMoh+dTtbevQTMmU3De+6pdFh5UVGkrV5D2urV5J4+DQYDbn364BkZicewoRjc3a1ouaKqrP3kMFHHk7j/1T64eKjxTBVBiQ4FKNFRYapddBQlKwku7tC7Y7ZB7BFAgsEJgnpeG5jatBc4VK7Z0xrsvZDEP789QFJWHi+N7sDfezWrl90txuRkoh56mJyTJ2nyf/+H1+hRVgs759SpQgGSHx2NcHTEfeBAPCMjcR80EDtn24vMm5nY86n88OY+eo1uQc/IFrY2p86hRIcClOioMDUuOoqSnQwXd17rjon9C6QZDI4QGHZtYGrTXuDoVqOmJWbk8uR3h9hyKp6xXZvw+u2dcHOq3YNjK0J+bCyXJk8hPyaGwA/ex2PQoGqJR0pJzqFDpK5eQ9ratZgSErBzc8Nj6FA8R0XiFh6OcLg5urFqC1JKfvrPAZKuZHLfq31wdK4/+bqmUKJDAUp0VBibi46i5KRqU3ELBqZePgjSBHb20KS7JkCC+0HTcHCq/qZ6s1my4I8z/GfDKVr6ufPmuM50a9oAu0pOs6st5F24wKXJUzClphL08Ue49epVI/FKk4msPXtIXb2a9N/WYU5Px9CwIR4jhuMVGYlL9+4Iu3q93E6t4OLRRFZ9eIiI8SF0Hhxka3PqJEp0KECJjgpT60RHUXLT4dJurSvmwna4vB/MRhAGbUZMcD9tXEizcHC+YR00q7HjTAKPLztAQkYevu5ODAjxZWCIHxFt/PCuY2t75Jw4waWHHgaTiaaffYZLx1Cb2GHOyyNz61bSVq8mfeMfyJwc7Bs3xnPkbXhFRuLUvn297NKyNdIs+e7//iQv28jf54ZjsFcirzIo0aEAJToqTK0XHUXJy4So3dcGpsbsA3M+CDto3OVad0yzPuDSwKpRp2TlsfHEVTafimfLqXiSs/IRAjoHNWBQiB8D2/rRJagBhlrcCpK1/wBR06Zh5+pKs8WLcGrZ0tYmAWDOzCR94x+krVpFxvbtYDTi2KIFnpGReEaOxKmFGnNgLU79Gcv6RccYNrkDIb0CbG1OnUWJDgUo0VFh6pzoKEpeFkT/ea07JvpPMOUBAgI66d0xughxtd4iQCaz5HBMKptPxrP51FUORqVgluDl4kBEG60VZGCIH408a89gyYyt24h+7DHs/RvRfPFiHAIDbW1SsRiTk0lft5601avJ+vNPkBLnDh0KBYhDgHpRVhaT0cy3c3fh4GzP+Jk9K70ap0KJDoWGEh0VpM6LjqLk50DMXk2EXNimiRBjDiDAP1RfJ0SfIeNmvfUjUrLy2HYmQRch8VxNzwWgfWNPBrXVBEj3Zg1xtFFTdtqvvxHzr3/h1KoVzT7/DHtfX5vYUVHy4+JIW7uWtFWryTlyBITANSwMz1GReAwfjn3Dm3f12MpweFM0W5adYtQ/u9C8o1o/pSoo0aEAJToqTL0THUUx5mpdMBe2a+NCLu0GY7bm1qiD3h2jjwtx97NKlFJKjl9JZ/MprRVk74VkjGaJu5M9fVv5MFAXIUENXa0SX1mkLF/OlTkv4dKlC00/WYjBs/rGvlQneRcukLpmDWmrVpN37hzY2+PWtw9ekZG4DxmKwb1mZzfVNfJyjHwzeycNA9wY+1Q3NV6miijRoQAlOipMvRcdRTHmweUD1wamXtoF+Zmam2/ba+uEBPcHD+s042fkGtlxJoHNp+LZdDKemBRN9LTyc2NgSCMGtvWjdwtvnB0MVonPksTFX3D1rbdw69+foHkfYOdaM0KnOpFSknviBGmrV5O6Zg3Gy1cQTk64Dx6MZ+RI3AcMwM6pdq12Wxv4c/V59vxynnHPhhHQsn4veFcTKNGhACU6KsxNJzqKYsqHK4eudcdc2gV56ZqbT2tdgERoYsSz6vuJSCk5l5BZ2A2z61wiuUYzzg52hLf0KRwL0sLXrUpfokV3ig18602EY92aZVMepNlM9sGDpK1aTdqvv2JKSsLO3R2PYcPwjIzELbw3wl6tQZGdkcfXs3bStJ03t03rZGtz6gVKdChAiY4Kc9OLjqKYjNoCZQUDUy/uhNxUza1hC+h0Fwx4xmr7xuTkm9h1LlHvionnXLzW6tLU20UXII3o28qnQouSWe4U2+CuOwmYOxdhsH4rSm1DGo1k7tylTcHdsAFzRgYGHx88R4zAMzISl25db9ouhW3fn+avjVFMmNMb78aqG8oaKNGhACU6KowSHWVgNkHsYU2AnNsEp9dpY0FuX6hN0bUyUUlZhQJkx5kEMvNMOBgEPZp7awNS2/rR1t+jxJenzM/n8gszSVu1Cu8pk2n0TMk7xdZnzLm5ZGzeTNrqNWT88QcyLw+HJk20TegiI3Fq2/amSZe0xGyWvLSLtr0DuOX+9rY2p96gRIcClOioMEp0VJDT6+Gnf0JWAgx8Dvo/BYbqab7PM5rZezFJEyEn4zkRq3X7+Hs6FbaC9G/ti5ertoR4VXaKrc+YMjJI37CBtNVryNyxA0wmHFu3wisyEs/ISBybNbO1idXK718e4/Teq9z7Sjge3rVnCnddR4kOBSjRUWGU6KgEWUmw9lk4/L22NPvtC8GvbbVHG5eWU9gKsvVUPGk5RuwEdGvWkFuaujHoqzexO3ywyjvF1meMSUmk//YbqatWk71vHwDOnTrhNSoSjxG34eDfyMYWWpfEmAyWvbaHrkOb0W9ca1ubU69QokMBSnRUGCU6qsDRlbDqSW2V1CFzIHw61NC+IUaTmUPRKWw+Gc+fh85xzw/v0SL1Mgv73o/DsOEMbKst0e7rrmZxlET+5cukrV1L6urV5B47rq0B0qsXnpEj8Ro1ql7M9Fn90V9cPp3C/a/1wdlNbapnTZToUIASHRVGiY4qknEVfpkBJ9doM13GfgQNg2ss+oKdYvNiYoiZMZs1bq3YcjqehIw8ADoFemldMW396Na0AfYGtc9GceSeO0fa6jWkrVpF3sWLOIeG0vSzT7H3tt4qtjXNlTMp/PjOfsLHtiRsRLCtzal3KNGhgDoiOoQQzYE2UsoNQggXwF5KmW4LW5TosAJSwqGlsPY5beDp8Nch7EGo5vEUJe0UazZLjl1JY9NJbZ+Y/ZdSMJklHs72hUu0Dwjxo7GXS7XaVxeRUpK+YQOXn/kXDk2a0GzR5zg0qfpU6ZpGSsmKd/eTGp/Nfa/2wcGx/s9eqmmU6FBAHRAdQoiHgamAt5SylRCiDbBQSjmkjOucgS2AE2APLJdSvlSMv0HA+4ADkCClHFhauEp0WJGUKPjpH3B+M7QeCmM+tMraHsVRkZ1iU7PzCxcn23wqniupOQC09fcoXB21R3BDnOzVi6mArL17iZr2KHbu7jRb9DlOrVrZ2qQKceGvBFZ/9BcD/96WjgNq5x47dR0lOhRQN0THQaAXsFtK2U0/d1hKWeqKPUKbhuAmpcwQQjgA24AZUspdFn4aADuAEVLKS0KIRlLKq6WFq0SHlTGbYe8iWDcb7B1h5Dva2h5WbPWoyk6xUkpOX80oXJxsz/kk8kxmXBwM1y3R3txHreWQc/w4lx6eCkYjTT/7FJdOdWNRLbNZ8r/X9mAymrnnpd4YVJdataBEhwK0FoDaTq6UMq9gKqMQwh4oUylJTU1l6IcO+l/R6/4O/CilvKRfU6rgUFQDdnbQ62FodQusmAY/PgzHf4FR/wG3qm+yVtWdYoUQhPh7EOLvwcMDWpKZayxcnGzTyXh+P6FlmWAfVwa1bcTAED/6tPKpliXaazvO7dsTvOQbLk2ewsUHHqTpgvm49elja7PK5NSeWJIuZ3LrQ6FKcCgU1UxdaOl4C0gBJgKPAdOBY1LKF8txrQHYB7QGFkgpnyviXtCtEgp4AB9IKb8qJpypaF08NGvWLOzixYtVuidFCZhNsOND+ON1cPaC0R9Au8hKB1cTO8VeSMi8tjjZ2QRy8s008nDin7e0ZnzPpjdlF0x+3FWiHnqIvAsXaPLOO3gOv9XWJpWIKd/Mkpd24ezuwF3P91Bb11cjqqVDAXVDdAjgIeBWQAC/AZ/LChiud6OsAB6TUh6xOD8f6AEMAVyAnUCklPJUSWFVtntFSqkWniovcUdhxSPayqZd7oERb4BLgwoFUbhTbNeuNF34cY3sFJuTb2LnuUQ+/uMsey4k0cTLmceGtOHOsCAcbrIvaFNqKlGPTCP7r78ImPsSDe++29YmFcuh36PY9v1pxszoStP2dXfmTV1AiQ4FQK2uCYUQdsBhKeVnUsq7pJR36r8rpJSklCnAJmBEEado4FcpZaaUMgFt4Kn11+oGEj/9jEuPPELmnj3UdqFnc/xD4aGNMOBZ+Os7+LgvnP2j3JcnLlrMlVmzcevbl2aff1ZjW9M7OxgY3LYR/3sknK+n9KKRpzMv/HiYIe9uZvm+aIwmc43YURsweHnRbPEi3Pr1I3bOSyR89lmty/d52Ub2rr1AULuGSnAoFDVErRYdUkozcEgIUeF1l4UQfnoLB/o026HAiSLefgIihBD2QghXoDdwvIpmF4uduxs5h49waeIDXJgwgbR165AmU3VEVT+wd4RbXoSH1oOjG3w9FlY/rS0sVgJSSq7+532uvv02HiNG0PSjBTZZsEoIQUQbP1ZM78viB3vg6WLPM98f4tb/bOGngzGYzLXr5Vtd2Lm60nTBfDwjI4l/9z2uvv1OrRIeBzZcIicjnz63162ZNgpFXaYudK9sBHoCe4DCN46UckwZ13UG/gsY0MTVd1LKV4QQ0/TrF+r+/gVMAsxo3TbvlxZuVWavmHNySF25ksTFX5B/6RKOwcF4T56E19/+hp2TWgmzRPKzYeNrsHOBtpDY7QuhWfh1XmrzTrFSStYdi+M/609xIjadEH93nhwawvDQAOxugjEE2rN5neRvv8Xrjjto/MrLCHvbjmHPSsvj69k7aR7qw4ipHW1qy82C6l5RQN0QHcWumyGl3FzTtoB1psxKk4n09etJ/Oxzco4exeDni/f9E2k4YXyNdQXUSS5sg5WPaut79HscBs0EB+c6s1Os2SxZc+QK/1l/irPxmXRo7MlTw0IY0r5RrbTXmkgpSZi/gIQFC3AfMoTA9961qdDesuwUR7bE8PeXetPAv+4v314XUKJDAXVAdAAIIfzRWjsA9thyaqs11+mQUpK1ezeJny8ic9s27FxdaTB+PN4PTMQhIMAqcdQ7ctNh3SzY9yX4tcc8ch4xb35Rp3aKNZklPx2M4YPfT3MxMYsuTRvw1LAQBrTxrfW2V5Wkr78h7vXXce3Vi6CPFmBwd69xG1Ljs/l27i7a923MoHvb1Xj8NytKdCigDogOIcTdwNtoA0EFEAH8S0q53Bb2VNfiYDnHj5O4aDFpa9eCnR1eo0bhM2UyTq3VTpfFcno9pu//SfSvRrLiHQmY9SIN773P1lZViHyTmR/3RzPv9zPEpGTTo3lDnro1hL6trD+1tzaR+ssvXH5hJs4hIdp+LT4+NRr/+sVHOXcgnvte7YNbA9WtWVMo0aGAuiE6DgHDClo3hBB+wAYpZbXMMimL6l6RNC86hqQvvyRl+XJkTg7ugwfj89AUXMPCqi3OuogxKYmoKZPJOXmKJr2T8OrTDsYuhEZ178s1z2jmf3ujWLDxDLFpOfRp6cPTt4bQI7j+zqjI2LyZ6BlP4BAQoO3XUsFF2ypLQnQ6/3v9T7oPb06fsWoAaXnINZrYcTaRdUdjeWpYW/w8KifUlOhQQN0QHdctea5Poz1U1jLo1UVNLYNuTE4m+dtvSf5mCabkZFy6dcPnoSm4Dx6MqKHt4GsrBTvF5sfEEPjB+3j4pcCqJ7WZLUPmQPijYFc7BpFWhJx8E9/uvsRHm86SkJHLgBA/nhoWQtemFVujpK6QtW+ftl+Lq6u2X0sNtOr98uEh4s6ncv9rfXByVVvXl0RmrpFNJ+P57Wgsf5y4SnquETdHA5/c34P+bSrXEqdEhwLqhuh4G+gMLNVPjUdbu+NZW9hT03uvmLOzSfnxR5IWf0F+TAyOLVviM2UynqNHY+foWGN2FEeOMYerWVeJy4rT/jLjCo+vZl0lLjMOicTXxRcfFx98XXxL/HNzKN/eJSXtFEvGVfhlBpxcA836wtiPwLtFNd599ZGdZ+KrnRdYuPksyVn5DG3fiCeHhRDaxMvWplmdnJMnufTQQ5CXT9NPP8GlS/U1YMacSmblewfoc0crut/avNriqaskZeax4Vgcvx2NZeuZBPKMZrzdHBnW3p/hHf3p28q3Ssv7K9GhgDogOgCEEHcA/dHGdGyRUq6wlS222vBNGo2k/fYbiYsWkXvsOPZ+fng/MJEG48dj8PCwblxSkpaXdoOAKBQX+rnU3NQbrnV3cMff1Z9Gro3wd/PHTtiRkJ1Q+JeUnYRRGm+4zsXepVRR4uviS4OoFDL+8SyYzcXvFCslHFoKa5/TllQf/hqETbLq5nE1SUaukS+3n+fTLedIyzFyW8cAnhwWQoi/dZ+3rcm7dIlLUx7CmJhI0IfzcO/Xz+pxSCn54a19ZKbkcu/L4dirresBiEnJZt3RWH49EsufF5IwSwhs4MLw0ACGh/rTI9gbg5WmdSvRoYA6IDqEEC2AK1LKHP3YBfCXUl6whT223mVWSknmjh0kLVpE5o6d2Lm703DCeBrePxEH/0ZlXm8ym0jKSSq5dUL/n23MvuFaH2efQjHh7+p/nbho5NoIf1f/MlsszNJMam4q8dnxJGQnkJidSEJ2QrHH6XnphdeFREue/95EjgN8+IA3xmb++Ln4XWtFcfbFz1U/Nhrx/f11PM5vRbQaAn+bD55NKp7YtYTU7HwWbTvP4m3nycwzMrpzE2YMbUMrv5qf+VFd5F+9StRDD5N7/jyBb7+N54jhVg3/3IF41n5ymMH3t6NDv7qbF6qKlJIzVzP47Wgsvx2N43CM9uEQ4u+uC40AQpt4VsssKiU6FFA3RMdeoK+UMk8/dgS2Syl7ln5l9WBr0WFJ9tGjJC1aRNqvvyEMBtzHjMI0YRQJjZxKbJ2Iz4rHJK9fCdVe2N8gHoqKCz8XPxwMNdsHnmvKJTE7kcRNGzC8+A55Pp7se2EUMe5517WeJGQnkG/Ov+F6J2HANz8PH7PE1y8UX//O+OrCxNdZaz3xc/XDx9mnxu+tMiRn5vHp1nN8uf0CuUYTt3cLYsaQNjTzqR/rTJhSU4l6dDrZBw4QMHcuDcdbZ78Ws8nMslf3ADBhdi/sbrJ9cMxmyV8xqfx6JJZ1R2M5l6CtsditWYNCodHCt3zdm1VBiQ4F1A3RcVBK2bXIuUP1dfZKSWTkZZTYOpEXFUW3jVH03Z+NoxH+bCNYGW7H6SCBi72LJhyKtk64+tPITfvv7eyNnaidFXF5doot6A4qKkQSshNISDlPQtROEowZJDq6kEzxS897OXkVChFf12uixMfFR2tB0Y+9nLxsvpZGQkYuCzed5etdFzGZJXf1COKft7QhsIGLTe2yBubsbKJnzCBzy1arrbtybPtl/vj6BLc90omW3fysZGntJt9kZs/5JH47Gsu6o3HEpuVgbycIb+nD8FB/hnUIIMDLuWKBmvKhCuJciQ4F1A3RsR74UEr5s378N+BxKeUQW9hjbdFhlmaSc5JvEBOWrRNxmXFkGbNuuLahU8PrWicCje6E/H4W79W7sUvPxLFbFxo9/AjugwbWyRkvVtsp1myCHR/CH6+T7+RJ4vBXSAzsel23TkHXjuVxrin3hqDs7ezxcfa5vmtHH3Pi5+KHj4sPAW4BNHJtVO1CLi4th4/+OMPSPVEATOjVlH8Mbo2/ZwVfJrWM61aYfeABGj33bKXzrzHPxJKXduHWwIlxz4bZXDBWJ9l5Jrac1mac/H78KqnZ+Tg72DEwxI/hoQEMaeePV2Vm7BhzYe9i2PYfmPhzpaelK9GhgLohOloBS4AmaANJo4CJUsoztrCnsqJjf9x+jiQcuWHsRFxWHEbz9QMrDcKAr4tv8a0TFt0gTobi58ubMzNJ+eFHEr/8AuPlKzi2boXP5Cl4jYpE2HjGS3lJXLSYq2+/jVv//gTN+8A6G7fFHYMVj0DsX9DlHhjxBrgUPx1VSklmfuYNY00KhIrlcVJOEpLry5GTwYlA90CaejQlyCOIph5Ntd/uQQR6BJb47CpDTEo28zee4fu9URjsBPeFN+fRQa3wda+7C19Js5m41/9N8pIleI0dS+PXXq3Ufi0H1l1ix49nGPtkNwLbNqwGS21LanY+G0/E8duRODafiic734Snsz1D2/szvGMAA9r44VLZQbMmI/y1DDa9AalREBwBI9+GRu0rFZwSHQqoA6KjACGEO5q96WV6rkYqKzpe3vkyy08tx9ngfOPYCV1YFJz3cfbBYIV1JmR+Pmm//kri54vIPXkSe39/vB94gAZ332WT5afLg5SS+Pc/IPGTT/AYMYLAt960rlAy5sGWt2Hru+ARoA0ybXVL1YI0G0nOSS4UJFcyrhCVHkV0RjRR6VFEpUddNzBXIGjk2ugGMVLwu7JdOJcSs5i38TQ/7o/Gyd7AA32DeWRASxq61Q2hWRQpJQkffUTCh/Nxv+UWbb8W5/K34uRm5fP1rJ34t/Bk9GNdy76gjnA1LYffjsWx7mgsO88mYjRL/D2duLWDNj6jd0tvHKoybkVKOP6ztsliwilo0g2GvAQtB1VpJpgSHQqoxaJDCDEa+EtKeVE/ngOMAy4CM6SU521hxQX5aQAAIABJREFUV2VFR1JOEgZhwNOxekaGl4aUksxt20j8fBFZu3dj5+FBw3vuwfv++7D3qz193DW6U2zMPlgxTatUe0yBYa+AU/UIMSklSTlJhQIkOiOa6PRrgiQhO+E6/+4O7oUtJEWFSYBbAPZ2pX/xn4vP4IPfT/Pzocu4OdozuV8wUyJa4uVS+wfLFkfSkiXEvfY6rmFhBH38UbmniO9ceZb9v17k7hd74te0bk8zvpCQqc84ieVAVApSQgtfN24N9WdEaABdghpUfcdiKeHcH/D7K3D5APi2hVtmQfvRVpl2rkSHAmq36PgLCJdSZgkhRgHvAfcA3YC7pJTWnVNXTmrT7JXKkH34MImfLyJ93TqEvT1eY8fiPXkSTi1su5CWTXaKzc/WvuZ2LoCGwTD2Y2jep3rjLIas/CxiMmI0QVIgRjKiiEmPIToj+rruN3thTxP3Jtd12wR5BBW2lLg6XOuGOhWXzvsbTrHmcCyezvY8HNGSSf1b4O5k223lK0PqqtVcfv55nNq0odlnnxY7oNiSzNRcvpm1kxZd/bh1SmipfmsjUkqOXk5jnT619WSc1sDbMdCT4R0CGN4xgDaN3K1XRqL+hN9fhgtbwaspDHoBOo8Hg/XyihIdCqjdoqNwhooQYjFwUkr5pn68X0rZ3RZ21XXRUUDexYskfvEFqT+uQObn4zF0KD4PTanWFSFLwpyTQ8wTT9pup9gL22Hlo5ByCfo+BoNfBIfaMRjTZDYRlxV3XcuIZbeN5VomoK2lcl3riEcQxtyGrPwzjy3Hs2no6sgjA1sxsU9zXB3rlvjI2LKF6MdnYO/fiGaLFuMYVPJ+LZu+Pcnx7Zf5+9xwvPzqxqwek1my72JyYYtGdHI2dgJ6BnszPDSAW0P9CWpo5enRccc04X1yNbj6woB/QY9JYG/98UBKdCigdouOv4C+QBZwHhgnpdyrux2TUnawhV31RXQUYExIIOmbb0j+dinmtDRce/bE56EpuA0YUCMvflNGBtGPTidr714C5sym4T33VHucxZKbDutmw74vwK893L4QmtT+cQCpuamFgsRSjESnRxObGXvdAFcnO2eEyYf0DC+c8WNAi3aM7diZlg2aEegeWCfWKsnaf4CoadOwc3bW9mtp0+YGPylxWXz78m46DghkwIQQG1hZfnKNJnacSeS3o7FsOB5HQkYejgY7+rfxZXioP0Pb++NTHQOCky/AH/8Hf/2P/2/vvuOjqtI/jn+eZNI7IYQQCB0UUQER0ZWf2Hvbqu6qa2Mt6+qCir1hV1j7uoqurmUta3ftBXUVUEBEEAEhtBQSIKSS/vz+uDcQQoCETObOTJ7363Vf0+5cnuOY5DvnnnsOMUlw0F+cNYs66RQjWOgwjmAOHecC1wJlQJGqHuM+PxK4L1wumQ0WDRWVbPrPK2x8+hnqCwuJGTyY9PPPI/m445CozvljVL9xI2sumED1kiX0uusuUk44vlP+nXZZ9jG89WeoLHa+9Y2b1KG5CbxU21BLXkXedr0kyzasIr8yD5XaLftGSAQ943tuc8qm+W1y9G5ertwJqpcsZc3559NYW0vOPx4jbsS24fCDJxaycuEGzpxyIPHJwTeItqKmnhlLinh/YSEzlhRTUVNPYoyPQ/fowdF7ZTJ+aI/OOwVWvs4ZSD33aWdRxDET4OC/Qnznr2hsocNAEIcOABHJBnrgrCrb6D6XBUSp6updvDcW+AKIAXzAf1T1ph3suz8wC/idqv5nZ8cN19DRROvqKHv3XeeKl2XL8GVlkf7Hs0n99a+JSPDfrIXbrRQ7frzfjt1hm0vg3avgh5chawSc+o/dnpsgWKkq7/+0lIe+mM3SjStJSSpjSHYNEr2RvIq1bKzeuM3+KTEp21xh0/wUTiDmJGmpds0aZ72W4mJ6P/ggieMOBqBoVRmv3DmH0cf144CTBgS0pp3ZUFHDx4vX8cGidfzPXUwtPSGaI4c5l7YeNDCdGF8nrgezuQS+ehBmP+bMuzHqLDjkqoAuD2Chw0CQh46OEOfcQIKqVohIFPA/nKteZrXYLxL4CKgGnurqoaOJqlL5xRdseGI6VXPmEJGSQtrpp9HtzDPxpad36NjNV4rt89jfid/fkxntd+3HN+Gdv0JNBRx+A4y92Pl2GEZUlS+WrWfah0v4fm0pOd3iuezwwRw5PJWCyhaDW92ekoKKgm0W7YuOiCYnOYf+Kf3pn9KfASkDGJAygH4p/Yjzdd54ivriYlZfMIGa5cvJvvsuko87jjfv/471ays4c8qBRMd5O2ZlbUkVHyxyVm2d4y6m1jstbsvU4/v1TfPbYmo7VFvlBI2v7ofqUhj+azj0Wkgf2Ln/bissdBgI49DRnIjE44SOi1R1dovXLgfqgP2Bdyx0bG/z/PlsePIpyj/+GImOJuXUU0g/5xyi+7Z/efDqn35i9fkXQEND6yvFBpuKInj7cmegXc5BcMoj0C14vkH7i6ryyeIipn20lB8LyhiQkcDlRwzhhL2ztrsUs76xnoLKgq1jScrXkluWS25pLmvK19DodEoC0CuhF/1TnSDSPJCkxfpnoq6GsjJnvZZ58+DSKXy6II2DfzOYfQ/v45fjt4eqsqyogg8WFvLBj4UszCsDYGhmEkcPd1ZtHZYVoEvm62th3jPOqZSKdTD4aCc499y78//tHbDQYSDMQ4fbizEXGAQ8oqqTW7yeDbwAHAY8yQ5Ch4hMACYA5OTk7Ldq1arOLj0o1azIZeM//0npG2+gDQ0kHXUU6eedR9zew9v0/qp581jzpwuJSEgg56kniRkQIn+8VeH7F+G9q5wp1Y+aAqPP9cvcBcGmsVH5YFEhf/t4KUvXVTA0M4m/HjmYo/fq2aY/lrUNtawqW0VuaS4rSlewonQFuaW5rCxdSXVD9Zb90mLStu0ZSXVCSVZCVrtP1TRu3szay//KjPIDaEjvxZlTjwjY0vWNjcr3azfxvrvGSa67mNqoZoup9QvAYmpbC2qAH/4Dn90Om1Y5QfnwGz25FLwlCx0GQiB0uNOgr1XVGhEZD+wD/EtVN7XjGKnA68Clqrqw2fOvAFNVdZaIPI31dLRJXVERJc8+R8mLL9JYXk78AQeQfv75JBz8ix3+Yar48n+svfRSojIzyXnqSaKyd3y5Y9AqXQtvXgIrZjizmJ70MKSEYDvaoKFReWdBPg98vIwV6yvZq1cyE48cwmF79Nitb+qN2khBZQErNq3YEkiabjfVbP1RjvPF0S+5H/1S+m3pFRmQMoCc5ByiI3c8KHTZN/l8+NRP7Ln4GfY6Zg96TJ7st/WGGhuVqroGKmvqKa+up6Kmng0VNcxYUsyHPxayrqwGX4Rw4MB059LWYZn0CPT6N6qw5D34dAoU/ej0aBx+Eww6ImjCsYUOA6EROuYDo4F+wAfAW8BQVT2unce5CahU1fuaPZeLs54LQHecy3MnqOobOzqOhY6tGioq2PTSy2x85hnqi4qI2WMP0s87j+Rjj9lmnYy2rBQbMlTh2+nw0Y0QEeWsRbHPb4PmF7u/1Tc08sb8fB78ZBmrN1Yxok8qE48cwrjB3f12mqCkumRLr8iKTSucUzWbcsmvzN+yT6RE0jup95aekea38ZEJ/PuW2UT6Ihgf8QmbnnuWlJNPotvNt1DZIFS4YaGyxgkMLR83BYlWH1fXU1FbT2u/JuOiIp3F1IZnctjQ3VxMzR9yv3Qm9lr7LXQbCIddB8NOhSBb5NFCh4HQCB3zVHWUiFwJVKvqQyLynaqO3MX7MoA6Vd0kInHAh8DdqvrODvZ/Guvp2C1aW0vp2++w4amnqF2+nKhevej2xz+S+utfUfbuu/5ZKTbYbFgOb1wMa2Y500Qf/zdIDJ4p5f2trqGR/8xdy0OfLCO/tJr9+6Ux8cihHDiwY4OKW2po1C3BYENlOctKVpBbupI15bnkV62iuHoNJXX5NLJ1IOvwwiM4OPdEPhvwNatj6zl+Vi6/nfcNszP35I4xZ1G7k0ueRSAxxkdSjI/EWB8JMT7ncaxzm9DstcSYKBJiIkmK9ZEUG8Xe2SnERnk4sDj/O2fK8uWfQlIvGD8ZRvw+aC/xttBhIDRCx2zgfuA64ERVzRWRhaq604EEIrIP8AwQCUQAL6vqrSJyIYCqPtZi/6ex0NEh2thIxYzP2TB9OpvnzSMiKYnG8nISxo2j9wP3+2el2GDS2AAzH3ZmdIxJhhPvdwJIGKupb+Clb9fw8Kc/U1Rew0ED05l01BD2zEp2woLbS7DltpWehYrqesprWn9cVdvQhioaiI3fRFz8BuJiNnLq0gMojynhzeEP0ijOuJEj5zVy3geNrOgbzxvnHEj37oPom9SfgakD6J/ah9S4WBJifMRHR4becvfFS+Gz25yrq+K6wbiJsP/5EBXcM69a6DAQGqFjGHAhMFNV/y0i/XHm07jLi3osdLRN1bx5bPzn00SmptDzhhv8u1JssFn3I7z+JyhcAPuc5ky2lJzlBJFQ+4PWRtV1DTw3axWPfb6c9RW1u34DEBkhJMX6SIje2pOQ2HQb08rj2K29Dlt6INzeBp+7iurc91cy640V/PKKUfQcmELx5uItp2nqPviM/R7/ioIekdzyG6U00fksoiKi6JvcN+CX+HbYpjXw+V0w/wWIiocDL4ED/wyxodF7aKHDQAiEjuZEJA3oo6oLvKrBQodpVUOdc3niF/eBut/Wo+IhMROSejpbYk9IyoSkrG2fj00N2XBSVVvPq/PyqKiuJzHWORXR6imKWB8xvgi/9ipUVzpL1/canMrxF+/T6j4VX37J2r9cRkT3dKrvm8yKhApnEOumXHLLdn6Jb/OxI/66xHe3VK6HL6c6Y4nA6dUYNwkSQmtslIUOAyEQOkRkBnASzqyi84Fi4HNVnehFPRY6zE6tXwb586GiEMrdrWIdlBc4U1C3WKANgMiY7cNIovs4KdMNK1nOVNUhGk46w9ev/sx3H6/mtOvHkJ694zVDqr77jjUXXkREdDR9npxO7JCt67E0XeLb/Gqatlzi2z+lP6kxqcRHxRPvi99y69f1a6pLnRWQZz4CdVUw4gw45GpIDfwcJP5gocNAaISO71R1pIicj9PLcZOILFDV1r/adDILHaZDaircEFK442BSUej8wWkpIqpFz0nLYOJu8d2D7soFf6soqea5G2cxaL8eHPHHXa/9WL10KWvOO5/Gmhr6/OMx4kfudBz6Npf4NgWR1i7xbckX4dsmhMT54rYGE/f5bZ5r7ZYI4n98h7hvpxNfVULcHicih90AGcG9eN2uWOgwEBqh4wfgKJxBodep6rcWOkzYq9vcehhpGVI2l2z/Xol0A0mLMNLyVE9CBkSG1vL2TT59djFLZhfy+1vGkpzetnEYtWvXsvq886gvKqb3gw+QOG7cbv3bG6s3sqpsFeW15VTVV7G5bjNV9VVU1VXt8HZz/fb7NF8BeGcE2S6oxPniWr2/s9u4qG3fExUR2KtcLHQYcE5ZBLtbcebn+MoNHAOAZR7XZEznioqDbv2dbWfqa7b2nLQWUkrXOPM3VK3f/r0S4QSPHY47ce8nZgbVZZgbCyr56esC9jm0T5sDB0B07970e/55Vp9/AWsuuphed99FyvHtX9m4W2w3usV2bFVWVaW6odoJIbWVVP30NpvnPEFVRQGbuw+maq9TqErt4wSUVoLM5rrNlNWWUVhZuM0+dY11ba4hOiK61R6Z5uFkm1tfPIf0OYSeCT071HbTtQV96FDVV4BXmj1eAfzKu4qMCSK+GEjNcbadqa+FyqJWekwKnefKC6Dge6gshmYDKx0C8ek7HxCb1t8Z2BiAMSez31qBLyaS/Y5r/9o/vu7d6fvsv1hz0UXkX3ElDaWldDvjjE6ocudEhLjIWOJWfEn6p7dC4Q/QYxic/E8Yeuxu/3esa6hzQkn95h32vLT2WvPnNlVs2u61JgNSB1joMB0S9KFDRIYAfwcyVXW4O//GSap6m8elGRM6fNGQ0tvZdqah3gkezcPINj0phc4lwhXrtl6l0yQ2FboPhu5DnNt09363/n7rKSnMLWXFd8WMObE/cYm7dxl2ZFISOdOnk/fXiay7dQoNJSV0v/jiwM7XsWqmM4vo6pmQ2hdOfRz2/nWHVzGOiowiJTKFlJgUPxXqjG+prq+mqr6KpOgkvx3XdE1BHzqAJ4ArgX8AqOoCEXkBsNBhjL9F+pw5RpKzdr5fYwNUbXDDSAFsXOFcubN+Kfz8Ccx/fuu+EukEj+5DIH2QG0rcYBLf9tMUqsqs15cTlxTV4VVkI2Jj6f3gAxRcfz3rH3qYhk2lZF5ztd/Wa9mhggXO+ijLPnR6iY67D0ad7YTCIBUhEc4plqgwm9zPeCIUQke8qn7T4ltI/Y52NsYEQEQkJPZwtqxWxnRXl8GGZW4QccPIhp/h54+hodlkYvHpbo9Isx6S7kOcb/8tBrmu/nEjeUs3Me53Q4iO7fivLomKIuvOO4lMTWXjM/+iYdMmet1xOxLVCeNXNix3Vn5d+CrEpsARN8OYCRAdwBVojQkCoRA61rsrzSqAiPwaKPC2JGPMTsUmQ/Z+ztZcY4Oz5Pr6n50g0hRGlr4P3z27db+IKOg2YEsI0fTBzHyjF8np0ew1rpffypSICHpcfTWRaWkU3/8AjWVlZN//NyLi/DQzaVk+fH43zHvWGX8zbhIc9BeIS/XP8Y0JMaFwyewA4HHgIKAEyAX+oKorvajHLpk1ppNsLtkaRjY06yHZuIKllQfyUelEjkyZxpDuS9xekWanatIHOYNpOzAmouTFFym85VbiRo2iz98f7djihFUb4X/T4JsnnKA1+hwYd4UzALeLsktmDYRA6GgiIglAhKq2MqVj4FjoMCawGmpqeOHm2UT7avnt0YuQDUu3BpLm85RExrhjRlqEke6DIaZtAyDL3nuPvKsmEzNgADnTn8CX0c6Vg2sqYNaj8PVDUFMO+54G46+GtH7tO04YstBhIAROr4hIDM4lsv0AX9PYDlW91cOyjDEB8uPMYspK6jnh0pHIXkds+2LlBrdXxD1Vs/5nKFwIi9/Z9uqapKyt40WajyFJzt5m9tbkY48lIimZtZdeysozfk/OU08S3acNg1bra2DOU87aO1XrYY8T4LDroceefvqvYEx4CPrQAbwJlAJzgRqPazHGBFBtdT3f/jeX7CGp5Axr5UqXhHRnyxm77fP1tVCSu20YWb8UFrwCNc2mmPfFbe0ZccNI4sDB9H38UVb/+XJWnnEGOdOnEzt0aOsFNjbA9y/CjDudidj6/x8cfhP0ti/0xrQmFEJHb1U9xusijDGB9/0na9hcXsfYiwa2bx4NXzRkDHW25lSdeUjWL932ypq8ubDwNdzx6sQB/Y7qzer3Ilh12m/oM+mXxB803gknSe7lxIvfgk9vh/VLoNdIOOkhGHioP5ptTNgKhdDxtYjsrao/eF2IMSZwNpfX8t1HqxkwIoOeA/w02ZXI1kt9+x287Wt11bBx+ZYwErN+KX2Tf2LNy+tYfee/6f2LR0nsVQPRiRDXDUpXQ/eh8NtnYc8TbQVgY9ogFELHwcAfRSQX5/SKAOrVgm/GmMCY+94q6msaOODkAYH5B6NiIXMvZ3NFA33/WMzq889lzVcr6HXB0aQMjYJNa5wBovue1uFZRI3pSkIhdBy7O28SkVjgCyAGp53/UdWbWuzze2Cy+7ACuEhVv+9ArcYYPyjbsJkfvljLHgdl0S3L2wm0fBkZ9H3uBdZedDH5/3ifhuuuo9sf7va0JmNCVSfP+bv7RKTpIvnyHWy7UgMcpqr7AiOAY0SkxWgzcoFD3F6TKTjzgRhjPPbt27mICGNO2MUquwESmZREn+lPkHjooay77TaKH36EUJluwJhgEsw9HS8AJ+BctaI4p1WaKLDTPld1fiNUuA+j3E1b7PN1s4ezgF2shmWM6Wwb8ir4aXYhI4/IITEt1utytti6XssNrH/4YSLi40k/9xyvyzImpARt6FDVE9zb3f6qIyKROKFlEPCIqs7eye7nAe/t4DgTgAkAOTm7WELcGNMhs95cQXSsj1HHtH/p+s4mPh9Zd9xOY2UFRdOmEb//aOL23tvrsowJGUF7eqU5EfmliEwTkakickpb36eqDao6AqcHY4yIDN/B8Q/FCR2TW3tdVR9X1dGqOjqjvTMUGmPaLP/nTaxcsJ5RR+cQm9AJC6/5gUREkDVlCr6MDPImTqKhomLXbzLGACEQOkTkUeBC4AdgIXChiDzSnmOo6iZgBrDdfB8isg8wHThZVTd0uGBjzG5pWro+PiWafQ7r2NL1nS0yNZXs++6lLi+PwptvsfEdxrRR0IcO4BDgaFX9p6r+EzgOGL+rN4lIhoikuvfjgCOAn1rskwO8Bpypqkv9Xbgxpu1W/bCBguWl7H98f6Kig/8y1Pj99iPj0j9T9s47lL7+htflGBMSQiF0LAGaD6ToAyxow/uygM9EZAHwLfCRqr4jIheKyIXuPjcC6cCjIjJfRGwlN2M80NiozHxjOSk94tjzF1lel9Nm6RMmED9mDIVTplCzYoXX5RgT9IJ+lVkR+RzYH/jGfWp/YCZQBaCqJwWyHltl1hj/+2lWAZ88vZijLxjOoP16eF1Ou9StW0fuyafg69mTfi+9SERMjNclBSVbZdZAEF+90syNXhdgjOk8DXWNfPNWLhk5SQwcGXoDtaMyM8m68w7WXnQxRffeR8/rr/O6JGOCVtCfXlHVz3FOsaQAycASVf28afO2OmNMRy38Io/yjdUceOpAJCI01y9JOvRQ0s46k5LnnqP800+9LseYoBX0oUNEzsc5tfJL4NfALBE519uqjDH+ULu5njnvraT3Hmn02bOVpetDSI8rriBm2J4UXHMtdYWFXpdjTFAK+tABXAmMVNU/qurZwH7sYD4NY0xo+e7j1VRX1HHgqQO9LqXDIqKjyZ46lca6OvKvvAptaPC6JGOCTiiEjrVsu9ZKObDGo1qMMX5SVVbL/I/XMGi/HvTom7zrN4SAmP796XnjDVR9+y3rH3vM63KMCTqhMJA0D5gtIm/irJ1yMvCNiEwEUNVpXhZnjNk9c95dSUNdIwecFKCl6wMk9ZRTqPz6a9Y/8igJY8YQv//+XpdkTNAIhZ6O5cAbbF2s7U2gAEhyN2NMiCkt3syiL/MY9ossUjPjvS7H73reeBNRfXqTd+VV1JeUeF2OMUEj6Hs6VPUWr2swxvjX7LdWEBEh7H98cCxd72+RiQlkT53GytNPp+D6G+j98EOIhOaVOcb4U9D3dLjTmd8rIu+KyKdNm9d1GWN2T/GacpZ9u459Du9DQmr4TqQVN3wvekycSMUnn1Dywgtel2NMUAj60AE8j7NmSn/gFmAlzrTmxpgQNOuNFcTE+xh1VM6udw5x3c4+i4T/G0fR3fdQ/dNPu36DMWEuFEJHuqo+CdS5E4KdC4z1uihjTPvlLS1h9aIN7HdMP2Lig3Ppen+SiAh63XknkSkp5E2cRGNVldclGeOpUAgdde5tgYgcLyIjgd5eFmSMaT9VZebry0lMi2Hv8dlelxMwvvR0et17D7W5uRTefrvX5RjjqVAIHbeJSAowCbgCmA781duSjDHtlTt/Petyy9j/hP74QmDpen9KGDuW9AkTKH31NUr/+1+vyzHGM6Fw9co77t1S4FAvazHG7J7GhkZmvbmctJ7x7DG2p9fleCLjz5dQNXs2hTfeRNw++xDdp4/XJRkTcEEbOkTkIbbOzbEdVf1LAMsxxnTAT7MKKSms4tg/7U1EZCh0sPqfREXR6777yD31VPImXUG/559DosJ/XIsxzQXzT/8cYK67ndTsftNmjAkB9bUNfPtOLpn9k+k/orvX5Xgqunc2WVOmUL1gAcUPPOB1OcYEXND2dKjqM033ReTy5o+NMaHjhxl5VJTUcMQ5w2yCLCD5mKOp/N3v2DD9SeLHHkjiwb/wuiRjAiaYezqa2+Fplh0RkVgR+UZEvheRRSKy3cym4nhQRH4WkQUiMso/5RpjAGqq6pj7/kpy9kone0ia1+UEjcxrriZm8CDyJ0+mvrjY63KMCZhQCR27owY4TFX3BUYAx4hIy/k9jgUGu9sE4O+BLdGY8Dbvw9XUVNUz9pTwWtStoyJiY8meNo3GigryJ1+NNjZ6XZIxARG0oUNEykWkTETKgH2a7jc9v6v3q6PCfRjlbi17TE4G/uXuOwtIFZEsvzbEmC6qclMNCz5Zw+D9M8noY2szthQzeDCZ11xD5ddfs/Gpp7wux5iACNrQoapJqprsbr5m95NUNbktxxCRSBGZDxQBH6nq7Ba7ZANrmj1e6z7X8jgTRGSOiMwptq5QY9rk2//m0tioYbd0vT+l/u63JB11FEX3P8Dm77/3uhxjOl3Qhg5/UNUGVR2BM4PpGBEZ3mKX1ka1bTd+RFUfV9XRqjo6IyOjM0o1JqxsWlfFj18VsNe4bFIy4rwuJ2iJCFlTbsXXI4O8SVfQUF7udUnGdKqwDh1NVHUTMAM4psVLa4HmM/T0BvIDVJYxYWv2WyuIjIpg9HH9vC4l6EWmpJB931TqCgoovOlmVNs9bt6YkBG2oUNEMkQk1b0fBxyBs1ptc28BZ7lXsYwFSlW1IMClGhNWilaV8fPcIkYc0Yf45GivywkJ8aNGknHppZS9+y6lr73mdTnGdJqgnafDD7KAZ0QkEidcvayq74jIhQCq+hjwLnAc8DNQBZzjVbHGhIuZry8nNjGKkUeE/9L1/pR+wflUzppF4ZTbiBsxgpiBA70uyRi/E+vKa5/Ro0frnDlzvC7DmKC0ZvFG3npgPgf/ZjD7Hm5ri7RX3boick85BV+PHvR7+SUiYmK8LslvRGSuqo72ug7jrbA9vWKMCSxtdJauT+oWy/D/6zpL1/tTVGYPet11JzVLllB09z1el2OM31noMMb4xfLviileXc6Yk/oTGWW/Wnbl/tVjAAAORElEQVRX4iGH0O3ssyl54QXKP/7Y63KM8Sv7zWCM6bAGd+n6br0SGDKmay5d708ZkyYSO2wY+dddT12BjW034cNChzGmwxZ/VUBp0WYOPGUgERG2qFtHRURHkz1tKtTVkXfllWh9vdclGeMXFjqMMR1SV9vAt//NJWtgCn33Tve6nLAR3a8fPW++ic1z5rL+UVsWyoSHcL5kNqjUbq6nvs4WdTLhZ+EXeVSV1nLMBcNt6Xo/SznpJCq/+pr1jz1G/NgDSBgzxuuSjOkQCx0B8tV/lvHjV3Zu1oSnfvt0J2tQqtdlhKWeN97A5vnzyb/yKvq/8Tq+tDSvSzJmt1noCJAhY3qSkWMrbZrwIxHCoNGZXpcRtiISEug1bSorTzudgmuvo/ejj1iPkglZFjoCJHtoGtlD7RuKMab94vbai8wrJrHuzrsoee55up35B69LMma32EBSY4wJAWlnnUXi+PEU3XMP1YsXe12OMbvFQocxxoQAESHrzjuITEsjb+IkGisrvS7JmHaz0GGMMSHCl5ZGr3vuoXblSgpvu93rcoxpNwsdxhgTQhLGHkD6hX+i9PXXKX37Ha/LMaZdLHQYY0yIybjkEuJGjaLw5pupXb3a63KMaTMLHcYYE2LE5yP73nsgMpK8iZPQ2lqvSzKmTSx0GGNMCIrKzibrtilUL1xI0f0PeF2OMW1iocMYY0JU8lFHkXr6aWx86ikqvvzS63KM2aWwDR0i0kdEPhORxSKySEQua2WfFBF5W0S+d/c5x4tajTFmd2VOnkzMkCHkT76auqIir8sxZqfCNnQA9cAkVd0TGAtcIiLDWuxzCfCjqu4LjAemikh0YMs0xpjdFxEbS/a0qTRWVVFw9dVooy0saYJX2IYOVS1Q1Xnu/XJgMZDdcjcgSZyFDBKBjThhxRhjQkbMoEFkXnsNlV/PZMP0J70ux5gdCtvQ0ZyI9ANGArNbvPQwsCeQD/wAXKaq231NEJEJIjJHROYUFxd3crXGGNN+qb/5DUnHHEPxAw+wef58r8sxplVhHzpEJBF4FbhcVctavHw0MB/oBYwAHhaR5JbHUNXHVXW0qo7OyMjo9JqNMaa9RISsW28hKjOTvElX0FDW8tedMd4L69AhIlE4geN5VX2tlV3OAV5Tx89ALrBHIGs0xhh/iUxOJnvaVOoKCym48SZU1euSjNlG2IYOd5zGk8BiVZ22g91WA4e7+2cCQ4EVganQGGP8L27ECDIuu4zy999n0yuveF2OMdvweV1AJ/oFcCbwg4g0neC8FsgBUNXHgCnA0yLyAyDAZFVd70WxxhjjL+nnn0fVrJmsu+NO4keNImbQIK9LMgYAse639hk9erTOmTPH6zKMMWan6oqKyD3lVHzp6fR75WUiYmM9rUdE5qrqaE+LMJ4L29MrxhjTlUX16EGvu++iZtky1t19t9flGANY6DDGmLCVOG4c3c45h03/fpGyDz/0uhxjLHQYY0w46/HXy4kdPpyC62+gLj/f63JMF2ehwxhjwphER5M99T5oaCDviivRept02XjHQocxxoS56L596XnzzWyeN4/iRx7xuhzThVnoMMaYLiDlxBNIOfVUNjz2DypntVwRwpjAsNBhjDFdRM/rryO6Xz/yr7qK+pISr8sxXZCFDmOM6SIiEhLInjaVhpISCq651qZJNwFnocMYY7qQ2D33pMeVV1IxYwYlzz7rdTmmi7HQYYwxXUzamX8g8dBDKbr3PjYvWuR1OaYLsdBhjDFdjIiQdcftRHbrRv7ESTRUVHpdkukiLHQYY0wX5EtLo9e991C7Zg3rpkzxuhzTRVjoMMaYLiphzBi6X3ghpW++Selbb3ldjukCLHQYY0wX1v3ii4gbvR+FN99C7cqVXpdjwpyFDmOM6cLE5yP73nshKoq8SVegtbVel2TCmIUOY4zp4qKysuh1+21UL1pE0bS/eV2OCWMWOowxxpB0xBGknXEGG59+morPP/e6HBOmwjZ0iEgfEflMRBaLyCIRuWwH+40XkfnuPvaTZozpsnpMvoqYoUPJv/oa6tYVeV2OCUNhGzqAemCSqu4JjAUuEZFhzXcQkVTgUeAkVd0L+E3gyzTGmOAQERND9rSpNFZXkz95MtrQ4HVJJsyEbehQ1QJVnefeLwcWA9ktdjsDeE1VV7v7WbQ3xnRpMQMH0vO6a6maNYsNT0z3uhwTZsI2dDQnIv2AkUDL9ZyHAGkiMkNE5orIWYGuzRhjgk3Kr35F8nHHUvzQQ1TN+87rckwYCfvQISKJwKvA5apa1uJlH7AfcDxwNHCDiAxp5RgTRGSOiMwpLi7u9JqNMcZLIkLPW24hKiuL/CuuoKGs5a9OY3ZPWIcOEYnCCRzPq+prreyyFnhfVStVdT3wBbBvy51U9XFVHa2qozMyMjq3aGOMCQKRSUlkT72PuqIiCq6/AVX1uiQTBsI2dIiIAE8Ci1V12g52exMYJyI+EYkHDsAZ+2GMMV1e3L770uPyyyj/8EM2vfSy1+WYMODzuoBO9AvgTOAHEZnvPnctkAOgqo+p6mIReR9YADQC01V1oSfVGmNMEOp27rlUzpzFujvvJG7USGKHbHcG2pg2C9vQoar/A6QN+90L3Nv5FRljTOiRiAh63X0X+VdNRnxh+yfDBIj9H2SMMWanfN27k/PUk16XYcJA2I7pMMYYY0xwsdBhjDHGmICw0GGMMcaYgLDQYYwxxpiAsNBhjDHGmICw0GGMMcaYgLDQYYwxxpiAsNBhjDHGmIAQW8SnfUSkGFi1m2/vDqz3YzmhwNrcNVibu4aOtLmvqtqKmV2chY4AEpE5qjra6zoCydrcNVibu4au2GbjX3Z6xRhjjDEBYaHDGGOMMQFhoSOwHve6AA9Ym7sGa3PX0BXbbPzIxnQYY4wxJiCsp8MYY4wxAWGhwxhjjDEBYaGjA0Skj4h8JiKLRWSRiFzmPt9NRD4SkWXubZr7fLq7f4WIPNziWDNEZImIzHe3Hl60aVf83OZoEXlcRJaKyE8i8isv2rQr/mqziCQ1+3zni8h6Ebnfq3btjJ8/59NF5AcRWSAi74tIdy/atCt+bvPv3PYuEpF7vGhPW+xGm48Ukbnu5zlXRA5rdqz93Od/FpEHRUS8apcJYqpq225uQBYwyr2fBCwFhgH3AFe7z18N3O3eTwAOBi4EHm5xrBnAaK/bFOA23wLc5t6PALp73b7ObnOL484F/s/r9nVmmwEfUNT02brvv9nr9nVym9OB1UCG+/gZ4HCv2+enNo8Eern3hwN5zY71DXAgIMB7wLFet8+24Nusp6MDVLVAVee598uBxUA2cDLOLxrc21PcfSpV9X9AtQfl+oWf23wucKe7X6OqBuXsjp3xOYvIYKAH8GUnlr7b/NhmcbcE95tvMpDf+S1oPz+2eQCwVFWL3ccfA0HZi7cbbf5OVZs+v0VArIjEiEgWkKyqM1VVgX81vceY5ix0+ImI9MP5FjAbyFTVAnB+qHH+uLTFP91u9xtCoWuyI20WkVT37hQRmScir4hIZieW6xd++pwBTgdecn9BB7WOtFlV64CLgB9wwsYw4MlOLNcvOvg5/wzsISL9RMSH88e3T+dV6x+70eZfAd+pag1OUFnb7LW17nPGbMNChx+ISCLwKnC5qpbt5mF+r6p7A+Pc7Ux/1dcZ/NBmH9Ab+EpVRwEzgfv8WKLf+elzbnIa8O+OV9W5OtpmEYnCCR0jgV7AAuAavxbpZx1ts6qW4LT5JZyerJVAvT9r9Lf2tllE9gLuBv7U9FQruwV9oDaBZ6Gjg9xfqq8Cz6vqa+7T69zuRtzbol0dR1Xz3Nty4AVgTOdU3HF+avMGoAp43X38CjCqE8r1C399zu6++wI+VZ3bKcX6iZ/aPAJAVZe7vTovAwd1Uskd5sef57dV9QBVPRBYAizrrJo7qr1tFpHeOD+3Z6nqcvfptThfIpr0JkhPoxlvWejoAPcUyJPAYlWd1uylt4Cz3ftnA2/u4ji+phH97i+AE4CF/q+44/zVZvcP0NvAePepw4Ef/Vqsn/irzc2cTpD3cvixzXnAMBFpWl30SJxxA0HHn5+zuFefuVd9XAxM92+1/tHeNrunRf8LXKOqXzXt7J6CKReRse4xz6LtPw+mK/F6JGsobzgj1xWny3i+ux2HM3r9E5xvN58A3Zq9ZyWwEajA+XYwDGcU/Fz3OIuAB4BIr9vXmW12n+8LfOEe6xMgx+v2dXab3ddWAHt43a4Afs4X4gSNBThBM93r9gWgzf/GCdE/Aqd53TZ/tRm4Hqhstu98oIf72micL0vLgYdxZ7y2zbbmm02DbowxxpiAsNMrxhhjjAkICx3GGGOMCQgLHcYYY4wJCAsdxhhjjAkICx3GGGOMCQgLHcYEOXH8T0SObfbcb0XkfS/rMsaY9rJLZo0JASIyHGfW1pFAJM78CMfo1hkh23OsSFVt8HOJxhizSxY6jAkRInIPzsRMCe5tX2BvnHVsblbVN91Fu5519wH4s6p+LSLjgZuAAmCEqg4LbPXGGGOhw5iQISIJwDygFngHWKSqz7lTU3+D0wuiQKOqVovIYODfqjraDR3/BYaraq43LTDGdHU+rwswxrSNqlaKyEs4U27/FjhRRK5wX44FcnAW2XpYREYADcCQZof4xgKHMcZLFjqMCS2N7ibAr1R1SfMXReRmYB2wL85A8epmL1cGqEZjjGmVXb1iTGj6ALjUXdETERnpPp8CFKhqI3AmzqBTY4wJChY6jAlNU4AoYIGILHQfAzwKnC0is3BOrVjvhjEmaNhAUmOMMcYEhPV0GGOMMSYgLHQYY4wxJiAsdBhjjDEmICx0GGOMMSYgLHQYY4wxJiAsdBhjjDEmICx0GGOMMSYg/h/haavk8MzNlwAAAABJRU5ErkJggg==
"
>
</div>

</div>

</div>
</div>

</div>
<div class="cell border-box-sizing text_cell rendered"><div class="prompt input_prompt">
</div><div class="inner_cell">
<div class="text_cell_render border-box-sizing rendered_html">
<p>From inspecting these plots, we can see that happiness score indeed fluctuates within these groups of countries, to the point where the the ranking between them changes. We would like to dive deeper into what can cause these changes over time by looking at the attributes for each country provided in our data sets, which also fluctate, sometimes dramatically, over the course of our time interval.</p>

</div>
</div>
</div>
<div class="cell border-box-sizing text_cell rendered"><div class="prompt input_prompt">
</div><div class="inner_cell">
<div class="text_cell_render border-box-sizing rendered_html">
<h2 id="Looking-for-Consistent-Factors">Looking for Consistent Factors<a class="anchor-link" href="#Looking-for-Consistent-Factors">&#182;</a></h2>
</div>
</div>
</div>
<div class="cell border-box-sizing text_cell rendered"><div class="prompt input_prompt">
</div><div class="inner_cell">
<div class="text_cell_render border-box-sizing rendered_html">
<p>Now to take a closer look at the different factors that could affect this happiness rating for each country, we will inspect the following variables: GDP, Life Expectancy, Freedom, Trust, and Generosity. This way, for each country we can look at how these attributes fluctuate over our time interval. For the same group of countries, this time representing the top 5 and bottom 5 on the same plots, we plot each variable over time for these countries. Pay close attention firstly to how these attributes fluctuate and change over time, as well as which ones seem to stay consistent for some span of years, and also how the values and changes differ between the more happy and less happy groups of countries.</p>

</div>
</div>
</div>
<div class="cell border-box-sizing code_cell rendered">
<div class="input">
<div class="prompt input_prompt">In&nbsp;[97]:</div>
<div class="inner_cell">
    <div class="input_area">
<div class=" highlight hl-ipython3"><pre><span></span><span class="n">yearly_df1</span> <span class="o">=</span> <span class="n">yearly_df</span><span class="p">[[</span><span class="s1">&#39;Country&#39;</span><span class="p">,</span><span class="s1">&#39;Year&#39;</span><span class="p">,</span><span class="s1">&#39;Happiness Score&#39;</span><span class="p">,</span><span class="s1">&#39;GDP&#39;</span><span class="p">,</span><span class="s1">&#39;Life Expectancy&#39;</span><span class="p">,</span><span class="s1">&#39;Freedom&#39;</span><span class="p">,</span><span class="s1">&#39;Trust&#39;</span><span class="p">,</span><span class="s1">&#39;Generosity&#39;</span><span class="p">]]</span>
<span class="n">top5_factors</span> <span class="o">=</span> <span class="n">yearly_df1</span><span class="p">[</span><span class="n">yearly_df1</span><span class="p">[</span><span class="s1">&#39;Country&#39;</span><span class="p">]</span><span class="o">.</span><span class="n">isin</span><span class="p">([</span><span class="s1">&#39;Iceland&#39;</span><span class="p">])]</span>
<span class="n">top5_factors</span>
</pre></div>

    </div>
</div>
</div>

<div class="output_wrapper">
<div class="output">


<div class="output_area">

    <div class="prompt output_prompt">Out[97]:</div>



<div class="output_html rendered_html output_subarea output_execute_result">
<div>
<style scoped>
    .dataframe tbody tr th:only-of-type {
        vertical-align: middle;
    }

    .dataframe tbody tr th {
        vertical-align: top;
    }

    .dataframe thead th {
        text-align: right;
    }
</style>
<table border="1" class="dataframe">
  <thead>
    <tr style="text-align: right;">
      <th></th>
      <th>Country</th>
      <th>Year</th>
      <th>Happiness Score</th>
      <th>GDP</th>
      <th>Life Expectancy</th>
      <th>Freedom</th>
      <th>Trust</th>
      <th>Generosity</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <th>1</th>
      <td>Iceland</td>
      <td>2015</td>
      <td>7.5610</td>
      <td>1.302320</td>
      <td>0.947840</td>
      <td>0.628770</td>
      <td>0.141450</td>
      <td>0.436300</td>
    </tr>
    <tr>
      <th>2</th>
      <td>Iceland</td>
      <td>2016</td>
      <td>7.5010</td>
      <td>1.426660</td>
      <td>0.867330</td>
      <td>0.566240</td>
      <td>0.149750</td>
      <td>0.476780</td>
    </tr>
    <tr>
      <th>2</th>
      <td>Iceland</td>
      <td>2017</td>
      <td>7.5040</td>
      <td>1.480633</td>
      <td>0.833552</td>
      <td>0.627163</td>
      <td>0.153527</td>
      <td>0.475540</td>
    </tr>
    <tr>
      <th>3</th>
      <td>Iceland</td>
      <td>2018</td>
      <td>7.4950</td>
      <td>1.343000</td>
      <td>0.914000</td>
      <td>0.677000</td>
      <td>0.138000</td>
      <td>0.353000</td>
    </tr>
    <tr>
      <th>3</th>
      <td>Iceland</td>
      <td>2019</td>
      <td>7.4940</td>
      <td>1.380000</td>
      <td>1.026000</td>
      <td>0.591000</td>
      <td>0.118000</td>
      <td>0.354000</td>
    </tr>
    <tr>
      <th>3</th>
      <td>Iceland</td>
      <td>2020</td>
      <td>7.5045</td>
      <td>10.772559</td>
      <td>73.000000</td>
      <td>0.948892</td>
      <td>0.711710</td>
      <td>0.246944</td>
    </tr>
  </tbody>
</table>
</div>
</div>

</div>

</div>
</div>

</div>
<div class="cell border-box-sizing text_cell rendered"><div class="prompt input_prompt">
</div><div class="inner_cell">
<div class="text_cell_render border-box-sizing rendered_html">
<p>We construct plots for each of the 5 variables we've mentioned over time for the 5 highest and lowest countries that we've been using as our sample.</p>

</div>
</div>
</div>
<div class="cell border-box-sizing code_cell rendered">
<div class="input">
<div class="prompt input_prompt">In&nbsp;[98]:</div>
<div class="inner_cell">
    <div class="input_area">
<div class=" highlight hl-ipython3"><pre><span></span><span class="n">top5</span><span class="o">.</span><span class="n">extend</span><span class="p">(</span><span class="n">bottom5</span><span class="p">)</span>
<span class="n">countries</span> <span class="o">=</span> <span class="n">top5</span>
<span class="n">gdp</span> <span class="o">=</span> <span class="n">yearly_df</span><span class="o">.</span><span class="n">pivot</span><span class="p">(</span><span class="n">index</span><span class="o">=</span><span class="s2">&quot;Year&quot;</span><span class="p">,</span> <span class="n">columns</span><span class="o">=</span><span class="s2">&quot;Country&quot;</span><span class="p">,</span><span class="n">values</span><span class="o">=</span><span class="s2">&quot;GDP&quot;</span><span class="p">)</span>
<span class="k">for</span> <span class="n">country</span> <span class="ow">in</span> <span class="n">countries</span><span class="p">:</span>
    <span class="n">plt</span><span class="o">.</span><span class="n">plot</span><span class="p">(</span><span class="n">gdp</span><span class="p">[</span><span class="n">country</span><span class="p">],</span> <span class="n">label</span><span class="o">=</span><span class="n">country</span><span class="p">)</span>
    <span class="n">plt</span><span class="o">.</span><span class="n">legend</span><span class="p">(</span><span class="n">country</span><span class="p">)</span>

<span class="n">yMax</span> <span class="o">=</span> <span class="n">plt</span><span class="o">.</span><span class="n">ylim</span><span class="p">()[</span><span class="mi">1</span><span class="p">]</span>
<span class="n">plt</span><span class="o">.</span><span class="n">title</span><span class="p">(</span><span class="s2">&quot;Distribution of GDP Across Countries Over Time&quot;</span><span class="p">)</span>
<span class="n">plt</span><span class="o">.</span><span class="n">xlabel</span><span class="p">(</span><span class="s2">&quot;Year&quot;</span><span class="p">)</span>
<span class="n">plt</span><span class="o">.</span><span class="n">ylabel</span><span class="p">(</span><span class="s2">&quot;GDP per Capita&quot;</span><span class="p">)</span>
<span class="n">plt</span><span class="o">.</span><span class="n">legend</span><span class="p">(</span><span class="n">bbox_to_anchor</span><span class="o">=</span><span class="p">(</span><span class="mf">0.03</span><span class="p">,</span><span class="mf">0.95</span><span class="p">),</span> <span class="n">loc</span><span class="o">=</span><span class="mi">2</span><span class="p">,</span> <span class="n">ncol</span><span class="o">=</span><span class="mi">5</span><span class="p">)</span>
<span class="n">plt</span><span class="o">.</span><span class="n">show</span><span class="p">()</span>
</pre></div>

    </div>
</div>
</div>

<div class="output_wrapper">
<div class="output">


<div class="output_area">

    <div class="prompt"></div>




<div class="output_png output_subarea ">
<img src="data:image/png;base64,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1/PEE08wfPhwBg8eXLsf3377ba644gouvfRS4uPjefnll3n22WcZPHgwo0aNqp0Ntalp1puaQr29OUpLweHA6mmc2JaZPfD3cs9V6YEDBzoyMjI8Aa6//vqYxYsXBwJccMEFvX/zm9/EATz33HOhd955ZyS0fWr0/fv3ew4aNCgpNTW13x/+8IfImvJNTft9tisuLjYHBgbawJhf5bzzzutTs2zWrFkxL774YneAqKio/n/84x8jhg4d2nfhwoXBI0aM6Lt27VpfgKysLEtUVFR/MFoiLrzwwt7jx4//VWxsbOqtt95am7S88MIL3ekPMDsAACAASURBVOPi4lKHDx/ed/369bXNznWnq+8onXYcC7dY9SBk73JtneH9YVrb+qAmJCTgcDjIzc1l5cqVBAYG8uOPP1JVVcXYsWO58MILgeanU4+OjmbDhg3cfffdzJ49m++//57KykpSUlK49dZb8fb2Zvny5XTr1o38/HxGjRpVO+33gQMHeOutt/jnP/9ZG1NOTg6XXXYZjz/+eO1sna6S/fe/U7XPtdOme/VLIvyhh1osd/vttzNgwADuv//+eo/PnTuXWbNm8dvf/paFCxdy5513smLFCgAOHjzI6tWrMZvN3HrrrXz//ffExsaSkJDAunXrmDVrFhs3buTVV1/FZDLx5Zdf4u3tzaFDh7juuuvYvHkzN910E8899xyXX345xcXFrF+/nnfeecel+8DV1ry9gNyjR1xaZ4/YBM6bfXOL5ebNm8eQIUPw9PTkkksu4fzzz2fhwoUUFRUxYsQIpkyZAhizmG7bto3Kykr69OnD008/zbZt27j77rt59913ueuuu5qdZr2xKdTdZdWqVWRnZ5/yuK6qwmG34TB7ARptMeNpbt05Xnh4ONOmTWtVWbvdzqZNm8y33HJLEcCECRNK1q5dGzBz5szi7Oxsz9zcXA3w/fff+1933XUnoO1To8+ZMyfmpptuyps7d27Bk08+Wdsy0tS03zWTlbnDXfuORe8vq3TptOlJft7lz/eLaXZys6qqKlNSUlJyVVWVys/P9/j8889PmfCrMd7e3o4tW7YcAHjjjTeaHCxy7969vjt27Njr4+Pj6NOnT+of//jHHA8PD5566qnILVu27AsJCbGPGTOmb2pqannbnp37nFuJRSdS0/rw3//+l507d9aePRUXF3Po0CE8PT2b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
"
>
</div>

</div>

</div>
</div>

</div>
<div class="cell border-box-sizing code_cell rendered">
<div class="input">
<div class="prompt input_prompt">In&nbsp;[99]:</div>
<div class="inner_cell">
    <div class="input_area">
<div class=" highlight hl-ipython3"><pre><span></span><span class="n">life</span> <span class="o">=</span> <span class="n">yearly_df</span><span class="o">.</span><span class="n">pivot</span><span class="p">(</span><span class="n">index</span><span class="o">=</span><span class="s2">&quot;Year&quot;</span><span class="p">,</span> <span class="n">columns</span><span class="o">=</span><span class="s2">&quot;Country&quot;</span><span class="p">,</span><span class="n">values</span><span class="o">=</span><span class="s2">&quot;Life Expectancy&quot;</span><span class="p">)</span>
<span class="k">for</span> <span class="n">country</span> <span class="ow">in</span> <span class="n">countries</span><span class="p">:</span>
    <span class="n">plt</span><span class="o">.</span><span class="n">plot</span><span class="p">(</span><span class="n">life</span><span class="p">[</span><span class="n">country</span><span class="p">],</span> <span class="n">label</span><span class="o">=</span><span class="n">country</span><span class="p">)</span>
    <span class="n">plt</span><span class="o">.</span><span class="n">legend</span><span class="p">(</span><span class="n">country</span><span class="p">)</span>

<span class="n">yMax</span> <span class="o">=</span> <span class="n">plt</span><span class="o">.</span><span class="n">ylim</span><span class="p">()[</span><span class="mi">1</span><span class="p">]</span>
<span class="n">plt</span><span class="o">.</span><span class="n">title</span><span class="p">(</span><span class="s2">&quot;Distribution of Life Expectancy Across Countries Over Time&quot;</span><span class="p">)</span>
<span class="n">plt</span><span class="o">.</span><span class="n">xlabel</span><span class="p">(</span><span class="s2">&quot;Year&quot;</span><span class="p">)</span>
<span class="n">plt</span><span class="o">.</span><span class="n">ylabel</span><span class="p">(</span><span class="s2">&quot;Life Expectancy&quot;</span><span class="p">)</span>
<span class="n">plt</span><span class="o">.</span><span class="n">legend</span><span class="p">(</span><span class="n">bbox_to_anchor</span><span class="o">=</span><span class="p">(</span><span class="mf">0.03</span><span class="p">,</span><span class="mf">0.95</span><span class="p">),</span> <span class="n">loc</span><span class="o">=</span><span class="mi">2</span><span class="p">,</span> <span class="n">ncol</span><span class="o">=</span><span class="mi">5</span><span class="p">)</span>
<span class="n">plt</span><span class="o">.</span><span class="n">show</span><span class="p">()</span>
</pre></div>

    </div>
</div>
</div>

<div class="output_wrapper">
<div class="output">


<div class="output_area">

    <div class="prompt"></div>




<div class="output_png output_subarea ">
<img src="data:image/png;base64,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35x6nz59+PHHH7n33nuZPXs2P/zwA5WVlSQkJHDbbbfh5+fH0qVL6dSpE/n5+YwcObK22e/du3fz9ttv88orr9TGlJOTw8UXX8wTTzxR21qnq2T/4x9U7XRts+m+cbH0fPjhFoe74447SE5O5oEHHqjX/c4772TWrFnceOONLFiwgLvvvptPPvkEgD179rBixQqsViu33XYbP/zwA/369SM6Opq1a9cya9Ys1q9fz6uvvorFYmH58uX4+fmxd+9err32WjZu3MjNN9/M888/zyWXXEJRURHr1q3j3Xffdek6cLWV78wn9+B+l04zrF80k2bf0uJwc+fOZfDgwfj4+HDhhRdy7rnnsmDBAgoLCxk+fDhTpkwBjFZM09LSqKysZMCAATz99NOkpaVx77338t5773HPPfc028x6Y02ou8uyZcvIzs5utJ/daUdXOwErWOx4+7SufkXPnj2ZMWNGq4Z1OBxs2LDBeuuttxYCjB8/vmTNmjXB1113XVF2drZPbm6uBvjhhx+Crr322mPQ9qbR58yZ0/fmm2/Ou/POOwv++c9/1paMNNXst8WNL/+6Z+ehPrvKKl3abHpsoF/5vLi+zTZuVlVVZYmNjY2vqqpS+fn53l999dVJDX41xs/Pz7lp06bdAG+++WZYU8Pt2LEjICMjY4e/v79zwIABiX/84x9zvL29eeqppyI2bdq0MzQ01DF69OiBiYmJ5W1bOvf5bSUWHUhN6cM333zDli1baq+eioqK2Lt3Lz4+Ps02p16TJCQlJVFaWkpwcDDBwcH4+flRWFhIYGAgDz/8MGvWrMFisXD06NHaJqP79evHyJEja2Ox2WxMnjyZl19++axrh6JTp07MmjWLF198sbbxMIAff/yxtln5G264oV7icdVVV2G1Grelx40bx5o1a+jXrx+333478+fP5+jRo4SGhhIUFERRURF33nkn6enpWK1W9uwxjikTJkzgjjvuIDc3l48//pgrrrgCLy/Z3ZoSGBjINddcQ1BQEEuWLOHzzz+vbXG2srKytkRp0qRJtdt6SEgIF110EWDsB1u2bGmxmfXGmlD3BIfTgQUrCgfa4trtoqKiovZ4ERMToy699NJigKlTp5a+/PLLPTZt2uQXExNTUVhYaD148KD3pk2bAt94441D0Pam0Tdv3hy0bNmyfQC33nprwd///vfe0HSz3337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
"
>
</div>

</div>

</div>
</div>

</div>
<div class="cell border-box-sizing code_cell rendered">
<div class="input">
<div class="prompt input_prompt">In&nbsp;[100]:</div>
<div class="inner_cell">
    <div class="input_area">
<div class=" highlight hl-ipython3"><pre><span></span><span class="n">freedom</span> <span class="o">=</span> <span class="n">yearly_df</span><span class="o">.</span><span class="n">pivot</span><span class="p">(</span><span class="n">index</span><span class="o">=</span><span class="s2">&quot;Year&quot;</span><span class="p">,</span> <span class="n">columns</span><span class="o">=</span><span class="s2">&quot;Country&quot;</span><span class="p">,</span><span class="n">values</span><span class="o">=</span><span class="s2">&quot;Freedom&quot;</span><span class="p">)</span>
<span class="k">for</span> <span class="n">country</span> <span class="ow">in</span> <span class="n">countries</span><span class="p">:</span>
    <span class="n">plt</span><span class="o">.</span><span class="n">plot</span><span class="p">(</span><span class="n">freedom</span><span class="p">[</span><span class="n">country</span><span class="p">],</span> <span class="n">label</span><span class="o">=</span><span class="n">country</span><span class="p">)</span>
    <span class="n">plt</span><span class="o">.</span><span class="n">legend</span><span class="p">(</span><span class="n">country</span><span class="p">)</span>

<span class="n">yMax</span> <span class="o">=</span> <span class="n">plt</span><span class="o">.</span><span class="n">ylim</span><span class="p">()[</span><span class="mi">1</span><span class="p">]</span>
<span class="n">plt</span><span class="o">.</span><span class="n">title</span><span class="p">(</span><span class="s2">&quot;Distribution of Freedom Across Countries Over Time&quot;</span><span class="p">)</span>
<span class="n">plt</span><span class="o">.</span><span class="n">xlabel</span><span class="p">(</span><span class="s2">&quot;Year&quot;</span><span class="p">)</span>
<span class="n">plt</span><span class="o">.</span><span class="n">ylabel</span><span class="p">(</span><span class="s2">&quot;Freedom Rating&quot;</span><span class="p">)</span>
<span class="n">plt</span><span class="o">.</span><span class="n">legend</span><span class="p">(</span><span class="n">bbox_to_anchor</span><span class="o">=</span><span class="p">(</span><span class="mf">0.03</span><span class="p">,</span><span class="mf">0.95</span><span class="p">),</span> <span class="n">loc</span><span class="o">=</span><span class="mi">2</span><span class="p">,</span> <span class="n">ncol</span><span class="o">=</span><span class="mi">5</span><span class="p">)</span>
<span class="n">plt</span><span class="o">.</span><span class="n">show</span><span class="p">()</span>
</pre></div>

    </div>
</div>
</div>

<div class="output_wrapper">
<div class="output">


<div class="output_area">

    <div class="prompt"></div>




<div class="output_png output_subarea ">
<img src="data:image/png;base64,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no0bNxISol1TJ0/WZnJNnTqVMWPGYLPZWLBgAZ999hmhoaH885//5M9//jOrVq0CoLS0lO+++w7QXP213Hjjjdx5550APPLII7z55pssWLAA0ATS//73P44cOcLkyZOZMmUKn3zyCUePHmX//v3k5+eTmJjI7373u1/Ziw3Z8v4xTJkVbVpnSFcfUqfGn1PZr7/+mk8//ZTt27fj5eVFcXExAHfddRcrVqzgsssuY/v27cybN49vv/22wbadsT8BSr84QU1OpfZFOnFWV+PUGZHiFHqjjhKdDqd0YHFY8BN6DHo7efZcnE4nBoMBs+6Xw51ukd4ETOrRIjtmzJhR8sADD5gAFi5cGLl8+fKQP//5zwUA+fn5xh07dhzZs2ePxw033NBz9uzZJa6n45yioiL98OHDe917770FAGvXrk0PDw93VFRUiAEDBiTedtttJREREY7q6mrd8OHDK1588cXsuXPnRr/44ouhzz33XO652tAWHDq8uGtlxbFf53pshLdPfFVi72czz1Rm7dq1AWPHjjX37dvXGhAQ4HA6neJPf/pTzo4dO7xXr16dkZ6eblyyZEmXXbt2HQoICHCOGDEiPikpqbp2+6b638vLy/nVV18dDwoKcubm5hqGDh2acOutt5YCZGRkeLz77rsnR4wYceo3v/lN99WrVwfOmzevuF59+vXr1weePHnygE6nw2Qy6UNCQhzjx48vvfbaa82zZ88uAQgODra35Jxoad9dskKjo2hq6KQ+Q4YMITo6GqAuhqOx0Hj//fdZuXIldrud3NxcDh06VCc0ap/QBw4cyMcffwzA5s2b6/6/5pprCAxsk2HACwofHx927tzJli1b2LhxI7fccgvPPPMMPXv25PDhw/z444/cf//9bN68GYfDQWpq6jnV+9xzz+Hp6ck999zDgQMHOHDgAFdeeSUADoeDLl1Ov/PglltuabKOAwcO8Mgjj1BaWkpFRQUTJ06sW3f99dej0+lITEwkP1/zeG/evJnp06ej1+uJjIzkiiuuaG23dFo2bNjA7Nmz64apgoKCqKioYOvWrdx888115axW6y+27fT9KSVOiwWnMCCFDp1eoNPpkDixOqwIBO56dxwOB06nE71ej66VL+lqip07d3o++uijUeXl5frKykr9mDFjzLXrJk+eXKrX6xk4cKClqKjIWLvc6XQyZcqUuHvu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
"
>
</div>

</div>

</div>
</div>

</div>
<div class="cell border-box-sizing code_cell rendered">
<div class="input">
<div class="prompt input_prompt">In&nbsp;[101]:</div>
<div class="inner_cell">
    <div class="input_area">
<div class=" highlight hl-ipython3"><pre><span></span><span class="n">trust</span> <span class="o">=</span> <span class="n">yearly_df</span><span class="o">.</span><span class="n">pivot</span><span class="p">(</span><span class="n">index</span><span class="o">=</span><span class="s2">&quot;Year&quot;</span><span class="p">,</span> <span class="n">columns</span><span class="o">=</span><span class="s2">&quot;Country&quot;</span><span class="p">,</span><span class="n">values</span><span class="o">=</span><span class="s2">&quot;Trust&quot;</span><span class="p">)</span>
<span class="k">for</span> <span class="n">country</span> <span class="ow">in</span> <span class="n">countries</span><span class="p">:</span>
    <span class="n">plt</span><span class="o">.</span><span class="n">plot</span><span class="p">(</span><span class="n">trust</span><span class="p">[</span><span class="n">country</span><span class="p">],</span> <span class="n">label</span><span class="o">=</span><span class="n">country</span><span class="p">)</span>
    <span class="n">plt</span><span class="o">.</span><span class="n">legend</span><span class="p">(</span><span class="n">country</span><span class="p">)</span>

<span class="n">yMax</span> <span class="o">=</span> <span class="n">plt</span><span class="o">.</span><span class="n">ylim</span><span class="p">()[</span><span class="mi">1</span><span class="p">]</span>
<span class="n">plt</span><span class="o">.</span><span class="n">title</span><span class="p">(</span><span class="s2">&quot;Distribution of Trust Across Countries Over Time&quot;</span><span class="p">)</span>
<span class="n">plt</span><span class="o">.</span><span class="n">xlabel</span><span class="p">(</span><span class="s2">&quot;Year&quot;</span><span class="p">)</span>
<span class="n">plt</span><span class="o">.</span><span class="n">ylabel</span><span class="p">(</span><span class="s2">&quot;Trust Rating&quot;</span><span class="p">)</span>
<span class="n">plt</span><span class="o">.</span><span class="n">legend</span><span class="p">(</span><span class="n">bbox_to_anchor</span><span class="o">=</span><span class="p">(</span><span class="mf">0.03</span><span class="p">,</span><span class="mf">0.95</span><span class="p">),</span> <span class="n">loc</span><span class="o">=</span><span class="mi">2</span><span class="p">,</span> <span class="n">ncol</span><span class="o">=</span><span class="mi">5</span><span class="p">)</span>
<span class="n">plt</span><span class="o">.</span><span class="n">show</span><span class="p">()</span>
</pre></div>

    </div>
</div>
</div>

<div class="output_wrapper">
<div class="output">


<div class="output_area">

    <div class="prompt"></div>




<div class="output_png output_subarea ">
<img src="data:image/png;base64,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myPAiDplXgY+B44BocB0rXW9n9VKqRuAG4DWu3z2N/dCzubWqatGt/5w3lMt2qVPnz44HA5yc3P57LPPCA8P5+eff6aqqooxY8YwdepUoPH08b169WLVqlXccccdzJo1ix9++IHKykrS09OZPXs2AQEBfPLJJ4SFhWGxWBg5cqQrxfnOnTt5++23efXVV11tOn78OBdddBGPP/64KxNpa8n561+p2t66aeL9U1Podt99TZa75ZZbyMzM5O677661fs6cOcycOZPf/va3zJ8/n9tuu41PP/0UgF27dpGVlYXZbGb27Nn88MMPxMfH08bglkYAACAASURBVKdPH77//ntmzpzJ6tWree211zCZTCxZsoSAgAB2797N1VdfzZo1a7j++ut5/vnnufjiiykuLmblypW8++67rXoMWtvSd+aRe3Bfq9YZG9+HSbNuaLLcww8/zODBg/Hz8+OCCy7g7LPPZv78+RQVFTF8+HCmTJkCGFla169fT2VlJUlJSTz99NOsX7+eO+64g/fee4/bb7+90bTynlLGe9M333xDTo7nlO92exlK+WIyrfS4XWuNtaoSs48vZp+TH9vdunXjvPPOa9b92+12li5dGvr73//eAjB+/PiSFStWhF5zzTXFOTk5frm5uRrghx9+CLn66qsLoOWp4G+++ebe119/fd6cOXPyn3zySVfPSUOpzmuSr7W227cf6rWjrLJV08SnBAeUv5Dau9FkbVVVVaaUlJS0qqoqZbFYfL/++ut6Ccw8CQgIcKxdu3YnwJtvvhnbULlt27YFbdy4cVtgYKAjKSkp449//ONxX19fnnrqqbi1a9duj4yMtI8ePbpfRkZGecsenXd5M9DwlA6x7vXOpwEbgLOBvsASpdT3WusTtXbSeh4wD4xLkHuhre2qpndi8eLFbNq0yfXrqri4mN27d+Pn59do+viaoKF///6UlpYSGhpKaGgoAQEBFBUVERwczH333ceKFSswmUwcPXrUlSI7Pj6ekSNHutpitVqZPHkyr7zySrvnfGhtYWFhzJw5k7lz57oSoQGsWrWKjz/+GDB6H9wDkSuvvBKz2RjSHjduHCtWrCA+Pp6bbrqJefPmcfToUSIjIwkJCaG4uJg5c+awYcMGzGYzu3YZnzETJkzglltuITc3l48//pjLL78cHx+5Vl5DgoODmT59OiEhIXzwwQd8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
"
>
</div>

</div>

</div>
</div>

</div>
<div class="cell border-box-sizing code_cell rendered">
<div class="input">
<div class="prompt input_prompt">In&nbsp;[102]:</div>
<div class="inner_cell">
    <div class="input_area">
<div class=" highlight hl-ipython3"><pre><span></span><span class="n">generosity</span> <span class="o">=</span> <span class="n">yearly_df</span><span class="o">.</span><span class="n">pivot</span><span class="p">(</span><span class="n">index</span><span class="o">=</span><span class="s2">&quot;Year&quot;</span><span class="p">,</span> <span class="n">columns</span><span class="o">=</span><span class="s2">&quot;Country&quot;</span><span class="p">,</span><span class="n">values</span><span class="o">=</span><span class="s2">&quot;Generosity&quot;</span><span class="p">)</span>
<span class="k">for</span> <span class="n">country</span> <span class="ow">in</span> <span class="n">countries</span><span class="p">:</span>
    <span class="n">plt</span><span class="o">.</span><span class="n">plot</span><span class="p">(</span><span class="n">generosity</span><span class="p">[</span><span class="n">country</span><span class="p">],</span> <span class="n">label</span><span class="o">=</span><span class="n">country</span><span class="p">)</span>
    <span class="n">plt</span><span class="o">.</span><span class="n">legend</span><span class="p">(</span><span class="n">country</span><span class="p">)</span>

<span class="n">yMax</span> <span class="o">=</span> <span class="n">plt</span><span class="o">.</span><span class="n">ylim</span><span class="p">()[</span><span class="mi">1</span><span class="p">]</span>
<span class="n">plt</span><span class="o">.</span><span class="n">title</span><span class="p">(</span><span class="s2">&quot;Distribution of Generosity Across Countries Over Time&quot;</span><span class="p">)</span>
<span class="n">plt</span><span class="o">.</span><span class="n">xlabel</span><span class="p">(</span><span class="s2">&quot;Year&quot;</span><span class="p">)</span>
<span class="n">plt</span><span class="o">.</span><span class="n">ylabel</span><span class="p">(</span><span class="s2">&quot;Generosity Rating&quot;</span><span class="p">)</span>
<span class="n">plt</span><span class="o">.</span><span class="n">legend</span><span class="p">(</span><span class="n">bbox_to_anchor</span><span class="o">=</span><span class="p">(</span><span class="mf">0.03</span><span class="p">,</span><span class="mf">0.95</span><span class="p">),</span> <span class="n">loc</span><span class="o">=</span><span class="mi">2</span><span class="p">,</span> <span class="n">ncol</span><span class="o">=</span><span class="mi">5</span><span class="p">)</span>
<span class="n">plt</span><span class="o">.</span><span class="n">show</span><span class="p">()</span>
</pre></div>

    </div>
</div>
</div>

<div class="output_wrapper">
<div class="output">


<div class="output_area">

    <div class="prompt"></div>




<div class="output_png output_subarea ">
<img src="data:image/png;base64,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iSeeSM3KyuozbNiwXtOnT+88c+bMTjXlP/vsM2fdc+ByubSRI0f2zMnJ6d2zZ8+cf/zjH0kAu3btsnXt2jV3+vTpnbt37547evToHm63W0Bt78rcuXPbd+vWLbdnz545s2fP7vDRRx/FrVixIum+++7rkJ2dnbNt2zZ7c6+L5qA8IhGMv7YXO3bswBZjHJYH393G9qPlLbqNnMwEHpice9I81dXVDBgwAIAuXbrw9ttv10rftGkT27ZtIzMzk9GjR7Nq1SrGjBlTK88jjzxCSkoKwWCQ888/n6+//pp+/foBxkN248aNPP/88yxYsICXX36ZBx98kDFjxnD//ffz/vvvs3Dhwhbc66bz2JePsbPkxAfHDyE7JZu7ht110jwXXnghv/vd7+jZsycTJ05k2rRpjB49mk2bNgGwcuVK+vTpw1dffUUgEGD48OEIIdCtGs4UO/Om3sJfXnqOf73+LlndO2BzWLjsMqOn2jXXXMP48ePx+/3ccsstLF++nLS0NN544w3uvfdeFi1aBEBZWRmfffYZYDQj1HDVVVfxv//7vwDcd999/PWvf+WWW24BDAH1xRdfsHPnTi677DKmTp3K22+/za5du/jmm284duwYOTk5/OxnP2vRYwqwculuig65W7TO1I5Oxl7Ts0l5P/zwQ9555x3WrVtHbGwsJSUlAMyePZsXX3yRHj16sG7dOubOncvHH39cq+zpeEzL3t2L72hli9Zpy4wjaXK3ZpWZMWNG6R133FEEcOutt2Y+/fTTqffee28BwLFjx6zr16/fuXnzZseVV17Z/YYbbig136yPFhcX6yNHjux12223FQAsXrx4f0ZGRtDtdouBAwfmXHfddaVt27YNVldXayNHjnQ/88wzR+bMmdPhmWeeSXv88cfzmmpDS7B9x10dK927f5jrsg5xzp5VOb0fO9RYvsWLFydNmDDB1a9fP29SUlIwFAqJX//610fXr18f9+qrrx7cv3+/dcGCBe02bty4PSkpKTRq1Kieubm51TXl6zsHsbGxoffff39PSkpKKC8vzzJ8+PDsn/zkJ2UABw8edPzjH//YN2rUqAM//vGPu7766qvJc+fOLYmoT//ggw+S9+3bt1XTNIqKivTU1NTgxIkTyy699FLXDTfcUArQpk2bQHOui+YcOyVETkPqa5qJZNiwYXTo0AEgHENSV4gsXbqUhQsXEggEyMvLY/v27WEhUvOWP3jwYJYtWwbA559/Hl6+5JJLSE5ukWbIMwan08mGDRtYuXIln3zyCdOmTePRRx+le/fu7Nixgy+//JLbb7+dzz//nGAwyNixY8NlNTOYVegCGcIIZnVacSbZWfCnBcTExHDzzTezdetWtm7dygUXXABAMBikXbt24XqmTZtWr21bt27lvvvuo6ysDLfbzaRJk8JpV1xxBZqmkZOTw7Fjhkf9888/59prr0XXdTIzM/nRj350Kg5Z1FmxYgU33HBDuCksJSUFt9vN6tWrufrqq8P5vF7vCWXVMW2YDRs2xNx///3tKyoq9MrKSn38+PGumrTLLrusTNd1Bg8e7CkuLrbWrA+FQkydOrXLzTfffGzs2LFVAI899ljG+++/nwSQn59v3bZtm6Nt27aVVqtVTp8+3QUwePDgyhUrViQ0x4YznaVLl6bUiLUpU6aUvPbaaymRQmPlypVxw4cPr8jIyAgCXHnllaW7d+8Ox2rUdw5CoZCYP39+h7Vr1zo1TaOgoMB2+PBhC0D79u29o0aNqgYYOHBg1f79++2R9qSkpATtdnto+vTpnS+55BLXtGnT6j3W3+e6aCpKiJyExjwX0aKm+QCMwNa6MQXfffcdCxYs4KuvviI5OZlZs2bVGim2pnzdsqdDT5/GPBenEl3XmTBhAhMmTKBv3778/e9/Z+zYsXz44YdYrVYmTpzIrFmzCAaD9QY9CgHJbeOItdqoKvex4r8reOONpaxc+TlguPdzc3NZs2ZNvduPi4urd/2sWbN455136N+/P3/729/49NNPw2mR10Jkc1prnMumei5OFVLKE/YzFAqRlJR0UiEPp+cxba7n4lQxe/bsLm+99daekSNHVj/99NNtPvvss3BAo8PhCB+QyGNzxx13ZLZr18532223FQO899578Z999ln8+vXrd8bHx4eGDRvWq7q6WgOwWCxS04yWFovFQiAQOOHAnsyGlqApnotTQX5+vr527dqE3bt3x8ybN49gMCiEEDInJycsRBprFq/vHPzlL39JKS4utnzzzTc77Ha7bN++fd+a422z2cL5dV2XNetrsFqtbN68ece///3vhCVLliS/8MIL6WvXrt1dd7vf57poKmdNu5viOOXl5cTFxZGYmMixY8f48MMPGy0zbtw4Fi9eDBgu79LSZnnWznh27drF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
"
>
</div>

</div>

</div>
</div>

</div>
<div class="cell border-box-sizing text_cell rendered"><div class="prompt input_prompt">
</div><div class="inner_cell">
<div class="text_cell_render border-box-sizing rendered_html">
<p>From inspecting the time plots we can see that for the Freedom rating variable, there is a clear distinction and separation in value between the top 5 countries and the bottom 5 in terms of happiness rating. Because of this, we will choose to run a linear regression analysis on the Freedom variable. The goal is to determine through this linear regression model if the variable is statistically significant to the dependant variable, a country's happiness rating. Using the dataframe that we set up in this section, we will perform the regression using the OLS method and look at the resulting p-value to conduct our hypothesis testing.</p>

</div>
</div>
</div>
<div class="cell border-box-sizing code_cell rendered">
<div class="input">
<div class="prompt input_prompt">In&nbsp;[120]:</div>
<div class="inner_cell">
    <div class="input_area">
<div class=" highlight hl-ipython3"><pre><span></span><span class="n">yearly_df</span><span class="o">=</span><span class="n">yearly_df</span><span class="o">.</span><span class="n">rename</span><span class="p">(</span><span class="n">columns</span><span class="o">=</span><span class="p">{</span><span class="s1">&#39;Happiness Score&#39;</span><span class="p">:</span><span class="s1">&#39;Happiness&#39;</span><span class="p">})</span>

<span class="n">x</span> <span class="o">=</span> <span class="n">yearly_df</span><span class="p">[</span><span class="s1">&#39;Freedom&#39;</span><span class="p">]</span><span class="o">.</span><span class="n">values</span><span class="o">.</span><span class="n">reshape</span><span class="p">(</span><span class="o">-</span><span class="mi">1</span><span class="p">,</span><span class="mi">1</span><span class="p">)</span>
<span class="n">y</span> <span class="o">=</span> <span class="n">yearly_df</span><span class="p">[</span><span class="s1">&#39;Happiness&#39;</span><span class="p">]</span><span class="o">.</span><span class="n">values</span>

<span class="n">reg</span> <span class="o">=</span> <span class="n">sm</span><span class="o">.</span><span class="n">ols</span><span class="p">(</span><span class="n">formula</span><span class="o">=</span><span class="s1">&#39;Happiness ~ Freedom&#39;</span><span class="p">,</span> <span class="n">data</span><span class="o">=</span><span class="n">yearly_df</span><span class="p">)</span><span class="o">.</span><span class="n">fit</span><span class="p">()</span>

<span class="n">lm</span> <span class="o">=</span> <span class="n">linear_model</span><span class="o">.</span><span class="n">LinearRegression</span><span class="p">()</span>
<span class="n">lm</span><span class="o">.</span><span class="n">fit</span><span class="p">(</span><span class="n">x</span><span class="p">,</span> <span class="n">y</span><span class="p">)</span>

<span class="n">reg</span><span class="o">.</span><span class="n">summary</span><span class="p">()</span>
</pre></div>

    </div>
</div>
</div>

<div class="output_wrapper">
<div class="output">


<div class="output_area">

    <div class="prompt output_prompt">Out[120]:</div>



<div class="output_html rendered_html output_subarea output_execute_result">
<table class="simpletable">
<caption>OLS Regression Results</caption>
<tr>
  <th>Dep. Variable:</th>        <td>Happiness</td>    <th>  R-squared:         </th> <td>   0.182</td>
</tr>
<tr>
  <th>Model:</th>                   <td>OLS</td>       <th>  Adj. R-squared:    </th> <td>   0.181</td>
</tr>
<tr>
  <th>Method:</th>             <td>Least Squares</td>  <th>  F-statistic:       </th> <td>   207.2</td>
</tr>
<tr>
  <th>Date:</th>             <td>Fri, 18 Dec 2020</td> <th>  Prob (F-statistic):</th> <td>1.42e-42</td>
</tr>
<tr>
  <th>Time:</th>                 <td>07:07:52</td>     <th>  Log-Likelihood:    </th> <td> -1342.5</td>
</tr>
<tr>
  <th>No. Observations:</th>      <td>   935</td>      <th>  AIC:               </th> <td>   2689.</td>
</tr>
<tr>
  <th>Df Residuals:</th>          <td>   933</td>      <th>  BIC:               </th> <td>   2699.</td>
</tr>
<tr>
  <th>Df Model:</th>              <td>     1</td>      <th>                     </th>     <td> </td>   
</tr>
<tr>
  <th>Covariance Type:</th>      <td>nonrobust</td>    <th>                     </th>     <td> </td>   
</tr>
</table>
<table class="simpletable">
<tr>
      <td></td>         <th>coef</th>     <th>std err</th>      <th>t</th>      <th>P>|t|</th>  <th>[0.025</th>    <th>0.975]</th>  
</tr>
<tr>
  <th>Intercept</th> <td>    4.2737</td> <td>    0.085</td> <td>   50.468</td> <td> 0.000</td> <td>    4.107</td> <td>    4.440</td>
</tr>
<tr>
  <th>Freedom</th>   <td>    2.3745</td> <td>    0.165</td> <td>   14.395</td> <td> 0.000</td> <td>    2.051</td> <td>    2.698</td>
</tr>
</table>
<table class="simpletable">
<tr>
  <th>Omnibus:</th>       <td>27.870</td> <th>  Durbin-Watson:     </th> <td>   0.230</td>
</tr>
<tr>
  <th>Prob(Omnibus):</th> <td> 0.000</td> <th>  Jarque-Bera (JB):  </th> <td>  17.549</td>
</tr>
<tr>
  <th>Skew:</th>          <td>-0.194</td> <th>  Prob(JB):          </th> <td>0.000155</td>
</tr>
<tr>
  <th>Kurtosis:</th>      <td> 2.453</td> <th>  Cond. No.          </th> <td>    6.10</td>
</tr>
</table><br/><br/>Warnings:<br/>[1] Standard Errors assume that the covariance matrix of the errors is correctly specified.
</div>

</div>

</div>
</div>

</div>
<div class="cell border-box-sizing code_cell rendered">
<div class="input">
<div class="prompt input_prompt">In&nbsp;[121]:</div>
<div class="inner_cell">
    <div class="input_area">
<div class=" highlight hl-ipython3"><pre><span></span><span class="c1"># Print P value</span>
<span class="nb">print</span><span class="p">(</span><span class="s1">&#39;</span><span class="se">\t</span><span class="si">{}</span><span class="s1">&#39;</span><span class="o">.</span><span class="n">format</span><span class="p">(</span><span class="n">reg</span><span class="o">.</span><span class="n">pvalues</span><span class="p">[</span><span class="s1">&#39;Freedom&#39;</span><span class="p">]))</span>
</pre></div>

    </div>
</div>
</div>

<div class="output_wrapper">
<div class="output">


<div class="output_area">

    <div class="prompt"></div>


<div class="output_subarea output_stream output_stdout output_text">
<pre>	1.4216711837834532e-42
</pre>
</div>
</div>

</div>
</div>

</div>
<div class="cell border-box-sizing text_cell rendered"><div class="prompt input_prompt">
</div><div class="inner_cell">
<div class="text_cell_render border-box-sizing rendered_html">
<h3 id="Conclusion">Conclusion<a class="anchor-link" href="#Conclusion">&#182;</a></h3><p>From plotting each attribute, it is clear that there is a differenciation between the top 5 and bottom 5 countries for all 5 attribute. However, the plots made it clear that life expectancy and GDP showed the greatest difference. Because of this, we ran the regression on GDP versus happiness and found that the P-value of 1.3159381177526332e-35. Using an alpha value of 5% for our OLS regressions, based on the p-value for GDP versus happiness we can accept the null hypothesis and state that the variable is not statistically significant. Furthermore, from plotting these same attributes across time for the top 5 and bottom 5 countries in average happiness rating, we were able to look at how these attributes change over time, as well as how they differ between countries with vastly different happiness ratings. From inspecting these plots, we chose to also perform an OLS regression test on a country's freedom rating, and discovered a P-value of 1.4216711837834532e-42, which again is sufficiently low to accept the null hypothesis that the freedom variable to a country's happiness is not statistically significant. Future research and analysis can be done to find statistically significant variables from other sources for information on countries, as well as running multivariable regressions.</p>

</div>
</div>
</div>
<div class="cell border-box-sizing code_cell rendered">
<div class="input">
<div class="prompt input_prompt">In&nbsp;[&nbsp;]:</div>
<div class="inner_cell">
    <div class="input_area">
<div class=" highlight hl-ipython3"><pre><span></span> 
</pre></div>

    </div>
</div>
</div>

</div>
    </div>
  </div>
</body>

 


</html>

