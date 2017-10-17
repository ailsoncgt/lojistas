<template>
  <div id="app">
    <div style="height: 0; width: 0; position: absolute; visibility: hidden"><!-- inject:svg --><!-- endinject --></div>
<div id="frame">

    <aside class="left del-right">
      <a href="/">
        <div id="logo">
          <svg class="icon">
            <use xlink:href="#Logo-icon"></use>
          </svg>
        </div>
      </a>

      <nav>
        <div class="item" data-index="1">
          <svg class="icon link" >
            <use xlink:href="#bar-chart-icon"></use>
          </svg>
        </div>
        <div class="item" data-index="2">
          <a href="/produtos.html"></a>
          <svg class="icon link">
            <use xlink:href="#clothes-icon"></use>
          </svg>
        </div>
        <div class="item" data-index="3">
          <svg class="icon link">
            <use xlink:href="#label-icon"></use>
          </svg>
        </div>
        <div class="item" data-index="4">
          <svg class="icon link">
            <use xlink:href="#info-icon"></use>
          </svg>
        </div>
      </nav>
    </aside>
    <section id="beside" class="">
      <header class="main del-bottom">
        <svg class="icon">
          <use xlink:href="#shop-icon"></use>
        </svg>
        <h1>
          Loja ModaJá
        </h1>
        <div id="user-account">
          <button id="logout-btn" type="button" class="custom">

            <svg class="icon">
              <use xlink:href="#logout-icon"></use>
            </svg>

            <div role="label" for="logout-btn">Logout</div>
          </button>
          <div style="background-image:url(http://www.hellomaps.net/images/joomla-maps/faceuser1.jpg)" class="avatar"></div>
        </div>
      </header>
      <div class="d-flex flex-row">
        <section id="content">

        </section>
        <aside class="right del-left">

          <header>
            <h2>Bem-vindo!</h2>
            <h3>04 de Outubro</h3>
          </header>

          <article class="sidebar-summary-item">
            <h4>Central de Suporte</h4>
            <p>Nenhum chamado aberto</p>
            <a href="">Abrir Chamado
              <svg class="icon text">
                <use xlink:href="#forward-arrow-icon"></use>
              </svg>
            </a>
          </article>
          <article class="sidebar-summary-item">
            <h4>Método de Pagamento</h4>
            <p>Mastercard xxxx6677</p>
            <a href="">Alterar
              <svg class="icon text">
                <use xlink:href="#forward-arrow-icon"></use>
              </svg>
            </a>
          </article>
        </aside>
      </div>
    </section>

  </div>

</div>
  </div>
</template>

<script>
import HelloWorld from './components/HelloWorld'

export default {
  name: 'app',
  components: {
    HelloWorld
  }
}
</script>

<style>
/* FRAME */
/* BOOTSTRAP */
/*!
 * Bootstrap v4.0.0-beta (https://getbootstrap.com)
 * Copyright 2011-2017 The Bootstrap Authors
 * Copyright 2011-2017 Twitter, Inc.
 * Licensed under MIT (https://github.com/twbs/bootstrap/blob/master/LICENSE)
 */
@media print {
  *,
  *::before,
  *::after {
    text-shadow: none !important;
    box-shadow: none !important; }
  a,
  a:visited {
    text-decoration: underline; }
  abbr[title]::after {
    content: " (" attr(title) ")"; }
  pre {
    white-space: pre-wrap !important; }
  pre,
  blockquote {
    border: 1px solid #999;
    page-break-inside: avoid; }
  thead {
    display: table-header-group; }
  tr,
  img {
    page-break-inside: avoid; }
  p,
  h2,
  h3 {
    orphans: 3;
    widows: 3; }
  h2,
  h3 {
    page-break-after: avoid; }
  .navbar {
    display: none; }
  .badge {
    border: 1px solid #000; }
  .table {
    border-collapse: collapse !important; }
    .table td,
    .table th {
      background-color: #fff !important; }
  .table-bordered th,
  .table-bordered td {
    border: 1px solid #ddd !important; } }

*,
*::before,
*::after {
  box-sizing: border-box; }

html {
  font-family: sans-serif;
  line-height: 1.15;
  -webkit-text-size-adjust: 100%;
  -ms-text-size-adjust: 100%;
  -ms-overflow-style: scrollbar;
  -webkit-tap-highlight-color: transparent; }

@-ms-viewport {
  width: device-width; }

article, aside, dialog, figcaption, figure, footer, header, hgroup, main, nav, section {
  display: block; }

body {
  margin: 0;
  font-family: -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, "Helvetica Neue", Arial, sans-serif, "Apple Color Emoji", "Segoe UI Emoji", "Segoe UI Symbol";
  font-size: 1rem;
  font-weight: normal;
  line-height: 1.5;
  color: #212529;
  text-align: left;
  background-color: #fff; }

[tabindex="-1"]:focus {
  outline: none !important; }

hr {
  box-sizing: content-box;
  height: 0;
  overflow: visible; }

h1, h2, h3, h4, h5, h6 {
  margin-top: 0;
  margin-bottom: .5rem; }

p {
  margin-top: 0;
  margin-bottom: 1rem; }

abbr[title],
abbr[data-original-title] {
  text-decoration: underline;
  text-decoration: underline dotted;
  cursor: help;
  border-bottom: 0; }

address {
  margin-bottom: 1rem;
  font-style: normal;
  line-height: inherit; }

ol,
ul,
dl {
  margin-top: 0;
  margin-bottom: 1rem; }

ol ol,
ul ul,
ol ul,
ul ol {
  margin-bottom: 0; }

dt {
  font-weight: bold; }

dd {
  margin-bottom: .5rem;
  margin-left: 0; }

blockquote {
  margin: 0 0 1rem; }

dfn {
  font-style: italic; }

b,
strong {
  font-weight: bolder; }

small {
  font-size: 80%; }

sub,
sup {
  position: relative;
  font-size: 75%;
  line-height: 0;
  vertical-align: baseline; }

sub {
  bottom: -.25em; }

sup {
  top: -.5em; }

a {
  color: #007bff;
  text-decoration: none;
  background-color: transparent;
  -webkit-text-decoration-skip: objects; }
  a:hover {
    color: #0056b3;
    text-decoration: underline; }

a:not([href]):not([tabindex]) {
  color: inherit;
  text-decoration: none; }
  a:not([href]):not([tabindex]):focus, a:not([href]):not([tabindex]):hover {
    color: inherit;
    text-decoration: none; }
  a:not([href]):not([tabindex]):focus {
    outline: 0; }

pre,
code,
kbd,
samp {
  font-family: monospace, monospace;
  font-size: 1em; }

pre {
  margin-top: 0;
  margin-bottom: 1rem;
  overflow: auto; }

figure {
  margin: 0 0 1rem; }

img {
  vertical-align: middle;
  border-style: none; }

svg:not(:root) {
  overflow: hidden; }

a,
area,
button,
[role="button"],
input,
label,
select,
summary,
textarea {
  -ms-touch-action: manipulation;
      touch-action: manipulation; }

table {
  border-collapse: collapse; }

caption {
  padding-top: 0.75rem;
  padding-bottom: 0.75rem;
  color: #868e96;
  text-align: left;
  caption-side: bottom; }

th {
  text-align: inherit; }

label {
  display: inline-block;
  margin-bottom: .5rem; }

button:focus {
  outline: 1px dotted;
  outline: 5px auto -webkit-focus-ring-color; }

input,
button,
select,
optgroup,
textarea {
  margin: 0;
  font-family: inherit;
  font-size: inherit;
  line-height: inherit; }

button,
input {
  overflow: visible; }

button,
select {
  text-transform: none; }

button,
html [type="button"],
[type="reset"],
[type="submit"] {
  -webkit-appearance: button; }

button::-moz-focus-inner,
[type="button"]::-moz-focus-inner,
[type="reset"]::-moz-focus-inner,
[type="submit"]::-moz-focus-inner {
  padding: 0;
  border-style: none; }

input[type="radio"],
input[type="checkbox"] {
  box-sizing: border-box;
  padding: 0; }

input[type="date"],
input[type="time"],
input[type="datetime-local"],
input[type="month"] {
  -webkit-appearance: listbox; }

textarea {
  overflow: auto;
  resize: vertical; }

fieldset {
  min-width: 0;
  padding: 0;
  margin: 0;
  border: 0; }

legend {
  display: block;
  width: 100%;
  max-width: 100%;
  padding: 0;
  margin-bottom: .5rem;
  font-size: 1.5rem;
  line-height: inherit;
  color: inherit;
  white-space: normal; }

progress {
  vertical-align: baseline; }

[type="number"]::-webkit-inner-spin-button,
[type="number"]::-webkit-outer-spin-button {
  height: auto; }

[type="search"] {
  outline-offset: -2px;
  -webkit-appearance: none; }

[type="search"]::-webkit-search-cancel-button,
[type="search"]::-webkit-search-decoration {
  -webkit-appearance: none; }

::-webkit-file-upload-button {
  font: inherit;
  -webkit-appearance: button; }

output {
  display: inline-block; }

summary {
  display: list-item; }

template {
  display: none; }

[hidden] {
  display: none !important; }

h1, h2, h3, h4, h5, h6,
.h1, .h2, .h3, .h4, .h5, .h6 {
  margin-bottom: 0.5rem;
  font-family: inherit;
  font-weight: 500;
  line-height: 1.1;
  color: inherit; }

h1, .h1 {
  font-size: 2.5rem; }

h2, .h2 {
  font-size: 2rem; }

h3, .h3 {
  font-size: 1.75rem; }

h4, .h4 {
  font-size: 1.5rem; }

h5, .h5 {
  font-size: 1.25rem; }

h6, .h6 {
  font-size: 1rem; }

.lead {
  font-size: 1.25rem;
  font-weight: 300; }

.display-1 {
  font-size: 6rem;
  font-weight: 300;
  line-height: 1.1; }

.display-2 {
  font-size: 5.5rem;
  font-weight: 300;
  line-height: 1.1; }

.display-3 {
  font-size: 4.5rem;
  font-weight: 300;
  line-height: 1.1; }

.display-4 {
  font-size: 3.5rem;
  font-weight: 300;
  line-height: 1.1; }

hr {
  margin-top: 1rem;
  margin-bottom: 1rem;
  border: 0;
  border-top: 1px solid rgba(0, 0, 0, 0.1); }

small,
.small {
  font-size: 80%;
  font-weight: normal; }

mark,
.mark {
  padding: 0.2em;
  background-color: #fcf8e3; }

.list-unstyled {
  padding-left: 0;
  list-style: none; }

.list-inline {
  padding-left: 0;
  list-style: none; }

.list-inline-item {
  display: inline-block; }
  .list-inline-item:not(:last-child) {
    margin-right: 5px; }

.initialism {
  font-size: 90%;
  text-transform: uppercase; }

.blockquote {
  margin-bottom: 1rem;
  font-size: 1.25rem; }

.blockquote-footer {
  display: block;
  font-size: 80%;
  color: #868e96; }
  .blockquote-footer::before {
    content: "\2014 \00A0"; }

.img-fluid {
  max-width: 100%;
  height: auto; }

.img-thumbnail {
  padding: 0.25rem;
  background-color: #fff;
  border: 1px solid #ddd;
  border-radius: 0.25rem;
  transition: all 0.2s ease-in-out;
  max-width: 100%;
  height: auto; }

.figure {
  display: inline-block; }

.figure-img {
  margin-bottom: 0.5rem;
  line-height: 1; }

.figure-caption {
  font-size: 90%;
  color: #868e96; }

code,
kbd,
pre,
samp {
  font-family: "SFMono-Regular", Menlo, Monaco, Consolas, "Liberation Mono", "Courier New", monospace; }

code {
  padding: 0.2rem 0.4rem;
  font-size: 90%;
  color: #bd4147;
  background-color: #f8f9fa;
  border-radius: 0.25rem; }
  a > code {
    padding: 0;
    color: inherit;
    background-color: inherit; }

kbd {
  padding: 0.2rem 0.4rem;
  font-size: 90%;
  color: #fff;
  background-color: #212529;
  border-radius: 0.2rem; }
  kbd kbd {
    padding: 0;
    font-size: 100%;
    font-weight: bold; }

pre {
  display: block;
  margin-top: 0;
  margin-bottom: 1rem;
  font-size: 90%;
  color: #212529; }
  pre code {
    padding: 0;
    font-size: inherit;
    color: inherit;
    background-color: transparent;
    border-radius: 0; }

.pre-scrollable {
  max-height: 340px;
  overflow-y: scroll; }

.container {
  margin-right: auto;
  margin-left: auto;
  padding-right: 15px;
  padding-left: 15px;
  width: 100%; }
  @media (min-width: 576px) {
    .container {
      max-width: 540px; } }
  @media (min-width: 768px) {
    .container {
      max-width: 720px; } }
  @media (min-width: 992px) {
    .container {
      max-width: 960px; } }
  @media (min-width: 1200px) {
    .container {
      max-width: 1140px; } }

.container-fluid {
  width: 100%;
  margin-right: auto;
  margin-left: auto;
  padding-right: 15px;
  padding-left: 15px;
  width: 100%; }

.row {
  display: -webkit-flex;
  display: -ms-flexbox;
  display: flex;
  -webkit-flex-wrap: wrap;
      -ms-flex-wrap: wrap;
          flex-wrap: wrap;
  margin-right: -15px;
  margin-left: -15px; }

.no-gutters {
  margin-right: 0;
  margin-left: 0; }
  .no-gutters > .col,
  .no-gutters > [class*="col-"] {
    padding-right: 0;
    padding-left: 0; }

.col-1, .col-2, .col-3, .col-4, .col-5, .col-6, .col-7, .col-8, .col-9, .col-10, .col-11, .col-12, .col,
.col-auto, .col-sm-1, .col-sm-2, .col-sm-3, .col-sm-4, .col-sm-5, .col-sm-6, .col-sm-7, .col-sm-8, .col-sm-9, .col-sm-10, .col-sm-11, .col-sm-12, .col-sm,
.col-sm-auto, .col-md-1, .col-md-2, .col-md-3, .col-md-4, .col-md-5, .col-md-6, .col-md-7, .col-md-8, .col-md-9, .col-md-10, .col-md-11, .col-md-12, .col-md,
.col-md-auto, .col-lg-1, .col-lg-2, .col-lg-3, .col-lg-4, .col-lg-5, .col-lg-6, .col-lg-7, .col-lg-8, .col-lg-9, .col-lg-10, .col-lg-11, .col-lg-12, .col-lg,
.col-lg-auto, .col-xl-1, .col-xl-2, .col-xl-3, .col-xl-4, .col-xl-5, .col-xl-6, .col-xl-7, .col-xl-8, .col-xl-9, .col-xl-10, .col-xl-11, .col-xl-12, .col-xl,
.col-xl-auto {
  position: relative;
  width: 100%;
  min-height: 1px;
  padding-right: 15px;
  padding-left: 15px; }

.col {
  -webkit-flex-basis: 0;
      -ms-flex-preferred-size: 0;
          flex-basis: 0;
  -webkit-flex-grow: 1;
      -ms-flex-positive: 1;
          flex-grow: 1;
  max-width: 100%; }

.col-auto {
  -webkit-flex: 0 0 auto;
      -ms-flex: 0 0 auto;
          flex: 0 0 auto;
  width: auto;
  max-width: none; }

.col-1 {
  -webkit-flex: 0 0 8.33333%;
      -ms-flex: 0 0 8.33333%;
          flex: 0 0 8.33333%;
  max-width: 8.33333%; }

.col-2 {
  -webkit-flex: 0 0 16.66667%;
      -ms-flex: 0 0 16.66667%;
          flex: 0 0 16.66667%;
  max-width: 16.66667%; }

.col-3 {
  -webkit-flex: 0 0 25%;
      -ms-flex: 0 0 25%;
          flex: 0 0 25%;
  max-width: 25%; }

.col-4 {
  -webkit-flex: 0 0 33.33333%;
      -ms-flex: 0 0 33.33333%;
          flex: 0 0 33.33333%;
  max-width: 33.33333%; }

.col-5 {
  -webkit-flex: 0 0 41.66667%;
      -ms-flex: 0 0 41.66667%;
          flex: 0 0 41.66667%;
  max-width: 41.66667%; }

.col-6 {
  -webkit-flex: 0 0 50%;
      -ms-flex: 0 0 50%;
          flex: 0 0 50%;
  max-width: 50%; }

.col-7 {
  -webkit-flex: 0 0 58.33333%;
      -ms-flex: 0 0 58.33333%;
          flex: 0 0 58.33333%;
  max-width: 58.33333%; }

.col-8 {
  -webkit-flex: 0 0 66.66667%;
      -ms-flex: 0 0 66.66667%;
          flex: 0 0 66.66667%;
  max-width: 66.66667%; }

.col-9 {
  -webkit-flex: 0 0 75%;
      -ms-flex: 0 0 75%;
          flex: 0 0 75%;
  max-width: 75%; }

.col-10 {
  -webkit-flex: 0 0 83.33333%;
      -ms-flex: 0 0 83.33333%;
          flex: 0 0 83.33333%;
  max-width: 83.33333%; }

.col-11 {
  -webkit-flex: 0 0 91.66667%;
      -ms-flex: 0 0 91.66667%;
          flex: 0 0 91.66667%;
  max-width: 91.66667%; }

.col-12 {
  -webkit-flex: 0 0 100%;
      -ms-flex: 0 0 100%;
          flex: 0 0 100%;
  max-width: 100%; }

.order-1 {
  -webkit-order: 1;
      -ms-flex-order: 1;
          order: 1; }

.order-2 {
  -webkit-order: 2;
      -ms-flex-order: 2;
          order: 2; }

.order-3 {
  -webkit-order: 3;
      -ms-flex-order: 3;
          order: 3; }

.order-4 {
  -webkit-order: 4;
      -ms-flex-order: 4;
          order: 4; }

.order-5 {
  -webkit-order: 5;
      -ms-flex-order: 5;
          order: 5; }

.order-6 {
  -webkit-order: 6;
      -ms-flex-order: 6;
          order: 6; }

.order-7 {
  -webkit-order: 7;
      -ms-flex-order: 7;
          order: 7; }

.order-8 {
  -webkit-order: 8;
      -ms-flex-order: 8;
          order: 8; }

.order-9 {
  -webkit-order: 9;
      -ms-flex-order: 9;
          order: 9; }

.order-10 {
  -webkit-order: 10;
      -ms-flex-order: 10;
          order: 10; }

.order-11 {
  -webkit-order: 11;
      -ms-flex-order: 11;
          order: 11; }

.order-12 {
  -webkit-order: 12;
      -ms-flex-order: 12;
          order: 12; }

@media (min-width: 576px) {
  .col-sm {
    -webkit-flex-basis: 0;
        -ms-flex-preferred-size: 0;
            flex-basis: 0;
    -webkit-flex-grow: 1;
        -ms-flex-positive: 1;
            flex-grow: 1;
    max-width: 100%; }
  .col-sm-auto {
    -webkit-flex: 0 0 auto;
        -ms-flex: 0 0 auto;
            flex: 0 0 auto;
    width: auto;
    max-width: none; }
  .col-sm-1 {
    -webkit-flex: 0 0 8.33333%;
        -ms-flex: 0 0 8.33333%;
            flex: 0 0 8.33333%;
    max-width: 8.33333%; }
  .col-sm-2 {
    -webkit-flex: 0 0 16.66667%;
        -ms-flex: 0 0 16.66667%;
            flex: 0 0 16.66667%;
    max-width: 16.66667%; }
  .col-sm-3 {
    -webkit-flex: 0 0 25%;
        -ms-flex: 0 0 25%;
            flex: 0 0 25%;
    max-width: 25%; }
  .col-sm-4 {
    -webkit-flex: 0 0 33.33333%;
        -ms-flex: 0 0 33.33333%;
            flex: 0 0 33.33333%;
    max-width: 33.33333%; }
  .col-sm-5 {
    -webkit-flex: 0 0 41.66667%;
        -ms-flex: 0 0 41.66667%;
            flex: 0 0 41.66667%;
    max-width: 41.66667%; }
  .col-sm-6 {
    -webkit-flex: 0 0 50%;
        -ms-flex: 0 0 50%;
            flex: 0 0 50%;
    max-width: 50%; }
  .col-sm-7 {
    -webkit-flex: 0 0 58.33333%;
        -ms-flex: 0 0 58.33333%;
            flex: 0 0 58.33333%;
    max-width: 58.33333%; }
  .col-sm-8 {
    -webkit-flex: 0 0 66.66667%;
        -ms-flex: 0 0 66.66667%;
            flex: 0 0 66.66667%;
    max-width: 66.66667%; }
  .col-sm-9 {
    -webkit-flex: 0 0 75%;
        -ms-flex: 0 0 75%;
            flex: 0 0 75%;
    max-width: 75%; }
  .col-sm-10 {
    -webkit-flex: 0 0 83.33333%;
        -ms-flex: 0 0 83.33333%;
            flex: 0 0 83.33333%;
    max-width: 83.33333%; }
  .col-sm-11 {
    -webkit-flex: 0 0 91.66667%;
        -ms-flex: 0 0 91.66667%;
            flex: 0 0 91.66667%;
    max-width: 91.66667%; }
  .col-sm-12 {
    -webkit-flex: 0 0 100%;
        -ms-flex: 0 0 100%;
            flex: 0 0 100%;
    max-width: 100%; }
  .order-sm-1 {
    -webkit-order: 1;
        -ms-flex-order: 1;
            order: 1; }
  .order-sm-2 {
    -webkit-order: 2;
        -ms-flex-order: 2;
            order: 2; }
  .order-sm-3 {
    -webkit-order: 3;
        -ms-flex-order: 3;
            order: 3; }
  .order-sm-4 {
    -webkit-order: 4;
        -ms-flex-order: 4;
            order: 4; }
  .order-sm-5 {
    -webkit-order: 5;
        -ms-flex-order: 5;
            order: 5; }
  .order-sm-6 {
    -webkit-order: 6;
        -ms-flex-order: 6;
            order: 6; }
  .order-sm-7 {
    -webkit-order: 7;
        -ms-flex-order: 7;
            order: 7; }
  .order-sm-8 {
    -webkit-order: 8;
        -ms-flex-order: 8;
            order: 8; }
  .order-sm-9 {
    -webkit-order: 9;
        -ms-flex-order: 9;
            order: 9; }
  .order-sm-10 {
    -webkit-order: 10;
        -ms-flex-order: 10;
            order: 10; }
  .order-sm-11 {
    -webkit-order: 11;
        -ms-flex-order: 11;
            order: 11; }
  .order-sm-12 {
    -webkit-order: 12;
        -ms-flex-order: 12;
            order: 12; } }

@media (min-width: 768px) {
  .col-md {
    -webkit-flex-basis: 0;
        -ms-flex-preferred-size: 0;
            flex-basis: 0;
    -webkit-flex-grow: 1;
        -ms-flex-positive: 1;
            flex-grow: 1;
    max-width: 100%; }
  .col-md-auto {
    -webkit-flex: 0 0 auto;
        -ms-flex: 0 0 auto;
            flex: 0 0 auto;
    width: auto;
    max-width: none; }
  .col-md-1 {
    -webkit-flex: 0 0 8.33333%;
        -ms-flex: 0 0 8.33333%;
            flex: 0 0 8.33333%;
    max-width: 8.33333%; }
  .col-md-2 {
    -webkit-flex: 0 0 16.66667%;
        -ms-flex: 0 0 16.66667%;
            flex: 0 0 16.66667%;
    max-width: 16.66667%; }
  .col-md-3 {
    -webkit-flex: 0 0 25%;
        -ms-flex: 0 0 25%;
            flex: 0 0 25%;
    max-width: 25%; }
  .col-md-4 {
    -webkit-flex: 0 0 33.33333%;
        -ms-flex: 0 0 33.33333%;
            flex: 0 0 33.33333%;
    max-width: 33.33333%; }
  .col-md-5 {
    -webkit-flex: 0 0 41.66667%;
        -ms-flex: 0 0 41.66667%;
            flex: 0 0 41.66667%;
    max-width: 41.66667%; }
  .col-md-6 {
    -webkit-flex: 0 0 50%;
        -ms-flex: 0 0 50%;
            flex: 0 0 50%;
    max-width: 50%; }
  .col-md-7 {
    -webkit-flex: 0 0 58.33333%;
        -ms-flex: 0 0 58.33333%;
            flex: 0 0 58.33333%;
    max-width: 58.33333%; }
  .col-md-8 {
    -webkit-flex: 0 0 66.66667%;
        -ms-flex: 0 0 66.66667%;
            flex: 0 0 66.66667%;
    max-width: 66.66667%; }
  .col-md-9 {
    -webkit-flex: 0 0 75%;
        -ms-flex: 0 0 75%;
            flex: 0 0 75%;
    max-width: 75%; }
  .col-md-10 {
    -webkit-flex: 0 0 83.33333%;
        -ms-flex: 0 0 83.33333%;
            flex: 0 0 83.33333%;
    max-width: 83.33333%; }
  .col-md-11 {
    -webkit-flex: 0 0 91.66667%;
        -ms-flex: 0 0 91.66667%;
            flex: 0 0 91.66667%;
    max-width: 91.66667%; }
  .col-md-12 {
    -webkit-flex: 0 0 100%;
        -ms-flex: 0 0 100%;
            flex: 0 0 100%;
    max-width: 100%; }
  .order-md-1 {
    -webkit-order: 1;
        -ms-flex-order: 1;
            order: 1; }
  .order-md-2 {
    -webkit-order: 2;
        -ms-flex-order: 2;
            order: 2; }
  .order-md-3 {
    -webkit-order: 3;
        -ms-flex-order: 3;
            order: 3; }
  .order-md-4 {
    -webkit-order: 4;
        -ms-flex-order: 4;
            order: 4; }
  .order-md-5 {
    -webkit-order: 5;
        -ms-flex-order: 5;
            order: 5; }
  .order-md-6 {
    -webkit-order: 6;
        -ms-flex-order: 6;
            order: 6; }
  .order-md-7 {
    -webkit-order: 7;
        -ms-flex-order: 7;
            order: 7; }
  .order-md-8 {
    -webkit-order: 8;
        -ms-flex-order: 8;
            order: 8; }
  .order-md-9 {
    -webkit-order: 9;
        -ms-flex-order: 9;
            order: 9; }
  .order-md-10 {
    -webkit-order: 10;
        -ms-flex-order: 10;
            order: 10; }
  .order-md-11 {
    -webkit-order: 11;
        -ms-flex-order: 11;
            order: 11; }
  .order-md-12 {
    -webkit-order: 12;
        -ms-flex-order: 12;
            order: 12; } }

@media (min-width: 992px) {
  .col-lg {
    -webkit-flex-basis: 0;
        -ms-flex-preferred-size: 0;
            flex-basis: 0;
    -webkit-flex-grow: 1;
        -ms-flex-positive: 1;
            flex-grow: 1;
    max-width: 100%; }
  .col-lg-auto {
    -webkit-flex: 0 0 auto;
        -ms-flex: 0 0 auto;
            flex: 0 0 auto;
    width: auto;
    max-width: none; }
  .col-lg-1 {
    -webkit-flex: 0 0 8.33333%;
        -ms-flex: 0 0 8.33333%;
            flex: 0 0 8.33333%;
    max-width: 8.33333%; }
  .col-lg-2 {
    -webkit-flex: 0 0 16.66667%;
        -ms-flex: 0 0 16.66667%;
            flex: 0 0 16.66667%;
    max-width: 16.66667%; }
  .col-lg-3 {
    -webkit-flex: 0 0 25%;
        -ms-flex: 0 0 25%;
            flex: 0 0 25%;
    max-width: 25%; }
  .col-lg-4 {
    -webkit-flex: 0 0 33.33333%;
        -ms-flex: 0 0 33.33333%;
            flex: 0 0 33.33333%;
    max-width: 33.33333%; }
  .col-lg-5 {
    -webkit-flex: 0 0 41.66667%;
        -ms-flex: 0 0 41.66667%;
            flex: 0 0 41.66667%;
    max-width: 41.66667%; }
  .col-lg-6 {
    -webkit-flex: 0 0 50%;
        -ms-flex: 0 0 50%;
            flex: 0 0 50%;
    max-width: 50%; }
  .col-lg-7 {
    -webkit-flex: 0 0 58.33333%;
        -ms-flex: 0 0 58.33333%;
            flex: 0 0 58.33333%;
    max-width: 58.33333%; }
  .col-lg-8 {
    -webkit-flex: 0 0 66.66667%;
        -ms-flex: 0 0 66.66667%;
            flex: 0 0 66.66667%;
    max-width: 66.66667%; }
  .col-lg-9 {
    -webkit-flex: 0 0 75%;
        -ms-flex: 0 0 75%;
            flex: 0 0 75%;
    max-width: 75%; }
  .col-lg-10 {
    -webkit-flex: 0 0 83.33333%;
        -ms-flex: 0 0 83.33333%;
            flex: 0 0 83.33333%;
    max-width: 83.33333%; }
  .col-lg-11 {
    -webkit-flex: 0 0 91.66667%;
        -ms-flex: 0 0 91.66667%;
            flex: 0 0 91.66667%;
    max-width: 91.66667%; }
  .col-lg-12 {
    -webkit-flex: 0 0 100%;
        -ms-flex: 0 0 100%;
            flex: 0 0 100%;
    max-width: 100%; }
  .order-lg-1 {
    -webkit-order: 1;
        -ms-flex-order: 1;
            order: 1; }
  .order-lg-2 {
    -webkit-order: 2;
        -ms-flex-order: 2;
            order: 2; }
  .order-lg-3 {
    -webkit-order: 3;
        -ms-flex-order: 3;
            order: 3; }
  .order-lg-4 {
    -webkit-order: 4;
        -ms-flex-order: 4;
            order: 4; }
  .order-lg-5 {
    -webkit-order: 5;
        -ms-flex-order: 5;
            order: 5; }
  .order-lg-6 {
    -webkit-order: 6;
        -ms-flex-order: 6;
            order: 6; }
  .order-lg-7 {
    -webkit-order: 7;
        -ms-flex-order: 7;
            order: 7; }
  .order-lg-8 {
    -webkit-order: 8;
        -ms-flex-order: 8;
            order: 8; }
  .order-lg-9 {
    -webkit-order: 9;
        -ms-flex-order: 9;
            order: 9; }
  .order-lg-10 {
    -webkit-order: 10;
        -ms-flex-order: 10;
            order: 10; }
  .order-lg-11 {
    -webkit-order: 11;
        -ms-flex-order: 11;
            order: 11; }
  .order-lg-12 {
    -webkit-order: 12;
        -ms-flex-order: 12;
            order: 12; } }

@media (min-width: 1200px) {
  .col-xl {
    -webkit-flex-basis: 0;
        -ms-flex-preferred-size: 0;
            flex-basis: 0;
    -webkit-flex-grow: 1;
        -ms-flex-positive: 1;
            flex-grow: 1;
    max-width: 100%; }
  .col-xl-auto {
    -webkit-flex: 0 0 auto;
        -ms-flex: 0 0 auto;
            flex: 0 0 auto;
    width: auto;
    max-width: none; }
  .col-xl-1 {
    -webkit-flex: 0 0 8.33333%;
        -ms-flex: 0 0 8.33333%;
            flex: 0 0 8.33333%;
    max-width: 8.33333%; }
  .col-xl-2 {
    -webkit-flex: 0 0 16.66667%;
        -ms-flex: 0 0 16.66667%;
            flex: 0 0 16.66667%;
    max-width: 16.66667%; }
  .col-xl-3 {
    -webkit-flex: 0 0 25%;
        -ms-flex: 0 0 25%;
            flex: 0 0 25%;
    max-width: 25%; }
  .col-xl-4 {
    -webkit-flex: 0 0 33.33333%;
        -ms-flex: 0 0 33.33333%;
            flex: 0 0 33.33333%;
    max-width: 33.33333%; }
  .col-xl-5 {
    -webkit-flex: 0 0 41.66667%;
        -ms-flex: 0 0 41.66667%;
            flex: 0 0 41.66667%;
    max-width: 41.66667%; }
  .col-xl-6 {
    -webkit-flex: 0 0 50%;
        -ms-flex: 0 0 50%;
            flex: 0 0 50%;
    max-width: 50%; }
  .col-xl-7 {
    -webkit-flex: 0 0 58.33333%;
        -ms-flex: 0 0 58.33333%;
            flex: 0 0 58.33333%;
    max-width: 58.33333%; }
  .col-xl-8 {
    -webkit-flex: 0 0 66.66667%;
        -ms-flex: 0 0 66.66667%;
            flex: 0 0 66.66667%;
    max-width: 66.66667%; }
  .col-xl-9 {
    -webkit-flex: 0 0 75%;
        -ms-flex: 0 0 75%;
            flex: 0 0 75%;
    max-width: 75%; }
  .col-xl-10 {
    -webkit-flex: 0 0 83.33333%;
        -ms-flex: 0 0 83.33333%;
            flex: 0 0 83.33333%;
    max-width: 83.33333%; }
  .col-xl-11 {
    -webkit-flex: 0 0 91.66667%;
        -ms-flex: 0 0 91.66667%;
            flex: 0 0 91.66667%;
    max-width: 91.66667%; }
  .col-xl-12 {
    -webkit-flex: 0 0 100%;
        -ms-flex: 0 0 100%;
            flex: 0 0 100%;
    max-width: 100%; }
  .order-xl-1 {
    -webkit-order: 1;
        -ms-flex-order: 1;
            order: 1; }
  .order-xl-2 {
    -webkit-order: 2;
        -ms-flex-order: 2;
            order: 2; }
  .order-xl-3 {
    -webkit-order: 3;
        -ms-flex-order: 3;
            order: 3; }
  .order-xl-4 {
    -webkit-order: 4;
        -ms-flex-order: 4;
            order: 4; }
  .order-xl-5 {
    -webkit-order: 5;
        -ms-flex-order: 5;
            order: 5; }
  .order-xl-6 {
    -webkit-order: 6;
        -ms-flex-order: 6;
            order: 6; }
  .order-xl-7 {
    -webkit-order: 7;
        -ms-flex-order: 7;
            order: 7; }
  .order-xl-8 {
    -webkit-order: 8;
        -ms-flex-order: 8;
            order: 8; }
  .order-xl-9 {
    -webkit-order: 9;
        -ms-flex-order: 9;
            order: 9; }
  .order-xl-10 {
    -webkit-order: 10;
        -ms-flex-order: 10;
            order: 10; }
  .order-xl-11 {
    -webkit-order: 11;
        -ms-flex-order: 11;
            order: 11; }
  .order-xl-12 {
    -webkit-order: 12;
        -ms-flex-order: 12;
            order: 12; } }

.table {
  width: 100%;
  max-width: 100%;
  margin-bottom: 1rem;
  background-color: transparent; }
  .table th,
  .table td {
    padding: 0.75rem;
    vertical-align: top;
    border-top: 1px solid #e9ecef; }
  .table thead th {
    vertical-align: bottom;
    border-bottom: 2px solid #e9ecef; }
  .table tbody + tbody {
    border-top: 2px solid #e9ecef; }
  .table .table {
    background-color: #fff; }

.table-sm th,
.table-sm td {
  padding: 0.3rem; }

.table-bordered {
  border: 1px solid #e9ecef; }
  .table-bordered th,
  .table-bordered td {
    border: 1px solid #e9ecef; }
  .table-bordered thead th,
  .table-bordered thead td {
    border-bottom-width: 2px; }

.table-striped tbody tr:nth-of-type(odd) {
  background-color: rgba(0, 0, 0, 0.05); }

.table-hover tbody tr:hover {
  background-color: rgba(0, 0, 0, 0.075); }

.table-primary,
.table-primary > th,
.table-primary > td {
  background-color: #b8daff; }

.table-hover .table-primary:hover {
  background-color: #9fcdff; }
  .table-hover .table-primary:hover > td,
  .table-hover .table-primary:hover > th {
    background-color: #9fcdff; }

.table-secondary,
.table-secondary > th,
.table-secondary > td {
  background-color: #dddfe2; }

.table-hover .table-secondary:hover {
  background-color: #cfd2d6; }
  .table-hover .table-secondary:hover > td,
  .table-hover .table-secondary:hover > th {
    background-color: #cfd2d6; }

.table-success,
.table-success > th,
.table-success > td {
  background-color: #c3e6cb; }

.table-hover .table-success:hover {
  background-color: #b1dfbb; }
  .table-hover .table-success:hover > td,
  .table-hover .table-success:hover > th {
    background-color: #b1dfbb; }

.table-info,
.table-info > th,
.table-info > td {
  background-color: #bee5eb; }

.table-hover .table-info:hover {
  background-color: #abdde5; }
  .table-hover .table-info:hover > td,
  .table-hover .table-info:hover > th {
    background-color: #abdde5; }

.table-warning,
.table-warning > th,
.table-warning > td {
  background-color: #ffeeba; }

.table-hover .table-warning:hover {
  background-color: #ffe8a1; }
  .table-hover .table-warning:hover > td,
  .table-hover .table-warning:hover > th {
    background-color: #ffe8a1; }

.table-danger,
.table-danger > th,
.table-danger > td {
  background-color: #f5c6cb; }

.table-hover .table-danger:hover {
  background-color: #f1b0b7; }
  .table-hover .table-danger:hover > td,
  .table-hover .table-danger:hover > th {
    background-color: #f1b0b7; }

.table-light,
.table-light > th,
.table-light > td {
  background-color: #fdfdfe; }

.table-hover .table-light:hover {
  background-color: #ececf6; }
  .table-hover .table-light:hover > td,
  .table-hover .table-light:hover > th {
    background-color: #ececf6; }

.table-dark,
.table-dark > th,
.table-dark > td {
  background-color: #c6c8ca; }

.table-hover .table-dark:hover {
  background-color: #b9bbbe; }
  .table-hover .table-dark:hover > td,
  .table-hover .table-dark:hover > th {
    background-color: #b9bbbe; }

.table-active,
.table-active > th,
.table-active > td {
  background-color: rgba(0, 0, 0, 0.075); }

.table-hover .table-active:hover {
  background-color: rgba(0, 0, 0, 0.075); }
  .table-hover .table-active:hover > td,
  .table-hover .table-active:hover > th {
    background-color: rgba(0, 0, 0, 0.075); }

.thead-inverse th {
  color: #fff;
  background-color: #212529; }

.thead-default th {
  color: #495057;
  background-color: #e9ecef; }

.table-inverse {
  color: #fff;
  background-color: #212529; }
  .table-inverse th,
  .table-inverse td,
  .table-inverse thead th {
    border-color: #32383e; }
  .table-inverse.table-bordered {
    border: 0; }
  .table-inverse.table-striped tbody tr:nth-of-type(odd) {
    background-color: rgba(255, 255, 255, 0.05); }
  .table-inverse.table-hover tbody tr:hover {
    background-color: rgba(255, 255, 255, 0.075); }

@media (max-width: 991px) {
  .table-responsive {
    display: block;
    width: 100%;
    overflow-x: auto;
    -ms-overflow-style: -ms-autohiding-scrollbar; }
    .table-responsive.table-bordered {
      border: 0; } }

.form-control {
  display: block;
  width: 100%;
  padding: 0.5rem 0.75rem;
  font-size: 1rem;
  line-height: 1.25;
  color: #495057;
  background-color: #fff;
  background-image: none;
  background-clip: padding-box;
  border: 1px solid rgba(0, 0, 0, 0.15);
  border-radius: 0.25rem;
  transition: border-color ease-in-out 0.15s, box-shadow ease-in-out 0.15s; }
  .form-control::-ms-expand {
    background-color: transparent;
    border: 0; }
  .form-control:focus {
    color: #495057;
    background-color: #fff;
    border-color: #80bdff;
    outline: none; }
  .form-control::-webkit-input-placeholder {
    color: #868e96;
    opacity: 1; }
  .form-control:-ms-input-placeholder {
    color: #868e96;
    opacity: 1; }
  .form-control::placeholder {
    color: #868e96;
    opacity: 1; }
  .form-control:disabled, .form-control[readonly] {
    background-color: #e9ecef;
    opacity: 1; }

select.form-control:not([size]):not([multiple]) {
  height: calc(2.25rem + 2px); }

select.form-control:focus::-ms-value {
  color: #495057;
  background-color: #fff; }

.form-control-file,
.form-control-range {
  display: block; }

.col-form-label {
  padding-top: calc(0.5rem - 1px * 2);
  padding-bottom: calc(0.5rem - 1px * 2);
  margin-bottom: 0; }

.col-form-label-lg {
  padding-top: calc(0.5rem - 1px * 2);
  padding-bottom: calc(0.5rem - 1px * 2);
  font-size: 1.25rem; }

.col-form-label-sm {
  padding-top: calc(0.25rem - 1px * 2);
  padding-bottom: calc(0.25rem - 1px * 2);
  font-size: 0.875rem; }

.col-form-legend {
  padding-top: 0.5rem;
  padding-bottom: 0.5rem;
  margin-bottom: 0;
  font-size: 1rem; }

.form-control-plaintext {
  padding-top: 0.5rem;
  padding-bottom: 0.5rem;
  margin-bottom: 0;
  line-height: 1.25;
  border: solid transparent;
  border-width: 1px 0; }
  .form-control-plaintext.form-control-sm, .input-group-sm > .form-control-plaintext.form-control,
  .input-group-sm > .form-control-plaintext.input-group-addon,
  .input-group-sm > .input-group-btn > .form-control-plaintext.btn,
  .input-group-sm > .input-group-btn > button.form-control-plaintext.custom, .form-control-plaintext.form-control-lg, .input-group-lg > .form-control-plaintext.form-control,
  .input-group-lg > .form-control-plaintext.input-group-addon,
  .input-group-lg > .input-group-btn > .form-control-plaintext.btn,
  .input-group-lg > .input-group-btn > button.form-control-plaintext.custom {
    padding-right: 0;
    padding-left: 0; }

.form-control-sm, .input-group-sm > .form-control,
.input-group-sm > .input-group-addon,
.input-group-sm > .input-group-btn > .btn,
.input-group-sm > .input-group-btn > button.custom {
  padding: 0.25rem 0.5rem;
  font-size: 0.875rem;
  line-height: 1.5;
  border-radius: 0.2rem; }

select.form-control-sm:not([size]):not([multiple]), .input-group-sm > select.form-control:not([size]):not([multiple]),
.input-group-sm > select.input-group-addon:not([size]):not([multiple]),
.input-group-sm > .input-group-btn > select.btn:not([size]):not([multiple]) {
  height: calc(1.8125rem + 2px); }

.form-control-lg, .input-group-lg > .form-control,
.input-group-lg > .input-group-addon,
.input-group-lg > .input-group-btn > .btn,
.input-group-lg > .input-group-btn > button.custom {
  padding: 0.5rem 1rem;
  font-size: 1.25rem;
  line-height: 1.5;
  border-radius: 0.3rem; }

select.form-control-lg:not([size]):not([multiple]), .input-group-lg > select.form-control:not([size]):not([multiple]),
.input-group-lg > select.input-group-addon:not([size]):not([multiple]),
.input-group-lg > .input-group-btn > select.btn:not([size]):not([multiple]) {
  height: calc(2.875rem + 2px); }

.form-group {
  margin-bottom: 1rem; }

.form-text {
  display: block;
  margin-top: 0.25rem; }

.form-row {
  display: -webkit-flex;
  display: -ms-flexbox;
  display: flex;
  -webkit-flex-wrap: wrap;
      -ms-flex-wrap: wrap;
          flex-wrap: wrap;
  margin-right: -5px;
  margin-left: -5px; }
  .form-row > .col,
  .form-row > [class*="col-"] {
    padding-right: 5px;
    padding-left: 5px; }

.form-check {
  position: relative;
  display: block;
  margin-bottom: 0.5rem; }
  .form-check.disabled .form-check-label {
    color: #868e96; }

.form-check-label {
  padding-left: 1.25rem;
  margin-bottom: 0; }

.form-check-input {
  position: absolute;
  margin-top: 0.25rem;
  margin-left: -1.25rem; }

.form-check-inline {
  display: inline-block; }
  .form-check-inline .form-check-label {
    vertical-align: middle; }
  .form-check-inline + .form-check-inline {
    margin-left: 0.75rem; }

.invalid-feedback {
  display: none;
  margin-top: .25rem;
  font-size: .875rem;
  color: #dc3545; }

.invalid-tooltip {
  position: absolute;
  top: 100%;
  z-index: 5;
  display: none;
  width: 250px;
  padding: .5rem;
  margin-top: .1rem;
  font-size: .875rem;
  line-height: 1;
  color: #fff;
  background-color: rgba(220, 53, 69, 0.8);
  border-radius: .2rem; }

.was-validated .form-control:valid, .form-control.is-valid, .was-validated
.custom-select:valid,
.custom-select.is-valid {
  border-color: #28a745; }
  .was-validated .form-control:valid:focus, .form-control.is-valid:focus, .was-validated
  .custom-select:valid:focus,
  .custom-select.is-valid:focus {
    box-shadow: 0 0 0 0.2rem rgba(40, 167, 69, 0.25); }
  .was-validated .form-control:valid ~ .invalid-feedback,
  .was-validated .form-control:valid ~ .invalid-tooltip, .form-control.is-valid ~ .invalid-feedback,
  .form-control.is-valid ~ .invalid-tooltip, .was-validated
  .custom-select:valid ~ .invalid-feedback,
  .was-validated
  .custom-select:valid ~ .invalid-tooltip,
  .custom-select.is-valid ~ .invalid-feedback,
  .custom-select.is-valid ~ .invalid-tooltip {
    display: block; }

.was-validated .form-check-input:valid + .form-check-label, .form-check-input.is-valid + .form-check-label {
  color: #28a745; }

.was-validated .custom-control-input:valid ~ .custom-control-indicator, .custom-control-input.is-valid ~ .custom-control-indicator {
  background-color: rgba(40, 167, 69, 0.25); }

.was-validated .custom-control-input:valid ~ .custom-control-description, .custom-control-input.is-valid ~ .custom-control-description {
  color: #28a745; }

.was-validated .custom-file-input:valid ~ .custom-file-control, .custom-file-input.is-valid ~ .custom-file-control {
  border-color: #28a745; }
  .was-validated .custom-file-input:valid ~ .custom-file-control::before, .custom-file-input.is-valid ~ .custom-file-control::before {
    border-color: inherit; }

.was-validated .custom-file-input:valid:focus, .custom-file-input.is-valid:focus {
  box-shadow: 0 0 0 0.2rem rgba(40, 167, 69, 0.25); }

.was-validated .form-control:invalid, .form-control.is-invalid, .was-validated
.custom-select:invalid,
.custom-select.is-invalid {
  border-color: #dc3545; }
  .was-validated .form-control:invalid:focus, .form-control.is-invalid:focus, .was-validated
  .custom-select:invalid:focus,
  .custom-select.is-invalid:focus {
    box-shadow: 0 0 0 0.2rem rgba(220, 53, 69, 0.25); }
  .was-validated .form-control:invalid ~ .invalid-feedback,
  .was-validated .form-control:invalid ~ .invalid-tooltip, .form-control.is-invalid ~ .invalid-feedback,
  .form-control.is-invalid ~ .invalid-tooltip, .was-validated
  .custom-select:invalid ~ .invalid-feedback,
  .was-validated
  .custom-select:invalid ~ .invalid-tooltip,
  .custom-select.is-invalid ~ .invalid-feedback,
  .custom-select.is-invalid ~ .invalid-tooltip {
    display: block; }

.was-validated .form-check-input:invalid + .form-check-label, .form-check-input.is-invalid + .form-check-label {
  color: #dc3545; }

.was-validated .custom-control-input:invalid ~ .custom-control-indicator, .custom-control-input.is-invalid ~ .custom-control-indicator {
  background-color: rgba(220, 53, 69, 0.25); }

.was-validated .custom-control-input:invalid ~ .custom-control-description, .custom-control-input.is-invalid ~ .custom-control-description {
  color: #dc3545; }

.was-validated .custom-file-input:invalid ~ .custom-file-control, .custom-file-input.is-invalid ~ .custom-file-control {
  border-color: #dc3545; }
  .was-validated .custom-file-input:invalid ~ .custom-file-control::before, .custom-file-input.is-invalid ~ .custom-file-control::before {
    border-color: inherit; }

.was-validated .custom-file-input:invalid:focus, .custom-file-input.is-invalid:focus {
  box-shadow: 0 0 0 0.2rem rgba(220, 53, 69, 0.25); }

.form-inline {
  display: -webkit-flex;
  display: -ms-flexbox;
  display: flex;
  -webkit-flex-flow: row wrap;
      -ms-flex-flow: row wrap;
          flex-flow: row wrap;
  -webkit-align-items: center;
      -ms-flex-align: center;
          align-items: center; }
  .form-inline .form-check {
    width: 100%; }
  @media (min-width: 576px) {
    .form-inline label {
      display: -webkit-flex;
      display: -ms-flexbox;
      display: flex;
      -webkit-align-items: center;
          -ms-flex-align: center;
              align-items: center;
      -webkit-justify-content: center;
          -ms-flex-pack: center;
              justify-content: center;
      margin-bottom: 0; }
    .form-inline .form-group {
      display: -webkit-flex;
      display: -ms-flexbox;
      display: flex;
      -webkit-flex: 0 0 auto;
          -ms-flex: 0 0 auto;
              flex: 0 0 auto;
      -webkit-flex-flow: row wrap;
          -ms-flex-flow: row wrap;
              flex-flow: row wrap;
      -webkit-align-items: center;
          -ms-flex-align: center;
              align-items: center;
      margin-bottom: 0; }
    .form-inline .form-control {
      display: inline-block;
      width: auto;
      vertical-align: middle; }
    .form-inline .form-control-plaintext {
      display: inline-block; }
    .form-inline .input-group {
      width: auto; }
    .form-inline .form-control-label {
      margin-bottom: 0;
      vertical-align: middle; }
    .form-inline .form-check {
      display: -webkit-flex;
      display: -ms-flexbox;
      display: flex;
      -webkit-align-items: center;
          -ms-flex-align: center;
              align-items: center;
      -webkit-justify-content: center;
          -ms-flex-pack: center;
              justify-content: center;
      width: auto;
      margin-top: 0;
      margin-bottom: 0; }
    .form-inline .form-check-label {
      padding-left: 0; }
    .form-inline .form-check-input {
      position: relative;
      margin-top: 0;
      margin-right: 0.25rem;
      margin-left: 0; }
    .form-inline .custom-control {
      display: -webkit-flex;
      display: -ms-flexbox;
      display: flex;
      -webkit-align-items: center;
          -ms-flex-align: center;
              align-items: center;
      -webkit-justify-content: center;
          -ms-flex-pack: center;
              justify-content: center;
      padding-left: 0; }
    .form-inline .custom-control-indicator {
      position: static;
      display: inline-block;
      margin-right: 0.25rem;
      vertical-align: text-bottom; }
    .form-inline .has-feedback .form-control-feedback {
      top: 0; } }

.btn, button.custom {
  display: inline-block;
  font-weight: normal;
  text-align: center;
  white-space: nowrap;
  vertical-align: middle;
  -webkit-user-select: none;
     -moz-user-select: none;
      -ms-user-select: none;
          user-select: none;
  border: 1px solid transparent;
  padding: 0.5rem 0.75rem;
  font-size: 1rem;
  line-height: 1.25;
  border-radius: 0.25rem;
  transition: background-color 0.15s ease-in-out, border-color 0.15s ease-in-out, box-shadow 0.15s ease-in-out; }
  .btn:focus, button.custom:focus, .btn:hover, button.custom:hover {
    text-decoration: none; }
  .btn:focus, button.custom:focus, .btn.focus, button.focus.custom {
    outline: 0;
    box-shadow: 0 0 0 3px rgba(0, 123, 255, 0.25); }
  .btn.disabled, button.disabled.custom, .btn:disabled, button.custom:disabled {
    opacity: .65; }
  .btn:active, button.custom:active, .btn.active, button.active.custom {
    background-image: none; }

a.btn.disabled,
fieldset[disabled] a.btn {
  pointer-events: none; }

.btn-primary {
  color: #fff;
  background-color: #007bff;
  border-color: #007bff; }
  .btn-primary:hover {
    color: #fff;
    background-color: #0069d9;
    border-color: #0062cc; }
  .btn-primary:focus, .btn-primary.focus {
    box-shadow: 0 0 0 3px rgba(0, 123, 255, 0.5); }
  .btn-primary.disabled, .btn-primary:disabled {
    background-color: #007bff;
    border-color: #007bff; }
  .btn-primary:active, .btn-primary.active,
  .show > .btn-primary.dropdown-toggle {
    background-color: #0069d9;
    background-image: none;
    border-color: #0062cc; }

.btn-secondary {
  color: #fff;
  background-color: #868e96;
  border-color: #868e96; }
  .btn-secondary:hover {
    color: #fff;
    background-color: #727b84;
    border-color: #6c757d; }
  .btn-secondary:focus, .btn-secondary.focus {
    box-shadow: 0 0 0 3px rgba(134, 142, 150, 0.5); }
  .btn-secondary.disabled, .btn-secondary:disabled {
    background-color: #868e96;
    border-color: #868e96; }
  .btn-secondary:active, .btn-secondary.active,
  .show > .btn-secondary.dropdown-toggle {
    background-color: #727b84;
    background-image: none;
    border-color: #6c757d; }

.btn-success {
  color: #fff;
  background-color: #28a745;
  border-color: #28a745; }
  .btn-success:hover {
    color: #fff;
    background-color: #218838;
    border-color: #1e7e34; }
  .btn-success:focus, .btn-success.focus {
    box-shadow: 0 0 0 3px rgba(40, 167, 69, 0.5); }
  .btn-success.disabled, .btn-success:disabled {
    background-color: #28a745;
    border-color: #28a745; }
  .btn-success:active, .btn-success.active,
  .show > .btn-success.dropdown-toggle {
    background-color: #218838;
    background-image: none;
    border-color: #1e7e34; }

.btn-info {
  color: #fff;
  background-color: #17a2b8;
  border-color: #17a2b8; }
  .btn-info:hover {
    color: #fff;
    background-color: #138496;
    border-color: #117a8b; }
  .btn-info:focus, .btn-info.focus {
    box-shadow: 0 0 0 3px rgba(23, 162, 184, 0.5); }
  .btn-info.disabled, .btn-info:disabled {
    background-color: #17a2b8;
    border-color: #17a2b8; }
  .btn-info:active, .btn-info.active,
  .show > .btn-info.dropdown-toggle {
    background-color: #138496;
    background-image: none;
    border-color: #117a8b; }

.btn-warning {
  color: #111;
  background-color: #ffc107;
  border-color: #ffc107; }
  .btn-warning:hover {
    color: #111;
    background-color: #e0a800;
    border-color: #d39e00; }
  .btn-warning:focus, .btn-warning.focus {
    box-shadow: 0 0 0 3px rgba(255, 193, 7, 0.5); }
  .btn-warning.disabled, .btn-warning:disabled {
    background-color: #ffc107;
    border-color: #ffc107; }
  .btn-warning:active, .btn-warning.active,
  .show > .btn-warning.dropdown-toggle {
    background-color: #e0a800;
    background-image: none;
    border-color: #d39e00; }

.btn-danger {
  color: #fff;
  background-color: #dc3545;
  border-color: #dc3545; }
  .btn-danger:hover {
    color: #fff;
    background-color: #c82333;
    border-color: #bd2130; }
  .btn-danger:focus, .btn-danger.focus {
    box-shadow: 0 0 0 3px rgba(220, 53, 69, 0.5); }
  .btn-danger.disabled, .btn-danger:disabled {
    background-color: #dc3545;
    border-color: #dc3545; }
  .btn-danger:active, .btn-danger.active,
  .show > .btn-danger.dropdown-toggle {
    background-color: #c82333;
    background-image: none;
    border-color: #bd2130; }

.btn-light {
  color: #111;
  background-color: #f8f9fa;
  border-color: #f8f9fa; }
  .btn-light:hover {
    color: #111;
    background-color: #e2e6ea;
    border-color: #dae0e5; }
  .btn-light:focus, .btn-light.focus {
    box-shadow: 0 0 0 3px rgba(248, 249, 250, 0.5); }
  .btn-light.disabled, .btn-light:disabled {
    background-color: #f8f9fa;
    border-color: #f8f9fa; }
  .btn-light:active, .btn-light.active,
  .show > .btn-light.dropdown-toggle {
    background-color: #e2e6ea;
    background-image: none;
    border-color: #dae0e5; }

.btn-dark {
  color: #fff;
  background-color: #343a40;
  border-color: #343a40; }
  .btn-dark:hover {
    color: #fff;
    background-color: #23272b;
    border-color: #1d2124; }
  .btn-dark:focus, .btn-dark.focus {
    box-shadow: 0 0 0 3px rgba(52, 58, 64, 0.5); }
  .btn-dark.disabled, .btn-dark:disabled {
    background-color: #343a40;
    border-color: #343a40; }
  .btn-dark:active, .btn-dark.active,
  .show > .btn-dark.dropdown-toggle {
    background-color: #23272b;
    background-image: none;
    border-color: #1d2124; }

.btn-outline-primary {
  color: #007bff;
  background-color: transparent;
  background-image: none;
  border-color: #007bff; }
  .btn-outline-primary:hover {
    color: #fff;
    background-color: #007bff;
    border-color: #007bff; }
  .btn-outline-primary:focus, .btn-outline-primary.focus {
    box-shadow: 0 0 0 3px rgba(0, 123, 255, 0.5); }
  .btn-outline-primary.disabled, .btn-outline-primary:disabled {
    color: #007bff;
    background-color: transparent; }
  .btn-outline-primary:active, .btn-outline-primary.active,
  .show > .btn-outline-primary.dropdown-toggle {
    color: #fff;
    background-color: #007bff;
    border-color: #007bff; }

.btn-outline-secondary {
  color: #868e96;
  background-color: transparent;
  background-image: none;
  border-color: #868e96; }
  .btn-outline-secondary:hover {
    color: #fff;
    background-color: #868e96;
    border-color: #868e96; }
  .btn-outline-secondary:focus, .btn-outline-secondary.focus {
    box-shadow: 0 0 0 3px rgba(134, 142, 150, 0.5); }
  .btn-outline-secondary.disabled, .btn-outline-secondary:disabled {
    color: #868e96;
    background-color: transparent; }
  .btn-outline-secondary:active, .btn-outline-secondary.active,
  .show > .btn-outline-secondary.dropdown-toggle {
    color: #fff;
    background-color: #868e96;
    border-color: #868e96; }

.btn-outline-success {
  color: #28a745;
  background-color: transparent;
  background-image: none;
  border-color: #28a745; }
  .btn-outline-success:hover {
    color: #fff;
    background-color: #28a745;
    border-color: #28a745; }
  .btn-outline-success:focus, .btn-outline-success.focus {
    box-shadow: 0 0 0 3px rgba(40, 167, 69, 0.5); }
  .btn-outline-success.disabled, .btn-outline-success:disabled {
    color: #28a745;
    background-color: transparent; }
  .btn-outline-success:active, .btn-outline-success.active,
  .show > .btn-outline-success.dropdown-toggle {
    color: #fff;
    background-color: #28a745;
    border-color: #28a745; }

.btn-outline-info {
  color: #17a2b8;
  background-color: transparent;
  background-image: none;
  border-color: #17a2b8; }
  .btn-outline-info:hover {
    color: #fff;
    background-color: #17a2b8;
    border-color: #17a2b8; }
  .btn-outline-info:focus, .btn-outline-info.focus {
    box-shadow: 0 0 0 3px rgba(23, 162, 184, 0.5); }
  .btn-outline-info.disabled, .btn-outline-info:disabled {
    color: #17a2b8;
    background-color: transparent; }
  .btn-outline-info:active, .btn-outline-info.active,
  .show > .btn-outline-info.dropdown-toggle {
    color: #fff;
    background-color: #17a2b8;
    border-color: #17a2b8; }

.btn-outline-warning {
  color: #ffc107;
  background-color: transparent;
  background-image: none;
  border-color: #ffc107; }
  .btn-outline-warning:hover {
    color: #fff;
    background-color: #ffc107;
    border-color: #ffc107; }
  .btn-outline-warning:focus, .btn-outline-warning.focus {
    box-shadow: 0 0 0 3px rgba(255, 193, 7, 0.5); }
  .btn-outline-warning.disabled, .btn-outline-warning:disabled {
    color: #ffc107;
    background-color: transparent; }
  .btn-outline-warning:active, .btn-outline-warning.active,
  .show > .btn-outline-warning.dropdown-toggle {
    color: #fff;
    background-color: #ffc107;
    border-color: #ffc107; }

.btn-outline-danger {
  color: #dc3545;
  background-color: transparent;
  background-image: none;
  border-color: #dc3545; }
  .btn-outline-danger:hover {
    color: #fff;
    background-color: #dc3545;
    border-color: #dc3545; }
  .btn-outline-danger:focus, .btn-outline-danger.focus {
    box-shadow: 0 0 0 3px rgba(220, 53, 69, 0.5); }
  .btn-outline-danger.disabled, .btn-outline-danger:disabled {
    color: #dc3545;
    background-color: transparent; }
  .btn-outline-danger:active, .btn-outline-danger.active,
  .show > .btn-outline-danger.dropdown-toggle {
    color: #fff;
    background-color: #dc3545;
    border-color: #dc3545; }

.btn-outline-light {
  color: #f8f9fa;
  background-color: transparent;
  background-image: none;
  border-color: #f8f9fa; }
  .btn-outline-light:hover {
    color: #fff;
    background-color: #f8f9fa;
    border-color: #f8f9fa; }
  .btn-outline-light:focus, .btn-outline-light.focus {
    box-shadow: 0 0 0 3px rgba(248, 249, 250, 0.5); }
  .btn-outline-light.disabled, .btn-outline-light:disabled {
    color: #f8f9fa;
    background-color: transparent; }
  .btn-outline-light:active, .btn-outline-light.active,
  .show > .btn-outline-light.dropdown-toggle {
    color: #fff;
    background-color: #f8f9fa;
    border-color: #f8f9fa; }

.btn-outline-dark {
  color: #343a40;
  background-color: transparent;
  background-image: none;
  border-color: #343a40; }
  .btn-outline-dark:hover {
    color: #fff;
    background-color: #343a40;
    border-color: #343a40; }
  .btn-outline-dark:focus, .btn-outline-dark.focus {
    box-shadow: 0 0 0 3px rgba(52, 58, 64, 0.5); }
  .btn-outline-dark.disabled, .btn-outline-dark:disabled {
    color: #343a40;
    background-color: transparent; }
  .btn-outline-dark:active, .btn-outline-dark.active,
  .show > .btn-outline-dark.dropdown-toggle {
    color: #fff;
    background-color: #343a40;
    border-color: #343a40; }

.btn-link {
  font-weight: normal;
  color: #007bff;
  border-radius: 0; }
  .btn-link, .btn-link:active, .btn-link.active, .btn-link:disabled {
    background-color: transparent; }
  .btn-link, .btn-link:focus, .btn-link:active {
    border-color: transparent;
    box-shadow: none; }
  .btn-link:hover {
    border-color: transparent; }
  .btn-link:focus, .btn-link:hover {
    color: #0056b3;
    text-decoration: underline;
    background-color: transparent; }
  .btn-link:disabled {
    color: #868e96; }
    .btn-link:disabled:focus, .btn-link:disabled:hover {
      text-decoration: none; }

.btn-lg, .btn-group-lg > .btn, .btn-group-lg > button.custom {
  padding: 0.5rem 1rem;
  font-size: 1.25rem;
  line-height: 1.5;
  border-radius: 0.3rem; }

.btn-sm, .btn-group-sm > .btn, .btn-group-sm > button.custom {
  padding: 0.25rem 0.5rem;
  font-size: 0.875rem;
  line-height: 1.5;
  border-radius: 0.2rem; }

.btn-block {
  display: block;
  width: 100%; }

.btn-block + .btn-block {
  margin-top: 0.5rem; }

input[type="submit"].btn-block,
input[type="reset"].btn-block,
input[type="button"].btn-block {
  width: 100%; }

.fade {
  opacity: 0;
  transition: opacity 0.15s linear; }
  .fade.show {
    opacity: 1; }

.collapse {
  display: none; }
  .collapse.show {
    display: block; }

tr.collapse.show {
  display: table-row; }

tbody.collapse.show {
  display: table-row-group; }

.collapsing {
  position: relative;
  height: 0;
  overflow: hidden;
  transition: height 0.35s ease; }

.dropup,
.dropdown {
  position: relative; }

.dropdown-toggle::after {
  display: inline-block;
  width: 0;
  height: 0;
  margin-left: 0.255em;
  vertical-align: 0.255em;
  content: "";
  border-top: 0.3em solid;
  border-right: 0.3em solid transparent;
  border-left: 0.3em solid transparent; }

.dropdown-toggle:empty::after {
  margin-left: 0; }

.dropup .dropdown-menu {
  margin-top: 0;
  margin-bottom: 0.125rem; }

.dropup .dropdown-toggle::after {
  border-top: 0;
  border-bottom: 0.3em solid; }

.dropdown-menu {
  position: absolute;
  top: 100%;
  left: 0;
  z-index: 1000;
  display: none;
  float: left;
  min-width: 10rem;
  padding: 0.5rem 0;
  margin: 0.125rem 0 0;
  font-size: 1rem;
  color: #212529;
  text-align: left;
  list-style: none;
  background-color: #fff;
  background-clip: padding-box;
  border: 1px solid rgba(0, 0, 0, 0.15);
  border-radius: 0.25rem; }

.dropdown-divider {
  height: 0;
  margin: 0.5rem 0;
  overflow: hidden;
  border-top: 1px solid #e9ecef; }

.dropdown-item {
  display: block;
  width: 100%;
  padding: 0.25rem 1.5rem;
  clear: both;
  font-weight: normal;
  color: #212529;
  text-align: inherit;
  white-space: nowrap;
  background: none;
  border: 0; }
  .dropdown-item:focus, .dropdown-item:hover {
    color: #16181b;
    text-decoration: none;
    background-color: #f8f9fa; }
  .dropdown-item.active, .dropdown-item:active {
    color: #fff;
    text-decoration: none;
    background-color: #007bff; }
  .dropdown-item.disabled, .dropdown-item:disabled {
    color: #868e96;
    background-color: transparent; }

.show > a {
  outline: 0; }

.dropdown-menu.show {
  display: block; }

.dropdown-header {
  display: block;
  padding: 0.5rem 1.5rem;
  margin-bottom: 0;
  font-size: 0.875rem;
  color: #868e96;
  white-space: nowrap; }

.btn-group,
.btn-group-vertical {
  position: relative;
  display: -webkit-inline-flex;
  display: -ms-inline-flexbox;
  display: inline-flex;
  vertical-align: middle; }
  .btn-group > .btn, .btn-group > button.custom,
  .btn-group-vertical > .btn,
  .btn-group-vertical > button.custom {
    position: relative;
    -webkit-flex: 0 1 auto;
        -ms-flex: 0 1 auto;
            flex: 0 1 auto;
    margin-bottom: 0; }
    .btn-group > .btn:hover, .btn-group > button.custom:hover,
    .btn-group-vertical > .btn:hover,
    .btn-group-vertical > button.custom:hover {
      z-index: 2; }
    .btn-group > .btn:focus, .btn-group > button.custom:focus, .btn-group > .btn:active, .btn-group > button.custom:active, .btn-group > .btn.active, .btn-group > button.active.custom,
    .btn-group-vertical > .btn:focus,
    .btn-group-vertical > button.custom:focus,
    .btn-group-vertical > .btn:active,
    .btn-group-vertical > button.custom:active,
    .btn-group-vertical > .btn.active,
    .btn-group-vertical > button.active.custom {
      z-index: 2; }
  .btn-group .btn + .btn, .btn-group button.custom + .btn, .btn-group .btn + button.custom, .btn-group button.custom + button.custom,
  .btn-group .btn + .btn-group,
  .btn-group button.custom + .btn-group,
  .btn-group .btn-group + .btn,
  .btn-group .btn-group + button.custom,
  .btn-group .btn-group + .btn-group,
  .btn-group-vertical .btn + .btn,
  .btn-group-vertical button.custom + .btn,
  .btn-group-vertical .btn + button.custom,
  .btn-group-vertical button.custom + button.custom,
  .btn-group-vertical .btn + .btn-group,
  .btn-group-vertical button.custom + .btn-group,
  .btn-group-vertical .btn-group + .btn,
  .btn-group-vertical .btn-group + button.custom,
  .btn-group-vertical .btn-group + .btn-group {
    margin-left: -1px; }

.btn-toolbar {
  display: -webkit-flex;
  display: -ms-flexbox;
  display: flex;
  -webkit-flex-wrap: wrap;
      -ms-flex-wrap: wrap;
          flex-wrap: wrap;
  -webkit-justify-content: flex-start;
      -ms-flex-pack: start;
          justify-content: flex-start; }
  .btn-toolbar .input-group {
    width: auto; }

.btn-group > .btn:not(:first-child):not(:last-child):not(.dropdown-toggle), .btn-group > button.custom:not(:first-child):not(:last-child):not(.dropdown-toggle) {
  border-radius: 0; }

.btn-group > .btn:first-child, .btn-group > button.custom:first-child {
  margin-left: 0; }
  .btn-group > .btn:first-child:not(:last-child):not(.dropdown-toggle), .btn-group > button.custom:first-child:not(:last-child):not(.dropdown-toggle) {
    border-top-right-radius: 0;
    border-bottom-right-radius: 0; }

.btn-group > .btn:last-child:not(:first-child), .btn-group > button.custom:last-child:not(:first-child),
.btn-group > .dropdown-toggle:not(:first-child) {
  border-top-left-radius: 0;
  border-bottom-left-radius: 0; }

.btn-group > .btn-group {
  float: left; }

.btn-group > .btn-group:not(:first-child):not(:last-child) > .btn, .btn-group > .btn-group:not(:first-child):not(:last-child) > button.custom {
  border-radius: 0; }

.btn-group > .btn-group:first-child:not(:last-child) > .btn:last-child, .btn-group > .btn-group:first-child:not(:last-child) > button.custom:last-child,
.btn-group > .btn-group:first-child:not(:last-child) > .dropdown-toggle {
  border-top-right-radius: 0;
  border-bottom-right-radius: 0; }

.btn-group > .btn-group:last-child:not(:first-child) > .btn:first-child, .btn-group > .btn-group:last-child:not(:first-child) > button.custom:first-child {
  border-top-left-radius: 0;
  border-bottom-left-radius: 0; }

.btn + .dropdown-toggle-split, button.custom + .dropdown-toggle-split {
  padding-right: 0.5625rem;
  padding-left: 0.5625rem; }
  .btn + .dropdown-toggle-split::after, button.custom + .dropdown-toggle-split::after {
    margin-left: 0; }

.btn-sm + .dropdown-toggle-split, .btn-group-sm > .btn + .dropdown-toggle-split, .btn-group-sm > button.custom + .dropdown-toggle-split {
  padding-right: 0.375rem;
  padding-left: 0.375rem; }

.btn-lg + .dropdown-toggle-split, .btn-group-lg > .btn + .dropdown-toggle-split, .btn-group-lg > button.custom + .dropdown-toggle-split {
  padding-right: 0.75rem;
  padding-left: 0.75rem; }

.btn-group-vertical {
  display: -webkit-inline-flex;
  display: -ms-inline-flexbox;
  display: inline-flex;
  -webkit-flex-direction: column;
      -ms-flex-direction: column;
          flex-direction: column;
  -webkit-align-items: flex-start;
      -ms-flex-align: start;
          align-items: flex-start;
  -webkit-justify-content: center;
      -ms-flex-pack: center;
          justify-content: center; }
  .btn-group-vertical .btn, .btn-group-vertical button.custom,
  .btn-group-vertical .btn-group {
    width: 100%; }
  .btn-group-vertical > .btn + .btn, .btn-group-vertical > button.custom + .btn, .btn-group-vertical > .btn + button.custom, .btn-group-vertical > button.custom + button.custom,
  .btn-group-vertical > .btn + .btn-group,
  .btn-group-vertical > button.custom + .btn-group,
  .btn-group-vertical > .btn-group + .btn,
  .btn-group-vertical > .btn-group + button.custom,
  .btn-group-vertical > .btn-group + .btn-group {
    margin-top: -1px;
    margin-left: 0; }

.btn-group-vertical > .btn:not(:first-child):not(:last-child), .btn-group-vertical > button.custom:not(:first-child):not(:last-child) {
  border-radius: 0; }

.btn-group-vertical > .btn:first-child:not(:last-child), .btn-group-vertical > button.custom:first-child:not(:last-child) {
  border-bottom-right-radius: 0;
  border-bottom-left-radius: 0; }

.btn-group-vertical > .btn:last-child:not(:first-child), .btn-group-vertical > button.custom:last-child:not(:first-child) {
  border-top-left-radius: 0;
  border-top-right-radius: 0; }

.btn-group-vertical > .btn-group:not(:first-child):not(:last-child) > .btn, .btn-group-vertical > .btn-group:not(:first-child):not(:last-child) > button.custom {
  border-radius: 0; }

.btn-group-vertical > .btn-group:first-child:not(:last-child) > .btn:last-child, .btn-group-vertical > .btn-group:first-child:not(:last-child) > button.custom:last-child,
.btn-group-vertical > .btn-group:first-child:not(:last-child) > .dropdown-toggle {
  border-bottom-right-radius: 0;
  border-bottom-left-radius: 0; }

.btn-group-vertical > .btn-group:last-child:not(:first-child) > .btn:first-child, .btn-group-vertical > .btn-group:last-child:not(:first-child) > button.custom:first-child {
  border-top-left-radius: 0;
  border-top-right-radius: 0; }

[data-toggle="buttons"] > .btn input[type="radio"], [data-toggle="buttons"] > button.custom input[type="radio"],
[data-toggle="buttons"] > .btn input[type="checkbox"],
[data-toggle="buttons"] > button.custom input[type="checkbox"],
[data-toggle="buttons"] > .btn-group > .btn input[type="radio"],
[data-toggle="buttons"] > .btn-group > button.custom input[type="radio"],
[data-toggle="buttons"] > .btn-group > .btn input[type="checkbox"],
[data-toggle="buttons"] > .btn-group > button.custom input[type="checkbox"] {
  position: absolute;
  clip: rect(0, 0, 0, 0);
  pointer-events: none; }

.input-group {
  position: relative;
  display: -webkit-flex;
  display: -ms-flexbox;
  display: flex;
  width: 100%; }
  .input-group .form-control {
    position: relative;
    z-index: 2;
    -webkit-flex: 1 1 auto;
        -ms-flex: 1 1 auto;
            flex: 1 1 auto;
    width: 1%;
    margin-bottom: 0; }
    .input-group .form-control:focus, .input-group .form-control:active, .input-group .form-control:hover {
      z-index: 3; }

.input-group-addon,
.input-group-btn,
.input-group .form-control {
  display: -webkit-flex;
  display: -ms-flexbox;
  display: flex;
  -webkit-align-items: center;
      -ms-flex-align: center;
          align-items: center; }
  .input-group-addon:not(:first-child):not(:last-child),
  .input-group-btn:not(:first-child):not(:last-child),
  .input-group .form-control:not(:first-child):not(:last-child) {
    border-radius: 0; }

.input-group-addon,
.input-group-btn {
  white-space: nowrap;
  vertical-align: middle; }

.input-group-addon {
  padding: 0.5rem 0.75rem;
  margin-bottom: 0;
  font-size: 1rem;
  font-weight: normal;
  line-height: 1.25;
  color: #495057;
  text-align: center;
  background-color: #e9ecef;
  background-clip: padding-box;
  border: 1px solid rgba(0, 0, 0, 0.15);
  border-radius: 0.25rem; }
  .input-group-addon.form-control-sm,
  .input-group-sm > .input-group-addon,
  .input-group-sm > .input-group-btn > .input-group-addon.btn,
  .input-group-sm > .input-group-btn > button.input-group-addon.custom {
    padding: 0.25rem 0.5rem;
    font-size: 0.875rem;
    border-radius: 0.2rem; }
  .input-group-addon.form-control-lg,
  .input-group-lg > .input-group-addon,
  .input-group-lg > .input-group-btn > .input-group-addon.btn,
  .input-group-lg > .input-group-btn > button.input-group-addon.custom {
    padding: 0.5rem 1rem;
    font-size: 1.25rem;
    border-radius: 0.3rem; }
  .input-group-addon input[type="radio"],
  .input-group-addon input[type="checkbox"] {
    margin-top: 0; }

.input-group .form-control:not(:last-child),
.input-group-addon:not(:last-child),
.input-group-btn:not(:last-child) > .btn,
.input-group-btn:not(:last-child) > button.custom,
.input-group-btn:not(:last-child) > .btn-group > .btn,
.input-group-btn:not(:last-child) > .btn-group > button.custom,
.input-group-btn:not(:last-child) > .dropdown-toggle,
.input-group-btn:not(:first-child) > .btn:not(:last-child):not(.dropdown-toggle),
.input-group-btn:not(:first-child) > button.custom:not(:last-child):not(.dropdown-toggle),
.input-group-btn:not(:first-child) > .btn-group:not(:last-child) > .btn,
.input-group-btn:not(:first-child) > .btn-group:not(:last-child) > button.custom {
  border-top-right-radius: 0;
  border-bottom-right-radius: 0; }

.input-group-addon:not(:last-child) {
  border-right: 0; }

.input-group .form-control:not(:first-child),
.input-group-addon:not(:first-child),
.input-group-btn:not(:first-child) > .btn,
.input-group-btn:not(:first-child) > button.custom,
.input-group-btn:not(:first-child) > .btn-group > .btn,
.input-group-btn:not(:first-child) > .btn-group > button.custom,
.input-group-btn:not(:first-child) > .dropdown-toggle,
.input-group-btn:not(:last-child) > .btn:not(:first-child),
.input-group-btn:not(:last-child) > button.custom:not(:first-child),
.input-group-btn:not(:last-child) > .btn-group:not(:first-child) > .btn,
.input-group-btn:not(:last-child) > .btn-group:not(:first-child) > button.custom {
  border-top-left-radius: 0;
  border-bottom-left-radius: 0; }

.form-control + .input-group-addon:not(:first-child) {
  border-left: 0; }

.input-group-btn {
  position: relative;
  font-size: 0;
  white-space: nowrap; }
  .input-group-btn > .btn, .input-group-btn > button.custom {
    position: relative;
    background-clip: padding-box;
    border: 1px solid rgba(0, 0, 0, 0.15); }
    .input-group-btn > .btn + .btn, .input-group-btn > button.custom + .btn, .input-group-btn > .btn + button.custom, .input-group-btn > button.custom + button.custom {
      margin-left: -1px; }
    .input-group-btn > .btn:focus, .input-group-btn > button.custom:focus, .input-group-btn > .btn:active, .input-group-btn > button.custom:active, .input-group-btn > .btn:hover, .input-group-btn > button.custom:hover {
      z-index: 3; }
  .input-group-btn:not(:last-child) > .btn, .input-group-btn:not(:last-child) > button.custom,
  .input-group-btn:not(:last-child) > .btn-group {
    margin-right: -1px; }
  .input-group-btn:not(:first-child) > .btn, .input-group-btn:not(:first-child) > button.custom,
  .input-group-btn:not(:first-child) > .btn-group {
    z-index: 2;
    margin-left: -1px; }
    .input-group-btn:not(:first-child) > .btn:focus, .input-group-btn:not(:first-child) > button.custom:focus, .input-group-btn:not(:first-child) > .btn:active, .input-group-btn:not(:first-child) > button.custom:active, .input-group-btn:not(:first-child) > .btn:hover, .input-group-btn:not(:first-child) > button.custom:hover,
    .input-group-btn:not(:first-child) > .btn-group:focus,
    .input-group-btn:not(:first-child) > .btn-group:active,
    .input-group-btn:not(:first-child) > .btn-group:hover {
      z-index: 3; }

.custom-control {
  position: relative;
  display: -webkit-inline-flex;
  display: -ms-inline-flexbox;
  display: inline-flex;
  min-height: 1.5rem;
  padding-left: 1.5rem;
  margin-right: 1rem; }

.custom-control-input {
  position: absolute;
  z-index: -1;
  opacity: 0; }
  .custom-control-input:checked ~ .custom-control-indicator {
    color: #fff;
    background-color: #007bff; }
  .custom-control-input:focus ~ .custom-control-indicator {
    box-shadow: 0 0 0 1px #fff, 0 0 0 3px #007bff; }
  .custom-control-input:active ~ .custom-control-indicator {
    color: #fff;
    background-color: #b3d7ff; }
  .custom-control-input:disabled ~ .custom-control-indicator {
    background-color: #e9ecef; }
  .custom-control-input:disabled ~ .custom-control-description {
    color: #868e96; }

.custom-control-indicator {
  position: absolute;
  top: 0.25rem;
  left: 0;
  display: block;
  width: 1rem;
  height: 1rem;
  pointer-events: none;
  -webkit-user-select: none;
     -moz-user-select: none;
      -ms-user-select: none;
          user-select: none;
  background-color: #ddd;
  background-repeat: no-repeat;
  background-position: center center;
  background-size: 50% 50%; }

.custom-checkbox .custom-control-indicator {
  border-radius: 0.25rem; }

.custom-checkbox .custom-control-input:checked ~ .custom-control-indicator {
  background-image: url("data:image/svg+xml;charset=utf8,%3Csvg xmlns='http://www.w3.org/2000/svg' viewBox='0 0 8 8'%3E%3Cpath fill='%23fff' d='M6.564.75l-3.59 3.612-1.538-1.55L0 4.26 2.974 7.25 8 2.193z'/%3E%3C/svg%3E"); }

.custom-checkbox .custom-control-input:indeterminate ~ .custom-control-indicator {
  background-color: #007bff;
  background-image: url("data:image/svg+xml;charset=utf8,%3Csvg xmlns='http://www.w3.org/2000/svg' viewBox='0 0 4 4'%3E%3Cpath stroke='%23fff' d='M0 2h4'/%3E%3C/svg%3E"); }

.custom-radio .custom-control-indicator {
  border-radius: 50%; }

.custom-radio .custom-control-input:checked ~ .custom-control-indicator {
  background-image: url("data:image/svg+xml;charset=utf8,%3Csvg xmlns='http://www.w3.org/2000/svg' viewBox='-4 -4 8 8'%3E%3Ccircle r='3' fill='%23fff'/%3E%3C/svg%3E"); }

.custom-controls-stacked {
  display: -webkit-flex;
  display: -ms-flexbox;
  display: flex;
  -webkit-flex-direction: column;
      -ms-flex-direction: column;
          flex-direction: column; }
  .custom-controls-stacked .custom-control {
    margin-bottom: 0.25rem; }
    .custom-controls-stacked .custom-control + .custom-control {
      margin-left: 0; }

.custom-select {
  display: inline-block;
  max-width: 100%;
  height: calc(2.25rem + 2px);
  padding: 0.375rem 1.75rem 0.375rem 0.75rem;
  line-height: 1.25;
  color: #495057;
  vertical-align: middle;
  background: #fff url("data:image/svg+xml;charset=utf8,%3Csvg xmlns='http://www.w3.org/2000/svg' viewBox='0 0 4 5'%3E%3Cpath fill='%23333' d='M2 0L0 2h4zm0 5L0 3h4z'/%3E%3C/svg%3E") no-repeat right 0.75rem center;
  background-clip: padding-box;
  background-size: 8px 10px;
  border: 1px solid rgba(0, 0, 0, 0.15);
  border-radius: 0.25rem;
  -webkit-appearance: none;
     -moz-appearance: none;
          appearance: none; }
  .custom-select:focus {
    border-color: #80bdff;
    outline: none; }
    .custom-select:focus::-ms-value {
      color: #495057;
      background-color: #fff; }
  .custom-select:disabled {
    color: #868e96;
    background-color: #e9ecef; }
  .custom-select::-ms-expand {
    opacity: 0; }

.custom-select-sm {
  height: calc(1.8125rem + 2px);
  padding-top: 0.375rem;
  padding-bottom: 0.375rem;
  font-size: 75%; }

.custom-file {
  position: relative;
  display: inline-block;
  max-width: 100%;
  height: calc(2.25rem + 2px);
  margin-bottom: 0; }

.custom-file-input {
  min-width: 14rem;
  max-width: 100%;
  height: calc(2.25rem + 2px);
  margin: 0;
  opacity: 0; }
  .custom-file-input:focus ~ .custom-file-control {
    box-shadow: 0 0 0 0.075rem #fff, 0 0 0 0.2rem #007bff; }

.custom-file-control {
  position: absolute;
  top: 0;
  right: 0;
  left: 0;
  z-index: 5;
  height: calc(2.25rem + 2px);
  padding: 0.5rem 0.75rem;
  overflow: hidden;
  line-height: 1.25;
  color: #495057;
  pointer-events: none;
  -webkit-user-select: none;
     -moz-user-select: none;
      -ms-user-select: none;
          user-select: none;
  background-color: #fff;
  background-clip: padding-box;
  border: 1px solid rgba(0, 0, 0, 0.15);
  border-radius: 0.25rem; }
  .custom-file-control:lang(en):empty::after {
    content: "Choose file..."; }
  .custom-file-control::before {
    position: absolute;
    top: 0;
    right: 0;
    z-index: 6;
    display: block;
    height: calc(2.25rem + 2px);
    padding: 0.5rem 0.75rem;
    line-height: 1.25;
    color: #495057;
    background-color: #e9ecef;
    border-left: 1px solid rgba(0, 0, 0, 0.15); }
  .custom-file-control:lang(en)::before {
    content: "Browse"; }

.nav {
  display: -webkit-flex;
  display: -ms-flexbox;
  display: flex;
  -webkit-flex-wrap: wrap;
      -ms-flex-wrap: wrap;
          flex-wrap: wrap;
  padding-left: 0;
  margin-bottom: 0;
  list-style: none; }

.nav-link {
  display: block;
  padding: 0.5rem 1rem; }
  .nav-link:focus, .nav-link:hover {
    text-decoration: none; }
  .nav-link.disabled {
    color: #868e96; }

.nav-tabs {
  border-bottom: 1px solid #ddd; }
  .nav-tabs .nav-item {
    margin-bottom: -1px; }
  .nav-tabs .nav-link {
    border: 1px solid transparent;
    border-top-left-radius: 0.25rem;
    border-top-right-radius: 0.25rem; }
    .nav-tabs .nav-link:focus, .nav-tabs .nav-link:hover {
      border-color: #e9ecef #e9ecef #ddd; }
    .nav-tabs .nav-link.disabled {
      color: #868e96;
      background-color: transparent;
      border-color: transparent; }
  .nav-tabs .nav-link.active,
  .nav-tabs .nav-item.show .nav-link {
    color: #495057;
    background-color: #fff;
    border-color: #ddd #ddd #fff; }
  .nav-tabs .dropdown-menu {
    margin-top: -1px;
    border-top-left-radius: 0;
    border-top-right-radius: 0; }

.nav-pills .nav-link {
  border-radius: 0.25rem; }
  .nav-pills .nav-link.active,
  .show > .nav-pills .nav-link {
    color: #fff;
    background-color: #007bff; }

.nav-fill .nav-item {
  -webkit-flex: 1 1 auto;
      -ms-flex: 1 1 auto;
          flex: 1 1 auto;
  text-align: center; }

.nav-justified .nav-item {
  -webkit-flex-basis: 0;
      -ms-flex-preferred-size: 0;
          flex-basis: 0;
  -webkit-flex-grow: 1;
      -ms-flex-positive: 1;
          flex-grow: 1;
  text-align: center; }

.tab-content > .tab-pane {
  display: none; }

.tab-content > .active {
  display: block; }

.navbar {
  position: relative;
  display: -webkit-flex;
  display: -ms-flexbox;
  display: flex;
  -webkit-flex-wrap: wrap;
      -ms-flex-wrap: wrap;
          flex-wrap: wrap;
  -webkit-align-items: center;
      -ms-flex-align: center;
          align-items: center;
  -webkit-justify-content: space-between;
      -ms-flex-pack: justify;
          justify-content: space-between;
  padding: 0.5rem 1rem; }
  .navbar > .container,
  .navbar > .container-fluid {
    display: -webkit-flex;
    display: -ms-flexbox;
    display: flex;
    -webkit-flex-wrap: wrap;
        -ms-flex-wrap: wrap;
            flex-wrap: wrap;
    -webkit-align-items: center;
        -ms-flex-align: center;
            align-items: center;
    -webkit-justify-content: space-between;
        -ms-flex-pack: justify;
            justify-content: space-between; }

.navbar-brand {
  display: inline-block;
  padding-top: 0.3125rem;
  padding-bottom: 0.3125rem;
  margin-right: 1rem;
  font-size: 1.25rem;
  line-height: inherit;
  white-space: nowrap; }
  .navbar-brand:focus, .navbar-brand:hover {
    text-decoration: none; }

.navbar-nav {
  display: -webkit-flex;
  display: -ms-flexbox;
  display: flex;
  -webkit-flex-direction: column;
      -ms-flex-direction: column;
          flex-direction: column;
  padding-left: 0;
  margin-bottom: 0;
  list-style: none; }
  .navbar-nav .nav-link {
    padding-right: 0;
    padding-left: 0; }
  .navbar-nav .dropdown-menu {
    position: static;
    float: none; }

.navbar-text {
  display: inline-block;
  padding-top: 0.5rem;
  padding-bottom: 0.5rem; }

.navbar-collapse {
  -webkit-flex-basis: 100%;
      -ms-flex-preferred-size: 100%;
          flex-basis: 100%;
  -webkit-align-items: center;
      -ms-flex-align: center;
              -ms-grid-row-align: center;
          align-items: center; }

.navbar-toggler {
  padding: 0.25rem 0.75rem;
  font-size: 1.25rem;
  line-height: 1;
  background: transparent;
  border: 1px solid transparent;
  border-radius: 0.25rem; }
  .navbar-toggler:focus, .navbar-toggler:hover {
    text-decoration: none; }

.navbar-toggler-icon {
  display: inline-block;
  width: 1.5em;
  height: 1.5em;
  vertical-align: middle;
  content: "";
  background: no-repeat center center;
  background-size: 100% 100%; }

@media (max-width: 575px) {
  .navbar-expand-sm > .container,
  .navbar-expand-sm > .container-fluid {
    padding-right: 0;
    padding-left: 0; } }

@media (min-width: 576px) {
  .navbar-expand-sm {
    -webkit-flex-direction: row;
        -ms-flex-direction: row;
            flex-direction: row;
    -webkit-flex-wrap: nowrap;
        -ms-flex-wrap: nowrap;
            flex-wrap: nowrap;
    -webkit-justify-content: flex-start;
        -ms-flex-pack: start;
            justify-content: flex-start; }
    .navbar-expand-sm .navbar-nav {
      -webkit-flex-direction: row;
          -ms-flex-direction: row;
              flex-direction: row; }
      .navbar-expand-sm .navbar-nav .dropdown-menu {
        position: absolute; }
      .navbar-expand-sm .navbar-nav .dropdown-menu-right {
        right: 0;
        left: auto; }
      .navbar-expand-sm .navbar-nav .nav-link {
        padding-right: .5rem;
        padding-left: .5rem; }
    .navbar-expand-sm > .container,
    .navbar-expand-sm > .container-fluid {
      -webkit-flex-wrap: nowrap;
          -ms-flex-wrap: nowrap;
              flex-wrap: nowrap; }
    .navbar-expand-sm .navbar-collapse {
      display: -webkit-flex !important;
      display: -ms-flexbox !important;
      display: flex !important; }
    .navbar-expand-sm .navbar-toggler {
      display: none; } }

@media (max-width: 767px) {
  .navbar-expand-md > .container,
  .navbar-expand-md > .container-fluid {
    padding-right: 0;
    padding-left: 0; } }

@media (min-width: 768px) {
  .navbar-expand-md {
    -webkit-flex-direction: row;
        -ms-flex-direction: row;
            flex-direction: row;
    -webkit-flex-wrap: nowrap;
        -ms-flex-wrap: nowrap;
            flex-wrap: nowrap;
    -webkit-justify-content: flex-start;
        -ms-flex-pack: start;
            justify-content: flex-start; }
    .navbar-expand-md .navbar-nav {
      -webkit-flex-direction: row;
          -ms-flex-direction: row;
              flex-direction: row; }
      .navbar-expand-md .navbar-nav .dropdown-menu {
        position: absolute; }
      .navbar-expand-md .navbar-nav .dropdown-menu-right {
        right: 0;
        left: auto; }
      .navbar-expand-md .navbar-nav .nav-link {
        padding-right: .5rem;
        padding-left: .5rem; }
    .navbar-expand-md > .container,
    .navbar-expand-md > .container-fluid {
      -webkit-flex-wrap: nowrap;
          -ms-flex-wrap: nowrap;
              flex-wrap: nowrap; }
    .navbar-expand-md .navbar-collapse {
      display: -webkit-flex !important;
      display: -ms-flexbox !important;
      display: flex !important; }
    .navbar-expand-md .navbar-toggler {
      display: none; } }

@media (max-width: 991px) {
  .navbar-expand-lg > .container,
  .navbar-expand-lg > .container-fluid {
    padding-right: 0;
    padding-left: 0; } }

@media (min-width: 992px) {
  .navbar-expand-lg {
    -webkit-flex-direction: row;
        -ms-flex-direction: row;
            flex-direction: row;
    -webkit-flex-wrap: nowrap;
        -ms-flex-wrap: nowrap;
            flex-wrap: nowrap;
    -webkit-justify-content: flex-start;
        -ms-flex-pack: start;
            justify-content: flex-start; }
    .navbar-expand-lg .navbar-nav {
      -webkit-flex-direction: row;
          -ms-flex-direction: row;
              flex-direction: row; }
      .navbar-expand-lg .navbar-nav .dropdown-menu {
        position: absolute; }
      .navbar-expand-lg .navbar-nav .dropdown-menu-right {
        right: 0;
        left: auto; }
      .navbar-expand-lg .navbar-nav .nav-link {
        padding-right: .5rem;
        padding-left: .5rem; }
    .navbar-expand-lg > .container,
    .navbar-expand-lg > .container-fluid {
      -webkit-flex-wrap: nowrap;
          -ms-flex-wrap: nowrap;
              flex-wrap: nowrap; }
    .navbar-expand-lg .navbar-collapse {
      display: -webkit-flex !important;
      display: -ms-flexbox !important;
      display: flex !important; }
    .navbar-expand-lg .navbar-toggler {
      display: none; } }

@media (max-width: 1199px) {
  .navbar-expand-xl > .container,
  .navbar-expand-xl > .container-fluid {
    padding-right: 0;
    padding-left: 0; } }

@media (min-width: 1200px) {
  .navbar-expand-xl {
    -webkit-flex-direction: row;
        -ms-flex-direction: row;
            flex-direction: row;
    -webkit-flex-wrap: nowrap;
        -ms-flex-wrap: nowrap;
            flex-wrap: nowrap;
    -webkit-justify-content: flex-start;
        -ms-flex-pack: start;
            justify-content: flex-start; }
    .navbar-expand-xl .navbar-nav {
      -webkit-flex-direction: row;
          -ms-flex-direction: row;
              flex-direction: row; }
      .navbar-expand-xl .navbar-nav .dropdown-menu {
        position: absolute; }
      .navbar-expand-xl .navbar-nav .dropdown-menu-right {
        right: 0;
        left: auto; }
      .navbar-expand-xl .navbar-nav .nav-link {
        padding-right: .5rem;
        padding-left: .5rem; }
    .navbar-expand-xl > .container,
    .navbar-expand-xl > .container-fluid {
      -webkit-flex-wrap: nowrap;
          -ms-flex-wrap: nowrap;
              flex-wrap: nowrap; }
    .navbar-expand-xl .navbar-collapse {
      display: -webkit-flex !important;
      display: -ms-flexbox !important;
      display: flex !important; }
    .navbar-expand-xl .navbar-toggler {
      display: none; } }

.navbar-expand {
  -webkit-flex-direction: row;
      -ms-flex-direction: row;
          flex-direction: row;
  -webkit-flex-wrap: nowrap;
      -ms-flex-wrap: nowrap;
          flex-wrap: nowrap;
  -webkit-justify-content: flex-start;
      -ms-flex-pack: start;
          justify-content: flex-start; }
  .navbar-expand > .container,
  .navbar-expand > .container-fluid {
    padding-right: 0;
    padding-left: 0; }
  .navbar-expand .navbar-nav {
    -webkit-flex-direction: row;
        -ms-flex-direction: row;
            flex-direction: row; }
    .navbar-expand .navbar-nav .dropdown-menu {
      position: absolute; }
    .navbar-expand .navbar-nav .dropdown-menu-right {
      right: 0;
      left: auto; }
    .navbar-expand .navbar-nav .nav-link {
      padding-right: .5rem;
      padding-left: .5rem; }
  .navbar-expand > .container,
  .navbar-expand > .container-fluid {
    -webkit-flex-wrap: nowrap;
        -ms-flex-wrap: nowrap;
            flex-wrap: nowrap; }
  .navbar-expand .navbar-collapse {
    display: -webkit-flex !important;
    display: -ms-flexbox !important;
    display: flex !important; }
  .navbar-expand .navbar-toggler {
    display: none; }

.navbar-light .navbar-brand {
  color: rgba(0, 0, 0, 0.9); }
  .navbar-light .navbar-brand:focus, .navbar-light .navbar-brand:hover {
    color: rgba(0, 0, 0, 0.9); }

.navbar-light .navbar-nav .nav-link {
  color: rgba(0, 0, 0, 0.5); }
  .navbar-light .navbar-nav .nav-link:focus, .navbar-light .navbar-nav .nav-link:hover {
    color: rgba(0, 0, 0, 0.7); }
  .navbar-light .navbar-nav .nav-link.disabled {
    color: rgba(0, 0, 0, 0.3); }

.navbar-light .navbar-nav .show > .nav-link,
.navbar-light .navbar-nav .active > .nav-link,
.navbar-light .navbar-nav .nav-link.show,
.navbar-light .navbar-nav .nav-link.active {
  color: rgba(0, 0, 0, 0.9); }

.navbar-light .navbar-toggler {
  color: rgba(0, 0, 0, 0.5);
  border-color: rgba(0, 0, 0, 0.1); }

.navbar-light .navbar-toggler-icon {
  background-image: url("data:image/svg+xml;charset=utf8,%3Csvg viewBox='0 0 30 30' xmlns='http://www.w3.org/2000/svg'%3E%3Cpath stroke='rgba(0, 0, 0, 0.5)' stroke-width='2' stroke-linecap='round' stroke-miterlimit='10' d='M4 7h22M4 15h22M4 23h22'/%3E%3C/svg%3E"); }

.navbar-light .navbar-text {
  color: rgba(0, 0, 0, 0.5); }

.navbar-dark .navbar-brand {
  color: white; }
  .navbar-dark .navbar-brand:focus, .navbar-dark .navbar-brand:hover {
    color: white; }

.navbar-dark .navbar-nav .nav-link {
  color: rgba(255, 255, 255, 0.5); }
  .navbar-dark .navbar-nav .nav-link:focus, .navbar-dark .navbar-nav .nav-link:hover {
    color: rgba(255, 255, 255, 0.75); }
  .navbar-dark .navbar-nav .nav-link.disabled {
    color: rgba(255, 255, 255, 0.25); }

.navbar-dark .navbar-nav .show > .nav-link,
.navbar-dark .navbar-nav .active > .nav-link,
.navbar-dark .navbar-nav .nav-link.show,
.navbar-dark .navbar-nav .nav-link.active {
  color: white; }

.navbar-dark .navbar-toggler {
  color: rgba(255, 255, 255, 0.5);
  border-color: rgba(255, 255, 255, 0.1); }

.navbar-dark .navbar-toggler-icon {
  background-image: url("data:image/svg+xml;charset=utf8,%3Csvg viewBox='0 0 30 30' xmlns='http://www.w3.org/2000/svg'%3E%3Cpath stroke='rgba(255, 255, 255, 0.5)' stroke-width='2' stroke-linecap='round' stroke-miterlimit='10' d='M4 7h22M4 15h22M4 23h22'/%3E%3C/svg%3E"); }

.navbar-dark .navbar-text {
  color: rgba(255, 255, 255, 0.5); }

.card {
  position: relative;
  display: -webkit-flex;
  display: -ms-flexbox;
  display: flex;
  -webkit-flex-direction: column;
      -ms-flex-direction: column;
          flex-direction: column;
  min-width: 0;
  word-wrap: break-word;
  background-color: #fff;
  background-clip: border-box;
  border: 1px solid rgba(0, 0, 0, 0.125);
  border-radius: 0.25rem; }

.card-body {
  -webkit-flex: 1 1 auto;
      -ms-flex: 1 1 auto;
          flex: 1 1 auto;
  padding: 1.25rem; }

.card-title {
  margin-bottom: 0.75rem; }

.card-subtitle {
  margin-top: -0.375rem;
  margin-bottom: 0; }

.card-text:last-child {
  margin-bottom: 0; }

.card-link:hover {
  text-decoration: none; }

.card-link + .card-link {
  margin-left: 1.25rem; }

.card > .list-group:first-child .list-group-item:first-child {
  border-top-left-radius: 0.25rem;
  border-top-right-radius: 0.25rem; }

.card > .list-group:last-child .list-group-item:last-child {
  border-bottom-right-radius: 0.25rem;
  border-bottom-left-radius: 0.25rem; }

.card-header {
  padding: 0.75rem 1.25rem;
  margin-bottom: 0;
  background-color: rgba(0, 0, 0, 0.03);
  border-bottom: 1px solid rgba(0, 0, 0, 0.125); }
  .card-header:first-child {
    border-radius: calc(0.25rem - 1px) calc(0.25rem - 1px) 0 0; }

.card-footer {
  padding: 0.75rem 1.25rem;
  background-color: rgba(0, 0, 0, 0.03);
  border-top: 1px solid rgba(0, 0, 0, 0.125); }
  .card-footer:last-child {
    border-radius: 0 0 calc(0.25rem - 1px) calc(0.25rem - 1px); }

.card-header-tabs {
  margin-right: -0.625rem;
  margin-bottom: -0.75rem;
  margin-left: -0.625rem;
  border-bottom: 0; }

.card-header-pills {
  margin-right: -0.625rem;
  margin-left: -0.625rem; }

.card-img-overlay {
  position: absolute;
  top: 0;
  right: 0;
  bottom: 0;
  left: 0;
  padding: 1.25rem; }

.card-img {
  width: 100%;
  border-radius: calc(0.25rem - 1px); }

.card-img-top {
  width: 100%;
  border-top-left-radius: calc(0.25rem - 1px);
  border-top-right-radius: calc(0.25rem - 1px); }

.card-img-bottom {
  width: 100%;
  border-bottom-right-radius: calc(0.25rem - 1px);
  border-bottom-left-radius: calc(0.25rem - 1px); }

@media (min-width: 576px) {
  .card-deck {
    display: -webkit-flex;
    display: -ms-flexbox;
    display: flex;
    -webkit-flex-flow: row wrap;
        -ms-flex-flow: row wrap;
            flex-flow: row wrap;
    margin-right: -15px;
    margin-left: -15px; }
    .card-deck .card {
      display: -webkit-flex;
      display: -ms-flexbox;
      display: flex;
      -webkit-flex: 1 0 0%;
          -ms-flex: 1 0 0%;
              flex: 1 0 0%;
      -webkit-flex-direction: column;
          -ms-flex-direction: column;
              flex-direction: column;
      margin-right: 15px;
      margin-left: 15px; } }

@media (min-width: 576px) {
  .card-group {
    display: -webkit-flex;
    display: -ms-flexbox;
    display: flex;
    -webkit-flex-flow: row wrap;
        -ms-flex-flow: row wrap;
            flex-flow: row wrap; }
    .card-group .card {
      -webkit-flex: 1 0 0%;
          -ms-flex: 1 0 0%;
              flex: 1 0 0%; }
      .card-group .card + .card {
        margin-left: 0;
        border-left: 0; }
      .card-group .card:first-child {
        border-top-right-radius: 0;
        border-bottom-right-radius: 0; }
        .card-group .card:first-child .card-img-top {
          border-top-right-radius: 0; }
        .card-group .card:first-child .card-img-bottom {
          border-bottom-right-radius: 0; }
      .card-group .card:last-child {
        border-top-left-radius: 0;
        border-bottom-left-radius: 0; }
        .card-group .card:last-child .card-img-top {
          border-top-left-radius: 0; }
        .card-group .card:last-child .card-img-bottom {
          border-bottom-left-radius: 0; }
      .card-group .card:not(:first-child):not(:last-child) {
        border-radius: 0; }
        .card-group .card:not(:first-child):not(:last-child) .card-img-top,
        .card-group .card:not(:first-child):not(:last-child) .card-img-bottom {
          border-radius: 0; } }

.card-columns .card {
  margin-bottom: 0.75rem; }

@media (min-width: 576px) {
  .card-columns {
    -webkit-column-count: 3;
            column-count: 3;
    -webkit-column-gap: 1.25rem;
            column-gap: 1.25rem; }
    .card-columns .card {
      display: inline-block;
      width: 100%; } }

.breadcrumb {
  padding: 0.75rem 1rem;
  margin-bottom: 1rem;
  list-style: none;
  background-color: #e9ecef;
  border-radius: 0.25rem; }
  .breadcrumb::after {
    display: block;
    clear: both;
    content: ""; }

.breadcrumb-item {
  float: left; }
  .breadcrumb-item + .breadcrumb-item::before {
    display: inline-block;
    padding-right: 0.5rem;
    padding-left: 0.5rem;
    color: #868e96;
    content: "/"; }
  .breadcrumb-item + .breadcrumb-item:hover::before {
    text-decoration: underline; }
  .breadcrumb-item + .breadcrumb-item:hover::before {
    text-decoration: none; }
  .breadcrumb-item.active {
    color: #868e96; }

.pagination {
  display: -webkit-flex;
  display: -ms-flexbox;
  display: flex;
  padding-left: 0;
  list-style: none;
  border-radius: 0.25rem; }

.page-item:first-child .page-link {
  margin-left: 0;
  border-top-left-radius: 0.25rem;
  border-bottom-left-radius: 0.25rem; }

.page-item:last-child .page-link {
  border-top-right-radius: 0.25rem;
  border-bottom-right-radius: 0.25rem; }

.page-item.active .page-link {
  z-index: 2;
  color: #fff;
  background-color: #007bff;
  border-color: #007bff; }

.page-item.disabled .page-link {
  color: #868e96;
  pointer-events: none;
  background-color: #fff;
  border-color: #ddd; }

.page-link {
  position: relative;
  display: block;
  padding: 0.5rem 0.75rem;
  margin-left: -1px;
  line-height: 1.25;
  color: #007bff;
  background-color: #fff;
  border: 1px solid #ddd; }
  .page-link:focus, .page-link:hover {
    color: #0056b3;
    text-decoration: none;
    background-color: #e9ecef;
    border-color: #ddd; }

.pagination-lg .page-link {
  padding: 0.75rem 1.5rem;
  font-size: 1.25rem;
  line-height: 1.5; }

.pagination-lg .page-item:first-child .page-link {
  border-top-left-radius: 0.3rem;
  border-bottom-left-radius: 0.3rem; }

.pagination-lg .page-item:last-child .page-link {
  border-top-right-radius: 0.3rem;
  border-bottom-right-radius: 0.3rem; }

.pagination-sm .page-link {
  padding: 0.25rem 0.5rem;
  font-size: 0.875rem;
  line-height: 1.5; }

.pagination-sm .page-item:first-child .page-link {
  border-top-left-radius: 0.2rem;
  border-bottom-left-radius: 0.2rem; }

.pagination-sm .page-item:last-child .page-link {
  border-top-right-radius: 0.2rem;
  border-bottom-right-radius: 0.2rem; }

.badge {
  display: inline-block;
  padding: 0.25em 0.4em;
  font-size: 75%;
  font-weight: bold;
  line-height: 1;
  color: #fff;
  text-align: center;
  white-space: nowrap;
  vertical-align: baseline;
  border-radius: 0.25rem; }
  .badge:empty {
    display: none; }

.btn .badge, button.custom .badge {
  position: relative;
  top: -1px; }

.badge-pill {
  padding-right: 0.6em;
  padding-left: 0.6em;
  border-radius: 10rem; }

.badge-primary {
  color: #fff;
  background-color: #007bff; }
  .badge-primary[href]:focus, .badge-primary[href]:hover {
    color: #fff;
    text-decoration: none;
    background-color: #0062cc; }

.badge-secondary {
  color: #fff;
  background-color: #868e96; }
  .badge-secondary[href]:focus, .badge-secondary[href]:hover {
    color: #fff;
    text-decoration: none;
    background-color: #6c757d; }

.badge-success {
  color: #fff;
  background-color: #28a745; }
  .badge-success[href]:focus, .badge-success[href]:hover {
    color: #fff;
    text-decoration: none;
    background-color: #1e7e34; }

.badge-info {
  color: #fff;
  background-color: #17a2b8; }
  .badge-info[href]:focus, .badge-info[href]:hover {
    color: #fff;
    text-decoration: none;
    background-color: #117a8b; }

.badge-warning {
  color: #111;
  background-color: #ffc107; }
  .badge-warning[href]:focus, .badge-warning[href]:hover {
    color: #111;
    text-decoration: none;
    background-color: #d39e00; }

.badge-danger {
  color: #fff;
  background-color: #dc3545; }
  .badge-danger[href]:focus, .badge-danger[href]:hover {
    color: #fff;
    text-decoration: none;
    background-color: #bd2130; }

.badge-light {
  color: #111;
  background-color: #f8f9fa; }
  .badge-light[href]:focus, .badge-light[href]:hover {
    color: #111;
    text-decoration: none;
    background-color: #dae0e5; }

.badge-dark {
  color: #fff;
  background-color: #343a40; }
  .badge-dark[href]:focus, .badge-dark[href]:hover {
    color: #fff;
    text-decoration: none;
    background-color: #1d2124; }

.jumbotron {
  padding: 2rem 1rem;
  margin-bottom: 2rem;
  background-color: #e9ecef;
  border-radius: 0.3rem; }
  @media (min-width: 576px) {
    .jumbotron {
      padding: 4rem 2rem; } }

.jumbotron-fluid {
  padding-right: 0;
  padding-left: 0;
  border-radius: 0; }

.alert {
  padding: 0.75rem 1.25rem;
  margin-bottom: 1rem;
  border: 1px solid transparent;
  border-radius: 0.25rem; }

.alert-heading {
  color: inherit; }

.alert-link {
  font-weight: bold; }

.alert-dismissible .close {
  position: relative;
  top: -0.75rem;
  right: -1.25rem;
  padding: 0.75rem 1.25rem;
  color: inherit; }

.alert-primary {
  color: #004085;
  background-color: #cce5ff;
  border-color: #b8daff; }
  .alert-primary hr {
    border-top-color: #9fcdff; }
  .alert-primary .alert-link {
    color: #002752; }

.alert-secondary {
  color: #464a4e;
  background-color: #e7e8ea;
  border-color: #dddfe2; }
  .alert-secondary hr {
    border-top-color: #cfd2d6; }
  .alert-secondary .alert-link {
    color: #2e3133; }

.alert-success {
  color: #155724;
  background-color: #d4edda;
  border-color: #c3e6cb; }
  .alert-success hr {
    border-top-color: #b1dfbb; }
  .alert-success .alert-link {
    color: #0b2e13; }

.alert-info {
  color: #0c5460;
  background-color: #d1ecf1;
  border-color: #bee5eb; }
  .alert-info hr {
    border-top-color: #abdde5; }
  .alert-info .alert-link {
    color: #062c33; }

.alert-warning {
  color: #856404;
  background-color: #fff3cd;
  border-color: #ffeeba; }
  .alert-warning hr {
    border-top-color: #ffe8a1; }
  .alert-warning .alert-link {
    color: #533f03; }

.alert-danger {
  color: #721c24;
  background-color: #f8d7da;
  border-color: #f5c6cb; }
  .alert-danger hr {
    border-top-color: #f1b0b7; }
  .alert-danger .alert-link {
    color: #491217; }

.alert-light {
  color: #818182;
  background-color: #fefefe;
  border-color: #fdfdfe; }
  .alert-light hr {
    border-top-color: #ececf6; }
  .alert-light .alert-link {
    color: #686868; }

.alert-dark {
  color: #1b1e21;
  background-color: #d6d8d9;
  border-color: #c6c8ca; }
  .alert-dark hr {
    border-top-color: #b9bbbe; }
  .alert-dark .alert-link {
    color: #040505; }

@-webkit-keyframes progress-bar-stripes {
  from {
    background-position: 1rem 0; }
  to {
    background-position: 0 0; } }

@keyframes progress-bar-stripes {
  from {
    background-position: 1rem 0; }
  to {
    background-position: 0 0; } }

.progress {
  display: -webkit-flex;
  display: -ms-flexbox;
  display: flex;
  height: 1rem;
  overflow: hidden;
  font-size: 0.75rem;
  background-color: #e9ecef;
  border-radius: 0.25rem; }

.progress-bar {
  display: -webkit-flex;
  display: -ms-flexbox;
  display: flex;
  -webkit-align-items: center;
      -ms-flex-align: center;
          align-items: center;
  -webkit-justify-content: center;
      -ms-flex-pack: center;
          justify-content: center;
  color: #fff;
  background-color: #007bff; }

.progress-bar-striped {
  background-image: linear-gradient(45deg, rgba(255, 255, 255, 0.15) 25%, transparent 25%, transparent 50%, rgba(255, 255, 255, 0.15) 50%, rgba(255, 255, 255, 0.15) 75%, transparent 75%, transparent);
  background-size: 1rem 1rem; }

.progress-bar-animated {
  -webkit-animation: progress-bar-stripes 1s linear infinite;
          animation: progress-bar-stripes 1s linear infinite; }

.media {
  display: -webkit-flex;
  display: -ms-flexbox;
  display: flex;
  -webkit-align-items: flex-start;
      -ms-flex-align: start;
          align-items: flex-start; }

.media-body {
  -webkit-flex: 1;
      -ms-flex: 1;
          flex: 1; }

.list-group {
  display: -webkit-flex;
  display: -ms-flexbox;
  display: flex;
  -webkit-flex-direction: column;
      -ms-flex-direction: column;
          flex-direction: column;
  padding-left: 0;
  margin-bottom: 0; }

.list-group-item-action {
  width: 100%;
  color: #495057;
  text-align: inherit; }
  .list-group-item-action:focus, .list-group-item-action:hover {
    color: #495057;
    text-decoration: none;
    background-color: #f8f9fa; }
  .list-group-item-action:active {
    color: #212529;
    background-color: #e9ecef; }

.list-group-item {
  position: relative;
  display: block;
  padding: 0.75rem 1.25rem;
  margin-bottom: -1px;
  background-color: #fff;
  border: 1px solid rgba(0, 0, 0, 0.125); }
  .list-group-item:first-child {
    border-top-left-radius: 0.25rem;
    border-top-right-radius: 0.25rem; }
  .list-group-item:last-child {
    margin-bottom: 0;
    border-bottom-right-radius: 0.25rem;
    border-bottom-left-radius: 0.25rem; }
  .list-group-item:focus, .list-group-item:hover {
    text-decoration: none; }
  .list-group-item.disabled, .list-group-item:disabled {
    color: #868e96;
    background-color: #fff; }
  .list-group-item.active {
    z-index: 2;
    color: #fff;
    background-color: #007bff;
    border-color: #007bff; }

.list-group-flush .list-group-item {
  border-right: 0;
  border-left: 0;
  border-radius: 0; }

.list-group-flush:first-child .list-group-item:first-child {
  border-top: 0; }

.list-group-flush:last-child .list-group-item:last-child {
  border-bottom: 0; }

.list-group-item-primary {
  color: #004085;
  background-color: #b8daff; }

a.list-group-item-primary,
button.list-group-item-primary {
  color: #004085; }
  a.list-group-item-primary:focus, a.list-group-item-primary:hover,
  button.list-group-item-primary:focus,
  button.list-group-item-primary:hover {
    color: #004085;
    background-color: #9fcdff; }
  a.list-group-item-primary.active,
  button.list-group-item-primary.active {
    color: #fff;
    background-color: #004085;
    border-color: #004085; }

.list-group-item-secondary {
  color: #464a4e;
  background-color: #dddfe2; }

a.list-group-item-secondary,
button.list-group-item-secondary {
  color: #464a4e; }
  a.list-group-item-secondary:focus, a.list-group-item-secondary:hover,
  button.list-group-item-secondary:focus,
  button.list-group-item-secondary:hover {
    color: #464a4e;
    background-color: #cfd2d6; }
  a.list-group-item-secondary.active,
  button.list-group-item-secondary.active {
    color: #fff;
    background-color: #464a4e;
    border-color: #464a4e; }

.list-group-item-success {
  color: #155724;
  background-color: #c3e6cb; }

a.list-group-item-success,
button.list-group-item-success {
  color: #155724; }
  a.list-group-item-success:focus, a.list-group-item-success:hover,
  button.list-group-item-success:focus,
  button.list-group-item-success:hover {
    color: #155724;
    background-color: #b1dfbb; }
  a.list-group-item-success.active,
  button.list-group-item-success.active {
    color: #fff;
    background-color: #155724;
    border-color: #155724; }

.list-group-item-info {
  color: #0c5460;
  background-color: #bee5eb; }

a.list-group-item-info,
button.list-group-item-info {
  color: #0c5460; }
  a.list-group-item-info:focus, a.list-group-item-info:hover,
  button.list-group-item-info:focus,
  button.list-group-item-info:hover {
    color: #0c5460;
    background-color: #abdde5; }
  a.list-group-item-info.active,
  button.list-group-item-info.active {
    color: #fff;
    background-color: #0c5460;
    border-color: #0c5460; }

.list-group-item-warning {
  color: #856404;
  background-color: #ffeeba; }

a.list-group-item-warning,
button.list-group-item-warning {
  color: #856404; }
  a.list-group-item-warning:focus, a.list-group-item-warning:hover,
  button.list-group-item-warning:focus,
  button.list-group-item-warning:hover {
    color: #856404;
    background-color: #ffe8a1; }
  a.list-group-item-warning.active,
  button.list-group-item-warning.active {
    color: #fff;
    background-color: #856404;
    border-color: #856404; }

.list-group-item-danger {
  color: #721c24;
  background-color: #f5c6cb; }

a.list-group-item-danger,
button.list-group-item-danger {
  color: #721c24; }
  a.list-group-item-danger:focus, a.list-group-item-danger:hover,
  button.list-group-item-danger:focus,
  button.list-group-item-danger:hover {
    color: #721c24;
    background-color: #f1b0b7; }
  a.list-group-item-danger.active,
  button.list-group-item-danger.active {
    color: #fff;
    background-color: #721c24;
    border-color: #721c24; }

.list-group-item-light {
  color: #818182;
  background-color: #fdfdfe; }

a.list-group-item-light,
button.list-group-item-light {
  color: #818182; }
  a.list-group-item-light:focus, a.list-group-item-light:hover,
  button.list-group-item-light:focus,
  button.list-group-item-light:hover {
    color: #818182;
    background-color: #ececf6; }
  a.list-group-item-light.active,
  button.list-group-item-light.active {
    color: #fff;
    background-color: #818182;
    border-color: #818182; }

.list-group-item-dark {
  color: #1b1e21;
  background-color: #c6c8ca; }

a.list-group-item-dark,
button.list-group-item-dark {
  color: #1b1e21; }
  a.list-group-item-dark:focus, a.list-group-item-dark:hover,
  button.list-group-item-dark:focus,
  button.list-group-item-dark:hover {
    color: #1b1e21;
    background-color: #b9bbbe; }
  a.list-group-item-dark.active,
  button.list-group-item-dark.active {
    color: #fff;
    background-color: #1b1e21;
    border-color: #1b1e21; }

.close {
  float: right;
  font-size: 1.5rem;
  font-weight: bold;
  line-height: 1;
  color: #000;
  text-shadow: 0 1px 0 #fff;
  opacity: .5; }
  .close:focus, .close:hover {
    color: #000;
    text-decoration: none;
    opacity: .75; }

button.close {
  padding: 0;
  background: transparent;
  border: 0;
  -webkit-appearance: none; }

.modal-open {
  overflow: hidden; }

.modal {
  position: fixed;
  top: 0;
  right: 0;
  bottom: 0;
  left: 0;
  z-index: 1050;
  display: none;
  overflow: hidden;
  outline: 0; }
  .modal.fade .modal-dialog {
    transition: -webkit-transform 0.3s ease-out;
    transition: transform 0.3s ease-out;
    transition: transform 0.3s ease-out, -webkit-transform 0.3s ease-out;
    -webkit-transform: translate(0, -25%);
        -ms-transform: translate(0, -25%);
            transform: translate(0, -25%); }
  .modal.show .modal-dialog {
    -webkit-transform: translate(0, 0);
        -ms-transform: translate(0, 0);
            transform: translate(0, 0); }

.modal-open .modal {
  overflow-x: hidden;
  overflow-y: auto; }

.modal-dialog {
  position: relative;
  width: auto;
  margin: 10px; }

.modal-content {
  position: relative;
  display: -webkit-flex;
  display: -ms-flexbox;
  display: flex;
  -webkit-flex-direction: column;
      -ms-flex-direction: column;
          flex-direction: column;
  background-color: #fff;
  background-clip: padding-box;
  border: 1px solid rgba(0, 0, 0, 0.2);
  border-radius: 0.3rem;
  outline: 0; }

.modal-backdrop {
  position: fixed;
  top: 0;
  right: 0;
  bottom: 0;
  left: 0;
  z-index: 1040;
  background-color: #000; }
  .modal-backdrop.fade {
    opacity: 0; }
  .modal-backdrop.show {
    opacity: 0.5; }

.modal-header {
  display: -webkit-flex;
  display: -ms-flexbox;
  display: flex;
  -webkit-align-items: center;
      -ms-flex-align: center;
          align-items: center;
  -webkit-justify-content: space-between;
      -ms-flex-pack: justify;
          justify-content: space-between;
  padding: 15px;
  border-bottom: 1px solid #e9ecef; }
  .modal-header .close {
    margin-left: auto; }

.modal-title {
  margin-bottom: 0;
  line-height: 1.5; }

.modal-body {
  position: relative;
  -webkit-flex: 1 1 auto;
      -ms-flex: 1 1 auto;
          flex: 1 1 auto;
  padding: 15px; }

.modal-footer {
  display: -webkit-flex;
  display: -ms-flexbox;
  display: flex;
  -webkit-align-items: center;
      -ms-flex-align: center;
          align-items: center;
  -webkit-justify-content: flex-end;
      -ms-flex-pack: end;
          justify-content: flex-end;
  padding: 15px;
  border-top: 1px solid #e9ecef; }
  .modal-footer > :not(:first-child) {
    margin-left: .25rem; }
  .modal-footer > :not(:last-child) {
    margin-right: .25rem; }

.modal-scrollbar-measure {
  position: absolute;
  top: -9999px;
  width: 50px;
  height: 50px;
  overflow: scroll; }

@media (min-width: 576px) {
  .modal-dialog {
    max-width: 500px;
    margin: 30px auto; }
  .modal-sm {
    max-width: 300px; } }

@media (min-width: 992px) {
  .modal-lg {
    max-width: 800px; } }

.tooltip {
  position: absolute;
  z-index: 1070;
  display: block;
  margin: 0;
  font-family: -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, "Helvetica Neue", Arial, sans-serif, "Apple Color Emoji", "Segoe UI Emoji", "Segoe UI Symbol";
  font-style: normal;
  font-weight: normal;
  line-height: 1.5;
  text-align: left;
  text-align: start;
  text-decoration: none;
  text-shadow: none;
  text-transform: none;
  letter-spacing: normal;
  word-break: normal;
  word-spacing: normal;
  white-space: normal;
  line-break: auto;
  font-size: 0.875rem;
  word-wrap: break-word;
  opacity: 0; }
  .tooltip.show {
    opacity: 0.9; }
  .tooltip .arrow {
    position: absolute;
    display: block;
    width: 5px;
    height: 5px; }
  .tooltip.bs-tooltip-top, .tooltip.bs-tooltip-auto[x-placement^="top"] {
    padding: 5px 0; }
    .tooltip.bs-tooltip-top .arrow, .tooltip.bs-tooltip-auto[x-placement^="top"] .arrow {
      bottom: 0; }
    .tooltip.bs-tooltip-top .arrow::before, .tooltip.bs-tooltip-auto[x-placement^="top"] .arrow::before {
      margin-left: -3px;
      content: "";
      border-width: 5px 5px 0;
      border-top-color: #000; }
  .tooltip.bs-tooltip-right, .tooltip.bs-tooltip-auto[x-placement^="right"] {
    padding: 0 5px; }
    .tooltip.bs-tooltip-right .arrow, .tooltip.bs-tooltip-auto[x-placement^="right"] .arrow {
      left: 0; }
    .tooltip.bs-tooltip-right .arrow::before, .tooltip.bs-tooltip-auto[x-placement^="right"] .arrow::before {
      margin-top: -3px;
      content: "";
      border-width: 5px 5px 5px 0;
      border-right-color: #000; }
  .tooltip.bs-tooltip-bottom, .tooltip.bs-tooltip-auto[x-placement^="bottom"] {
    padding: 5px 0; }
    .tooltip.bs-tooltip-bottom .arrow, .tooltip.bs-tooltip-auto[x-placement^="bottom"] .arrow {
      top: 0; }
    .tooltip.bs-tooltip-bottom .arrow::before, .tooltip.bs-tooltip-auto[x-placement^="bottom"] .arrow::before {
      margin-left: -3px;
      content: "";
      border-width: 0 5px 5px;
      border-bottom-color: #000; }
  .tooltip.bs-tooltip-left, .tooltip.bs-tooltip-auto[x-placement^="left"] {
    padding: 0 5px; }
    .tooltip.bs-tooltip-left .arrow, .tooltip.bs-tooltip-auto[x-placement^="left"] .arrow {
      right: 0; }
    .tooltip.bs-tooltip-left .arrow::before, .tooltip.bs-tooltip-auto[x-placement^="left"] .arrow::before {
      right: 0;
      margin-top: -3px;
      content: "";
      border-width: 5px 0 5px 5px;
      border-left-color: #000; }
  .tooltip .arrow::before {
    position: absolute;
    border-color: transparent;
    border-style: solid; }

.tooltip-inner {
  max-width: 200px;
  padding: 3px 8px;
  color: #fff;
  text-align: center;
  background-color: #000;
  border-radius: 0.25rem; }

.popover {
  position: absolute;
  top: 0;
  left: 0;
  z-index: 1060;
  display: block;
  max-width: 276px;
  padding: 1px;
  font-family: -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, "Helvetica Neue", Arial, sans-serif, "Apple Color Emoji", "Segoe UI Emoji", "Segoe UI Symbol";
  font-style: normal;
  font-weight: normal;
  line-height: 1.5;
  text-align: left;
  text-align: start;
  text-decoration: none;
  text-shadow: none;
  text-transform: none;
  letter-spacing: normal;
  word-break: normal;
  word-spacing: normal;
  white-space: normal;
  line-break: auto;
  font-size: 0.875rem;
  word-wrap: break-word;
  background-color: #fff;
  background-clip: padding-box;
  border: 1px solid rgba(0, 0, 0, 0.2);
  border-radius: 0.3rem; }
  .popover .arrow {
    position: absolute;
    display: block;
    width: 10px;
    height: 5px; }
  .popover .arrow::before,
  .popover .arrow::after {
    position: absolute;
    display: block;
    border-color: transparent;
    border-style: solid; }
  .popover .arrow::before {
    content: "";
    border-width: 11px; }
  .popover .arrow::after {
    content: "";
    border-width: 11px; }
  .popover.bs-popover-top, .popover.bs-popover-auto[x-placement^="top"] {
    margin-bottom: 10px; }
    .popover.bs-popover-top .arrow, .popover.bs-popover-auto[x-placement^="top"] .arrow {
      bottom: 0; }
    .popover.bs-popover-top .arrow::before, .popover.bs-popover-auto[x-placement^="top"] .arrow::before,
    .popover.bs-popover-top .arrow::after, .popover.bs-popover-auto[x-placement^="top"] .arrow::after {
      border-bottom-width: 0; }
    .popover.bs-popover-top .arrow::before, .popover.bs-popover-auto[x-placement^="top"] .arrow::before {
      bottom: -11px;
      margin-left: -6px;
      border-top-color: rgba(0, 0, 0, 0.25); }
    .popover.bs-popover-top .arrow::after, .popover.bs-popover-auto[x-placement^="top"] .arrow::after {
      bottom: -10px;
      margin-left: -6px;
      border-top-color: #fff; }
  .popover.bs-popover-right, .popover.bs-popover-auto[x-placement^="right"] {
    margin-left: 10px; }
    .popover.bs-popover-right .arrow, .popover.bs-popover-auto[x-placement^="right"] .arrow {
      left: 0; }
    .popover.bs-popover-right .arrow::before, .popover.bs-popover-auto[x-placement^="right"] .arrow::before,
    .popover.bs-popover-right .arrow::after, .popover.bs-popover-auto[x-placement^="right"] .arrow::after {
      margin-top: -8px;
      border-left-width: 0; }
    .popover.bs-popover-right .arrow::before, .popover.bs-popover-auto[x-placement^="right"] .arrow::before {
      left: -11px;
      border-right-color: rgba(0, 0, 0, 0.25); }
    .popover.bs-popover-right .arrow::after, .popover.bs-popover-auto[x-placement^="right"] .arrow::after {
      left: -10px;
      border-right-color: #fff; }
  .popover.bs-popover-bottom, .popover.bs-popover-auto[x-placement^="bottom"] {
    margin-top: 10px; }
    .popover.bs-popover-bottom .arrow, .popover.bs-popover-auto[x-placement^="bottom"] .arrow {
      top: 0; }
    .popover.bs-popover-bottom .arrow::before, .popover.bs-popover-auto[x-placement^="bottom"] .arrow::before,
    .popover.bs-popover-bottom .arrow::after, .popover.bs-popover-auto[x-placement^="bottom"] .arrow::after {
      margin-left: -7px;
      border-top-width: 0; }
    .popover.bs-popover-bottom .arrow::before, .popover.bs-popover-auto[x-placement^="bottom"] .arrow::before {
      top: -11px;
      border-bottom-color: rgba(0, 0, 0, 0.25); }
    .popover.bs-popover-bottom .arrow::after, .popover.bs-popover-auto[x-placement^="bottom"] .arrow::after {
      top: -10px;
      border-bottom-color: #fff; }
    .popover.bs-popover-bottom .popover-header::before, .popover.bs-popover-auto[x-placement^="bottom"] .popover-header::before {
      position: absolute;
      top: 0;
      left: 50%;
      display: block;
      width: 20px;
      margin-left: -10px;
      content: "";
      border-bottom: 1px solid #f7f7f7; }
  .popover.bs-popover-left, .popover.bs-popover-auto[x-placement^="left"] {
    margin-right: 10px; }
    .popover.bs-popover-left .arrow, .popover.bs-popover-auto[x-placement^="left"] .arrow {
      right: 0; }
    .popover.bs-popover-left .arrow::before, .popover.bs-popover-auto[x-placement^="left"] .arrow::before,
    .popover.bs-popover-left .arrow::after, .popover.bs-popover-auto[x-placement^="left"] .arrow::after {
      margin-top: -8px;
      border-right-width: 0; }
    .popover.bs-popover-left .arrow::before, .popover.bs-popover-auto[x-placement^="left"] .arrow::before {
      right: -11px;
      border-left-color: rgba(0, 0, 0, 0.25); }
    .popover.bs-popover-left .arrow::after, .popover.bs-popover-auto[x-placement^="left"] .arrow::after {
      right: -10px;
      border-left-color: #fff; }

.popover-header {
  padding: 8px 14px;
  margin-bottom: 0;
  font-size: 1rem;
  color: inherit;
  background-color: #f7f7f7;
  border-bottom: 1px solid #ebebeb;
  border-top-left-radius: calc(0.3rem - 1px);
  border-top-right-radius: calc(0.3rem - 1px); }
  .popover-header:empty {
    display: none; }

.popover-body {
  padding: 9px 14px;
  color: #212529; }

.carousel {
  position: relative; }

.carousel-inner {
  position: relative;
  width: 100%;
  overflow: hidden; }

.carousel-item {
  position: relative;
  display: none;
  -webkit-align-items: center;
      -ms-flex-align: center;
              -ms-grid-row-align: center;
          align-items: center;
  width: 100%;
  transition: -webkit-transform 0.6s ease;
  transition: transform 0.6s ease;
  transition: transform 0.6s ease, -webkit-transform 0.6s ease;
  -webkit-backface-visibility: hidden;
          backface-visibility: hidden;
  -webkit-perspective: 1000px;
          perspective: 1000px; }

.carousel-item.active,
.carousel-item-next,
.carousel-item-prev {
  display: block; }

.carousel-item-next,
.carousel-item-prev {
  position: absolute;
  top: 0; }

.carousel-item-next.carousel-item-left,
.carousel-item-prev.carousel-item-right {
  -webkit-transform: translateX(0);
      -ms-transform: translateX(0);
          transform: translateX(0); }
  @supports (transform-style: preserve-3d) {
    .carousel-item-next.carousel-item-left,
    .carousel-item-prev.carousel-item-right {
      -webkit-transform: translate3d(0, 0, 0);
              transform: translate3d(0, 0, 0); } }

.carousel-item-next,
.active.carousel-item-right {
  -webkit-transform: translateX(100%);
      -ms-transform: translateX(100%);
          transform: translateX(100%); }
  @supports (transform-style: preserve-3d) {
    .carousel-item-next,
    .active.carousel-item-right {
      -webkit-transform: translate3d(100%, 0, 0);
              transform: translate3d(100%, 0, 0); } }

.carousel-item-prev,
.active.carousel-item-left {
  -webkit-transform: translateX(-100%);
      -ms-transform: translateX(-100%);
          transform: translateX(-100%); }
  @supports (transform-style: preserve-3d) {
    .carousel-item-prev,
    .active.carousel-item-left {
      -webkit-transform: translate3d(-100%, 0, 0);
              transform: translate3d(-100%, 0, 0); } }

.carousel-control-prev,
.carousel-control-next {
  position: absolute;
  top: 0;
  bottom: 0;
  display: -webkit-flex;
  display: -ms-flexbox;
  display: flex;
  -webkit-align-items: center;
      -ms-flex-align: center;
          align-items: center;
  -webkit-justify-content: center;
      -ms-flex-pack: center;
          justify-content: center;
  width: 15%;
  color: #fff;
  text-align: center;
  opacity: 0.5; }
  .carousel-control-prev:focus, .carousel-control-prev:hover,
  .carousel-control-next:focus,
  .carousel-control-next:hover {
    color: #fff;
    text-decoration: none;
    outline: 0;
    opacity: .9; }

.carousel-control-prev {
  left: 0; }

.carousel-control-next {
  right: 0; }

.carousel-control-prev-icon,
.carousel-control-next-icon {
  display: inline-block;
  width: 20px;
  height: 20px;
  background: transparent no-repeat center center;
  background-size: 100% 100%; }

.carousel-control-prev-icon {
  background-image: url("data:image/svg+xml;charset=utf8,%3Csvg xmlns='http://www.w3.org/2000/svg' fill='%23fff' viewBox='0 0 8 8'%3E%3Cpath d='M4 0l-4 4 4 4 1.5-1.5-2.5-2.5 2.5-2.5-1.5-1.5z'/%3E%3C/svg%3E"); }

.carousel-control-next-icon {
  background-image: url("data:image/svg+xml;charset=utf8,%3Csvg xmlns='http://www.w3.org/2000/svg' fill='%23fff' viewBox='0 0 8 8'%3E%3Cpath d='M1.5 0l-1.5 1.5 2.5 2.5-2.5 2.5 1.5 1.5 4-4-4-4z'/%3E%3C/svg%3E"); }

.carousel-indicators {
  position: absolute;
  right: 0;
  bottom: 10px;
  left: 0;
  z-index: 15;
  display: -webkit-flex;
  display: -ms-flexbox;
  display: flex;
  -webkit-justify-content: center;
      -ms-flex-pack: center;
          justify-content: center;
  padding-left: 0;
  margin-right: 15%;
  margin-left: 15%;
  list-style: none; }
  .carousel-indicators li {
    position: relative;
    -webkit-flex: 0 1 auto;
        -ms-flex: 0 1 auto;
            flex: 0 1 auto;
    width: 30px;
    height: 3px;
    margin-right: 3px;
    margin-left: 3px;
    text-indent: -999px;
    background-color: rgba(255, 255, 255, 0.5); }
    .carousel-indicators li::before {
      position: absolute;
      top: -10px;
      left: 0;
      display: inline-block;
      width: 100%;
      height: 10px;
      content: ""; }
    .carousel-indicators li::after {
      position: absolute;
      bottom: -10px;
      left: 0;
      display: inline-block;
      width: 100%;
      height: 10px;
      content: ""; }
  .carousel-indicators .active {
    background-color: #fff; }

.carousel-caption {
  position: absolute;
  right: 15%;
  bottom: 20px;
  left: 15%;
  z-index: 10;
  padding-top: 20px;
  padding-bottom: 20px;
  color: #fff;
  text-align: center; }

.align-baseline {
  vertical-align: baseline !important; }

.align-top {
  vertical-align: top !important; }

.align-middle {
  vertical-align: middle !important; }

.align-bottom {
  vertical-align: bottom !important; }

.align-text-bottom {
  vertical-align: text-bottom !important; }

.align-text-top {
  vertical-align: text-top !important; }

.bg-primary {
  background-color: #007bff !important; }

a.bg-primary:focus, a.bg-primary:hover {
  background-color: #0062cc !important; }

.bg-secondary {
  background-color: #868e96 !important; }

a.bg-secondary:focus, a.bg-secondary:hover {
  background-color: #6c757d !important; }

.bg-success {
  background-color: #28a745 !important; }

a.bg-success:focus, a.bg-success:hover {
  background-color: #1e7e34 !important; }

.bg-info {
  background-color: #17a2b8 !important; }

a.bg-info:focus, a.bg-info:hover {
  background-color: #117a8b !important; }

.bg-warning {
  background-color: #ffc107 !important; }

a.bg-warning:focus, a.bg-warning:hover {
  background-color: #d39e00 !important; }

.bg-danger {
  background-color: #dc3545 !important; }

a.bg-danger:focus, a.bg-danger:hover {
  background-color: #bd2130 !important; }

.bg-light {
  background-color: #f8f9fa !important; }

a.bg-light:focus, a.bg-light:hover {
  background-color: #dae0e5 !important; }

.bg-dark {
  background-color: #343a40 !important; }

a.bg-dark:focus, a.bg-dark:hover {
  background-color: #1d2124 !important; }

.bg-white {
  background-color: #fff !important; }

.bg-transparent {
  background-color: transparent !important; }

.border {
  border: 1px solid #e9ecef !important; }

.border-0 {
  border: 0 !important; }

.border-top-0 {
  border-top: 0 !important; }

.border-right-0 {
  border-right: 0 !important; }

.border-bottom-0 {
  border-bottom: 0 !important; }

.border-left-0 {
  border-left: 0 !important; }

.border-primary {
  border-color: #007bff !important; }

.border-secondary {
  border-color: #868e96 !important; }

.border-success {
  border-color: #28a745 !important; }

.border-info {
  border-color: #17a2b8 !important; }

.border-warning {
  border-color: #ffc107 !important; }

.border-danger {
  border-color: #dc3545 !important; }

.border-light {
  border-color: #f8f9fa !important; }

.border-dark {
  border-color: #343a40 !important; }

.border-white {
  border-color: #fff !important; }

.rounded {
  border-radius: 0.25rem !important; }

.rounded-top {
  border-top-left-radius: 0.25rem !important;
  border-top-right-radius: 0.25rem !important; }

.rounded-right {
  border-top-right-radius: 0.25rem !important;
  border-bottom-right-radius: 0.25rem !important; }

.rounded-bottom {
  border-bottom-right-radius: 0.25rem !important;
  border-bottom-left-radius: 0.25rem !important; }

.rounded-left {
  border-top-left-radius: 0.25rem !important;
  border-bottom-left-radius: 0.25rem !important; }

.rounded-circle {
  border-radius: 50%; }

.rounded-0 {
  border-radius: 0; }

.clearfix::after {
  display: block;
  clear: both;
  content: ""; }

.d-none {
  display: none !important; }

.d-inline {
  display: inline !important; }

.d-inline-block {
  display: inline-block !important; }

.d-block {
  display: block !important; }

.d-table {
  display: table !important; }

.d-table-cell {
  display: table-cell !important; }

.d-flex, button.custom, #frame, aside.left, aside.left nav > div.item, #beside, header.main, #user-account {
  display: -webkit-flex !important;
  display: -ms-flexbox !important;
  display: flex !important; }

.d-inline-flex {
  display: -webkit-inline-flex !important;
  display: -ms-inline-flexbox !important;
  display: inline-flex !important; }

@media (min-width: 576px) {
  .d-sm-none {
    display: none !important; }
  .d-sm-inline {
    display: inline !important; }
  .d-sm-inline-block {
    display: inline-block !important; }
  .d-sm-block {
    display: block !important; }
  .d-sm-table {
    display: table !important; }
  .d-sm-table-cell {
    display: table-cell !important; }
  .d-sm-flex {
    display: -webkit-flex !important;
    display: -ms-flexbox !important;
    display: flex !important; }
  .d-sm-inline-flex {
    display: -webkit-inline-flex !important;
    display: -ms-inline-flexbox !important;
    display: inline-flex !important; } }

@media (min-width: 768px) {
  .d-md-none {
    display: none !important; }
  .d-md-inline {
    display: inline !important; }
  .d-md-inline-block {
    display: inline-block !important; }
  .d-md-block {
    display: block !important; }
  .d-md-table {
    display: table !important; }
  .d-md-table-cell {
    display: table-cell !important; }
  .d-md-flex {
    display: -webkit-flex !important;
    display: -ms-flexbox !important;
    display: flex !important; }
  .d-md-inline-flex {
    display: -webkit-inline-flex !important;
    display: -ms-inline-flexbox !important;
    display: inline-flex !important; } }

@media (min-width: 992px) {
  .d-lg-none {
    display: none !important; }
  .d-lg-inline {
    display: inline !important; }
  .d-lg-inline-block {
    display: inline-block !important; }
  .d-lg-block {
    display: block !important; }
  .d-lg-table {
    display: table !important; }
  .d-lg-table-cell {
    display: table-cell !important; }
  .d-lg-flex {
    display: -webkit-flex !important;
    display: -ms-flexbox !important;
    display: flex !important; }
  .d-lg-inline-flex {
    display: -webkit-inline-flex !important;
    display: -ms-inline-flexbox !important;
    display: inline-flex !important; } }

@media (min-width: 1200px) {
  .d-xl-none {
    display: none !important; }
  .d-xl-inline {
    display: inline !important; }
  .d-xl-inline-block {
    display: inline-block !important; }
  .d-xl-block {
    display: block !important; }
  .d-xl-table {
    display: table !important; }
  .d-xl-table-cell {
    display: table-cell !important; }
  .d-xl-flex {
    display: -webkit-flex !important;
    display: -ms-flexbox !important;
    display: flex !important; }
  .d-xl-inline-flex {
    display: -webkit-inline-flex !important;
    display: -ms-inline-flexbox !important;
    display: inline-flex !important; } }

.d-print-block {
  display: none !important; }
  @media print {
    .d-print-block {
      display: block !important; } }

.d-print-inline {
  display: none !important; }
  @media print {
    .d-print-inline {
      display: inline !important; } }

.d-print-inline-block {
  display: none !important; }
  @media print {
    .d-print-inline-block {
      display: inline-block !important; } }

@media print {
  .d-print-none {
    display: none !important; } }

.embed-responsive {
  position: relative;
  display: block;
  width: 100%;
  padding: 0;
  overflow: hidden; }
  .embed-responsive::before {
    display: block;
    content: ""; }
  .embed-responsive .embed-responsive-item,
  .embed-responsive iframe,
  .embed-responsive embed,
  .embed-responsive object,
  .embed-responsive video {
    position: absolute;
    top: 0;
    bottom: 0;
    left: 0;
    width: 100%;
    height: 100%;
    border: 0; }

.embed-responsive-21by9::before {
  padding-top: 42.85714%; }

.embed-responsive-16by9::before {
  padding-top: 56.25%; }

.embed-responsive-4by3::before {
  padding-top: 75%; }

.embed-responsive-1by1::before {
  padding-top: 100%; }

.flex-row, button.custom, #frame, header.main, #user-account {
  -webkit-flex-direction: row !important;
      -ms-flex-direction: row !important;
          flex-direction: row !important; }

.flex-column, aside.left, #beside {
  -webkit-flex-direction: column !important;
      -ms-flex-direction: column !important;
          flex-direction: column !important; }

.flex-row-reverse {
  -webkit-flex-direction: row-reverse !important;
      -ms-flex-direction: row-reverse !important;
          flex-direction: row-reverse !important; }

.flex-column-reverse {
  -webkit-flex-direction: column-reverse !important;
      -ms-flex-direction: column-reverse !important;
          flex-direction: column-reverse !important; }

.flex-wrap {
  -webkit-flex-wrap: wrap !important;
      -ms-flex-wrap: wrap !important;
          flex-wrap: wrap !important; }

.flex-nowrap {
  -webkit-flex-wrap: nowrap !important;
      -ms-flex-wrap: nowrap !important;
          flex-wrap: nowrap !important; }

.flex-wrap-reverse {
  -webkit-flex-wrap: wrap-reverse !important;
      -ms-flex-wrap: wrap-reverse !important;
          flex-wrap: wrap-reverse !important; }

.justify-content-start {
  -webkit-justify-content: flex-start !important;
      -ms-flex-pack: start !important;
          justify-content: flex-start !important; }

.justify-content-end {
  -webkit-justify-content: flex-end !important;
      -ms-flex-pack: end !important;
          justify-content: flex-end !important; }

.justify-content-center, aside.left nav > div.item {
  -webkit-justify-content: center !important;
      -ms-flex-pack: center !important;
          justify-content: center !important; }

.justify-content-between {
  -webkit-justify-content: space-between !important;
      -ms-flex-pack: justify !important;
          justify-content: space-between !important; }

.justify-content-around, #user-account {
  -webkit-justify-content: space-around !important;
      -ms-flex-pack: distribute !important;
          justify-content: space-around !important; }

.align-items-start {
  -webkit-align-items: flex-start !important;
      -ms-flex-align: start !important;
              -ms-grid-row-align: flex-start !important;
          align-items: flex-start !important; }

.align-items-end {
  -webkit-align-items: flex-end !important;
      -ms-flex-align: end !important;
              -ms-grid-row-align: flex-end !important;
          align-items: flex-end !important; }

.align-items-center, aside.left, aside.left nav > div.item, header.main, #user-account {
  -webkit-align-items: center !important;
      -ms-flex-align: center !important;
              -ms-grid-row-align: center !important;
          align-items: center !important; }

.align-items-baseline {
  -webkit-align-items: baseline !important;
      -ms-flex-align: baseline !important;
              -ms-grid-row-align: baseline !important;
          align-items: baseline !important; }

.align-items-stretch, #frame {
  -webkit-align-items: stretch !important;
      -ms-flex-align: stretch !important;
              -ms-grid-row-align: stretch !important;
          align-items: stretch !important; }

.align-content-start {
  -webkit-align-content: flex-start !important;
      -ms-flex-line-pack: start !important;
          align-content: flex-start !important; }

.align-content-end {
  -webkit-align-content: flex-end !important;
      -ms-flex-line-pack: end !important;
          align-content: flex-end !important; }

.align-content-center {
  -webkit-align-content: center !important;
      -ms-flex-line-pack: center !important;
          align-content: center !important; }

.align-content-between {
  -webkit-align-content: space-between !important;
      -ms-flex-line-pack: justify !important;
          align-content: space-between !important; }

.align-content-around {
  -webkit-align-content: space-around !important;
      -ms-flex-line-pack: distribute !important;
          align-content: space-around !important; }

.align-content-stretch {
  -webkit-align-content: stretch !important;
      -ms-flex-line-pack: stretch !important;
          align-content: stretch !important; }

.align-self-auto {
  -webkit-align-self: auto !important;
      -ms-flex-item-align: auto !important;
          align-self: auto !important; }

.align-self-start {
  -webkit-align-self: flex-start !important;
      -ms-flex-item-align: start !important;
          align-self: flex-start !important; }

.align-self-end {
  -webkit-align-self: flex-end !important;
      -ms-flex-item-align: end !important;
          align-self: flex-end !important; }

.align-self-center {
  -webkit-align-self: center !important;
      -ms-flex-item-align: center !important;
          align-self: center !important; }

.align-self-baseline {
  -webkit-align-self: baseline !important;
      -ms-flex-item-align: baseline !important;
          align-self: baseline !important; }

.align-self-stretch {
  -webkit-align-self: stretch !important;
      -ms-flex-item-align: stretch !important;
          align-self: stretch !important; }

@media (min-width: 576px) {
  .flex-sm-row {
    -webkit-flex-direction: row !important;
        -ms-flex-direction: row !important;
            flex-direction: row !important; }
  .flex-sm-column {
    -webkit-flex-direction: column !important;
        -ms-flex-direction: column !important;
            flex-direction: column !important; }
  .flex-sm-row-reverse {
    -webkit-flex-direction: row-reverse !important;
        -ms-flex-direction: row-reverse !important;
            flex-direction: row-reverse !important; }
  .flex-sm-column-reverse {
    -webkit-flex-direction: column-reverse !important;
        -ms-flex-direction: column-reverse !important;
            flex-direction: column-reverse !important; }
  .flex-sm-wrap {
    -webkit-flex-wrap: wrap !important;
        -ms-flex-wrap: wrap !important;
            flex-wrap: wrap !important; }
  .flex-sm-nowrap {
    -webkit-flex-wrap: nowrap !important;
        -ms-flex-wrap: nowrap !important;
            flex-wrap: nowrap !important; }
  .flex-sm-wrap-reverse {
    -webkit-flex-wrap: wrap-reverse !important;
        -ms-flex-wrap: wrap-reverse !important;
            flex-wrap: wrap-reverse !important; }
  .justify-content-sm-start {
    -webkit-justify-content: flex-start !important;
        -ms-flex-pack: start !important;
            justify-content: flex-start !important; }
  .justify-content-sm-end {
    -webkit-justify-content: flex-end !important;
        -ms-flex-pack: end !important;
            justify-content: flex-end !important; }
  .justify-content-sm-center {
    -webkit-justify-content: center !important;
        -ms-flex-pack: center !important;
            justify-content: center !important; }
  .justify-content-sm-between {
    -webkit-justify-content: space-between !important;
        -ms-flex-pack: justify !important;
            justify-content: space-between !important; }
  .justify-content-sm-around {
    -webkit-justify-content: space-around !important;
        -ms-flex-pack: distribute !important;
            justify-content: space-around !important; }
  .align-items-sm-start {
    -webkit-align-items: flex-start !important;
        -ms-flex-align: start !important;
                -ms-grid-row-align: flex-start !important;
            align-items: flex-start !important; }
  .align-items-sm-end {
    -webkit-align-items: flex-end !important;
        -ms-flex-align: end !important;
                -ms-grid-row-align: flex-end !important;
            align-items: flex-end !important; }
  .align-items-sm-center {
    -webkit-align-items: center !important;
        -ms-flex-align: center !important;
                -ms-grid-row-align: center !important;
            align-items: center !important; }
  .align-items-sm-baseline {
    -webkit-align-items: baseline !important;
        -ms-flex-align: baseline !important;
                -ms-grid-row-align: baseline !important;
            align-items: baseline !important; }
  .align-items-sm-stretch {
    -webkit-align-items: stretch !important;
        -ms-flex-align: stretch !important;
                -ms-grid-row-align: stretch !important;
            align-items: stretch !important; }
  .align-content-sm-start {
    -webkit-align-content: flex-start !important;
        -ms-flex-line-pack: start !important;
            align-content: flex-start !important; }
  .align-content-sm-end {
    -webkit-align-content: flex-end !important;
        -ms-flex-line-pack: end !important;
            align-content: flex-end !important; }
  .align-content-sm-center {
    -webkit-align-content: center !important;
        -ms-flex-line-pack: center !important;
            align-content: center !important; }
  .align-content-sm-between {
    -webkit-align-content: space-between !important;
        -ms-flex-line-pack: justify !important;
            align-content: space-between !important; }
  .align-content-sm-around {
    -webkit-align-content: space-around !important;
        -ms-flex-line-pack: distribute !important;
            align-content: space-around !important; }
  .align-content-sm-stretch {
    -webkit-align-content: stretch !important;
        -ms-flex-line-pack: stretch !important;
            align-content: stretch !important; }
  .align-self-sm-auto {
    -webkit-align-self: auto !important;
        -ms-flex-item-align: auto !important;
            align-self: auto !important; }
  .align-self-sm-start {
    -webkit-align-self: flex-start !important;
        -ms-flex-item-align: start !important;
            align-self: flex-start !important; }
  .align-self-sm-end {
    -webkit-align-self: flex-end !important;
        -ms-flex-item-align: end !important;
            align-self: flex-end !important; }
  .align-self-sm-center {
    -webkit-align-self: center !important;
        -ms-flex-item-align: center !important;
            align-self: center !important; }
  .align-self-sm-baseline {
    -webkit-align-self: baseline !important;
        -ms-flex-item-align: baseline !important;
            align-self: baseline !important; }
  .align-self-sm-stretch {
    -webkit-align-self: stretch !important;
        -ms-flex-item-align: stretch !important;
            align-self: stretch !important; } }

@media (min-width: 768px) {
  .flex-md-row {
    -webkit-flex-direction: row !important;
        -ms-flex-direction: row !important;
            flex-direction: row !important; }
  .flex-md-column {
    -webkit-flex-direction: column !important;
        -ms-flex-direction: column !important;
            flex-direction: column !important; }
  .flex-md-row-reverse {
    -webkit-flex-direction: row-reverse !important;
        -ms-flex-direction: row-reverse !important;
            flex-direction: row-reverse !important; }
  .flex-md-column-reverse {
    -webkit-flex-direction: column-reverse !important;
        -ms-flex-direction: column-reverse !important;
            flex-direction: column-reverse !important; }
  .flex-md-wrap {
    -webkit-flex-wrap: wrap !important;
        -ms-flex-wrap: wrap !important;
            flex-wrap: wrap !important; }
  .flex-md-nowrap {
    -webkit-flex-wrap: nowrap !important;
        -ms-flex-wrap: nowrap !important;
            flex-wrap: nowrap !important; }
  .flex-md-wrap-reverse {
    -webkit-flex-wrap: wrap-reverse !important;
        -ms-flex-wrap: wrap-reverse !important;
            flex-wrap: wrap-reverse !important; }
  .justify-content-md-start {
    -webkit-justify-content: flex-start !important;
        -ms-flex-pack: start !important;
            justify-content: flex-start !important; }
  .justify-content-md-end {
    -webkit-justify-content: flex-end !important;
        -ms-flex-pack: end !important;
            justify-content: flex-end !important; }
  .justify-content-md-center {
    -webkit-justify-content: center !important;
        -ms-flex-pack: center !important;
            justify-content: center !important; }
  .justify-content-md-between {
    -webkit-justify-content: space-between !important;
        -ms-flex-pack: justify !important;
            justify-content: space-between !important; }
  .justify-content-md-around {
    -webkit-justify-content: space-around !important;
        -ms-flex-pack: distribute !important;
            justify-content: space-around !important; }
  .align-items-md-start {
    -webkit-align-items: flex-start !important;
        -ms-flex-align: start !important;
                -ms-grid-row-align: flex-start !important;
            align-items: flex-start !important; }
  .align-items-md-end {
    -webkit-align-items: flex-end !important;
        -ms-flex-align: end !important;
                -ms-grid-row-align: flex-end !important;
            align-items: flex-end !important; }
  .align-items-md-center {
    -webkit-align-items: center !important;
        -ms-flex-align: center !important;
                -ms-grid-row-align: center !important;
            align-items: center !important; }
  .align-items-md-baseline {
    -webkit-align-items: baseline !important;
        -ms-flex-align: baseline !important;
                -ms-grid-row-align: baseline !important;
            align-items: baseline !important; }
  .align-items-md-stretch {
    -webkit-align-items: stretch !important;
        -ms-flex-align: stretch !important;
                -ms-grid-row-align: stretch !important;
            align-items: stretch !important; }
  .align-content-md-start {
    -webkit-align-content: flex-start !important;
        -ms-flex-line-pack: start !important;
            align-content: flex-start !important; }
  .align-content-md-end {
    -webkit-align-content: flex-end !important;
        -ms-flex-line-pack: end !important;
            align-content: flex-end !important; }
  .align-content-md-center {
    -webkit-align-content: center !important;
        -ms-flex-line-pack: center !important;
            align-content: center !important; }
  .align-content-md-between {
    -webkit-align-content: space-between !important;
        -ms-flex-line-pack: justify !important;
            align-content: space-between !important; }
  .align-content-md-around {
    -webkit-align-content: space-around !important;
        -ms-flex-line-pack: distribute !important;
            align-content: space-around !important; }
  .align-content-md-stretch {
    -webkit-align-content: stretch !important;
        -ms-flex-line-pack: stretch !important;
            align-content: stretch !important; }
  .align-self-md-auto {
    -webkit-align-self: auto !important;
        -ms-flex-item-align: auto !important;
            align-self: auto !important; }
  .align-self-md-start {
    -webkit-align-self: flex-start !important;
        -ms-flex-item-align: start !important;
            align-self: flex-start !important; }
  .align-self-md-end {
    -webkit-align-self: flex-end !important;
        -ms-flex-item-align: end !important;
            align-self: flex-end !important; }
  .align-self-md-center {
    -webkit-align-self: center !important;
        -ms-flex-item-align: center !important;
            align-self: center !important; }
  .align-self-md-baseline {
    -webkit-align-self: baseline !important;
        -ms-flex-item-align: baseline !important;
            align-self: baseline !important; }
  .align-self-md-stretch {
    -webkit-align-self: stretch !important;
        -ms-flex-item-align: stretch !important;
            align-self: stretch !important; } }

@media (min-width: 992px) {
  .flex-lg-row {
    -webkit-flex-direction: row !important;
        -ms-flex-direction: row !important;
            flex-direction: row !important; }
  .flex-lg-column {
    -webkit-flex-direction: column !important;
        -ms-flex-direction: column !important;
            flex-direction: column !important; }
  .flex-lg-row-reverse {
    -webkit-flex-direction: row-reverse !important;
        -ms-flex-direction: row-reverse !important;
            flex-direction: row-reverse !important; }
  .flex-lg-column-reverse {
    -webkit-flex-direction: column-reverse !important;
        -ms-flex-direction: column-reverse !important;
            flex-direction: column-reverse !important; }
  .flex-lg-wrap {
    -webkit-flex-wrap: wrap !important;
        -ms-flex-wrap: wrap !important;
            flex-wrap: wrap !important; }
  .flex-lg-nowrap {
    -webkit-flex-wrap: nowrap !important;
        -ms-flex-wrap: nowrap !important;
            flex-wrap: nowrap !important; }
  .flex-lg-wrap-reverse {
    -webkit-flex-wrap: wrap-reverse !important;
        -ms-flex-wrap: wrap-reverse !important;
            flex-wrap: wrap-reverse !important; }
  .justify-content-lg-start {
    -webkit-justify-content: flex-start !important;
        -ms-flex-pack: start !important;
            justify-content: flex-start !important; }
  .justify-content-lg-end {
    -webkit-justify-content: flex-end !important;
        -ms-flex-pack: end !important;
            justify-content: flex-end !important; }
  .justify-content-lg-center {
    -webkit-justify-content: center !important;
        -ms-flex-pack: center !important;
            justify-content: center !important; }
  .justify-content-lg-between {
    -webkit-justify-content: space-between !important;
        -ms-flex-pack: justify !important;
            justify-content: space-between !important; }
  .justify-content-lg-around {
    -webkit-justify-content: space-around !important;
        -ms-flex-pack: distribute !important;
            justify-content: space-around !important; }
  .align-items-lg-start {
    -webkit-align-items: flex-start !important;
        -ms-flex-align: start !important;
                -ms-grid-row-align: flex-start !important;
            align-items: flex-start !important; }
  .align-items-lg-end {
    -webkit-align-items: flex-end !important;
        -ms-flex-align: end !important;
                -ms-grid-row-align: flex-end !important;
            align-items: flex-end !important; }
  .align-items-lg-center {
    -webkit-align-items: center !important;
        -ms-flex-align: center !important;
                -ms-grid-row-align: center !important;
            align-items: center !important; }
  .align-items-lg-baseline {
    -webkit-align-items: baseline !important;
        -ms-flex-align: baseline !important;
                -ms-grid-row-align: baseline !important;
            align-items: baseline !important; }
  .align-items-lg-stretch {
    -webkit-align-items: stretch !important;
        -ms-flex-align: stretch !important;
                -ms-grid-row-align: stretch !important;
            align-items: stretch !important; }
  .align-content-lg-start {
    -webkit-align-content: flex-start !important;
        -ms-flex-line-pack: start !important;
            align-content: flex-start !important; }
  .align-content-lg-end {
    -webkit-align-content: flex-end !important;
        -ms-flex-line-pack: end !important;
            align-content: flex-end !important; }
  .align-content-lg-center {
    -webkit-align-content: center !important;
        -ms-flex-line-pack: center !important;
            align-content: center !important; }
  .align-content-lg-between {
    -webkit-align-content: space-between !important;
        -ms-flex-line-pack: justify !important;
            align-content: space-between !important; }
  .align-content-lg-around {
    -webkit-align-content: space-around !important;
        -ms-flex-line-pack: distribute !important;
            align-content: space-around !important; }
  .align-content-lg-stretch {
    -webkit-align-content: stretch !important;
        -ms-flex-line-pack: stretch !important;
            align-content: stretch !important; }
  .align-self-lg-auto {
    -webkit-align-self: auto !important;
        -ms-flex-item-align: auto !important;
            align-self: auto !important; }
  .align-self-lg-start {
    -webkit-align-self: flex-start !important;
        -ms-flex-item-align: start !important;
            align-self: flex-start !important; }
  .align-self-lg-end {
    -webkit-align-self: flex-end !important;
        -ms-flex-item-align: end !important;
            align-self: flex-end !important; }
  .align-self-lg-center {
    -webkit-align-self: center !important;
        -ms-flex-item-align: center !important;
            align-self: center !important; }
  .align-self-lg-baseline {
    -webkit-align-self: baseline !important;
        -ms-flex-item-align: baseline !important;
            align-self: baseline !important; }
  .align-self-lg-stretch {
    -webkit-align-self: stretch !important;
        -ms-flex-item-align: stretch !important;
            align-self: stretch !important; } }

@media (min-width: 1200px) {
  .flex-xl-row {
    -webkit-flex-direction: row !important;
        -ms-flex-direction: row !important;
            flex-direction: row !important; }
  .flex-xl-column {
    -webkit-flex-direction: column !important;
        -ms-flex-direction: column !important;
            flex-direction: column !important; }
  .flex-xl-row-reverse {
    -webkit-flex-direction: row-reverse !important;
        -ms-flex-direction: row-reverse !important;
            flex-direction: row-reverse !important; }
  .flex-xl-column-reverse {
    -webkit-flex-direction: column-reverse !important;
        -ms-flex-direction: column-reverse !important;
            flex-direction: column-reverse !important; }
  .flex-xl-wrap {
    -webkit-flex-wrap: wrap !important;
        -ms-flex-wrap: wrap !important;
            flex-wrap: wrap !important; }
  .flex-xl-nowrap {
    -webkit-flex-wrap: nowrap !important;
        -ms-flex-wrap: nowrap !important;
            flex-wrap: nowrap !important; }
  .flex-xl-wrap-reverse {
    -webkit-flex-wrap: wrap-reverse !important;
        -ms-flex-wrap: wrap-reverse !important;
            flex-wrap: wrap-reverse !important; }
  .justify-content-xl-start {
    -webkit-justify-content: flex-start !important;
        -ms-flex-pack: start !important;
            justify-content: flex-start !important; }
  .justify-content-xl-end {
    -webkit-justify-content: flex-end !important;
        -ms-flex-pack: end !important;
            justify-content: flex-end !important; }
  .justify-content-xl-center {
    -webkit-justify-content: center !important;
        -ms-flex-pack: center !important;
            justify-content: center !important; }
  .justify-content-xl-between {
    -webkit-justify-content: space-between !important;
        -ms-flex-pack: justify !important;
            justify-content: space-between !important; }
  .justify-content-xl-around {
    -webkit-justify-content: space-around !important;
        -ms-flex-pack: distribute !important;
            justify-content: space-around !important; }
  .align-items-xl-start {
    -webkit-align-items: flex-start !important;
        -ms-flex-align: start !important;
                -ms-grid-row-align: flex-start !important;
            align-items: flex-start !important; }
  .align-items-xl-end {
    -webkit-align-items: flex-end !important;
        -ms-flex-align: end !important;
                -ms-grid-row-align: flex-end !important;
            align-items: flex-end !important; }
  .align-items-xl-center {
    -webkit-align-items: center !important;
        -ms-flex-align: center !important;
                -ms-grid-row-align: center !important;
            align-items: center !important; }
  .align-items-xl-baseline {
    -webkit-align-items: baseline !important;
        -ms-flex-align: baseline !important;
                -ms-grid-row-align: baseline !important;
            align-items: baseline !important; }
  .align-items-xl-stretch {
    -webkit-align-items: stretch !important;
        -ms-flex-align: stretch !important;
                -ms-grid-row-align: stretch !important;
            align-items: stretch !important; }
  .align-content-xl-start {
    -webkit-align-content: flex-start !important;
        -ms-flex-line-pack: start !important;
            align-content: flex-start !important; }
  .align-content-xl-end {
    -webkit-align-content: flex-end !important;
        -ms-flex-line-pack: end !important;
            align-content: flex-end !important; }
  .align-content-xl-center {
    -webkit-align-content: center !important;
        -ms-flex-line-pack: center !important;
            align-content: center !important; }
  .align-content-xl-between {
    -webkit-align-content: space-between !important;
        -ms-flex-line-pack: justify !important;
            align-content: space-between !important; }
  .align-content-xl-around {
    -webkit-align-content: space-around !important;
        -ms-flex-line-pack: distribute !important;
            align-content: space-around !important; }
  .align-content-xl-stretch {
    -webkit-align-content: stretch !important;
        -ms-flex-line-pack: stretch !important;
            align-content: stretch !important; }
  .align-self-xl-auto {
    -webkit-align-self: auto !important;
        -ms-flex-item-align: auto !important;
            align-self: auto !important; }
  .align-self-xl-start {
    -webkit-align-self: flex-start !important;
        -ms-flex-item-align: start !important;
            align-self: flex-start !important; }
  .align-self-xl-end {
    -webkit-align-self: flex-end !important;
        -ms-flex-item-align: end !important;
            align-self: flex-end !important; }
  .align-self-xl-center {
    -webkit-align-self: center !important;
        -ms-flex-item-align: center !important;
            align-self: center !important; }
  .align-self-xl-baseline {
    -webkit-align-self: baseline !important;
        -ms-flex-item-align: baseline !important;
            align-self: baseline !important; }
  .align-self-xl-stretch {
    -webkit-align-self: stretch !important;
        -ms-flex-item-align: stretch !important;
            align-self: stretch !important; } }

.float-left {
  float: left !important; }

.float-right {
  float: right !important; }

.float-none {
  float: none !important; }

@media (min-width: 576px) {
  .float-sm-left {
    float: left !important; }
  .float-sm-right {
    float: right !important; }
  .float-sm-none {
    float: none !important; } }

@media (min-width: 768px) {
  .float-md-left {
    float: left !important; }
  .float-md-right {
    float: right !important; }
  .float-md-none {
    float: none !important; } }

@media (min-width: 992px) {
  .float-lg-left {
    float: left !important; }
  .float-lg-right {
    float: right !important; }
  .float-lg-none {
    float: none !important; } }

@media (min-width: 1200px) {
  .float-xl-left {
    float: left !important; }
  .float-xl-right {
    float: right !important; }
  .float-xl-none {
    float: none !important; } }

.position-static {
  position: static !important; }

.position-relative {
  position: relative !important; }

.position-absolute {
  position: absolute !important; }

.position-fixed {
  position: fixed !important; }

.position-sticky {
  position: -webkit-sticky !important;
  position: sticky !important; }

.fixed-top {
  position: fixed;
  top: 0;
  right: 0;
  left: 0;
  z-index: 1030; }

.fixed-bottom {
  position: fixed;
  right: 0;
  bottom: 0;
  left: 0;
  z-index: 1030; }

@supports ((position: -webkit-sticky) or (position: sticky)) {
  .sticky-top {
    position: -webkit-sticky;
    position: sticky;
    top: 0;
    z-index: 1020; } }

.sr-only {
  position: absolute;
  width: 1px;
  height: 1px;
  padding: 0;
  overflow: hidden;
  clip: rect(0, 0, 0, 0);
  white-space: nowrap;
  -webkit-clip-path: inset(50%);
          clip-path: inset(50%);
  border: 0; }

.sr-only-focusable:active, .sr-only-focusable:focus {
  position: static;
  width: auto;
  height: auto;
  overflow: visible;
  clip: auto;
  white-space: normal;
  -webkit-clip-path: none;
          clip-path: none; }

.w-25 {
  width: 25% !important; }

.w-50 {
  width: 50% !important; }

.w-75 {
  width: 75% !important; }

.w-100 {
  width: 100% !important; }

.h-25 {
  height: 25% !important; }

.h-50 {
  height: 50% !important; }

.h-75 {
  height: 75% !important; }

.h-100 {
  height: 100% !important; }

.mw-100 {
  max-width: 100% !important; }

.mh-100 {
  max-height: 100% !important; }

.m-0 {
  margin: 0 !important; }

.mt-0,
.my-0 {
  margin-top: 0 !important; }

.mr-0,
.mx-0 {
  margin-right: 0 !important; }

.mb-0,
.my-0 {
  margin-bottom: 0 !important; }

.ml-0,
.mx-0 {
  margin-left: 0 !important; }

.m-1 {
  margin: 0.25rem !important; }

.mt-1,
.my-1 {
  margin-top: 0.25rem !important; }

.mr-1,
.mx-1 {
  margin-right: 0.25rem !important; }

.mb-1,
.my-1 {
  margin-bottom: 0.25rem !important; }

.ml-1,
.mx-1 {
  margin-left: 0.25rem !important; }

.m-2 {
  margin: 0.5rem !important; }

.mt-2,
.my-2 {
  margin-top: 0.5rem !important; }

.mr-2,
.mx-2 {
  margin-right: 0.5rem !important; }

.mb-2,
.my-2 {
  margin-bottom: 0.5rem !important; }

.ml-2,
.mx-2 {
  margin-left: 0.5rem !important; }

.m-3 {
  margin: 1rem !important; }

.mt-3,
.my-3 {
  margin-top: 1rem !important; }

.mr-3,
.mx-3 {
  margin-right: 1rem !important; }

.mb-3,
.my-3 {
  margin-bottom: 1rem !important; }

.ml-3,
.mx-3 {
  margin-left: 1rem !important; }

.m-4 {
  margin: 1.5rem !important; }

.mt-4,
.my-4 {
  margin-top: 1.5rem !important; }

.mr-4,
.mx-4 {
  margin-right: 1.5rem !important; }

.mb-4,
.my-4 {
  margin-bottom: 1.5rem !important; }

.ml-4,
.mx-4 {
  margin-left: 1.5rem !important; }

.m-5 {
  margin: 3rem !important; }

.mt-5,
.my-5 {
  margin-top: 3rem !important; }

.mr-5,
.mx-5 {
  margin-right: 3rem !important; }

.mb-5,
.my-5 {
  margin-bottom: 3rem !important; }

.ml-5,
.mx-5 {
  margin-left: 3rem !important; }

.p-0 {
  padding: 0 !important; }

.pt-0,
.py-0 {
  padding-top: 0 !important; }

.pr-0,
.px-0 {
  padding-right: 0 !important; }

.pb-0,
.py-0 {
  padding-bottom: 0 !important; }

.pl-0,
.px-0 {
  padding-left: 0 !important; }

.p-1 {
  padding: 0.25rem !important; }

.pt-1,
.py-1 {
  padding-top: 0.25rem !important; }

.pr-1,
.px-1 {
  padding-right: 0.25rem !important; }

.pb-1,
.py-1 {
  padding-bottom: 0.25rem !important; }

.pl-1,
.px-1 {
  padding-left: 0.25rem !important; }

.p-2 {
  padding: 0.5rem !important; }

.pt-2,
.py-2 {
  padding-top: 0.5rem !important; }

.pr-2,
.px-2 {
  padding-right: 0.5rem !important; }

.pb-2,
.py-2 {
  padding-bottom: 0.5rem !important; }

.pl-2,
.px-2 {
  padding-left: 0.5rem !important; }

.p-3 {
  padding: 1rem !important; }

.pt-3,
.py-3 {
  padding-top: 1rem !important; }

.pr-3,
.px-3 {
  padding-right: 1rem !important; }

.pb-3,
.py-3 {
  padding-bottom: 1rem !important; }

.pl-3,
.px-3 {
  padding-left: 1rem !important; }

.p-4 {
  padding: 1.5rem !important; }

.pt-4,
.py-4 {
  padding-top: 1.5rem !important; }

.pr-4,
.px-4 {
  padding-right: 1.5rem !important; }

.pb-4,
.py-4 {
  padding-bottom: 1.5rem !important; }

.pl-4,
.px-4 {
  padding-left: 1.5rem !important; }

.p-5 {
  padding: 3rem !important; }

.pt-5,
.py-5 {
  padding-top: 3rem !important; }

.pr-5,
.px-5 {
  padding-right: 3rem !important; }

.pb-5,
.py-5 {
  padding-bottom: 3rem !important; }

.pl-5,
.px-5 {
  padding-left: 3rem !important; }

.m-auto {
  margin: auto !important; }

.mt-auto,
.my-auto {
  margin-top: auto !important; }

.mr-auto,
.mx-auto {
  margin-right: auto !important; }

.mb-auto,
.my-auto {
  margin-bottom: auto !important; }

.ml-auto,
.mx-auto {
  margin-left: auto !important; }

@media (min-width: 576px) {
  .m-sm-0 {
    margin: 0 !important; }
  .mt-sm-0,
  .my-sm-0 {
    margin-top: 0 !important; }
  .mr-sm-0,
  .mx-sm-0 {
    margin-right: 0 !important; }
  .mb-sm-0,
  .my-sm-0 {
    margin-bottom: 0 !important; }
  .ml-sm-0,
  .mx-sm-0 {
    margin-left: 0 !important; }
  .m-sm-1 {
    margin: 0.25rem !important; }
  .mt-sm-1,
  .my-sm-1 {
    margin-top: 0.25rem !important; }
  .mr-sm-1,
  .mx-sm-1 {
    margin-right: 0.25rem !important; }
  .mb-sm-1,
  .my-sm-1 {
    margin-bottom: 0.25rem !important; }
  .ml-sm-1,
  .mx-sm-1 {
    margin-left: 0.25rem !important; }
  .m-sm-2 {
    margin: 0.5rem !important; }
  .mt-sm-2,
  .my-sm-2 {
    margin-top: 0.5rem !important; }
  .mr-sm-2,
  .mx-sm-2 {
    margin-right: 0.5rem !important; }
  .mb-sm-2,
  .my-sm-2 {
    margin-bottom: 0.5rem !important; }
  .ml-sm-2,
  .mx-sm-2 {
    margin-left: 0.5rem !important; }
  .m-sm-3 {
    margin: 1rem !important; }
  .mt-sm-3,
  .my-sm-3 {
    margin-top: 1rem !important; }
  .mr-sm-3,
  .mx-sm-3 {
    margin-right: 1rem !important; }
  .mb-sm-3,
  .my-sm-3 {
    margin-bottom: 1rem !important; }
  .ml-sm-3,
  .mx-sm-3 {
    margin-left: 1rem !important; }
  .m-sm-4 {
    margin: 1.5rem !important; }
  .mt-sm-4,
  .my-sm-4 {
    margin-top: 1.5rem !important; }
  .mr-sm-4,
  .mx-sm-4 {
    margin-right: 1.5rem !important; }
  .mb-sm-4,
  .my-sm-4 {
    margin-bottom: 1.5rem !important; }
  .ml-sm-4,
  .mx-sm-4 {
    margin-left: 1.5rem !important; }
  .m-sm-5 {
    margin: 3rem !important; }
  .mt-sm-5,
  .my-sm-5 {
    margin-top: 3rem !important; }
  .mr-sm-5,
  .mx-sm-5 {
    margin-right: 3rem !important; }
  .mb-sm-5,
  .my-sm-5 {
    margin-bottom: 3rem !important; }
  .ml-sm-5,
  .mx-sm-5 {
    margin-left: 3rem !important; }
  .p-sm-0 {
    padding: 0 !important; }
  .pt-sm-0,
  .py-sm-0 {
    padding-top: 0 !important; }
  .pr-sm-0,
  .px-sm-0 {
    padding-right: 0 !important; }
  .pb-sm-0,
  .py-sm-0 {
    padding-bottom: 0 !important; }
  .pl-sm-0,
  .px-sm-0 {
    padding-left: 0 !important; }
  .p-sm-1 {
    padding: 0.25rem !important; }
  .pt-sm-1,
  .py-sm-1 {
    padding-top: 0.25rem !important; }
  .pr-sm-1,
  .px-sm-1 {
    padding-right: 0.25rem !important; }
  .pb-sm-1,
  .py-sm-1 {
    padding-bottom: 0.25rem !important; }
  .pl-sm-1,
  .px-sm-1 {
    padding-left: 0.25rem !important; }
  .p-sm-2 {
    padding: 0.5rem !important; }
  .pt-sm-2,
  .py-sm-2 {
    padding-top: 0.5rem !important; }
  .pr-sm-2,
  .px-sm-2 {
    padding-right: 0.5rem !important; }
  .pb-sm-2,
  .py-sm-2 {
    padding-bottom: 0.5rem !important; }
  .pl-sm-2,
  .px-sm-2 {
    padding-left: 0.5rem !important; }
  .p-sm-3 {
    padding: 1rem !important; }
  .pt-sm-3,
  .py-sm-3 {
    padding-top: 1rem !important; }
  .pr-sm-3,
  .px-sm-3 {
    padding-right: 1rem !important; }
  .pb-sm-3,
  .py-sm-3 {
    padding-bottom: 1rem !important; }
  .pl-sm-3,
  .px-sm-3 {
    padding-left: 1rem !important; }
  .p-sm-4 {
    padding: 1.5rem !important; }
  .pt-sm-4,
  .py-sm-4 {
    padding-top: 1.5rem !important; }
  .pr-sm-4,
  .px-sm-4 {
    padding-right: 1.5rem !important; }
  .pb-sm-4,
  .py-sm-4 {
    padding-bottom: 1.5rem !important; }
  .pl-sm-4,
  .px-sm-4 {
    padding-left: 1.5rem !important; }
  .p-sm-5 {
    padding: 3rem !important; }
  .pt-sm-5,
  .py-sm-5 {
    padding-top: 3rem !important; }
  .pr-sm-5,
  .px-sm-5 {
    padding-right: 3rem !important; }
  .pb-sm-5,
  .py-sm-5 {
    padding-bottom: 3rem !important; }
  .pl-sm-5,
  .px-sm-5 {
    padding-left: 3rem !important; }
  .m-sm-auto {
    margin: auto !important; }
  .mt-sm-auto,
  .my-sm-auto {
    margin-top: auto !important; }
  .mr-sm-auto,
  .mx-sm-auto {
    margin-right: auto !important; }
  .mb-sm-auto,
  .my-sm-auto {
    margin-bottom: auto !important; }
  .ml-sm-auto,
  .mx-sm-auto {
    margin-left: auto !important; } }

@media (min-width: 768px) {
  .m-md-0 {
    margin: 0 !important; }
  .mt-md-0,
  .my-md-0 {
    margin-top: 0 !important; }
  .mr-md-0,
  .mx-md-0 {
    margin-right: 0 !important; }
  .mb-md-0,
  .my-md-0 {
    margin-bottom: 0 !important; }
  .ml-md-0,
  .mx-md-0 {
    margin-left: 0 !important; }
  .m-md-1 {
    margin: 0.25rem !important; }
  .mt-md-1,
  .my-md-1 {
    margin-top: 0.25rem !important; }
  .mr-md-1,
  .mx-md-1 {
    margin-right: 0.25rem !important; }
  .mb-md-1,
  .my-md-1 {
    margin-bottom: 0.25rem !important; }
  .ml-md-1,
  .mx-md-1 {
    margin-left: 0.25rem !important; }
  .m-md-2 {
    margin: 0.5rem !important; }
  .mt-md-2,
  .my-md-2 {
    margin-top: 0.5rem !important; }
  .mr-md-2,
  .mx-md-2 {
    margin-right: 0.5rem !important; }
  .mb-md-2,
  .my-md-2 {
    margin-bottom: 0.5rem !important; }
  .ml-md-2,
  .mx-md-2 {
    margin-left: 0.5rem !important; }
  .m-md-3 {
    margin: 1rem !important; }
  .mt-md-3,
  .my-md-3 {
    margin-top: 1rem !important; }
  .mr-md-3,
  .mx-md-3 {
    margin-right: 1rem !important; }
  .mb-md-3,
  .my-md-3 {
    margin-bottom: 1rem !important; }
  .ml-md-3,
  .mx-md-3 {
    margin-left: 1rem !important; }
  .m-md-4 {
    margin: 1.5rem !important; }
  .mt-md-4,
  .my-md-4 {
    margin-top: 1.5rem !important; }
  .mr-md-4,
  .mx-md-4 {
    margin-right: 1.5rem !important; }
  .mb-md-4,
  .my-md-4 {
    margin-bottom: 1.5rem !important; }
  .ml-md-4,
  .mx-md-4 {
    margin-left: 1.5rem !important; }
  .m-md-5 {
    margin: 3rem !important; }
  .mt-md-5,
  .my-md-5 {
    margin-top: 3rem !important; }
  .mr-md-5,
  .mx-md-5 {
    margin-right: 3rem !important; }
  .mb-md-5,
  .my-md-5 {
    margin-bottom: 3rem !important; }
  .ml-md-5,
  .mx-md-5 {
    margin-left: 3rem !important; }
  .p-md-0 {
    padding: 0 !important; }
  .pt-md-0,
  .py-md-0 {
    padding-top: 0 !important; }
  .pr-md-0,
  .px-md-0 {
    padding-right: 0 !important; }
  .pb-md-0,
  .py-md-0 {
    padding-bottom: 0 !important; }
  .pl-md-0,
  .px-md-0 {
    padding-left: 0 !important; }
  .p-md-1 {
    padding: 0.25rem !important; }
  .pt-md-1,
  .py-md-1 {
    padding-top: 0.25rem !important; }
  .pr-md-1,
  .px-md-1 {
    padding-right: 0.25rem !important; }
  .pb-md-1,
  .py-md-1 {
    padding-bottom: 0.25rem !important; }
  .pl-md-1,
  .px-md-1 {
    padding-left: 0.25rem !important; }
  .p-md-2 {
    padding: 0.5rem !important; }
  .pt-md-2,
  .py-md-2 {
    padding-top: 0.5rem !important; }
  .pr-md-2,
  .px-md-2 {
    padding-right: 0.5rem !important; }
  .pb-md-2,
  .py-md-2 {
    padding-bottom: 0.5rem !important; }
  .pl-md-2,
  .px-md-2 {
    padding-left: 0.5rem !important; }
  .p-md-3 {
    padding: 1rem !important; }
  .pt-md-3,
  .py-md-3 {
    padding-top: 1rem !important; }
  .pr-md-3,
  .px-md-3 {
    padding-right: 1rem !important; }
  .pb-md-3,
  .py-md-3 {
    padding-bottom: 1rem !important; }
  .pl-md-3,
  .px-md-3 {
    padding-left: 1rem !important; }
  .p-md-4 {
    padding: 1.5rem !important; }
  .pt-md-4,
  .py-md-4 {
    padding-top: 1.5rem !important; }
  .pr-md-4,
  .px-md-4 {
    padding-right: 1.5rem !important; }
  .pb-md-4,
  .py-md-4 {
    padding-bottom: 1.5rem !important; }
  .pl-md-4,
  .px-md-4 {
    padding-left: 1.5rem !important; }
  .p-md-5 {
    padding: 3rem !important; }
  .pt-md-5,
  .py-md-5 {
    padding-top: 3rem !important; }
  .pr-md-5,
  .px-md-5 {
    padding-right: 3rem !important; }
  .pb-md-5,
  .py-md-5 {
    padding-bottom: 3rem !important; }
  .pl-md-5,
  .px-md-5 {
    padding-left: 3rem !important; }
  .m-md-auto {
    margin: auto !important; }
  .mt-md-auto,
  .my-md-auto {
    margin-top: auto !important; }
  .mr-md-auto,
  .mx-md-auto {
    margin-right: auto !important; }
  .mb-md-auto,
  .my-md-auto {
    margin-bottom: auto !important; }
  .ml-md-auto,
  .mx-md-auto {
    margin-left: auto !important; } }

@media (min-width: 992px) {
  .m-lg-0 {
    margin: 0 !important; }
  .mt-lg-0,
  .my-lg-0 {
    margin-top: 0 !important; }
  .mr-lg-0,
  .mx-lg-0 {
    margin-right: 0 !important; }
  .mb-lg-0,
  .my-lg-0 {
    margin-bottom: 0 !important; }
  .ml-lg-0,
  .mx-lg-0 {
    margin-left: 0 !important; }
  .m-lg-1 {
    margin: 0.25rem !important; }
  .mt-lg-1,
  .my-lg-1 {
    margin-top: 0.25rem !important; }
  .mr-lg-1,
  .mx-lg-1 {
    margin-right: 0.25rem !important; }
  .mb-lg-1,
  .my-lg-1 {
    margin-bottom: 0.25rem !important; }
  .ml-lg-1,
  .mx-lg-1 {
    margin-left: 0.25rem !important; }
  .m-lg-2 {
    margin: 0.5rem !important; }
  .mt-lg-2,
  .my-lg-2 {
    margin-top: 0.5rem !important; }
  .mr-lg-2,
  .mx-lg-2 {
    margin-right: 0.5rem !important; }
  .mb-lg-2,
  .my-lg-2 {
    margin-bottom: 0.5rem !important; }
  .ml-lg-2,
  .mx-lg-2 {
    margin-left: 0.5rem !important; }
  .m-lg-3 {
    margin: 1rem !important; }
  .mt-lg-3,
  .my-lg-3 {
    margin-top: 1rem !important; }
  .mr-lg-3,
  .mx-lg-3 {
    margin-right: 1rem !important; }
  .mb-lg-3,
  .my-lg-3 {
    margin-bottom: 1rem !important; }
  .ml-lg-3,
  .mx-lg-3 {
    margin-left: 1rem !important; }
  .m-lg-4 {
    margin: 1.5rem !important; }
  .mt-lg-4,
  .my-lg-4 {
    margin-top: 1.5rem !important; }
  .mr-lg-4,
  .mx-lg-4 {
    margin-right: 1.5rem !important; }
  .mb-lg-4,
  .my-lg-4 {
    margin-bottom: 1.5rem !important; }
  .ml-lg-4,
  .mx-lg-4 {
    margin-left: 1.5rem !important; }
  .m-lg-5 {
    margin: 3rem !important; }
  .mt-lg-5,
  .my-lg-5 {
    margin-top: 3rem !important; }
  .mr-lg-5,
  .mx-lg-5 {
    margin-right: 3rem !important; }
  .mb-lg-5,
  .my-lg-5 {
    margin-bottom: 3rem !important; }
  .ml-lg-5,
  .mx-lg-5 {
    margin-left: 3rem !important; }
  .p-lg-0 {
    padding: 0 !important; }
  .pt-lg-0,
  .py-lg-0 {
    padding-top: 0 !important; }
  .pr-lg-0,
  .px-lg-0 {
    padding-right: 0 !important; }
  .pb-lg-0,
  .py-lg-0 {
    padding-bottom: 0 !important; }
  .pl-lg-0,
  .px-lg-0 {
    padding-left: 0 !important; }
  .p-lg-1 {
    padding: 0.25rem !important; }
  .pt-lg-1,
  .py-lg-1 {
    padding-top: 0.25rem !important; }
  .pr-lg-1,
  .px-lg-1 {
    padding-right: 0.25rem !important; }
  .pb-lg-1,
  .py-lg-1 {
    padding-bottom: 0.25rem !important; }
  .pl-lg-1,
  .px-lg-1 {
    padding-left: 0.25rem !important; }
  .p-lg-2 {
    padding: 0.5rem !important; }
  .pt-lg-2,
  .py-lg-2 {
    padding-top: 0.5rem !important; }
  .pr-lg-2,
  .px-lg-2 {
    padding-right: 0.5rem !important; }
  .pb-lg-2,
  .py-lg-2 {
    padding-bottom: 0.5rem !important; }
  .pl-lg-2,
  .px-lg-2 {
    padding-left: 0.5rem !important; }
  .p-lg-3 {
    padding: 1rem !important; }
  .pt-lg-3,
  .py-lg-3 {
    padding-top: 1rem !important; }
  .pr-lg-3,
  .px-lg-3 {
    padding-right: 1rem !important; }
  .pb-lg-3,
  .py-lg-3 {
    padding-bottom: 1rem !important; }
  .pl-lg-3,
  .px-lg-3 {
    padding-left: 1rem !important; }
  .p-lg-4 {
    padding: 1.5rem !important; }
  .pt-lg-4,
  .py-lg-4 {
    padding-top: 1.5rem !important; }
  .pr-lg-4,
  .px-lg-4 {
    padding-right: 1.5rem !important; }
  .pb-lg-4,
  .py-lg-4 {
    padding-bottom: 1.5rem !important; }
  .pl-lg-4,
  .px-lg-4 {
    padding-left: 1.5rem !important; }
  .p-lg-5 {
    padding: 3rem !important; }
  .pt-lg-5,
  .py-lg-5 {
    padding-top: 3rem !important; }
  .pr-lg-5,
  .px-lg-5 {
    padding-right: 3rem !important; }
  .pb-lg-5,
  .py-lg-5 {
    padding-bottom: 3rem !important; }
  .pl-lg-5,
  .px-lg-5 {
    padding-left: 3rem !important; }
  .m-lg-auto {
    margin: auto !important; }
  .mt-lg-auto,
  .my-lg-auto {
    margin-top: auto !important; }
  .mr-lg-auto,
  .mx-lg-auto {
    margin-right: auto !important; }
  .mb-lg-auto,
  .my-lg-auto {
    margin-bottom: auto !important; }
  .ml-lg-auto,
  .mx-lg-auto {
    margin-left: auto !important; } }

@media (min-width: 1200px) {
  .m-xl-0 {
    margin: 0 !important; }
  .mt-xl-0,
  .my-xl-0 {
    margin-top: 0 !important; }
  .mr-xl-0,
  .mx-xl-0 {
    margin-right: 0 !important; }
  .mb-xl-0,
  .my-xl-0 {
    margin-bottom: 0 !important; }
  .ml-xl-0,
  .mx-xl-0 {
    margin-left: 0 !important; }
  .m-xl-1 {
    margin: 0.25rem !important; }
  .mt-xl-1,
  .my-xl-1 {
    margin-top: 0.25rem !important; }
  .mr-xl-1,
  .mx-xl-1 {
    margin-right: 0.25rem !important; }
  .mb-xl-1,
  .my-xl-1 {
    margin-bottom: 0.25rem !important; }
  .ml-xl-1,
  .mx-xl-1 {
    margin-left: 0.25rem !important; }
  .m-xl-2 {
    margin: 0.5rem !important; }
  .mt-xl-2,
  .my-xl-2 {
    margin-top: 0.5rem !important; }
  .mr-xl-2,
  .mx-xl-2 {
    margin-right: 0.5rem !important; }
  .mb-xl-2,
  .my-xl-2 {
    margin-bottom: 0.5rem !important; }
  .ml-xl-2,
  .mx-xl-2 {
    margin-left: 0.5rem !important; }
  .m-xl-3 {
    margin: 1rem !important; }
  .mt-xl-3,
  .my-xl-3 {
    margin-top: 1rem !important; }
  .mr-xl-3,
  .mx-xl-3 {
    margin-right: 1rem !important; }
  .mb-xl-3,
  .my-xl-3 {
    margin-bottom: 1rem !important; }
  .ml-xl-3,
  .mx-xl-3 {
    margin-left: 1rem !important; }
  .m-xl-4 {
    margin: 1.5rem !important; }
  .mt-xl-4,
  .my-xl-4 {
    margin-top: 1.5rem !important; }
  .mr-xl-4,
  .mx-xl-4 {
    margin-right: 1.5rem !important; }
  .mb-xl-4,
  .my-xl-4 {
    margin-bottom: 1.5rem !important; }
  .ml-xl-4,
  .mx-xl-4 {
    margin-left: 1.5rem !important; }
  .m-xl-5 {
    margin: 3rem !important; }
  .mt-xl-5,
  .my-xl-5 {
    margin-top: 3rem !important; }
  .mr-xl-5,
  .mx-xl-5 {
    margin-right: 3rem !important; }
  .mb-xl-5,
  .my-xl-5 {
    margin-bottom: 3rem !important; }
  .ml-xl-5,
  .mx-xl-5 {
    margin-left: 3rem !important; }
  .p-xl-0 {
    padding: 0 !important; }
  .pt-xl-0,
  .py-xl-0 {
    padding-top: 0 !important; }
  .pr-xl-0,
  .px-xl-0 {
    padding-right: 0 !important; }
  .pb-xl-0,
  .py-xl-0 {
    padding-bottom: 0 !important; }
  .pl-xl-0,
  .px-xl-0 {
    padding-left: 0 !important; }
  .p-xl-1 {
    padding: 0.25rem !important; }
  .pt-xl-1,
  .py-xl-1 {
    padding-top: 0.25rem !important; }
  .pr-xl-1,
  .px-xl-1 {
    padding-right: 0.25rem !important; }
  .pb-xl-1,
  .py-xl-1 {
    padding-bottom: 0.25rem !important; }
  .pl-xl-1,
  .px-xl-1 {
    padding-left: 0.25rem !important; }
  .p-xl-2 {
    padding: 0.5rem !important; }
  .pt-xl-2,
  .py-xl-2 {
    padding-top: 0.5rem !important; }
  .pr-xl-2,
  .px-xl-2 {
    padding-right: 0.5rem !important; }
  .pb-xl-2,
  .py-xl-2 {
    padding-bottom: 0.5rem !important; }
  .pl-xl-2,
  .px-xl-2 {
    padding-left: 0.5rem !important; }
  .p-xl-3 {
    padding: 1rem !important; }
  .pt-xl-3,
  .py-xl-3 {
    padding-top: 1rem !important; }
  .pr-xl-3,
  .px-xl-3 {
    padding-right: 1rem !important; }
  .pb-xl-3,
  .py-xl-3 {
    padding-bottom: 1rem !important; }
  .pl-xl-3,
  .px-xl-3 {
    padding-left: 1rem !important; }
  .p-xl-4 {
    padding: 1.5rem !important; }
  .pt-xl-4,
  .py-xl-4 {
    padding-top: 1.5rem !important; }
  .pr-xl-4,
  .px-xl-4 {
    padding-right: 1.5rem !important; }
  .pb-xl-4,
  .py-xl-4 {
    padding-bottom: 1.5rem !important; }
  .pl-xl-4,
  .px-xl-4 {
    padding-left: 1.5rem !important; }
  .p-xl-5 {
    padding: 3rem !important; }
  .pt-xl-5,
  .py-xl-5 {
    padding-top: 3rem !important; }
  .pr-xl-5,
  .px-xl-5 {
    padding-right: 3rem !important; }
  .pb-xl-5,
  .py-xl-5 {
    padding-bottom: 3rem !important; }
  .pl-xl-5,
  .px-xl-5 {
    padding-left: 3rem !important; }
  .m-xl-auto {
    margin: auto !important; }
  .mt-xl-auto,
  .my-xl-auto {
    margin-top: auto !important; }
  .mr-xl-auto,
  .mx-xl-auto {
    margin-right: auto !important; }
  .mb-xl-auto,
  .my-xl-auto {
    margin-bottom: auto !important; }
  .ml-xl-auto,
  .mx-xl-auto {
    margin-left: auto !important; } }

.text-justify {
  text-align: justify !important; }

.text-nowrap {
  white-space: nowrap !important; }

.text-truncate {
  overflow: hidden;
  text-overflow: ellipsis;
  white-space: nowrap; }

.text-left {
  text-align: left !important; }

.text-right {
  text-align: right !important; }

.text-center {
  text-align: center !important; }

@media (min-width: 576px) {
  .text-sm-left {
    text-align: left !important; }
  .text-sm-right {
    text-align: right !important; }
  .text-sm-center {
    text-align: center !important; } }

@media (min-width: 768px) {
  .text-md-left {
    text-align: left !important; }
  .text-md-right {
    text-align: right !important; }
  .text-md-center {
    text-align: center !important; } }

@media (min-width: 992px) {
  .text-lg-left {
    text-align: left !important; }
  .text-lg-right {
    text-align: right !important; }
  .text-lg-center {
    text-align: center !important; } }

@media (min-width: 1200px) {
  .text-xl-left {
    text-align: left !important; }
  .text-xl-right {
    text-align: right !important; }
  .text-xl-center {
    text-align: center !important; } }

.text-lowercase {
  text-transform: lowercase !important; }

.text-uppercase {
  text-transform: uppercase !important; }

.text-capitalize {
  text-transform: capitalize !important; }

.font-weight-light {
  font-weight: 300 !important; }

.font-weight-normal {
  font-weight: normal !important; }

.font-weight-bold {
  font-weight: bold !important; }

.font-italic {
  font-style: italic !important; }

.text-white {
  color: #fff !important; }

.text-primary {
  color: #007bff !important; }

a.text-primary:focus, a.text-primary:hover {
  color: #0062cc !important; }

.text-secondary {
  color: #868e96 !important; }

a.text-secondary:focus, a.text-secondary:hover {
  color: #6c757d !important; }

.text-success {
  color: #28a745 !important; }

a.text-success:focus, a.text-success:hover {
  color: #1e7e34 !important; }

.text-info {
  color: #17a2b8 !important; }

a.text-info:focus, a.text-info:hover {
  color: #117a8b !important; }

.text-warning {
  color: #ffc107 !important; }

a.text-warning:focus, a.text-warning:hover {
  color: #d39e00 !important; }

.text-danger {
  color: #dc3545 !important; }

a.text-danger:focus, a.text-danger:hover {
  color: #bd2130 !important; }

.text-light {
  color: #f8f9fa !important; }

a.text-light:focus, a.text-light:hover {
  color: #dae0e5 !important; }

.text-dark {
  color: #343a40 !important; }

a.text-dark:focus, a.text-dark:hover {
  color: #1d2124 !important; }

.text-muted {
  color: #868e96 !important; }

.text-hide {
  font: 0/0 a;
  color: transparent;
  text-shadow: none;
  background-color: transparent;
  border: 0; }

.visible {
  visibility: visible !important; }

.invisible {
  visibility: hidden !important; }

/* VARIAVEIS */
/*
 * SIZE
 */
/*
 * COLOR
 */
/* CORES */
.color__lime {
  color: #9ddd61; }

.color__pink {
  color: #f92b6d; }

.color__lightgrey {
  color: #E8E8E7; }

/* BOTAO */
button.custom {
  background-color: transparent;
  border: 2px solid #f92b6d;
  padding: .4em;
  color: #f92b6d;
  font-size: inherit;
  cursor: pointer;
  transition: color .5s, border-color .5s; }
  button.custom:hover {
    color: red;
    border-color: red; }
  button.custom .icon {
    height: 1em;
    width: 1em; }
    button.custom .icon * {
      stroke: #f92b6d;
      fill: #f92b6d; }
  button.custom [role="label"] {
    margin-left: .5em; }

/* BOTAO */
.card {
  box-shadow: 0 0 20px 0px rgba(0, 0, 0, 0.05);
  border: none;
  -webkit-flex-basis: 20%;
      -ms-flex-preferred-size: 20%;
          flex-basis: 20%;
  border-radius: .4em;
  padding: 1em;
  font-size: 20px;
  font-weight: 500;
  position: relative; }
  .card > * {
    margin: .2em; }
  .card h1 {
    position: relative;
    font-size: .7em; }
    .card h1 .icon {
      position: absolute;
      right: 0;
      height: 1em;
      width: 2em; }
      .card h1 .icon > * {
        fill: #E8E8E7; }
  .card p {
    font-size: 1.2em;
    letter-spacing: .1em; }
    .card p span {
      font-size: .8em;
      font-weight: 400; }

.marcacao {
  border: 1px solid black; }

.delimitador, .del-right, .del-left, .del-bottom {
  border-color: #E8E8E7;
  border-width: 0;
  border-style: solid; }

.del-right {
  border-right-width: 1px; }

.del-left {
  border-left-width: 1px; }

.del-bottom {
  border-bottom-width: 1px; }

.whitebg, aside.left, header.main, aside.right {
  background-color: white; }

body {
  background-color: #faf7f6; }

svg.icon.text {
  height: 1em;
  width: 1em; }

aside.left {
  width: 120px; }
  aside.left #logo {
    padding: 20px;
    width: 120px;
    height: 120px; }
    aside.left #logo > svg {
      width: 80px;
      height: 80px; }
  aside.left nav {
    position: relative; }
    aside.left nav:before {
      content: '';
      display: block;
      position: absolute;
      background-color: #f92b6d;
      width: 8px;
      left: -20px;
      top: -80px;
      transition: left, .5s, top .5s;
      box-shadow: 0px 1px 9px 3px rgba(0, 0, 0, 0.42);
      border-radius: 100%;
      height: 40px; }
    aside.left nav.cursor:before {
      left: -4px; }
    aside.left nav.item-1:before {
      top: 40px; }
    aside.left nav.item-2:before {
      top: 160px; }
    aside.left nav.item-3:before {
      top: 280px; }
    aside.left nav.item-4:before {
      top: 400px; }
    aside.left nav.item-5:before {
      top: 520px; }
    aside.left nav.item-6:before {
      top: 640px; }
    aside.left nav.item-7:before {
      top: 760px; }
    aside.left nav.item-8:before {
      top: 880px; }
    aside.left nav.item-9:before {
      top: 1000px; }
    aside.left nav.item-10:before {
      top: 1120px; }
    aside.left nav > div.item {
      width: 120px;
      line-height: 120px;
      text-align: center;
      height: 120px;
      text-align: center;
      line-height: 120px;
      position: relative; }
      aside.left nav > div.item a {
        position: absolute;
        width: 40%;
        height: 40%; }
      aside.left nav > div.item .icon {
        cursor: pointer;
        stroke: #f92b6d;
        fill: #f92b6d;
        width: 40%;
        height: 40%;
        margin: auto;
        transition: fill .5s; }
        aside.left nav > div.item .icon:hover {
          fill: red; }

#beside {
  -webkit-flex: 1 1 auto;
      -ms-flex: 1 1 auto;
          flex: 1 1 auto; }

header.main {
  font-size: 30px;
  color: rgba(142, 142, 142, 0.4);
  height: 120px; }
  header.main > .icon {
    margin-left: 2em;
    margin-right: 1em;
    height: 60px;
    width: 60px;
    -webkit-flex: 0 1 auto;
        -ms-flex: 0 1 auto;
            flex: 0 1 auto; }
    header.main > .icon * {
      stroke: rgba(142, 142, 142, 0.4);
      fill: rgba(142, 142, 142, 0.4); }
  header.main > h1 {
    -webkit-flex: 1 1 auto;
        -ms-flex: 1 1 auto;
            flex: 1 1 auto;
    font-weight: 400;
    font-size: inherit; }

#user-account {
  -webkit-flex: 0 0 288px;
      -ms-flex: 0 0 288px;
          flex: 0 0 288px;
  font-size: 15px;
  height: 100%;
  padding: 0 3em; }
  #user-account > .avatar {
    border-radius: 100%;
    height: 72px;
    width: 72px;
    background-repeat: no-repeat;
    background-position: center;
    background-size: cover; }

aside.right {
  padding: 3em;
  font-size: 16px;
  -webkit-flex: 0 0 288px;
      -ms-flex: 0 0 288px;
          flex: 0 0 288px; }
  aside.right header {
    margin-bottom: 4em; }
    aside.right header h2 {
      font-size: 1.6em; }
    aside.right header h3 {
      font-size: 1.2em;
      color: rgba(142, 142, 142, 0.4); }
  aside.right .sidebar-summary-item {
    margin-bottom: 2em; }
    aside.right .sidebar-summary-item:before {
      content: '';
      display: block;
      width: 100%;
      height: 5px;
      background-color: #f92b6d;
      margin-bottom: .5em; }
    aside.right .sidebar-summary-item h4 {
      font-size: .8em;
      color: rgba(142, 142, 142, 0.4); }
    aside.right .sidebar-summary-item p {
      margin: 0;
      padding: 0; }
    aside.right .sidebar-summary-item a {
      color: #f92b6d;
      font-size: .8em; }
      aside.right .sidebar-summary-item a .icon * {
        stroke: #f92b6d;
        fill: #f92b6d; }

#content {
  -webkit-flex: 1 1 100%;
      -ms-flex: 1 1 100%;
          flex: 1 1 100%;
  padding: 3em; }

/*# sourceMappingURL=data:application/json;base64,eyJ2ZXJzaW9uIjozLCJzb3VyY2VzIjpbInBhaW5lbC5zY3NzIiwiX2ZyYW1lLnNjc3MiLCIuLi8uLi9ub2RlX21vZHVsZXMvYm9vdHN0cmFwL3Njc3MvYm9vdHN0cmFwLnNjc3MiLCIuLi8uLi9ub2RlX21vZHVsZXMvYm9vdHN0cmFwL3Njc3MvX3ByaW50LnNjc3MiLCIuLi8uLi9ub2RlX21vZHVsZXMvYm9vdHN0cmFwL3Njc3MvX3JlYm9vdC5zY3NzIiwiLi4vLi4vbm9kZV9tb2R1bGVzL2Jvb3RzdHJhcC9zY3NzL192YXJpYWJsZXMuc2NzcyIsInBhaW5lbC5jc3MiLCIuLi8uLi9ub2RlX21vZHVsZXMvYm9vdHN0cmFwL3Njc3MvbWl4aW5zL19ob3Zlci5zY3NzIiwiLi4vLi4vbm9kZV9tb2R1bGVzL2Jvb3RzdHJhcC9zY3NzL190eXBlLnNjc3MiLCIuLi8uLi9ub2RlX21vZHVsZXMvYm9vdHN0cmFwL3Njc3MvbWl4aW5zL19saXN0cy5zY3NzIiwiLi4vLi4vbm9kZV9tb2R1bGVzL2Jvb3RzdHJhcC9zY3NzL19pbWFnZXMuc2NzcyIsIi4uLy4uL25vZGVfbW9kdWxlcy9ib290c3RyYXAvc2Nzcy9taXhpbnMvX2ltYWdlLnNjc3MiLCIuLi8uLi9ub2RlX21vZHVsZXMvYm9vdHN0cmFwL3Njc3MvbWl4aW5zL19ib3JkZXItcmFkaXVzLnNjc3MiLCIuLi8uLi9ub2RlX21vZHVsZXMvYm9vdHN0cmFwL3Njc3MvbWl4aW5zL190cmFuc2l0aW9uLnNjc3MiLCIuLi8uLi9ub2RlX21vZHVsZXMvYm9vdHN0cmFwL3Njc3MvX2NvZGUuc2NzcyIsIi4uLy4uL25vZGVfbW9kdWxlcy9ib290c3RyYXAvc2Nzcy9fZ3JpZC5zY3NzIiwiLi4vLi4vbm9kZV9tb2R1bGVzL2Jvb3RzdHJhcC9zY3NzL21peGlucy9fZ3JpZC5zY3NzIiwiLi4vLi4vbm9kZV9tb2R1bGVzL2Jvb3RzdHJhcC9zY3NzL21peGlucy9fYnJlYWtwb2ludHMuc2NzcyIsIi4uLy4uL25vZGVfbW9kdWxlcy9ib290c3RyYXAvc2Nzcy9taXhpbnMvX2dyaWQtZnJhbWV3b3JrLnNjc3MiLCIuLi8uLi9ub2RlX21vZHVsZXMvYm9vdHN0cmFwL3Njc3MvX3RhYmxlcy5zY3NzIiwiLi4vLi4vbm9kZV9tb2R1bGVzL2Jvb3RzdHJhcC9zY3NzL21peGlucy9fdGFibGUtcm93LnNjc3MiLCIuLi8uLi9ub2RlX21vZHVsZXMvYm9vdHN0cmFwL3Njc3MvX2Z1bmN0aW9ucy5zY3NzIiwiLi4vLi4vbm9kZV9tb2R1bGVzL2Jvb3RzdHJhcC9zY3NzL19mb3Jtcy5zY3NzIiwiLi4vLi4vbm9kZV9tb2R1bGVzL2Jvb3RzdHJhcC9zY3NzL21peGlucy9fZm9ybXMuc2NzcyIsIi4uLy4uL25vZGVfbW9kdWxlcy9ib290c3RyYXAvc2Nzcy9fYnV0dG9ucy5zY3NzIiwiLi4vLi4vbm9kZV9tb2R1bGVzL2Jvb3RzdHJhcC9zY3NzL21peGlucy9fYnV0dG9ucy5zY3NzIiwiLi4vLi4vbm9kZV9tb2R1bGVzL2Jvb3RzdHJhcC9zY3NzL190cmFuc2l0aW9ucy5zY3NzIiwiLi4vLi4vbm9kZV9tb2R1bGVzL2Jvb3RzdHJhcC9zY3NzL19kcm9wZG93bi5zY3NzIiwiLi4vLi4vbm9kZV9tb2R1bGVzL2Jvb3RzdHJhcC9zY3NzL21peGlucy9fbmF2LWRpdmlkZXIuc2NzcyIsIi4uLy4uL25vZGVfbW9kdWxlcy9ib290c3RyYXAvc2Nzcy9fYnV0dG9uLWdyb3VwLnNjc3MiLCIuLi8uLi9ub2RlX21vZHVsZXMvYm9vdHN0cmFwL3Njc3MvX2lucHV0LWdyb3VwLnNjc3MiLCIuLi8uLi9ub2RlX21vZHVsZXMvYm9vdHN0cmFwL3Njc3MvX2N1c3RvbS1mb3Jtcy5zY3NzIiwiLi4vLi4vbm9kZV9tb2R1bGVzL2Jvb3RzdHJhcC9zY3NzL19uYXYuc2NzcyIsIi4uLy4uL25vZGVfbW9kdWxlcy9ib290c3RyYXAvc2Nzcy9fbmF2YmFyLnNjc3MiLCIuLi8uLi9ub2RlX21vZHVsZXMvYm9vdHN0cmFwL3Njc3MvX2NhcmQuc2NzcyIsIi4uLy4uL25vZGVfbW9kdWxlcy9ib290c3RyYXAvc2Nzcy9fYnJlYWRjcnVtYi5zY3NzIiwiLi4vLi4vbm9kZV9tb2R1bGVzL2Jvb3RzdHJhcC9zY3NzL21peGlucy9fY2xlYXJmaXguc2NzcyIsIi4uLy4uL25vZGVfbW9kdWxlcy9ib290c3RyYXAvc2Nzcy9fcGFnaW5hdGlvbi5zY3NzIiwiLi4vLi4vbm9kZV9tb2R1bGVzL2Jvb3RzdHJhcC9zY3NzL21peGlucy9fcGFnaW5hdGlvbi5zY3NzIiwiLi4vLi4vbm9kZV9tb2R1bGVzL2Jvb3RzdHJhcC9zY3NzL19iYWRnZS5zY3NzIiwiLi4vLi4vbm9kZV9tb2R1bGVzL2Jvb3RzdHJhcC9zY3NzL21peGlucy9fYmFkZ2Uuc2NzcyIsIi4uLy4uL25vZGVfbW9kdWxlcy9ib290c3RyYXAvc2Nzcy9fanVtYm90cm9uLnNjc3MiLCIuLi8uLi9ub2RlX21vZHVsZXMvYm9vdHN0cmFwL3Njc3MvX2FsZXJ0LnNjc3MiLCIuLi8uLi9ub2RlX21vZHVsZXMvYm9vdHN0cmFwL3Njc3MvbWl4aW5zL19hbGVydC5zY3NzIiwiLi4vLi4vbm9kZV9tb2R1bGVzL2Jvb3RzdHJhcC9zY3NzL19wcm9ncmVzcy5zY3NzIiwiLi4vLi4vbm9kZV9tb2R1bGVzL2Jvb3RzdHJhcC9zY3NzL21peGlucy9fZ3JhZGllbnRzLnNjc3MiLCIuLi8uLi9ub2RlX21vZHVsZXMvYm9vdHN0cmFwL3Njc3MvX21lZGlhLnNjc3MiLCIuLi8uLi9ub2RlX21vZHVsZXMvYm9vdHN0cmFwL3Njc3MvX2xpc3QtZ3JvdXAuc2NzcyIsIi4uLy4uL25vZGVfbW9kdWxlcy9ib290c3RyYXAvc2Nzcy9taXhpbnMvX2xpc3QtZ3JvdXAuc2NzcyIsIi4uLy4uL25vZGVfbW9kdWxlcy9ib290c3RyYXAvc2Nzcy9fY2xvc2Uuc2NzcyIsIi4uLy4uL25vZGVfbW9kdWxlcy9ib290c3RyYXAvc2Nzcy9fbW9kYWwuc2NzcyIsIi4uLy4uL25vZGVfbW9kdWxlcy9ib290c3RyYXAvc2Nzcy9fdG9vbHRpcC5zY3NzIiwiLi4vLi4vbm9kZV9tb2R1bGVzL2Jvb3RzdHJhcC9zY3NzL21peGlucy9fcmVzZXQtdGV4dC5zY3NzIiwiLi4vLi4vbm9kZV9tb2R1bGVzL2Jvb3RzdHJhcC9zY3NzL19wb3BvdmVyLnNjc3MiLCIuLi8uLi9ub2RlX21vZHVsZXMvYm9vdHN0cmFwL3Njc3MvX2Nhcm91c2VsLnNjc3MiLCIuLi8uLi9ub2RlX21vZHVsZXMvYm9vdHN0cmFwL3Njc3MvdXRpbGl0aWVzL19hbGlnbi5zY3NzIiwiLi4vLi4vbm9kZV9tb2R1bGVzL2Jvb3RzdHJhcC9zY3NzL21peGlucy9fYmFja2dyb3VuZC12YXJpYW50LnNjc3MiLCIuLi8uLi9ub2RlX21vZHVsZXMvYm9vdHN0cmFwL3Njc3MvdXRpbGl0aWVzL19iYWNrZ3JvdW5kLnNjc3MiLCIuLi8uLi9ub2RlX21vZHVsZXMvYm9vdHN0cmFwL3Njc3MvdXRpbGl0aWVzL19ib3JkZXJzLnNjc3MiLCIuLi8uLi9ub2RlX21vZHVsZXMvYm9vdHN0cmFwL3Njc3MvdXRpbGl0aWVzL19jbGVhcmZpeC5zY3NzIiwiLi4vLi4vbm9kZV9tb2R1bGVzL2Jvb3RzdHJhcC9zY3NzL3V0aWxpdGllcy9fZGlzcGxheS5zY3NzIiwiLi4vLi4vbm9kZV9tb2R1bGVzL2Jvb3RzdHJhcC9zY3NzL3V0aWxpdGllcy9fZW1iZWQuc2NzcyIsIi4uLy4uL25vZGVfbW9kdWxlcy9ib290c3RyYXAvc2Nzcy91dGlsaXRpZXMvX2ZsZXguc2NzcyIsIi4uLy4uL25vZGVfbW9kdWxlcy9ib290c3RyYXAvc2Nzcy91dGlsaXRpZXMvX2Zsb2F0LnNjc3MiLCIuLi8uLi9ub2RlX21vZHVsZXMvYm9vdHN0cmFwL3Njc3MvbWl4aW5zL19mbG9hdC5zY3NzIiwiLi4vLi4vbm9kZV9tb2R1bGVzL2Jvb3RzdHJhcC9zY3NzL3V0aWxpdGllcy9fcG9zaXRpb24uc2NzcyIsIi4uLy4uL25vZGVfbW9kdWxlcy9ib290c3RyYXAvc2Nzcy91dGlsaXRpZXMvX3NjcmVlbnJlYWRlcnMuc2NzcyIsIi4uLy4uL25vZGVfbW9kdWxlcy9ib290c3RyYXAvc2Nzcy9taXhpbnMvX3NjcmVlbi1yZWFkZXIuc2NzcyIsIi4uLy4uL25vZGVfbW9kdWxlcy9ib290c3RyYXAvc2Nzcy91dGlsaXRpZXMvX3NpemluZy5zY3NzIiwiLi4vLi4vbm9kZV9tb2R1bGVzL2Jvb3RzdHJhcC9zY3NzL3V0aWxpdGllcy9fc3BhY2luZy5zY3NzIiwiLi4vLi4vbm9kZV9tb2R1bGVzL2Jvb3RzdHJhcC9zY3NzL3V0aWxpdGllcy9fdGV4dC5zY3NzIiwiLi4vLi4vbm9kZV9tb2R1bGVzL2Jvb3RzdHJhcC9zY3NzL21peGlucy9fdGV4dC10cnVuY2F0ZS5zY3NzIiwiLi4vLi4vbm9kZV9tb2R1bGVzL2Jvb3RzdHJhcC9zY3NzL21peGlucy9fdGV4dC1lbXBoYXNpcy5zY3NzIiwiLi4vLi4vbm9kZV9tb2R1bGVzL2Jvb3RzdHJhcC9zY3NzL21peGlucy9fdGV4dC1oaWRlLnNjc3MiLCIuLi8uLi9ub2RlX21vZHVsZXMvYm9vdHN0cmFwL3Njc3MvdXRpbGl0aWVzL192aXNpYmlsaXR5LnNjc3MiLCIuLi8uLi9ub2RlX21vZHVsZXMvYm9vdHN0cmFwL3Njc3MvbWl4aW5zL192aXNpYmlsaXR5LnNjc3MiLCJfdmFyaWFibGVzLnNjc3MiLCJfY29sb3Iuc2NzcyIsImNvbXBvbmVudHMvX2J1dHRvbi5zY3NzIiwiY29tcG9uZW50cy9fY2FyZC5zY3NzIl0sIm5hbWVzIjpbXSwibWFwcGluZ3MiOiJBQUFBLFdBQVc7QUNBWCxlQUFlO0FDQWY7Ozs7O0dBS0c7QUNNRDtFQUNFOzs7SUFNRSw2QkFBNkI7SUFFN0IsNEJBQTRCLEVBQzdCO0VBRUQ7O0lBRUUsMkJBQTJCLEVBQzVCO0VBT0Q7SUFDRSw4QkFBNkIsRUFDOUI7RUFhRDtJQUNFLGlDQUFpQyxFQUNsQztFQUNEOztJQUVFLHVCQUFnQztJQUNoQyx5QkFBeUIsRUFDMUI7RUFPRDtJQUNFLDRCQUE0QixFQUM3QjtFQUVEOztJQUVFLHlCQUF5QixFQUMxQjtFQUVEOzs7SUFHRSxXQUFXO0lBQ1gsVUFBVSxFQUNYO0VBRUQ7O0lBRUUsd0JBQXdCLEVBQ3pCO0VBS0Q7SUFDRSxj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O0VvQmhRaEMsZ0JwQnNLbUI7RW9CcktuQixrQnBCZ1E4QjtFTzVVNUIsdUJQMk4yQjtFUTFOekIsNkdSbVd3SCxFbUJqVTdIO0VBakNEO0lBYUksc0JBQXNCLEVqQk1yQjtFaUJuQkw7SUFpQkksV0FBVztJQUNYLDhDbkJtRGEsRW1CbERkO0VBbkJIO0lBd0JJLGFBQWEsRUFFZDtFQTFCSDtJQThCSSx1QkFBdUIsRUFFeEI7O0FBSUg7O0VBRUUscUJBQXFCLEVBQ3RCOztBQVFDO0VIUUUsWUFBWTtFSXREZCwwQnBCb0VlO0VvQm5FZixzQnBCbUVlLEVtQnBCZDtFQUZEO0lIUUUsWUFBWTtJSWhEWiwwQkFSa0U7SUFTbEUsc0JBVDZHLEVBVTlHO0VEc0NEO0lDOUJJLDZDcEJvRFcsRW9CbERkO0VENEJEO0lDdkJFLDBCcEI2Q2E7SW9CNUNiLHNCcEI0Q2EsRW9CM0NkO0VEcUJEOztJQ2hCRSwwQkFoQ2tFO0lBaUNsRSx1QkFBdUI7SUFDdkIsc0JBbEM2RyxFQW9DOUc7O0FEWUQ7RUhRRSxZQUFZO0VJdERkLDBCcEJrRGdCO0VvQmpEaEIsc0JwQmlEZ0IsRW1CRmY7RUFGRDtJSFFFLFlBQVk7SUloRFosMEJBUmtFO0lBU2xFLHNCQVQ2RyxFQVU5RztFRHNDRDtJQzlCSSwrQ3BCa0NZLEVvQmhDZjtFRDRCRDtJQ3ZCRSwwQnBCMkJjO0lvQjFCZCxzQnBCMEJjLEVvQnpCZjtFRHFCRDs7SUNoQkUsMEJBaENrRTtJQWlDbEUsdUJBQXVCO0lBQ3ZCLHNCQWxDNkcsRUFvQzlHOztBRFlEO0VIUUUsWUFBWTtFSXREZCwwQnBCMkVlO0VvQjFFZixzQnBCMEVlLEVtQjNCZDtFQUZEO0lIUUUsWUFBWTtJSWhEWiwwQkFSa0U7SUFTbEUsc0JBVDZHLEVBVTlHO0VEc0NEO0lDOUJJLDZDcEIyRFcsRW9CekRkO0VENEJEO0lDdkJFLDBCcEJvRGE7SW9CbkRiLHNCcEJtRGEsRW9CbERkO0VEcUJEOztJQ2hCRSwwQkFoQ2tFO0lBaUNsRSx1QkFBdUI7SUFDdkIsc0JBbEM2RyxFQW9DOUc7O0FEWUQ7RUhRRSxZQUFZO0VJdERkLDBCcEI2RWU7RW9CNUVmLHNCcEI0RWUsRW1CN0JkO0VBRkQ7SUhRRSxZQUFZO0lJaERaLDBCQVJrRTtJQVNsRSxzQkFUNkcsRUFVOUc7RURzQ0Q7SUM5QkksOENwQjZEVyxFb0IzRGQ7RUQ0QkQ7SUN2QkUsMEJwQnNEYTtJb0JyRGIsc0JwQnFEYSxFb0JwRGQ7RURxQkQ7O0lDaEJFLDBCQWhDa0U7SUFpQ2xFLHVCQUF1QjtJQUN2QixzQkFsQzZHLEVBb0M5Rzs7QURZRDtFSE1FLFlBQVk7RUlwRGQsMEJwQjBFZTtFb0J6RWYsc0JwQnlFZSxFbUIxQmQ7RUFGRDtJSE1FLFlBQVk7SUk5Q1osMEJBUmtFO0lBU2xFLHNCQVQ2RyxFQVU5RztFRHNDRDtJQzlCSSw2Q3BCMERXLEVvQnhEZDtFRDRCRDtJQ3ZCRSwwQnBCbURhO0lvQmxEYixzQnBCa0RhLEVvQmpEZDtFRHFCRDs7SUNoQkUsMEJBaENrRTtJQWlDbEUsdUJBQXVCO0lBQ3ZCLHNCQWxDNkcsRUFvQzlHOztBRFlEO0VIUUUsWUFBWTtFSXREZCwwQnBCd0VlO0VvQnZFZixzQnBCdUVlLEVtQnhCZDtFQUZEO0lIUUUsWUFBWTtJSWhEWiwwQkFSa0U7SUFTbEUsc0JBVDZHLEVBVTlHO0VEc0NEO0lDOUJJLDZDcEJ3RFcsRW9CdERkO0VENEJEO0lDdkJFLDBCcEJpRGE7SW9CaERiLHNCcEJnRGEsRW9CL0NkO0VEcUJEOztJQ2hCRSwwQkFoQ2tFO0lBaUNsRSx1QkFBdUI7SUFDdkIsc0JBbEM2RyxFQW9DOUc7O0FEWUQ7RUhNRSxZQUFZO0VJcERkLDBCcEI2Q2dCO0VvQjVDaEIsc0JwQjRDZ0IsRW1CR2Y7RUFGRDtJSE1FLFlBQVk7SUk5Q1osMEJBUmtFO0lBU2xFLHNCQVQ2RyxFQVU5RztFRHNDRDtJQzlCSSwrQ3BCNkJZLEVvQjNCZjtFRDRCRDtJQ3ZCRSwwQnBCc0JjO0lvQnJCZCxzQnBCcUJjLEVvQnBCZjtFRHFCRDs7SUNoQkUsMEJBaENrRTtJQWlDbEUsdUJBQXVCO0lBQ3ZCLHNCQWxDNkcsRUFvQzlHOztBRFlEO0VIUUUsWUFBWTtFSXREZCwwQnBCb0RnQjtFb0JuRGhCLHNCcEJtRGdCLEVtQkpmO0VBRkQ7SUhRRSxZQUFZO0lJaERaLDBCQVJrRTtJQVNsRSxzQkFUNkcsRUFVOUc7RURzQ0Q7SUM5QkksNENwQm9DWSxFb0JsQ2Y7RUQ0QkQ7SUN2QkUsMEJwQjZCYztJb0I1QmQsc0JwQjRCYyxFb0IzQmY7RURxQkQ7O0lDaEJFLDBCQWhDa0U7SUFpQ2xFLHVCQUF1QjtJQUN2QixzQkFsQzZHLEVBb0M5Rzs7QURrQkQ7RUNkQSxlcEI4QmU7RW9CN0JmLDhCQUE4QjtFQUM5Qix1QkFBdUI7RUFDdkIsc0JwQjJCZSxFbUJkZDtFQUZEO0lDUkUsWURTNEM7SUNSNUMsMEJwQnVCYTtJb0J0QmIsc0JwQnNCYSxFRWhFUTtFaUJnRHZCO0lDREUsNkNwQmlCYSxFb0JoQmQ7RURBRDtJQ0lFLGVwQllhO0lvQlhiLDhCQUE4QixFQUMvQjtFRE5EOztJQ1dFLFlEVjRDO0lDVzVDLDBCcEJJYTtJb0JIYixzQnBCR2EsRW9CRmQ7O0FEZEQ7RUNkQSxlcEJZZ0I7RW9CWGhCLDhCQUE4QjtFQUM5Qix1QkFBdUI7RUFDdkIsc0JwQlNnQixFbUJJZjtFQUZEO0lDUkUsWURTNEM7SUNSNUMsMEJwQktjO0lvQkpkLHNCcEJJYyxFRTlDTztFaUJnRHZCO0lDREUsK0NwQkRjLEVvQkVmO0VEQUQ7SUNJRSxlcEJOYztJb0JPZCw4QkFBOEIsRUFDL0I7RURORDs7SUNXRSxZRFY0QztJQ1c1QywwQnBCZGM7SW9CZWQsc0JwQmZjLEVvQmdCZjs7QURkRDtFQ2RBLGVwQnFDZTtFb0JwQ2YsOEJBQThCO0VBQzlCLHVCQUF1QjtFQUN2QixzQnBCa0NlLEVtQnJCZDtFQUZEO0lDUkUsWURTNEM7SUNSNUMsMEJwQjhCYTtJb0I3QmIsc0JwQjZCYSxFRXZFUTtFaUJnRHZCO0lDREUsNkNwQndCYSxFb0J2QmQ7RURBRDtJQ0lFLGVwQm1CYTtJb0JsQmIsOEJBQThCLEVBQy9CO0VETkQ7O0lDV0UsWURWNEM7SUNXNUMsMEJwQldhO0lvQlZiLHNCcEJVYSxFb0JUZDs7QURkRDtFQ2RBLGVwQnVDZTtFb0J0Q2YsOEJBQThCO0VBQzlCLHVCQUF1QjtFQUN2QixzQnBCb0NlLEVtQnZCZDtFQUZEO0lDUkUsWURTNEM7SUNSNUMsMEJwQmdDYTtJb0IvQmIsc0JwQitCYSxFRXpFUTtFaUJnRHZCO0lDREUsOENwQjBCYSxFb0J6QmQ7RURBRDtJQ0lFLGVwQnFCYTtJb0JwQmIsOEJBQThCLEVBQy9CO0VETkQ7O0lDV0UsWURWNEM7SUNXNUMsMEJwQmFhO0lvQlpiLHNCcEJZYSxFb0JYZDs7QURkRDtFQ2RBLGVwQm9DZTtFb0JuQ2YsOEJBQThCO0VBQzlCLHVCQUF1QjtFQUN2QixzQnBCaUNlLEVtQnBCZDtFQUZEO0lDUkUsWURTNEM7SUNSNUMsMEJwQjZCYTtJb0I1QmIsc0JwQjRCYSxFRXRFUTtFaUJnRHZCO0lDREUsNkNwQnVCYSxFb0J0QmQ7RURBRDtJQ0lFLGVwQmtCYTtJb0JqQmIsOEJBQThCLEVBQy9CO0VETkQ7O0lDV0UsWURWNEM7SUNXNUMsMEJwQlVhO0lvQlRiLHNCcEJTYSxFb0JSZDs7QURkRDtFQ2RBLGVwQmtDZTtFb0JqQ2YsOEJBQThCO0VBQzlCLHVCQUF1QjtFQUN2QixzQnBCK0JlLEVtQmxCZDtFQUZEO0lDUkUsWURTNEM7SUNSNUMsMEJwQjJCYTtJb0IxQmIsc0JwQjBCYSxFRXBFUTtFaUJnRHZCO0lDREUsNkNwQnFCYSxFb0JwQmQ7RURBRDtJQ0lFLGVwQmdCYTtJb0JmYiw4QkFBOEIsRUFDL0I7RURORDs7SUNXRSxZRFY0QztJQ1c1QywwQnBCUWE7SW9CUGIsc0JwQk9hLEVvQk5kOztBRGREO0VDZEEsZXBCT2dCO0VvQk5oQiw4QkFBOEI7RUFDOUIsdUJBQXVCO0VBQ3ZCLHNCcEJJZ0IsRW1CU2Y7RUFGRDtJQ1JFLFlEUzRDO0lDUjVDLDBCcEJBYztJb0JDZCxzQnBCRGMsRUV6Q087RWlCZ0R2QjtJQ0RFLCtDcEJOYyxFb0JPZjtFREFEO0lDSUUsZXBCWGM7SW9CWWQsOEJBQThCLEVBQy9CO0VETkQ7O0lDV0UsWURWNEM7SUNXNUMsMEJwQm5CYztJb0JvQmQsc0JwQnBCYyxFb0JxQmY7O0FEZEQ7RUNkQSxlcEJjZ0I7RW9CYmhCLDhCQUE4QjtFQUM5Qix1QkFBdUI7RUFDdkIsc0JwQldnQixFbUJFZjtFQUZEO0lDUkUsWURTNEM7SUNSNUMsMEJwQk9jO0lvQk5kLHNCcEJNYyxFRWhETztFaUJnRHZCO0lDREUsNENwQkNjLEVvQkFmO0VEQUQ7SUNJRSxlcEJKYztJb0JLZCw4QkFBOEIsRUFDL0I7RURORDs7SUNXRSxZRFY0QztJQ1c1QywwQnBCWmM7SW9CYWQsc0JwQmJjLEVvQmNmOztBREhIO0VBQ0Usb0JuQm1MeUI7RW1CbEx6QixlbkJHZTtFbUJGZixpQkFBaUIsRUE4QmxCO0VBakNEO0lBU0ksOEJBQThCLEVBRS9CO0VBWEg7SUFlSSwwQkFBMEI7SUFDMUIsaUJBQWlCLEVBQ2xCO0VBakJIO0lBbUJJLDBCQUEwQixFakI5RUw7RWlCMkR6QjtJQXNCSSxlbkIyRTBCO0ltQjFFMUIsMkJuQjJFNkI7SW1CMUU3Qiw4QkFBOEIsRWpCckU3QjtFaUI2Q0w7SUEyQkksZW5CeENjLEVtQjZDZjtJQWhDSDtNQThCTSxzQkFBc0IsRWpCM0V2Qjs7QWlCcUZMO0VDaENFLHFCcEJ5UThCO0VvQnhROUIsbUJwQnVLc0I7RW9CdEt0QixpQnBCeUkwQjtFT3JOeEIsc0JQNE4wQixFbUJoSDdCOztBQUVEO0VDcENFLHdCcEJxUStCO0VvQnBRL0Isb0JwQndLc0I7RW9Cdkt0QixpQnBCMEkwQjtFT3ROeEIsc0JQNk4wQixFbUI3RzdCOztBQU9EO0VBQ0UsZUFBZTtFQUNmLFlBQVksRUFDYjs7QUFHRDtFQUNFLG1CbkIrTm9DLEVtQjlOckM7O0FBR0Q7OztFQUlJLFlBQVksRUFDYjs7QUUzSUg7RUFDRSxXQUFXO0ViSVAsaUNSb09zQyxFcUJsTzNDO0VBUEQ7SUFLSSxXQUFXLEVBQ1o7O0FBR0g7RUFDRSxjQUFjLEVBSWY7RUFMRDtJQUdJLGVBQWUsRUFDaEI7O0FBR0g7RUFFSSxtQkFBbUIsRUFDcEI7O0FBR0g7RUFFSSx5QkFBeUIsRUFDMUI7O0FBR0g7RUFDRSxtQkFBbUI7RUFDbkIs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Q3ZIMUIsc0JBQXNCO0lBQ3RCLDBCaENJYztJZ0NIZCxtQmhDMGlCdUMsRUVua0J0Qzs7QStCdEJIO0VBQ0Usd0JqQzhrQndDO0VpQzdrQnhDLG1CakNpUG9CO0VpQ2hQcEIsaUJqQ21Od0IsRWlDbE56Qjs7QUFJRztFMUJvQkYsK0JQaU0wQjtFT2hNMUIsa0NQZ00wQixFaUNuTnZCOztBQUdEO0UxQkNGLGdDUCtNMEI7RU85TTFCLG1DUDhNMEIsRWlDOU12Qjs7QUFmTDtFQUNFLHdCakM0a0J1QztFaUMza0J2QyxvQmpDa1BvQjtFaUNqUHBCLGlCakNvTndCLEVpQ25OekI7O0FBSUc7RTFCb0JGLCtCUGtNMEI7RU9qTTFCLGtDUGlNMEIsRWlDcE52Qjs7QUFHRDtFMUJDRixnQ1BnTjBCO0VPL00xQixtQ1ArTTBCLEVpQy9NdkI7O0FDYlA7RUFDRSxzQkFBc0I7RUFDdEIsc0JsQzBxQmdDO0VrQ3pxQmhDLGVsQ3NxQitCO0VrQ3JxQi9CLGtCbENrUHFCO0VrQ2pQckIsZUFBZTtFQUNmLFlsQ3dDVztFa0N2Q1gsbUJBQW1CO0VBQ25CLG9CQUFvQjtFQUNwQix5QkFBeUI7RTNCVnZCLHVCUDJOMkIsRWtDMU05QjtFQWhCRDtJQWNJLGNBQWMsRUFDZjs7QUFJSDtFQUNFLG1CQUFtQjtFQUNuQixVQUFVLEVBQ1g7O0FBTUQ7RUFDRSxxQmxDaXBCZ0M7RWtDaHBCaEMsb0JsQ2dwQmdDO0VPL3FCOUIscUJQa3JCK0IsRWtDanBCbEM7O0FBT0M7RWxCaUJFLFlBQVk7RW1CM0RkLDBCbkN5RWUsRWtDN0JkO0VBRkQ7SWxCaUJFLFlBQVk7SW1CdERWLHNCQUFzQjtJQUN0QiwwQkFBd0IsRWpDaUJ6Qjs7QWdDbUJIO0VsQmlCRSxZQUFZO0VtQjNEZCwwQm5DdURnQixFa0NYZjtFQUZEO0lsQmlCRSxZQUFZO0ltQnREVixzQkFBc0I7SUFDdEIsMEJBQXdCLEVqQ2lCekI7O0FnQ21CSDtFbEJpQkUsWUFBWTtFbUIzRGQsMEJuQ2dGZSxFa0NwQ2Q7RUFGRDtJbEJpQkUsWUFBWTtJbUJ0RFYsc0JBQXNCO0lBQ3RCLDBCQUF3QixFakNpQnpCOztBZ0NtQkg7RWxCaUJFLFlBQVk7RW1CM0RkLDBCbkNrRmUsRWtDdENkO0VBRkQ7SWxCaUJFLFlBQVk7SW1CdERWLHNCQUFzQjtJQUN0QiwwQkFBd0IsRWpDaUJ6Qjs7QWdDbUJIO0VsQmVFLFlBQVk7RW1CekRkLDBCbkMrRWUsRWtDbkNkO0VBRkQ7SWxCZUUsWUFBWTtJbUJwRFYsc0JBQXNCO0lBQ3RCLDBCQUF3QixFakNpQnpCOztBZ0NtQkg7RWxCaUJFLFlBQVk7RW1CM0RkLDBCbkM2RWUsRWtDakNkO0VBRkQ7SWxCaUJFLFlBQVk7SW1CdERWLHNCQUFzQjtJQUN0QiwwQkFBd0IsRWpDaUJ6Qjs7QWdDbUJIO0VsQmVFLFlBQVk7RW1CekRkLDBCbkNrRGdCLEVrQ05mO0VBRkQ7SWxCZUUsWUFBWTtJbUJwRFYsc0JBQXNCO0lBQ3RCLDBCQUF3QixFakNpQnpCOztBZ0NtQkg7RWxCaUJFLFlBQVk7RW1CM0RkLDBCbkN5RGdCLEVrQ2JmO0VBRkQ7SWxCaUJFLFlBQVk7SW1CdERWLHNCQUFzQjtJQUN0QiwwQkFBd0IsRWpDaUJ6Qjs7QWtDekJMO0VBQ0UsbUJBQStDO0VBQy9DLG9CcEN1bUJtQztFb0N0bUJuQywwQnBDa0RnQjtFT2pEZCxzQlA0TjBCLEVvQ3ZON0I7RXhCK0NHO0l3QnhESjtNQU9JLG1CcENrbUJpQyxFb0NobUJwQyxFQUFBOztBQUVEO0VBQ0UsaUJBQWlCO0VBQ2pCLGdCQUFnQjtFN0JUZCxpQjZCVXNCLEVBQ3pCOztBQ1hEO0VBQ0UseUJyQ3d0Qm1DO0VxQ3Z0Qm5DLG9CckN3dEJnQztFcUN2dEJoQyw4QkFBNkM7RTlCSDNDLHVCUDJOMkIsRXFDdE45Qjs7QUFHRDtFQUVFLGVBQWUsRUFDaEI7O0FBR0Q7RUFDRSxrQnJDd09xQixFcUN2T3RCOztBQU9EO0VBR0ksbUJBQW1CO0VBQ25CLGNyQzZyQmdDO0VxQzVyQmhDLGdCckM2ckJpQztFcUM1ckJqQyx5QnJDNHJCaUM7RXFDM3JCakMsZUFBZSxFQUNoQjs7QUFTRDtFQzNDQSxldEJzRmE7RXNCckZiLDBCdEJt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UHVNMkI7SU90TTNCLG1DUHNNMkIsRTBDcks1QjtFQWhCSDtJQW1CSSxzQkFBc0IsRXhDcENyQjtFd0NpQkw7SUF3QkksZTFDVGM7STBDVWQsdUIxQ2hCUyxFMENpQlY7RUExQkg7SUE4QkksV0FBVztJQUNYLFkxQ3RCUztJMEN1QlQsMEIxQ0NhO0kwQ0FiLHNCMUNBYSxFMENDZDs7QUFTSDtFQUVJLGdCQUFnQjtFQUNoQixlQUFlO0VBQ2YsaUJBQWlCLEVBQ2xCOztBQUxIO0VBU00sY0FBYyxFQUNmOztBQVZMO0VBZU0saUJBQWlCLEVBQ2xCOztBQ2xHSDtFQUNFLGUzQm1GVztFMkJsRlgsMEIzQmdGVyxFMkIvRVo7O0FBR0Q7O0VBQ0UsZTNCNkVXLEUyQmpFWjtFQWJEOzs7SUFJSSxlM0IwRVM7STJCekVULDBCQUF3QixFekNXekI7RXlDaEJIOztJQVNJLFlBQVk7SUFDWiwwQjNCb0VTO0kyQm5FVCxzQjNCbUVTLEUyQmxFVjs7QUFsQkg7RUFDRSxlM0JtRlc7RTJCbEZYLDBCM0JnRlcsRTJCL0VaOztBQUdEOztFQUNFLGUzQjZFVyxFMkJqRVo7RUFiRDs7O0lBSUksZTNCMEVTO0kyQnpFVCwwQkFBd0IsRXpDV3pCO0V5Q2hCSDs7SUFTSSxZQUFZO0lBQ1osMEIzQm9FUztJMkJuRVQsc0IzQm1FUyxFMkJsRVY7O0FBbEJIO0VBQ0UsZTNCbUZXO0UyQmxGWCwwQjNCZ0ZXLEUyQi9FWjs7QUFHRDs7RUFDRSxlM0I2RVcsRTJCakVaO0VBYkQ7OztJQUlJLGUzQjBFUztJMkJ6RVQsMEJBQXdCLEV6Q1d6QjtFeUNoQkg7O0lBU0ksWUFBWTtJQUNaLDBCM0JvRVM7STJCbkVULHNCM0JtRVMsRTJCbEVWOztBQWxCSDtFQUNFLGUzQm1GVztFMkJsRlgsMEIzQmdGVyxFMkIvRVo7O0FBR0Q7O0VBQ0UsZTNCNkVXLEUyQmpFWjtFQWJEOzs7SUFJSSxlM0IwRVM7STJCekVULDBCQUF3QixFekNXekI7RXlDaEJIOztJQVNJLFlBQVk7SUFDWiwwQjNCb0VTO0kyQm5FVCxzQjNCbUVTLEUyQmxFVjs7QUFsQkg7RUFDRSxlM0JtRlc7RTJCbEZYLDBCM0JnRlcsRTJCL0VaOztBQUdEOztFQUNFLGUzQjZFVyxFMkJqRVo7RUFiRDs7O0lBSUksZTNCMEVTO0kyQnpFVCwwQkFBd0IsRXpDV3pCO0V5Q2hCSDs7SUFTSSxZQUFZO0lBQ1osMEIzQm9FUztJMkJuRVQsc0IzQm1FUyxFMkJsRVY7O0FBbEJIO0VBQ0UsZTNCbUZXO0UyQmxGWCwwQjNCZ0ZXLEUyQi9FWjs7QUFHRDs7RUFDRSxlM0I2RVcsRTJCakVaO0VBYkQ7OztJQUlJLGUzQjBFUztJMkJ6RVQsMEJBQXdCLEV6Q1d6QjtFeUNoQkg7O0lBU0ksWUFBWTtJQUNaLDBCM0JvRVM7STJCbkVULHNCM0JtRVMsRTJCbEVWOztBQWxCSDtFQUNFLGUzQm1GVztFMkJsRlgsMEIzQmdGVyxFMkIvRVo7O0FBR0Q7O0VBQ0UsZTNCNkVXLEUyQmpFWjtFQWJEOzs7SUFJSSxlM0IwRVM7STJCekVULDBCQUF3QixFekNXekI7RXlDaEJIOztJQVNJLFlBQVk7SUFDWiwwQjNCb0VTO0kyQm5FVCxzQjNCbUVTLEUyQmxFVjs7QUFsQkg7RUFDRSxlM0JtRlc7RTJCbEZYLDBCM0JnRlcsRTJCL0VaOztBQUdEOztFQUNFLGUzQjZFVyxFMkJqRVo7RUFiRDs7O0lBSUksZTNCMEVTO0kyQnpFVCwwQkFBd0IsRXpDV3pCO0V5Q2hCSDs7SUFTSSxZQUFZO0lBQ1osMEIzQm9FUztJMkJuRVQsc0IzQm1FUyxFMkJsRVY7O0FDckJMO0VBQ0UsYUFBYTtFQUNiLGtCNUM4ekIyQztFNEM3ekIzQyxrQjVDd1BxQjtFNEN2UHJCLGVBQWU7RUFDZixZNUN3RFc7RTRDdkRYLDBCNUM2Q1c7RTRDNUNYLFlBQVksRUFPYjtFQWREO0lBVUksWTVDbURTO0k0Q2xEVCxzQkFBc0I7SUFDdEIsYUFBYSxFMUNhWjs7QTBDSEw7RUFDRSxXQUFXO0VBQ1gsd0JBQXdCO0VBQ3hCLFVBQVU7RUFDVix5QkFBeUIsRUFDMUI7O0FDcEJEO0VBQ0UsaUJBQWlCLEVBQ2xCOztBQUdEO0VBQ0UsZ0JBQWdCO0VBQ2hCLE9BQU87RUFD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RDtFM0U2Sm5ELGdCQUE2QjtFQUM3QixhQUFhO0VBQ2IsZUFBZSxFQVdoQjtFQWxCRDtJQVdJLG9CQUFvQjtJQUNwQixhQUYyQjtJQUczQixZQUgyQjtJQUkzQiw2QkFBNkI7SUFDN0IsNEJBQTRCO0lBQzVCLHVCQUF1QixFQUN4Qjs7QUFFSDtFQUVFLGFBQWE7RUFDYixnQkFBZ0I7RUFDaEIsd0IyRS9LbUQ7TTNFK0tuRCxvQjJFL0ttRDtVM0UrS25ELGdCMkUvS21ELEUzRTBOcEQ7RUEvQ0Q7SUFPSSxtQkFBbUIsRUFTcEI7SUFoQkg7TUFVTSxpQkFBaUIsRUFDbEI7SUFYTDtNQWFNLGlCQUFpQjtNQUNqQixnQzJFcExjLEUzRXFMZjtFQWZMO0lBbUJJLG1CQUFtQixFQTJCcEI7SUE5Q0g7TUFzQk0sWUFBWTtNQUNaLGVBQWU7TUFDZixZQUFZO01BQ1osWUFBWTtNQUNaLDBCMkUvTGU7TTNFZ01mLG9CQUFvQixFQUNyQjtJQTVCTDtNQThCTSxnQkFBZ0I7TUFDaEIsZ0MyRXJNYyxFM0V1TWY7SUFqQ0w7TUFtQ00sVUFBVTtNQUNWLFdBQVcsRUFDWjtJQXJDTDtNQXVDTSxlMkU1TWU7TTNFNk1mLGdCQUFnQixFQUtqQjtNQTdDTDtRQTBDUSxnQjJFL01hO1EzRWdOYixjMkVoTmEsRTNFaU5kOztBQUlQO0VBQ0UsdUJBQWU7TUFBZixtQkFBZTtVQUFmLGVBQWU7RUFDZixhQUFhLEVBQ2QiLCJmaWxlIjoicGFpbmVsLmNzcyIsInNvdXJjZXNDb250ZW50IjpbIi8qIEZSQU1FICovXG5AaW1wb3J0IFwiZnJhbWVcIjtcbiIsIi8qIEJPT1RTVFJBUCAqL1xuQGltcG9ydCBcImJvb3RzdHJhcC9zY3NzL2Jvb3RzdHJhcFwiO1xuXG4vKiBWQVJJQVZFSVMgKi9cbkBpbXBvcnQgXCJ2YXJpYWJsZXNcIjtcbi8qIENPUkVTICovXG5AaW1wb3J0ICdjb2xvcic7XG4vKiBCT1RBTyAqL1xuQGltcG9ydCAnLi9jb21wb25lbnRzL2J1dHRvbic7XG4vKiBCT1RBTyAqL1xuQGltcG9ydCAnLi9jb21wb25lbnRzL2NhcmQnO1xuXG4ubWFyY2FjYW97XG4gIGJvcmRlcjogMXB4IHNvbGlkIGJsYWNrO1xufVxuLmRlbGltaXRhZG9ye1xuICBib3JkZXItY29sb3I6ICRjb2xvcl9fbGlnaHRncmV5O1xuICBib3JkZXItd2lkdGg6IDA7XG4gIGJvcmRlci1zdHlsZTogc29saWQ7XG59XG4uZGVsLXJpZ2h0e1xuICBAZXh0ZW5kIC5kZWxpbWl0YWRvcjtcbiAgYm9yZGVyLXJpZ2h0LXdpZHRoOiAkc2l6ZV9fZGVsaW1pdGFkb3Jfd2lkdGg7XG59XG4uZGVsLWxlZnR7XG4gIEBleHRlbmQgLmRlbGltaXRhZG9yO1xuICBib3JkZXItbGVmdC13aWR0aDogJHNpemVfX2RlbGltaXRhZG9yX3dpZHRoO1xufVxuLmRlbC1ib3R0b217XG4gIEBleHRlbmQgLmRlbGltaXRhZG9yO1xuICBib3JkZXItYm90dG9tLXdpZHRoOiAkc2l6ZV9fZGVsaW1pdGFkb3Jfd2lkdGg7XG59XG4ud2hpdGViZ3tcbiAgYmFja2dyb3VuZC1jb2xvcjogd2hpdGU7XG59XG5ib2R5e1xuICBiYWNrZ3JvdW5kLWNvbG9yOiAkY29sb3JfX21haW5fYmc7XG59XG5zdmcuaWNvbi50ZXh0e1xuICBoZWlnaHQ6IDFlbTtcbiAgd2lkdGg6IDFlbTtcbn1cbiNmcmFtZXtcbiAgQGV4dGVuZCAuZC1mbGV4LCAuZmxleC1yb3c7XG4gIEBleHRlbmQgLmFsaWduLWl0ZW1zLXN0cmV0Y2g7XG59XG5hc2lkZS5sZWZ0e1xuICBAZXh0ZW5kIC5kLWZsZXgsIC5mbGV4LWNvbHVtbjtcbiAgQGV4dGVuZCAuYWxpZ24taXRlbXMtY2VudGVyO1xuICBAZXh0ZW5kIC53aGl0ZWJnO1xuXG4gIHdpZHRoOiAkc2l6ZV9fbGVmdF9zaWRlYmFyX3dpZHRoO1xuXG4gICNsb2dve1xuICAgICRwYWRkaW5nOiAyMHB4O1xuICAgIHBhZGRpbmc6JHBhZGRpbmc7XG4gICAgd2lkdGg6ICRzaXplX19sZWZ0X3NpZGViYXJfd2lkdGg7XG4gICAgaGVpZ2h0OiAkc2l6ZV9faGVhZGVyX2hlaWdodDtcbiAgICAmPnN2Z3tcbiAgICAgICRzaXplOiAkc2l6ZV9fbGVmdF9zaWRlYmFyX3dpZHRoIC0gMiokcGFkZGluZztcbiAgICAgIHdpZHRoOiAkc2l6ZTtcbiAgICAgIGhlaWdodDogJHNpemU7XG4gICAgfVxuICB9XG5cbiAgbmF2e1xuXG4gICAgcG9zaXRpb246IHJlbGF0aXZlO1xuICAgICRjdXJzb3JfaGVpZ2h0OiAkc2l6ZV9fbGVmdF9zaWRlYmFyX3dpZHRoLzM7XG4gICAgJjpiZWZvcmV7XG4gICAgICBjb250ZW50OiAnJztcbiAgICAgIGRpc3BsYXk6IGJsb2NrO1xuICAgICAgcG9zaXRpb246IGFic29sdXRlO1xuICAgICAgYmFja2dyb3VuZC1jb2xvcjogJGNvbG9yX19waW5rO1xuICAgICAgd2lkdGg6IDhweDtcbiAgICAgIGxlZnQ6LTIwcHg7XG4gICAgICB0b3A6IC04MHB4O1xuICAgICAgdHJhbnNpdGlvbjogbGVmdCwgLjVzLCB0b3AgLjVzO1xuICAgICAgYm94LXNoYWRvdzogMHB4IDFweCA5cHggM3B4IHJnYmEoMCwgMCwgMCwgMC40Mik7XG4gICAgICBib3JkZXItcmFkaXVzOiAxMDAlO1xuICAgICAgaGVpZ2h0OiAkY3Vyc29yX2hlaWdodDtcbiAgICB9XG4gICAgJi5jdXJzb3I6YmVmb3Jle1xuICAgICAgbGVmdDogLTRweDtcbiAgICB9XG4gICAgQGZvciAkaSBmcm9tIDEgdGhyb3VnaCAxMHtcbiAgICAgICR0b3A6ICRpICogJHNpemVfX2xlZnRfc2lkZWJhcl93aWR0aCAtICgkc2l6ZV9fbGVmdF9zaWRlYmFyX3dpZHRoICsgJGN1cnNvcl9oZWlnaHQpLzI7XG4gICAgICAmLml0ZW0tI3skaX06YmVmb3Jle1xuICAgICAgICB0b3A6JHRvcDtcbiAgICAgIH1cbiAgICB9XG5cbiAgICAmPmRpdi5pdGVte1xuICAgICAgQGV4dGVuZCAuZC1mbGV4O1xuICAgICAgQGV4dGVuZCAuYWxpZ24taXRlbXMtY2VudGVyLCAuanVzdGlmeS1jb250ZW50LWNlbnRlcjtcbiAgICAgIHdpZHRoOiAkc2l6ZV9fbGVmdF9zaWRlYmFyX3dpZHRoO1xuICAgICAgbGluZS1oZWlnaHQ6ICRzaXplX19sZWZ0X3NpZGViYXJfd2lkdGg7XG4gICAgICB0ZXh0LWFsaWduOiBjZW50ZXI7XG4gICAgICBoZWlnaHQ6ICRzaXplX19sZWZ0X3NpZGViYXJfd2lkdGg7XG4gICAgICB0ZXh0LWFsaWduOiBjZW50ZXI7XG4gICAgICBsaW5lLWhlaWdodDogJHNpemVfX2xlZnRfc2lkZWJhcl93aWR0aDtcbiAgICAgIHBvc2l0aW9uOiByZWxhdGl2ZTtcblxuICAgICAgJGNsaWNrYWJsZV9zaXplOiA0MCU7XG4gICAgICBhe1xuICAgICAgICBwb3NpdGlvbjogYWJzb2x1dGU7XG4gICAgICAgIHdpZHRoOiAkY2xpY2thYmxlX3NpemU7XG4gICAgICAgIGhlaWdodDogJGNsaWNrYWJsZV9zaXplO1xuICAgICAgfVxuICAgICAgLmljb257XG4gICAgICAgIGN1cnNvcjogcG9pbnRlcjtcbiAgICAgICAgc3Ryb2tlOiAkY29sb3JfX3Bpbms7XG4gICAgICAgIGZpbGw6ICRjb2xvcl9fcGluaztcbiAgICAgICAgd2lkdGg6ICRjbGlja2FibGVfc2l6ZTtcbiAgICAgICAgaGVpZ2h0OiAkY2xpY2thYmxlX3NpemU7XG4gICAgICAgIG1hcmdpbjogYXV0bztcbiAgICAgICAgdHJhbnNpdGlvbjogZmlsbCAuNXM7XG5cbiAgICAgICAgJjpob3ZlcntcbiAgICAgICAgICBmaWxsOiRjb2xvcl9fcGlua19oaWdodGxpZ2h0O1xuICAgICAgICB9XG5cbiAgICAgIH1cbiAgICB9XG4gIH1cbn1cbiNiZXNpZGV7XG4gIEBleHRlbmQgLmQtZmxleCwgLmZsZXgtY29sdW1uO1xuICBmbGV4OiAxIDEgYXV0bztcbn1cbmhlYWRlci5tYWlue1xuICBAZXh0ZW5kIC5kLWZsZXgsIC5mbGV4LXJvdztcbiAgQGV4dGVuZCAuYWxpZ24taXRlbXMtY2VudGVyO1xuICBAZXh0ZW5kIC53aGl0ZWJnO1xuXG4gIGZvbnQtc2l6ZTogJHNpemVfX2hlYWRlcl9mb250O1xuICBjb2xvcjogJGNvbG9yX19oZWFkZXI7XG4gIGhlaWdodDogJHNpemVfX2hlYWRlcl9oZWlnaHQ7XG5cbiAgJj4uaWNvbntcbiAgICAkc2l6ZTogMiokc2l6ZV9faGVhZGVyX2ZvbnQ7XG4gICAgbWFyZ2luLWxlZnQ6IDJlbTtcbiAgICBtYXJnaW4tcmlnaHQ6IDFlbTtcbiAgICBoZWlnaHQ6ICRzaXplO1xuICAgIHdpZHRoOiAkc2l6ZTtcbiAgICBmbGV4OiAwIDEgYXV0bztcblxuICAgICp7XG4gICAgICBzdHJva2U6ICRjb2xvcl9faGVhZGVyO1xuICAgICAgZmlsbDogJGNvbG9yX19oZWFkZXI7XG4gICAgfVxuICB9XG4gICY+aDF7XG4gICAgZmxleDogMSAxIGF1dG87XG4gICAgZm9udC13ZWlnaHQ6IDQwMDtcbiAgICBmb250LXNpemU6aW5oZXJpdDtcbiAgfVxufVxuI3VzZXItYWNjb3VudHtcbiAgQGV4dGVuZCAuZC1mbGV4LCAuZmxleC1yb3c7XG4gIEBleHRlbmQgLmFsaWduLWl0ZW1zLWNlbnRlciwgLmp1c3RpZnktY29udGVudC1hcm91bmQ7XG5cbiAgZmxleDowIDAgJHNpemVfX3JpZ2h0X3NpZGViYXJfd2lkdGg7XG4gIGZvbnQtc2l6ZTogJHNpemVfX2hlYWRlcl9mb250ICogLjU7XG4gIGhlaWdodDogMTAwJTtcbiAgcGFkZGluZzogMCAzZW07XG5cbiAgJj4uYXZhdGFye1xuICAgICRzaXplOiAkc2l6ZV9faGVhZGVyX2hlaWdodCAqIC42O1xuICAgIGJvcmRlci1yYWRpdXM6IDEwMCU7XG4gICAgaGVpZ2h0OiAkc2l6ZTtcbiAgICB3aWR0aDogJHNpemU7XG4gICAgYmFja2dyb3VuZC1yZXBlYXQ6IG5vLXJlcGVhdDtcbiAgICBiYWNrZ3JvdW5kLXBvc2l0aW9uOiBjZW50ZXI7XG4gICAgYmFja2dyb3VuZC1zaXplOiBjb3ZlcjtcbiAgfVxufVxuYXNpZGUucmlnaHR7XG4gIEBleHRlbmQgLndoaXRlYmc7XG4gIHBhZGRpbmc6IDNlbTtcbiAgZm9udC1zaXplOiAxNnB4O1xuICBmbGV4OiAwIDAgJHNpemVfX3JpZ2h0X3NpZGViYXJfd2lkdGg7XG5cbiAgaGVhZGVye1xuICAgIG1hcmdpbi1ib3R0b206IDRlbTtcblxuICAgIGgye1xuICAgICAgZm9udC1zaXplOiAxLjZlbTtcbiAgICB9XG4gICAgaDN7XG4gICAgICBmb250LXNpemU6IDEuMmVtO1xuICAgICAgY29sb3I6ICRjb2xvcl9faGVhZGVyO1xuICAgIH1cbiAgfVxuXG4gIC5zaWRlYmFyLXN1bW1hcnktaXRlbXtcbiAgICBtYXJnaW4tYm90dG9tOiAyZW07XG5cbiAgICAmOmJlZm9yZXtcbiAgICAgIGNvbnRlbnQ6ICcnO1xuICAgICAgZGlzcGxheTogYmxvY2s7XG4gICAgICB3aWR0aDogMTAwJTtcbiAgICAgIGhlaWdodDogNXB4O1xuICAgICAgYmFja2dyb3VuZC1jb2xvcjogJGNvbG9yX19waW5rO1xuICAgICAgbWFyZ2luLWJvdHRvbTogLjVlbTtcbiAgICB9XG4gICAgaDR7XG4gICAgICBmb250LXNpemU6IC44ZW07XG4gICAgICBjb2xvcjogJGNvbG9yX19oZWFkZXI7XG5cbiAgICB9XG4gICAgcHtcbiAgICAgIG1hcmdpbjogMDtcbiAgICAgIHBhZGRpbmc6IDA7XG4gICAgfVxuICAgIGF7XG4gICAgICBjb2xvcjogJGNvbG9yX19waW5rO1xuICAgICAgZm9udC1zaXplOiAuOGVtO1xuICAgICAgLmljb24gKntcbiAgICAgICAgc3Ryb2tlOiAkY29sb3JfX3Bpbms7XG4gICAgICAgIGZpbGw6ICRjb2xvcl9fcGluaztcbiAgICAgIH1cbiAgICB9XG4gIH1cbn1cbiNjb250ZW50e1xuICBmbGV4OiAxIDEgMTAwJTtcbiAgcGFkZGluZzogM2VtO1xufVxuIiwiLyohXG4gKiBCb290c3RyYXAgdjQuMC4wLWJldGEgKGh0dHBzOi8vZ2V0Ym9vdHN0cmFwLmNvbSlcbiAqIENvcHlyaWdodCAyMDExLTIwMTcgVGhlIEJvb3RzdHJhcCBBdXRob3JzXG4gKiBDb3B5cmlnaHQgMjAxMS0yMDE3IFR3aXR0ZXIsIEluYy5cbiAqIExpY2Vuc2VkIHVuZGVyIE1JVCAoaHR0cHM6Ly9naXRodWIuY29tL3R3YnMvYm9vdHN0cmFwL2Jsb2IvbWFzdGVyL0xJQ0VOU0UpXG4gKi9cblxuQGltcG9ydCBcImZ1bmN0aW9uc1wiO1xuQGltcG9ydCBcInZhcmlhYmxlc1wiO1xuQGltcG9ydCBcIm1peGluc1wiO1xuQGltcG9ydCBcInByaW50XCI7XG5AaW1wb3J0IFwicmVib290XCI7XG5AaW1wb3J0IFwidHlwZVwiO1xuQGltcG9ydCBcImltYWdlc1wiO1xuQGltcG9ydCBcImNvZGVcIjtcbkBpbXBvcnQgXCJncmlkXCI7XG5AaW1wb3J0IFwidGFibGVzXCI7XG5AaW1wb3J0IFwiZm9ybXNcIjtcbkBpbXBvcnQgXCJidXR0b25zXCI7XG5AaW1wb3J0IFwidHJhbnNpdGlvbnNcIjtcbkBpbXBvcnQgXCJkcm9wZG93blwiO1xuQGltcG9ydCBcImJ1dHRvbi1ncm91cFwiO1xuQGltcG9ydCBcImlucHV0LWdyb3VwXCI7XG5AaW1wb3J0IFwiY3VzdG9tLWZvcm1zXCI7XG5AaW1wb3J0IFwibmF2XCI7XG5AaW1wb3J0IFwibmF2YmFyXCI7XG5AaW1wb3J0IFwiY2FyZFwiO1xuQGltcG9ydCBcImJyZWFkY3J1bWJcIjtcbkBpbXBvcnQgXCJwYWdpbmF0aW9uXCI7XG5AaW1wb3J0IFwiYmFkZ2VcIjtcbkBpbXBvcnQgXCJqdW1ib3Ryb25cIjtcbkBpbXBvcnQgXCJhbGVydFwiO1xuQGltcG9ydCBcInByb2dyZXNzXCI7XG5AaW1wb3J0IFwibWVkaWFcIjtcbkBpbXBvcnQgXCJsaXN0LWdyb3VwXCI7XG5AaW1wb3J0IFwiY2xvc2VcIjtcbkBpbXBvcnQgXCJtb2RhbFwiO1xuQGltcG9ydCBcInRvb2x0aXBcIjtcbkBpbXBvcnQgXCJwb3BvdmVyXCI7XG5AaW1wb3J0IFwiY2Fyb3VzZWxcIjtcbkBpbXBvcnQgXCJ1dGlsaXRpZXNcIjtcbiIsIi8vIHNjc3MtbGludDpkaXNhYmxlIFF1YWxpZnlpbmdFbGVtZW50XG5cbi8vIFNvdXJjZTogaHR0cHM6Ly9naXRodWIuY29tL2g1YnAvaHRtbDUtYm9pbGVycGxhdGUvYmxvYi9tYXN0ZXIvc3JjL2Nzcy9tYWluLmNzc1xuXG4vLyA9PT09PT09PT09PT09PT09PT09PT09PT09PT09PT09PT09PT09PT09PT09PT09PT09PT09PT09PT09PT09PT09PT09PT09PT09PVxuLy8gUHJpbnQgc3R5bGVzLlxuLy8gSW5saW5lZCB0byBhdm9pZCB0aGUgYWRkaXRpb25hbCBIVFRQIHJlcXVlc3Q6XG4vLyBodHRwOi8vd3d3LnBocGllZC5jb20vZGVsYXktbG9hZGluZy15b3VyLXByaW50LWNzcy9cbi8vID09PT09PT09PT09PT09PT09PT09PT09PT09PT09PT09PT09PT09PT09PT09PT09PT09PT09PT09PT09PT09PT09PT09PT09PT09XG5cbkBpZiAkZW5hYmxlLXByaW50LXN0eWxlcyB7XG4gIEBtZWRpYSBwcmludCB7XG4gICAgKixcbiAgICAqOjpiZWZvcmUsXG4gICAgKjo6YWZ0ZXIge1xuICAgICAgLy8gQm9vdHN0cmFwIHNwZWNpZmljOyBjb21tZW50IG91dCBgY29sb3JgIGFuZCBgYmFja2dyb3VuZGBcbiAgICAgIC8vY29sb3I6ICMwMDAgIWltcG9ydGFudDsgLy8gQmxhY2sgcHJpbnRzIGZhc3RlcjpcbiAgICAgICAgICAgICAgICAgICAgICAgICAgICAgICAgLy8gICBodHRwOi8vd3d3LnNhbmJlaWppLmNvbS9hcmNoaXZlcy85NTNcbiAgICAgIHRleHQtc2hhZG93OiBub25lICFpbXBvcnRhbnQ7XG4gICAgICAvL2JhY2tncm91bmQ6IHRyYW5zcGFyZW50ICFpbXBvcnRhbnQ7XG4gICAgICBib3gtc2hhZG93OiBub25lICFpbXBvcnRhbnQ7XG4gICAgfVxuXG4gICAgYSxcbiAgICBhOnZpc2l0ZWQge1xuICAgICAgdGV4dC1kZWNvcmF0aW9uOiB1bmRlcmxpbmU7XG4gICAgfVxuXG4gICAgLy8gQm9vdHN0cmFwIHNwZWNpZmljOyBjb21tZW50IHRoZSBmb2xsb3dpbmcgc2VsZWN0b3Igb3V0XG4gICAgLy9hW2hyZWZdOjphZnRlciB7XG4gICAgLy8gIGNvbnRlbnQ6IFwiIChcIiBhdHRyKGhyZWYpIFwiKVwiO1xuICAgIC8vfVxuXG4gICAgYWJiclt0aXRsZV06OmFmdGVyIHtcbiAgICAgIGNvbnRlbnQ6IFwiIChcIiBhdHRyKHRpdGxlKSBcIilcIjtcbiAgICB9XG5cbiAgICAvLyBCb290c3RyYXAgc3BlY2lmaWM7IGNvbW1lbnQgdGhlIGZvbGxvd2luZyBzZWxlY3RvciBvdXRcbiAgICAvL1xuICAgIC8vIERvbid0IHNob3cgbGlua3MgdGhhdCBhcmUgZnJhZ21lbnQgaWRlbnRpZmllcnMsXG4gICAgLy8gb3IgdXNlIHRoZSBgamF2YXNjcmlwdDpgIHBzZXVkbyBwcm90b2NvbFxuICAgIC8vXG5cbiAgICAvL2FbaHJlZl49XCIjXCJdOjphZnRlcixcbiAgICAvL2FbaHJlZl49XCJqYXZhc2NyaXB0OlwiXTo6YWZ0ZXIge1xuICAgIC8vIGNvbnRlbnQ6IFwiXCI7XG4gICAgLy99XG5cbiAgICBwcmUge1xuICAgICAgd2hpdGUtc3BhY2U6IHByZS13cmFwICFpbXBvcnRhbnQ7XG4gICAgfVxuICAgIHByZSxcbiAgICBibG9ja3F1b3RlIHtcbiAgICAgIGJvcmRlcjogJGJvcmRlci13aWR0aCBzb2xpZCAjOTk5OyAgIC8vIEJvb3RzdHJhcCBjdXN0b20gY29kZTsgdXNpbmcgYCRib3JkZXItd2lkdGhgIGluc3RlYWQgb2YgMXB4XG4gICAgICBwYWdlLWJyZWFrLWluc2lkZTogYXZvaWQ7XG4gICAgfVxuXG4gICAgLy9cbiAgICAvLyBQcmludGluZyBUYWJsZXM6XG4gICAgLy8gaHR0cDovL2Nzcy1kaXNjdXNzLmluY3V0aW8uY29tL3dpa2kvUHJpbnRpbmdfVGFibGVzXG4gICAgLy9cblxuICAgIHRoZWFkIHtcbiAgICAgIGRpc3BsYXk6IHRhYmxlLWhlYWRlci1ncm91cDtcbiAgICB9XG5cbiAgICB0cixcbiAgICBpbWcge1xuICAgICAgcGFnZS1icmVhay1pbnNpZGU6IGF2b2lkO1xuICAgIH1cblxuICAgIHAsXG4gICAgaDIsXG4gICAgaDMge1xuICAgICAgb3JwaGFuczogMztcbiAgICAgIHdpZG93czogMztcbiAgICB9XG5cbiAgICBoMixcbiAgICBoMyB7XG4gICAgICBwYWdlLWJyZWFrLWFmdGVyOiBhdm9pZDtcbiAgICB9XG5cbiAgICAvLyBCb290c3RyYXAgc3BlY2lmaWMgY2hhbmdlcyBzdGFydFxuXG4gICAgLy8gQm9vdHN0cmFwIGNvbXBvbmVudHNcbiAgICAubmF2YmFyIHtcbiAgICAgIGRpc3BsYXk6IG5vbmU7XG4gICAgfVxuICAgIC5iYWRnZSB7XG4gICAgICBib3JkZXI6ICRib3JkZXItd2lkdGggc29saWQgIzAwMDtcbiAgICB9XG5cbiAgICAudGFibGUge1xuICAgICAgYm9yZGVyLWNvbGxhcHNlOiBjb2xsYXBzZSAhaW1wb3J0YW50O1xuXG4gICAgICB0ZCxcbiAgICAgIHRoIHtcbiAgICAgICAgYmFja2dyb3VuZC1jb2xvcjogI2ZmZiAhaW1wb3J0YW50O1xuICAgICAgfVxuICAgIH1cbiAgICAudGFibGUtYm9yZGVyZWQge1xuICAgICAgdGgsXG4gICAgICB0ZCB7XG4gICAgICAgIGJvcmRlcjogMXB4IHNvbGlkICNkZGQgIWltcG9ydGFudDtcbiAgICAgIH1cbiAgICB9XG5cbiAgICAvLyBCb290c3RyYXAgc3BlY2lmaWMgY2hhbmdlcyBlbmRcbiAgfVxufVxuIiwiLy8gc2Nzcy1saW50OmRpc2FibGUgUXVhbGlmeWluZ0VsZW1lbnQsIER1cGxpY2F0ZVByb3BlcnR5LCBWZW5kb3JQcmVmaXhcblxuLy8gUmVib290XG4vL1xuLy8gTm9ybWFsaXphdGlvbiBvZiBIVE1MIGVsZW1lbnRzLCBtYW51YWxseSBmb3JrZWQgZnJvbSBOb3JtYWxpemUuY3NzIHRvIHJlbW92ZVxuLy8gc3R5bGVzIHRhcmdldGluZyBpcnJlbGV2YW50IGJyb3dzZXJzIHdoaWxlIGFwcGx5aW5nIG5ldyBzdHlsZXMuXG4vL1xuLy8gTm9ybWFsaXplIGlzIGxpY2Vuc2VkIE1JVC4gaHR0cHM6Ly9naXRodWIuY29tL25lY29sYXMvbm9ybWFsaXplLmNzc1xuXG5cbi8vIERvY3VtZW50XG4vL1xuLy8gMS4gQ2hhbmdlIGZyb20gYGJveC1zaXppbmc6IGNvbnRlbnQtYm94YCBzbyB0aGF0IGB3aWR0aGAgaXMgbm90IGFmZmVjdGVkIGJ5IGBwYWRkaW5nYCBvciBgYm9yZGVyYC5cbi8vIDIuIENoYW5nZSB0aGUgZGVmYXVsdCBmb250IGZhbWlseSBpbiBhbGwgYnJvd3NlcnMuXG4vLyAzLiBDb3JyZWN0IHRoZSBsaW5lIGhlaWdodCBpbiBhbGwgYnJvd3NlcnMuXG4vLyA0LiBQcmV2ZW50IGFkanVzdG1lbnRzIG9mIGZvbnQgc2l6ZSBhZnRlciBvcmllbnRhdGlvbiBjaGFuZ2VzIGluIElFIG9uIFdpbmRvd3MgUGhvbmUgYW5kIGluIGlPUy5cbi8vIDUuIFNldHRpbmcgQHZpZXdwb3J0IGNhdXNlcyBzY3JvbGxiYXJzIHRvIG92ZXJsYXAgY29udGVudCBpbiBJRTExIGFuZCBFZGdlLCBzb1xuLy8gICAgd2UgZm9yY2UgYSBub24tb3ZlcmxhcHBpbmcsIG5vbi1hdXRvLWhpZGluZyBzY3JvbGxiYXIgdG8gY291bnRlcmFjdC5cbi8vIDYuIENoYW5nZSB0aGUgZGVmYXVsdCB0YXAgaGlnaGxpZ2h0IHRvIGJlIGNvbXBsZXRlbHkgdHJhbnNwYXJlbnQgaW4gaU9TLlxuXG4qLFxuKjo6YmVmb3JlLFxuKjo6YWZ0ZXIge1xuICBib3gtc2l6aW5nOiBib3JkZXItYm94OyAvLyAxXG59XG5cbmh0bWwge1xuICBmb250LWZhbWlseTogc2Fucy1zZXJpZjsgLy8gMlxuICBsaW5lLWhlaWdodDogMS4xNTsgLy8gM1xuICAtd2Via2l0LXRleHQtc2l6ZS1hZGp1c3Q6IDEwMCU7IC8vIDRcbiAgLW1zLXRleHQtc2l6ZS1hZGp1c3Q6IDEwMCU7IC8vIDRcbiAgLW1zLW92ZXJmbG93LXN0eWxlOiBzY3JvbGxiYXI7IC8vIDVcbiAgLXdlYmtpdC10YXAtaGlnaGxpZ2h0LWNvbG9yOiByZ2JhKDAsMCwwLDApOyAvLyA2XG59XG5cbi8vIElFMTArIGRvZXNuJ3QgaG9ub3IgYDxtZXRhIG5hbWU9XCJ2aWV3cG9ydFwiPmAgaW4gc29tZSBjYXNlcy5cbkBhdC1yb290IHtcbiAgQC1tcy12aWV3cG9ydCB7IHdpZHRoOiBkZXZpY2Utd2lkdGg7IH1cbn1cblxuLy8gU2hpbSBmb3IgXCJuZXdcIiBIVE1MNSBzdHJ1Y3R1cmFsIGVsZW1lbnRzIHRvIGRpc3BsYXkgY29ycmVjdGx5IChJRTEwLCBvbGRlciBicm93c2VycylcbmFydGljbGUsIGFzaWRlLCBkaWFsb2csIGZpZ2NhcHRpb24sIGZpZ3VyZSwgZm9vdGVyLCBoZWFkZXIsIGhncm91cCwgbWFpbiwgbmF2LCBzZWN0aW9uIHtcbiAgZGlzcGxheTogYmxvY2s7XG59XG5cbi8vIEJvZHlcbi8vXG4vLyAxLiBSZW1vdmUgdGhlIG1hcmdpbiBpbiBhbGwgYnJvd3NlcnMuXG4vLyAyLiBBcyBhIGJlc3QgcHJhY3RpY2UsIGFwcGx5IGEgZGVmYXVsdCBgYmFja2dyb3VuZC1jb2xvcmAuXG4vLyAzLiBTZXQgYW4gZXhwbGljaXQgaW5pdGlhbCB0ZXh0LWFsaWduIHZhbHVlIHNvIHRoYXQgd2UgY2FuIGxhdGVyIHVzZSB0aGVcbi8vICAgIHRoZSBgaW5oZXJpdGAgdmFsdWUgb24gdGhpbmdzIGxpa2UgYDx0aD5gIGVsZW1lbnRzLlxuXG5ib2R5IHtcbiAgbWFyZ2luOiAwOyAvLyAxXG4gIGZvbnQtZmFtaWx5OiAkZm9udC1mYW1pbHktYmFzZTtcbiAgZm9udC1zaXplOiAkZm9udC1zaXplLWJhc2U7XG4gIGZvbnQtd2VpZ2h0OiAkZm9udC13ZWlnaHQtYmFzZTtcbiAgbGluZS1oZWlnaHQ6ICRsaW5lLWhlaWdodC1iYXNlO1xuICBjb2xvcjogJGJvZHktY29sb3I7XG4gIHRleHQtYWxpZ246IGxlZnQ7IC8vIDNcbiAgYmFja2dyb3VuZC1jb2xvcjogJGJvZHktYmc7IC8vIDJcbn1cblxuLy8gU3VwcHJlc3MgdGhlIGZvY3VzIG91dGxpbmUgb24gZWxlbWVudHMgdGhhdCBjYW5ub3QgYmUgYWNjZXNzZWQgdmlhIGtleWJvYXJkLlxuLy8gVGhpcyBwcmV2ZW50cyBhbiB1bndhbnRlZCBmb2N1cyBvdXRsaW5lIGZyb20gYXBwZWFyaW5nIGFyb3VuZCBlbGVtZW50cyB0aGF0XG4vLyBtaWdodCBzdGlsbCByZXNwb25kIHRvIHBvaW50ZXIgZXZlbnRzLlxuLy9cbi8vIENyZWRpdDogaHR0cHM6Ly9naXRodWIuY29tL3N1aXRjc3MvYmFzZVxuW3RhYmluZGV4PVwiLTFcIl06Zm9jdXMge1xuICBvdXRsaW5lOiBub25lICFpbXBvcnRhbnQ7XG59XG5cblxuLy8gQ29udGVudCBncm91cGluZ1xuLy9cbi8vIDEuIEFkZCB0aGUgY29ycmVjdCBib3ggc2l6aW5nIGluIEZpcmVmb3guXG4vLyAyLiBTaG93IHRoZSBvdmVyZmxvdyBpbiBFZGdlIGFuZCBJRS5cblxuaHIge1xuICBib3gtc2l6aW5nOiBjb250ZW50LWJveDsgLy8gMVxuICBoZWlnaHQ6IDA7IC8vIDFcbiAgb3ZlcmZsb3c6IHZpc2libGU7IC8vIDJcbn1cblxuXG4vL1xuLy8gVHlwb2dyYXBoeVxuLy9cblxuLy8gUmVtb3ZlIHRvcCBtYXJnaW5zIGZyb20gaGVhZGluZ3Ncbi8vXG4vLyBCeSBkZWZhdWx0LCBgPGgxPmAtYDxoNj5gIGFsbCByZWNlaXZlIHRvcCBhbmQgYm90dG9tIG1hcmdpbnMuIFdlIG51a2UgdGhlIHRvcFxuLy8gbWFyZ2luIGZvciBlYXNpZXIgY29udHJvbCB3aXRoaW4gdHlwZSBzY2FsZXMgYXMgaXQgYXZvaWRzIG1hcmdpbiBjb2xsYXBzaW5nLlxuaDEsIGgyLCBoMywgaDQsIGg1LCBoNiB7XG4gIG1hcmdpbi10b3A6IDA7XG4gIG1hcmdpbi1ib3R0b206IC41cmVtO1xufVxuXG4vLyBSZXNldCBtYXJnaW5zIG9uIHBhcmFncmFwaHNcbi8vXG4vLyBTaW1pbGFybHksIHRoZSB0b3AgbWFyZ2luIG9uIGA8cD5gcyBnZXQgcmVzZXQuIEhvd2V2ZXIsIHdlIGFsc28gcmVzZXQgdGhlXG4vLyBib3R0b20gbWFyZ2luIHRvIHVzZSBgcmVtYCB1bml0cyBpbnN0ZWFkIG9mIGBlbWAuXG5wIHtcbiAgbWFyZ2luLXRvcDogMDtcbiAgbWFyZ2luLWJvdHRvbTogJHBhcmFncmFwaC1tYXJnaW4tYm90dG9tO1xufVxuXG4vLyBBYmJyZXZpYXRpb25zXG4vL1xuLy8gMS4gUmVtb3ZlIHRoZSBib3R0b20gYm9yZGVyIGluIEZpcmVmb3ggMzktLlxuLy8gMi4gQWRkIHRoZSBjb3JyZWN0IHRleHQgZGVjb3JhdGlvbiBpbiBDaHJvbWUsIEVkZ2UsIElFLCBPcGVyYSwgYW5kIFNhZmFyaS5cbi8vIDMuIEFkZCBleHBsaWNpdCBjdXJzb3IgdG8gaW5kaWNhdGUgY2hhbmdlZCBiZWhhdmlvci5cbi8vIDQuIER1cGxpY2F0ZSBiZWhhdmlvciB0byB0aGUgZGF0YS0qIGF0dHJpYnV0ZSBmb3Igb3VyIHRvb2x0aXAgcGx1Z2luXG5cbmFiYnJbdGl0bGVdLFxuYWJicltkYXRhLW9yaWdpbmFsLXRpdGxlXSB7IC8vIDRcbiAgdGV4dC1kZWNvcmF0aW9uOiB1bmRlcmxpbmU7IC8vIDJcbiAgdGV4dC1kZWNvcmF0aW9uOiB1bmRlcmxpbmUgZG90dGVkOyAvLyAyXG4gIGN1cnNvcjogaGVscDsgLy8gM1xuICBib3JkZXItYm90dG9tOiAwOyAvLyAxXG59XG5cbmFkZHJlc3Mge1xuICBtYXJnaW4tYm90dG9tOiAxcmVtO1xuICBmb250LXN0eWxlOiBub3JtYWw7XG4gIGxpbmUtaGVpZ2h0OiBpbmhlcml0O1xufVxuXG5vbCxcbnVsLFxuZGwge1xuICBtYXJnaW4tdG9wOiAwO1xuICBtYXJnaW4tYm90dG9tOiAxcmVtO1xufVxuXG5vbCBvbCxcbnVsIHVsLFxub2wgdWwsXG51bCBvbCB7XG4gIG1hcmdpbi1ib3R0b206IDA7XG59XG5cbmR0IHtcbiAgZm9udC13ZWlnaHQ6ICRkdC1mb250LXdlaWdodDtcbn1cblxuZGQge1xuICBtYXJnaW4tYm90dG9tOiAuNXJlbTtcbiAgbWFyZ2luLWxlZnQ6IDA7IC8vIFVuZG8gYnJvd3NlciBkZWZhdWx0XG59XG5cbmJsb2NrcXVvdGUge1xuICBtYXJnaW46IDAgMCAxcmVtO1xufVxuXG5kZm4ge1xuICBmb250LXN0eWxlOiBpdGFsaWM7IC8vIEFkZCB0aGUgY29ycmVjdCBmb250IHN0eWxlIGluIEFuZHJvaWQgNC4zLVxufVxuXG5iLFxuc3Ryb25nIHtcbiAgZm9udC13ZWlnaHQ6IGJvbGRlcjsgLy8gQWRkIHRoZSBjb3JyZWN0IGZvbnQgd2VpZ2h0IGluIENocm9tZSwgRWRnZSwgYW5kIFNhZmFyaVxufVxuXG5zbWFsbCB7XG4gIGZvbnQtc2l6ZTogODAlOyAvLyBBZGQgdGhlIGNvcnJlY3QgZm9udCBzaXplIGluIGFsbCBicm93c2Vyc1xufVxuXG4vL1xuLy8gUHJldmVudCBgc3ViYCBhbmQgYHN1cGAgZWxlbWVudHMgZnJvbSBhZmZlY3RpbmcgdGhlIGxpbmUgaGVpZ2h0IGluXG4vLyBhbGwgYnJvd3NlcnMuXG4vL1xuXG5zdWIsXG5zdXAge1xuICBwb3NpdGlvbjogcmVsYXRpdmU7XG4gIGZvbnQtc2l6ZTogNzUlO1xuICBsaW5lLWhlaWdodDogMDtcbiAgdmVydGljYWwtYWxpZ246IGJhc2VsaW5lO1xufVxuXG5zdWIgeyBib3R0b206IC0uMjVlbTsgfVxuc3VwIHsgdG9wOiAtLjVlbTsgfVxuXG5cbi8vXG4vLyBMaW5rc1xuLy9cblxuYSB7XG4gIGNvbG9yOiAkbGluay1jb2xvcjtcbiAgdGV4dC1kZWNvcmF0aW9uOiAkbGluay1kZWNvcmF0aW9uO1xuICBiYWNrZ3JvdW5kLWNvbG9yOiB0cmFuc3BhcmVudDsgLy8gUmVtb3ZlIHRoZSBncmF5IGJhY2tncm91bmQgb24gYWN0aXZlIGxpbmtzIGluIElFIDEwLlxuICAtd2Via2l0LXRleHQtZGVjb3JhdGlvbi1za2lwOiBvYmplY3RzOyAvLyBSZW1vdmUgZ2FwcyBpbiBsaW5rcyB1bmRlcmxpbmUgaW4gaU9TIDgrIGFuZCBTYWZhcmkgOCsuXG5cbiAgQGluY2x1ZGUgaG92ZXIge1xuICAgIGNvbG9yOiAkbGluay1ob3Zlci1jb2xvcjtcbiAgICB0ZXh0LWRlY29yYXRpb246ICRsaW5rLWhvdmVyLWRlY29yYXRpb247XG4gIH1cbn1cblxuLy8gQW5kIHVuZG8gdGhlc2Ugc3R5bGVzIGZvciBwbGFjZWhvbGRlciBsaW5rcy9uYW1lZCBhbmNob3JzICh3aXRob3V0IGhyZWYpXG4vLyB3aGljaCBoYXZlIG5vdCBiZWVuIG1hZGUgZXhwbGljaXRseSBrZXlib2FyZC1mb2N1c2FibGUgKHdpdGhvdXQgdGFiaW5kZXgpLlxuLy8gSXQgd291bGQgYmUgbW9yZSBzdHJhaWdodGZvcndhcmQgdG8ganVzdCB1c2UgYVtocmVmXSBpbiBwcmV2aW91cyBibG9jaywgYnV0IHRoYXRcbi8vIGNhdXNlcyBzcGVjaWZpY2l0eSBpc3N1ZXMgaW4gbWFueSBvdGhlciBzdHlsZXMgdGhhdCBhcmUgdG9vIGNvbXBsZXggdG8gZml4LlxuLy8gU2VlIGh0dHBzOi8vZ2l0aHViLmNvbS90d2JzL2Jvb3RzdHJhcC9pc3N1ZXMvMTk0MDJcblxuYTpub3QoW2hyZWZdKTpub3QoW3RhYmluZGV4XSkge1xuICBjb2xvcjogaW5oZXJpdDtcbiAgdGV4dC1kZWNvcmF0aW9uOiBub25lO1xuXG4gIEBpbmNsdWRlIGhvdmVyLWZvY3VzIHtcbiAgICBjb2xvcjogaW5oZXJpdDtcbiAgICB0ZXh0LWRlY29yYXRpb246IG5vbmU7XG4gIH1cblxuICAmOmZvY3VzIHtcbiAgICBvdXRsaW5lOiAwO1xuICB9XG59XG5cblxuLy9cbi8vIENvZGVcbi8vXG5cbnByZSxcbmNvZGUsXG5rYmQsXG5zYW1wIHtcbiAgZm9udC1mYW1pbHk6IG1vbm9zcGFjZSwgbW9ub3NwYWNlOyAvLyBDb3JyZWN0IHRoZSBpbmhlcml0YW5jZSBhbmQgc2NhbGluZyBvZiBmb250IHNpemUgaW4gYWxsIGJyb3dzZXJzLlxuICBmb250LXNpemU6IDFlbTsgLy8gQ29ycmVjdCB0aGUgb2RkIGBlbWAgZm9udCBzaXppbmcgaW4gYWxsIGJyb3dzZXJzLlxufVxuXG5wcmUge1xuICAvLyBSZW1vdmUgYnJvd3NlciBkZWZhdWx0IHRvcCBtYXJnaW5cbiAgbWFyZ2luLXRvcDogMDtcbiAgLy8gUmVzZXQgYnJvd3NlciBkZWZhdWx0IG9mIGAxZW1gIHRvIHVzZSBgcmVtYHNcbiAgbWFyZ2luLWJvdHRvbTogMXJlbTtcbiAgLy8gRG9uJ3QgYWxsb3cgY29udGVudCB0byBicmVhayBvdXRzaWRlXG4gIG92ZXJmbG93OiBhdXRvO1xufVxuXG5cbi8vXG4vLyBGaWd1cmVzXG4vL1xuXG5maWd1cmUge1xuICAvLyBBcHBseSBhIGNvbnNpc3RlbnQgbWFyZ2luIHN0cmF0ZWd5IChtYXRjaGVzIG91ciB0eXBlIHN0eWxlcykuXG4gIG1hcmdpbjogMCAwIDFyZW07XG59XG5cblxuLy9cbi8vIEltYWdlcyBhbmQgY29udGVudFxuLy9cblxuaW1nIHtcbiAgdmVydGljYWwtYWxpZ246IG1pZGRsZTtcbiAgYm9yZGVyLXN0eWxlOiBub25lOyAvLyBSZW1vdmUgdGhlIGJvcmRlciBvbiBpbWFnZXMgaW5zaWRlIGxpbmtzIGluIElFIDEwLS5cbn1cblxuc3ZnOm5vdCg6cm9vdCkge1xuICBvdmVyZmxvdzogaGlkZGVuOyAvLyBIaWRlIHRoZSBvdmVyZmxvdyBpbiBJRVxufVxuXG5cbi8vIEF2b2lkIDMwMG1zIGNsaWNrIGRlbGF5IG9uIHRvdWNoIGRldmljZXMgdGhhdCBzdXBwb3J0IHRoZSBgdG91Y2gtYWN0aW9uYCBDU1MgcHJvcGVydHkuXG4vL1xuLy8gSW4gcGFydGljdWxhciwgdW5saWtlIG1vc3Qgb3RoZXIgYnJvd3NlcnMsIElFMTErRWRnZSBvbiBXaW5kb3dzIDEwIG9uIHRvdWNoIGRldmljZXMgYW5kIElFIE1vYmlsZSAxMC0xMVxuLy8gRE9OJ1QgcmVtb3ZlIHRoZSBjbGljayBkZWxheSB3aGVuIGA8bWV0YSBuYW1lPVwidmlld3BvcnRcIiBjb250ZW50PVwid2lkdGg9ZGV2aWNlLXdpZHRoXCI+YCBpcyBwcmVzZW50LlxuLy8gSG93ZXZlciwgdGhleSBETyBzdXBwb3J0IHJlbW92aW5nIHRoZSBjbGljayBkZWxheSB2aWEgYHRvdWNoLWFjdGlvbjogbWFuaXB1bGF0aW9uYC5cbi8vIFNlZTpcbi8vICogaHR0cHM6Ly92NC1hbHBoYS5nZXRib290c3RyYXAuY29tL2NvbnRlbnQvcmVib290LyNjbGljay1kZWxheS1vcHRpbWl6YXRpb24tZm9yLXRvdWNoXG4vLyAqIGh0dHA6Ly9jYW5pdXNlLmNvbS8jZmVhdD1jc3MtdG91Y2gtYWN0aW9uXG4vLyAqIGh0dHBzOi8vcGF0cmlja2hsYXVrZS5naXRodWIuaW8vdG91Y2gvdGVzdHMvcmVzdWx0cy8jc3VwcHJlc3NpbmctMzAwbXMtZGVsYXlcblxuYSxcbmFyZWEsXG5idXR0b24sXG5bcm9sZT1cImJ1dHRvblwiXSxcbmlucHV0LFxubGFiZWwsXG5zZWxlY3QsXG5zdW1tYXJ5LFxudGV4dGFyZWEge1xuICB0b3VjaC1hY3Rpb246IG1hbmlwdWxhdGlvbjtcbn1cblxuXG4vL1xuLy8gVGFibGVzXG4vL1xuXG50YWJsZSB7XG4gIGJvcmRlci1jb2xsYXBzZTogY29sbGFwc2U7IC8vIFByZXZlbnQgZG91YmxlIGJvcmRlcnNcbn1cblxuY2FwdGlvbiB7XG4gIHBhZGRpbmctdG9wOiAkdGFibGUtY2VsbC1wYWRkaW5nO1xuICBwYWRkaW5nLWJvdHRvbTogJHRhYmxlLWNlbGwtcGFkZGluZztcbiAgY29sb3I6ICR0ZXh0LW11dGVkO1xuICB0ZXh0LWFsaWduOiBsZWZ0O1xuICBjYXB0aW9uLXNpZGU6IGJvdHRvbTtcbn1cblxudGgge1xuICAvLyBNYXRjaGVzIGRlZmF1bHQgYDx0ZD5gIGFsaWdubWVudCBieSBpbmhlcml0aW5nIGZyb20gdGhlIGA8Ym9keT5gLCBvciB0aGVcbiAgLy8gY2xvc2VzdCBwYXJlbnQgd2l0aCBhIHNldCBgdGV4dC1hbGlnbmAuXG4gIHRleHQtYWxpZ246IGluaGVyaXQ7XG59XG5cblxuLy9cbi8vIEZvcm1zXG4vL1xuXG5sYWJlbCB7XG4gIC8vIEFsbG93IGxhYmVscyB0byB1c2UgYG1hcmdpbmAgZm9yIHNwYWNpbmcuXG4gIGRpc3BsYXk6IGlubGluZS1ibG9jaztcbiAgbWFyZ2luLWJvdHRvbTogLjVyZW07XG59XG5cbi8vIFdvcmsgYXJvdW5kIGEgRmlyZWZveC9JRSBidWcgd2hlcmUgdGhlIHRyYW5zcGFyZW50IGBidXR0b25gIGJhY2tncm91bmRcbi8vIHJlc3VsdHMgaW4gYSBsb3NzIG9mIHRoZSBkZWZhdWx0IGBidXR0b25gIGZvY3VzIHN0eWxlcy5cbi8vXG4vLyBDcmVkaXQ6IGh0dHBzOi8vZ2l0aHViLmNvbS9zdWl0Y3NzL2Jhc2UvXG5idXR0b246Zm9jdXMge1xuICBvdXRsaW5lOiAxcHggZG90dGVkO1xuICBvdXRsaW5lOiA1cHggYXV0byAtd2Via2l0LWZvY3VzLXJpbmctY29sb3I7XG59XG5cbmlucHV0LFxuYnV0dG9uLFxuc2VsZWN0LFxub3B0Z3JvdXAsXG50ZXh0YXJlYSB7XG4gIG1hcmdpbjogMDsgLy8gUmVtb3ZlIHRoZSBtYXJnaW4gaW4gRmlyZWZveCBhbmQgU2FmYXJpXG4gIGZvbnQtZmFtaWx5OiBpbmhlcml0O1xuICBmb250LXNpemU6IGluaGVyaXQ7XG4gIGxpbmUtaGVpZ2h0OiBpbmhlcml0O1xufVxuXG5idXR0b24sXG5pbnB1dCB7XG4gIG92ZXJmbG93OiB2aXNpYmxlOyAvLyBTaG93IHRoZSBvdmVyZmxvdyBpbiBFZGdlXG59XG5cbmJ1dHRvbixcbnNlbGVjdCB7XG4gIHRleHQtdHJhbnNmb3JtOiBub25lOyAvLyBSZW1vdmUgdGhlIGluaGVyaXRhbmNlIG9mIHRleHQgdHJhbnNmb3JtIGluIEZpcmVmb3hcbn1cblxuLy8gMS4gUHJldmVudCBhIFdlYktpdCBidWcgd2hlcmUgKDIpIGRlc3Ryb3lzIG5hdGl2ZSBgYXVkaW9gIGFuZCBgdmlkZW9gXG4vLyAgICBjb250cm9scyBpbiBBbmRyb2lkIDQuXG4vLyAyLiBDb3JyZWN0IHRoZSBpbmFiaWxpdHkgdG8gc3R5bGUgY2xpY2thYmxlIHR5cGVzIGluIGlPUyBhbmQgU2FmYXJpLlxuYnV0dG9uLFxuaHRtbCBbdHlwZT1cImJ1dHRvblwiXSwgLy8gMVxuW3R5cGU9XCJyZXNldFwiXSxcblt0eXBlPVwic3VibWl0XCJdIHtcbiAgLXdlYmtpdC1hcHBlYXJhbmNlOiBidXR0b247IC8vIDJcbn1cblxuLy8gUmVtb3ZlIGlubmVyIGJvcmRlciBhbmQgcGFkZGluZyBmcm9tIEZpcmVmb3gsIGJ1dCBkb24ndCByZXN0b3JlIHRoZSBvdXRsaW5lIGxpa2UgTm9ybWFsaXplLlxuYnV0dG9uOjotbW96LWZvY3VzLWlubmVyLFxuW3R5cGU9XCJidXR0b25cIl06Oi1tb3otZm9jdXMtaW5uZXIsXG5bdHlwZT1cInJlc2V0XCJdOjotbW96LWZvY3VzLWlubmVyLFxuW3R5cGU9XCJzdWJtaXRcIl06Oi1tb3otZm9jdXMtaW5uZXIge1xuICBwYWRkaW5nOiAwO1xuICBib3JkZXItc3R5bGU6IG5vbmU7XG59XG5cbmlucHV0W3R5cGU9XCJyYWRpb1wiXSxcbmlucHV0W3R5cGU9XCJjaGVja2JveFwiXSB7XG4gIGJveC1zaXppbmc6IGJvcmRlci1ib3g7IC8vIDEuIEFkZCB0aGUgY29ycmVjdCBib3ggc2l6aW5nIGluIElFIDEwLVxuICBwYWRkaW5nOiAwOyAvLyAyLiBSZW1vdmUgdGhlIHBhZGRpbmcgaW4gSUUgMTAtXG59XG5cblxuaW5wdXRbdHlwZT1cImRhdGVcIl0sXG5pbnB1dFt0eXBlPVwidGltZVwiXSxcbmlucHV0W3R5cGU9XCJkYXRldGltZS1sb2NhbFwiXSxcbmlucHV0W3R5cGU9XCJtb250aFwiXSB7XG4gIC8vIFJlbW92ZSB0aGUgZGVmYXVsdCBhcHBlYXJhbmNlIG9mIHRlbXBvcmFsIGlucHV0cyB0byBhdm9pZCBhIE1vYmlsZSBTYWZhcmlcbiAgLy8gYnVnIHdoZXJlIHNldHRpbmcgYSBjdXN0b20gbGluZS1oZWlnaHQgcHJldmVudHMgdGV4dCBmcm9tIGJlaW5nIHZlcnRpY2FsbHlcbiAgLy8gY2VudGVyZWQgd2l0aGluIHRoZSBpbnB1dC5cbiAgLy8gU2VlIGh0dHBzOi8vYnVncy53ZWJraXQub3JnL3Nob3dfYnVnLmNnaT9pZD0xMzk4NDhcbiAgLy8gYW5kIGh0dHBzOi8vZ2l0aHViLmNvbS90d2JzL2Jvb3RzdHJhcC9pc3N1ZXMvMTEyNjZcbiAgLXdlYmtpdC1hcHBlYXJhbmNlOiBsaXN0Ym94O1xufVxuXG50ZXh0YXJlYSB7XG4gIG92ZXJmbG93OiBhdXRvOyAvLyBSZW1vdmUgdGhlIGRlZmF1bHQgdmVydGljYWwgc2Nyb2xsYmFyIGluIElFLlxuICAvLyBUZXh0YXJlYXMgc2hvdWxkIHJlYWxseSBvbmx5IHJlc2l6ZSB2ZXJ0aWNhbGx5IHNvIHRoZXkgZG9uJ3QgYnJlYWsgdGhlaXIgKGhvcml6b250YWwpIGNvbnRhaW5lcnMuXG4gIHJlc2l6ZTogdmVydGljYWw7XG59XG5cbmZpZWxkc2V0IHtcbiAgLy8gQnJvd3NlcnMgc2V0IGEgZGVmYXVsdCBgbWluLXdpZHRoOiBtaW4tY29udGVudDtgIG9uIGZpZWxkc2V0cyxcbiAgLy8gdW5saWtlIGUuZy4gYDxkaXY+YHMsIHdoaWNoIGhhdmUgYG1pbi13aWR0aDogMDtgIGJ5IGRlZmF1bHQuXG4gIC8vIFNvIHdlIHJlc2V0IHRoYXQgdG8gZW5zdXJlIGZpZWxkc2V0cyBiZWhhdmUgbW9yZSBsaWtlIGEgc3RhbmRhcmQgYmxvY2sgZWxlbWVudC5cbiAgLy8gU2VlIGh0dHBzOi8vZ2l0aHViLmNvbS90d2JzL2Jvb3RzdHJhcC9pc3N1ZXMvMTIzNTlcbiAgLy8gYW5kIGh0dHBzOi8vaHRtbC5zcGVjLndoYXR3Zy5vcmcvbXVsdGlwYWdlLyN0aGUtZmllbGRzZXQtYW5kLWxlZ2VuZC1lbGVtZW50c1xuICBtaW4td2lkdGg6IDA7XG4gIC8vIFJlc2V0IHRoZSBkZWZhdWx0IG91dGxpbmUgYmVoYXZpb3Igb2YgZmllbGRzZXRzIHNvIHRoZXkgZG9uJ3QgYWZmZWN0IHBhZ2UgbGF5b3V0LlxuICBwYWRkaW5nOiAwO1xuICBtYXJnaW46IDA7XG4gIGJvcmRlcjogMDtcbn1cblxuLy8gMS4gQ29ycmVjdCB0aGUgdGV4dCB3cmFwcGluZyBpbiBFZGdlIGFuZCBJRS5cbi8vIDIuIENvcnJlY3QgdGhlIGNvbG9yIGluaGVyaXRhbmNlIGZyb20gYGZpZWxkc2V0YCBlbGVtZW50cyBpbiBJRS5cbmxlZ2VuZCB7XG4gIGRpc3BsYXk6IGJsb2NrO1xuICB3aWR0aDogMTAwJTtcbiAgbWF4LXdpZHRoOiAxMDAlOyAvLyAxXG4gIHBhZGRpbmc6IDA7XG4gIG1hcmdpbi1ib3R0b206IC41cmVtO1xuICBmb250LXNpemU6IDEuNXJlbTtcbiAgbGluZS1oZWlnaHQ6IGluaGVyaXQ7XG4gIGNvbG9yOiBpbmhlcml0OyAvLyAyXG4gIHdoaXRlLXNwYWNlOiBub3JtYWw7IC8vIDFcbn1cblxucHJvZ3Jlc3Mge1xuICB2ZXJ0aWNhbC1hbGlnbjogYmFzZWxpbmU7IC8vIEFkZCB0aGUgY29ycmVjdCB2ZXJ0aWNhbCBhbGlnbm1lbnQgaW4gQ2hyb21lLCBGaXJlZm94LCBhbmQgT3BlcmEuXG59XG5cbi8vIENvcnJlY3QgdGhlIGN1cnNvciBzdHlsZSBvZiBpbmNyZW1lbnQgYW5kIGRlY3JlbWVudCBidXR0b25zIGluIENocm9tZS5cblt0eXBlPVwibnVtYmVyXCJdOjotd2Via2l0LWlubmVyLXNwaW4tYnV0dG9uLFxuW3R5cGU9XCJudW1iZXJcIl06Oi13ZWJraXQtb3V0ZXItc3Bpbi1idXR0b24ge1xuICBoZWlnaHQ6IGF1dG87XG59XG5cblt0eXBlPVwic2VhcmNoXCJdIHtcbiAgLy8gVGhpcyBvdmVycmlkZXMgdGhlIGV4dHJhIHJvdW5kZWQgY29ybmVycyBvbiBzZWFyY2ggaW5wdXRzIGluIGlPUyBzbyB0aGF0IG91clxuICAvLyBgLmZvcm0tY29udHJvbGAgY2xhc3MgY2FuIHByb3Blcmx5IHN0eWxlIHRoZW0uIE5vdGUgdGhhdCB0aGlzIGNhbm5vdCBzaW1wbHlcbiAgLy8gYmUgYWRkZWQgdG8gYC5mb3JtLWNvbnRyb2xgIGFzIGl0J3Mgbm90IHNwZWNpZmljIGVub3VnaC4gRm9yIGRldGFpbHMsIHNlZVxuICAvLyBodHRwczovL2dpdGh1Yi5jb20vdHdicy9ib290c3RyYXAvaXNzdWVzLzExNTg2LlxuICBvdXRsaW5lLW9mZnNldDogLTJweDsgLy8gMi4gQ29ycmVjdCB0aGUgb3V0bGluZSBzdHlsZSBpbiBTYWZhcmkuXG4gIC13ZWJraXQtYXBwZWFyYW5jZTogbm9uZTtcbn1cblxuLy9cbi8vIFJlbW92ZSB0aGUgaW5uZXIgcGFkZGluZyBhbmQgY2FuY2VsIGJ1dHRvbnMgaW4gQ2hyb21lIGFuZCBTYWZhcmkgb24gbWFjT1MuXG4vL1xuXG5bdHlwZT1cInNlYXJjaFwiXTo6LXdlYmtpdC1zZWFyY2gtY2FuY2VsLWJ1dHRvbixcblt0eXBlPVwic2VhcmNoXCJdOjotd2Via2l0LXNlYXJjaC1kZWNvcmF0aW9uIHtcbiAgLXdlYmtpdC1hcHBlYXJhbmNlOiBub25lO1xufVxuXG4vL1xuLy8gMS4gQ29ycmVjdCB0aGUgaW5hYmlsaXR5IHRvIHN0eWxlIGNsaWNrYWJsZSB0eXBlcyBpbiBpT1MgYW5kIFNhZmFyaS5cbi8vIDIuIENoYW5nZSBmb250IHByb3BlcnRpZXMgdG8gYGluaGVyaXRgIGluIFNhZmFyaS5cbi8vXG5cbjo6LXdlYmtpdC1maWxlLXVwbG9hZC1idXR0b24ge1xuICBmb250OiBpbmhlcml0OyAvLyAyXG4gIC13ZWJraXQtYXBwZWFyYW5jZTogYnV0dG9uOyAvLyAxXG59XG5cbi8vXG4vLyBDb3JyZWN0IGVsZW1lbnQgZGlzcGxheXNcbi8vXG5cbm91dHB1dCB7XG4gIGRpc3BsYXk6IGlubGluZS1ibG9jaztcbn1cblxuc3VtbWFyeSB7XG4gIGRpc3BsYXk6IGxpc3QtaXRlbTsgLy8gQWRkIHRoZSBjb3JyZWN0IGRpc3BsYXkgaW4gYWxsIGJyb3dzZXJzXG59XG5cbnRlbXBsYXRlIHtcbiAgZGlzcGxheTogbm9uZTsgLy8gQWRkIHRoZSBjb3JyZWN0IGRpc3BsYXkgaW4gSUVcbn1cblxuLy8gQWx3YXlzIGhpZGUgYW4gZWxlbWVudCB3aXRoIHRoZSBgaGlkZGVuYCBIVE1MIGF0dHJpYnV0ZSAoZnJvbSBQdXJlQ1NTKS5cbi8vIE5lZWRlZCBmb3IgcHJvcGVyIGRpc3BsYXkgaW4gSUUgMTAtLlxuW2hpZGRlbl0ge1xuICBkaXNwbGF5OiBub25lICFpbXBvcnRhbnQ7XG59XG4iLCIvLyBWYXJpYWJsZXNcbi8vXG4vLyBDb3B5IHNldHRpbmdzIGZyb20gdGhpcyBmaWxlIGludG8gdGhlIHByb3ZpZGVkIGBfY3VzdG9tLnNjc3NgIHRvIG92ZXJyaWRlXG4vLyB0aGUgQm9vdHN0cmFwIGRlZmF1bHRzIHdpdGhvdXQgbW9kaWZ5aW5nIGtleSwgdmVyc2lvbmVkIGZpbGVzLlxuLy9cbi8vIFZhcmlhYmxlcyBzaG91bGQgZm9sbG93IHRoZSBgJGNvbXBvbmVudC1zdGF0ZS1wcm9wZXJ0eS1zaXplYCBmb3JtdWxhIGZvclxuLy8gY29uc2lzdGVudCBuYW1pbmcuIEV4OiAkbmF2LWxpbmstZGlzYWJsZWQtY29sb3IgYW5kICRtb2RhbC1jb250ZW50LWJveC1zaGFkb3cteHMuXG5cbi8vIFRhYmxlIG9mIENvbnRlbnRzXG4vL1xuLy8gQ29sb3Igc3lzdGVtXG4vLyBPcHRpb25zXG4vLyBTcGFjaW5nXG4vLyBCb2R5XG4vLyBMaW5rc1xuLy8gUGFyYWdyYXBoc1xuLy8gR3JpZCBicmVha3BvaW50c1xuLy8gR3JpZCBjb250YWluZXJzXG4vLyBHcmlkIGNvbHVtbnNcbi8vIEZvbnRzXG4vLyBDb21wb25lbnRzXG4vLyBUYWJsZXNcbi8vIEJ1dHRvbnNcbi8vIEZvcm1zXG4vLyBEcm9wZG93bnNcbi8vIFotaW5kZXggbWFzdGVyIGxpc3Rcbi8vIE5hdnNcbi8vIE5hdmJhclxuLy8gUGFnaW5hdGlvblxuLy8gSnVtYm90cm9uXG4vLyBGb3JtIHN0YXRlcyBhbmQgYWxlcnRzXG4vLyBDYXJkc1xuLy8gVG9vbHRpcHNcbi8vIFBvcG92ZXJzXG4vLyBCYWRnZXNcbi8vIE1vZGFsc1xuLy8gQWxlcnRzXG4vLyBQcm9ncmVzcyBiYXJzXG4vLyBMaXN0IGdyb3VwXG4vLyBJbWFnZSB0aHVtYm5haWxzXG4vLyBGaWd1cmVzXG4vLyBCcmVhZGNydW1ic1xuLy8gQ2Fyb3VzZWxcbi8vIENsb3NlXG4vLyBDb2RlXG5cblxuLy9cbi8vIENvbG9yIHN5c3RlbVxuLy9cblxuJHdoaXRlOiAgI2ZmZiAhZGVmYXVsdDtcbiRncmF5LTEwMDogI2Y4ZjlmYSAhZGVmYXVsdDtcbiRncmF5LTIwMDogI2U5ZWNlZiAhZGVmYXVsdDtcbiRncmF5LTMwMDogI2RlZTJlNiAhZGVmYXVsdDtcbiRncmF5LTQwMDogI2NlZDRkYSAhZGVmYXVsdDtcbiRncmF5LTUwMDogI2FkYjViZCAhZGVmYXVsdDtcbiRncmF5LTYwMDogIzg2OGU5NiAhZGVmYXVsdDtcbiRncmF5LTcwMDogIzQ5NTA1NyAhZGVmYXVsdDtcbiRncmF5LTgwMDogIzM0M2E0MCAhZGVmYXVsdDtcbiRncmF5LTkwMDogIzIxMjUyOSAhZGVmYXVsdDtcbiRibGFjazogICMwMDAgIWRlZmF1bHQ7XG5cbiRncmF5czogKFxuICAxMDA6ICRncmF5LTEwMCxcbiAgMjAwOiAkZ3JheS0yMDAsXG4gIDMwMDogJGdyYXktMzAwLFxuICA0MDA6ICRncmF5LTQwMCxcbiAgNTAwOiAkZ3JheS01MDAsXG4gIDYwMDogJGdyYXktNjAwLFxuICA3MDA6ICRncmF5LTcwMCxcbiAgODAwOiAkZ3JheS04MDAsXG4gIDkwMDogJGdyYXktOTAwXG4pICFkZWZhdWx0O1xuXG4kYmx1ZTogICAgIzAwN2JmZiAhZGVmYXVsdDtcbiRpbmRpZ286ICAjNjYxMGYyICFkZWZhdWx0O1xuJHB1cnBsZTogICM2ZjQyYzEgIWRlZmF1bHQ7XG4kcGluazogICAgI2U4M2U4YyAhZGVmYXVsdDtcbiRyZWQ6ICAgICAjZGMzNTQ1ICFkZWZhdWx0O1xuJG9yYW5nZTogICNmZDdlMTQgIWRlZmF1bHQ7XG4keWVsbG93OiAgI2ZmYzEwNyAhZGVmYXVsdDtcbiRncmVlbjogICAjMjhhNzQ1ICFkZWZhdWx0O1xuJHRlYWw6ICAgICMyMGM5OTcgIWRlZmF1bHQ7XG4kY3lhbjogICAgIzE3YTJiOCAhZGVmYXVsdDtcblxuJGNvbG9yczogKFxuICBibHVlOiAkYmx1ZSxcbiAgaW5kaWdvOiAkaW5kaWdvLFxuICBwdXJwbGU6ICRwdXJwbGUsXG4gIHBpbms6ICRwaW5rLFxuICByZWQ6ICRyZWQsXG4gIG9yYW5nZTogJG9yYW5nZSxcbiAgeWVsbG93OiAkeWVsbG93LFxuICBncmVlbjogJGdyZWVuLFxuICB0ZWFsOiAkdGVhbCxcbiAgY3lhbjogJGN5YW4sXG4gIHdoaXRlOiAkd2hpdGUsXG4gIGdyYXk6ICRncmF5LTYwMCxcbiAgZ3JheS1kYXJrOiAkZ3JheS04MDBcbikgIWRlZmF1bHQ7XG5cbiR0aGVtZS1jb2xvcnM6IChcbiAgcHJpbWFyeTogJGJsdWUsXG4gIHNlY29uZGFyeTogJGdyYXktNjAwLFxuICBzdWNjZXNzOiAkZ3JlZW4sXG4gIGluZm86ICRjeWFuLFxuICB3YXJuaW5nOiAkeWVsbG93LFxuICBkYW5nZXI6ICRyZWQsXG4gIGxpZ2h0OiAkZ3JheS0xMDAsXG4gIGRhcms6ICRncmF5LTgwMFxuKSAhZGVmYXVsdDtcblxuLy8gU2V0IGEgc3BlY2lmaWMganVtcCBwb2ludCBmb3IgcmVxdWVzdGluZyBjb2xvciBqdW1wc1xuJHRoZW1lLWNvbG9yLWludGVydmFsOiA4JSAhZGVmYXVsdDtcblxuXG4vLyBPcHRpb25zXG4vL1xuLy8gUXVpY2tseSBtb2RpZnkgZ2xvYmFsIHN0eWxpbmcgYnkgZW5hYmxpbmcgb3IgZGlzYWJsaW5nIG9wdGlvbmFsIGZlYXR1cmVzLlxuXG4kZW5hYmxlLXJvdW5kZWQ6ICAgICAgICAgICAgdHJ1ZSAhZGVmYXVsdDtcbiRlbmFibGUtc2hhZG93czogICAgICAgICAgICBmYWxzZSAhZGVmYXVsdDtcbiRlbmFibGUtZ3JhZGllbnRzOiAgICAgICAgICBmYWxzZSAhZGVmYXVsdDtcbiRlbmFibGUtdHJhbnNpdGlvbnM6ICAgICAgICB0cnVlICFkZWZhdWx0O1xuJGVuYWJsZS1ob3Zlci1tZWRpYS1xdWVyeTogIGZhbHNlICFkZWZhdWx0O1xuJGVuYWJsZS1ncmlkLWNsYXNzZXM6ICAgICAgIHRydWUgIWRlZmF1bHQ7XG4kZW5hYmxlLXByaW50LXN0eWxlczogICAgICAgdHJ1ZSAhZGVmYXVsdDtcblxuXG4vLyBTcGFjaW5nXG4vL1xuLy8gQ29udHJvbCB0aGUgZGVmYXVsdCBzdHlsaW5nIG9mIG1vc3QgQm9vdHN0cmFwIGVsZW1lbnRzIGJ5IG1vZGlmeWluZyB0aGVzZVxuLy8gdmFyaWFibGVzLiBNb3N0bHkgZm9jdXNlZCBvbiBzcGFjaW5nLlxuLy8gWW91IGNhbiBhZGQgbW9yZSBlbnRyaWVzIHRvIHRoZSAkc3BhY2VycyBtYXAsIHNob3VsZCB5b3UgbmVlZCBtb3JlIHZhcmlhdGlvbi5cblxuJHNwYWNlcjogMXJlbSAhZGVmYXVsdDtcbiRzcGFjZXJzOiAoXG4gIDA6IDAsXG4gIDE6ICgkc3BhY2VyICogLjI1KSxcbiAgMjogKCRzcGFjZXIgKiAuNSksXG4gIDM6ICRzcGFjZXIsXG4gIDQ6ICgkc3BhY2VyICogMS41KSxcbiAgNTogKCRzcGFjZXIgKiAzKVxuKSAhZGVmYXVsdDtcblxuLy8gVGhpcyB2YXJpYWJsZSBhZmZlY3RzIHRoZSBgLmgtKmAgYW5kIGAudy0qYCBjbGFzc2VzLlxuJHNpemVzOiAoXG4gIDI1OiAyNSUsXG4gIDUwOiA1MCUsXG4gIDc1OiA3NSUsXG4gIDEwMDogMTAwJVxuKSAhZGVmYXVsdDtcblxuLy8gQm9keVxuLy9cbi8vIFNldHRpbmdzIGZvciB0aGUgYDxib2R5PmAgZWxlbWVudC5cblxuJGJvZHktYmc6ICAgICAgICR3aGl0ZSAhZGVmYXVsdDtcbiRib2R5LWNvbG9yOiAgICAkZ3JheS05MDAgIWRlZmF1bHQ7XG5cbi8vIExpbmtzXG4vL1xuLy8gU3R5bGUgYW5jaG9yIGVsZW1lbnRzLlxuXG4kbGluay1jb2xvcjogICAgICAgICAgICB0aGVtZS1jb2xvcihcInByaW1hcnlcIikgIWRlZmF1bHQ7XG4kbGluay1kZWNvcmF0aW9uOiAgICAgICBub25lICFkZWZhdWx0O1xuJGxpbmstaG92ZXItY29sb3I6ICAgICAgZGFya2VuKCRsaW5rLWNvbG9yLCAxNSUpICFkZWZhdWx0O1xuJGxpbmstaG92ZXItZGVjb3JhdGlvbjogdW5kZXJsaW5lICFkZWZhdWx0O1xuXG4vLyBQYXJhZ3JhcGhzXG4vL1xuLy8gU3R5bGUgcCBlbGVtZW50LlxuXG4kcGFyYWdyYXBoLW1hcmdpbi1ib3R0b206IDFyZW07XG5cblxuLy8gR3JpZCBicmVha3BvaW50c1xuLy9cbi8vIERlZmluZSB0aGUgbWluaW11bSBkaW1lbnNpb25zIGF0IHdoaWNoIHlvdXIgbGF5b3V0IHdpbGwgY2hhbmdlLFxuLy8gYWRhcHRpbmcgdG8gZGlmZmVyZW50IHNjcmVlbiBzaXplcywgZm9yIHVzZSBpbiBtZWRpYSBxdWVyaWVzLlxuXG4kZ3JpZC1icmVha3BvaW50czogKFxuICB4czogMCxcbiAgc206IDU3NnB4LFxuICBtZDogNzY4cHgsXG4gIGxnOiA5OTJweCxcbiAgeGw6IDEyMDBweFxuKSAhZGVmYXVsdDtcbkBpbmNsdWRlIF9hc3NlcnQtYXNjZW5kaW5nKCRncmlkLWJyZWFrcG9pbnRzLCBcIiRncmlkLWJyZWFrcG9pbnRzXCIpO1xuQGluY2x1ZGUgX2Fzc2VydC1zdGFydHMtYXQtemVybygkZ3JpZC1icmVha3BvaW50cyk7XG5cblxuLy8gR3JpZCBjb250YWluZXJzXG4vL1xuLy8gRGVmaW5lIHRoZSBtYXhpbXVtIHdpZHRoIG9mIGAuY29udGFpbmVyYCBmb3IgZGlmZmVyZW50IHNjcmVlbiBzaXplcy5cblxuJGNvbnRhaW5lci1tYXgtd2lkdGhzOiAoXG4gIHNtOiA1NDBweCxcbiAgbWQ6IDcyMHB4LFxuICBsZzogOTYwcHgsXG4gIHhsOiAxMTQwcHhcbikgIWRlZmF1bHQ7XG5AaW5jbHVkZSBfYXNzZXJ0LWFzY2VuZGluZygkY29udGFpbmVyLW1heC13aWR0aHMsIFwiJGNvbnRhaW5lci1tYXgtd2lkdGhzXCIpO1xuXG5cbi8vIEdyaWQgY29sdW1uc1xuLy9cbi8vIFNldCB0aGUgbnVtYmVyIG9mIGNvbHVtbnMgYW5kIHNwZWNpZnkgdGhlIHdpZHRoIG9mIHRoZSBndXR0ZXJzLlxuXG4kZ3JpZC1jb2x1bW5zOiAxMiAhZGVmYXVsdDtcbiRncmlkLWd1dHRlci13aWR0aDogMzBweCAhZGVmYXVsdDtcblxuLy8gQ29tcG9uZW50c1xuLy9cbi8vIERlZmluZSBjb21tb24gcGFkZGluZyBhbmQgYm9yZGVyIHJhZGl1cyBzaXplcyBhbmQgbW9yZS5cblxuJGxpbmUtaGVpZ2h0LWxnOiAgICAgICAgIDEuNSAhZGVmYXVsdDtcbiRsaW5lLWhlaWdodC1zbTogICAgICAgICAxLjUgIWRlZmF1bHQ7XG5cbiRib3JkZXItd2lkdGg6IDFweCAhZGVmYXVsdDtcbiRib3JkZXItY29sb3I6ICRncmF5LTIwMCAhZGVmYXVsdDtcblxuJGJvcmRlci1yYWRpdXM6ICAgICAgICAgIC4yNXJlbSAhZGVmYXVsdDtcbiRib3JkZXItcmFkaXVzLWxnOiAgICAgICAuM3JlbSAhZGVmYXVsdDtcbiRib3JkZXItcmFkaXVzLXNtOiAgICAgICAuMnJlbSAhZGVmYXVsdDtcblxuJGNvbXBvbmVudC1hY3RpdmUtY29sb3I6ICR3aGl0ZSAhZGVmYXVsdDtcbiRjb21wb25lbnQtYWN0aXZlLWJnOiAgICB0aGVtZS1jb2xvcihcInByaW1hcnlcIikgIWRlZmF1bHQ7XG5cbiRjYXJldC13aWR0aDogICAgICAgICAgICAuM2VtICFkZWZhdWx0O1xuXG4kdHJhbnNpdGlvbi1iYXNlOiAgICAgICAgYWxsIC4ycyBlYXNlLWluLW91dCAhZGVmYXVsdDtcbiR0cmFuc2l0aW9uLWZhZGU6ICAgICAgICBvcGFjaXR5IC4xNXMgbGluZWFyICFkZWZhdWx0O1xuJHRyYW5zaXRpb24tY29sbGFwc2U6ICAgIGhlaWdodCAuMzVzIGVhc2UgIWRlZmF1bHQ7XG5cblxuLy8gRm9udHNcbi8vXG4vLyBGb250LCBsaW5lLWhlaWdodCwgYW5kIGNvbG9yIGZvciBib2R5IHRleHQsIGhlYWRpbmdzLCBhbmQgbW9yZS5cblxuJGZvbnQtZmFtaWx5LXNhbnMtc2VyaWY6IC1hcHBsZS1zeXN0ZW0sIEJsaW5rTWFjU3lzdGVtRm9udCwgXCJTZWdvZSBVSVwiLCBSb2JvdG8sIFwiSGVsdmV0aWNhIE5ldWVcIiwgQXJpYWwsIHNhbnMtc2VyaWYsIFwiQXBwbGUgQ29sb3IgRW1vamlcIiwgXCJTZWdvZSBVSSBFbW9qaVwiLCBcIlNlZ29lIFVJIFN5bWJvbFwiICFkZWZhdWx0O1xuJGZvbnQtZmFtaWx5LW1vbm9zcGFjZTogIFwiU0ZNb25vLVJlZ3VsYXJcIiwgTWVubG8sIE1vbmFjbywgQ29uc29sYXMsIFwiTGliZXJhdGlvbiBNb25vXCIsIFwiQ291cmllciBOZXdcIiwgbW9ub3NwYWNlICFkZWZhdWx0O1xuJGZvbnQtZmFtaWx5LWJhc2U6ICAgICAgICRmb250LWZhbWlseS1zYW5zLXNlcmlmICFkZWZhdWx0O1xuXG4kZm9udC1zaXplLWJhc2U6IDFyZW0gIWRlZmF1bHQ7IC8vIEFzc3VtZXMgdGhlIGJyb3dzZXIgZGVmYXVsdCwgdHlwaWNhbGx5IGAxNnB4YFxuJGZvbnQtc2l6ZS1sZzogICAxLjI1cmVtICFkZWZhdWx0O1xuJGZvbnQtc2l6ZS1zbTogICAuODc1cmVtICFkZWZhdWx0O1xuXG4kZm9udC13ZWlnaHQtbGlnaHQ6IDMwMCAhZGVmYXVsdDtcbiRmb250LXdlaWdodC1ub3JtYWw6IG5vcm1hbCAhZGVmYXVsdDtcbiRmb250LXdlaWdodC1ib2xkOiBib2xkICFkZWZhdWx0O1xuXG4kZm9udC13ZWlnaHQtYmFzZTogJGZvbnQtd2VpZ2h0LW5vcm1hbCAhZGVmYXVsdDtcbiRsaW5lLWhlaWdodC1iYXNlOiAxLjUgIWRlZmF1bHQ7XG5cbiRoMS1mb250LXNpemU6IDIuNXJlbSAhZGVmYXVsdDtcbiRoMi1mb250LXNpemU6IDJyZW0gIWRlZmF1bHQ7XG4kaDMtZm9udC1zaXplOiAxLjc1cmVtICFkZWZhdWx0O1xuJGg0LWZvbnQtc2l6ZTogMS41cmVtICFkZWZhdWx0O1xuJGg1LWZvbnQtc2l6ZTogMS4yNXJlbSAhZGVmYXVsdDtcbiRoNi1mb250LXNpemU6IDFyZW0gIWRlZmF1bHQ7XG5cbiRoZWFkaW5ncy1tYXJnaW4tYm90dG9tOiAoJHNwYWNlciAvIDIpICFkZWZhdWx0O1xuJGhlYWRpbmdzLWZvbnQtZmFtaWx5OiAgIGluaGVyaXQgIWRlZmF1bHQ7XG4kaGVhZGluZ3MtZm9udC13ZWlnaHQ6ICAgNTAwICFkZWZhdWx0O1xuJGhlYWRpbmdzLWxpbmUtaGVpZ2h0OiAgIDEuMSAhZGVmYXVsdDtcbiRoZWFkaW5ncy1jb2xvcjogICAgICAgICBpbmhlcml0ICFkZWZhdWx0O1xuXG4kZGlzcGxheTEtc2l6ZTogNnJlbSAhZGVmYXVsdDtcbiRkaXNwbGF5Mi1zaXplOiA1LjVyZW0gIWRlZmF1bHQ7XG4kZGlzcGxheTMtc2l6ZTogNC41cmVtICFkZWZhdWx0O1xuJGRpc3BsYXk0LXNpemU6IDMuNXJlbSAhZGVmYXVsdDtcblxuJGRpc3BsYXkxLXdlaWdodDogICAgIDMwMCAhZGVmYXVsdDtcbiRkaXNwbGF5Mi13ZWlnaHQ6ICAgICAzMDAgIWRlZmF1bHQ7XG4kZGlzcGxheTMtd2VpZ2h0OiAgICAgMzAwICFkZWZhdWx0O1xuJGRpc3BsYXk0LXdlaWdodDogICAgIDMwMCAhZGVmYXVsdDtcbiRkaXNwbGF5LWxpbmUtaGVpZ2h0OiAkaGVhZGluZ3MtbGluZS1oZWlnaHQgIWRlZmF1bHQ7XG5cbiRsZWFkLWZvbnQtc2l6ZTogICAxLjI1cmVtICFkZWZhdWx0O1xuJGxlYWQtZm9udC13ZWlnaHQ6IDMwMCAhZGVmYXVsdDtcblxuJHNtYWxsLWZvbnQtc2l6ZTogODAlICFkZWZhdWx0O1xuXG4kdGV4dC1tdXRlZDogJGdyYXktNjAwICFkZWZhdWx0O1xuXG4kYmxvY2txdW90ZS1zbWFsbC1jb2xvcjogICRncmF5LTYwMCAhZGVmYXVsdDtcbiRibG9ja3F1b3RlLWZvbnQtc2l6ZTogICAgKCRmb250LXNpemUtYmFzZSAqIDEuMjUpICFkZWZhdWx0O1xuXG4kaHItYm9yZGVyLWNvbG9yOiByZ2JhKCRibGFjaywuMSkgIWRlZmF1bHQ7XG4kaHItYm9yZGVyLXdpZHRoOiAkYm9yZGVyLXdpZHRoICFkZWZhdWx0O1xuXG4kbWFyay1wYWRkaW5nOiAuMmVtICFkZWZhdWx0O1xuXG4kZHQtZm9udC13ZWlnaHQ6ICRmb250LXdlaWdodC1ib2xkICFkZWZhdWx0O1xuXG4ka2JkLWJveC1zaGFkb3c6ICAgICAgICAgaW5zZXQgMCAtLjFyZW0gMCByZ2JhKCRibGFjaywuMjUpICFkZWZhdWx0O1xuJG5lc3RlZC1rYmQtZm9udC13ZWlnaHQ6ICRmb250LXdlaWdodC1ib2xkICFkZWZhdWx0O1xuXG4kbGlzdC1pbmxpbmUtcGFkZGluZzogNXB4ICFkZWZhdWx0O1xuXG4kbWFyay1iZzogI2ZjZjhlMyAhZGVmYXVsdDtcblxuXG4vLyBUYWJsZXNcbi8vXG4vLyBDdXN0b21pemVzIHRoZSBgLnRhYmxlYCBjb21wb25lbnQgd2l0aCBiYXNpYyB2YWx1ZXMsIGVhY2ggdXNlZCBhY3Jvc3MgYWxsIHRhYmxlIHZhcmlhdGlvbnMuXG5cbiR0YWJsZS1jZWxsLXBhZGRpbmc6ICAgICAgICAgICAgLjc1cmVtICFkZWZhdWx0O1xuJHRhYmxlLWNlbGwtcGFkZGluZy1zbTogICAgICAgICAuM3JlbSAhZGVmYXVsdDtcblxuJHRhYmxlLWJnOiAgICAgICAgICAgICAgICAgICAgICB0cmFuc3BhcmVudCAhZGVmYXVsdDtcbiR0YWJsZS1hY2NlbnQtYmc6ICAgICAgICAgICAgICAgcmdiYSgkYmxhY2ssLjA1KSAhZGVmYXVsdDtcbiR0YWJsZS1ob3Zlci1iZzogICAgICAgICAgICAgICAgcmdiYSgkYmxhY2ssLjA3NSkgIWRlZmF1bHQ7XG4kdGFibGUtYWN0aXZlLWJnOiAgICAgICAgICAgICAgICR0YWJsZS1ob3Zlci1iZyAhZGVmYXVsdDtcblxuJHRhYmxlLWJvcmRlci13aWR0aDogICAgICAgICAgICAkYm9yZGVyLXdpZHRoICFkZWZhdWx0O1xuJHRhYmxlLWJvcmRlci1jb2xvcjogICAgICAgICAgICAkZ3JheS0yMDAgIWRlZmF1bHQ7XG5cbiR0YWJsZS1oZWFkLWJnOiAgICAgICAgICAgICAgICAgJGdyYXktMjAwICFkZWZhdWx0O1xuJHRhYmxlLWhlYWQtY29sb3I6ICAgICAgICAgICAgICAkZ3JheS03MDAgIWRlZmF1bHQ7XG5cbiR0YWJsZS1pbnZlcnNlLWJnOiAgICAgICAgICAgICAgJGdyYXktOTAwICFkZWZhdWx0O1xuJHRhYmxlLWludmVyc2UtYWNjZW50LWJnOiAgICAgICByZ2JhKCR3aGl0ZSwgLjA1KSAhZGVmYXVsdDtcbiR0YWJsZS1pbnZlcnNlLWhvdmVyLWJnOiAgICAgICAgcmdiYSgkd2hpdGUsIC4wNzUpICFkZWZhdWx0O1xuJHRhYmxlLWludmVyc2UtYm9yZGVyLWNvbG9yOiAgICBsaWdodGVuKCRncmF5LTkwMCwgNy41JSkgIWRlZmF1bHQ7XG4kdGFibGUtaW52ZXJzZS1jb2xvcjogICAgICAgICAgICRib2R5LWJnICFkZWZhdWx0O1xuXG5cbi8vIEJ1dHRvbnNcbi8vXG4vLyBGb3IgZWFjaCBvZiBCb290c3RyYXAncyBidXR0b25zLCBkZWZpbmUgdGV4dCwgYmFja2dyb3VuZCBhbmQgYm9yZGVyIGNvbG9yLlxuXG4kaW5wdXQtYnRuLXBhZGRpbmcteTogICAgICAgLjVyZW0gIWRlZmF1bHQ7XG4kaW5wdXQtYnRuLXBhZGRpbmcteDogICAgICAgLjc1cmVtICFkZWZhdWx0O1xuJGlucHV0LWJ0bi1saW5lLWhlaWdodDogICAgIDEuMjUgIWRlZmF1bHQ7XG5cbiRpbnB1dC1idG4tcGFkZGluZy15LXNtOiAgICAuMjVyZW0gIWRlZmF1bHQ7XG4kaW5wdXQtYnRuLXBhZGRpbmcteC1zbTogICAgLjVyZW0gIWRlZmF1bHQ7XG4kaW5wdXQtYnRuLWxpbmUtaGVpZ2h0LXNtOiAgMS41ICFkZWZhdWx0O1xuXG4kaW5wdXQtYnRuLXBhZGRpbmcteS1sZzogICAgLjVyZW0gIWRlZmF1bHQ7XG4kaW5wdXQtYnRuLXBhZGRpbmcteC1sZzogICAgMXJlbSAhZGVmYXVsdDtcbiRpbnB1dC1idG4tbGluZS1oZWlnaHQtbGc6ICAxLjUgIWRlZmF1bHQ7XG5cbiRidG4tZm9udC13ZWlnaHQ6ICAgICAgICAgICAgICAgICRmb250LXdlaWdodC1ub3JtYWwgIWRlZmF1bHQ7XG4kYnRuLWJveC1zaGFkb3c6ICAgICAgICAgICAgICAgICBpbnNldCAwIDFweCAwIHJnYmEoJHdoaXRlLC4xNSksIDAgMXB4IDFweCByZ2JhKCRibGFjaywuMDc1KSAhZGVmYXVsdDtcbiRidG4tZm9jdXMtYm94LXNoYWRvdzogICAgICAgICAgIDAgMCAwIDNweCByZ2JhKHRoZW1lLWNvbG9yKFwicHJpbWFyeVwiKSwgLjI1KSAhZGVmYXVsdDtcbiRidG4tYWN0aXZlLWJveC1zaGFkb3c6ICAgICAgICAgIGluc2V0IDAgM3B4IDVweCByZ2JhKCRibGFjaywuMTI1KSAhZGVmYXVsdDtcblxuJGJ0bi1saW5rLWRpc2FibGVkLWNvbG9yOiAgICAgICAgJGdyYXktNjAwICFkZWZhdWx0O1xuXG4kYnRuLWJsb2NrLXNwYWNpbmcteTogICAgICAgICAgICAuNXJlbSAhZGVmYXVsdDtcblxuLy8gQWxsb3dzIGZvciBjdXN0b21pemluZyBidXR0b24gcmFkaXVzIGluZGVwZW5kZW50bHkgZnJvbSBnbG9iYWwgYm9yZGVyIHJhZGl1c1xuJGJ0bi1ib3JkZXItcmFkaXVzOiAgICAgICAgICAgICAgJGJvcmRlci1yYWRpdXMgIWRlZmF1bHQ7XG4kYnRuLWJvcmRlci1yYWRpdXMtbGc6ICAgICAgICAgICAkYm9yZGVyLXJhZGl1cy1sZyAhZGVmYXVsdDtcbiRidG4tYm9yZGVyLXJhZGl1cy1zbTogICAgICAgICAgICRib3JkZXItcmFkaXVzLXNtICFkZWZhdWx0O1xuXG4kYnRuLXRyYW5zaXRpb246ICAgICAgICAgICAgICAgICBiYWNrZ3JvdW5kLWNvbG9yIC4xNXMgZWFzZS1pbi1vdXQsIGJvcmRlci1jb2xvciAuMTVzIGVhc2UtaW4tb3V0LCBib3gtc2hhZG93IC4xNXMgZWFzZS1pbi1vdXQgIWRlZmF1bHQ7XG5cblxuLy8gRm9ybXNcblxuJGlucHV0LWJnOiAgICAgICAgICAgICAgICAgICAgICAgJHdoaXRlICFkZWZhdWx0O1xuJGlucHV0LWRpc2FibGVkLWJnOiAgICAgICAgICAgICAgJGdyYXktMjAwICFkZWZhdWx0O1xuXG4kaW5wdXQtY29sb3I6ICAgICAgICAgICAgICAgICAgICAkZ3JheS03MDAgIWRlZmF1bHQ7XG4kaW5wdXQtYm9yZGVyLWNvbG9yOiAgICAgICAgICAgICByZ2JhKCRibGFjaywuMTUpICFkZWZhdWx0O1xuJGlucHV0LWJ0bi1ib3JkZXItd2lkdGg6ICAgICAgICAgJGJvcmRlci13aWR0aCAhZGVmYXVsdDsgLy8gRm9yIGZvcm0gY29udHJvbHMgYW5kIGJ1dHRvbnNcbiRpbnB1dC1ib3gtc2hhZG93OiAgICAgICAgICAgICAgIGluc2V0IDAgMXB4IDFweCByZ2JhKCRibGFjaywuMDc1KSAhZGVmYXVsdDtcblxuJGlucHV0LWJvcmRlci1yYWRpdXM6ICAgICAgICAgICAgJGJvcmRlci1yYWRpdXMgIWRlZmF1bHQ7XG4kaW5wdXQtYm9yZGVyLXJhZGl1cy1sZzogICAgICAgICAkYm9yZGVyLXJhZGl1cy1sZyAhZGVmYXVsdDtcbiRpbnB1dC1ib3JkZXItcmFkaXVzLXNtOiAgICAgICAgICRib3JkZXItcmFkaXVzLXNtICFkZWZhdWx0O1xuXG4kaW5wdXQtZm9jdXMtYmc6ICAgICAgICAgICAgICAgICAkaW5wdXQtYmcgIWRlZmF1bHQ7XG4kaW5wdXQtZm9jdXMtYm9yZGVyLWNvbG9yOiAgICAgICBsaWdodGVuKHRoZW1lLWNvbG9yKFwicHJpbWFyeVwiKSwgMjUlKSAhZGVmYXVsdDtcbiRpbnB1dC1mb2N1cy1ib3gtc2hhZG93OiAgICAgICAgICRpbnB1dC1ib3gtc2hhZG93LCAkYnRuLWZvY3VzLWJveC1zaGFkb3cgIWRlZmF1bHQ7XG4kaW5wdXQtZm9jdXMtY29sb3I6ICAgICAgICAgICAgICAkaW5wdXQtY29sb3IgIWRlZmF1bHQ7XG5cbiRpbnB1dC1wbGFjZWhvbGRlci1jb2xvcjogICAgICAgICRncmF5LTYwMCAhZGVmYXVsdDtcblxuJGlucHV0LWhlaWdodC1ib3JkZXI6ICAgICAgICAgICAkaW5wdXQtYnRuLWJvcmRlci13aWR0aCAqIDIgIWRlZmF1bHQ7XG5cbiRpbnB1dC1oZWlnaHQtaW5uZXI6ICAgICAgICAgICAgKCRmb250LXNpemUtYmFzZSAqICRpbnB1dC1idG4tbGluZS1oZWlnaHQpICsgKCRpbnB1dC1idG4tcGFkZGluZy15ICogMikgIWRlZmF1bHQ7XG4kaW5wdXQtaGVpZ2h0OiAgICAgICAgICAgICAgICAgIGNhbGMoI3skaW5wdXQtaGVpZ2h0LWlubmVyfSArICN7JGlucHV0LWhlaWdodC1ib3JkZXJ9KSAhZGVmYXVsdDtcblxuJGlucHV0LWhlaWdodC1pbm5lci1zbTogICAgICAgICAoJGZvbnQtc2l6ZS1zbSAqICRpbnB1dC1idG4tbGluZS1oZWlnaHQtc20pICsgKCRpbnB1dC1idG4tcGFkZGluZy15LXNtICogMikgIWRlZmF1bHQ7XG4kaW5wdXQtaGVpZ2h0LXNtOiAgICAgICAgICAgICAgIGNhbGMoI3skaW5wdXQtaGVpZ2h0LWlubmVyLXNtfSArICN7JGlucHV0LWhlaWdodC1ib3JkZXJ9KSAhZGVmYXVsdDtcblxuJGlucHV0LWhlaWdodC1pbm5lci1sZzogICAgICAgICAoJGZvbnQtc2l6ZS1sZyAqICRpbnB1dC1idG4tbGluZS1oZWlnaHQtbGcpICsgKCRpbnB1dC1idG4tcGFkZGluZy15LWxnICogMikgIWRlZmF1bHQ7XG4kaW5wdXQtaGVpZ2h0LWxnOiAgICAgICAgICAgICAgIGNhbGMoI3skaW5wdXQtaGVpZ2h0LWlubmVyLWxnfSArICN7JGlucHV0LWhlaWdodC1ib3JkZXJ9KSAhZGVmYXVsdDtcblxuJGlucHV0LXRyYW5zaXRpb246ICAgICAgICAgICAgICAgYm9yZGVyLWNvbG9yIGVhc2UtaW4tb3V0IC4xNXMsIGJveC1zaGFkb3cgZWFzZS1pbi1vdXQgLjE1cyAhZGVmYXVsdDtcblxuJGZvcm0tdGV4dC1tYXJnaW4tdG9wOiAgICAgLjI1cmVtICFkZWZhdWx0O1xuXG4kZm9ybS1jaGVjay1tYXJnaW4tYm90dG9tOiAgLjVyZW0gIWRlZmF1bHQ7XG4kZm9ybS1jaGVjay1pbnB1dC1ndXR0ZXI6ICAgMS4yNXJlbSAhZGVmYXVsdDtcbiRmb3JtLWNoZWNrLWlucHV0LW1hcmdpbi15OiAuMjVyZW0gIWRlZmF1bHQ7XG4kZm9ybS1jaGVjay1pbnB1dC1tYXJnaW4teDogLjI1cmVtICFkZWZhdWx0O1xuXG4kZm9ybS1jaGVjay1pbmxpbmUtbWFyZ2luLXg6IC43NXJlbSAhZGVmYXVsdDtcblxuJGZvcm0tZ3JvdXAtbWFyZ2luLWJvdHRvbTogICAgICAgMXJlbSAhZGVmYXVsdDtcblxuJGlucHV0LWdyb3VwLWFkZG9uLWNvbG9yOiAgICAgICAgJGlucHV0LWNvbG9yICFkZWZhdWx0O1xuJGlucHV0LWdyb3VwLWFkZG9uLWJnOiAgICAgICAgICAgJGdyYXktMjAwICFkZWZhdWx0O1xuJGlucHV0LWdyb3VwLWFkZG9uLWJvcmRlci1jb2xvcjogJGlucHV0LWJvcmRlci1jb2xvciAhZGVmYXVsdDtcbiRpbnB1dC1ncm91cC1idG4tYm9yZGVyLWNvbG9yOiAgICRpbnB1dC1ib3JkZXItY29sb3IgIWRlZmF1bHQ7XG5cbiRjdXN0b20tY29udHJvbC1ndXR0ZXI6ICAgMS41cmVtICFkZWZhdWx0O1xuJGN1c3RvbS1jb250cm9sLXNwYWNlci15OiAuMjVyZW0gIWRlZmF1bHQ7XG4kY3VzdG9tLWNvbnRyb2wtc3BhY2VyLXg6IDFyZW0gIWRlZmF1bHQ7XG5cbiRjdXN0b20tY29udHJvbC1pbmRpY2F0b3Itc2l6ZTogICAgICAgMXJlbSAhZGVmYXVsdDtcbiRjdXN0b20tY29udHJvbC1pbmRpY2F0b3ItYmc6ICAgICAgICAgI2RkZCAhZGVmYXVsdDtcbiRjdXN0b20tY29udHJvbC1pbmRpY2F0b3ItYmctc2l6ZTogICAgNTAlIDUwJSAhZGVmYXVsdDtcbiRjdXN0b20tY29udHJvbC1pbmRpY2F0b3ItYm94LXNoYWRvdzogaW5zZXQgMCAuMjVyZW0gLjI1cmVtIHJnYmEoJGJsYWNrLC4xKSAhZGVmYXVsdDtcblxuJGN1c3RvbS1jb250cm9sLWluZGljYXRvci1kaXNhYmxlZC1iZzogICAgICAgJGdyYXktMjAwICFkZWZhdWx0O1xuJGN1c3RvbS1jb250cm9sLWRlc2NyaXB0aW9uLWRpc2FibGVkLWNvbG9yOiAgJGdyYXktNjAwICFkZWZhdWx0O1xuXG4kY3VzdG9tLWNvbnRyb2wtaW5kaWNhdG9yLWNoZWNrZWQtY29sb3I6ICAgICAgJHdoaXRlICFkZWZhdWx0O1xuJGN1c3RvbS1jb250cm9sLWluZGljYXRvci1jaGVja2VkLWJnOiAgICAgICAgIHRoZW1lLWNvbG9yKFwicHJpbWFyeVwiKSAhZGVmYXVsdDtcbiRjdXN0b20tY29udHJvbC1pbmRpY2F0b3ItY2hlY2tlZC1ib3gtc2hhZG93OiBub25lICFkZWZhdWx0O1xuXG4kY3VzdG9tLWNvbnRyb2wtaW5kaWNhdG9yLWZvY3VzLWJveC1zaGFkb3c6IDAgMCAwIDFweCAkYm9keS1iZywgMCAwIDAgM3B4IHRoZW1lLWNvbG9yKFwicHJpbWFyeVwiKSAhZGVmYXVsdDtcblxuJGN1c3RvbS1jb250cm9sLWluZGljYXRvci1hY3RpdmUtY29sb3I6ICAgICAgJHdoaXRlICFkZWZhdWx0O1xuJGN1c3RvbS1jb250cm9sLWluZGljYXRvci1hY3RpdmUtYmc6ICAgICAgICAgbGlnaHRlbih0aGVtZS1jb2xvcihcInByaW1hcnlcIiksIDM1JSkgIWRlZmF1bHQ7XG4kY3VzdG9tLWNvbnRyb2wtaW5kaWNhdG9yLWFjdGl2ZS1ib3gtc2hhZG93OiBub25lICFkZWZhdWx0O1xuXG4kY3VzdG9tLWNoZWNrYm94LWluZGljYXRvci1ib3JkZXItcmFkaXVzOiAkYm9yZGVyLXJhZGl1cyAhZGVmYXVsdDtcbiRjdXN0b20tY2hlY2tib3gtaW5kaWNhdG9yLWljb24tY2hlY2tlZDogc3RyLXJlcGxhY2UodXJsKFwiZGF0YTppbWFnZS9zdmcreG1sO2NoYXJzZXQ9dXRmOCwlM0NzdmcgeG1sbnM9J2h0dHA6Ly93d3cudzMub3JnLzIwMDAvc3ZnJyB2aWV3Qm94PScwIDAgOCA4JyUzRSUzQ3BhdGggZmlsbD0nI3skY3VzdG9tLWNvbnRyb2wtaW5kaWNhdG9yLWNoZWNrZWQtY29sb3J9JyBkPSdNNi41NjQuNzVsLTMuNTkgMy42MTItMS41MzgtMS41NUwwIDQuMjYgMi45NzQgNy4yNSA4IDIuMTkzeicvJTNFJTNDL3N2ZyUzRVwiKSwgXCIjXCIsIFwiJTIzXCIpICFkZWZhdWx0O1xuXG4kY3VzdG9tLWNoZWNrYm94LWluZGljYXRvci1pbmRldGVybWluYXRlLWJnOiB0aGVtZS1jb2xvcihcInByaW1hcnlcIikgIWRlZmF1bHQ7XG4kY3VzdG9tLWNoZWNrYm94LWluZGljYXRvci1pbmRldGVybWluYXRlLWNvbG9yOiAkY3VzdG9tLWNvbnRyb2wtaW5kaWNhdG9yLWNoZWNrZWQtY29sb3IgIWRlZmF1bHQ7XG4kY3VzdG9tLWNoZWNrYm94LWluZGljYXRvci1pY29uLWluZGV0ZXJtaW5hdGU6IHN0ci1yZXBsYWNlKHVybChcImRhdGE6aW1hZ2Uvc3ZnK3htbDtjaGFyc2V0PXV0ZjgsJTNDc3ZnIHhtbG5zPSdodHRwOi8vd3d3LnczLm9yZy8yMDAwL3N2Zycgdmlld0JveD0nMCAwIDQgNCclM0UlM0NwYXRoIHN0cm9rZT0nI3skY3VzdG9tLWNoZWNrYm94LWluZGljYXRvci1pbmRldGVybWluYXRlLWNvbG9yfScgZD0nTTAgMmg0Jy8lM0UlM0Mvc3ZnJTNFXCIpLCBcIiNcIiwgXCIlMjNcIikgIWRlZmF1bHQ7XG4kY3VzdG9tLWNoZWNrYm94LWluZGljYXRvci1pbmRldGVybWluYXRlLWJveC1zaGFkb3c6IG5vbmUgIWRlZmF1bHQ7XG5cbiRjdXN0b20tcmFkaW8taW5kaWNhdG9yLWJvcmRlci1yYWRpdXM6IDUwJSAhZGVmYXVsdDtcbiRjdXN0b20tcmFkaW8taW5kaWNhdG9yLWljb24tY2hlY2tlZDogc3RyLXJlcGxhY2UodXJsKFwiZGF0YTppbWFnZS9zdmcreG1sO2NoYXJzZXQ9dXRmOCwlM0NzdmcgeG1sbnM9J2h0dHA6Ly93d3cudzMub3JnLzIwMDAvc3ZnJyB2aWV3Qm94PSctNCAtNCA4IDgnJTNFJTNDY2lyY2xlIHI9JzMnIGZpbGw9JyN7JGN1c3RvbS1jb250cm9sLWluZGljYXRvci1jaGVja2VkLWNvbG9yfScvJTNFJTNDL3N2ZyUzRVwiKSwgXCIjXCIsIFwiJTIzXCIpICFkZWZhdWx0O1xuXG4kY3VzdG9tLXNlbGVjdC1wYWRkaW5nLXk6ICAgICAgICAgIC4zNzVyZW0gIWRlZmF1bHQ7XG4kY3VzdG9tLXNlbGVjdC1wYWRkaW5nLXg6ICAgICAgICAgIC43NXJlbSAgIWRlZmF1bHQ7XG4kY3VzdG9tLXNlbGVjdC1oZWlnaHQ6ICAgICAgICAgICAgICAkaW5wdXQtaGVpZ2h0ICAhZGVmYXVsdDtcbiRjdXN0b20tc2VsZWN0LWluZGljYXRvci1wYWRkaW5nOiAgIDFyZW0gIWRlZmF1bHQ7IC8vIEV4dHJhIHBhZGRpbmcgdG8gYWNjb3VudCBmb3IgdGhlIHByZXNlbmNlIG9mIHRoZSBiYWNrZ3JvdW5kLWltYWdlIGJhc2VkIGluZGljYXRvclxuJGN1c3RvbS1zZWxlY3QtbGluZS1oZWlnaHQ6ICAgICAgICAgJGlucHV0LWJ0bi1saW5lLWhlaWdodCAhZGVmYXVsdDtcbiRjdXN0b20tc2VsZWN0LWNvbG9yOiAgICAgICAgICAgICAgICRpbnB1dC1jb2xvciAhZGVmYXVsdDtcbiRjdXN0b20tc2VsZWN0LWRpc2FibGVkLWNvbG9yOiAgICAgICRncmF5LTYwMCAhZGVmYXVsdDtcbiRjdXN0b20tc2VsZWN0LWJnOiAgICAgICAgICAgICR3aGl0ZSAhZGVmYXVsdDtcbiRjdXN0b20tc2VsZWN0LWRpc2FibGVkLWJnOiAgICRncmF5LTIwMCAhZGVmYXVsdDtcbiRjdXN0b20tc2VsZWN0LWJnLXNpemU6ICAgICAgIDhweCAxMHB4ICFkZWZhdWx0OyAvLyBJbiBwaXhlbHMgYmVjYXVzZSBpbWFnZSBkaW1lbnNpb25zXG4kY3VzdG9tLXNlbGVjdC1pbmRpY2F0b3ItY29sb3I6ICMzMzMgIWRlZmF1bHQ7XG4kY3VzdG9tLXNlbGVjdC1pbmRpY2F0b3I6ICAgICBzdHItcmVwbGFjZSh1cmwoXCJkYXRhOmltYWdlL3N2Zyt4bWw7Y2hhcnNldD11dGY4LCUzQ3N2ZyB4bWxucz0naHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmcnIHZpZXdCb3g9JzAgMCA0IDUnJTNFJTNDcGF0aCBmaWxsPScjeyRjdXN0b20tc2VsZWN0LWluZGljYXRvci1jb2xvcn0nIGQ9J00yIDBMMCAyaDR6bTAgNUwwIDNoNHonLyUzRSUzQy9zdmclM0VcIiksIFwiI1wiLCBcIiUyM1wiKSAhZGVmYXVsdDtcbiRjdXN0b20tc2VsZWN0LWJvcmRlci13aWR0aDogICRpbnB1dC1idG4tYm9yZGVyLXdpZHRoICFkZWZhdWx0O1xuJGN1c3RvbS1zZWxlY3QtYm9yZGVyLWNvbG9yOiAgJGlucHV0LWJvcmRlci1jb2xvciAhZGVmYXVsdDtcbiRjdXN0b20tc2VsZWN0LWJvcmRlci1yYWRpdXM6ICRib3JkZXItcmFkaXVzICFkZWZhdWx0O1xuXG4kY3VzdG9tLXNlbGVjdC1mb2N1cy1ib3JkZXItY29sb3I6IGxpZ2h0ZW4odGhlbWUtY29sb3IoXCJwcmltYXJ5XCIpLCAyNSUpICFkZWZhdWx0O1xuJGN1c3RvbS1zZWxlY3QtZm9jdXMtYm94LXNoYWRvdzogICBpbnNldCAwIDFweCAycHggcmdiYSgkYmxhY2ssIC4wNzUpLCAwIDAgNXB4IHJnYmEoJGN1c3RvbS1zZWxlY3QtZm9jdXMtYm9yZGVyLWNvbG9yLCAuNSkgIWRlZmF1bHQ7XG5cbiRjdXN0b20tc2VsZWN0LWZvbnQtc2l6ZS1zbTogIDc1JSAhZGVmYXVsdDtcbiRjdXN0b20tc2VsZWN0LWhlaWdodC1zbTogJGlucHV0LWhlaWdodC1zbSAhZGVmYXVsdDtcblxuJGN1c3RvbS1maWxlLWhlaWdodDogICAgICAgICAgICRpbnB1dC1oZWlnaHQgIWRlZmF1bHQ7XG4kY3VzdG9tLWZpbGUtd2lkdGg6ICAgICAgICAgICAgMTRyZW0gIWRlZmF1bHQ7XG4kY3VzdG9tLWZpbGUtZm9jdXMtYm94LXNoYWRvdzogMCAwIDAgLjA3NXJlbSAkd2hpdGUsIDAgMCAwIC4ycmVtIHRoZW1lLWNvbG9yKFwicHJpbWFyeVwiKSAhZGVmYXVsdDtcblxuJGN1c3RvbS1maWxlLXBhZGRpbmcteTogICAgICRpbnB1dC1idG4tcGFkZGluZy15ICFkZWZhdWx0O1xuJGN1c3RvbS1maWxlLXBhZGRpbmcteDogICAgICRpbnB1dC1idG4tcGFkZGluZy14ICFkZWZhdWx0O1xuJGN1c3RvbS1maWxlLWxpbmUtaGVpZ2h0OiAgICRpbnB1dC1idG4tbGluZS1oZWlnaHQgIWRlZmF1bHQ7XG4kY3VzdG9tLWZpbGUtY29sb3I6ICAgICAgICAgJGlucHV0LWNvbG9yICFkZWZhdWx0O1xuJGN1c3RvbS1maWxlLWJnOiAgICAgICAgICAgICRpbnB1dC1iZyAhZGVmYXVsdDtcbiRjdXN0b20tZmlsZS1ib3JkZXItd2lkdGg6ICAkaW5wdXQtYnRuLWJvcmRlci13aWR0aCAhZGVmYXVsdDtcbiRjdXN0b20tZmlsZS1ib3JkZXItY29sb3I6ICAkaW5wdXQtYm9yZGVyLWNvbG9yICFkZWZhdWx0O1xuJGN1c3RvbS1maWxlLWJvcmRlci1yYWRpdXM6ICRpbnB1dC1ib3JkZXItcmFkaXVzICFkZWZhdWx0O1xuJGN1c3RvbS1maWxlLWJveC1zaGFkb3c6ICAgICRpbnB1dC1ib3gtc2hhZG93ICFkZWZhdWx0O1xuJGN1c3RvbS1maWxlLWJ1dHRvbi1jb2xvcjogICRjdXN0b20tZmlsZS1jb2xvciAhZGVmYXVsdDtcbiRjdXN0b20tZmlsZS1idXR0b24tYmc6ICAgICAkaW5wdXQtZ3JvdXAtYWRkb24tYmcgIWRlZmF1bHQ7XG4kY3VzdG9tLWZpbGUtdGV4dDogKFxuICBwbGFjZWhvbGRlcjogKFxuICAgIGVuOiBcIkNob29zZSBmaWxlLi4uXCJcbiAgKSxcbiAgYnV0dG9uLWxhYmVsOiAoXG4gICAgZW46IFwiQnJvd3NlXCJcbiAgKVxuKSAhZGVmYXVsdDtcblxuXG4vLyBGb3JtIHZhbGlkYXRpb25cbiRmb3JtLWZlZWRiYWNrLXZhbGlkLWNvbG9yOiAgIHRoZW1lLWNvbG9yKFwic3VjY2Vzc1wiKSAhZGVmYXVsdDtcbiRmb3JtLWZlZWRiYWNrLWludmFsaWQtY29sb3I6IHRoZW1lLWNvbG9yKFwiZGFuZ2VyXCIpICFkZWZhdWx0O1xuXG5cbi8vIERyb3Bkb3duc1xuLy9cbi8vIERyb3Bkb3duIG1lbnUgY29udGFpbmVyIGFuZCBjb250ZW50cy5cblxuJGRyb3Bkb3duLW1pbi13aWR0aDogICAgICAgICAgICAgMTByZW0gIWRlZmF1bHQ7XG4kZHJvcGRvd24tcGFkZGluZy15OiAgICAgICAgICAgICAuNXJlbSAhZGVmYXVsdDtcbiRkcm9wZG93bi1zcGFjZXI6ICAgICAgICAgICAgICAgIC4xMjVyZW0gIWRlZmF1bHQ7XG4kZHJvcGRvd24tYmc6ICAgICAgICAgICAgICAgICAgICAkd2hpdGUgIWRlZmF1bHQ7XG4kZHJvcGRvd24tYm9yZGVyLWNvbG9yOiAgICAgICAgICByZ2JhKCRibGFjaywuMTUpICFkZWZhdWx0O1xuJGRyb3Bkb3duLWJvcmRlci13aWR0aDogICAgICAgICAgJGJvcmRlci13aWR0aCAhZGVmYXVsdDtcbiRkcm9wZG93bi1kaXZpZGVyLWJnOiAgICAgICAgICAgICRncmF5LTIwMCAhZGVmYXVsdDtcbiRkcm9wZG93bi1ib3gtc2hhZG93OiAgICAgICAgICAgIDAgLjVyZW0gMXJlbSByZ2JhKCRibGFjaywuMTc1KSAhZGVmYXVsdDtcblxuJGRyb3Bkb3duLWxpbmstY29sb3I6ICAgICAgICAgICAgJGdyYXktOTAwICFkZWZhdWx0O1xuJGRyb3Bkb3duLWxpbmstaG92ZXItY29sb3I6ICAgICAgZGFya2VuKCRncmF5LTkwMCwgNSUpICFkZWZhdWx0O1xuJGRyb3Bkb3duLWxpbmstaG92ZXItYmc6ICAgICAgICAgJGdyYXktMTAwICFkZWZhdWx0O1xuXG4kZHJvcGRvd24tbGluay1hY3RpdmUtY29sb3I6ICAgICAkY29tcG9uZW50LWFjdGl2ZS1jb2xvciAhZGVmYXVsdDtcbiRkcm9wZG93bi1saW5rLWFjdGl2ZS1iZzogICAgICAgICRjb21wb25lbnQtYWN0aXZlLWJnICFkZWZhdWx0O1xuXG4kZHJvcGRvd24tbGluay1kaXNhYmxlZC1jb2xvcjogICAkZ3JheS02MDAgIWRlZmF1bHQ7XG5cbiRkcm9wZG93bi1pdGVtLXBhZGRpbmcteTogICAgICAgIC4yNXJlbSAhZGVmYXVsdDtcbiRkcm9wZG93bi1pdGVtLXBhZGRpbmcteDogICAgICAgIDEuNXJlbSAhZGVmYXVsdDtcblxuJGRyb3Bkb3duLWhlYWRlci1jb2xvcjogICAgICAgICAgJGdyYXktNjAwICFkZWZhdWx0O1xuXG5cbi8vIFotaW5kZXggbWFzdGVyIGxpc3Rcbi8vXG4vLyBXYXJuaW5nOiBBdm9pZCBjdXN0b21pemluZyB0aGVzZSB2YWx1ZXMuIFRoZXkncmUgdXNlZCBmb3IgYSBiaXJkJ3MgZXllIHZpZXdcbi8vIG9mIGNvbXBvbmVudHMgZGVwZW5kZW50IG9uIHRoZSB6LWF4aXMgYW5kIGFyZSBkZXNpZ25lZCB0byBhbGwgd29yayB0b2dldGhlci5cblxuJHppbmRleC1kcm9wZG93bjogICAgICAgICAgIDEwMDAgIWRlZmF1bHQ7XG4kemluZGV4LXN0aWNreTogICAgICAgICAgICAgMTAyMCAhZGVmYXVsdDtcbiR6aW5kZXgtZml4ZWQ6ICAgICAgICAgICAgICAxMDMwICFkZWZhdWx0O1xuJHppbmRleC1tb2RhbC1iYWNrZHJvcDogICAgIDEwNDAgIWRlZmF1bHQ7XG4kemluZGV4LW1vZGFsOiAgICAgICAgICAgICAgMTA1MCAhZGVmYXVsdDtcbiR6aW5kZXgtcG9wb3ZlcjogICAgICAgICAgICAxMDYwICFkZWZhdWx0O1xuJHppbmRleC10b29sdGlwOiAgICAgICAgICAgIDEwNzAgIWRlZmF1bHQ7XG5cbi8vIE5hdnNcblxuJG5hdi1saW5rLXBhZGRpbmcteTogICAgICAgICAgICAuNXJlbSAhZGVmYXVsdDtcbiRuYXYtbGluay1wYWRkaW5nLXg6ICAgICAgICAgICAgMXJlbSAhZGVmYXVsdDtcbiRuYXYtbGluay1kaXNhYmxlZC1jb2xvcjogICAgICAgJGdyYXktNjAwICFkZWZhdWx0O1xuXG4kbmF2LXRhYnMtYm9yZGVyLWNvbG9yOiAgICAgICAgICAgICAgICAgICAgICAgI2RkZCAhZGVmYXVsdDtcbiRuYXYtdGFicy1ib3JkZXItd2lkdGg6ICAgICAgICAgICAgICAgICAgICAgICAkYm9yZGVyLXdpZHRoICFkZWZhdWx0O1xuJG5hdi10YWJzLWJvcmRlci1yYWRpdXM6ICAgICAgICAgICAgICAgICAgICAgICRib3JkZXItcmFkaXVzICFkZWZhdWx0O1xuJG5hdi10YWJzLWxpbmstaG92ZXItYm9yZGVyLWNvbG9yOiAgICAgICAgICAgICRncmF5LTIwMCAhZGVmYXVsdDtcbiRuYXYtdGFicy1saW5rLWFjdGl2ZS1jb2xvcjogICAgICAgICAgICAgICAgICAkZ3JheS03MDAgIWRlZmF1bHQ7XG4kbmF2LXRhYnMtbGluay1hY3RpdmUtYmc6ICAgICAgICAgICAgICAgICAgICAgJGJvZHktYmcgIWRlZmF1bHQ7XG4kbmF2LXRhYnMtbGluay1hY3RpdmUtYm9yZGVyLWNvbG9yOiAgICAgICAgICAgI2RkZCAhZGVmYXVsdDtcblxuJG5hdi1waWxscy1ib3JkZXItcmFkaXVzOiAgICAgJGJvcmRlci1yYWRpdXMgIWRlZmF1bHQ7XG4kbmF2LXBpbGxzLWxpbmstYWN0aXZlLWNvbG9yOiAkY29tcG9uZW50LWFjdGl2ZS1jb2xvciAhZGVmYXVsdDtcbiRuYXYtcGlsbHMtbGluay1hY3RpdmUtYmc6ICAgICRjb21wb25lbnQtYWN0aXZlLWJnICFkZWZhdWx0O1xuXG4vLyBOYXZiYXJcblxuJG5hdmJhci1wYWRkaW5nLXk6ICAgICAgICAgICAgICAgICAgKCRzcGFjZXIgLyAyKSAhZGVmYXVsdDtcbiRuYXZiYXItcGFkZGluZy14OiAgICAgICAgICAgICAgICAgICRzcGFjZXIgIWRlZmF1bHQ7XG5cbiRuYXZiYXItYnJhbmQtZm9udC1zaXplOiAgICAgICAgICAgICRmb250LXNpemUtbGcgIWRlZmF1bHQ7XG4vLyBDb21wdXRlIHRoZSBuYXZiYXItYnJhbmQgcGFkZGluZy15IHNvIHRoZSBuYXZiYXItYnJhbmQgd2lsbCBoYXZlIHRoZSBzYW1lIGhlaWdodCBhcyBuYXZiYXItdGV4dCBhbmQgbmF2LWxpbmtcbiRuYXYtbGluay1oZWlnaHQ6ICAgICAgICAgICAgICAgICAgICRuYXZiYXItYnJhbmQtZm9udC1zaXplICogJGxpbmUtaGVpZ2h0LWJhc2UgIWRlZmF1bHQ7XG4kbmF2YmFyLWJyYW5kLWhlaWdodDogICAgICAgICAgICAgICAoJGZvbnQtc2l6ZS1iYXNlICogJGxpbmUtaGVpZ2h0LWJhc2UgKyAkbmF2LWxpbmstcGFkZGluZy15ICogMikgIWRlZmF1bHQ7XG4kbmF2YmFyLWJyYW5kLXBhZGRpbmcteTogICAgICAgICAgICAoJG5hdmJhci1icmFuZC1oZWlnaHQgLSAkbmF2LWxpbmstaGVpZ2h0KSAvIDIgIWRlZmF1bHQ7XG5cbiRuYXZiYXItdG9nZ2xlci1wYWRkaW5nLXk6ICAgICAgICAgICAuMjVyZW0gIWRlZmF1bHQ7XG4kbmF2YmFyLXRvZ2dsZXItcGFkZGluZy14OiAgICAgICAgICAgLjc1cmVtICFkZWZhdWx0O1xuJG5hdmJhci10b2dnbGVyLWZvbnQtc2l6ZTogICAgICAgICAgICRmb250LXNpemUtbGcgIWRlZmF1bHQ7XG4kbmF2YmFyLXRvZ2dsZXItYm9yZGVyLXJhZGl1czogICAgICAgJGJ0bi1ib3JkZXItcmFkaXVzICFkZWZhdWx0O1xuXG4kbmF2YmFyLWRhcmstY29sb3I6ICAgICAgICAgICAgICAgICByZ2JhKCR3aGl0ZSwuNSkgIWRlZmF1bHQ7XG4kbmF2YmFyLWRhcmstaG92ZXItY29sb3I6ICAgICAgICAgICByZ2JhKCR3aGl0ZSwuNzUpICFkZWZhdWx0O1xuJG5hdmJhci1kYXJrLWFjdGl2ZS1jb2xvcjogICAgICAgICAgcmdiYSgkd2hpdGUsMSkgIWRlZmF1bHQ7XG4kbmF2YmFyLWRhcmstZGlzYWJsZWQtY29sb3I6ICAgICAgICByZ2JhKCR3aGl0ZSwuMjUpICFkZWZhdWx0O1xuJG5hdmJhci1kYXJrLXRvZ2dsZXItaWNvbi1iZzogc3RyLXJlcGxhY2UodXJsKFwiZGF0YTppbWFnZS9zdmcreG1sO2NoYXJzZXQ9dXRmOCwlM0Nzdmcgdmlld0JveD0nMCAwIDMwIDMwJyB4bWxucz0naHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmcnJTNFJTNDcGF0aCBzdHJva2U9JyN7JG5hdmJhci1kYXJrLWNvbG9yfScgc3Ryb2tlLXdpZHRoPScyJyBzdHJva2UtbGluZWNhcD0ncm91bmQnIHN0cm9rZS1taXRlcmxpbWl0PScxMCcgZD0nTTQgN2gyMk00IDE1aDIyTTQgMjNoMjInLyUzRSUzQy9zdmclM0VcIiksIFwiI1wiLCBcIiUyM1wiKSAhZGVmYXVsdDtcbiRuYXZiYXItZGFyay10b2dnbGVyLWJvcmRlci1jb2xvcjogIHJnYmEoJHdoaXRlLC4xKSAhZGVmYXVsdDtcblxuJG5hdmJhci1saWdodC1jb2xvcjogICAgICAgICAgICAgICAgcmdiYSgkYmxhY2ssLjUpICFkZWZhdWx0O1xuJG5hdmJhci1saWdodC1ob3Zlci1jb2xvcjogICAgICAgICAgcmdiYSgkYmxhY2ssLjcpICFkZWZhdWx0O1xuJG5hdmJhci1saWdodC1hY3RpdmUtY29sb3I6ICAgICAgICAgcmdiYSgkYmxhY2ssLjkpICFkZWZhdWx0O1xuJG5hdmJhci1saWdodC1kaXNhYmxlZC1jb2xvcjogICAgICAgcmdiYSgkYmxhY2ssLjMpICFkZWZhdWx0O1xuJG5hdmJhci1saWdodC10b2dnbGVyLWljb24tYmc6IHN0ci1yZXBsYWNlKHVybChcImRhdGE6aW1hZ2Uvc3ZnK3htbDtjaGFyc2V0PXV0ZjgsJTNDc3ZnIHZpZXdCb3g9JzAgMCAzMCAzMCcgeG1sbnM9J2h0dHA6Ly93d3cudzMub3JnLzIwMDAvc3ZnJyUzRSUzQ3BhdGggc3Ryb2tlPScjeyRuYXZiYXItbGlnaHQtY29sb3J9JyBzdHJva2Utd2lkdGg9JzInIHN0cm9rZS1saW5lY2FwPSdyb3VuZCcgc3Ryb2tlLW1pdGVybGltaXQ9JzEwJyBkPSdNNCA3aDIyTTQgMTVoMjJNNCAyM2gyMicvJTNFJTNDL3N2ZyUzRVwiKSwgXCIjXCIsIFwiJTIzXCIpICFkZWZhdWx0O1xuJG5hdmJhci1saWdodC10b2dnbGVyLWJvcmRlci1jb2xvcjogcmdiYSgkYmxhY2ssLjEpICFkZWZhdWx0O1xuXG4vLyBQYWdpbmF0aW9uXG5cbiRwYWdpbmF0aW9uLXBhZGRpbmcteTogICAgICAgICAgICAgICAgLjVyZW0gIWRlZmF1bHQ7XG4kcGFnaW5hdGlvbi1wYWRkaW5nLXg6ICAgICAgICAgICAgICAgIC43NXJlbSAhZGVmYXVsdDtcbiRwYWdpbmF0aW9uLXBhZGRpbmcteS1zbTogICAgICAgICAgICAgLjI1cmVtICFkZWZhdWx0O1xuJHBhZ2luYXRpb24tcGFkZGluZy14LXNtOiAgICAgICAgICAgICAuNXJlbSAhZGVmYXVsdDtcbiRwYWdpbmF0aW9uLXBhZGRpbmcteS1sZzogICAgICAgICAgICAgLjc1cmVtICFkZWZhdWx0O1xuJHBhZ2luYXRpb24tcGFkZGluZy14LWxnOiAgICAgICAgICAgICAxLjVyZW0gIWRlZmF1bHQ7XG4kcGFnaW5hdGlvbi1saW5lLWhlaWdodDogICAgICAgICAgICAgIDEuMjUgIWRlZmF1bHQ7XG5cbiRwYWdpbmF0aW9uLWNvbG9yOiAgICAgICAgICAgICAgICAgICAgICRsaW5rLWNvbG9yICFkZWZhdWx0O1xuJHBhZ2luYXRpb24tYmc6ICAgICAgICAgICAgICAgICAgICAgICAgJHdoaXRlICFkZWZhdWx0O1xuJHBhZ2luYXRpb24tYm9yZGVyLXdpZHRoOiAgICAgICAgICAgICAgJGJvcmRlci13aWR0aCAhZGVmYXVsdDtcbiRwYWdpbmF0aW9uLWJvcmRlci1jb2xvcjogICAgICAgICAgICAgICNkZGQgIWRlZmF1bHQ7XG5cbiRwYWdpbmF0aW9uLWhvdmVyLWNvbG9yOiAgICAgICAgICAgICAgICRsaW5rLWhvdmVyLWNvbG9yICFkZWZhdWx0O1xuJHBhZ2luYXRpb24taG92ZXItYmc6ICAgICAgICAgICAgICAgICAgJGdyYXktMjAwICFkZWZhdWx0O1xuJHBhZ2luYXRpb24taG92ZXItYm9yZGVyLWNvbG9yOiAgICAgICAgI2RkZCAhZGVmYXVsdDtcblxuJHBhZ2luYXRpb24tYWN0aXZlLWNvbG9yOiAgICAgICAgICAgICAgJHdoaXRlICFkZWZhdWx0O1xuJHBhZ2luYXRpb24tYWN0aXZlLWJnOiAgICAgICAgICAgICAgICAgdGhlbWUtY29sb3IoXCJwcmltYXJ5XCIpICFkZWZhdWx0O1xuJHBhZ2luYXRpb24tYWN0aXZlLWJvcmRlci1jb2xvcjogICAgICAgdGhlbWUtY29sb3IoXCJwcmltYXJ5XCIpICFkZWZhdWx0O1xuXG4kcGFnaW5hdGlvbi1kaXNhYmxlZC1jb2xvcjogICAgICAgICAgICAkZ3JheS02MDAgIWRlZmF1bHQ7XG4kcGFnaW5hdGlvbi1kaXNhYmxlZC1iZzogICAgICAgICAgICAgICAkd2hpdGUgIWRlZmF1bHQ7XG4kcGFnaW5hdGlvbi1kaXNhYmxlZC1ib3JkZXItY29sb3I6ICAgICAjZGRkICFkZWZhdWx0O1xuXG5cbi8vIEp1bWJvdHJvblxuXG4kanVtYm90cm9uLXBhZGRpbmc6ICAgICAgICAgICAgICAycmVtICFkZWZhdWx0O1xuJGp1bWJvdHJvbi1iZzogICAgICAgICAgICAgICAgICAgJGdyYXktMjAwICFkZWZhdWx0O1xuXG5cbi8vIENhcmRzXG5cbiRjYXJkLXNwYWNlci15OiAgICAgICAgICAgIC43NXJlbSAhZGVmYXVsdDtcbiRjYXJkLXNwYWNlci14OiAgICAgICAgICAgIDEuMjVyZW0gIWRlZmF1bHQ7XG4kY2FyZC1ib3JkZXItd2lkdGg6ICAgICAgICAxcHggIWRlZmF1bHQ7XG4kY2FyZC1ib3JkZXItcmFkaXVzOiAgICAgICAkYm9yZGVyLXJhZGl1cyAhZGVmYXVsdDtcbiRjYXJkLWJvcmRlci1jb2xvcjogICAgICAgIHJnYmEoJGJsYWNrLC4xMjUpICFkZWZhdWx0O1xuJGNhcmQtaW5uZXItYm9yZGVyLXJhZGl1czogY2FsYygjeyRjYXJkLWJvcmRlci1yYWRpdXN9IC0gI3skY2FyZC1ib3JkZXItd2lkdGh9KSAhZGVmYXVsdDtcbiRjYXJkLWNhcC1iZzogICAgICAgICAgICAgIHJnYmEoJGJsYWNrLCAuMDMpICFkZWZhdWx0O1xuJGNhcmQtYmc6ICAgICAgICAgICAgICAgICAgJHdoaXRlICFkZWZhdWx0O1xuXG4kY2FyZC1pbWctb3ZlcmxheS1wYWRkaW5nOiAxLjI1cmVtICFkZWZhdWx0O1xuXG4kY2FyZC1kZWNrLW1hcmdpbjogICAgICAgICAgKCRncmlkLWd1dHRlci13aWR0aCAvIDIpICFkZWZhdWx0O1xuXG4kY2FyZC1jb2x1bW5zLWNvdW50OiAgICAgICAgMyAhZGVmYXVsdDtcbiRjYXJkLWNvbHVtbnMtZ2FwOiAgICAgICAgICAxLjI1cmVtICFkZWZhdWx0O1xuJGNhcmQtY29sdW1ucy1tYXJnaW46ICAgICAgICRjYXJkLXNwYWNlci15ICFkZWZhdWx0O1xuXG5cbi8vIFRvb2x0aXBzXG5cbiR0b29sdGlwLW1heC13aWR0aDogICAgICAgICAgIDIwMHB4ICFkZWZhdWx0O1xuJHRvb2x0aXAtY29sb3I6ICAgICAgICAgICAgICAgJHdoaXRlICFkZWZhdWx0O1xuJHRvb2x0aXAtYmc6ICAgICAgICAgICAgICAgICAgJGJsYWNrICFkZWZhdWx0O1xuJHRvb2x0aXAtb3BhY2l0eTogICAgICAgICAgICAgLjkgIWRlZmF1bHQ7XG4kdG9vbHRpcC1wYWRkaW5nLXk6ICAgICAgICAgICAzcHggIWRlZmF1bHQ7XG4kdG9vbHRpcC1wYWRkaW5nLXg6ICAgICAgICAgICA4cHggIWRlZmF1bHQ7XG4kdG9vbHRpcC1tYXJnaW46ICAgICAgICAgICAgICAwICFkZWZhdWx0O1xuXG5cbiR0b29sdGlwLWFycm93LXdpZHRoOiAgICAgICAgIDVweCAhZGVmYXVsdDtcbiR0b29sdGlwLWFycm93LWhlaWdodDogICAgICAgIDVweCAhZGVmYXVsdDtcbiR0b29sdGlwLWFycm93LWNvbG9yOiAgICAgICAgICR0b29sdGlwLWJnICFkZWZhdWx0O1xuXG5cbi8vIFBvcG92ZXJzXG5cbiRwb3BvdmVyLWlubmVyLXBhZGRpbmc6ICAgICAgICAgICAgICAgMXB4ICFkZWZhdWx0O1xuJHBvcG92ZXItYmc6ICAgICAgICAgICAgICAgICAgICAgICAgICAkd2hpdGUgIWRlZmF1bHQ7XG4kcG9wb3Zlci1tYXgtd2lkdGg6ICAgICAgICAgICAgICAgICAgIDI3NnB4ICFkZWZhdWx0O1xuJHBvcG92ZXItYm9yZGVyLXdpZHRoOiAgICAgICAgICAgICAgICAkYm9yZGVyLXdpZHRoICFkZWZhdWx0O1xuJHBvcG92ZXItYm9yZGVyLWNvbG9yOiAgICAgICAgICAgICAgICByZ2JhKCRibGFjaywuMikgIWRlZmF1bHQ7XG4kcG9wb3Zlci1ib3gtc2hhZG93OiAgICAgICAgICAgICAgICAgIDAgNXB4IDEwcHggcmdiYSgkYmxhY2ssLjIpICFkZWZhdWx0O1xuXG4kcG9wb3Zlci1oZWFkZXItYmc6ICAgICAgICAgICAgICAgICAgICBkYXJrZW4oJHBvcG92ZXItYmcsIDMlKSAhZGVmYXVsdDtcbiRwb3BvdmVyLWhlYWRlci1jb2xvcjogICAgICAgICAgICAgICAgICRoZWFkaW5ncy1jb2xvciAhZGVmYXVsdDtcbiRwb3BvdmVyLWhlYWRlci1wYWRkaW5nLXk6ICAgICAgICAgICAgIDhweCAhZGVmYXVsdDtcbiRwb3BvdmVyLWhlYWRlci1wYWRkaW5nLXg6ICAgICAgICAgICAgIDE0cHggIWRlZmF1bHQ7XG5cbiRwb3BvdmVyLWJvZHktY29sb3I6ICAgICAgICAgICAgICAgJGJvZHktY29sb3IgIWRlZmF1bHQ7XG4kcG9wb3Zlci1ib2R5LXBhZGRpbmcteTogICAgICAgICAgIDlweCAhZGVmYXVsdDtcbiRwb3BvdmVyLWJvZHktcGFkZGluZy14OiAgICAgICAgICAgMTRweCAhZGVmYXVsdDtcblxuJHBvcG92ZXItYXJyb3ctd2lkdGg6ICAgICAgICAgICAgICAgICAxMHB4ICFkZWZhdWx0O1xuJHBvcG92ZXItYXJyb3ctaGVpZ2h0OiAgICAgICAgICAgICAgICA1cHggIWRlZmF1bHQ7XG4kcG9wb3Zlci1hcnJvdy1jb2xvcjogICAgICAgICAgICAgICAgICRwb3BvdmVyLWJnICFkZWZhdWx0O1xuXG4kcG9wb3Zlci1hcnJvdy1vdXRlci13aWR0aDogICAgICAgICAgICgkcG9wb3Zlci1hcnJvdy13aWR0aCArIDFweCkgIWRlZmF1bHQ7XG4kcG9wb3Zlci1hcnJvdy1vdXRlci1jb2xvcjogICAgICAgICAgIGZhZGUtaW4oJHBvcG92ZXItYm9yZGVyLWNvbG9yLCAuMDUpICFkZWZhdWx0O1xuXG5cbi8vIEJhZGdlc1xuXG4kYmFkZ2UtY29sb3I6ICAgICAgICAgICAgICAgICAkd2hpdGUgIWRlZmF1bHQ7XG4kYmFkZ2UtZm9udC1zaXplOiAgICAgICAgICAgICA3NSUgIWRlZmF1bHQ7XG4kYmFkZ2UtZm9udC13ZWlnaHQ6ICAgICAgICAgICAkZm9udC13ZWlnaHQtYm9sZCAhZGVmYXVsdDtcbiRiYWRnZS1wYWRkaW5nLXk6ICAgICAgICAgICAgIC4yNWVtICFkZWZhdWx0O1xuJGJhZGdlLXBhZGRpbmcteDogICAgICAgICAgICAgLjRlbSAhZGVmYXVsdDtcblxuJGJhZGdlLXBpbGwtcGFkZGluZy14OiAgICAgICAgLjZlbSAhZGVmYXVsdDtcbi8vIFVzZSBhIGhpZ2hlciB0aGFuIG5vcm1hbCB2YWx1ZSB0byBlbnN1cmUgY29tcGxldGVseSByb3VuZGVkIGVkZ2VzIHdoZW5cbi8vIGN1c3RvbWl6aW5nIHBhZGRpbmcgb3IgZm9udC1zaXplIG9uIGxhYmVscy5cbiRiYWRnZS1waWxsLWJvcmRlci1yYWRpdXM6ICAgIDEwcmVtICFkZWZhdWx0O1xuXG5cbi8vIE1vZGFsc1xuXG4vLyBQYWRkaW5nIGFwcGxpZWQgdG8gdGhlIG1vZGFsIGJvZHlcbiRtb2RhbC1pbm5lci1wYWRkaW5nOiAgICAgICAgIDE1cHggIWRlZmF1bHQ7XG5cbiRtb2RhbC1kaWFsb2ctbWFyZ2luOiAgICAgICAgIDEwcHggIWRlZmF1bHQ7XG4kbW9kYWwtZGlhbG9nLW1hcmdpbi15LXNtLXVwOiAzMHB4ICFkZWZhdWx0O1xuXG4kbW9kYWwtdGl0bGUtbGluZS1oZWlnaHQ6ICAgICAkbGluZS1oZWlnaHQtYmFzZSAhZGVmYXVsdDtcblxuJG1vZGFsLWNvbnRlbnQtYmc6ICAgICAgICAgICAgICAgJHdoaXRlICFkZWZhdWx0O1xuJG1vZGFsLWNvbnRlbnQtYm9yZGVyLWNvbG9yOiAgICAgcmdiYSgkYmxhY2ssLjIpICFkZWZhdWx0O1xuJG1vZGFsLWNvbnRlbnQtYm9yZGVyLXdpZHRoOiAgICAgJGJvcmRlci13aWR0aCAhZGVmYXVsdDtcbiRtb2RhbC1jb250ZW50LWJveC1zaGFkb3cteHM6ICAgIDAgM3B4IDlweCByZ2JhKCRibGFjaywuNSkgIWRlZmF1bHQ7XG4kbW9kYWwtY29udGVudC1ib3gtc2hhZG93LXNtLXVwOiAwIDVweCAxNXB4IHJnYmEoJGJsYWNrLC41KSAhZGVmYXVsdDtcblxuJG1vZGFsLWJhY2tkcm9wLWJnOiAgICAgICAgICAgJGJsYWNrICFkZWZhdWx0O1xuJG1vZGFsLWJhY2tkcm9wLW9wYWNpdHk6ICAgICAgLjUgIWRlZmF1bHQ7XG4kbW9kYWwtaGVhZGVyLWJvcmRlci1jb2xvcjogICAkZ3JheS0yMDAgIWRlZmF1bHQ7XG4kbW9kYWwtZm9vdGVyLWJvcmRlci1jb2xvcjogICAkbW9kYWwtaGVhZGVyLWJvcmRlci1jb2xvciAhZGVmYXVsdDtcbiRtb2RhbC1oZWFkZXItYm9yZGVyLXdpZHRoOiAgICRtb2RhbC1jb250ZW50LWJvcmRlci13aWR0aCAhZGVmYXVsdDtcbiRtb2RhbC1mb290ZXItYm9yZGVyLXdpZHRoOiAgICRtb2RhbC1oZWFkZXItYm9yZGVyLXdpZHRoICFkZWZhdWx0O1xuJG1vZGFsLWhlYWRlci1wYWRkaW5nOiAgICAgICAgMTVweCAhZGVmYXVsdDtcblxuJG1vZGFsLWxnOiAgICAgICAgICAgICAgICAgICAgODAwcHggIWRlZmF1bHQ7XG4kbW9kYWwtbWQ6ICAgICAgICAgICAgICAgICAgICA1MDBweCAhZGVmYXVsdDtcbiRtb2RhbC1zbTogICAgICAgICAgICAgICAgICAgIDMwMHB4ICFkZWZhdWx0O1xuXG4kbW9kYWwtdHJhbnNpdGlvbjogICAgICAgICAgICB0cmFuc2Zvcm0gLjNzIGVhc2Utb3V0ICFkZWZhdWx0O1xuXG5cbi8vIEFsZXJ0c1xuLy9cbi8vIERlZmluZSBhbGVydCBjb2xvcnMsIGJvcmRlciByYWRpdXMsIGFuZCBwYWRkaW5nLlxuXG4kYWxlcnQtcGFkZGluZy15OiAgICAgICAgICAgICAuNzVyZW0gIWRlZmF1bHQ7XG4kYWxlcnQtcGFkZGluZy14OiAgICAgICAgICAgICAxLjI1cmVtICFkZWZhdWx0O1xuJGFsZXJ0LW1hcmdpbi1ib3R0b206ICAgICAgICAgMXJlbSAhZGVmYXVsdDtcbiRhbGVydC1ib3JkZXItcmFkaXVzOiAgICAgICAgICRib3JkZXItcmFkaXVzICFkZWZhdWx0O1xuJGFsZXJ0LWxpbmstZm9udC13ZWlnaHQ6ICAgICAgJGZvbnQtd2VpZ2h0LWJvbGQgIWRlZmF1bHQ7XG4kYWxlcnQtYm9yZGVyLXdpZHRoOiAgICAgICAgICAkYm9yZGVyLXdpZHRoICFkZWZhdWx0O1xuXG5cbi8vIFByb2dyZXNzIGJhcnNcblxuJHByb2dyZXNzLWhlaWdodDogICAgICAgICAgICAgICAxcmVtICFkZWZhdWx0O1xuJHByb2dyZXNzLWZvbnQtc2l6ZTogICAgICAgICAgICAuNzVyZW0gIWRlZmF1bHQ7XG4kcHJvZ3Jlc3MtYmc6ICAgICAgICAgICAgICAgICAgICRncmF5LTIwMCAhZGVmYXVsdDtcbiRwcm9ncmVzcy1ib3JkZXItcmFkaXVzOiAgICAgICAgJGJvcmRlci1yYWRpdXMgIWRlZmF1bHQ7XG4kcHJvZ3Jlc3MtYm94LXNoYWRvdzogICAgICAgICAgIGluc2V0IDAgLjFyZW0gLjFyZW0gcmdiYSgkYmxhY2ssLjEpICFkZWZhdWx0O1xuJHByb2dyZXNzLWJhci1jb2xvcjogICAgICAgICAgICAkd2hpdGUgIWRlZmF1bHQ7XG4kcHJvZ3Jlc3MtYmFyLWJnOiAgICAgICAgICAgICAgIHRoZW1lLWNvbG9yKFwicHJpbWFyeVwiKSAhZGVmYXVsdDtcbiRwcm9ncmVzcy1iYXItYW5pbWF0aW9uLXRpbWluZzogMXMgbGluZWFyIGluZmluaXRlICFkZWZhdWx0O1xuJHByb2dyZXNzLWJhci10cmFuc2l0aW9uOiAgICAgICB3aWR0aCAuNnMgZWFzZSAhZGVmYXVsdDtcblxuLy8gTGlzdCBncm91cFxuXG4kbGlzdC1ncm91cC1iZzogICAgICAgICAgICAgICAgICAkd2hpdGUgIWRlZmF1bHQ7XG4kbGlzdC1ncm91cC1ib3JkZXItY29sb3I6ICAgICAgICByZ2JhKCRibGFjaywuMTI1KSAhZGVmYXVsdDtcbiRsaXN0LWdyb3VwLWJvcmRlci13aWR0aDogICAgICAgICRib3JkZXItd2lkdGggIWRlZmF1bHQ7XG4kbGlzdC1ncm91cC1ib3JkZXItcmFkaXVzOiAgICAgICAkYm9yZGVyLXJhZGl1cyAhZGVmYXVsdDtcblxuJGxpc3QtZ3JvdXAtaXRlbS1wYWRkaW5nLXk6ICAgICAgLjc1cmVtICFkZWZhdWx0O1xuJGxpc3QtZ3JvdXAtaXRlbS1wYWRkaW5nLXg6ICAgICAgMS4yNXJlbSAhZGVmYXVsdDtcblxuJGxpc3QtZ3JvdXAtaG92ZXItYmc6ICAgICAgICAgICAgICAgICAkZ3JheS0xMDAgIWRlZmF1bHQ7XG4kbGlzdC1ncm91cC1hY3RpdmUtY29sb3I6ICAgICAgICAgICAgICRjb21wb25lbnQtYWN0aXZlLWNvbG9yICFkZWZhdWx0O1xuJGxpc3QtZ3JvdXAtYWN0aXZlLWJnOiAgICAgICAgICAgICAgICAkY29tcG9uZW50LWFjdGl2ZS1iZyAhZGVmYXVsdDtcbiRsaXN0LWdyb3VwLWFjdGl2ZS1ib3JkZXItY29sb3I6ICAgICAgJGxpc3QtZ3JvdXAtYWN0aXZlLWJnICFkZWZhdWx0O1xuXG4kbGlzdC1ncm91cC1kaXNhYmxlZC1jb2xvcjogICAgICAkZ3JheS02MDAgIWRlZmF1bHQ7XG4kbGlzdC1ncm91cC1kaXNhYmxlZC1iZzogICAgICAgICAkbGlzdC1ncm91cC1iZyAhZGVmYXVsdDtcblxuJGxpc3QtZ3JvdXAtYWN0aW9uLWNvbG9yOiAgICAgICAgICAgICAkZ3JheS03MDAgIWRlZmF1bHQ7XG4kbGlzdC1ncm91cC1hY3Rpb24taG92ZXItY29sb3I6ICAgICAgICRsaXN0LWdyb3VwLWFjdGlvbi1jb2xvciAhZGVmYXVsdDtcblxuJGxpc3QtZ3JvdXAtYWN0aW9uLWFjdGl2ZS1jb2xvcjogICAgICAkYm9keS1jb2xvciAhZGVmYXVsdDtcbiRsaXN0LWdyb3VwLWFjdGlvbi1hY3RpdmUtYmc6ICAgICAgICAgJGdyYXktMjAwICFkZWZhdWx0O1xuXG5cbi8vIEltYWdlIHRodW1ibmFpbHNcblxuJHRodW1ibmFpbC1wYWRkaW5nOiAgICAgICAgICAgLjI1cmVtICFkZWZhdWx0O1xuJHRodW1ibmFpbC1iZzogICAgICAgICAgICAgICAgJGJvZHktYmcgIWRlZmF1bHQ7XG4kdGh1bWJuYWlsLWJvcmRlci13aWR0aDogICAgICAkYm9yZGVyLXdpZHRoICFkZWZhdWx0O1xuJHRodW1ibmFpbC1ib3JkZXItY29sb3I6ICAgICAgI2RkZCAhZGVmYXVsdDtcbiR0aHVtYm5haWwtYm9yZGVyLXJhZGl1czogICAgICRib3JkZXItcmFkaXVzICFkZWZhdWx0O1xuJHRodW1ibmFpbC1ib3gtc2hhZG93OiAgICAgICAgMCAxcHggMnB4IHJnYmEoJGJsYWNrLC4wNzUpICFkZWZhdWx0O1xuJHRodW1ibmFpbC10cmFuc2l0aW9uOiAgICAgICAgYWxsIC4ycyBlYXNlLWluLW91dCAhZGVmYXVsdDtcblxuXG4vLyBGaWd1cmVzXG5cbiRmaWd1cmUtY2FwdGlvbi1mb250LXNpemU6IDkwJSAhZGVmYXVsdDtcbiRmaWd1cmUtY2FwdGlvbi1jb2xvcjogICAgICRncmF5LTYwMCAhZGVmYXVsdDtcblxuXG4vLyBCcmVhZGNydW1ic1xuXG4kYnJlYWRjcnVtYi1wYWRkaW5nLXk6ICAgICAgICAgIC43NXJlbSAhZGVmYXVsdDtcbiRicmVhZGNydW1iLXBhZGRpbmcteDogICAgICAgICAgMXJlbSAhZGVmYXVsdDtcbiRicmVhZGNydW1iLWl0ZW0tcGFkZGluZzogICAgICAgLjVyZW0gIWRlZmF1bHQ7XG5cbiRicmVhZGNydW1iLW1hcmdpbi1ib3R0b206ICAgICAgMXJlbSAhZGVmYXVsdDtcblxuJGJyZWFkY3J1bWItYmc6ICAgICAgICAgICAgICAgICAkZ3JheS0yMDAgIWRlZmF1bHQ7XG4kYnJlYWRjcnVtYi1kaXZpZGVyLWNvbG9yOiAgICAgICRncmF5LTYwMCAhZGVmYXVsdDtcbiRicmVhZGNydW1iLWFjdGl2ZS1jb2xvcjogICAgICAgJGdyYXktNjAwICFkZWZhdWx0O1xuJGJyZWFkY3J1bWItZGl2aWRlcjogICAgICAgICAgICBcIi9cIiAhZGVmYXVsdDtcblxuXG4vLyBDYXJvdXNlbFxuXG4kY2Fyb3VzZWwtY29udHJvbC1jb2xvcjogICAgICAgICAgICAgICAgICAgICAgJHdoaXRlICFkZWZhdWx0O1xuJGNhcm91c2VsLWNvbnRyb2wtd2lkdGg6ICAgICAgICAgICAgICAgICAgICAgIDE1JSAhZGVmYXVsdDtcbiRjYXJvdXNlbC1jb250cm9sLW9wYWNpdHk6ICAgICAgICAgICAgICAgICAgICAuNSAhZGVmYXVsdDtcblxuJGNhcm91c2VsLWluZGljYXRvci13aWR0aDogICAgICAgICAgICAgICAgICAgIDMwcHggIWRlZmF1bHQ7XG4kY2Fyb3VzZWwtaW5kaWNhdG9yLWhlaWdodDogICAgICAgICAgICAgICAgICAgM3B4ICFkZWZhdWx0O1xuJGNhcm91c2VsLWluZGljYXRvci1zcGFjZXI6ICAgICAgICAgICAgICAgICAgIDNweCAhZGVmYXVsdDtcbiRjYXJvdXNlbC1pbmRpY2F0b3ItYWN0aXZlLWJnOiAgICAgICAgICAgICAgICAkd2hpdGUgIWRlZmF1bHQ7XG5cbiRjYXJvdXNlbC1jYXB0aW9uLXdpZHRoOiAgICAgICAgICAgICAgICAgICAgICA3MCUgIWRlZmF1bHQ7XG4kY2Fyb3VzZWwtY2FwdGlvbi1jb2xvcjogICAgICAgICAgICAgICAgICAgICAgJHdoaXRlICFkZWZhdWx0O1xuXG4kY2Fyb3VzZWwtY29udHJvbC1pY29uLXdpZHRoOiAgICAgICAgICAgICAgICAgMjBweCAhZGVmYXVsdDtcblxuJGNhcm91c2VsLWNvbnRyb2wtcHJldi1pY29uLWJnOiBzdHItcmVwbGFjZSh1cmwoXCJkYXRhOmltYWdlL3N2Zyt4bWw7Y2hhcnNldD11dGY4LCUzQ3N2ZyB4bWxucz0naHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmcnIGZpbGw9JyN7JGNhcm91c2VsLWNvbnRyb2wtY29sb3J9JyB2aWV3Qm94PScwIDAgOCA4JyUzRSUzQ3BhdGggZD0nTTQgMGwtNCA0IDQgNCAxLjUtMS41LTIuNS0yLjUgMi41LTIuNS0xLjUtMS41eicvJTNFJTNDL3N2ZyUzRVwiKSwgXCIjXCIsIFwiJTIzXCIpICFkZWZhdWx0O1xuJGNhcm91c2VsLWNvbnRyb2wtbmV4dC1pY29uLWJnOiBzdHItcmVwbGFjZSh1cmwoXCJkYXRhOmltYWdlL3N2Zyt4bWw7Y2hhcnNldD11dGY4LCUzQ3N2ZyB4bWxucz0naHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmcnIGZpbGw9JyN7JGNhcm91c2VsLWNvbnRyb2wtY29sb3J9JyB2aWV3Qm94PScwIDAgOCA4JyUzRSUzQ3BhdGggZD0nTTEuNSAwbC0xLjUgMS41IDIuNSAyLjUtMi41IDIuNSAxLjUgMS41IDQtNC00LTR6Jy8lM0UlM0Mvc3ZnJTNFXCIpLCBcIiNcIiwgXCIlMjNcIikgIWRlZmF1bHQ7XG5cbiRjYXJvdXNlbC10cmFuc2l0aW9uOiAgICAgICAgICAgdHJhbnNmb3JtIC42cyBlYXNlICFkZWZhdWx0O1xuXG5cbi8vIENsb3NlXG5cbiRjbG9zZS1mb250LXNpemU6ICAgICAgICAgICAgICRmb250LXNpemUtYmFzZSAqIDEuNSAhZGVmYXVsdDtcbiRjbG9zZS1mb250LXdlaWdodDogICAgICAgICAgICRmb250LXdlaWdodC1ib2xkICFkZWZhdWx0O1xuJGNsb3NlLWNvbG9yOiAgICAgICAgICAgICAgICAgJGJsYWNrICFkZWZhdWx0O1xuJGNsb3NlLXRleHQtc2hhZG93OiAgICAgICAgICAgMCAxcHggMCAkd2hpdGUgIWRlZmF1bHQ7XG5cbi8vIENvZGVcblxuJGNvZGUtZm9udC1zaXplOiAgICAgICAgICAgICAgOTAlICFkZWZhdWx0O1xuJGNvZGUtcGFkZGluZy15OiAgICAgICAgICAgICAgLjJyZW0gIWRlZmF1bHQ7XG4kY29kZS1wYWRkaW5nLXg6ICAgICAgICAgICAgICAuNHJlbSAhZGVmYXVsdDtcbiRjb2RlLWNvbG9yOiAgICAgICAgICAgICAgICAgICNiZDQxNDcgIWRlZmF1bHQ7XG4kY29kZS1iZzogICAgICAgICAgICAgICAgICAgICAkZ3JheS0xMDAgIWRlZmF1bHQ7XG5cbiRrYmQtY29sb3I6ICAgICAgICAgICAgICAgICAgICR3aGl0ZSAhZGVmYXVsdDtcbiRrYmQtYmc6ICAgICAgICAgICAgICAgICAgICAgICRncmF5LTkwMCAhZGVmYXVsdDtcblxuJHByZS1jb2xvcjogICAgICAgICAgICAgICAgICAgJGdyYXktOTAwICFkZWZhdWx0O1xuJHByZS1zY3JvbGxhYmxlLW1heC1oZWlnaHQ6ICAgMzQwcHggIWRlZmF1bHQ7XG4iLCIvKiBGUkFNRSAqL1xuLyogQk9PVFNUUkFQICovXG4vKiFcbiAqIEJvb3RzdHJhcCB2NC4wLjAtYmV0YSAoaHR0cHM6Ly9nZXRib290c3RyYXAuY29tKVxuICogQ29weXJpZ2h0IDIwMTEtMjAxNyBUaGUgQm9vdHN0cmFwIEF1dGhvcnNcbiAqIENvcHlyaWdodCAyMDExLTIwMTcgVHdpdHRlciwgSW5jLlxuICogTGljZW5zZWQgdW5kZXIgTUlUIChodHRwczovL2dpdGh1Yi5jb20vdHdicy9ib290c3RyYXAvYmxvYi9tYXN0ZXIvTElDRU5TRSlcbiAqL1xuQG1lZGlhIHByaW50IHtcbiAgKixcbiAgKjo6YmVmb3JlLFxuICAqOjphZnRlciB7XG4gICAgdGV4dC1zaGFkb3c6IG5vbmUgIWltcG9ydGFudDtcbiAgICBib3gtc2hhZG93OiBub25lICFpbXBvcnRhbnQ7IH1cbiAgYSxcbiAgYTp2aXNpdGVkIHtcbiAgICB0ZXh0LWRlY29yYXRpb246IHVuZGVybGluZTsgfVxuICBhYmJyW3RpdGxlXTo6YWZ0ZXIge1xuICAgIGNvbnRlbnQ6IFwiIChcIiBhdHRyKHRpdGxlKSBcIilcIjsgfVxuICBwcmUge1xuICAgIHdoaXRlLXNwYWNlOiBwcmUtd3JhcCAhaW1wb3J0YW50OyB9XG4gIHByZSxcbiAgYmxvY2txdW90ZSB7XG4gICAgYm9yZGVyOiAxcHggc29saWQgIzk5OTtcbiAgICBwYWdlLWJyZWFrLWluc2lkZTogYXZvaWQ7IH1cbiAgdGhlYWQge1xuICAgIGRpc3BsYXk6IHRhYmxlLWhlYWRlci1ncm91cDsgfVxuICB0cixcbiAgaW1nIHtcbiAgICBwYWdlLWJyZWFrLWluc2lkZTogYXZvaWQ7IH1cbiAgcCxcbiAgaDIsXG4gIGgzIHtcbiAgICBvcnBoYW5zOiAzO1xuICAgIHdpZG93czogMzsgfVxuICBoMixcbiAgaDMge1xuICAgIHBhZ2UtYnJlYWstYWZ0ZXI6IGF2b2lkOyB9XG4gIC5uYXZiYXIge1xuICAgIGRpc3BsYXk6IG5vbmU7IH1cbiAgLmJhZGdlIHtcbiAgICBib3JkZXI6IDFweCBzb2xpZCAjMDAwOyB9XG4gIC50YWJsZSB7XG4gICAgYm9yZGVyLWNvbGxhcHNlOiBjb2xsYXBzZSAhaW1wb3J0YW50OyB9XG4gICAgLnRhYmxlIHRkLFxuICAgIC50YWJsZSB0aCB7XG4gICAgICBiYWNrZ3JvdW5kLWNvbG9yOiAjZmZmICFpbXBvcnRhbnQ7IH1cbiAgLnRhYmxlLWJvcmRlcmVkIHRoLFxuICAudGFibGUtYm9yZGVyZWQgdGQge1xuICAgIGJvcmRlcjogMXB4IHNvbGlkICNkZGQgIWltcG9ydGFudDsgfSB9XG5cbiosXG4qOjpiZWZvcmUsXG4qOjphZnRlciB7XG4gIGJveC1zaXppbmc6IGJvcmRlci1ib3g7IH1cblxuaHRtbCB7XG4gIGZvbnQtZmFtaWx5OiBzYW5zLXNlcmlmO1xuICBsaW5lLWhlaWdodDogMS4xNTtcbiAgLXdlYmtpdC10ZXh0LXNpemUtYWRqdXN0OiAxMDAlO1xuICAtbXMtdGV4dC1zaXplLWFkanVzdDogMTAwJTtcbiAgLW1zLW92ZXJmbG93LXN0eWxlOiBzY3JvbGxiYXI7XG4gIC13ZWJraXQtdGFwLWhpZ2hsaWdodC1jb2xvcjogdHJhbnNwYXJlbnQ7IH1cblxuQC1tcy12aWV3cG9ydCB7XG4gIHdpZHRoOiBkZXZpY2Utd2lkdGg7IH1cblxuYXJ0aWNsZSwgYXNpZGUsIGRpYWxvZywgZmlnY2FwdGlvbiwgZmlndXJlLCBmb290ZXIsIGhlYWRlciwgaGdyb3VwLCBtYWluLCBuYXYsIHNlY3Rpb24ge1xuICBkaXNwbGF5OiBibG9jazsgfVxuXG5ib2R5IHtcbiAgbWFyZ2luOiAwO1xuICBmb250LWZhbWlseTogLWFwcGxlLXN5c3RlbSwgQmxpbmtNYWNTeXN0ZW1Gb250LCBcIlNlZ29lIFVJXCIsIFJvYm90bywgXCJIZWx2ZXRpY2EgTmV1ZVwiLCBBcmlhbCwgc2Fucy1zZXJpZiwgXCJBcHBsZSBDb2xvciBFbW9qaVwiLCBcIlNlZ29lIFVJIEVtb2ppXCIsIFwiU2Vnb2UgVUkgU3ltYm9sXCI7XG4gIGZvbnQtc2l6ZTogMXJlbTtcbiAgZm9udC13ZWlnaHQ6IG5vcm1hbDtcbiAgbGluZS1oZWlnaHQ6IDEuNTtcbiAgY29sb3I6ICMyMTI1Mjk7XG4gIHRleHQtYWxpZ246IGxlZnQ7XG4gIGJhY2tncm91bmQtY29sb3I6ICNmZmY7IH1cblxuW3RhYmluZGV4PVwiLTFcIl06Zm9jdXMge1xuICBvdXRsaW5lOiBub25lICFpbXBvcnRhbnQ7IH1cblxuaHIge1xuICBib3gtc2l6aW5nOiBjb250ZW50LWJveDtcbiAgaGVpZ2h0OiAwO1xuICBvdmVyZmxvdzogdmlzaWJsZTsgfVxuXG5oMSwgaDIsIGgzLCBoNCwgaDUsIGg2IHtcbiAgbWFyZ2luLXRvcDogMDtcbiAgbWFyZ2luLWJvdHRvbTogLjVyZW07IH1cblxucCB7XG4gIG1hcmdpbi10b3A6IDA7XG4gIG1hcmdpbi1ib3R0b206IDFyZW07IH1cblxuYWJiclt0aXRsZV0sXG5hYmJyW2RhdGEtb3JpZ2luYWwtdGl0bGVdIHtcbiAgdGV4dC1kZWNvcmF0aW9uOiB1bmRlcmxpbmU7XG4gIHRleHQtZGVjb3JhdGlvbjogdW5kZXJsaW5lIGRvdHRlZDtcbiAgY3Vyc29yOiBoZWxwO1xuICBib3JkZXItYm90dG9tOiAwOyB9XG5cbmFkZHJlc3Mge1xuICBtYXJnaW4tYm90dG9tOiAxcmVtO1xuICBmb250LXN0eWxlOiBub3JtYWw7XG4gIGxpbmUtaGVpZ2h0OiBpbmhlcml0OyB9XG5cbm9sLFxudWwsXG5kbCB7XG4gIG1hcmdpbi10b3A6IDA7XG4gIG1hcmdpbi1ib3R0b206IDFyZW07IH1cblxub2wgb2wsXG51bCB1bCxcbm9sIHVsLFxudWwgb2wge1xuICBtYXJnaW4tYm90dG9tOiAwOyB9XG5cbmR0IHtcbiAgZm9udC13ZWlnaHQ6IGJvbGQ7IH1cblxuZGQge1xuICBtYXJnaW4tYm90dG9tOiAuNXJlbTtcbiAgbWFyZ2luLWxlZnQ6IDA7IH1cblxuYmxvY2txdW90ZSB7XG4gIG1hcmdpbjogMCAwIDFyZW07IH1cblxuZGZuIHtcbiAgZm9udC1zdHlsZTogaXRhbGljOyB9XG5cbmIsXG5zdHJvbmcge1xuICBmb250LXdlaWdodDogYm9sZGVyOyB9XG5cbnNtYWxsIHtcbiAgZm9udC1zaXplOiA4MCU7IH1cblxuc3ViLFxuc3VwIHtcbiAgcG9zaXRpb246IHJlbGF0aXZlO1xuICBmb250LXNpemU6IDc1JTtcbiAgbGluZS1oZWlnaHQ6IDA7XG4gIHZlcnRpY2FsLWFsaWduOiBiYXNlbGluZTsgfVxuXG5zdWIge1xuICBib3R0b206IC0uMjVlbTsgfVxuXG5zdXAge1xuICB0b3A6IC0uNWVtOyB9XG5cbmEge1xuICBjb2xvcjogIzAwN2JmZjtcbiAgdGV4dC1kZWNvcmF0aW9uOiBub25lO1xuICBiYWNrZ3JvdW5kLWNvbG9yOiB0cmFuc3BhcmVudDtcbiAgLXdlYmtpdC10ZXh0LWRlY29yYXRpb24tc2tpcDogb2JqZWN0czsgfVxuICBhOmhvdmVyIHtcbiAgICBjb2xvcjogIzAwNTZiMztcbiAgICB0ZXh0LWRlY29yYXRpb246IHVuZGVybGluZTsgfVxuXG5hOm5vdChbaHJlZl0pOm5vdChbdGFiaW5kZXhdKSB7XG4gIGNvbG9yOiBpbmhlcml0O1xuICB0ZXh0LWRlY29yYXRpb246IG5vbmU7IH1cbiAgYTpub3QoW2hyZWZdKTpub3QoW3RhYmluZGV4XSk6Zm9jdXMsIGE6bm90KFtocmVmXSk6bm90KFt0YWJpbmRleF0pOmhvdmVyIHtcbiAgICBjb2xvcjogaW5oZXJpdDtcbiAgICB0ZXh0LWRlY29yYXRpb246IG5vbmU7IH1cbiAgYTpub3QoW2hyZWZdKTpub3QoW3RhYmluZGV4XSk6Zm9jdXMge1xuICAgIG91dGxpbmU6IDA7IH1cblxucHJlLFxuY29kZSxcbmtiZCxcbnNhbXAge1xuICBmb250LWZhbWlseTogbW9ub3NwYWNlLCBtb25vc3BhY2U7XG4gIGZvbnQtc2l6ZTogMWVtOyB9XG5cbnByZSB7XG4gIG1hcmdpbi10b3A6IDA7XG4gIG1hcmdpbi1ib3R0b206IDFyZW07XG4gIG92ZXJmbG93OiBhdXRvOyB9XG5cbmZpZ3VyZSB7XG4gIG1hcmdpbjogMCAwIDFyZW07IH1cblxuaW1nIHtcbiAgdmVydGljYWwtYWxpZ246IG1pZGRsZTtcbiAgYm9yZGVyLXN0eWxlOiBub25lOyB9XG5cbnN2Zzpub3QoOnJvb3QpIHtcbiAgb3ZlcmZsb3c6IGhpZGRlbjsgfVxuXG5hLFxuYXJlYSxcbmJ1dHRvbixcbltyb2xlPVwiYnV0dG9uXCJdLFxuaW5wdXQsXG5sYWJlbCxcbnNlbGVjdCxcbnN1bW1hcnksXG50ZXh0YXJlYSB7XG4gIHRvdWNoLWFjdGlvbjogbWFuaXB1bGF0aW9uOyB9XG5cbnRhYmxlIHtcbiAgYm9yZGVyLWNvbGxhcHNlOiBjb2xsYXBzZTsgfVxuXG5jYXB0aW9uIHtcbiAgcGFkZGluZy10b3A6IDAuNzVyZW07XG4gIHBhZGRpbmctYm90dG9tOiAwLjc1cmVtO1xuICBjb2xvcjogIzg2OGU5NjtcbiAgdGV4dC1hbGlnbjogbGVmdDtcbiAgY2FwdGlvbi1zaWRlOiBib3R0b207IH1cblxudGgge1xuICB0ZXh0LWFsaWduOiBpbmhlcml0OyB9XG5cbmxhYmVsIHtcbiAgZGlzcGxheTogaW5saW5lLWJsb2NrO1xuICBtYXJnaW4tYm90dG9tOiAuNXJlbTsgfVxuXG5idXR0b246Zm9jdXMge1xuICBvdXRsaW5lOiAxcHggZG90dGVkO1xuICBvdXRsaW5lOiA1cHggYXV0byAtd2Via2l0LWZvY3VzLXJpbmctY29sb3I7IH1cblxuaW5wdXQsXG5idXR0b24sXG5zZWxlY3QsXG5vcHRncm91cCxcbnRleHRhcmVhIHtcbiAgbWFyZ2luOiAwO1xuICBmb250LWZhbWlseTogaW5oZXJpdDtcbiAgZm9udC1zaXplOiBpbmhlcml0O1xuICBsaW5lLWhlaWdodDogaW5oZXJpdDsgfVxuXG5idXR0b24sXG5pbnB1dCB7XG4gIG92ZXJmbG93OiB2aXNpYmxlOyB9XG5cbmJ1dHRvbixcbnNlbGVjdCB7XG4gIHRleHQtdHJhbnNmb3JtOiBub25lOyB9XG5cbmJ1dHRvbixcbmh0bWwgW3R5cGU9XCJidXR0b25cIl0sXG5bdHlwZT1cInJlc2V0XCJdLFxuW3R5cGU9XCJzdWJtaXRcIl0ge1xuICAtd2Via2l0LWFwcGVhcmFuY2U6IGJ1dHRvbjsgfVxuXG5idXR0b246Oi1tb3otZm9jdXMtaW5uZXIsXG5bdHlwZT1cImJ1dHRvblwiXTo6LW1vei1mb2N1cy1pbm5lcixcblt0eXBlPVwicmVzZXRcIl06Oi1tb3otZm9jdXMtaW5uZXIsXG5bdHlwZT1cInN1Ym1pdFwiXTo6LW1vei1mb2N1cy1pbm5lciB7XG4gIHBhZGRpbmc6IDA7XG4gIGJvcmRlci1zdHlsZTogbm9uZTsgfVxuXG5pbnB1dFt0eXBlPVwicmFkaW9cIl0sXG5pbnB1dFt0eXBlPVwiY2hlY2tib3hcIl0ge1xuICBib3gtc2l6aW5nOiBib3JkZXItYm94O1xuICBwYWRkaW5nOiAwOyB9XG5cbmlucHV0W3R5cGU9XCJkYXRlXCJdLFxuaW5wdXRbdHlwZT1cInRpbWVcIl0sXG5pbnB1dFt0eXBlPVwiZGF0ZXRpbWUtbG9jYWxcIl0sXG5pbnB1dFt0eXBlPVwibW9udGhcIl0ge1xuICAtd2Via2l0LWFwcGVhcmFuY2U6IGxpc3Rib3g7IH1cblxudGV4dGFyZWEge1xuICBvdmVyZmxvdzogYXV0bztcbiAgcmVzaXplOiB2ZXJ0aWNhbDsgfVxuXG5maWVsZHNldCB7XG4gIG1pbi13aWR0aDogMDtcbiAgcGFkZGluZzogMDtcbiAgbWFyZ2luOiAwO1xuICBib3JkZXI6IDA7IH1cblxubGVnZW5kIHtcbiAgZGlzcGxheTogYmxvY2s7XG4gIHdpZHRoOiAxMDAlO1xuICBtYXgtd2lkdGg6IDEwMCU7XG4gIHBhZGRpbmc6IDA7XG4gIG1hcmdpbi1ib3R0b206IC41cmVtO1xuICBmb250LXNpemU6IDEuNXJlbTtcbiAgbGluZS1oZWlnaHQ6IGluaGVyaXQ7XG4gIGNvbG9yOiBpbmhlcml0O1xuICB3aGl0ZS1zcGFjZTogbm9ybWFsOyB9XG5cbnByb2dyZXNzIHtcbiAgdmVydGljYWwtYWxpZ246IGJhc2VsaW5lOyB9XG5cblt0eXBlPVwibnVtYmVyXCJdOjotd2Via2l0LWlubmVyLXNwaW4tYnV0dG9uLFxuW3R5cGU9XCJudW1iZXJcIl06Oi13ZWJraXQtb3V0ZXItc3Bpbi1idXR0b24ge1xuICBoZWlnaHQ6IGF1dG87IH1cblxuW3R5cGU9XCJzZWFyY2hcIl0ge1xuICBvdXRsaW5lLW9mZnNldDogLTJweDtcbiAgLXdlYmtpdC1hcHBlYXJhbmNlOiBub25lOyB9XG5cblt0eXBlPVwic2VhcmNoXCJdOjotd2Via2l0LXNlYXJjaC1jYW5jZWwtYnV0dG9uLFxuW3R5cGU9XCJzZWFyY2hcIl06Oi13ZWJraXQtc2VhcmNoLWRlY29yYXRpb24ge1xuICAtd2Via2l0LWFwcGVhcmFuY2U6IG5vbmU7IH1cblxuOjotd2Via2l0LWZpbGUtdXBsb2FkLWJ1dHRvbiB7XG4gIGZvbnQ6IGluaGVyaXQ7XG4gIC13ZWJraXQtYXBwZWFyYW5jZTogYnV0dG9uOyB9XG5cbm91dHB1dCB7XG4gIGRpc3BsYXk6IGlubGluZS1ibG9jazsgfVxuXG5zdW1tYXJ5IHtcbiAgZGlzcGxheTogbGlzdC1pdGVtOyB9XG5cbnRlbXBsYXRlIHtcbiAgZGlzcGxheTogbm9uZTsgfVxuXG5baGlkZGVuXSB7XG4gIGRpc3BsYXk6IG5vbmUgIWltcG9ydGFudDsgfVxuXG5oMSwgaDIsIGgzLCBoNCwgaDUsIGg2LFxuLmgxLCAuaDIsIC5oMywgLmg0LCAuaDUsIC5oNiB7XG4gIG1hcmdpbi1ib3R0b206IDAuNXJlbTtcbiAgZm9udC1mYW1pbHk6IGluaGVyaXQ7XG4gIGZvbnQtd2VpZ2h0OiA1MDA7XG4gIGxpbmUtaGVpZ2h0OiAxLjE7XG4gIGNvbG9yOiBpbmhlcml0OyB9XG5cbmgxLCAuaDEge1xuICBmb250LXNpemU6IDIuNXJlbTsgfVxuXG5oMiwgLmgyIHtcbiAgZm9udC1zaXplOiAycmVtOyB9XG5cbmgzLCAuaDMge1xuICBmb250LXNpemU6IDEuNzVyZW07IH1cblxuaDQsIC5oNCB7XG4gIGZvbnQtc2l6ZTogMS41cmVtOyB9XG5cbmg1LCAuaDUge1xuICBmb250LXNpemU6IDEuMjVyZW07IH1cblxuaDYsIC5oNiB7XG4gIGZvbnQtc2l6ZTogMXJlbTsgfVxuXG4ubGVhZCB7XG4gIGZvbnQtc2l6ZTogMS4yNXJlbTtcbiAgZm9udC13ZWlnaHQ6IDMwMDsgfVxuXG4uZGlzcGxheS0xIHtcbiAgZm9udC1zaXplOiA2cmVtO1xuICBmb250LXdlaWdodDogMzAwO1xuICBsaW5lLWhlaWdodDogMS4xOyB9XG5cbi5kaXNwbGF5LTIge1xuICBmb250LXNpemU6IDUuNXJlbTtcbiAgZm9udC13ZWlnaHQ6IDMwMDtcbiAgbGluZS1oZWlnaHQ6IDEuMTsgfVxuXG4uZGlzcGxheS0zIHtcbiAgZm9udC1zaXplOiA0LjVyZW07XG4gIGZvbnQtd2VpZ2h0OiAzMDA7XG4gIGxpbmUtaGVpZ2h0OiAxLjE7IH1cblxuLmRpc3BsYXktNCB7XG4gIGZvbnQtc2l6ZTogMy41cmVtO1xuICBmb250LXdlaWdodDogMzAwO1xuICBsaW5lLWhlaWdodDogMS4xOyB9XG5cbmhyIHtcbiAgbWFyZ2luLXRvcDogMXJlbTtcbiAgbWFyZ2luLWJvdHRvbTogMXJlbTtcbiAgYm9yZGVyOiAwO1xuICBib3JkZXItdG9wOiAxcHggc29saWQgcmdiYSgwLCAwLCAwLCAwLjEpOyB9XG5cbnNtYWxsLFxuLnNtYWxsIHtcbiAgZm9udC1zaXplOiA4MCU7XG4gIGZvbnQtd2VpZ2h0OiBub3JtYWw7IH1cblxubWFyayxcbi5tYXJrIHtcbiAgcGFkZGluZzogMC4yZW07XG4gIGJhY2tncm91bmQtY29sb3I6ICNmY2Y4ZTM7IH1cblxuLmxpc3QtdW5zdHlsZWQge1xuICBwYWRkaW5nLWxlZnQ6IDA7XG4gIGxpc3Qtc3R5bGU6IG5vbmU7IH1cblxuLmxpc3QtaW5saW5lIHtcbiAgcGFkZGluZy1sZWZ0OiAwO1xuICBsaXN0LXN0eWxlOiBub25lOyB9XG5cbi5saXN0LWlubGluZS1pdGVtIHtcbiAgZGlzcGxheTogaW5saW5lLWJsb2NrOyB9XG4gIC5saXN0LWlubGluZS1pdGVtOm5vdCg6bGFzdC1jaGlsZCkge1xuICAgIG1hcmdpbi1yaWdodDogNXB4OyB9XG5cbi5pbml0aWFsaXNtIHtcbiAgZm9udC1zaXplOiA5MCU7XG4gIHRleHQtdHJhbnNmb3JtOiB1cHBlcmNhc2U7IH1cblxuLmJsb2NrcXVvdGUge1xuICBtYXJnaW4tYm90dG9tOiAxcmVtO1xuICBmb250LXNpemU6IDEuMjVyZW07IH1cblxuLmJsb2NrcXVvdGUtZm9vdGVyIHtcbiAgZGlzcGxheTogYmxvY2s7XG4gIGZvbnQtc2l6ZTogODAlO1xuICBjb2xvcjogIzg2OGU5NjsgfVxuICAuYmxvY2txdW90ZS1mb290ZXI6OmJlZm9yZSB7XG4gICAgY29udGVudDogXCJcXDIwMTQgXFwwMEEwXCI7IH1cblxuLmltZy1mbHVpZCB7XG4gIG1heC13aWR0aDogMTAwJTtcbiAgaGVpZ2h0OiBhdXRvOyB9XG5cbi5pbWctdGh1bWJuYWlsIHtcbiAgcGFkZGluZzogMC4yNXJlbTtcbiAgYmFja2dyb3VuZC1jb2xvcjogI2ZmZjtcbiAgYm9yZGVyOiAxcHggc29saWQgI2RkZDtcbiAgYm9yZGVyLXJhZGl1czogMC4yNXJlbTtcbiAgdHJhbnNpdGlvbjogYWxsIDAuMnMgZWFzZS1pbi1vdXQ7XG4gIG1heC13aWR0aDogMTAwJTtcbiAgaGVpZ2h0OiBhdXRvOyB9XG5cbi5maWd1cmUge1xuICBkaXNwbGF5OiBpbmxpbmUtYmxvY2s7IH1cblxuLmZpZ3VyZS1pbWcge1xuICBtYXJnaW4tYm90dG9tOiAwLjVyZW07XG4gIGxpbmUtaGVpZ2h0OiAxOyB9XG5cbi5maWd1cmUtY2FwdGlvbiB7XG4gIGZvbnQtc2l6ZTogOTAlO1xuICBjb2xvcjogIzg2OGU5NjsgfVxuXG5jb2RlLFxua2JkLFxucHJlLFxuc2FtcCB7XG4gIGZvbnQtZmFtaWx5OiBcIlNGTW9uby1SZWd1bGFyXCIsIE1lbmxvLCBNb25hY28sIENvbnNvbGFzLCBcIkxpYmVyYXRpb24gTW9ub1wiLCBcIkNvdXJpZXIgTmV3XCIsIG1vbm9zcGFjZTsgfVxuXG5jb2RlIHtcbiAgcGFkZGluZzogMC4ycmVtIDAuNHJlbTtcbiAgZm9udC1zaXplOiA5MCU7XG4gIGNvbG9yOiAjYmQ0MTQ3O1xuICBiYWNrZ3JvdW5kLWNvbG9yOiAjZjhmOWZhO1xuICBib3JkZXItcmFkaXVzOiAwLjI1cmVtOyB9XG4gIGEgPiBjb2RlIHtcbiAgICBwYWRkaW5nOiAwO1xuICAgIGNvbG9yOiBpbmhlcml0O1xuICAgIGJhY2tncm91bmQtY29sb3I6IGluaGVyaXQ7IH1cblxua2JkIHtcbiAgcGFkZGluZzogMC4ycmVtIDAuNHJlbTtcbiAgZm9udC1zaXplOiA5MCU7XG4gIGNvbG9yOiAjZmZmO1xuICBiYWNrZ3JvdW5kLWNvbG9yOiAjMjEyNTI5O1xuICBib3JkZXItcmFkaXVzOiAwLjJyZW07IH1cbiAga2JkIGtiZCB7XG4gICAgcGFkZGluZzogMDtcbiAgICBmb250LXNpemU6IDEwMCU7XG4gICAgZm9udC13ZWlnaHQ6IGJvbGQ7IH1cblxucHJlIHtcbiAgZGlzcGxheTogYmxvY2s7XG4gIG1hcmdpbi10b3A6IDA7XG4gIG1hcmdpbi1ib3R0b206IDFyZW07XG4gIGZvbnQtc2l6ZTogOTAlO1xuICBjb2xvcjogIzIxMjUyOTsgfVxuICBwcmUgY29kZSB7XG4gICAgcGFkZGluZzogMDtcbiAgICBmb250LXNpemU6IGluaGVyaXQ7XG4gICAgY29sb3I6IGluaGVyaXQ7XG4gICAgYmFja2dyb3VuZC1jb2xvcjogdHJhbnNwYXJlbnQ7XG4gICAgYm9yZGVyLXJhZGl1czogMDsgfVxuXG4ucHJlLXNjcm9sbGFibGUge1xuICBtYXgtaGVpZ2h0OiAzNDBweDtcbiAgb3ZlcmZsb3cteTogc2Nyb2xsOyB9XG5cbi5jb250YWluZXIge1xuICBtYXJnaW4tcmlnaHQ6IGF1dG87XG4gIG1hcmdpbi1sZWZ0OiBhdXRvO1xuICBwYWRkaW5nLXJpZ2h0OiAxNXB4O1xuICBwYWRkaW5nLWxlZnQ6IDE1cHg7XG4gIHdpZHRoOiAxMDAlOyB9XG4gIEBtZWRpYSAobWluLXdpZHRoOiA1NzZweCkge1xuICAgIC5jb250YWluZXIge1xuICAgICAgbWF4LXdpZHRoOiA1NDBweDsgfSB9XG4gIEBtZWRpYSAobWluLXdpZHRoOiA3NjhweCkge1xuICAgIC5jb250YWluZXIge1xuICAgICAgbWF4LXdpZHRoOiA3MjBweDsgfSB9XG4gIEBtZWRpYSAobWluLXdpZHRoOiA5OTJweCkge1xuICAgIC5jb250YWluZXIge1xuICAgICAgbWF4LXdpZHRoOiA5NjBweDsgfSB9XG4gIEBtZWRpYSAobWluLXdpZHRoOiAxMjAwcHgpIHtcbiAgICAuY29udGFpbmVyIHtcbiAgICAgIG1heC13aWR0aDogMTE0MHB4OyB9IH1cblxuLmNvbnRhaW5lci1mbHVpZCB7XG4gIHdpZHRoOiAxMDAlO1xuICBtYXJnaW4tcmlnaHQ6IGF1dG87XG4gIG1hcmdpbi1sZWZ0OiBhdXRvO1xuICBwYWRkaW5nLXJpZ2h0OiAxNXB4O1xuICBwYWRkaW5nLWxlZnQ6IDE1cHg7XG4gIHdpZHRoOiAxMDAlOyB9XG5cbi5yb3cge1xuICBkaXNwbGF5OiBmbGV4O1xuICBmbGV4LXdyYXA6IHdyYXA7XG4gIG1hcmdpbi1yaWdodDogLTE1cHg7XG4gIG1hcmdpbi1sZWZ0OiAtMTVweDsgfVxuXG4ubm8tZ3V0dGVycyB7XG4gIG1hcmdpbi1yaWdodDogMDtcbiAgbWFyZ2luLWxlZnQ6IDA7IH1cbiAgLm5vLWd1dHRlcnMgPiAuY29sLFxuICAubm8tZ3V0dGVycyA+IFtjbGFzcyo9XCJjb2wtXCJdIHtcbiAgICBwYWRkaW5nLXJpZ2h0OiAwO1xuICAgIHBhZGRpbmctbGVmdDogMDsgfVxuXG4uY29sLTEsIC5jb2wtMiwgLmNvbC0zLCAuY29sLTQsIC5jb2wtNSwgLmNvbC02LCAuY29sLTcsIC5jb2wtOCwgLmNvbC05LCAuY29sLTEwLCAuY29sLTExLCAuY29sLTEyLCAuY29sLFxuLmNvbC1hdXRvLCAuY29sLXNtLTEsIC5jb2wtc20tMiwgLmNvbC1zbS0zLCAuY29sLXNtLTQsIC5jb2wtc20tNSwgLmNvbC1zbS02LCAuY29sLXNtLTcsIC5jb2wtc20tOCwgLmNvbC1zbS05LCAuY29sLXNtLTEwLCAuY29sLXNtLTExLCAuY29sLXNtLTEyLCAuY29sLXNtLFxuLmNvbC1zbS1hdXRvLCAuY29sLW1kLTEsIC5jb2wtbWQtMiwgLmNvbC1tZC0zLCAuY29sLW1kLTQsIC5jb2wtbWQtNSwgLmNvbC1tZC02LCAuY29sLW1kLTcsIC5jb2wtbWQtOCwgLmNvbC1tZC05LCAuY29sLW1kLTEwLCAuY29sLW1kLTExLCAuY29sLW1kLTEyLCAuY29sLW1kLFxuLmNvbC1tZC1hdXRvLCAuY29sLWxnLTEsIC5jb2wtbGctMiwgLmNvbC1sZy0zLCAuY29sLWxnLTQsIC5jb2wtbGctNSwgLmNvbC1sZy02LCAuY29sLWxnLTcsIC5jb2wtbGctOCwgLmNvbC1sZy05LCAuY29sLWxnLTEwLCAuY29sLWxnLTExLCAuY29sLWxnLTEyLCAuY29sLWxnLFxuLmNvbC1sZy1hdXRvLCAuY29sLXhsLTEsIC5jb2wteGwtMiwgLmNvbC14bC0zLCAuY29sLXhsLTQsIC5jb2wteGwtNSwgLmNvbC14bC02LCAuY29sLXhsLTcsIC5jb2wteGwtOCwgLmNvbC14bC05LCAuY29sLXhsLTEwLCAuY29sLXhsLTExLCAuY29sLXhsLTEyLCAuY29sLXhsLFxuLmNvbC14bC1hdXRvIHtcbiAgcG9zaXRpb246IHJlbGF0aXZlO1xuICB3aWR0aDogMTAwJTtcbiAgbWluLWhlaWdodDogMXB4O1xuICBwYWRkaW5nLXJpZ2h0OiAxNXB4O1xuICBwYWRkaW5nLWxlZnQ6IDE1cHg7IH1cblxuLmNvbCB7XG4gIGZsZXgtYmFzaXM6IDA7XG4gIGZsZXgtZ3JvdzogMTtcbiAgbWF4LXdpZHRoOiAxMDAlOyB9XG5cbi5jb2wtYXV0byB7XG4gIGZsZXg6IDAgMCBhdXRvO1xuICB3aWR0aDogYXV0bztcbiAgbWF4LXdpZHRoOiBub25lOyB9XG5cbi5jb2wtMSB7XG4gIGZsZXg6IDAgMCA4LjMzMzMzJTtcbiAgbWF4LXdpZHRoOiA4LjMzMzMzJTsgfVxuXG4uY29sLTIge1xuICBmbGV4OiAwIDAgMTYuNjY2NjclO1xuICBtYXgtd2lkdGg6IDE2LjY2NjY3JTsgfVxuXG4uY29sLTMge1xuICBmbGV4OiAwIDAgMjUlO1xuICBtYXgtd2lkdGg6IDI1JTsgfVxuXG4uY29sLTQge1xuICBmbGV4OiAwIDAgMzMuMzMzMzMlO1xuICBtYXgtd2lkdGg6IDMzLjMzMzMzJTsgfVxuXG4uY29sLTUge1xuICBmbGV4OiAwIDAgNDEuNjY2NjclO1xuICBtYXgtd2lkdGg6IDQxLjY2NjY3JTsgfVxuXG4uY29sLTYge1xuICBmbGV4OiAwIDAgNTAlO1xuICBtYXgtd2lkdGg6IDUwJTsgfVxuXG4uY29sLTcge1xuICBmbGV4OiAwIDAgNTguMzMzMzMlO1xuICBtYXgtd2lkdGg6IDU4LjMzMzMzJTsgfVxuXG4uY29sLTgge1xuICBmbGV4OiAwIDAgNjYuNjY2NjclO1xuICBtYXgtd2lkdGg6IDY2LjY2NjY3JTsgfVxuXG4uY29sLTkge1xuICBmbGV4OiAwIDAgNzUlO1xuICBtYXgtd2lkdGg6IDc1JTsgfVxuXG4uY29sLTEwIHtcbiAgZmxleDogMCAwIDgzLjMzMzMzJTtcbiAgbWF4LXdpZHRoOiA4My4zMzMzMyU7IH1cblxuLmNvbC0xMSB7XG4gIGZsZXg6IDAgMCA5MS42NjY2NyU7XG4gIG1heC13aWR0aDogOTEuNjY2NjclOyB9XG5cbi5jb2wtMTIge1xuICBmbGV4OiAwIDAgMTAwJTtcbiAgbWF4LXdpZHRoOiAxMDAlOyB9XG5cbi5vcmRlci0xIHtcbiAgb3JkZXI6IDE7IH1cblxuLm9yZGVyLTIge1xuICBvcmRlcjogMjsgfVxuXG4ub3JkZXItMyB7XG4gIG9yZGVyOiAzOyB9XG5cbi5vcmRlci00IHtcbiAgb3JkZXI6IDQ7IH1cblxuLm9yZGVyLTUge1xuICBvcmRlcjogNTsgfVxuXG4ub3JkZXItNiB7XG4gIG9yZGVyOiA2OyB9XG5cbi5vcmRlci03IHtcbiAgb3JkZXI6IDc7IH1cblxuLm9yZGVyLTgge1xuICBvcmRlcjogODsgfVxuXG4ub3JkZXItOSB7XG4gIG9yZGVyOiA5OyB9XG5cbi5vcmRlci0xMCB7XG4gIG9yZGVyOiAxMDsgfVxuXG4ub3JkZXItMTEge1xuICBvcmRlcjogMTE7IH1cblxuLm9yZGVyLTEyIHtcbiAgb3JkZXI6IDEyOyB9XG5cbkBtZWRpYSAobWluLXdpZHRoOiA1NzZweCkge1xuICAuY29sLXNtIHtcbiAgICBmbGV4LWJhc2lzOiAwO1xuICAgIGZsZXgtZ3JvdzogMTtcbiAgICBtYXgtd2lkdGg6IDEwMCU7IH1cbiAgLmNvbC1zbS1hdXRvIHtcbiAgICBmbGV4OiAwIDAgYXV0bztcbiAgICB3aWR0aDogYXV0bztcbiAgICBtYXgtd2lkdGg6IG5vbmU7IH1cbiAgLmNvbC1zbS0xIHtcbiAgICBmbGV4OiAwIDAgOC4zMzMzMyU7XG4gICAgbWF4LXdpZHRoOiA4LjMzMzMzJTsgfVxuICAuY29sLXNtLTIge1xuICAgIGZsZXg6IDAgMCAxNi42NjY2NyU7XG4gICAgbWF4LXdpZHRoOiAxNi42NjY2NyU7IH1cbiAgLmNvbC1zbS0zIHtcbiAgICBmbGV4OiAwIDAgMjUlO1xuICAgIG1heC13aWR0aDogMjUlOyB9XG4gIC5jb2wtc20tNCB7XG4gICAgZmxleDogMCAwIDMzLjMzMzMzJTtcbiAgICBtYXgtd2lkdGg6IDMzLjMzMzMzJTsgfVxuICAuY29sLXNtLTUge1xuICAgIGZsZXg6IDAgMCA0MS42NjY2NyU7XG4gICAgbWF4LXdpZHRoOiA0MS42NjY2NyU7IH1cbiAgLmNvbC1zbS02IHtcbiAgICBmbGV4OiAwIDAgNTAlO1xuICAgIG1heC13aWR0aDogNTAlOyB9XG4gIC5jb2wtc20tNyB7XG4gICAgZmxleDogMCAwIDU4LjMzMzMzJTtcbiAgICBtYXgtd2lkdGg6IDU4LjMzMzMzJTsgfVxuICAuY29sLXNtLTgge1xuICAgIGZsZXg6IDAgMCA2Ni42NjY2NyU7XG4gICAgbWF4LXdpZHRoOiA2Ni42NjY2NyU7IH1cbiAgLmNvbC1zbS05IHtcbiAgICBmbGV4OiAwIDAgNzUlO1xuICAgIG1heC13aWR0aDogNzUlOyB9XG4gIC5jb2wtc20tMTAge1xuICAgIGZsZXg6IDAgMCA4My4zMzMzMyU7XG4gICAgbWF4LXdpZHRoOiA4My4zMzMzMyU7IH1cbiAgLmNvbC1zbS0xMSB7XG4gICAgZmxleDogMCAwIDkxLjY2NjY3JTtcbiAgICBtYXgtd2lkdGg6IDkxLjY2NjY3JTsgfVxuICAuY29sLXNtLTEyIHtcbiAgICBmbGV4OiAwIDAgMTAwJTtcbiAgICBtYXgtd2lkdGg6IDEwMCU7IH1cbiAgLm9yZGVyLXNtLTEge1xuICAgIG9yZGVyOiAxOyB9XG4gIC5vcmRlci1zbS0yIHtcbiAgICBvcmRlcjogMjsgfVxuICAub3JkZXItc20tMyB7XG4gICAgb3JkZXI6IDM7IH1cbiAgLm9yZGVyLXNtLTQge1xuICAgIG9yZGVyOiA0OyB9XG4gIC5vcmRlci1zbS01IHtcbiAgICBvcmRlcjogNTsgfVxuICAub3JkZXItc20tNiB7XG4gICAgb3JkZXI6IDY7IH1cbiAgLm9yZGVyLXNtLTcge1xuICAgIG9yZGVyOiA3OyB9XG4gIC5vcmRlci1zbS04IHtcbiAgICBvcmRlcjogODsgfVxuICAub3JkZXItc20tOSB7XG4gICAgb3JkZXI6IDk7IH1cbiAgLm9yZGVyLXNtLTEwIHtcbiAgICBvcmRlcjogMTA7IH1cbiAgLm9yZGVyLXNtLTExIHtcbiAgICBvcmRlcjogMTE7IH1cbiAgLm9yZGVyLXNtLTEyIHtcbiAgICBvcmRlcjogMTI7IH0gfVxuXG5AbWVkaWEgKG1pbi13aWR0aDogNzY4cHgpIHtcbiAgLmNvbC1tZCB7XG4gICAgZmxleC1iYXNpczogMDtcbiAgICBmbGV4LWdyb3c6IDE7XG4gICAgbWF4LXdpZHRoOiAxMDAlOyB9XG4gIC5jb2wtbWQtYXV0byB7XG4gICAgZmxleDogMCAwIGF1dG87XG4gICAgd2lkdGg6IGF1dG87XG4gICAgbWF4LXdpZHRoOiBub25lOyB9XG4gIC5jb2wtbWQtMSB7XG4gICAgZmxleDogMCAwIDguMzMzMzMlO1xuICAgIG1heC13aWR0aDogOC4zMzMzMyU7IH1cbiAgLmNvbC1tZC0yIHtcbiAgICBmbGV4OiAwIDAgMTYuNjY2NjclO1xuICAgIG1heC13aWR0aDogMTYuNjY2NjclOyB9XG4gIC5jb2wtbWQtMyB7XG4gICAgZmxleDogMCAwIDI1JTtcbiAgICBtYXgtd2lkdGg6IDI1JTsgfVxuICAuY29sLW1kLTQge1xuICAgIGZsZXg6IDAgMCAzMy4zMzMzMyU7XG4gICAgbWF4LXdpZHRoOiAzMy4zMzMzMyU7IH1cbiAgLmNvbC1tZC01IHtcbiAgICBmbGV4OiAwIDAgNDEuNjY2NjclO1xuICAgIG1heC13aWR0aDogNDEuNjY2NjclOyB9XG4gIC5jb2wtbWQtNiB7XG4gICAgZmxleDogMCAwIDUwJTtcbiAgICBtYXgtd2lkdGg6IDUwJTsgfVxuICAuY29sLW1kLTcge1xuICAgIGZsZXg6IDAgMCA1OC4zMzMzMyU7XG4gICAgbWF4LXdpZHRoOiA1OC4zMzMzMyU7IH1cbiAgLmNvbC1tZC04IHtcbiAgICBmbGV4OiAwIDAgNjYuNjY2NjclO1xuICAgIG1heC13aWR0aDogNjYuNjY2NjclOyB9XG4gIC5jb2wtbWQtOSB7XG4gICAgZmxleDogMCAwIDc1JTtcbiAgICBtYXgtd2lkdGg6IDc1JTsgfVxuICAuY29sLW1kLTEwIHtcbiAgICBmbGV4OiAwIDAgODMuMzMzMzMlO1xuICAgIG1heC13aWR0aDogODMuMzMzMzMlOyB9XG4gIC5jb2wtbWQtMTEge1xuICAgIGZsZXg6IDAgMCA5MS42NjY2NyU7XG4gICAgbWF4LXdpZHRoOiA5MS42NjY2NyU7IH1cbiAgLmNvbC1tZC0xMiB7XG4gICAgZmxleDogMCAwIDEwMCU7XG4gICAgbWF4LXdpZHRoOiAxMDAlOyB9XG4gIC5vcmRlci1tZC0xIHtcbiAgICBvcmRlcjogMTsgfVxuICAub3JkZXItbWQtMiB7XG4gICAgb3JkZXI6IDI7IH1cbiAgLm9yZGVyLW1kLTMge1xuICAgIG9yZGVyOiAzOyB9XG4gIC5vcmRlci1tZC00IHtcbiAgICBvcmRlcjogNDsgfVxuICAub3JkZXItbWQtNSB7XG4gICAgb3JkZXI6IDU7IH1cbiAgLm9yZGVyLW1kLTYge1xuICAgIG9yZGVyOiA2OyB9XG4gIC5vcmRlci1tZC03IHtcbiAgICBvcmRlcjogNzsgfVxuICAub3JkZXItbWQtOCB7XG4gICAgb3JkZXI6IDg7IH1cbiAgLm9yZGVyLW1kLTkge1xuICAgIG9yZGVyOiA5OyB9XG4gIC5vcmRlci1tZC0xMCB7XG4gICAgb3JkZXI6IDEwOyB9XG4gIC5vcmRlci1tZC0xMSB7XG4gICAgb3JkZXI6IDExOyB9XG4gIC5vcmRlci1tZC0xMiB7XG4gICAgb3JkZXI6IDEyOyB9IH1cblxuQG1lZGlhIChtaW4td2lkdGg6IDk5MnB4KSB7XG4gIC5jb2wtbGcge1xuICAgIGZsZXgtYmFzaXM6IDA7XG4gICAgZmxleC1ncm93OiAxO1xuICAgIG1heC13aWR0aDogMTAwJTsgfVxuICAuY29sLWxnLWF1dG8ge1xuICAgIGZsZXg6IDAgMCBhdXRvO1xuICAgIHdpZHRoOiBhdXRvO1xuICAgIG1heC13aWR0aDogbm9uZTsgfVxuICAuY29sLWxnLTEge1xuICAgIGZsZXg6IDAgMCA4LjMzMzMzJTtcbiAgICBtYXgtd2lkdGg6IDguMzMzMzMlOyB9XG4gIC5jb2wtbGctMiB7XG4gICAgZmxleDogMCAwIDE2LjY2NjY3JTtcbiAgICBtYXgtd2lkdGg6IDE2LjY2NjY3JTsgfVxuICAuY29sLWxnLTMge1xuICAgIGZsZXg6IDAgMCAyNSU7XG4gICAgbWF4LXdpZHRoOiAyNSU7IH1cbiAgLmNvbC1sZy00IHtcbiAgICBmbGV4OiAwIDAgMzMuMzMzMzMlO1xuICAgIG1heC13aWR0aDogMzMuMzMzMzMlOyB9XG4gIC5jb2wtbGctNSB7XG4gICAgZmxleDogMCAwIDQxLjY2NjY3JTtcbiAgICBtYXgtd2lkdGg6IDQxLjY2NjY3JTsgfVxuICAuY29sLWxnLTYge1xuICAgIGZsZXg6IDAgMCA1MCU7XG4gICAgbWF4LXdpZHRoOiA1MCU7IH1cbiAgLmNvbC1sZy03IHtcbiAgICBmbGV4OiAwIDAgNTguMzMzMzMlO1xuICAgIG1heC13aWR0aDogNTguMzMzMzMlOyB9XG4gIC5jb2wtbGctOCB7XG4gICAgZmxleDogMCAwIDY2LjY2NjY3JTtcbiAgICBtYXgtd2lkdGg6IDY2LjY2NjY3JTsgfVxuICAuY29sLWxnLTkge1xuICAgIGZsZXg6IDAgMCA3NSU7XG4gICAgbWF4LXdpZHRoOiA3NSU7IH1cbiAgLmNvbC1sZy0xMCB7XG4gICAgZmxleDogMCAwIDgzLjMzMzMzJTtcbiAgICBtYXgtd2lkdGg6IDgzLjMzMzMzJTsgfVxuICAuY29sLWxnLTExIHtcbiAgICBmbGV4OiAwIDAgOTEuNjY2NjclO1xuICAgIG1heC13aWR0aDogOTEuNjY2NjclOyB9XG4gIC5jb2wtbGctMTIge1xuICAgIGZsZXg6IDAgMCAxMDAlO1xuICAgIG1heC13aWR0aDogMTAwJTsgfVxuICAub3JkZXItbGctMSB7XG4gICAgb3JkZXI6IDE7IH1cbiAgLm9yZGVyLWxnLTIge1xuICAgIG9yZGVyOiAyOyB9XG4gIC5vcmRlci1sZy0zIHtcbiAgICBvcmRlcjogMzsgfVxuICAub3JkZXItbGctNCB7XG4gICAgb3JkZXI6IDQ7IH1cbiAgLm9yZGVyLWxnLTUge1xuICAgIG9yZGVyOiA1OyB9XG4gIC5vcmRlci1sZy02IHtcbiAgICBvcmRlcjogNjsgfVxuICAub3JkZXItbGctNyB7XG4gICAgb3JkZXI6IDc7IH1cbiAgLm9yZGVyLWxnLTgge1xuICAgIG9yZGVyOiA4OyB9XG4gIC5vcmRlci1sZy05IHtcbiAgICBvcmRlcjogOTsgfVxuICAub3JkZXItbGctMTAge1xuICAgIG9yZGVyOiAxMDsgfVxuICAub3JkZXItbGctMTEge1xuICAgIG9yZGVyOiAxMTsgfVxuICAub3JkZXItbGctMTIge1xuICAgIG9yZGVyOiAxMjsgfSB9XG5cbkBtZWRpYSAobWluLXdpZHRoOiAxMjAwcHgpIHtcbiAgLmNvbC14bCB7XG4gICAgZmxleC1iYXNpczogMDtcbiAgICBmbGV4LWdyb3c6IDE7XG4gICAgbWF4LXdpZHRoOiAxMDAlOyB9XG4gIC5jb2wteGwtYXV0byB7XG4gICAgZmxleDogMCAwIGF1dG87XG4gICAgd2lkdGg6IGF1dG87XG4gICAgbWF4LXdpZHRoOiBub25lOyB9XG4gIC5jb2wteGwtMSB7XG4gICAgZmxleDogMCAwIDguMzMzMzMlO1xuICAgIG1heC13aWR0aDogOC4zMzMzMyU7IH1cbiAgLmNvbC14bC0yIHtcbiAgICBmbGV4OiAwIDAgMTYuNjY2NjclO1xuICAgIG1heC13aWR0aDogMTYuNjY2NjclOyB9XG4gIC5jb2wteGwtMyB7XG4gICAgZmxleDogMCAwIDI1JTtcbiAgICBtYXgtd2lkdGg6IDI1JTsgfVxuICAuY29sLXhsLTQge1xuICAgIGZsZXg6IDAgMCAzMy4zMzMzMyU7XG4gICAgbWF4LXdpZHRoOiAzMy4zMzMzMyU7IH1cbiAgLmNvbC14bC01IHtcbiAgICBmbGV4OiAwIDAgNDEuNjY2NjclO1xuICAgIG1heC13aWR0aDogNDEuNjY2NjclOyB9XG4gIC5jb2wteGwtNiB7XG4gICAgZmxleDogMCAwIDUwJTtcbiAgICBtYXgtd2lkdGg6IDUwJTsgfVxuICAuY29sLXhsLTcge1xuICAgIGZsZXg6IDAgMCA1OC4zMzMzMyU7XG4gICAgbWF4LXdpZHRoOiA1OC4zMzMzMyU7IH1cbiAgLmNvbC14bC04IHtcbiAgICBmbGV4OiAwIDAgNjYuNjY2NjclO1xuICAgIG1heC13aWR0aDogNjYuNjY2NjclOyB9XG4gIC5jb2wteGwtOSB7XG4gICAgZmxleDogMCAwIDc1JTtcbiAgICBtYXgtd2lkdGg6IDc1JTsgfVxuICAuY29sLXhsLTEwIHtcbiAgICBmbGV4OiAwIDAgODMuMzMzMzMlO1xuICAgIG1heC13aWR0aDogODMuMzMzMzMlOyB9XG4gIC5jb2wteGwtMTEge1xuICAgIGZsZXg6IDAgMCA5MS42NjY2NyU7XG4gICAgbWF4LXdpZHRoOiA5MS42NjY2NyU7IH1cbiAgLmNvbC14bC0xMiB7XG4gICAgZmxleDogMCAwIDEwMCU7XG4gICAgbWF4LXdpZHRoOiAxMDAlOyB9XG4gIC5vcmRlci14bC0xIHtcbiAgICBvcmRlcjogMTsgfVxuICAub3JkZXIteGwtMiB7XG4gICAgb3JkZXI6IDI7IH1cbiAgLm9yZGVyLXhsLTMge1xuICAgIG9yZGVyOiAzOyB9XG4gIC5vcmRlci14bC00IHtcbiAgICBvcmRlcjogNDsgfVxuICAub3JkZXIteGwtNSB7XG4gICAgb3JkZXI6IDU7IH1cbiAgLm9yZGVyLXhsLTYge1xuICAgIG9yZGVyOiA2OyB9XG4gIC5vcmRlci14bC03IHtcbiAgICBvcmRlcjogNzsgfVxuICAub3JkZXIteGwtOCB7XG4gICAgb3JkZXI6IDg7IH1cbiAgLm9yZGVyLXhsLTkge1xuICAgIG9yZGVyOiA5OyB9XG4gIC5vcmRlci14bC0xMCB7XG4gICAgb3JkZXI6IDEwOyB9XG4gIC5vcmRlci14bC0xMSB7XG4gICAgb3JkZXI6IDExOyB9XG4gIC5vcmRlci14bC0xMiB7XG4gICAgb3JkZXI6IDEyOyB9IH1cblxuLnRhYmxlIHtcbiAgd2lkdGg6IDEwMCU7XG4gIG1heC13aWR0aDogMTAwJTtcbiAgbWFyZ2luLWJvdHRvbTogMXJlbTtcbiAgYmFja2dyb3VuZC1jb2xvcjogdHJhbnNwYXJlbnQ7IH1cbiAgLnRhYmxlIHRoLFxuICAudGFibGUgdGQge1xuICAgIHBhZGRpbmc6IDAuNzVyZW07XG4gICAgdmVydGljYWwtYWxpZ246IHRvcDtcbiAgICBib3JkZXItdG9wOiAxcHggc29saWQgI2U5ZWNlZjsgfVxuICAudGFibGUgdGhlYWQgdGgge1xuICAgIHZlcnRpY2FsLWFsaWduOiBib3R0b207XG4gICAgYm9yZGVyLWJvdHRvbTogMnB4IHNvbGlkICNlOWVjZWY7IH1cbiAgLnRhYmxlIHRib2R5ICsgdGJvZHkge1xuICAgIGJvcmRlci10b3A6IDJweCBzb2xpZCAjZTllY2VmOyB9XG4gIC50YWJsZSAudGFibGUge1xuICAgIGJhY2tncm91bmQtY29sb3I6ICNmZmY7IH1cblxuLnRhYmxlLXNtIHRoLFxuLnRhYmxlLXNtIHRkIHtcbiAgcGFkZGluZzogMC4zcmVtOyB9XG5cbi50YWJsZS1ib3JkZXJlZCB7XG4gIGJvcmRlcjogMXB4IHNvbGlkICNlOWVjZWY7IH1cbiAgLnRhYmxlLWJvcmRlcmVkIHRoLFxuICAudGFibGUtYm9yZGVyZWQgdGQge1xuICAgIGJvcmRlcjogMXB4IHNvbGlkICNlOWVjZWY7IH1cbiAgLnRhYmxlLWJvcmRlcmVkIHRoZWFkIHRoLFxuICAudGFibGUtYm9yZGVyZWQgdGhlYWQgdGQge1xuICAgIGJvcmRlci1ib3R0b20td2lkdGg6IDJweDsgfVxuXG4udGFibGUtc3RyaXBlZCB0Ym9keSB0cjpudGgtb2YtdHlwZShvZGQpIHtcbiAgYmFja2dyb3VuZC1jb2xvcjogcmdiYSgwLCAwLCAwLCAwLjA1KTsgfVxuXG4udGFibGUtaG92ZXIgdGJvZHkgdHI6aG92ZXIge1xuICBiYWNrZ3JvdW5kLWNvbG9yOiByZ2JhKDAsIDAsIDAsIDAuMDc1KTsgfVxuXG4udGFibGUtcHJpbWFyeSxcbi50YWJsZS1wcmltYXJ5ID4gdGgsXG4udGFibGUtcHJpbWFyeSA+IHRkIHtcbiAgYmFja2dyb3VuZC1jb2xvcjogI2I4ZGFmZjsgfVxuXG4udGFibGUtaG92ZXIgLnRhYmxlLXByaW1hcnk6aG92ZXIge1xuICBiYWNrZ3JvdW5kLWNvbG9yOiAjOWZjZGZmOyB9XG4gIC50YWJsZS1ob3ZlciAudGFibGUtcHJpbWFyeTpob3ZlciA+IHRkLFxuICAudGFibGUtaG92ZXIgLnRhYmxlLXByaW1hcnk6aG92ZXIgPiB0aCB7XG4gICAgYmFja2dyb3VuZC1jb2xvcjogIzlmY2RmZjsgfVxuXG4udGFibGUtc2Vjb25kYXJ5LFxuLnRhYmxlLXNlY29uZGFyeSA+IHRoLFxuLnRhYmxlLXNlY29uZGFyeSA+IHRkIHtcbiAgYmFja2dyb3VuZC1jb2xvcjogI2RkZGZlMjsgfVxuXG4udGFibGUtaG92ZXIgLnRhYmxlLXNlY29uZGFyeTpob3ZlciB7XG4gIGJhY2tncm91bmQtY29sb3I6ICNjZmQyZDY7IH1cbiAgLnRhYmxlLWhvdmVyIC50YWJsZS1zZWNvbmRhcnk6aG92ZXIgPiB0ZCxcbiAgLnRhYmxlLWhvdmVyIC50YWJsZS1zZWNvbmRhcnk6aG92ZXIgPiB0aCB7XG4gICAgYmFja2dyb3VuZC1jb2xvcjogI2NmZDJkNjsgfVxuXG4udGFibGUtc3VjY2Vzcyxcbi50YWJsZS1zdWNjZXNzID4gdGgsXG4udGFibGUtc3VjY2VzcyA+IHRkIHtcbiAgYmFja2dyb3VuZC1jb2xvcjogI2MzZTZjYjsgfVxuXG4udGFibGUtaG92ZXIgLnRhYmxlLXN1Y2Nlc3M6aG92ZXIge1xuICBiYWNrZ3JvdW5kLWNvbG9yOiAjYjFkZmJiOyB9XG4gIC50YWJsZS1ob3ZlciAudGFibGUtc3VjY2Vzczpob3ZlciA+IHRkLFxuICAudGFibGUtaG92ZXIgLnRhYmxlLXN1Y2Nlc3M6aG92ZXIgPiB0aCB7XG4gICAgYmFja2dyb3VuZC1jb2xvcjogI2IxZGZiYjsgfVxuXG4udGFibGUtaW5mbyxcbi50YWJsZS1pbmZvID4gdGgsXG4udGFibGUtaW5mbyA+IHRkIHtcbiAgYmFja2dyb3VuZC1jb2xvcjogI2JlZTVlYjsgfVxuXG4udGFibGUtaG92ZXIgLnRhYmxlLWluZm86aG92ZXIge1xuICBiYWNrZ3JvdW5kLWNvbG9yOiAjYWJkZGU1OyB9XG4gIC50YWJsZS1ob3ZlciAudGFibGUtaW5mbzpob3ZlciA+IHRkLFxuICAudGFibGUtaG92ZXIgLnRhYmxlLWluZm86aG92ZXIgPiB0aCB7XG4gICAgYmFja2dyb3VuZC1jb2xvcjogI2FiZGRlNTsgfVxuXG4udGFibGUtd2FybmluZyxcbi50YWJsZS13YXJuaW5nID4gdGgsXG4udGFibGUtd2FybmluZyA+IHRkIHtcbiAgYmFja2dyb3VuZC1jb2xvcjogI2ZmZWViYTsgfVxuXG4udGFibGUtaG92ZXIgLnRhYmxlLXdhcm5pbmc6aG92ZXIge1xuICBiYWNrZ3JvdW5kLWNvbG9yOiAjZmZlOGExOyB9XG4gIC50YWJsZS1ob3ZlciAudGFibGUtd2FybmluZzpob3ZlciA+IHRkLFxuICAudGFibGUtaG92ZXIgLnRhYmxlLXdhcm5pbmc6aG92ZXIgPiB0aCB7XG4gICAgYmFja2dyb3VuZC1jb2xvcjogI2ZmZThhMTsgfVxuXG4udGFibGUtZGFuZ2VyLFxuLnRhYmxlLWRhbmdlciA+IHRoLFxuLnRhYmxlLWRhbmdlciA+IHRkIHtcbiAgYmFja2dyb3VuZC1jb2xvcjogI2Y1YzZjYjsgfVxuXG4udGFibGUtaG92ZXIgLnRhYmxlLWRhbmdlcjpob3ZlciB7XG4gIGJhY2tncm91bmQtY29sb3I6ICNmMWIwYjc7IH1cbiAgLnRhYmxlLWhvdmVyIC50YWJsZS1kYW5nZXI6aG92ZXIgPiB0ZCxcbiAgLnRhYmxlLWhvdmVyIC50YWJsZS1kYW5nZXI6aG92ZXIgPiB0aCB7XG4gICAgYmFja2dyb3VuZC1jb2xvcjogI2YxYjBiNzsgfVxuXG4udGFibGUtbGlnaHQsXG4udGFibGUtbGlnaHQgPiB0aCxcbi50YWJsZS1saWdodCA+IHRkIHtcbiAgYmFja2dyb3VuZC1jb2xvcjogI2ZkZmRmZTsgfVxuXG4udGFibGUtaG92ZXIgLnRhYmxlLWxpZ2h0OmhvdmVyIHtcbiAgYmFja2dyb3VuZC1jb2xvcjogI2VjZWNmNjsgfVxuICAudGFibGUtaG92ZXIgLnRhYmxlLWxpZ2h0OmhvdmVyID4gdGQsXG4gIC50YWJsZS1ob3ZlciAudGFibGUtbGlnaHQ6aG92ZXIgPiB0aCB7XG4gICAgYmFja2dyb3VuZC1jb2xvcjogI2VjZWNmNjsgfVxuXG4udGFibGUtZGFyayxcbi50YWJsZS1kYXJrID4gdGgsXG4udGFibGUtZGFyayA+IHRkIHtcbiAgYmFja2dyb3VuZC1jb2xvcjogI2M2YzhjYTsgfVxuXG4udGFibGUtaG92ZXIgLnRhYmxlLWRhcms6aG92ZXIge1xuICBiYWNrZ3JvdW5kLWNvbG9yOiAjYjliYmJlOyB9XG4gIC50YWJsZS1ob3ZlciAudGFibGUtZGFyazpob3ZlciA+IHRkLFxuICAudGFibGUtaG92ZXIgLnRhYmxlLWRhcms6aG92ZXIgPiB0aCB7XG4gICAgYmFja2dyb3VuZC1jb2xvcjogI2I5YmJiZTsgfVxuXG4udGFibGUtYWN0aXZlLFxuLnRhYmxlLWFjdGl2ZSA+IHRoLFxuLnRhYmxlLWFjdGl2ZSA+IHRkIHtcbiAgYmFja2dyb3VuZC1jb2xvcjogcmdiYSgwLCAwLCAwLCAwLjA3NSk7IH1cblxuLnRhYmxlLWhvdmVyIC50YWJsZS1hY3RpdmU6aG92ZXIge1xuICBiYWNrZ3JvdW5kLWNvbG9yOiByZ2JhKDAsIDAsIDAsIDAuMDc1KTsgfVxuICAudGFibGUtaG92ZXIgLnRhYmxlLWFjdGl2ZTpob3ZlciA+IHRkLFxuICAudGFibGUtaG92ZXIgLnRhYmxlLWFjdGl2ZTpob3ZlciA+IHRoIHtcbiAgICBiYWNrZ3JvdW5kLWNvbG9yOiByZ2JhKDAsIDAsIDAsIDAuMDc1KTsgfVxuXG4udGhlYWQtaW52ZXJzZSB0aCB7XG4gIGNvbG9yOiAjZmZmO1xuICBiYWNrZ3JvdW5kLWNvbG9yOiAjMjEyNTI5OyB9XG5cbi50aGVhZC1kZWZhdWx0IHRoIHtcbiAgY29sb3I6ICM0OTUwNTc7XG4gIGJhY2tncm91bmQtY29sb3I6ICNlOWVjZWY7IH1cblxuLnRhYmxlLWludmVyc2Uge1xuICBjb2xvcjogI2ZmZjtcbiAgYmFja2dyb3VuZC1jb2xvcjogIzIxMjUyOTsgfVxuICAudGFibGUtaW52ZXJzZSB0aCxcbiAgLnRhYmxlLWludmVyc2UgdGQsXG4gIC50YWJsZS1pbnZlcnNlIHRoZWFkIHRoIHtcbiAgICBib3JkZXItY29sb3I6ICMzMjM4M2U7IH1cbiAgLnRhYmxlLWludmVyc2UudGFibGUtYm9yZGVyZWQge1xuICAgIGJvcmRlcjogMDsgfVxuICAudGFibGUtaW52ZXJzZS50YWJsZS1zdHJpcGVkIHRib2R5IHRyOm50aC1vZi10eXBlKG9kZCkge1xuICAgIGJhY2tncm91bmQtY29sb3I6IHJnYmEoMjU1LCAyNTUsIDI1NSwgMC4wNSk7IH1cbiAgLnRhYmxlLWludmVyc2UudGFibGUtaG92ZXIgdGJvZHkgdHI6aG92ZXIge1xuICAgIGJhY2tncm91bmQtY29sb3I6IHJnYmEoMjU1LCAyNTUsIDI1NSwgMC4wNzUpOyB9XG5cbkBtZWRpYSAobWF4LXdpZHRoOiA5OTFweCkge1xuICAudGFibGUtcmVzcG9uc2l2ZSB7XG4gICAgZGlzcGxheTogYmxvY2s7XG4gICAgd2lkdGg6IDEwMCU7XG4gICAgb3ZlcmZsb3cteDogYXV0bztcbiAgICAtbXMtb3ZlcmZsb3ctc3R5bGU6IC1tcy1hdXRvaGlkaW5nLXNjcm9sbGJhcjsgfVxuICAgIC50YWJsZS1yZXNwb25zaXZlLnRhYmxlLWJvcmRlcmVkIHtcbiAgICAgIGJvcmRlcjogMDsgfSB9XG5cbi5mb3JtLWNvbnRyb2wge1xuICBkaXNwbGF5OiBibG9jaztcbiAgd2lkdGg6IDEwMCU7XG4gIHBhZGRpbmc6IDAuNXJlbSAwLjc1cmVtO1xuICBmb250LXNpemU6IDFyZW07XG4gIGxpbmUtaGVpZ2h0OiAxLjI1O1xuICBjb2xvcjogIzQ5NTA1NztcbiAgYmFja2dyb3VuZC1jb2xvcjogI2ZmZjtcbiAgYmFja2dyb3VuZC1pbWFnZTogbm9uZTtcbiAgYmFja2dyb3VuZC1jbGlwOiBwYWRkaW5nLWJveDtcbiAgYm9yZGVyOiAxcHggc29saWQgcmdiYSgwLCAwLCAwLCAwLjE1KTtcbiAgYm9yZGVyLXJhZGl1czogMC4yNXJlbTtcbiAgdHJhbnNpdGlvbjogYm9yZGVyLWNvbG9yIGVhc2UtaW4tb3V0IDAuMTVzLCBib3gtc2hhZG93IGVhc2UtaW4tb3V0IDAuMTVzOyB9XG4gIC5mb3JtLWNvbnRyb2w6Oi1tcy1leHBhbmQge1xuICAgIGJhY2tncm91bmQtY29sb3I6IHRyYW5zcGFyZW50O1xuICAgIGJvcmRlcjogMDsgfVxuICAuZm9ybS1jb250cm9sOmZvY3VzIHtcbiAgICBjb2xvcjogIzQ5NTA1NztcbiAgICBiYWNrZ3JvdW5kLWNvbG9yOiAjZmZmO1xuICAgIGJvcmRlci1jb2xvcjogIzgwYmRmZjtcbiAgICBvdXRsaW5lOiBub25lOyB9XG4gIC5mb3JtLWNvbnRyb2w6OnBsYWNlaG9sZGVyIHtcbiAgICBjb2xvcjogIzg2OGU5NjtcbiAgICBvcGFjaXR5OiAxOyB9XG4gIC5mb3JtLWNvbnRyb2w6ZGlzYWJsZWQsIC5mb3JtLWNvbnRyb2xbcmVhZG9ubHldIHtcbiAgICBiYWNrZ3JvdW5kLWNvbG9yOiAjZTllY2VmO1xuICAgIG9wYWNpdHk6IDE7IH1cblxuc2VsZWN0LmZvcm0tY29udHJvbDpub3QoW3NpemVdKTpub3QoW211bHRpcGxlXSkge1xuICBoZWlnaHQ6IGNhbGMoMi4yNXJlbSArIDJweCk7IH1cblxuc2VsZWN0LmZvcm0tY29udHJvbDpmb2N1czo6LW1zLXZhbHVlIHtcbiAgY29sb3I6ICM0OTUwNTc7XG4gIGJhY2tncm91bmQtY29sb3I6ICNmZmY7IH1cblxuLmZvcm0tY29udHJvbC1maWxlLFxuLmZvcm0tY29udHJvbC1yYW5nZSB7XG4gIGRpc3BsYXk6IGJsb2NrOyB9XG5cbi5jb2wtZm9ybS1sYWJlbCB7XG4gIHBhZGRpbmctdG9wOiBjYWxjKDAuNXJlbSAtIDFweCAqIDIpO1xuICBwYWRkaW5nLWJvdHRvbTogY2FsYygwLjVyZW0gLSAxcHggKiAyKTtcbiAgbWFyZ2luLWJvdHRvbTogMDsgfVxuXG4uY29sLWZvcm0tbGFiZWwtbGcge1xuICBwYWRkaW5nLXRvcDogY2FsYygwLjVyZW0gLSAxcHggKiAyKTtcbiAgcGFkZGluZy1ib3R0b206IGNhbGMoMC41cmVtIC0gMXB4ICogMik7XG4gIGZvbnQtc2l6ZTogMS4yNXJlbTsgfVxuXG4uY29sLWZvcm0tbGFiZWwtc20ge1xuICBwYWRkaW5nLXRvcDogY2FsYygwLjI1cmVtIC0gMXB4ICogMik7XG4gIHBhZGRpbmctYm90dG9tOiBjYWxjKDAuMjVyZW0gLSAxcHggKiAyKTtcbiAgZm9udC1zaXplOiAwLjg3NXJlbTsgfVxuXG4uY29sLWZvcm0tbGVnZW5kIHtcbiAgcGFkZGluZy10b3A6IDAuNXJlbTtcbiAgcGFkZGluZy1ib3R0b206IDAuNXJlbTtcbiAgbWFyZ2luLWJvdHRvbTogMDtcbiAgZm9udC1zaXplOiAxcmVtOyB9XG5cbi5mb3JtLWNvbnRyb2wtcGxhaW50ZXh0IHtcbiAgcGFkZGluZy10b3A6IDAuNXJlbTtcbiAgcGFkZGluZy1ib3R0b206IDAuNXJlbTtcbiAgbWFyZ2luLWJvdHRvbTogMDtcbiAgbGluZS1oZWlnaHQ6IDEuMjU7XG4gIGJvcmRlcjogc29saWQgdHJhbnNwYXJlbnQ7XG4gIGJvcmRlci13aWR0aDogMXB4IDA7IH1cbiAgLmZvcm0tY29udHJvbC1wbGFpbnRleHQuZm9ybS1jb250cm9sLXNtLCAuaW5wdXQtZ3JvdXAtc20gPiAuZm9ybS1jb250cm9sLXBsYWludGV4dC5mb3JtLWNvbnRyb2wsXG4gIC5pbnB1dC1ncm91cC1zbSA+IC5mb3JtLWNvbnRyb2wtcGxhaW50ZXh0LmlucHV0LWdyb3VwLWFkZG9uLFxuICAuaW5wdXQtZ3JvdXAtc20gPiAuaW5wdXQtZ3JvdXAtYnRuID4gLmZvcm0tY29udHJvbC1wbGFpbnRleHQuYnRuLFxuICAuaW5wdXQtZ3JvdXAtc20gPiAuaW5wdXQtZ3JvdXAtYnRuID4gYnV0dG9uLmZvcm0tY29udHJvbC1wbGFpbnRleHQuY3VzdG9tLCAuZm9ybS1jb250cm9sLXBsYWludGV4dC5mb3JtLWNvbnRyb2wtbGcsIC5pbnB1dC1ncm91cC1sZyA+IC5mb3JtLWNvbnRyb2wtcGxhaW50ZXh0LmZvcm0tY29udHJvbCxcbiAgLmlucHV0LWdyb3VwLWxnID4gLmZvcm0tY29udHJvbC1wbGFpbnRleHQuaW5wdXQtZ3JvdXAtYWRkb24sXG4gIC5pbnB1dC1ncm91cC1sZyA+IC5pbnB1dC1ncm91cC1idG4gPiAuZm9ybS1jb250cm9sLXBsYWludGV4dC5idG4sXG4gIC5pbnB1dC1ncm91cC1sZyA+IC5pbnB1dC1ncm91cC1idG4gPiBidXR0b24uZm9ybS1jb250cm9sLXBsYWludGV4dC5jdXN0b20ge1xuICAgIHBhZGRpbmctcmlnaHQ6IDA7XG4gICAgcGFkZGluZy1sZWZ0OiAwOyB9XG5cbi5mb3JtLWNvbnRyb2wtc20sIC5pbnB1dC1ncm91cC1zbSA+IC5mb3JtLWNvbnRyb2wsXG4uaW5wdXQtZ3JvdXAtc20gPiAuaW5wdXQtZ3JvdXAtYWRkb24sXG4uaW5wdXQtZ3JvdXAtc20gPiAuaW5wdXQtZ3JvdXAtYnRuID4gLmJ0bixcbi5pbnB1dC1ncm91cC1zbSA+IC5pbnB1dC1ncm91cC1idG4gPiBidXR0b24uY3VzdG9tIHtcbiAgcGFkZGluZzogMC4yNXJlbSAwLjVyZW07XG4gIGZvbnQtc2l6ZTogMC44NzVyZW07XG4gIGxpbmUtaGVpZ2h0OiAxLjU7XG4gIGJvcmRlci1yYWRpdXM6IDAuMnJlbTsgfVxuXG5zZWxlY3QuZm9ybS1jb250cm9sLXNtOm5vdChbc2l6ZV0pOm5vdChbbXVsdGlwbGVdKSwgLmlucHV0LWdyb3VwLXNtID4gc2VsZWN0LmZvcm0tY29udHJvbDpub3QoW3NpemVdKTpub3QoW211bHRpcGxlXSksXG4uaW5wdXQtZ3JvdXAtc20gPiBzZWxlY3QuaW5wdXQtZ3JvdXAtYWRkb246bm90KFtzaXplXSk6bm90KFttdWx0aXBsZV0pLFxuLmlucHV0LWdyb3VwLXNtID4gLmlucHV0LWdyb3VwLWJ0biA+IHNlbGVjdC5idG46bm90KFtzaXplXSk6bm90KFttdWx0aXBsZV0pIHtcbiAgaGVpZ2h0OiBjYWxjKDEuODEyNXJlbSArIDJweCk7IH1cblxuLmZvcm0tY29udHJvbC1sZywgLmlucHV0LWdyb3VwLWxnID4gLmZvcm0tY29udHJvbCxcbi5pbnB1dC1ncm91cC1sZyA+IC5pbnB1dC1ncm91cC1hZGRvbixcbi5pbnB1dC1ncm91cC1sZyA+IC5pbnB1dC1ncm91cC1idG4gPiAuYnRuLFxuLmlucHV0LWdyb3VwLWxnID4gLmlucHV0LWdyb3VwLWJ0biA+IGJ1dHRvbi5jdXN0b20ge1xuICBwYWRkaW5nOiAwLjVyZW0gMXJlbTtcbiAgZm9udC1zaXplOiAxLjI1cmVtO1xuICBsaW5lLWhlaWdodDogMS41O1xuICBib3JkZXItcmFkaXVzOiAwLjNyZW07IH1cblxuc2VsZWN0LmZvcm0tY29udHJvbC1sZzpub3QoW3NpemVdKTpub3QoW211bHRpcGxlXSksIC5pbnB1dC1ncm91cC1sZyA+IHNlbGVjdC5mb3JtLWNvbnRyb2w6bm90KFtzaXplXSk6bm90KFttdWx0aXBsZV0pLFxuLmlucHV0LWdyb3VwLWxnID4gc2VsZWN0LmlucHV0LWdyb3VwLWFkZG9uOm5vdChbc2l6ZV0pOm5vdChbbXVsdGlwbGVdKSxcbi5pbnB1dC1ncm91cC1sZyA+IC5pbnB1dC1ncm91cC1idG4gPiBzZWxlY3QuYnRuOm5vdChbc2l6ZV0pOm5vdChbbXVsdGlwbGVdKSB7XG4gIGhlaWdodDogY2FsYygyLjg3NXJlbSArIDJweCk7IH1cblxuLmZvcm0tZ3JvdXAge1xuICBtYXJnaW4tYm90dG9tOiAxcmVtOyB9XG5cbi5mb3JtLXRleHQge1xuICBkaXNwbGF5OiBibG9jaztcbiAgbWFyZ2luLXRvcDogMC4yNXJlbTsgfVxuXG4uZm9ybS1yb3cge1xuICBkaXNwbGF5OiBmbGV4O1xuICBmbGV4LXdyYXA6IHdyYXA7XG4gIG1hcmdpbi1yaWdodDogLTVweDtcbiAgbWFyZ2luLWxlZnQ6IC01cHg7IH1cbiAgLmZvcm0tcm93ID4gLmNvbCxcbiAgLmZvcm0tcm93ID4gW2NsYXNzKj1cImNvbC1cIl0ge1xuICAgIHBhZGRpbmctcmlnaHQ6IDVweDtcbiAgICBwYWRkaW5nLWxlZnQ6IDVweDsgfVxuXG4uZm9ybS1jaGVjayB7XG4gIHBvc2l0aW9uOiByZWxhdGl2ZTtcbiAgZGlzcGxheTogYmxvY2s7XG4gIG1hcmdpbi1ib3R0b206IDAuNXJlbTsgfVxuICAuZm9ybS1jaGVjay5kaXNhYmxlZCAuZm9ybS1jaGVjay1sYWJlbCB7XG4gICAgY29sb3I6ICM4NjhlOTY7IH1cblxuLmZvcm0tY2hlY2stbGFiZWwge1xuICBwYWRkaW5nLWxlZnQ6IDEuMjVyZW07XG4gIG1hcmdpbi1ib3R0b206IDA7IH1cblxuLmZvcm0tY2hlY2staW5wdXQge1xuICBwb3NpdGlvbjogYWJzb2x1dGU7XG4gIG1hcmdpbi10b3A6IDAuMjVyZW07XG4gIG1hcmdpbi1sZWZ0OiAtMS4yNXJlbTsgfVxuXG4uZm9ybS1jaGVjay1pbmxpbmUge1xuICBkaXNwbGF5OiBpbmxpbmUtYmxvY2s7IH1cbiAgLmZvcm0tY2hlY2staW5saW5lIC5mb3JtLWNoZWNrLWxhYmVsIHtcbiAgICB2ZXJ0aWNhbC1hbGlnbjogbWlkZGxlOyB9XG4gIC5mb3JtLWNoZWNrLWlubGluZSArIC5mb3JtLWNoZWNrLWlubGluZSB7XG4gICAgbWFyZ2luLWxlZnQ6IDAuNzVyZW07IH1cblxuLmludmFsaWQtZmVlZGJhY2sge1xuICBkaXNwbGF5OiBub25lO1xuICBtYXJnaW4tdG9wOiAuMjVyZW07XG4gIGZvbnQtc2l6ZTogLjg3NXJlbTtcbiAgY29sb3I6ICNkYzM1NDU7IH1cblxuLmludmFsaWQtdG9vbHRpcCB7XG4gIHBvc2l0aW9uOiBhYnNvbHV0ZTtcbiAgdG9wOiAxMDAlO1xuICB6LWluZGV4OiA1O1xuICBkaXNwbGF5OiBub25lO1xuICB3aWR0aDogMjUwcHg7XG4gIHBhZGRpbmc6IC41cmVtO1xuICBtYXJnaW4tdG9wOiAuMXJlbTtcbiAgZm9udC1zaXplOiAuODc1cmVtO1xuICBsaW5lLWhlaWdodDogMTtcbiAgY29sb3I6ICNmZmY7XG4gIGJhY2tncm91bmQtY29sb3I6IHJnYmEoMjIwLCA1MywgNjksIDAuOCk7XG4gIGJvcmRlci1yYWRpdXM6IC4ycmVtOyB9XG5cbi53YXMtdmFsaWRhdGVkIC5mb3JtLWNvbnRyb2w6dmFsaWQsIC5mb3JtLWNvbnRyb2wuaXMtdmFsaWQsIC53YXMtdmFsaWRhdGVkXG4uY3VzdG9tLXNlbGVjdDp2YWxpZCxcbi5jdXN0b20tc2VsZWN0LmlzLXZhbGlkIHtcbiAgYm9yZGVyLWNvbG9yOiAjMjhhNzQ1OyB9XG4gIC53YXMtdmFsaWRhdGVkIC5mb3JtLWNvbnRyb2w6dmFsaWQ6Zm9jdXMsIC5mb3JtLWNvbnRyb2wuaXMtdmFsaWQ6Zm9jdXMsIC53YXMtdmFsaWRhdGVkXG4gIC5jdXN0b20tc2VsZWN0OnZhbGlkOmZvY3VzLFxuICAuY3VzdG9tLXNlbGVjdC5pcy12YWxpZDpmb2N1cyB7XG4gICAgYm94LXNoYWRvdzogMCAwIDAgMC4ycmVtIHJnYmEoNDAsIDE2NywgNjksIDAuMjUpOyB9XG4gIC53YXMtdmFsaWRhdGVkIC5mb3JtLWNvbnRyb2w6dmFsaWQgfiAuaW52YWxpZC1mZWVkYmFjayxcbiAgLndhcy12YWxpZGF0ZWQgLmZvcm0tY29udHJvbDp2YWxpZCB+IC5pbnZhbGlkLXRvb2x0aXAsIC5mb3JtLWNvbnRyb2wuaXMtdmFsaWQgfiAuaW52YWxpZC1mZWVkYmFjayxcbiAgLmZvcm0tY29udHJvbC5pcy12YWxpZCB+IC5pbnZhbGlkLXRvb2x0aXAsIC53YXMtdmFsaWRhdGVkXG4gIC5jdXN0b20tc2VsZWN0OnZhbGlkIH4gLmludmFsaWQtZmVlZGJhY2ssXG4gIC53YXMtdmFsaWRhdGVkXG4gIC5jdXN0b20tc2VsZWN0OnZhbGlkIH4gLmludmFsaWQtdG9vbHRpcCxcbiAgLmN1c3RvbS1zZWxlY3QuaXMtdmFsaWQgfiAuaW52YWxpZC1mZWVkYmFjayxcbiAgLmN1c3RvbS1zZWxlY3QuaXMtdmFsaWQgfiAuaW52YWxpZC10b29sdGlwIHtcbiAgICBkaXNwbGF5OiBibG9jazsgfVxuXG4ud2FzLXZhbGlkYXRlZCAuZm9ybS1jaGVjay1pbnB1dDp2YWxpZCArIC5mb3JtLWNoZWNrLWxhYmVsLCAuZm9ybS1jaGVjay1pbnB1dC5pcy12YWxpZCArIC5mb3JtLWNoZWNrLWxhYmVsIHtcbiAgY29sb3I6ICMyOGE3NDU7IH1cblxuLndhcy12YWxpZGF0ZWQgLmN1c3RvbS1jb250cm9sLWlucHV0OnZhbGlkIH4gLmN1c3RvbS1jb250cm9sLWluZGljYXRvciwgLmN1c3RvbS1jb250cm9sLWlucHV0LmlzLXZhbGlkIH4gLmN1c3RvbS1jb250cm9sLWluZGljYXRvciB7XG4gIGJhY2tncm91bmQtY29sb3I6IHJnYmEoNDAsIDE2NywgNjksIDAuMjUpOyB9XG5cbi53YXMtdmFsaWRhdGVkIC5jdXN0b20tY29udHJvbC1pbnB1dDp2YWxpZCB+IC5jdXN0b20tY29udHJvbC1kZXNjcmlwdGlvbiwgLmN1c3RvbS1jb250cm9sLWlucHV0LmlzLXZhbGlkIH4gLmN1c3RvbS1jb250cm9sLWRlc2NyaXB0aW9uIHtcbiAgY29sb3I6ICMyOGE3NDU7IH1cblxuLndhcy12YWxpZGF0ZWQgLmN1c3RvbS1maWxlLWlucHV0OnZhbGlkIH4gLmN1c3RvbS1maWxlLWNvbnRyb2wsIC5jdXN0b20tZmlsZS1pbnB1dC5pcy12YWxpZCB+IC5jdXN0b20tZmlsZS1jb250cm9sIHtcbiAgYm9yZGVyLWNvbG9yOiAjMjhhNzQ1OyB9XG4gIC53YXMtdmFsaWRhdGVkIC5jdXN0b20tZmlsZS1pbnB1dDp2YWxpZCB+IC5jdXN0b20tZmlsZS1jb250cm9sOjpiZWZvcmUsIC5jdXN0b20tZmlsZS1pbnB1dC5pcy12YWxpZCB+IC5jdXN0b20tZmlsZS1jb250cm9sOjpiZWZvcmUge1xuICAgIGJvcmRlci1jb2xvcjogaW5oZXJpdDsgfVxuXG4ud2FzLXZhbGlkYXRlZCAuY3VzdG9tLWZpbGUtaW5wdXQ6dmFsaWQ6Zm9jdXMsIC5jdXN0b20tZmlsZS1pbnB1dC5pcy12YWxpZDpmb2N1cyB7XG4gIGJveC1zaGFkb3c6IDAgMCAwIDAuMnJlbSByZ2JhKDQwLCAxNjcsIDY5LCAwLjI1KTsgfVxuXG4ud2FzLXZhbGlkYXRlZCAuZm9ybS1jb250cm9sOmludmFsaWQsIC5mb3JtLWNvbnRyb2wuaXMtaW52YWxpZCwgLndhcy12YWxpZGF0ZWRcbi5jdXN0b20tc2VsZWN0OmludmFsaWQsXG4uY3VzdG9tLXNlbGVjdC5pcy1pbnZhbGlkIHtcbiAgYm9yZGVyLWNvbG9yOiAjZGMzNTQ1OyB9XG4gIC53YXMtdmFsaWRhdGVkIC5mb3JtLWNvbnRyb2w6aW52YWxpZDpmb2N1cywgLmZvcm0tY29udHJvbC5pcy1pbnZhbGlkOmZvY3VzLCAud2FzLXZhbGlkYXRlZFxuICAuY3VzdG9tLXNlbGVjdDppbnZhbGlkOmZvY3VzLFxuICAuY3VzdG9tLXNlbGVjdC5pcy1pbnZhbGlkOmZvY3VzIHtcbiAgICBib3gtc2hhZG93OiAwIDAgMCAwLjJyZW0gcmdiYSgyMjAsIDUzLCA2OSwgMC4yNSk7IH1cbiAgLndhcy12YWxpZGF0ZWQgLmZvcm0tY29udHJvbDppbnZhbGlkIH4gLmludmFsaWQtZmVlZGJhY2ssXG4gIC53YXMtdmFsaWRhdGVkIC5mb3JtLWNvbnRyb2w6aW52YWxpZCB+IC5pbnZhbGlkLXRvb2x0aXAsIC5mb3JtLWNvbnRyb2wuaXMtaW52YWxpZCB+IC5pbnZhbGlkLWZlZWRiYWNrLFxuICAuZm9ybS1jb250cm9sLmlzLWludmFsaWQgfiAuaW52YWxpZC10b29sdGlwLCAud2FzLXZhbGlkYXRlZFxuICAuY3VzdG9tLXNlbGVjdDppbnZhbGlkIH4gLmludmFsaWQtZmVlZGJhY2ssXG4gIC53YXMtdmFsaWRhdGVkXG4gIC5jdXN0b20tc2VsZWN0OmludmFsaWQgfiAuaW52YWxpZC10b29sdGlwLFxuICAuY3VzdG9tLXNlbGVjdC5pcy1pbnZhbGlkIH4gLmludmFsaWQtZmVlZGJhY2ssXG4gIC5jdXN0b20tc2VsZWN0LmlzLWludmFsaWQgfiAuaW52YWxpZC10b29sdGlwIHtcbiAgICBkaXNwbGF5OiBibG9jazsgfVxuXG4ud2FzLXZhbGlkYXRlZCAuZm9ybS1jaGVjay1pbnB1dDppbnZhbGlkICsgLmZvcm0tY2hlY2stbGFiZWwsIC5mb3JtLWNoZWNrLWlucHV0LmlzLWludmFsaWQgKyAuZm9ybS1jaGVjay1sYWJlbCB7XG4gIGNvbG9yOiAjZGMzNTQ1OyB9XG5cbi53YXMtdmFsaWRhdGVkIC5jdXN0b20tY29udHJvbC1pbnB1dDppbnZhbGlkIH4gLmN1c3RvbS1jb250cm9sLWluZGljYXRvciwgLmN1c3RvbS1jb250cm9sLWlucHV0LmlzLWludmFsaWQgfiAuY3VzdG9tLWNvbnRyb2wtaW5kaWNhdG9yIHtcbiAgYmFja2dyb3VuZC1jb2xvcjogcmdiYSgyMjAsIDUzLCA2OSwgMC4yNSk7IH1cblxuLndhcy12YWxpZGF0ZWQgLmN1c3RvbS1jb250cm9sLWlucHV0OmludmFsaWQgfiAuY3VzdG9tLWNvbnRyb2wtZGVzY3JpcHRpb24sIC5jdXN0b20tY29udHJvbC1pbnB1dC5pcy1pbnZhbGlkIH4gLmN1c3RvbS1jb250cm9sLWRlc2NyaXB0aW9uIHtcbiAgY29sb3I6ICNkYzM1NDU7IH1cblxuLndhcy12YWxpZGF0ZWQgLmN1c3RvbS1maWxlLWlucHV0OmludmFsaWQgfiAuY3VzdG9tLWZpbGUtY29udHJvbCwgLmN1c3RvbS1maWxlLWlucHV0LmlzLWludmFsaWQgfiAuY3VzdG9tLWZpbGUtY29udHJvbCB7XG4gIGJvcmRlci1jb2xvcjogI2RjMzU0NTsgfVxuICAud2FzLXZhbGlkYXRlZCAuY3VzdG9tLWZpbGUtaW5wdXQ6aW52YWxpZCB+IC5jdXN0b20tZmlsZS1jb250cm9sOjpiZWZvcmUsIC5jdXN0b20tZmlsZS1pbnB1dC5pcy1pbnZhbGlkIH4gLmN1c3RvbS1maWxlLWNvbnRyb2w6OmJlZm9yZSB7XG4gICAgYm9yZGVyLWNvbG9yOiBpbmhlcml0OyB9XG5cbi53YXMtdmFsaWRhdGVkIC5jdXN0b20tZmlsZS1pbnB1dDppbnZhbGlkOmZvY3VzLCAuY3VzdG9tLWZpbGUtaW5wdXQuaXMtaW52YWxpZDpmb2N1cyB7XG4gIGJveC1zaGFkb3c6IDAgMCAwIDAuMnJlbSByZ2JhKDIyMCwgNTMsIDY5LCAwLjI1KTsgfVxuXG4uZm9ybS1pbmxpbmUge1xuICBkaXNwbGF5OiBmbGV4O1xuICBmbGV4LWZsb3c6IHJvdyB3cmFwO1xuICBhbGlnbi1pdGVtczogY2VudGVyOyB9XG4gIC5mb3JtLWlubGluZSAuZm9ybS1jaGVjayB7XG4gICAgd2lkdGg6IDEwMCU7IH1cbiAgQG1lZGlhIChtaW4td2lkdGg6IDU3NnB4KSB7XG4gICAgLmZvcm0taW5saW5lIGxhYmVsIHtcbiAgICAgIGRpc3BsYXk6IGZsZXg7XG4gICAgICBhbGlnbi1pdGVtczogY2VudGVyO1xuICAgICAganVzdGlmeS1jb250ZW50OiBjZW50ZXI7XG4gICAgICBtYXJnaW4tYm90dG9tOiAwOyB9XG4gICAgLmZvcm0taW5saW5lIC5mb3JtLWdyb3VwIHtcbiAgICAgIGRpc3BsYXk6IGZsZXg7XG4gICAgICBmbGV4OiAwIDAgYXV0bztcbiAgICAgIGZsZXgtZmxvdzogcm93IHdyYXA7XG4gICAgICBhbGlnbi1pdGVtczogY2VudGVyO1xuICAgICAgbWFyZ2luLWJvdHRvbTogMDsgfVxuICAgIC5mb3JtLWlubGluZSAuZm9ybS1jb250cm9sIHtcbiAgICAgIGRpc3BsYXk6IGlubGluZS1ibG9jaztcbiAgICAgIHdpZHRoOiBhdXRvO1xuICAgICAgdmVydGljYWwtYWxpZ246IG1pZGRsZTsgfVxuICAgIC5mb3JtLWlubGluZSAuZm9ybS1jb250cm9sLXBsYWludGV4dCB7XG4gICAgICBkaXNwbGF5OiBpbmxpbmUtYmxvY2s7IH1cbiAgICAuZm9ybS1pbmxpbmUgLmlucHV0LWdyb3VwIHtcbiAgICAgIHdpZHRoOiBhdXRvOyB9XG4gICAgLmZvcm0taW5saW5lIC5mb3JtLWNvbnRyb2wtbGFiZWwge1xuICAgICAgbWFyZ2luLWJvdHRvbTogMDtcbiAgICAgIHZlcnRpY2FsLWFsaWduOiBtaWRkbGU7IH1cbiAgICAuZm9ybS1pbmxpbmUgLmZvcm0tY2hlY2sge1xuICAgICAgZGlzcGxheTogZmxleDtcbiAgICAgIGFsaWduLWl0ZW1zOiBjZW50ZXI7XG4gICAgICBqdXN0aWZ5LWNvbnRlbnQ6IGNlbnRlcjtcbiAgICAgIHdpZHRoOiBhdXRvO1xuICAgICAgbWFyZ2luLXRvcDogMDtcbiAgICAgIG1hcmdpbi1ib3R0b206IDA7IH1cbiAgICAuZm9ybS1pbmxpbmUgLmZvcm0tY2hlY2stbGFiZWwge1xuICAgICAgcGFkZGluZy1sZWZ0OiAwOyB9XG4gICAgLmZvcm0taW5saW5lIC5mb3JtLWNoZWNrLWlucHV0IHtcbiAgICAgIHBvc2l0aW9uOiByZWxhdGl2ZTtcbiAgICAgIG1hcmdpbi10b3A6IDA7XG4gICAgICBtYXJnaW4tcmlnaHQ6IDAuMjVyZW07XG4gICAgICBtYXJnaW4tbGVmdDogMDsgfVxuICAgIC5mb3JtLWlubGluZSAuY3VzdG9tLWNvbnRyb2wge1xuICAgICAgZGlzcGxheTogZmxleDtcbiAgICAgIGFsaWduLWl0ZW1zOiBjZW50ZXI7XG4gICAgICBqdXN0aWZ5LWNvbnRlbnQ6IGNlbnRlcjtcbiAgICAgIHBhZGRpbmctbGVmdDogMDsgfVxuICAgIC5mb3JtLWlubGluZSAuY3VzdG9tLWNvbnRyb2wtaW5kaWNhdG9yIHtcbiAgICAgIHBvc2l0aW9uOiBzdGF0aWM7XG4gICAgICBkaXNwbGF5OiBpbmxpbmUtYmxvY2s7XG4gICAgICBtYXJnaW4tcmlnaHQ6IDAuMjVyZW07XG4gICAgICB2ZXJ0aWNhbC1hbGlnbjogdGV4dC1ib3R0b207IH1cbiAgICAuZm9ybS1pbmxpbmUgLmhhcy1mZWVkYmFjayAuZm9ybS1jb250cm9sLWZlZWRiYWNrIHtcbiAgICAgIHRvcDogMDsgfSB9XG5cbi5idG4sIGJ1dHRvbi5jdXN0b20ge1xuICBkaXNwbGF5OiBpbmxpbmUtYmxvY2s7XG4gIGZvbnQtd2VpZ2h0OiBub3JtYWw7XG4gIHRleHQtYWxpZ246IGNlbnRlcjtcbiAgd2hpdGUtc3BhY2U6IG5vd3JhcDtcbiAgdmVydGljYWwtYWxpZ246IG1pZGRsZTtcbiAgdXNlci1zZWxlY3Q6IG5vbmU7XG4gIGJvcmRlcjogMXB4IHNvbGlkIHRyYW5zcGFyZW50O1xuICBwYWRkaW5nOiAwLjVyZW0gMC43NXJlbTtcbiAgZm9udC1zaXplOiAxcmVtO1xuICBsaW5lLWhlaWdodDogMS4yNTtcbiAgYm9yZGVyLXJhZGl1czogMC4yNXJlbTtcbiAgdHJhbnNpdGlvbjogYmFja2dyb3VuZC1jb2xvciAwLjE1cyBlYXNlLWluLW91dCwgYm9yZGVyLWNvbG9yIDAuMTVzIGVhc2UtaW4tb3V0LCBib3gtc2hhZG93IDAuMTVzIGVhc2UtaW4tb3V0OyB9XG4gIC5idG46Zm9jdXMsIGJ1dHRvbi5jdXN0b206Zm9jdXMsIC5idG46aG92ZXIsIGJ1dHRvbi5jdXN0b206aG92ZXIge1xuICAgIHRleHQtZGVjb3JhdGlvbjogbm9uZTsgfVxuICAuYnRuOmZvY3VzLCBidXR0b24uY3VzdG9tOmZvY3VzLCAuYnRuLmZvY3VzLCBidXR0b24uZm9jdXMuY3VzdG9tIHtcbiAgICBvdXRsaW5lOiAwO1xuICAgIGJveC1zaGFkb3c6IDAgMCAwIDNweCByZ2JhKDAsIDEyMywgMjU1LCAwLjI1KTsgfVxuICAuYnRuLmRpc2FibGVkLCBidXR0b24uZGlzYWJsZWQuY3VzdG9tLCAuYnRuOmRpc2FibGVkLCBidXR0b24uY3VzdG9tOmRpc2FibGVkIHtcbiAgICBvcGFjaXR5OiAuNjU7IH1cbiAgLmJ0bjphY3RpdmUsIGJ1dHRvbi5jdXN0b206YWN0aXZlLCAuYnRuLmFjdGl2ZSwgYnV0dG9uLmFjdGl2ZS5jdXN0b20ge1xuICAgIGJhY2tncm91bmQtaW1hZ2U6IG5vbmU7IH1cblxuYS5idG4uZGlzYWJsZWQsXG5maWVsZHNldFtkaXNhYmxlZF0gYS5idG4ge1xuICBwb2ludGVyLWV2ZW50czogbm9uZTsgfVxuXG4uYnRuLXByaW1hcnkge1xuICBjb2xvcjogI2ZmZjtcbiAgYmFja2dyb3VuZC1jb2xvcjogIzAwN2JmZjtcbiAgYm9yZGVyLWNvbG9yOiAjMDA3YmZmOyB9XG4gIC5idG4tcHJpbWFyeTpob3ZlciB7XG4gICAgY29sb3I6ICNmZmY7XG4gICAgYmFja2dyb3VuZC1jb2xvcjogIzAwNjlkOTtcbiAgICBib3JkZXItY29sb3I6ICMwMDYyY2M7IH1cbiAgLmJ0bi1wcmltYXJ5OmZvY3VzLCAuYnRuLXByaW1hcnkuZm9jdXMge1xuICAgIGJveC1zaGFkb3c6IDAgMCAwIDNweCByZ2JhKDAsIDEyMywgMjU1LCAwLjUpOyB9XG4gIC5idG4tcHJpbWFyeS5kaXNhYmxlZCwgLmJ0bi1wcmltYXJ5OmRpc2FibGVkIHtcbiAgICBiYWNrZ3JvdW5kLWNvbG9yOiAjMDA3YmZmO1xuICAgIGJvcmRlci1jb2xvcjogIzAwN2JmZjsgfVxuICAuYnRuLXByaW1hcnk6YWN0aXZlLCAuYnRuLXByaW1hcnkuYWN0aXZlLFxuICAuc2hvdyA+IC5idG4tcHJpbWFyeS5kcm9wZG93bi10b2dnbGUge1xuICAgIGJhY2tncm91bmQtY29sb3I6ICMwMDY5ZDk7XG4gICAgYmFja2dyb3VuZC1pbWFnZTogbm9uZTtcbiAgICBib3JkZXItY29sb3I6ICMwMDYyY2M7IH1cblxuLmJ0bi1zZWNvbmRhcnkge1xuICBjb2xvcjogI2ZmZjtcbiAgYmFja2dyb3VuZC1jb2xvcjogIzg2OGU5NjtcbiAgYm9yZGVyLWNvbG9yOiAjODY4ZTk2OyB9XG4gIC5idG4tc2Vjb25kYXJ5OmhvdmVyIHtcbiAgICBjb2xvcjogI2ZmZjtcbiAgICBiYWNrZ3JvdW5kLWNvbG9yOiAjNzI3Yjg0O1xuICAgIGJvcmRlci1jb2xvcjogIzZjNzU3ZDsgfVxuICAuYnRuLXNlY29uZGFyeTpmb2N1cywgLmJ0bi1zZWNvbmRhcnkuZm9jdXMge1xuICAgIGJveC1zaGFkb3c6IDAgMCAwIDNweCByZ2JhKDEzNCwgMTQyLCAxNTAsIDAuNSk7IH1cbiAgLmJ0bi1zZWNvbmRhcnkuZGlzYWJsZWQsIC5idG4tc2Vjb25kYXJ5OmRpc2FibGVkIHtcbiAgICBiYWNrZ3JvdW5kLWNvbG9yOiAjODY4ZTk2O1xuICAgIGJvcmRlci1jb2xvcjogIzg2OGU5NjsgfVxuICAuYnRuLXNlY29uZGFyeTphY3RpdmUsIC5idG4tc2Vjb25kYXJ5LmFjdGl2ZSxcbiAgLnNob3cgPiAuYnRuLXNlY29uZGFyeS5kcm9wZG93bi10b2dnbGUge1xuICAgIGJhY2tncm91bmQtY29sb3I6ICM3MjdiODQ7XG4gICAgYmFja2dyb3VuZC1pbWFnZTogbm9uZTtcbiAgICBib3JkZXItY29sb3I6ICM2Yzc1N2Q7IH1cblxuLmJ0bi1zdWNjZXNzIHtcbiAgY29sb3I6ICNmZmY7XG4gIGJhY2tncm91bmQtY29sb3I6ICMyOGE3NDU7XG4gIGJvcmRlci1jb2xvcjogIzI4YTc0NTsgfVxuICAuYnRuLXN1Y2Nlc3M6aG92ZXIge1xuICAgIGNvbG9yOiAjZmZmO1xuICAgIGJhY2tncm91bmQtY29sb3I6ICMyMTg4Mzg7XG4gICAgYm9yZGVyLWNvbG9yOiAjMWU3ZTM0OyB9XG4gIC5idG4tc3VjY2Vzczpmb2N1cywgLmJ0bi1zdWNjZXNzLmZvY3VzIHtcbiAgICBib3gtc2hhZG93OiAwIDAgMCAzcHggcmdiYSg0MCwgMTY3LCA2OSwgMC41KTsgfVxuICAuYnRuLXN1Y2Nlc3MuZGlzYWJsZWQsIC5idG4tc3VjY2VzczpkaXNhYmxlZCB7XG4gICAgYmFja2dyb3VuZC1jb2xvcjogIzI4YTc0NTtcbiAgICBib3JkZXItY29sb3I6ICMyOGE3NDU7IH1cbiAgLmJ0bi1zdWNjZXNzOmFjdGl2ZSwgLmJ0bi1zdWNjZXNzLmFjdGl2ZSxcbiAgLnNob3cgPiAuYnRuLXN1Y2Nlc3MuZHJvcGRvd24tdG9nZ2xlIHtcbiAgICBiYWNrZ3JvdW5kLWNvbG9yOiAjMjE4ODM4O1xuICAgIGJhY2tncm91bmQtaW1hZ2U6IG5vbmU7XG4gICAgYm9yZGVyLWNvbG9yOiAjMWU3ZTM0OyB9XG5cbi5idG4taW5mbyB7XG4gIGNvbG9yOiAjZmZmO1xuICBiYWNrZ3JvdW5kLWNvbG9yOiAjMTdhMmI4O1xuICBib3JkZXItY29sb3I6ICMxN2EyYjg7IH1cbiAgLmJ0bi1pbmZvOmhvdmVyIHtcbiAgICBjb2xvcjogI2ZmZjtcbiAgICBiYWNrZ3JvdW5kLWNvbG9yOiAjMTM4NDk2O1xuICAgIGJvcmRlci1jb2xvcjogIzExN2E4YjsgfVxuICAuYnRuLWluZm86Zm9jdXMsIC5idG4taW5mby5mb2N1cyB7XG4gICAgYm94LXNoYWRvdzogMCAwIDAgM3B4IHJnYmEoMjMsIDE2MiwgMTg0LCAwLjUpOyB9XG4gIC5idG4taW5mby5kaXNhYmxlZCwgLmJ0bi1pbmZvOmRpc2FibGVkIHtcbiAgICBiYWNrZ3JvdW5kLWNvbG9yOiAjMTdhMmI4O1xuICAgIGJvcmRlci1jb2xvcjogIzE3YTJiODsgfVxuICAuYnRuLWluZm86YWN0aXZlLCAuYnRuLWluZm8uYWN0aXZlLFxuICAuc2hvdyA+IC5idG4taW5mby5kcm9wZG93bi10b2dnbGUge1xuICAgIGJhY2tncm91bmQtY29sb3I6ICMxMzg0OTY7XG4gICAgYmFja2dyb3VuZC1pbWFnZTogbm9uZTtcbiAgICBib3JkZXItY29sb3I6ICMxMTdhOGI7IH1cblxuLmJ0bi13YXJuaW5nIHtcbiAgY29sb3I6ICMxMTE7XG4gIGJhY2tncm91bmQtY29sb3I6ICNmZmMxMDc7XG4gIGJvcmRlci1jb2xvcjogI2ZmYzEwNzsgfVxuICAuYnRuLXdhcm5pbmc6aG92ZXIge1xuICAgIGNvbG9yOiAjMTExO1xuICAgIGJhY2tncm91bmQtY29sb3I6ICNlMGE4MDA7XG4gICAgYm9yZGVyLWNvbG9yOiAjZDM5ZTAwOyB9XG4gIC5idG4td2FybmluZzpmb2N1cywgLmJ0bi13YXJuaW5nLmZvY3VzIHtcbiAgICBib3gtc2hhZG93OiAwIDAgMCAzcHggcmdiYSgyNTUsIDE5MywgNywgMC41KTsgfVxuICAuYnRuLXdhcm5pbmcuZGlzYWJsZWQsIC5idG4td2FybmluZzpkaXNhYmxlZCB7XG4gICAgYmFja2dyb3VuZC1jb2xvcjogI2ZmYzEwNztcbiAgICBib3JkZXItY29sb3I6ICNmZmMxMDc7IH1cbiAgLmJ0bi13YXJuaW5nOmFjdGl2ZSwgLmJ0bi13YXJuaW5nLmFjdGl2ZSxcbiAgLnNob3cgPiAuYnRuLXdhcm5pbmcuZHJvcGRvd24tdG9nZ2xlIHtcbiAgICBiYWNrZ3JvdW5kLWNvbG9yOiAjZTBhODAwO1xuICAgIGJhY2tncm91bmQtaW1hZ2U6IG5vbmU7XG4gICAgYm9yZGVyLWNvbG9yOiAjZDM5ZTAwOyB9XG5cbi5idG4tZGFuZ2VyIHtcbiAgY29sb3I6ICNmZmY7XG4gIGJhY2tncm91bmQtY29sb3I6ICNkYzM1NDU7XG4gIGJvcmRlci1jb2xvcjogI2RjMzU0NTsgfVxuICAuYnRuLWRhbmdlcjpob3ZlciB7XG4gICAgY29sb3I6ICNmZmY7XG4gICAgYmFja2dyb3VuZC1jb2xvcjogI2M4MjMzMztcbiAgICBib3JkZXItY29sb3I6ICNiZDIxMzA7IH1cbiAgLmJ0bi1kYW5nZXI6Zm9jdXMsIC5idG4tZGFuZ2VyLmZvY3VzIHtcbiAgICBib3gtc2hhZG93OiAwIDAgMCAzcHggcmdiYSgyMjAsIDUzLCA2OSwgMC41KTsgfVxuICAuYnRuLWRhbmdlci5kaXNhYmxlZCwgLmJ0bi1kYW5nZXI6ZGlzYWJsZWQge1xuICAgIGJhY2tncm91bmQtY29sb3I6ICNkYzM1NDU7XG4gICAgYm9yZGVyLWNvbG9yOiAjZGMzNTQ1OyB9XG4gIC5idG4tZGFuZ2VyOmFjdGl2ZSwgLmJ0bi1kYW5nZXIuYWN0aXZlLFxuICAuc2hvdyA+IC5idG4tZGFuZ2VyLmRyb3Bkb3duLXRvZ2dsZSB7XG4gICAgYmFja2dyb3VuZC1jb2xvcjogI2M4MjMzMztcbiAgICBiYWNrZ3JvdW5kLWltYWdlOiBub25lO1xuICAgIGJvcmRlci1jb2xvcjogI2JkMjEzMDsgfVxuXG4uYnRuLWxpZ2h0IHtcbiAgY29sb3I6ICMxMTE7XG4gIGJhY2tncm91bmQtY29sb3I6ICNmOGY5ZmE7XG4gIGJvcmRlci1jb2xvcjogI2Y4ZjlmYTsgfVxuICAuYnRuLWxpZ2h0OmhvdmVyIHtcbiAgICBjb2xvcjogIzExMTtcbiAgICBiYWNrZ3JvdW5kLWNvbG9yOiAjZTJlNmVhO1xuICAgIGJvcmRlci1jb2xvcjogI2RhZTBlNTsgfVxuICAuYnRuLWxpZ2h0OmZvY3VzLCAuYnRuLWxpZ2h0LmZvY3VzIHtcbiAgICBib3gtc2hhZG93OiAwIDAgMCAzcHggcmdiYSgyNDgsIDI0OSwgMjUwLCAwLjUpOyB9XG4gIC5idG4tbGlnaHQuZGlzYWJsZWQsIC5idG4tbGlnaHQ6ZGlzYWJsZWQge1xuICAgIGJhY2tncm91bmQtY29sb3I6ICNmOGY5ZmE7XG4gICAgYm9yZGVyLWNvbG9yOiAjZjhmOWZhOyB9XG4gIC5idG4tbGlnaHQ6YWN0aXZlLCAuYnRuLWxpZ2h0LmFjdGl2ZSxcbiAgLnNob3cgPiAuYnRuLWxpZ2h0LmRyb3Bkb3duLXRvZ2dsZSB7XG4gICAgYmFja2dyb3VuZC1jb2xvcjogI2UyZTZlYTtcbiAgICBiYWNrZ3JvdW5kLWltYWdlOiBub25lO1xuICAgIGJvcmRlci1jb2xvcjogI2RhZTBlNTsgfVxuXG4uYnRuLWRhcmsge1xuICBjb2xvcjogI2ZmZjtcbiAgYmFja2dyb3VuZC1jb2xvcjogIzM0M2E0MDtcbiAgYm9yZGVyLWNvbG9yOiAjMzQzYTQwOyB9XG4gIC5idG4tZGFyazpob3ZlciB7XG4gICAgY29sb3I6ICNmZmY7XG4gICAgYmFja2dyb3VuZC1jb2xvcjogIzIzMjcyYjtcbiAgICBib3JkZXItY29sb3I6ICMxZDIxMjQ7IH1cbiAgLmJ0bi1kYXJrOmZvY3VzLCAuYnRuLWRhcmsuZm9jdXMge1xuICAgIGJveC1zaGFkb3c6IDAgMCAwIDNweCByZ2JhKDUyLCA1OCwgNjQsIDAuNSk7IH1cbiAgLmJ0bi1kYXJrLmRpc2FibGVkLCAuYnRuLWRhcms6ZGlzYWJsZWQge1xuICAgIGJhY2tncm91bmQtY29sb3I6ICMzNDNhNDA7XG4gICAgYm9yZGVyLWNvbG9yOiAjMzQzYTQwOyB9XG4gIC5idG4tZGFyazphY3RpdmUsIC5idG4tZGFyay5hY3RpdmUsXG4gIC5zaG93ID4gLmJ0bi1kYXJrLmRyb3Bkb3duLXRvZ2dsZSB7XG4gICAgYmFja2dyb3VuZC1jb2xvcjogIzIzMjcyYjtcbiAgICBiYWNrZ3JvdW5kLWltYWdlOiBub25lO1xuICAgIGJvcmRlci1jb2xvcjogIzFkMjEyNDsgfVxuXG4uYnRuLW91dGxpbmUtcHJpbWFyeSB7XG4gIGNvbG9yOiAjMDA3YmZmO1xuICBiYWNrZ3JvdW5kLWNvbG9yOiB0cmFuc3BhcmVudDtcbiAgYmFja2dyb3VuZC1pbWFnZTogbm9uZTtcbiAgYm9yZGVyLWNvbG9yOiAjMDA3YmZmOyB9XG4gIC5idG4tb3V0bGluZS1wcmltYXJ5OmhvdmVyIHtcbiAgICBjb2xvcjogI2ZmZjtcbiAgICBiYWNrZ3JvdW5kLWNvbG9yOiAjMDA3YmZmO1xuICAgIGJvcmRlci1jb2xvcjogIzAwN2JmZjsgfVxuICAuYnRuLW91dGxpbmUtcHJpbWFyeTpmb2N1cywgLmJ0bi1vdXRsaW5lLXByaW1hcnkuZm9jdXMge1xuICAgIGJveC1zaGFkb3c6IDAgMCAwIDNweCByZ2JhKDAsIDEyMywgMjU1LCAwLjUpOyB9XG4gIC5idG4tb3V0bGluZS1wcmltYXJ5LmRpc2FibGVkLCAuYnRuLW91dGxpbmUtcHJpbWFyeTpkaXNhYmxlZCB7XG4gICAgY29sb3I6ICMwMDdiZmY7XG4gICAgYmFja2dyb3VuZC1jb2xvcjogdHJhbnNwYXJlbnQ7IH1cbiAgLmJ0bi1vdXRsaW5lLXByaW1hcnk6YWN0aXZlLCAuYnRuLW91dGxpbmUtcHJpbWFyeS5hY3RpdmUsXG4gIC5zaG93ID4gLmJ0bi1vdXRsaW5lLXByaW1hcnkuZHJvcGRvd24tdG9nZ2xlIHtcbiAgICBjb2xvcjogI2ZmZjtcbiAgICBiYWNrZ3JvdW5kLWNvbG9yOiAjMDA3YmZmO1xuICAgIGJvcmRlci1jb2xvcjogIzAwN2JmZjsgfVxuXG4uYnRuLW91dGxpbmUtc2Vjb25kYXJ5IHtcbiAgY29sb3I6ICM4NjhlOTY7XG4gIGJhY2tncm91bmQtY29sb3I6IHRyYW5zcGFyZW50O1xuICBiYWNrZ3JvdW5kLWltYWdlOiBub25lO1xuICBib3JkZXItY29sb3I6ICM4NjhlOTY7IH1cbiAgLmJ0bi1vdXRsaW5lLXNlY29uZGFyeTpob3ZlciB7XG4gICAgY29sb3I6ICNmZmY7XG4gICAgYmFja2dyb3VuZC1jb2xvcjogIzg2OGU5NjtcbiAgICBib3JkZXItY29sb3I6ICM4NjhlOTY7IH1cbiAgLmJ0bi1vdXRsaW5lLXNlY29uZGFyeTpmb2N1cywgLmJ0bi1vdXRsaW5lLXNlY29uZGFyeS5mb2N1cyB7XG4gICAgYm94LXNoYWRvdzogMCAwIDAgM3B4IHJnYmEoMTM0LCAxNDIsIDE1MCwgMC41KTsgfVxuICAuYnRuLW91dGxpbmUtc2Vjb25kYXJ5LmRpc2FibGVkLCAuYnRuLW91dGxpbmUtc2Vjb25kYXJ5OmRpc2FibGVkIHtcbiAgICBjb2xvcjogIzg2OGU5NjtcbiAgICBiYWNrZ3JvdW5kLWNvbG9yOiB0cmFuc3BhcmVudDsgfVxuICAuYnRuLW91dGxpbmUtc2Vjb25kYXJ5OmFjdGl2ZSwgLmJ0bi1vdXRsaW5lLXNlY29uZGFyeS5hY3RpdmUsXG4gIC5zaG93ID4gLmJ0bi1vdXRsaW5lLXNlY29uZGFyeS5kcm9wZG93bi10b2dnbGUge1xuICAgIGNvbG9yOiAjZmZmO1xuICAgIGJhY2tncm91bmQtY29sb3I6ICM4NjhlOTY7XG4gICAgYm9yZGVyLWNvbG9yOiAjODY4ZTk2OyB9XG5cbi5idG4tb3V0bGluZS1zdWNjZXNzIHtcbiAgY29sb3I6ICMyOGE3NDU7XG4gIGJhY2tncm91bmQtY29sb3I6IHRyYW5zcGFyZW50O1xuICBiYWNrZ3JvdW5kLWltYWdlOiBub25lO1xuICBib3JkZXItY29sb3I6ICMyOGE3NDU7IH1cbiAgLmJ0bi1vdXRsaW5lLXN1Y2Nlc3M6aG92ZXIge1xuICAgIGNvbG9yOiAjZmZmO1xuICAgIGJhY2tncm91bmQtY29sb3I6ICMyOGE3NDU7XG4gICAgYm9yZGVyLWNvbG9yOiAjMjhhNzQ1OyB9XG4gIC5idG4tb3V0bGluZS1zdWNjZXNzOmZvY3VzLCAuYnRuLW91dGxpbmUtc3VjY2Vzcy5mb2N1cyB7XG4gICAgYm94LXNoYWRvdzogMCAwIDAgM3B4IHJnYmEoNDAsIDE2NywgNjksIDAuNSk7IH1cbiAgLmJ0bi1vdXRsaW5lLXN1Y2Nlc3MuZGlzYWJsZWQsIC5idG4tb3V0bGluZS1zdWNjZXNzOmRpc2FibGVkIHtcbiAgICBjb2xvcjogIzI4YTc0NTtcbiAgICBiYWNrZ3JvdW5kLWNvbG9yOiB0cmFuc3BhcmVudDsgfVxuICAuYnRuLW91dGxpbmUtc3VjY2VzczphY3RpdmUsIC5idG4tb3V0bGluZS1zdWNjZXNzLmFjdGl2ZSxcbiAgLnNob3cgPiAuYnRuLW91dGxpbmUtc3VjY2Vzcy5kcm9wZG93bi10b2dnbGUge1xuICAgIGNvbG9yOiAjZmZmO1xuICAgIGJhY2tncm91bmQtY29sb3I6ICMyOGE3NDU7XG4gICAgYm9yZGVyLWNvbG9yOiAjMjhhNzQ1OyB9XG5cbi5idG4tb3V0bGluZS1pbmZvIHtcbiAgY29sb3I6ICMxN2EyYjg7XG4gIGJhY2tncm91bmQtY29sb3I6IHRyYW5zcGFyZW50O1xuICBiYWNrZ3JvdW5kLWltYWdlOiBub25lO1xuICBib3JkZXItY29sb3I6ICMxN2EyYjg7IH1cbiAgLmJ0bi1vdXRsaW5lLWluZm86aG92ZXIge1xuICAgIGNvbG9yOiAjZmZmO1xuICAgIGJhY2tncm91bmQtY29sb3I6ICMxN2EyYjg7XG4gICAgYm9yZGVyLWNvbG9yOiAjMTdhMmI4OyB9XG4gIC5idG4tb3V0bGluZS1pbmZvOmZvY3VzLCAuYnRuLW91dGxpbmUtaW5mby5mb2N1cyB7XG4gICAgYm94LXNoYWRvdzogMCAwIDAgM3B4IHJnYmEoMjMsIDE2MiwgMTg0LCAwLjUpOyB9XG4gIC5idG4tb3V0bGluZS1pbmZvLmRpc2FibGVkLCAuYnRuLW91dGxpbmUtaW5mbzpkaXNhYmxlZCB7XG4gICAgY29sb3I6ICMxN2EyYjg7XG4gICAgYmFja2dyb3VuZC1jb2xvcjogdHJhbnNwYXJlbnQ7IH1cbiAgLmJ0bi1vdXRsaW5lLWluZm86YWN0aXZlLCAuYnRuLW91dGxpbmUtaW5mby5hY3RpdmUsXG4gIC5zaG93ID4gLmJ0bi1vdXRsaW5lLWluZm8uZHJvcGRvd24tdG9nZ2xlIHtcbiAgICBjb2xvcjogI2ZmZjtcbiAgICBiYWNrZ3JvdW5kLWNvbG9yOiAjMTdhMmI4O1xuICAgIGJvcmRlci1jb2xvcjogIzE3YTJiODsgfVxuXG4uYnRuLW91dGxpbmUtd2FybmluZyB7XG4gIGNvbG9yOiAjZmZjMTA3O1xuICBiYWNrZ3JvdW5kLWNvbG9yOiB0cmFuc3BhcmVudDtcbiAgYmFja2dyb3VuZC1pbWFnZTogbm9uZTtcbiAgYm9yZGVyLWNvbG9yOiAjZmZjMTA3OyB9XG4gIC5idG4tb3V0bGluZS13YXJuaW5nOmhvdmVyIHtcbiAgICBjb2xvcjogI2ZmZjtcbiAgICBiYWNrZ3JvdW5kLWNvbG9yOiAjZmZjMTA3O1xuICAgIGJvcmRlci1jb2xvcjogI2ZmYzEwNzsgfVxuICAuYnRuLW91dGxpbmUtd2FybmluZzpmb2N1cywgLmJ0bi1vdXRsaW5lLXdhcm5pbmcuZm9jdXMge1xuICAgIGJveC1zaGFkb3c6IDAgMCAwIDNweCByZ2JhKDI1NSwgMTkzLCA3LCAwLjUpOyB9XG4gIC5idG4tb3V0bGluZS13YXJuaW5nLmRpc2FibGVkLCAuYnRuLW91dGxpbmUtd2FybmluZzpkaXNhYmxlZCB7XG4gICAgY29sb3I6ICNmZmMxMDc7XG4gICAgYmFja2dyb3VuZC1jb2xvcjogdHJhbnNwYXJlbnQ7IH1cbiAgLmJ0bi1vdXRsaW5lLXdhcm5pbmc6YWN0aXZlLCAuYnRuLW91dGxpbmUtd2FybmluZy5hY3RpdmUsXG4gIC5zaG93ID4gLmJ0bi1vdXRsaW5lLXdhcm5pbmcuZHJvcGRvd24tdG9nZ2xlIHtcbiAgICBjb2xvcjogI2ZmZjtcbiAgICBiYWNrZ3JvdW5kLWNvbG9yOiAjZmZjMTA3O1xuICAgIGJvcmRlci1jb2xvcjogI2ZmYzEwNzsgfVxuXG4uYnRuLW91dGxpbmUtZGFuZ2VyIHtcbiAgY29sb3I6ICNkYzM1NDU7XG4gIGJhY2tncm91bmQtY29sb3I6IHRyYW5zcGFyZW50O1xuICBiYWNrZ3JvdW5kLWltYWdlOiBub25lO1xuICBib3JkZXItY29sb3I6ICNkYzM1NDU7IH1cbiAgLmJ0bi1vdXRsaW5lLWRhbmdlcjpob3ZlciB7XG4gICAgY29sb3I6ICNmZmY7XG4gICAgYmFja2dyb3VuZC1jb2xvcjogI2RjMzU0NTtcbiAgICBib3JkZXItY29sb3I6ICNkYzM1NDU7IH1cbiAgLmJ0bi1vdXRsaW5lLWRhbmdlcjpmb2N1cywgLmJ0bi1vdXRsaW5lLWRhbmdlci5mb2N1cyB7XG4gICAgYm94LXNoYWRvdzogMCAwIDAgM3B4IHJnYmEoMjIwLCA1MywgNjksIDAuNSk7IH1cbiAgLmJ0bi1vdXRsaW5lLWRhbmdlci5kaXNhYmxlZCwgLmJ0bi1vdXRsaW5lLWRhbmdlcjpkaXNhYmxlZCB7XG4gICAgY29sb3I6ICNkYzM1NDU7XG4gICAgYmFja2dyb3VuZC1jb2xvcjogdHJhbnNwYXJlbnQ7IH1cbiAgLmJ0bi1vdXRsaW5lLWRhbmdlcjphY3RpdmUsIC5idG4tb3V0bGluZS1kYW5nZXIuYWN0aXZlLFxuICAuc2hvdyA+IC5idG4tb3V0bGluZS1kYW5nZXIuZHJvcGRvd24tdG9nZ2xlIHtcbiAgICBjb2xvcjogI2ZmZjtcbiAgICBiYWNrZ3JvdW5kLWNvbG9yOiAjZGMzNTQ1O1xuICAgIGJvcmRlci1jb2xvcjogI2RjMzU0NTsgfVxuXG4uYnRuLW91dGxpbmUtbGlnaHQge1xuICBjb2xvcjogI2Y4ZjlmYTtcbiAgYmFja2dyb3VuZC1jb2xvcjogdHJhbnNwYXJlbnQ7XG4gIGJhY2tncm91bmQtaW1hZ2U6IG5vbmU7XG4gIGJvcmRlci1jb2xvcjogI2Y4ZjlmYTsgfVxuICAuYnRuLW91dGxpbmUtbGlnaHQ6aG92ZXIge1xuICAgIGNvbG9yOiAjZmZmO1xuICAgIGJhY2tncm91bmQtY29sb3I6ICNmOGY5ZmE7XG4gICAgYm9yZGVyLWNvbG9yOiAjZjhmOWZhOyB9XG4gIC5idG4tb3V0bGluZS1saWdodDpmb2N1cywgLmJ0bi1vdXRsaW5lLWxpZ2h0LmZvY3VzIHtcbiAgICBib3gtc2hhZG93OiAwIDAgMCAzcHggcmdiYSgyNDgsIDI0OSwgMjUwLCAwLjUpOyB9XG4gIC5idG4tb3V0bGluZS1saWdodC5kaXNhYmxlZCwgLmJ0bi1vdXRsaW5lLWxpZ2h0OmRpc2FibGVkIHtcbiAgICBjb2xvcjogI2Y4ZjlmYTtcbiAgICBiYWNrZ3JvdW5kLWNvbG9yOiB0cmFuc3BhcmVudDsgfVxuICAuYnRuLW91dGxpbmUtbGlnaHQ6YWN0aXZlLCAuYnRuLW91dGxpbmUtbGlnaHQuYWN0aXZlLFxuICAuc2hvdyA+IC5idG4tb3V0bGluZS1saWdodC5kcm9wZG93bi10b2dnbGUge1xuICAgIGNvbG9yOiAjZmZmO1xuICAgIGJhY2tncm91bmQtY29sb3I6ICNmOGY5ZmE7XG4gICAgYm9yZGVyLWNvbG9yOiAjZjhmOWZhOyB9XG5cbi5idG4tb3V0bGluZS1kYXJrIHtcbiAgY29sb3I6ICMzNDNhNDA7XG4gIGJhY2tncm91bmQtY29sb3I6IHRyYW5zcGFyZW50O1xuICBiYWNrZ3JvdW5kLWltYWdlOiBub25lO1xuICBib3JkZXItY29sb3I6ICMzNDNhNDA7IH1cbiAgLmJ0bi1vdXRsaW5lLWRhcms6aG92ZXIge1xuICAgIGNvbG9yOiAjZmZmO1xuICAgIGJhY2tncm91bmQtY29sb3I6ICMzNDNhNDA7XG4gICAgYm9yZGVyLWNvbG9yOiAjMzQzYTQwOyB9XG4gIC5idG4tb3V0bGluZS1kYXJrOmZvY3VzLCAuYnRuLW91dGxpbmUtZGFyay5mb2N1cyB7XG4gICAgYm94LXNoYWRvdzogMCAwIDAgM3B4IHJnYmEoNTIsIDU4LCA2NCwgMC41KTsgfVxuICAuYnRuLW91dGxpbmUtZGFyay5kaXNhYmxlZCwgLmJ0bi1vdXRsaW5lLWRhcms6ZGlzYWJsZWQge1xuICAgIGNvbG9yOiAjMzQzYTQwO1xuICAgIGJhY2tncm91bmQtY29sb3I6IHRyYW5zcGFyZW50OyB9XG4gIC5idG4tb3V0bGluZS1kYXJrOmFjdGl2ZSwgLmJ0bi1vdXRsaW5lLWRhcmsuYWN0aXZlLFxuICAuc2hvdyA+IC5idG4tb3V0bGluZS1kYXJrLmRyb3Bkb3duLXRvZ2dsZSB7XG4gICAgY29sb3I6ICNmZmY7XG4gICAgYmFja2dyb3VuZC1jb2xvcjogIzM0M2E0MDtcbiAgICBib3JkZXItY29sb3I6ICMzNDNhNDA7IH1cblxuLmJ0bi1saW5rIHtcbiAgZm9udC13ZWlnaHQ6IG5vcm1hbDtcbiAgY29sb3I6ICMwMDdiZmY7XG4gIGJvcmRlci1yYWRpdXM6IDA7IH1cbiAgLmJ0bi1saW5rLCAuYnRuLWxpbms6YWN0aXZlLCAuYnRuLWxpbmsuYWN0aXZlLCAuYnRuLWxpbms6ZGlzYWJsZWQge1xuICAgIGJhY2tncm91bmQtY29sb3I6IHRyYW5zcGFyZW50OyB9XG4gIC5idG4tbGluaywgLmJ0bi1saW5rOmZvY3VzLCAuYnRuLWxpbms6YWN0aXZlIHtcbiAgICBib3JkZXItY29sb3I6IHRyYW5zcGFyZW50O1xuICAgIGJveC1zaGFkb3c6IG5vbmU7IH1cbiAgLmJ0bi1saW5rOmhvdmVyIHtcbiAgICBib3JkZXItY29sb3I6IHRyYW5zcGFyZW50OyB9XG4gIC5idG4tbGluazpmb2N1cywgLmJ0bi1saW5rOmhvdmVyIHtcbiAgICBjb2xvcjogIzAwNTZiMztcbiAgICB0ZXh0LWRlY29yYXRpb246IHVuZGVybGluZTtcbiAgICBiYWNrZ3JvdW5kLWNvbG9yOiB0cmFuc3BhcmVudDsgfVxuICAuYnRuLWxpbms6ZGlzYWJsZWQge1xuICAgIGNvbG9yOiAjODY4ZTk2OyB9XG4gICAgLmJ0bi1saW5rOmRpc2FibGVkOmZvY3VzLCAuYnRuLWxpbms6ZGlzYWJsZWQ6aG92ZXIge1xuICAgICAgdGV4dC1kZWNvcmF0aW9uOiBub25lOyB9XG5cbi5idG4tbGcsIC5idG4tZ3JvdXAtbGcgPiAuYnRuLCAuYnRuLWdyb3VwLWxnID4gYnV0dG9uLmN1c3RvbSB7XG4gIHBhZGRpbmc6IDAuNXJlbSAxcmVtO1xuICBmb250LXNpemU6IDEuMjVyZW07XG4gIGxpbmUtaGVpZ2h0OiAxLjU7XG4gIGJvcmRlci1yYWRpdXM6IDAuM3JlbTsgfVxuXG4uYnRuLXNtLCAuYnRuLWdyb3VwLXNtID4gLmJ0biwgLmJ0bi1ncm91cC1zbSA+IGJ1dHRvbi5jdXN0b20ge1xuICBwYWRkaW5nOiAwLjI1cmVtIDAuNXJlbTtcbiAgZm9udC1zaXplOiAwLjg3NXJlbTtcbiAgbGluZS1oZWlnaHQ6IDEuNTtcbiAgYm9yZGVyLXJhZGl1czogMC4ycmVtOyB9XG5cbi5idG4tYmxvY2sge1xuICBkaXNwbGF5OiBibG9jaztcbiAgd2lkdGg6IDEwMCU7IH1cblxuLmJ0bi1ibG9jayArIC5idG4tYmxvY2sge1xuICBtYXJnaW4tdG9wOiAwLjVyZW07IH1cblxuaW5wdXRbdHlwZT1cInN1Ym1pdFwiXS5idG4tYmxvY2ssXG5pbnB1dFt0eXBlPVwicmVzZXRcIl0uYnRuLWJsb2NrLFxuaW5wdXRbdHlwZT1cImJ1dHRvblwiXS5idG4tYmxvY2sge1xuICB3aWR0aDogMTAwJTsgfVxuXG4uZmFkZSB7XG4gIG9wYWNpdHk6IDA7XG4gIHRyYW5zaXRpb246IG9wYWNpdHkgMC4xNXMgbGluZWFyOyB9XG4gIC5mYWRlLnNob3cge1xuICAgIG9wYWNpdHk6IDE7IH1cblxuLmNvbGxhcHNlIHtcbiAgZGlzcGxheTogbm9uZTsgfVxuICAuY29sbGFwc2Uuc2hvdyB7XG4gICAgZGlzcGxheTogYmxvY2s7IH1cblxudHIuY29sbGFwc2Uuc2hvdyB7XG4gIGRpc3BsYXk6IHRhYmxlLXJvdzsgfVxuXG50Ym9keS5jb2xsYXBzZS5zaG93IHtcbiAgZGlzcGxheTogdGFibGUtcm93LWdyb3VwOyB9XG5cbi5jb2xsYXBzaW5nIHtcbiAgcG9zaXRpb246IHJlbGF0aXZlO1xuICBoZWlnaHQ6IDA7XG4gIG92ZXJmbG93OiBoaWRkZW47XG4gIHRyYW5zaXRpb246IGhlaWdodCAwLjM1cyBlYXNlOyB9XG5cbi5kcm9wdXAsXG4uZHJvcGRvd24ge1xuICBwb3NpdGlvbjogcmVsYXRpdmU7IH1cblxuLmRyb3Bkb3duLXRvZ2dsZTo6YWZ0ZXIge1xuICBkaXNwbGF5OiBpbmxpbmUtYmxvY2s7XG4gIHdpZHRoOiAwO1xuICBoZWlnaHQ6IDA7XG4gIG1hcmdpbi1sZWZ0OiAwLjI1NWVtO1xuICB2ZXJ0aWNhbC1hbGlnbjogMC4yNTVlbTtcbiAgY29udGVudDogXCJcIjtcbiAgYm9yZGVyLXRvcDogMC4zZW0gc29saWQ7XG4gIGJvcmRlci1yaWdodDogMC4zZW0gc29saWQgdHJhbnNwYXJlbnQ7XG4gIGJvcmRlci1sZWZ0OiAwLjNlbSBzb2xpZCB0cmFuc3BhcmVudDsgfVxuXG4uZHJvcGRvd24tdG9nZ2xlOmVtcHR5OjphZnRlciB7XG4gIG1hcmdpbi1sZWZ0OiAwOyB9XG5cbi5kcm9wdXAgLmRyb3Bkb3duLW1lbnUge1xuICBtYXJnaW4tdG9wOiAwO1xuICBtYXJnaW4tYm90dG9tOiAwLjEyNXJlbTsgfVxuXG4uZHJvcHVwIC5kcm9wZG93bi10b2dnbGU6OmFmdGVyIHtcbiAgYm9yZGVyLXRvcDogMDtcbiAgYm9yZGVyLWJvdHRvbTogMC4zZW0gc29saWQ7IH1cblxuLmRyb3Bkb3duLW1lbnUge1xuICBwb3NpdGlvbjogYWJzb2x1dGU7XG4gIHRvcDogMTAwJTtcbiAgbGVmdDogMDtcbiAgei1pbmRleDogMTAwMDtcbiAgZGlzcGxheTogbm9uZTtcbiAgZmxvYXQ6IGxlZnQ7XG4gIG1pbi13aWR0aDogMTByZW07XG4gIHBhZGRpbmc6IDAuNXJlbSAwO1xuICBtYXJnaW46IDAuMTI1cmVtIDAgMDtcbiAgZm9udC1zaXplOiAxcmVtO1xuICBjb2xvcjogIzIxMjUyOTtcbiAgdGV4dC1hbGlnbjogbGVmdDtcbiAgbGlzdC1zdHlsZTogbm9uZTtcbiAgYmFja2dyb3VuZC1jb2xvcjogI2ZmZjtcbiAgYmFja2dyb3VuZC1jbGlwOiBwYWRkaW5nLWJveDtcbiAgYm9yZGVyOiAxcHggc29saWQgcmdiYSgwLCAwLCAwLCAwLjE1KTtcbiAgYm9yZGVyLXJhZGl1czogMC4yNXJlbTsgfVxuXG4uZHJvcGRvd24tZGl2aWRlciB7XG4gIGhlaWdodDogMDtcbiAgbWFyZ2luOiAwLjVyZW0gMDtcbiAgb3ZlcmZsb3c6IGhpZGRlbjtcbiAgYm9yZGVyLXRvcDogMXB4IHNvbGlkICNlOWVjZWY7IH1cblxuLmRyb3Bkb3duLWl0ZW0ge1xuICBkaXNwbGF5OiBibG9jaztcbiAgd2lkdGg6IDEwMCU7XG4gIHBhZGRpbmc6IDAuMjVyZW0gMS41cmVtO1xuICBjbGVhcjogYm90aDtcbiAgZm9udC13ZWlnaHQ6IG5vcm1hbDtcbiAgY29sb3I6ICMyMTI1Mjk7XG4gIHRleHQtYWxpZ246IGluaGVyaXQ7XG4gIHdoaXRlLXNwYWNlOiBub3dyYXA7XG4gIGJhY2tncm91bmQ6IG5vbmU7XG4gIGJvcmRlcjogMDsgfVxuICAuZHJvcGRvd24taXRlbTpmb2N1cywgLmRyb3Bkb3duLWl0ZW06aG92ZXIge1xuICAgIGNvbG9yOiAjMTYxODFiO1xuICAgIHRleHQtZGVjb3JhdGlvbjogbm9uZTtcbiAgICBiYWNrZ3JvdW5kLWNvbG9yOiAjZjhmOWZhOyB9XG4gIC5kcm9wZG93bi1pdGVtLmFjdGl2ZSwgLmRyb3Bkb3duLWl0ZW06YWN0aXZlIHtcbiAgICBjb2xvcjogI2ZmZjtcbiAgICB0ZXh0LWRlY29yYXRpb246IG5vbmU7XG4gICAgYmFja2dyb3VuZC1jb2xvcjogIzAwN2JmZjsgfVxuICAuZHJvcGRvd24taXRlbS5kaXNhYmxlZCwgLmRyb3Bkb3duLWl0ZW06ZGlzYWJsZWQge1xuICAgIGNvbG9yOiAjODY4ZTk2O1xuICAgIGJhY2tncm91bmQtY29sb3I6IHRyYW5zcGFyZW50OyB9XG5cbi5zaG93ID4gYSB7XG4gIG91dGxpbmU6IDA7IH1cblxuLmRyb3Bkb3duLW1lbnUuc2hvdyB7XG4gIGRpc3BsYXk6IGJsb2NrOyB9XG5cbi5kcm9wZG93bi1oZWFkZXIge1xuICBkaXNwbGF5OiBibG9jaztcbiAgcGFkZGluZzogMC41cmVtIDEuNXJlbTtcbiAgbWFyZ2luLWJvdHRvbTogMDtcbiAgZm9udC1zaXplOiAwLjg3NXJlbTtcbiAgY29sb3I6ICM4NjhlOTY7XG4gIHdoaXRlLXNwYWNlOiBub3dyYXA7IH1cblxuLmJ0bi1ncm91cCxcbi5idG4tZ3JvdXAtdmVydGljYWwge1xuICBwb3NpdGlvbjogcmVsYXRpdmU7XG4gIGRpc3BsYXk6IGlubGluZS1mbGV4O1xuICB2ZXJ0aWNhbC1hbGlnbjogbWlkZGxlOyB9XG4gIC5idG4tZ3JvdXAgPiAuYnRuLCAuYnRuLWdyb3VwID4gYnV0dG9uLmN1c3RvbSxcbiAgLmJ0bi1ncm91cC12ZXJ0aWNhbCA+IC5idG4sXG4gIC5idG4tZ3JvdXAtdmVydGljYWwgPiBidXR0b24uY3VzdG9tIHtcbiAgICBwb3NpdGlvbjogcmVsYXRpdmU7XG4gICAgZmxleDogMCAxIGF1dG87XG4gICAgbWFyZ2luLWJvdHRvbTogMDsgfVxuICAgIC5idG4tZ3JvdXAgPiAuYnRuOmhvdmVyLCAuYnRuLWdyb3VwID4gYnV0dG9uLmN1c3RvbTpob3ZlcixcbiAgICAuYnRuLWdyb3VwLXZlcnRpY2FsID4gLmJ0bjpob3ZlcixcbiAgICAuYnRuLWdyb3VwLXZlcnRpY2FsID4gYnV0dG9uLmN1c3RvbTpob3ZlciB7XG4gICAgICB6LWluZGV4OiAyOyB9XG4gICAgLmJ0bi1ncm91cCA+IC5idG46Zm9jdXMsIC5idG4tZ3JvdXAgPiBidXR0b24uY3VzdG9tOmZvY3VzLCAuYnRuLWdyb3VwID4gLmJ0bjphY3RpdmUsIC5idG4tZ3JvdXAgPiBidXR0b24uY3VzdG9tOmFjdGl2ZSwgLmJ0bi1ncm91cCA+IC5idG4uYWN0aXZlLCAuYnRuLWdyb3VwID4gYnV0dG9uLmFjdGl2ZS5jdXN0b20sXG4gICAgLmJ0bi1ncm91cC12ZXJ0aWNhbCA+IC5idG46Zm9jdXMsXG4gICAgLmJ0bi1ncm91cC12ZXJ0aWNhbCA+IGJ1dHRvbi5jdXN0b206Zm9jdXMsXG4gICAgLmJ0bi1ncm91cC12ZXJ0aWNhbCA+IC5idG46YWN0aXZlLFxuICAgIC5idG4tZ3JvdXAtdmVydGljYWwgPiBidXR0b24uY3VzdG9tOmFjdGl2ZSxcbiAgICAuYnRuLWdyb3VwLXZlcnRpY2FsID4gLmJ0bi5hY3RpdmUsXG4gICAgLmJ0bi1ncm91cC12ZXJ0aWNhbCA+IGJ1dHRvbi5hY3RpdmUuY3VzdG9tIHtcbiAgICAgIHotaW5kZXg6IDI7IH1cbiAgLmJ0bi1ncm91cCAuYnRuICsgLmJ0biwgLmJ0bi1ncm91cCBidXR0b24uY3VzdG9tICsgLmJ0biwgLmJ0bi1ncm91cCAuYnRuICsgYnV0dG9uLmN1c3RvbSwgLmJ0bi1ncm91cCBidXR0b24uY3VzdG9tICsgYnV0dG9uLmN1c3RvbSxcbiAgLmJ0bi1ncm91cCAuYnRuICsgLmJ0bi1ncm91cCxcbiAgLmJ0bi1ncm91cCBidXR0b24uY3VzdG9tICsgLmJ0bi1ncm91cCxcbiAgLmJ0bi1ncm91cCAuYnRuLWdyb3VwICsgLmJ0bixcbiAgLmJ0bi1ncm91cCAuYnRuLWdyb3VwICsgYnV0dG9uLmN1c3RvbSxcbiAgLmJ0bi1ncm91cCAuYnRuLWdyb3VwICsgLmJ0bi1ncm91cCxcbiAgLmJ0bi1ncm91cC12ZXJ0aWNhbCAuYnRuICsgLmJ0bixcbiAgLmJ0bi1ncm91cC12ZXJ0aWNhbCBidXR0b24uY3VzdG9tICsgLmJ0bixcbiAgLmJ0bi1ncm91cC12ZXJ0aWNhbCAuYnRuICsgYnV0dG9uLmN1c3RvbSxcbiAgLmJ0bi1ncm91cC12ZXJ0aWNhbCBidXR0b24uY3VzdG9tICsgYnV0dG9uLmN1c3RvbSxcbiAgLmJ0bi1ncm91cC12ZXJ0aWNhbCAuYnRuICsgLmJ0bi1ncm91cCxcbiAgLmJ0bi1ncm91cC12ZXJ0aWNhbCBidXR0b24uY3VzdG9tICsgLmJ0bi1ncm91cCxcbiAgLmJ0bi1ncm91cC12ZXJ0aWNhbCAuYnRuLWdyb3VwICsgLmJ0bixcbiAgLmJ0bi1ncm91cC12ZXJ0aWNhbCAuYnRuLWdyb3VwICsgYnV0dG9uLmN1c3RvbSxcbiAgLmJ0bi1ncm91cC12ZXJ0aWNhbCAuYnRuLWdyb3VwICsgLmJ0bi1ncm91cCB7XG4gICAgbWFyZ2luLWxlZnQ6IC0xcHg7IH1cblxuLmJ0bi10b29sYmFyIHtcbiAgZGlzcGxheTogZmxleDtcbiAgZmxleC13cmFwOiB3cmFwO1xuICBqdXN0aWZ5LWNvbnRlbnQ6IGZsZXgtc3RhcnQ7IH1cbiAgLmJ0bi10b29sYmFyIC5pbnB1dC1ncm91cCB7XG4gICAgd2lkdGg6IGF1dG87IH1cblxuLmJ0bi1ncm91cCA+IC5idG46bm90KDpmaXJzdC1jaGlsZCk6bm90KDpsYXN0LWNoaWxkKTpub3QoLmRyb3Bkb3duLXRvZ2dsZSksIC5idG4tZ3JvdXAgPiBidXR0b24uY3VzdG9tOm5vdCg6Zmlyc3QtY2hpbGQpOm5vdCg6bGFzdC1jaGlsZCk6bm90KC5kcm9wZG93bi10b2dnbGUpIHtcbiAgYm9yZGVyLXJhZGl1czogMDsgfVxuXG4uYnRuLWdyb3VwID4gLmJ0bjpmaXJzdC1jaGlsZCwgLmJ0bi1ncm91cCA+IGJ1dHRvbi5jdXN0b206Zmlyc3QtY2hpbGQge1xuICBtYXJnaW4tbGVmdDogMDsgfVxuICAuYnRuLWdyb3VwID4gLmJ0bjpmaXJzdC1jaGlsZDpub3QoOmxhc3QtY2hpbGQpOm5vdCguZHJvcGRvd24tdG9nZ2xlKSwgLmJ0bi1ncm91cCA+IGJ1dHRvbi5jdXN0b206Zmlyc3QtY2hpbGQ6bm90KDpsYXN0LWNoaWxkKTpub3QoLmRyb3Bkb3duLXRvZ2dsZSkge1xuICAgIGJvcmRlci10b3AtcmlnaHQtcmFkaXVzOiAwO1xuICAgIGJvcmRlci1ib3R0b20tcmlnaHQtcmFkaXVzOiAwOyB9XG5cbi5idG4tZ3JvdXAgPiAuYnRuOmxhc3QtY2hpbGQ6bm90KDpmaXJzdC1jaGlsZCksIC5idG4tZ3JvdXAgPiBidXR0b24uY3VzdG9tOmxhc3QtY2hpbGQ6bm90KDpmaXJzdC1jaGlsZCksXG4uYnRuLWdyb3VwID4gLmRyb3Bkb3duLXRvZ2dsZTpub3QoOmZpcnN0LWNoaWxkKSB7XG4gIGJvcmRlci10b3AtbGVmdC1yYWRpdXM6IDA7XG4gIGJvcmRlci1ib3R0b20tbGVmdC1yYWRpdXM6IDA7IH1cblxuLmJ0bi1ncm91cCA+IC5idG4tZ3JvdXAge1xuICBmbG9hdDogbGVmdDsgfVxuXG4uYnRuLWdyb3VwID4gLmJ0bi1ncm91cDpub3QoOmZpcnN0LWNoaWxkKTpub3QoOmxhc3QtY2hpbGQpID4gLmJ0biwgLmJ0bi1ncm91cCA+IC5idG4tZ3JvdXA6bm90KDpmaXJzdC1jaGlsZCk6bm90KDpsYXN0LWNoaWxkKSA+IGJ1dHRvbi5jdXN0b20ge1xuICBib3JkZXItcmFkaXVzOiAwOyB9XG5cbi5idG4tZ3JvdXAgPiAuYnRuLWdyb3VwOmZpcnN0LWNoaWxkOm5vdCg6bGFzdC1jaGlsZCkgPiAuYnRuOmxhc3QtY2hpbGQsIC5idG4tZ3JvdXAgPiAuYnRuLWdyb3VwOmZpcnN0LWNoaWxkOm5vdCg6bGFzdC1jaGlsZCkgPiBidXR0b24uY3VzdG9tOmxhc3QtY2hpbGQsXG4uYnRuLWdyb3VwID4gLmJ0bi1ncm91cDpmaXJzdC1jaGlsZDpub3QoOmxhc3QtY2hpbGQpID4gLmRyb3Bkb3duLXRvZ2dsZSB7XG4gIGJvcmRlci10b3AtcmlnaHQtcmFkaXVzOiAwO1xuICBib3JkZXItYm90dG9tLXJpZ2h0LXJhZGl1czogMDsgfVxuXG4uYnRuLWdyb3VwID4gLmJ0bi1ncm91cDpsYXN0LWNoaWxkOm5vdCg6Zmlyc3QtY2hpbGQpID4gLmJ0bjpmaXJzdC1jaGlsZCwgLmJ0bi1ncm91cCA+IC5idG4tZ3JvdXA6bGFzdC1jaGlsZDpub3QoOmZpcnN0LWNoaWxkKSA+IGJ1dHRvbi5jdXN0b206Zmlyc3QtY2hpbGQge1xuICBib3JkZXItdG9wLWxlZnQtcmFkaXVzOiAwO1xuICBib3JkZXItYm90dG9tLWxlZnQtcmFkaXVzOiAwOyB9XG5cbi5idG4gKyAuZHJvcGRvd24tdG9nZ2xlLXNwbGl0LCBidXR0b24uY3VzdG9tICsgLmRyb3Bkb3duLXRvZ2dsZS1zcGxpdCB7XG4gIHBhZGRpbmctcmlnaHQ6IDAuNTYyNXJlbTtcbiAgcGFkZGluZy1sZWZ0OiAwLjU2MjVyZW07IH1cbiAgLmJ0biArIC5kcm9wZG93bi10b2dnbGUtc3BsaXQ6OmFmdGVyLCBidXR0b24uY3VzdG9tICsgLmRyb3Bkb3duLXRvZ2dsZS1zcGxpdDo6YWZ0ZXIge1xuICAgIG1hcmdpbi1sZWZ0OiAwOyB9XG5cbi5idG4tc20gKyAuZHJvcGRvd24tdG9nZ2xlLXNwbGl0LCAuYnRuLWdyb3VwLXNtID4gLmJ0biArIC5kcm9wZG93bi10b2dnbGUtc3BsaXQsIC5idG4tZ3JvdXAtc20gPiBidXR0b24uY3VzdG9tICsgLmRyb3Bkb3duLXRvZ2dsZS1zcGxpdCB7XG4gIHBhZGRpbmctcmlnaHQ6IDAuMzc1cmVtO1xuICBwYWRkaW5nLWxlZnQ6IDAuMzc1cmVtOyB9XG5cbi5idG4tbGcgKyAuZHJvcGRvd24tdG9nZ2xlLXNwbGl0LCAuYnRuLWdyb3VwLWxnID4gLmJ0biArIC5kcm9wZG93bi10b2dnbGUtc3BsaXQsIC5idG4tZ3JvdXAtbGcgPiBidXR0b24uY3VzdG9tICsgLmRyb3Bkb3duLXRvZ2dsZS1zcGxpdCB7XG4gIHBhZGRpbmctcmlnaHQ6IDAuNzVyZW07XG4gIHBhZGRpbmctbGVmdDogMC43NXJlbTsgfVxuXG4uYnRuLWdyb3VwLXZlcnRpY2FsIHtcbiAgZGlzcGxheTogaW5saW5lLWZsZXg7XG4gIGZsZXgtZGlyZWN0aW9uOiBjb2x1bW47XG4gIGFsaWduLWl0ZW1zOiBmbGV4LXN0YXJ0O1xuICBqdXN0aWZ5LWNvbnRlbnQ6IGNlbnRlcjsgfVxuICAuYnRuLWdyb3VwLXZlcnRpY2FsIC5idG4sIC5idG4tZ3JvdXAtdmVydGljYWwgYnV0dG9uLmN1c3RvbSxcbiAgLmJ0bi1ncm91cC12ZXJ0aWNhbCAuYnRuLWdyb3VwIHtcbiAgICB3aWR0aDogMTAwJTsgfVxuICAuYnRuLWdyb3VwLXZlcnRpY2FsID4gLmJ0biArIC5idG4sIC5idG4tZ3JvdXAtdmVydGljYWwgPiBidXR0b24uY3VzdG9tICsgLmJ0biwgLmJ0bi1ncm91cC12ZXJ0aWNhbCA+IC5idG4gKyBidXR0b24uY3VzdG9tLCAuYnRuLWdyb3VwLXZlcnRpY2FsID4gYnV0dG9uLmN1c3RvbSArIGJ1dHRvbi5jdXN0b20sXG4gIC5idG4tZ3JvdXAtdmVydGljYWwgPiAuYnRuICsgLmJ0bi1ncm91cCxcbiAgLmJ0bi1ncm91cC12ZXJ0aWNhbCA+IGJ1dHRvbi5jdXN0b20gKyAuYnRuLWdyb3VwLFxuICAuYnRuLWdyb3VwLXZlcnRpY2FsID4gLmJ0bi1ncm91cCArIC5idG4sXG4gIC5idG4tZ3JvdXAtdmVydGljYWwgPiAuYnRuLWdyb3VwICsgYnV0dG9uLmN1c3RvbSxcbiAgLmJ0bi1ncm91cC12ZXJ0aWNhbCA+IC5idG4tZ3JvdXAgKyAuYnRuLWdyb3VwIHtcbiAgICBtYXJnaW4tdG9wOiAtMXB4O1xuICAgIG1hcmdpbi1sZWZ0OiAwOyB9XG5cbi5idG4tZ3JvdXAtdmVydGljYWwgPiAuYnRuOm5vdCg6Zmlyc3QtY2hpbGQpOm5vdCg6bGFzdC1jaGlsZCksIC5idG4tZ3JvdXAtdmVydGljYWwgPiBidXR0b24uY3VzdG9tOm5vdCg6Zmlyc3QtY2hpbGQpOm5vdCg6bGFzdC1jaGlsZCkge1xuICBib3JkZXItcmFkaXVzOiAwOyB9XG5cbi5idG4tZ3JvdXAtdmVydGljYWwgPiAuYnRuOmZpcnN0LWNoaWxkOm5vdCg6bGFzdC1jaGlsZCksIC5idG4tZ3JvdXAtdmVydGljYWwgPiBidXR0b24uY3VzdG9tOmZpcnN0LWNoaWxkOm5vdCg6bGFzdC1jaGlsZCkge1xuICBib3JkZXItYm90dG9tLXJpZ2h0LXJhZGl1czogMDtcbiAgYm9yZGVyLWJvdHRvbS1sZWZ0LXJhZGl1czogMDsgfVxuXG4uYnRuLWdyb3VwLXZlcnRpY2FsID4gLmJ0bjpsYXN0LWNoaWxkOm5vdCg6Zmlyc3QtY2hpbGQpLCAuYnRuLWdyb3VwLXZlcnRpY2FsID4gYnV0dG9uLmN1c3RvbTpsYXN0LWNoaWxkOm5vdCg6Zmlyc3QtY2hpbGQpIHtcbiAgYm9yZGVyLXRvcC1sZWZ0LXJhZGl1czogMDtcbiAgYm9yZGVyLXRvcC1yaWdodC1yYWRpdXM6IDA7IH1cblxuLmJ0bi1ncm91cC12ZXJ0aWNhbCA+IC5idG4tZ3JvdXA6bm90KDpmaXJzdC1jaGlsZCk6bm90KDpsYXN0LWNoaWxkKSA+IC5idG4sIC5idG4tZ3JvdXAtdmVydGljYWwgPiAuYnRuLWdyb3VwOm5vdCg6Zmlyc3QtY2hpbGQpOm5vdCg6bGFzdC1jaGlsZCkgPiBidXR0b24uY3VzdG9tIHtcbiAgYm9yZGVyLXJhZGl1czogMDsgfVxuXG4uYnRuLWdyb3VwLXZlcnRpY2FsID4gLmJ0bi1ncm91cDpmaXJzdC1jaGlsZDpub3QoOmxhc3QtY2hpbGQpID4gLmJ0bjpsYXN0LWNoaWxkLCAuYnRuLWdyb3VwLXZlcnRpY2FsID4gLmJ0bi1ncm91cDpmaXJzdC1jaGlsZDpub3QoOmxhc3QtY2hpbGQpID4gYnV0dG9uLmN1c3RvbTpsYXN0LWNoaWxkLFxuLmJ0bi1ncm91cC12ZXJ0aWNhbCA+IC5idG4tZ3JvdXA6Zmlyc3QtY2hpbGQ6bm90KDpsYXN0LWNoaWxkKSA+IC5kcm9wZG93bi10b2dnbGUge1xuICBib3JkZXItYm90dG9tLXJpZ2h0LXJhZGl1czogMDtcbiAgYm9yZGVyLWJvdHRvbS1sZWZ0LXJhZGl1czogMDsgfVxuXG4uYnRuLWdyb3VwLXZlcnRpY2FsID4gLmJ0bi1ncm91cDpsYXN0LWNoaWxkOm5vdCg6Zmlyc3QtY2hpbGQpID4gLmJ0bjpmaXJzdC1jaGlsZCwgLmJ0bi1ncm91cC12ZXJ0aWNhbCA+IC5idG4tZ3JvdXA6bGFzdC1jaGlsZDpub3QoOmZpcnN0LWNoaWxkKSA+IGJ1dHRvbi5jdXN0b206Zmlyc3QtY2hpbGQge1xuICBib3JkZXItdG9wLWxlZnQtcmFkaXVzOiAwO1xuICBib3JkZXItdG9wLXJpZ2h0LXJhZGl1czogMDsgfVxuXG5bZGF0YS10b2dnbGU9XCJidXR0b25zXCJdID4gLmJ0biBpbnB1dFt0eXBlPVwicmFkaW9cIl0sIFtkYXRhLXRvZ2dsZT1cImJ1dHRvbnNcIl0gPiBidXR0b24uY3VzdG9tIGlucHV0W3R5cGU9XCJyYWRpb1wiXSxcbltkYXRhLXRvZ2dsZT1cImJ1dHRvbnNcIl0gPiAuYnRuIGlucHV0W3R5cGU9XCJjaGVja2JveFwiXSxcbltkYXRhLXRvZ2dsZT1cImJ1dHRvbnNcIl0gPiBidXR0b24uY3VzdG9tIGlucHV0W3R5cGU9XCJjaGVja2JveFwiXSxcbltkYXRhLXRvZ2dsZT1cImJ1dHRvbnNcIl0gPiAuYnRuLWdyb3VwID4gLmJ0biBpbnB1dFt0eXBlPVwicmFkaW9cIl0sXG5bZGF0YS10b2dnbGU9XCJidXR0b25zXCJdID4gLmJ0bi1ncm91cCA+IGJ1dHRvbi5jdXN0b20gaW5wdXRbdHlwZT1cInJhZGlvXCJdLFxuW2RhdGEtdG9nZ2xlPVwiYnV0dG9uc1wiXSA+IC5idG4tZ3JvdXAgPiAuYnRuIGlucHV0W3R5cGU9XCJjaGVja2JveFwiXSxcbltkYXRhLXRvZ2dsZT1cImJ1dHRvbnNcIl0gPiAuYnRuLWdyb3VwID4gYnV0dG9uLmN1c3RvbSBpbnB1dFt0eXBlPVwiY2hlY2tib3hcIl0ge1xuICBwb3NpdGlvbjogYWJzb2x1dGU7XG4gIGNsaXA6IHJlY3QoMCwgMCwgMCwgMCk7XG4gIHBvaW50ZXItZXZlbnRzOiBub25lOyB9XG5cbi5pbnB1dC1ncm91cCB7XG4gIHBvc2l0aW9uOiByZWxhdGl2ZTtcbiAgZGlzcGxheTogZmxleDtcbiAgd2lkdGg6IDEwMCU7IH1cbiAgLmlucHV0LWdyb3VwIC5mb3JtLWNvbnRyb2wge1xuICAgIHBvc2l0aW9uOiByZWxhdGl2ZTtcbiAgICB6LWluZGV4OiAyO1xuICAgIGZsZXg6IDEgMSBhdXRvO1xuICAgIHdpZHRoOiAxJTtcbiAgICBtYXJnaW4tYm90dG9tOiAwOyB9XG4gICAgLmlucHV0LWdyb3VwIC5mb3JtLWNvbnRyb2w6Zm9jdXMsIC5pbnB1dC1ncm91cCAuZm9ybS1jb250cm9sOmFjdGl2ZSwgLmlucHV0LWdyb3VwIC5mb3JtLWNvbnRyb2w6aG92ZXIge1xuICAgICAgei1pbmRleDogMzsgfVxuXG4uaW5wdXQtZ3JvdXAtYWRkb24sXG4uaW5wdXQtZ3JvdXAtYnRuLFxuLmlucHV0LWdyb3VwIC5mb3JtLWNvbnRyb2wge1xuICBkaXNwbGF5OiBmbGV4O1xuICBhbGlnbi1pdGVtczogY2VudGVyOyB9XG4gIC5pbnB1dC1ncm91cC1hZGRvbjpub3QoOmZpcnN0LWNoaWxkKTpub3QoOmxhc3QtY2hpbGQpLFxuICAuaW5wdXQtZ3JvdXAtYnRuOm5vdCg6Zmlyc3QtY2hpbGQpOm5vdCg6bGFzdC1jaGlsZCksXG4gIC5pbnB1dC1ncm91cCAuZm9ybS1jb250cm9sOm5vdCg6Zmlyc3QtY2hpbGQpOm5vdCg6bGFzdC1jaGlsZCkge1xuICAgIGJvcmRlci1yYWRpdXM6IDA7IH1cblxuLmlucHV0LWdyb3VwLWFkZG9uLFxuLmlucHV0LWdyb3VwLWJ0biB7XG4gIHdoaXRlLXNwYWNlOiBub3dyYXA7XG4gIHZlcnRpY2FsLWFsaWduOiBtaWRkbGU7IH1cblxuLmlucHV0LWdyb3VwLWFkZG9uIHtcbiAgcGFkZGluZzogMC41cmVtIDAuNzVyZW07XG4gIG1hcmdpbi1ib3R0b206IDA7XG4gIGZvbnQtc2l6ZTogMXJlbTtcbiAgZm9udC13ZWlnaHQ6IG5vcm1hbDtcbiAgbGluZS1oZWlnaHQ6IDEuMjU7XG4gIGNvbG9yOiAjNDk1MDU3O1xuICB0ZXh0LWFsaWduOiBjZW50ZXI7XG4gIGJhY2tncm91bmQtY29sb3I6ICNlOWVjZWY7XG4gIGJhY2tncm91bmQtY2xpcDogcGFkZGluZy1ib3g7XG4gIGJvcmRlcjogMXB4IHNvbGlkIHJnYmEoMCwgMCwgMCwgMC4xNSk7XG4gIGJvcmRlci1yYWRpdXM6IDAuMjVyZW07IH1cbiAgLmlucHV0LWdyb3VwLWFkZG9uLmZvcm0tY29udHJvbC1zbSxcbiAgLmlucHV0LWdyb3VwLXNtID4gLmlucHV0LWdyb3VwLWFkZG9uLFxuICAuaW5wdXQtZ3JvdXAtc20gPiAuaW5wdXQtZ3JvdXAtYnRuID4gLmlucHV0LWdyb3VwLWFkZG9uLmJ0bixcbiAgLmlucHV0LWdyb3VwLXNtID4gLmlucHV0LWdyb3VwLWJ0biA+IGJ1dHRvbi5pbnB1dC1ncm91cC1hZGRvbi5jdXN0b20ge1xuICAgIHBhZGRpbmc6IDAuMjVyZW0gMC41cmVtO1xuICAgIGZvbnQtc2l6ZTogMC44NzVyZW07XG4gICAgYm9yZGVyLXJhZGl1czogMC4ycmVtOyB9XG4gIC5pbnB1dC1ncm91cC1hZGRvbi5mb3JtLWNvbnRyb2wtbGcsXG4gIC5pbnB1dC1ncm91cC1sZyA+IC5pbnB1dC1ncm91cC1hZGRvbixcbiAgLmlucHV0LWdyb3VwLWxnID4gLmlucHV0LWdyb3VwLWJ0biA+IC5pbnB1dC1ncm91cC1hZGRvbi5idG4sXG4gIC5pbnB1dC1ncm91cC1sZyA+IC5pbnB1dC1ncm91cC1idG4gPiBidXR0b24uaW5wdXQtZ3JvdXAtYWRkb24uY3VzdG9tIHtcbiAgICBwYWRkaW5nOiAwLjVyZW0gMXJlbTtcbiAgICBmb250LXNpemU6IDEuMjVyZW07XG4gICAgYm9yZGVyLXJhZGl1czogMC4zcmVtOyB9XG4gIC5pbnB1dC1ncm91cC1hZGRvbiBpbnB1dFt0eXBlPVwicmFkaW9cIl0sXG4gIC5pbnB1dC1ncm91cC1hZGRvbiBpbnB1dFt0eXBlPVwiY2hlY2tib3hcIl0ge1xuICAgIG1hcmdpbi10b3A6IDA7IH1cblxuLmlucHV0LWdyb3VwIC5mb3JtLWNvbnRyb2w6bm90KDpsYXN0LWNoaWxkKSxcbi5pbnB1dC1ncm91cC1hZGRvbjpub3QoOmxhc3QtY2hpbGQpLFxuLmlucHV0LWdyb3VwLWJ0bjpub3QoOmxhc3QtY2hpbGQpID4gLmJ0bixcbi5pbnB1dC1ncm91cC1idG46bm90KDpsYXN0LWNoaWxkKSA+IGJ1dHRvbi5jdXN0b20sXG4uaW5wdXQtZ3JvdXAtYnRuOm5vdCg6bGFzdC1jaGlsZCkgPiAuYnRuLWdyb3VwID4gLmJ0bixcbi5pbnB1dC1ncm91cC1idG46bm90KDpsYXN0LWNoaWxkKSA+IC5idG4tZ3JvdXAgPiBidXR0b24uY3VzdG9tLFxuLmlucHV0LWdyb3VwLWJ0bjpub3QoOmxhc3QtY2hpbGQpID4gLmRyb3Bkb3duLXRvZ2dsZSxcbi5pbnB1dC1ncm91cC1idG46bm90KDpmaXJzdC1jaGlsZCkgPiAuYnRuOm5vdCg6bGFzdC1jaGlsZCk6bm90KC5kcm9wZG93bi10b2dnbGUpLFxuLmlucHV0LWdyb3VwLWJ0bjpub3QoOmZpcnN0LWNoaWxkKSA+IGJ1dHRvbi5jdXN0b206bm90KDpsYXN0LWNoaWxkKTpub3QoLmRyb3Bkb3duLXRvZ2dsZSksXG4uaW5wdXQtZ3JvdXAtYnRuOm5vdCg6Zmlyc3QtY2hpbGQpID4gLmJ0bi1ncm91cDpub3QoOmxhc3QtY2hpbGQpID4gLmJ0bixcbi5pbnB1dC1ncm91cC1idG46bm90KDpmaXJzdC1jaGlsZCkgPiAuYnRuLWdyb3VwOm5vdCg6bGFzdC1jaGlsZCkgPiBidXR0b24uY3VzdG9tIHtcbiAgYm9yZGVyLXRvcC1yaWdodC1yYWRpdXM6IDA7XG4gIGJvcmRlci1ib3R0b20tcmlnaHQtcmFkaXVzOiAwOyB9XG5cbi5pbnB1dC1ncm91cC1hZGRvbjpub3QoOmxhc3QtY2hpbGQpIHtcbiAgYm9yZGVyLXJpZ2h0OiAwOyB9XG5cbi5pbnB1dC1ncm91cCAuZm9ybS1jb250cm9sOm5vdCg6Zmlyc3QtY2hpbGQpLFxuLmlucHV0LWdyb3VwLWFkZG9uOm5vdCg6Zmlyc3QtY2hpbGQpLFxuLmlucHV0LWdyb3VwLWJ0bjpub3QoOmZpcnN0LWNoaWxkKSA+IC5idG4sXG4uaW5wdXQtZ3JvdXAtYnRuOm5vdCg6Zmlyc3QtY2hpbGQpID4gYnV0dG9uLmN1c3RvbSxcbi5pbnB1dC1ncm91cC1idG46bm90KDpmaXJzdC1jaGlsZCkgPiAuYnRuLWdyb3VwID4gLmJ0bixcbi5pbnB1dC1ncm91cC1idG46bm90KDpmaXJzdC1jaGlsZCkgPiAuYnRuLWdyb3VwID4gYnV0dG9uLmN1c3RvbSxcbi5pbnB1dC1ncm91cC1idG46bm90KDpmaXJzdC1jaGlsZCkgPiAuZHJvcGRvd24tdG9nZ2xlLFxuLmlucHV0LWdyb3VwLWJ0bjpub3QoOmxhc3QtY2hpbGQpID4gLmJ0bjpub3QoOmZpcnN0LWNoaWxkKSxcbi5pbnB1dC1ncm91cC1idG46bm90KDpsYXN0LWNoaWxkKSA+IGJ1dHRvbi5jdXN0b206bm90KDpmaXJzdC1jaGlsZCksXG4uaW5wdXQtZ3JvdXAtYnRuOm5vdCg6bGFzdC1jaGlsZCkgPiAuYnRuLWdyb3VwOm5vdCg6Zmlyc3QtY2hpbGQpID4gLmJ0bixcbi5pbnB1dC1ncm91cC1idG46bm90KDpsYXN0LWNoaWxkKSA+IC5idG4tZ3JvdXA6bm90KDpmaXJzdC1jaGlsZCkgPiBidXR0b24uY3VzdG9tIHtcbiAgYm9yZGVyLXRvcC1sZWZ0LXJhZGl1czogMDtcbiAgYm9yZGVyLWJvdHRvbS1sZWZ0LXJhZGl1czogMDsgfVxuXG4uZm9ybS1jb250cm9sICsgLmlucHV0LWdyb3VwLWFkZG9uOm5vdCg6Zmlyc3QtY2hpbGQpIHtcbiAgYm9yZGVyLWxlZnQ6IDA7IH1cblxuLmlucHV0LWdyb3VwLWJ0biB7XG4gIHBvc2l0aW9uOiByZWxhdGl2ZTtcbiAgZm9udC1zaXplOiAwO1xuICB3aGl0ZS1zcGFjZTogbm93cmFwOyB9XG4gIC5pbnB1dC1ncm91cC1idG4gPiAuYnRuLCAuaW5wdXQtZ3JvdXAtYnRuID4gYnV0dG9uLmN1c3RvbSB7XG4gICAgcG9zaXRpb246IHJlbGF0aXZlO1xuICAgIGJhY2tncm91bmQtY2xpcDogcGFkZGluZy1ib3g7XG4gICAgYm9yZGVyOiAxcHggc29saWQgcmdiYSgwLCAwLCAwLCAwLjE1KTsgfVxuICAgIC5pbnB1dC1ncm91cC1idG4gPiAuYnRuICsgLmJ0biwgLmlucHV0LWdyb3VwLWJ0biA+IGJ1dHRvbi5jdXN0b20gKyAuYnRuLCAuaW5wdXQtZ3JvdXAtYnRuID4gLmJ0biArIGJ1dHRvbi5jdXN0b20sIC5pbnB1dC1ncm91cC1idG4gPiBidXR0b24uY3VzdG9tICsgYnV0dG9uLmN1c3RvbSB7XG4gICAgICBtYXJnaW4tbGVmdDogLTFweDsgfVxuICAgIC5pbnB1dC1ncm91cC1idG4gPiAuYnRuOmZvY3VzLCAuaW5wdXQtZ3JvdXAtYnRuID4gYnV0dG9uLmN1c3RvbTpmb2N1cywgLmlucHV0LWdyb3VwLWJ0biA+IC5idG46YWN0aXZlLCAuaW5wdXQtZ3JvdXAtYnRuID4gYnV0dG9uLmN1c3RvbTphY3RpdmUsIC5pbnB1dC1ncm91cC1idG4gPiAuYnRuOmhvdmVyLCAuaW5wdXQtZ3JvdXAtYnRuID4gYnV0dG9uLmN1c3RvbTpob3ZlciB7XG4gICAgICB6LWluZGV4OiAzOyB9XG4gIC5pbnB1dC1ncm91cC1idG46bm90KDpsYXN0LWNoaWxkKSA+IC5idG4sIC5pbnB1dC1ncm91cC1idG46bm90KDpsYXN0LWNoaWxkKSA+IGJ1dHRvbi5jdXN0b20sXG4gIC5pbnB1dC1ncm91cC1idG46bm90KDpsYXN0LWNoaWxkKSA+IC5idG4tZ3JvdXAge1xuICAgIG1hcmdpbi1yaWdodDogLTFweDsgfVxuICAuaW5wdXQtZ3JvdXAtYnRuOm5vdCg6Zmlyc3QtY2hpbGQpID4gLmJ0biwgLmlucHV0LWdyb3VwLWJ0bjpub3QoOmZpcnN0LWNoaWxkKSA+IGJ1dHRvbi5jdXN0b20sXG4gIC5pbnB1dC1ncm91cC1idG46bm90KDpmaXJzdC1jaGlsZCkgPiAuYnRuLWdyb3VwIHtcbiAgICB6LWluZGV4OiAyO1xuICAgIG1hcmdpbi1sZWZ0OiAtMXB4OyB9XG4gICAgLmlucHV0LWdyb3VwLWJ0bjpub3QoOmZpcnN0LWNoaWxkKSA+IC5idG46Zm9jdXMsIC5pbnB1dC1ncm91cC1idG46bm90KDpmaXJzdC1jaGlsZCkgPiBidXR0b24uY3VzdG9tOmZvY3VzLCAuaW5wdXQtZ3JvdXAtYnRuOm5vdCg6Zmlyc3QtY2hpbGQpID4gLmJ0bjphY3RpdmUsIC5pbnB1dC1ncm91cC1idG46bm90KDpmaXJzdC1jaGlsZCkgPiBidXR0b24uY3VzdG9tOmFjdGl2ZSwgLmlucHV0LWdyb3VwLWJ0bjpub3QoOmZpcnN0LWNoaWxkKSA+IC5idG46aG92ZXIsIC5pbnB1dC1ncm91cC1idG46bm90KDpmaXJzdC1jaGlsZCkgPiBidXR0b24uY3VzdG9tOmhvdmVyLFxuICAgIC5pbnB1dC1ncm91cC1idG46bm90KDpmaXJzdC1jaGlsZCkgPiAuYnRuLWdyb3VwOmZvY3VzLFxuICAgIC5pbnB1dC1ncm91cC1idG46bm90KDpmaXJzdC1jaGlsZCkgPiAuYnRuLWdyb3VwOmFjdGl2ZSxcbiAgICAuaW5wdXQtZ3JvdXAtYnRuOm5vdCg6Zmlyc3QtY2hpbGQpID4gLmJ0bi1ncm91cDpob3ZlciB7XG4gICAgICB6LWluZGV4OiAzOyB9XG5cbi5jdXN0b20tY29udHJvbCB7XG4gIHBvc2l0aW9uOiByZWxhdGl2ZTtcbiAgZGlzcGxheTogaW5saW5lLWZsZXg7XG4gIG1pbi1oZWlnaHQ6IDEuNXJlbTtcbiAgcGFkZGluZy1sZWZ0OiAxLjVyZW07XG4gIG1hcmdpbi1yaWdodDogMXJlbTsgfVxuXG4uY3VzdG9tLWNvbnRyb2wtaW5wdXQge1xuICBwb3NpdGlvbjogYWJzb2x1dGU7XG4gIHotaW5kZXg6IC0xO1xuICBvcGFjaXR5OiAwOyB9XG4gIC5jdXN0b20tY29udHJvbC1pbnB1dDpjaGVja2VkIH4gLmN1c3RvbS1jb250cm9sLWluZGljYXRvciB7XG4gICAgY29sb3I6ICNmZmY7XG4gICAgYmFja2dyb3VuZC1jb2xvcjogIzAwN2JmZjsgfVxuICAuY3VzdG9tLWNvbnRyb2wtaW5wdXQ6Zm9jdXMgfiAuY3VzdG9tLWNvbnRyb2wtaW5kaWNhdG9yIHtcbiAgICBib3gtc2hhZG93OiAwIDAgMCAxcHggI2ZmZiwgMCAwIDAgM3B4ICMwMDdiZmY7IH1cbiAgLmN1c3RvbS1jb250cm9sLWlucHV0OmFjdGl2ZSB+IC5jdXN0b20tY29udHJvbC1pbmRpY2F0b3Ige1xuICAgIGNvbG9yOiAjZmZmO1xuICAgIGJhY2tncm91bmQtY29sb3I6ICNiM2Q3ZmY7IH1cbiAgLmN1c3RvbS1jb250cm9sLWlucHV0OmRpc2FibGVkIH4gLmN1c3RvbS1jb250cm9sLWluZGljYXRvciB7XG4gICAgYmFja2dyb3VuZC1jb2xvcjogI2U5ZWNlZjsgfVxuICAuY3VzdG9tLWNvbnRyb2wtaW5wdXQ6ZGlzYWJsZWQgfiAuY3VzdG9tLWNvbnRyb2wtZGVzY3JpcHRpb24ge1xuICAgIGNvbG9yOiAjODY4ZTk2OyB9XG5cbi5jdXN0b20tY29udHJvbC1pbmRpY2F0b3Ige1xuICBwb3NpdGlvbjogYWJzb2x1dGU7XG4gIHRvcDogMC4yNXJlbTtcbiAgbGVmdDogMDtcbiAgZGlzcGxheTogYmxvY2s7XG4gIHdpZHRoOiAxcmVtO1xuICBoZWlnaHQ6IDFyZW07XG4gIHBvaW50ZXItZXZlbnRzOiBub25lO1xuICB1c2VyLXNlbGVjdDogbm9uZTtcbiAgYmFja2dyb3VuZC1jb2xvcjogI2RkZDtcbiAgYmFja2dyb3VuZC1yZXBlYXQ6IG5vLXJlcGVhdDtcbiAgYmFja2dyb3VuZC1wb3NpdGlvbjogY2VudGVyIGNlbnRlcjtcbiAgYmFja2dyb3VuZC1zaXplOiA1MCUgNTAlOyB9XG5cbi5jdXN0b20tY2hlY2tib3ggLmN1c3RvbS1jb250cm9sLWluZGljYXRvciB7XG4gIGJvcmRlci1yYWRpdXM6IDAuMjVyZW07IH1cblxuLmN1c3RvbS1jaGVja2JveCAuY3VzdG9tLWNvbnRyb2wtaW5wdXQ6Y2hlY2tlZCB+IC5jdXN0b20tY29udHJvbC1pbmRpY2F0b3Ige1xuICBiYWNrZ3JvdW5kLWltYWdlOiB1cmwoXCJkYXRhOmltYWdlL3N2Zyt4bWw7Y2hhcnNldD11dGY4LCUzQ3N2ZyB4bWxucz0naHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmcnIHZpZXdCb3g9JzAgMCA4IDgnJTNFJTNDcGF0aCBmaWxsPSclMjNmZmYnIGQ9J002LjU2NC43NWwtMy41OSAzLjYxMi0xLjUzOC0xLjU1TDAgNC4yNiAyLjk3NCA3LjI1IDggMi4xOTN6Jy8lM0UlM0Mvc3ZnJTNFXCIpOyB9XG5cbi5jdXN0b20tY2hlY2tib3ggLmN1c3RvbS1jb250cm9sLWlucHV0OmluZGV0ZXJtaW5hdGUgfiAuY3VzdG9tLWNvbnRyb2wtaW5kaWNhdG9yIHtcbiAgYmFja2dyb3VuZC1jb2xvcjogIzAwN2JmZjtcbiAgYmFja2dyb3VuZC1pbWFnZTogdXJsKFwiZGF0YTppbWFnZS9zdmcreG1sO2NoYXJzZXQ9dXRmOCwlM0NzdmcgeG1sbnM9J2h0dHA6Ly93d3cudzMub3JnLzIwMDAvc3ZnJyB2aWV3Qm94PScwIDAgNCA0JyUzRSUzQ3BhdGggc3Ryb2tlPSclMjNmZmYnIGQ9J00wIDJoNCcvJTNFJTNDL3N2ZyUzRVwiKTsgfVxuXG4uY3VzdG9tLXJhZGlvIC5jdXN0b20tY29udHJvbC1pbmRpY2F0b3Ige1xuICBib3JkZXItcmFkaXVzOiA1MCU7IH1cblxuLmN1c3RvbS1yYWRpbyAuY3VzdG9tLWNvbnRyb2wtaW5wdXQ6Y2hlY2tlZCB+IC5jdXN0b20tY29udHJvbC1pbmRpY2F0b3Ige1xuICBiYWNrZ3JvdW5kLWltYWdlOiB1cmwoXCJkYXRhOmltYWdlL3N2Zyt4bWw7Y2hhcnNldD11dGY4LCUzQ3N2ZyB4bWxucz0naHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmcnIHZpZXdCb3g9Jy00IC00IDggOCclM0UlM0NjaXJjbGUgcj0nMycgZmlsbD0nJTIzZmZmJy8lM0UlM0Mvc3ZnJTNFXCIpOyB9XG5cbi5jdXN0b20tY29udHJvbHMtc3RhY2tlZCB7XG4gIGRpc3BsYXk6IGZsZXg7XG4gIGZsZXgtZGlyZWN0aW9uOiBjb2x1bW47IH1cbiAgLmN1c3RvbS1jb250cm9scy1zdGFja2VkIC5jdXN0b20tY29udHJvbCB7XG4gICAgbWFyZ2luLWJvdHRvbTogMC4yNXJlbTsgfVxuICAgIC5jdXN0b20tY29udHJvbHMtc3RhY2tlZCAuY3VzdG9tLWNvbnRyb2wgKyAuY3VzdG9tLWNvbnRyb2wge1xuICAgICAgbWFyZ2luLWxlZnQ6IDA7IH1cblxuLmN1c3RvbS1zZWxlY3Qge1xuICBkaXNwbGF5OiBpbmxpbmUtYmxvY2s7XG4gIG1heC13aWR0aDogMTAwJTtcbiAgaGVpZ2h0OiBjYWxjKDIuMjVyZW0gKyAycHgpO1xuICBwYWRkaW5nOiAwLjM3NXJlbSAxLjc1cmVtIDAuMzc1cmVtIDAuNzVyZW07XG4gIGxpbmUtaGVpZ2h0OiAxLjI1O1xuICBjb2xvcjogIzQ5NTA1NztcbiAgdmVydGljYWwtYWxpZ246IG1pZGRsZTtcbiAgYmFja2dyb3VuZDogI2ZmZiB1cmwoXCJkYXRhOmltYWdlL3N2Zyt4bWw7Y2hhcnNldD11dGY4LCUzQ3N2ZyB4bWxucz0naHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmcnIHZpZXdCb3g9JzAgMCA0IDUnJTNFJTNDcGF0aCBmaWxsPSclMjMzMzMnIGQ9J00yIDBMMCAyaDR6bTAgNUwwIDNoNHonLyUzRSUzQy9zdmclM0VcIikgbm8tcmVwZWF0IHJpZ2h0IDAuNzVyZW0gY2VudGVyO1xuICBiYWNrZ3JvdW5kLWNsaXA6IHBhZGRpbmctYm94O1xuICBiYWNrZ3JvdW5kLXNpemU6IDhweCAxMHB4O1xuICBib3JkZXI6IDFweCBzb2xpZCByZ2JhKDAsIDAsIDAsIDAuMTUpO1xuICBib3JkZXItcmFkaXVzOiAwLjI1cmVtO1xuICBhcHBlYXJhbmNlOiBub25lOyB9XG4gIC5jdXN0b20tc2VsZWN0OmZvY3VzIHtcbiAgICBib3JkZXItY29sb3I6ICM4MGJkZmY7XG4gICAgb3V0bGluZTogbm9uZTsgfVxuICAgIC5jdXN0b20tc2VsZWN0OmZvY3VzOjotbXMtdmFsdWUge1xuICAgICAgY29sb3I6ICM0OTUwNTc7XG4gICAgICBiYWNrZ3JvdW5kLWNvbG9yOiAjZmZmOyB9XG4gIC5jdXN0b20tc2VsZWN0OmRpc2FibGVkIHtcbiAgICBjb2xvcjogIzg2OGU5NjtcbiAgICBiYWNrZ3JvdW5kLWNvbG9yOiAjZTllY2VmOyB9XG4gIC5jdXN0b20tc2VsZWN0OjotbXMtZXhwYW5kIHtcbiAgICBvcGFjaXR5OiAwOyB9XG5cbi5jdXN0b20tc2VsZWN0LXNtIHtcbiAgaGVpZ2h0OiBjYWxjKDEuODEyNXJlbSArIDJweCk7XG4gIHBhZGRpbmctdG9wOiAwLjM3NXJlbTtcbiAgcGFkZGluZy1ib3R0b206IDAuMzc1cmVtO1xuICBmb250LXNpemU6IDc1JTsgfVxuXG4uY3VzdG9tLWZpbGUge1xuICBwb3NpdGlvbjogcmVsYXRpdmU7XG4gIGRpc3BsYXk6IGlubGluZS1ibG9jaztcbiAgbWF4LXdpZHRoOiAxMDAlO1xuICBoZWlnaHQ6IGNhbGMoMi4yNXJlbSArIDJweCk7XG4gIG1hcmdpbi1ib3R0b206IDA7IH1cblxuLmN1c3RvbS1maWxlLWlucHV0IHtcbiAgbWluLXdpZHRoOiAxNHJlbTtcbiAgbWF4LXdpZHRoOiAxMDAlO1xuICBoZWlnaHQ6IGNhbGMoMi4yNXJlbSArIDJweCk7XG4gIG1hcmdpbjogMDtcbiAgb3BhY2l0eTogMDsgfVxuICAuY3VzdG9tLWZpbGUtaW5wdXQ6Zm9jdXMgfiAuY3VzdG9tLWZpbGUtY29udHJvbCB7XG4gICAgYm94LXNoYWRvdzogMCAwIDAgMC4wNzVyZW0gI2ZmZiwgMCAwIDAgMC4ycmVtICMwMDdiZmY7IH1cblxuLmN1c3RvbS1maWxlLWNvbnRyb2wge1xuICBwb3NpdGlvbjogYWJzb2x1dGU7XG4gIHRvcDogMDtcbiAgcmlnaHQ6IDA7XG4gIGxlZnQ6IDA7XG4gIHotaW5kZXg6IDU7XG4gIGhlaWdodDogY2FsYygyLjI1cmVtICsgMnB4KTtcbiAgcGFkZGluZzogMC41cmVtIDAuNzVyZW07XG4gIG92ZXJmbG93OiBoaWRkZW47XG4gIGxpbmUtaGVpZ2h0OiAxLjI1O1xuICBjb2xvcjogIzQ5NTA1NztcbiAgcG9pbnRlci1ldmVudHM6IG5vbmU7XG4gIHVzZXItc2VsZWN0OiBub25lO1xuICBiYWNrZ3JvdW5kLWNvbG9yOiAjZmZmO1xuICBiYWNrZ3JvdW5kLWNsaXA6IHBhZGRpbmctYm94O1xuICBib3JkZXI6IDFweCBzb2xpZCByZ2JhKDAsIDAsIDAsIDAuMTUpO1xuICBib3JkZXItcmFkaXVzOiAwLjI1cmVtOyB9XG4gIC5jdXN0b20tZmlsZS1jb250cm9sOmxhbmcoZW4pOmVtcHR5OjphZnRlciB7XG4gICAgY29udGVudDogXCJDaG9vc2UgZmlsZS4uLlwiOyB9XG4gIC5jdXN0b20tZmlsZS1jb250cm9sOjpiZWZvcmUge1xuICAgIHBvc2l0aW9uOiBhYnNvbHV0ZTtcbiAgICB0b3A6IDA7XG4gICAgcmlnaHQ6IDA7XG4gICAgei1pbmRleDogNjtcbiAgICBkaXNwbGF5OiBibG9jaztcbiAgICBoZWlnaHQ6IGNhbGMoMi4yNXJlbSArIDJweCk7XG4gICAgcGFkZGluZzogMC41cmVtIDAuNzVyZW07XG4gICAgbGluZS1oZWlnaHQ6IDEuMjU7XG4gICAgY29sb3I6ICM0OTUwNTc7XG4gICAgYmFja2dyb3VuZC1jb2xvcjogI2U5ZWNlZjtcbiAgICBib3JkZXItbGVmdDogMXB4IHNvbGlkIHJnYmEoMCwgMCwgMCwgMC4xNSk7IH1cbiAgLmN1c3RvbS1maWxlLWNvbnRyb2w6bGFuZyhlbik6OmJlZm9yZSB7XG4gICAgY29udGVudDogXCJCcm93c2VcIjsgfVxuXG4ubmF2IHtcbiAgZGlzcGxheTogZmxleDtcbiAgZmxleC13cmFwOiB3cmFwO1xuICBwYWRkaW5nLWxlZnQ6IDA7XG4gIG1hcmdpbi1ib3R0b206IDA7XG4gIGxpc3Qtc3R5bGU6IG5vbmU7IH1cblxuLm5hdi1saW5rIHtcbiAgZGlzcGxheTogYmxvY2s7XG4gIHBhZGRpbmc6IDAuNXJlbSAxcmVtOyB9XG4gIC5uYXYtbGluazpmb2N1cywgLm5hdi1saW5rOmhvdmVyIHtcbiAgICB0ZXh0LWRlY29yYXRpb246IG5vbmU7IH1cbiAgLm5hdi1saW5rLmRpc2FibGVkIHtcbiAgICBjb2xvcjogIzg2OGU5NjsgfVxuXG4ubmF2LXRhYnMge1xuICBib3JkZXItYm90dG9tOiAxcHggc29saWQgI2RkZDsgfVxuICAubmF2LXRhYnMgLm5hdi1pdGVtIHtcbiAgICBtYXJnaW4tYm90dG9tOiAtMXB4OyB9XG4gIC5uYXYtdGFicyAubmF2LWxpbmsge1xuICAgIGJvcmRlcjogMXB4IHNvbGlkIHRyYW5zcGFyZW50O1xuICAgIGJvcmRlci10b3AtbGVmdC1yYWRpdXM6IDAuMjVyZW07XG4gICAgYm9yZGVyLXRvcC1yaWdodC1yYWRpdXM6IDAuMjVyZW07IH1cbiAgICAubmF2LXRhYnMgLm5hdi1saW5rOmZvY3VzLCAubmF2LXRhYnMgLm5hdi1saW5rOmhvdmVyIHtcbiAgICAgIGJvcmRlci1jb2xvcjogI2U5ZWNlZiAjZTllY2VmICNkZGQ7IH1cbiAgICAubmF2LXRhYnMgLm5hdi1saW5rLmRpc2FibGVkIHtcbiAgICAgIGNvbG9yOiAjODY4ZTk2O1xuICAgICAgYmFja2dyb3VuZC1jb2xvcjogdHJhbnNwYXJlbnQ7XG4gICAgICBib3JkZXItY29sb3I6IHRyYW5zcGFyZW50OyB9XG4gIC5uYXYtdGFicyAubmF2LWxpbmsuYWN0aXZlLFxuICAubmF2LXRhYnMgLm5hdi1pdGVtLnNob3cgLm5hdi1saW5rIHtcbiAgICBjb2xvcjogIzQ5NTA1NztcbiAgICBiYWNrZ3JvdW5kLWNvbG9yOiAjZmZmO1xuICAgIGJvcmRlci1jb2xvcjogI2RkZCAjZGRkICNmZmY7IH1cbiAgLm5hdi10YWJzIC5kcm9wZG93bi1tZW51IHtcbiAgICBtYXJnaW4tdG9wOiAtMXB4O1xuICAgIGJvcmRlci10b3AtbGVmdC1yYWRpdXM6IDA7XG4gICAgYm9yZGVyLXRvcC1yaWdodC1yYWRpdXM6IDA7IH1cblxuLm5hdi1waWxscyAubmF2LWxpbmsge1xuICBib3JkZXItcmFkaXVzOiAwLjI1cmVtOyB9XG4gIC5uYXYtcGlsbHMgLm5hdi1saW5rLmFjdGl2ZSxcbiAgLnNob3cgPiAubmF2LXBpbGxzIC5uYXYtbGluayB7XG4gICAgY29sb3I6ICNmZmY7XG4gICAgYmFja2dyb3VuZC1jb2xvcjogIzAwN2JmZjsgfVxuXG4ubmF2LWZpbGwgLm5hdi1pdGVtIHtcbiAgZmxleDogMSAxIGF1dG87XG4gIHRleHQtYWxpZ246IGNlbnRlcjsgfVxuXG4ubmF2LWp1c3RpZmllZCAubmF2LWl0ZW0ge1xuICBmbGV4LWJhc2lzOiAwO1xuICBmbGV4LWdyb3c6IDE7XG4gIHRleHQtYWxpZ246IGNlbnRlcjsgfVxuXG4udGFiLWNvbnRlbnQgPiAudGFiLXBhbmUge1xuICBkaXNwbGF5OiBub25lOyB9XG5cbi50YWItY29udGVudCA+IC5hY3RpdmUge1xuICBkaXNwbGF5OiBibG9jazsgfVxuXG4ubmF2YmFyIHtcbiAgcG9zaXRpb246IHJlbGF0aXZlO1xuICBkaXNwbGF5OiBmbGV4O1xuICBmbGV4LXdyYXA6IHdyYXA7XG4gIGFsaWduLWl0ZW1zOiBjZW50ZXI7XG4gIGp1c3RpZnktY29udGVudDogc3BhY2UtYmV0d2VlbjtcbiAgcGFkZGluZzogMC41cmVtIDFyZW07IH1cbiAgLm5hdmJhciA+IC5jb250YWluZXIsXG4gIC5uYXZiYXIgPiAuY29udGFpbmVyLWZsdWlkIHtcbiAgICBkaXNwbGF5OiBmbGV4O1xuICAgIGZsZXgtd3JhcDogd3JhcDtcbiAgICBhbGlnbi1pdGVtczogY2VudGVyO1xuICAgIGp1c3RpZnktY29udGVudDogc3BhY2UtYmV0d2VlbjsgfVxuXG4ubmF2YmFyLWJyYW5kIHtcbiAgZGlzcGxheTogaW5saW5lLWJsb2NrO1xuICBwYWRkaW5nLXRvcDogMC4zMTI1cmVtO1xuICBwYWRkaW5nLWJvdHRvbTogMC4zMTI1cmVtO1xuICBtYXJnaW4tcmlnaHQ6IDFyZW07XG4gIGZvbnQtc2l6ZTogMS4yNXJlbTtcbiAgbGluZS1oZWlnaHQ6IGluaGVyaXQ7XG4gIHdoaXRlLXNwYWNlOiBub3dyYXA7IH1cbiAgLm5hdmJhci1icmFuZDpmb2N1cywgLm5hdmJhci1icmFuZDpob3ZlciB7XG4gICAgdGV4dC1kZWNvcmF0aW9uOiBub25lOyB9XG5cbi5uYXZiYXItbmF2IHtcbiAgZGlzcGxheTogZmxleDtcbiAgZmxleC1kaXJlY3Rpb246IGNvbHVtbjtcbiAgcGFkZGluZy1sZWZ0OiAwO1xuICBtYXJnaW4tYm90dG9tOiAwO1xuICBsaXN0LXN0eWxlOiBub25lOyB9XG4gIC5uYXZiYXItbmF2IC5uYXYtbGluayB7XG4gICAgcGFkZGluZy1yaWdodDogMDtcbiAgICBwYWRkaW5nLWxlZnQ6IDA7IH1cbiAgLm5hdmJhci1uYXYgLmRyb3Bkb3duLW1lbnUge1xuICAgIHBvc2l0aW9uOiBzdGF0aWM7XG4gICAgZmxvYXQ6IG5vbmU7IH1cblxuLm5hdmJhci10ZXh0IHtcbiAgZGlzcGxheTogaW5saW5lLWJsb2NrO1xuICBwYWRkaW5nLXRvcDogMC41cmVtO1xuICBwYWRkaW5nLWJvdHRvbTogMC41cmVtOyB9XG5cbi5uYXZiYXItY29sbGFwc2Uge1xuICBmbGV4LWJhc2lzOiAxMDAlO1xuICBhbGlnbi1pdGVtczogY2VudGVyOyB9XG5cbi5uYXZiYXItdG9nZ2xlciB7XG4gIHBhZGRpbmc6IDAuMjVyZW0gMC43NXJlbTtcbiAgZm9udC1zaXplOiAxLjI1cmVtO1xuICBsaW5lLWhlaWdodDogMTtcbiAgYmFja2dyb3VuZDogdHJhbnNwYXJlbnQ7XG4gIGJvcmRlcjogMXB4IHNvbGlkIHRyYW5zcGFyZW50O1xuICBib3JkZXItcmFkaXVzOiAwLjI1cmVtOyB9XG4gIC5uYXZiYXItdG9nZ2xlcjpmb2N1cywgLm5hdmJhci10b2dnbGVyOmhvdmVyIHtcbiAgICB0ZXh0LWRlY29yYXRpb246IG5vbmU7IH1cblxuLm5hdmJhci10b2dnbGVyLWljb24ge1xuICBkaXNwbGF5OiBpbmxpbmUtYmxvY2s7XG4gIHdpZHRoOiAxLjVlbTtcbiAgaGVpZ2h0OiAxLjVlbTtcbiAgdmVydGljYWwtYWxpZ246IG1pZGRsZTtcbiAgY29udGVudDogXCJcIjtcbiAgYmFja2dyb3VuZDogbm8tcmVwZWF0IGNlbnRlciBjZW50ZXI7XG4gIGJhY2tncm91bmQtc2l6ZTogMTAwJSAxMDAlOyB9XG5cbkBtZWRpYSAobWF4LXdpZHRoOiA1NzVweCkge1xuICAubmF2YmFyLWV4cGFuZC1zbSA+IC5jb250YWluZXIsXG4gIC5uYXZiYXItZXhwYW5kLXNtID4gLmNvbnRhaW5lci1mbHVpZCB7XG4gICAgcGFkZGluZy1yaWdodDogMDtcbiAgICBwYWRkaW5nLWxlZnQ6IDA7IH0gfVxuXG5AbWVkaWEgKG1pbi13aWR0aDogNTc2cHgpIHtcbiAgLm5hdmJhci1leHBhbmQtc20ge1xuICAgIGZsZXgtZGlyZWN0aW9uOiByb3c7XG4gICAgZmxleC13cmFwOiBub3dyYXA7XG4gICAganVzdGlmeS1jb250ZW50OiBmbGV4LXN0YXJ0OyB9XG4gICAgLm5hdmJhci1leHBhbmQtc20gLm5hdmJhci1uYXYge1xuICAgICAgZmxleC1kaXJlY3Rpb246IHJvdzsgfVxuICAgICAgLm5hdmJhci1leHBhbmQtc20gLm5hdmJhci1uYXYgLmRyb3Bkb3duLW1lbnUge1xuICAgICAgICBwb3NpdGlvbjogYWJzb2x1dGU7IH1cbiAgICAgIC5uYXZiYXItZXhwYW5kLXNtIC5uYXZiYXItbmF2IC5kcm9wZG93bi1tZW51LXJpZ2h0IHtcbiAgICAgICAgcmlnaHQ6IDA7XG4gICAgICAgIGxlZnQ6IGF1dG87IH1cbiAgICAgIC5uYXZiYXItZXhwYW5kLXNtIC5uYXZiYXItbmF2IC5uYXYtbGluayB7XG4gICAgICAgIHBhZGRpbmctcmlnaHQ6IC41cmVtO1xuICAgICAgICBwYWRkaW5nLWxlZnQ6IC41cmVtOyB9XG4gICAgLm5hdmJhci1leHBhbmQtc20gPiAuY29udGFpbmVyLFxuICAgIC5uYXZiYXItZXhwYW5kLXNtID4gLmNvbnRhaW5lci1mbHVpZCB7XG4gICAgICBmbGV4LXdyYXA6IG5vd3JhcDsgfVxuICAgIC5uYXZiYXItZXhwYW5kLXNtIC5uYXZiYXItY29sbGFwc2Uge1xuICAgICAgZGlzcGxheTogZmxleCAhaW1wb3J0YW50OyB9XG4gICAgLm5hdmJhci1leHBhbmQtc20gLm5hdmJhci10b2dnbGVyIHtcbiAgICAgIGRpc3BsYXk6IG5vbmU7IH0gfVxuXG5AbWVkaWEgKG1heC13aWR0aDogNzY3cHgpIHtcbiAgLm5hdmJhci1leHBhbmQtbWQgPiAuY29udGFpbmVyLFxuICAubmF2YmFyLWV4cGFuZC1tZCA+IC5jb250YWluZXItZmx1aWQge1xuICAgIHBhZGRpbmctcmlnaHQ6IDA7XG4gICAgcGFkZGluZy1sZWZ0OiAwOyB9IH1cblxuQG1lZGlhIChtaW4td2lkdGg6IDc2OHB4KSB7XG4gIC5uYXZiYXItZXhwYW5kLW1kIHtcbiAgICBmbGV4LWRpcmVjdGlvbjogcm93O1xuICAgIGZsZXgtd3JhcDogbm93cmFwO1xuICAgIGp1c3RpZnktY29udGVudDogZmxleC1zdGFydDsgfVxuICAgIC5uYXZiYXItZXhwYW5kLW1kIC5uYXZiYXItbmF2IHtcbiAgICAgIGZsZXgtZGlyZWN0aW9uOiByb3c7IH1cbiAgICAgIC5uYXZiYXItZXhwYW5kLW1kIC5uYXZiYXItbmF2IC5kcm9wZG93bi1tZW51IHtcbiAgICAgICAgcG9zaXRpb246IGFic29sdXRlOyB9XG4gICAgICAubmF2YmFyLWV4cGFuZC1tZCAubmF2YmFyLW5hdiAuZHJvcGRvd24tbWVudS1yaWdodCB7XG4gICAgICAgIHJpZ2h0OiAwO1xuICAgICAgICBsZWZ0OiBhdXRvOyB9XG4gICAgICAubmF2YmFyLWV4cGFuZC1tZCAubmF2YmFyLW5hdiAubmF2LWxpbmsge1xuICAgICAgICBwYWRkaW5nLXJpZ2h0OiAuNXJlbTtcbiAgICAgICAgcGFkZGluZy1sZWZ0OiAuNXJlbTsgfVxuICAgIC5uYXZiYXItZXhwYW5kLW1kID4gLmNvbnRhaW5lcixcbiAgICAubmF2YmFyLWV4cGFuZC1tZCA+IC5jb250YWluZXItZmx1aWQge1xuICAgICAgZmxleC13cmFwOiBub3dyYXA7IH1cbiAgICAubmF2YmFyLWV4cGFuZC1tZCAubmF2YmFyLWNvbGxhcHNlIHtcbiAgICAgIGRpc3BsYXk6IGZsZXggIWltcG9ydGFudDsgfVxuICAgIC5uYXZiYXItZXhwYW5kLW1kIC5uYXZiYXItdG9nZ2xlciB7XG4gICAgICBkaXNwbGF5OiBub25lOyB9IH1cblxuQG1lZGlhIChtYXgtd2lkdGg6IDk5MXB4KSB7XG4gIC5uYXZiYXItZXhwYW5kLWxnID4gLmNvbnRhaW5lcixcbiAgLm5hdmJhci1leHBhbmQtbGcgPiAuY29udGFpbmVyLWZsdWlkIHtcbiAgICBwYWRkaW5nLXJpZ2h0OiAwO1xuICAgIHBhZGRpbmctbGVmdDogMDsgfSB9XG5cbkBtZWRpYSAobWluLXdpZHRoOiA5OTJweCkge1xuICAubmF2YmFyLWV4cGFuZC1sZyB7XG4gICAgZmxleC1kaXJlY3Rpb246IHJvdztcbiAgICBmbGV4LXdyYXA6IG5vd3JhcDtcbiAgICBqdXN0aWZ5LWNvbnRlbnQ6IGZsZXgtc3RhcnQ7IH1cbiAgICAubmF2YmFyLWV4cGFuZC1sZyAubmF2YmFyLW5hdiB7XG4gICAgICBmbGV4LWRpcmVjdGlvbjogcm93OyB9XG4gICAgICAubmF2YmFyLWV4cGFuZC1sZyAubmF2YmFyLW5hdiAuZHJvcGRvd24tbWVudSB7XG4gICAgICAgIHBvc2l0aW9uOiBhYnNvbHV0ZTsgfVxuICAgICAgLm5hdmJhci1leHBhbmQtbGcgLm5hdmJhci1uYXYgLmRyb3Bkb3duLW1lbnUtcmlnaHQge1xuICAgICAgICByaWdodDogMDtcbiAgICAgICAgbGVmdDogYXV0bzsgfVxuICAgICAgLm5hdmJhci1leHBhbmQtbGcgLm5hdmJhci1uYXYgLm5hdi1saW5rIHtcbiAgICAgICAgcGFkZGluZy1yaWdodDogLjVyZW07XG4gICAgICAgIHBhZGRpbmctbGVmdDogLjVyZW07IH1cbiAgICAubmF2YmFyLWV4cGFuZC1sZyA+IC5jb250YWluZXIsXG4gICAgLm5hdmJhci1leHBhbmQtbGcgPiAuY29udGFpbmVyLWZsdWlkIHtcbiAgICAgIGZsZXgtd3JhcDogbm93cmFwOyB9XG4gICAgLm5hdmJhci1leHBhbmQtbGcgLm5hdmJhci1jb2xsYXBzZSB7XG4gICAgICBkaXNwbGF5OiBmbGV4ICFpbXBvcnRhbnQ7IH1cbiAgICAubmF2YmFyLWV4cGFuZC1sZyAubmF2YmFyLXRvZ2dsZXIge1xuICAgICAgZGlzcGxheTogbm9uZTsgfSB9XG5cbkBtZWRpYSAobWF4LXdpZHRoOiAxMTk5cHgpIHtcbiAgLm5hdmJhci1leHBhbmQteGwgPiAuY29udGFpbmVyLFxuICAubmF2YmFyLWV4cGFuZC14bCA+IC5jb250YWluZXItZmx1aWQge1xuICAgIHBhZGRpbmctcmlnaHQ6IDA7XG4gICAgcGFkZGluZy1sZWZ0OiAwOyB9IH1cblxuQG1lZGlhIChtaW4td2lkdGg6IDEyMDBweCkge1xuICAubmF2YmFyLWV4cGFuZC14bCB7XG4gICAgZmxleC1kaXJlY3Rpb246IHJvdztcbiAgICBmbGV4LXdyYXA6IG5vd3JhcDtcbiAgICBqdXN0aWZ5LWNvbnRlbnQ6IGZsZXgtc3RhcnQ7IH1cbiAgICAubmF2YmFyLWV4cGFuZC14bCAubmF2YmFyLW5hdiB7XG4gICAgICBmbGV4LWRpcmVjdGlvbjogcm93OyB9XG4gICAgICAubmF2YmFyLWV4cGFuZC14bCAubmF2YmFyLW5hdiAuZHJvcGRvd24tbWVudSB7XG4gICAgICAgIHBvc2l0aW9uOiBhYnNvbHV0ZTsgfVxuICAgICAgLm5hdmJhci1leHBhbmQteGwgLm5hdmJhci1uYXYgLmRyb3Bkb3duLW1lbnUtcmlnaHQge1xuICAgICAgICByaWdodDogMDtcbiAgICAgICAgbGVmdDogYXV0bzsgfVxuICAgICAgLm5hdmJhci1leHBhbmQteGwgLm5hdmJhci1uYXYgLm5hdi1saW5rIHtcbiAgICAgICAgcGFkZGluZy1yaWdodDogLjVyZW07XG4gICAgICAgIHBhZGRpbmctbGVmdDogLjVyZW07IH1cbiAgICAubmF2YmFyLWV4cGFuZC14bCA+IC5jb250YWluZXIsXG4gICAgLm5hdmJhci1leHBhbmQteGwgPiAuY29udGFpbmVyLWZsdWlkIHtcbiAgICAgIGZsZXgtd3JhcDogbm93cmFwOyB9XG4gICAgLm5hdmJhci1leHBhbmQteGwgLm5hdmJhci1jb2xsYXBzZSB7XG4gICAgICBkaXNwbGF5OiBmbGV4ICFpbXBvcnRhbnQ7IH1cbiAgICAubmF2YmFyLWV4cGFuZC14bCAubmF2YmFyLXRvZ2dsZXIge1xuICAgICAgZGlzcGxheTogbm9uZTsgfSB9XG5cbi5uYXZiYXItZXhwYW5kIHtcbiAgZmxleC1kaXJlY3Rpb246IHJvdztcbiAgZmxleC13cmFwOiBub3dyYXA7XG4gIGp1c3RpZnktY29udGVudDogZmxleC1zdGFydDsgfVxuICAubmF2YmFyLWV4cGFuZCA+IC5jb250YWluZXIsXG4gIC5uYXZiYXItZXhwYW5kID4gLmNvbnRhaW5lci1mbHVpZCB7XG4gICAgcGFkZGluZy1yaWdodDogMDtcbiAgICBwYWRkaW5nLWxlZnQ6IDA7IH1cbiAgLm5hdmJhci1leHBhbmQgLm5hdmJhci1uYXYge1xuICAgIGZsZXgtZGlyZWN0aW9uOiByb3c7IH1cbiAgICAubmF2YmFyLWV4cGFuZCAubmF2YmFyLW5hdiAuZHJvcGRvd24tbWVudSB7XG4gICAgICBwb3NpdGlvbjogYWJzb2x1dGU7IH1cbiAgICAubmF2YmFyLWV4cGFuZCAubmF2YmFyLW5hdiAuZHJvcGRvd24tbWVudS1yaWdodCB7XG4gICAgICByaWdodDogMDtcbiAgICAgIGxlZnQ6IGF1dG87IH1cbiAgICAubmF2YmFyLWV4cGFuZCAubmF2YmFyLW5hdiAubmF2LWxpbmsge1xuICAgICAgcGFkZGluZy1yaWdodDogLjVyZW07XG4gICAgICBwYWRkaW5nLWxlZnQ6IC41cmVtOyB9XG4gIC5uYXZiYXItZXhwYW5kID4gLmNvbnRhaW5lcixcbiAgLm5hdmJhci1leHBhbmQgPiAuY29udGFpbmVyLWZsdWlkIHtcbiAgICBmbGV4LXdyYXA6IG5vd3JhcDsgfVxuICAubmF2YmFyLWV4cGFuZCAubmF2YmFyLWNvbGxhcHNlIHtcbiAgICBkaXNwbGF5OiBmbGV4ICFpbXBvcnRhbnQ7IH1cbiAgLm5hdmJhci1leHBhbmQgLm5hdmJhci10b2dnbGVyIHtcbiAgICBkaXNwbGF5OiBub25lOyB9XG5cbi5uYXZiYXItbGlnaHQgLm5hdmJhci1icmFuZCB7XG4gIGNvbG9yOiByZ2JhKDAsIDAsIDAsIDAuOSk7IH1cbiAgLm5hdmJhci1saWdodCAubmF2YmFyLWJyYW5kOmZvY3VzLCAubmF2YmFyLWxpZ2h0IC5uYXZiYXItYnJhbmQ6aG92ZXIge1xuICAgIGNvbG9yOiByZ2JhKDAsIDAsIDAsIDAuOSk7IH1cblxuLm5hdmJhci1saWdodCAubmF2YmFyLW5hdiAubmF2LWxpbmsge1xuICBjb2xvcjogcmdiYSgwLCAwLCAwLCAwLjUpOyB9XG4gIC5uYXZiYXItbGlnaHQgLm5hdmJhci1uYXYgLm5hdi1saW5rOmZvY3VzLCAubmF2YmFyLWxpZ2h0IC5uYXZiYXItbmF2IC5uYXYtbGluazpob3ZlciB7XG4gICAgY29sb3I6IHJnYmEoMCwgMCwgMCwgMC43KTsgfVxuICAubmF2YmFyLWxpZ2h0IC5uYXZiYXItbmF2IC5uYXYtbGluay5kaXNhYmxlZCB7XG4gICAgY29sb3I6IHJnYmEoMCwgMCwgMCwgMC4zKTsgfVxuXG4ubmF2YmFyLWxpZ2h0IC5uYXZiYXItbmF2IC5zaG93ID4gLm5hdi1saW5rLFxuLm5hdmJhci1saWdodCAubmF2YmFyLW5hdiAuYWN0aXZlID4gLm5hdi1saW5rLFxuLm5hdmJhci1saWdodCAubmF2YmFyLW5hdiAubmF2LWxpbmsuc2hvdyxcbi5uYXZiYXItbGlnaHQgLm5hdmJhci1uYXYgLm5hdi1saW5rLmFjdGl2ZSB7XG4gIGNvbG9yOiByZ2JhKDAsIDAsIDAsIDAuOSk7IH1cblxuLm5hdmJhci1saWdodCAubmF2YmFyLXRvZ2dsZXIge1xuICBjb2xvcjogcmdiYSgwLCAwLCAwLCAwLjUpO1xuICBib3JkZXItY29sb3I6IHJnYmEoMCwgMCwgMCwgMC4xKTsgfVxuXG4ubmF2YmFyLWxpZ2h0IC5uYXZiYXItdG9nZ2xlci1pY29uIHtcbiAgYmFja2dyb3VuZC1pbWFnZTogdXJsKFwiZGF0YTppbWFnZS9zdmcreG1sO2NoYXJzZXQ9dXRmOCwlM0Nzdmcgdmlld0JveD0nMCAwIDMwIDMwJyB4bWxucz0naHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmcnJTNFJTNDcGF0aCBzdHJva2U9J3JnYmEoMCwgMCwgMCwgMC41KScgc3Ryb2tlLXdpZHRoPScyJyBzdHJva2UtbGluZWNhcD0ncm91bmQnIHN0cm9rZS1taXRlcmxpbWl0PScxMCcgZD0nTTQgN2gyMk00IDE1aDIyTTQgMjNoMjInLyUzRSUzQy9zdmclM0VcIik7IH1cblxuLm5hdmJhci1saWdodCAubmF2YmFyLXRleHQge1xuICBjb2xvcjogcmdiYSgwLCAwLCAwLCAwLjUpOyB9XG5cbi5uYXZiYXItZGFyayAubmF2YmFyLWJyYW5kIHtcbiAgY29sb3I6IHdoaXRlOyB9XG4gIC5uYXZiYXItZGFyayAubmF2YmFyLWJyYW5kOmZvY3VzLCAubmF2YmFyLWRhcmsgLm5hdmJhci1icmFuZDpob3ZlciB7XG4gICAgY29sb3I6IHdoaXRlOyB9XG5cbi5uYXZiYXItZGFyayAubmF2YmFyLW5hdiAubmF2LWxpbmsge1xuICBjb2xvcjogcmdiYSgyNTUsIDI1NSwgMjU1LCAwLjUpOyB9XG4gIC5uYXZiYXItZGFyayAubmF2YmFyLW5hdiAubmF2LWxpbms6Zm9jdXMsIC5uYXZiYXItZGFyayAubmF2YmFyLW5hdiAubmF2LWxpbms6aG92ZXIge1xuICAgIGNvbG9yOiByZ2JhKDI1NSwgMjU1LCAyNTUsIDAuNzUpOyB9XG4gIC5uYXZiYXItZGFyayAubmF2YmFyLW5hdiAubmF2LWxpbmsuZGlzYWJsZWQge1xuICAgIGNvbG9yOiByZ2JhKDI1NSwgMjU1LCAyNTUsIDAuMjUpOyB9XG5cbi5uYXZiYXItZGFyayAubmF2YmFyLW5hdiAuc2hvdyA+IC5uYXYtbGluayxcbi5uYXZiYXItZGFyayAubmF2YmFyLW5hdiAuYWN0aXZlID4gLm5hdi1saW5rLFxuLm5hdmJhci1kYXJrIC5uYXZiYXItbmF2IC5uYXYtbGluay5zaG93LFxuLm5hdmJhci1kYXJrIC5uYXZiYXItbmF2IC5uYXYtbGluay5hY3RpdmUge1xuICBjb2xvcjogd2hpdGU7IH1cblxuLm5hdmJhci1kYXJrIC5uYXZiYXItdG9nZ2xlciB7XG4gIGNvbG9yOiByZ2JhKDI1NSwgMjU1LCAyNTUsIDAuNSk7XG4gIGJvcmRlci1jb2xvcjogcmdiYSgyNTUsIDI1NSwgMjU1LCAwLjEpOyB9XG5cbi5uYXZiYXItZGFyayAubmF2YmFyLXRvZ2dsZXItaWNvbiB7XG4gIGJhY2tncm91bmQtaW1hZ2U6IHVybChcImRhdGE6aW1hZ2Uvc3ZnK3htbDtjaGFyc2V0PXV0ZjgsJTNDc3ZnIHZpZXdCb3g9JzAgMCAzMCAzMCcgeG1sbnM9J2h0dHA6Ly93d3cudzMub3JnLzIwMDAvc3ZnJyUzRSUzQ3BhdGggc3Ryb2tlPSdyZ2JhKDI1NSwgMjU1LCAyNTUsIDAuNSknIHN0cm9rZS13aWR0aD0nMicgc3Ryb2tlLWxpbmVjYXA9J3JvdW5kJyBzdHJva2UtbWl0ZXJsaW1pdD0nMTAnIGQ9J000IDdoMjJNNCAxNWgyMk00IDIzaDIyJy8lM0UlM0Mvc3ZnJTNFXCIpOyB9XG5cbi5uYXZiYXItZGFyayAubmF2YmFyLXRleHQge1xuICBjb2xvcjogcmdiYSgyNTUsIDI1NSwgMjU1LCAwLjUpOyB9XG5cbi5jYXJkIHtcbiAgcG9zaXRpb246IHJlbGF0aXZlO1xuICBkaXNwbGF5OiBmbGV4O1xuICBmbGV4LWRpcmVjdGlvbjogY29sdW1uO1xuICBtaW4td2lkdGg6IDA7XG4gIHdvcmQtd3JhcDogYnJlYWstd29yZDtcbiAgYmFja2dyb3VuZC1jb2xvcjogI2ZmZjtcbiAgYmFja2dyb3VuZC1jbGlwOiBib3JkZXItYm94O1xuICBib3JkZXI6IDFweCBzb2xpZCByZ2JhKDAsIDAsIDAsIDAuMTI1KTtcbiAgYm9yZGVyLXJhZGl1czogMC4yNXJlbTsgfVxuXG4uY2FyZC1ib2R5IHtcbiAgZmxleDogMSAxIGF1dG87XG4gIHBhZGRpbmc6IDEuMjVyZW07IH1cblxuLmNhcmQtdGl0bGUge1xuICBtYXJnaW4tYm90dG9tOiAwLjc1cmVtOyB9XG5cbi5jYXJkLXN1YnRpdGxlIHtcbiAgbWFyZ2luLXRvcDogLTAuMzc1cmVtO1xuICBtYXJnaW4tYm90dG9tOiAwOyB9XG5cbi5jYXJkLXRleHQ6bGFzdC1jaGlsZCB7XG4gIG1hcmdpbi1ib3R0b206IDA7IH1cblxuLmNhcmQtbGluazpob3ZlciB7XG4gIHRleHQtZGVjb3JhdGlvbjogbm9uZTsgfVxuXG4uY2FyZC1saW5rICsgLmNhcmQtbGluayB7XG4gIG1hcmdpbi1sZWZ0OiAxLjI1cmVtOyB9XG5cbi5jYXJkID4gLmxpc3QtZ3JvdXA6Zmlyc3QtY2hpbGQgLmxpc3QtZ3JvdXAtaXRlbTpmaXJzdC1jaGlsZCB7XG4gIGJvcmRlci10b3AtbGVmdC1yYWRpdXM6IDAuMjVyZW07XG4gIGJvcmRlci10b3AtcmlnaHQtcmFkaXVzOiAwLjI1cmVtOyB9XG5cbi5jYXJkID4gLmxpc3QtZ3JvdXA6bGFzdC1jaGlsZCAubGlzdC1ncm91cC1pdGVtOmxhc3QtY2hpbGQge1xuICBib3JkZXItYm90dG9tLXJpZ2h0LXJhZGl1czogMC4yNXJlbTtcbiAgYm9yZGVyLWJvdHRvbS1sZWZ0LXJhZGl1czogMC4yNXJlbTsgfVxuXG4uY2FyZC1oZWFkZXIge1xuICBwYWRkaW5nOiAwLjc1cmVtIDEuMjVyZW07XG4gIG1hcmdpbi1ib3R0b206IDA7XG4gIGJhY2tncm91bmQtY29sb3I6IHJnYmEoMCwgMCwgMCwgMC4wMyk7XG4gIGJvcmRlci1ib3R0b206IDFweCBzb2xpZCByZ2JhKDAsIDAsIDAsIDAuMTI1KTsgfVxuICAuY2FyZC1oZWFkZXI6Zmlyc3QtY2hpbGQge1xuICAgIGJvcmRlci1yYWRpdXM6IGNhbGMoMC4yNXJlbSAtIDFweCkgY2FsYygwLjI1cmVtIC0gMXB4KSAwIDA7IH1cblxuLmNhcmQtZm9vdGVyIHtcbiAgcGFkZGluZzogMC43NXJlbSAxLjI1cmVtO1xuICBiYWNrZ3JvdW5kLWNvbG9yOiByZ2JhKDAsIDAsIDAsIDAuMDMpO1xuICBib3JkZXItdG9wOiAxcHggc29saWQgcmdiYSgwLCAwLCAwLCAwLjEyNSk7IH1cbiAgLmNhcmQtZm9vdGVyOmxhc3QtY2hpbGQge1xuICAgIGJvcmRlci1yYWRpdXM6IDAgMCBjYWxjKDAuMjVyZW0gLSAxcHgpIGNhbGMoMC4yNXJlbSAtIDFweCk7IH1cblxuLmNhcmQtaGVhZGVyLXRhYnMge1xuICBtYXJnaW4tcmlnaHQ6IC0wLjYyNXJlbTtcbiAgbWFyZ2luLWJvdHRvbTogLTAuNzVyZW07XG4gIG1hcmdpbi1sZWZ0OiAtMC42MjVyZW07XG4gIGJvcmRlci1ib3R0b206IDA7IH1cblxuLmNhcmQtaGVhZGVyLXBpbGxzIHtcbiAgbWFyZ2luLXJpZ2h0OiAtMC42MjVyZW07XG4gIG1hcmdpbi1sZWZ0OiAtMC42MjVyZW07IH1cblxuLmNhcmQtaW1nLW92ZXJsYXkge1xuICBwb3NpdGlvbjogYWJzb2x1dGU7XG4gIHRvcDogMDtcbiAgcmlnaHQ6IDA7XG4gIGJvdHRvbTogMDtcbiAgbGVmdDogMDtcbiAgcGFkZGluZzogMS4yNXJlbTsgfVxuXG4uY2FyZC1pbWcge1xuICB3aWR0aDogMTAwJTtcbiAgYm9yZGVyLXJhZGl1czogY2FsYygwLjI1cmVtIC0gMXB4KTsgfVxuXG4uY2FyZC1pbWctdG9wIHtcbiAgd2lkdGg6IDEwMCU7XG4gIGJvcmRlci10b3AtbGVmdC1yYWRpdXM6IGNhbGMoMC4yNXJlbSAtIDFweCk7XG4gIGJvcmRlci10b3AtcmlnaHQtcmFkaXVzOiBjYWxjKDAuMjVyZW0gLSAxcHgpOyB9XG5cbi5jYXJkLWltZy1ib3R0b20ge1xuICB3aWR0aDogMTAwJTtcbiAgYm9yZGVyLWJvdHRvbS1yaWdodC1yYWRpdXM6IGNhbGMoMC4yNXJlbSAtIDFweCk7XG4gIGJvcmRlci1ib3R0b20tbGVmdC1yYWRpdXM6IGNhbGMoMC4yNXJlbSAtIDFweCk7IH1cblxuQG1lZGlhIChtaW4td2lkdGg6IDU3NnB4KSB7XG4gIC5jYXJkLWRlY2sge1xuICAgIGRpc3BsYXk6IGZsZXg7XG4gICAgZmxleC1mbG93OiByb3cgd3JhcDtcbiAgICBtYXJnaW4tcmlnaHQ6IC0xNXB4O1xuICAgIG1hcmdpbi1sZWZ0OiAtMTVweDsgfVxuICAgIC5jYXJkLWRlY2sgLmNhcmQge1xuICAgICAgZGlzcGxheTogZmxleDtcbiAgICAgIGZsZXg6IDEgMCAwJTtcbiAgICAgIGZsZXgtZGlyZWN0aW9uOiBjb2x1bW47XG4gICAgICBtYXJnaW4tcmlnaHQ6IDE1cHg7XG4gICAgICBtYXJnaW4tbGVmdDogMTVweDsgfSB9XG5cbkBtZWRpYSAobWluLXdpZHRoOiA1NzZweCkge1xuICAuY2FyZC1ncm91cCB7XG4gICAgZGlzcGxheTogZmxleDtcbiAgICBmbGV4LWZsb3c6IHJvdyB3cmFwOyB9XG4gICAgLmNhcmQtZ3JvdXAgLmNhcmQge1xuICAgICAgZmxleDogMSAwIDAlOyB9XG4gICAgICAuY2FyZC1ncm91cCAuY2FyZCArIC5jYXJkIHtcbiAgICAgICAgbWFyZ2luLWxlZnQ6IDA7XG4gICAgICAgIGJvcmRlci1sZWZ0OiAwOyB9XG4gICAgICAuY2FyZC1ncm91cCAuY2FyZDpmaXJzdC1jaGlsZCB7XG4gICAgICAgIGJvcmRlci10b3AtcmlnaHQtcmFkaXVzOiAwO1xuICAgICAgICBib3JkZXItYm90dG9tLXJpZ2h0LXJhZGl1czogMDsgfVxuICAgICAgICAuY2FyZC1ncm91cCAuY2FyZDpmaXJzdC1jaGlsZCAuY2FyZC1pbWctdG9wIHtcbiAgICAgICAgICBib3JkZXItdG9wLXJpZ2h0LXJhZGl1czogMDsgfVxuICAgICAgICAuY2FyZC1ncm91cCAuY2FyZDpmaXJzdC1jaGlsZCAuY2FyZC1pbWctYm90dG9tIHtcbiAgICAgICAgICBib3JkZXItYm90dG9tLXJpZ2h0LXJhZGl1czogMDsgfVxuICAgICAgLmNhcmQtZ3JvdXAgLmNhcmQ6bGFzdC1jaGlsZCB7XG4gICAgICAgIGJvcmRlci10b3AtbGVmdC1yYWRpdXM6IDA7XG4gICAgICAgIGJvcmRlci1ib3R0b20tbGVmdC1yYWRpdXM6IDA7IH1cbiAgICAgICAgLmNhcmQtZ3JvdXAgLmNhcmQ6bGFzdC1jaGlsZCAuY2FyZC1pbWctdG9wIHtcbiAgICAgICAgICBib3JkZXItdG9wLWxlZnQtcmFkaXVzOiAwOyB9XG4gICAgICAgIC5jYXJkLWdyb3VwIC5jYXJkOmxhc3QtY2hpbGQgLmNhcmQtaW1nLWJvdHRvbSB7XG4gICAgICAgICAgYm9yZGVyLWJvdHRvbS1sZWZ0LXJhZGl1czogMDsgfVxuICAgICAgLmNhcmQtZ3JvdXAgLmNhcmQ6bm90KDpmaXJzdC1jaGlsZCk6bm90KDpsYXN0LWNoaWxkKSB7XG4gICAgICAgIGJvcmRlci1yYWRpdXM6IDA7IH1cbiAgICAgICAgLmNhcmQtZ3JvdXAgLmNhcmQ6bm90KDpmaXJzdC1jaGlsZCk6bm90KDpsYXN0LWNoaWxkKSAuY2FyZC1pbWctdG9wLFxuICAgICAgICAuY2FyZC1ncm91cCAuY2FyZDpub3QoOmZpcnN0LWNoaWxkKTpub3QoOmxhc3QtY2hpbGQpIC5jYXJkLWltZy1ib3R0b20ge1xuICAgICAgICAgIGJvcmRlci1yYWRpdXM6IDA7IH0gfVxuXG4uY2FyZC1jb2x1bW5zIC5jYXJkIHtcbiAgbWFyZ2luLWJvdHRvbTogMC43NXJlbTsgfVxuXG5AbWVkaWEgKG1pbi13aWR0aDogNTc2cHgpIHtcbiAgLmNhcmQtY29sdW1ucyB7XG4gICAgY29sdW1uLWNvdW50OiAzO1xuICAgIGNvbHVtbi1nYXA6IDEuMjVyZW07IH1cbiAgICAuY2FyZC1jb2x1bW5zIC5jYXJkIHtcbiAgICAgIGRpc3BsYXk6IGlubGluZS1ibG9jaztcbiAgICAgIHdpZHRoOiAxMDAlOyB9IH1cblxuLmJyZWFkY3J1bWIge1xuICBwYWRkaW5nOiAwLjc1cmVtIDFyZW07XG4gIG1hcmdpbi1ib3R0b206IDFyZW07XG4gIGxpc3Qtc3R5bGU6IG5vbmU7XG4gIGJhY2tncm91bmQtY29sb3I6ICNlOWVjZWY7XG4gIGJvcmRlci1yYWRpdXM6IDAuMjVyZW07IH1cbiAgLmJyZWFkY3J1bWI6OmFmdGVyIHtcbiAgICBkaXNwbGF5OiBibG9jaztcbiAgICBjbGVhcjogYm90aDtcbiAgICBjb250ZW50OiBcIlwiOyB9XG5cbi5icmVhZGNydW1iLWl0ZW0ge1xuICBmbG9hdDogbGVmdDsgfVxuICAuYnJlYWRjcnVtYi1pdGVtICsgLmJyZWFkY3J1bWItaXRlbTo6YmVmb3JlIHtcbiAgICBkaXNwbGF5OiBpbmxpbmUtYmxvY2s7XG4gICAgcGFkZGluZy1yaWdodDogMC41cmVtO1xuICAgIHBhZGRpbmctbGVmdDogMC41cmVtO1xuICAgIGNvbG9yOiAjODY4ZTk2O1xuICAgIGNvbnRlbnQ6IFwiL1wiOyB9XG4gIC5icmVhZGNydW1iLWl0ZW0gKyAuYnJlYWRjcnVtYi1pdGVtOmhvdmVyOjpiZWZvcmUge1xuICAgIHRleHQtZGVjb3JhdGlvbjogdW5kZXJsaW5lOyB9XG4gIC5icmVhZGNydW1iLWl0ZW0gKyAuYnJlYWRjcnVtYi1pdGVtOmhvdmVyOjpiZWZvcmUge1xuICAgIHRleHQtZGVjb3JhdGlvbjogbm9uZTsgfVxuICAuYnJlYWRjcnVtYi1pdGVtLmFjdGl2ZSB7XG4gICAgY29sb3I6ICM4NjhlOTY7IH1cblxuLnBhZ2luYXRpb24ge1xuICBkaXNwbGF5OiBmbGV4O1xuICBwYWRkaW5nLWxlZnQ6IDA7XG4gIGxpc3Qtc3R5bGU6IG5vbmU7XG4gIGJvcmRlci1yYWRpdXM6IDAuMjVyZW07IH1cblxuLnBhZ2UtaXRlbTpmaXJzdC1jaGlsZCAucGFnZS1saW5rIHtcbiAgbWFyZ2luLWxlZnQ6IDA7XG4gIGJvcmRlci10b3AtbGVmdC1yYWRpdXM6IDAuMjVyZW07XG4gIGJvcmRlci1ib3R0b20tbGVmdC1yYWRpdXM6IDAuMjVyZW07IH1cblxuLnBhZ2UtaXRlbTpsYXN0LWNoaWxkIC5wYWdlLWxpbmsge1xuICBib3JkZXItdG9wLXJpZ2h0LXJhZGl1czogMC4yNXJlbTtcbiAgYm9yZGVyLWJvdHRvbS1yaWdodC1yYWRpdXM6IDAuMjVyZW07IH1cblxuLnBhZ2UtaXRlbS5hY3RpdmUgLnBhZ2UtbGluayB7XG4gIHotaW5kZXg6IDI7XG4gIGNvbG9yOiAjZmZmO1xuICBiYWNrZ3JvdW5kLWNvbG9yOiAjMDA3YmZmO1xuICBib3JkZXItY29sb3I6ICMwMDdiZmY7IH1cblxuLnBhZ2UtaXRlbS5kaXNhYmxlZCAucGFnZS1saW5rIHtcbiAgY29sb3I6ICM4NjhlOTY7XG4gIHBvaW50ZXItZXZlbnRzOiBub25lO1xuICBiYWNrZ3JvdW5kLWNvbG9yOiAjZmZmO1xuICBib3JkZXItY29sb3I6ICNkZGQ7IH1cblxuLnBhZ2UtbGluayB7XG4gIHBvc2l0aW9uOiByZWxhdGl2ZTtcbiAgZGlzcGxheTogYmxvY2s7XG4gIHBhZGRpbmc6IDAuNXJlbSAwLjc1cmVtO1xuICBtYXJnaW4tbGVmdDogLTFweDtcbiAgbGluZS1oZWlnaHQ6IDEuMjU7XG4gIGNvbG9yOiAjMDA3YmZmO1xuICBiYWNrZ3JvdW5kLWNvbG9yOiAjZmZmO1xuICBib3JkZXI6IDFweCBzb2xpZCAjZGRkOyB9XG4gIC5wYWdlLWxpbms6Zm9jdXMsIC5wYWdlLWxpbms6aG92ZXIge1xuICAgIGNvbG9yOiAjMDA1NmIzO1xuICAgIHRleHQtZGVjb3JhdGlvbjogbm9uZTtcbiAgICBiYWNrZ3JvdW5kLWNvbG9yOiAjZTllY2VmO1xuICAgIGJvcmRlci1jb2xvcjogI2RkZDsgfVxuXG4ucGFnaW5hdGlvbi1sZyAucGFnZS1saW5rIHtcbiAgcGFkZGluZzogMC43NXJlbSAxLjVyZW07XG4gIGZvbnQtc2l6ZTogMS4yNXJlbTtcbiAgbGluZS1oZWlnaHQ6IDEuNTsgfVxuXG4ucGFnaW5hdGlvbi1sZyAucGFnZS1pdGVtOmZpcnN0LWNoaWxkIC5wYWdlLWxpbmsge1xuICBib3JkZXItdG9wLWxlZnQtcmFkaXVzOiAwLjNyZW07XG4gIGJvcmRlci1ib3R0b20tbGVmdC1yYWRpdXM6IDAuM3JlbTsgfVxuXG4ucGFnaW5hdGlvbi1sZyAucGFnZS1pdGVtOmxhc3QtY2hpbGQgLnBhZ2UtbGluayB7XG4gIGJvcmRlci10b3AtcmlnaHQtcmFkaXVzOiAwLjNyZW07XG4gIGJvcmRlci1ib3R0b20tcmlnaHQtcmFkaXVzOiAwLjNyZW07IH1cblxuLnBhZ2luYXRpb24tc20gLnBhZ2UtbGluayB7XG4gIHBhZGRpbmc6IDAuMjVyZW0gMC41cmVtO1xuICBmb250LXNpemU6IDAuODc1cmVtO1xuICBsaW5lLWhlaWdodDogMS41OyB9XG5cbi5wYWdpbmF0aW9uLXNtIC5wYWdlLWl0ZW06Zmlyc3QtY2hpbGQgLnBhZ2UtbGluayB7XG4gIGJvcmRlci10b3AtbGVmdC1yYWRpdXM6IDAuMnJlbTtcbiAgYm9yZGVyLWJvdHRvbS1sZWZ0LXJhZGl1czogMC4ycmVtOyB9XG5cbi5wYWdpbmF0aW9uLXNtIC5wYWdlLWl0ZW06bGFzdC1jaGlsZCAucGFnZS1saW5rIHtcbiAgYm9yZGVyLXRvcC1yaWdodC1yYWRpdXM6IDAuMnJlbTtcbiAgYm9yZGVyLWJvdHRvbS1yaWdodC1yYWRpdXM6IDAuMnJlbTsgfVxuXG4uYmFkZ2Uge1xuICBkaXNwbGF5OiBpbmxpbmUtYmxvY2s7XG4gIHBhZGRpbmc6IDAuMjVlbSAwLjRlbTtcbiAgZm9udC1zaXplOiA3NSU7XG4gIGZvbnQtd2VpZ2h0OiBib2xkO1xuICBsaW5lLWhlaWdodDogMTtcbiAgY29sb3I6ICNmZmY7XG4gIHRleHQtYWxpZ246IGNlbnRlcjtcbiAgd2hpdGUtc3BhY2U6IG5vd3JhcDtcbiAgdmVydGljYWwtYWxpZ246IGJhc2VsaW5lO1xuICBib3JkZXItcmFkaXVzOiAwLjI1cmVtOyB9XG4gIC5iYWRnZTplbXB0eSB7XG4gICAgZGlzcGxheTogbm9uZTsgfVxuXG4uYnRuIC5iYWRnZSwgYnV0dG9uLmN1c3RvbSAuYmFkZ2Uge1xuICBwb3NpdGlvbjogcmVsYXRpdmU7XG4gIHRvcDogLTFweDsgfVxuXG4uYmFkZ2UtcGlsbCB7XG4gIHBhZGRpbmctcmlnaHQ6IDAuNmVtO1xuICBwYWRkaW5nLWxlZnQ6IDAuNmVtO1xuICBib3JkZXItcmFkaXVzOiAxMHJlbTsgfVxuXG4uYmFkZ2UtcHJpbWFyeSB7XG4gIGNvbG9yOiAjZmZmO1xuICBiYWNrZ3JvdW5kLWNvbG9yOiAjMDA3YmZmOyB9XG4gIC5iYWRnZS1wcmltYXJ5W2hyZWZdOmZvY3VzLCAuYmFkZ2UtcHJpbWFyeVtocmVmXTpob3ZlciB7XG4gICAgY29sb3I6ICNmZmY7XG4gICAgdGV4dC1kZWNvcmF0aW9uOiBub25lO1xuICAgIGJhY2tncm91bmQtY29sb3I6ICMwMDYyY2M7IH1cblxuLmJhZGdlLXNlY29uZGFyeSB7XG4gIGNvbG9yOiAjZmZmO1xuICBiYWNrZ3JvdW5kLWNvbG9yOiAjODY4ZTk2OyB9XG4gIC5iYWRnZS1zZWNvbmRhcnlbaHJlZl06Zm9jdXMsIC5iYWRnZS1zZWNvbmRhcnlbaHJlZl06aG92ZXIge1xuICAgIGNvbG9yOiAjZmZmO1xuICAgIHRleHQtZGVjb3JhdGlvbjogbm9uZTtcbiAgICBiYWNrZ3JvdW5kLWNvbG9yOiAjNmM3NTdkOyB9XG5cbi5iYWRnZS1zdWNjZXNzIHtcbiAgY29sb3I6ICNmZmY7XG4gIGJhY2tncm91bmQtY29sb3I6ICMyOGE3NDU7IH1cbiAgLmJhZGdlLXN1Y2Nlc3NbaHJlZl06Zm9jdXMsIC5iYWRnZS1zdWNjZXNzW2hyZWZdOmhvdmVyIHtcbiAgICBjb2xvcjogI2ZmZjtcbiAgICB0ZXh0LWRlY29yYXRpb246IG5vbmU7XG4gICAgYmFja2dyb3VuZC1jb2xvcjogIzFlN2UzNDsgfVxuXG4uYmFkZ2UtaW5mbyB7XG4gIGNvbG9yOiAjZmZmO1xuICBiYWNrZ3JvdW5kLWNvbG9yOiAjMTdhMmI4OyB9XG4gIC5iYWRnZS1pbmZvW2hyZWZdOmZvY3VzLCAuYmFkZ2UtaW5mb1tocmVmXTpob3ZlciB7XG4gICAgY29sb3I6ICNmZmY7XG4gICAgdGV4dC1kZWNvcmF0aW9uOiBub25lO1xuICAgIGJhY2tncm91bmQtY29sb3I6ICMxMTdhOGI7IH1cblxuLmJhZGdlLXdhcm5pbmcge1xuICBjb2xvcjogIzExMTtcbiAgYmFja2dyb3VuZC1jb2xvcjogI2ZmYzEwNzsgfVxuICAuYmFkZ2Utd2FybmluZ1tocmVmXTpmb2N1cywgLmJhZGdlLXdhcm5pbmdbaHJlZl06aG92ZXIge1xuICAgIGNvbG9yOiAjMTExO1xuICAgIHRleHQtZGVjb3JhdGlvbjogbm9uZTtcbiAgICBiYWNrZ3JvdW5kLWNvbG9yOiAjZDM5ZTAwOyB9XG5cbi5iYWRnZS1kYW5nZXIge1xuICBjb2xvcjogI2ZmZjtcbiAgYmFja2dyb3VuZC1jb2xvcjogI2RjMzU0NTsgfVxuICAuYmFkZ2UtZGFuZ2VyW2hyZWZdOmZvY3VzLCAuYmFkZ2UtZGFuZ2VyW2hyZWZdOmhvdmVyIHtcbiAgICBjb2xvcjogI2ZmZjtcbiAgICB0ZXh0LWRlY29yYXRpb246IG5vbmU7XG4gICAgYmFja2dyb3VuZC1jb2xvcjogI2JkMjEzMDsgfVxuXG4uYmFkZ2UtbGlnaHQge1xuICBjb2xvcjogIzExMTtcbiAgYmFja2dyb3VuZC1jb2xvcjogI2Y4ZjlmYTsgfVxuICAuYmFkZ2UtbGlnaHRbaHJlZl06Zm9jdXMsIC5iYWRnZS1saWdodFtocmVmXTpob3ZlciB7XG4gICAgY29sb3I6ICMxMTE7XG4gICAgdGV4dC1kZWNvcmF0aW9uOiBub25lO1xuICAgIGJhY2tncm91bmQtY29sb3I6ICNkYWUwZTU7IH1cblxuLmJhZGdlLWRhcmsge1xuICBjb2xvcjogI2ZmZjtcbiAgYmFja2dyb3VuZC1jb2xvcjogIzM0M2E0MDsgfVxuICAuYmFkZ2UtZGFya1tocmVmXTpmb2N1cywgLmJhZGdlLWRhcmtbaHJlZl06aG92ZXIge1xuICAgIGNvbG9yOiAjZmZmO1xuICAgIHRleHQtZGVjb3JhdGlvbjogbm9uZTtcbiAgICBiYWNrZ3JvdW5kLWNvbG9yOiAjMWQyMTI0OyB9XG5cbi5qdW1ib3Ryb24ge1xuICBwYWRkaW5nOiAycmVtIDFyZW07XG4gIG1hcmdpbi1ib3R0b206IDJyZW07XG4gIGJhY2tncm91bmQtY29sb3I6ICNlOWVjZWY7XG4gIGJvcmRlci1yYWRpdXM6IDAuM3JlbTsgfVxuICBAbWVkaWEgKG1pbi13aWR0aDogNTc2cHgpIHtcbiAgICAuanVtYm90cm9uIHtcbiAgICAgIHBhZGRpbmc6IDRyZW0gMnJlbTsgfSB9XG5cbi5qdW1ib3Ryb24tZmx1aWQge1xuICBwYWRkaW5nLXJpZ2h0OiAwO1xuICBwYWRkaW5nLWxlZnQ6IDA7XG4gIGJvcmRlci1yYWRpdXM6IDA7IH1cblxuLmFsZXJ0IHtcbiAgcGFkZGluZzogMC43NXJlbSAxLjI1cmVtO1xuICBtYXJnaW4tYm90dG9tOiAxcmVtO1xuICBib3JkZXI6IDFweCBzb2xpZCB0cmFuc3BhcmVudDtcbiAgYm9yZGVyLXJhZGl1czogMC4yNXJlbTsgfVxuXG4uYWxlcnQtaGVhZGluZyB7XG4gIGNvbG9yOiBpbmhlcml0OyB9XG5cbi5hbGVydC1saW5rIHtcbiAgZm9udC13ZWlnaHQ6IGJvbGQ7IH1cblxuLmFsZXJ0LWRpc21pc3NpYmxlIC5jbG9zZSB7XG4gIHBvc2l0aW9uOiByZWxhdGl2ZTtcbiAgdG9wOiAtMC43NXJlbTtcbiAgcmlnaHQ6IC0xLjI1cmVtO1xuICBwYWRkaW5nOiAwLjc1cmVtIDEuMjVyZW07XG4gIGNvbG9yOiBpbmhlcml0OyB9XG5cbi5hbGVydC1wcmltYXJ5IHtcbiAgY29sb3I6ICMwMDQwODU7XG4gIGJhY2tncm91bmQtY29sb3I6ICNjY2U1ZmY7XG4gIGJvcmRlci1jb2xvcjogI2I4ZGFmZjsgfVxuICAuYWxlcnQtcHJpbWFyeSBociB7XG4gICAgYm9yZGVyLXRvcC1jb2xvcjogIzlmY2RmZjsgfVxuICAuYWxlcnQtcHJpbWFyeSAuYWxlcnQtbGluayB7XG4gICAgY29sb3I6ICMwMDI3NTI7IH1cblxuLmFsZXJ0LXNlY29uZGFyeSB7XG4gIGNvbG9yOiAjNDY0YTRlO1xuICBiYWNrZ3JvdW5kLWNvbG9yOiAjZTdlOGVhO1xuICBib3JkZXItY29sb3I6ICNkZGRmZTI7IH1cbiAgLmFsZXJ0LXNlY29uZGFyeSBociB7XG4gICAgYm9yZGVyLXRvcC1jb2xvcjogI2NmZDJkNjsgfVxuICAuYWxlcnQtc2Vjb25kYXJ5IC5hbGVydC1saW5rIHtcbiAgICBjb2xvcjogIzJlMzEzMzsgfVxuXG4uYWxlcnQtc3VjY2VzcyB7XG4gIGNvbG9yOiAjMTU1NzI0O1xuICBiYWNrZ3JvdW5kLWNvbG9yOiAjZDRlZGRhO1xuICBib3JkZXItY29sb3I6ICNjM2U2Y2I7IH1cbiAgLmFsZXJ0LXN1Y2Nlc3MgaHIge1xuICAgIGJvcmRlci10b3AtY29sb3I6ICNiMWRmYmI7IH1cbiAgLmFsZXJ0LXN1Y2Nlc3MgLmFsZXJ0LWxpbmsge1xuICAgIGNvbG9yOiAjMGIyZTEzOyB9XG5cbi5hbGVydC1pbmZvIHtcbiAgY29sb3I6ICMwYzU0NjA7XG4gIGJhY2tncm91bmQtY29sb3I6ICNkMWVjZjE7XG4gIGJvcmRlci1jb2xvcjogI2JlZTVlYjsgfVxuICAuYWxlcnQtaW5mbyBociB7XG4gICAgYm9yZGVyLXRvcC1jb2xvcjogI2FiZGRlNTsgfVxuICAuYWxlcnQtaW5mbyAuYWxlcnQtbGluayB7XG4gICAgY29sb3I6ICMwNjJjMzM7IH1cblxuLmFsZXJ0LXdhcm5pbmcge1xuICBjb2xvcjogIzg1NjQwNDtcbiAgYmFja2dyb3VuZC1jb2xvcjogI2ZmZjNjZDtcbiAgYm9yZGVyLWNvbG9yOiAjZmZlZWJhOyB9XG4gIC5hbGVydC13YXJuaW5nIGhyIHtcbiAgICBib3JkZXItdG9wLWNvbG9yOiAjZmZlOGExOyB9XG4gIC5hbGVydC13YXJuaW5nIC5hbGVydC1saW5rIHtcbiAgICBjb2xvcjogIzUzM2YwMzsgfVxuXG4uYWxlcnQtZGFuZ2VyIHtcbiAgY29sb3I6ICM3MjFjMjQ7XG4gIGJhY2tncm91bmQtY29sb3I6ICNmOGQ3ZGE7XG4gIGJvcmRlci1jb2xvcjogI2Y1YzZjYjsgfVxuICAuYWxlcnQtZGFuZ2VyIGhyIHtcbiAgICBib3JkZXItdG9wLWNvbG9yOiAjZjFiMGI3OyB9XG4gIC5hbGVydC1kYW5nZXIgLmFsZXJ0LWxpbmsge1xuICAgIGNvbG9yOiAjNDkxMjE3OyB9XG5cbi5hbGVydC1saWdodCB7XG4gIGNvbG9yOiAjODE4MTgyO1xuICBiYWNrZ3JvdW5kLWNvbG9yOiAjZmVmZWZlO1xuICBib3JkZXItY29sb3I6ICNmZGZkZmU7IH1cbiAgLmFsZXJ0LWxpZ2h0IGhyIHtcbiAgICBib3JkZXItdG9wLWNvbG9yOiAjZWNlY2Y2OyB9XG4gIC5hbGVydC1saWdodCAuYWxlcnQtbGluayB7XG4gICAgY29sb3I6ICM2ODY4Njg7IH1cblxuLmFsZXJ0LWRhcmsge1xuICBjb2xvcjogIzFiMWUyMTtcbiAgYmFja2dyb3VuZC1jb2xvcjogI2Q2ZDhkOTtcbiAgYm9yZGVyLWNvbG9yOiAjYzZjOGNhOyB9XG4gIC5hbGVydC1kYXJrIGhyIHtcbiAgICBib3JkZXItdG9wLWNvbG9yOiAjYjliYmJlOyB9XG4gIC5hbGVydC1kYXJrIC5hbGVydC1saW5rIHtcbiAgICBjb2xvcjogIzA0MDUwNTsgfVxuXG5Aa2V5ZnJhbWVzIHByb2dyZXNzLWJhci1zdHJpcGVzIHtcbiAgZnJvbSB7XG4gICAgYmFja2dyb3VuZC1wb3NpdGlvbjogMXJlbSAwOyB9XG4gIHRvIHtcbiAgICBiYWNrZ3JvdW5kLXBvc2l0aW9uOiAwIDA7IH0gfVxuXG4ucHJvZ3Jlc3Mge1xuICBkaXNwbGF5OiBmbGV4O1xuICBoZWlnaHQ6IDFyZW07XG4gIG92ZXJmbG93OiBoaWRkZW47XG4gIGZvbnQtc2l6ZTogMC43NXJlbTtcbiAgYmFja2dyb3VuZC1jb2xvcjogI2U5ZWNlZjtcbiAgYm9yZGVyLXJhZGl1czogMC4yNXJlbTsgfVxuXG4ucHJvZ3Jlc3MtYmFyIHtcbiAgZGlzcGxheTogZmxleDtcbiAgYWxpZ24taXRlbXM6IGNlbnRlcjtcbiAganVzdGlmeS1jb250ZW50OiBjZW50ZXI7XG4gIGNvbG9yOiAjZmZmO1xuICBiYWNrZ3JvdW5kLWNvbG9yOiAjMDA3YmZmOyB9XG5cbi5wcm9ncmVzcy1iYXItc3RyaXBlZCB7XG4gIGJhY2tncm91bmQtaW1hZ2U6IGxpbmVhci1ncmFkaWVudCg0NWRlZywgcmdiYSgyNTUsIDI1NSwgMjU1LCAwLjE1KSAyNSUsIHRyYW5zcGFyZW50IDI1JSwgdHJhbnNwYXJlbnQgNTAlLCByZ2JhKDI1NSwgMjU1LCAyNTUsIDAuMTUpIDUwJSwgcmdiYSgyNTUsIDI1NSwgMjU1LCAwLjE1KSA3NSUsIHRyYW5zcGFyZW50IDc1JSwgdHJhbnNwYXJlbnQpO1xuICBiYWNrZ3JvdW5kLXNpemU6IDFyZW0gMXJlbTsgfVxuXG4ucHJvZ3Jlc3MtYmFyLWFuaW1hdGVkIHtcbiAgYW5pbWF0aW9uOiBwcm9ncmVzcy1iYXItc3RyaXBlcyAxcyBsaW5lYXIgaW5maW5pdGU7IH1cblxuLm1lZGlhIHtcbiAgZGlzcGxheTogZmxleDtcbiAgYWxpZ24taXRlbXM6IGZsZXgtc3RhcnQ7IH1cblxuLm1lZGlhLWJvZHkge1xuICBmbGV4OiAxOyB9XG5cbi5saXN0LWdyb3VwIHtcbiAgZGlzcGxheTogZmxleDtcbiAgZmxleC1kaXJlY3Rpb246IGNvbHVtbjtcbiAgcGFkZGluZy1sZWZ0OiAwO1xuICBtYXJnaW4tYm90dG9tOiAwOyB9XG5cbi5saXN0LWdyb3VwLWl0ZW0tYWN0aW9uIHtcbiAgd2lkdGg6IDEwMCU7XG4gIGNvbG9yOiAjNDk1MDU3O1xuICB0ZXh0LWFsaWduOiBpbmhlcml0OyB9XG4gIC5saXN0LWdyb3VwLWl0ZW0tYWN0aW9uOmZvY3VzLCAubGlzdC1ncm91cC1pdGVtLWFjdGlvbjpob3ZlciB7XG4gICAgY29sb3I6ICM0OTUwNTc7XG4gICAgdGV4dC1kZWNvcmF0aW9uOiBub25lO1xuICAgIGJhY2tncm91bmQtY29sb3I6ICNmOGY5ZmE7IH1cbiAgLmxpc3QtZ3JvdXAtaXRlbS1hY3Rpb246YWN0aXZlIHtcbiAgICBjb2xvcjogIzIxMjUyOTtcbiAgICBiYWNrZ3JvdW5kLWNvbG9yOiAjZTllY2VmOyB9XG5cbi5saXN0LWdyb3VwLWl0ZW0ge1xuICBwb3NpdGlvbjogcmVsYXRpdmU7XG4gIGRpc3BsYXk6IGJsb2NrO1xuICBwYWRkaW5nOiAwLjc1cmVtIDEuMjVyZW07XG4gIG1hcmdpbi1ib3R0b206IC0xcHg7XG4gIGJhY2tncm91bmQtY29sb3I6ICNmZmY7XG4gIGJvcmRlcjogMXB4IHNvbGlkIHJnYmEoMCwgMCwgMCwgMC4xMjUpOyB9XG4gIC5saXN0LWdyb3VwLWl0ZW06Zmlyc3QtY2hpbGQge1xuICAgIGJvcmRlci10b3AtbGVmdC1yYWRpdXM6IDAuMjVyZW07XG4gICAgYm9yZGVyLXRvcC1yaWdodC1yYWRpdXM6IDAuMjVyZW07IH1cbiAgLmxpc3QtZ3JvdXAtaXRlbTpsYXN0LWNoaWxkIHtcbiAgICBtYXJnaW4tYm90dG9tOiAwO1xuICAgIGJvcmRlci1ib3R0b20tcmlnaHQtcmFkaXVzOiAwLjI1cmVtO1xuICAgIGJvcmRlci1ib3R0b20tbGVmdC1yYWRpdXM6IDAuMjVyZW07IH1cbiAgLmxpc3QtZ3JvdXAtaXRlbTpmb2N1cywgLmxpc3QtZ3JvdXAtaXRlbTpob3ZlciB7XG4gICAgdGV4dC1kZWNvcmF0aW9uOiBub25lOyB9XG4gIC5saXN0LWdyb3VwLWl0ZW0uZGlzYWJsZWQsIC5saXN0LWdyb3VwLWl0ZW06ZGlzYWJsZWQge1xuICAgIGNvbG9yOiAjODY4ZTk2O1xuICAgIGJhY2tncm91bmQtY29sb3I6ICNmZmY7IH1cbiAgLmxpc3QtZ3JvdXAtaXRlbS5hY3RpdmUge1xuICAgIHotaW5kZXg6IDI7XG4gICAgY29sb3I6ICNmZmY7XG4gICAgYmFja2dyb3VuZC1jb2xvcjogIzAwN2JmZjtcbiAgICBib3JkZXItY29sb3I6ICMwMDdiZmY7IH1cblxuLmxpc3QtZ3JvdXAtZmx1c2ggLmxpc3QtZ3JvdXAtaXRlbSB7XG4gIGJvcmRlci1yaWdodDogMDtcbiAgYm9yZGVyLWxlZnQ6IDA7XG4gIGJvcmRlci1yYWRpdXM6IDA7IH1cblxuLmxpc3QtZ3JvdXAtZmx1c2g6Zmlyc3QtY2hpbGQgLmxpc3QtZ3JvdXAtaXRlbTpmaXJzdC1jaGlsZCB7XG4gIGJvcmRlci10b3A6IDA7IH1cblxuLmxpc3QtZ3JvdXAtZmx1c2g6bGFzdC1jaGlsZCAubGlzdC1ncm91cC1pdGVtOmxhc3QtY2hpbGQge1xuICBib3JkZXItYm90dG9tOiAwOyB9XG5cbi5saXN0LWdyb3VwLWl0ZW0tcHJpbWFyeSB7XG4gIGNvbG9yOiAjMDA0MDg1O1xuICBiYWNrZ3JvdW5kLWNvbG9yOiAjYjhkYWZmOyB9XG5cbmEubGlzdC1ncm91cC1pdGVtLXByaW1hcnksXG5idXR0b24ubGlzdC1ncm91cC1pdGVtLXByaW1hcnkge1xuICBjb2xvcjogIzAwNDA4NTsgfVxuICBhLmxpc3QtZ3JvdXAtaXRlbS1wcmltYXJ5OmZvY3VzLCBhLmxpc3QtZ3JvdXAtaXRlbS1wcmltYXJ5OmhvdmVyLFxuICBidXR0b24ubGlzdC1ncm91cC1pdGVtLXByaW1hcnk6Zm9jdXMsXG4gIGJ1dHRvbi5saXN0LWdyb3VwLWl0ZW0tcHJpbWFyeTpob3ZlciB7XG4gICAgY29sb3I6ICMwMDQwODU7XG4gICAgYmFja2dyb3VuZC1jb2xvcjogIzlmY2RmZjsgfVxuICBhLmxpc3QtZ3JvdXAtaXRlbS1wcmltYXJ5LmFjdGl2ZSxcbiAgYnV0dG9uLmxpc3QtZ3JvdXAtaXRlbS1wcmltYXJ5LmFjdGl2ZSB7XG4gICAgY29sb3I6ICNmZmY7XG4gICAgYmFja2dyb3VuZC1jb2xvcjogIzAwNDA4NTtcbiAgICBib3JkZXItY29sb3I6ICMwMDQwODU7IH1cblxuLmxpc3QtZ3JvdXAtaXRlbS1zZWNvbmRhcnkge1xuICBjb2xvcjogIzQ2NGE0ZTtcbiAgYmFja2dyb3VuZC1jb2xvcjogI2RkZGZlMjsgfVxuXG5hLmxpc3QtZ3JvdXAtaXRlbS1zZWNvbmRhcnksXG5idXR0b24ubGlzdC1ncm91cC1pdGVtLXNlY29uZGFyeSB7XG4gIGNvbG9yOiAjNDY0YTRlOyB9XG4gIGEubGlzdC1ncm91cC1pdGVtLXNlY29uZGFyeTpmb2N1cywgYS5saXN0LWdyb3VwLWl0ZW0tc2Vjb25kYXJ5OmhvdmVyLFxuICBidXR0b24ubGlzdC1ncm91cC1pdGVtLXNlY29uZGFyeTpmb2N1cyxcbiAgYnV0dG9uLmxpc3QtZ3JvdXAtaXRlbS1zZWNvbmRhcnk6aG92ZXIge1xuICAgIGNvbG9yOiAjNDY0YTRlO1xuICAgIGJhY2tncm91bmQtY29sb3I6ICNjZmQyZDY7IH1cbiAgYS5saXN0LWdyb3VwLWl0ZW0tc2Vjb25kYXJ5LmFjdGl2ZSxcbiAgYnV0dG9uLmxpc3QtZ3JvdXAtaXRlbS1zZWNvbmRhcnkuYWN0aXZlIHtcbiAgICBjb2xvcjogI2ZmZjtcbiAgICBiYWNrZ3JvdW5kLWNvbG9yOiAjNDY0YTRlO1xuICAgIGJvcmRlci1jb2xvcjogIzQ2NGE0ZTsgfVxuXG4ubGlzdC1ncm91cC1pdGVtLXN1Y2Nlc3Mge1xuICBjb2xvcjogIzE1NTcyNDtcbiAgYmFja2dyb3VuZC1jb2xvcjogI2MzZTZjYjsgfVxuXG5hLmxpc3QtZ3JvdXAtaXRlbS1zdWNjZXNzLFxuYnV0dG9uLmxpc3QtZ3JvdXAtaXRlbS1zdWNjZXNzIHtcbiAgY29sb3I6ICMxNTU3MjQ7IH1cbiAgYS5saXN0LWdyb3VwLWl0ZW0tc3VjY2Vzczpmb2N1cywgYS5saXN0LWdyb3VwLWl0ZW0tc3VjY2Vzczpob3ZlcixcbiAgYnV0dG9uLmxpc3QtZ3JvdXAtaXRlbS1zdWNjZXNzOmZvY3VzLFxuICBidXR0b24ubGlzdC1ncm91cC1pdGVtLXN1Y2Nlc3M6aG92ZXIge1xuICAgIGNvbG9yOiAjMTU1NzI0O1xuICAgIGJhY2tncm91bmQtY29sb3I6ICNiMWRmYmI7IH1cbiAgYS5saXN0LWdyb3VwLWl0ZW0tc3VjY2Vzcy5hY3RpdmUsXG4gIGJ1dHRvbi5saXN0LWdyb3VwLWl0ZW0tc3VjY2Vzcy5hY3RpdmUge1xuICAgIGNvbG9yOiAjZmZmO1xuICAgIGJhY2tncm91bmQtY29sb3I6ICMxNTU3MjQ7XG4gICAgYm9yZGVyLWNvbG9yOiAjMTU1NzI0OyB9XG5cbi5saXN0LWdyb3VwLWl0ZW0taW5mbyB7XG4gIGNvbG9yOiAjMGM1NDYwO1xuICBiYWNrZ3JvdW5kLWNvbG9yOiAjYmVlNWViOyB9XG5cbmEubGlzdC1ncm91cC1pdGVtLWluZm8sXG5idXR0b24ubGlzdC1ncm91cC1pdGVtLWluZm8ge1xuICBjb2xvcjogIzBjNTQ2MDsgfVxuICBhLmxpc3QtZ3JvdXAtaXRlbS1pbmZvOmZvY3VzLCBhLmxpc3QtZ3JvdXAtaXRlbS1pbmZvOmhvdmVyLFxuICBidXR0b24ubGlzdC1ncm91cC1pdGVtLWluZm86Zm9jdXMsXG4gIGJ1dHRvbi5saXN0LWdyb3VwLWl0ZW0taW5mbzpob3ZlciB7XG4gICAgY29sb3I6ICMwYzU0NjA7XG4gICAgYmFja2dyb3VuZC1jb2xvcjogI2FiZGRlNTsgfVxuICBhLmxpc3QtZ3JvdXAtaXRlbS1pbmZvLmFjdGl2ZSxcbiAgYnV0dG9uLmxpc3QtZ3JvdXAtaXRlbS1pbmZvLmFjdGl2ZSB7XG4gICAgY29sb3I6ICNmZmY7XG4gICAgYmFja2dyb3VuZC1jb2xvcjogIzBjNTQ2MDtcbiAgICBib3JkZXItY29sb3I6ICMwYzU0NjA7IH1cblxuLmxpc3QtZ3JvdXAtaXRlbS13YXJuaW5nIHtcbiAgY29sb3I6ICM4NTY0MDQ7XG4gIGJhY2tncm91bmQtY29sb3I6ICNmZmVlYmE7IH1cblxuYS5saXN0LWdyb3VwLWl0ZW0td2FybmluZyxcbmJ1dHRvbi5saXN0LWdyb3VwLWl0ZW0td2FybmluZyB7XG4gIGNvbG9yOiAjODU2NDA0OyB9XG4gIGEubGlzdC1ncm91cC1pdGVtLXdhcm5pbmc6Zm9jdXMsIGEubGlzdC1ncm91cC1pdGVtLXdhcm5pbmc6aG92ZXIsXG4gIGJ1dHRvbi5saXN0LWdyb3VwLWl0ZW0td2FybmluZzpmb2N1cyxcbiAgYnV0dG9uLmxpc3QtZ3JvdXAtaXRlbS13YXJuaW5nOmhvdmVyIHtcbiAgICBjb2xvcjogIzg1NjQwNDtcbiAgICBiYWNrZ3JvdW5kLWNvbG9yOiAjZmZlOGExOyB9XG4gIGEubGlzdC1ncm91cC1pdGVtLXdhcm5pbmcuYWN0aXZlLFxuICBidXR0b24ubGlzdC1ncm91cC1pdGVtLXdhcm5pbmcuYWN0aXZlIHtcbiAgICBjb2xvcjogI2ZmZjtcbiAgICBiYWNrZ3JvdW5kLWNvbG9yOiAjODU2NDA0O1xuICAgIGJvcmRlci1jb2xvcjogIzg1NjQwNDsgfVxuXG4ubGlzdC1ncm91cC1pdGVtLWRhbmdlciB7XG4gIGNvbG9yOiAjNzIxYzI0O1xuICBiYWNrZ3JvdW5kLWNvbG9yOiAjZjVjNmNiOyB9XG5cbmEubGlzdC1ncm91cC1pdGVtLWRhbmdlcixcbmJ1dHRvbi5saXN0LWdyb3VwLWl0ZW0tZGFuZ2VyIHtcbiAgY29sb3I6ICM3MjFjMjQ7IH1cbiAgYS5saXN0LWdyb3VwLWl0ZW0tZGFuZ2VyOmZvY3VzLCBhLmxpc3QtZ3JvdXAtaXRlbS1kYW5nZXI6aG92ZXIsXG4gIGJ1dHRvbi5saXN0LWdyb3VwLWl0ZW0tZGFuZ2VyOmZvY3VzLFxuICBidXR0b24ubGlzdC1ncm91cC1pdGVtLWRhbmdlcjpob3ZlciB7XG4gICAgY29sb3I6ICM3MjFjMjQ7XG4gICAgYmFja2dyb3VuZC1jb2xvcjogI2YxYjBiNzsgfVxuICBhLmxpc3QtZ3JvdXAtaXRlbS1kYW5nZXIuYWN0aXZlLFxuICBidXR0b24ubGlzdC1ncm91cC1pdGVtLWRhbmdlci5hY3RpdmUge1xuICAgIGNvbG9yOiAjZmZmO1xuICAgIGJhY2tncm91bmQtY29sb3I6ICM3MjFjMjQ7XG4gICAgYm9yZGVyLWNvbG9yOiAjNzIxYzI0OyB9XG5cbi5saXN0LWdyb3VwLWl0ZW0tbGlnaHQge1xuICBjb2xvcjogIzgxODE4MjtcbiAgYmFja2dyb3VuZC1jb2xvcjogI2ZkZmRmZTsgfVxuXG5hLmxpc3QtZ3JvdXAtaXRlbS1saWdodCxcbmJ1dHRvbi5saXN0LWdyb3VwLWl0ZW0tbGlnaHQge1xuICBjb2xvcjogIzgxODE4MjsgfVxuICBhLmxpc3QtZ3JvdXAtaXRlbS1saWdodDpmb2N1cywgYS5saXN0LWdyb3VwLWl0ZW0tbGlnaHQ6aG92ZXIsXG4gIGJ1dHRvbi5saXN0LWdyb3VwLWl0ZW0tbGlnaHQ6Zm9jdXMsXG4gIGJ1dHRvbi5saXN0LWdyb3VwLWl0ZW0tbGlnaHQ6aG92ZXIge1xuICAgIGNvbG9yOiAjODE4MTgyO1xuICAgIGJhY2tncm91bmQtY29sb3I6ICNlY2VjZjY7IH1cbiAgYS5saXN0LWdyb3VwLWl0ZW0tbGlnaHQuYWN0aXZlLFxuICBidXR0b24ubGlzdC1ncm91cC1pdGVtLWxpZ2h0LmFjdGl2ZSB7XG4gICAgY29sb3I6ICNmZmY7XG4gICAgYmFja2dyb3VuZC1jb2xvcjogIzgxODE4MjtcbiAgICBib3JkZXItY29sb3I6ICM4MTgxODI7IH1cblxuLmxpc3QtZ3JvdXAtaXRlbS1kYXJrIHtcbiAgY29sb3I6ICMxYjFlMjE7XG4gIGJhY2tncm91bmQtY29sb3I6ICNjNmM4Y2E7IH1cblxuYS5saXN0LWdyb3VwLWl0ZW0tZGFyayxcbmJ1dHRvbi5saXN0LWdyb3VwLWl0ZW0tZGFyayB7XG4gIGNvbG9yOiAjMWIxZTIxOyB9XG4gIGEubGlzdC1ncm91cC1pdGVtLWRhcms6Zm9jdXMsIGEubGlzdC1ncm91cC1pdGVtLWRhcms6aG92ZXIsXG4gIGJ1dHRvbi5saXN0LWdyb3VwLWl0ZW0tZGFyazpmb2N1cyxcbiAgYnV0dG9uLmxpc3QtZ3JvdXAtaXRlbS1kYXJrOmhvdmVyIHtcbiAgICBjb2xvcjogIzFiMWUyMTtcbiAgICBiYWNrZ3JvdW5kLWNvbG9yOiAjYjliYmJlOyB9XG4gIGEubGlzdC1ncm91cC1pdGVtLWRhcmsuYWN0aXZlLFxuICBidXR0b24ubGlzdC1ncm91cC1pdGVtLWRhcmsuYWN0aXZlIHtcbiAgICBjb2xvcjogI2ZmZjtcbiAgICBiYWNrZ3JvdW5kLWNvbG9yOiAjMWIxZTIxO1xuICAgIGJvcmRlci1jb2xvcjogIzFiMWUyMTsgfVxuXG4uY2xvc2Uge1xuICBmbG9hdDogcmlnaHQ7XG4gIGZvbnQtc2l6ZTogMS41cmVtO1xuICBmb250LXdlaWdodDogYm9sZDtcbiAgbGluZS1oZWlnaHQ6IDE7XG4gIGNvbG9yOiAjMDAwO1xuICB0ZXh0LXNoYWRvdzogMCAxcHggMCAjZmZmO1xuICBvcGFjaXR5OiAuNTsgfVxuICAuY2xvc2U6Zm9jdXMsIC5jbG9zZTpob3ZlciB7XG4gICAgY29sb3I6ICMwMDA7XG4gICAgdGV4dC1kZWNvcmF0aW9uOiBub25lO1xuICAgIG9wYWNpdHk6IC43NTsgfVxuXG5idXR0b24uY2xvc2Uge1xuICBwYWRkaW5nOiAwO1xuICBiYWNrZ3JvdW5kOiB0cmFuc3BhcmVudDtcbiAgYm9yZGVyOiAwO1xuICAtd2Via2l0LWFwcGVhcmFuY2U6IG5vbmU7IH1cblxuLm1vZGFsLW9wZW4ge1xuICBvdmVyZmxvdzogaGlkZGVuOyB9XG5cbi5tb2RhbCB7XG4gIHBvc2l0aW9uOiBmaXhlZDtcbiAgdG9wOiAwO1xuICByaWdodDogMDtcbiAgYm90dG9tOiAwO1xuICBsZWZ0OiAwO1xuICB6LWluZGV4OiAxMDUwO1xuICBkaXNwbGF5OiBub25lO1xuICBvdmVyZmxvdzogaGlkZGVuO1xuICBvdXRsaW5lOiAwOyB9XG4gIC5tb2RhbC5mYWRlIC5tb2RhbC1kaWFsb2cge1xuICAgIHRyYW5zaXRpb246IHRyYW5zZm9ybSAwLjNzIGVhc2Utb3V0O1xuICAgIHRyYW5zZm9ybTogdHJhbnNsYXRlKDAsIC0yNSUpOyB9XG4gIC5tb2RhbC5zaG93IC5tb2RhbC1kaWFsb2cge1xuICAgIHRyYW5zZm9ybTogdHJhbnNsYXRlKDAsIDApOyB9XG5cbi5tb2RhbC1vcGVuIC5tb2RhbCB7XG4gIG92ZXJmbG93LXg6IGhpZGRlbjtcbiAgb3ZlcmZsb3cteTogYXV0bzsgfVxuXG4ubW9kYWwtZGlhbG9nIHtcbiAgcG9zaXRpb246IHJlbGF0aXZlO1xuICB3aWR0aDogYXV0bztcbiAgbWFyZ2luOiAxMHB4OyB9XG5cbi5tb2RhbC1jb250ZW50IHtcbiAgcG9zaXRpb246IHJlbGF0aXZlO1xuICBkaXNwbGF5OiBmbGV4O1xuICBmbGV4LWRpcmVjdGlvbjogY29sdW1uO1xuICBiYWNrZ3JvdW5kLWNvbG9yOiAjZmZmO1xuICBiYWNrZ3JvdW5kLWNsaXA6IHBhZGRpbmctYm94O1xuICBib3JkZXI6IDFweCBzb2xpZCByZ2JhKDAsIDAsIDAsIDAuMik7XG4gIGJvcmRlci1yYWRpdXM6IDAuM3JlbTtcbiAgb3V0bGluZTogMDsgfVxuXG4ubW9kYWwtYmFja2Ryb3Age1xuICBwb3NpdGlvbjogZml4ZWQ7XG4gIHRvcDogMDtcbiAgcmlnaHQ6IDA7XG4gIGJvdHRvbTogMDtcbiAgbGVmdDogMDtcbiAgei1pbmRleDogMTA0MDtcbiAgYmFja2dyb3VuZC1jb2xvcjogIzAwMDsgfVxuICAubW9kYWwtYmFja2Ryb3AuZmFkZSB7XG4gICAgb3BhY2l0eTogMDsgfVxuICAubW9kYWwtYmFja2Ryb3Auc2hvdyB7XG4gICAgb3BhY2l0eTogMC41OyB9XG5cbi5tb2RhbC1oZWFkZXIge1xuICBkaXNwbGF5OiBmbGV4O1xuICBhbGlnbi1pdGVtczogY2VudGVyO1xuICBqdXN0aWZ5LWNvbnRlbnQ6IHNwYWNlLWJldHdlZW47XG4gIHBhZGRpbmc6IDE1cHg7XG4gIGJvcmRlci1ib3R0b206IDFweCBzb2xpZCAjZTllY2VmOyB9XG4gIC5tb2RhbC1oZWFkZXIgLmNsb3NlIHtcbiAgICBtYXJnaW4tbGVmdDogYXV0bzsgfVxuXG4ubW9kYWwtdGl0bGUge1xuICBtYXJnaW4tYm90dG9tOiAwO1xuICBsaW5lLWhlaWdodDogMS41OyB9XG5cbi5tb2RhbC1ib2R5IHtcbiAgcG9zaXRpb246IHJlbGF0aXZlO1xuICBmbGV4OiAxIDEgYXV0bztcbiAgcGFkZGluZzogMTVweDsgfVxuXG4ubW9kYWwtZm9vdGVyIHtcbiAgZGlzcGxheTogZmxleDtcbiAgYWxpZ24taXRlbXM6IGNlbnRlcjtcbiAganVzdGlmeS1jb250ZW50OiBmbGV4LWVuZDtcbiAgcGFkZGluZzogMTVweDtcbiAgYm9yZGVyLXRvcDogMXB4IHNvbGlkICNlOWVjZWY7IH1cbiAgLm1vZGFsLWZvb3RlciA+IDpub3QoOmZpcnN0LWNoaWxkKSB7XG4gICAgbWFyZ2luLWxlZnQ6IC4yNXJlbTsgfVxuICAubW9kYWwtZm9vdGVyID4gOm5vdCg6bGFzdC1jaGlsZCkge1xuICAgIG1hcmdpbi1yaWdodDogLjI1cmVtOyB9XG5cbi5tb2RhbC1zY3JvbGxiYXItbWVhc3VyZSB7XG4gIHBvc2l0aW9uOiBhYnNvbHV0ZTtcbiAgdG9wOiAtOTk5OXB4O1xuICB3aWR0aDogNTBweDtcbiAgaGVpZ2h0OiA1MHB4O1xuICBvdmVyZmxvdzogc2Nyb2xsOyB9XG5cbkBtZWRpYSAobWluLXdpZHRoOiA1NzZweCkge1xuICAubW9kYWwtZGlhbG9nIHtcbiAgICBtYXgtd2lkdGg6IDUwMHB4O1xuICAgIG1hcmdpbjogMzBweCBhdXRvOyB9XG4gIC5tb2RhbC1zbSB7XG4gICAgbWF4LXdpZHRoOiAzMDBweDsgfSB9XG5cbkBtZWRpYSAobWluLXdpZHRoOiA5OTJweCkge1xuICAubW9kYWwtbGcge1xuICAgIG1heC13aWR0aDogODAwcHg7IH0gfVxuXG4udG9vbHRpcCB7XG4gIHBvc2l0aW9uOiBhYnNvbHV0ZTtcbiAgei1pbmRleDogMTA3MDtcbiAgZGlzcGxheTogYmxvY2s7XG4gIG1hcmdpbjogMDtcbiAgZm9udC1mYW1pbHk6IC1hcHBsZS1zeXN0ZW0sIEJsaW5rTWFjU3lzdGVtRm9udCwgXCJTZWdvZSBVSVwiLCBSb2JvdG8sIFwiSGVsdmV0aWNhIE5ldWVcIiwgQXJpYWwsIHNhbnMtc2VyaWYsIFwiQXBwbGUgQ29sb3IgRW1vamlcIiwgXCJTZWdvZSBVSSBFbW9qaVwiLCBcIlNlZ29lIFVJIFN5bWJvbFwiO1xuICBmb250LXN0eWxlOiBub3JtYWw7XG4gIGZvbnQtd2VpZ2h0OiBub3JtYWw7XG4gIGxpbmUtaGVpZ2h0OiAxLjU7XG4gIHRleHQtYWxpZ246IGxlZnQ7XG4gIHRleHQtYWxpZ246IHN0YXJ0O1xuICB0ZXh0LWRlY29yYXRpb246IG5vbmU7XG4gIHRleHQtc2hhZG93OiBub25lO1xuICB0ZXh0LXRyYW5zZm9ybTogbm9uZTtcbiAgbGV0dGVyLXNwYWNpbmc6IG5vcm1hbDtcbiAgd29yZC1icmVhazogbm9ybWFsO1xuICB3b3JkLXNwYWNpbmc6IG5vcm1hbDtcbiAgd2hpdGUtc3BhY2U6IG5vcm1hbDtcbiAgbGluZS1icmVhazogYXV0bztcbiAgZm9udC1zaXplOiAwLjg3NXJlbTtcbiAgd29yZC13cmFwOiBicmVhay13b3JkO1xuICBvcGFjaXR5OiAwOyB9XG4gIC50b29sdGlwLnNob3cge1xuICAgIG9wYWNpdHk6IDAuOTsgfVxuICAudG9vbHRpcCAuYXJyb3cge1xuICAgIHBvc2l0aW9uOiBhYnNvbHV0ZTtcbiAgICBkaXNwbGF5OiBibG9jaztcbiAgICB3aWR0aDogNXB4O1xuICAgIGhlaWdodDogNXB4OyB9XG4gIC50b29sdGlwLmJzLXRvb2x0aXAtdG9wLCAudG9vbHRpcC5icy10b29sdGlwLWF1dG9beC1wbGFjZW1lbnRePVwidG9wXCJdIHtcbiAgICBwYWRkaW5nOiA1cHggMDsgfVxuICAgIC50b29sdGlwLmJzLXRvb2x0aXAtdG9wIC5hcnJvdywgLnRvb2x0aXAuYnMtdG9vbHRpcC1hdXRvW3gtcGxhY2VtZW50Xj1cInRvcFwiXSAuYXJyb3cge1xuICAgICAgYm90dG9tOiAwOyB9XG4gICAgLnRvb2x0aXAuYnMtdG9vbHRpcC10b3AgLmFycm93OjpiZWZvcmUsIC50b29sdGlwLmJzLXRvb2x0aXAtYXV0b1t4LXBsYWNlbWVudF49XCJ0b3BcIl0gLmFycm93OjpiZWZvcmUge1xuICAgICAgbWFyZ2luLWxlZnQ6IC0zcHg7XG4gICAgICBjb250ZW50OiBcIlwiO1xuICAgICAgYm9yZGVyLXdpZHRoOiA1cHggNXB4IDA7XG4gICAgICBib3JkZXItdG9wLWNvbG9yOiAjMDAwOyB9XG4gIC50b29sdGlwLmJzLXRvb2x0aXAtcmlnaHQsIC50b29sdGlwLmJzLXRvb2x0aXAtYXV0b1t4LXBsYWNlbWVudF49XCJyaWdodFwiXSB7XG4gICAgcGFkZGluZzogMCA1cHg7IH1cbiAgICAudG9vbHRpcC5icy10b29sdGlwLXJpZ2h0IC5hcnJvdywgLnRvb2x0aXAuYnMtdG9vbHRpcC1hdXRvW3gtcGxhY2VtZW50Xj1cInJpZ2h0XCJdIC5hcnJvdyB7XG4gICAgICBsZWZ0OiAwOyB9XG4gICAgLnRvb2x0aXAuYnMtdG9vbHRpcC1yaWdodCAuYXJyb3c6OmJlZm9yZSwgLnRvb2x0aXAuYnMtdG9vbHRpcC1hdXRvW3gtcGxhY2VtZW50Xj1cInJpZ2h0XCJdIC5hcnJvdzo6YmVmb3JlIHtcbiAgICAgIG1hcmdpbi10b3A6IC0zcHg7XG4gICAgICBjb250ZW50OiBcIlwiO1xuICAgICAgYm9yZGVyLXdpZHRoOiA1cHggNXB4IDVweCAwO1xuICAgICAgYm9yZGVyLXJpZ2h0LWNvbG9yOiAjMDAwOyB9XG4gIC50b29sdGlwLmJzLXRvb2x0aXAtYm90dG9tLCAudG9vbHRpcC5icy10b29sdGlwLWF1dG9beC1wbGFjZW1lbnRePVwiYm90dG9tXCJdIHtcbiAgICBwYWRkaW5nOiA1cHggMDsgfVxuICAgIC50b29sdGlwLmJzLXRvb2x0aXAtYm90dG9tIC5hcnJvdywgLnRvb2x0aXAuYnMtdG9vbHRpcC1hdXRvW3gtcGxhY2VtZW50Xj1cImJvdHRvbVwiXSAuYXJyb3cge1xuICAgICAgdG9wOiAwOyB9XG4gICAgLnRvb2x0aXAuYnMtdG9vbHRpcC1ib3R0b20gLmFycm93OjpiZWZvcmUsIC50b29sdGlwLmJzLXRvb2x0aXAtYXV0b1t4LXBsYWNlbWVudF49XCJib3R0b21cIl0gLmFycm93OjpiZWZvcmUge1xuICAgICAgbWFyZ2luLWxlZnQ6IC0zcHg7XG4gICAgICBjb250ZW50OiBcIlwiO1xuICAgICAgYm9yZGVyLXdpZHRoOiAwIDVweCA1cHg7XG4gICAgICBib3JkZXItYm90dG9tLWNvbG9yOiAjMDAwOyB9XG4gIC50b29sdGlwLmJzLXRvb2x0aXAtbGVmdCwgLnRvb2x0aXAuYnMtdG9vbHRpcC1hdXRvW3gtcGxhY2VtZW50Xj1cImxlZnRcIl0ge1xuICAgIHBhZGRpbmc6IDAgNXB4OyB9XG4gICAgLnRvb2x0aXAuYnMtdG9vbHRpcC1sZWZ0IC5hcnJvdywgLnRvb2x0aXAuYnMtdG9vbHRpcC1hdXRvW3gtcGxhY2VtZW50Xj1cImxlZnRcIl0gLmFycm93IHtcbiAgICAgIHJpZ2h0OiAwOyB9XG4gICAgLnRvb2x0aXAuYnMtdG9vbHRpcC1sZWZ0IC5hcnJvdzo6YmVmb3JlLCAudG9vbHRpcC5icy10b29sdGlwLWF1dG9beC1wbGFjZW1lbnRePVwibGVmdFwiXSAuYXJyb3c6OmJlZm9yZSB7XG4gICAgICByaWdodDogMDtcbiAgICAgIG1hcmdpbi10b3A6IC0zcHg7XG4gICAgICBjb250ZW50OiBcIlwiO1xuICAgICAgYm9yZGVyLXdpZHRoOiA1cHggMCA1cHggNXB4O1xuICAgICAgYm9yZGVyLWxlZnQtY29sb3I6ICMwMDA7IH1cbiAgLnRvb2x0aXAgLmFycm93OjpiZWZvcmUge1xuICAgIHBvc2l0aW9uOiBhYnNvbHV0ZTtcbiAgICBib3JkZXItY29sb3I6IHRyYW5zcGFyZW50O1xuICAgIGJvcmRlci1zdHlsZTogc29saWQ7IH1cblxuLnRvb2x0aXAtaW5uZXIge1xuICBtYXgtd2lkdGg6IDIwMHB4O1xuICBwYWRkaW5nOiAzcHggOHB4O1xuICBjb2xvcjogI2ZmZjtcbiAgdGV4dC1hbGlnbjogY2VudGVyO1xuICBiYWNrZ3JvdW5kLWNvbG9yOiAjMDAwO1xuICBib3JkZXItcmFkaXVzOiAwLjI1cmVtOyB9XG5cbi5wb3BvdmVyIHtcbiAgcG9zaXRpb246IGFic29sdXRlO1xuICB0b3A6IDA7XG4gIGxlZnQ6IDA7XG4gIHotaW5kZXg6IDEwNjA7XG4gIGRpc3BsYXk6IGJsb2NrO1xuICBtYXgtd2lkdGg6IDI3NnB4O1xuICBwYWRkaW5nOiAxcHg7XG4gIGZvbnQtZmFtaWx5OiAtYXBwbGUtc3lzdGVtLCBCbGlua01hY1N5c3RlbUZvbnQsIFwiU2Vnb2UgVUlcIiwgUm9ib3RvLCBcIkhlbHZldGljYSBOZXVlXCIsIEFyaWFsLCBzYW5zLXNlcmlmLCBcIkFwcGxlIENvbG9yIEVtb2ppXCIsIFwiU2Vnb2UgVUkgRW1vamlcIiwgXCJTZWdvZSBVSSBTeW1ib2xcIjtcbiAgZm9udC1zdHlsZTogbm9ybWFsO1xuICBmb250LXdlaWdodDogbm9ybWFsO1xuICBsaW5lLWhlaWdodDogMS41O1xuICB0ZXh0LWFsaWduOiBsZWZ0O1xuICB0ZXh0LWFsaWduOiBzdGFydDtcbiAgdGV4dC1kZWNvcmF0aW9uOiBub25lO1xuICB0ZXh0LXNoYWRvdzogbm9uZTtcbiAgdGV4dC10cmFuc2Zvcm06IG5vbmU7XG4gIGxldHRlci1zcGFjaW5nOiBub3JtYWw7XG4gIHdvcmQtYnJlYWs6IG5vcm1hbDtcbiAgd29yZC1zcGFjaW5nOiBub3JtYWw7XG4gIHdoaXRlLXNwYWNlOiBub3JtYWw7XG4gIGxpbmUtYnJlYWs6IGF1dG87XG4gIGZvbnQtc2l6ZTogMC44NzVyZW07XG4gIHdvcmQtd3JhcDogYnJlYWstd29yZDtcbiAgYmFja2dyb3VuZC1jb2xvcjogI2ZmZjtcbiAgYmFja2dyb3VuZC1jbGlwOiBwYWRkaW5nLWJveDtcbiAgYm9yZGVyOiAxcHggc29saWQgcmdiYSgwLCAwLCAwLCAwLjIpO1xuICBib3JkZXItcmFkaXVzOiAwLjNyZW07IH1cbiAgLnBvcG92ZXIgLmFycm93IHtcbiAgICBwb3NpdGlvbjogYWJzb2x1dGU7XG4gICAgZGlzcGxheTogYmxvY2s7XG4gICAgd2lkdGg6IDEwcHg7XG4gICAgaGVpZ2h0OiA1cHg7IH1cbiAgLnBvcG92ZXIgLmFycm93OjpiZWZvcmUsXG4gIC5wb3BvdmVyIC5hcnJvdzo6YWZ0ZXIge1xuICAgIHBvc2l0aW9uOiBhYnNvbHV0ZTtcbiAgICBkaXNwbGF5OiBibG9jaztcbiAgICBib3JkZXItY29sb3I6IHRyYW5zcGFyZW50O1xuICAgIGJvcmRlci1zdHlsZTogc29saWQ7IH1cbiAgLnBvcG92ZXIgLmFycm93OjpiZWZvcmUge1xuICAgIGNvbnRlbnQ6IFwiXCI7XG4gICAgYm9yZGVyLXdpZHRoOiAxMXB4OyB9XG4gIC5wb3BvdmVyIC5hcnJvdzo6YWZ0ZXIge1xuICAgIGNvbnRlbnQ6IFwiXCI7XG4gICAgYm9yZGVyLXdpZHRoOiAxMXB4OyB9XG4gIC5wb3BvdmVyLmJzLXBvcG92ZXItdG9wLCAucG9wb3Zlci5icy1wb3BvdmVyLWF1dG9beC1wbGFjZW1lbnRePVwidG9wXCJdIHtcbiAgICBtYXJnaW4tYm90dG9tOiAxMHB4OyB9XG4gICAgLnBvcG92ZXIuYnMtcG9wb3Zlci10b3AgLmFycm93LCAucG9wb3Zlci5icy1wb3BvdmVyLWF1dG9beC1wbGFjZW1lbnRePVwidG9wXCJdIC5hcnJvdyB7XG4gICAgICBib3R0b206IDA7IH1cbiAgICAucG9wb3Zlci5icy1wb3BvdmVyLXRvcCAuYXJyb3c6OmJlZm9yZSwgLnBvcG92ZXIuYnMtcG9wb3Zlci1hdXRvW3gtcGxhY2VtZW50Xj1cInRvcFwiXSAuYXJyb3c6OmJlZm9yZSxcbiAgICAucG9wb3Zlci5icy1wb3BvdmVyLXRvcCAuYXJyb3c6OmFmdGVyLCAucG9wb3Zlci5icy1wb3BvdmVyLWF1dG9beC1wbGFjZW1lbnRePVwidG9wXCJdIC5hcnJvdzo6YWZ0ZXIge1xuICAgICAgYm9yZGVyLWJvdHRvbS13aWR0aDogMDsgfVxuICAgIC5wb3BvdmVyLmJzLXBvcG92ZXItdG9wIC5hcnJvdzo6YmVmb3JlLCAucG9wb3Zlci5icy1wb3BvdmVyLWF1dG9beC1wbGFjZW1lbnRePVwidG9wXCJdIC5hcnJvdzo6YmVmb3JlIHtcbiAgICAgIGJvdHRvbTogLTExcHg7XG4gICAgICBtYXJnaW4tbGVmdDogLTZweDtcbiAgICAgIGJvcmRlci10b3AtY29sb3I6IHJnYmEoMCwgMCwgMCwgMC4yNSk7IH1cbiAgICAucG9wb3Zlci5icy1wb3BvdmVyLXRvcCAuYXJyb3c6OmFmdGVyLCAucG9wb3Zlci5icy1wb3BvdmVyLWF1dG9beC1wbGFjZW1lbnRePVwidG9wXCJdIC5hcnJvdzo6YWZ0ZXIge1xuICAgICAgYm90dG9tOiAtMTBweDtcbiAgICAgIG1hcmdpbi1sZWZ0OiAtNnB4O1xuICAgICAgYm9yZGVyLXRvcC1jb2xvcjogI2ZmZjsgfVxuICAucG9wb3Zlci5icy1wb3BvdmVyLXJpZ2h0LCAucG9wb3Zlci5icy1wb3BvdmVyLWF1dG9beC1wbGFjZW1lbnRePVwicmlnaHRcIl0ge1xuICAgIG1hcmdpbi1sZWZ0OiAxMHB4OyB9XG4gICAgLnBvcG92ZXIuYnMtcG9wb3Zlci1yaWdodCAuYXJyb3csIC5wb3BvdmVyLmJzLXBvcG92ZXItYXV0b1t4LXBsYWNlbWVudF49XCJyaWdodFwiXSAuYXJyb3cge1xuICAgICAgbGVmdDogMDsgfVxuICAgIC5wb3BvdmVyLmJzLXBvcG92ZXItcmlnaHQgLmFycm93OjpiZWZvcmUsIC5wb3BvdmVyLmJzLXBvcG92ZXItYXV0b1t4LXBsYWNlbWVudF49XCJyaWdodFwiXSAuYXJyb3c6OmJlZm9yZSxcbiAgICAucG9wb3Zlci5icy1wb3BvdmVyLXJpZ2h0IC5hcnJvdzo6YWZ0ZXIsIC5wb3BvdmVyLmJzLXBvcG92ZXItYXV0b1t4LXBsYWNlbWVudF49XCJyaWdodFwiXSAuYXJyb3c6OmFmdGVyIHtcbiAgICAgIG1hcmdpbi10b3A6IC04cHg7XG4gICAgICBib3JkZXItbGVmdC13aWR0aDogMDsgfVxuICAgIC5wb3BvdmVyLmJzLXBvcG92ZXItcmlnaHQgLmFycm93OjpiZWZvcmUsIC5wb3BvdmVyLmJzLXBvcG92ZXItYXV0b1t4LXBsYWNlbWVudF49XCJyaWdodFwiXSAuYXJyb3c6OmJlZm9yZSB7XG4gICAgICBsZWZ0OiAtMTFweDtcbiAgICAgIGJvcmRlci1yaWdodC1jb2xvcjogcmdiYSgwLCAwLCAwLCAwLjI1KTsgfVxuICAgIC5wb3BvdmVyLmJzLXBvcG92ZXItcmlnaHQgLmFycm93OjphZnRlciwgLnBvcG92ZXIuYnMtcG9wb3Zlci1hdXRvW3gtcGxhY2VtZW50Xj1cInJpZ2h0XCJdIC5hcnJvdzo6YWZ0ZXIge1xuICAgICAgbGVmdDogLTEwcHg7XG4gICAgICBib3JkZXItcmlnaHQtY29sb3I6ICNmZmY7IH1cbiAgLnBvcG92ZXIuYnMtcG9wb3Zlci1ib3R0b20sIC5wb3BvdmVyLmJzLXBvcG92ZXItYXV0b1t4LXBsYWNlbWVudF49XCJib3R0b21cIl0ge1xuICAgIG1hcmdpbi10b3A6IDEwcHg7IH1cbiAgICAucG9wb3Zlci5icy1wb3BvdmVyLWJvdHRvbSAuYXJyb3csIC5wb3BvdmVyLmJzLXBvcG92ZXItYXV0b1t4LXBsYWNlbWVudF49XCJib3R0b21cIl0gLmFycm93IHtcbiAgICAgIHRvcDogMDsgfVxuICAgIC5wb3BvdmVyLmJzLXBvcG92ZXItYm90dG9tIC5hcnJvdzo6YmVmb3JlLCAucG9wb3Zlci5icy1wb3BvdmVyLWF1dG9beC1wbGFjZW1lbnRePVwiYm90dG9tXCJdIC5hcnJvdzo6YmVmb3JlLFxuICAgIC5wb3BvdmVyLmJzLXBvcG92ZXItYm90dG9tIC5hcnJvdzo6YWZ0ZXIsIC5wb3BvdmVyLmJzLXBvcG92ZXItYXV0b1t4LXBsYWNlbWVudF49XCJib3R0b21cIl0gLmFycm93OjphZnRlciB7XG4gICAgICBtYXJnaW4tbGVmdDogLTdweDtcbiAgICAgIGJvcmRlci10b3Atd2lkdGg6IDA7IH1cbiAgICAucG9wb3Zlci5icy1wb3BvdmVyLWJvdHRvbSAuYXJyb3c6OmJlZm9yZSwgLnBvcG92ZXIuYnMtcG9wb3Zlci1hdXRvW3gtcGxhY2VtZW50Xj1cImJvdHRvbVwiXSAuYXJyb3c6OmJlZm9yZSB7XG4gICAgICB0b3A6IC0xMXB4O1xuICAgICAgYm9yZGVyLWJvdHRvbS1jb2xvcjogcmdiYSgwLCAwLCAwLCAwLjI1KTsgfVxuICAgIC5wb3BvdmVyLmJzLXBvcG92ZXItYm90dG9tIC5hcnJvdzo6YWZ0ZXIsIC5wb3BvdmVyLmJzLXBvcG92ZXItYXV0b1t4LXBsYWNlbWVudF49XCJib3R0b21cIl0gLmFycm93OjphZnRlciB7XG4gICAgICB0b3A6IC0xMHB4O1xuICAgICAgYm9yZGVyLWJvdHRvbS1jb2xvcjogI2ZmZjsgfVxuICAgIC5wb3BvdmVyLmJzLXBvcG92ZXItYm90dG9tIC5wb3BvdmVyLWhlYWRlcjo6YmVmb3JlLCAucG9wb3Zlci5icy1wb3BvdmVyLWF1dG9beC1wbGFjZW1lbnRePVwiYm90dG9tXCJdIC5wb3BvdmVyLWhlYWRlcjo6YmVmb3JlIHtcbiAgICAgIHBvc2l0aW9uOiBhYnNvbHV0ZTtcbiAgICAgIHRvcDogMDtcbiAgICAgIGxlZnQ6IDUwJTtcbiAgICAgIGRpc3BsYXk6IGJsb2NrO1xuICAgICAgd2lkdGg6IDIwcHg7XG4gICAgICBtYXJnaW4tbGVmdDogLTEwcHg7XG4gICAgICBjb250ZW50OiBcIlwiO1xuICAgICAgYm9yZGVyLWJvdHRvbTogMXB4IHNvbGlkICNmN2Y3Zjc7IH1cbiAgLnBvcG92ZXIuYnMtcG9wb3Zlci1sZWZ0LCAucG9wb3Zlci5icy1wb3BvdmVyLWF1dG9beC1wbGFjZW1lbnRePVwibGVmdFwiXSB7XG4gICAgbWFyZ2luLXJpZ2h0OiAxMHB4OyB9XG4gICAgLnBvcG92ZXIuYnMtcG9wb3Zlci1sZWZ0IC5hcnJvdywgLnBvcG92ZXIuYnMtcG9wb3Zlci1hdXRvW3gtcGxhY2VtZW50Xj1cImxlZnRcIl0gLmFycm93IHtcbiAgICAgIHJpZ2h0OiAwOyB9XG4gICAgLnBvcG92ZXIuYnMtcG9wb3Zlci1sZWZ0IC5hcnJvdzo6YmVmb3JlLCAucG9wb3Zlci5icy1wb3BvdmVyLWF1dG9beC1wbGFjZW1lbnRePVwibGVmdFwiXSAuYXJyb3c6OmJlZm9yZSxcbiAgICAucG9wb3Zlci5icy1wb3BvdmVyLWxlZnQgLmFycm93OjphZnRlciwgLnBvcG92ZXIuYnMtcG9wb3Zlci1hdXRvW3gtcGxhY2VtZW50Xj1cImxlZnRcIl0gLmFycm93OjphZnRlciB7XG4gICAgICBtYXJnaW4tdG9wOiAtOHB4O1xuICAgICAgYm9yZGVyLXJpZ2h0LXdpZHRoOiAwOyB9XG4gICAgLnBvcG92ZXIuYnMtcG9wb3Zlci1sZWZ0IC5hcnJvdzo6YmVmb3JlLCAucG9wb3Zlci5icy1wb3BvdmVyLWF1dG9beC1wbGFjZW1lbnRePVwibGVmdFwiXSAuYXJyb3c6OmJlZm9yZSB7XG4gICAgICByaWdodDogLTExcHg7XG4gICAgICBib3JkZXItbGVmdC1jb2xvcjogcmdiYSgwLCAwLCAwLCAwLjI1KTsgfVxuICAgIC5wb3BvdmVyLmJzLXBvcG92ZXItbGVmdCAuYXJyb3c6OmFmdGVyLCAucG9wb3Zlci5icy1wb3BvdmVyLWF1dG9beC1wbGFjZW1lbnRePVwibGVmdFwiXSAuYXJyb3c6OmFmdGVyIHtcbiAgICAgIHJpZ2h0OiAtMTBweDtcbiAgICAgIGJvcmRlci1sZWZ0LWNvbG9yOiAjZmZmOyB9XG5cbi5wb3BvdmVyLWhlYWRlciB7XG4gIHBhZGRpbmc6IDhweCAxNHB4O1xuICBtYXJnaW4tYm90dG9tOiAwO1xuICBmb250LXNpemU6IDFyZW07XG4gIGNvbG9yOiBpbmhlcml0O1xuICBiYWNrZ3JvdW5kLWNvbG9yOiAjZjdmN2Y3O1xuICBib3JkZXItYm90dG9tOiAxcHggc29saWQgI2ViZWJlYjtcbiAgYm9yZGVyLXRvcC1sZWZ0LXJhZGl1czogY2FsYygwLjNyZW0gLSAxcHgpO1xuICBib3JkZXItdG9wLXJpZ2h0LXJhZGl1czogY2FsYygwLjNyZW0gLSAxcHgpOyB9XG4gIC5wb3BvdmVyLWhlYWRlcjplbXB0eSB7XG4gICAgZGlzcGxheTogbm9uZTsgfVxuXG4ucG9wb3Zlci1ib2R5IHtcbiAgcGFkZGluZzogOXB4IDE0cHg7XG4gIGNvbG9yOiAjMjEyNTI5OyB9XG5cbi5jYXJvdXNlbCB7XG4gIHBvc2l0aW9uOiByZWxhdGl2ZTsgfVxuXG4uY2Fyb3VzZWwtaW5uZXIge1xuICBwb3NpdGlvbjogcmVsYXRpdmU7XG4gIHdpZHRoOiAxMDAlO1xuICBvdmVyZmxvdzogaGlkZGVuOyB9XG5cbi5jYXJvdXNlbC1pdGVtIHtcbiAgcG9zaXRpb246IHJlbGF0aXZlO1xuICBkaXNwbGF5OiBub25lO1xuICBhbGlnbi1pdGVtczogY2VudGVyO1xuICB3aWR0aDogMTAwJTtcbiAgdHJhbnNpdGlvbjogdHJhbnNmb3JtIDAuNnMgZWFzZTtcbiAgYmFja2ZhY2UtdmlzaWJpbGl0eTogaGlkZGVuO1xuICBwZXJzcGVjdGl2ZTogMTAwMHB4OyB9XG5cbi5jYXJvdXNlbC1pdGVtLmFjdGl2ZSxcbi5jYXJvdXNlbC1pdGVtLW5leHQsXG4uY2Fyb3VzZWwtaXRlbS1wcmV2IHtcbiAgZGlzcGxheTogYmxvY2s7IH1cblxuLmNhcm91c2VsLWl0ZW0tbmV4dCxcbi5jYXJvdXNlbC1pdGVtLXByZXYge1xuICBwb3NpdGlvbjogYWJzb2x1dGU7XG4gIHRvcDogMDsgfVxuXG4uY2Fyb3VzZWwtaXRlbS1uZXh0LmNhcm91c2VsLWl0ZW0tbGVmdCxcbi5jYXJvdXNlbC1pdGVtLXByZXYuY2Fyb3VzZWwtaXRlbS1yaWdodCB7XG4gIHRyYW5zZm9ybTogdHJhbnNsYXRlWCgwKTsgfVxuICBAc3VwcG9ydHMgKHRyYW5zZm9ybS1zdHlsZTogcHJlc2VydmUtM2QpIHtcbiAgICAuY2Fyb3VzZWwtaXRlbS1uZXh0LmNhcm91c2VsLWl0ZW0tbGVmdCxcbiAgICAuY2Fyb3VzZWwtaXRlbS1wcmV2LmNhcm91c2VsLWl0ZW0tcmlnaHQge1xuICAgICAgdHJhbnNmb3JtOiB0cmFuc2xhdGUzZCgwLCAwLCAwKTsgfSB9XG5cbi5jYXJvdXNlbC1pdGVtLW5leHQsXG4uYWN0aXZlLmNhcm91c2VsLWl0ZW0tcmlnaHQge1xuICB0cmFuc2Zvcm06IHRyYW5zbGF0ZVgoMTAwJSk7IH1cbiAgQHN1cHBvcnRzICh0cmFuc2Zvcm0tc3R5bGU6IHByZXNlcnZlLTNkKSB7XG4gICAgLmNhcm91c2VsLWl0ZW0tbmV4dCxcbiAgICAuYWN0aXZlLmNhcm91c2VsLWl0ZW0tcmlnaHQge1xuICAgICAgdHJhbnNmb3JtOiB0cmFuc2xhdGUzZCgxMDAlLCAwLCAwKTsgfSB9XG5cbi5jYXJvdXNlbC1pdGVtLXByZXYsXG4uYWN0aXZlLmNhcm91c2VsLWl0ZW0tbGVmdCB7XG4gIHRyYW5zZm9ybTogdHJhbnNsYXRlWCgtMTAwJSk7IH1cbiAgQHN1cHBvcnRzICh0cmFuc2Zvcm0tc3R5bGU6IHByZXNlcnZlLTNkKSB7XG4gICAgLmNhcm91c2VsLWl0ZW0tcHJldixcbiAgICAuYWN0aXZlLmNhcm91c2VsLWl0ZW0tbGVmdCB7XG4gICAgICB0cmFuc2Zvcm06IHRyYW5zbGF0ZTNkKC0xMDAlLCAwLCAwKTsgfSB9XG5cbi5jYXJvdXNlbC1jb250cm9sLXByZXYsXG4uY2Fyb3VzZWwtY29udHJvbC1uZXh0IHtcbiAgcG9zaXRpb246IGFic29sdXRlO1xuICB0b3A6IDA7XG4gIGJvdHRvbTogMDtcbiAgZGlzcGxheTogZmxleDtcbiAgYWxpZ24taXRlbXM6IGNlbnRlcjtcbiAganVzdGlmeS1jb250ZW50OiBjZW50ZXI7XG4gIHdpZHRoOiAxNSU7XG4gIGNvbG9yOiAjZmZmO1xuICB0ZXh0LWFsaWduOiBjZW50ZXI7XG4gIG9wYWNpdHk6IDAuNTsgfVxuICAuY2Fyb3VzZWwtY29udHJvbC1wcmV2OmZvY3VzLCAuY2Fyb3VzZWwtY29udHJvbC1wcmV2OmhvdmVyLFxuICAuY2Fyb3VzZWwtY29udHJvbC1uZXh0OmZvY3VzLFxuICAuY2Fyb3VzZWwtY29udHJvbC1uZXh0OmhvdmVyIHtcbiAgICBjb2xvcjogI2ZmZjtcbiAgICB0ZXh0LWRlY29yYXRpb246IG5vbmU7XG4gICAgb3V0bGluZTogMDtcbiAgICBvcGFjaXR5OiAuOTsgfVxuXG4uY2Fyb3VzZWwtY29udHJvbC1wcmV2IHtcbiAgbGVmdDogMDsgfVxuXG4uY2Fyb3VzZWwtY29udHJvbC1uZXh0IHtcbiAgcmlnaHQ6IDA7IH1cblxuLmNhcm91c2VsLWNvbnRyb2wtcHJldi1pY29uLFxuLmNhcm91c2VsLWNvbnRyb2wtbmV4dC1pY29uIHtcbiAgZGlzcGxheTogaW5saW5lLWJsb2NrO1xuICB3aWR0aDogMjBweDtcbiAgaGVpZ2h0OiAyMHB4O1xuICBiYWNrZ3JvdW5kOiB0cmFuc3BhcmVudCBuby1yZXBlYXQgY2VudGVyIGNlbnRlcjtcbiAgYmFja2dyb3VuZC1zaXplOiAxMDAlIDEwMCU7IH1cblxuLmNhcm91c2VsLWNvbnRyb2wtcHJldi1pY29uIHtcbiAgYmFja2dyb3VuZC1pbWFnZTogdXJsKFwiZGF0YTppbWFnZS9zdmcreG1sO2NoYXJzZXQ9dXRmOCwlM0NzdmcgeG1sbnM9J2h0dHA6Ly93d3cudzMub3JnLzIwMDAvc3ZnJyBmaWxsPSclMjNmZmYnIHZpZXdCb3g9JzAgMCA4IDgnJTNFJTNDcGF0aCBkPSdNNCAwbC00IDQgNCA0IDEuNS0xLjUtMi41LTIuNSAyLjUtMi41LTEuNS0xLjV6Jy8lM0UlM0Mvc3ZnJTNFXCIpOyB9XG5cbi5jYXJvdXNlbC1jb250cm9sLW5leHQtaWNvbiB7XG4gIGJhY2tncm91bmQtaW1hZ2U6IHVybChcImRhdGE6aW1hZ2Uvc3ZnK3htbDtjaGFyc2V0PXV0ZjgsJTNDc3ZnIHhtbG5zPSdodHRwOi8vd3d3LnczLm9yZy8yMDAwL3N2ZycgZmlsbD0nJTIzZmZmJyB2aWV3Qm94PScwIDAgOCA4JyUzRSUzQ3BhdGggZD0nTTEuNSAwbC0xLjUgMS41IDIuNSAyLjUtMi41IDIuNSAxLjUgMS41IDQtNC00LTR6Jy8lM0UlM0Mvc3ZnJTNFXCIpOyB9XG5cbi5jYXJvdXNlbC1pbmRpY2F0b3JzIHtcbiAgcG9zaXRpb246IGFic29sdXRlO1xuICByaWdodDogMDtcbiAgYm90dG9tOiAxMHB4O1xuICBsZWZ0OiAwO1xuICB6LWluZGV4OiAxNTtcbiAgZGlzcGxheTogZmxleDtcbiAganVzdGlmeS1jb250ZW50OiBjZW50ZXI7XG4gIHBhZGRpbmctbGVmdDogMDtcbiAgbWFyZ2luLXJpZ2h0OiAxNSU7XG4gIG1hcmdpbi1sZWZ0OiAxNSU7XG4gIGxpc3Qtc3R5bGU6IG5vbmU7IH1cbiAgLmNhcm91c2VsLWluZGljYXRvcnMgbGkge1xuICAgIHBvc2l0aW9uOiByZWxhdGl2ZTtcbiAgICBmbGV4OiAwIDEgYXV0bztcbiAgICB3aWR0aDogMzBweDtcbiAgICBoZWlnaHQ6IDNweDtcbiAgICBtYXJnaW4tcmlnaHQ6IDNweDtcbiAgICBtYXJnaW4tbGVmdDogM3B4O1xuICAgIHRleHQtaW5kZW50OiAtOTk5cHg7XG4gICAgYmFja2dyb3VuZC1jb2xvcjogcmdiYSgyNTUsIDI1NSwgMjU1LCAwLjUpOyB9XG4gICAgLmNhcm91c2VsLWluZGljYXRvcnMgbGk6OmJlZm9yZSB7XG4gICAgICBwb3NpdGlvbjogYWJzb2x1dGU7XG4gICAgICB0b3A6IC0xMHB4O1xuICAgICAgbGVmdDogMDtcbiAgICAgIGRpc3BsYXk6IGlubGluZS1ibG9jaztcbiAgICAgIHdpZHRoOiAxMDAlO1xuICAgICAgaGVpZ2h0OiAxMHB4O1xuICAgICAgY29udGVudDogXCJcIjsgfVxuICAgIC5jYXJvdXNlbC1pbmRpY2F0b3JzIGxpOjphZnRlciB7XG4gICAgICBwb3NpdGlvbjogYWJzb2x1dGU7XG4gICAgICBib3R0b206IC0xMHB4O1xuICAgICAgbGVmdDogMDtcbiAgICAgIGRpc3BsYXk6IGlubGluZS1ibG9jaztcbiAgICAgIHdpZHRoOiAxMDAlO1xuICAgICAgaGVpZ2h0OiAxMHB4O1xuICAgICAgY29udGVudDogXCJcIjsgfVxuICAuY2Fyb3VzZWwtaW5kaWNhdG9ycyAuYWN0aXZlIHtcbiAgICBiYWNrZ3JvdW5kLWNvbG9yOiAjZmZmOyB9XG5cbi5jYXJvdXNlbC1jYXB0aW9uIHtcbiAgcG9zaXRpb246IGFic29sdXRlO1xuICByaWdodDogMTUlO1xuICBib3R0b206IDIwcHg7XG4gIGxlZnQ6IDE1JTtcbiAgei1pbmRleDogMTA7XG4gIHBhZGRpbmctdG9wOiAyMHB4O1xuICBwYWRkaW5nLWJvdHRvbTogMjBweDtcbiAgY29sb3I6ICNmZmY7XG4gIHRleHQtYWxpZ246IGNlbnRlcjsgfVxuXG4uYWxpZ24tYmFzZWxpbmUge1xuICB2ZXJ0aWNhbC1hbGlnbjogYmFzZWxpbmUgIWltcG9ydGFudDsgfVxuXG4uYWxpZ24tdG9wIHtcbiAgdmVydGljYWwtYWxpZ246IHRvcCAhaW1wb3J0YW50OyB9XG5cbi5hbGlnbi1taWRkbGUge1xuICB2ZXJ0aWNhbC1hbGlnbjogbWlkZGxlICFpbXBvcnRhbnQ7IH1cblxuLmFsaWduLWJvdHRvbSB7XG4gIHZlcnRpY2FsLWFsaWduOiBib3R0b20gIWltcG9ydGFudDsgfVxuXG4uYWxpZ24tdGV4dC1ib3R0b20ge1xuICB2ZXJ0aWNhbC1hbGlnbjogdGV4dC1ib3R0b20gIWltcG9ydGFudDsgfVxuXG4uYWxpZ24tdGV4dC10b3Age1xuICB2ZXJ0aWNhbC1hbGlnbjogdGV4dC10b3AgIWltcG9ydGFudDsgfVxuXG4uYmctcHJpbWFyeSB7XG4gIGJhY2tncm91bmQtY29sb3I6ICMwMDdiZmYgIWltcG9ydGFudDsgfVxuXG5hLmJnLXByaW1hcnk6Zm9jdXMsIGEuYmctcHJpbWFyeTpob3ZlciB7XG4gIGJhY2tncm91bmQtY29sb3I6ICMwMDYyY2MgIWltcG9ydGFudDsgfVxuXG4uYmctc2Vjb25kYXJ5IHtcbiAgYmFja2dyb3VuZC1jb2xvcjogIzg2OGU5NiAhaW1wb3J0YW50OyB9XG5cbmEuYmctc2Vjb25kYXJ5OmZvY3VzLCBhLmJnLXNlY29uZGFyeTpob3ZlciB7XG4gIGJhY2tncm91bmQtY29sb3I6ICM2Yzc1N2QgIWltcG9ydGFudDsgfVxuXG4uYmctc3VjY2VzcyB7XG4gIGJhY2tncm91bmQtY29sb3I6ICMyOGE3NDUgIWltcG9ydGFudDsgfVxuXG5hLmJnLXN1Y2Nlc3M6Zm9jdXMsIGEuYmctc3VjY2Vzczpob3ZlciB7XG4gIGJhY2tncm91bmQtY29sb3I6ICMxZTdlMzQgIWltcG9ydGFudDsgfVxuXG4uYmctaW5mbyB7XG4gIGJhY2tncm91bmQtY29sb3I6ICMxN2EyYjggIWltcG9ydGFudDsgfVxuXG5hLmJnLWluZm86Zm9jdXMsIGEuYmctaW5mbzpob3ZlciB7XG4gIGJhY2tncm91bmQtY29sb3I6ICMxMTdhOGIgIWltcG9ydGFudDsgfVxuXG4uYmctd2FybmluZyB7XG4gIGJhY2tncm91bmQtY29sb3I6ICNmZmMxMDcgIWltcG9ydGFudDsgfVxuXG5hLmJnLXdhcm5pbmc6Zm9jdXMsIGEuYmctd2FybmluZzpob3ZlciB7XG4gIGJhY2tncm91bmQtY29sb3I6ICNkMzllMDAgIWltcG9ydGFudDsgfVxuXG4uYmctZGFuZ2VyIHtcbiAgYmFja2dyb3VuZC1jb2xvcjogI2RjMzU0NSAhaW1wb3J0YW50OyB9XG5cbmEuYmctZGFuZ2VyOmZvY3VzLCBhLmJnLWRhbmdlcjpob3ZlciB7XG4gIGJhY2tncm91bmQtY29sb3I6ICNiZDIxMzAgIWltcG9ydGFudDsgfVxuXG4uYmctbGlnaHQge1xuICBiYWNrZ3JvdW5kLWNvbG9yOiAjZjhmOWZhICFpbXBvcnRhbnQ7IH1cblxuYS5iZy1saWdodDpmb2N1cywgYS5iZy1saWdodDpob3ZlciB7XG4gIGJhY2tncm91bmQtY29sb3I6ICNkYWUwZTUgIWltcG9ydGFudDsgfVxuXG4uYmctZGFyayB7XG4gIGJhY2tncm91bmQtY29sb3I6ICMzNDNhNDAgIWltcG9ydGFudDsgfVxuXG5hLmJnLWRhcms6Zm9jdXMsIGEuYmctZGFyazpob3ZlciB7XG4gIGJhY2tncm91bmQtY29sb3I6ICMxZDIxMjQgIWltcG9ydGFudDsgfVxuXG4uYmctd2hpdGUge1xuICBiYWNrZ3JvdW5kLWNvbG9yOiAjZmZmICFpbXBvcnRhbnQ7IH1cblxuLmJnLXRyYW5zcGFyZW50IHtcbiAgYmFja2dyb3VuZC1jb2xvcjogdHJhbnNwYXJlbnQgIWltcG9ydGFudDsgfVxuXG4uYm9yZGVyIHtcbiAgYm9yZGVyOiAxcHggc29saWQgI2U5ZWNlZiAhaW1wb3J0YW50OyB9XG5cbi5ib3JkZXItMCB7XG4gIGJvcmRlcjogMCAhaW1wb3J0YW50OyB9XG5cbi5ib3JkZXItdG9wLTAge1xuICBib3JkZXItdG9wOiAwICFpbXBvcnRhbnQ7IH1cblxuLmJvcmRlci1yaWdodC0wIHtcbiAgYm9yZGVyLXJpZ2h0OiAwICFpbXBvcnRhbnQ7IH1cblxuLmJvcmRlci1ib3R0b20tMCB7XG4gIGJvcmRlci1ib3R0b206IDAgIWltcG9ydGFudDsgfVxuXG4uYm9yZGVyLWxlZnQtMCB7XG4gIGJvcmRlci1sZWZ0OiAwICFpbXBvcnRhbnQ7IH1cblxuLmJvcmRlci1wcmltYXJ5IHtcbiAgYm9yZGVyLWNvbG9yOiAjMDA3YmZmICFpbXBvcnRhbnQ7IH1cblxuLmJvcmRlci1zZWNvbmRhcnkge1xuICBib3JkZXItY29sb3I6ICM4NjhlOTYgIWltcG9ydGFudDsgfVxuXG4uYm9yZGVyLXN1Y2Nlc3Mge1xuICBib3JkZXItY29sb3I6ICMyOGE3NDUgIWltcG9ydGFudDsgfVxuXG4uYm9yZGVyLWluZm8ge1xuICBib3JkZXItY29sb3I6ICMxN2EyYjggIWltcG9ydGFudDsgfVxuXG4uYm9yZGVyLXdhcm5pbmcge1xuICBib3JkZXItY29sb3I6ICNmZmMxMDcgIWltcG9ydGFudDsgfVxuXG4uYm9yZGVyLWRhbmdlciB7XG4gIGJvcmRlci1jb2xvcjogI2RjMzU0NSAhaW1wb3J0YW50OyB9XG5cbi5ib3JkZXItbGlnaHQge1xuICBib3JkZXItY29sb3I6ICNmOGY5ZmEgIWltcG9ydGFudDsgfVxuXG4uYm9yZGVyLWRhcmsge1xuICBib3JkZXItY29sb3I6ICMzNDNhNDAgIWltcG9ydGFudDsgfVxuXG4uYm9yZGVyLXdoaXRlIHtcbiAgYm9yZGVyLWNvbG9yOiAjZmZmICFpbXBvcnRhbnQ7IH1cblxuLnJvdW5kZWQge1xuICBib3JkZXItcmFkaXVzOiAwLjI1cmVtICFpbXBvcnRhbnQ7IH1cblxuLnJvdW5kZWQtdG9wIHtcbiAgYm9yZGVyLXRvcC1sZWZ0LXJhZGl1czogMC4yNXJlbSAhaW1wb3J0YW50O1xuICBib3JkZXItdG9wLXJpZ2h0LXJhZGl1czogMC4yNXJlbSAhaW1wb3J0YW50OyB9XG5cbi5yb3VuZGVkLXJpZ2h0IHtcbiAgYm9yZGVyLXRvcC1yaWdodC1yYWRpdXM6IDAuMjVyZW0gIWltcG9ydGFudDtcbiAgYm9yZGVyLWJvdHRvbS1yaWdodC1yYWRpdXM6IDAuMjVyZW0gIWltcG9ydGFudDsgfVxuXG4ucm91bmRlZC1ib3R0b20ge1xuICBib3JkZXItYm90dG9tLXJpZ2h0LXJhZGl1czogMC4yNXJlbSAhaW1wb3J0YW50O1xuICBib3JkZXItYm90dG9tLWxlZnQtcmFkaXVzOiAwLjI1cmVtICFpbXBvcnRhbnQ7IH1cblxuLnJvdW5kZWQtbGVmdCB7XG4gIGJvcmRlci10b3AtbGVmdC1yYWRpdXM6IDAuMjVyZW0gIWltcG9ydGFudDtcbiAgYm9yZGVyLWJvdHRvbS1sZWZ0LXJhZGl1czogMC4yNXJlbSAhaW1wb3J0YW50OyB9XG5cbi5yb3VuZGVkLWNpcmNsZSB7XG4gIGJvcmRlci1yYWRpdXM6IDUwJTsgfVxuXG4ucm91bmRlZC0wIHtcbiAgYm9yZGVyLXJhZGl1czogMDsgfVxuXG4uY2xlYXJmaXg6OmFmdGVyIHtcbiAgZGlzcGxheTogYmxvY2s7XG4gIGNsZWFyOiBib3RoO1xuICBjb250ZW50OiBcIlwiOyB9XG5cbi5kLW5vbmUge1xuICBkaXNwbGF5OiBub25lICFpbXBvcnRhbnQ7IH1cblxuLmQtaW5saW5lIHtcbiAgZGlzcGxheTogaW5saW5lICFpbXBvcnRhbnQ7IH1cblxuLmQtaW5saW5lLWJsb2NrIHtcbiAgZGlzcGxheTogaW5saW5lLWJsb2NrICFpbXBvcnRhbnQ7IH1cblxuLmQtYmxvY2sge1xuICBkaXNwbGF5OiBibG9jayAhaW1wb3J0YW50OyB9XG5cbi5kLXRhYmxlIHtcbiAgZGlzcGxheTogdGFibGUgIWltcG9ydGFudDsgfVxuXG4uZC10YWJsZS1jZWxsIHtcbiAgZGlzcGxheTogdGFibGUtY2VsbCAhaW1wb3J0YW50OyB9XG5cbi5kLWZsZXgsIGJ1dHRvbi5jdXN0b20sICNmcmFtZSwgYXNpZGUubGVmdCwgYXNpZGUubGVmdCBuYXYgPiBkaXYuaXRlbSwgI2Jlc2lkZSwgaGVhZGVyLm1haW4sICN1c2VyLWFjY291bnQge1xuICBkaXNwbGF5OiBmbGV4ICFpbXBvcnRhbnQ7IH1cblxuLmQtaW5saW5lLWZsZXgge1xuICBkaXNwbGF5OiBpbmxpbmUtZmxleCAhaW1wb3J0YW50OyB9XG5cbkBtZWRpYSAobWluLXdpZHRoOiA1NzZweCkge1xuICAuZC1zbS1ub25lIHtcbiAgICBkaXNwbGF5OiBub25lICFpbXBvcnRhbnQ7IH1cbiAgLmQtc20taW5saW5lIHtcbiAgICBkaXNwbGF5OiBpbmxpbmUgIWltcG9ydGFudDsgfVxuICAuZC1zbS1pbmxpbmUtYmxvY2sge1xuICAgIGRpc3BsYXk6IGlubGluZS1ibG9jayAhaW1wb3J0YW50OyB9XG4gIC5kLXNtLWJsb2NrIHtcbiAgICBkaXNwbGF5OiBibG9jayAhaW1wb3J0YW50OyB9XG4gIC5kLXNtLXRhYmxlIHtcbiAgICBkaXNwbGF5OiB0YWJsZSAhaW1wb3J0YW50OyB9XG4gIC5kLXNtLXRhYmxlLWNlbGwge1xuICAgIGRpc3BsYXk6IHRhYmxlLWNlbGwgIWltcG9ydGFudDsgfVxuICAuZC1zbS1mbGV4IHtcbiAgICBkaXNwbGF5OiBmbGV4ICFpbXBvcnRhbnQ7IH1cbiAgLmQtc20taW5saW5lLWZsZXgge1xuICAgIGRpc3BsYXk6IGlubGluZS1mbGV4ICFpbXBvcnRhbnQ7IH0gfVxuXG5AbWVkaWEgKG1pbi13aWR0aDogNzY4cHgpIHtcbiAgLmQtbWQtbm9uZSB7XG4gICAgZGlzcGxheTogbm9uZSAhaW1wb3J0YW50OyB9XG4gIC5kLW1kLWlubGluZSB7XG4gICAgZGlzcGxheTogaW5saW5lICFpbXBvcnRhbnQ7IH1cbiAgLmQtbWQtaW5saW5lLWJsb2NrIHtcbiAgICBkaXNwbGF5OiBpbmxpbmUtYmxvY2sgIWltcG9ydGFudDsgfVxuICAuZC1tZC1ibG9jayB7XG4gICAgZGlzcGxheTogYmxvY2sgIWltcG9ydGFudDsgfVxuICAuZC1tZC10YWJsZSB7XG4gICAgZGlzcGxheTogdGFibGUgIWltcG9ydGFudDsgfVxuICAuZC1tZC10YWJsZS1jZWxsIHtcbiAgICBkaXNwbGF5OiB0YWJsZS1jZWxsICFpbXBvcnRhbnQ7IH1cbiAgLmQtbWQtZmxleCB7XG4gICAgZGlzcGxheTogZmxleCAhaW1wb3J0YW50OyB9XG4gIC5kLW1kLWlubGluZS1mbGV4IHtcbiAgICBkaXNwbGF5OiBpbmxpbmUtZmxleCAhaW1wb3J0YW50OyB9IH1cblxuQG1lZGlhIChtaW4td2lkdGg6IDk5MnB4KSB7XG4gIC5kLWxnLW5vbmUge1xuICAgIGRpc3BsYXk6IG5vbmUgIWltcG9ydGFudDsgfVxuICAuZC1sZy1pbmxpbmUge1xuICAgIGRpc3BsYXk6IGlubGluZSAhaW1wb3J0YW50OyB9XG4gIC5kLWxnLWlubGluZS1ibG9jayB7XG4gICAgZGlzcGxheTogaW5saW5lLWJsb2NrICFpbXBvcnRhbnQ7IH1cbiAgLmQtbGctYmxvY2sge1xuICAgIGRpc3BsYXk6IGJsb2NrICFpbXBvcnRhbnQ7IH1cbiAgLmQtbGctdGFibGUge1xuICAgIGRpc3BsYXk6IHRhYmxlICFpbXBvcnRhbnQ7IH1cbiAgLmQtbGctdGFibGUtY2VsbCB7XG4gICAgZGlzcGxheTogdGFibGUtY2VsbCAhaW1wb3J0YW50OyB9XG4gIC5kLWxnLWZsZXgge1xuICAgIGRpc3BsYXk6IGZsZXggIWltcG9ydGFudDsgfVxuICAuZC1sZy1pbmxpbmUtZmxleCB7XG4gICAgZGlzcGxheTogaW5saW5lLWZsZXggIWltcG9ydGFudDsgfSB9XG5cbkBtZWRpYSAobWluLXdpZHRoOiAxMjAwcHgpIHtcbiAgLmQteGwtbm9uZSB7XG4gICAgZGlzcGxheTogbm9uZSAhaW1wb3J0YW50OyB9XG4gIC5kLXhsLWlubGluZSB7XG4gICAgZGlzcGxheTogaW5saW5lICFpbXBvcnRhbnQ7IH1cbiAgLmQteGwtaW5saW5lLWJsb2NrIHtcbiAgICBkaXNwbGF5OiBpbmxpbmUtYmxvY2sgIWltcG9ydGFudDsgfVxuICAuZC14bC1ibG9jayB7XG4gICAgZGlzcGxheTogYmxvY2sgIWltcG9ydGFudDsgfVxuICAuZC14bC10YWJsZSB7XG4gICAgZGlzcGxheTogdGFibGUgIWltcG9ydGFudDsgfVxuICAuZC14bC10YWJsZS1jZWxsIHtcbiAgICBkaXNwbGF5OiB0YWJsZS1jZWxsICFpbXBvcnRhbnQ7IH1cbiAgLmQteGwtZmxleCB7XG4gICAgZGlzcGxheTogZmxleCAhaW1wb3J0YW50OyB9XG4gIC5kLXhsLWlubGluZS1mbGV4IHtcbiAgICBkaXNwbGF5OiBpbmxpbmUtZmxleCAhaW1wb3J0YW50OyB9IH1cblxuLmQtcHJpbnQtYmxvY2sge1xuICBkaXNwbGF5OiBub25lICFpbXBvcnRhbnQ7IH1cbiAgQG1lZGlhIHByaW50IHtcbiAgICAuZC1wcmludC1ibG9jayB7XG4gICAgICBkaXNwbGF5OiBibG9jayAhaW1wb3J0YW50OyB9IH1cblxuLmQtcHJpbnQtaW5saW5lIHtcbiAgZGlzcGxheTogbm9uZSAhaW1wb3J0YW50OyB9XG4gIEBtZWRpYSBwcmludCB7XG4gICAgLmQtcHJpbnQtaW5saW5lIHtcbiAgICAgIGRpc3BsYXk6IGlubGluZSAhaW1wb3J0YW50OyB9IH1cblxuLmQtcHJpbnQtaW5saW5lLWJsb2NrIHtcbiAgZGlzcGxheTogbm9uZSAhaW1wb3J0YW50OyB9XG4gIEBtZWRpYSBwcmludCB7XG4gICAgLmQtcHJpbnQtaW5saW5lLWJsb2NrIHtcbiAgICAgIGRpc3BsYXk6IGlubGluZS1ibG9jayAhaW1wb3J0YW50OyB9IH1cblxuQG1lZGlhIHByaW50IHtcbiAgLmQtcHJpbnQtbm9uZSB7XG4gICAgZGlzcGxheTogbm9uZSAhaW1wb3J0YW50OyB9IH1cblxuLmVtYmVkLXJlc3BvbnNpdmUge1xuICBwb3NpdGlvbjogcmVsYXRpdmU7XG4gIGRpc3BsYXk6IGJsb2NrO1xuICB3aWR0aDogMTAwJTtcbiAgcGFkZGluZzogMDtcbiAgb3ZlcmZsb3c6IGhpZGRlbjsgfVxuICAuZW1iZWQtcmVzcG9uc2l2ZTo6YmVmb3JlIHtcbiAgICBkaXNwbGF5OiBibG9jaztcbiAgICBjb250ZW50OiBcIlwiOyB9XG4gIC5lbWJlZC1yZXNwb25zaXZlIC5lbWJlZC1yZXNwb25zaXZlLWl0ZW0sXG4gIC5lbWJlZC1yZXNwb25zaXZlIGlmcmFtZSxcbiAgLmVtYmVkLXJlc3BvbnNpdmUgZW1iZWQsXG4gIC5lbWJlZC1yZXNwb25zaXZlIG9iamVjdCxcbiAgLmVtYmVkLXJlc3BvbnNpdmUgdmlkZW8ge1xuICAgIHBvc2l0aW9uOiBhYnNvbHV0ZTtcbiAgICB0b3A6IDA7XG4gICAgYm90dG9tOiAwO1xuICAgIGxlZnQ6IDA7XG4gICAgd2lkdGg6IDEwMCU7XG4gICAgaGVpZ2h0OiAxMDAlO1xuICAgIGJvcmRlcjogMDsgfVxuXG4uZW1iZWQtcmVzcG9uc2l2ZS0yMWJ5OTo6YmVmb3JlIHtcbiAgcGFkZGluZy10b3A6IDQyLjg1NzE0JTsgfVxuXG4uZW1iZWQtcmVzcG9uc2l2ZS0xNmJ5OTo6YmVmb3JlIHtcbiAgcGFkZGluZy10b3A6IDU2LjI1JTsgfVxuXG4uZW1iZWQtcmVzcG9uc2l2ZS00YnkzOjpiZWZvcmUge1xuICBwYWRkaW5nLXRvcDogNzUlOyB9XG5cbi5lbWJlZC1yZXNwb25zaXZlLTFieTE6OmJlZm9yZSB7XG4gIHBhZGRpbmctdG9wOiAxMDAlOyB9XG5cbi5mbGV4LXJvdywgYnV0dG9uLmN1c3RvbSwgI2ZyYW1lLCBoZWFkZXIubWFpbiwgI3VzZXItYWNjb3VudCB7XG4gIGZsZXgtZGlyZWN0aW9uOiByb3cgIWltcG9ydGFudDsgfVxuXG4uZmxleC1jb2x1bW4sIGFzaWRlLmxlZnQsICNiZXNpZGUge1xuICBmbGV4LWRpcmVjdGlvbjogY29sdW1uICFpbXBvcnRhbnQ7IH1cblxuLmZsZXgtcm93LXJldmVyc2Uge1xuICBmbGV4LWRpcmVjdGlvbjogcm93LXJldmVyc2UgIWltcG9ydGFudDsgfVxuXG4uZmxleC1jb2x1bW4tcmV2ZXJzZSB7XG4gIGZsZXgtZGlyZWN0aW9uOiBjb2x1bW4tcmV2ZXJzZSAhaW1wb3J0YW50OyB9XG5cbi5mbGV4LXdyYXAge1xuICBmbGV4LXdyYXA6IHdyYXAgIWltcG9ydGFudDsgfVxuXG4uZmxleC1ub3dyYXAge1xuICBmbGV4LXdyYXA6IG5vd3JhcCAhaW1wb3J0YW50OyB9XG5cbi5mbGV4LXdyYXAtcmV2ZXJzZSB7XG4gIGZsZXgtd3JhcDogd3JhcC1yZXZlcnNlICFpbXBvcnRhbnQ7IH1cblxuLmp1c3RpZnktY29udGVudC1zdGFydCB7XG4gIGp1c3RpZnktY29udGVudDogZmxleC1zdGFydCAhaW1wb3J0YW50OyB9XG5cbi5qdXN0aWZ5LWNvbnRlbnQtZW5kIHtcbiAganVzdGlmeS1jb250ZW50OiBmbGV4LWVuZCAhaW1wb3J0YW50OyB9XG5cbi5qdXN0aWZ5LWNvbnRlbnQtY2VudGVyLCBhc2lkZS5sZWZ0IG5hdiA+IGRpdi5pdGVtIHtcbiAganVzdGlmeS1jb250ZW50OiBjZW50ZXIgIWltcG9ydGFudDsgfVxuXG4uanVzdGlmeS1jb250ZW50LWJldHdlZW4ge1xuICBqdXN0aWZ5LWNvbnRlbnQ6IHNwYWNlLWJldHdlZW4gIWltcG9ydGFudDsgfVxuXG4uanVzdGlmeS1jb250ZW50LWFyb3VuZCwgI3VzZXItYWNjb3VudCB7XG4gIGp1c3RpZnktY29udGVudDogc3BhY2UtYXJvdW5kICFpbXBvcnRhbnQ7IH1cblxuLmFsaWduLWl0ZW1zLXN0YXJ0IHtcbiAgYWxpZ24taXRlbXM6IGZsZXgtc3RhcnQgIWltcG9ydGFudDsgfVxuXG4uYWxpZ24taXRlbXMtZW5kIHtcbiAgYWxpZ24taXRlbXM6IGZsZXgtZW5kICFpbXBvcnRhbnQ7IH1cblxuLmFsaWduLWl0ZW1zLWNlbnRlciwgYXNpZGUubGVmdCwgYXNpZGUubGVmdCBuYXYgPiBkaXYuaXRlbSwgaGVhZGVyLm1haW4sICN1c2VyLWFjY291bnQge1xuICBhbGlnbi1pdGVtczogY2VudGVyICFpbXBvcnRhbnQ7IH1cblxuLmFsaWduLWl0ZW1zLWJhc2VsaW5lIHtcbiAgYWxpZ24taXRlbXM6IGJhc2VsaW5lICFpbXBvcnRhbnQ7IH1cblxuLmFsaWduLWl0ZW1zLXN0cmV0Y2gsICNmcmFtZSB7XG4gIGFsaWduLWl0ZW1zOiBzdHJldGNoICFpbXBvcnRhbnQ7IH1cblxuLmFsaWduLWNvbnRlbnQtc3RhcnQge1xuICBhbGlnbi1jb250ZW50OiBmbGV4LXN0YXJ0ICFpbXBvcnRhbnQ7IH1cblxuLmFsaWduLWNvbnRlbnQtZW5kIHtcbiAgYWxpZ24tY29udGVudDogZmxleC1lbmQgIWltcG9ydGFudDsgfVxuXG4uYWxpZ24tY29udGVudC1jZW50ZXIge1xuICBhbGlnbi1jb250ZW50OiBjZW50ZXIgIWltcG9ydGFudDsgfVxuXG4uYWxpZ24tY29udGVudC1iZXR3ZWVuIHtcbiAgYWxpZ24tY29udGVudDogc3BhY2UtYmV0d2VlbiAhaW1wb3J0YW50OyB9XG5cbi5hbGlnbi1jb250ZW50LWFyb3VuZCB7XG4gIGFsaWduLWNvbnRlbnQ6IHNwYWNlLWFyb3VuZCAhaW1wb3J0YW50OyB9XG5cbi5hbGlnbi1jb250ZW50LXN0cmV0Y2gge1xuICBhbGlnbi1jb250ZW50OiBzdHJldGNoICFpbXBvcnRhbnQ7IH1cblxuLmFsaWduLXNlbGYtYXV0byB7XG4gIGFsaWduLXNlbGY6IGF1dG8gIWltcG9ydGFudDsgfVxuXG4uYWxpZ24tc2VsZi1zdGFydCB7XG4gIGFsaWduLXNlbGY6IGZsZXgtc3RhcnQgIWltcG9ydGFudDsgfVxuXG4uYWxpZ24tc2VsZi1lbmQge1xuICBhbGlnbi1zZWxmOiBmbGV4LWVuZCAhaW1wb3J0YW50OyB9XG5cbi5hbGlnbi1zZWxmLWNlbnRlciB7XG4gIGFsaWduLXNlbGY6IGNlbnRlciAhaW1wb3J0YW50OyB9XG5cbi5hbGlnbi1zZWxmLWJhc2VsaW5lIHtcbiAgYWxpZ24tc2VsZjogYmFzZWxpbmUgIWltcG9ydGFudDsgfVxuXG4uYWxpZ24tc2VsZi1zdHJldGNoIHtcbiAgYWxpZ24tc2VsZjogc3RyZXRjaCAhaW1wb3J0YW50OyB9XG5cbkBtZWRpYSAobWluLXdpZHRoOiA1NzZweCkge1xuICAuZmxleC1zbS1yb3cge1xuICAgIGZsZXgtZGlyZWN0aW9uOiByb3cgIWltcG9ydGFudDsgfVxuICAuZmxleC1zbS1jb2x1bW4ge1xuICAgIGZsZXgtZGlyZWN0aW9uOiBjb2x1bW4gIWltcG9ydGFudDsgfVxuICAuZmxleC1zbS1yb3ctcmV2ZXJzZSB7XG4gICAgZmxleC1kaXJlY3Rpb246IHJvdy1yZXZlcnNlICFpbXBvcnRhbnQ7IH1cbiAgLmZsZXgtc20tY29sdW1uLXJldmVyc2Uge1xuICAgIGZsZXgtZGlyZWN0aW9uOiBjb2x1bW4tcmV2ZXJzZSAhaW1wb3J0YW50OyB9XG4gIC5mbGV4LXNtLXdyYXAge1xuICAgIGZsZXgtd3JhcDogd3JhcCAhaW1wb3J0YW50OyB9XG4gIC5mbGV4LXNtLW5vd3JhcCB7XG4gICAgZmxleC13cmFwOiBub3dyYXAgIWltcG9ydGFudDsgfVxuICAuZmxleC1zbS13cmFwLXJldmVyc2Uge1xuICAgIGZsZXgtd3JhcDogd3JhcC1yZXZlcnNlICFpbXBvcnRhbnQ7IH1cbiAgLmp1c3RpZnktY29udGVudC1zbS1zdGFydCB7XG4gICAganVzdGlmeS1jb250ZW50OiBmbGV4LXN0YXJ0ICFpbXBvcnRhbnQ7IH1cbiAgLmp1c3RpZnktY29udGVudC1zbS1lbmQge1xuICAgIGp1c3RpZnktY29udGVudDogZmxleC1lbmQgIWltcG9ydGFudDsgfVxuICAuanVzdGlmeS1jb250ZW50LXNtLWNlbnRlciB7XG4gICAganVzdGlmeS1jb250ZW50OiBjZW50ZXIgIWltcG9ydGFudDsgfVxuICAuanVzdGlmeS1jb250ZW50LXNtLWJldHdlZW4ge1xuICAgIGp1c3RpZnktY29udGVudDogc3BhY2UtYmV0d2VlbiAhaW1wb3J0YW50OyB9XG4gIC5qdXN0aWZ5LWNvbnRlbnQtc20tYXJvdW5kIHtcbiAgICBqdXN0aWZ5LWNvbnRlbnQ6IHNwYWNlLWFyb3VuZCAhaW1wb3J0YW50OyB9XG4gIC5hbGlnbi1pdGVtcy1zbS1zdGFydCB7XG4gICAgYWxpZ24taXRlbXM6IGZsZXgtc3RhcnQgIWltcG9ydGFudDsgfVxuICAuYWxpZ24taXRlbXMtc20tZW5kIHtcbiAgICBhbGlnbi1pdGVtczogZmxleC1lbmQgIWltcG9ydGFudDsgfVxuICAuYWxpZ24taXRlbXMtc20tY2VudGVyIHtcbiAgICBhbGlnbi1pdGVtczogY2VudGVyICFpbXBvcnRhbnQ7IH1cbiAgLmFsaWduLWl0ZW1zLXNtLWJhc2VsaW5lIHtcbiAgICBhbGlnbi1pdGVtczogYmFzZWxpbmUgIWltcG9ydGFudDsgfVxuICAuYWxpZ24taXRlbXMtc20tc3RyZXRjaCB7XG4gICAgYWxpZ24taXRlbXM6IHN0cmV0Y2ggIWltcG9ydGFudDsgfVxuICAuYWxpZ24tY29udGVudC1zbS1zdGFydCB7XG4gICAgYWxpZ24tY29udGVudDogZmxleC1zdGFydCAhaW1wb3J0YW50OyB9XG4gIC5hbGlnbi1jb250ZW50LXNtLWVuZCB7XG4gICAgYWxpZ24tY29udGVudDogZmxleC1lbmQgIWltcG9ydGFudDsgfVxuICAuYWxpZ24tY29udGVudC1zbS1jZW50ZXIge1xuICAgIGFsaWduLWNvbnRlbnQ6IGNlbnRlciAhaW1wb3J0YW50OyB9XG4gIC5hbGlnbi1jb250ZW50LXNtLWJldHdlZW4ge1xuICAgIGFsaWduLWNvbnRlbnQ6IHNwYWNlLWJldHdlZW4gIWltcG9ydGFudDsgfVxuICAuYWxpZ24tY29udGVudC1zbS1hcm91bmQge1xuICAgIGFsaWduLWNvbnRlbnQ6IHNwYWNlLWFyb3VuZCAhaW1wb3J0YW50OyB9XG4gIC5hbGlnbi1jb250ZW50LXNtLXN0cmV0Y2gge1xuICAgIGFsaWduLWNvbnRlbnQ6IHN0cmV0Y2ggIWltcG9ydGFudDsgfVxuICAuYWxpZ24tc2VsZi1zbS1hdXRvIHtcbiAgICBhbGlnbi1zZWxmOiBhdXRvICFpbXBvcnRhbnQ7IH1cbiAgLmFsaWduLXNlbGYtc20tc3RhcnQge1xuICAgIGFsaWduLXNlbGY6IGZsZXgtc3RhcnQgIWltcG9ydGFudDsgfVxuICAuYWxpZ24tc2VsZi1zbS1lbmQge1xuICAgIGFsaWduLXNlbGY6IGZsZXgtZW5kICFpbXBvcnRhbnQ7IH1cbiAgLmFsaWduLXNlbGYtc20tY2VudGVyIHtcbiAgICBhbGlnbi1zZWxmOiBjZW50ZXIgIWltcG9ydGFudDsgfVxuICAuYWxpZ24tc2VsZi1zbS1iYXNlbGluZSB7XG4gICAgYWxpZ24tc2VsZjogYmFzZWxpbmUgIWltcG9ydGFudDsgfVxuICAuYWxpZ24tc2VsZi1zbS1zdHJldGNoIHtcbiAgICBhbGlnbi1zZWxmOiBzdHJldGNoICFpbXBvcnRhbnQ7IH0gfVxuXG5AbWVkaWEgKG1pbi13aWR0aDogNzY4cHgpIHtcbiAgLmZsZXgtbWQtcm93IHtcbiAgICBmbGV4LWRpcmVjdGlvbjogcm93ICFpbXBvcnRhbnQ7IH1cbiAgLmZsZXgtbWQtY29sdW1uIHtcbiAgICBmbGV4LWRpcmVjdGlvbjogY29sdW1uICFpbXBvcnRhbnQ7IH1cbiAgLmZsZXgtbWQtcm93LXJldmVyc2Uge1xuICAgIGZsZXgtZGlyZWN0aW9uOiByb3ctcmV2ZXJzZSAhaW1wb3J0YW50OyB9XG4gIC5mbGV4LW1kLWNvbHVtbi1yZXZlcnNlIHtcbiAgICBmbGV4LWRpcmVjdGlvbjogY29sdW1uLXJldmVyc2UgIWltcG9ydGFudDsgfVxuICAuZmxleC1tZC13cmFwIHtcbiAgICBmbGV4LXdyYXA6IHdyYXAgIWltcG9ydGFudDsgfVxuICAuZmxleC1tZC1ub3dyYXAge1xuICAgIGZsZXgtd3JhcDogbm93cmFwICFpbXBvcnRhbnQ7IH1cbiAgLmZsZXgtbWQtd3JhcC1yZXZlcnNlIHtcbiAgICBmbGV4LXdyYXA6IHdyYXAtcmV2ZXJzZSAhaW1wb3J0YW50OyB9XG4gIC5qdXN0aWZ5LWNvbnRlbnQtbWQtc3RhcnQge1xuICAgIGp1c3RpZnktY29udGVudDogZmxleC1zdGFydCAhaW1wb3J0YW50OyB9XG4gIC5qdXN0aWZ5LWNvbnRlbnQtbWQtZW5kIHtcbiAgICBqdXN0aWZ5LWNvbnRlbnQ6IGZsZXgtZW5kICFpbXBvcnRhbnQ7IH1cbiAgLmp1c3RpZnktY29udGVudC1tZC1jZW50ZXIge1xuICAgIGp1c3RpZnktY29udGVudDogY2VudGVyICFpbXBvcnRhbnQ7IH1cbiAgLmp1c3RpZnktY29udGVudC1tZC1iZXR3ZWVuIHtcbiAgICBqdXN0aWZ5LWNvbnRlbnQ6IHNwYWNlLWJldHdlZW4gIWltcG9ydGFudDsgfVxuICAuanVzdGlmeS1jb250ZW50LW1kLWFyb3VuZCB7XG4gICAganVzdGlmeS1jb250ZW50OiBzcGFjZS1hcm91bmQgIWltcG9ydGFudDsgfVxuICAuYWxpZ24taXRlbXMtbWQtc3RhcnQge1xuICAgIGFsaWduLWl0ZW1zOiBmbGV4LXN0YXJ0ICFpbXBvcnRhbnQ7IH1cbiAgLmFsaWduLWl0ZW1zLW1kLWVuZCB7XG4gICAgYWxpZ24taXRlbXM6IGZsZXgtZW5kICFpbXBvcnRhbnQ7IH1cbiAgLmFsaWduLWl0ZW1zLW1kLWNlbnRlciB7XG4gICAgYWxpZ24taXRlbXM6IGNlbnRlciAhaW1wb3J0YW50OyB9XG4gIC5hbGlnbi1pdGVtcy1tZC1iYXNlbGluZSB7XG4gICAgYWxpZ24taXRlbXM6IGJhc2VsaW5lICFpbXBvcnRhbnQ7IH1cbiAgLmFsaWduLWl0ZW1zLW1kLXN0cmV0Y2gge1xuICAgIGFsaWduLWl0ZW1zOiBzdHJldGNoICFpbXBvcnRhbnQ7IH1cbiAgLmFsaWduLWNvbnRlbnQtbWQtc3RhcnQge1xuICAgIGFsaWduLWNvbnRlbnQ6IGZsZXgtc3RhcnQgIWltcG9ydGFudDsgfVxuICAuYWxpZ24tY29udGVudC1tZC1lbmQge1xuICAgIGFsaWduLWNvbnRlbnQ6IGZsZXgtZW5kICFpbXBvcnRhbnQ7IH1cbiAgLmFsaWduLWNvbnRlbnQtbWQtY2VudGVyIHtcbiAgICBhbGlnbi1jb250ZW50OiBjZW50ZXIgIWltcG9ydGFudDsgfVxuICAuYWxpZ24tY29udGVudC1tZC1iZXR3ZWVuIHtcbiAgICBhbGlnbi1jb250ZW50OiBzcGFjZS1iZXR3ZWVuICFpbXBvcnRhbnQ7IH1cbiAgLmFsaWduLWNvbnRlbnQtbWQtYXJvdW5kIHtcbiAgICBhbGlnbi1jb250ZW50OiBzcGFjZS1hcm91bmQgIWltcG9ydGFudDsgfVxuICAuYWxpZ24tY29udGVudC1tZC1zdHJldGNoIHtcbiAgICBhbGlnbi1jb250ZW50OiBzdHJldGNoICFpbXBvcnRhbnQ7IH1cbiAgLmFsaWduLXNlbGYtbWQtYXV0byB7XG4gICAgYWxpZ24tc2VsZjogYXV0byAhaW1wb3J0YW50OyB9XG4gIC5hbGlnbi1zZWxmLW1kLXN0YXJ0IHtcbiAgICBhbGlnbi1zZWxmOiBmbGV4LXN0YXJ0ICFpbXBvcnRhbnQ7IH1cbiAgLmFsaWduLXNlbGYtbWQtZW5kIHtcbiAgICBhbGlnbi1zZWxmOiBmbGV4LWVuZCAhaW1wb3J0YW50OyB9XG4gIC5hbGlnbi1zZWxmLW1kLWNlbnRlciB7XG4gICAgYWxpZ24tc2VsZjogY2VudGVyICFpbXBvcnRhbnQ7IH1cbiAgLmFsaWduLXNlbGYtbWQtYmFzZWxpbmUge1xuICAgIGFsaWduLXNlbGY6IGJhc2VsaW5lICFpbXBvcnRhbnQ7IH1cbiAgLmFsaWduLXNlbGYtbWQtc3RyZXRjaCB7XG4gICAgYWxpZ24tc2VsZjogc3RyZXRjaCAhaW1wb3J0YW50OyB9IH1cblxuQG1lZGlhIChtaW4td2lkdGg6IDk5MnB4KSB7XG4gIC5mbGV4LWxnLXJvdyB7XG4gICAgZmxleC1kaXJlY3Rpb246IHJvdyAhaW1wb3J0YW50OyB9XG4gIC5mbGV4LWxnLWNvbHVtbiB7XG4gICAgZmxleC1kaXJlY3Rpb246IGNvbHVtbiAhaW1wb3J0YW50OyB9XG4gIC5mbGV4LWxnLXJvdy1yZXZlcnNlIHtcbiAgICBmbGV4LWRpcmVjdGlvbjogcm93LXJldmVyc2UgIWltcG9ydGFudDsgfVxuICAuZmxleC1sZy1jb2x1bW4tcmV2ZXJzZSB7XG4gICAgZmxleC1kaXJlY3Rpb246IGNvbHVtbi1yZXZlcnNlICFpbXBvcnRhbnQ7IH1cbiAgLmZsZXgtbGctd3JhcCB7XG4gICAgZmxleC13cmFwOiB3cmFwICFpbXBvcnRhbnQ7IH1cbiAgLmZsZXgtbGctbm93cmFwIHtcbiAgICBmbGV4LXdyYXA6IG5vd3JhcCAhaW1wb3J0YW50OyB9XG4gIC5mbGV4LWxnLXdyYXAtcmV2ZXJzZSB7XG4gICAgZmxleC13cmFwOiB3cmFwLXJldmVyc2UgIWltcG9ydGFudDsgfVxuICAuanVzdGlmeS1jb250ZW50LWxnLXN0YXJ0IHtcbiAgICBqdXN0aWZ5LWNvbnRlbnQ6IGZsZXgtc3RhcnQgIWltcG9ydGFudDsgfVxuICAuanVzdGlmeS1jb250ZW50LWxnLWVuZCB7XG4gICAganVzdGlmeS1jb250ZW50OiBmbGV4LWVuZCAhaW1wb3J0YW50OyB9XG4gIC5qdXN0aWZ5LWNvbnRlbnQtbGctY2VudGVyIHtcbiAgICBqdXN0aWZ5LWNvbnRlbnQ6IGNlbnRlciAhaW1wb3J0YW50OyB9XG4gIC5qdXN0aWZ5LWNvbnRlbnQtbGctYmV0d2VlbiB7XG4gICAganVzdGlmeS1jb250ZW50OiBzcGFjZS1iZXR3ZWVuICFpbXBvcnRhbnQ7IH1cbiAgLmp1c3RpZnktY29udGVudC1sZy1hcm91bmQge1xuICAgIGp1c3RpZnktY29udGVudDogc3BhY2UtYXJvdW5kICFpbXBvcnRhbnQ7IH1cbiAgLmFsaWduLWl0ZW1zLWxnLXN0YXJ0IHtcbiAgICBhbGlnbi1pdGVtczogZmxleC1zdGFydCAhaW1wb3J0YW50OyB9XG4gIC5hbGlnbi1pdGVtcy1sZy1lbmQge1xuICAgIGFsaWduLWl0ZW1zOiBmbGV4LWVuZCAhaW1wb3J0YW50OyB9XG4gIC5hbGlnbi1pdGVtcy1sZy1jZW50ZXIge1xuICAgIGFsaWduLWl0ZW1zOiBjZW50ZXIgIWltcG9ydGFudDsgfVxuICAuYWxpZ24taXRlbXMtbGctYmFzZWxpbmUge1xuICAgIGFsaWduLWl0ZW1zOiBiYXNlbGluZSAhaW1wb3J0YW50OyB9XG4gIC5hbGlnbi1pdGVtcy1sZy1zdHJldGNoIHtcbiAgICBhbGlnbi1pdGVtczogc3RyZXRjaCAhaW1wb3J0YW50OyB9XG4gIC5hbGlnbi1jb250ZW50LWxnLXN0YXJ0IHtcbiAgICBhbGlnbi1jb250ZW50OiBmbGV4LXN0YXJ0ICFpbXBvcnRhbnQ7IH1cbiAgLmFsaWduLWNvbnRlbnQtbGctZW5kIHtcbiAgICBhbGlnbi1jb250ZW50OiBmbGV4LWVuZCAhaW1wb3J0YW50OyB9XG4gIC5hbGlnbi1jb250ZW50LWxnLWNlbnRlciB7XG4gICAgYWxpZ24tY29udGVudDogY2VudGVyICFpbXBvcnRhbnQ7IH1cbiAgLmFsaWduLWNvbnRlbnQtbGctYmV0d2VlbiB7XG4gICAgYWxpZ24tY29udGVudDogc3BhY2UtYmV0d2VlbiAhaW1wb3J0YW50OyB9XG4gIC5hbGlnbi1jb250ZW50LWxnLWFyb3VuZCB7XG4gICAgYWxpZ24tY29udGVudDogc3BhY2UtYXJvdW5kICFpbXBvcnRhbnQ7IH1cbiAgLmFsaWduLWNvbnRlbnQtbGctc3RyZXRjaCB7XG4gICAgYWxpZ24tY29udGVudDogc3RyZXRjaCAhaW1wb3J0YW50OyB9XG4gIC5hbGlnbi1zZWxmLWxnLWF1dG8ge1xuICAgIGFsaWduLXNlbGY6IGF1dG8gIWltcG9ydGFudDsgfVxuICAuYWxpZ24tc2VsZi1sZy1zdGFydCB7XG4gICAgYWxpZ24tc2VsZjogZmxleC1zdGFydCAhaW1wb3J0YW50OyB9XG4gIC5hbGlnbi1zZWxmLWxnLWVuZCB7XG4gICAgYWxpZ24tc2VsZjogZmxleC1lbmQgIWltcG9ydGFudDsgfVxuICAuYWxpZ24tc2VsZi1sZy1jZW50ZXIge1xuICAgIGFsaWduLXNlbGY6IGNlbnRlciAhaW1wb3J0YW50OyB9XG4gIC5hbGlnbi1zZWxmLWxnLWJhc2VsaW5lIHtcbiAgICBhbGlnbi1zZWxmOiBiYXNlbGluZSAhaW1wb3J0YW50OyB9XG4gIC5hbGlnbi1zZWxmLWxnLXN0cmV0Y2gge1xuICAgIGFsaWduLXNlbGY6IHN0cmV0Y2ggIWltcG9ydGFudDsgfSB9XG5cbkBtZWRpYSAobWluLXdpZHRoOiAxMjAwcHgpIHtcbiAgLmZsZXgteGwtcm93IHtcbiAgICBmbGV4LWRpcmVjdGlvbjogcm93ICFpbXBvcnRhbnQ7IH1cbiAgLmZsZXgteGwtY29sdW1uIHtcbiAgICBmbGV4LWRpcmVjdGlvbjogY29sdW1uICFpbXBvcnRhbnQ7IH1cbiAgLmZsZXgteGwtcm93LXJldmVyc2Uge1xuICAgIGZsZXgtZGlyZWN0aW9uOiByb3ctcmV2ZXJzZSAhaW1wb3J0YW50OyB9XG4gIC5mbGV4LXhsLWNvbHVtbi1yZXZlcnNlIHtcbiAgICBmbGV4LWRpcmVjdGlvbjogY29sdW1uLXJldmVyc2UgIWltcG9ydGFudDsgfVxuICAuZmxleC14bC13cmFwIHtcbiAgICBmbGV4LXdyYXA6IHdyYXAgIWltcG9ydGFudDsgfVxuICAuZmxleC14bC1ub3dyYXAge1xuICAgIGZsZXgtd3JhcDogbm93cmFwICFpbXBvcnRhbnQ7IH1cbiAgLmZsZXgteGwtd3JhcC1yZXZlcnNlIHtcbiAgICBmbGV4LXdyYXA6IHdyYXAtcmV2ZXJzZSAhaW1wb3J0YW50OyB9XG4gIC5qdXN0aWZ5LWNvbnRlbnQteGwtc3RhcnQge1xuICAgIGp1c3RpZnktY29udGVudDogZmxleC1zdGFydCAhaW1wb3J0YW50OyB9XG4gIC5qdXN0aWZ5LWNvbnRlbnQteGwtZW5kIHtcbiAgICBqdXN0aWZ5LWNvbnRlbnQ6IGZsZXgtZW5kICFpbXBvcnRhbnQ7IH1cbiAgLmp1c3RpZnktY29udGVudC14bC1jZW50ZXIge1xuICAgIGp1c3RpZnktY29udGVudDogY2VudGVyICFpbXBvcnRhbnQ7IH1cbiAgLmp1c3RpZnktY29udGVudC14bC1iZXR3ZWVuIHtcbiAgICBqdXN0aWZ5LWNvbnRlbnQ6IHNwYWNlLWJldHdlZW4gIWltcG9ydGFudDsgfVxuICAuanVzdGlmeS1jb250ZW50LXhsLWFyb3VuZCB7XG4gICAganVzdGlmeS1jb250ZW50OiBzcGFjZS1hcm91bmQgIWltcG9ydGFudDsgfVxuICAuYWxpZ24taXRlbXMteGwtc3RhcnQge1xuICAgIGFsaWduLWl0ZW1zOiBmbGV4LXN0YXJ0ICFpbXBvcnRhbnQ7IH1cbiAgLmFsaWduLWl0ZW1zLXhsLWVuZCB7XG4gICAgYWxpZ24taXRlbXM6IGZsZXgtZW5kICFpbXBvcnRhbnQ7IH1cbiAgLmFsaWduLWl0ZW1zLXhsLWNlbnRlciB7XG4gICAgYWxpZ24taXRlbXM6IGNlbnRlciAhaW1wb3J0YW50OyB9XG4gIC5hbGlnbi1pdGVtcy14bC1iYXNlbGluZSB7XG4gICAgYWxpZ24taXRlbXM6IGJhc2VsaW5lICFpbXBvcnRhbnQ7IH1cbiAgLmFsaWduLWl0ZW1zLXhsLXN0cmV0Y2gge1xuICAgIGFsaWduLWl0ZW1zOiBzdHJldGNoICFpbXBvcnRhbnQ7IH1cbiAgLmFsaWduLWNvbnRlbnQteGwtc3RhcnQge1xuICAgIGFsaWduLWNvbnRlbnQ6IGZsZXgtc3RhcnQgIWltcG9ydGFudDsgfVxuICAuYWxpZ24tY29udGVudC14bC1lbmQge1xuICAgIGFsaWduLWNvbnRlbnQ6IGZsZXgtZW5kICFpbXBvcnRhbnQ7IH1cbiAgLmFsaWduLWNvbnRlbnQteGwtY2VudGVyIHtcbiAgICBhbGlnbi1jb250ZW50OiBjZW50ZXIgIWltcG9ydGFudDsgfVxuICAuYWxpZ24tY29udGVudC14bC1iZXR3ZWVuIHtcbiAgICBhbGlnbi1jb250ZW50OiBzcGFjZS1iZXR3ZWVuICFpbXBvcnRhbnQ7IH1cbiAgLmFsaWduLWNvbnRlbnQteGwtYXJvdW5kIHtcbiAgICBhbGlnbi1jb250ZW50OiBzcGFjZS1hcm91bmQgIWltcG9ydGFudDsgfVxuICAuYWxpZ24tY29udGVudC14bC1zdHJldGNoIHtcbiAgICBhbGlnbi1jb250ZW50OiBzdHJldGNoICFpbXBvcnRhbnQ7IH1cbiAgLmFsaWduLXNlbGYteGwtYXV0byB7XG4gICAgYWxpZ24tc2VsZjogYXV0byAhaW1wb3J0YW50OyB9XG4gIC5hbGlnbi1zZWxmLXhsLXN0YXJ0IHtcbiAgICBhbGlnbi1zZWxmOiBmbGV4LXN0YXJ0ICFpbXBvcnRhbnQ7IH1cbiAgLmFsaWduLXNlbGYteGwtZW5kIHtcbiAgICBhbGlnbi1zZWxmOiBmbGV4LWVuZCAhaW1wb3J0YW50OyB9XG4gIC5hbGlnbi1zZWxmLXhsLWNlbnRlciB7XG4gICAgYWxpZ24tc2VsZjogY2VudGVyICFpbXBvcnRhbnQ7IH1cbiAgLmFsaWduLXNlbGYteGwtYmFzZWxpbmUge1xuICAgIGFsaWduLXNlbGY6IGJhc2VsaW5lICFpbXBvcnRhbnQ7IH1cbiAgLmFsaWduLXNlbGYteGwtc3RyZXRjaCB7XG4gICAgYWxpZ24tc2VsZjogc3RyZXRjaCAhaW1wb3J0YW50OyB9IH1cblxuLmZsb2F0LWxlZnQge1xuICBmbG9hdDogbGVmdCAhaW1wb3J0YW50OyB9XG5cbi5mbG9hdC1yaWdodCB7XG4gIGZsb2F0OiByaWdodCAhaW1wb3J0YW50OyB9XG5cbi5mbG9hdC1ub25lIHtcbiAgZmxvYXQ6IG5vbmUgIWltcG9ydGFudDsgfVxuXG5AbWVkaWEgKG1pbi13aWR0aDogNTc2cHgpIHtcbiAgLmZsb2F0LXNtLWxlZnQge1xuICAgIGZsb2F0OiBsZWZ0ICFpbXBvcnRhbnQ7IH1cbiAgLmZsb2F0LXNtLXJpZ2h0IHtcbiAgICBmbG9hdDogcmlnaHQgIWltcG9ydGFudDsgfVxuICAuZmxvYXQtc20tbm9uZSB7XG4gICAgZmxvYXQ6IG5vbmUgIWltcG9ydGFudDsgfSB9XG5cbkBtZWRpYSAobWluLXdpZHRoOiA3NjhweCkge1xuICAuZmxvYXQtbWQtbGVmdCB7XG4gICAgZmxvYXQ6IGxlZnQgIWltcG9ydGFudDsgfVxuICAuZmxvYXQtbWQtcmlnaHQge1xuICAgIGZsb2F0OiByaWdodCAhaW1wb3J0YW50OyB9XG4gIC5mbG9hdC1tZC1ub25lIHtcbiAgICBmbG9hdDogbm9uZSAhaW1wb3J0YW50OyB9IH1cblxuQG1lZGlhIChtaW4td2lkdGg6IDk5MnB4KSB7XG4gIC5mbG9hdC1sZy1sZWZ0IHtcbiAgICBmbG9hdDogbGVmdCAhaW1wb3J0YW50OyB9XG4gIC5mbG9hdC1sZy1yaWdodCB7XG4gICAgZmxvYXQ6IHJpZ2h0ICFpbXBvcnRhbnQ7IH1cbiAgLmZsb2F0LWxnLW5vbmUge1xuICAgIGZsb2F0OiBub25lICFpbXBvcnRhbnQ7IH0gfVxuXG5AbWVkaWEgKG1pbi13aWR0aDogMTIwMHB4KSB7XG4gIC5mbG9hdC14bC1sZWZ0IHtcbiAgICBmbG9hdDogbGVmdCAhaW1wb3J0YW50OyB9XG4gIC5mbG9hdC14bC1yaWdodCB7XG4gICAgZmxvYXQ6IHJpZ2h0ICFpbXBvcnRhbnQ7IH1cbiAgLmZsb2F0LXhsLW5vbmUge1xuICAgIGZsb2F0OiBub25lICFpbXBvcnRhbnQ7IH0gfVxuXG4ucG9zaXRpb24tc3RhdGljIHtcbiAgcG9zaXRpb246IHN0YXRpYyAhaW1wb3J0YW50OyB9XG5cbi5wb3NpdGlvbi1yZWxhdGl2ZSB7XG4gIHBvc2l0aW9uOiByZWxhdGl2ZSAhaW1wb3J0YW50OyB9XG5cbi5wb3NpdGlvbi1hYnNvbHV0ZSB7XG4gIHBvc2l0aW9uOiBhYnNvbHV0ZSAhaW1wb3J0YW50OyB9XG5cbi5wb3NpdGlvbi1maXhlZCB7XG4gIHBvc2l0aW9uOiBmaXhlZCAhaW1wb3J0YW50OyB9XG5cbi5wb3NpdGlvbi1zdGlja3kge1xuICBwb3NpdGlvbjogc3RpY2t5ICFpbXBvcnRhbnQ7IH1cblxuLmZpeGVkLXRvcCB7XG4gIHBvc2l0aW9uOiBmaXhlZDtcbiAgdG9wOiAwO1xuICByaWdodDogMDtcbiAgbGVmdDogMDtcbiAgei1pbmRleDogMTAzMDsgfVxuXG4uZml4ZWQtYm90dG9tIHtcbiAgcG9zaXRpb246IGZpeGVkO1xuICByaWdodDogMDtcbiAgYm90dG9tOiAwO1xuICBsZWZ0OiAwO1xuICB6LWluZGV4OiAxMDMwOyB9XG5cbkBzdXBwb3J0cyAocG9zaXRpb246IHN0aWNreSkge1xuICAuc3RpY2t5LXRvcCB7XG4gICAgcG9zaXRpb246IHN0aWNreTtcbiAgICB0b3A6IDA7XG4gICAgei1pbmRleDogMTAyMDsgfSB9XG5cbi5zci1vbmx5IHtcbiAgcG9zaXRpb246IGFic29sdXRlO1xuICB3aWR0aDogMXB4O1xuICBoZWlnaHQ6IDFweDtcbiAgcGFkZGluZzogMDtcbiAgb3ZlcmZsb3c6IGhpZGRlbjtcbiAgY2xpcDogcmVjdCgwLCAwLCAwLCAwKTtcbiAgd2hpdGUtc3BhY2U6IG5vd3JhcDtcbiAgY2xpcC1wYXRoOiBpbnNldCg1MCUpO1xuICBib3JkZXI6IDA7IH1cblxuLnNyLW9ubHktZm9jdXNhYmxlOmFjdGl2ZSwgLnNyLW9ubHktZm9jdXNhYmxlOmZvY3VzIHtcbiAgcG9zaXRpb246IHN0YXRpYztcbiAgd2lkdGg6IGF1dG87XG4gIGhlaWdodDogYXV0bztcbiAgb3ZlcmZsb3c6IHZpc2libGU7XG4gIGNsaXA6IGF1dG87XG4gIHdoaXRlLXNwYWNlOiBub3JtYWw7XG4gIGNsaXAtcGF0aDogbm9uZTsgfVxuXG4udy0yNSB7XG4gIHdpZHRoOiAyNSUgIWltcG9ydGFudDsgfVxuXG4udy01MCB7XG4gIHdpZHRoOiA1MCUgIWltcG9ydGFudDsgfVxuXG4udy03NSB7XG4gIHdpZHRoOiA3NSUgIWltcG9ydGFudDsgfVxuXG4udy0xMDAge1xuICB3aWR0aDogMTAwJSAhaW1wb3J0YW50OyB9XG5cbi5oLTI1IHtcbiAgaGVpZ2h0OiAyNSUgIWltcG9ydGFudDsgfVxuXG4uaC01MCB7XG4gIGhlaWdodDogNTAlICFpbXBvcnRhbnQ7IH1cblxuLmgtNzUge1xuICBoZWlnaHQ6IDc1JSAhaW1wb3J0YW50OyB9XG5cbi5oLTEwMCB7XG4gIGhlaWdodDogMTAwJSAhaW1wb3J0YW50OyB9XG5cbi5tdy0xMDAge1xuICBtYXgtd2lkdGg6IDEwMCUgIWltcG9ydGFudDsgfVxuXG4ubWgtMTAwIHtcbiAgbWF4LWhlaWdodDogMTAwJSAhaW1wb3J0YW50OyB9XG5cbi5tLTAge1xuICBtYXJnaW46IDAgIWltcG9ydGFudDsgfVxuXG4ubXQtMCxcbi5teS0wIHtcbiAgbWFyZ2luLXRvcDogMCAhaW1wb3J0YW50OyB9XG5cbi5tci0wLFxuLm14LTAge1xuICBtYXJnaW4tcmlnaHQ6IDAgIWltcG9ydGFudDsgfVxuXG4ubWItMCxcbi5teS0wIHtcbiAgbWFyZ2luLWJvdHRvbTogMCAhaW1wb3J0YW50OyB9XG5cbi5tbC0wLFxuLm14LTAge1xuICBtYXJnaW4tbGVmdDogMCAhaW1wb3J0YW50OyB9XG5cbi5tLTEge1xuICBtYXJnaW46IDAuMjVyZW0gIWltcG9ydGFudDsgfVxuXG4ubXQtMSxcbi5teS0xIHtcbiAgbWFyZ2luLXRvcDogMC4yNXJlbSAhaW1wb3J0YW50OyB9XG5cbi5tci0xLFxuLm14LTEge1xuICBtYXJnaW4tcmlnaHQ6IDAuMjVyZW0gIWltcG9ydGFudDsgfVxuXG4ubWItMSxcbi5teS0xIHtcbiAgbWFyZ2luLWJvdHRvbTogMC4yNXJlbSAhaW1wb3J0YW50OyB9XG5cbi5tbC0xLFxuLm14LTEge1xuICBtYXJnaW4tbGVmdDogMC4yNXJlbSAhaW1wb3J0YW50OyB9XG5cbi5tLTIge1xuICBtYXJnaW46IDAuNXJlbSAhaW1wb3J0YW50OyB9XG5cbi5tdC0yLFxuLm15LTIge1xuICBtYXJnaW4tdG9wOiAwLjVyZW0gIWltcG9ydGFudDsgfVxuXG4ubXItMixcbi5teC0yIHtcbiAgbWFyZ2luLXJpZ2h0OiAwLjVyZW0gIWltcG9ydGFudDsgfVxuXG4ubWItMixcbi5teS0yIHtcbiAgbWFyZ2luLWJvdHRvbTogMC41cmVtICFpbXBvcnRhbnQ7IH1cblxuLm1sLTIsXG4ubXgtMiB7XG4gIG1hcmdpbi1sZWZ0OiAwLjVyZW0gIWltcG9ydGFudDsgfVxuXG4ubS0zIHtcbiAgbWFyZ2luOiAxcmVtICFpbXBvcnRhbnQ7IH1cblxuLm10LTMsXG4ubXktMyB7XG4gIG1hcmdpbi10b3A6IDFyZW0gIWltcG9ydGFudDsgfVxuXG4ubXItMyxcbi5teC0zIHtcbiAgbWFyZ2luLXJpZ2h0OiAxcmVtICFpbXBvcnRhbnQ7IH1cblxuLm1iLTMsXG4ubXktMyB7XG4gIG1hcmdpbi1ib3R0b206IDFyZW0gIWltcG9ydGFudDsgfVxuXG4ubWwtMyxcbi5teC0zIHtcbiAgbWFyZ2luLWxlZnQ6IDFyZW0gIWltcG9ydGFudDsgfVxuXG4ubS00IHtcbiAgbWFyZ2luOiAxLjVyZW0gIWltcG9ydGFudDsgfVxuXG4ubXQtNCxcbi5teS00IHtcbiAgbWFyZ2luLXRvcDogMS41cmVtICFpbXBvcnRhbnQ7IH1cblxuLm1yLTQsXG4ubXgtNCB7XG4gIG1hcmdpbi1yaWdodDogMS41cmVtICFpbXBvcnRhbnQ7IH1cblxuLm1iLTQsXG4ubXktNCB7XG4gIG1hcmdpbi1ib3R0b206IDEuNXJlbSAhaW1wb3J0YW50OyB9XG5cbi5tbC00LFxuLm14LTQge1xuICBtYXJnaW4tbGVmdDogMS41cmVtICFpbXBvcnRhbnQ7IH1cblxuLm0tNSB7XG4gIG1hcmdpbjogM3JlbSAhaW1wb3J0YW50OyB9XG5cbi5tdC01LFxuLm15LTUge1xuICBtYXJnaW4tdG9wOiAzcmVtICFpbXBvcnRhbnQ7IH1cblxuLm1yLTUsXG4ubXgtNSB7XG4gIG1hcmdpbi1yaWdodDogM3JlbSAhaW1wb3J0YW50OyB9XG5cbi5tYi01LFxuLm15LTUge1xuICBtYXJnaW4tYm90dG9tOiAzcmVtICFpbXBvcnRhbnQ7IH1cblxuLm1sLTUsXG4ubXgtNSB7XG4gIG1hcmdpbi1sZWZ0OiAzcmVtICFpbXBvcnRhbnQ7IH1cblxuLnAtMCB7XG4gIHBhZGRpbmc6IDAgIWltcG9ydGFudDsgfVxuXG4ucHQtMCxcbi5weS0wIHtcbiAgcGFkZGluZy10b3A6IDAgIWltcG9ydGFudDsgfVxuXG4ucHItMCxcbi5weC0wIHtcbiAgcGFkZGluZy1yaWdodDogMCAhaW1wb3J0YW50OyB9XG5cbi5wYi0wLFxuLnB5LTAge1xuICBwYWRkaW5nLWJvdHRvbTogMCAhaW1wb3J0YW50OyB9XG5cbi5wbC0wLFxuLnB4LTAge1xuICBwYWRkaW5nLWxlZnQ6IDAgIWltcG9ydGFudDsgfVxuXG4ucC0xIHtcbiAgcGFkZGluZzogMC4yNXJlbSAhaW1wb3J0YW50OyB9XG5cbi5wdC0xLFxuLnB5LTEge1xuICBwYWRkaW5nLXRvcDogMC4yNXJlbSAhaW1wb3J0YW50OyB9XG5cbi5wci0xLFxuLnB4LTEge1xuICBwYWRkaW5nLXJpZ2h0OiAwLjI1cmVtICFpbXBvcnRhbnQ7IH1cblxuLnBiLTEsXG4ucHktMSB7XG4gIHBhZGRpbmctYm90dG9tOiAwLjI1cmVtICFpbXBvcnRhbnQ7IH1cblxuLnBsLTEsXG4ucHgtMSB7XG4gIHBhZGRpbmctbGVmdDogMC4yNXJlbSAhaW1wb3J0YW50OyB9XG5cbi5wLTIge1xuICBwYWRkaW5nOiAwLjVyZW0gIWltcG9ydGFudDsgfVxuXG4ucHQtMixcbi5weS0yIHtcbiAgcGFkZGluZy10b3A6IDAuNXJlbSAhaW1wb3J0YW50OyB9XG5cbi5wci0yLFxuLnB4LTIge1xuICBwYWRkaW5nLXJpZ2h0OiAwLjVyZW0gIWltcG9ydGFudDsgfVxuXG4ucGItMixcbi5weS0yIHtcbiAgcGFkZGluZy1ib3R0b206IDAuNXJlbSAhaW1wb3J0YW50OyB9XG5cbi5wbC0yLFxuLnB4LTIge1xuICBwYWRkaW5nLWxlZnQ6IDAuNXJlbSAhaW1wb3J0YW50OyB9XG5cbi5wLTMge1xuICBwYWRkaW5nOiAxcmVtICFpbXBvcnRhbnQ7IH1cblxuLnB0LTMsXG4ucHktMyB7XG4gIHBhZGRpbmctdG9wOiAxcmVtICFpbXBvcnRhbnQ7IH1cblxuLnByLTMsXG4ucHgtMyB7XG4gIHBhZGRpbmctcmlnaHQ6IDFyZW0gIWltcG9ydGFudDsgfVxuXG4ucGItMyxcbi5weS0zIHtcbiAgcGFkZGluZy1ib3R0b206IDFyZW0gIWltcG9ydGFudDsgfVxuXG4ucGwtMyxcbi5weC0zIHtcbiAgcGFkZGluZy1sZWZ0OiAxcmVtICFpbXBvcnRhbnQ7IH1cblxuLnAtNCB7XG4gIHBhZGRpbmc6IDEuNXJlbSAhaW1wb3J0YW50OyB9XG5cbi5wdC00LFxuLnB5LTQge1xuICBwYWRkaW5nLXRvcDogMS41cmVtICFpbXBvcnRhbnQ7IH1cblxuLnByLTQsXG4ucHgtNCB7XG4gIHBhZGRpbmctcmlnaHQ6IDEuNXJlbSAhaW1wb3J0YW50OyB9XG5cbi5wYi00LFxuLnB5LTQge1xuICBwYWRkaW5nLWJvdHRvbTogMS41cmVtICFpbXBvcnRhbnQ7IH1cblxuLnBsLTQsXG4ucHgtNCB7XG4gIHBhZGRpbmctbGVmdDogMS41cmVtICFpbXBvcnRhbnQ7IH1cblxuLnAtNSB7XG4gIHBhZGRpbmc6IDNyZW0gIWltcG9ydGFudDsgfVxuXG4ucHQtNSxcbi5weS01IHtcbiAgcGFkZGluZy10b3A6IDNyZW0gIWltcG9ydGFudDsgfVxuXG4ucHItNSxcbi5weC01IHtcbiAgcGFkZGluZy1yaWdodDogM3JlbSAhaW1wb3J0YW50OyB9XG5cbi5wYi01LFxuLnB5LTUge1xuICBwYWRkaW5nLWJvdHRvbTogM3JlbSAhaW1wb3J0YW50OyB9XG5cbi5wbC01LFxuLnB4LTUge1xuICBwYWRkaW5nLWxlZnQ6IDNyZW0gIWltcG9ydGFudDsgfVxuXG4ubS1hdXRvIHtcbiAgbWFyZ2luOiBhdXRvICFpbXBvcnRhbnQ7IH1cblxuLm10LWF1dG8sXG4ubXktYXV0byB7XG4gIG1hcmdpbi10b3A6IGF1dG8gIWltcG9ydGFudDsgfVxuXG4ubXItYXV0byxcbi5teC1hdXRvIHtcbiAgbWFyZ2luLXJpZ2h0OiBhdXRvICFpbXBvcnRhbnQ7IH1cblxuLm1iLWF1dG8sXG4ubXktYXV0byB7XG4gIG1hcmdpbi1ib3R0b206IGF1dG8gIWltcG9ydGFudDsgfVxuXG4ubWwtYXV0byxcbi5teC1hdXRvIHtcbiAgbWFyZ2luLWxlZnQ6IGF1dG8gIWltcG9ydGFudDsgfVxuXG5AbWVkaWEgKG1pbi13aWR0aDogNTc2cHgpIHtcbiAgLm0tc20tMCB7XG4gICAgbWFyZ2luOiAwICFpbXBvcnRhbnQ7IH1cbiAgLm10LXNtLTAsXG4gIC5teS1zbS0wIHtcbiAgICBtYXJnaW4tdG9wOiAwICFpbXBvcnRhbnQ7IH1cbiAgLm1yLXNtLTAsXG4gIC5teC1zbS0wIHtcbiAgICBtYXJnaW4tcmlnaHQ6IDAgIWltcG9ydGFudDsgfVxuICAubWItc20tMCxcbiAgLm15LXNtLTAge1xuICAgIG1hcmdpbi1ib3R0b206IDAgIWltcG9ydGFudDsgfVxuICAubWwtc20tMCxcbiAgLm14LXNtLTAge1xuICAgIG1hcmdpbi1sZWZ0OiAwICFpbXBvcnRhbnQ7IH1cbiAgLm0tc20tMSB7XG4gICAgbWFyZ2luOiAwLjI1cmVtICFpbXBvcnRhbnQ7IH1cbiAgLm10LXNtLTEsXG4gIC5teS1zbS0xIHtcbiAgICBtYXJnaW4tdG9wOiAwLjI1cmVtICFpbXBvcnRhbnQ7IH1cbiAgLm1yLXNtLTEsXG4gIC5teC1zbS0xIHtcbiAgICBtYXJnaW4tcmlnaHQ6IDAuMjVyZW0gIWltcG9ydGFudDsgfVxuICAubWItc20tMSxcbiAgLm15LXNtLTEge1xuICAgIG1hcmdpbi1ib3R0b206IDAuMjVyZW0gIWltcG9ydGFudDsgfVxuICAubWwtc20tMSxcbiAgLm14LXNtLTEge1xuICAgIG1hcmdpbi1sZWZ0OiAwLjI1cmVtICFpbXBvcnRhbnQ7IH1cbiAgLm0tc20tMiB7XG4gICAgbWFyZ2luOiAwLjVyZW0gIWltcG9ydGFudDsgfVxuICAubXQtc20tMixcbiAgLm15LXNtLTIge1xuICAgIG1hcmdpbi10b3A6IDAuNXJlbSAhaW1wb3J0YW50OyB9XG4gIC5tci1zbS0yLFxuICAubXgtc20tMiB7XG4gICAgbWFyZ2luLXJpZ2h0OiAwLjVyZW0gIWltcG9ydGFudDsgfVxuICAubWItc20tMixcbiAgLm15LXNtLTIge1xuICAgIG1hcmdpbi1ib3R0b206IDAuNXJlbSAhaW1wb3J0YW50OyB9XG4gIC5tbC1zbS0yLFxuICAubXgtc20tMiB7XG4gICAgbWFyZ2luLWxlZnQ6IDAuNXJlbSAhaW1wb3J0YW50OyB9XG4gIC5tLXNtLTMge1xuICAgIG1hcmdpbjogMXJlbSAhaW1wb3J0YW50OyB9XG4gIC5tdC1zbS0zLFxuICAubXktc20tMyB7XG4gICAgbWFyZ2luLXRvcDogMXJlbSAhaW1wb3J0YW50OyB9XG4gIC5tci1zbS0zLFxuICAubXgtc20tMyB7XG4gICAgbWFyZ2luLXJpZ2h0OiAxcmVtICFpbXBvcnRhbnQ7IH1cbiAgLm1iLXNtLTMsXG4gIC5teS1zbS0zIHtcbiAgICBtYXJnaW4tYm90dG9tOiAxcmVtICFpbXBvcnRhbnQ7IH1cbiAgLm1sLXNtLTMsXG4gIC5teC1zbS0zIHtcbiAgICBtYXJnaW4tbGVmdDogMXJlbSAhaW1wb3J0YW50OyB9XG4gIC5tLXNtLTQge1xuICAgIG1hcmdpbjogMS41cmVtICFpbXBvcnRhbnQ7IH1cbiAgLm10LXNtLTQsXG4gIC5teS1zbS00IHtcbiAgICBtYXJnaW4tdG9wOiAxLjVyZW0gIWltcG9ydGFudDsgfVxuICAubXItc20tNCxcbiAgLm14LXNtLTQge1xuICAgIG1hcmdpbi1yaWdodDogMS41cmVtICFpbXBvcnRhbnQ7IH1cbiAgLm1iLXNtLTQsXG4gIC5teS1zbS00IHtcbiAgICBtYXJnaW4tYm90dG9tOiAxLjVyZW0gIWltcG9ydGFudDsgfVxuICAubWwtc20tNCxcbiAgLm14LXNtLTQge1xuICAgIG1hcmdpbi1sZWZ0OiAxLjVyZW0gIWltcG9ydGFudDsgfVxuICAubS1zbS01IHtcbiAgICBtYXJnaW46IDNyZW0gIWltcG9ydGFudDsgfVxuICAubXQtc20tNSxcbiAgLm15LXNtLTUge1xuICAgIG1hcmdpbi10b3A6IDNyZW0gIWltcG9ydGFudDsgfVxuICAubXItc20tNSxcbiAgLm14LXNtLTUge1xuICAgIG1hcmdpbi1yaWdodDogM3JlbSAhaW1wb3J0YW50OyB9XG4gIC5tYi1zbS01LFxuICAubXktc20tNSB7XG4gICAgbWFyZ2luLWJvdHRvbTogM3JlbSAhaW1wb3J0YW50OyB9XG4gIC5tbC1zbS01LFxuICAubXgtc20tNSB7XG4gICAgbWFyZ2luLWxlZnQ6IDNyZW0gIWltcG9ydGFudDsgfVxuICAucC1zbS0wIHtcbiAgICBwYWRkaW5nOiAwICFpbXBvcnRhbnQ7IH1cbiAgLnB0LXNtLTAsXG4gIC5weS1zbS0wIHtcbiAgICBwYWRkaW5nLXRvcDogMCAhaW1wb3J0YW50OyB9XG4gIC5wci1zbS0wLFxuICAucHgtc20tMCB7XG4gICAgcGFkZGluZy1yaWdodDogMCAhaW1wb3J0YW50OyB9XG4gIC5wYi1zbS0wLFxuICAucHktc20tMCB7XG4gICAgcGFkZGluZy1ib3R0b206IDAgIWltcG9ydGFudDsgfVxuICAucGwtc20tMCxcbiAgLnB4LXNtLTAge1xuICAgIHBhZGRpbmctbGVmdDogMCAhaW1wb3J0YW50OyB9XG4gIC5wLXNtLTEge1xuICAgIHBhZGRpbmc6IDAuMjVyZW0gIWltcG9ydGFudDsgfVxuICAucHQtc20tMSxcbiAgLnB5LXNtLTEge1xuICAgIHBhZGRpbmctdG9wOiAwLjI1cmVtICFpbXBvcnRhbnQ7IH1cbiAgLnByLXNtLTEsXG4gIC5weC1zbS0xIHtcbiAgICBwYWRkaW5nLXJpZ2h0OiAwLjI1cmVtICFpbXBvcnRhbnQ7IH1cbiAgLnBiLXNtLTEsXG4gIC5weS1zbS0xIHtcbiAgICBwYWRkaW5nLWJvdHRvbTogMC4yNXJlbSAhaW1wb3J0YW50OyB9XG4gIC5wbC1zbS0xLFxuICAucHgtc20tMSB7XG4gICAgcGFkZGluZy1sZWZ0OiAwLjI1cmVtICFpbXBvcnRhbnQ7IH1cbiAgLnAtc20tMiB7XG4gICAgcGFkZGluZzogMC41cmVtICFpbXBvcnRhbnQ7IH1cbiAgLnB0LXNtLTIsXG4gIC5weS1zbS0yIHtcbiAgICBwYWRkaW5nLXRvcDogMC41cmVtICFpbXBvcnRhbnQ7IH1cbiAgLnByLXNtLTIsXG4gIC5weC1zbS0yIHtcbiAgICBwYWRkaW5nLXJpZ2h0OiAwLjVyZW0gIWltcG9ydGFudDsgfVxuICAucGItc20tMixcbiAgLnB5LXNtLTIge1xuICAgIHBhZGRpbmctYm90dG9tOiAwLjVyZW0gIWltcG9ydGFudDsgfVxuICAucGwtc20tMixcbiAgLnB4LXNtLTIge1xuICAgIHBhZGRpbmctbGVmdDogMC41cmVtICFpbXBvcnRhbnQ7IH1cbiAgLnAtc20tMyB7XG4gICAgcGFkZGluZzogMXJlbSAhaW1wb3J0YW50OyB9XG4gIC5wdC1zbS0zLFxuICAucHktc20tMyB7XG4gICAgcGFkZGluZy10b3A6IDFyZW0gIWltcG9ydGFudDsgfVxuICAucHItc20tMyxcbiAgLnB4LXNtLTMge1xuICAgIHBhZGRpbmctcmlnaHQ6IDFyZW0gIWltcG9ydGFudDsgfVxuICAucGItc20tMyxcbiAgLnB5LXNtLTMge1xuICAgIHBhZGRpbmctYm90dG9tOiAxcmVtICFpbXBvcnRhbnQ7IH1cbiAgLnBsLXNtLTMsXG4gIC5weC1zbS0zIHtcbiAgICBwYWRkaW5nLWxlZnQ6IDFyZW0gIWltcG9ydGFudDsgfVxuICAucC1zbS00IHtcbiAgICBwYWRkaW5nOiAxLjVyZW0gIWltcG9ydGFudDsgfVxuICAucHQtc20tNCxcbiAgLnB5LXNtLTQge1xuICAgIHBhZGRpbmctdG9wOiAxLjVyZW0gIWltcG9ydGFudDsgfVxuICAucHItc20tNCxcbiAgLnB4LXNtLTQge1xuICAgIHBhZGRpbmctcmlnaHQ6IDEuNXJlbSAhaW1wb3J0YW50OyB9XG4gIC5wYi1zbS00LFxuICAucHktc20tNCB7XG4gICAgcGFkZGluZy1ib3R0b206IDEuNXJlbSAhaW1wb3J0YW50OyB9XG4gIC5wbC1zbS00LFxuICAucHgtc20tNCB7XG4gICAgcGFkZGluZy1sZWZ0OiAxLjVyZW0gIWltcG9ydGFudDsgfVxuICAucC1zbS01IHtcbiAgICBwYWRkaW5nOiAzcmVtICFpbXBvcnRhbnQ7IH1cbiAgLnB0LXNtLTUsXG4gIC5weS1zbS01IHtcbiAgICBwYWRkaW5nLXRvcDogM3JlbSAhaW1wb3J0YW50OyB9XG4gIC5wci1zbS01LFxuICAucHgtc20tNSB7XG4gICAgcGFkZGluZy1yaWdodDogM3JlbSAhaW1wb3J0YW50OyB9XG4gIC5wYi1zbS01LFxuICAucHktc20tNSB7XG4gICAgcGFkZGluZy1ib3R0b206IDNyZW0gIWltcG9ydGFudDsgfVxuICAucGwtc20tNSxcbiAgLnB4LXNtLTUge1xuICAgIHBhZGRpbmctbGVmdDogM3JlbSAhaW1wb3J0YW50OyB9XG4gIC5tLXNtLWF1dG8ge1xuICAgIG1hcmdpbjogYXV0byAhaW1wb3J0YW50OyB9XG4gIC5tdC1zbS1hdXRvLFxuICAubXktc20tYXV0byB7XG4gICAgbWFyZ2luLXRvcDogYXV0byAhaW1wb3J0YW50OyB9XG4gIC5tci1zbS1hdXRvLFxuICAubXgtc20tYXV0byB7XG4gICAgbWFyZ2luLXJpZ2h0OiBhdXRvICFpbXBvcnRhbnQ7IH1cbiAgLm1iLXNtLWF1dG8sXG4gIC5teS1zbS1hdXRvIHtcbiAgICBtYXJnaW4tYm90dG9tOiBhdXRvICFpbXBvcnRhbnQ7IH1cbiAgLm1sLXNtLWF1dG8sXG4gIC5teC1zbS1hdXRvIHtcbiAgICBtYXJnaW4tbGVmdDogYXV0byAhaW1wb3J0YW50OyB9IH1cblxuQG1lZGlhIChtaW4td2lkdGg6IDc2OHB4KSB7XG4gIC5tLW1kLTAge1xuICAgIG1hcmdpbjogMCAhaW1wb3J0YW50OyB9XG4gIC5tdC1tZC0wLFxuICAubXktbWQtMCB7XG4gICAgbWFyZ2luLXRvcDogMCAhaW1wb3J0YW50OyB9XG4gIC5tci1tZC0wLFxuICAubXgtbWQtMCB7XG4gICAgbWFyZ2luLXJpZ2h0OiAwICFpbXBvcnRhbnQ7IH1cbiAgLm1iLW1kLTAsXG4gIC5teS1tZC0wIHtcbiAgICBtYXJnaW4tYm90dG9tOiAwICFpbXBvcnRhbnQ7IH1cbiAgLm1sLW1kLTAsXG4gIC5teC1tZC0wIHtcbiAgICBtYXJnaW4tbGVmdDogMCAhaW1wb3J0YW50OyB9XG4gIC5tLW1kLTEge1xuICAgIG1hcmdpbjogMC4yNXJlbSAhaW1wb3J0YW50OyB9XG4gIC5tdC1tZC0xLFxuICAubXktbWQtMSB7XG4gICAgbWFyZ2luLXRvcDogMC4yNXJlbSAhaW1wb3J0YW50OyB9XG4gIC5tci1tZC0xLFxuICAubXgtbWQtMSB7XG4gICAgbWFyZ2luLXJpZ2h0OiAwLjI1cmVtICFpbXBvcnRhbnQ7IH1cbiAgLm1iLW1kLTEsXG4gIC5teS1tZC0xIHtcbiAgICBtYXJnaW4tYm90dG9tOiAwLjI1cmVtICFpbXBvcnRhbnQ7IH1cbiAgLm1sLW1kLTEsXG4gIC5teC1tZC0xIHtcbiAgICBtYXJnaW4tbGVmdDogMC4yNXJlbSAhaW1wb3J0YW50OyB9XG4gIC5tLW1kLTIge1xuICAgIG1hcmdpbjogMC41cmVtICFpbXBvcnRhbnQ7IH1cbiAgLm10LW1kLTIsXG4gIC5teS1tZC0yIHtcbiAgICBtYXJnaW4tdG9wOiAwLjVyZW0gIWltcG9ydGFudDsgfVxuICAubXItbWQtMixcbiAgLm14LW1kLTIge1xuICAgIG1hcmdpbi1yaWdodDogMC41cmVtICFpbXBvcnRhbnQ7IH1cbiAgLm1iLW1kLTIsXG4gIC5teS1tZC0yIHtcbiAgICBtYXJnaW4tYm90dG9tOiAwLjVyZW0gIWltcG9ydGFudDsgfVxuICAubWwtbWQtMixcbiAgLm14LW1kLTIge1xuICAgIG1hcmdpbi1sZWZ0OiAwLjVyZW0gIWltcG9ydGFudDsgfVxuICAubS1tZC0zIHtcbiAgICBtYXJnaW46IDFyZW0gIWltcG9ydGFudDsgfVxuICAubXQtbWQtMyxcbiAgLm15LW1kLTMge1xuICAgIG1hcmdpbi10b3A6IDFyZW0gIWltcG9ydGFudDsgfVxuICAubXItbWQtMyxcbiAgLm14LW1kLTMge1xuICAgIG1hcmdpbi1yaWdodDogMXJlbSAhaW1wb3J0YW50OyB9XG4gIC5tYi1tZC0zLFxuICAubXktbWQtMyB7XG4gICAgbWFyZ2luLWJvdHRvbTogMXJlbSAhaW1wb3J0YW50OyB9XG4gIC5tbC1tZC0zLFxuICAubXgtbWQtMyB7XG4gICAgbWFyZ2luLWxlZnQ6IDFyZW0gIWltcG9ydGFudDsgfVxuICAubS1tZC00IHtcbiAgICBtYXJnaW46IDEuNXJlbSAhaW1wb3J0YW50OyB9XG4gIC5tdC1tZC00LFxuICAubXktbWQtNCB7XG4gICAgbWFyZ2luLXRvcDogMS41cmVtICFpbXBvcnRhbnQ7IH1cbiAgLm1yLW1kLTQsXG4gIC5teC1tZC00IHtcbiAgICBtYXJnaW4tcmlnaHQ6IDEuNXJlbSAhaW1wb3J0YW50OyB9XG4gIC5tYi1tZC00LFxuICAubXktbWQtNCB7XG4gICAgbWFyZ2luLWJvdHRvbTogMS41cmVtICFpbXBvcnRhbnQ7IH1cbiAgLm1sLW1kLTQsXG4gIC5teC1tZC00IHtcbiAgICBtYXJnaW4tbGVmdDogMS41cmVtICFpbXBvcnRhbnQ7IH1cbiAgLm0tbWQtNSB7XG4gICAgbWFyZ2luOiAzcmVtICFpbXBvcnRhbnQ7IH1cbiAgLm10LW1kLTUsXG4gIC5teS1tZC01IHtcbiAgICBtYXJnaW4tdG9wOiAzcmVtICFpbXBvcnRhbnQ7IH1cbiAgLm1yLW1kLTUsXG4gIC5teC1tZC01IHtcbiAgICBtYXJnaW4tcmlnaHQ6IDNyZW0gIWltcG9ydGFudDsgfVxuICAubWItbWQtNSxcbiAgLm15LW1kLTUge1xuICAgIG1hcmdpbi1ib3R0b206IDNyZW0gIWltcG9ydGFudDsgfVxuICAubWwtbWQtNSxcbiAgLm14LW1kLTUge1xuICAgIG1hcmdpbi1sZWZ0OiAzcmVtICFpbXBvcnRhbnQ7IH1cbiAgLnAtbWQtMCB7XG4gICAgcGFkZGluZzogMCAhaW1wb3J0YW50OyB9XG4gIC5wdC1tZC0wLFxuICAucHktbWQtMCB7XG4gICAgcGFkZGluZy10b3A6IDAgIWltcG9ydGFudDsgfVxuICAucHItbWQtMCxcbiAgLnB4LW1kLTAge1xuICAgIHBhZGRpbmctcmlnaHQ6IDAgIWltcG9ydGFudDsgfVxuICAucGItbWQtMCxcbiAgLnB5LW1kLTAge1xuICAgIHBhZGRpbmctYm90dG9tOiAwICFpbXBvcnRhbnQ7IH1cbiAgLnBsLW1kLTAsXG4gIC5weC1tZC0wIHtcbiAgICBwYWRkaW5nLWxlZnQ6IDAgIWltcG9ydGFudDsgfVxuICAucC1tZC0xIHtcbiAgICBwYWRkaW5nOiAwLjI1cmVtICFpbXBvcnRhbnQ7IH1cbiAgLnB0LW1kLTEsXG4gIC5weS1tZC0xIHtcbiAgICBwYWRkaW5nLXRvcDogMC4yNXJlbSAhaW1wb3J0YW50OyB9XG4gIC5wci1tZC0xLFxuICAucHgtbWQtMSB7XG4gICAgcGFkZGluZy1yaWdodDogMC4yNXJlbSAhaW1wb3J0YW50OyB9XG4gIC5wYi1tZC0xLFxuICAucHktbWQtMSB7XG4gICAgcGFkZGluZy1ib3R0b206IDAuMjVyZW0gIWltcG9ydGFudDsgfVxuICAucGwtbWQtMSxcbiAgLnB4LW1kLTEge1xuICAgIHBhZGRpbmctbGVmdDogMC4yNXJlbSAhaW1wb3J0YW50OyB9XG4gIC5wLW1kLTIge1xuICAgIHBhZGRpbmc6IDAuNXJlbSAhaW1wb3J0YW50OyB9XG4gIC5wdC1tZC0yLFxuICAucHktbWQtMiB7XG4gICAgcGFkZGluZy10b3A6IDAuNXJlbSAhaW1wb3J0YW50OyB9XG4gIC5wci1tZC0yLFxuICAucHgtbWQtMiB7XG4gICAgcGFkZGluZy1yaWdodDogMC41cmVtICFpbXBvcnRhbnQ7IH1cbiAgLnBiLW1kLTIsXG4gIC5weS1tZC0yIHtcbiAgICBwYWRkaW5nLWJvdHRvbTogMC41cmVtICFpbXBvcnRhbnQ7IH1cbiAgLnBsLW1kLTIsXG4gIC5weC1tZC0yIHtcbiAgICBwYWRkaW5nLWxlZnQ6IDAuNXJlbSAhaW1wb3J0YW50OyB9XG4gIC5wLW1kLTMge1xuICAgIHBhZGRpbmc6IDFyZW0gIWltcG9ydGFudDsgfVxuICAucHQtbWQtMyxcbiAgLnB5LW1kLTMge1xuICAgIHBhZGRpbmctdG9wOiAxcmVtICFpbXBvcnRhbnQ7IH1cbiAgLnByLW1kLTMsXG4gIC5weC1tZC0zIHtcbiAgICBwYWRkaW5nLXJpZ2h0OiAxcmVtICFpbXBvcnRhbnQ7IH1cbiAgLnBiLW1kLTMsXG4gIC5weS1tZC0zIHtcbiAgICBwYWRkaW5nLWJvdHRvbTogMXJlbSAhaW1wb3J0YW50OyB9XG4gIC5wbC1tZC0zLFxuICAucHgtbWQtMyB7XG4gICAgcGFkZGluZy1sZWZ0OiAxcmVtICFpbXBvcnRhbnQ7IH1cbiAgLnAtbWQtNCB7XG4gICAgcGFkZGluZzogMS41cmVtICFpbXBvcnRhbnQ7IH1cbiAgLnB0LW1kLTQsXG4gIC5weS1tZC00IHtcbiAgICBwYWRkaW5nLXRvcDogMS41cmVtICFpbXBvcnRhbnQ7IH1cbiAgLnByLW1kLTQsXG4gIC5weC1tZC00IHtcbiAgICBwYWRkaW5nLXJpZ2h0OiAxLjVyZW0gIWltcG9ydGFudDsgfVxuICAucGItbWQtNCxcbiAgLnB5LW1kLTQge1xuICAgIHBhZGRpbmctYm90dG9tOiAxLjVyZW0gIWltcG9ydGFudDsgfVxuICAucGwtbWQtNCxcbiAgLnB4LW1kLTQge1xuICAgIHBhZGRpbmctbGVmdDogMS41cmVtICFpbXBvcnRhbnQ7IH1cbiAgLnAtbWQtNSB7XG4gICAgcGFkZGluZzogM3JlbSAhaW1wb3J0YW50OyB9XG4gIC5wdC1tZC01LFxuICAucHktbWQtNSB7XG4gICAgcGFkZGluZy10b3A6IDNyZW0gIWltcG9ydGFudDsgfVxuICAucHItbWQtNSxcbiAgLnB4LW1kLTUge1xuICAgIHBhZGRpbmctcmlnaHQ6IDNyZW0gIWltcG9ydGFudDsgfVxuICAucGItbWQtNSxcbiAgLnB5LW1kLTUge1xuICAgIHBhZGRpbmctYm90dG9tOiAzcmVtICFpbXBvcnRhbnQ7IH1cbiAgLnBsLW1kLTUsXG4gIC5weC1tZC01IHtcbiAgICBwYWRkaW5nLWxlZnQ6IDNyZW0gIWltcG9ydGFudDsgfVxuICAubS1tZC1hdXRvIHtcbiAgICBtYXJnaW46IGF1dG8gIWltcG9ydGFudDsgfVxuICAubXQtbWQtYXV0byxcbiAgLm15LW1kLWF1dG8ge1xuICAgIG1hcmdpbi10b3A6IGF1dG8gIWltcG9ydGFudDsgfVxuICAubXItbWQtYXV0byxcbiAgLm14LW1kLWF1dG8ge1xuICAgIG1hcmdpbi1yaWdodDogYXV0byAhaW1wb3J0YW50OyB9XG4gIC5tYi1tZC1hdXRvLFxuICAubXktbWQtYXV0byB7XG4gICAgbWFyZ2luLWJvdHRvbTogYXV0byAhaW1wb3J0YW50OyB9XG4gIC5tbC1tZC1hdXRvLFxuICAubXgtbWQtYXV0byB7XG4gICAgbWFyZ2luLWxlZnQ6IGF1dG8gIWltcG9ydGFudDsgfSB9XG5cbkBtZWRpYSAobWluLXdpZHRoOiA5OTJweCkge1xuICAubS1sZy0wIHtcbiAgICBtYXJnaW46IDAgIWltcG9ydGFudDsgfVxuICAubXQtbGctMCxcbiAgLm15LWxnLTAge1xuICAgIG1hcmdpbi10b3A6IDAgIWltcG9ydGFudDsgfVxuICAubXItbGctMCxcbiAgLm14LWxnLTAge1xuICAgIG1hcmdpbi1yaWdodDogMCAhaW1wb3J0YW50OyB9XG4gIC5tYi1sZy0wLFxuICAubXktbGctMCB7XG4gICAgbWFyZ2luLWJvdHRvbTogMCAhaW1wb3J0YW50OyB9XG4gIC5tbC1sZy0wLFxuICAubXgtbGctMCB7XG4gICAgbWFyZ2luLWxlZnQ6IDAgIWltcG9ydGFudDsgfVxuICAubS1sZy0xIHtcbiAgICBtYXJnaW46IDAuMjVyZW0gIWltcG9ydGFudDsgfVxuICAubXQtbGctMSxcbiAgLm15LWxnLTEge1xuICAgIG1hcmdpbi10b3A6IDAuMjVyZW0gIWltcG9ydGFudDsgfVxuICAubXItbGctMSxcbiAgLm14LWxnLTEge1xuICAgIG1hcmdpbi1yaWdodDogMC4yNXJlbSAhaW1wb3J0YW50OyB9XG4gIC5tYi1sZy0xLFxuICAubXktbGctMSB7XG4gICAgbWFyZ2luLWJvdHRvbTogMC4yNXJlbSAhaW1wb3J0YW50OyB9XG4gIC5tbC1sZy0xLFxuICAubXgtbGctMSB7XG4gICAgbWFyZ2luLWxlZnQ6IDAuMjVyZW0gIWltcG9ydGFudDsgfVxuICAubS1sZy0yIHtcbiAgICBtYXJnaW46IDAuNXJlbSAhaW1wb3J0YW50OyB9XG4gIC5tdC1sZy0yLFxuICAubXktbGctMiB7XG4gICAgbWFyZ2luLXRvcDogMC41cmVtICFpbXBvcnRhbnQ7IH1cbiAgLm1yLWxnLTIsXG4gIC5teC1sZy0yIHtcbiAgICBtYXJnaW4tcmlnaHQ6IDAuNXJlbSAhaW1wb3J0YW50OyB9XG4gIC5tYi1sZy0yLFxuICAubXktbGctMiB7XG4gICAgbWFyZ2luLWJvdHRvbTogMC41cmVtICFpbXBvcnRhbnQ7IH1cbiAgLm1sLWxnLTIsXG4gIC5teC1sZy0yIHtcbiAgICBtYXJnaW4tbGVmdDogMC41cmVtICFpbXBvcnRhbnQ7IH1cbiAgLm0tbGctMyB7XG4gICAgbWFyZ2luOiAxcmVtICFpbXBvcnRhbnQ7IH1cbiAgLm10LWxnLTMsXG4gIC5teS1sZy0zIHtcbiAgICBtYXJnaW4tdG9wOiAxcmVtICFpbXBvcnRhbnQ7IH1cbiAgLm1yLWxnLTMsXG4gIC5teC1sZy0zIHtcbiAgICBtYXJnaW4tcmlnaHQ6IDFyZW0gIWltcG9ydGFudDsgfVxuICAubWItbGctMyxcbiAgLm15LWxnLTMge1xuICAgIG1hcmdpbi1ib3R0b206IDFyZW0gIWltcG9ydGFudDsgfVxuICAubWwtbGctMyxcbiAgLm14LWxnLTMge1xuICAgIG1hcmdpbi1sZWZ0OiAxcmVtICFpbXBvcnRhbnQ7IH1cbiAgLm0tbGctNCB7XG4gICAgbWFyZ2luOiAxLjVyZW0gIWltcG9ydGFudDsgfVxuICAubXQtbGctNCxcbiAgLm15LWxnLTQge1xuICAgIG1hcmdpbi10b3A6IDEuNXJlbSAhaW1wb3J0YW50OyB9XG4gIC5tci1sZy00LFxuICAubXgtbGctNCB7XG4gICAgbWFyZ2luLXJpZ2h0OiAxLjVyZW0gIWltcG9ydGFudDsgfVxuICAubWItbGctNCxcbiAgLm15LWxnLTQge1xuICAgIG1hcmdpbi1ib3R0b206IDEuNXJlbSAhaW1wb3J0YW50OyB9XG4gIC5tbC1sZy00LFxuICAubXgtbGctNCB7XG4gICAgbWFyZ2luLWxlZnQ6IDEuNXJlbSAhaW1wb3J0YW50OyB9XG4gIC5tLWxnLTUge1xuICAgIG1hcmdpbjogM3JlbSAhaW1wb3J0YW50OyB9XG4gIC5tdC1sZy01LFxuICAubXktbGctNSB7XG4gICAgbWFyZ2luLXRvcDogM3JlbSAhaW1wb3J0YW50OyB9XG4gIC5tci1sZy01LFxuICAubXgtbGctNSB7XG4gICAgbWFyZ2luLXJpZ2h0OiAzcmVtICFpbXBvcnRhbnQ7IH1cbiAgLm1iLWxnLTUsXG4gIC5teS1sZy01IHtcbiAgICBtYXJnaW4tYm90dG9tOiAzcmVtICFpbXBvcnRhbnQ7IH1cbiAgLm1sLWxnLTUsXG4gIC5teC1sZy01IHtcbiAgICBtYXJnaW4tbGVmdDogM3JlbSAhaW1wb3J0YW50OyB9XG4gIC5wLWxnLTAge1xuICAgIHBhZGRpbmc6IDAgIWltcG9ydGFudDsgfVxuICAucHQtbGctMCxcbiAgLnB5LWxnLTAge1xuICAgIHBhZGRpbmctdG9wOiAwICFpbXBvcnRhbnQ7IH1cbiAgLnByLWxnLTAsXG4gIC5weC1sZy0wIHtcbiAgICBwYWRkaW5nLXJpZ2h0OiAwICFpbXBvcnRhbnQ7IH1cbiAgLnBiLWxnLTAsXG4gIC5weS1sZy0wIHtcbiAgICBwYWRkaW5nLWJvdHRvbTogMCAhaW1wb3J0YW50OyB9XG4gIC5wbC1sZy0wLFxuICAucHgtbGctMCB7XG4gICAgcGFkZGluZy1sZWZ0OiAwICFpbXBvcnRhbnQ7IH1cbiAgLnAtbGctMSB7XG4gICAgcGFkZGluZzogMC4yNXJlbSAhaW1wb3J0YW50OyB9XG4gIC5wdC1sZy0xLFxuICAucHktbGctMSB7XG4gICAgcGFkZGluZy10b3A6IDAuMjVyZW0gIWltcG9ydGFudDsgfVxuICAucHItbGctMSxcbiAgLnB4LWxnLTEge1xuICAgIHBhZGRpbmctcmlnaHQ6IDAuMjVyZW0gIWltcG9ydGFudDsgfVxuICAucGItbGctMSxcbiAgLnB5LWxnLTEge1xuICAgIHBhZGRpbmctYm90dG9tOiAwLjI1cmVtICFpbXBvcnRhbnQ7IH1cbiAgLnBsLWxnLTEsXG4gIC5weC1sZy0xIHtcbiAgICBwYWRkaW5nLWxlZnQ6IDAuMjVyZW0gIWltcG9ydGFudDsgfVxuICAucC1sZy0yIHtcbiAgICBwYWRkaW5nOiAwLjVyZW0gIWltcG9ydGFudDsgfVxuICAucHQtbGctMixcbiAgLnB5LWxnLTIge1xuICAgIHBhZGRpbmctdG9wOiAwLjVyZW0gIWltcG9ydGFudDsgfVxuICAucHItbGctMixcbiAgLnB4LWxnLTIge1xuICAgIHBhZGRpbmctcmlnaHQ6IDAuNXJlbSAhaW1wb3J0YW50OyB9XG4gIC5wYi1sZy0yLFxuICAucHktbGctMiB7XG4gICAgcGFkZGluZy1ib3R0b206IDAuNXJlbSAhaW1wb3J0YW50OyB9XG4gIC5wbC1sZy0yLFxuICAucHgtbGctMiB7XG4gICAgcGFkZGluZy1sZWZ0OiAwLjVyZW0gIWltcG9ydGFudDsgfVxuICAucC1sZy0zIHtcbiAgICBwYWRkaW5nOiAxcmVtICFpbXBvcnRhbnQ7IH1cbiAgLnB0LWxnLTMsXG4gIC5weS1sZy0zIHtcbiAgICBwYWRkaW5nLXRvcDogMXJlbSAhaW1wb3J0YW50OyB9XG4gIC5wci1sZy0zLFxuICAucHgtbGctMyB7XG4gICAgcGFkZGluZy1yaWdodDogMXJlbSAhaW1wb3J0YW50OyB9XG4gIC5wYi1sZy0zLFxuICAucHktbGctMyB7XG4gICAgcGFkZGluZy1ib3R0b206IDFyZW0gIWltcG9ydGFudDsgfVxuICAucGwtbGctMyxcbiAgLnB4LWxnLTMge1xuICAgIHBhZGRpbmctbGVmdDogMXJlbSAhaW1wb3J0YW50OyB9XG4gIC5wLWxnLTQge1xuICAgIHBhZGRpbmc6IDEuNXJlbSAhaW1wb3J0YW50OyB9XG4gIC5wdC1sZy00LFxuICAucHktbGctNCB7XG4gICAgcGFkZGluZy10b3A6IDEuNXJlbSAhaW1wb3J0YW50OyB9XG4gIC5wci1sZy00LFxuICAucHgtbGctNCB7XG4gICAgcGFkZGluZy1yaWdodDogMS41cmVtICFpbXBvcnRhbnQ7IH1cbiAgLnBiLWxnLTQsXG4gIC5weS1sZy00IHtcbiAgICBwYWRkaW5nLWJvdHRvbTogMS41cmVtICFpbXBvcnRhbnQ7IH1cbiAgLnBsLWxnLTQsXG4gIC5weC1sZy00IHtcbiAgICBwYWRkaW5nLWxlZnQ6IDEuNXJlbSAhaW1wb3J0YW50OyB9XG4gIC5wLWxnLTUge1xuICAgIHBhZGRpbmc6IDNyZW0gIWltcG9ydGFudDsgfVxuICAucHQtbGctNSxcbiAgLnB5LWxnLTUge1xuICAgIHBhZGRpbmctdG9wOiAzcmVtICFpbXBvcnRhbnQ7IH1cbiAgLnByLWxnLTUsXG4gIC5weC1sZy01IHtcbiAgICBwYWRkaW5nLXJpZ2h0OiAzcmVtICFpbXBvcnRhbnQ7IH1cbiAgLnBiLWxnLTUsXG4gIC5weS1sZy01IHtcbiAgICBwYWRkaW5nLWJvdHRvbTogM3JlbSAhaW1wb3J0YW50OyB9XG4gIC5wbC1sZy01LFxuICAucHgtbGctNSB7XG4gICAgcGFkZGluZy1sZWZ0OiAzcmVtICFpbXBvcnRhbnQ7IH1cbiAgLm0tbGctYXV0byB7XG4gICAgbWFyZ2luOiBhdXRvICFpbXBvcnRhbnQ7IH1cbiAgLm10LWxnLWF1dG8sXG4gIC5teS1sZy1hdXRvIHtcbiAgICBtYXJnaW4tdG9wOiBhdXRvICFpbXBvcnRhbnQ7IH1cbiAgLm1yLWxnLWF1dG8sXG4gIC5teC1sZy1hdXRvIHtcbiAgICBtYXJnaW4tcmlnaHQ6IGF1dG8gIWltcG9ydGFudDsgfVxuICAubWItbGctYXV0byxcbiAgLm15LWxnLWF1dG8ge1xuICAgIG1hcmdpbi1ib3R0b206IGF1dG8gIWltcG9ydGFudDsgfVxuICAubWwtbGctYXV0byxcbiAgLm14LWxnLWF1dG8ge1xuICAgIG1hcmdpbi1sZWZ0OiBhdXRvICFpbXBvcnRhbnQ7IH0gfVxuXG5AbWVkaWEgKG1pbi13aWR0aDogMTIwMHB4KSB7XG4gIC5tLXhsLTAge1xuICAgIG1hcmdpbjogMCAhaW1wb3J0YW50OyB9XG4gIC5tdC14bC0wLFxuICAubXkteGwtMCB7XG4gICAgbWFyZ2luLXRvcDogMCAhaW1wb3J0YW50OyB9XG4gIC5tci14bC0wLFxuICAubXgteGwtMCB7XG4gICAgbWFyZ2luLXJpZ2h0OiAwICFpbXBvcnRhbnQ7IH1cbiAgLm1iLXhsLTAsXG4gIC5teS14bC0wIHtcbiAgICBtYXJnaW4tYm90dG9tOiAwICFpbXBvcnRhbnQ7IH1cbiAgLm1sLXhsLTAsXG4gIC5teC14bC0wIHtcbiAgICBtYXJnaW4tbGVmdDogMCAhaW1wb3J0YW50OyB9XG4gIC5tLXhsLTEge1xuICAgIG1hcmdpbjogMC4yNXJlbSAhaW1wb3J0YW50OyB9XG4gIC5tdC14bC0xLFxuICAubXkteGwtMSB7XG4gICAgbWFyZ2luLXRvcDogMC4yNXJlbSAhaW1wb3J0YW50OyB9XG4gIC5tci14bC0xLFxuICAubXgteGwtMSB7XG4gICAgbWFyZ2luLXJpZ2h0OiAwLjI1cmVtICFpbXBvcnRhbnQ7IH1cbiAgLm1iLXhsLTEsXG4gIC5teS14bC0xIHtcbiAgICBtYXJnaW4tYm90dG9tOiAwLjI1cmVtICFpbXBvcnRhbnQ7IH1cbiAgLm1sLXhsLTEsXG4gIC5teC14bC0xIHtcbiAgICBtYXJnaW4tbGVmdDogMC4yNXJlbSAhaW1wb3J0YW50OyB9XG4gIC5tLXhsLTIge1xuICAgIG1hcmdpbjogMC41cmVtICFpbXBvcnRhbnQ7IH1cbiAgLm10LXhsLTIsXG4gIC5teS14bC0yIHtcbiAgICBtYXJnaW4tdG9wOiAwLjVyZW0gIWltcG9ydGFudDsgfVxuICAubXIteGwtMixcbiAgLm14LXhsLTIge1xuICAgIG1hcmdpbi1yaWdodDogMC41cmVtICFpbXBvcnRhbnQ7IH1cbiAgLm1iLXhsLTIsXG4gIC5teS14bC0yIHtcbiAgICBtYXJnaW4tYm90dG9tOiAwLjVyZW0gIWltcG9ydGFudDsgfVxuICAubWwteGwtMixcbiAgLm14LXhsLTIge1xuICAgIG1hcmdpbi1sZWZ0OiAwLjVyZW0gIWltcG9ydGFudDsgfVxuICAubS14bC0zIHtcbiAgICBtYXJnaW46IDFyZW0gIWltcG9ydGFudDsgfVxuICAubXQteGwtMyxcbiAgLm15LXhsLTMge1xuICAgIG1hcmdpbi10b3A6IDFyZW0gIWltcG9ydGFudDsgfVxuICAubXIteGwtMyxcbiAgLm14LXhsLTMge1xuICAgIG1hcmdpbi1yaWdodDogMXJlbSAhaW1wb3J0YW50OyB9XG4gIC5tYi14bC0zLFxuICAubXkteGwtMyB7XG4gICAgbWFyZ2luLWJvdHRvbTogMXJlbSAhaW1wb3J0YW50OyB9XG4gIC5tbC14bC0zLFxuICAubXgteGwtMyB7XG4gICAgbWFyZ2luLWxlZnQ6IDFyZW0gIWltcG9ydGFudDsgfVxuICAubS14bC00IHtcbiAgICBtYXJnaW46IDEuNXJlbSAhaW1wb3J0YW50OyB9XG4gIC5tdC14bC00LFxuICAubXkteGwtNCB7XG4gICAgbWFyZ2luLXRvcDogMS41cmVtICFpbXBvcnRhbnQ7IH1cbiAgLm1yLXhsLTQsXG4gIC5teC14bC00IHtcbiAgICBtYXJnaW4tcmlnaHQ6IDEuNXJlbSAhaW1wb3J0YW50OyB9XG4gIC5tYi14bC00LFxuICAubXkteGwtNCB7XG4gICAgbWFyZ2luLWJvdHRvbTogMS41cmVtICFpbXBvcnRhbnQ7IH1cbiAgLm1sLXhsLTQsXG4gIC5teC14bC00IHtcbiAgICBtYXJnaW4tbGVmdDogMS41cmVtICFpbXBvcnRhbnQ7IH1cbiAgLm0teGwtNSB7XG4gICAgbWFyZ2luOiAzcmVtICFpbXBvcnRhbnQ7IH1cbiAgLm10LXhsLTUsXG4gIC5teS14bC01IHtcbiAgICBtYXJnaW4tdG9wOiAzcmVtICFpbXBvcnRhbnQ7IH1cbiAgLm1yLXhsLTUsXG4gIC5teC14bC01IHtcbiAgICBtYXJnaW4tcmlnaHQ6IDNyZW0gIWltcG9ydGFudDsgfVxuICAubWIteGwtNSxcbiAgLm15LXhsLTUge1xuICAgIG1hcmdpbi1ib3R0b206IDNyZW0gIWltcG9ydGFudDsgfVxuICAubWwteGwtNSxcbiAgLm14LXhsLTUge1xuICAgIG1hcmdpbi1sZWZ0OiAzcmVtICFpbXBvcnRhbnQ7IH1cbiAgLnAteGwtMCB7XG4gICAgcGFkZGluZzogMCAhaW1wb3J0YW50OyB9XG4gIC5wdC14bC0wLFxuICAucHkteGwtMCB7XG4gICAgcGFkZGluZy10b3A6IDAgIWltcG9ydGFudDsgfVxuICAucHIteGwtMCxcbiAgLnB4LXhsLTAge1xuICAgIHBhZGRpbmctcmlnaHQ6IDAgIWltcG9ydGFudDsgfVxuICAucGIteGwtMCxcbiAgLnB5LXhsLTAge1xuICAgIHBhZGRpbmctYm90dG9tOiAwICFpbXBvcnRhbnQ7IH1cbiAgLnBsLXhsLTAsXG4gIC5weC14bC0wIHtcbiAgICBwYWRkaW5nLWxlZnQ6IDAgIWltcG9ydGFudDsgfVxuICAucC14bC0xIHtcbiAgICBwYWRkaW5nOiAwLjI1cmVtICFpbXBvcnRhbnQ7IH1cbiAgLnB0LXhsLTEsXG4gIC5weS14bC0xIHtcbiAgICBwYWRkaW5nLXRvcDogMC4yNXJlbSAhaW1wb3J0YW50OyB9XG4gIC5wci14bC0xLFxuICAucHgteGwtMSB7XG4gICAgcGFkZGluZy1yaWdodDogMC4yNXJlbSAhaW1wb3J0YW50OyB9XG4gIC5wYi14bC0xLFxuICAucHkteGwtMSB7XG4gICAgcGFkZGluZy1ib3R0b206IDAuMjVyZW0gIWltcG9ydGFudDsgfVxuICAucGwteGwtMSxcbiAgLnB4LXhsLTEge1xuICAgIHBhZGRpbmctbGVmdDogMC4yNXJlbSAhaW1wb3J0YW50OyB9XG4gIC5wLXhsLTIge1xuICAgIHBhZGRpbmc6IDAuNXJlbSAhaW1wb3J0YW50OyB9XG4gIC5wdC14bC0yLFxuICAucHkteGwtMiB7XG4gICAgcGFkZGluZy10b3A6IDAuNXJlbSAhaW1wb3J0YW50OyB9XG4gIC5wci14bC0yLFxuICAucHgteGwtMiB7XG4gICAgcGFkZGluZy1yaWdodDogMC41cmVtICFpbXBvcnRhbnQ7IH1cbiAgLnBiLXhsLTIsXG4gIC5weS14bC0yIHtcbiAgICBwYWRkaW5nLWJvdHRvbTogMC41cmVtICFpbXBvcnRhbnQ7IH1cbiAgLnBsLXhsLTIsXG4gIC5weC14bC0yIHtcbiAgICBwYWRkaW5nLWxlZnQ6IDAuNXJlbSAhaW1wb3J0YW50OyB9XG4gIC5wLXhsLTMge1xuICAgIHBhZGRpbmc6IDFyZW0gIWltcG9ydGFudDsgfVxuICAucHQteGwtMyxcbiAgLnB5LXhsLTMge1xuICAgIHBhZGRpbmctdG9wOiAxcmVtICFpbXBvcnRhbnQ7IH1cbiAgLnByLXhsLTMsXG4gIC5weC14bC0zIHtcbiAgICBwYWRkaW5nLXJpZ2h0OiAxcmVtICFpbXBvcnRhbnQ7IH1cbiAgLnBiLXhsLTMsXG4gIC5weS14bC0zIHtcbiAgICBwYWRkaW5nLWJvdHRvbTogMXJlbSAhaW1wb3J0YW50OyB9XG4gIC5wbC14bC0zLFxuICAucHgteGwtMyB7XG4gICAgcGFkZGluZy1sZWZ0OiAxcmVtICFpbXBvcnRhbnQ7IH1cbiAgLnAteGwtNCB7XG4gICAgcGFkZGluZzogMS41cmVtICFpbXBvcnRhbnQ7IH1cbiAgLnB0LXhsLTQsXG4gIC5weS14bC00IHtcbiAgICBwYWRkaW5nLXRvcDogMS41cmVtICFpbXBvcnRhbnQ7IH1cbiAgLnByLXhsLTQsXG4gIC5weC14bC00IHtcbiAgICBwYWRkaW5nLXJpZ2h0OiAxLjVyZW0gIWltcG9ydGFudDsgfVxuICAucGIteGwtNCxcbiAgLnB5LXhsLTQge1xuICAgIHBhZGRpbmctYm90dG9tOiAxLjVyZW0gIWltcG9ydGFudDsgfVxuICAucGwteGwtNCxcbiAgLnB4LXhsLTQge1xuICAgIHBhZGRpbmctbGVmdDogMS41cmVtICFpbXBvcnRhbnQ7IH1cbiAgLnAteGwtNSB7XG4gICAgcGFkZGluZzogM3JlbSAhaW1wb3J0YW50OyB9XG4gIC5wdC14bC01LFxuICAucHkteGwtNSB7XG4gICAgcGFkZGluZy10b3A6IDNyZW0gIWltcG9ydGFudDsgfVxuICAucHIteGwtNSxcbiAgLnB4LXhsLTUge1xuICAgIHBhZGRpbmctcmlnaHQ6IDNyZW0gIWltcG9ydGFudDsgfVxuICAucGIteGwtNSxcbiAgLnB5LXhsLTUge1xuICAgIHBhZGRpbmctYm90dG9tOiAzcmVtICFpbXBvcnRhbnQ7IH1cbiAgLnBsLXhsLTUsXG4gIC5weC14bC01IHtcbiAgICBwYWRkaW5nLWxlZnQ6IDNyZW0gIWltcG9ydGFudDsgfVxuICAubS14bC1hdXRvIHtcbiAgICBtYXJnaW46IGF1dG8gIWltcG9ydGFudDsgfVxuICAubXQteGwtYXV0byxcbiAgLm15LXhsLWF1dG8ge1xuICAgIG1hcmdpbi10b3A6IGF1dG8gIWltcG9ydGFudDsgfVxuICAubXIteGwtYXV0byxcbiAgLm14LXhsLWF1dG8ge1xuICAgIG1hcmdpbi1yaWdodDogYXV0byAhaW1wb3J0YW50OyB9XG4gIC5tYi14bC1hdXRvLFxuICAubXkteGwtYXV0byB7XG4gICAgbWFyZ2luLWJvdHRvbTogYXV0byAhaW1wb3J0YW50OyB9XG4gIC5tbC14bC1hdXRvLFxuICAubXgteGwtYXV0byB7XG4gICAgbWFyZ2luLWxlZnQ6IGF1dG8gIWltcG9ydGFudDsgfSB9XG5cbi50ZXh0LWp1c3RpZnkge1xuICB0ZXh0LWFsaWduOiBqdXN0aWZ5ICFpbXBvcnRhbnQ7IH1cblxuLnRleHQtbm93cmFwIHtcbiAgd2hpdGUtc3BhY2U6IG5vd3JhcCAhaW1wb3J0YW50OyB9XG5cbi50ZXh0LXRydW5jYXRlIHtcbiAgb3ZlcmZsb3c6IGhpZGRlbjtcbiAgdGV4dC1vdmVyZmxvdzogZWxsaXBzaXM7XG4gIHdoaXRlLXNwYWNlOiBub3dyYXA7IH1cblxuLnRleHQtbGVmdCB7XG4gIHRleHQtYWxpZ246IGxlZnQgIWltcG9ydGFudDsgfVxuXG4udGV4dC1yaWdodCB7XG4gIHRleHQtYWxpZ246IHJpZ2h0ICFpbXBvcnRhbnQ7IH1cblxuLnRleHQtY2VudGVyIHtcbiAgdGV4dC1hbGlnbjogY2VudGVyICFpbXBvcnRhbnQ7IH1cblxuQG1lZGlhIChtaW4td2lkdGg6IDU3NnB4KSB7XG4gIC50ZXh0LXNtLWxlZnQge1xuICAgIHRleHQtYWxpZ246IGxlZnQgIWltcG9ydGFudDsgfVxuICAudGV4dC1zbS1yaWdodCB7XG4gICAgdGV4dC1hbGlnbjogcmlnaHQgIWltcG9ydGFudDsgfVxuICAudGV4dC1zbS1jZW50ZXIge1xuICAgIHRleHQtYWxpZ246IGNlbnRlciAhaW1wb3J0YW50OyB9IH1cblxuQG1lZGlhIChtaW4td2lkdGg6IDc2OHB4KSB7XG4gIC50ZXh0LW1kLWxlZnQge1xuICAgIHRleHQtYWxpZ246IGxlZnQgIWltcG9ydGFudDsgfVxuICAudGV4dC1tZC1yaWdodCB7XG4gICAgdGV4dC1hbGlnbjogcmlnaHQgIWltcG9ydGFudDsgfVxuICAudGV4dC1tZC1jZW50ZXIge1xuICAgIHRleHQtYWxpZ246IGNlbnRlciAhaW1wb3J0YW50OyB9IH1cblxuQG1lZGlhIChtaW4td2lkdGg6IDk5MnB4KSB7XG4gIC50ZXh0LWxnLWxlZnQge1xuICAgIHRleHQtYWxpZ246IGxlZnQgIWltcG9ydGFudDsgfVxuICAudGV4dC1sZy1yaWdodCB7XG4gICAgdGV4dC1hbGlnbjogcmlnaHQgIWltcG9ydGFudDsgfVxuICAudGV4dC1sZy1jZW50ZXIge1xuICAgIHRleHQtYWxpZ246IGNlbnRlciAhaW1wb3J0YW50OyB9IH1cblxuQG1lZGlhIChtaW4td2lkdGg6IDEyMDBweCkge1xuICAudGV4dC14bC1sZWZ0IHtcbiAgICB0ZXh0LWFsaWduOiBsZWZ0ICFpbXBvcnRhbnQ7IH1cbiAgLnRleHQteGwtcmlnaHQge1xuICAgIHRleHQtYWxpZ246IHJpZ2h0ICFpbXBvcnRhbnQ7IH1cbiAgLnRleHQteGwtY2VudGVyIHtcbiAgICB0ZXh0LWFsaWduOiBjZW50ZXIgIWltcG9ydGFudDsgfSB9XG5cbi50ZXh0LWxvd2VyY2FzZSB7XG4gIHRleHQtdHJhbnNmb3JtOiBsb3dlcmNhc2UgIWltcG9ydGFudDsgfVxuXG4udGV4dC11cHBlcmNhc2Uge1xuICB0ZXh0LXRyYW5zZm9ybTogdXBwZXJjYXNlICFpbXBvcnRhbnQ7IH1cblxuLnRleHQtY2FwaXRhbGl6ZSB7XG4gIHRleHQtdHJhbnNmb3JtOiBjYXBpdGFsaXplICFpbXBvcnRhbnQ7IH1cblxuLmZvbnQtd2VpZ2h0LWxpZ2h0IHtcbiAgZm9udC13ZWlnaHQ6IDMwMCAhaW1wb3J0YW50OyB9XG5cbi5mb250LXdlaWdodC1ub3JtYWwge1xuICBmb250LXdlaWdodDogbm9ybWFsICFpbXBvcnRhbnQ7IH1cblxuLmZvbnQtd2VpZ2h0LWJvbGQge1xuICBmb250LXdlaWdodDogYm9sZCAhaW1wb3J0YW50OyB9XG5cbi5mb250LWl0YWxpYyB7XG4gIGZvbnQtc3R5bGU6IGl0YWxpYyAhaW1wb3J0YW50OyB9XG5cbi50ZXh0LXdoaXRlIHtcbiAgY29sb3I6ICNmZmYgIWltcG9ydGFudDsgfVxuXG4udGV4dC1wcmltYXJ5IHtcbiAgY29sb3I6ICMwMDdiZmYgIWltcG9ydGFudDsgfVxuXG5hLnRleHQtcHJpbWFyeTpmb2N1cywgYS50ZXh0LXByaW1hcnk6aG92ZXIge1xuICBjb2xvcjogIzAwNjJjYyAhaW1wb3J0YW50OyB9XG5cbi50ZXh0LXNlY29uZGFyeSB7XG4gIGNvbG9yOiAjODY4ZTk2ICFpbXBvcnRhbnQ7IH1cblxuYS50ZXh0LXNlY29uZGFyeTpmb2N1cywgYS50ZXh0LXNlY29uZGFyeTpob3ZlciB7XG4gIGNvbG9yOiAjNmM3NTdkICFpbXBvcnRhbnQ7IH1cblxuLnRleHQtc3VjY2VzcyB7XG4gIGNvbG9yOiAjMjhhNzQ1ICFpbXBvcnRhbnQ7IH1cblxuYS50ZXh0LXN1Y2Nlc3M6Zm9jdXMsIGEudGV4dC1zdWNjZXNzOmhvdmVyIHtcbiAgY29sb3I6ICMxZTdlMzQgIWltcG9ydGFudDsgfVxuXG4udGV4dC1pbmZvIHtcbiAgY29sb3I6ICMxN2EyYjggIWltcG9ydGFudDsgfVxuXG5hLnRleHQtaW5mbzpmb2N1cywgYS50ZXh0LWluZm86aG92ZXIge1xuICBjb2xvcjogIzExN2E4YiAhaW1wb3J0YW50OyB9XG5cbi50ZXh0LXdhcm5pbmcge1xuICBjb2xvcjogI2ZmYzEwNyAhaW1wb3J0YW50OyB9XG5cbmEudGV4dC13YXJuaW5nOmZvY3VzLCBhLnRleHQtd2FybmluZzpob3ZlciB7XG4gIGNvbG9yOiAjZDM5ZTAwICFpbXBvcnRhbnQ7IH1cblxuLnRleHQtZGFuZ2VyIHtcbiAgY29sb3I6ICNkYzM1NDUgIWltcG9ydGFudDsgfVxuXG5hLnRleHQtZGFuZ2VyOmZvY3VzLCBhLnRleHQtZGFuZ2VyOmhvdmVyIHtcbiAgY29sb3I6ICNiZDIxMzAgIWltcG9ydGFudDsgfVxuXG4udGV4dC1saWdodCB7XG4gIGNvbG9yOiAjZjhmOWZhICFpbXBvcnRhbnQ7IH1cblxuYS50ZXh0LWxpZ2h0OmZvY3VzLCBhLnRleHQtbGlnaHQ6aG92ZXIge1xuICBjb2xvcjogI2RhZTBlNSAhaW1wb3J0YW50OyB9XG5cbi50ZXh0LWRhcmsge1xuICBjb2xvcjogIzM0M2E0MCAhaW1wb3J0YW50OyB9XG5cbmEudGV4dC1kYXJrOmZvY3VzLCBhLnRleHQtZGFyazpob3ZlciB7XG4gIGNvbG9yOiAjMWQyMTI0ICFpbXBvcnRhbnQ7IH1cblxuLnRleHQtbXV0ZWQge1xuICBjb2xvcjogIzg2OGU5NiAhaW1wb3J0YW50OyB9XG5cbi50ZXh0LWhpZGUge1xuICBmb250OiAwLzAgYTtcbiAgY29sb3I6IHRyYW5zcGFyZW50O1xuICB0ZXh0LXNoYWRvdzogbm9uZTtcbiAgYmFja2dyb3VuZC1jb2xvcjogdHJhbnNwYXJlbnQ7XG4gIGJvcmRlcjogMDsgfVxuXG4udmlzaWJsZSB7XG4gIHZpc2liaWxpdHk6IHZpc2libGUgIWltcG9ydGFudDsgfVxuXG4uaW52aXNpYmxlIHtcbiAgdmlzaWJpbGl0eTogaGlkZGVuICFpbXBvcnRhbnQ7IH1cblxuLyogVkFSSUFWRUlTICovXG4vKlxuICogU0laRVxuICovXG4vKlxuICogQ09MT1JcbiAqL1xuLyogQ09SRVMgKi9cbi5jb2xvcl9fbGltZSB7XG4gIGNvbG9yOiAjOWRkZDYxOyB9XG5cbi5jb2xvcl9fcGluayB7XG4gIGNvbG9yOiAjZjkyYjZkOyB9XG5cbi5jb2xvcl9fbGlnaHRncmV5IHtcbiAgY29sb3I6ICNFOEU4RTc7IH1cblxuLyogQk9UQU8gKi9cbmJ1dHRvbi5jdXN0b20ge1xuICBiYWNrZ3JvdW5kLWNvbG9yOiB0cmFuc3BhcmVudDtcbiAgYm9yZGVyOiAycHggc29saWQgI2Y5MmI2ZDtcbiAgcGFkZGluZzogLjRlbTtcbiAgY29sb3I6ICNmOTJiNmQ7XG4gIGZvbnQtc2l6ZTogaW5oZXJpdDtcbiAgY3Vyc29yOiBwb2ludGVyO1xuICB0cmFuc2l0aW9uOiBjb2xvciAuNXMsIGJvcmRlci1jb2xvciAuNXM7IH1cbiAgYnV0dG9uLmN1c3RvbTpob3ZlciB7XG4gICAgY29sb3I6IHJlZDtcbiAgICBib3JkZXItY29sb3I6IHJlZDsgfVxuICBidXR0b24uY3VzdG9tIC5pY29uIHtcbiAgICBoZWlnaHQ6IDFlbTtcbiAgICB3aWR0aDogMWVtOyB9XG4gICAgYnV0dG9uLmN1c3RvbSAuaWNvbiAqIHtcbiAgICAgIHN0cm9rZTogI2Y5MmI2ZDtcbiAgICAgIGZpbGw6ICNmOTJiNmQ7IH1cbiAgYnV0dG9uLmN1c3RvbSBbcm9sZT1cImxhYmVsXCJdIHtcbiAgICBtYXJnaW4tbGVmdDogLjVlbTsgfVxuXG4vKiBCT1RBTyAqL1xuLmNhcmQge1xuICBib3gtc2hhZG93OiAwIDAgMjBweCAwcHggcmdiYSgwLCAwLCAwLCAwLjA1KTtcbiAgYm9yZGVyOiBub25lO1xuICBmbGV4LWJhc2lzOiAyMCU7XG4gIGJvcmRlci1yYWRpdXM6IC40ZW07XG4gIHBhZGRpbmc6IDFlbTtcbiAgZm9udC1zaXplOiAyMHB4O1xuICBmb250LXdlaWdodDogNTAwO1xuICBwb3NpdGlvbjogcmVsYXRpdmU7IH1cbiAgLmNhcmQgPiAqIHtcbiAgICBtYXJnaW46IC4yZW07IH1cbiAgLmNhcmQgaDEge1xuICAgIHBvc2l0aW9uOiByZWxhdGl2ZTtcbiAgICBmb250LXNpemU6IC43ZW07IH1cbiAgICAuY2FyZCBoMSAuaWNvbiB7XG4gICAgICBwb3NpdGlvbjogYWJzb2x1dGU7XG4gICAgICByaWdodDogMDtcbiAgICAgIGhlaWdodDogMWVtO1xuICAgICAgd2lkdGg6IDJlbTsgfVxuICAgICAgLmNhcmQgaDEgLmljb24gPiAqIHtcbiAgICAgICAgZmlsbDogI0U4RThFNzsgfVxuICAuY2FyZCBwIHtcbiAgICBmb250LXNpemU6IDEuMmVtO1xuICAgIGxldHRlci1zcGFjaW5nOiAuMWVtOyB9XG4gICAgLmNhcmQgcCBzcGFuIHtcbiAgICAgIGZvbnQtc2l6ZTogLjhlbTtcbiAgICAgIGZvbnQtd2VpZ2h0OiA0MDA7IH1cblxuLm1hcmNhY2FvIHtcbiAgYm9yZGVyOiAxcHggc29saWQgYmxhY2s7IH1cblxuLmRlbGltaXRhZG9yLCAuZGVsLXJpZ2h0LCAuZGVsLWxlZnQsIC5kZWwtYm90dG9tIHtcbiAgYm9yZGVyLWNvbG9yOiAjRThFOEU3O1xuICBib3JkZXItd2lkdGg6IDA7XG4gIGJvcmRlci1zdHlsZTogc29saWQ7IH1cblxuLmRlbC1yaWdodCB7XG4gIGJvcmRlci1yaWdodC13aWR0aDogMXB4OyB9XG5cbi5kZWwtbGVmdCB7XG4gIGJvcmRlci1sZWZ0LXdpZHRoOiAxcHg7IH1cblxuLmRlbC1ib3R0b20ge1xuICBib3JkZXItYm90dG9tLXdpZHRoOiAxcHg7IH1cblxuLndoaXRlYmcsIGFzaWRlLmxlZnQsIGhlYWRlci5tYWluLCBhc2lkZS5yaWdodCB7XG4gIGJhY2tncm91bmQtY29sb3I6IHdoaXRlOyB9XG5cbmJvZHkge1xuICBiYWNrZ3JvdW5kLWNvbG9yOiAjZmFmN2Y2OyB9XG5cbnN2Zy5pY29uLnRleHQge1xuICBoZWlnaHQ6IDFlbTtcbiAgd2lkdGg6IDFlbTsgfVxuXG5hc2lkZS5sZWZ0IHtcbiAgd2lkdGg6IDEyMHB4OyB9XG4gIGFzaWRlLmxlZnQgI2xvZ28ge1xuICAgIHBhZGRpbmc6IDIwcHg7XG4gICAgd2lkdGg6IDEyMHB4O1xuICAgIGhlaWdodDogMTIwcHg7IH1cbiAgICBhc2lkZS5sZWZ0ICNsb2dvID4gc3ZnIHtcbiAgICAgIHdpZHRoOiA4MHB4O1xuICAgICAgaGVpZ2h0OiA4MHB4OyB9XG4gIGFzaWRlLmxlZnQgbmF2IHtcbiAgICBwb3NpdGlvbjogcmVsYXRpdmU7IH1cbiAgICBhc2lkZS5sZWZ0IG5hdjpiZWZvcmUge1xuICAgICAgY29udGVudDogJyc7XG4gICAgICBkaXNwbGF5OiBibG9jaztcbiAgICAgIHBvc2l0aW9uOiBhYnNvbHV0ZTtcbiAgICAgIGJhY2tncm91bmQtY29sb3I6ICNmOTJiNmQ7XG4gICAgICB3aWR0aDogOHB4O1xuICAgICAgbGVmdDogLTIwcHg7XG4gICAgICB0b3A6IC04MHB4O1xuICAgICAgdHJhbnNpdGlvbjogbGVmdCwgLjVzLCB0b3AgLjVzO1xuICAgICAgYm94LXNoYWRvdzogMHB4IDFweCA5cHggM3B4IHJnYmEoMCwgMCwgMCwgMC40Mik7XG4gICAgICBib3JkZXItcmFkaXVzOiAxMDAlO1xuICAgICAgaGVpZ2h0OiA0MHB4OyB9XG4gICAgYXNpZGUubGVmdCBuYXYuY3Vyc29yOmJlZm9yZSB7XG4gICAgICBsZWZ0OiAtNHB4OyB9XG4gICAgYXNpZGUubGVmdCBuYXYuaXRlbS0xOmJlZm9yZSB7XG4gICAgICB0b3A6IDQwcHg7IH1cbiAgICBhc2lkZS5sZWZ0IG5hdi5pdGVtLTI6YmVmb3JlIHtcbiAgICAgIHRvcDogMTYwcHg7IH1cbiAgICBhc2lkZS5sZWZ0IG5hdi5pdGVtLTM6YmVmb3JlIHtcbiAgICAgIHRvcDogMjgwcHg7IH1cbiAgICBhc2lkZS5sZWZ0IG5hdi5pdGVtLTQ6YmVmb3JlIHtcbiAgICAgIHRvcDogNDAwcHg7IH1cbiAgICBhc2lkZS5sZWZ0IG5hdi5pdGVtLTU6YmVmb3JlIHtcbiAgICAgIHRvcDogNTIwcHg7IH1cbiAgICBhc2lkZS5sZWZ0IG5hdi5pdGVtLTY6YmVmb3JlIHtcbiAgICAgIHRvcDogNjQwcHg7IH1cbiAgICBhc2lkZS5sZWZ0IG5hdi5pdGVtLTc6YmVmb3JlIHtcbiAgICAgIHRvcDogNzYwcHg7IH1cbiAgICBhc2lkZS5sZWZ0IG5hdi5pdGVtLTg6YmVmb3JlIHtcbiAgICAgIHRvcDogODgwcHg7IH1cbiAgICBhc2lkZS5sZWZ0IG5hdi5pdGVtLTk6YmVmb3JlIHtcbiAgICAgIHRvcDogMTAwMHB4OyB9XG4gICAgYXNpZGUubGVmdCBuYXYuaXRlbS0xMDpiZWZvcmUge1xuICAgICAgdG9wOiAxMTIwcHg7IH1cbiAgICBhc2lkZS5sZWZ0IG5hdiA+IGRpdi5pdGVtIHtcbiAgICAgIHdpZHRoOiAxMjBweDtcbiAgICAgIGxpbmUtaGVpZ2h0OiAxMjBweDtcbiAgICAgIHRleHQtYWxpZ246IGNlbnRlcjtcbiAgICAgIGhlaWdodDogMTIwcHg7XG4gICAgICB0ZXh0LWFsaWduOiBjZW50ZXI7XG4gICAgICBsaW5lLWhlaWdodDogMTIwcHg7XG4gICAgICBwb3NpdGlvbjogcmVsYXRpdmU7IH1cbiAgICAgIGFzaWRlLmxlZnQgbmF2ID4gZGl2Lml0ZW0gYSB7XG4gICAgICAgIHBvc2l0aW9uOiBhYnNvbHV0ZTtcbiAgICAgICAgd2lkdGg6IDQwJTtcbiAgICAgICAgaGVpZ2h0OiA0MCU7IH1cbiAgICAgIGFzaWRlLmxlZnQgbmF2ID4gZGl2Lml0ZW0gLmljb24ge1xuICAgICAgICBjdXJzb3I6IHBvaW50ZXI7XG4gICAgICAgIHN0cm9rZTogI2Y5MmI2ZDtcbiAgICAgICAgZmlsbDogI2Y5MmI2ZDtcbiAgICAgICAgd2lkdGg6IDQwJTtcbiAgICAgICAgaGVpZ2h0OiA0MCU7XG4gICAgICAgIG1hcmdpbjogYXV0bztcbiAgICAgICAgdHJhbnNpdGlvbjogZmlsbCAuNXM7IH1cbiAgICAgICAgYXNpZGUubGVmdCBuYXYgPiBkaXYuaXRlbSAuaWNvbjpob3ZlciB7XG4gICAgICAgICAgZmlsbDogcmVkOyB9XG5cbiNiZXNpZGUge1xuICBmbGV4OiAxIDEgYXV0bzsgfVxuXG5oZWFkZXIubWFpbiB7XG4gIGZvbnQtc2l6ZTogMzBweDtcbiAgY29sb3I6IHJnYmEoMTQyLCAxNDIsIDE0MiwgMC40KTtcbiAgaGVpZ2h0OiAxMjBweDsgfVxuICBoZWFkZXIubWFpbiA+IC5pY29uIHtcbiAgICBtYXJnaW4tbGVmdDogMmVtO1xuICAgIG1hcmdpbi1yaWdodDogMWVtO1xuICAgIGhlaWdodDogNjBweDtcbiAgICB3aWR0aDogNjBweDtcbiAgICBmbGV4OiAwIDEgYXV0bzsgfVxuICAgIGhlYWRlci5tYWluID4gLmljb24gKiB7XG4gICAgICBzdHJva2U6IHJnYmEoMTQyLCAxNDIsIDE0MiwgMC40KTtcbiAgICAgIGZpbGw6IHJnYmEoMTQyLCAxNDIsIDE0MiwgMC40KTsgfVxuICBoZWFkZXIubWFpbiA+IGgxIHtcbiAgICBmbGV4OiAxIDEgYXV0bztcbiAgICBmb250LXdlaWdodDogNDAwO1xuICAgIGZvbnQtc2l6ZTogaW5oZXJpdDsgfVxuXG4jdXNlci1hY2NvdW50IHtcbiAgZmxleDogMCAwIDI4OHB4O1xuICBmb250LXNpemU6IDE1cHg7XG4gIGhlaWdodDogMTAwJTtcbiAgcGFkZGluZzogMCAzZW07IH1cbiAgI3VzZXItYWNjb3VudCA+IC5hdmF0YXIge1xuICAgIGJvcmRlci1yYWRpdXM6IDEwMCU7XG4gICAgaGVpZ2h0OiA3MnB4O1xuICAgIHdpZHRoOiA3MnB4O1xuICAgIGJhY2tncm91bmQtcmVwZWF0OiBuby1yZXBlYXQ7XG4gICAgYmFja2dyb3VuZC1wb3NpdGlvbjogY2VudGVyO1xuICAgIGJhY2tncm91bmQtc2l6ZTogY292ZXI7IH1cblxuYXNpZGUucmlnaHQge1xuICBwYWRkaW5nOiAzZW07XG4gIGZvbnQtc2l6ZTogMTZweDtcbiAgZmxleDogMCAwIDI4OHB4OyB9XG4gIGFzaWRlLnJpZ2h0IGhlYWRlciB7XG4gICAgbWFyZ2luLWJvdHRvbTogNGVtOyB9XG4gICAgYXNpZGUucmlnaHQgaGVhZGVyIGgyIHtcbiAgICAgIGZvbnQtc2l6ZTogMS42ZW07IH1cbiAgICBhc2lkZS5yaWdodCBoZWFkZXIgaDMge1xuICAgICAgZm9udC1zaXplOiAxLjJlbTtcbiAgICAgIGNvbG9yOiByZ2JhKDE0MiwgMTQyLCAxNDIsIDAuNCk7IH1cbiAgYXNpZGUucmlnaHQgLnNpZGViYXItc3VtbWFyeS1pdGVtIHtcbiAgICBtYXJnaW4tYm90dG9tOiAyZW07IH1cbiAgICBhc2lkZS5yaWdodCAuc2lkZWJhci1zdW1tYXJ5LWl0ZW06YmVmb3JlIHtcbiAgICAgIGNvbnRlbnQ6ICcnO1xuICAgICAgZGlzcGxheTogYmxvY2s7XG4gICAgICB3aWR0aDogMTAwJTtcbiAgICAgIGhlaWdodDogNXB4O1xuICAgICAgYmFja2dyb3VuZC1jb2xvcjogI2Y5MmI2ZDtcbiAgICAgIG1hcmdpbi1ib3R0b206IC41ZW07IH1cbiAgICBhc2lkZS5yaWdodCAuc2lkZWJhci1zdW1tYXJ5LWl0ZW0gaDQge1xuICAgICAgZm9udC1zaXplOiAuOGVtO1xuICAgICAgY29sb3I6IHJnYmEoMTQyLCAxNDIsIDE0MiwgMC40KTsgfVxuICAgIGFzaWRlLnJpZ2h0IC5zaWRlYmFyLXN1bW1hcnktaXRlbSBwIHtcbiAgICAgIG1hcmdpbjogMDtcbiAgICAgIHBhZGRpbmc6IDA7IH1cbiAgICBhc2lkZS5yaWdodCAuc2lkZWJhci1zdW1tYXJ5LWl0ZW0gYSB7XG4gICAgICBjb2xvcjogI2Y5MmI2ZDtcbiAgICAgIGZvbnQtc2l6ZTogLjhlbTsgfVxuICAgICAgYXNpZGUucmlnaHQgLnNpZGViYXItc3VtbWFyeS1pdGVtIGEgLmljb24gKiB7XG4gICAgICAgIHN0cm9rZTogI2Y5MmI2ZDtcbiAgICAgICAgZmlsbDogI2Y5MmI2ZDsgfVxuXG4jY29udGVudCB7XG4gIGZsZXg6IDEgMSAxMDAlO1xuICBwYWRkaW5nOiAzZW07IH1cbiIsIkBtaXhpbiBob3ZlciB7XG4gIC8vIFRPRE86IHJlLWVuYWJsZSBhbG9uZyB3aXRoIG1xNC1ob3Zlci1zaGltXG4vLyAgQGlmICRlbmFibGUtaG92ZXItbWVkaWEtcXVlcnkge1xuLy8gICAgLy8gU2VlIE1lZGlhIFF1ZXJpZXMgTGV2ZWwgNDogaHR0cHM6Ly9kcmFmdHMuY3Nzd2cub3JnL21lZGlhcXVlcmllcy8jaG92ZXJcbi8vICAgIC8vIEN1cnJlbnRseSBzaGltbWVkIGJ5IGh0dHBzOi8vZ2l0aHViLmNvbS90d2JzL21xNC1ob3Zlci1zaGltXG4vLyAgICBAbWVkaWEgKGhvdmVyOiBob3Zlcikge1xuLy8gICAgICAmOmhvdmVyIHsgQGNvbnRlbnQgfVxuLy8gICAgfVxuLy8gIH1cbi8vICBAZWxzZSB7XG4vLyBzY3NzLWxpbnQ6ZGlzYWJsZSBJbmRlbnRhdGlvblxuICAgICY6aG92ZXIgeyBAY29udGVudCB9XG4vLyBzY3NzLWxpbnQ6ZW5hYmxlIEluZGVudGF0aW9uXG4vLyAgfVxufVxuXG5cbkBtaXhpbiBob3Zlci1mb2N1cyB7XG4gIEBpZiAkZW5hYmxlLWhvdmVyLW1lZGlhLXF1ZXJ5IHtcbiAgICAmOmZvY3VzIHsgQGNvbnRlbnQgfVxuICAgIEBpbmNsdWRlIGhvdmVyIHsgQGNvbnRlbnQgfVxuICB9IEBlbHNlIHtcbiAgICAmOmZvY3VzLFxuICAgICY6aG92ZXIge1xuICAgICAgQGNvbnRlbnRcbiAgICB9XG4gIH1cbn1cblxuQG1peGluIHBsYWluLWhvdmVyLWZvY3VzIHtcbiAgQGlmICRlbmFibGUtaG92ZXItbWVkaWEtcXVlcnkge1xuICAgICYsXG4gICAgJjpmb2N1cyB7XG4gICAgICBAY29udGVudFxuICAgIH1cbiAgICBAaW5jbHVkZSBob3ZlciB7IEBjb250ZW50IH1cbiAgfSBAZWxzZSB7XG4gICAgJixcbiAgICAmOmZvY3VzLFxuICAgICY6aG92ZXIge1xuICAgICAgQGNvbnRlbnRcbiAgICB9XG4gIH1cbn1cblxuQG1peGluIGhvdmVyLWZvY3VzLWFjdGl2ZSB7XG4gIEBpZiAkZW5hYmxlLWhvdmVyLW1lZGlhLXF1ZXJ5IHtcbiAgICAmOmZvY3VzLFxuICAgICY6YWN0aXZlIHtcbiAgICAgIEBjb250ZW50XG4gICAgfVxuICAgIEBpbmNsdWRlIGhvdmVyIHsgQGNvbnRlbnQgfVxuICB9IEBlbHNlIHtcbiAgICAmOmZvY3VzLFxuICAgICY6YWN0aXZlLFxuICAgICY6aG92ZXIge1xuICAgICAgQGNvbnRlbnRcbiAgICB9XG4gIH1cbn1cbiIsIi8vXG4vLyBIZWFkaW5nc1xuLy9cblxuaDEsIGgyLCBoMywgaDQsIGg1LCBoNixcbi5oMSwgLmgyLCAuaDMsIC5oNCwgLmg1LCAuaDYge1xuICBtYXJnaW4tYm90dG9tOiAkaGVhZGluZ3MtbWFyZ2luLWJvdHRvbTtcbiAgZm9udC1mYW1pbHk6ICRoZWFkaW5ncy1mb250LWZhbWlseTtcbiAgZm9udC13ZWlnaHQ6ICRoZWFkaW5ncy1mb250LXdlaWdodDtcbiAgbGluZS1oZWlnaHQ6ICRoZWFkaW5ncy1saW5lLWhlaWdodDtcbiAgY29sb3I6ICRoZWFkaW5ncy1jb2xvcjtcbn1cblxuaDEsIC5oMSB7IGZvbnQtc2l6ZTogJGgxLWZvbnQtc2l6ZTsgfVxuaDIsIC5oMiB7IGZvbnQtc2l6ZTogJGgyLWZvbnQtc2l6ZTsgfVxuaDMsIC5oMyB7IGZvbnQtc2l6ZTogJGgzLWZvbnQtc2l6ZTsgfVxuaDQsIC5oNCB7IGZvbnQtc2l6ZTogJGg0LWZvbnQtc2l6ZTsgfVxuaDUsIC5oNSB7IGZvbnQtc2l6ZTogJGg1LWZvbnQtc2l6ZTsgfVxuaDYsIC5oNiB7IGZvbnQtc2l6ZTogJGg2LWZvbnQtc2l6ZTsgfVxuXG4ubGVhZCB7XG4gIGZvbnQtc2l6ZTogJGxlYWQtZm9udC1zaXplO1xuICBmb250LXdlaWdodDogJGxlYWQtZm9udC13ZWlnaHQ7XG59XG5cbi8vIFR5cGUgZGlzcGxheSBjbGFzc2VzXG4uZGlzcGxheS0xIHtcbiAgZm9udC1zaXplOiAkZGlzcGxheTEtc2l6ZTtcbiAgZm9udC13ZWlnaHQ6ICRkaXNwbGF5MS13ZWlnaHQ7XG4gIGxpbmUtaGVpZ2h0OiAkZGlzcGxheS1saW5lLWhlaWdodDtcbn1cbi5kaXNwbGF5LTIge1xuICBmb250LXNpemU6ICRkaXNwbGF5Mi1zaXplO1xuICBmb250LXdlaWdodDogJGRpc3BsYXkyLXdlaWdodDtcbiAgbGluZS1oZWlnaHQ6ICRkaXNwbGF5LWxpbmUtaGVpZ2h0O1xufVxuLmRpc3BsYXktMyB7XG4gIGZvbnQtc2l6ZTogJGRpc3BsYXkzLXNpemU7XG4gIGZvbnQtd2VpZ2h0OiAkZGlzcGxheTMtd2VpZ2h0O1xuICBsaW5lLWhlaWdodDogJGRpc3BsYXktbGluZS1oZWlnaHQ7XG59XG4uZGlzcGxheS00IHtcbiAgZm9udC1zaXplOiAkZGlzcGxheTQtc2l6ZTtcbiAgZm9udC13ZWlnaHQ6ICRkaXNwbGF5NC13ZWlnaHQ7XG4gIGxpbmUtaGVpZ2h0OiAkZGlzcGxheS1saW5lLWhlaWdodDtcbn1cblxuXG4vL1xuLy8gSG9yaXpvbnRhbCBydWxlc1xuLy9cblxuaHIge1xuICBtYXJnaW4tdG9wOiAxcmVtO1xuICBtYXJnaW4tYm90dG9tOiAxcmVtO1xuICBib3JkZXI6IDA7XG4gIGJvcmRlci10b3A6ICRoci1ib3JkZXItd2lkdGggc29saWQgJGhyLWJvcmRlci1jb2xvcjtcbn1cblxuXG4vL1xuLy8gRW1waGFzaXNcbi8vXG5cbnNtYWxsLFxuLnNtYWxsIHtcbiAgZm9udC1zaXplOiAkc21hbGwtZm9udC1zaXplO1xuICBmb250LXdlaWdodDogJGZvbnQtd2VpZ2h0LW5vcm1hbDtcbn1cblxubWFyayxcbi5tYXJrIHtcbiAgcGFkZGluZzogJG1hcmstcGFkZGluZztcbiAgYmFja2dyb3VuZC1jb2xvcjogJG1hcmstYmc7XG59XG5cblxuLy9cbi8vIExpc3RzXG4vL1xuXG4ubGlzdC11bnN0eWxlZCB7XG4gIEBpbmNsdWRlIGxpc3QtdW5zdHlsZWQ7XG59XG5cbi8vIElubGluZSB0dXJucyBsaXN0IGl0ZW1zIGludG8gaW5saW5lLWJsb2NrXG4ubGlzdC1pbmxpbmUge1xuICBAaW5jbHVkZSBsaXN0LXVuc3R5bGVkO1xufVxuLmxpc3QtaW5saW5lLWl0ZW0ge1xuICBkaXNwbGF5OiBpbmxpbmUtYmxvY2s7XG5cbiAgJjpub3QoOmxhc3QtY2hpbGQpIHtcbiAgICBtYXJnaW4tcmlnaHQ6ICRsaXN0LWlubGluZS1wYWRkaW5nO1xuICB9XG59XG5cblxuLy9cbi8vIE1pc2Ncbi8vXG5cbi8vIEJ1aWxkcyBvbiBgYWJicmBcbi5pbml0aWFsaXNtIHtcbiAgZm9udC1zaXplOiA5MCU7XG4gIHRleHQtdHJhbnNmb3JtOiB1cHBlcmNhc2U7XG59XG5cbi8vIEJsb2NrcXVvdGVzXG4uYmxvY2txdW90ZSB7XG4gIG1hcmdpbi1ib3R0b206ICRzcGFjZXI7XG4gIGZvbnQtc2l6ZTogJGJsb2NrcXVvdGUtZm9udC1zaXplO1xufVxuXG4uYmxvY2txdW90ZS1mb290ZXIge1xuICBkaXNwbGF5OiBibG9jaztcbiAgZm9udC1zaXplOiA4MCU7IC8vIGJhY2sgdG8gZGVmYXVsdCBmb250LXNpemVcbiAgY29sb3I6ICRibG9ja3F1b3RlLXNtYWxsLWNvbG9yO1xuXG4gICY6OmJlZm9yZSB7XG4gICAgY29udGVudDogXCJcXDIwMTQgXFwwMEEwXCI7IC8vIGVtIGRhc2gsIG5ic3BcbiAgfVxufVxuIiwiLy8gTGlzdHNcblxuLy8gVW5zdHlsZWQga2VlcHMgbGlzdCBpdGVtcyBibG9jayBsZXZlbCwganVzdCByZW1vdmVzIGRlZmF1bHQgYnJvd3NlciBwYWRkaW5nIGFuZCBsaXN0LXN0eWxlXG5AbWl4aW4gbGlzdC11bnN0eWxlZCB7XG4gIHBhZGRpbmctbGVmdDogMDtcbiAgbGlzdC1zdHlsZTogbm9uZTtcbn1cbiIsIi8vIFJlc3BvbnNpdmUgaW1hZ2VzIChlbnN1cmUgaW1hZ2VzIGRvbid0IHNjYWxlIGJleW9uZCB0aGVpciBwYXJlbnRzKVxuLy9cbi8vIFRoaXMgaXMgcHVycG9zZWZ1bGx5IG9wdC1pbiB2aWEgYW4gZXhwbGljaXQgY2xhc3MgcmF0aGVyIHRoYW4gYmVpbmcgdGhlIGRlZmF1bHQgZm9yIGFsbCBgPGltZz5gcy5cbi8vIFdlIHByZXZpb3VzbHkgdHJpZWQgdGhlIFwiaW1hZ2VzIGFyZSByZXNwb25zaXZlIGJ5IGRlZmF1bHRcIiBhcHByb2FjaCBpbiBCb290c3RyYXAgdjIsXG4vLyBhbmQgYWJhbmRvbmVkIGl0IGluIEJvb3RzdHJhcCB2MyBiZWNhdXNlIGl0IGJyZWFrcyBsb3RzIG9mIHRoaXJkLXBhcnR5IHdpZGdldHMgKGluY2x1ZGluZyBHb29nbGUgTWFwcylcbi8vIHdoaWNoIHdlcmVuJ3QgZXhwZWN0aW5nIHRoZSBpbWFnZXMgd2l0aGluIHRoZW1zZWx2ZXMgdG8gYmUgaW52b2x1bnRhcmlseSByZXNpemVkLlxuLy8gU2VlIGFsc28gaHR0cHM6Ly9naXRodWIuY29tL3R3YnMvYm9vdHN0cmFwL2lzc3Vlcy8xODE3OFxuLmltZy1mbHVpZCB7XG4gIEBpbmNsdWRlIGltZy1mbHVpZDtcbn1cblxuXG4vLyBJbWFnZSB0aHVtYm5haWxzXG4uaW1nLXRodW1ibmFpbCB7XG4gIHBhZGRpbmc6ICR0aHVtYm5haWwtcGFkZGluZztcbiAgYmFja2dyb3VuZC1jb2xvcjogJHRodW1ibmFpbC1iZztcbiAgYm9yZGVyOiAkdGh1bWJuYWlsLWJvcmRlci13aWR0aCBzb2xpZCAkdGh1bWJuYWlsLWJvcmRlci1jb2xvcjtcbiAgQGluY2x1ZGUgYm9yZGVyLXJhZGl1cygkdGh1bWJuYWlsLWJvcmRlci1yYWRpdXMpO1xuICBAaW5jbHVkZSB0cmFuc2l0aW9uKCR0aHVtYm5haWwtdHJhbnNpdGlvbik7XG4gIEBpbmNsdWRlIGJveC1zaGFkb3coJHRodW1ibmFpbC1ib3gtc2hhZG93KTtcblxuICAvLyBLZWVwIHRoZW0gYXQgbW9zdCAxMDAlIHdpZGVcbiAgQGluY2x1ZGUgaW1nLWZsdWlkO1xufVxuXG4vL1xuLy8gRmlndXJlc1xuLy9cblxuLmZpZ3VyZSB7XG4gIC8vIEVuc3VyZXMgdGhlIGNhcHRpb24ncyB0ZXh0IGFsaWducyB3aXRoIHRoZSBpbWFnZS5cbiAgZGlzcGxheTogaW5saW5lLWJsb2NrO1xufVxuXG4uZmlndXJlLWltZyB7XG4gIG1hcmdpbi1ib3R0b206ICgkc3BhY2VyIC8gMik7XG4gIGxpbmUtaGVpZ2h0OiAxO1xufVxuXG4uZmlndXJlLWNhcHRpb24ge1xuICBmb250LXNpemU6ICRmaWd1cmUtY2FwdGlvbi1mb250LXNpemU7XG4gIGNvbG9yOiAkZmlndXJlLWNhcHRpb24tY29sb3I7XG59XG4iLCIvLyBJbWFnZSBNaXhpbnNcbi8vIC0gUmVzcG9uc2l2ZSBpbWFnZVxuLy8gLSBSZXRpbmEgaW1hZ2VcblxuXG4vLyBSZXNwb25zaXZlIGltYWdlXG4vL1xuLy8gS2VlcCBpbWFnZXMgZnJvbSBzY2FsaW5nIGJleW9uZCB0aGUgd2lkdGggb2YgdGhlaXIgcGFyZW50cy5cblxuQG1peGluIGltZy1mbHVpZCB7XG4gIC8vIFBhcnQgMTogU2V0IGEgbWF4aW11bSByZWxhdGl2ZSB0byB0aGUgcGFyZW50XG4gIG1heC13aWR0aDogMTAwJTtcbiAgLy8gUGFydCAyOiBPdmVycmlkZSB0aGUgaGVpZ2h0IHRvIGF1dG8sIG90aGVyd2lzZSBpbWFnZXMgd2lsbCBiZSBzdHJldGNoZWRcbiAgLy8gd2hlbiBzZXR0aW5nIGEgd2lkdGggYW5kIGhlaWdodCBhdHRyaWJ1dGUgb24gdGhlIGltZyBlbGVtZW50LlxuICBoZWlnaHQ6IGF1dG87XG59XG5cblxuLy8gUmV0aW5hIGltYWdlXG4vL1xuLy8gU2hvcnQgcmV0aW5hIG1peGluIGZvciBzZXR0aW5nIGJhY2tncm91bmQtaW1hZ2UgYW5kIC1zaXplLlxuXG5AbWl4aW4gaW1nLXJldGluYSgkZmlsZS0xeCwgJGZpbGUtMngsICR3aWR0aC0xeCwgJGhlaWdodC0xeCkge1xuICBiYWNrZ3JvdW5kLWltYWdlOiB1cmwoJGZpbGUtMXgpO1xuXG4gIC8vIEF1dG9wcmVmaXhlciB0YWtlcyBjYXJlIG9mIGFkZGluZyAtd2Via2l0LW1pbi1kZXZpY2UtcGl4ZWwtcmF0aW8gYW5kIC1vLW1pbi1kZXZpY2UtcGl4ZWwtcmF0aW8sXG4gIC8vIGJ1dCBkb2Vzbid0IGNvbnZlcnQgZHBweD0+ZHBpLlxuICAvLyBUaGVyZSdzIG5vIHN1Y2ggdGhpbmcgYXMgdW5wcmVmaXhlZCBtaW4tZGV2aWNlLXBpeGVsLXJhdGlvIHNpbmNlIGl0J3Mgbm9uc3RhbmRhcmQuXG4gIC8vIENvbXBhdGliaWxpdHkgaW5mbzogaHR0cDovL2Nhbml1c2UuY29tLyNmZWF0PWNzcy1tZWRpYS1yZXNvbHV0aW9uXG4gIEBtZWRpYVxuICBvbmx5IHNjcmVlbiBhbmQgKG1pbi1yZXNvbHV0aW9uOiAxOTJkcGkpLCAvLyBJRTktMTEgZG9uJ3Qgc3VwcG9ydCBkcHB4XG4gIG9ubHkgc2NyZWVuIGFuZCAobWluLXJlc29sdXRpb246IDJkcHB4KSB7IC8vIFN0YW5kYXJkaXplZFxuICAgIGJhY2tncm91bmQtaW1hZ2U6IHVybCgkZmlsZS0yeCk7XG4gICAgYmFja2dyb3VuZC1zaXplOiAkd2lkdGgtMXggJGhlaWdodC0xeDtcbiAgfVxufVxuIiwiLy8gU2luZ2xlIHNpZGUgYm9yZGVyLXJhZGl1c1xuXG5AbWl4aW4gYm9yZGVyLXJhZGl1cygkcmFkaXVzOiAkYm9yZGVyLXJhZGl1cykge1xuICBAaWYgJGVuYWJsZS1yb3VuZGVkIHtcbiAgICBib3JkZXItcmFkaXVzOiAkcmFkaXVzO1xuICB9XG59XG5cbkBtaXhpbiBib3JkZXItdG9wLXJhZGl1cygkcmFkaXVzKSB7XG4gIEBpZiAkZW5hYmxlLXJvdW5kZWQge1xuICAgIGJvcmRlci10b3AtbGVmdC1yYWRpdXM6ICRyYWRpdXM7XG4gICAgYm9yZGVyLXRvcC1yaWdodC1yYWRpdXM6ICRyYWRpdXM7XG4gIH1cbn1cblxuQG1peGluIGJvcmRlci1yaWdodC1yYWRpdXMoJHJhZGl1cykge1xuICBAaWYgJGVuYWJsZS1yb3VuZGVkIHtcbiAgICBib3JkZXItdG9wLXJpZ2h0LXJhZGl1czogJHJhZGl1cztcbiAgICBib3JkZXItYm90dG9tLXJpZ2h0LXJhZGl1czogJHJhZGl1cztcbiAgfVxufVxuXG5AbWl4aW4gYm9yZGVyLWJvdHRvbS1yYWRpdXMoJHJhZGl1cykge1xuICBAaWYgJGVuYWJsZS1yb3VuZGVkIHtcbiAgICBib3JkZXItYm90dG9tLXJpZ2h0LXJhZGl1czogJHJhZGl1cztcbiAgICBib3JkZXItYm90dG9tLWxlZnQtcmFkaXVzOiAkcmFkaXVzO1xuICB9XG59XG5cbkBtaXhpbiBib3JkZXItbGVmdC1yYWRpdXMoJHJhZGl1cykge1xuICBAaWYgJGVuYWJsZS1yb3VuZGVkIHtcbiAgICBib3JkZXItdG9wLWxlZnQtcmFkaXVzOiAkcmFkaXVzO1xuICAgIGJvcmRlci1ib3R0b20tbGVmdC1yYWRpdXM6ICRyYWRpdXM7XG4gIH1cbn1cbiIsIkBtaXhpbiB0cmFuc2l0aW9uKCR0cmFuc2l0aW9uLi4uKSB7XG4gIEBpZiAkZW5hYmxlLXRyYW5zaXRpb25zIHtcbiAgICBAaWYgbGVuZ3RoKCR0cmFuc2l0aW9uKSA9PSAwIHtcbiAgICAgIHRyYW5zaXRpb246ICR0cmFuc2l0aW9uLWJhc2U7XG4gICAgfSBAZWxzZSB7XG4gICAgICB0cmFuc2l0aW9uOiAkdHJhbnNpdGlvbjtcbiAgICB9XG4gIH1cbn1cbiIsIi8vIElubGluZSBhbmQgYmxvY2sgY29kZSBzdHlsZXNcbmNvZGUsXG5rYmQsXG5wcmUsXG5zYW1wIHtcbiAgZm9udC1mYW1pbHk6ICRmb250LWZhbWlseS1tb25vc3BhY2U7XG59XG5cbi8vIElubGluZSBjb2RlXG5jb2RlIHtcbiAgcGFkZGluZzogJGNvZGUtcGFkZGluZy15ICRjb2RlLXBhZGRpbmcteDtcbiAgZm9udC1zaXplOiAkY29kZS1mb250LXNpemU7XG4gIGNvbG9yOiAkY29kZS1jb2xvcjtcbiAgYmFja2dyb3VuZC1jb2xvcjogJGNvZGUtYmc7XG4gIEBpbmNsdWRlIGJvcmRlci1yYWRpdXMoJGJvcmRlci1yYWRpdXMpO1xuXG4gIC8vIFN0cmVhbWxpbmUgdGhlIHN0eWxlIHdoZW4gaW5zaWRlIGFuY2hvcnMgdG8gYXZvaWQgYnJva2VuIHVuZGVybGluZSBhbmQgbW9yZVxuICBhID4gJiB7XG4gICAgcGFkZGluZzogMDtcbiAgICBjb2xvcjogaW5oZXJpdDtcbiAgICBiYWNrZ3JvdW5kLWNvbG9yOiBpbmhlcml0O1xuICB9XG59XG5cbi8vIFVzZXIgaW5wdXQgdHlwaWNhbGx5IGVudGVyZWQgdmlhIGtleWJvYXJkXG5rYmQge1xuICBwYWRkaW5nOiAkY29kZS1wYWRkaW5nLXkgJGNvZGUtcGFkZGluZy14O1xuICBmb250LXNpemU6ICRjb2RlLWZvbnQtc2l6ZTtcbiAgY29sb3I6ICRrYmQtY29sb3I7XG4gIGJhY2tncm91bmQtY29sb3I6ICRrYmQtYmc7XG4gIEBpbmNsdWRlIGJvcmRlci1yYWRpdXMoJGJvcmRlci1yYWRpdXMtc20pO1xuICBAaW5jbHVkZSBib3gtc2hhZG93KCRrYmQtYm94LXNoYWRvdyk7XG5cbiAga2JkIHtcbiAgICBwYWRkaW5nOiAwO1xuICAgIGZvbnQtc2l6ZTogMTAwJTtcbiAgICBmb250LXdlaWdodDogJG5lc3RlZC1rYmQtZm9udC13ZWlnaHQ7XG4gICAgQGluY2x1ZGUgYm94LXNoYWRvdyhub25lKTtcbiAgfVxufVxuXG4vLyBCbG9ja3Mgb2YgY29kZVxucHJlIHtcbiAgZGlzcGxheTogYmxvY2s7XG4gIG1hcmdpbi10b3A6IDA7XG4gIG1hcmdpbi1ib3R0b206IDFyZW07XG4gIGZvbnQtc2l6ZTogJGNvZGUtZm9udC1zaXplO1xuICBjb2xvcjogJHByZS1jb2xvcjtcblxuICAvLyBBY2NvdW50IGZvciBzb21lIGNvZGUgb3V0cHV0cyB0aGF0IHBsYWNlIGNvZGUgdGFncyBpbiBwcmUgdGFnc1xuICBjb2RlIHtcbiAgICBwYWRkaW5nOiAwO1xuICAgIGZvbnQtc2l6ZTogaW5oZXJpdDtcbiAgICBjb2xvcjogaW5oZXJpdDtcbiAgICBiYWNrZ3JvdW5kLWNvbG9yOiB0cmFuc3BhcmVudDtcbiAgICBib3JkZXItcmFkaXVzOiAwO1xuICB9XG59XG5cbi8vIEVuYWJsZSBzY3JvbGxhYmxlIGJsb2NrcyBvZiBjb2RlXG4ucHJlLXNjcm9sbGFibGUge1xuICBtYXgtaGVpZ2h0OiAkcHJlLXNjcm9sbGFibGUtbWF4LWhlaWdodDtcbiAgb3ZlcmZsb3cteTogc2Nyb2xsO1xufVxuIiwiLy8gQ29udGFpbmVyIHdpZHRoc1xuLy9cbi8vIFNldCB0aGUgY29udGFpbmVyIHdpZHRoLCBhbmQgb3ZlcnJpZGUgaXQgZm9yIGZpeGVkIG5hdmJhcnMgaW4gbWVkaWEgcXVlcmllcy5cblxuQGlmICRlbmFibGUtZ3JpZC1jbGFzc2VzIHtcbiAgLmNvbnRhaW5lciB7XG4gICAgQGluY2x1ZGUgbWFrZS1jb250YWluZXIoKTtcbiAgICBAaW5jbHVkZSBtYWtlLWNvbnRhaW5lci1tYXgtd2lkdGhzKCk7XG4gIH1cbn1cblxuLy8gRmx1aWQgY29udGFpbmVyXG4vL1xuLy8gVXRpbGl6ZXMgdGhlIG1peGluIG1lYW50IGZvciBmaXhlZCB3aWR0aCBjb250YWluZXJzLCBidXQgd2l0aCAxMDAlIHdpZHRoIGZvclxuLy8gZmx1aWQsIGZ1bGwgd2lkdGggbGF5b3V0cy5cblxuQGlmICRlbmFibGUtZ3JpZC1jbGFzc2VzIHtcbiAgLmNvbnRhaW5lci1mbHVpZCB7XG4gICAgd2lkdGg6IDEwMCU7XG4gICAgQGluY2x1ZGUgbWFrZS1jb250YWluZXIoKTtcbiAgfVxufVxuXG4vLyBSb3dcbi8vXG4vLyBSb3dzIGNvbnRhaW4gYW5kIGNsZWFyIHRoZSBmbG9hdHMgb2YgeW91ciBjb2x1bW5zLlxuXG5AaWYgJGVuYWJsZS1ncmlkLWNsYXNzZXMge1xuICAucm93IHtcbiAgICBAaW5jbHVkZSBtYWtlLXJvdygpO1xuICB9XG5cbiAgLy8gUmVtb3ZlIHRoZSBuZWdhdGl2ZSBtYXJnaW4gZnJvbSBkZWZhdWx0IC5yb3csIHRoZW4gdGhlIGhvcml6b250YWwgcGFkZGluZ1xuICAvLyBmcm9tIGFsbCBpbW1lZGlhdGUgY2hpbGRyZW4gY29sdW1ucyAodG8gcHJldmVudCBydW5hd2F5IHN0eWxlIGluaGVyaXRhbmNlKS5cbiAgLm5vLWd1dHRlcnMge1xuICAgIG1hcmdpbi1yaWdodDogMDtcbiAgICBtYXJnaW4tbGVmdDogMDtcblxuICAgID4gLmNvbCxcbiAgICA+IFtjbGFzcyo9XCJjb2wtXCJdIHtcbiAgICAgIHBhZGRpbmctcmlnaHQ6IDA7XG4gICAgICBwYWRkaW5nLWxlZnQ6IDA7XG4gICAgfVxuICB9XG59XG5cbi8vIENvbHVtbnNcbi8vXG4vLyBDb21tb24gc3R5bGVzIGZvciBzbWFsbCBhbmQgbGFyZ2UgZ3JpZCBjb2x1bW5zXG5cbkBpZiAkZW5hYmxlLWdyaWQtY2xhc3NlcyB7XG4gIEBpbmNsdWRlIG1ha2UtZ3JpZC1jb2x1bW5zKCk7XG59XG4iLCIvLy8gR3JpZCBzeXN0ZW1cbi8vXG4vLyBHZW5lcmF0ZSBzZW1hbnRpYyBncmlkIGNvbHVtbnMgd2l0aCB0aGVzZSBtaXhpbnMuXG5cbkBtaXhpbiBtYWtlLWNvbnRhaW5lcigpIHtcbiAgbWFyZ2luLXJpZ2h0OiBhdXRvO1xuICBtYXJnaW4tbGVmdDogYXV0bztcbiAgcGFkZGluZy1yaWdodDogKCRncmlkLWd1dHRlci13aWR0aCAvIDIpO1xuICBwYWRkaW5nLWxlZnQ6ICAoJGdyaWQtZ3V0dGVyLXdpZHRoIC8gMik7XG4gIHdpZHRoOiAxMDAlO1xufVxuXG5cbi8vIEZvciBlYWNoIGJyZWFrcG9pbnQsIGRlZmluZSB0aGUgbWF4aW11bSB3aWR0aCBvZiB0aGUgY29udGFpbmVyIGluIGEgbWVkaWEgcXVlcnlcbkBtaXhpbiBtYWtlLWNvbnRhaW5lci1tYXgtd2lkdGhzKCRtYXgtd2lkdGhzOiAkY29udGFpbmVyLW1heC13aWR0aHMsICRicmVha3BvaW50czogJGdyaWQtYnJlYWtwb2ludHMpIHtcbiAgQGVhY2ggJGJyZWFrcG9pbnQsICRjb250YWluZXItbWF4LXdpZHRoIGluICRtYXgtd2lkdGhzIHtcbiAgICBAaW5jbHVkZSBtZWRpYS1icmVha3BvaW50LXVwKCRicmVha3BvaW50LCAkYnJlYWtwb2ludHMpIHtcbiAgICAgIG1heC13aWR0aDogJGNvbnRhaW5lci1tYXgtd2lkdGg7XG4gICAgfVxuICB9XG59XG5cbkBtaXhpbiBtYWtlLXJvdygpIHtcbiAgZGlzcGxheTogZmxleDtcbiAgZmxleC13cmFwOiB3cmFwO1xuICBtYXJnaW4tcmlnaHQ6ICgkZ3JpZC1ndXR0ZXItd2lkdGggLyAtMik7XG4gIG1hcmdpbi1sZWZ0OiAgKCRncmlkLWd1dHRlci13aWR0aCAvIC0yKTtcbn1cblxuQG1peGluIG1ha2UtY29sLXJlYWR5KCkge1xuICBwb3NpdGlvbjogcmVsYXRpdmU7XG4gIC8vIFByZXZlbnQgY29sdW1ucyBmcm9tIGJlY29taW5nIHRvbyBuYXJyb3cgd2hlbiBhdCBzbWFsbGVyIGdyaWQgdGllcnMgYnlcbiAgLy8gYWx3YXlzIHNldHRpbmcgYHdpZHRoOiAxMDAlO2AuIFRoaXMgd29ya3MgYmVjYXVzZSB3ZSB1c2UgYGZsZXhgIHZhbHVlc1xuICAvLyBsYXRlciBvbiB0byBvdmVycmlkZSB0aGlzIGluaXRpYWwgd2lkdGguXG4gIHdpZHRoOiAxMDAlO1xuICBtaW4taGVpZ2h0OiAxcHg7IC8vIFByZXZlbnQgY29sbGFwc2luZ1xuICBwYWRkaW5nLXJpZ2h0OiAoJGdyaWQtZ3V0dGVyLXdpZHRoIC8gMik7XG4gIHBhZGRpbmctbGVmdDogICgkZ3JpZC1ndXR0ZXItd2lkdGggLyAyKTtcbn1cblxuQG1peGluIG1ha2UtY29sKCRzaXplLCAkY29sdW1uczogJGdyaWQtY29sdW1ucykge1xuICBmbGV4OiAwIDAgcGVyY2VudGFnZSgkc2l6ZSAvICRjb2x1bW5zKTtcbiAgLy8gQWRkIGEgYG1heC13aWR0aGAgdG8gZW5zdXJlIGNvbnRlbnQgd2l0aGluIGVhY2ggY29sdW1uIGRvZXMgbm90IGJsb3cgb3V0XG4gIC8vIHRoZSB3aWR0aCBvZiB0aGUgY29sdW1uLiBBcHBsaWVzIHRvIElFMTArIGFuZCBGaXJlZm94LiBDaHJvbWUgYW5kIFNhZmFyaVxuICAvLyBkbyBub3QgYXBwZWFyIHRvIHJlcXVpcmUgdGhpcy5cbiAgbWF4LXdpZHRoOiBwZXJjZW50YWdlKCRzaXplIC8gJGNvbHVtbnMpO1xufVxuIiwiLy8gQnJlYWtwb2ludCB2aWV3cG9ydCBzaXplcyBhbmQgbWVkaWEgcXVlcmllcy5cbi8vXG4vLyBCcmVha3BvaW50cyBhcmUgZGVmaW5lZCBhcyBhIG1hcCBvZiAobmFtZTogbWluaW11bSB3aWR0aCksIG9yZGVyIGZyb20gc21hbGwgdG8gbGFyZ2U6XG4vL1xuLy8gICAgKHhzOiAwLCBzbTogNTc2cHgsIG1kOiA3NjhweCwgbGc6IDk5MnB4LCB4bDogMTIwMHB4KVxuLy9cbi8vIFRoZSBtYXAgZGVmaW5lZCBpbiB0aGUgYCRncmlkLWJyZWFrcG9pbnRzYCBnbG9iYWwgdmFyaWFibGUgaXMgdXNlZCBhcyB0aGUgYCRicmVha3BvaW50c2AgYXJndW1lbnQgYnkgZGVmYXVsdC5cblxuLy8gTmFtZSBvZiB0aGUgbmV4dCBicmVha3BvaW50LCBvciBudWxsIGZvciB0aGUgbGFzdCBicmVha3BvaW50LlxuLy9cbi8vICAgID4+IGJyZWFrcG9pbnQtbmV4dChzbSlcbi8vICAgIG1kXG4vLyAgICA+PiBicmVha3BvaW50LW5leHQoc20sICh4czogMCwgc206IDU3NnB4LCBtZDogNzY4cHgsIGxnOiA5OTJweCwgeGw6IDEyMDBweCkpXG4vLyAgICBtZFxuLy8gICAgPj4gYnJlYWtwb2ludC1uZXh0KHNtLCAkYnJlYWtwb2ludC1uYW1lczogKHhzIHNtIG1kIGxnIHhsKSlcbi8vICAgIG1kXG5AZnVuY3Rpb24gYnJlYWtwb2ludC1uZXh0KCRuYW1lLCAkYnJlYWtwb2ludHM6ICRncmlkLWJyZWFrcG9pbnRzLCAkYnJlYWtwb2ludC1uYW1lczogbWFwLWtleXMoJGJyZWFrcG9pbnRzKSkge1xuICAkbjogaW5kZXgoJGJyZWFrcG9pbnQtbmFtZXMsICRuYW1lKTtcbiAgQHJldHVybiBpZigkbiA8IGxlbmd0aCgkYnJlYWtwb2ludC1uYW1lcyksIG50aCgkYnJlYWtwb2ludC1uYW1lcywgJG4gKyAxKSwgbnVsbCk7XG59XG5cbi8vIE1pbmltdW0gYnJlYWtwb2ludCB3aWR0aC4gTnVsbCBmb3IgdGhlIHNtYWxsZXN0IChmaXJzdCkgYnJlYWtwb2ludC5cbi8vXG4vLyAgICA+PiBicmVha3BvaW50LW1pbihzbSwgKHhzOiAwLCBzbTogNTc2cHgsIG1kOiA3NjhweCwgbGc6IDk5MnB4LCB4bDogMTIwMHB4KSlcbi8vICAgIDU3NnB4XG5AZnVuY3Rpb24gYnJlYWtwb2ludC1taW4oJG5hbWUsICRicmVha3BvaW50czogJGdyaWQtYnJlYWtwb2ludHMpIHtcbiAgJG1pbjogbWFwLWdldCgkYnJlYWtwb2ludHMsICRuYW1lKTtcbiAgQHJldHVybiBpZigkbWluICE9IDAsICRtaW4sIG51bGwpO1xufVxuXG4vLyBNYXhpbXVtIGJyZWFrcG9pbnQgd2lkdGguIE51bGwgZm9yIHRoZSBsYXJnZXN0IChsYXN0KSBicmVha3BvaW50LlxuLy8gVGhlIG1heGltdW0gdmFsdWUgaXMgY2FsY3VsYXRlZCBhcyB0aGUgbWluaW11bSBvZiB0aGUgbmV4dCBvbmUgbGVzcyAwLjEuXG4vL1xuLy8gICAgPj4gYnJlYWtwb2ludC1tYXgoc20sICh4czogMCwgc206IDU3NnB4LCBtZDogNzY4cHgsIGxnOiA5OTJweCwgeGw6IDEyMDBweCkpXG4vLyAgICA3NjdweFxuQGZ1bmN0aW9uIGJyZWFrcG9pbnQtbWF4KCRuYW1lLCAkYnJlYWtwb2ludHM6ICRncmlkLWJyZWFrcG9pbnRzKSB7XG4gICRuZXh0OiBicmVha3BvaW50LW5leHQoJG5hbWUsICRicmVha3BvaW50cyk7XG4gIEByZXR1cm4gaWYoJG5leHQsIGJyZWFrcG9pbnQtbWluKCRuZXh0LCAkYnJlYWtwb2ludHMpIC0gMXB4LCBudWxsKTtcbn1cblxuLy8gUmV0dXJucyBhIGJsYW5rIHN0cmluZyBpZiBzbWFsbGVzdCBicmVha3BvaW50LCBvdGhlcndpc2UgcmV0dXJucyB0aGUgbmFtZSB3aXRoIGEgZGFzaCBpbmZyb250LlxuLy8gVXNlZnVsIGZvciBtYWtpbmcgcmVzcG9uc2l2ZSB1dGlsaXRpZXMuXG4vL1xuLy8gICAgPj4gYnJlYWtwb2ludC1pbmZpeCh4cywgKHhzOiAwLCBzbTogNTc2cHgsIG1kOiA3NjhweCwgbGc6IDk5MnB4LCB4bDogMTIwMHB4KSlcbi8vICAgIFwiXCIgIChSZXR1cm5zIGEgYmxhbmsgc3RyaW5nKVxuLy8gICAgPj4gYnJlYWtwb2ludC1pbmZpeChzbSwgKHhzOiAwLCBzbTogNTc2cHgsIG1kOiA3NjhweCwgbGc6IDk5MnB4LCB4bDogMTIwMHB4KSlcbi8vICAgIFwiLXNtXCJcbkBmdW5jdGlvbiBicmVha3BvaW50LWluZml4KCRuYW1lLCAkYnJlYWtwb2ludHM6ICRncmlkLWJyZWFrcG9pbnRzKSB7XG4gIEByZXR1cm4gaWYoYnJlYWtwb2ludC1taW4oJG5hbWUsICRicmVha3BvaW50cykgPT0gbnVsbCwgXCJcIiwgXCItI3skbmFtZX1cIik7XG59XG5cbi8vIE1lZGlhIG9mIGF0IGxlYXN0IHRoZSBtaW5pbXVtIGJyZWFrcG9pbnQgd2lkdGguIE5vIHF1ZXJ5IGZvciB0aGUgc21hbGxlc3QgYnJlYWtwb2ludC5cbi8vIE1ha2VzIHRoZSBAY29udGVudCBhcHBseSB0byB0aGUgZ2l2ZW4gYnJlYWtwb2ludCBhbmQgd2lkZXIuXG5AbWl4aW4gbWVkaWEtYnJlYWtwb2ludC11cCgkbmFtZSwgJGJyZWFrcG9pbnRzOiAkZ3JpZC1icmVha3BvaW50cykge1xuICAkbWluOiBicmVha3BvaW50LW1pbigkbmFtZSwgJGJyZWFrcG9pbnRzKTtcbiAgQGlmICRtaW4ge1xuICAgIEBtZWRpYSAobWluLXdpZHRoOiAkbWluKSB7XG4gICAgICBAY29udGVudDtcbiAgICB9XG4gIH0gQGVsc2Uge1xuICAgIEBjb250ZW50O1xuICB9XG59XG5cbi8vIE1lZGlhIG9mIGF0IG1vc3QgdGhlIG1heGltdW0gYnJlYWtwb2ludCB3aWR0aC4gTm8gcXVlcnkgZm9yIHRoZSBsYXJnZXN0IGJyZWFrcG9pbnQuXG4vLyBNYWtlcyB0aGUgQGNvbnRlbnQgYXBwbHkgdG8gdGhlIGdpdmVuIGJyZWFrcG9pbnQgYW5kIG5hcnJvd2VyLlxuQG1peGluIG1lZGlhLWJyZWFrcG9pbnQtZG93bigkbmFtZSwgJGJyZWFrcG9pbnRzOiAkZ3JpZC1icmVha3BvaW50cykge1xuICAkbWF4OiBicmVha3BvaW50LW1heCgkbmFtZSwgJGJyZWFrcG9pbnRzKTtcbiAgQGlmICRtYXgge1xuICAgIEBtZWRpYSAobWF4LXdpZHRoOiAkbWF4KSB7XG4gICAgICBAY29udGVudDtcbiAgICB9XG4gIH0gQGVsc2Uge1xuICAgIEBjb250ZW50O1xuICB9XG59XG5cbi8vIE1lZGlhIHRoYXQgc3BhbnMgbXVsdGlwbGUgYnJlYWtwb2ludCB3aWR0aHMuXG4vLyBNYWtlcyB0aGUgQGNvbnRlbnQgYXBwbHkgYmV0d2VlbiB0aGUgbWluIGFuZCBtYXggYnJlYWtwb2ludHNcbkBtaXhpbiBtZWRpYS1icmVha3BvaW50LWJldHdlZW4oJGxvd2VyLCAkdXBwZXIsICRicmVha3BvaW50czogJGdyaWQtYnJlYWtwb2ludHMpIHtcbiAgJG1pbjogYnJlYWtwb2ludC1taW4oJGxvd2VyLCAkYnJlYWtwb2ludHMpO1xuICAkbWF4OiBicmVha3BvaW50LW1heCgkdXBwZXIsICRicmVha3BvaW50cyk7XG5cbiAgQG1lZGlhIChtaW4td2lkdGg6ICRtaW4pIGFuZCAobWF4LXdpZHRoOiAkbWF4KSB7XG4gICAgQGNvbnRlbnQ7XG4gIH1cbn1cblxuLy8gTWVkaWEgYmV0d2VlbiB0aGUgYnJlYWtwb2ludCdzIG1pbmltdW0gYW5kIG1heGltdW0gd2lkdGhzLlxuLy8gTm8gbWluaW11bSBmb3IgdGhlIHNtYWxsZXN0IGJyZWFrcG9pbnQsIGFuZCBubyBtYXhpbXVtIGZvciB0aGUgbGFyZ2VzdCBvbmUuXG4vLyBNYWtlcyB0aGUgQGNvbnRlbnQgYXBwbHkgb25seSB0byB0aGUgZ2l2ZW4gYnJlYWtwb2ludCwgbm90IHZpZXdwb3J0cyBhbnkgd2lkZXIgb3IgbmFycm93ZXIuXG5AbWl4aW4gbWVkaWEtYnJlYWtwb2ludC1vbmx5KCRuYW1lLCAkYnJlYWtwb2ludHM6ICRncmlkLWJyZWFrcG9pbnRzKSB7XG4gICRtaW46IGJyZWFrcG9pbnQtbWluKCRuYW1lLCAkYnJlYWtwb2ludHMpO1xuICAkbWF4OiBicmVha3BvaW50LW1heCgkbmFtZSwgJGJyZWFrcG9pbnRzKTtcblxuICBAaWYgJG1pbiAhPSBudWxsIGFuZCAkbWF4ICE9IG51bGwge1xuICAgIEBtZWRpYSAobWluLXdpZHRoOiAkbWluKSBhbmQgKG1heC13aWR0aDogJG1heCkge1xuICAgICAgQGNvbnRlbnQ7XG4gICAgfVxuICB9IEBlbHNlIGlmICRtYXggPT0gbnVsbCB7XG4gICAgQGluY2x1ZGUgbWVkaWEtYnJlYWtwb2ludC11cCgkbmFtZSlcbiAgfSBAZWxzZSBpZiAkbWluID09IG51bGwge1xuICAgIEBpbmNsdWRlIG1lZGlhLWJyZWFrcG9pbnQtZG93bigkbmFtZSlcbiAgfVxufVxuIiwiLy8gRnJhbWV3b3JrIGdyaWQgZ2VuZXJhdGlvblxuLy9cbi8vIFVzZWQgb25seSBieSBCb290c3RyYXAgdG8gZ2VuZXJhdGUgdGhlIGNvcnJlY3QgbnVtYmVyIG9mIGdyaWQgY2xhc3NlcyBnaXZlblxuLy8gYW55IHZhbHVlIG9mIGAkZ3JpZC1jb2x1bW5zYC5cblxuQG1peGluIG1ha2UtZ3JpZC1jb2x1bW5zKCRjb2x1bW5zOiAkZ3JpZC1jb2x1bW5zLCAkZ3V0dGVyOiAkZ3JpZC1ndXR0ZXItd2lkdGgsICRicmVha3BvaW50czogJGdyaWQtYnJlYWtwb2ludHMpIHtcbiAgLy8gQ29tbW9uIHByb3BlcnRpZXMgZm9yIGFsbCBicmVha3BvaW50c1xuICAlZ3JpZC1jb2x1bW4ge1xuICAgIHBvc2l0aW9uOiByZWxhdGl2ZTtcbiAgICB3aWR0aDogMTAwJTtcbiAgICBtaW4taGVpZ2h0OiAxcHg7IC8vIFByZXZlbnQgY29sdW1ucyBmcm9tIGNvbGxhcHNpbmcgd2hlbiBlbXB0eVxuICAgIHBhZGRpbmctcmlnaHQ6ICgkZ3V0dGVyIC8gMik7XG4gICAgcGFkZGluZy1sZWZ0OiAgKCRndXR0ZXIgLyAyKTtcbiAgfVxuXG4gIEBlYWNoICRicmVha3BvaW50IGluIG1hcC1rZXlzKCRicmVha3BvaW50cykge1xuICAgICRpbmZpeDogYnJlYWtwb2ludC1pbmZpeCgkYnJlYWtwb2ludCwgJGJyZWFrcG9pbnRzKTtcblxuICAgIC8vIEFsbG93IGNvbHVtbnMgdG8gc3RyZXRjaCBmdWxsIHdpZHRoIGJlbG93IHRoZWlyIGJyZWFrcG9pbnRzXG4gICAgQGZvciAkaSBmcm9tIDEgdGhyb3VnaCAkY29sdW1ucyB7XG4gICAgICAuY29sI3skaW5maXh9LSN7JGl9IHtcbiAgICAgICAgQGV4dGVuZCAlZ3JpZC1jb2x1bW47XG4gICAgICB9XG4gICAgfVxuICAgIC5jb2wjeyRpbmZpeH0sXG4gICAgLmNvbCN7JGluZml4fS1hdXRvIHtcbiAgICAgIEBleHRlbmQgJWdyaWQtY29sdW1uO1xuICAgIH1cblxuICAgIEBpbmNsdWRlIG1lZGlhLWJyZWFrcG9pbnQtdXAoJGJyZWFrcG9pbnQsICRicmVha3BvaW50cykge1xuICAgICAgLy8gUHJvdmlkZSBiYXNpYyBgLmNvbC17YnB9YCBjbGFzc2VzIGZvciBlcXVhbC13aWR0aCBmbGV4Ym94IGNvbHVtbnNcbiAgICAgIC5jb2wjeyRpbmZpeH0ge1xuICAgICAgICBmbGV4LWJhc2lzOiAwO1xuICAgICAgICBmbGV4LWdyb3c6IDE7XG4gICAgICAgIG1heC13aWR0aDogMTAwJTtcbiAgICAgIH1cbiAgICAgIC5jb2wjeyRpbmZpeH0tYXV0byB7XG4gICAgICAgIGZsZXg6IDAgMCBhdXRvO1xuICAgICAgICB3aWR0aDogYXV0bztcbiAgICAgICAgbWF4LXdpZHRoOiBub25lOyAvLyBSZXNldCBlYXJsaWVyIGdyaWQgdGllcnNcbiAgICAgIH1cblxuICAgICAgQGZvciAkaSBmcm9tIDEgdGhyb3VnaCAkY29sdW1ucyB7XG4gICAgICAgIC5jb2wjeyRpbmZpeH0tI3skaX0ge1xuICAgICAgICAgIEBpbmNsdWRlIG1ha2UtY29sKCRpLCAkY29sdW1ucyk7XG4gICAgICAgIH1cbiAgICAgIH1cblxuICAgICAgQGZvciAkaSBmcm9tIDEgdGhyb3VnaCAkY29sdW1ucyB7XG4gICAgICAgIC5vcmRlciN7JGluZml4fS0jeyRpfSB7XG4gICAgICAgICAgb3JkZXI6ICRpO1xuICAgICAgICB9XG4gICAgICB9XG4gICAgfVxuICB9XG59XG4iLCIvL1xuLy8gQmFzaWMgQm9vdHN0cmFwIHRhYmxlXG4vL1xuXG4udGFibGUge1xuICB3aWR0aDogMTAwJTtcbiAgbWF4LXdpZHRoOiAxMDAlO1xuICBtYXJnaW4tYm90dG9tOiAkc3BhY2VyO1xuICBiYWNrZ3JvdW5kLWNvbG9yOiAkdGFibGUtYmc7IC8vIFJlc2V0IGZvciBuZXN0aW5nIHdpdGhpbiBwYXJlbnRzIHdpdGggYGJhY2tncm91bmQtY29sb3JgLlxuXG4gIHRoLFxuICB0ZCB7XG4gICAgcGFkZGluZzogJHRhYmxlLWNlbGwtcGFkZGluZztcbiAgICB2ZXJ0aWNhbC1hbGlnbjogdG9wO1xuICAgIGJvcmRlci10b3A6ICR0YWJsZS1ib3JkZXItd2lkdGggc29saWQgJHRhYmxlLWJvcmRlci1jb2xvcjtcbiAgfVxuXG4gIHRoZWFkIHRoIHtcbiAgICB2ZXJ0aWNhbC1hbGlnbjogYm90dG9tO1xuICAgIGJvcmRlci1ib3R0b206ICgyICogJHRhYmxlLWJvcmRlci13aWR0aCkgc29saWQgJHRhYmxlLWJvcmRlci1jb2xvcjtcbiAgfVxuXG4gIHRib2R5ICsgdGJvZHkge1xuICAgIGJvcmRlci10b3A6ICgyICogJHRhYmxlLWJvcmRlci13aWR0aCkgc29saWQgJHRhYmxlLWJvcmRlci1jb2xvcjtcbiAgfVxuXG4gIC50YWJsZSB7XG4gICAgYmFja2dyb3VuZC1jb2xvcjogJGJvZHktYmc7XG4gIH1cbn1cblxuXG4vL1xuLy8gQ29uZGVuc2VkIHRhYmxlIHcvIGhhbGYgcGFkZGluZ1xuLy9cblxuLnRhYmxlLXNtIHtcbiAgdGgsXG4gIHRkIHtcbiAgICBwYWRkaW5nOiAkdGFibGUtY2VsbC1wYWRkaW5nLXNtO1xuICB9XG59XG5cblxuLy8gQm9yZGVyZWQgdmVyc2lvblxuLy9cbi8vIEFkZCBib3JkZXJzIGFsbCBhcm91bmQgdGhlIHRhYmxlIGFuZCBiZXR3ZWVuIGFsbCB0aGUgY29sdW1ucy5cblxuLnRhYmxlLWJvcmRlcmVkIHtcbiAgYm9yZGVyOiAkdGFibGUtYm9yZGVyLXdpZHRoIHNvbGlkICR0YWJsZS1ib3JkZXItY29sb3I7XG5cbiAgdGgsXG4gIHRkIHtcbiAgICBib3JkZXI6ICR0YWJsZS1ib3JkZXItd2lkdGggc29saWQgJHRhYmxlLWJvcmRlci1jb2xvcjtcbiAgfVxuXG4gIHRoZWFkIHtcbiAgICB0aCxcbiAgICB0ZCB7XG4gICAgICBib3JkZXItYm90dG9tLXdpZHRoOiAoMiAqICR0YWJsZS1ib3JkZXItd2lkdGgpO1xuICAgIH1cbiAgfVxufVxuXG5cbi8vIFplYnJhLXN0cmlwaW5nXG4vL1xuLy8gRGVmYXVsdCB6ZWJyYS1zdHJpcGUgc3R5bGVzIChhbHRlcm5hdGluZyBncmF5IGFuZCB0cmFuc3BhcmVudCBiYWNrZ3JvdW5kcylcblxuLnRhYmxlLXN0cmlwZWQge1xuICB0Ym9keSB0cjpudGgtb2YtdHlwZShvZGQpIHtcbiAgICBiYWNrZ3JvdW5kLWNvbG9yOiAkdGFibGUtYWNjZW50LWJnO1xuICB9XG59XG5cblxuLy8gSG92ZXIgZWZmZWN0XG4vL1xuLy8gUGxhY2VkIGhlcmUgc2luY2UgaXQgaGFzIHRvIGNvbWUgYWZ0ZXIgdGhlIHBvdGVudGlhbCB6ZWJyYSBzdHJpcGluZ1xuXG4udGFibGUtaG92ZXIge1xuICB0Ym9keSB0ciB7XG4gICAgQGluY2x1ZGUgaG92ZXIge1xuICAgICAgYmFja2dyb3VuZC1jb2xvcjogJHRhYmxlLWhvdmVyLWJnO1xuICAgIH1cbiAgfVxufVxuXG5cbi8vIFRhYmxlIGJhY2tncm91bmRzXG4vL1xuLy8gRXhhY3Qgc2VsZWN0b3JzIGJlbG93IHJlcXVpcmVkIHRvIG92ZXJyaWRlIGAudGFibGUtc3RyaXBlZGAgYW5kIHByZXZlbnRcbi8vIGluaGVyaXRhbmNlIHRvIG5lc3RlZCB0YWJsZXMuXG5cbkBlYWNoICRjb2xvciwgJHZhbHVlIGluICR0aGVtZS1jb2xvcnMge1xuICBAaW5jbHVkZSB0YWJsZS1yb3ctdmFyaWFudCgkY29sb3IsIHRoZW1lLWNvbG9yLWxldmVsKCRjb2xvciwgLTkpKTtcbn1cblxuQGluY2x1ZGUgdGFibGUtcm93LXZhcmlhbnQoYWN0aXZlLCAkdGFibGUtYWN0aXZlLWJnKTtcblxuXG4vLyBJbnZlcnNlIHN0eWxlc1xuLy9cbi8vIFNhbWUgdGFibGUgbWFya3VwLCBidXQgaW52ZXJ0ZWQgY29sb3Igc2NoZW1lOiBkYXJrIGJhY2tncm91bmQgYW5kIGxpZ2h0IHRleHQuXG5cbi50aGVhZC1pbnZlcnNlIHtcbiAgdGgge1xuICAgIGNvbG9yOiAkdGFibGUtaW52ZXJzZS1jb2xvcjtcbiAgICBiYWNrZ3JvdW5kLWNvbG9yOiAkdGFibGUtaW52ZXJzZS1iZztcbiAgfVxufVxuXG4udGhlYWQtZGVmYXVsdCB7XG4gIHRoIHtcbiAgICBjb2xvcjogJHRhYmxlLWhlYWQtY29sb3I7XG4gICAgYmFja2dyb3VuZC1jb2xvcjogJHRhYmxlLWhlYWQtYmc7XG4gIH1cbn1cblxuLnRhYmxlLWludmVyc2Uge1xuICBjb2xvcjogJHRhYmxlLWludmVyc2UtY29sb3I7XG4gIGJhY2tncm91bmQtY29sb3I6ICR0YWJsZS1pbnZlcnNlLWJnO1xuXG4gIHRoLFxuICB0ZCxcbiAgdGhlYWQgdGgge1xuICAgIGJvcmRlci1jb2xvcjogJHRhYmxlLWludmVyc2UtYm9yZGVyLWNvbG9yO1xuICB9XG5cbiAgJi50YWJsZS1ib3JkZXJlZCB7XG4gICAgYm9yZGVyOiAwO1xuICB9XG5cbiAgJi50YWJsZS1zdHJpcGVkIHtcbiAgICB0Ym9keSB0cjpudGgtb2YtdHlwZShvZGQpIHtcbiAgICAgIGJhY2tncm91bmQtY29sb3I6ICR0YWJsZS1pbnZlcnNlLWFjY2VudC1iZztcbiAgICB9XG4gIH1cblxuICAmLnRhYmxlLWhvdmVyIHtcbiAgICB0Ym9keSB0ciB7XG4gICAgICBAaW5jbHVkZSBob3ZlciB7XG4gICAgICAgIGJhY2tncm91bmQtY29sb3I6ICR0YWJsZS1pbnZlcnNlLWhvdmVyLWJnO1xuICAgICAgfVxuICAgIH1cbiAgfVxufVxuXG5cbi8vIFJlc3BvbnNpdmUgdGFibGVzXG4vL1xuLy8gQWRkIGAudGFibGUtcmVzcG9uc2l2ZWAgdG8gYC50YWJsZWBzIGFuZCB3ZSdsbCBtYWtlIHRoZW0gbW9iaWxlIGZyaWVuZGx5IGJ5XG4vLyBlbmFibGluZyBob3Jpem9udGFsIHNjcm9sbGluZy4gT25seSBhcHBsaWVzIDw3NjhweC4gRXZlcnl0aGluZyBhYm92ZSB0aGF0XG4vLyB3aWxsIGRpc3BsYXkgbm9ybWFsbHkuXG5cbi50YWJsZS1yZXNwb25zaXZlIHtcbiAgQGluY2x1ZGUgbWVkaWEtYnJlYWtwb2ludC1kb3duKG1kKSB7XG4gICAgZGlzcGxheTogYmxvY2s7XG4gICAgd2lkdGg6IDEwMCU7XG4gICAgb3ZlcmZsb3cteDogYXV0bztcbiAgICAtbXMtb3ZlcmZsb3ctc3R5bGU6IC1tcy1hdXRvaGlkaW5nLXNjcm9sbGJhcjsgLy8gU2VlIGh0dHBzOi8vZ2l0aHViLmNvbS90d2JzL2Jvb3RzdHJhcC9wdWxsLzEwMDU3XG5cbiAgICAvLyBQcmV2ZW50IGRvdWJsZSBib3JkZXIgb24gaG9yaXpvbnRhbCBzY3JvbGwgZHVlIHRvIHVzZSBvZiBgZGlzcGxheTogYmxvY2s7YFxuICAgICYudGFibGUtYm9yZGVyZWQge1xuICAgICAgYm9yZGVyOiAwO1xuICAgIH1cbiAgfVxufVxuIiwiLy8gVGFibGVzXG5cbkBtaXhpbiB0YWJsZS1yb3ctdmFyaWFudCgkc3RhdGUsICRiYWNrZ3JvdW5kKSB7XG4gIC8vIEV4YWN0IHNlbGVjdG9ycyBiZWxvdyByZXF1aXJlZCB0byBvdmVycmlkZSBgLnRhYmxlLXN0cmlwZWRgIGFuZCBwcmV2ZW50XG4gIC8vIGluaGVyaXRhbmNlIHRvIG5lc3RlZCB0YWJsZXMuXG4gIC50YWJsZS0jeyRzdGF0ZX0ge1xuICAgICYsXG4gICAgPiB0aCxcbiAgICA+IHRkIHtcbiAgICAgIGJhY2tncm91bmQtY29sb3I6ICRiYWNrZ3JvdW5kO1xuICAgIH1cbiAgfVxuXG4gIC8vIEhvdmVyIHN0YXRlcyBmb3IgYC50YWJsZS1ob3ZlcmBcbiAgLy8gTm90ZTogdGhpcyBpcyBub3QgYXZhaWxhYmxlIGZvciBjZWxscyBvciByb3dzIHdpdGhpbiBgdGhlYWRgIG9yIGB0Zm9vdGAuXG4gIC50YWJsZS1ob3ZlciB7XG4gICAgJGhvdmVyLWJhY2tncm91bmQ6IGRhcmtlbigkYmFja2dyb3VuZCwgNSUpO1xuXG4gICAgLnRhYmxlLSN7JHN0YXRlfSB7XG4gICAgICBAaW5jbHVkZSBob3ZlciB7XG4gICAgICAgIGJhY2tncm91bmQtY29sb3I6ICRob3Zlci1iYWNrZ3JvdW5kO1xuXG4gICAgICAgID4gdGQsXG4gICAgICAgID4gdGgge1xuICAgICAgICAgIGJhY2tncm91bmQtY29sb3I6ICRob3Zlci1iYWNrZ3JvdW5kO1xuICAgICAgICB9XG4gICAgICB9XG4gICAgfVxuICB9XG59XG4iLCIvLyBCb290c3RyYXAgZnVuY3Rpb25zXG4vL1xuLy8gVXRpbGl0eSBtaXhpbnMgYW5kIGZ1bmN0aW9ucyBmb3IgZXZhbHV0YXRpbmcgc291cmNlIGNvZGUgYWNyb3NzIG91ciB2YXJpYWJsZXMsIG1hcHMsIGFuZCBtaXhpbnMuXG5cbi8vIEFzY2VuZGluZ1xuLy8gVXNlZCB0byBldmFsdWF0ZSBTYXNzIG1hcHMgbGlrZSBvdXIgZ3JpZCBicmVha3BvaW50cy5cbkBtaXhpbiBfYXNzZXJ0LWFzY2VuZGluZygkbWFwLCAkbWFwLW5hbWUpIHtcbiAgJHByZXYta2V5OiBudWxsO1xuICAkcHJldi1udW06IG51bGw7XG4gIEBlYWNoICRrZXksICRudW0gaW4gJG1hcCB7XG4gICAgQGlmICRwcmV2LW51bSA9PSBudWxsIHtcbiAgICAgIC8vIERvIG5vdGhpbmdcbiAgICB9IEBlbHNlIGlmIG5vdCBjb21wYXJhYmxlKCRwcmV2LW51bSwgJG51bSkge1xuICAgICAgQHdhcm4gXCJQb3RlbnRpYWxseSBpbnZhbGlkIHZhbHVlIGZvciAjeyRtYXAtbmFtZX06IFRoaXMgbWFwIG11c3QgYmUgaW4gYXNjZW5kaW5nIG9yZGVyLCBidXQga2V5ICcjeyRrZXl9JyBoYXMgdmFsdWUgI3skbnVtfSB3aG9zZSB1bml0IG1ha2VzIGl0IGluY29tcGFyYWJsZSB0byAjeyRwcmV2LW51bX0sIHRoZSB2YWx1ZSBvZiB0aGUgcHJldmlvdXMga2V5ICcjeyRwcmV2LWtleX0nICFcIjtcbiAgICB9IEBlbHNlIGlmICRwcmV2LW51bSA+PSAkbnVtIHtcbiAgICAgIEB3YXJuIFwiSW52YWxpZCB2YWx1ZSBmb3IgI3skbWFwLW5hbWV9OiBUaGlzIG1hcCBtdXN0IGJlIGluIGFzY2VuZGluZyBvcmRlciwgYnV0IGtleSAnI3ska2V5fScgaGFzIHZhbHVlICN7JG51bX0gd2hpY2ggaXNuJ3QgZ3JlYXRlciB0aGFuICN7JHByZXYtbnVtfSwgdGhlIHZhbHVlIG9mIHRoZSBwcmV2aW91cyBrZXkgJyN7JHByZXYta2V5fScgIVwiO1xuICAgIH1cbiAgICAkcHJldi1rZXk6ICRrZXk7XG4gICAgJHByZXYtbnVtOiAkbnVtO1xuICB9XG59XG5cbi8vIFN0YXJ0cyBhdCB6ZXJvXG4vLyBBbm90aGVyIGdyaWQgbWl4aW4gdGhhdCBlbnN1cmVzIHRoZSBtaW4td2lkdGggb2YgdGhlIGxvd2VzdCBicmVha3BvaW50IHN0YXJ0cyBhdCAwLlxuQG1peGluIF9hc3NlcnQtc3RhcnRzLWF0LXplcm8oJG1hcCkge1xuICAkdmFsdWVzOiBtYXAtdmFsdWVzKCRtYXApO1xuICAkZmlyc3QtdmFsdWU6IG50aCgkdmFsdWVzLCAxKTtcbiAgQGlmICRmaXJzdC12YWx1ZSAhPSAwIHtcbiAgICBAd2FybiBcIkZpcnN0IGJyZWFrcG9pbnQgaW4gYCRncmlkLWJyZWFrcG9pbnRzYCBtdXN0IHN0YXJ0IGF0IDAsIGJ1dCBzdGFydHMgYXQgI3skZmlyc3QtdmFsdWV9LlwiO1xuICB9XG59XG5cbi8vIFJlcGxhY2UgYCRzZWFyY2hgIHdpdGggYCRyZXBsYWNlYCBpbiBgJHN0cmluZ2Bcbi8vIFVzZWQgb24gb3VyIFNWRyBpY29uIGJhY2tncm91bmRzIGZvciBjdXN0b20gZm9ybXMuXG4vL1xuLy8gQGF1dGhvciBIdWdvIEdpcmF1ZGVsXG4vLyBAcGFyYW0ge1N0cmluZ30gJHN0cmluZyAtIEluaXRpYWwgc3RyaW5nXG4vLyBAcGFyYW0ge1N0cmluZ30gJHNlYXJjaCAtIFN1YnN0cmluZyB0byByZXBsYWNlXG4vLyBAcGFyYW0ge1N0cmluZ30gJHJlcGxhY2UgKCcnKSAtIE5ldyB2YWx1ZVxuLy8gQHJldHVybiB7U3RyaW5nfSAtIFVwZGF0ZWQgc3RyaW5nXG5AZnVuY3Rpb24gc3RyLXJlcGxhY2UoJHN0cmluZywgJHNlYXJjaCwgJHJlcGxhY2U6IFwiXCIpIHtcbiAgJGluZGV4OiBzdHItaW5kZXgoJHN0cmluZywgJHNlYXJjaCk7XG5cbiAgQGlmICRpbmRleCB7XG4gICAgQHJldHVybiBzdHItc2xpY2UoJHN0cmluZywgMSwgJGluZGV4IC0gMSkgKyAkcmVwbGFjZSArIHN0ci1yZXBsYWNlKHN0ci1zbGljZSgkc3RyaW5nLCAkaW5kZXggKyBzdHItbGVuZ3RoKCRzZWFyY2gpKSwgJHNlYXJjaCwgJHJlcGxhY2UpO1xuICB9XG5cbiAgQHJldHVybiAkc3RyaW5nO1xufVxuXG4vLyBDb2xvciBjb250cmFzdFxuQG1peGluIGNvbG9yLXlpcSgkY29sb3IpIHtcbiAgJHI6IHJlZCgkY29sb3IpO1xuICAkZzogZ3JlZW4oJGNvbG9yKTtcbiAgJGI6IGJsdWUoJGNvbG9yKTtcblxuICAkeWlxOiAoKCRyICogMjk5KSArICgkZyAqIDU4NykgKyAoJGIgKiAxMTQpKSAvIDEwMDA7XG5cbiAgQGlmICgkeWlxID49IDE1MCkge1xuICAgIGNvbG9yOiAjMTExO1xuICB9IEBlbHNlIHtcbiAgICBjb2xvcjogI2ZmZjtcbiAgfVxufVxuXG4vLyBSZXRyZWl2ZSBjb2xvciBTYXNzIG1hcHNcbkBmdW5jdGlvbiBjb2xvcigka2V5OiBcImJsdWVcIikge1xuICBAcmV0dXJuIG1hcC1nZXQoJGNvbG9ycywgJGtleSk7XG59XG5cbkBmdW5jdGlvbiB0aGVtZS1jb2xvcigka2V5OiBcInByaW1hcnlcIikge1xuICBAcmV0dXJuIG1hcC1nZXQoJHRoZW1lLWNvbG9ycywgJGtleSk7XG59XG5cbkBmdW5jdGlvbiBncmF5c2NhbGUoJGtleTogXCIxMDBcIikge1xuICBAcmV0dXJuIG1hcC1nZXQoJGdyYXlzLCAka2V5KTtcbn1cblxuLy8gUmVxdWVzdCBhIHRoZW1lIGNvbG9yIGxldmVsXG5AZnVuY3Rpb24gdGhlbWUtY29sb3ItbGV2ZWwoJGNvbG9yLW5hbWU6IFwicHJpbWFyeVwiLCAkbGV2ZWw6IDApIHtcbiAgJGNvbG9yOiB0aGVtZS1jb2xvcigkY29sb3ItbmFtZSk7XG4gICRjb2xvci1iYXNlOiBpZigkbGV2ZWwgPiAwLCAjMDAwLCAjZmZmKTtcblxuICBAaWYgJGxldmVsIDwgMCB7XG4gICAgLy8gTGlnaHRlciB2YWx1ZXMgbmVlZCBhIHF1aWNrIGRvdWJsZSBuZWdhdGl2ZSBmb3IgdGhlIFNhc3MgbWF0aCB0byB3b3JrXG4gICAgQHJldHVybiBtaXgoJGNvbG9yLWJhc2UsICRjb2xvciwgJGxldmVsICogLTEgKiAkdGhlbWUtY29sb3ItaW50ZXJ2YWwpO1xuICB9IEBlbHNlIHtcbiAgICBAcmV0dXJuIG1peCgkY29sb3ItYmFzZSwgJGNvbG9yLCAkbGV2ZWwgKiAkdGhlbWUtY29sb3ItaW50ZXJ2YWwpO1xuICB9XG59XG4iLCIvLyBzY3NzLWxpbnQ6ZGlzYWJsZSBRdWFsaWZ5aW5nRWxlbWVudCwgVmVuZG9yUHJlZml4XG5cbi8vXG4vLyBUZXh0dWFsIGZvcm0gY29udHJvbHNcbi8vXG5cbi5mb3JtLWNvbnRyb2wge1xuICBkaXNwbGF5OiBibG9jaztcbiAgd2lkdGg6IDEwMCU7XG4gIC8vIC8vIE1ha2UgaW5wdXRzIGF0IGxlYXN0IHRoZSBoZWlnaHQgb2YgdGhlaXIgYnV0dG9uIGNvdW50ZXJwYXJ0IChiYXNlIGxpbmUtaGVpZ2h0ICsgcGFkZGluZyArIGJvcmRlcilcbiAgLy8gaGVpZ2h0OiAkaW5wdXQtaGVpZ2h0O1xuICBwYWRkaW5nOiAkaW5wdXQtYnRuLXBhZGRpbmcteSAkaW5wdXQtYnRuLXBhZGRpbmcteDtcbiAgZm9udC1zaXplOiAkZm9udC1zaXplLWJhc2U7XG4gIGxpbmUtaGVpZ2h0OiAkaW5wdXQtYnRuLWxpbmUtaGVpZ2h0O1xuICBjb2xvcjogJGlucHV0LWNvbG9yO1xuICBiYWNrZ3JvdW5kLWNvbG9yOiAkaW5wdXQtYmc7XG4gIC8vIFJlc2V0IHVudXN1YWwgRmlyZWZveC1vbi1BbmRyb2lkIGRlZmF1bHQgc3R5bGU7IHNlZSBodHRwczovL2dpdGh1Yi5jb20vbmVjb2xhcy9ub3JtYWxpemUuY3NzL2lzc3Vlcy8yMTQuXG4gIGJhY2tncm91bmQtaW1hZ2U6IG5vbmU7XG4gIGJhY2tncm91bmQtY2xpcDogcGFkZGluZy1ib3g7XG4gIGJvcmRlcjogJGlucHV0LWJ0bi1ib3JkZXItd2lkdGggc29saWQgJGlucHV0LWJvcmRlci1jb2xvcjtcblxuICAvLyBOb3RlOiBUaGlzIGhhcyBubyBlZmZlY3Qgb24gPHNlbGVjdD5zIGluIHNvbWUgYnJvd3NlcnMsIGR1ZSB0byB0aGUgbGltaXRlZCBzdHlsYWJpbGl0eSBvZiBgPHNlbGVjdD5gcyBpbiBDU1MuXG4gIEBpZiAkZW5hYmxlLXJvdW5kZWQge1xuICAgIC8vIE1hbnVhbGx5IHVzZSB0aGUgaWYvZWxzZSBpbnN0ZWFkIG9mIHRoZSBtaXhpbiB0byBhY2NvdW50IGZvciBpT1Mgb3ZlcnJpZGVcbiAgICBib3JkZXItcmFkaXVzOiAkaW5wdXQtYm9yZGVyLXJhZGl1cztcbiAgfSBAZWxzZSB7XG4gICAgLy8gT3RoZXJ3aXNlIHVuZG8gdGhlIGlPUyBkZWZhdWx0XG4gICAgYm9yZGVyLXJhZGl1czogMDtcbiAgfVxuXG4gIEBpbmNsdWRlIGJveC1zaGFkb3coJGlucHV0LWJveC1zaGFkb3cpO1xuICBAaW5jbHVkZSB0cmFuc2l0aW9uKCRpbnB1dC10cmFuc2l0aW9uKTtcblxuICAvLyBVbnN0eWxlIHRoZSBjYXJldCBvbiBgPHNlbGVjdD5gcyBpbiBJRTEwKy5cbiAgJjo6LW1zLWV4cGFuZCB7XG4gICAgYmFja2dyb3VuZC1jb2xvcjogdHJhbnNwYXJlbnQ7XG4gICAgYm9yZGVyOiAwO1xuICB9XG5cbiAgLy8gQ3VzdG9taXplIHRoZSBgOmZvY3VzYCBzdGF0ZSB0byBpbWl0YXRlIG5hdGl2ZSBXZWJLaXQgc3R5bGVzLlxuICBAaW5jbHVkZSBmb3JtLWNvbnRyb2wtZm9jdXMoKTtcblxuICAvLyBQbGFjZWhvbGRlclxuICAmOjpwbGFjZWhvbGRlciB7XG4gICAgY29sb3I6ICRpbnB1dC1wbGFjZWhvbGRlci1jb2xvcjtcbiAgICAvLyBPdmVycmlkZSBGaXJlZm94J3MgdW51c3VhbCBkZWZhdWx0IG9wYWNpdHk7IHNlZSBodHRwczovL2dpdGh1Yi5jb20vdHdicy9ib290c3RyYXAvcHVsbC8xMTUyNi5cbiAgICBvcGFjaXR5OiAxO1xuICB9XG5cbiAgLy8gRGlzYWJsZWQgYW5kIHJlYWQtb25seSBpbnB1dHNcbiAgLy9cbiAgLy8gSFRNTDUgc2F5cyB0aGF0IGNvbnRyb2xzIHVuZGVyIGEgZmllbGRzZXQgPiBsZWdlbmQ6Zmlyc3QtY2hpbGQgd29uJ3QgYmVcbiAgLy8gZGlzYWJsZWQgaWYgdGhlIGZpZWxkc2V0IGlzIGRpc2FibGVkLiBEdWUgdG8gaW1wbGVtZW50YXRpb24gZGlmZmljdWx0eSwgd2VcbiAgLy8gZG9uJ3QgaG9ub3IgdGhhdCBlZGdlIGNhc2U7IHdlIHN0eWxlIHRoZW0gYXMgZGlzYWJsZWQgYW55d2F5LlxuICAmOmRpc2FibGVkLFxuICAmW3JlYWRvbmx5XSB7XG4gICAgYmFja2dyb3VuZC1jb2xvcjogJGlucHV0LWRpc2FibGVkLWJnO1xuICAgIC8vIGlPUyBmaXggZm9yIHVucmVhZGFibGUgZGlzYWJsZWQgY29udGVudDsgc2VlIGh0dHBzOi8vZ2l0aHViLmNvbS90d2JzL2Jvb3RzdHJhcC9pc3N1ZXMvMTE2NTUuXG4gICAgb3BhY2l0eTogMTtcbiAgfVxufVxuXG5zZWxlY3QuZm9ybS1jb250cm9sIHtcbiAgJjpub3QoW3NpemVdKTpub3QoW211bHRpcGxlXSkge1xuICAgIGhlaWdodDogJGlucHV0LWhlaWdodDtcbiAgfVxuXG4gICY6Zm9jdXM6Oi1tcy12YWx1ZSB7XG4gICAgLy8gU3VwcHJlc3MgdGhlIG5lc3RlZCBkZWZhdWx0IHdoaXRlIHRleHQgb24gYmx1ZSBiYWNrZ3JvdW5kIGhpZ2hsaWdodCBnaXZlbiB0b1xuICAgIC8vIHRoZSBzZWxlY3RlZCBvcHRpb24gdGV4dCB3aGVuIHRoZSAoc3RpbGwgY2xvc2VkKSA8c2VsZWN0PiByZWNlaXZlcyBmb2N1c1xuICAgIC8vIGluIElFIGFuZCAodW5kZXIgY2VydGFpbiBjb25kaXRpb25zKSBFZGdlLCBhcyBpdCBsb29rcyBiYWQgYW5kIGNhbm5vdCBiZSBtYWRlIHRvXG4gICAgLy8gbWF0Y2ggdGhlIGFwcGVhcmFuY2Ugb2YgdGhlIG5hdGl2ZSB3aWRnZXQuXG4gICAgLy8gU2VlIGh0dHBzOi8vZ2l0aHViLmNvbS90d2JzL2Jvb3RzdHJhcC9pc3N1ZXMvMTkzOTguXG4gICAgY29sb3I6ICRpbnB1dC1jb2xvcjtcbiAgICBiYWNrZ3JvdW5kLWNvbG9yOiAkaW5wdXQtYmc7XG4gIH1cbn1cblxuLy8gTWFrZSBmaWxlIGlucHV0cyBiZXR0ZXIgbWF0Y2ggdGV4dCBpbnB1dHMgYnkgZm9yY2luZyB0aGVtIHRvIG5ldyBsaW5lcy5cbi5mb3JtLWNvbnRyb2wtZmlsZSxcbi5mb3JtLWNvbnRyb2wtcmFuZ2Uge1xuICBkaXNwbGF5OiBibG9jaztcbn1cblxuXG4vL1xuLy8gTGFiZWxzXG4vL1xuXG4vLyBGb3IgdXNlIHdpdGggaG9yaXpvbnRhbCBhbmQgaW5saW5lIGZvcm1zLCB3aGVuIHlvdSBuZWVkIHRoZSBsYWJlbCB0ZXh0IHRvXG4vLyBhbGlnbiB3aXRoIHRoZSBmb3JtIGNvbnRyb2xzLlxuLmNvbC1mb3JtLWxhYmVsIHtcbiAgcGFkZGluZy10b3A6IGNhbGMoI3skaW5wdXQtYnRuLXBhZGRpbmcteX0gLSAjeyRpbnB1dC1idG4tYm9yZGVyLXdpZHRofSAqIDIpO1xuICBwYWRkaW5nLWJvdHRvbTogY2FsYygjeyRpbnB1dC1idG4tcGFkZGluZy15fSAtICN7JGlucHV0LWJ0bi1ib3JkZXItd2lkdGh9ICogMik7XG4gIG1hcmdpbi1ib3R0b206IDA7IC8vIE92ZXJyaWRlIHRoZSBgPGxhYmVsPmAgZGVmYXVsdFxufVxuXG4uY29sLWZvcm0tbGFiZWwtbGcge1xuICBwYWRkaW5nLXRvcDogY2FsYygjeyRpbnB1dC1idG4tcGFkZGluZy15LWxnfSAtICN7JGlucHV0LWJ0bi1ib3JkZXItd2lkdGh9ICogMik7XG4gIHBhZGRpbmctYm90dG9tOiBjYWxjKCN7JGlucHV0LWJ0bi1wYWRkaW5nLXktbGd9IC0gI3skaW5wdXQtYnRuLWJvcmRlci13aWR0aH0gKiAyKTtcbiAgZm9udC1zaXplOiAkZm9udC1zaXplLWxnO1xufVxuXG4uY29sLWZvcm0tbGFiZWwtc20ge1xuICBwYWRkaW5nLXRvcDogY2FsYygjeyRpbnB1dC1idG4tcGFkZGluZy15LXNtfSAtICN7JGlucHV0LWJ0bi1ib3JkZXItd2lkdGh9ICogMik7XG4gIHBhZGRpbmctYm90dG9tOiBjYWxjKCN7JGlucHV0LWJ0bi1wYWRkaW5nLXktc219IC0gI3skaW5wdXQtYnRuLWJvcmRlci13aWR0aH0gKiAyKTtcbiAgZm9udC1zaXplOiAkZm9udC1zaXplLXNtO1xufVxuXG5cbi8vXG4vLyBMZWdlbmRzXG4vL1xuXG4vLyBGb3IgdXNlIHdpdGggaG9yaXpvbnRhbCBhbmQgaW5saW5lIGZvcm1zLCB3aGVuIHlvdSBuZWVkIHRoZSBsZWdlbmQgdGV4dCB0b1xuLy8gYmUgdGhlIHNhbWUgc2l6ZSBhcyByZWd1bGFyIGxhYmVscywgYW5kIHRvIGFsaWduIHdpdGggdGhlIGZvcm0gY29udHJvbHMuXG4uY29sLWZvcm0tbGVnZW5kIHtcbiAgcGFkZGluZy10b3A6ICRpbnB1dC1idG4tcGFkZGluZy15O1xuICBwYWRkaW5nLWJvdHRvbTogJGlucHV0LWJ0bi1wYWRkaW5nLXk7XG4gIG1hcmdpbi1ib3R0b206IDA7XG4gIGZvbnQtc2l6ZTogJGZvbnQtc2l6ZS1iYXNlO1xufVxuXG5cbi8vIFJlYWRvbmx5IGNvbnRyb2xzIGFzIHBsYWluIHRleHRcbi8vXG4vLyBBcHBseSBjbGFzcyB0byBhIHJlYWRvbmx5IGlucHV0IHRvIG1ha2UgaXQgYXBwZWFyIGxpa2UgcmVndWxhciBwbGFpblxuLy8gdGV4dCAod2l0aG91dCBhbnkgYm9yZGVyLCBiYWNrZ3JvdW5kIGNvbG9yLCBmb2N1cyBpbmRpY2F0b3IpXG5cbi5mb3JtLWNvbnRyb2wtcGxhaW50ZXh0IHtcbiAgcGFkZGluZy10b3A6ICRpbnB1dC1idG4tcGFkZGluZy15O1xuICBwYWRkaW5nLWJvdHRvbTogJGlucHV0LWJ0bi1wYWRkaW5nLXk7XG4gIG1hcmdpbi1ib3R0b206IDA7IC8vIG1hdGNoIGlucHV0cyBpZiB0aGlzIGNsYXNzIGNvbWVzIG9uIGlucHV0cyB3aXRoIGRlZmF1bHQgbWFyZ2luc1xuICBsaW5lLWhlaWdodDogJGlucHV0LWJ0bi1saW5lLWhlaWdodDtcbiAgYm9yZGVyOiBzb2xpZCB0cmFuc3BhcmVudDtcbiAgYm9yZGVyLXdpZHRoOiAkaW5wdXQtYnRuLWJvcmRlci13aWR0aCAwO1xuXG4gICYuZm9ybS1jb250cm9sLXNtLFxuICAmLmZvcm0tY29udHJvbC1sZyB7XG4gICAgcGFkZGluZy1yaWdodDogMDtcbiAgICBwYWRkaW5nLWxlZnQ6IDA7XG4gIH1cbn1cblxuXG4vLyBGb3JtIGNvbnRyb2wgc2l6aW5nXG4vL1xuLy8gQnVpbGQgb24gYC5mb3JtLWNvbnRyb2xgIHdpdGggbW9kaWZpZXIgY2xhc3NlcyB0byBkZWNyZWFzZSBvciBpbmNyZWFzZSB0aGVcbi8vIGhlaWdodCBhbmQgZm9udC1zaXplIG9mIGZvcm0gY29udHJvbHMuXG4vL1xuLy8gVGhlIGAuZm9ybS1ncm91cC0qIGZvcm0tY29udHJvbGAgdmFyaWF0aW9ucyBhcmUgc2FkbHkgZHVwbGljYXRlZCB0byBhdm9pZCB0aGVcbi8vIGlzc3VlIGRvY3VtZW50ZWQgaW4gaHR0cHM6Ly9naXRodWIuY29tL3R3YnMvYm9vdHN0cmFwL2lzc3Vlcy8xNTA3NC5cblxuLmZvcm0tY29udHJvbC1zbSB7XG4gIHBhZGRpbmc6ICRpbnB1dC1idG4tcGFkZGluZy15LXNtICRpbnB1dC1idG4tcGFkZGluZy14LXNtO1xuICBmb250LXNpemU6ICRmb250LXNpemUtc207XG4gIGxpbmUtaGVpZ2h0OiAkaW5wdXQtYnRuLWxpbmUtaGVpZ2h0LXNtO1xuICBAaW5jbHVkZSBib3JkZXItcmFkaXVzKCRpbnB1dC1ib3JkZXItcmFkaXVzLXNtKTtcbn1cblxuc2VsZWN0LmZvcm0tY29udHJvbC1zbSB7XG4gICY6bm90KFtzaXplXSk6bm90KFttdWx0aXBsZV0pIHtcbiAgICBoZWlnaHQ6ICRpbnB1dC1oZWlnaHQtc207XG4gIH1cbn1cblxuLmZvcm0tY29udHJvbC1sZyB7XG4gIHBhZGRpbmc6ICRpbnB1dC1idG4tcGFkZGluZy15LWxnICRpbnB1dC1idG4tcGFkZGluZy14LWxnO1xuICBmb250LXNpemU6ICRmb250LXNpemUtbGc7XG4gIGxpbmUtaGVpZ2h0OiAkaW5wdXQtYnRuLWxpbmUtaGVpZ2h0LWxnO1xuICBAaW5jbHVkZSBib3JkZXItcmFkaXVzKCRpbnB1dC1ib3JkZXItcmFkaXVzLWxnKTtcbn1cblxuc2VsZWN0LmZvcm0tY29udHJvbC1sZyB7XG4gICY6bm90KFtzaXplXSk6bm90KFttdWx0aXBsZV0pIHtcbiAgICBoZWlnaHQ6ICRpbnB1dC1oZWlnaHQtbGc7XG4gIH1cbn1cblxuXG4vLyBGb3JtIGdyb3Vwc1xuLy9cbi8vIERlc2lnbmVkIHRvIGhlbHAgd2l0aCB0aGUgb3JnYW5pemF0aW9uIGFuZCBzcGFjaW5nIG9mIHZlcnRpY2FsIGZvcm1zLiBGb3Jcbi8vIGhvcml6b250YWwgZm9ybXMsIHVzZSB0aGUgcHJlZGVmaW5lZCBncmlkIGNsYXNzZXMuXG5cbi5mb3JtLWdyb3VwIHtcbiAgbWFyZ2luLWJvdHRvbTogJGZvcm0tZ3JvdXAtbWFyZ2luLWJvdHRvbTtcbn1cblxuLmZvcm0tdGV4dCB7XG4gIGRpc3BsYXk6IGJsb2NrO1xuICBtYXJnaW4tdG9wOiAkZm9ybS10ZXh0LW1hcmdpbi10b3A7XG59XG5cblxuLy8gRm9ybSBncmlkXG4vL1xuLy8gU3BlY2lhbCByZXBsYWNlbWVudCBmb3Igb3VyIGdyaWQgc3lzdGVtJ3MgYC5yb3dgIGZvciB0aWdodGVyIGZvcm0gbGF5b3V0cy5cblxuLmZvcm0tcm93IHtcbiAgZGlzcGxheTogZmxleDtcbiAgZmxleC13cmFwOiB3cmFwO1xuICBtYXJnaW4tcmlnaHQ6IC01cHg7XG4gIG1hcmdpbi1sZWZ0OiAtNXB4O1xuXG4gID4gLmNvbCxcbiAgPiBbY2xhc3MqPVwiY29sLVwiXSB7XG4gICAgcGFkZGluZy1yaWdodDogNXB4O1xuICAgIHBhZGRpbmctbGVmdDogNXB4O1xuICB9XG59XG5cblxuLy8gQ2hlY2tib3hlcyBhbmQgcmFkaW9zXG4vL1xuLy8gSW5kZW50IHRoZSBsYWJlbHMgdG8gcG9zaXRpb24gcmFkaW9zL2NoZWNrYm94ZXMgYXMgaGFuZ2luZyBjb250cm9scy5cblxuLmZvcm0tY2hlY2sge1xuICBwb3NpdGlvbjogcmVsYXRpdmU7XG4gIGRpc3BsYXk6IGJsb2NrO1xuICBtYXJnaW4tYm90dG9tOiAkZm9ybS1jaGVjay1tYXJnaW4tYm90dG9tO1xuXG4gICYuZGlzYWJsZWQge1xuICAgIC5mb3JtLWNoZWNrLWxhYmVsIHtcbiAgICAgIGNvbG9yOiAkdGV4dC1tdXRlZDtcbiAgICB9XG4gIH1cbn1cblxuLmZvcm0tY2hlY2stbGFiZWwge1xuICBwYWRkaW5nLWxlZnQ6ICRmb3JtLWNoZWNrLWlucHV0LWd1dHRlcjtcbiAgbWFyZ2luLWJvdHRvbTogMDsgLy8gT3ZlcnJpZGUgZGVmYXVsdCBgPGxhYmVsPmAgYm90dG9tIG1hcmdpblxufVxuXG4uZm9ybS1jaGVjay1pbnB1dCB7XG4gIHBvc2l0aW9uOiBhYnNvbHV0ZTtcbiAgbWFyZ2luLXRvcDogJGZvcm0tY2hlY2staW5wdXQtbWFyZ2luLXk7XG4gIG1hcmdpbi1sZWZ0OiAtJGZvcm0tY2hlY2staW5wdXQtZ3V0dGVyO1xufVxuXG4vLyBSYWRpb3MgYW5kIGNoZWNrYm94ZXMgb24gc2FtZSBsaW5lXG4uZm9ybS1jaGVjay1pbmxpbmUge1xuICBkaXNwbGF5OiBpbmxpbmUtYmxvY2s7XG5cbiAgLmZvcm0tY2hlY2stbGFiZWwge1xuICAgIHZlcnRpY2FsLWFsaWduOiBtaWRkbGU7XG4gIH1cblxuICArIC5mb3JtLWNoZWNrLWlubGluZSB7XG4gICAgbWFyZ2luLWxlZnQ6ICRmb3JtLWNoZWNrLWlubGluZS1tYXJnaW4teDtcbiAgfVxufVxuXG5cbi8vIEZvcm0gdmFsaWRhdGlvblxuLy9cbi8vIFByb3ZpZGUgZmVlZGJhY2sgdG8gdXNlcnMgd2hlbiBmb3JtIGZpZWxkIHZhbHVlcyBhcmUgdmFsaWQgb3IgaW52YWxpZC4gV29ya3Ncbi8vIHByaW1hcmlseSBmb3IgY2xpZW50LXNpZGUgdmFsaWRhdGlvbiB2aWEgc2NvcGVkIGA6aW52YWxpZGAgYW5kIGA6dmFsaWRgXG4vLyBwc2V1ZG8tY2xhc3NlcyBidXQgYWxzbyBpbmNsdWRlcyBgLmlzLWludmFsaWRgIGFuZCBgLmlzLXZhbGlkYCBjbGFzc2VzIGZvclxuLy8gc2VydmVyIHNpZGUgdmFsaWRhdGlvbi5cblxuLmludmFsaWQtZmVlZGJhY2sge1xuICBkaXNwbGF5OiBub25lO1xuICBtYXJnaW4tdG9wOiAuMjVyZW07XG4gIGZvbnQtc2l6ZTogLjg3NXJlbTtcbiAgY29sb3I6ICRmb3JtLWZlZWRiYWNrLWludmFsaWQtY29sb3I7XG59XG5cbi5pbnZhbGlkLXRvb2x0aXAge1xuICBwb3NpdGlvbjogYWJzb2x1dGU7XG4gIHRvcDogMTAwJTtcbiAgei1pbmRleDogNTtcbiAgZGlzcGxheTogbm9uZTtcbiAgd2lkdGg6IDI1MHB4O1xuICBwYWRkaW5nOiAuNXJlbTtcbiAgbWFyZ2luLXRvcDogLjFyZW07XG4gIGZvbnQtc2l6ZTogLjg3NXJlbTtcbiAgbGluZS1oZWlnaHQ6IDE7XG4gIGNvbG9yOiAjZmZmO1xuICBiYWNrZ3JvdW5kLWNvbG9yOiByZ2JhKCRmb3JtLWZlZWRiYWNrLWludmFsaWQtY29sb3IsLjgpO1xuICBib3JkZXItcmFkaXVzOiAuMnJlbTtcbn1cblxuQGluY2x1ZGUgZm9ybS12YWxpZGF0aW9uLXN0YXRlKFwidmFsaWRcIiwgJGZvcm0tZmVlZGJhY2stdmFsaWQtY29sb3IpO1xuQGluY2x1ZGUgZm9ybS12YWxpZGF0aW9uLXN0YXRlKFwiaW52YWxpZFwiLCAkZm9ybS1mZWVkYmFjay1pbnZhbGlkLWNvbG9yKTtcblxuLy8gSW5saW5lIGZvcm1zXG4vL1xuLy8gTWFrZSBmb3JtcyBhcHBlYXIgaW5saW5lKC1ibG9jaykgYnkgYWRkaW5nIHRoZSBgLmZvcm0taW5saW5lYCBjbGFzcy4gSW5saW5lXG4vLyBmb3JtcyBiZWdpbiBzdGFja2VkIG9uIGV4dHJhIHNtYWxsIChtb2JpbGUpIGRldmljZXMgYW5kIHRoZW4gZ28gaW5saW5lIHdoZW5cbi8vIHZpZXdwb3J0cyByZWFjaCA8NzY4cHguXG4vL1xuLy8gUmVxdWlyZXMgd3JhcHBpbmcgaW5wdXRzIGFuZCBsYWJlbHMgd2l0aCBgLmZvcm0tZ3JvdXBgIGZvciBwcm9wZXIgZGlzcGxheSBvZlxuLy8gZGVmYXVsdCBIVE1MIGZvcm0gY29udHJvbHMgYW5kIG91ciBjdXN0b20gZm9ybSBjb250cm9scyAoZS5nLiwgaW5wdXQgZ3JvdXBzKS5cblxuLmZvcm0taW5saW5lIHtcbiAgZGlzcGxheTogZmxleDtcbiAgZmxleC1mbG93OiByb3cgd3JhcDtcbiAgYWxpZ24taXRlbXM6IGNlbnRlcjsgLy8gUHJldmVudCBzaG9ydGVyIGVsZW1lbnRzIGZyb20gZ3Jvd2luZyB0byBzYW1lIGhlaWdodCBhcyBvdGhlcnMgKGUuZy4sIHNtYWxsIGJ1dHRvbnMgZ3Jvd2luZyB0byBub3JtYWwgc2l6ZWQgYnV0dG9uIGhlaWdodClcblxuICAvLyBCZWNhdXNlIHdlIHVzZSBmbGV4LCB0aGUgaW5pdGlhbCBzaXppbmcgb2YgY2hlY2tib3hlcyBpcyBjb2xsYXBzZWQgYW5kXG4gIC8vIGRvZXNuJ3Qgb2NjdXB5IHRoZSBmdWxsLXdpZHRoICh3aGljaCBpcyB3aGF0IHdlIHdhbnQgZm9yIHhzIGdyaWQgdGllciksXG4gIC8vIHNvIHdlIGZvcmNlIHRoYXQgaGVyZS5cbiAgLmZvcm0tY2hlY2sge1xuICAgIHdpZHRoOiAxMDAlO1xuICB9XG5cbiAgLy8gS2ljayBpbiB0aGUgaW5saW5lXG4gIEBpbmNsdWRlIG1lZGlhLWJyZWFrcG9pbnQtdXAoc20pIHtcbiAgICBsYWJlbCB7XG4gICAgICBkaXNwbGF5OiBmbGV4O1xuICAgICAgYWxpZ24taXRlbXM6IGNlbnRlcjtcbiAgICAgIGp1c3RpZnktY29udGVudDogY2VudGVyO1xuICAgICAgbWFyZ2luLWJvdHRvbTogMDtcbiAgICB9XG5cbiAgICAvLyBJbmxpbmUtYmxvY2sgYWxsIHRoZSB0aGluZ3MgZm9yIFwiaW5saW5lXCJcbiAgICAuZm9ybS1ncm91cCB7XG4gICAgICBkaXNwbGF5OiBmbGV4O1xuICAgICAgZmxleDogMCAwIGF1dG87XG4gICAgICBmbGV4LWZsb3c6IHJvdyB3cmFwO1xuICAgICAgYWxpZ24taXRlbXM6IGNlbnRlcjtcbiAgICAgIG1hcmdpbi1ib3R0b206IDA7XG4gICAgfVxuXG4gICAgLy8gQWxsb3cgZm9sa3MgdG8gKm5vdCogdXNlIGAuZm9ybS1ncm91cGBcbiAgICAuZm9ybS1jb250cm9sIHtcbiAgICAgIGRpc3BsYXk6IGlubGluZS1ibG9jaztcbiAgICAgIHdpZHRoOiBhdXRvOyAvLyBQcmV2ZW50IGxhYmVscyBmcm9tIHN0YWNraW5nIGFib3ZlIGlucHV0cyBpbiBgLmZvcm0tZ3JvdXBgXG4gICAgICB2ZXJ0aWNhbC1hbGlnbjogbWlkZGxlO1xuICAgIH1cblxuICAgIC8vIE1ha2Ugc3RhdGljIGNvbnRyb2xzIGJlaGF2ZSBsaWtlIHJlZ3VsYXIgb25lc1xuICAgIC5mb3JtLWNvbnRyb2wtcGxhaW50ZXh0IHtcbiAgICAgIGRpc3BsYXk6IGlubGluZS1ibG9jaztcbiAgICB9XG5cbiAgICAuaW5wdXQtZ3JvdXAge1xuICAgICAgd2lkdGg6IGF1dG87XG4gICAgfVxuXG4gICAgLmZvcm0tY29udHJvbC1sYWJlbCB7XG4gICAgICBtYXJnaW4tYm90dG9tOiAwO1xuICAgICAgdmVydGljYWwtYWxpZ246IG1pZGRsZTtcbiAgICB9XG5cbiAgICAvLyBSZW1vdmUgZGVmYXVsdCBtYXJnaW4gb24gcmFkaW9zL2NoZWNrYm94ZXMgdGhhdCB3ZXJlIHVzZWQgZm9yIHN0YWNraW5nLCBhbmRcbiAgICAvLyB0aGVuIHVuZG8gdGhlIGZsb2F0aW5nIG9mIHJhZGlvcyBhbmQgY2hlY2tib3hlcyB0byBtYXRjaC5cbiAgICAuZm9ybS1jaGVjayB7XG4gICAgICBkaXNwbGF5OiBmbGV4O1xuICAgICAgYWxpZ24taXRlbXM6IGNlbnRlcjtcbiAgICAgIGp1c3RpZnktY29udGVudDogY2VudGVyO1xuICAgICAgd2lkdGg6IGF1dG87XG4gICAgICBtYXJnaW4tdG9wOiAwO1xuICAgICAgbWFyZ2luLWJvdHRvbTogMDtcbiAgICB9XG4gICAgLmZvcm0tY2hlY2stbGFiZWwge1xuICAgICAgcGFkZGluZy1sZWZ0OiAwO1xuICAgIH1cbiAgICAuZm9ybS1jaGVjay1pbnB1dCB7XG4gICAgICBwb3NpdGlvbjogcmVsYXRpdmU7XG4gICAgICBtYXJnaW4tdG9wOiAwO1xuICAgICAgbWFyZ2luLXJpZ2h0OiAkZm9ybS1jaGVjay1pbnB1dC1tYXJnaW4teDtcbiAgICAgIG1hcmdpbi1sZWZ0OiAwO1xuICAgIH1cblxuICAgIC8vIEN1c3RvbSBmb3JtIGNvbnRyb2xzXG4gICAgLmN1c3RvbS1jb250cm9sIHtcbiAgICAgIGRpc3BsYXk6IGZsZXg7XG4gICAgICBhbGlnbi1pdGVtczogY2VudGVyO1xuICAgICAganVzdGlmeS1jb250ZW50OiBjZW50ZXI7XG4gICAgICBwYWRkaW5nLWxlZnQ6IDA7XG4gICAgfVxuICAgIC5jdXN0b20tY29udHJvbC1pbmRpY2F0b3Ige1xuICAgICAgcG9zaXRpb246IHN0YXRpYztcbiAgICAgIGRpc3BsYXk6IGlubGluZS1ibG9jaztcbiAgICAgIG1hcmdpbi1yaWdodDogJGZvcm0tY2hlY2staW5wdXQtbWFyZ2luLXg7IC8vIEZsZXhib3ggYWxpZ25tZW50IG1lYW5zIHdlIGxvc2Ugb3VyIEhUTUwgc3BhY2UgaGVyZSwgc28gd2UgY29tcGVuc2F0ZS5cbiAgICAgIHZlcnRpY2FsLWFsaWduOiB0ZXh0LWJvdHRvbTtcbiAgICB9XG5cbiAgICAvLyBSZS1vdmVycmlkZSB0aGUgZmVlZGJhY2sgaWNvbi5cbiAgICAuaGFzLWZlZWRiYWNrIC5mb3JtLWNvbnRyb2wtZmVlZGJhY2sge1xuICAgICAgdG9wOiAwO1xuICAgIH1cbiAgfVxufVxuIiwiLy8gRm9ybSBjb250cm9sIGZvY3VzIHN0YXRlXG4vL1xuLy8gR2VuZXJhdGUgYSBjdXN0b21pemVkIGZvY3VzIHN0YXRlIGFuZCBmb3IgYW55IGlucHV0IHdpdGggdGhlIHNwZWNpZmllZCBjb2xvcixcbi8vIHdoaWNoIGRlZmF1bHRzIHRvIHRoZSBgQGlucHV0LWJvcmRlci1jb2xvci1mb2N1c2AgdmFyaWFibGUuXG4vL1xuLy8gV2UgaGlnaGx5IGVuY291cmFnZSB5b3UgdG8gbm90IGN1c3RvbWl6ZSB0aGUgZGVmYXVsdCB2YWx1ZSwgYnV0IGluc3RlYWQgdXNlXG4vLyB0aGlzIHRvIHR3ZWFrIGNvbG9ycyBvbiBhbiBhcy1uZWVkZWQgYmFzaXMuIFRoaXMgYWVzdGhldGljIGNoYW5nZSBpcyBiYXNlZCBvblxuLy8gV2ViS2l0J3MgZGVmYXVsdCBzdHlsZXMsIGJ1dCBhcHBsaWNhYmxlIHRvIGEgd2lkZXIgcmFuZ2Ugb2YgYnJvd3NlcnMuIEl0c1xuLy8gdXNhYmlsaXR5IGFuZCBhY2Nlc3NpYmlsaXR5IHNob3VsZCBiZSB0YWtlbiBpbnRvIGFjY291bnQgd2l0aCBhbnkgY2hhbmdlLlxuLy9cbi8vIEV4YW1wbGUgdXNhZ2U6IGNoYW5nZSB0aGUgZGVmYXVsdCBibHVlIGJvcmRlciBhbmQgc2hhZG93IHRvIHdoaXRlIGZvciBiZXR0ZXJcbi8vIGNvbnRyYXN0IGFnYWluc3QgYSBkYXJrIGdyYXkgYmFja2dyb3VuZC5cbkBtaXhpbiBmb3JtLWNvbnRyb2wtZm9jdXMoKSB7XG4gICY6Zm9jdXMge1xuICAgIGNvbG9yOiAkaW5wdXQtZm9jdXMtY29sb3I7XG4gICAgYmFja2dyb3VuZC1jb2xvcjogJGlucHV0LWZvY3VzLWJnO1xuICAgIGJvcmRlci1jb2xvcjogJGlucHV0LWZvY3VzLWJvcmRlci1jb2xvcjtcbiAgICBvdXRsaW5lOiBub25lO1xuICAgIEBpbmNsdWRlIGJveC1zaGFkb3coJGlucHV0LWZvY3VzLWJveC1zaGFkb3cpO1xuICB9XG59XG5cblxuQG1peGluIGZvcm0tdmFsaWRhdGlvbi1zdGF0ZSgkc3RhdGUsICRjb2xvcikge1xuXG4gIC5mb3JtLWNvbnRyb2wsXG4gIC5jdXN0b20tc2VsZWN0IHtcbiAgICAud2FzLXZhbGlkYXRlZCAmOiN7JHN0YXRlfSxcbiAgICAmLmlzLSN7JHN0YXRlfSB7XG4gICAgICBib3JkZXItY29sb3I6ICRjb2xvcjtcblxuICAgICAgJjpmb2N1cyB7XG4gICAgICAgIGJveC1zaGFkb3c6IDAgMCAwIC4ycmVtIHJnYmEoJGNvbG9yLC4yNSk7XG4gICAgICB9XG5cbiAgICAgIH4gLmludmFsaWQtZmVlZGJhY2ssXG4gICAgICB+IC5pbnZhbGlkLXRvb2x0aXAge1xuICAgICAgICBkaXNwbGF5OiBibG9jaztcbiAgICAgIH1cbiAgICB9XG4gIH1cblxuXG4gIC8vIFRPRE86IHJlZG8gY2hlY2sgbWFya3VwIGxvbCBjcmFwXG4gIC5mb3JtLWNoZWNrLWlucHV0IHtcbiAgICAud2FzLXZhbGlkYXRlZCAmOiN7JHN0YXRlfSxcbiAgICAmLmlzLSN7JHN0YXRlfSB7XG4gICAgICArIC5mb3JtLWNoZWNrLWxhYmVsIHtcbiAgICAgICAgY29sb3I6ICRjb2xvcjtcbiAgICAgIH1cbiAgICB9XG4gIH1cblxuICAvLyBjdXN0b20gcmFkaW9zIGFuZCBjaGVja3NcbiAgLmN1c3RvbS1jb250cm9sLWlucHV0IHtcbiAgICAud2FzLXZhbGlkYXRlZCAmOiN7JHN0YXRlfSxcbiAgICAmLmlzLSN7JHN0YXRlfSB7XG4gICAgICB+IC5jdXN0b20tY29udHJvbC1pbmRpY2F0b3Ige1xuICAgICAgICBiYWNrZ3JvdW5kLWNvbG9yOiByZ2JhKCRjb2xvciwgLjI1KTtcbiAgICAgIH1cbiAgICAgIH4gLmN1c3RvbS1jb250cm9sLWRlc2NyaXB0aW9uIHtcbiAgICAgICAgY29sb3I6ICRjb2xvcjtcbiAgICAgIH1cbiAgICB9XG4gIH1cblxuICAvLyBjdXN0b20gZmlsZVxuICAuY3VzdG9tLWZpbGUtaW5wdXQge1xuICAgIC53YXMtdmFsaWRhdGVkICY6I3skc3RhdGV9LFxuICAgICYuaXMtI3skc3RhdGV9IHtcbiAgICAgIH4gLmN1c3RvbS1maWxlLWNvbnRyb2wge1xuICAgICAgICBib3JkZXItY29sb3I6ICRjb2xvcjtcblxuICAgICAgICAmOjpiZWZvcmUgeyBib3JkZXItY29sb3I6IGluaGVyaXQ7IH1cbiAgICAgIH1cbiAgICAgICY6Zm9jdXMge1xuICAgICAgICBib3gtc2hhZG93OiAwIDAgMCAuMnJlbSByZ2JhKCRjb2xvciwuMjUpO1xuICAgICAgfVxuICAgIH1cbiAgfVxufVxuIiwiLy8gc2Nzcy1saW50OmRpc2FibGUgUXVhbGlmeWluZ0VsZW1lbnRcblxuLy9cbi8vIEJhc2Ugc3R5bGVzXG4vL1xuXG4uYnRuIHtcbiAgZGlzcGxheTogaW5saW5lLWJsb2NrO1xuICBmb250LXdlaWdodDogJGJ0bi1mb250LXdlaWdodDtcbiAgdGV4dC1hbGlnbjogY2VudGVyO1xuICB3aGl0ZS1zcGFjZTogbm93cmFwO1xuICB2ZXJ0aWNhbC1hbGlnbjogbWlkZGxlO1xuICB1c2VyLXNlbGVjdDogbm9uZTtcbiAgYm9yZGVyOiAkaW5wdXQtYnRuLWJvcmRlci13aWR0aCBzb2xpZCB0cmFuc3BhcmVudDtcbiAgQGluY2x1ZGUgYnV0dG9uLXNpemUoJGlucHV0LWJ0bi1wYWRkaW5nLXksICRpbnB1dC1idG4tcGFkZGluZy14LCAkZm9udC1zaXplLWJhc2UsICRpbnB1dC1idG4tbGluZS1oZWlnaHQsICRidG4tYm9yZGVyLXJhZGl1cyk7XG4gIEBpbmNsdWRlIHRyYW5zaXRpb24oJGJ0bi10cmFuc2l0aW9uKTtcblxuICAvLyBTaGFyZSBob3ZlciBhbmQgZm9jdXMgc3R5bGVzXG4gIEBpbmNsdWRlIGhvdmVyLWZvY3VzIHtcbiAgICB0ZXh0LWRlY29yYXRpb246IG5vbmU7XG4gIH1cbiAgJjpmb2N1cyxcbiAgJi5mb2N1cyB7XG4gICAgb3V0bGluZTogMDtcbiAgICBib3gtc2hhZG93OiAkYnRuLWZvY3VzLWJveC1zaGFkb3c7XG4gIH1cblxuICAvLyBEaXNhYmxlZCBjb21lcyBmaXJzdCBzbyBhY3RpdmUgY2FuIHByb3Blcmx5IHJlc3R5bGVcbiAgJi5kaXNhYmxlZCxcbiAgJjpkaXNhYmxlZCB7XG4gICAgb3BhY2l0eTogLjY1O1xuICAgIEBpbmNsdWRlIGJveC1zaGFkb3cobm9uZSk7XG4gIH1cblxuICAmOmFjdGl2ZSxcbiAgJi5hY3RpdmUge1xuICAgIGJhY2tncm91bmQtaW1hZ2U6IG5vbmU7XG4gICAgQGluY2x1ZGUgYm94LXNoYWRvdygkYnRuLWZvY3VzLWJveC1zaGFkb3csICRidG4tYWN0aXZlLWJveC1zaGFkb3cpO1xuICB9XG59XG5cbi8vIEZ1dHVyZS1wcm9vZiBkaXNhYmxpbmcgb2YgY2xpY2tzIG9uIGA8YT5gIGVsZW1lbnRzXG5hLmJ0bi5kaXNhYmxlZCxcbmZpZWxkc2V0W2Rpc2FibGVkXSBhLmJ0biB7XG4gIHBvaW50ZXItZXZlbnRzOiBub25lO1xufVxuXG5cbi8vXG4vLyBBbHRlcm5hdGUgYnV0dG9uc1xuLy9cblxuQGVhY2ggJGNvbG9yLCAkdmFsdWUgaW4gJHRoZW1lLWNvbG9ycyB7XG4gIC5idG4tI3skY29sb3J9IHtcbiAgICBAaW5jbHVkZSBidXR0b24tdmFyaWFudCgkdmFsdWUsICR2YWx1ZSk7XG4gIH1cbn1cblxuQGVhY2ggJGNvbG9yLCAkdmFsdWUgaW4gJHRoZW1lLWNvbG9ycyB7XG4gIC5idG4tb3V0bGluZS0jeyRjb2xvcn0ge1xuICAgIEBpbmNsdWRlIGJ1dHRvbi1vdXRsaW5lLXZhcmlhbnQoJHZhbHVlLCAjZmZmKTtcbiAgfVxufVxuXG5cbi8vXG4vLyBMaW5rIGJ1dHRvbnNcbi8vXG5cbi8vIE1ha2UgYSBidXR0b24gbG9vayBhbmQgYmVoYXZlIGxpa2UgYSBsaW5rXG4uYnRuLWxpbmsge1xuICBmb250LXdlaWdodDogJGZvbnQtd2VpZ2h0LW5vcm1hbDtcbiAgY29sb3I6ICRsaW5rLWNvbG9yO1xuICBib3JkZXItcmFkaXVzOiAwO1xuXG4gICYsXG4gICY6YWN0aXZlLFxuICAmLmFjdGl2ZSxcbiAgJjpkaXNhYmxlZCB7XG4gICAgYmFja2dyb3VuZC1jb2xvcjogdHJhbnNwYXJlbnQ7XG4gICAgQGluY2x1ZGUgYm94LXNoYWRvdyhub25lKTtcbiAgfVxuICAmLFxuICAmOmZvY3VzLFxuICAmOmFjdGl2ZSB7XG4gICAgYm9yZGVyLWNvbG9yOiB0cmFuc3BhcmVudDtcbiAgICBib3gtc2hhZG93OiBub25lO1xuICB9XG4gIEBpbmNsdWRlIGhvdmVyIHtcbiAgICBib3JkZXItY29sb3I6IHRyYW5zcGFyZW50O1xuICB9XG4gIEBpbmNsdWRlIGhvdmVyLWZvY3VzIHtcbiAgICBjb2xvcjogJGxpbmstaG92ZXItY29sb3I7XG4gICAgdGV4dC1kZWNvcmF0aW9uOiAkbGluay1ob3Zlci1kZWNvcmF0aW9uO1xuICAgIGJhY2tncm91bmQtY29sb3I6IHRyYW5zcGFyZW50O1xuICB9XG4gICY6ZGlzYWJsZWQge1xuICAgIGNvbG9yOiAkYnRuLWxpbmstZGlzYWJsZWQtY29sb3I7XG5cbiAgICBAaW5jbHVkZSBob3Zlci1mb2N1cyB7XG4gICAgICB0ZXh0LWRlY29yYXRpb246IG5vbmU7XG4gICAgfVxuICB9XG59XG5cblxuLy9cbi8vIEJ1dHRvbiBTaXplc1xuLy9cblxuLmJ0bi1sZyB7XG4gIEBpbmNsdWRlIGJ1dHRvbi1zaXplKCRpbnB1dC1idG4tcGFkZGluZy15LWxnLCAkaW5wdXQtYnRuLXBhZGRpbmcteC1sZywgJGZvbnQtc2l6ZS1sZywgJGxpbmUtaGVpZ2h0LWxnLCAkYnRuLWJvcmRlci1yYWRpdXMtbGcpO1xufVxuXG4uYnRuLXNtIHtcbiAgQGluY2x1ZGUgYnV0dG9uLXNpemUoJGlucHV0LWJ0bi1wYWRkaW5nLXktc20sICRpbnB1dC1idG4tcGFkZGluZy14LXNtLCAkZm9udC1zaXplLXNtLCAkbGluZS1oZWlnaHQtc20sICRidG4tYm9yZGVyLXJhZGl1cy1zbSk7XG59XG5cblxuLy9cbi8vIEJsb2NrIGJ1dHRvblxuLy9cblxuLmJ0bi1ibG9jayB7XG4gIGRpc3BsYXk6IGJsb2NrO1xuICB3aWR0aDogMTAwJTtcbn1cblxuLy8gVmVydGljYWxseSBzcGFjZSBvdXQgbXVsdGlwbGUgYmxvY2sgYnV0dG9uc1xuLmJ0bi1ibG9jayArIC5idG4tYmxvY2sge1xuICBtYXJnaW4tdG9wOiAkYnRuLWJsb2NrLXNwYWNpbmcteTtcbn1cblxuLy8gU3BlY2lmaWNpdHkgb3ZlcnJpZGVzXG5pbnB1dFt0eXBlPVwic3VibWl0XCJdLFxuaW5wdXRbdHlwZT1cInJlc2V0XCJdLFxuaW5wdXRbdHlwZT1cImJ1dHRvblwiXSB7XG4gICYuYnRuLWJsb2NrIHtcbiAgICB3aWR0aDogMTAwJTtcbiAgfVxufVxuIiwiLy8gQnV0dG9uIHZhcmlhbnRzXG4vL1xuLy8gRWFzaWx5IHB1bXAgb3V0IGRlZmF1bHQgc3R5bGVzLCBhcyB3ZWxsIGFzIDpob3ZlciwgOmZvY3VzLCA6YWN0aXZlLFxuLy8gYW5kIGRpc2FibGVkIG9wdGlvbnMgZm9yIGFsbCBidXR0b25zXG5cbkBtaXhpbiBidXR0b24tdmFyaWFudCgkYmFja2dyb3VuZCwgJGJvcmRlciwgJGFjdGl2ZS1iYWNrZ3JvdW5kOiBkYXJrZW4oJGJhY2tncm91bmQsIDcuNSUpLCAkYWN0aXZlLWJvcmRlcjogZGFya2VuKCRib3JkZXIsIDEwJSkpIHtcbiAgQGluY2x1ZGUgY29sb3IteWlxKCRiYWNrZ3JvdW5kKTtcbiAgYmFja2dyb3VuZC1jb2xvcjogJGJhY2tncm91bmQ7XG4gIGJvcmRlci1jb2xvcjogJGJvcmRlcjtcbiAgQGluY2x1ZGUgYm94LXNoYWRvdygkYnRuLWJveC1zaGFkb3cpO1xuXG4gICY6aG92ZXIge1xuICAgIEBpbmNsdWRlIGNvbG9yLXlpcSgkYmFja2dyb3VuZCk7XG4gICAgYmFja2dyb3VuZC1jb2xvcjogJGFjdGl2ZS1iYWNrZ3JvdW5kO1xuICAgIGJvcmRlci1jb2xvcjogJGFjdGl2ZS1ib3JkZXI7XG4gIH1cblxuICAmOmZvY3VzLFxuICAmLmZvY3VzIHtcbiAgICAvLyBBdm9pZCB1c2luZyBtaXhpbiBzbyB3ZSBjYW4gcGFzcyBjdXN0b20gZm9jdXMgc2hhZG93IHByb3Blcmx5XG4gICAgQGlmICRlbmFibGUtc2hhZG93cyB7XG4gICAgICBib3gtc2hhZG93OiAkYnRuLWJveC1zaGFkb3csIDAgMCAwIDNweCByZ2JhKCRib3JkZXIsIC41KTtcbiAgICB9IEBlbHNlIHtcbiAgICAgIGJveC1zaGFkb3c6IDAgMCAwIDNweCByZ2JhKCRib3JkZXIsIC41KTtcbiAgICB9XG4gIH1cblxuICAvLyBEaXNhYmxlZCBjb21lcyBmaXJzdCBzbyBhY3RpdmUgY2FuIHByb3Blcmx5IHJlc3R5bGVcbiAgJi5kaXNhYmxlZCxcbiAgJjpkaXNhYmxlZCB7XG4gICAgYmFja2dyb3VuZC1jb2xvcjogJGJhY2tncm91bmQ7XG4gICAgYm9yZGVyLWNvbG9yOiAkYm9yZGVyO1xuICB9XG5cbiAgJjphY3RpdmUsXG4gICYuYWN0aXZlLFxuICAuc2hvdyA+ICYuZHJvcGRvd24tdG9nZ2xlIHtcbiAgICBiYWNrZ3JvdW5kLWNvbG9yOiAkYWN0aXZlLWJhY2tncm91bmQ7XG4gICAgYmFja2dyb3VuZC1pbWFnZTogbm9uZTsgLy8gUmVtb3ZlIHRoZSBncmFkaWVudCBmb3IgdGhlIHByZXNzZWQvYWN0aXZlIHN0YXRlXG4gICAgYm9yZGVyLWNvbG9yOiAkYWN0aXZlLWJvcmRlcjtcbiAgICBAaW5jbHVkZSBib3gtc2hhZG93KCRidG4tYWN0aXZlLWJveC1zaGFkb3cpO1xuICB9XG59XG5cbkBtaXhpbiBidXR0b24tb3V0bGluZS12YXJpYW50KCRjb2xvciwgJGNvbG9yLWhvdmVyOiAjZmZmKSB7XG4gIGNvbG9yOiAkY29sb3I7XG4gIGJhY2tncm91bmQtY29sb3I6IHRyYW5zcGFyZW50O1xuICBiYWNrZ3JvdW5kLWltYWdlOiBub25lO1xuICBib3JkZXItY29sb3I6ICRjb2xvcjtcblxuICBAaW5jbHVkZSBob3ZlciB7XG4gICAgY29sb3I6ICRjb2xvci1ob3ZlcjtcbiAgICBiYWNrZ3JvdW5kLWNvbG9yOiAkY29sb3I7XG4gICAgYm9yZGVyLWNvbG9yOiAkY29sb3I7XG4gIH1cblxuICAmOmZvY3VzLFxuICAmLmZvY3VzIHtcbiAgICBib3gtc2hhZG93OiAwIDAgMCAzcHggcmdiYSgkY29sb3IsIC41KTtcbiAgfVxuXG4gICYuZGlzYWJsZWQsXG4gICY6ZGlzYWJsZWQge1xuICAgIGNvbG9yOiAkY29sb3I7XG4gICAgYmFja2dyb3VuZC1jb2xvcjogdHJhbnNwYXJlbnQ7XG4gIH1cblxuICAmOmFjdGl2ZSxcbiAgJi5hY3RpdmUsXG4gIC5zaG93ID4gJi5kcm9wZG93bi10b2dnbGUge1xuICAgIGNvbG9yOiAkY29sb3ItaG92ZXI7XG4gICAgYmFja2dyb3VuZC1jb2xvcjogJGNvbG9yO1xuICAgIGJvcmRlci1jb2xvcjogJGNvbG9yO1xuICB9XG59XG5cbi8vIEJ1dHRvbiBzaXplc1xuQG1peGluIGJ1dHRvbi1zaXplKCRwYWRkaW5nLXksICRwYWRkaW5nLXgsICRmb250LXNpemUsICRsaW5lLWhlaWdodCwgJGJvcmRlci1yYWRpdXMpIHtcbiAgcGFkZGluZzogJHBhZGRpbmcteSAkcGFkZGluZy14O1xuICBmb250LXNpemU6ICRmb250LXNpemU7XG4gIGxpbmUtaGVpZ2h0OiAkbGluZS1oZWlnaHQ7XG4gIEBpbmNsdWRlIGJvcmRlci1yYWRpdXMoJGJvcmRlci1yYWRpdXMpO1xufVxuIiwiLmZhZGUge1xuICBvcGFjaXR5OiAwO1xuICBAaW5jbHVkZSB0cmFuc2l0aW9uKCR0cmFuc2l0aW9uLWZhZGUpO1xuXG4gICYuc2hvdyB7XG4gICAgb3BhY2l0eTogMTtcbiAgfVxufVxuXG4uY29sbGFwc2Uge1xuICBkaXNwbGF5OiBub25lO1xuICAmLnNob3cge1xuICAgIGRpc3BsYXk6IGJsb2NrO1xuICB9XG59XG5cbnRyIHtcbiAgJi5jb2xsYXBzZS5zaG93IHtcbiAgICBkaXNwbGF5OiB0YWJsZS1yb3c7XG4gIH1cbn1cblxudGJvZHkge1xuICAmLmNvbGxhcHNlLnNob3cge1xuICAgIGRpc3BsYXk6IHRhYmxlLXJvdy1ncm91cDtcbiAgfVxufVxuXG4uY29sbGFwc2luZyB7XG4gIHBvc2l0aW9uOiByZWxhdGl2ZTtcbiAgaGVpZ2h0OiAwO1xuICBvdmVyZmxvdzogaGlkZGVuO1xuICBAaW5jbHVkZSB0cmFuc2l0aW9uKCR0cmFuc2l0aW9uLWNvbGxhcHNlKTtcbn1cbiIsIi8vIFRoZSBkcm9wZG93biB3cmFwcGVyIChgPGRpdj5gKVxuLmRyb3B1cCxcbi5kcm9wZG93biB7XG4gIHBvc2l0aW9uOiByZWxhdGl2ZTtcbn1cblxuLmRyb3Bkb3duLXRvZ2dsZSB7XG4gIC8vIEdlbmVyYXRlIHRoZSBjYXJldCBhdXRvbWF0aWNhbGx5XG4gICY6OmFmdGVyIHtcbiAgICBkaXNwbGF5OiBpbmxpbmUtYmxvY2s7XG4gICAgd2lkdGg6IDA7XG4gICAgaGVpZ2h0OiAwO1xuICAgIG1hcmdpbi1sZWZ0OiAkY2FyZXQtd2lkdGggKiAuODU7XG4gICAgdmVydGljYWwtYWxpZ246ICRjYXJldC13aWR0aCAqIC44NTtcbiAgICBjb250ZW50OiBcIlwiO1xuICAgIGJvcmRlci10b3A6ICRjYXJldC13aWR0aCBzb2xpZDtcbiAgICBib3JkZXItcmlnaHQ6ICRjYXJldC13aWR0aCBzb2xpZCB0cmFuc3BhcmVudDtcbiAgICBib3JkZXItbGVmdDogJGNhcmV0LXdpZHRoIHNvbGlkIHRyYW5zcGFyZW50O1xuICB9XG5cbiAgJjplbXB0eTo6YWZ0ZXIge1xuICAgIG1hcmdpbi1sZWZ0OiAwO1xuICB9XG59XG5cbi8vIEFsbG93IGZvciBkcm9wZG93bnMgdG8gZ28gYm90dG9tIHVwIChha2EsIGRyb3B1cC1tZW51KVxuLy8gSnVzdCBhZGQgLmRyb3B1cCBhZnRlciB0aGUgc3RhbmRhcmQgLmRyb3Bkb3duIGNsYXNzIGFuZCB5b3UncmUgc2V0LlxuLmRyb3B1cCB7XG4gIC5kcm9wZG93bi1tZW51IHtcbiAgICBtYXJnaW4tdG9wOiAwO1xuICAgIG1hcmdpbi1ib3R0b206ICRkcm9wZG93bi1zcGFjZXI7XG4gIH1cblxuICAuZHJvcGRvd24tdG9nZ2xlIHtcbiAgICAmOjphZnRlciB7XG4gICAgICBib3JkZXItdG9wOiAwO1xuICAgICAgYm9yZGVyLWJvdHRvbTogJGNhcmV0LXdpZHRoIHNvbGlkO1xuICAgIH1cbiAgfVxufVxuXG4vLyBUaGUgZHJvcGRvd24gbWVudVxuLmRyb3Bkb3duLW1lbnUge1xuICBwb3NpdGlvbjogYWJzb2x1dGU7XG4gIHRvcDogMTAwJTtcbiAgbGVmdDogMDtcbiAgei1pbmRleDogJHppbmRleC1kcm9wZG93bjtcbiAgZGlzcGxheTogbm9uZTsgLy8gbm9uZSBieSBkZWZhdWx0LCBidXQgYmxvY2sgb24gXCJvcGVuXCIgb2YgdGhlIG1lbnVcbiAgZmxvYXQ6IGxlZnQ7XG4gIG1pbi13aWR0aDogJGRyb3Bkb3duLW1pbi13aWR0aDtcbiAgcGFkZGluZzogJGRyb3Bkb3duLXBhZGRpbmcteSAwO1xuICBtYXJnaW46ICRkcm9wZG93bi1zcGFjZXIgMCAwOyAvLyBvdmVycmlkZSBkZWZhdWx0IHVsXG4gIGZvbnQtc2l6ZTogJGZvbnQtc2l6ZS1iYXNlOyAvLyBSZWRlY2xhcmUgYmVjYXVzZSBuZXN0aW5nIGNhbiBjYXVzZSBpbmhlcml0YW5jZSBpc3N1ZXNcbiAgY29sb3I6ICRib2R5LWNvbG9yO1xuICB0ZXh0LWFsaWduOiBsZWZ0OyAvLyBFbnN1cmVzIHByb3BlciBhbGlnbm1lbnQgaWYgcGFyZW50IGhhcyBpdCBjaGFuZ2VkIChlLmcuLCBtb2RhbCBmb290ZXIpXG4gIGxpc3Qtc3R5bGU6IG5vbmU7XG4gIGJhY2tncm91bmQtY29sb3I6ICRkcm9wZG93bi1iZztcbiAgYmFja2dyb3VuZC1jbGlwOiBwYWRkaW5nLWJveDtcbiAgYm9yZGVyOiAkZHJvcGRvd24tYm9yZGVyLXdpZHRoIHNvbGlkICRkcm9wZG93bi1ib3JkZXItY29sb3I7XG4gIEBpbmNsdWRlIGJvcmRlci1yYWRpdXMoJGJvcmRlci1yYWRpdXMpO1xuICBAaW5jbHVkZSBib3gtc2hhZG93KCRkcm9wZG93bi1ib3gtc2hhZG93KTtcbn1cblxuLy8gRGl2aWRlcnMgKGJhc2ljYWxseSBhbiBgPGhyPmApIHdpdGhpbiB0aGUgZHJvcGRvd25cbi5kcm9wZG93bi1kaXZpZGVyIHtcbiAgQGluY2x1ZGUgbmF2LWRpdmlkZXIoJGRyb3Bkb3duLWRpdmlkZXItYmcpO1xufVxuXG4vLyBMaW5rcywgYnV0dG9ucywgYW5kIG1vcmUgd2l0aGluIHRoZSBkcm9wZG93biBtZW51XG4vL1xuLy8gYDxidXR0b24+YC1zcGVjaWZpYyBzdHlsZXMgYXJlIGRlbm90ZWQgd2l0aCBgLy8gRm9yIDxidXR0b24+c2Bcbi5kcm9wZG93bi1pdGVtIHtcbiAgZGlzcGxheTogYmxvY2s7XG4gIHdpZHRoOiAxMDAlOyAvLyBGb3IgYDxidXR0b24+YHNcbiAgcGFkZGluZzogJGRyb3Bkb3duLWl0ZW0tcGFkZGluZy15ICRkcm9wZG93bi1pdGVtLXBhZGRpbmcteDtcbiAgY2xlYXI6IGJvdGg7XG4gIGZvbnQtd2VpZ2h0OiAkZm9udC13ZWlnaHQtbm9ybWFsO1xuICBjb2xvcjogJGRyb3Bkb3duLWxpbmstY29sb3I7XG4gIHRleHQtYWxpZ246IGluaGVyaXQ7IC8vIEZvciBgPGJ1dHRvbj5gc1xuICB3aGl0ZS1zcGFjZTogbm93cmFwOyAvLyBwcmV2ZW50IGxpbmtzIGZyb20gcmFuZG9tbHkgYnJlYWtpbmcgb250byBuZXcgbGluZXNcbiAgYmFja2dyb3VuZDogbm9uZTsgLy8gRm9yIGA8YnV0dG9uPmBzXG4gIGJvcmRlcjogMDsgLy8gRm9yIGA8YnV0dG9uPmBzXG5cbiAgQGluY2x1ZGUgaG92ZXItZm9jdXMge1xuICAgIGNvbG9yOiAkZHJvcGRvd24tbGluay1ob3Zlci1jb2xvcjtcbiAgICB0ZXh0LWRlY29yYXRpb246IG5vbmU7XG4gICAgYmFja2dyb3VuZC1jb2xvcjogJGRyb3Bkb3duLWxpbmstaG92ZXItYmc7XG4gIH1cblxuICAmLmFjdGl2ZSxcbiAgJjphY3RpdmUge1xuICAgIGNvbG9yOiAkZHJvcGRvd24tbGluay1hY3RpdmUtY29sb3I7XG4gICAgdGV4dC1kZWNvcmF0aW9uOiBub25lO1xuICAgIGJhY2tncm91bmQtY29sb3I6ICRkcm9wZG93bi1saW5rLWFjdGl2ZS1iZztcbiAgfVxuXG4gICYuZGlzYWJsZWQsXG4gICY6ZGlzYWJsZWQge1xuICAgIGNvbG9yOiAkZHJvcGRvd24tbGluay1kaXNhYmxlZC1jb2xvcjtcbiAgICBiYWNrZ3JvdW5kLWNvbG9yOiB0cmFuc3BhcmVudDtcbiAgICAvLyBSZW1vdmUgQ1NTIGdyYWRpZW50cyBpZiB0aGV5J3JlIGVuYWJsZWRcbiAgICBAaWYgJGVuYWJsZS1ncmFkaWVudHMge1xuICAgICAgYmFja2dyb3VuZC1pbWFnZTogbm9uZTtcbiAgICB9XG4gIH1cbn1cblxuLy8gT3BlbiBzdGF0ZSBmb3IgdGhlIGRyb3Bkb3duXG4uc2hvdyB7XG4gIC8vIFJlbW92ZSB0aGUgb3V0bGluZSB3aGVuIDpmb2N1cyBpcyB0cmlnZ2VyZWRcbiAgPiBhIHtcbiAgICBvdXRsaW5lOiAwO1xuICB9XG59XG5cbi5kcm9wZG93bi1tZW51LnNob3cge1xuICBkaXNwbGF5OiBibG9jaztcbn1cblxuLy8gRHJvcGRvd24gc2VjdGlvbiBoZWFkZXJzXG4uZHJvcGRvd24taGVhZGVyIHtcbiAgZGlzcGxheTogYmxvY2s7XG4gIHBhZGRpbmc6ICRkcm9wZG93bi1wYWRkaW5nLXkgJGRyb3Bkb3duLWl0ZW0tcGFkZGluZy14O1xuICBtYXJnaW4tYm90dG9tOiAwOyAvLyBmb3IgdXNlIHdpdGggaGVhZGluZyBlbGVtZW50c1xuICBmb250LXNpemU6ICRmb250LXNpemUtc207XG4gIGNvbG9yOiAkZHJvcGRvd24taGVhZGVyLWNvbG9yO1xuICB3aGl0ZS1zcGFjZTogbm93cmFwOyAvLyBhcyB3aXRoID4gbGkgPiBhXG59XG4iLCIvLyBIb3Jpem9udGFsIGRpdmlkZXJzXG4vL1xuLy8gRGl2aWRlcnMgKGJhc2ljYWxseSBhbiBocikgd2l0aGluIGRyb3Bkb3ducyBhbmQgbmF2IGxpc3RzXG5cbkBtaXhpbiBuYXYtZGl2aWRlcigkY29sb3I6ICNlNWU1ZTUpIHtcbiAgaGVpZ2h0OiAwO1xuICBtYXJnaW46ICgkc3BhY2VyIC8gMikgMDtcbiAgb3ZlcmZsb3c6IGhpZGRlbjtcbiAgYm9yZGVyLXRvcDogMXB4IHNvbGlkICRjb2xvcjtcbn1cbiIsIi8vIHNjc3MtbGludDpkaXNhYmxlIFF1YWxpZnlpbmdFbGVtZW50XG5cbi8vIE1ha2UgdGhlIGRpdiBiZWhhdmUgbGlrZSBhIGJ1dHRvblxuLmJ0bi1ncm91cCxcbi5idG4tZ3JvdXAtdmVydGljYWwge1xuICBwb3NpdGlvbjogcmVsYXRpdmU7XG4gIGRpc3BsYXk6IGlubGluZS1mbGV4O1xuICB2ZXJ0aWNhbC1hbGlnbjogbWlkZGxlOyAvLyBtYXRjaCAuYnRuIGFsaWdubWVudCBnaXZlbiBmb250LXNpemUgaGFjayBhYm92ZVxuXG4gID4gLmJ0biB7XG4gICAgcG9zaXRpb246IHJlbGF0aXZlO1xuICAgIGZsZXg6IDAgMSBhdXRvO1xuICAgIG1hcmdpbi1ib3R0b206IDA7XG5cbiAgICAvLyBCcmluZyB0aGUgaG92ZXIsIGZvY3VzZWQsIGFuZCBcImFjdGl2ZVwiIGJ1dHRvbnMgdG8gdGhlIGZyb250IHRvIG92ZXJsYXlcbiAgICAvLyB0aGUgYm9yZGVycyBwcm9wZXJseVxuICAgIEBpbmNsdWRlIGhvdmVyIHtcbiAgICAgIHotaW5kZXg6IDI7XG4gICAgfVxuICAgICY6Zm9jdXMsXG4gICAgJjphY3RpdmUsXG4gICAgJi5hY3RpdmUge1xuICAgICAgei1pbmRleDogMjtcbiAgICB9XG4gIH1cblxuICAvLyBQcmV2ZW50IGRvdWJsZSBib3JkZXJzIHdoZW4gYnV0dG9ucyBhcmUgbmV4dCB0byBlYWNoIG90aGVyXG4gIC5idG4gKyAuYnRuLFxuICAuYnRuICsgLmJ0bi1ncm91cCxcbiAgLmJ0bi1ncm91cCArIC5idG4sXG4gIC5idG4tZ3JvdXAgKyAuYnRuLWdyb3VwIHtcbiAgICBtYXJnaW4tbGVmdDogLSRpbnB1dC1idG4tYm9yZGVyLXdpZHRoO1xuICB9XG59XG5cbi8vIE9wdGlvbmFsOiBHcm91cCBtdWx0aXBsZSBidXR0b24gZ3JvdXBzIHRvZ2V0aGVyIGZvciBhIHRvb2xiYXJcbi5idG4tdG9vbGJhciB7XG4gIGRpc3BsYXk6IGZsZXg7XG4gIGZsZXgtd3JhcDogd3JhcDtcbiAganVzdGlmeS1jb250ZW50OiBmbGV4LXN0YXJ0O1xuXG4gIC5pbnB1dC1ncm91cCB7XG4gICAgd2lkdGg6IGF1dG87XG4gIH1cbn1cblxuLmJ0bi1ncm91cCA+IC5idG46bm90KDpmaXJzdC1jaGlsZCk6bm90KDpsYXN0LWNoaWxkKTpub3QoLmRyb3Bkb3duLXRvZ2dsZSkge1xuICBib3JkZXItcmFkaXVzOiAwO1xufVxuXG4vLyBTZXQgY29ybmVycyBpbmRpdmlkdWFsIGJlY2F1c2Ugc29tZXRpbWVzIGEgc2luZ2xlIGJ1dHRvbiBjYW4gYmUgaW4gYSAuYnRuLWdyb3VwIGFuZCB3ZSBuZWVkIDpmaXJzdC1jaGlsZCBhbmQgOmxhc3QtY2hpbGQgdG8gYm90aCBtYXRjaFxuLmJ0bi1ncm91cCA+IC5idG46Zmlyc3QtY2hpbGQge1xuICBtYXJnaW4tbGVmdDogMDtcblxuICAmOm5vdCg6bGFzdC1jaGlsZCk6bm90KC5kcm9wZG93bi10b2dnbGUpIHtcbiAgICBAaW5jbHVkZSBib3JkZXItcmlnaHQtcmFkaXVzKDApO1xuICB9XG59XG4vLyBOZWVkIC5kcm9wZG93bi10b2dnbGUgc2luY2UgOmxhc3QtY2hpbGQgZG9lc24ndCBhcHBseSBnaXZlbiBhIC5kcm9wZG93bi1tZW51IGltbWVkaWF0ZWx5IGFmdGVyIGl0XG4uYnRuLWdyb3VwID4gLmJ0bjpsYXN0LWNoaWxkOm5vdCg6Zmlyc3QtY2hpbGQpLFxuLmJ0bi1ncm91cCA+IC5kcm9wZG93bi10b2dnbGU6bm90KDpmaXJzdC1jaGlsZCkge1xuICBAaW5jbHVkZSBib3JkZXItbGVmdC1yYWRpdXMoMCk7XG59XG5cbi8vIEN1c3RvbSBlZGl0cyBmb3IgaW5jbHVkaW5nIGJ0bi1ncm91cHMgd2l0aGluIGJ0bi1ncm91cHMgKHVzZWZ1bCBmb3IgaW5jbHVkaW5nIGRyb3Bkb3duIGJ1dHRvbnMgd2l0aGluIGEgYnRuLWdyb3VwKVxuLmJ0bi1ncm91cCA+IC5idG4tZ3JvdXAge1xuICBmbG9hdDogbGVmdDtcbn1cbi5idG4tZ3JvdXAgPiAuYnRuLWdyb3VwOm5vdCg6Zmlyc3QtY2hpbGQpOm5vdCg6bGFzdC1jaGlsZCkgPiAuYnRuIHtcbiAgYm9yZGVyLXJhZGl1czogMDtcbn1cbi5idG4tZ3JvdXAgPiAuYnRuLWdyb3VwOmZpcnN0LWNoaWxkOm5vdCg6bGFzdC1jaGlsZCkge1xuICA+IC5idG46bGFzdC1jaGlsZCxcbiAgPiAuZHJvcGRvd24tdG9nZ2xlIHtcbiAgICBAaW5jbHVkZSBib3JkZXItcmlnaHQtcmFkaXVzKDApO1xuICB9XG59XG4uYnRuLWdyb3VwID4gLmJ0bi1ncm91cDpsYXN0LWNoaWxkOm5vdCg6Zmlyc3QtY2hpbGQpID4gLmJ0bjpmaXJzdC1jaGlsZCB7XG4gIEBpbmNsdWRlIGJvcmRlci1sZWZ0LXJhZGl1cygwKTtcbn1cblxuXG4vLyBTaXppbmdcbi8vXG4vLyBSZW1peCB0aGUgZGVmYXVsdCBidXR0b24gc2l6aW5nIGNsYXNzZXMgaW50byBuZXcgb25lcyBmb3IgZWFzaWVyIG1hbmlwdWxhdGlvbi5cblxuLmJ0bi1ncm91cC1zbSA+IC5idG4geyBAZXh0ZW5kIC5idG4tc207IH1cbi5idG4tZ3JvdXAtbGcgPiAuYnRuIHsgQGV4dGVuZCAuYnRuLWxnOyB9XG5cblxuLy9cbi8vIFNwbGl0IGJ1dHRvbiBkcm9wZG93bnNcbi8vXG5cbi5idG4gKyAuZHJvcGRvd24tdG9nZ2xlLXNwbGl0IHtcbiAgcGFkZGluZy1yaWdodDogJGlucHV0LWJ0bi1wYWRkaW5nLXggKiAuNzU7XG4gIHBhZGRpbmctbGVmdDogJGlucHV0LWJ0bi1wYWRkaW5nLXggKiAuNzU7XG5cbiAgJjo6YWZ0ZXIge1xuICAgIG1hcmdpbi1sZWZ0OiAwO1xuICB9XG59XG5cbi5idG4tc20gKyAuZHJvcGRvd24tdG9nZ2xlLXNwbGl0IHtcbiAgcGFkZGluZy1yaWdodDogJGlucHV0LWJ0bi1wYWRkaW5nLXgtc20gKiAuNzU7XG4gIHBhZGRpbmctbGVmdDogJGlucHV0LWJ0bi1wYWRkaW5nLXgtc20gKiAuNzU7XG59XG5cbi5idG4tbGcgKyAuZHJvcGRvd24tdG9nZ2xlLXNwbGl0IHtcbiAgcGFkZGluZy1yaWdodDogJGlucHV0LWJ0bi1wYWRkaW5nLXgtbGcgKiAuNzU7XG4gIHBhZGRpbmctbGVmdDogJGlucHV0LWJ0bi1wYWRkaW5nLXgtbGcgKiAuNzU7XG59XG5cblxuLy8gVGhlIGNsaWNrYWJsZSBidXR0b24gZm9yIHRvZ2dsaW5nIHRoZSBtZW51XG4vLyBTZXQgdGhlIHNhbWUgaW5zZXQgc2hhZG93IGFzIHRoZSA6YWN0aXZlIHN0YXRlXG4uYnRuLWdyb3VwLnNob3cgLmRyb3Bkb3duLXRvZ2dsZSB7XG4gIEBpbmNsdWRlIGJveC1zaGFkb3coJGJ0bi1hY3RpdmUtYm94LXNoYWRvdyk7XG5cbiAgLy8gU2hvdyBubyBzaGFkb3cgZm9yIGAuYnRuLWxpbmtgIHNpbmNlIGl0IGhhcyBubyBvdGhlciBidXR0b24gc3R5bGVzLlxuICAmLmJ0bi1saW5rIHtcbiAgICBAaW5jbHVkZSBib3gtc2hhZG93KG5vbmUpO1xuICB9XG59XG5cblxuLy9cbi8vIFZlcnRpY2FsIGJ1dHRvbiBncm91cHNcbi8vXG5cbi5idG4tZ3JvdXAtdmVydGljYWwge1xuICBkaXNwbGF5OiBpbmxpbmUtZmxleDtcbiAgZmxleC1kaXJlY3Rpb246IGNvbHVtbjtcbiAgYWxpZ24taXRlbXM6IGZsZXgtc3RhcnQ7XG4gIGp1c3RpZnktY29udGVudDogY2VudGVyO1xuXG4gIC5idG4sXG4gIC5idG4tZ3JvdXAge1xuICAgIHdpZHRoOiAxMDAlO1xuICB9XG5cbiAgPiAuYnRuICsgLmJ0bixcbiAgPiAuYnRuICsgLmJ0bi1ncm91cCxcbiAgPiAuYnRuLWdyb3VwICsgLmJ0bixcbiAgPiAuYnRuLWdyb3VwICsgLmJ0bi1ncm91cCB7XG4gICAgbWFyZ2luLXRvcDogLSRpbnB1dC1idG4tYm9yZGVyLXdpZHRoO1xuICAgIG1hcmdpbi1sZWZ0OiAwO1xuICB9XG59XG5cbi5idG4tZ3JvdXAtdmVydGljYWwgPiAuYnRuIHtcbiAgJjpub3QoOmZpcnN0LWNoaWxkKTpub3QoOmxhc3QtY2hpbGQpIHtcbiAgICBib3JkZXItcmFkaXVzOiAwO1xuICB9XG4gICY6Zmlyc3QtY2hpbGQ6bm90KDpsYXN0LWNoaWxkKSB7XG4gICAgQGluY2x1ZGUgYm9yZGVyLWJvdHRvbS1yYWRpdXMoMCk7XG4gIH1cbiAgJjpsYXN0LWNoaWxkOm5vdCg6Zmlyc3QtY2hpbGQpIHtcbiAgICBAaW5jbHVkZSBib3JkZXItdG9wLXJhZGl1cygwKTtcbiAgfVxufVxuLmJ0bi1ncm91cC12ZXJ0aWNhbCA+IC5idG4tZ3JvdXA6bm90KDpmaXJzdC1jaGlsZCk6bm90KDpsYXN0LWNoaWxkKSA+IC5idG4ge1xuICBib3JkZXItcmFkaXVzOiAwO1xufVxuLmJ0bi1ncm91cC12ZXJ0aWNhbCA+IC5idG4tZ3JvdXA6Zmlyc3QtY2hpbGQ6bm90KDpsYXN0LWNoaWxkKSB7XG4gID4gLmJ0bjpsYXN0LWNoaWxkLFxuICA+IC5kcm9wZG93bi10b2dnbGUge1xuICAgIEBpbmNsdWRlIGJvcmRlci1ib3R0b20tcmFkaXVzKDApO1xuICB9XG59XG4uYnRuLWdyb3VwLXZlcnRpY2FsID4gLmJ0bi1ncm91cDpsYXN0LWNoaWxkOm5vdCg6Zmlyc3QtY2hpbGQpID4gLmJ0bjpmaXJzdC1jaGlsZCB7XG4gIEBpbmNsdWRlIGJvcmRlci10b3AtcmFkaXVzKDApO1xufVxuXG5cbi8vIENoZWNrYm94IGFuZCByYWRpbyBvcHRpb25zXG4vL1xuLy8gSW4gb3JkZXIgdG8gc3VwcG9ydCB0aGUgYnJvd3NlcidzIGZvcm0gdmFsaWRhdGlvbiBmZWVkYmFjaywgcG93ZXJlZCBieSB0aGVcbi8vIGByZXF1aXJlZGAgYXR0cmlidXRlLCB3ZSBoYXZlIHRvIFwiaGlkZVwiIHRoZSBpbnB1dHMgdmlhIGBjbGlwYC4gV2UgY2Fubm90IHVzZVxuLy8gYGRpc3BsYXk6IG5vbmU7YCBvciBgdmlzaWJpbGl0eTogaGlkZGVuO2AgYXMgdGhhdCBhbHNvIGhpZGVzIHRoZSBwb3BvdmVyLlxuLy8gU2ltcGx5IHZpc3VhbGx5IGhpZGluZyB0aGUgaW5wdXRzIHZpYSBgb3BhY2l0eWAgd291bGQgbGVhdmUgdGhlbSBjbGlja2FibGUgaW5cbi8vIGNlcnRhaW4gY2FzZXMgd2hpY2ggaXMgcHJldmVudGVkIGJ5IHVzaW5nIGBjbGlwYCBhbmQgYHBvaW50ZXItZXZlbnRzYC5cbi8vIFRoaXMgd2F5LCB3ZSBlbnN1cmUgYSBET00gZWxlbWVudCBpcyB2aXNpYmxlIHRvIHBvc2l0aW9uIHRoZSBwb3BvdmVyIGZyb20uXG4vL1xuLy8gU2VlIGh0dHBzOi8vZ2l0aHViLmNvbS90d2JzL2Jvb3RzdHJhcC9wdWxsLzEyNzk0IGFuZFxuLy8gaHR0cHM6Ly9naXRodWIuY29tL3R3YnMvYm9vdHN0cmFwL3B1bGwvMTQ1NTkgZm9yIG1vcmUgaW5mb3JtYXRpb24uXG5cbltkYXRhLXRvZ2dsZT1cImJ1dHRvbnNcIl0ge1xuICA+IC5idG4sXG4gID4gLmJ0bi1ncm91cCA+IC5idG4ge1xuICAgIGlucHV0W3R5cGU9XCJyYWRpb1wiXSxcbiAgICBpbnB1dFt0eXBlPVwiY2hlY2tib3hcIl0ge1xuICAgICAgcG9zaXRpb246IGFic29sdXRlO1xuICAgICAgY2xpcDogcmVjdCgwLDAsMCwwKTtcbiAgICAgIHBvaW50ZXItZXZlbnRzOiBub25lO1xuICAgIH1cbiAgfVxufVxuIiwiLy9cbi8vIEJhc2Ugc3R5bGVzXG4vL1xuXG4uaW5wdXQtZ3JvdXAge1xuICBwb3NpdGlvbjogcmVsYXRpdmU7XG4gIGRpc3BsYXk6IGZsZXg7XG4gIHdpZHRoOiAxMDAlO1xuXG4gIC5mb3JtLWNvbnRyb2wge1xuICAgIC8vIEVuc3VyZSB0aGF0IHRoZSBpbnB1dCBpcyBhbHdheXMgYWJvdmUgdGhlICphcHBlbmRlZCogYWRkb24gYnV0dG9uIGZvclxuICAgIC8vIHByb3BlciBib3JkZXIgY29sb3JzLlxuICAgIHBvc2l0aW9uOiByZWxhdGl2ZTtcbiAgICB6LWluZGV4OiAyO1xuICAgIGZsZXg6IDEgMSBhdXRvO1xuICAgIC8vIEFkZCB3aWR0aCAxJSBhbmQgZmxleC1iYXNpcyBhdXRvIHRvIGVuc3VyZSB0aGF0IGJ1dHRvbiB3aWxsIG5vdCB3cmFwIG91dFxuICAgIC8vIHRoZSBjb2x1bW4uIEFwcGxpZXMgdG8gSUUgRWRnZSsgYW5kIEZpcmVmb3guIENocm9tZSBkb2VzIG5vdCByZXF1aXJlIHRoaXMuXG4gICAgd2lkdGg6IDElO1xuICAgIG1hcmdpbi1ib3R0b206IDA7XG5cbiAgICAvLyBCcmluZyB0aGUgXCJhY3RpdmVcIiBmb3JtIGNvbnRyb2wgdG8gdGhlIGZyb250XG4gICAgQGluY2x1ZGUgaG92ZXItZm9jdXMtYWN0aXZlIHtcbiAgICAgIHotaW5kZXg6IDM7XG4gICAgfVxuICB9XG59XG5cbi5pbnB1dC1ncm91cC1hZGRvbixcbi5pbnB1dC1ncm91cC1idG4sXG4uaW5wdXQtZ3JvdXAgLmZvcm0tY29udHJvbCB7XG4gIC8vIFZlcnRpY2FsbHkgY2VudGVycyB0aGUgY29udGVudCBvZiB0aGUgYWRkb25zIHdpdGhpbiB0aGUgaW5wdXQgZ3JvdXBcbiAgZGlzcGxheTogZmxleDtcbiAgYWxpZ24taXRlbXM6IGNlbnRlcjtcblxuICAmOm5vdCg6Zmlyc3QtY2hpbGQpOm5vdCg6bGFzdC1jaGlsZCkge1xuICAgIEBpbmNsdWRlIGJvcmRlci1yYWRpdXMoMCk7XG4gIH1cbn1cblxuLmlucHV0LWdyb3VwLWFkZG9uLFxuLmlucHV0LWdyb3VwLWJ0biB7XG4gIHdoaXRlLXNwYWNlOiBub3dyYXA7XG4gIHZlcnRpY2FsLWFsaWduOiBtaWRkbGU7IC8vIE1hdGNoIHRoZSBpbnB1dHNcbn1cblxuXG4vLyBTaXppbmcgb3B0aW9uc1xuLy9cbi8vIFJlbWl4IHRoZSBkZWZhdWx0IGZvcm0gY29udHJvbCBzaXppbmcgY2xhc3NlcyBpbnRvIG5ldyBvbmVzIGZvciBlYXNpZXJcbi8vIG1hbmlwdWxhdGlvbi5cblxuLmlucHV0LWdyb3VwLWxnID4gLmZvcm0tY29udHJvbCxcbi5pbnB1dC1ncm91cC1sZyA+IC5pbnB1dC1ncm91cC1hZGRvbixcbi5pbnB1dC1ncm91cC1sZyA+IC5pbnB1dC1ncm91cC1idG4gPiAuYnRuIHtcbiAgQGV4dGVuZCAuZm9ybS1jb250cm9sLWxnO1xufVxuLmlucHV0LWdyb3VwLXNtID4gLmZvcm0tY29udHJvbCxcbi5pbnB1dC1ncm91cC1zbSA+IC5pbnB1dC1ncm91cC1hZGRvbixcbi5pbnB1dC1ncm91cC1zbSA+IC5pbnB1dC1ncm91cC1idG4gPiAuYnRuIHtcbiAgQGV4dGVuZCAuZm9ybS1jb250cm9sLXNtO1xufVxuXG5cbi8vXG4vLyBUZXh0IGlucHV0IGdyb3Vwc1xuLy9cblxuLmlucHV0LWdyb3VwLWFkZG9uIHtcbiAgcGFkZGluZzogJGlucHV0LWJ0bi1wYWRkaW5nLXkgJGlucHV0LWJ0bi1wYWRkaW5nLXg7XG4gIG1hcmdpbi1ib3R0b206IDA7IC8vIEFsbG93IHVzZSBvZiA8bGFiZWw+IGVsZW1lbnRzIGJ5IG92ZXJyaWRpbmcgb3VyIGRlZmF1bHQgbWFyZ2luLWJvdHRvbVxuICBmb250LXNpemU6ICRmb250LXNpemUtYmFzZTsgLy8gTWF0Y2ggaW5wdXRzXG4gIGZvbnQtd2VpZ2h0OiAkZm9udC13ZWlnaHQtbm9ybWFsO1xuICBsaW5lLWhlaWdodDogJGlucHV0LWJ0bi1saW5lLWhlaWdodDtcbiAgY29sb3I6ICRpbnB1dC1ncm91cC1hZGRvbi1jb2xvcjtcbiAgdGV4dC1hbGlnbjogY2VudGVyO1xuICBiYWNrZ3JvdW5kLWNvbG9yOiAkaW5wdXQtZ3JvdXAtYWRkb24tYmc7XG4gIGJhY2tncm91bmQtY2xpcDogcGFkZGluZy1ib3g7XG4gIGJvcmRlcjogJGlucHV0LWJ0bi1ib3JkZXItd2lkdGggc29saWQgJGlucHV0LWdyb3VwLWFkZG9uLWJvcmRlci1jb2xvcjtcbiAgQGluY2x1ZGUgYm9yZGVyLXJhZGl1cygkaW5wdXQtYm9yZGVyLXJhZGl1cyk7XG5cbiAgLy8gU2l6aW5nXG4gICYuZm9ybS1jb250cm9sLXNtIHtcbiAgICBwYWRkaW5nOiAkaW5wdXQtYnRuLXBhZGRpbmcteS1zbSAkaW5wdXQtYnRuLXBhZGRpbmcteC1zbTtcbiAgICBmb250LXNpemU6ICRmb250LXNpemUtc207XG4gICAgQGluY2x1ZGUgYm9yZGVyLXJhZGl1cygkaW5wdXQtYm9yZGVyLXJhZGl1cy1zbSk7XG4gIH1cblxuICAmLmZvcm0tY29udHJvbC1sZyB7XG4gICAgcGFkZGluZzogJGlucHV0LWJ0bi1wYWRkaW5nLXktbGcgJGlucHV0LWJ0bi1wYWRkaW5nLXgtbGc7XG4gICAgZm9udC1zaXplOiAkZm9udC1zaXplLWxnO1xuICAgIEBpbmNsdWRlIGJvcmRlci1yYWRpdXMoJGlucHV0LWJvcmRlci1yYWRpdXMtbGcpO1xuICB9XG5cbiAgLy8gc2Nzcy1saW50OmRpc2FibGUgUXVhbGlmeWluZ0VsZW1lbnRcbiAgLy8gTnVrZSBkZWZhdWx0IG1hcmdpbnMgZnJvbSBjaGVja2JveGVzIGFuZCByYWRpb3MgdG8gdmVydGljYWxseSBjZW50ZXIgd2l0aGluLlxuICBpbnB1dFt0eXBlPVwicmFkaW9cIl0sXG4gIGlucHV0W3R5cGU9XCJjaGVja2JveFwiXSB7XG4gICAgbWFyZ2luLXRvcDogMDtcbiAgfVxuICAvLyBzY3NzLWxpbnQ6ZW5hYmxlIFF1YWxpZnlpbmdFbGVtZW50XG59XG5cblxuLy9cbi8vIFJlc2V0IHJvdW5kZWQgY29ybmVyc1xuLy9cblxuLmlucHV0LWdyb3VwIC5mb3JtLWNvbnRyb2w6bm90KDpsYXN0LWNoaWxkKSxcbi5pbnB1dC1ncm91cC1hZGRvbjpub3QoOmxhc3QtY2hpbGQpLFxuLmlucHV0LWdyb3VwLWJ0bjpub3QoOmxhc3QtY2hpbGQpID4gLmJ0bixcbi5pbnB1dC1ncm91cC1idG46bm90KDpsYXN0LWNoaWxkKSA+IC5idG4tZ3JvdXAgPiAuYnRuLFxuLmlucHV0LWdyb3VwLWJ0bjpub3QoOmxhc3QtY2hpbGQpID4gLmRyb3Bkb3duLXRvZ2dsZSxcbi5pbnB1dC1ncm91cC1idG46bm90KDpmaXJzdC1jaGlsZCkgPiAuYnRuOm5vdCg6bGFzdC1jaGlsZCk6bm90KC5kcm9wZG93bi10b2dnbGUpLFxuLmlucHV0LWdyb3VwLWJ0bjpub3QoOmZpcnN0LWNoaWxkKSA+IC5idG4tZ3JvdXA6bm90KDpsYXN0LWNoaWxkKSA+IC5idG4ge1xuICBAaW5jbHVkZSBib3JkZXItcmlnaHQtcmFkaXVzKDApO1xufVxuLmlucHV0LWdyb3VwLWFkZG9uOm5vdCg6bGFzdC1jaGlsZCkge1xuICBib3JkZXItcmlnaHQ6IDA7XG59XG4uaW5wdXQtZ3JvdXAgLmZvcm0tY29udHJvbDpub3QoOmZpcnN0LWNoaWxkKSxcbi5pbnB1dC1ncm91cC1hZGRvbjpub3QoOmZpcnN0LWNoaWxkKSxcbi5pbnB1dC1ncm91cC1idG46bm90KDpmaXJzdC1jaGlsZCkgPiAuYnRuLFxuLmlucHV0LWdyb3VwLWJ0bjpub3QoOmZpcnN0LWNoaWxkKSA+IC5idG4tZ3JvdXAgPiAuYnRuLFxuLmlucHV0LWdyb3VwLWJ0bjpub3QoOmZpcnN0LWNoaWxkKSA+IC5kcm9wZG93bi10b2dnbGUsXG4uaW5wdXQtZ3JvdXAtYnRuOm5vdCg6bGFzdC1jaGlsZCkgPiAuYnRuOm5vdCg6Zmlyc3QtY2hpbGQpLFxuLmlucHV0LWdyb3VwLWJ0bjpub3QoOmxhc3QtY2hpbGQpID4gLmJ0bi1ncm91cDpub3QoOmZpcnN0LWNoaWxkKSA+IC5idG4ge1xuICBAaW5jbHVkZSBib3JkZXItbGVmdC1yYWRpdXMoMCk7XG59XG4uZm9ybS1jb250cm9sICsgLmlucHV0LWdyb3VwLWFkZG9uOm5vdCg6Zmlyc3QtY2hpbGQpIHtcbiAgYm9yZGVyLWxlZnQ6IDA7XG59XG5cbi8vXG4vLyBCdXR0b24gaW5wdXQgZ3JvdXBzXG4vL1xuXG4uaW5wdXQtZ3JvdXAtYnRuIHtcbiAgcG9zaXRpb246IHJlbGF0aXZlO1xuICAvLyBKYW5raWx5IHByZXZlbnQgaW5wdXQgYnV0dG9uIGdyb3VwcyBmcm9tIHdyYXBwaW5nIHdpdGggYHdoaXRlLXNwYWNlYCBhbmRcbiAgLy8gYGZvbnQtc2l6ZWAgaW4gY29tYmluYXRpb24gd2l0aCBgaW5saW5lLWJsb2NrYCBvbiBidXR0b25zLlxuICBmb250LXNpemU6IDA7XG4gIHdoaXRlLXNwYWNlOiBub3dyYXA7XG5cbiAgLy8gTmVnYXRpdmUgbWFyZ2luIGZvciBzcGFjaW5nLCBwb3NpdGlvbiBmb3IgYnJpbmdpbmcgaG92ZXJlZC9mb2N1c2VkL2FjdGl2ZWRcbiAgLy8gZWxlbWVudCBhYm92ZSB0aGUgc2libGluZ3MuXG4gID4gLmJ0biB7XG4gICAgcG9zaXRpb246IHJlbGF0aXZlO1xuICAgIGJhY2tncm91bmQtY2xpcDogcGFkZGluZy1ib3g7XG4gICAgYm9yZGVyOiAkaW5wdXQtYnRuLWJvcmRlci13aWR0aCBzb2xpZCAkaW5wdXQtZ3JvdXAtYnRuLWJvcmRlci1jb2xvcjtcblxuICAgICsgLmJ0biB7XG4gICAgICBtYXJnaW4tbGVmdDogKC0kaW5wdXQtYnRuLWJvcmRlci13aWR0aCk7XG4gICAgfVxuXG4gICAgLy8gQnJpbmcgdGhlIFwiYWN0aXZlXCIgYnV0dG9uIHRvIHRoZSBmcm9udFxuICAgIEBpbmNsdWRlIGhvdmVyLWZvY3VzLWFjdGl2ZSB7XG4gICAgICB6LWluZGV4OiAzO1xuICAgIH1cbiAgfVxuXG4gIC8vIE5lZ2F0aXZlIG1hcmdpbiB0byBvbmx5IGhhdmUgYSBzaW5nbGUsIHNoYXJlZCBib3JkZXIgYmV0d2VlbiB0aGUgdHdvXG4gICY6bm90KDpsYXN0LWNoaWxkKSB7XG4gICAgPiAuYnRuLFxuICAgID4gLmJ0bi1ncm91cCB7XG4gICAgICBtYXJnaW4tcmlnaHQ6ICgtJGlucHV0LWJ0bi1ib3JkZXItd2lkdGgpO1xuICAgIH1cbiAgfVxuICAmOm5vdCg6Zmlyc3QtY2hpbGQpIHtcbiAgICA+IC5idG4sXG4gICAgPiAuYnRuLWdyb3VwIHtcbiAgICAgIHotaW5kZXg6IDI7XG4gICAgICBtYXJnaW4tbGVmdDogKC0kaW5wdXQtYnRuLWJvcmRlci13aWR0aCk7XG4gICAgICAvLyBCZWNhdXNlIHNwZWNpZmljaXR5XG4gICAgICBAaW5jbHVkZSBob3Zlci1mb2N1cy1hY3RpdmUge1xuICAgICAgICB6LWluZGV4OiAzO1xuICAgICAgfVxuICAgIH1cbiAgfVxufVxuIiwiLy8gc2Nzcy1saW50OmRpc2FibGUgUHJvcGVydHlDb3VudCwgVmVuZG9yUHJlZml4XG5cbi8vIEVtYmVkZGVkIGljb25zIGZyb20gT3BlbiBJY29uaWMuXG4vLyBSZWxlYXNlZCB1bmRlciBNSVQgYW5kIGNvcHlyaWdodCAyMDE0IFdheWJ1cnkuXG4vLyBodHRwczovL3VzZWljb25pYy5jb20vb3BlblxuXG5cbi8vIENoZWNrYm94ZXMgYW5kIHJhZGlvc1xuLy9cbi8vIEJhc2UgY2xhc3MgdGFrZXMgY2FyZSBvZiBhbGwgdGhlIGtleSBiZWhhdmlvcmFsIGFzcGVjdHMuXG5cbi5jdXN0b20tY29udHJvbCB7XG4gIHBvc2l0aW9uOiByZWxhdGl2ZTtcbiAgZGlzcGxheTogaW5saW5lLWZsZXg7XG4gIG1pbi1oZWlnaHQ6ICgxcmVtICogJGxpbmUtaGVpZ2h0LWJhc2UpO1xuICBwYWRkaW5nLWxlZnQ6ICRjdXN0b20tY29udHJvbC1ndXR0ZXI7XG4gIG1hcmdpbi1yaWdodDogJGN1c3RvbS1jb250cm9sLXNwYWNlci14O1xufVxuXG4uY3VzdG9tLWNvbnRyb2wtaW5wdXQge1xuICBwb3NpdGlvbjogYWJzb2x1dGU7XG4gIHotaW5kZXg6IC0xOyAvLyBQdXQgdGhlIGlucHV0IGJlaGluZCB0aGUgbGFiZWwgc28gaXQgZG9lc24ndCBvdmVybGF5IHRleHRcbiAgb3BhY2l0eTogMDtcblxuICAmOmNoZWNrZWQgfiAuY3VzdG9tLWNvbnRyb2wtaW5kaWNhdG9yIHtcbiAgICBjb2xvcjogJGN1c3RvbS1jb250cm9sLWluZGljYXRvci1jaGVja2VkLWNvbG9yO1xuICAgIGJhY2tncm91bmQtY29sb3I6ICRjdXN0b20tY29udHJvbC1pbmRpY2F0b3ItY2hlY2tlZC1iZztcbiAgICBAaW5jbHVkZSBib3gtc2hhZG93KCRjdXN0b20tY29udHJvbC1pbmRpY2F0b3ItY2hlY2tlZC1ib3gtc2hhZG93KTtcbiAgfVxuXG4gICY6Zm9jdXMgfiAuY3VzdG9tLWNvbnRyb2wtaW5kaWNhdG9yIHtcbiAgICAvLyB0aGUgbWl4aW4gaXMgbm90IHVzZWQgaGVyZSB0byBtYWtlIHN1cmUgdGhlcmUgaXMgZmVlZGJhY2tcbiAgICBib3gtc2hhZG93OiAkY3VzdG9tLWNvbnRyb2wtaW5kaWNhdG9yLWZvY3VzLWJveC1zaGFkb3c7XG4gIH1cblxuICAmOmFjdGl2ZSB+IC5jdXN0b20tY29udHJvbC1pbmRpY2F0b3Ige1xuICAgIGNvbG9yOiAkY3VzdG9tLWNvbnRyb2wtaW5kaWNhdG9yLWFjdGl2ZS1jb2xvcjtcbiAgICBiYWNrZ3JvdW5kLWNvbG9yOiAkY3VzdG9tLWNvbnRyb2wtaW5kaWNhdG9yLWFjdGl2ZS1iZztcbiAgICBAaW5jbHVkZSBib3gtc2hhZG93KCRjdXN0b20tY29udHJvbC1pbmRpY2F0b3ItYWN0aXZlLWJveC1zaGFkb3cpO1xuICB9XG5cbiAgJjpkaXNhYmxlZCB7XG4gICAgfiAuY3VzdG9tLWNvbnRyb2wtaW5kaWNhdG9yIHtcbiAgICAgIGJhY2tncm91bmQtY29sb3I6ICRjdXN0b20tY29udHJvbC1pbmRpY2F0b3ItZGlzYWJsZWQtYmc7XG4gICAgfVxuXG4gICAgfiAuY3VzdG9tLWNvbnRyb2wtZGVzY3JpcHRpb24ge1xuICAgICAgY29sb3I6ICRjdXN0b20tY29udHJvbC1kZXNjcmlwdGlvbi1kaXNhYmxlZC1jb2xvcjtcbiAgICB9XG4gIH1cbn1cblxuLy8gQ3VzdG9tIGluZGljYXRvclxuLy9cbi8vIEdlbmVyYXRlcyBhIHNoYWRvdyBlbGVtZW50IHRvIGNyZWF0ZSBvdXIgbWFrZXNoaWZ0IGNoZWNrYm94L3JhZGlvIGJhY2tncm91bmQuXG5cbi5jdXN0b20tY29udHJvbC1pbmRpY2F0b3Ige1xuICBwb3NpdGlvbjogYWJzb2x1dGU7XG4gIHRvcDogKCgkbGluZS1oZWlnaHQtYmFzZSAtICRjdXN0b20tY29udHJvbC1pbmRpY2F0b3Itc2l6ZSkgLyAyKTtcbiAgbGVmdDogMDtcbiAgZGlzcGxheTogYmxvY2s7XG4gIHdpZHRoOiAkY3VzdG9tLWNvbnRyb2wtaW5kaWNhdG9yLXNpemU7XG4gIGhlaWdodDogJGN1c3RvbS1jb250cm9sLWluZGljYXRvci1zaXplO1xuICBwb2ludGVyLWV2ZW50czogbm9uZTtcbiAgdXNlci1zZWxlY3Q6IG5vbmU7XG4gIGJhY2tncm91bmQtY29sb3I6ICRjdXN0b20tY29udHJvbC1pbmRpY2F0b3ItYmc7XG4gIGJhY2tncm91bmQtcmVwZWF0OiBuby1yZXBlYXQ7XG4gIGJhY2tncm91bmQtcG9zaXRpb246IGNlbnRlciBjZW50ZXI7XG4gIGJhY2tncm91bmQtc2l6ZTogJGN1c3RvbS1jb250cm9sLWluZGljYXRvci1iZy1zaXplO1xuICBAaW5jbHVkZSBib3gtc2hhZG93KCRjdXN0b20tY29udHJvbC1pbmRpY2F0b3ItYm94LXNoYWRvdyk7XG59XG5cbi8vIENoZWNrYm94ZXNcbi8vXG4vLyBUd2VhayBqdXN0IGEgZmV3IHRoaW5ncyBmb3IgY2hlY2tib3hlcy5cblxuLmN1c3RvbS1jaGVja2JveCB7XG4gIC5jdXN0b20tY29udHJvbC1pbmRpY2F0b3Ige1xuICAgIEBpbmNsdWRlIGJvcmRlci1yYWRpdXMoJGN1c3RvbS1jaGVja2JveC1pbmRpY2F0b3ItYm9yZGVyLXJhZGl1cyk7XG4gIH1cblxuICAuY3VzdG9tLWNvbnRyb2wtaW5wdXQ6Y2hlY2tlZCB+IC5jdXN0b20tY29udHJvbC1pbmRpY2F0b3Ige1xuICAgIGJhY2tncm91bmQtaW1hZ2U6ICRjdXN0b20tY2hlY2tib3gtaW5kaWNhdG9yLWljb24tY2hlY2tlZDtcbiAgfVxuXG4gIC5jdXN0b20tY29udHJvbC1pbnB1dDppbmRldGVybWluYXRlIH4gLmN1c3RvbS1jb250cm9sLWluZGljYXRvciB7XG4gICAgYmFja2dyb3VuZC1jb2xvcjogJGN1c3RvbS1jaGVja2JveC1pbmRpY2F0b3ItaW5kZXRlcm1pbmF0ZS1iZztcbiAgICBiYWNrZ3JvdW5kLWltYWdlOiAkY3VzdG9tLWNoZWNrYm94LWluZGljYXRvci1pY29uLWluZGV0ZXJtaW5hdGU7XG4gICAgQGluY2x1ZGUgYm94LXNoYWRvdygkY3VzdG9tLWNoZWNrYm94LWluZGljYXRvci1pbmRldGVybWluYXRlLWJveC1zaGFkb3cpO1xuICB9XG59XG5cbi8vIFJhZGlvc1xuLy9cbi8vIFR3ZWFrIGp1c3QgYSBmZXcgdGhpbmdzIGZvciByYWRpb3MuXG5cbi5jdXN0b20tcmFkaW8ge1xuICAuY3VzdG9tLWNvbnRyb2wtaW5kaWNhdG9yIHtcbiAgICBib3JkZXItcmFkaXVzOiAkY3VzdG9tLXJhZGlvLWluZGljYXRvci1ib3JkZXItcmFkaXVzO1xuICB9XG5cbiAgLmN1c3RvbS1jb250cm9sLWlucHV0OmNoZWNrZWQgfiAuY3VzdG9tLWNvbnRyb2wtaW5kaWNhdG9yIHtcbiAgICBiYWNrZ3JvdW5kLWltYWdlOiAkY3VzdG9tLXJhZGlvLWluZGljYXRvci1pY29uLWNoZWNrZWQ7XG4gIH1cbn1cblxuXG4vLyBMYXlvdXQgb3B0aW9uc1xuLy9cbi8vIEJ5IGRlZmF1bHQgcmFkaW9zIGFuZCBjaGVja2JveGVzIGFyZSBgaW5saW5lLWJsb2NrYCB3aXRoIG5vIGFkZGl0aW9uYWwgc3BhY2luZ1xuLy8gc2V0LiBVc2UgdGhlc2Ugb3B0aW9uYWwgY2xhc3NlcyB0byB0d2VhayB0aGUgbGF5b3V0LlxuXG4uY3VzdG9tLWNvbnRyb2xzLXN0YWNrZWQge1xuICBkaXNwbGF5OiBmbGV4O1xuICBmbGV4LWRpcmVjdGlvbjogY29sdW1uO1xuXG4gIC5jdXN0b20tY29udHJvbCB7XG4gICAgbWFyZ2luLWJvdHRvbTogJGN1c3RvbS1jb250cm9sLXNwYWNlci15O1xuXG4gICAgKyAuY3VzdG9tLWNvbnRyb2wge1xuICAgICAgbWFyZ2luLWxlZnQ6IDA7XG4gICAgfVxuICB9XG59XG5cblxuLy8gU2VsZWN0XG4vL1xuLy8gUmVwbGFjZXMgdGhlIGJyb3dzZXIgZGVmYXVsdCBzZWxlY3Qgd2l0aCBhIGN1c3RvbSBvbmUsIG1vc3RseSBwdWxsZWQgZnJvbVxuLy8gaHR0cDovL3ByaW1lcmNzcy5pby5cbi8vXG5cbi5jdXN0b20tc2VsZWN0IHtcbiAgZGlzcGxheTogaW5saW5lLWJsb2NrO1xuICBtYXgtd2lkdGg6IDEwMCU7XG4gIGhlaWdodDogJGlucHV0LWhlaWdodDtcbiAgcGFkZGluZzogJGN1c3RvbS1zZWxlY3QtcGFkZGluZy15ICgkY3VzdG9tLXNlbGVjdC1wYWRkaW5nLXggKyAkY3VzdG9tLXNlbGVjdC1pbmRpY2F0b3ItcGFkZGluZykgJGN1c3RvbS1zZWxlY3QtcGFkZGluZy15ICRjdXN0b20tc2VsZWN0LXBhZGRpbmcteDtcbiAgbGluZS1oZWlnaHQ6ICRjdXN0b20tc2VsZWN0LWxpbmUtaGVpZ2h0O1xuICBjb2xvcjogJGN1c3RvbS1zZWxlY3QtY29sb3I7XG4gIHZlcnRpY2FsLWFsaWduOiBtaWRkbGU7XG4gIGJhY2tncm91bmQ6ICRjdXN0b20tc2VsZWN0LWJnICRjdXN0b20tc2VsZWN0LWluZGljYXRvciBuby1yZXBlYXQgcmlnaHQgJGN1c3RvbS1zZWxlY3QtcGFkZGluZy14IGNlbnRlcjtcbiAgYmFja2dyb3VuZC1jbGlwOiBwYWRkaW5nLWJveDtcbiAgYmFja2dyb3VuZC1zaXplOiAkY3VzdG9tLXNlbGVjdC1iZy1zaXplO1xuICBib3JkZXI6ICRjdXN0b20tc2VsZWN0LWJvcmRlci13aWR0aCBzb2xpZCAkY3VzdG9tLXNlbGVjdC1ib3JkZXItY29sb3I7XG4gIEBpZiAkZW5hYmxlLXJvdW5kZWQge1xuICAgIGJvcmRlci1yYWRpdXM6ICRjdXN0b20tc2VsZWN0LWJvcmRlci1yYWRpdXM7XG4gIH0gQGVsc2Uge1xuICAgIGJvcmRlci1yYWRpdXM6IDA7XG4gIH1cbiAgYXBwZWFyYW5jZTogbm9uZTtcblxuICAmOmZvY3VzIHtcbiAgICBib3JkZXItY29sb3I6ICRjdXN0b20tc2VsZWN0LWZvY3VzLWJvcmRlci1jb2xvcjtcbiAgICBvdXRsaW5lOiBub25lO1xuICAgIEBpbmNsdWRlIGJveC1zaGFkb3coJGN1c3RvbS1zZWxlY3QtZm9jdXMtYm94LXNoYWRvdyk7XG5cbiAgICAmOjotbXMtdmFsdWUge1xuICAgICAgLy8gRm9yIHZpc3VhbCBjb25zaXN0ZW5jeSB3aXRoIG90aGVyIHBsYXRmb3Jtcy9icm93c2VycyxcbiAgICAgIC8vIHN1cHJlc3MgdGhlIGRlZmF1bHQgd2hpdGUgdGV4dCBvbiBibHVlIGJhY2tncm91bmQgaGlnaGxpZ2h0IGdpdmVuIHRvXG4gICAgICAvLyB0aGUgc2VsZWN0ZWQgb3B0aW9uIHRleHQgd2hlbiB0aGUgKHN0aWxsIGNsb3NlZCkgPHNlbGVjdD4gcmVjZWl2ZXMgZm9jdXNcbiAgICAgIC8vIGluIElFIGFuZCAodW5kZXIgY2VydGFpbiBjb25kaXRpb25zKSBFZGdlLlxuICAgICAgLy8gU2VlIGh0dHBzOi8vZ2l0aHViLmNvbS90d2JzL2Jvb3RzdHJhcC9pc3N1ZXMvMTkzOTguXG4gICAgICBjb2xvcjogJGlucHV0LWNvbG9yO1xuICAgICAgYmFja2dyb3VuZC1jb2xvcjogJGlucHV0LWJnO1xuICAgIH1cbiAgfVxuXG4gICY6ZGlzYWJsZWQge1xuICAgIGNvbG9yOiAkY3VzdG9tLXNlbGVjdC1kaXNhYmxlZC1jb2xvcjtcbiAgICBiYWNrZ3JvdW5kLWNvbG9yOiAkY3VzdG9tLXNlbGVjdC1kaXNhYmxlZC1iZztcbiAgfVxuXG4gIC8vIEhpZGVzIHRoZSBkZWZhdWx0IGNhcmV0IGluIElFMTFcbiAgJjo6LW1zLWV4cGFuZCB7XG4gICAgb3BhY2l0eTogMDtcbiAgfVxufVxuXG4uY3VzdG9tLXNlbGVjdC1zbSB7XG4gIGhlaWdodDogJGN1c3RvbS1zZWxlY3QtaGVpZ2h0LXNtO1xuICBwYWRkaW5nLXRvcDogJGN1c3RvbS1zZWxlY3QtcGFkZGluZy15O1xuICBwYWRkaW5nLWJvdHRvbTogJGN1c3RvbS1zZWxlY3QtcGFkZGluZy15O1xuICBmb250LXNpemU6ICRjdXN0b20tc2VsZWN0LWZvbnQtc2l6ZS1zbTtcbn1cblxuXG4vLyBGaWxlXG4vL1xuLy8gQ3VzdG9tIGZpbGUgaW5wdXQuXG5cbi5jdXN0b20tZmlsZSB7XG4gIHBvc2l0aW9uOiByZWxhdGl2ZTtcbiAgZGlzcGxheTogaW5saW5lLWJsb2NrO1xuICBtYXgtd2lkdGg6IDEwMCU7XG4gIGhlaWdodDogJGN1c3RvbS1maWxlLWhlaWdodDtcbiAgbWFyZ2luLWJvdHRvbTogMDtcbn1cblxuLmN1c3RvbS1maWxlLWlucHV0IHtcbiAgbWluLXdpZHRoOiAkY3VzdG9tLWZpbGUtd2lkdGg7XG4gIG1heC13aWR0aDogMTAwJTtcbiAgaGVpZ2h0OiAkY3VzdG9tLWZpbGUtaGVpZ2h0O1xuICBtYXJnaW46IDA7XG4gIG9wYWNpdHk6IDA7XG5cbiAgJjpmb2N1cyB+IC5jdXN0b20tZmlsZS1jb250cm9sIHtcbiAgICBib3gtc2hhZG93OiAkY3VzdG9tLWZpbGUtZm9jdXMtYm94LXNoYWRvdztcbiAgfVxufVxuXG4uY3VzdG9tLWZpbGUtY29udHJvbCB7XG4gIHBvc2l0aW9uOiBhYnNvbHV0ZTtcbiAgdG9wOiAwO1xuICByaWdodDogMDtcbiAgbGVmdDogMDtcbiAgei1pbmRleDogNTtcbiAgaGVpZ2h0OiAkY3VzdG9tLWZpbGUtaGVpZ2h0O1xuICBwYWRkaW5nOiAkY3VzdG9tLWZpbGUtcGFkZGluZy15ICRjdXN0b20tZmlsZS1wYWRkaW5nLXg7XG4gIG92ZXJmbG93OiBoaWRkZW47XG4gIGxpbmUtaGVpZ2h0OiAkY3VzdG9tLWZpbGUtbGluZS1oZWlnaHQ7XG4gIGNvbG9yOiAkY3VzdG9tLWZpbGUtY29sb3I7XG4gIHBvaW50ZXItZXZlbnRzOiBub25lO1xuICB1c2VyLXNlbGVjdDogbm9uZTtcbiAgYmFja2dyb3VuZC1jb2xvcjogJGN1c3RvbS1maWxlLWJnO1xuICBiYWNrZ3JvdW5kLWNsaXA6IHBhZGRpbmctYm94O1xuICBib3JkZXI6ICRjdXN0b20tZmlsZS1ib3JkZXItd2lkdGggc29saWQgJGN1c3RvbS1maWxlLWJvcmRlci1jb2xvcjtcbiAgQGluY2x1ZGUgYm9yZGVyLXJhZGl1cygkY3VzdG9tLWZpbGUtYm9yZGVyLXJhZGl1cyk7XG4gIEBpbmNsdWRlIGJveC1zaGFkb3coJGN1c3RvbS1maWxlLWJveC1zaGFkb3cpO1xuXG4gIEBlYWNoICRsYW5nLCAkdGV4dCBpbiBtYXAtZ2V0KCRjdXN0b20tZmlsZS10ZXh0LCBwbGFjZWhvbGRlcikge1xuICAgICY6bGFuZygjeyRsYW5nfSk6ZW1wdHk6OmFmdGVyIHtcbiAgICAgIGNvbnRlbnQ6ICR0ZXh0O1xuICAgIH1cbiAgfVxuXG4gICY6OmJlZm9yZSB7XG4gICAgcG9zaXRpb246IGFic29sdXRlO1xuICAgIHRvcDogMDtcbiAgICByaWdodDogMDtcbiAgICB6LWluZGV4OiA2O1xuICAgIGRpc3BsYXk6IGJsb2NrO1xuICAgIGhlaWdodDogJGN1c3RvbS1maWxlLWhlaWdodDtcbiAgICBwYWRkaW5nOiAkY3VzdG9tLWZpbGUtcGFkZGluZy15ICRjdXN0b20tZmlsZS1wYWRkaW5nLXg7XG4gICAgbGluZS1oZWlnaHQ6ICRjdXN0b20tZmlsZS1saW5lLWhlaWdodDtcbiAgICBjb2xvcjogJGN1c3RvbS1maWxlLWJ1dHRvbi1jb2xvcjtcbiAgICBiYWNrZ3JvdW5kLWNvbG9yOiAkY3VzdG9tLWZpbGUtYnV0dG9uLWJnO1xuICAgIGJvcmRlci1sZWZ0OiAkY3VzdG9tLWZpbGUtYm9yZGVyLXdpZHRoIHNvbGlkICRjdXN0b20tZmlsZS1ib3JkZXItY29sb3I7XG4gIH1cblxuICBAZWFjaCAkbGFuZywgJHRleHQgaW4gbWFwLWdldCgkY3VzdG9tLWZpbGUtdGV4dCwgYnV0dG9uLWxhYmVsKSB7XG4gICAgJjpsYW5nKCN7JGxhbmd9KTo6YmVmb3JlIHtcbiAgICAgIGNvbnRlbnQ6ICR0ZXh0O1xuICAgIH1cbiAgfVxufVxuIiwiLy8gQmFzZSBjbGFzc1xuLy9cbi8vIEtpY2tzdGFydCBhbnkgbmF2aWdhdGlvbiBjb21wb25lbnQgd2l0aCBhIHNldCBvZiBzdHlsZSByZXNldHMuIFdvcmtzIHdpdGhcbi8vIGA8bmF2PmBzIG9yIGA8dWw+YHMuXG5cbi5uYXYge1xuICBkaXNwbGF5OiBmbGV4O1xuICBmbGV4LXdyYXA6IHdyYXA7XG4gIHBhZGRpbmctbGVmdDogMDtcbiAgbWFyZ2luLWJvdHRvbTogMDtcbiAgbGlzdC1zdHlsZTogbm9uZTtcbn1cblxuLm5hdi1saW5rIHtcbiAgZGlzcGxheTogYmxvY2s7XG4gIHBhZGRpbmc6ICRuYXYtbGluay1wYWRkaW5nLXkgJG5hdi1saW5rLXBhZGRpbmcteDtcblxuICBAaW5jbHVkZSBob3Zlci1mb2N1cyB7XG4gICAgdGV4dC1kZWNvcmF0aW9uOiBub25lO1xuICB9XG5cbiAgLy8gRGlzYWJsZWQgc3RhdGUgbGlnaHRlbnMgdGV4dFxuICAmLmRpc2FibGVkIHtcbiAgICBjb2xvcjogJG5hdi1saW5rLWRpc2FibGVkLWNvbG9yO1xuICB9XG59XG5cbi8vXG4vLyBUYWJzXG4vL1xuXG4ubmF2LXRhYnMge1xuICBib3JkZXItYm90dG9tOiAkbmF2LXRhYnMtYm9yZGVyLXdpZHRoIHNvbGlkICRuYXYtdGFicy1ib3JkZXItY29sb3I7XG5cbiAgLm5hdi1pdGVtIHtcbiAgICBtYXJnaW4tYm90dG9tOiAtJG5hdi10YWJzLWJvcmRlci13aWR0aDtcbiAgfVxuXG4gIC5uYXYtbGluayB7XG4gICAgYm9yZGVyOiAkbmF2LXRhYnMtYm9yZGVyLXdpZHRoIHNvbGlkIHRyYW5zcGFyZW50O1xuICAgIEBpbmNsdWRlIGJvcmRlci10b3AtcmFkaXVzKCRuYXYtdGFicy1ib3JkZXItcmFkaXVzKTtcblxuICAgIEBpbmNsdWRlIGhvdmVyLWZvY3VzIHtcbiAgICAgIGJvcmRlci1jb2xvcjogJG5hdi10YWJzLWxpbmstaG92ZXItYm9yZGVyLWNvbG9yICRuYXYtdGFicy1saW5rLWhvdmVyLWJvcmRlci1jb2xvciAkbmF2LXRhYnMtYm9yZGVyLWNvbG9yO1xuICAgIH1cblxuICAgICYuZGlzYWJsZWQge1xuICAgICAgY29sb3I6ICRuYXYtbGluay1kaXNhYmxlZC1jb2xvcjtcbiAgICAgIGJhY2tncm91bmQtY29sb3I6IHRyYW5zcGFyZW50O1xuICAgICAgYm9yZGVyLWNvbG9yOiB0cmFuc3BhcmVudDtcbiAgICB9XG4gIH1cblxuICAubmF2LWxpbmsuYWN0aXZlLFxuICAubmF2LWl0ZW0uc2hvdyAubmF2LWxpbmsge1xuICAgIGNvbG9yOiAkbmF2LXRhYnMtbGluay1hY3RpdmUtY29sb3I7XG4gICAgYmFja2dyb3VuZC1jb2xvcjogJG5hdi10YWJzLWxpbmstYWN0aXZlLWJnO1xuICAgIGJvcmRlci1jb2xvcjogJG5hdi10YWJzLWxpbmstYWN0aXZlLWJvcmRlci1jb2xvciAkbmF2LXRhYnMtbGluay1hY3RpdmUtYm9yZGVyLWNvbG9yICRuYXYtdGFicy1saW5rLWFjdGl2ZS1iZztcbiAgfVxuXG4gIC5kcm9wZG93bi1tZW51IHtcbiAgICAvLyBNYWtlIGRyb3Bkb3duIGJvcmRlciBvdmVybGFwIHRhYiBib3JkZXJcbiAgICBtYXJnaW4tdG9wOiAtJG5hdi10YWJzLWJvcmRlci13aWR0aDtcbiAgICAvLyBSZW1vdmUgdGhlIHRvcCByb3VuZGVkIGNvcm5lcnMgaGVyZSBzaW5jZSB0aGVyZSBpcyBhIGhhcmQgZWRnZSBhYm92ZSB0aGUgbWVudVxuICAgIEBpbmNsdWRlIGJvcmRlci10b3AtcmFkaXVzKDApO1xuICB9XG59XG5cblxuLy9cbi8vIFBpbGxzXG4vL1xuXG4ubmF2LXBpbGxzIHtcbiAgLm5hdi1saW5rIHtcbiAgICBAaW5jbHVkZSBib3JkZXItcmFkaXVzKCRuYXYtcGlsbHMtYm9yZGVyLXJhZGl1cyk7XG5cbiAgICAmLmFjdGl2ZSxcbiAgICAuc2hvdyA+ICYge1xuICAgICAgY29sb3I6ICRuYXYtcGlsbHMtbGluay1hY3RpdmUtY29sb3I7XG4gICAgICBiYWNrZ3JvdW5kLWNvbG9yOiAkbmF2LXBpbGxzLWxpbmstYWN0aXZlLWJnO1xuICAgIH1cbiAgfVxufVxuXG5cbi8vXG4vLyBKdXN0aWZpZWQgdmFyaWFudHNcbi8vXG5cbi5uYXYtZmlsbCB7XG4gIC5uYXYtaXRlbSB7XG4gICAgZmxleDogMSAxIGF1dG87XG4gICAgdGV4dC1hbGlnbjogY2VudGVyO1xuICB9XG59XG5cbi5uYXYtanVzdGlmaWVkIHtcbiAgLm5hdi1pdGVtIHtcbiAgICBmbGV4LWJhc2lzOiAwO1xuICAgIGZsZXgtZ3JvdzogMTtcbiAgICB0ZXh0LWFsaWduOiBjZW50ZXI7XG4gIH1cbn1cblxuXG4vLyBUYWJiYWJsZSB0YWJzXG4vL1xuLy8gSGlkZSB0YWJiYWJsZSBwYW5lcyB0byBzdGFydCwgc2hvdyB0aGVtIHdoZW4gYC5hY3RpdmVgXG5cbi50YWItY29udGVudCB7XG4gID4gLnRhYi1wYW5lIHtcbiAgICBkaXNwbGF5OiBub25lO1xuICB9XG4gID4gLmFjdGl2ZSB7XG4gICAgZGlzcGxheTogYmxvY2s7XG4gIH1cbn1cbiIsIi8vIENvbnRlbnRzXG4vL1xuLy8gTmF2YmFyXG4vLyBOYXZiYXIgYnJhbmRcbi8vIE5hdmJhciBuYXZcbi8vIE5hdmJhciB0ZXh0XG4vLyBOYXZiYXIgZGl2aWRlclxuLy8gUmVzcG9uc2l2ZSBuYXZiYXJcbi8vIE5hdmJhciBwb3NpdGlvblxuLy8gTmF2YmFyIHRoZW1lc1xuXG5cbi8vIE5hdmJhclxuLy9cbi8vIFByb3ZpZGUgYSBzdGF0aWMgbmF2YmFyIGZyb20gd2hpY2ggd2UgZXhwYW5kIHRvIGNyZWF0ZSBmdWxsLXdpZHRoLCBmaXhlZCwgYW5kXG4vLyBvdGhlciBuYXZiYXIgdmFyaWF0aW9ucy5cblxuLm5hdmJhciB7XG4gIHBvc2l0aW9uOiByZWxhdGl2ZTtcbiAgZGlzcGxheTogZmxleDtcbiAgZmxleC13cmFwOiB3cmFwOyAvLyBhbGxvdyB1cyB0byBkbyB0aGUgbGluZSBicmVhayBmb3IgY29sbGFwc2luZyBjb250ZW50XG4gIGFsaWduLWl0ZW1zOiBjZW50ZXI7XG4gIGp1c3RpZnktY29udGVudDogc3BhY2UtYmV0d2VlbjsgLy8gc3BhY2Ugb3V0IGJyYW5kIGZyb20gbG9nb1xuICBwYWRkaW5nOiAkbmF2YmFyLXBhZGRpbmcteSAkbmF2YmFyLXBhZGRpbmcteDtcblxuICAvLyBCZWNhdXNlIGZsZXggcHJvcGVydGllcyBhcmVuJ3QgaW5oZXJpdGVkLCB3ZSBuZWVkIHRvIHJlZGVjbGFyZSB0aGVzZSBmaXJzdFxuICAvLyBmZXcgcHJvcGVyaXRpZXMgc28gdGhhdCBjb250ZW50IG5lc3RlZCB3aXRoaW4gYmVoYXZlIHByb3Blcmx5LlxuICA+IC5jb250YWluZXIsXG4gID4gLmNvbnRhaW5lci1mbHVpZCB7XG4gICAgZGlzcGxheTogZmxleDtcbiAgICBmbGV4LXdyYXA6IHdyYXA7XG4gICAgYWxpZ24taXRlbXM6IGNlbnRlcjtcbiAgICBqdXN0aWZ5LWNvbnRlbnQ6IHNwYWNlLWJldHdlZW47XG4gIH1cbn1cblxuXG4vLyBOYXZiYXIgYnJhbmRcbi8vXG4vLyBVc2VkIGZvciBicmFuZCwgcHJvamVjdCwgb3Igc2l0ZSBuYW1lcy5cblxuLm5hdmJhci1icmFuZCB7XG4gIGRpc3BsYXk6IGlubGluZS1ibG9jaztcbiAgcGFkZGluZy10b3A6ICRuYXZiYXItYnJhbmQtcGFkZGluZy15O1xuICBwYWRkaW5nLWJvdHRvbTogJG5hdmJhci1icmFuZC1wYWRkaW5nLXk7XG4gIG1hcmdpbi1yaWdodDogJG5hdmJhci1wYWRkaW5nLXg7XG4gIGZvbnQtc2l6ZTogJG5hdmJhci1icmFuZC1mb250LXNpemU7XG4gIGxpbmUtaGVpZ2h0OiBpbmhlcml0O1xuICB3aGl0ZS1zcGFjZTogbm93cmFwO1xuXG4gIEBpbmNsdWRlIGhvdmVyLWZvY3VzIHtcbiAgICB0ZXh0LWRlY29yYXRpb246IG5vbmU7XG4gIH1cbn1cblxuXG4vLyBOYXZiYXIgbmF2XG4vL1xuLy8gQ3VzdG9tIG5hdmJhciBuYXZpZ2F0aW9uIChkb2Vzbid0IHJlcXVpcmUgYC5uYXZgLCBidXQgZG9lcyBtYWtlIHVzZSBvZiBgLm5hdi1saW5rYCkuXG5cbi5uYXZiYXItbmF2IHtcbiAgZGlzcGxheTogZmxleDtcbiAgZmxleC1kaXJlY3Rpb246IGNvbHVtbjsgLy8gY2Fubm90IHVzZSBgaW5oZXJpdGAgdG8gZ2V0IHRoZSBgLm5hdmJhcmBzIHZhbHVlXG4gIHBhZGRpbmctbGVmdDogMDtcbiAgbWFyZ2luLWJvdHRvbTogMDtcbiAgbGlzdC1zdHlsZTogbm9uZTtcblxuICAubmF2LWxpbmsge1xuICAgIHBhZGRpbmctcmlnaHQ6IDA7XG4gICAgcGFkZGluZy1sZWZ0OiAwO1xuICB9XG5cbiAgLmRyb3Bkb3duLW1lbnUge1xuICAgIHBvc2l0aW9uOiBzdGF0aWM7XG4gICAgZmxvYXQ6IG5vbmU7XG4gIH1cbn1cblxuXG4vLyBOYXZiYXIgdGV4dFxuLy9cbi8vXG5cbi5uYXZiYXItdGV4dCB7XG4gIGRpc3BsYXk6IGlubGluZS1ibG9jaztcbiAgcGFkZGluZy10b3A6ICRuYXYtbGluay1wYWRkaW5nLXk7XG4gIHBhZGRpbmctYm90dG9tOiAkbmF2LWxpbmstcGFkZGluZy15O1xufVxuXG5cbi8vIFJlc3BvbnNpdmUgbmF2YmFyXG4vL1xuLy8gQ3VzdG9tIHN0eWxlcyBmb3IgcmVzcG9uc2l2ZSBjb2xsYXBzaW5nIGFuZCB0b2dnbGluZyBvZiBuYXZiYXIgY29udGVudHMuXG4vLyBQb3dlcmVkIGJ5IHRoZSBjb2xsYXBzZSBCb290c3RyYXAgSmF2YVNjcmlwdCBwbHVnaW4uXG5cbi8vIFdoZW4gY29sbGFwc2VkLCBwcmV2ZW50IHRoZSB0b2dnbGVhYmxlIG5hdmJhciBjb250ZW50cyBmcm9tIGFwcGVhcmluZyBpblxuLy8gdGhlIGRlZmF1bHQgZmxleGJveCByb3cgb3JpZW5hdGlvbi4gUmVxdWlyZXMgdGhlIHVzZSBvZiBgZmxleC13cmFwOiB3cmFwYFxuLy8gb24gdGhlIGAubmF2YmFyYCBwYXJlbnQuXG4ubmF2YmFyLWNvbGxhcHNlIHtcbiAgZmxleC1iYXNpczogMTAwJTtcbiAgLy8gRm9yIGFsd2F5cyBleHBhbmRlZCBvciBleHRyYSBmdWxsIG5hdmJhcnMsIGVuc3VyZSBjb250ZW50IGFsaWducyBpdHNlbGZcbiAgLy8gcHJvcGVybHkgdmVydGljYWxseS4gQ2FuIGJlIGVhc2lseSBvdmVycmlkZGVuIHdpdGggZmxleCB1dGlsaXRpZXMuXG4gIGFsaWduLWl0ZW1zOiBjZW50ZXI7XG59XG5cbi8vIEJ1dHRvbiBmb3IgdG9nZ2xpbmcgdGhlIG5hdmJhciB3aGVuIGluIGl0cyBjb2xsYXBzZWQgc3RhdGVcbi5uYXZiYXItdG9nZ2xlciB7XG4gIHBhZGRpbmc6ICRuYXZiYXItdG9nZ2xlci1wYWRkaW5nLXkgJG5hdmJhci10b2dnbGVyLXBhZGRpbmcteDtcbiAgZm9udC1zaXplOiAkbmF2YmFyLXRvZ2dsZXItZm9udC1zaXplO1xuICBsaW5lLWhlaWdodDogMTtcbiAgYmFja2dyb3VuZDogdHJhbnNwYXJlbnQ7IC8vIHJlbW92ZSBkZWZhdWx0IGJ1dHRvbiBzdHlsZVxuICBib3JkZXI6ICRib3JkZXItd2lkdGggc29saWQgdHJhbnNwYXJlbnQ7IC8vIHJlbW92ZSBkZWZhdWx0IGJ1dHRvbiBzdHlsZVxuICBAaW5jbHVkZSBib3JkZXItcmFkaXVzKCRuYXZiYXItdG9nZ2xlci1ib3JkZXItcmFkaXVzKTtcblxuICBAaW5jbHVkZSBob3Zlci1mb2N1cyB7XG4gICAgdGV4dC1kZWNvcmF0aW9uOiBub25lO1xuICB9XG59XG5cbi8vIEtlZXAgYXMgYSBzZXBhcmF0ZSBlbGVtZW50IHNvIGZvbGtzIGNhbiBlYXNpbHkgb3ZlcnJpZGUgaXQgd2l0aCBhbm90aGVyIGljb25cbi8vIG9yIGltYWdlIGZpbGUgYXMgbmVlZGVkLlxuLm5hdmJhci10b2dnbGVyLWljb24ge1xuICBkaXNwbGF5OiBpbmxpbmUtYmxvY2s7XG4gIHdpZHRoOiAxLjVlbTtcbiAgaGVpZ2h0OiAxLjVlbTtcbiAgdmVydGljYWwtYWxpZ246IG1pZGRsZTtcbiAgY29udGVudDogXCJcIjtcbiAgYmFja2dyb3VuZDogbm8tcmVwZWF0IGNlbnRlciBjZW50ZXI7XG4gIGJhY2tncm91bmQtc2l6ZTogMTAwJSAxMDAlO1xufVxuXG4vLyBHZW5lcmF0ZSBzZXJpZXMgb2YgYC5uYXZiYXItZXhwYW5kLSpgIHJlc3BvbnNpdmUgY2xhc3NlcyBmb3IgY29uZmlndXJpbmdcbi8vIHdoZXJlIHlvdXIgbmF2YmFyIGNvbGxhcHNlcy5cbi5uYXZiYXItZXhwYW5kIHtcbiAgQGVhY2ggJGJyZWFrcG9pbnQgaW4gbWFwLWtleXMoJGdyaWQtYnJlYWtwb2ludHMpIHtcbiAgICAkbmV4dDogYnJlYWtwb2ludC1uZXh0KCRicmVha3BvaW50LCAkZ3JpZC1icmVha3BvaW50cyk7XG4gICAgJGluZml4OiBicmVha3BvaW50LWluZml4KCRuZXh0LCAkZ3JpZC1icmVha3BvaW50cyk7XG5cbiAgICAmI3skaW5maXh9IHtcbiAgICAgIEBpbmNsdWRlIG1lZGlhLWJyZWFrcG9pbnQtZG93bigkYnJlYWtwb2ludCkge1xuICAgICAgICA+IC5jb250YWluZXIsXG4gICAgICAgID4gLmNvbnRhaW5lci1mbHVpZCB7XG4gICAgICAgICAgcGFkZGluZy1yaWdodDogMDtcbiAgICAgICAgICBwYWRkaW5nLWxlZnQ6IDA7XG4gICAgICAgIH1cbiAgICAgIH1cblxuICAgICAgQGluY2x1ZGUgbWVkaWEtYnJlYWtwb2ludC11cCgkbmV4dCkge1xuICAgICAgICBmbGV4LWRpcmVjdGlvbjogcm93O1xuICAgICAgICBmbGV4LXdyYXA6IG5vd3JhcDtcbiAgICAgICAganVzdGlmeS1jb250ZW50OiBmbGV4LXN0YXJ0O1xuXG4gICAgICAgIC5uYXZiYXItbmF2IHtcbiAgICAgICAgICBmbGV4LWRpcmVjdGlvbjogcm93O1xuXG4gICAgICAgICAgLmRyb3Bkb3duLW1lbnUge1xuICAgICAgICAgICAgcG9zaXRpb246IGFic29sdXRlO1xuICAgICAgICAgIH1cblxuICAgICAgICAgIC5kcm9wZG93bi1tZW51LXJpZ2h0IHtcbiAgICAgICAgICAgIHJpZ2h0OiAwO1xuICAgICAgICAgICAgbGVmdDogYXV0bzsgLy8gUmVzZXQgdGhlIGRlZmF1bHQgZnJvbSBgLmRyb3Bkb3duLW1lbnVgXG4gICAgICAgICAgfVxuXG4gICAgICAgICAgLm5hdi1saW5rIHtcbiAgICAgICAgICAgIHBhZGRpbmctcmlnaHQ6IC41cmVtO1xuICAgICAgICAgICAgcGFkZGluZy1sZWZ0OiAuNXJlbTtcbiAgICAgICAgICB9XG4gICAgICAgIH1cblxuICAgICAgICAvLyBGb3IgbmVzdGluZyBjb250YWluZXJzLCBoYXZlIHRvIHJlZGVjbGFyZSBmb3IgYWxpZ25tZW50IHB1cnBvc2VzXG4gICAgICAgID4gLmNvbnRhaW5lcixcbiAgICAgICAgPiAuY29udGFpbmVyLWZsdWlkIHtcbiAgICAgICAgICBmbGV4LXdyYXA6IG5vd3JhcDtcbiAgICAgICAgfVxuXG4gICAgICAgIC8vIHNjc3MtbGludDpkaXNhYmxlIEltcG9ydGFudFJ1bGVcbiAgICAgICAgLm5hdmJhci1jb2xsYXBzZSB7XG4gICAgICAgICAgZGlzcGxheTogZmxleCAhaW1wb3J0YW50O1xuICAgICAgICB9XG4gICAgICAgIC8vIHNjc3MtbGludDplbmFibGUgSW1wb3J0YW50UnVsZVxuXG4gICAgICAgIC5uYXZiYXItdG9nZ2xlciB7XG4gICAgICAgICAgZGlzcGxheTogbm9uZTtcbiAgICAgICAgfVxuICAgICAgfVxuICAgIH1cbiAgfVxufVxuXG5cbi8vIE5hdmJhciB0aGVtZXNcbi8vXG4vLyBTdHlsZXMgZm9yIHN3aXRjaGluZyBiZXR3ZWVuIG5hdmJhcnMgd2l0aCBsaWdodCBvciBkYXJrIGJhY2tncm91bmQuXG5cbi8vIERhcmsgbGlua3MgYWdhaW5zdCBhIGxpZ2h0IGJhY2tncm91bmRcbi5uYXZiYXItbGlnaHQge1xuICAubmF2YmFyLWJyYW5kIHtcbiAgICBjb2xvcjogJG5hdmJhci1saWdodC1hY3RpdmUtY29sb3I7XG5cbiAgICBAaW5jbHVkZSBob3Zlci1mb2N1cyB7XG4gICAgICBjb2xvcjogJG5hdmJhci1saWdodC1hY3RpdmUtY29sb3I7XG4gICAgfVxuICB9XG5cbiAgLm5hdmJhci1uYXYge1xuICAgIC5uYXYtbGluayB7XG4gICAgICBjb2xvcjogJG5hdmJhci1saWdodC1jb2xvcjtcblxuICAgICAgQGluY2x1ZGUgaG92ZXItZm9jdXMge1xuICAgICAgICBjb2xvcjogJG5hdmJhci1saWdodC1ob3Zlci1jb2xvcjtcbiAgICAgIH1cblxuICAgICAgJi5kaXNhYmxlZCB7XG4gICAgICAgIGNvbG9yOiAkbmF2YmFyLWxpZ2h0LWRpc2FibGVkLWNvbG9yO1xuICAgICAgfVxuICAgIH1cblxuICAgIC5zaG93ID4gLm5hdi1saW5rLFxuICAgIC5hY3RpdmUgPiAubmF2LWxpbmssXG4gICAgLm5hdi1saW5rLnNob3csXG4gICAgLm5hdi1saW5rLmFjdGl2ZSB7XG4gICAgICBjb2xvcjogJG5hdmJhci1saWdodC1hY3RpdmUtY29sb3I7XG4gICAgfVxuICB9XG5cbiAgLm5hdmJhci10b2dnbGVyIHtcbiAgICBjb2xvcjogJG5hdmJhci1saWdodC1jb2xvcjtcbiAgICBib3JkZXItY29sb3I6ICRuYXZiYXItbGlnaHQtdG9nZ2xlci1ib3JkZXItY29sb3I7XG4gIH1cblxuICAubmF2YmFyLXRvZ2dsZXItaWNvbiB7XG4gICAgYmFja2dyb3VuZC1pbWFnZTogJG5hdmJhci1saWdodC10b2dnbGVyLWljb24tYmc7XG4gIH1cblxuICAubmF2YmFyLXRleHQge1xuICAgIGNvbG9yOiAkbmF2YmFyLWxpZ2h0LWNvbG9yO1xuICB9XG59XG5cbi8vIFdoaXRlIGxpbmtzIGFnYWluc3QgYSBkYXJrIGJhY2tncm91bmRcbi5uYXZiYXItZGFyayB7XG4gIC5uYXZiYXItYnJhbmQge1xuICAgIGNvbG9yOiAkbmF2YmFyLWRhcmstYWN0aXZlLWNvbG9yO1xuXG4gICAgQGluY2x1ZGUgaG92ZXItZm9jdXMge1xuICAgICAgY29sb3I6ICRuYXZiYXItZGFyay1hY3RpdmUtY29sb3I7XG4gICAgfVxuICB9XG5cbiAgLm5hdmJhci1uYXYge1xuICAgIC5uYXYtbGluayB7XG4gICAgICBjb2xvcjogJG5hdmJhci1kYXJrLWNvbG9yO1xuXG4gICAgICBAaW5jbHVkZSBob3Zlci1mb2N1cyB7XG4gICAgICAgIGNvbG9yOiAkbmF2YmFyLWRhcmstaG92ZXItY29sb3I7XG4gICAgICB9XG5cbiAgICAgICYuZGlzYWJsZWQge1xuICAgICAgICBjb2xvcjogJG5hdmJhci1kYXJrLWRpc2FibGVkLWNvbG9yO1xuICAgICAgfVxuICAgIH1cblxuICAgIC5zaG93ID4gLm5hdi1saW5rLFxuICAgIC5hY3RpdmUgPiAubmF2LWxpbmssXG4gICAgLm5hdi1saW5rLnNob3csXG4gICAgLm5hdi1saW5rLmFjdGl2ZSB7XG4gICAgICBjb2xvcjogJG5hdmJhci1kYXJrLWFjdGl2ZS1jb2xvcjtcbiAgICB9XG4gIH1cblxuICAubmF2YmFyLXRvZ2dsZXIge1xuICAgIGNvbG9yOiAkbmF2YmFyLWRhcmstY29sb3I7XG4gICAgYm9yZGVyLWNvbG9yOiAkbmF2YmFyLWRhcmstdG9nZ2xlci1ib3JkZXItY29sb3I7XG4gIH1cblxuICAubmF2YmFyLXRvZ2dsZXItaWNvbiB7XG4gICAgYmFja2dyb3VuZC1pbWFnZTogJG5hdmJhci1kYXJrLXRvZ2dsZXItaWNvbi1iZztcbiAgfVxuXG4gIC5uYXZiYXItdGV4dCB7XG4gICAgY29sb3I6ICRuYXZiYXItZGFyay1jb2xvcjtcbiAgfVxufVxuIiwiLy9cbi8vIEJhc2Ugc3R5bGVzXG4vL1xuXG4uY2FyZCB7XG4gIHBvc2l0aW9uOiByZWxhdGl2ZTtcbiAgZGlzcGxheTogZmxleDtcbiAgZmxleC1kaXJlY3Rpb246IGNvbHVtbjtcbiAgbWluLXdpZHRoOiAwO1xuICB3b3JkLXdyYXA6IGJyZWFrLXdvcmQ7XG4gIGJhY2tncm91bmQtY29sb3I6ICRjYXJkLWJnO1xuICBiYWNrZ3JvdW5kLWNsaXA6IGJvcmRlci1ib3g7XG4gIGJvcmRlcjogJGNhcmQtYm9yZGVyLXdpZHRoIHNvbGlkICRjYXJkLWJvcmRlci1jb2xvcjtcbiAgQGluY2x1ZGUgYm9yZGVyLXJhZGl1cygkY2FyZC1ib3JkZXItcmFkaXVzKTtcbn1cblxuLmNhcmQtYm9keSB7XG4gIC8vIEVuYWJsZSBgZmxleC1ncm93OiAxYCBmb3IgZGVja3MgYW5kIGdyb3VwcyBzbyB0aGF0IGNhcmQgYmxvY2tzIHRha2UgdXBcbiAgLy8gYXMgbXVjaCBzcGFjZSBhcyBwb3NzaWJsZSwgZW5zdXJpbmcgZm9vdGVycyBhcmUgYWxpZ25lZCB0byB0aGUgYm90dG9tLlxuICBmbGV4OiAxIDEgYXV0bztcbiAgcGFkZGluZzogJGNhcmQtc3BhY2VyLXg7XG59XG5cbi5jYXJkLXRpdGxlIHtcbiAgbWFyZ2luLWJvdHRvbTogJGNhcmQtc3BhY2VyLXk7XG59XG5cbi5jYXJkLXN1YnRpdGxlIHtcbiAgbWFyZ2luLXRvcDogLSgkY2FyZC1zcGFjZXIteSAvIDIpO1xuICBtYXJnaW4tYm90dG9tOiAwO1xufVxuXG4uY2FyZC10ZXh0Omxhc3QtY2hpbGQge1xuICBtYXJnaW4tYm90dG9tOiAwO1xufVxuXG4uY2FyZC1saW5rIHtcbiAgQGluY2x1ZGUgaG92ZXIge1xuICAgIHRleHQtZGVjb3JhdGlvbjogbm9uZTtcbiAgfVxuXG4gICsgLmNhcmQtbGluayB7XG4gICAgbWFyZ2luLWxlZnQ6ICRjYXJkLXNwYWNlci14O1xuICB9XG59XG5cbi5jYXJkIHtcbiAgPiAubGlzdC1ncm91cDpmaXJzdC1jaGlsZCB7XG4gICAgLmxpc3QtZ3JvdXAtaXRlbTpmaXJzdC1jaGlsZCB7XG4gICAgICBAaW5jbHVkZSBib3JkZXItdG9wLXJhZGl1cygkY2FyZC1ib3JkZXItcmFkaXVzKTtcbiAgICB9XG4gIH1cblxuICA+IC5saXN0LWdyb3VwOmxhc3QtY2hpbGQge1xuICAgIC5saXN0LWdyb3VwLWl0ZW06bGFzdC1jaGlsZCB7XG4gICAgICBAaW5jbHVkZSBib3JkZXItYm90dG9tLXJhZGl1cygkY2FyZC1ib3JkZXItcmFkaXVzKTtcbiAgICB9XG4gIH1cbn1cblxuXG4vL1xuLy8gT3B0aW9uYWwgdGV4dHVhbCBjYXBzXG4vL1xuXG4uY2FyZC1oZWFkZXIge1xuICBwYWRkaW5nOiAkY2FyZC1zcGFjZXIteSAkY2FyZC1zcGFjZXIteDtcbiAgbWFyZ2luLWJvdHRvbTogMDsgLy8gUmVtb3ZlcyB0aGUgZGVmYXVsdCBtYXJnaW4tYm90dG9tIG9mIDxoTj5cbiAgYmFja2dyb3VuZC1jb2xvcjogJGNhcmQtY2FwLWJnO1xuICBib3JkZXItYm90dG9tOiAkY2FyZC1ib3JkZXItd2lkdGggc29saWQgJGNhcmQtYm9yZGVyLWNvbG9yO1xuXG4gICY6Zmlyc3QtY2hpbGQge1xuICAgIEBpbmNsdWRlIGJvcmRlci1yYWRpdXMoJGNhcmQtaW5uZXItYm9yZGVyLXJhZGl1cyAkY2FyZC1pbm5lci1ib3JkZXItcmFkaXVzIDAgMCk7XG4gIH1cbn1cblxuLmNhcmQtZm9vdGVyIHtcbiAgcGFkZGluZzogJGNhcmQtc3BhY2VyLXkgJGNhcmQtc3BhY2VyLXg7XG4gIGJhY2tncm91bmQtY29sb3I6ICRjYXJkLWNhcC1iZztcbiAgYm9yZGVyLXRvcDogJGNhcmQtYm9yZGVyLXdpZHRoIHNvbGlkICRjYXJkLWJvcmRlci1jb2xvcjtcblxuICAmOmxhc3QtY2hpbGQge1xuICAgIEBpbmNsdWRlIGJvcmRlci1yYWRpdXMoMCAwICRjYXJkLWlubmVyLWJvcmRlci1yYWRpdXMgJGNhcmQtaW5uZXItYm9yZGVyLXJhZGl1cyk7XG4gIH1cbn1cblxuXG4vL1xuLy8gSGVhZGVyIG5hdnNcbi8vXG5cbi5jYXJkLWhlYWRlci10YWJzIHtcbiAgbWFyZ2luLXJpZ2h0OiAtKCRjYXJkLXNwYWNlci14IC8gMik7XG4gIG1hcmdpbi1ib3R0b206IC0kY2FyZC1zcGFjZXIteTtcbiAgbWFyZ2luLWxlZnQ6IC0oJGNhcmQtc3BhY2VyLXggLyAyKTtcbiAgYm9yZGVyLWJvdHRvbTogMDtcbn1cblxuLmNhcmQtaGVhZGVyLXBpbGxzIHtcbiAgbWFyZ2luLXJpZ2h0OiAtKCRjYXJkLXNwYWNlci14IC8gMik7XG4gIG1hcmdpbi1sZWZ0OiAtKCRjYXJkLXNwYWNlci14IC8gMik7XG59XG5cbi8vIENhcmQgaW1hZ2Vcbi5jYXJkLWltZy1vdmVybGF5IHtcbiAgcG9zaXRpb246IGFic29sdXRlO1xuICB0b3A6IDA7XG4gIHJpZ2h0OiAwO1xuICBib3R0b206IDA7XG4gIGxlZnQ6IDA7XG4gIHBhZGRpbmc6ICRjYXJkLWltZy1vdmVybGF5LXBhZGRpbmc7XG59XG5cbi5jYXJkLWltZyB7XG4gIHdpZHRoOiAxMDAlOyAvLyBSZXF1aXJlZCBiZWNhdXNlIHdlIHVzZSBmbGV4Ym94IGFuZCB0aGlzIGluaGVyZW50bHkgYXBwbGllcyBhbGlnbi1zZWxmOiBzdHJldGNoXG4gIEBpbmNsdWRlIGJvcmRlci1yYWRpdXMoJGNhcmQtaW5uZXItYm9yZGVyLXJhZGl1cyk7XG59XG5cbi8vIENhcmQgaW1hZ2UgY2Fwc1xuLmNhcmQtaW1nLXRvcCB7XG4gIHdpZHRoOiAxMDAlOyAvLyBSZXF1aXJlZCBiZWNhdXNlIHdlIHVzZSBmbGV4Ym94IGFuZCB0aGlzIGluaGVyZW50bHkgYXBwbGllcyBhbGlnbi1zZWxmOiBzdHJldGNoXG4gIEBpbmNsdWRlIGJvcmRlci10b3AtcmFkaXVzKCRjYXJkLWlubmVyLWJvcmRlci1yYWRpdXMpO1xufVxuXG4uY2FyZC1pbWctYm90dG9tIHtcbiAgd2lkdGg6IDEwMCU7IC8vIFJlcXVpcmVkIGJlY2F1c2Ugd2UgdXNlIGZsZXhib3ggYW5kIHRoaXMgaW5oZXJlbnRseSBhcHBsaWVzIGFsaWduLXNlbGY6IHN0cmV0Y2hcbiAgQGluY2x1ZGUgYm9yZGVyLWJvdHRvbS1yYWRpdXMoJGNhcmQtaW5uZXItYm9yZGVyLXJhZGl1cyk7XG59XG5cblxuLy8gQ2FyZCBkZWNrXG5cbkBpbmNsdWRlIG1lZGlhLWJyZWFrcG9pbnQtdXAoc20pIHtcbiAgLmNhcmQtZGVjayB7XG4gICAgZGlzcGxheTogZmxleDtcbiAgICBmbGV4LWZsb3c6IHJvdyB3cmFwO1xuICAgIG1hcmdpbi1yaWdodDogLSRjYXJkLWRlY2stbWFyZ2luO1xuICAgIG1hcmdpbi1sZWZ0OiAtJGNhcmQtZGVjay1tYXJnaW47XG5cbiAgICAuY2FyZCB7XG4gICAgICBkaXNwbGF5OiBmbGV4O1xuICAgICAgZmxleDogMSAwIDAlO1xuICAgICAgZmxleC1kaXJlY3Rpb246IGNvbHVtbjtcbiAgICAgIG1hcmdpbi1yaWdodDogJGNhcmQtZGVjay1tYXJnaW47XG4gICAgICBtYXJnaW4tbGVmdDogJGNhcmQtZGVjay1tYXJnaW47XG4gICAgfVxuICB9XG59XG5cblxuLy9cbi8vIENhcmQgZ3JvdXBzXG4vL1xuXG5AaW5jbHVkZSBtZWRpYS1icmVha3BvaW50LXVwKHNtKSB7XG4gIC5jYXJkLWdyb3VwIHtcbiAgICBkaXNwbGF5OiBmbGV4O1xuICAgIGZsZXgtZmxvdzogcm93IHdyYXA7XG5cbiAgICAuY2FyZCB7XG4gICAgICBmbGV4OiAxIDAgMCU7XG5cbiAgICAgICsgLmNhcmQge1xuICAgICAgICBtYXJnaW4tbGVmdDogMDtcbiAgICAgICAgYm9yZGVyLWxlZnQ6IDA7XG4gICAgICB9XG5cbiAgICAgIC8vIEhhbmRsZSByb3VuZGVkIGNvcm5lcnNcbiAgICAgIEBpZiAkZW5hYmxlLXJvdW5kZWQge1xuICAgICAgICAmOmZpcnN0LWNoaWxkIHtcbiAgICAgICAgICBAaW5jbHVkZSBib3JkZXItcmlnaHQtcmFkaXVzKDApO1xuXG4gICAgICAgICAgLmNhcmQtaW1nLXRvcCB7XG4gICAgICAgICAgICBib3JkZXItdG9wLXJpZ2h0LXJhZGl1czogMDtcbiAgICAgICAgICB9XG4gICAgICAgICAgLmNhcmQtaW1nLWJvdHRvbSB7XG4gICAgICAgICAgICBib3JkZXItYm90dG9tLXJpZ2h0LXJhZGl1czogMDtcbiAgICAgICAgICB9XG4gICAgICAgIH1cbiAgICAgICAgJjpsYXN0LWNoaWxkIHtcbiAgICAgICAgICBAaW5jbHVkZSBib3JkZXItbGVmdC1yYWRpdXMoMCk7XG5cbiAgICAgICAgICAuY2FyZC1pbWctdG9wIHtcbiAgICAgICAgICAgIGJvcmRlci10b3AtbGVmdC1yYWRpdXM6IDA7XG4gICAgICAgICAgfVxuICAgICAgICAgIC5jYXJkLWltZy1ib3R0b20ge1xuICAgICAgICAgICAgYm9yZGVyLWJvdHRvbS1sZWZ0LXJhZGl1czogMDtcbiAgICAgICAgICB9XG4gICAgICAgIH1cblxuICAgICAgICAmOm5vdCg6Zmlyc3QtY2hpbGQpOm5vdCg6bGFzdC1jaGlsZCkge1xuICAgICAgICAgIGJvcmRlci1yYWRpdXM6IDA7XG5cbiAgICAgICAgICAuY2FyZC1pbWctdG9wLFxuICAgICAgICAgIC5jYXJkLWltZy1ib3R0b20ge1xuICAgICAgICAgICAgYm9yZGVyLXJhZGl1czogMDtcbiAgICAgICAgICB9XG4gICAgICAgIH1cbiAgICAgIH1cbiAgICB9XG4gIH1cbn1cblxuXG4vL1xuLy8gQ29sdW1uc1xuLy9cblxuLmNhcmQtY29sdW1ucyB7XG4gIC5jYXJkIHtcbiAgICBtYXJnaW4tYm90dG9tOiAkY2FyZC1jb2x1bW5zLW1hcmdpbjtcbiAgfVxuXG4gIEBpbmNsdWRlIG1lZGlhLWJyZWFrcG9pbnQtdXAoc20pIHtcbiAgICBjb2x1bW4tY291bnQ6ICRjYXJkLWNvbHVtbnMtY291bnQ7XG4gICAgY29sdW1uLWdhcDogJGNhcmQtY29sdW1ucy1nYXA7XG5cbiAgICAuY2FyZCB7XG4gICAgICBkaXNwbGF5OiBpbmxpbmUtYmxvY2s7IC8vIERvbid0IGxldCB0aGVtIHZlcnRpY2FsbHkgc3BhbiBtdWx0aXBsZSBjb2x1bW5zXG4gICAgICB3aWR0aDogMTAwJTsgLy8gRG9uJ3QgbGV0IHRoZWlyIHdpZHRoIGNoYW5nZVxuICAgIH1cbiAgfVxufVxuIiwiLmJyZWFkY3J1bWIge1xuICBwYWRkaW5nOiAkYnJlYWRjcnVtYi1wYWRkaW5nLXkgJGJyZWFkY3J1bWItcGFkZGluZy14O1xuICBtYXJnaW4tYm90dG9tOiAkYnJlYWRjcnVtYi1tYXJnaW4tYm90dG9tO1xuICBsaXN0LXN0eWxlOiBub25lO1xuICBiYWNrZ3JvdW5kLWNvbG9yOiAkYnJlYWRjcnVtYi1iZztcbiAgQGluY2x1ZGUgYm9yZGVyLXJhZGl1cygkYm9yZGVyLXJhZGl1cyk7XG4gIEBpbmNsdWRlIGNsZWFyZml4O1xufVxuXG4uYnJlYWRjcnVtYi1pdGVtIHtcbiAgZmxvYXQ6IGxlZnQ7XG5cbiAgLy8gVGhlIHNlcGFyYXRvciBiZXR3ZWVuIGJyZWFkY3J1bWJzIChieSBkZWZhdWx0LCBhIGZvcndhcmQtc2xhc2g6IFwiL1wiKVxuICArIC5icmVhZGNydW1iLWl0ZW06OmJlZm9yZSB7XG4gICAgZGlzcGxheTogaW5saW5lLWJsb2NrOyAvLyBTdXBwcmVzcyB1bmRlcmxpbmluZyBvZiB0aGUgc2VwYXJhdG9yIGluIG1vZGVybiBicm93c2Vyc1xuICAgIHBhZGRpbmctcmlnaHQ6ICRicmVhZGNydW1iLWl0ZW0tcGFkZGluZztcbiAgICBwYWRkaW5nLWxlZnQ6ICRicmVhZGNydW1iLWl0ZW0tcGFkZGluZztcbiAgICBjb2xvcjogJGJyZWFkY3J1bWItZGl2aWRlci1jb2xvcjtcbiAgICBjb250ZW50OiBcIiN7JGJyZWFkY3J1bWItZGl2aWRlcn1cIjtcbiAgfVxuXG4gIC8vIElFOS0xMSBoYWNrIHRvIHByb3Blcmx5IGhhbmRsZSBoeXBlcmxpbmsgdW5kZXJsaW5lcyBmb3IgYnJlYWRjcnVtYnMgYnVpbHRcbiAgLy8gd2l0aG91dCBgPHVsPmBzLiBUaGUgYDo6YmVmb3JlYCBwc2V1ZG8tZWxlbWVudCBnZW5lcmF0ZXMgYW4gZWxlbWVudFxuICAvLyAqd2l0aGluKiB0aGUgLmJyZWFkY3J1bWItaXRlbSBhbmQgdGhlcmVieSBpbmhlcml0cyB0aGUgYHRleHQtZGVjb3JhdGlvbmAuXG4gIC8vXG4gIC8vIFRvIHRyaWNrIElFIGludG8gc3VwcHJlc3NpbmcgdGhlIHVuZGVybGluZSwgd2UgZ2l2ZSB0aGUgcHNldWRvLWVsZW1lbnQgYW5cbiAgLy8gdW5kZXJsaW5lIGFuZCB0aGVuIGltbWVkaWF0ZWx5IHJlbW92ZSBpdC5cbiAgKyAuYnJlYWRjcnVtYi1pdGVtOmhvdmVyOjpiZWZvcmUge1xuICAgIHRleHQtZGVjb3JhdGlvbjogdW5kZXJsaW5lO1xuICB9XG4gICsgLmJyZWFkY3J1bWItaXRlbTpob3Zlcjo6YmVmb3JlIHtcbiAgICB0ZXh0LWRlY29yYXRpb246IG5vbmU7XG4gIH1cblxuICAmLmFjdGl2ZSB7XG4gICAgY29sb3I6ICRicmVhZGNydW1iLWFjdGl2ZS1jb2xvcjtcbiAgfVxufVxuIiwiQG1peGluIGNsZWFyZml4KCkge1xuICAmOjphZnRlciB7XG4gICAgZGlzcGxheTogYmxvY2s7XG4gICAgY2xlYXI6IGJvdGg7XG4gICAgY29udGVudDogXCJcIjtcbiAgfVxufVxuIiwiLnBhZ2luYXRpb24ge1xuICBkaXNwbGF5OiBmbGV4O1xuICAvLyAxLTI6IERpc2FibGUgYnJvd3NlciBkZWZhdWx0IGxpc3Qgc3R5bGVzXG4gIHBhZGRpbmctbGVmdDogMDsgLy8gMVxuICBsaXN0LXN0eWxlOiBub25lOyAvLyAyXG4gIEBpbmNsdWRlIGJvcmRlci1yYWRpdXMoKTtcbn1cblxuLnBhZ2UtaXRlbSB7XG4gICY6Zmlyc3QtY2hpbGQge1xuICAgIC5wYWdlLWxpbmsge1xuICAgICAgbWFyZ2luLWxlZnQ6IDA7XG4gICAgICBAaW5jbHVkZSBib3JkZXItbGVmdC1yYWRpdXMoJGJvcmRlci1yYWRpdXMpO1xuICAgIH1cbiAgfVxuICAmOmxhc3QtY2hpbGQge1xuICAgIC5wYWdlLWxpbmsge1xuICAgICAgQGluY2x1ZGUgYm9yZGVyLXJpZ2h0LXJhZGl1cygkYm9yZGVyLXJhZGl1cyk7XG4gICAgfVxuICB9XG5cbiAgJi5hY3RpdmUgLnBhZ2UtbGluayB7XG4gICAgei1pbmRleDogMjtcbiAgICBjb2xvcjogJHBhZ2luYXRpb24tYWN0aXZlLWNvbG9yO1xuICAgIGJhY2tncm91bmQtY29sb3I6ICRwYWdpbmF0aW9uLWFjdGl2ZS1iZztcbiAgICBib3JkZXItY29sb3I6ICRwYWdpbmF0aW9uLWFjdGl2ZS1ib3JkZXItY29sb3I7XG4gIH1cblxuICAmLmRpc2FibGVkIC5wYWdlLWxpbmsge1xuICAgIGNvbG9yOiAkcGFnaW5hdGlvbi1kaXNhYmxlZC1jb2xvcjtcbiAgICBwb2ludGVyLWV2ZW50czogbm9uZTtcbiAgICBiYWNrZ3JvdW5kLWNvbG9yOiAkcGFnaW5hdGlvbi1kaXNhYmxlZC1iZztcbiAgICBib3JkZXItY29sb3I6ICRwYWdpbmF0aW9uLWRpc2FibGVkLWJvcmRlci1jb2xvcjtcbiAgfVxufVxuXG4ucGFnZS1saW5rIHtcbiAgcG9zaXRpb246IHJlbGF0aXZlO1xuICBkaXNwbGF5OiBibG9jaztcbiAgcGFkZGluZzogJHBhZ2luYXRpb24tcGFkZGluZy15ICRwYWdpbmF0aW9uLXBhZGRpbmcteDtcbiAgbWFyZ2luLWxlZnQ6IC0xcHg7XG4gIGxpbmUtaGVpZ2h0OiAkcGFnaW5hdGlvbi1saW5lLWhlaWdodDtcbiAgY29sb3I6ICRwYWdpbmF0aW9uLWNvbG9yO1xuICBiYWNrZ3JvdW5kLWNvbG9yOiAkcGFnaW5hdGlvbi1iZztcbiAgYm9yZGVyOiAkcGFnaW5hdGlvbi1ib3JkZXItd2lkdGggc29saWQgJHBhZ2luYXRpb24tYm9yZGVyLWNvbG9yO1xuXG4gIEBpbmNsdWRlIGhvdmVyLWZvY3VzIHtcbiAgICBjb2xvcjogJHBhZ2luYXRpb24taG92ZXItY29sb3I7XG4gICAgdGV4dC1kZWNvcmF0aW9uOiBub25lO1xuICAgIGJhY2tncm91bmQtY29sb3I6ICRwYWdpbmF0aW9uLWhvdmVyLWJnO1xuICAgIGJvcmRlci1jb2xvcjogJHBhZ2luYXRpb24taG92ZXItYm9yZGVyLWNvbG9yO1xuICB9XG59XG5cblxuLy9cbi8vIFNpemluZ1xuLy9cblxuLnBhZ2luYXRpb24tbGcge1xuICBAaW5jbHVkZSBwYWdpbmF0aW9uLXNpemUoJHBhZ2luYXRpb24tcGFkZGluZy15LWxnLCAkcGFnaW5hdGlvbi1wYWRkaW5nLXgtbGcsICRmb250LXNpemUtbGcsICRsaW5lLWhlaWdodC1sZywgJGJvcmRlci1yYWRpdXMtbGcpO1xufVxuXG4ucGFnaW5hdGlvbi1zbSB7XG4gIEBpbmNsdWRlIHBhZ2luYXRpb24tc2l6ZSgkcGFnaW5hdGlvbi1wYWRkaW5nLXktc20sICRwYWdpbmF0aW9uLXBhZGRpbmcteC1zbSwgJGZvbnQtc2l6ZS1zbSwgJGxpbmUtaGVpZ2h0LXNtLCAkYm9yZGVyLXJhZGl1cy1zbSk7XG59XG4iLCIvLyBQYWdpbmF0aW9uXG5cbkBtaXhpbiBwYWdpbmF0aW9uLXNpemUoJHBhZGRpbmcteSwgJHBhZGRpbmcteCwgJGZvbnQtc2l6ZSwgJGxpbmUtaGVpZ2h0LCAkYm9yZGVyLXJhZGl1cykge1xuICAucGFnZS1saW5rIHtcbiAgICBwYWRkaW5nOiAkcGFkZGluZy15ICRwYWRkaW5nLXg7XG4gICAgZm9udC1zaXplOiAkZm9udC1zaXplO1xuICAgIGxpbmUtaGVpZ2h0OiAkbGluZS1oZWlnaHQ7XG4gIH1cblxuICAucGFnZS1pdGVtIHtcbiAgICAmOmZpcnN0LWNoaWxkIHtcbiAgICAgIC5wYWdlLWxpbmsge1xuICAgICAgICBAaW5jbHVkZSBib3JkZXItbGVmdC1yYWRpdXMoJGJvcmRlci1yYWRpdXMpO1xuICAgICAgfVxuICAgIH1cbiAgICAmOmxhc3QtY2hpbGQge1xuICAgICAgLnBhZ2UtbGluayB7XG4gICAgICAgIEBpbmNsdWRlIGJvcmRlci1yaWdodC1yYWRpdXMoJGJvcmRlci1yYWRpdXMpO1xuICAgICAgfVxuICAgIH1cbiAgfVxufVxuIiwiLy8gQmFzZSBjbGFzc1xuLy9cbi8vIFJlcXVpcmVzIG9uZSBvZiB0aGUgY29udGV4dHVhbCwgY29sb3IgbW9kaWZpZXIgY2xhc3NlcyBmb3IgYGNvbG9yYCBhbmRcbi8vIGBiYWNrZ3JvdW5kLWNvbG9yYC5cblxuLmJhZGdlIHtcbiAgZGlzcGxheTogaW5saW5lLWJsb2NrO1xuICBwYWRkaW5nOiAkYmFkZ2UtcGFkZGluZy15ICRiYWRnZS1wYWRkaW5nLXg7XG4gIGZvbnQtc2l6ZTogJGJhZGdlLWZvbnQtc2l6ZTtcbiAgZm9udC13ZWlnaHQ6ICRiYWRnZS1mb250LXdlaWdodDtcbiAgbGluZS1oZWlnaHQ6IDE7XG4gIGNvbG9yOiAkYmFkZ2UtY29sb3I7XG4gIHRleHQtYWxpZ246IGNlbnRlcjtcbiAgd2hpdGUtc3BhY2U6IG5vd3JhcDtcbiAgdmVydGljYWwtYWxpZ246IGJhc2VsaW5lO1xuICBAaW5jbHVkZSBib3JkZXItcmFkaXVzKCk7XG5cbiAgLy8gRW1wdHkgYmFkZ2VzIGNvbGxhcHNlIGF1dG9tYXRpY2FsbHlcbiAgJjplbXB0eSB7XG4gICAgZGlzcGxheTogbm9uZTtcbiAgfVxufVxuXG4vLyBRdWljayBmaXggZm9yIGJhZGdlcyBpbiBidXR0b25zXG4uYnRuIC5iYWRnZSB7XG4gIHBvc2l0aW9uOiByZWxhdGl2ZTtcbiAgdG9wOiAtMXB4O1xufVxuXG4vLyBQaWxsIGJhZGdlc1xuLy9cbi8vIE1ha2UgdGhlbSBleHRyYSByb3VuZGVkIHdpdGggYSBtb2RpZmllciB0byByZXBsYWNlIHYzJ3MgYmFkZ2VzLlxuXG4uYmFkZ2UtcGlsbCB7XG4gIHBhZGRpbmctcmlnaHQ6ICRiYWRnZS1waWxsLXBhZGRpbmcteDtcbiAgcGFkZGluZy1sZWZ0OiAkYmFkZ2UtcGlsbC1wYWRkaW5nLXg7XG4gIEBpbmNsdWRlIGJvcmRlci1yYWRpdXMoJGJhZGdlLXBpbGwtYm9yZGVyLXJhZGl1cyk7XG59XG5cbi8vIENvbG9yc1xuLy9cbi8vIENvbnRleHR1YWwgdmFyaWF0aW9ucyAobGlua2VkIGJhZGdlcyBnZXQgZGFya2VyIG9uIDpob3ZlcikuXG5cbkBlYWNoICRjb2xvciwgJHZhbHVlIGluICR0aGVtZS1jb2xvcnMge1xuICAuYmFkZ2UtI3skY29sb3J9IHtcbiAgICBAaW5jbHVkZSBiYWRnZS12YXJpYW50KCR2YWx1ZSk7XG4gIH1cbn1cbiIsIkBtaXhpbiBiYWRnZS12YXJpYW50KCRiZykge1xuICBAaW5jbHVkZSBjb2xvci15aXEoJGJnKTtcbiAgYmFja2dyb3VuZC1jb2xvcjogJGJnO1xuXG4gICZbaHJlZl0ge1xuICAgIEBpbmNsdWRlIGhvdmVyLWZvY3VzIHtcbiAgICAgIEBpbmNsdWRlIGNvbG9yLXlpcSgkYmcpO1xuICAgICAgdGV4dC1kZWNvcmF0aW9uOiBub25lO1xuICAgICAgYmFja2dyb3VuZC1jb2xvcjogZGFya2VuKCRiZywgMTAlKTtcbiAgICB9XG4gIH1cbn1cbiIsIi5qdW1ib3Ryb24ge1xuICBwYWRkaW5nOiAkanVtYm90cm9uLXBhZGRpbmcgKCRqdW1ib3Ryb24tcGFkZGluZyAvIDIpO1xuICBtYXJnaW4tYm90dG9tOiAkanVtYm90cm9uLXBhZGRpbmc7XG4gIGJhY2tncm91bmQtY29sb3I6ICRqdW1ib3Ryb24tYmc7XG4gIEBpbmNsdWRlIGJvcmRlci1yYWRpdXMoJGJvcmRlci1yYWRpdXMtbGcpO1xuXG4gIEBpbmNsdWRlIG1lZGlhLWJyZWFrcG9pbnQtdXAoc20pIHtcbiAgICBwYWRkaW5nOiAoJGp1bWJvdHJvbi1wYWRkaW5nICogMikgJGp1bWJvdHJvbi1wYWRkaW5nO1xuICB9XG59XG5cbi5qdW1ib3Ryb24tZmx1aWQge1xuICBwYWRkaW5nLXJpZ2h0OiAwO1xuICBwYWRkaW5nLWxlZnQ6IDA7XG4gIEBpbmNsdWRlIGJvcmRlci1yYWRpdXMoMCk7XG59XG4iLCIvL1xuLy8gQmFzZSBzdHlsZXNcbi8vXG5cbi5hbGVydCB7XG4gIHBhZGRpbmc6ICRhbGVydC1wYWRkaW5nLXkgJGFsZXJ0LXBhZGRpbmcteDtcbiAgbWFyZ2luLWJvdHRvbTogJGFsZXJ0LW1hcmdpbi1ib3R0b207XG4gIGJvcmRlcjogJGFsZXJ0LWJvcmRlci13aWR0aCBzb2xpZCB0cmFuc3BhcmVudDtcbiAgQGluY2x1ZGUgYm9yZGVyLXJhZGl1cygkYWxlcnQtYm9yZGVyLXJhZGl1cyk7XG59XG5cbi8vIEhlYWRpbmdzIGZvciBsYXJnZXIgYWxlcnRzXG4uYWxlcnQtaGVhZGluZyB7XG4gIC8vIFNwZWNpZmllZCB0byBwcmV2ZW50IGNvbmZsaWN0cyBvZiBjaGFuZ2luZyAkaGVhZGluZ3MtY29sb3JcbiAgY29sb3I6IGluaGVyaXQ7XG59XG5cbi8vIFByb3ZpZGUgY2xhc3MgZm9yIGxpbmtzIHRoYXQgbWF0Y2ggYWxlcnRzXG4uYWxlcnQtbGluayB7XG4gIGZvbnQtd2VpZ2h0OiAkYWxlcnQtbGluay1mb250LXdlaWdodDtcbn1cblxuXG4vLyBEaXNtaXNzaWJsZSBhbGVydHNcbi8vXG4vLyBFeHBhbmQgdGhlIHJpZ2h0IHBhZGRpbmcgYW5kIGFjY291bnQgZm9yIHRoZSBjbG9zZSBidXR0b24ncyBwb3NpdGlvbmluZy5cblxuLmFsZXJ0LWRpc21pc3NpYmxlIHtcbiAgLy8gQWRqdXN0IGNsb3NlIGxpbmsgcG9zaXRpb25cbiAgLmNsb3NlIHtcbiAgICBwb3NpdGlvbjogcmVsYXRpdmU7XG4gICAgdG9wOiAtJGFsZXJ0LXBhZGRpbmcteTtcbiAgICByaWdodDogLSRhbGVydC1wYWRkaW5nLXg7XG4gICAgcGFkZGluZzogJGFsZXJ0LXBhZGRpbmcteSAkYWxlcnQtcGFkZGluZy14O1xuICAgIGNvbG9yOiBpbmhlcml0O1xuICB9XG59XG5cblxuLy8gQWx0ZXJuYXRlIHN0eWxlc1xuLy9cbi8vIEdlbmVyYXRlIGNvbnRleHR1YWwgbW9kaWZpZXIgY2xhc3NlcyBmb3IgY29sb3JpemluZyB0aGUgYWxlcnQuXG5cbkBlYWNoICRjb2xvciwgJHZhbHVlIGluICR0aGVtZS1jb2xvcnMge1xuICAuYWxlcnQtI3skY29sb3J9IHtcbiAgICBAaW5jbHVkZSBhbGVydC12YXJpYW50KHRoZW1lLWNvbG9yLWxldmVsKCRjb2xvciwgLTEwKSwgdGhlbWUtY29sb3ItbGV2ZWwoJGNvbG9yLCAtOSksIHRoZW1lLWNvbG9yLWxldmVsKCRjb2xvciwgNikpO1xuICB9XG59XG4iLCJAbWl4aW4gYWxlcnQtdmFyaWFudCgkYmFja2dyb3VuZCwgJGJvcmRlciwgJGNvbG9yKSB7XG4gIGNvbG9yOiAkY29sb3I7XG4gIGJhY2tncm91bmQtY29sb3I6ICRiYWNrZ3JvdW5kO1xuICBib3JkZXItY29sb3I6ICRib3JkZXI7XG5cbiAgaHIge1xuICAgIGJvcmRlci10b3AtY29sb3I6IGRhcmtlbigkYm9yZGVyLCA1JSk7XG4gIH1cblxuICAuYWxlcnQtbGluayB7XG4gICAgY29sb3I6IGRhcmtlbigkY29sb3IsIDEwJSk7XG4gIH1cbn1cbiIsIkBrZXlmcmFtZXMgcHJvZ3Jlc3MtYmFyLXN0cmlwZXMge1xuICBmcm9tIHsgYmFja2dyb3VuZC1wb3NpdGlvbjogJHByb2dyZXNzLWhlaWdodCAwOyB9XG4gIHRvIHsgYmFja2dyb3VuZC1wb3NpdGlvbjogMCAwOyB9XG59XG5cbi5wcm9ncmVzcyB7XG4gIGRpc3BsYXk6IGZsZXg7XG4gIGhlaWdodDogJHByb2dyZXNzLWhlaWdodDtcbiAgb3ZlcmZsb3c6IGhpZGRlbjsgLy8gZm9yY2Ugcm91bmRlZCBjb3JuZXJzIGJ5IGNyb3BwaW5nIGl0XG4gIGZvbnQtc2l6ZTogJHByb2dyZXNzLWZvbnQtc2l6ZTtcbiAgYmFja2dyb3VuZC1jb2xvcjogJHByb2dyZXNzLWJnO1xuICBAaW5jbHVkZSBib3JkZXItcmFkaXVzKCRwcm9ncmVzcy1ib3JkZXItcmFkaXVzKTtcbn1cblxuLnByb2dyZXNzLWJhciB7XG4gIGRpc3BsYXk6IGZsZXg7XG4gIGFsaWduLWl0ZW1zOiBjZW50ZXI7XG4gIGp1c3RpZnktY29udGVudDogY2VudGVyO1xuICBjb2xvcjogJHByb2dyZXNzLWJhci1jb2xvcjtcbiAgYmFja2dyb3VuZC1jb2xvcjogJHByb2dyZXNzLWJhci1iZztcbn1cblxuLnByb2dyZXNzLWJhci1zdHJpcGVkIHtcbiAgQGluY2x1ZGUgZ3JhZGllbnQtc3RyaXBlZCgpO1xuICBiYWNrZ3JvdW5kLXNpemU6ICRwcm9ncmVzcy1oZWlnaHQgJHByb2dyZXNzLWhlaWdodDtcbn1cblxuLnByb2dyZXNzLWJhci1hbmltYXRlZCB7XG4gIGFuaW1hdGlvbjogcHJvZ3Jlc3MtYmFyLXN0cmlwZXMgJHByb2dyZXNzLWJhci1hbmltYXRpb24tdGltaW5nO1xufVxuIiwiLy8gR3JhZGllbnRzXG5cbi8vIEhvcml6b250YWwgZ3JhZGllbnQsIGZyb20gbGVmdCB0byByaWdodFxuLy9cbi8vIENyZWF0ZXMgdHdvIGNvbG9yIHN0b3BzLCBzdGFydCBhbmQgZW5kLCBieSBzcGVjaWZ5aW5nIGEgY29sb3IgYW5kIHBvc2l0aW9uIGZvciBlYWNoIGNvbG9yIHN0b3AuXG5AbWl4aW4gZ3JhZGllbnQteCgkc3RhcnQtY29sb3I6ICM1NTUsICRlbmQtY29sb3I6ICMzMzMsICRzdGFydC1wZXJjZW50OiAwJSwgJGVuZC1wZXJjZW50OiAxMDAlKSB7XG4gIGJhY2tncm91bmQtaW1hZ2U6IGxpbmVhci1ncmFkaWVudCh0byByaWdodCwgJHN0YXJ0LWNvbG9yICRzdGFydC1wZXJjZW50LCAkZW5kLWNvbG9yICRlbmQtcGVyY2VudCk7XG4gIGJhY2tncm91bmQtcmVwZWF0OiByZXBlYXQteDtcbn1cblxuLy8gVmVydGljYWwgZ3JhZGllbnQsIGZyb20gdG9wIHRvIGJvdHRvbVxuLy9cbi8vIENyZWF0ZXMgdHdvIGNvbG9yIHN0b3BzLCBzdGFydCBhbmQgZW5kLCBieSBzcGVjaWZ5aW5nIGEgY29sb3IgYW5kIHBvc2l0aW9uIGZvciBlYWNoIGNvbG9yIHN0b3AuXG5AbWl4aW4gZ3JhZGllbnQteSgkc3RhcnQtY29sb3I6ICM1NTUsICRlbmQtY29sb3I6ICMzMzMsICRzdGFydC1wZXJjZW50OiAwJSwgJGVuZC1wZXJjZW50OiAxMDAlKSB7XG4gIGJhY2tncm91bmQtaW1hZ2U6IGxpbmVhci1ncmFkaWVudCh0byBib3R0b20sICRzdGFydC1jb2xvciAkc3RhcnQtcGVyY2VudCwgJGVuZC1jb2xvciAkZW5kLXBlcmNlbnQpO1xuICBiYWNrZ3JvdW5kLXJlcGVhdDogcmVwZWF0LXg7XG59XG5cbkBtaXhpbiBncmFkaWVudC1kaXJlY3Rpb25hbCgkc3RhcnQtY29sb3I6ICM1NTUsICRlbmQtY29sb3I6ICMzMzMsICRkZWc6IDQ1ZGVnKSB7XG4gIGJhY2tncm91bmQtaW1hZ2U6IGxpbmVhci1ncmFkaWVudCgkZGVnLCAkc3RhcnQtY29sb3IsICRlbmQtY29sb3IpO1xuICBiYWNrZ3JvdW5kLXJlcGVhdDogcmVwZWF0LXg7XG59XG5AbWl4aW4gZ3JhZGllbnQteC10aHJlZS1jb2xvcnMoJHN0YXJ0LWNvbG9yOiAjMDBiM2VlLCAkbWlkLWNvbG9yOiAjN2E0M2I2LCAkY29sb3Itc3RvcDogNTAlLCAkZW5kLWNvbG9yOiAjYzMzMjVmKSB7XG4gIGJhY2tncm91bmQtaW1hZ2U6IGxpbmVhci1ncmFkaWVudCh0byByaWdodCwgJHN0YXJ0LWNvbG9yLCAkbWlkLWNvbG9yICRjb2xvci1zdG9wLCAkZW5kLWNvbG9yKTtcbiAgYmFja2dyb3VuZC1yZXBlYXQ6IG5vLXJlcGVhdDtcbn1cbkBtaXhpbiBncmFkaWVudC15LXRocmVlLWNvbG9ycygkc3RhcnQtY29sb3I6ICMwMGIzZWUsICRtaWQtY29sb3I6ICM3YTQzYjYsICRjb2xvci1zdG9wOiA1MCUsICRlbmQtY29sb3I6ICNjMzMyNWYpIHtcbiAgYmFja2dyb3VuZC1pbWFnZTogbGluZWFyLWdyYWRpZW50KCRzdGFydC1jb2xvciwgJG1pZC1jb2xvciAkY29sb3Itc3RvcCwgJGVuZC1jb2xvcik7XG4gIGJhY2tncm91bmQtcmVwZWF0OiBuby1yZXBlYXQ7XG59XG5AbWl4aW4gZ3JhZGllbnQtcmFkaWFsKCRpbm5lci1jb2xvcjogIzU1NSwgJG91dGVyLWNvbG9yOiAjMzMzKSB7XG4gIGJhY2tncm91bmQtaW1hZ2U6IHJhZGlhbC1ncmFkaWVudChjaXJjbGUsICRpbm5lci1jb2xvciwgJG91dGVyLWNvbG9yKTtcbiAgYmFja2dyb3VuZC1yZXBlYXQ6IG5vLXJlcGVhdDtcbn1cbkBtaXhpbiBncmFkaWVudC1zdHJpcGVkKCRjb2xvcjogcmdiYSgyNTUsMjU1LDI1NSwuMTUpLCAkYW5nbGU6IDQ1ZGVnKSB7XG4gIGJhY2tncm91bmQtaW1hZ2U6IGxpbmVhci1ncmFkaWVudCgkYW5nbGUsICRjb2xvciAyNSUsIHRyYW5zcGFyZW50IDI1JSwgdHJhbnNwYXJlbnQgNTAlLCAkY29sb3IgNTAlLCAkY29sb3IgNzUlLCB0cmFuc3BhcmVudCA3NSUsIHRyYW5zcGFyZW50KTtcbn1cbiIsIi5tZWRpYSB7XG4gIGRpc3BsYXk6IGZsZXg7XG4gIGFsaWduLWl0ZW1zOiBmbGV4LXN0YXJ0O1xufVxuXG4ubWVkaWEtYm9keSB7XG4gIGZsZXg6IDE7XG59XG4iLCIvLyBCYXNlIGNsYXNzXG4vL1xuLy8gRWFzaWx5IHVzYWJsZSBvbiA8dWw+LCA8b2w+LCBvciA8ZGl2Pi5cblxuLmxpc3QtZ3JvdXAge1xuICBkaXNwbGF5OiBmbGV4O1xuICBmbGV4LWRpcmVjdGlvbjogY29sdW1uO1xuXG4gIC8vIE5vIG5lZWQgdG8gc2V0IGxpc3Qtc3R5bGU6IG5vbmU7IHNpbmNlIC5saXN0LWdyb3VwLWl0ZW0gaXMgYmxvY2sgbGV2ZWxcbiAgcGFkZGluZy1sZWZ0OiAwOyAvLyByZXNldCBwYWRkaW5nIGJlY2F1c2UgdWwgYW5kIG9sXG4gIG1hcmdpbi1ib3R0b206IDA7XG59XG5cblxuLy8gSW50ZXJhY3RpdmUgbGlzdCBpdGVtc1xuLy9cbi8vIFVzZSBhbmNob3Igb3IgYnV0dG9uIGVsZW1lbnRzIGluc3RlYWQgb2YgYGxpYHMgb3IgYGRpdmBzIHRvIGNyZWF0ZSBpbnRlcmFjdGl2ZVxuLy8gbGlzdCBpdGVtcy4gSW5jbHVkZXMgYW4gZXh0cmEgYC5hY3RpdmVgIG1vZGlmaWVyIGNsYXNzIGZvciBzZWxlY3RlZCBpdGVtcy5cblxuLmxpc3QtZ3JvdXAtaXRlbS1hY3Rpb24ge1xuICB3aWR0aDogMTAwJTsgLy8gRm9yIGA8YnV0dG9uPmBzIChhbmNob3JzIGJlY29tZSAxMDAlIGJ5IGRlZmF1bHQgdGhvdWdoKVxuICBjb2xvcjogJGxpc3QtZ3JvdXAtYWN0aW9uLWNvbG9yO1xuICB0ZXh0LWFsaWduOiBpbmhlcml0OyAvLyBGb3IgYDxidXR0b24+YHMgKGFuY2hvcnMgaW5oZXJpdClcblxuICAvLyBIb3ZlciBzdGF0ZVxuICBAaW5jbHVkZSBob3Zlci1mb2N1cyB7XG4gICAgY29sb3I6ICRsaXN0LWdyb3VwLWFjdGlvbi1ob3Zlci1jb2xvcjtcbiAgICB0ZXh0LWRlY29yYXRpb246IG5vbmU7XG4gICAgYmFja2dyb3VuZC1jb2xvcjogJGxpc3QtZ3JvdXAtaG92ZXItYmc7XG4gIH1cblxuICAmOmFjdGl2ZSB7XG4gICAgY29sb3I6ICRsaXN0LWdyb3VwLWFjdGlvbi1hY3RpdmUtY29sb3I7XG4gICAgYmFja2dyb3VuZC1jb2xvcjogJGxpc3QtZ3JvdXAtYWN0aW9uLWFjdGl2ZS1iZztcbiAgfVxufVxuXG5cbi8vIEluZGl2aWR1YWwgbGlzdCBpdGVtc1xuLy9cbi8vIFVzZSBvbiBgbGlgcyBvciBgZGl2YHMgd2l0aGluIHRoZSBgLmxpc3QtZ3JvdXBgIHBhcmVudC5cblxuLmxpc3QtZ3JvdXAtaXRlbSB7XG4gIHBvc2l0aW9uOiByZWxhdGl2ZTtcbiAgZGlzcGxheTogYmxvY2s7XG4gIHBhZGRpbmc6ICRsaXN0LWdyb3VwLWl0ZW0tcGFkZGluZy15ICRsaXN0LWdyb3VwLWl0ZW0tcGFkZGluZy14O1xuICAvLyBQbGFjZSB0aGUgYm9yZGVyIG9uIHRoZSBsaXN0IGl0ZW1zIGFuZCBuZWdhdGl2ZSBtYXJnaW4gdXAgZm9yIGJldHRlciBzdHlsaW5nXG4gIG1hcmdpbi1ib3R0b206IC0kbGlzdC1ncm91cC1ib3JkZXItd2lkdGg7XG4gIGJhY2tncm91bmQtY29sb3I6ICRsaXN0LWdyb3VwLWJnO1xuICBib3JkZXI6ICRsaXN0LWdyb3VwLWJvcmRlci13aWR0aCBzb2xpZCAkbGlzdC1ncm91cC1ib3JkZXItY29sb3I7XG5cbiAgJjpmaXJzdC1jaGlsZCB7XG4gICAgQGluY2x1ZGUgYm9yZGVyLXRvcC1yYWRpdXMoJGxpc3QtZ3JvdXAtYm9yZGVyLXJhZGl1cyk7XG4gIH1cblxuICAmOmxhc3QtY2hpbGQge1xuICAgIG1hcmdpbi1ib3R0b206IDA7XG4gICAgQGluY2x1ZGUgYm9yZGVyLWJvdHRvbS1yYWRpdXMoJGxpc3QtZ3JvdXAtYm9yZGVyLXJhZGl1cyk7XG4gIH1cblxuICBAaW5jbHVkZSBob3Zlci1mb2N1cyB7XG4gICAgdGV4dC1kZWNvcmF0aW9uOiBub25lO1xuICB9XG5cbiAgJi5kaXNhYmxlZCxcbiAgJjpkaXNhYmxlZCB7XG4gICAgY29sb3I6ICRsaXN0LWdyb3VwLWRpc2FibGVkLWNvbG9yO1xuICAgIGJhY2tncm91bmQtY29sb3I6ICRsaXN0LWdyb3VwLWRpc2FibGVkLWJnO1xuICB9XG5cbiAgLy8gSW5jbHVkZSBib3RoIGhlcmUgZm9yIGA8YT5gcyBhbmQgYDxidXR0b24+YHNcbiAgJi5hY3RpdmUge1xuICAgIHotaW5kZXg6IDI7IC8vIFBsYWNlIGFjdGl2ZSBpdGVtcyBhYm92ZSB0aGVpciBzaWJsaW5ncyBmb3IgcHJvcGVyIGJvcmRlciBzdHlsaW5nXG4gICAgY29sb3I6ICRsaXN0LWdyb3VwLWFjdGl2ZS1jb2xvcjtcbiAgICBiYWNrZ3JvdW5kLWNvbG9yOiAkbGlzdC1ncm91cC1hY3RpdmUtYmc7XG4gICAgYm9yZGVyLWNvbG9yOiAkbGlzdC1ncm91cC1hY3RpdmUtYm9yZGVyLWNvbG9yO1xuICB9XG59XG5cblxuLy8gRmx1c2ggbGlzdCBpdGVtc1xuLy9cbi8vIFJlbW92ZSBib3JkZXJzIGFuZCBib3JkZXItcmFkaXVzIHRvIGtlZXAgbGlzdCBncm91cCBpdGVtcyBlZGdlLXRvLWVkZ2UuIE1vc3Rcbi8vIHVzZWZ1bCB3aXRoaW4gb3RoZXIgY29tcG9uZW50cyAoZS5nLiwgY2FyZHMpLlxuXG4ubGlzdC1ncm91cC1mbHVzaCB7XG4gIC5saXN0LWdyb3VwLWl0ZW0ge1xuICAgIGJvcmRlci1yaWdodDogMDtcbiAgICBib3JkZXItbGVmdDogMDtcbiAgICBib3JkZXItcmFkaXVzOiAwO1xuICB9XG5cbiAgJjpmaXJzdC1jaGlsZCB7XG4gICAgLmxpc3QtZ3JvdXAtaXRlbTpmaXJzdC1jaGlsZCB7XG4gICAgICBib3JkZXItdG9wOiAwO1xuICAgIH1cbiAgfVxuXG4gICY6bGFzdC1jaGlsZCB7XG4gICAgLmxpc3QtZ3JvdXAtaXRlbTpsYXN0LWNoaWxkIHtcbiAgICAgIGJvcmRlci1ib3R0b206IDA7XG4gICAgfVxuICB9XG59XG5cblxuLy8gQ29udGV4dHVhbCB2YXJpYW50c1xuLy9cbi8vIEFkZCBtb2RpZmllciBjbGFzc2VzIHRvIGNoYW5nZSB0ZXh0IGFuZCBiYWNrZ3JvdW5kIGNvbG9yIG9uIGluZGl2aWR1YWwgaXRlbXMuXG4vLyBPcmdhbml6YXRpb25hbGx5LCB0aGlzIG11c3QgY29tZSBhZnRlciB0aGUgYDpob3ZlcmAgc3RhdGVzLlxuXG5AZWFjaCAkY29sb3IsICR2YWx1ZSBpbiAkdGhlbWUtY29sb3JzIHtcbiAgQGluY2x1ZGUgbGlzdC1ncm91cC1pdGVtLXZhcmlhbnQoJGNvbG9yLCB0aGVtZS1jb2xvci1sZXZlbCgkY29sb3IsIC05KSwgdGhlbWUtY29sb3ItbGV2ZWwoJGNvbG9yLCA2KSk7XG59XG4iLCIvLyBMaXN0IEdyb3Vwc1xuXG5AbWl4aW4gbGlzdC1ncm91cC1pdGVtLXZhcmlhbnQoJHN0YXRlLCAkYmFja2dyb3VuZCwgJGNvbG9yKSB7XG4gIC5saXN0LWdyb3VwLWl0ZW0tI3skc3RhdGV9IHtcbiAgICBjb2xvcjogJGNvbG9yO1xuICAgIGJhY2tncm91bmQtY29sb3I6ICRiYWNrZ3JvdW5kO1xuICB9XG5cbiAgLy9zY3NzLWxpbnQ6ZGlzYWJsZSBRdWFsaWZ5aW5nRWxlbWVudFxuICBhLmxpc3QtZ3JvdXAtaXRlbS0jeyRzdGF0ZX0sXG4gIGJ1dHRvbi5saXN0LWdyb3VwLWl0ZW0tI3skc3RhdGV9IHtcbiAgICBjb2xvcjogJGNvbG9yO1xuXG4gICAgQGluY2x1ZGUgaG92ZXItZm9jdXMge1xuICAgICAgY29sb3I6ICRjb2xvcjtcbiAgICAgIGJhY2tncm91bmQtY29sb3I6IGRhcmtlbigkYmFja2dyb3VuZCwgNSUpO1xuICAgIH1cblxuICAgICYuYWN0aXZlIHtcbiAgICAgIGNvbG9yOiAjZmZmO1xuICAgICAgYmFja2dyb3VuZC1jb2xvcjogJGNvbG9yO1xuICAgICAgYm9yZGVyLWNvbG9yOiAkY29sb3I7XG4gICAgfVxuICB9XG4gIC8vIHNjc3MtbGludDplbmFibGUgUXVhbGlmeWluZ0VsZW1lbnRcbn1cbiIsIi5jbG9zZSB7XG4gIGZsb2F0OiByaWdodDtcbiAgZm9udC1zaXplOiAkY2xvc2UtZm9udC1zaXplO1xuICBmb250LXdlaWdodDogJGNsb3NlLWZvbnQtd2VpZ2h0O1xuICBsaW5lLWhlaWdodDogMTtcbiAgY29sb3I6ICRjbG9zZS1jb2xvcjtcbiAgdGV4dC1zaGFkb3c6ICRjbG9zZS10ZXh0LXNoYWRvdztcbiAgb3BhY2l0eTogLjU7XG5cbiAgQGluY2x1ZGUgaG92ZXItZm9jdXMge1xuICAgIGNvbG9yOiAkY2xvc2UtY29sb3I7XG4gICAgdGV4dC1kZWNvcmF0aW9uOiBub25lO1xuICAgIG9wYWNpdHk6IC43NTtcbiAgfVxufVxuXG4vLyBBZGRpdGlvbmFsIHByb3BlcnRpZXMgZm9yIGJ1dHRvbiB2ZXJzaW9uXG4vLyBpT1MgcmVxdWlyZXMgdGhlIGJ1dHRvbiBlbGVtZW50IGluc3RlYWQgb2YgYW4gYW5jaG9yIHRhZy5cbi8vIElmIHlvdSB3YW50IHRoZSBhbmNob3IgdmVyc2lvbiwgaXQgcmVxdWlyZXMgYGhyZWY9XCIjXCJgLlxuLy8gU2VlIGh0dHBzOi8vZGV2ZWxvcGVyLm1vemlsbGEub3JnL2VuLVVTL2RvY3MvV2ViL0V2ZW50cy9jbGljayNTYWZhcmlfTW9iaWxlXG5cbi8vIHNjc3MtbGludDpkaXNhYmxlIFF1YWxpZnlpbmdFbGVtZW50XG5idXR0b24uY2xvc2Uge1xuICBwYWRkaW5nOiAwO1xuICBiYWNrZ3JvdW5kOiB0cmFuc3BhcmVudDtcbiAgYm9yZGVyOiAwO1xuICAtd2Via2l0LWFwcGVhcmFuY2U6IG5vbmU7XG59XG4vLyBzY3NzLWxpbnQ6ZW5hYmxlIFF1YWxpZnlpbmdFbGVtZW50XG4iLCIvLyAubW9kYWwtb3BlbiAgICAgIC0gYm9keSBjbGFzcyBmb3Iga2lsbGluZyB0aGUgc2Nyb2xsXG4vLyAubW9kYWwgICAgICAgICAgIC0gY29udGFpbmVyIHRvIHNjcm9sbCB3aXRoaW5cbi8vIC5tb2RhbC1kaWFsb2cgICAgLSBwb3NpdGlvbmluZyBzaGVsbCBmb3IgdGhlIGFjdHVhbCBtb2RhbFxuLy8gLm1vZGFsLWNvbnRlbnQgICAtIGFjdHVhbCBtb2RhbCB3LyBiZyBhbmQgY29ybmVycyBhbmQgc3R1ZmZcblxuXG4vLyBLaWxsIHRoZSBzY3JvbGwgb24gdGhlIGJvZHlcbi5tb2RhbC1vcGVuIHtcbiAgb3ZlcmZsb3c6IGhpZGRlbjtcbn1cblxuLy8gQ29udGFpbmVyIHRoYXQgdGhlIG1vZGFsIHNjcm9sbHMgd2l0aGluXG4ubW9kYWwge1xuICBwb3NpdGlvbjogZml4ZWQ7XG4gIHRvcDogMDtcbiAgcmlnaHQ6IDA7XG4gIGJvdHRvbTogMDtcbiAgbGVmdDogMDtcbiAgei1pbmRleDogJHppbmRleC1tb2RhbDtcbiAgZGlzcGxheTogbm9uZTtcbiAgb3ZlcmZsb3c6IGhpZGRlbjtcbiAgLy8gUHJldmVudCBDaHJvbWUgb24gV2luZG93cyBmcm9tIGFkZGluZyBhIGZvY3VzIG91dGxpbmUuIEZvciBkZXRhaWxzLCBzZWVcbiAgLy8gaHR0cHM6Ly9naXRodWIuY29tL3R3YnMvYm9vdHN0cmFwL3B1bGwvMTA5NTEuXG4gIG91dGxpbmU6IDA7XG4gIC8vIFdlIGRlbGliZXJhdGVseSBkb24ndCB1c2UgYC13ZWJraXQtb3ZlcmZsb3ctc2Nyb2xsaW5nOiB0b3VjaDtgIGR1ZSB0byBhXG4gIC8vIGduYXJseSBpT1MgU2FmYXJpIGJ1ZzogaHR0cHM6Ly9idWdzLndlYmtpdC5vcmcvc2hvd19idWcuY2dpP2lkPTE1ODM0MlxuICAvLyBTZWUgYWxzbyBodHRwczovL2dpdGh1Yi5jb20vdHdicy9ib290c3RyYXAvaXNzdWVzLzE3Njk1XG5cbiAgLy8gV2hlbiBmYWRpbmcgaW4gdGhlIG1vZGFsLCBhbmltYXRlIGl0IHRvIHNsaWRlIGRvd25cbiAgJi5mYWRlIC5tb2RhbC1kaWFsb2cge1xuICAgIEBpbmNsdWRlIHRyYW5zaXRpb24oJG1vZGFsLXRyYW5zaXRpb24pO1xuICAgIHRyYW5zZm9ybTogdHJhbnNsYXRlKDAsIC0yNSUpO1xuICB9XG4gICYuc2hvdyAubW9kYWwtZGlhbG9nIHsgdHJhbnNmb3JtOiB0cmFuc2xhdGUoMCwgMCk7IH1cbn1cbi5tb2RhbC1vcGVuIC5tb2RhbCB7XG4gIG92ZXJmbG93LXg6IGhpZGRlbjtcbiAgb3ZlcmZsb3cteTogYXV0bztcbn1cblxuLy8gU2hlbGwgZGl2IHRvIHBvc2l0aW9uIHRoZSBtb2RhbCB3aXRoIGJvdHRvbSBwYWRkaW5nXG4ubW9kYWwtZGlhbG9nIHtcbiAgcG9zaXRpb246IHJlbGF0aXZlO1xuICB3aWR0aDogYXV0bztcbiAgbWFyZ2luOiAkbW9kYWwtZGlhbG9nLW1hcmdpbjtcbn1cblxuLy8gQWN0dWFsIG1vZGFsXG4ubW9kYWwtY29udGVudCB7XG4gIHBvc2l0aW9uOiByZWxhdGl2ZTtcbiAgZGlzcGxheTogZmxleDtcbiAgZmxleC1kaXJlY3Rpb246IGNvbHVtbjtcbiAgYmFja2dyb3VuZC1jb2xvcjogJG1vZGFsLWNvbnRlbnQtYmc7XG4gIGJhY2tncm91bmQtY2xpcDogcGFkZGluZy1ib3g7XG4gIGJvcmRlcjogJG1vZGFsLWNvbnRlbnQtYm9yZGVyLXdpZHRoIHNvbGlkICRtb2RhbC1jb250ZW50LWJvcmRlci1jb2xvcjtcbiAgQGluY2x1ZGUgYm9yZGVyLXJhZGl1cygkYm9yZGVyLXJhZGl1cy1sZyk7XG4gIEBpbmNsdWRlIGJveC1zaGFkb3coJG1vZGFsLWNvbnRlbnQtYm94LXNoYWRvdy14cyk7XG4gIC8vIFJlbW92ZSBmb2N1cyBvdXRsaW5lIGZyb20gb3BlbmVkIG1vZGFsXG4gIG91dGxpbmU6IDA7XG59XG5cbi8vIE1vZGFsIGJhY2tncm91bmRcbi5tb2RhbC1iYWNrZHJvcCB7XG4gIHBvc2l0aW9uOiBmaXhlZDtcbiAgdG9wOiAwO1xuICByaWdodDogMDtcbiAgYm90dG9tOiAwO1xuICBsZWZ0OiAwO1xuICB6LWluZGV4OiAkemluZGV4LW1vZGFsLWJhY2tkcm9wO1xuICBiYWNrZ3JvdW5kLWNvbG9yOiAkbW9kYWwtYmFja2Ryb3AtYmc7XG5cbiAgLy8gRmFkZSBmb3IgYmFja2Ryb3BcbiAgJi5mYWRlIHsgb3BhY2l0eTogMDsgfVxuICAmLnNob3cgeyBvcGFjaXR5OiAkbW9kYWwtYmFja2Ryb3Atb3BhY2l0eTsgfVxufVxuXG4vLyBNb2RhbCBoZWFkZXJcbi8vIFRvcCBzZWN0aW9uIG9mIHRoZSBtb2RhbCB3LyB0aXRsZSBhbmQgZGlzbWlzc1xuLm1vZGFsLWhlYWRlciB7XG4gIGRpc3BsYXk6IGZsZXg7XG4gIGFsaWduLWl0ZW1zOiBjZW50ZXI7IC8vIHZlcnRpY2FsbHkgY2VudGVyIGl0XG4gIGp1c3RpZnktY29udGVudDogc3BhY2UtYmV0d2VlbjsgLy8gUHV0IG1vZGFsIGhlYWRlciBlbGVtZW50cyAodGl0bGUgYW5kIGRpc21pc3MpIG9uIG9wcG9zaXRlIGVuZHNcbiAgcGFkZGluZzogJG1vZGFsLWhlYWRlci1wYWRkaW5nO1xuICBib3JkZXItYm90dG9tOiAkbW9kYWwtaGVhZGVyLWJvcmRlci13aWR0aCBzb2xpZCAkbW9kYWwtaGVhZGVyLWJvcmRlci1jb2xvcjtcblxuICAuY2xvc2Uge1xuICAgIG1hcmdpbi1sZWZ0OiBhdXRvOyAvLyBGb3JjZSBpY29uIHRvIHRoZSByaWdodCBldmVuIHdoZW4gdGhlcmUncyBubyAubW9kYWwtdGl0bGVcbiAgfVxufVxuXG4vLyBUaXRsZSB0ZXh0IHdpdGhpbiBoZWFkZXJcbi5tb2RhbC10aXRsZSB7XG4gIG1hcmdpbi1ib3R0b206IDA7XG4gIGxpbmUtaGVpZ2h0OiAkbW9kYWwtdGl0bGUtbGluZS1oZWlnaHQ7XG59XG5cbi8vIE1vZGFsIGJvZHlcbi8vIFdoZXJlIGFsbCBtb2RhbCBjb250ZW50IHJlc2lkZXMgKHNpYmxpbmcgb2YgLm1vZGFsLWhlYWRlciBhbmQgLm1vZGFsLWZvb3Rlcilcbi5tb2RhbC1ib2R5IHtcbiAgcG9zaXRpb246IHJlbGF0aXZlO1xuICAvLyBFbmFibGUgYGZsZXgtZ3JvdzogMWAgc28gdGhhdCB0aGUgYm9keSB0YWtlIHVwIGFzIG11Y2ggc3BhY2UgYXMgcG9zc2libGVcbiAgLy8gd2hlbiBzaG91bGQgdGhlcmUgYmUgYSBmaXhlZCBoZWlnaHQgb24gYC5tb2RhbC1kaWFsb2dgLlxuICBmbGV4OiAxIDEgYXV0bztcbiAgcGFkZGluZzogJG1vZGFsLWlubmVyLXBhZGRpbmc7XG59XG5cbi8vIEZvb3RlciAoZm9yIGFjdGlvbnMpXG4ubW9kYWwtZm9vdGVyIHtcbiAgZGlzcGxheTogZmxleDtcbiAgYWxpZ24taXRlbXM6IGNlbnRlcjsgLy8gdmVydGljYWxseSBjZW50ZXJcbiAganVzdGlmeS1jb250ZW50OiBmbGV4LWVuZDsgLy8gUmlnaHQgYWxpZ24gYnV0dG9ucyB3aXRoIGZsZXggcHJvcGVydHkgYmVjYXVzZSB0ZXh0LWFsaWduIGRvZXNuJ3Qgd29yayBvbiBmbGV4IGl0ZW1zXG4gIHBhZGRpbmc6ICRtb2RhbC1pbm5lci1wYWRkaW5nO1xuICBib3JkZXItdG9wOiAkbW9kYWwtZm9vdGVyLWJvcmRlci13aWR0aCBzb2xpZCAkbW9kYWwtZm9vdGVyLWJvcmRlci1jb2xvcjtcblxuICAvLyBFYXNpbHkgcGxhY2UgbWFyZ2luIGJldHdlZW4gZm9vdGVyIGVsZW1lbnRzXG4gID4gOm5vdCg6Zmlyc3QtY2hpbGQpIHsgbWFyZ2luLWxlZnQ6IC4yNXJlbTsgfVxuICA+IDpub3QoOmxhc3QtY2hpbGQpIHsgbWFyZ2luLXJpZ2h0OiAuMjVyZW07IH1cbn1cblxuLy8gTWVhc3VyZSBzY3JvbGxiYXIgd2lkdGggZm9yIHBhZGRpbmcgYm9keSBkdXJpbmcgbW9kYWwgc2hvdy9oaWRlXG4ubW9kYWwtc2Nyb2xsYmFyLW1lYXN1cmUge1xuICBwb3NpdGlvbjogYWJzb2x1dGU7XG4gIHRvcDogLTk5OTlweDtcbiAgd2lkdGg6IDUwcHg7XG4gIGhlaWdodDogNTBweDtcbiAgb3ZlcmZsb3c6IHNjcm9sbDtcbn1cblxuLy8gU2NhbGUgdXAgdGhlIG1vZGFsXG5AaW5jbHVkZSBtZWRpYS1icmVha3BvaW50LXVwKHNtKSB7XG4gIC8vIEF1dG9tYXRpY2FsbHkgc2V0IG1vZGFsJ3Mgd2lkdGggZm9yIGxhcmdlciB2aWV3cG9ydHNcbiAgLm1vZGFsLWRpYWxvZyB7XG4gICAgbWF4LXdpZHRoOiAkbW9kYWwtbWQ7XG4gICAgbWFyZ2luOiAkbW9kYWwtZGlhbG9nLW1hcmdpbi15LXNtLXVwIGF1dG87XG4gIH1cblxuICAubW9kYWwtY29udGVudCB7XG4gICAgQGluY2x1ZGUgYm94LXNoYWRvdygkbW9kYWwtY29udGVudC1ib3gtc2hhZG93LXNtLXVwKTtcbiAgfVxuXG4gIC5tb2RhbC1zbSB7IG1heC13aWR0aDogJG1vZGFsLXNtOyB9XG59XG5cbkBpbmNsdWRlIG1lZGlhLWJyZWFrcG9pbnQtdXAobGcpIHtcbiAgLm1vZGFsLWxnIHsgbWF4LXdpZHRoOiAkbW9kYWwtbGc7IH1cbn1cbiIsIi8vIEJhc2UgY2xhc3Ncbi50b29sdGlwIHtcbiAgcG9zaXRpb246IGFic29sdXRlO1xuICB6LWluZGV4OiAkemluZGV4LXRvb2x0aXA7XG4gIGRpc3BsYXk6IGJsb2NrO1xuICBtYXJnaW46ICR0b29sdGlwLW1hcmdpbjtcbiAgLy8gT3VyIHBhcmVudCBlbGVtZW50IGNhbiBiZSBhcmJpdHJhcnkgc2luY2UgdG9vbHRpcHMgYXJlIGJ5IGRlZmF1bHQgaW5zZXJ0ZWQgYXMgYSBzaWJsaW5nIG9mIHRoZWlyIHRhcmdldCBlbGVtZW50LlxuICAvLyBTbyByZXNldCBvdXIgZm9udCBhbmQgdGV4dCBwcm9wZXJ0aWVzIHRvIGF2b2lkIGluaGVyaXRpbmcgd2VpcmQgdmFsdWVzLlxuICBAaW5jbHVkZSByZXNldC10ZXh0KCk7XG4gIGZvbnQtc2l6ZTogJGZvbnQtc2l6ZS1zbTtcbiAgLy8gQWxsb3cgYnJlYWtpbmcgdmVyeSBsb25nIHdvcmRzIHNvIHRoZXkgZG9uJ3Qgb3ZlcmZsb3cgdGhlIHRvb2x0aXAncyBib3VuZHNcbiAgd29yZC13cmFwOiBicmVhay13b3JkO1xuICBvcGFjaXR5OiAwO1xuXG4gICYuc2hvdyB7IG9wYWNpdHk6ICR0b29sdGlwLW9wYWNpdHk7IH1cblxuICAuYXJyb3cge1xuICAgIHBvc2l0aW9uOiBhYnNvbHV0ZTtcbiAgICBkaXNwbGF5OiBibG9jaztcbiAgICB3aWR0aDogJHRvb2x0aXAtYXJyb3ctd2lkdGg7XG4gICAgaGVpZ2h0OiAkdG9vbHRpcC1hcnJvdy1oZWlnaHQ7XG4gIH1cblxuICAmLmJzLXRvb2x0aXAtdG9wIHtcbiAgICBwYWRkaW5nOiAkdG9vbHRpcC1hcnJvdy13aWR0aCAwO1xuICAgIC5hcnJvdyB7XG4gICAgICBib3R0b206IDA7XG4gICAgfVxuXG4gICAgLmFycm93OjpiZWZvcmUge1xuICAgICAgbWFyZ2luLWxlZnQ6IC0oJHRvb2x0aXAtYXJyb3ctd2lkdGggLSAyKTtcbiAgICAgIGNvbnRlbnQ6IFwiXCI7XG4gICAgICBib3JkZXItd2lkdGg6ICR0b29sdGlwLWFycm93LXdpZHRoICR0b29sdGlwLWFycm93LXdpZHRoIDA7XG4gICAgICBib3JkZXItdG9wLWNvbG9yOiAkdG9vbHRpcC1hcnJvdy1jb2xvcjtcbiAgICB9XG4gIH1cbiAgJi5icy10b29sdGlwLXJpZ2h0IHtcbiAgICBwYWRkaW5nOiAwICR0b29sdGlwLWFycm93LXdpZHRoO1xuICAgIC5hcnJvdyB7XG4gICAgICBsZWZ0OiAwO1xuICAgIH1cblxuICAgIC5hcnJvdzo6YmVmb3JlIHtcbiAgICAgIG1hcmdpbi10b3A6IC0oJHRvb2x0aXAtYXJyb3ctd2lkdGggLSAyKTtcbiAgICAgIGNvbnRlbnQ6IFwiXCI7XG4gICAgICBib3JkZXItd2lkdGg6ICR0b29sdGlwLWFycm93LXdpZHRoICR0b29sdGlwLWFycm93LXdpZHRoICR0b29sdGlwLWFycm93LXdpZHRoIDA7XG4gICAgICBib3JkZXItcmlnaHQtY29sb3I6ICR0b29sdGlwLWFycm93LWNvbG9yO1xuICAgIH1cbiAgfVxuICAmLmJzLXRvb2x0aXAtYm90dG9tIHtcbiAgICBwYWRkaW5nOiAkdG9vbHRpcC1hcnJvdy13aWR0aCAwO1xuICAgIC5hcnJvdyB7XG4gICAgICB0b3A6IDA7XG4gICAgfVxuXG4gICAgLmFycm93OjpiZWZvcmUge1xuICAgICAgbWFyZ2luLWxlZnQ6IC0oJHRvb2x0aXAtYXJyb3ctd2lkdGggLSAyKTtcbiAgICAgIGNvbnRlbnQ6IFwiXCI7XG4gICAgICBib3JkZXItd2lkdGg6IDAgJHRvb2x0aXAtYXJyb3ctd2lkdGggJHRvb2x0aXAtYXJyb3ctd2lkdGg7XG4gICAgICBib3JkZXItYm90dG9tLWNvbG9yOiAkdG9vbHRpcC1hcnJvdy1jb2xvcjtcbiAgICB9XG4gIH1cbiAgJi5icy10b29sdGlwLWxlZnQge1xuICAgIHBhZGRpbmc6IDAgJHRvb2x0aXAtYXJyb3ctd2lkdGg7XG4gICAgLmFycm93IHtcbiAgICAgIHJpZ2h0OiAwO1xuICAgIH1cblxuICAgIC5hcnJvdzo6YmVmb3JlIHtcbiAgICAgIHJpZ2h0OiAwO1xuICAgICAgbWFyZ2luLXRvcDogLSgkdG9vbHRpcC1hcnJvdy13aWR0aCAtIDIpO1xuICAgICAgY29udGVudDogXCJcIjtcbiAgICAgIGJvcmRlci13aWR0aDogJHRvb2x0aXAtYXJyb3ctd2lkdGggMCAkdG9vbHRpcC1hcnJvdy13aWR0aCAkdG9vbHRpcC1hcnJvdy13aWR0aDtcbiAgICAgIGJvcmRlci1sZWZ0LWNvbG9yOiAkdG9vbHRpcC1hcnJvdy1jb2xvcjtcbiAgICB9XG4gIH1cbiAgJi5icy10b29sdGlwLWF1dG8ge1xuICAgICZbeC1wbGFjZW1lbnRePVwidG9wXCJdIHtcbiAgICAgIEBleHRlbmQgLmJzLXRvb2x0aXAtdG9wO1xuICAgIH1cbiAgICAmW3gtcGxhY2VtZW50Xj1cInJpZ2h0XCJdIHtcbiAgICAgIEBleHRlbmQgLmJzLXRvb2x0aXAtcmlnaHQ7XG4gICAgfVxuICAgICZbeC1wbGFjZW1lbnRePVwiYm90dG9tXCJdIHtcbiAgICAgIEBleHRlbmQgLmJzLXRvb2x0aXAtYm90dG9tO1xuICAgIH1cbiAgICAmW3gtcGxhY2VtZW50Xj1cImxlZnRcIl0ge1xuICAgICAgQGV4dGVuZCAuYnMtdG9vbHRpcC1sZWZ0O1xuICAgIH1cbiAgfVxuXG4gIC5hcnJvdzo6YmVmb3JlIHtcbiAgICBwb3NpdGlvbjogYWJzb2x1dGU7XG4gICAgYm9yZGVyLWNvbG9yOiB0cmFuc3BhcmVudDtcbiAgICBib3JkZXItc3R5bGU6IHNvbGlkO1xuICB9XG59XG5cbi8vIFdyYXBwZXIgZm9yIHRoZSB0b29sdGlwIGNvbnRlbnRcbi50b29sdGlwLWlubmVyIHtcbiAgbWF4LXdpZHRoOiAkdG9vbHRpcC1tYXgtd2lkdGg7XG4gIHBhZGRpbmc6ICR0b29sdGlwLXBhZGRpbmcteSAkdG9vbHRpcC1wYWRkaW5nLXg7XG4gIGNvbG9yOiAkdG9vbHRpcC1jb2xvcjtcbiAgdGV4dC1hbGlnbjogY2VudGVyO1xuICBiYWNrZ3JvdW5kLWNvbG9yOiAkdG9vbHRpcC1iZztcbiAgQGluY2x1ZGUgYm9yZGVyLXJhZGl1cygkYm9yZGVyLXJhZGl1cyk7XG59XG4iLCIvLyBzY3NzLWxpbnQ6ZGlzYWJsZSBEdXBsaWNhdGVQcm9wZXJ0eVxuQG1peGluIHJlc2V0LXRleHQge1xuICBmb250LWZhbWlseTogJGZvbnQtZmFtaWx5LWJhc2U7XG4gIC8vIFdlIGRlbGliZXJhdGVseSBkbyBOT1QgcmVzZXQgZm9udC1zaXplIG9yIHdvcmQtd3JhcC5cbiAgZm9udC1zdHlsZTogbm9ybWFsO1xuICBmb250LXdlaWdodDogJGZvbnQtd2VpZ2h0LW5vcm1hbDtcbiAgbGluZS1oZWlnaHQ6ICRsaW5lLWhlaWdodC1iYXNlO1xuICB0ZXh0LWFsaWduOiBsZWZ0OyAvLyBGYWxsYmFjayBmb3Igd2hlcmUgYHN0YXJ0YCBpcyBub3Qgc3VwcG9ydGVkXG4gIHRleHQtYWxpZ246IHN0YXJ0O1xuICB0ZXh0LWRlY29yYXRpb246IG5vbmU7XG4gIHRleHQtc2hhZG93OiBub25lO1xuICB0ZXh0LXRyYW5zZm9ybTogbm9uZTtcbiAgbGV0dGVyLXNwYWNpbmc6IG5vcm1hbDtcbiAgd29yZC1icmVhazogbm9ybWFsO1xuICB3b3JkLXNwYWNpbmc6IG5vcm1hbDtcbiAgd2hpdGUtc3BhY2U6IG5vcm1hbDtcbiAgbGluZS1icmVhazogYXV0bztcbn1cbiIsIi5wb3BvdmVyIHtcbiAgcG9zaXRpb246IGFic29sdXRlO1xuICB0b3A6IDA7XG4gIGxlZnQ6IDA7XG4gIHotaW5kZXg6ICR6aW5kZXgtcG9wb3ZlcjtcbiAgZGlzcGxheTogYmxvY2s7XG4gIG1heC13aWR0aDogJHBvcG92ZXItbWF4LXdpZHRoO1xuICBwYWRkaW5nOiAkcG9wb3Zlci1pbm5lci1wYWRkaW5nO1xuICAvLyBPdXIgcGFyZW50IGVsZW1lbnQgY2FuIGJlIGFyYml0cmFyeSBzaW5jZSB0b29sdGlwcyBhcmUgYnkgZGVmYXVsdCBpbnNlcnRlZCBhcyBhIHNpYmxpbmcgb2YgdGhlaXIgdGFyZ2V0IGVsZW1lbnQuXG4gIC8vIFNvIHJlc2V0IG91ciBmb250IGFuZCB0ZXh0IHByb3BlcnRpZXMgdG8gYXZvaWQgaW5oZXJpdGluZyB3ZWlyZCB2YWx1ZXMuXG4gIEBpbmNsdWRlIHJlc2V0LXRleHQoKTtcbiAgZm9udC1zaXplOiAkZm9udC1zaXplLXNtO1xuICAvLyBBbGxvdyBicmVha2luZyB2ZXJ5IGxvbmcgd29yZHMgc28gdGhleSBkb24ndCBvdmVyZmxvdyB0aGUgcG9wb3ZlcidzIGJvdW5kc1xuICB3b3JkLXdyYXA6IGJyZWFrLXdvcmQ7XG4gIGJhY2tncm91bmQtY29sb3I6ICRwb3BvdmVyLWJnO1xuICBiYWNrZ3JvdW5kLWNsaXA6IHBhZGRpbmctYm94O1xuICBib3JkZXI6ICRwb3BvdmVyLWJvcmRlci13aWR0aCBzb2xpZCAkcG9wb3Zlci1ib3JkZXItY29sb3I7XG4gIEBpbmNsdWRlIGJvcmRlci1yYWRpdXMoJGJvcmRlci1yYWRpdXMtbGcpO1xuICBAaW5jbHVkZSBib3gtc2hhZG93KCRwb3BvdmVyLWJveC1zaGFkb3cpO1xuXG4gIC8vIEFycm93c1xuICAvL1xuICAvLyAuYXJyb3cgaXMgb3V0ZXIsIC5hcnJvdzo6YWZ0ZXIgaXMgaW5uZXJcblxuICAuYXJyb3cge1xuICAgIHBvc2l0aW9uOiBhYnNvbHV0ZTtcbiAgICBkaXNwbGF5OiBibG9jaztcbiAgICB3aWR0aDogJHBvcG92ZXItYXJyb3ctd2lkdGg7XG4gICAgaGVpZ2h0OiAkcG9wb3Zlci1hcnJvdy1oZWlnaHQ7XG4gIH1cblxuICAuYXJyb3c6OmJlZm9yZSxcbiAgLmFycm93OjphZnRlciB7XG4gICAgcG9zaXRpb246IGFic29sdXRlO1xuICAgIGRpc3BsYXk6IGJsb2NrO1xuICAgIGJvcmRlci1jb2xvcjogdHJhbnNwYXJlbnQ7XG4gICAgYm9yZGVyLXN0eWxlOiBzb2xpZDtcbiAgfVxuXG4gIC5hcnJvdzo6YmVmb3JlIHtcbiAgICBjb250ZW50OiBcIlwiO1xuICAgIGJvcmRlci13aWR0aDogJHBvcG92ZXItYXJyb3ctb3V0ZXItd2lkdGg7XG4gIH1cbiAgLmFycm93OjphZnRlciB7XG4gICAgY29udGVudDogXCJcIjtcbiAgICBib3JkZXItd2lkdGg6ICRwb3BvdmVyLWFycm93LW91dGVyLXdpZHRoO1xuICB9XG5cbiAgLy8gUG9wb3ZlciBkaXJlY3Rpb25zXG5cbiAgJi5icy1wb3BvdmVyLXRvcCB7XG4gICAgbWFyZ2luLWJvdHRvbTogJHBvcG92ZXItYXJyb3ctd2lkdGg7XG5cbiAgICAuYXJyb3cge1xuICAgICAgYm90dG9tOiAwO1xuICAgIH1cblxuICAgIC5hcnJvdzo6YmVmb3JlLFxuICAgIC5hcnJvdzo6YWZ0ZXIge1xuICAgICAgYm9yZGVyLWJvdHRvbS13aWR0aDogMDtcbiAgICB9XG5cbiAgICAuYXJyb3c6OmJlZm9yZSB7XG4gICAgICBib3R0b206IC0kcG9wb3Zlci1hcnJvdy1vdXRlci13aWR0aDtcbiAgICAgIG1hcmdpbi1sZWZ0OiAtKCRwb3BvdmVyLWFycm93LW91dGVyLXdpZHRoIC0gNSk7XG4gICAgICBib3JkZXItdG9wLWNvbG9yOiAkcG9wb3Zlci1hcnJvdy1vdXRlci1jb2xvcjtcbiAgICB9XG5cbiAgICAuYXJyb3c6OmFmdGVyIHtcbiAgICAgIGJvdHRvbTogLSgkcG9wb3Zlci1hcnJvdy1vdXRlci13aWR0aCAtIDEpO1xuICAgICAgbWFyZ2luLWxlZnQ6IC0oJHBvcG92ZXItYXJyb3ctb3V0ZXItd2lkdGggLSA1KTtcbiAgICAgIGJvcmRlci10b3AtY29sb3I6ICRwb3BvdmVyLWFycm93LWNvbG9yO1xuICAgIH1cbiAgfVxuXG4gICYuYnMtcG9wb3Zlci1yaWdodCB7XG4gICAgbWFyZ2luLWxlZnQ6ICRwb3BvdmVyLWFycm93LXdpZHRoO1xuXG4gICAgLmFycm93IHtcbiAgICAgIGxlZnQ6IDA7XG4gICAgfVxuXG4gICAgLmFycm93OjpiZWZvcmUsXG4gICAgLmFycm93OjphZnRlciB7XG4gICAgICBtYXJnaW4tdG9wOiAtKCRwb3BvdmVyLWFycm93LW91dGVyLXdpZHRoIC0gMyk7XG4gICAgICBib3JkZXItbGVmdC13aWR0aDogMDtcbiAgICB9XG5cbiAgICAuYXJyb3c6OmJlZm9yZSB7XG4gICAgICBsZWZ0OiAtJHBvcG92ZXItYXJyb3ctb3V0ZXItd2lkdGg7XG4gICAgICBib3JkZXItcmlnaHQtY29sb3I6ICRwb3BvdmVyLWFycm93LW91dGVyLWNvbG9yO1xuICAgIH1cblxuICAgIC5hcnJvdzo6YWZ0ZXIge1xuICAgICAgbGVmdDogLSgkcG9wb3Zlci1hcnJvdy1vdXRlci13aWR0aCAtIDEpO1xuICAgICAgYm9yZGVyLXJpZ2h0LWNvbG9yOiAkcG9wb3Zlci1hcnJvdy1jb2xvcjtcbiAgICB9XG4gIH1cblxuICAmLmJzLXBvcG92ZXItYm90dG9tIHtcbiAgICBtYXJnaW4tdG9wOiAkcG9wb3Zlci1hcnJvdy13aWR0aDtcblxuICAgIC5hcnJvdyB7XG4gICAgICB0b3A6IDA7XG4gICAgfVxuXG4gICAgLmFycm93OjpiZWZvcmUsXG4gICAgLmFycm93OjphZnRlciB7XG4gICAgICBtYXJnaW4tbGVmdDogLSgkcG9wb3Zlci1hcnJvdy13aWR0aCAtIDMpO1xuICAgICAgYm9yZGVyLXRvcC13aWR0aDogMDtcbiAgICB9XG5cbiAgICAuYXJyb3c6OmJlZm9yZSB7XG4gICAgICB0b3A6IC0kcG9wb3Zlci1hcnJvdy1vdXRlci13aWR0aDtcbiAgICAgIGJvcmRlci1ib3R0b20tY29sb3I6ICRwb3BvdmVyLWFycm93LW91dGVyLWNvbG9yO1xuICAgIH1cblxuICAgIC5hcnJvdzo6YWZ0ZXIge1xuICAgICAgdG9wOiAtKCRwb3BvdmVyLWFycm93LW91dGVyLXdpZHRoIC0gMSk7XG4gICAgICBib3JkZXItYm90dG9tLWNvbG9yOiAkcG9wb3Zlci1hcnJvdy1jb2xvcjtcbiAgICB9XG5cbiAgICAvLyBUaGlzIHdpbGwgcmVtb3ZlIHRoZSBwb3BvdmVyLWhlYWRlcidzIGJvcmRlciBqdXN0IGJlbG93IHRoZSBhcnJvd1xuICAgIC5wb3BvdmVyLWhlYWRlcjo6YmVmb3JlIHtcbiAgICAgIHBvc2l0aW9uOiBhYnNvbHV0ZTtcbiAgICAgIHRvcDogMDtcbiAgICAgIGxlZnQ6IDUwJTtcbiAgICAgIGRpc3BsYXk6IGJsb2NrO1xuICAgICAgd2lkdGg6IDIwcHg7XG4gICAgICBtYXJnaW4tbGVmdDogLTEwcHg7XG4gICAgICBjb250ZW50OiBcIlwiO1xuICAgICAgYm9yZGVyLWJvdHRvbTogMXB4IHNvbGlkICRwb3BvdmVyLWhlYWRlci1iZztcbiAgICB9XG4gIH1cblxuICAmLmJzLXBvcG92ZXItbGVmdCB7XG4gICAgbWFyZ2luLXJpZ2h0OiAkcG9wb3Zlci1hcnJvdy13aWR0aDtcblxuICAgIC5hcnJvdyB7XG4gICAgICByaWdodDogMDtcbiAgICB9XG5cbiAgICAuYXJyb3c6OmJlZm9yZSxcbiAgICAuYXJyb3c6OmFmdGVyIHtcbiAgICAgIG1hcmdpbi10b3A6IC0oJHBvcG92ZXItYXJyb3ctb3V0ZXItd2lkdGggLSAzKTtcbiAgICAgIGJvcmRlci1yaWdodC13aWR0aDogMDtcbiAgICB9XG5cbiAgICAuYXJyb3c6OmJlZm9yZSB7XG4gICAgICByaWdodDogLSRwb3BvdmVyLWFycm93LW91dGVyLXdpZHRoO1xuICAgICAgYm9yZGVyLWxlZnQtY29sb3I6ICRwb3BvdmVyLWFycm93LW91dGVyLWNvbG9yO1xuICAgIH1cblxuICAgIC5hcnJvdzo6YWZ0ZXIge1xuICAgICAgcmlnaHQ6IC0oJHBvcG92ZXItYXJyb3ctb3V0ZXItd2lkdGggLSAxKTtcbiAgICAgIGJvcmRlci1sZWZ0LWNvbG9yOiAkcG9wb3Zlci1hcnJvdy1jb2xvcjtcbiAgICB9XG4gIH1cbiAgJi5icy1wb3BvdmVyLWF1dG8ge1xuICAgICZbeC1wbGFjZW1lbnRePVwidG9wXCJdIHtcbiAgICAgIEBleHRlbmQgLmJzLXBvcG92ZXItdG9wO1xuICAgIH1cbiAgICAmW3gtcGxhY2VtZW50Xj1cInJpZ2h0XCJdIHtcbiAgICAgIEBleHRlbmQgLmJzLXBvcG92ZXItcmlnaHQ7XG4gICAgfVxuICAgICZbeC1wbGFjZW1lbnRePVwiYm90dG9tXCJdIHtcbiAgICAgIEBleHRlbmQgLmJzLXBvcG92ZXItYm90dG9tO1xuICAgIH1cbiAgICAmW3gtcGxhY2VtZW50Xj1cImxlZnRcIl0ge1xuICAgICAgQGV4dGVuZCAuYnMtcG9wb3Zlci1sZWZ0O1xuICAgIH1cbiAgfVxufVxuXG5cbi8vIE9mZnNldCB0aGUgcG9wb3ZlciB0byBhY2NvdW50IGZvciB0aGUgcG9wb3ZlciBhcnJvd1xuLnBvcG92ZXItaGVhZGVyIHtcbiAgcGFkZGluZzogJHBvcG92ZXItaGVhZGVyLXBhZGRpbmcteSAkcG9wb3Zlci1oZWFkZXItcGFkZGluZy14O1xuICBtYXJnaW4tYm90dG9tOiAwOyAvLyBSZXNldCB0aGUgZGVmYXVsdCBmcm9tIFJlYm9vdFxuICBmb250LXNpemU6ICRmb250LXNpemUtYmFzZTtcbiAgY29sb3I6ICRwb3BvdmVyLWhlYWRlci1jb2xvcjtcbiAgYmFja2dyb3VuZC1jb2xvcjogJHBvcG92ZXItaGVhZGVyLWJnO1xuICBib3JkZXItYm90dG9tOiAkcG9wb3Zlci1ib3JkZXItd2lkdGggc29saWQgZGFya2VuKCRwb3BvdmVyLWhlYWRlci1iZywgNSUpO1xuICAkb2Zmc2V0LWJvcmRlci13aWR0aDogY2FsYygjeyRib3JkZXItcmFkaXVzLWxnfSAtICN7JHBvcG92ZXItYm9yZGVyLXdpZHRofSk7XG4gIEBpbmNsdWRlIGJvcmRlci10b3AtcmFkaXVzKCRvZmZzZXQtYm9yZGVyLXdpZHRoKTtcblxuICAmOmVtcHR5IHtcbiAgICBkaXNwbGF5OiBub25lO1xuICB9XG59XG5cbi5wb3BvdmVyLWJvZHkge1xuICBwYWRkaW5nOiAkcG9wb3Zlci1ib2R5LXBhZGRpbmcteSAkcG9wb3Zlci1ib2R5LXBhZGRpbmcteDtcbiAgY29sb3I6ICRwb3BvdmVyLWJvZHktY29sb3I7XG59XG4iLCIvLyBXcmFwcGVyIGZvciB0aGUgc2xpZGUgY29udGFpbmVyIGFuZCBpbmRpY2F0b3JzXG4uY2Fyb3VzZWwge1xuICBwb3NpdGlvbjogcmVsYXRpdmU7XG59XG5cbi5jYXJvdXNlbC1pbm5lciB7XG4gIHBvc2l0aW9uOiByZWxhdGl2ZTtcbiAgd2lkdGg6IDEwMCU7XG4gIG92ZXJmbG93OiBoaWRkZW47XG59XG5cbi5jYXJvdXNlbC1pdGVtIHtcbiAgcG9zaXRpb246IHJlbGF0aXZlO1xuICBkaXNwbGF5OiBub25lO1xuICBhbGlnbi1pdGVtczogY2VudGVyO1xuICB3aWR0aDogMTAwJTtcbiAgQGluY2x1ZGUgdHJhbnNpdGlvbigkY2Fyb3VzZWwtdHJhbnNpdGlvbik7XG4gIGJhY2tmYWNlLXZpc2liaWxpdHk6IGhpZGRlbjtcbiAgcGVyc3BlY3RpdmU6IDEwMDBweDtcbn1cblxuLmNhcm91c2VsLWl0ZW0uYWN0aXZlLFxuLmNhcm91c2VsLWl0ZW0tbmV4dCxcbi5jYXJvdXNlbC1pdGVtLXByZXYge1xuICBkaXNwbGF5OiBibG9jaztcbn1cblxuLmNhcm91c2VsLWl0ZW0tbmV4dCxcbi5jYXJvdXNlbC1pdGVtLXByZXYge1xuICBwb3NpdGlvbjogYWJzb2x1dGU7XG4gIHRvcDogMDtcbn1cblxuLy8gQ1NTMyB0cmFuc2Zvcm1zIHdoZW4gc3VwcG9ydGVkIGJ5IHRoZSBicm93c2VyXG4uY2Fyb3VzZWwtaXRlbS1uZXh0LmNhcm91c2VsLWl0ZW0tbGVmdCxcbi5jYXJvdXNlbC1pdGVtLXByZXYuY2Fyb3VzZWwtaXRlbS1yaWdodCB7XG4gIHRyYW5zZm9ybTogdHJhbnNsYXRlWCgwKTtcblxuICBAc3VwcG9ydHMgKHRyYW5zZm9ybS1zdHlsZTogcHJlc2VydmUtM2QpIHtcbiAgICB0cmFuc2Zvcm06IHRyYW5zbGF0ZTNkKDAsIDAsIDApO1xuICB9XG59XG5cbi5jYXJvdXNlbC1pdGVtLW5leHQsXG4uYWN0aXZlLmNhcm91c2VsLWl0ZW0tcmlnaHQge1xuICB0cmFuc2Zvcm06IHRyYW5zbGF0ZVgoMTAwJSk7XG5cbiAgQHN1cHBvcnRzICh0cmFuc2Zvcm0tc3R5bGU6IHByZXNlcnZlLTNkKSB7XG4gICAgdHJhbnNmb3JtOiB0cmFuc2xhdGUzZCgxMDAlLCAwLCAwKTtcbiAgfVxufVxuXG4uY2Fyb3VzZWwtaXRlbS1wcmV2LFxuLmFjdGl2ZS5jYXJvdXNlbC1pdGVtLWxlZnQge1xuICB0cmFuc2Zvcm06IHRyYW5zbGF0ZVgoLTEwMCUpO1xuXG4gIEBzdXBwb3J0cyAodHJhbnNmb3JtLXN0eWxlOiBwcmVzZXJ2ZS0zZCkge1xuICAgIHRyYW5zZm9ybTogdHJhbnNsYXRlM2QoLTEwMCUsIDAsIDApO1xuICB9XG59XG5cblxuLy9cbi8vIExlZnQvcmlnaHQgY29udHJvbHMgZm9yIG5hdlxuLy9cblxuLmNhcm91c2VsLWNvbnRyb2wtcHJldixcbi5jYXJvdXNlbC1jb250cm9sLW5leHQge1xuICBwb3NpdGlvbjogYWJzb2x1dGU7XG4gIHRvcDogMDtcbiAgYm90dG9tOiAwO1xuICAvLyBVc2UgZmxleCBmb3IgYWxpZ25tZW50ICgxLTMpXG4gIGRpc3BsYXk6IGZsZXg7IC8vIDEuIGFsbG93IGZsZXggc3R5bGVzXG4gIGFsaWduLWl0ZW1zOiBjZW50ZXI7IC8vIDIuIHZlcnRpY2FsbHkgY2VudGVyIGNvbnRlbnRzXG4gIGp1c3RpZnktY29udGVudDogY2VudGVyOyAvLyAzLiBob3Jpem9udGFsbHkgY2VudGVyIGNvbnRlbnRzXG4gIHdpZHRoOiAkY2Fyb3VzZWwtY29udHJvbC13aWR0aDtcbiAgY29sb3I6ICRjYXJvdXNlbC1jb250cm9sLWNvbG9yO1xuICB0ZXh0LWFsaWduOiBjZW50ZXI7XG4gIG9wYWNpdHk6ICRjYXJvdXNlbC1jb250cm9sLW9wYWNpdHk7XG4gIC8vIFdlIGNhbid0IGhhdmUgYSB0cmFuc2l0aW9uIGhlcmUgYmVjYXVzZSBXZWJLaXQgY2FuY2VscyB0aGUgY2Fyb3VzZWxcbiAgLy8gYW5pbWF0aW9uIGlmIHlvdSB0cmlwIHRoaXMgd2hpbGUgaW4gdGhlIG1pZGRsZSBvZiBhbm90aGVyIGFuaW1hdGlvbi5cblxuICAvLyBIb3Zlci9mb2N1cyBzdGF0ZVxuICBAaW5jbHVkZSBob3Zlci1mb2N1cyB7XG4gICAgY29sb3I6ICRjYXJvdXNlbC1jb250cm9sLWNvbG9yO1xuICAgIHRleHQtZGVjb3JhdGlvbjogbm9uZTtcbiAgICBvdXRsaW5lOiAwO1xuICAgIG9wYWNpdHk6IC45O1xuICB9XG59XG4uY2Fyb3VzZWwtY29udHJvbC1wcmV2IHtcbiAgbGVmdDogMDtcbn1cbi5jYXJvdXNlbC1jb250cm9sLW5leHQge1xuICByaWdodDogMDtcbn1cblxuLy8gSWNvbnMgZm9yIHdpdGhpblxuLmNhcm91c2VsLWNvbnRyb2wtcHJldi1pY29uLFxuLmNhcm91c2VsLWNvbnRyb2wtbmV4dC1pY29uIHtcbiAgZGlzcGxheTogaW5saW5lLWJsb2NrO1xuICB3aWR0aDogJGNhcm91c2VsLWNvbnRyb2wtaWNvbi13aWR0aDtcbiAgaGVpZ2h0OiAkY2Fyb3VzZWwtY29udHJvbC1pY29uLXdpZHRoO1xuICBiYWNrZ3JvdW5kOiB0cmFuc3BhcmVudCBuby1yZXBlYXQgY2VudGVyIGNlbnRlcjtcbiAgYmFja2dyb3VuZC1zaXplOiAxMDAlIDEwMCU7XG59XG4uY2Fyb3VzZWwtY29udHJvbC1wcmV2LWljb24ge1xuICBiYWNrZ3JvdW5kLWltYWdlOiAkY2Fyb3VzZWwtY29udHJvbC1wcmV2LWljb24tYmc7XG59XG4uY2Fyb3VzZWwtY29udHJvbC1uZXh0LWljb24ge1xuICBiYWNrZ3JvdW5kLWltYWdlOiAkY2Fyb3VzZWwtY29udHJvbC1uZXh0LWljb24tYmc7XG59XG5cblxuLy8gT3B0aW9uYWwgaW5kaWNhdG9yIHBpcHNcbi8vXG4vLyBBZGQgYW4gb3JkZXJlZCBsaXN0IHdpdGggdGhlIGZvbGxvd2luZyBjbGFzcyBhbmQgYWRkIGEgbGlzdCBpdGVtIGZvciBlYWNoXG4vLyBzbGlkZSB5b3VyIGNhcm91c2VsIGhvbGRzLlxuXG4uY2Fyb3VzZWwtaW5kaWNhdG9ycyB7XG4gIHBvc2l0aW9uOiBhYnNvbHV0ZTtcbiAgcmlnaHQ6IDA7XG4gIGJvdHRvbTogMTBweDtcbiAgbGVmdDogMDtcbiAgei1pbmRleDogMTU7XG4gIGRpc3BsYXk6IGZsZXg7XG4gIGp1c3RpZnktY29udGVudDogY2VudGVyO1xuICBwYWRkaW5nLWxlZnQ6IDA7IC8vIG92ZXJyaWRlIDxvbD4gZGVmYXVsdFxuICAvLyBVc2UgdGhlIC5jYXJvdXNlbC1jb250cm9sJ3Mgd2lkdGggYXMgbWFyZ2luIHNvIHdlIGRvbid0IG92ZXJsYXkgdGhvc2VcbiAgbWFyZ2luLXJpZ2h0OiAkY2Fyb3VzZWwtY29udHJvbC13aWR0aDtcbiAgbWFyZ2luLWxlZnQ6ICRjYXJvdXNlbC1jb250cm9sLXdpZHRoO1xuICBsaXN0LXN0eWxlOiBub25lO1xuXG4gIGxpIHtcbiAgICBwb3NpdGlvbjogcmVsYXRpdmU7XG4gICAgZmxleDogMCAxIGF1dG87XG4gICAgd2lkdGg6ICRjYXJvdXNlbC1pbmRpY2F0b3Itd2lkdGg7XG4gICAgaGVpZ2h0OiAkY2Fyb3VzZWwtaW5kaWNhdG9yLWhlaWdodDtcbiAgICBtYXJnaW4tcmlnaHQ6ICRjYXJvdXNlbC1pbmRpY2F0b3Itc3BhY2VyO1xuICAgIG1hcmdpbi1sZWZ0OiAkY2Fyb3VzZWwtaW5kaWNhdG9yLXNwYWNlcjtcbiAgICB0ZXh0LWluZGVudDogLTk5OXB4O1xuICAgIGJhY2tncm91bmQtY29sb3I6IHJnYmEoJGNhcm91c2VsLWluZGljYXRvci1hY3RpdmUtYmcsIC41KTtcblxuICAgIC8vIFVzZSBwc2V1ZG8gY2xhc3NlcyB0byBpbmNyZWFzZSB0aGUgaGl0IGFyZWEgYnkgMTBweCBvbiB0b3AgYW5kIGJvdHRvbS5cbiAgICAmOjpiZWZvcmUge1xuICAgICAgcG9zaXRpb246IGFic29sdXRlO1xuICAgICAgdG9wOiAtMTBweDtcbiAgICAgIGxlZnQ6IDA7XG4gICAgICBkaXNwbGF5OiBpbmxpbmUtYmxvY2s7XG4gICAgICB3aWR0aDogMTAwJTtcbiAgICAgIGhlaWdodDogMTBweDtcbiAgICAgIGNvbnRlbnQ6IFwiXCI7XG4gICAgfVxuICAgICY6OmFmdGVyIHtcbiAgICAgIHBvc2l0aW9uOiBhYnNvbHV0ZTtcbiAgICAgIGJvdHRvbTogLTEwcHg7XG4gICAgICBsZWZ0OiAwO1xuICAgICAgZGlzcGxheTogaW5saW5lLWJsb2NrO1xuICAgICAgd2lkdGg6IDEwMCU7XG4gICAgICBoZWlnaHQ6IDEwcHg7XG4gICAgICBjb250ZW50OiBcIlwiO1xuICAgIH1cbiAgfVxuXG4gIC5hY3RpdmUge1xuICAgIGJhY2tncm91bmQtY29sb3I6ICRjYXJvdXNlbC1pbmRpY2F0b3ItYWN0aXZlLWJnO1xuICB9XG59XG5cblxuLy8gT3B0aW9uYWwgY2FwdGlvbnNcbi8vXG4vL1xuXG4uY2Fyb3VzZWwtY2FwdGlvbiB7XG4gIHBvc2l0aW9uOiBhYnNvbHV0ZTtcbiAgcmlnaHQ6ICgoMTAwJSAtICRjYXJvdXNlbC1jYXB0aW9uLXdpZHRoKSAvIDIpO1xuICBib3R0b206IDIwcHg7XG4gIGxlZnQ6ICgoMTAwJSAtICRjYXJvdXNlbC1jYXB0aW9uLXdpZHRoKSAvIDIpO1xuICB6LWluZGV4OiAxMDtcbiAgcGFkZGluZy10b3A6IDIwcHg7XG4gIHBhZGRpbmctYm90dG9tOiAyMHB4O1xuICBjb2xvcjogJGNhcm91c2VsLWNhcHRpb24tY29sb3I7XG4gIHRleHQtYWxpZ246IGNlbnRlcjtcbn1cbiIsIi5hbGlnbi1iYXNlbGluZSAgICB7IHZlcnRpY2FsLWFsaWduOiBiYXNlbGluZSAhaW1wb3J0YW50OyB9IC8vIEJyb3dzZXIgZGVmYXVsdFxuLmFsaWduLXRvcCAgICAgICAgIHsgdmVydGljYWwtYWxpZ246IHRvcCAhaW1wb3J0YW50OyB9XG4uYWxpZ24tbWlkZGxlICAgICAgeyB2ZXJ0aWNhbC1hbGlnbjogbWlkZGxlICFpbXBvcnRhbnQ7IH1cbi5hbGlnbi1ib3R0b20gICAgICB7IHZlcnRpY2FsLWFsaWduOiBib3R0b20gIWltcG9ydGFudDsgfVxuLmFsaWduLXRleHQtYm90dG9tIHsgdmVydGljYWwtYWxpZ246IHRleHQtYm90dG9tICFpbXBvcnRhbnQ7IH1cbi5hbGlnbi10ZXh0LXRvcCAgICB7IHZlcnRpY2FsLWFsaWduOiB0ZXh0LXRvcCAhaW1wb3J0YW50OyB9XG4iLCIvLyBDb250ZXh0dWFsIGJhY2tncm91bmRzXG5cbkBtaXhpbiBiZy12YXJpYW50KCRwYXJlbnQsICRjb2xvcikge1xuICAjeyRwYXJlbnR9IHtcbiAgICBiYWNrZ3JvdW5kLWNvbG9yOiAkY29sb3IgIWltcG9ydGFudDtcbiAgfVxuICBhI3skcGFyZW50fSB7XG4gICAgQGluY2x1ZGUgaG92ZXItZm9jdXMge1xuICAgICAgYmFja2dyb3VuZC1jb2xvcjogZGFya2VuKCRjb2xvciwgMTAlKSAhaW1wb3J0YW50O1xuICAgIH1cbiAgfVxufVxuIiwiQGVhY2ggJGNvbG9yLCAkdmFsdWUgaW4gJHRoZW1lLWNvbG9ycyB7XG4gIEBpbmNsdWRlIGJnLXZhcmlhbnQoJy5iZy0jeyRjb2xvcn0nLCAkdmFsdWUpO1xufVxuXG4uYmctd2hpdGUgeyBiYWNrZ3JvdW5kLWNvbG9yOiAkd2hpdGUgIWltcG9ydGFudDsgfVxuLmJnLXRyYW5zcGFyZW50IHsgYmFja2dyb3VuZC1jb2xvcjogdHJhbnNwYXJlbnQgIWltcG9ydGFudDsgfVxuIiwiLy9cbi8vIEJvcmRlclxuLy9cblxuLmJvcmRlciAgICAgICAgICB7IGJvcmRlcjogJGJvcmRlci13aWR0aCBzb2xpZCAkYm9yZGVyLWNvbG9yICFpbXBvcnRhbnQ7IH1cbi5ib3JkZXItMCAgICAgICAgeyBib3JkZXI6IDAgIWltcG9ydGFudDsgfVxuLmJvcmRlci10b3AtMCAgICB7IGJvcmRlci10b3A6IDAgIWltcG9ydGFudDsgfVxuLmJvcmRlci1yaWdodC0wICB7IGJvcmRlci1yaWdodDogMCAhaW1wb3J0YW50OyB9XG4uYm9yZGVyLWJvdHRvbS0wIHsgYm9yZGVyLWJvdHRvbTogMCAhaW1wb3J0YW50OyB9XG4uYm9yZGVyLWxlZnQtMCAgIHsgYm9yZGVyLWxlZnQ6IDAgIWltcG9ydGFudDsgfVxuXG5AZWFjaCAkY29sb3IsICR2YWx1ZSBpbiAkdGhlbWUtY29sb3JzIHtcbiAgLmJvcmRlci0jeyRjb2xvcn0ge1xuICAgIGJvcmRlci1jb2xvcjogJHZhbHVlICFpbXBvcnRhbnQ7XG4gIH1cbn1cblxuLmJvcmRlci13aGl0ZSB7XG4gIGJvcmRlci1jb2xvcjogJHdoaXRlICFpbXBvcnRhbnQ7XG59XG5cbi8vXG4vLyBCb3JkZXItcmFkaXVzXG4vL1xuXG4ucm91bmRlZCB7XG4gIGJvcmRlci1yYWRpdXM6ICRib3JkZXItcmFkaXVzICFpbXBvcnRhbnQ7XG59XG4ucm91bmRlZC10b3Age1xuICBib3JkZXItdG9wLWxlZnQtcmFkaXVzOiAkYm9yZGVyLXJhZGl1cyAhaW1wb3J0YW50O1xuICBib3JkZXItdG9wLXJpZ2h0LXJhZGl1czogJGJvcmRlci1yYWRpdXMgIWltcG9ydGFudDtcbn1cbi5yb3VuZGVkLXJpZ2h0IHtcbiAgYm9yZGVyLXRvcC1yaWdodC1yYWRpdXM6ICRib3JkZXItcmFkaXVzICFpbXBvcnRhbnQ7XG4gIGJvcmRlci1ib3R0b20tcmlnaHQtcmFkaXVzOiAkYm9yZGVyLXJhZGl1cyAhaW1wb3J0YW50O1xufVxuLnJvdW5kZWQtYm90dG9tIHtcbiAgYm9yZGVyLWJvdHRvbS1yaWdodC1yYWRpdXM6ICRib3JkZXItcmFkaXVzICFpbXBvcnRhbnQ7XG4gIGJvcmRlci1ib3R0b20tbGVmdC1yYWRpdXM6ICRib3JkZXItcmFkaXVzICFpbXBvcnRhbnQ7XG59XG4ucm91bmRlZC1sZWZ0IHtcbiAgYm9yZGVyLXRvcC1sZWZ0LXJhZGl1czogJGJvcmRlci1yYWRpdXMgIWltcG9ydGFudDtcbiAgYm9yZGVyLWJvdHRvbS1sZWZ0LXJhZGl1czogJGJvcmRlci1yYWRpdXMgIWltcG9ydGFudDtcbn1cblxuLnJvdW5kZWQtY2lyY2xlIHtcbiAgYm9yZGVyLXJhZGl1czogNTAlO1xufVxuXG4ucm91bmRlZC0wIHtcbiAgYm9yZGVyLXJhZGl1czogMDtcbn1cbiIsIi5jbGVhcmZpeCB7XG4gIEBpbmNsdWRlIGNsZWFyZml4KCk7XG59XG4iLCIvL1xuLy8gVXRpbGl0aWVzIGZvciBjb21tb24gYGRpc3BsYXlgIHZhbHVlc1xuLy9cblxuQGVhY2ggJGJyZWFrcG9pbnQgaW4gbWFwLWtleXMoJGdyaWQtYnJlYWtwb2ludHMpIHtcbiAgQGluY2x1ZGUgbWVkaWEtYnJlYWtwb2ludC11cCgkYnJlYWtwb2ludCkge1xuICAgICRpbmZpeDogYnJlYWtwb2ludC1pbmZpeCgkYnJlYWtwb2ludCwgJGdyaWQtYnJlYWtwb2ludHMpO1xuXG4gICAgLmQjeyRpbmZpeH0tbm9uZSAgICAgICAgIHsgZGlzcGxheTogbm9uZSAhaW1wb3J0YW50OyB9XG4gICAgLmQjeyRpbmZpeH0taW5saW5lICAgICAgIHsgZGlzcGxheTogaW5saW5lICFpbXBvcnRhbnQ7IH1cbiAgICAuZCN7JGluZml4fS1pbmxpbmUtYmxvY2sgeyBkaXNwbGF5OiBpbmxpbmUtYmxvY2sgIWltcG9ydGFudDsgfVxuICAgIC5kI3skaW5maXh9LWJsb2NrICAgICAgICB7IGRpc3BsYXk6IGJsb2NrICFpbXBvcnRhbnQ7IH1cbiAgICAuZCN7JGluZml4fS10YWJsZSAgICAgICAgeyBkaXNwbGF5OiB0YWJsZSAhaW1wb3J0YW50OyB9XG4gICAgLmQjeyRpbmZpeH0tdGFibGUtY2VsbCAgIHsgZGlzcGxheTogdGFibGUtY2VsbCAhaW1wb3J0YW50OyB9XG4gICAgLmQjeyRpbmZpeH0tZmxleCAgICAgICAgIHsgZGlzcGxheTogZmxleCAhaW1wb3J0YW50OyB9XG4gICAgLmQjeyRpbmZpeH0taW5saW5lLWZsZXggIHsgZGlzcGxheTogaW5saW5lLWZsZXggIWltcG9ydGFudDsgfVxuICB9XG59XG5cblxuLy9cbi8vIFV0aWxpdGllcyBmb3IgdG9nZ2xpbmcgYGRpc3BsYXlgIGluIHByaW50XG4vL1xuXG4uZC1wcmludC1ibG9jayB7XG4gIGRpc3BsYXk6IG5vbmUgIWltcG9ydGFudDtcblxuICBAbWVkaWEgcHJpbnQge1xuICAgIGRpc3BsYXk6IGJsb2NrICFpbXBvcnRhbnQ7XG4gIH1cbn1cblxuLmQtcHJpbnQtaW5saW5lIHtcbiAgZGlzcGxheTogbm9uZSAhaW1wb3J0YW50O1xuXG4gIEBtZWRpYSBwcmludCB7XG4gICAgZGlzcGxheTogaW5saW5lICFpbXBvcnRhbnQ7XG4gIH1cbn1cblxuLmQtcHJpbnQtaW5saW5lLWJsb2NrIHtcbiAgZGlzcGxheTogbm9uZSAhaW1wb3J0YW50O1xuXG4gIEBtZWRpYSBwcmludCB7XG4gICAgZGlzcGxheTogaW5saW5lLWJsb2NrICFpbXBvcnRhbnQ7XG4gIH1cbn1cblxuLmQtcHJpbnQtbm9uZSB7XG4gIEBtZWRpYSBwcmludCB7XG4gICAgZGlzcGxheTogbm9uZSAhaW1wb3J0YW50O1xuICB9XG59XG4iLCIvLyBDcmVkaXQ6IE5pY29sYXMgR2FsbGFnaGVyIGFuZCBTVUlUIENTUy5cblxuLmVtYmVkLXJlc3BvbnNpdmUge1xuICBwb3NpdGlvbjogcmVsYXRpdmU7XG4gIGRpc3BsYXk6IGJsb2NrO1xuICB3aWR0aDogMTAwJTtcbiAgcGFkZGluZzogMDtcbiAgb3ZlcmZsb3c6IGhpZGRlbjtcblxuICAmOjpiZWZvcmUge1xuICAgIGRpc3BsYXk6IGJsb2NrO1xuICAgIGNvbnRlbnQ6IFwiXCI7XG4gIH1cblxuICAuZW1iZWQtcmVzcG9uc2l2ZS1pdGVtLFxuICBpZnJhbWUsXG4gIGVtYmVkLFxuICBvYmplY3QsXG4gIHZpZGVvIHtcbiAgICBwb3NpdGlvbjogYWJzb2x1dGU7XG4gICAgdG9wOiAwO1xuICAgIGJvdHRvbTogMDtcbiAgICBsZWZ0OiAwO1xuICAgIHdpZHRoOiAxMDAlO1xuICAgIGhlaWdodDogMTAwJTtcbiAgICBib3JkZXI6IDA7XG4gIH1cbn1cblxuLmVtYmVkLXJlc3BvbnNpdmUtMjFieTkge1xuICAmOjpiZWZvcmUge1xuICAgIHBhZGRpbmctdG9wOiBwZXJjZW50YWdlKDkgLyAyMSk7XG4gIH1cbn1cblxuLmVtYmVkLXJlc3BvbnNpdmUtMTZieTkge1xuICAmOjpiZWZvcmUge1xuICAgIHBhZGRpbmctdG9wOiBwZXJjZW50YWdlKDkgLyAxNik7XG4gIH1cbn1cblxuLmVtYmVkLXJlc3BvbnNpdmUtNGJ5MyB7XG4gICY6OmJlZm9yZSB7XG4gICAgcGFkZGluZy10b3A6IHBlcmNlbnRhZ2UoMyAvIDQpO1xuICB9XG59XG5cbi5lbWJlZC1yZXNwb25zaXZlLTFieTEge1xuICAmOjpiZWZvcmUge1xuICAgIHBhZGRpbmctdG9wOiBwZXJjZW50YWdlKDEgLyAxKTtcbiAgfVxufVxuIiwiLy8gRmxleCB2YXJpYXRpb25cbi8vXG4vLyBDdXN0b20gc3R5bGVzIGZvciBhZGRpdGlvbmFsIGZsZXggYWxpZ25tZW50IG9wdGlvbnMuXG5cbkBlYWNoICRicmVha3BvaW50IGluIG1hcC1rZXlzKCRncmlkLWJyZWFrcG9pbnRzKSB7XG4gIEBpbmNsdWRlIG1lZGlhLWJyZWFrcG9pbnQtdXAoJGJyZWFrcG9pbnQpIHtcbiAgICAkaW5maXg6IGJyZWFrcG9pbnQtaW5maXgoJGJyZWFrcG9pbnQsICRncmlkLWJyZWFrcG9pbnRzKTtcblxuICAgIC5mbGV4I3skaW5maXh9LXJvdyAgICAgICAgICAgIHsgZmxleC1kaXJlY3Rpb246IHJvdyAhaW1wb3J0YW50OyB9XG4gICAgLmZsZXgjeyRpbmZpeH0tY29sdW1uICAgICAgICAgeyBmbGV4LWRpcmVjdGlvbjogY29sdW1uICFpbXBvcnRhbnQ7IH1cbiAgICAuZmxleCN7JGluZml4fS1yb3ctcmV2ZXJzZSAgICB7IGZsZXgtZGlyZWN0aW9uOiByb3ctcmV2ZXJzZSAhaW1wb3J0YW50OyB9XG4gICAgLmZsZXgjeyRpbmZpeH0tY29sdW1uLXJldmVyc2UgeyBmbGV4LWRpcmVjdGlvbjogY29sdW1uLXJldmVyc2UgIWltcG9ydGFudDsgfVxuXG4gICAgLmZsZXgjeyRpbmZpeH0td3JhcCAgICAgICAgIHsgZmxleC13cmFwOiB3cmFwICFpbXBvcnRhbnQ7IH1cbiAgICAuZmxleCN7JGluZml4fS1ub3dyYXAgICAgICAgeyBmbGV4LXdyYXA6IG5vd3JhcCAhaW1wb3J0YW50OyB9XG4gICAgLmZsZXgjeyRpbmZpeH0td3JhcC1yZXZlcnNlIHsgZmxleC13cmFwOiB3cmFwLXJldmVyc2UgIWltcG9ydGFudDsgfVxuXG4gICAgLmp1c3RpZnktY29udGVudCN7JGluZml4fS1zdGFydCAgIHsganVzdGlmeS1jb250ZW50OiBmbGV4LXN0YXJ0ICFpbXBvcnRhbnQ7IH1cbiAgICAuanVzdGlmeS1jb250ZW50I3skaW5maXh9LWVuZCAgICAgeyBqdXN0aWZ5LWNvbnRlbnQ6IGZsZXgtZW5kICFpbXBvcnRhbnQ7IH1cbiAgICAuanVzdGlmeS1jb250ZW50I3skaW5maXh9LWNlbnRlciAgeyBqdXN0aWZ5LWNvbnRlbnQ6IGNlbnRlciAhaW1wb3J0YW50OyB9XG4gICAgLmp1c3RpZnktY29udGVudCN7JGluZml4fS1iZXR3ZWVuIHsganVzdGlmeS1jb250ZW50OiBzcGFjZS1iZXR3ZWVuICFpbXBvcnRhbnQ7IH1cbiAgICAuanVzdGlmeS1jb250ZW50I3skaW5maXh9LWFyb3VuZCAgeyBqdXN0aWZ5LWNvbnRlbnQ6IHNwYWNlLWFyb3VuZCAhaW1wb3J0YW50OyB9XG5cbiAgICAuYWxpZ24taXRlbXMjeyRpbmZpeH0tc3RhcnQgICAgeyBhbGlnbi1pdGVtczogZmxleC1zdGFydCAhaW1wb3J0YW50OyB9XG4gICAgLmFsaWduLWl0ZW1zI3skaW5maXh9LWVuZCAgICAgIHsgYWxpZ24taXRlbXM6IGZsZXgtZW5kICFpbXBvcnRhbnQ7IH1cbiAgICAuYWxpZ24taXRlbXMjeyRpbmZpeH0tY2VudGVyICAgeyBhbGlnbi1pdGVtczogY2VudGVyICFpbXBvcnRhbnQ7IH1cbiAgICAuYWxpZ24taXRlbXMjeyRpbmZpeH0tYmFzZWxpbmUgeyBhbGlnbi1pdGVtczogYmFzZWxpbmUgIWltcG9ydGFudDsgfVxuICAgIC5hbGlnbi1pdGVtcyN7JGluZml4fS1zdHJldGNoICB7IGFsaWduLWl0ZW1zOiBzdHJldGNoICFpbXBvcnRhbnQ7IH1cblxuICAgIC5hbGlnbi1jb250ZW50I3skaW5maXh9LXN0YXJ0ICAgeyBhbGlnbi1jb250ZW50OiBmbGV4LXN0YXJ0ICFpbXBvcnRhbnQ7IH1cbiAgICAuYWxpZ24tY29udGVudCN7JGluZml4fS1lbmQgICAgIHsgYWxpZ24tY29udGVudDogZmxleC1lbmQgIWltcG9ydGFudDsgfVxuICAgIC5hbGlnbi1jb250ZW50I3skaW5maXh9LWNlbnRlciAgeyBhbGlnbi1jb250ZW50OiBjZW50ZXIgIWltcG9ydGFudDsgfVxuICAgIC5hbGlnbi1jb250ZW50I3skaW5maXh9LWJldHdlZW4geyBhbGlnbi1jb250ZW50OiBzcGFjZS1iZXR3ZWVuICFpbXBvcnRhbnQ7IH1cbiAgICAuYWxpZ24tY29udGVudCN7JGluZml4fS1hcm91bmQgIHsgYWxpZ24tY29udGVudDogc3BhY2UtYXJvdW5kICFpbXBvcnRhbnQ7IH1cbiAgICAuYWxpZ24tY29udGVudCN7JGluZml4fS1zdHJldGNoIHsgYWxpZ24tY29udGVudDogc3RyZXRjaCAhaW1wb3J0YW50OyB9XG5cbiAgICAuYWxpZ24tc2VsZiN7JGluZml4fS1hdXRvICAgICB7IGFsaWduLXNlbGY6IGF1dG8gIWltcG9ydGFudDsgfVxuICAgIC5hbGlnbi1zZWxmI3skaW5maXh9LXN0YXJ0ICAgIHsgYWxpZ24tc2VsZjogZmxleC1zdGFydCAhaW1wb3J0YW50OyB9XG4gICAgLmFsaWduLXNlbGYjeyRpbmZpeH0tZW5kICAgICAgeyBhbGlnbi1zZWxmOiBmbGV4LWVuZCAhaW1wb3J0YW50OyB9XG4gICAgLmFsaWduLXNlbGYjeyRpbmZpeH0tY2VudGVyICAgeyBhbGlnbi1zZWxmOiBjZW50ZXIgIWltcG9ydGFudDsgfVxuICAgIC5hbGlnbi1zZWxmI3skaW5maXh9LWJhc2VsaW5lIHsgYWxpZ24tc2VsZjogYmFzZWxpbmUgIWltcG9ydGFudDsgfVxuICAgIC5hbGlnbi1zZWxmI3skaW5maXh9LXN0cmV0Y2ggIHsgYWxpZ24tc2VsZjogc3RyZXRjaCAhaW1wb3J0YW50OyB9XG4gIH1cbn1cbiIsIkBlYWNoICRicmVha3BvaW50IGluIG1hcC1rZXlzKCRncmlkLWJyZWFrcG9pbnRzKSB7XG4gIEBpbmNsdWRlIG1lZGlhLWJyZWFrcG9pbnQtdXAoJGJyZWFrcG9pbnQpIHtcbiAgICAkaW5maXg6IGJyZWFrcG9pbnQtaW5maXgoJGJyZWFrcG9pbnQsICRncmlkLWJyZWFrcG9pbnRzKTtcblxuICAgIC5mbG9hdCN7JGluZml4fS1sZWZ0ICB7IEBpbmNsdWRlIGZsb2F0LWxlZnQ7IH1cbiAgICAuZmxvYXQjeyRpbmZpeH0tcmlnaHQgeyBAaW5jbHVkZSBmbG9hdC1yaWdodDsgfVxuICAgIC5mbG9hdCN7JGluZml4fS1ub25lICB7IEBpbmNsdWRlIGZsb2F0LW5vbmU7IH1cbiAgfVxufVxuIiwiQG1peGluIGZsb2F0LWxlZnQge1xuICBmbG9hdDogbGVmdCAhaW1wb3J0YW50O1xufVxuQG1peGluIGZsb2F0LXJpZ2h0IHtcbiAgZmxvYXQ6IHJpZ2h0ICFpbXBvcnRhbnQ7XG59XG5AbWl4aW4gZmxvYXQtbm9uZSB7XG4gIGZsb2F0OiBub25lICFpbXBvcnRhbnQ7XG59XG4iLCIvLyBDb21tb24gdmFsdWVzXG5cbi8vIFNhc3MgbGlzdCBub3QgaW4gdmFyaWFibGVzIHNpbmNlIGl0J3Mgbm90IGludGVuZGVkIGZvciBjdXN0b21pemF0aW9uLlxuJHBvc2l0aW9uczogc3RhdGljLCByZWxhdGl2ZSwgYWJzb2x1dGUsIGZpeGVkLCBzdGlja3k7XG5cbkBlYWNoICRwb3NpdGlvbiBpbiAkcG9zaXRpb25zIHtcbiAgLnBvc2l0aW9uLSN7JHBvc2l0aW9ufSB7IHBvc2l0aW9uOiAkcG9zaXRpb24gIWltcG9ydGFudDsgfVxufVxuXG4vLyBTaG9ydGhhbmRcblxuLmZpeGVkLXRvcCB7XG4gIHBvc2l0aW9uOiBmaXhlZDtcbiAgdG9wOiAwO1xuICByaWdodDogMDtcbiAgbGVmdDogMDtcbiAgei1pbmRleDogJHppbmRleC1maXhlZDtcbn1cblxuLmZpeGVkLWJvdHRvbSB7XG4gIHBvc2l0aW9uOiBmaXhlZDtcbiAgcmlnaHQ6IDA7XG4gIGJvdHRvbTogMDtcbiAgbGVmdDogMDtcbiAgei1pbmRleDogJHppbmRleC1maXhlZDtcbn1cblxuLnN0aWNreS10b3Age1xuICBAc3VwcG9ydHMgKHBvc2l0aW9uOiBzdGlja3kpIHtcbiAgICBwb3NpdGlvbjogc3RpY2t5O1xuICAgIHRvcDogMDtcbiAgICB6LWluZGV4OiAkemluZGV4LXN0aWNreTtcbiAgfVxufVxuIiwiLy9cbi8vIFNjcmVlbnJlYWRlcnNcbi8vXG5cbi5zci1vbmx5IHtcbiAgQGluY2x1ZGUgc3Itb25seSgpO1xufVxuXG4uc3Itb25seS1mb2N1c2FibGUge1xuICBAaW5jbHVkZSBzci1vbmx5LWZvY3VzYWJsZSgpO1xufVxuIiwiLy8gT25seSBkaXNwbGF5IGNvbnRlbnQgdG8gc2NyZWVuIHJlYWRlcnNcbi8vXG4vLyBTZWU6IGh0dHA6Ly9hMTF5cHJvamVjdC5jb20vcG9zdHMvaG93LXRvLWhpZGUtY29udGVudFxuLy8gU2VlOiBodHRwOi8vaHVnb2dpcmF1ZGVsLmNvbS8yMDE2LzEwLzEzL2Nzcy1oaWRlLWFuZC1zZWVrL1xuXG5AbWl4aW4gc3Itb25seSB7XG4gIHBvc2l0aW9uOiBhYnNvbHV0ZTtcbiAgd2lkdGg6IDFweDtcbiAgaGVpZ2h0OiAxcHg7XG4gIHBhZGRpbmc6IDA7XG4gIG92ZXJmbG93OiBoaWRkZW47XG4gIGNsaXA6IHJlY3QoMCwwLDAsMCk7XG4gIHdoaXRlLXNwYWNlOiBub3dyYXA7XG4gIGNsaXAtcGF0aDogaW5zZXQoNTAlKTtcbiAgYm9yZGVyOiAwO1xufVxuXG4vLyBVc2UgaW4gY29uanVuY3Rpb24gd2l0aCAuc3Itb25seSB0byBvbmx5IGRpc3BsYXkgY29udGVudCB3aGVuIGl0J3MgZm9jdXNlZC5cbi8vXG4vLyBVc2VmdWwgZm9yIFwiU2tpcCB0byBtYWluIGNvbnRlbnRcIiBsaW5rczsgc2VlIGh0dHBzOi8vd3d3LnczLm9yZy9UUi8yMDEzL05PVEUtV0NBRzIwLVRFQ0hTLTIwMTMwOTA1L0cxXG4vL1xuLy8gQ3JlZGl0OiBIVE1MNSBCb2lsZXJwbGF0ZVxuXG5AbWl4aW4gc3Itb25seS1mb2N1c2FibGUge1xuICAmOmFjdGl2ZSxcbiAgJjpmb2N1cyB7XG4gICAgcG9zaXRpb246IHN0YXRpYztcbiAgICB3aWR0aDogYXV0bztcbiAgICBoZWlnaHQ6IGF1dG87XG4gICAgb3ZlcmZsb3c6IHZpc2libGU7XG4gICAgY2xpcDogYXV0bztcbiAgICB3aGl0ZS1zcGFjZTogbm9ybWFsO1xuICAgIGNsaXAtcGF0aDogbm9uZTtcbiAgfVxufVxuIiwiLy8gV2lkdGggYW5kIGhlaWdodFxuXG5AZWFjaCAkcHJvcCwgJGFiYnJldiBpbiAod2lkdGg6IHcsIGhlaWdodDogaCkge1xuICBAZWFjaCAkc2l6ZSwgJGxlbmd0aCBpbiAkc2l6ZXMge1xuICAgIC4jeyRhYmJyZXZ9LSN7JHNpemV9IHsgI3skcHJvcH06ICRsZW5ndGggIWltcG9ydGFudDsgfVxuICB9XG59XG5cbi5tdy0xMDAgeyBtYXgtd2lkdGg6IDEwMCUgIWltcG9ydGFudDsgfVxuLm1oLTEwMCB7IG1heC1oZWlnaHQ6IDEwMCUgIWltcG9ydGFudDsgfVxuIiwiLy8gTWFyZ2luIGFuZCBQYWRkaW5nXG5cbkBlYWNoICRicmVha3BvaW50IGluIG1hcC1rZXlzKCRncmlkLWJyZWFrcG9pbnRzKSB7XG4gIEBpbmNsdWRlIG1lZGlhLWJyZWFrcG9pbnQtdXAoJGJyZWFrcG9pbnQpIHtcbiAgICAkaW5maXg6IGJyZWFrcG9pbnQtaW5maXgoJGJyZWFrcG9pbnQsICRncmlkLWJyZWFrcG9pbnRzKTtcblxuICAgIEBlYWNoICRwcm9wLCAkYWJicmV2IGluIChtYXJnaW46IG0sIHBhZGRpbmc6IHApIHtcbiAgICAgIEBlYWNoICRzaXplLCAkbGVuZ3RoIGluICRzcGFjZXJzIHtcblxuICAgICAgICAuI3skYWJicmV2fSN7JGluZml4fS0jeyRzaXplfSAgeyAjeyRwcm9wfTogICAgICAgICRsZW5ndGggIWltcG9ydGFudDsgfVxuICAgICAgICAuI3skYWJicmV2fXQjeyRpbmZpeH0tI3skc2l6ZX0sXG4gICAgICAgIC4jeyRhYmJyZXZ9eSN7JGluZml4fS0jeyRzaXplfSB7XG4gICAgICAgICAgI3skcHJvcH0tdG9wOiAkbGVuZ3RoICFpbXBvcnRhbnQ7XG4gICAgICAgIH1cbiAgICAgICAgLiN7JGFiYnJldn1yI3skaW5maXh9LSN7JHNpemV9LFxuICAgICAgICAuI3skYWJicmV2fXgjeyRpbmZpeH0tI3skc2l6ZX0ge1xuICAgICAgICAgICN7JHByb3B9LXJpZ2h0OiAkbGVuZ3RoICFpbXBvcnRhbnQ7XG4gICAgICAgIH1cbiAgICAgICAgLiN7JGFiYnJldn1iI3skaW5maXh9LSN7JHNpemV9LFxuICAgICAgICAuI3skYWJicmV2fXkjeyRpbmZpeH0tI3skc2l6ZX0ge1xuICAgICAgICAgICN7JHByb3B9LWJvdHRvbTogJGxlbmd0aCAhaW1wb3J0YW50O1xuICAgICAgICB9XG4gICAgICAgIC4jeyRhYmJyZXZ9bCN7JGluZml4fS0jeyRzaXplfSxcbiAgICAgICAgLiN7JGFiYnJldn14I3skaW5maXh9LSN7JHNpemV9IHtcbiAgICAgICAgICAjeyRwcm9wfS1sZWZ0OiAkbGVuZ3RoICFpbXBvcnRhbnQ7XG4gICAgICAgIH1cbiAgICAgIH1cbiAgICB9XG5cbiAgICAvLyBTb21lIHNwZWNpYWwgbWFyZ2luIHV0aWxzXG4gICAgLm0jeyRpbmZpeH0tYXV0byAgeyBtYXJnaW46ICAgICAgICBhdXRvICFpbXBvcnRhbnQ7IH1cbiAgICAubXQjeyRpbmZpeH0tYXV0byxcbiAgICAubXkjeyRpbmZpeH0tYXV0byB7XG4gICAgICBtYXJnaW4tdG9wOiBhdXRvICFpbXBvcnRhbnQ7XG4gICAgfVxuICAgIC5tciN7JGluZml4fS1hdXRvLFxuICAgIC5teCN7JGluZml4fS1hdXRvIHtcbiAgICAgIG1hcmdpbi1yaWdodDogYXV0byAhaW1wb3J0YW50O1xuICAgIH1cbiAgICAubWIjeyRpbmZpeH0tYXV0byxcbiAgICAubXkjeyRpbmZpeH0tYXV0byB7XG4gICAgICBtYXJnaW4tYm90dG9tOiBhdXRvICFpbXBvcnRhbnQ7XG4gICAgfVxuICAgIC5tbCN7JGluZml4fS1hdXRvLFxuICAgIC5teCN7JGluZml4fS1hdXRvIHtcbiAgICAgIG1hcmdpbi1sZWZ0OiBhdXRvICFpbXBvcnRhbnQ7XG4gICAgfVxuICB9XG59XG4iLCIvL1xuLy8gVGV4dFxuLy9cblxuLy8gQWxpZ25tZW50XG5cbi50ZXh0LWp1c3RpZnkgIHsgdGV4dC1hbGlnbjoganVzdGlmeSAhaW1wb3J0YW50OyB9XG4udGV4dC1ub3dyYXAgICB7IHdoaXRlLXNwYWNlOiBub3dyYXAgIWltcG9ydGFudDsgfVxuLnRleHQtdHJ1bmNhdGUgeyBAaW5jbHVkZSB0ZXh0LXRydW5jYXRlOyB9XG5cbi8vIFJlc3BvbnNpdmUgYWxpZ25tZW50XG5cbkBlYWNoICRicmVha3BvaW50IGluIG1hcC1rZXlzKCRncmlkLWJyZWFrcG9pbnRzKSB7XG4gIEBpbmNsdWRlIG1lZGlhLWJyZWFrcG9pbnQtdXAoJGJyZWFrcG9pbnQpIHtcbiAgICAkaW5maXg6IGJyZWFrcG9pbnQtaW5maXgoJGJyZWFrcG9pbnQsICRncmlkLWJyZWFrcG9pbnRzKTtcblxuICAgIC50ZXh0I3skaW5maXh9LWxlZnQgICB7IHRleHQtYWxpZ246IGxlZnQgIWltcG9ydGFudDsgfVxuICAgIC50ZXh0I3skaW5maXh9LXJpZ2h0ICB7IHRleHQtYWxpZ246IHJpZ2h0ICFpbXBvcnRhbnQ7IH1cbiAgICAudGV4dCN7JGluZml4fS1jZW50ZXIgeyB0ZXh0LWFsaWduOiBjZW50ZXIgIWltcG9ydGFudDsgfVxuICB9XG59XG5cbi8vIFRyYW5zZm9ybWF0aW9uXG5cbi50ZXh0LWxvd2VyY2FzZSAgeyB0ZXh0LXRyYW5zZm9ybTogbG93ZXJjYXNlICFpbXBvcnRhbnQ7IH1cbi50ZXh0LXVwcGVyY2FzZSAgeyB0ZXh0LXRyYW5zZm9ybTogdXBwZXJjYXNlICFpbXBvcnRhbnQ7IH1cbi50ZXh0LWNhcGl0YWxpemUgeyB0ZXh0LXRyYW5zZm9ybTogY2FwaXRhbGl6ZSAhaW1wb3J0YW50OyB9XG5cbi8vIFdlaWdodCBhbmQgaXRhbGljc1xuXG4uZm9udC13ZWlnaHQtbGlnaHQgIHsgZm9udC13ZWlnaHQ6ICRmb250LXdlaWdodC1saWdodCAhaW1wb3J0YW50OyB9XG4uZm9udC13ZWlnaHQtbm9ybWFsIHsgZm9udC13ZWlnaHQ6ICRmb250LXdlaWdodC1ub3JtYWwgIWltcG9ydGFudDsgfVxuLmZvbnQtd2VpZ2h0LWJvbGQgICB7IGZvbnQtd2VpZ2h0OiAkZm9udC13ZWlnaHQtYm9sZCAhaW1wb3J0YW50OyB9XG4uZm9udC1pdGFsaWMgICAgICAgIHsgZm9udC1zdHlsZTogaXRhbGljICFpbXBvcnRhbnQ7IH1cblxuLy8gQ29udGV4dHVhbCBjb2xvcnNcblxuLnRleHQtd2hpdGUgeyBjb2xvcjogI2ZmZiAhaW1wb3J0YW50OyB9XG5cbkBlYWNoICRjb2xvciwgJHZhbHVlIGluICR0aGVtZS1jb2xvcnMge1xuICBAaW5jbHVkZSB0ZXh0LWVtcGhhc2lzLXZhcmlhbnQoJy50ZXh0LSN7JGNvbG9yfScsICR2YWx1ZSk7XG59XG5cbi50ZXh0LW11dGVkIHsgY29sb3I6ICR0ZXh0LW11dGVkICFpbXBvcnRhbnQ7IH1cblxuLy8gTWlzY1xuXG4udGV4dC1oaWRlIHtcbiAgQGluY2x1ZGUgdGV4dC1oaWRlKCk7XG59XG4iLCIvLyBUZXh0IHRydW5jYXRlXG4vLyBSZXF1aXJlcyBpbmxpbmUtYmxvY2sgb3IgYmxvY2sgZm9yIHByb3BlciBzdHlsaW5nXG5cbkBtaXhpbiB0ZXh0LXRydW5jYXRlKCkge1xuICBvdmVyZmxvdzogaGlkZGVuO1xuICB0ZXh0LW92ZXJmbG93OiBlbGxpcHNpcztcbiAgd2hpdGUtc3BhY2U6IG5vd3JhcDtcbn1cbiIsIi8vIFR5cG9ncmFwaHlcblxuQG1peGluIHRleHQtZW1waGFzaXMtdmFyaWFudCgkcGFyZW50LCAkY29sb3IpIHtcbiAgI3skcGFyZW50fSB7XG4gICAgY29sb3I6ICRjb2xvciAhaW1wb3J0YW50O1xuICB9XG4gIGEjeyRwYXJlbnR9IHtcbiAgICBAaW5jbHVkZSBob3Zlci1mb2N1cyB7XG4gICAgICBjb2xvcjogZGFya2VuKCRjb2xvciwgMTAlKSAhaW1wb3J0YW50O1xuICAgIH1cbiAgfVxufVxuIiwiLy8gQ1NTIGltYWdlIHJlcGxhY2VtZW50XG5AbWl4aW4gdGV4dC1oaWRlKCkge1xuICBmb250OiAwLzAgYTtcbiAgY29sb3I6IHRyYW5zcGFyZW50O1xuICB0ZXh0LXNoYWRvdzogbm9uZTtcbiAgYmFja2dyb3VuZC1jb2xvcjogdHJhbnNwYXJlbnQ7XG4gIGJvcmRlcjogMDtcbn1cbiIsIi8vXG4vLyBWaXNpYmlsaXR5IHV0aWxpdGllc1xuLy9cblxuLnZpc2libGUge1xuICBAaW5jbHVkZSBpbnZpc2libGUodmlzaWJsZSk7XG59XG5cbi5pbnZpc2libGUge1xuICBAaW5jbHVkZSBpbnZpc2libGUoaGlkZGVuKTtcbn1cbiIsIi8vIFZpc2liaWxpdHlcblxuQG1peGluIGludmlzaWJsZSgkdmlzaWJpbGl0eSkge1xuICB2aXNpYmlsaXR5OiAkdmlzaWJpbGl0eSAhaW1wb3J0YW50O1xufVxuIiwiLypcbiAqIFNJWkVcbiAqL1xuJHNpemVfX2hlYWRlcl9oZWlnaHQ6IDEyMHB4O1xuJHNpemVfX2xlZnRfc2lkZWJhcl93aWR0aDogJHNpemVfX2hlYWRlcl9oZWlnaHQ7XG4kc2l6ZV9faGVhZGVyX2ZvbnQ6IDMwcHg7XG4kc2l6ZV9fcmlnaHRfc2lkZWJhcl93aWR0aDogJHNpemVfX2xlZnRfc2lkZWJhcl93aWR0aCoyLjQ7XG4kc2l6ZV9fZGVsaW1pdGFkb3Jfd2lkdGg6IDFweDtcbi8qXG4gKiBDT0xPUlxuICovXG4kY29sb3JfX2hlYWRlcjogcmdiYSgxNDIsIDE0MiwgMTQyLCAwLjQpO1xuJGNvbG9yX19waW5rOiAjZjkyYjZkO1xuJGNvbG9yX19saW1lOiAjOWRkZDYxO1xuJGNvbG9yX19waW5rX2hpZ2h0bGlnaHQ6IHJlZDtcbiRjb2xvcl9fbWFpbl9iZzogI2ZhZjdmNjtcbiRjb2xvcl9fbGlnaHRncmV5OiAjRThFOEU3O1xuIiwiLmNvbG9yX19saW1le1xuICBjb2xvcjogJGNvbG9yX19saW1lO1xufVxuLmNvbG9yX19waW5re1xuICBjb2xvcjogJGNvbG9yX19waW5rO1xufVxuLmNvbG9yX19saWdodGdyZXl7XG4gIGNvbG9yOiAkY29sb3JfX2xpZ2h0Z3JleTtcbn1cbiIsIlxuYnV0dG9uLmN1c3RvbXtcbiAgQGV4dGVuZCAuZC1mbGV4LCAuZmxleC1yb3c7XG4gIEBleHRlbmQgLmJ0bjtcblxuICAkY29sb3I6ICRjb2xvcl9fcGluaztcbiAgJGhpZ2g6ICRjb2xvcl9fcGlua19oaWdodGxpZ2h0O1xuXG4gIGJhY2tncm91bmQtY29sb3I6IHRyYW5zcGFyZW50O1xuICBib3JkZXI6IDJweCBzb2xpZCAkY29sb3I7XG4gIHBhZGRpbmc6IC40ZW07XG4gIGNvbG9yOiAkY29sb3I7XG4gIGZvbnQtc2l6ZTogaW5oZXJpdDtcbiAgY3Vyc29yOiBwb2ludGVyO1xuICB0cmFuc2l0aW9uOiBjb2xvciAuNXMsIGJvcmRlci1jb2xvciAuNXM7XG5cbiAgJjpob3ZlcntcbiAgICBjb2xvcjogJGhpZ2g7XG4gICAgYm9yZGVyLWNvbG9yOiAkaGlnaDtcbiAgfVxuXG4gIC5pY29ue1xuICAgICRzaXplOiAuOCokc2l6ZV9faGVhZGVyX2ZvbnQ7XG4gICAgaGVpZ2h0OiAxZW07XG4gICAgd2lkdGg6IDFlbTtcbiAgICAqe1xuICAgICAgc3Ryb2tlOiAkY29sb3I7XG4gICAgICBmaWxsOiAkY29sb3I7XG4gICAgfVxuICB9XG4gIFtyb2xlPVwibGFiZWxcIl17XG4gICAgbWFyZ2luLWxlZnQ6IC41ZW07XG4gIH1cbn1cbiIsIi5jYXJke1xuICBib3gtc2hhZG93OiAwIDAgMjBweCAwcHggcmdiYSgwLCAwLCAwLCAwLjA1KTtcbiAgYm9yZGVyOiBub25lO1xuICBmbGV4LWJhc2lzOiAyMCU7XG4gIGJvcmRlci1yYWRpdXM6IC40ZW07XG4gIHBhZGRpbmc6IDFlbTtcbiAgZm9udC1zaXplOiAyMHB4O1xuICBmb250LXdlaWdodDogNTAwO1xuICBwb3NpdGlvbjogcmVsYXRpdmU7XG4gIFxuICAmPip7XG4gICAgbWFyZ2luOiAuMmVtO1xuICB9XG4gIGgxe1xuICAgIHBvc2l0aW9uOiByZWxhdGl2ZTtcbiAgICBmb250LXNpemU6IC43ZW07XG4gICAgLmljb257XG4gICAgICAmPip7XG4gICAgICAgIGZpbGw6ICRjb2xvcl9fbGlnaHRncmV5O1xuICAgICAgfVxuICAgICAgcG9zaXRpb246IGFic29sdXRlO1xuICAgICAgcmlnaHQ6IDA7XG4gICAgICBoZWlnaHQ6IDFlbTtcbiAgICAgIHdpZHRoOiAyZW07O1xuICAgIH1cbiAgfVxuICBwe1xuICAgIHNwYW57XG4gICAgICBmb250LXNpemU6LjhlbTtcbiAgICAgIGZvbnQtd2VpZ2h0OiA0MDA7XG4gICAgfVxuICAgIGZvbnQtc2l6ZTogMS4yZW07XG4gICAgbGV0dGVyLXNwYWNpbmc6IC4xZW07XG4gIH1cbn1cbiJdLCJzb3VyY2VSb290IjoiL3NvdXJjZS8ifQ== */

</style>
