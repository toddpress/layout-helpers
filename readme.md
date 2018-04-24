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

Base Layout Helpers contains styles for resetting margins, resetting paddings, resetting floats, setting position types and flex helpers for all breakpoints.

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

Base Layout Helpers includes styles for resetting margins, resetting paddings, resetting floats, setting position types and flex helpers for all breakpoints.

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
| `.flex-top` | Applies vertical alignment of a flex item to the top | `<div class="flex flex-top">Items inside will be vertically aligned to the top</div>` | Aligns elements within a `div` element to the top for all breakpoints |
| `.flex-middle` | Applies vertical alignment of a flex item to the middle | `<div class="flex flex-middle">Items inside will be vertically aligned to the middle</div>` | Aligns elements within a `div` element to the middle for all breakpoints |
| `.flex-bottom` | Applies vertical alignment of a flex item to the bottom | `<div class="flex flex-bottom">Items inside will be vertically aligned to the bottom</div>` | Aligns elements within a `div` element to the bottom for all breakpoints |
| `.flex-wrap` | Applies flex items to wrap within a flex container | `<div class="flex flex-wrap">Flex items will wrap within a flex container</div>` | `div` elements will wrap within a flex container for all breakpoints |
| `.flex-no-wrap` | Applies flex items to not wrap within a flex container | `<div class="flex flex-no-wrap">Flex items will not wrap within a flex container</div>` | `div` elements will not wrap within a flex container for all breakpoints |
| `.left` | Applies float `left` | `<div class="left">This element will float left</div>` | Applies a float `left` to a `div` element for all breakpoints |
| `.right` | Applies float `right` | `<div class="right">This element will float right</div>` | Applies a float `right` to a `div` element for all breakpoints |
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
| `.flex-top-m` | Applies vertical alignment of a flex item to the top | `<div class="flex flex-top-m">Items inside will be vertically aligned to the top</div>` | Aligns elements within a `div` element to the top for medium devices and above |
| `.flex-middle-m` | Applies vertical alignment of a flex item to the middle | `<div class="flex flex-middle-m">Items inside will be vertically aligned to the middle</div>` | Aligns elements within a `div` element to the middle for medium devices and above |
| `.flex-bottom-m` | Applies vertical alignment of a flex item to the bottom | `<div class="flex flex-bottom-m">Items inside will be vertically aligned to the bottom</div>` | Aligns elements within a `div` element to the bottom for medium devices and above |
| `.flex-wrap-m` | Applies flex items to wrap within a flex container | `<div class="flex-m flex-wrap-m">Flex items will wrap within a flex container</div>` | `div` elements will wrap within a flex container for medium devices and above |
| `.flex-no-wrap-m` | Applies flex items to not wrap within a flex container | `<div class="flex-m flex-no-wrap-m">Flex items will not wrap within a flex container</div>` | `div` elements will not wrap within a flex container for medium devices and above |
| `.left-m` | Applies float `left` | `<div class="left-m">This element will float left</div>` | Applies a float `left` to a `div` element for medium devices and above |
| `.right-m` | Applies float `right` | `<div class="right-m">This element will float right</div>` | Applies a float `right` to a `div` element for medium devices and above |
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
| `.flex-top-l` | Applies vertical alignment of a flex item to the top | `<div class="flex flex-top-l">Items inside will be vertically aligned to the top</div>` | Aligns elements within a `div` element to the top for large devices and above |
| `.flex-middle-l` | Applies vertical alignment of a flex item to the middle | `<div class="flex flex-middle-l">Items inside will be vertically aligned to the middle</div>` | Aligns elements within a `div` element to the middle for large devices and above |
| `.flex-bottom-l` | Applies vertical alignment of a flex item to the bottom | `<div class="flex flex-bottom-l">Items inside will be vertically aligned to the bottom</div>` | Aligns elements within a `div` element to the bottom for large devices and above |
| `.flex-wrap-l` | Applies flex items to wrap within a flex container | `<div class="flex-m flex-wrap-l">Flex items will wrap within a flex container</div>` | `div` elements will wrap within a flex container for large devices and above |
| `.flex-no-wrap-l` | Applies flex items to not wrap within a flex container | `<div class="flex-m flex-no-wrap-l">Flex items will not wrap within a flex container</div>` | `div` elements will not wrap within a flex container for large devices and above |
| `.left-l` | Applies float `left` | `<div class="left-l">This element will float left</div>` | Applies a float `left` to a `div` element for large devices and above |
| `.right-l` | Applies float `right` | `<div class="right-l">This element will float right</div>` | Applies a float `right` to a `div` element for large devices and above |
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
| `.flex-top-xl` | Applies vertical alignment of a flex item to the top | `<div class="flex flex-top-xl">Items inside will be vertically aligned to the top</div>` | Aligns elements within a `div` element to the top for extra large devices and above |
| `.flex-middle-xl` | Applies vertical alignment of a flex item to the middle | `<div class="flex flex-middle-xl">Items inside will be vertically aligned to the middle</div>` | Aligns elements within a `div` element to the middle for extra large devices and above |
| `.flex-bottom-xl` | Applies vertical alignment of a flex item to the bottom | `<div class="flex flex-bottom-xl">Items inside will be vertically aligned to the bottom</div>` | Aligns elements within a `div` element to the bottom for extra large devices and above |
| `.flex-wrap-xl` | Applies flex items to wrap within a flex container | `<div class="flex-m flex-wrap-xl">Flex items will wrap within a flex container</div>` | `div` elements will wrap within a flex container for extra large devices and above |
| `.flex-no-wrap-xl` | Applies flex items to not wrap within a flex container | `<div class="flex-m flex-no-wrap-xl">Flex items will not wrap within a flex container</div>` | `div` elements will not wrap within a flex container for extra large devices and above |
| `.left-xl` | Applies float `left` | `<div class="left-xl">This element will float left</div>` | Applies a float `left` to a `div` element for extra large devices and above |
| `.right-xl` | Applies float `right` | `<div class="right-xl">This element will float right</div>` | Applies a float `right` to a `div` element for extra large devices and above |

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