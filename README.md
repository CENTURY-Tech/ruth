# Ruth

A friendly router written for Web Components

[![npm](https://img.shields.io/npm/v/@ctek/ruth.svg?style=flat-square)](https://www.npmjs.com/package/@ctek/ruth) [![Bower](https://img.shields.io/bower/v/ruth.svg?style=flat-square)](https://github.com/CENTURY-Tech/ruth)

## Basic usage
```html
<template is="ruth-redirect" to-path="/my-old-path" from-path="/my-new-path"></template>

<template is="ruth-route" path="my-courses">
  <!-- You can use HTML imports or whatever else suits you. Ruth won't care or judge you... -->
  <link rel="import" href="../my-component.html">
  <my-component></my-component>
</template>

<!-- ÏFallback template, when no routes are matched at this level -->
<template is="ruth" default>
  <link rel="import" href="../page-404.html">
  <page-404></page-404>
</template>
```
