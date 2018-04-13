# [Base Layout Helpers](http://getbase.org)

Base Layout Helpers is designed in a way where you can add it on top of the Base CSS framework or to your own custom project.

[![Travis Build Status][travis-img]][travis] [![David Dependencies Status][david-img]][david]

[travis-img]:   https://img.shields.io/travis/getbase/layout-helpers.svg?branch=master
[david-img]:    https://img.shields.io/david/dev/getbase/layout-helpers.svg?branch=master&label=dependencies
[travis]:       https://travis-ci.org/getbase/layout-helpers
[david]:        https://david-dm.org/getbase/layout-helpers?type=dev

* * *

## Table of contents

* [Overview](#overview)
* [Installation](#installation)
* [Documentation](#documentation)
* [Demo](#demo)
* [Support](#support)
* [Authors](#authors)
* [License](#license)

* * *

## Overview

Base Layout Helpers contains styles for adding spaced rows (`.pad-top-5, .pad-bottom-20`, etc), spaced layout (`pad-5, pad-20`, etc), resetting margins, resetting paddings, resetting floats, setting position types and flex helpers for all breakpoints.

* * *

## Installation

If you have an existing project and would like to include the Base layout helpers module, run the following command:

```bash
npm install --save @getbase/layout-helpers
```

Once you have the layout helpers module installed, you can include it in your CSS/LESS/SCSS file with one of the following ways:

#### CSS Import:
  ```css
  import url("https://cdn.rawgit.com/getbase/layout-helpers/master/css/index.css");
  ```

#### SCSS Import:

  ```scss
  /* Import Base Layout Helpers */
  @import "node_modules/@getbase/layout-helpers/scss/index";
  /* Your Other Styles */
  @import "main"
  ```


#### LESS Import:

  ```css
  /* Import Base Layout Helpers */
  @import "node_modules/@getbase/layout-helpers/scss/index";
  /* Your Other Styles */
  @import "main"
  ```

* * *

## Documentation

Base Layout Helpers includes styles for adding spaced rows (`.pad-top-5, .pad-bottom-20`, etc), spaced layout (`pad-5, pad-20`, etc), resetting margins, resetting paddings, resetting floats, setting position types and flex helpers for all breakpoints

#### Helpers (Applies to SCSS/LESS)

| Helper Class | Purpose | Example | Outcome |
| ------------ | ------- | ------- | ------- |
| `.no-margin` | Applies margin `0` | `<div class="no-margin">No margin</div>` | Applies a margin of `0` to a `div` element for all breakpoints |
| `.no-padding` | Applies padding `0` | `<div class="no-padding">No padding</div>` | Applies a padding of `0` to a `div` element for all breakpoints |
| `.no-float` | Applies float `none` | `<div class="no-float">No float</div>` | Applies a float of `none` to a `div` element for all breakpoints |
| `.absolute` | Applies position `absolute` | `<div class="absolute">Absolute</div>` | Applies a position of `absolute` to a `div` element for all breakpoints |
| `.static` | Applies position `static` | `<div class="static">Static</div>` | Applies a position of `static` to a `div` element for all breakpoints |
| `.fixed` | Applies position `fixed` | `<div class="fixed">Fixed</div>` | Applies a position of `fixed` to a `div` element for all breakpoints |
| `.none` | Applies display `none` | `<div class="none">You won't see this text</div>` | Applies a display of `none` to a `div` element for all breakpoints |
| `.block` | Applies display `block` | `<span class="block">This will be a block element</span>` | Applies a display of `block` to a `span` element for all breakpoints |
| `.inline-block` | Applies display `inline-block` | `<div class="inline-block">This element will be inline-block</div>` | Applies a display of `inline-block` to a `div` element for all breakpoints |
| `.inline` | Applies display `inline` | `<div class="inline">This element will be inline</div>` | Applies a display of `inline` to a `div` element for all breakpoints |
| `.flex` | Applies display `flex` | `<div class="flex">This element will be flex</div>` | Applies a display of `flex` to a `div` element for all breakpoints |
| `.flex-row` | Applies flex direction `row` | `<div class="flex flex-row">Flex direction will be row</div>` | Applies a flex direction of `flex-row` to a `div` element for all breakpoints |
| `.flex-row-reverse` | Applies flex direction `row-reverse` | `<div class="flex flex-row-reverse">Flex direction will be row in reverse</div>` | Applies a flex direction of `flex-row-reverse` to a `div` element for all breakpoints |
| `.flex-column` | Applies flex direction `column` | `<div class="flex flex-column">Flex direction will be column</div>` | Applies a flex direction of `flex-column` to a `div` element for all breakpoints |
| `.flex-column-reverse` | Applies flex direction `column-reverse` | `<div class="flex flex-column-reverse">Flex direction will be column reverse</div>` | Applies a flex direction of `flex-column-reverse` to a `div` element for all breakpoints |
| `.flex-space-around` | Applies spacing around elements within a flex container | `<div class="flex flex-space-around">Flex space around is applied</div>` | Applies spacing around elements within a `div` element for all breakpoints |
| `.flex-space-between` | Applies spacing between elements within a flex container | `<div class="flex flex-space-between">Flex space between is applied</div>` | Applies spacing between elements within a `div` element for all breakpoints |
| `.flex-start` | Applies alignment of a flex item to the start | `<div class="flex flex-start">This item will be aligned to the start</div>` | Aligns element within a `div` element to the start for all breakpoints |
| `.flex-center` | Applies alignment of a flex item to the center | `<div class="flex flex-center">This item will be aligned to the center</div>` | Aligns element within a `div` element to the center for all breakpoints |
| `.flex-end` | Applies alignment of flex item to the end | `<div class="flex flex-end">This item will be aligned to the end</div>` | Aligns element within a `div` element to the end for all breakpoints |
| `.flex-wrap` | Applies flex items to wrap within a flex container | `<div class="flex flex-wrap">Flex items will wrap within a flex container</div>` | `div` elements will wrap within a flex container for all breakpoints |
| `.flex-no-wrap` | Applies flex items to not wrap within a flex container | `<div class="flex flex-no-wrap">Flex items will not wrap within a flex container</div>` | `div` elements will not wrap within a flex container for all breakpoints |
| `.left` | Applies float `left` | `<div class="left">This element will float left</div>` | Applies a float `left` to a `div` element for all breakpoints |
| `.right` | Applies float `right` | `<div class="right">This element will float right</div>` | Applies a float `right` to a `div` element for all breakpoints |
| `.pad-top-5` | Applies top padding `5px` | `<div class="pad-top-5">This element will have a top padding of 5px</div>` | Applies a `padding-top` of `5px` to a `div` element for all breakpoints |
| `.pad-top-10` | Applies top padding `10px` | `<div class="pad-top-10">This element will have a top padding of 10px</div>` | Applies a `padding-top` of `10px` to a `div` element for all breakpoints |
| `.pad-top-15` | Applies top padding `15px` | `<div class="pad-top-15">This element will have a top padding of 15px</div>` | Applies a `padding-top` of `15px` to a `div` element for all breakpoints |
| `.pad-top-20` | Applies top padding `20px` | `<div class="pad-top-20">This element will have a top padding of 20px</div>` | Applies a `padding-top` of `20px` to a `div` element for all breakpoints |
| `.pad-top-25` | Applies top padding `25px` | `<div class="pad-top-25">This element will have a top padding of 25px</div>` | Applies a `padding-top` of `25px` to a `div` element for all breakpoints |
| `.pad-top-30` | Applies top padding `30px` | `<div class="pad-top-30">This element will have a top padding of 30px</div>` | Applies a `padding-top` of `30px` to a `div` element for all breakpoints |
| `.pad-top-35` | Applies top padding `35px` | `<div class="pad-top-35">This element will have a top padding of 35px</div>` | Applies a `padding-top` of `35px` to a `div` element for all breakpoints |
| `.pad-top-40` | Applies top padding `40px` | `<div class="pad-top-40">This element will have a top padding of 40px</div>` | Applies a `padding-top` of `40px` to a `div` element for all breakpoints |
| `.pad-top-45` | Applies top padding `45px` | `<div class="pad-top-45">This element will have a top padding of 45px</div>` | Applies a `padding-top` of `45px` to a `div` element for all breakpoints |
| `.pad-top-50` | Applies top padding `50px` | `<div class="pad-top-50">This element will have a top padding of 50px</div>` | Applies a `padding-top` of `50px` to a `div` element for all breakpoints |
| `.pad-top-55` | Applies top padding `55px` | `<div class="pad-top-55">This element will have a top padding of 55px</div>` | Applies a `padding-top` of `55px` to a `div` element for all breakpoints |
| `.pad-top-60` | Applies top padding `60px` | `<div class="pad-top-60">This element will have a top padding of 60px</div>` | Applies a `padding-top` of `60px` to a `div` element for all breakpoints |
| `.pad-bottom-5` | Applies bottom padding `5px` | `<div class="pad-bottom-5">This element will have a bottom padding of 5px</div>` | Applies a `padding-bottom` of `5px` to a `div` element for all breakpoints |
| `.pad-bottom-10` | Applies bottom padding `10px` | `<div class="pad-bottom-10">This element will have a bottom padding of 10px</div>` | Applies a `padding-bottom` of `10px` to a `div` element for all breakpoints |
| `.pad-bottom-15` | Applies bottom padding `15px` | `<div class="pad-bottom-15">This element will have a bottom padding of 15px</div>` | Applies a `padding-bottom` of `15px` to a `div` element for all breakpoints |
| `.pad-bottom-20` | Applies bottom padding `20px` | `<div class="pad-bottom-20">This element will have a bottom padding of 20px</div>` | Applies a `padding-bottom` of `20px` to a `div` element for all breakpoints |
| `.pad-bottom-25` | Applies bottom padding `25px` | `<div class="pad-bottom-25">This element will have a bottom padding of 25px</div>` | Applies a `padding-bottom` of `25px` to a `div` element for all breakpoints |
| `.pad-bottom-30` | Applies bottom padding `30px` | `<div class="pad-bottom-30">This element will have a bottom padding of 30px</div>` | Applies a `padding-bottom` of `30px` to a `div` element for all breakpoints |
| `.pad-bottom-35` | Applies bottom padding `35px` | `<div class="pad-bottom-35">This element will have a bottom padding of 35px</div>` | Applies a `padding-bottom` of `35px` to a `div` element for all breakpoints |
| `.pad-bottom-40` | Applies bottom padding `40px` | `<div class="pad-bottom-40">This element will have a bottom padding of 40px</div>` | Applies a `padding-bottom` of `40px` to a `div` element for all breakpoints |
| `.pad-bottom-45` | Applies bottom padding `45px` | `<div class="pad-bottom-45">This element will have a bottom padding of 45px</div>` | Applies a `padding-bottom` of `45px` to a `div` element for all breakpoints |
| `.pad-bottom-50` | Applies bottom padding `50px` | `<div class="pad-bottom-50">This element will have a bottom padding of 50px</div>` | Applies a `padding-bottom` of `50px` to a `div` element for all breakpoints |
| `.pad-bottom-55` | Applies bottom padding `55px` | `<div class="pad-bottom-55">This element will have a bottom padding of 55px</div>` | Applies a `padding-bottom` of `55px` to a `div` element for all breakpoints |
| `.pad-bottom-60` | Applies bottom padding `60px` | `<div class="pad-bottom-60">This element will have a bottom padding of 60px</div>` | Applies a `padding-bottom` of `60px` to a `div` element for all breakpoints |
| `.pad-5` | Applies padding `5px` | `<div class="pad-5">This element will have a padding of 5px</div>` | Applies a `padding` of `5px` to a `div` element for all breakpoints |
| `.pad-10` | Applies padding `10px` | `<div class="pad-10">This element will have a padding of 10px</div>` | Applies a `padding` of `10px` to a `div` element for all breakpoints |
| `.pad-15` | Applies padding `15px` | `<div class="pad-15">This element will have a padding of 15px</div>` | Applies a `padding` of `15px` to a `div` element for all breakpoints |
| `.pad-20` | Applies padding `20px` | `<div class="pad-20">This element will have a padding of 20px</div>` | Applies a `padding` of `20px` to a `div` element for all breakpoints |
| `.pad-25` | Applies padding `25px` | `<div class="pad-25">This element will have a padding of 25px</div>` | Applies a `padding` of `25px` to a `div` element for all breakpoints |
| `.pad-30` | Applies padding `30px` | `<div class="pad-30">This element will have a padding of 30px</div>` | Applies a `padding` of `30px` to a `div` element for all breakpoints |
| `.pad-35` | Applies padding `35px` | `<div class="pad-35">This element will have a padding of 35px</div>` | Applies a `padding` of `35px` to a `div` element for all breakpoints |
| `.pad-40` | Applies padding `40px` | `<div class="pad-40">This element will have a padding of 40px</div>` | Applies a `padding` of `40px` to a `div` element for all breakpoints |
| `.pad-45` | Applies padding `45px` | `<div class="pad-45">This element will have a padding of 45px</div>` | Applies a `padding` of `45px` to a `div` element for all breakpoints |
| `.pad-50` | Applies padding `50px` | `<div class="pad-50">This element will have a padding of 50px</div>` | Applies a `padding` of `50px` to a `div` element for all breakpoints |
| `.pad-55` | Applies padding `55px` | `<div class="pad-55">This element will have a padding of 55px</div>` | Applies a `padding` of `55px` to a `div` element for all breakpoints |
| `.pad-60` | Applies padding `60px` | `<div class="pad-60">This element will have a padding of 60px</div>` | Applies a `padding` of `60px` to a `div` element for all breakpoints |
| `.no-margin-m` | Applies margin `0` | `<div class="no-margin-m">No margin</div>` | Applies a margin of `0` to a `div` element for medium devices and above |
| `.no-padding-m` | Applies padding `0` | `<div class="no-padding-m">No padding</div>` | Applies a padding of `0` to a `div` element for medium devices and above |
| `.no-float-m` | Applies float `none` | `<div class="no-float-m">No float</div>` | Applies a float of `none` to a `div` element for medium devices and above |
| `.absolute-m` | Applies position `absolute` | `<div class="absolute-m">Absolute</div>` | Applies a position of `absolute` to a `div` element for medium devices and above |
| `.static-m` | Applies position `static` | `<div class="static-m">Static</div>` | Applies a position of `static` to a `div` element for medium devices and above |
| `.fixed-m` | Applies position `fixed` | `<div class="fixed-m">Fixed</div>` | Applies a position of `fixed` to a `div` element for medium devices and above |
| `.none-m` | Applies display `none` | `<div class="none-m">You won't see this text</div>` | Applies a display of `none` to a `div` element for medium devices and above |
| `.block-m` | Applies display `block` | `<span class="block-m">This will be a block element</span>` | Applies a display of `block` to a `span` element for medium devices and above |
| `.inline-block-m` | Applies display `inline-block` | `<div class="inline-block-m">This element will be inline-block</div>` | Applies a display of `inline-block` to a `div` element for medium devices and above |
| `.inline-m` | Applies display `inline` | `<div class="inline-m">This element will be inline</div>` | Applies a display of `inline` to a `div` element for medium devices and above |
| `.flex-m` | Applies display `flex` | `<div class="flex-m">This element will be flex</div>` | Applies a display of `flex` to a `div` element for medium devices and above |
| `.flex-row-m` | Applies flex direction `row` | `<div class="flex-m flex-row-m">Flex direction will be row</div>` | Applies a flex direction of `flex-row-m` to a `div` element for medium devices and above |
| `.flex-row-reverse-m` | Applies flex direction `row-reverse-m` | `<div class="flex-m flex-row-reverse-m">Flex direction will be row in reverse</div>` | Applies a flex direction of `flex-row-reverse-m` to a `div` element for medium devices and above |
| `.flex-column-m` | Applies flex direction `column` | `<div class="flex-m flex-column-m">Flex direction will be column</div>` | Applies a flex direction of `flex-column-m` to a `div` element for medium devices and above |
| `.flex-column-reverse-m` | Applies flex direction `column-reverse-m` | `<div class="flex-m flex-column-reverse-m">Flex direction will be column reverse</div>` | Applies a flex direction of `flex-column-reverse-m` to a `div` element for medium devices and above |
| `.flex-space-around-m` | Applies spacing around elements within a flex container | `<div class="flex-m flex-space-around-m">Flex space around is applied</div>` | Applies spacing around elements within a `div` element for medium devices and above |
| `.flex-space-between-m` | Applies spacing between elements within a flex container | `<div class="flex-m flex-space-between-m">Flex space between is applied</div>` | Applies spacing between elements within a `div` element for medium devices and above |
| `.flex-start-m` | Applies alignment of a flex item to the start | `<div class="flex-m flex-start-m">This item will be aligned to the start</div>` | Aligns element within a `div` element to the start for medium devices and above |
| `.flex-center-m` | Applies alignment of a flex item to the center | `<div class="flex-m flex-center-m">This item will be aligned to the center</div>` | Aligns element within a `div` element to the center for medium devices and above |
| `.flex-end-m` | Applies alignment of flex item to the end | `<div class="flex-m flex-end-m">This item will be aligned to the end</div>` | Aligns element within a `div` element to the end for medium devices and above |
| `.flex-wrap-m` | Applies flex items to wrap within a flex container | `<div class="flex-m flex-wrap-m">Flex items will wrap within a flex container</div>` | `div` elements will wrap within a flex container for medium devices and above |
| `.flex-no-wrap-m` | Applies flex items to not wrap within a flex container | `<div class="flex-m flex-no-wrap-m">Flex items will not wrap within a flex container</div>` | `div` elements will not wrap within a flex container for medium devices and above |
| `.left-m` | Applies float `left` | `<div class="left-m">This element will float left</div>` | Applies a float `left` to a `div` element for medium devices and above |
| `.right-m` | Applies float `right` | `<div class="right-m">This element will float right</div>` | Applies a float `right` to a `div` element for medium devices and above |
| `.pad-top-5-m` | Applies top padding `5px` | `<div class="pad-top-5-m">This element will have a top padding of 5px</div>` | Applies a `padding-top` of `5px` to a `div` element for medium devices and above |
| `.pad-top-10-m` | Applies top padding `10px` | `<div class="pad-top-10-m">This element will have a top padding of 10px</div>` | Applies a `padding-top` of `10px` to a `div` element for medium devices and above |
| `.pad-top-15-m` | Applies top padding `15px` | `<div class="pad-top-15-m">This element will have a top padding of 15px</div>` | Applies a `padding-top` of `15px` to a `div` element for medium devices and above |
| `.pad-top-20-m` | Applies top padding `20px` | `<div class="pad-top-20-m">This element will have a top padding of 20px</div>` | Applies a `padding-top` of `20px` to a `div` element for medium devices and above |
| `.pad-top-25-m` | Applies top padding `25px` | `<div class="pad-top-25-m">This element will have a top padding of 25px</div>` | Applies a `padding-top` of `25px` to a `div` element for medium devices and above |
| `.pad-top-30-m` | Applies top padding `30px` | `<div class="pad-top-30-m">This element will have a top padding of 30px</div>` | Applies a `padding-top` of `30px` to a `div` element for medium devices and above |
| `.pad-top-35-m` | Applies top padding `35px` | `<div class="pad-top-35-m">This element will have a top padding of 35px</div>` | Applies a `padding-top` of `35px` to a `div` element for medium devices and above |
| `.pad-top-40-m` | Applies top padding `40px` | `<div class="pad-top-40-m">This element will have a top padding of 40px</div>` | Applies a `padding-top` of `40px` to a `div` element for medium devices and above |
| `.pad-top-45-m` | Applies top padding `45px` | `<div class="pad-top-45-m">This element will have a top padding of 45px</div>` | Applies a `padding-top` of `45px` to a `div` element for medium devices and above |
| `.pad-top-50-m` | Applies top padding `50px` | `<div class="pad-top-50-m">This element will have a top padding of 50px</div>` | Applies a `padding-top` of `50px` to a `div` element for medium devices and above |
| `.pad-top-55-m` | Applies top padding `55px` | `<div class="pad-top-55-m">This element will have a top padding of 55px</div>` | Applies a `padding-top` of `55px` to a `div` element for medium devices and above |
| `.pad-top-60-m` | Applies top padding `60px` | `<div class="pad-top-60-m">This element will have a top padding of 60px</div>` | Applies a `padding-top` of `60px` to a `div` element for medium devices and above |
| `.pad-bottom-5-m` | Applies bottom padding `5px` | `<div class="pad-bottom-5-m">This element will have a bottom padding of 5px</div>` | Applies a `padding-bottom` of `5px` to a `div` element for medium devices and above |
| `.pad-bottom-10-m` | Applies bottom padding `10px` | `<div class="pad-bottom-10-m">This element will have a bottom padding of 10px</div>` | Applies a `padding-bottom` of `10px` to a `div` element for medium devices and above |
| `.pad-bottom-15-m` | Applies bottom padding `15px` | `<div class="pad-bottom-15-m">This element will have a bottom padding of 15px</div>` | Applies a `padding-bottom` of `15px` to a `div` element for medium devices and above |
| `.pad-bottom-20-m` | Applies bottom padding `20px` | `<div class="pad-bottom-20-m">This element will have a bottom padding of 20px</div>` | Applies a `padding-bottom` of `20px` to a `div` element for medium devices and above |
| `.pad-bottom-25-m` | Applies bottom padding `25px` | `<div class="pad-bottom-25-m">This element will have a bottom padding of 25px</div>` | Applies a `padding-bottom` of `25px` to a `div` element for medium devices and above |
| `.pad-bottom-30-m` | Applies bottom padding `30px` | `<div class="pad-bottom-30-m">This element will have a bottom padding of 30px</div>` | Applies a `padding-bottom` of `30px` to a `div` element for medium devices and above |
| `.pad-bottom-35-m` | Applies bottom padding `35px` | `<div class="pad-bottom-35-m">This element will have a bottom padding of 35px</div>` | Applies a `padding-bottom` of `35px` to a `div` element for medium devices and above |
| `.pad-bottom-40-m` | Applies bottom padding `40px` | `<div class="pad-bottom-40-m">This element will have a bottom padding of 40px</div>` | Applies a `padding-bottom` of `40px` to a `div` element for medium devices and above |
| `.pad-bottom-45-m` | Applies bottom padding `45px` | `<div class="pad-bottom-45-m">This element will have a bottom padding of 45px</div>` | Applies a `padding-bottom` of `45px` to a `div` element for medium devices and above |
| `.pad-bottom-50-m` | Applies bottom padding `50px` | `<div class="pad-bottom-50-m">This element will have a bottom padding of 50px</div>` | Applies a `padding-bottom` of `50px` to a `div` element for medium devices and above |
| `.pad-bottom-55-m` | Applies bottom padding `55px` | `<div class="pad-bottom-55-m">This element will have a bottom padding of 55px</div>` | Applies a `padding-bottom` of `55px` to a `div` element for medium devices and above |
| `.pad-bottom-60-m` | Applies bottom padding `60px` | `<div class="pad-bottom-60-m">This element will have a bottom padding of 60px</div>` | Applies a `padding-bottom` of `60px` to a `div` element for medium devices and above |
| `.pad-5-m` | Applies padding `5px` | `<div class="pad-5-m">This element will have a padding of 5px</div>` | Applies a `padding` of `5px` to a `div` element for medium devices and above |
| `.pad-10-m` | Applies padding `10px` | `<div class="pad-10-m">This element will have a padding of 10px</div>` | Applies a `padding` of `10px` to a `div` element for medium devices and above |
| `.pad-15-m` | Applies padding `15px` | `<div class="pad-15-m">This element will have a padding of 15px</div>` | Applies a `padding` of `15px` to a `div` element for medium devices and above |
| `.pad-20-m` | Applies padding `20px` | `<div class="pad-20-m">This element will have a padding of 20px</div>` | Applies a `padding` of `20px` to a `div` element for medium devices and above |
| `.pad-25-m` | Applies padding `25px` | `<div class="pad-25-m">This element will have a padding of 25px</div>` | Applies a `padding` of `25px` to a `div` element for medium devices and above |
| `.pad-30-m` | Applies padding `30px` | `<div class="pad-30-m">This element will have a padding of 30px</div>` | Applies a `padding` of `30px` to a `div` element for medium devices and above |
| `.pad-35-m` | Applies padding `35px` | `<div class="pad-35-m">This element will have a padding of 35px</div>` | Applies a `padding` of `35px` to a `div` element for medium devices and above |
| `.pad-40-m` | Applies padding `40px` | `<div class="pad-40-m">This element will have a padding of 40px</div>` | Applies a `padding` of `40px` to a `div` element for medium devices and above |
| `.pad-45-m` | Applies padding `45px` | `<div class="pad-45-m">This element will have a padding of 45px</div>` | Applies a `padding` of `45px` to a `div` element for medium devices and above |
| `.pad-50-m` | Applies padding `50px` | `<div class="pad-50-m">This element will have a padding of 50px</div>` | Applies a `padding` of `50px` to a `div` element for medium devices and above |
| `.pad-55-m` | Applies padding `55px` | `<div class="pad-55-m">This element will have a padding of 55px</div>` | Applies a `padding` of `55px` to a `div` element for medium devices and above |
| `.pad-60-m` | Applies padding `60px` | `<div class="pad-60-m">This element will have a padding of 60px</div>` | Applies a `padding` of `60px` to a `div` element for medium devices and above |
| `.no-margin-l` | Applies margin `0` | `<div class="no-margin-l">No margin</div>` | Applies a margin of `0` to a `div` element for large devices and above |
| `.no-padding-l` | Applies padding `0` | `<div class="no-padding-l">No padding</div>` | Applies a padding of `0` to a `div` element for large devices and above |
| `.no-float-l` | Applies float `none` | `<div class="no-float-l">No float</div>` | Applies a float of `none` to a `div` element for large devices and above |
| `.absolute-l` | Applies position `absolute` | `<div class="absolute-l">Absolute</div>` | Applies a position of `absolute` to a `div` element for large devices and above |
| `.static-l` | Applies position `static` | `<div class="static-l">Static</div>` | Applies a position of `static` to a `div` element for large devices and above |
| `.fixed-l` | Applies position `fixed` | `<div class="fixed-l">Fixed</div>` | Applies a position of `fixed` to a `div` element for large devices and above |
| `.none-l` | Applies display `none` | `<div class="none-l">You won't see this text</div>` | Applies a display of `none` to a `div` element for large devices and above |
| `.block-l` | Applies display `block` | `<span class="block-l">This will be a block element</span>` | Applies a display of `block` to a `span` element for large devices and above |
| `.inline-block-l` | Applies display `inline-block` | `<div class="inline-block-l">This element will be inline-block</div>` | Applies a display of `inline-block` to a `div` element for large devices and above |
| `.inline-l` | Applies display `inline` | `<div class="inline-l">This element will be inline</div>` | Applies a display of `inline` to a `div` element for large devices and above |
| `.flex-l` | Applies display `flex` | `<div class="flex-l">This element will be flex</div>` | Applies a display of `flex` to a `div` element for large devices and above |
| `.flex-row-l` | Applies flex direction `row` | `<div class="flex-l flex-row-l">Flex direction will be row</div>` | Applies a flex direction of `flex-row-l` to a `div` element for large devices and above |
| `.flex-row-reverse-l` | Applies flex direction `row-reverse-l` | `<div class="flex-l flex-row-reverse-l">Flex direction will be row in reverse</div>` | Applies a flex direction of `flex-row-reverse-l` to a `div` element for large devices and above |
| `.flex-column-l` | Applies flex direction `column` | `<div class="flex-l flex-column-l">Flex direction will be column</div>` | Applies a flex direction of `flex-column-l` to a `div` element for large devices and above |
| `.flex-column-reverse-l` | Applies flex direction `column-reverse-l` | `<div class="flex-l flex-column-reverse-l">Flex direction will be column reverse</div>` | Applies a flex direction of `flex-column-reverse-l` to a `div` element for large devices and above |
| `.flex-space-around-l` | Applies spacing around elements within a flex container | `<div class="flex-m flex-space-around-l">Flex space around is applied</div>` | Applies spacing around elements within a `div` element for large devices and above |
| `.flex-space-between-l` | Applies spacing between elements within a flex container | `<div class="flex-m flex-space-between-l">Flex space between is applied</div>` | Applies spacing between elements within a `div` element for large devices and above |
| `.flex-start-l` | Applies alignment of a flex item to the start | `<div class="flex-m flex-start-l">This item will be aligned to the start</div>` | Aligns element within a `div` element to the start for large devices and above |
| `.flex-center-l` | Applies alignment of a flex item to the center | `<div class="flex-m flex-center-l">This item will be aligned to the center</div>` | Aligns element within a `div` element to the center for large devices and above |
| `.flex-end-l` | Applies alignment of flex item to the end | `<div class="flex-m flex-end-l">This item will be aligned to the end</div>` | Aligns element within a `div` element to the end for large devices and above |
| `.flex-wrap-l` | Applies flex items to wrap within a flex container | `<div class="flex-m flex-wrap-l">Flex items will wrap within a flex container</div>` | `div` elements will wrap within a flex container for large devices and above |
| `.flex-no-wrap-l` | Applies flex items to not wrap within a flex container | `<div class="flex-m flex-no-wrap-l">Flex items will not wrap within a flex container</div>` | `div` elements will not wrap within a flex container for large devices and above |
| `.left-l` | Applies float `left` | `<div class="left-l">This element will float left</div>` | Applies a float `left` to a `div` element for large devices and above |
| `.right-l` | Applies float `right` | `<div class="right-l">This element will float right</div>` | Applies a float `right` to a `div` element for large devices and above |
| `.pad-top-5-l` | Applies top padding `5px` | `<div class="pad-top-5-l">This element will have a top padding of 5px</div>` | Applies a `padding-top` of `5px` to a `div` element for large devices and above |
| `.pad-top-10-l` | Applies top padding `10px` | `<div class="pad-top-10-l">This element will have a top padding of 10px</div>` | Applies a `padding-top` of `10px` to a `div` element for large devices and above |
| `.pad-top-15-l` | Applies top padding `15px` | `<div class="pad-top-15-l">This element will have a top padding of 15px</div>` | Applies a `padding-top` of `15px` to a `div` element for large devices and above |
| `.pad-top-20-l` | Applies top padding `20px` | `<div class="pad-top-20-l">This element will have a top padding of 20px</div>` | Applies a `padding-top` of `20px` to a `div` element for large devices and above |
| `.pad-top-25-l` | Applies top padding `25px` | `<div class="pad-top-25-l">This element will have a top padding of 25px</div>` | Applies a `padding-top` of `25px` to a `div` element for large devices and above |
| `.pad-top-30-l` | Applies top padding `30px` | `<div class="pad-top-30-l">This element will have a top padding of 30px</div>` | Applies a `padding-top` of `30px` to a `div` element for large devices and above |
| `.pad-top-35-l` | Applies top padding `35px` | `<div class="pad-top-35-l">This element will have a top padding of 35px</div>` | Applies a `padding-top` of `35px` to a `div` element for large devices and above |
| `.pad-top-40-l` | Applies top padding `40px` | `<div class="pad-top-40-l">This element will have a top padding of 40px</div>` | Applies a `padding-top` of `40px` to a `div` element for large devices and above |
| `.pad-top-45-l` | Applies top padding `45px` | `<div class="pad-top-45-l">This element will have a top padding of 45px</div>` | Applies a `padding-top` of `45px` to a `div` element for large devices and above |
| `.pad-top-50-l` | Applies top padding `50px` | `<div class="pad-top-50-l">This element will have a top padding of 50px</div>` | Applies a `padding-top` of `50px` to a `div` element for large devices and above |
| `.pad-top-55-l` | Applies top padding `55px` | `<div class="pad-top-55-l">This element will have a top padding of 55px</div>` | Applies a `padding-top` of `55px` to a `div` element for large devices and above |
| `.pad-top-60-l` | Applies top padding `60px` | `<div class="pad-top-60-l">This element will have a top padding of 60px</div>` | Applies a `padding-top` of `60px` to a `div` element for large devices and above |
| `.pad-bottom-5-l` | Applies bottom padding `5px` | `<div class="pad-bottom-5-l">This element will have a bottom padding of 5px</div>` | Applies a `padding-bottom` of `5px` to a `div` element for large devices and above |
| `.pad-bottom-10-l` | Applies bottom padding `10px` | `<div class="pad-bottom-10-l">This element will have a bottom padding of 10px</div>` | Applies a `padding-bottom` of `10px` to a `div` element for large devices and above |
| `.pad-bottom-15-l` | Applies bottom padding `15px` | `<div class="pad-bottom-15-l">This element will have a bottom padding of 15px</div>` | Applies a `padding-bottom` of `15px` to a `div` element for large devices and above |
| `.pad-bottom-20-l` | Applies bottom padding `20px` | `<div class="pad-bottom-20-l">This element will have a bottom padding of 20px</div>` | Applies a `padding-bottom` of `20px` to a `div` element for large devices and above |
| `.pad-bottom-25-l` | Applies bottom padding `25px` | `<div class="pad-bottom-25-l">This element will have a bottom padding of 25px</div>` | Applies a `padding-bottom` of `25px` to a `div` element for large devices and above |
| `.pad-bottom-30-l` | Applies bottom padding `30px` | `<div class="pad-bottom-30-l">This element will have a bottom padding of 30px</div>` | Applies a `padding-bottom` of `30px` to a `div` element for large devices and above |
| `.pad-bottom-35-l` | Applies bottom padding `35px` | `<div class="pad-bottom-35-l">This element will have a bottom padding of 35px</div>` | Applies a `padding-bottom` of `35px` to a `div` element for large devices and above |
| `.pad-bottom-40-l` | Applies bottom padding `40px` | `<div class="pad-bottom-40-l">This element will have a bottom padding of 40px</div>` | Applies a `padding-bottom` of `40px` to a `div` element for large devices and above |
| `.pad-bottom-45-l` | Applies bottom padding `45px` | `<div class="pad-bottom-45-l">This element will have a bottom padding of 45px</div>` | Applies a `padding-bottom` of `45px` to a `div` element for large devices and above |
| `.pad-bottom-50-l` | Applies bottom padding `50px` | `<div class="pad-bottom-50-l">This element will have a bottom padding of 50px</div>` | Applies a `padding-bottom` of `50px` to a `div` element for large devices and above |
| `.pad-bottom-55-l` | Applies bottom padding `55px` | `<div class="pad-bottom-55-l">This element will have a bottom padding of 55px</div>` | Applies a `padding-bottom` of `55px` to a `div` element for large devices and above |
| `.pad-bottom-60-l` | Applies bottom padding `60px` | `<div class="pad-bottom-60-l">This element will have a bottom padding of 60px</div>` | Applies a `padding-bottom` of `60px` to a `div` element for large devices and above |
| `.pad-5-l` | Applies padding `5px` | `<div class="pad-5-l">This element will have a padding of 5px</div>` | Applies a `padding` of `5px` to a `div` element for large devices and above |
| `.pad-10-l` | Applies padding `10px` | `<div class="pad-10-l">This element will have a padding of 10px</div>` | Applies a `padding` of `10px` to a `div` element for large devices and above |
| `.pad-15-l` | Applies padding `15px` | `<div class="pad-15-l">This element will have a padding of 15px</div>` | Applies a `padding` of `15px` to a `div` element for large devices and above |
| `.pad-20-l` | Applies padding `20px` | `<div class="pad-20-l">This element will have a padding of 20px</div>` | Applies a `padding` of `20px` to a `div` element for large devices and above |
| `.pad-25-l` | Applies padding `25px` | `<div class="pad-25-l">This element will have a padding of 25px</div>` | Applies a `padding` of `25px` to a `div` element for large devices and above |
| `.pad-30-l` | Applies padding `30px` | `<div class="pad-30-l">This element will have a padding of 30px</div>` | Applies a `padding` of `30px` to a `div` element for large devices and above |
| `.pad-35-l` | Applies padding `35px` | `<div class="pad-35-l">This element will have a padding of 35px</div>` | Applies a `padding` of `35px` to a `div` element for large devices and above |
| `.pad-40-l` | Applies padding `40px` | `<div class="pad-40-l">This element will have a padding of 40px</div>` | Applies a `padding` of `40px` to a `div` element for large devices and above |
| `.pad-45-l` | Applies padding `45px` | `<div class="pad-45-l">This element will have a padding of 45px</div>` | Applies a `padding` of `45px` to a `div` element for large devices and above |
| `.pad-50-l` | Applies padding `50px` | `<div class="pad-50-l">This element will have a padding of 50px</div>` | Applies a `padding` of `50px` to a `div` element for large devices and above |
| `.pad-55-l` | Applies padding `55px` | `<div class="pad-55-l">This element will have a padding of 55px</div>` | Applies a `padding` of `55px` to a `div` element for large devices and above |
| `.pad-60-l` | Applies padding `60px` | `<div class="pad-60-l">This element will have a padding of 60px</div>` | Applies a `padding` of `60px` to a `div` element for large devices and above |
| `.no-margin-xl` | Applies margin `0` | `<div class="no-margin-xl">No margin</div>` | Applies a margin of `0` to a `div` element for extra large devices and above |
| `.no-padding-xl` | Applies padding `0` | `<div class="no-padding-xl">No padding</div>` | Applies a padding of `0` to a `div` element for extra large devices and above |
| `.no-float-xl` | Applies float `none` | `<div class="no-float-xl">No float</div>` | Applies a float of `none` to a `div` element for extra large devices and above |
| `.absolute-xl` | Applies position `absolute` | `<div class="absolute-xl">Absolute</div>` | Applies a position of `absolute` to a `div` element for extra large devices and above |
| `.static-xl` | Applies position `static` | `<div class="static-xl">Static</div>` | Applies a position of `static` to a `div` element for extra large devices and above |
| `.fixed-xl` | Applies position `fixed` | `<div class="fixed-xl">Fixed</div>` | Applies a position of `fixed` to a `div` element for extra large devices and above |
| `.none-xl` | Applies display `none` | `<div class="none-xl">You won't see this text</div>` | Applies a display of `none` to a `div` element for extra large devices and above |
| `.block-xl` | Applies display `block` | `<span class="block-xl">This will be a block element</span>` | Applies a display of `block` to a `span` element for extra large devices and above |
| `.inline-block-xl` | Applies display `inline-block` | `<div class="inline-block-xl">This element will be inline-block</div>` | Applies a display of `inline-block` to a `div` element for extra large devices and above |
| `.inline-xl` | Applies display `inline` | `<div class="inline-xl">This element will be inline</div>` | Applies a display of `inline` to a `div` element for extra large devices and above |
| `.flex-xl` | Applies display `flex` | `<div class="flex-xl">This element will be flex</div>` | Applies a display of `flex` to a `div` element for extra large devices and above |
| `.flex-row-xl` | Applies flex direction `row` | `<div class="flex-xl flex-row-xl">Flex direction will be row</div>` | Applies a flex direction of `flex-row-xl` to a `div` element for extra large devices and above |
| `.flex-row-reverse-xl` | Applies flex direction `row-reverse-xl` | `<div class="flex-xl flex-row-reverse-xl">Flex direction will be row in reverse</div>` | Applies a flex direction of `flex-row-reverse-xl` to a `div` element for extra large devices and above |
| `.flex-column-xl` | Applies flex direction `column` | `<div class="flex-xl flex-column-xl">Flex direction will be column</div>` | Applies a flex direction of `flex-column-xl` to a `div` element for extra large devices and above |
| `.flex-column-reverse-xl` | Applies flex direction `column-reverse-xl` | `<div class="flex-xl flex-column-reverse-xl">Flex direction will be column reverse</div>` | Applies a flex direction of `flex-column-reverse-xl` to a `div` element for extra large devices and above |
| `.flex-space-around-xl` | Applies spacing around elements within a flex container | `<div class="flex-m flex-space-around-xl">Flex space around is applied</div>` | Applies spacing around elements within a `div` element for extra large devices and above |
| `.flex-space-between-xl` | Applies spacing between elements within a flex container | `<div class="flex-m flex-space-between-xl">Flex space between is applied</div>` | Applies spacing between elements within a `div` element for extra large devices and above |
| `.flex-start-xl` | Applies alignment of a flex item to the start | `<div class="flex-m flex-start-xl">This item will be aligned to the start</div>` | Aligns element within a `div` element to the start for extra large devices and above |
| `.flex-center-xl` | Applies alignment of a flex item to the center | `<div class="flex-m flex-center-xl">This item will be aligned to the center</div>` | Aligns element within a `div` element to the center for extra large devices and above |
| `.flex-end-xl` | Applies alignment of flex item to the end | `<div class="flex-m flex-end-xl">This item will be aligned to the end</div>` | Aligns element within a `div` element to the end for extra large devices and above |
| `.flex-wrap-xl` | Applies flex items to wrap within a flex container | `<div class="flex-m flex-wrap-xl">Flex items will wrap within a flex container</div>` | `div` elements will wrap within a flex container for extra large devices and above |
| `.flex-no-wrap-xl` | Applies flex items to not wrap within a flex container | `<div class="flex-m flex-no-wrap-xl">Flex items will not wrap within a flex container</div>` | `div` elements will not wrap within a flex container for extra large devices and above |
| `.left-xl` | Applies float `left` | `<div class="left-xl">This element will float left</div>` | Applies a float `left` to a `div` element for extra large devices and above |
| `.right-xl` | Applies float `right` | `<div class="right-xl">This element will float right</div>` | Applies a float `right` to a `div` element for extra large devices and above |
| `.pad-top-5-xl` | Applies top padding `5px` | `<div class="pad-top-5-xl">This element will have a top padding of 5px</div>` | Applies a `padding-top` of `5px` to a `div` element for extra large devices and above |
| `.pad-top-10-xl` | Applies top padding `10px` | `<div class="pad-top-10-xl">This element will have a top padding of 10px</div>` | Applies a `padding-top` of `10px` to a `div` element for extra large devices and above |
| `.pad-top-15-xl` | Applies top padding `15px` | `<div class="pad-top-15-xl">This element will have a top padding of 15px</div>` | Applies a `padding-top` of `15px` to a `div` element for extra large devices and above |
| `.pad-top-20-xl` | Applies top padding `20px` | `<div class="pad-top-20-xl">This element will have a top padding of 20px</div>` | Applies a `padding-top` of `20px` to a `div` element for extra large devices and above |
| `.pad-top-25-xl` | Applies top padding `25px` | `<div class="pad-top-25-xl">This element will have a top padding of 25px</div>` | Applies a `padding-top` of `25px` to a `div` element for extra large devices and above |
| `.pad-top-30-xl` | Applies top padding `30px` | `<div class="pad-top-30-xl">This element will have a top padding of 30px</div>` | Applies a `padding-top` of `30px` to a `div` element for extra large devices and above |
| `.pad-top-35-xl` | Applies top padding `35px` | `<div class="pad-top-35-xl">This element will have a top padding of 35px</div>` | Applies a `padding-top` of `35px` to a `div` element for extra large devices and above |
| `.pad-top-40-xl` | Applies top padding `40px` | `<div class="pad-top-40-xl">This element will have a top padding of 40px</div>` | Applies a `padding-top` of `40px` to a `div` element for extra large devices and above |
| `.pad-top-45-xl` | Applies top padding `45px` | `<div class="pad-top-45-xl">This element will have a top padding of 45px</div>` | Applies a `padding-top` of `45px` to a `div` element for extra large devices and above |
| `.pad-top-50-xl` | Applies top padding `50px` | `<div class="pad-top-50-xl">This element will have a top padding of 50px</div>` | Applies a `padding-top` of `50px` to a `div` element for extra large devices and above |
| `.pad-top-55-xl` | Applies top padding `55px` | `<div class="pad-top-55-xl">This element will have a top padding of 55px</div>` | Applies a `padding-top` of `55px` to a `div` element for extra large devices and above |
| `.pad-top-60-xl` | Applies top padding `60px` | `<div class="pad-top-60-xl">This element will have a top padding of 60px</div>` | Applies a `padding-top` of `60px` to a `div` element for extra large devices and above |
| `.pad-bottom-5-xl` | Applies bottom padding `5px` | `<div class="pad-bottom-5-xl">This element will have a bottom padding of 5px</div>` | Applies a `padding-bottom` of `5px` to a `div` element for extra large devices and above |
| `.pad-bottom-10-xl` | Applies bottom padding `10px` | `<div class="pad-bottom-10-xl">This element will have a bottom padding of 10px</div>` | Applies a `padding-bottom` of `10px` to a `div` element for extra large devices and above |
| `.pad-bottom-15-xl` | Applies bottom padding `15px` | `<div class="pad-bottom-15-xl">This element will have a bottom padding of 15px</div>` | Applies a `padding-bottom` of `15px` to a `div` element for extra large devices and above |
| `.pad-bottom-20-xl` | Applies bottom padding `20px` | `<div class="pad-bottom-20-xl">This element will have a bottom padding of 20px</div>` | Applies a `padding-bottom` of `20px` to a `div` element for extra large devices and above |
| `.pad-bottom-25-xl` | Applies bottom padding `25px` | `<div class="pad-bottom-25-xl">This element will have a bottom padding of 25px</div>` | Applies a `padding-bottom` of `25px` to a `div` element for extra large devices and above |
| `.pad-bottom-30-xl` | Applies bottom padding `30px` | `<div class="pad-bottom-30-xl">This element will have a bottom padding of 30px</div>` | Applies a `padding-bottom` of `30px` to a `div` element for extra large devices and above |
| `.pad-bottom-35-xl` | Applies bottom padding `35px` | `<div class="pad-bottom-35-xl">This element will have a bottom padding of 35px</div>` | Applies a `padding-bottom` of `35px` to a `div` element for extra large devices and above |
| `.pad-bottom-40-xl` | Applies bottom padding `40px` | `<div class="pad-bottom-40-xl">This element will have a bottom padding of 40px</div>` | Applies a `padding-bottom` of `40px` to a `div` element for extra large devices and above |
| `.pad-bottom-45-xl` | Applies bottom padding `45px` | `<div class="pad-bottom-45-xl">This element will have a bottom padding of 45px</div>` | Applies a `padding-bottom` of `45px` to a `div` element for extra large devices and above |
| `.pad-bottom-50-xl` | Applies bottom padding `50px` | `<div class="pad-bottom-50-xl">This element will have a bottom padding of 50px</div>` | Applies a `padding-bottom` of `50px` to a `div` element for extra large devices and above |
| `.pad-bottom-55-xl` | Applies bottom padding `55px` | `<div class="pad-bottom-55-xl">This element will have a bottom padding of 55px</div>` | Applies a `padding-bottom` of `55px` to a `div` element for extra large devices and above |
| `.pad-bottom-60-xl` | Applies bottom padding `60px` | `<div class="pad-bottom-60-xl">This element will have a bottom padding of 60px</div>` | Applies a `padding-bottom` of `60px` to a `div` element for extra large devices and above |
| `.pad-5-xl` | Applies padding `5px` | `<div class="pad-5-xl">This element will have a padding of 5px</div>` | Applies a `padding` of `5px` to a `div` element for extra large devices and above |
| `.pad-10-xl` | Applies padding `10px` | `<div class="pad-10-xl">This element will have a padding of 10px</div>` | Applies a `padding` of `10px` to a `div` element for extra large devices and above |
| `.pad-15-xl` | Applies padding `15px` | `<div class="pad-15-xl">This element will have a padding of 15px</div>` | Applies a `padding` of `15px` to a `div` element for extra large devices and above |
| `.pad-20-xl` | Applies padding `20px` | `<div class="pad-20-xl">This element will have a padding of 20px</div>` | Applies a `padding` of `20px` to a `div` element for extra large devices and above |
| `.pad-25-xl` | Applies padding `25px` | `<div class="pad-25-xl">This element will have a padding of 25px</div>` | Applies a `padding` of `25px` to a `div` element for extra large devices and above |
| `.pad-30-xl` | Applies padding `30px` | `<div class="pad-30-xl">This element will have a padding of 30px</div>` | Applies a `padding` of `30px` to a `div` element for extra large devices and above |
| `.pad-35-xl` | Applies padding `35px` | `<div class="pad-35-xl">This element will have a padding of 35px</div>` | Applies a `padding` of `35px` to a `div` element for extra large devices and above |
| `.pad-40-xl` | Applies padding `40px` | `<div class="pad-40-xl">This element will have a padding of 40px</div>` | Applies a `padding` of `40px` to a `div` element for extra large devices and above |
| `.pad-45-xl` | Applies padding `45px` | `<div class="pad-45-xl">This element will have a padding of 45px</div>` | Applies a `padding` of `45px` to a `div` element for extra large devices and above |
| `.pad-50-xl` | Applies padding `50px` | `<div class="pad-50-xl">This element will have a padding of 50px</div>` | Applies a `padding` of `50px` to a `div` element for extra large devices and above |
| `.pad-55-xl` | Applies padding `55px` | `<div class="pad-55-xl">This element will have a padding of 55px</div>` | Applies a `padding` of `55px` to a `div` element for extra large devices and above |
| `.pad-60-xl` | Applies padding `60px` | `<div class="pad-60-xl">This element will have a padding of 60px</div>` | Applies a `padding` of `60px` to a `div` element for extra large devices and above |

* * *

## Demo

[View page example](https://rawgit.com/getbase/layout-helpers/master/index.html) with the layout helpers stylesheet applied.

* * *

## Support

* IE10+ and all other modern browsers.
* Please specify browsers you need to support in `package.json` according to [browserslist docs](https://github.com/ai/browserslist#queries).

* * *

## Authors

#### Matthew Hartman

* [https://twitter.com/matthewhartmans](https://twitter.com/matthewhartmans)
* [https://github.com/matthewhartman](https://github.com/matthewhartman)

* * *

## License

Code released under the [MIT Open Source](https://opensource.org/licenses/MIT) license.