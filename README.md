# util.css

[![Version Badge][version-image]][project-url]
[![License][license-image]][license-url]
[![Build Status][build-image]][build-url]

> A collection of unopinionated and modular CSS utility classes.

## Install

Download [util.css](https://github.com/ryanmorr/util.css/raw/master/dist/util.min.css) directly or install via NPM:

```sh
npm install @ryanmorr/util.css
```

## Features

The library is composed of dozens of utility classes written in raw CSS (not a preprocessor such as Sass or Less). Unlike Atomic CSS, util.css does not contain (with a few exceptions) single-purpose units of styles, such as `.text-center {text-align: center}`. Instead, it focuses on common helpers and fixes that add functionality beyond simple shortcuts. Theses classes are unopinionated and modular declarations, making them applicable to and easily adopted into any project.

The following is a complete list of all the classes available, grouped into categories. **Note:** For class names, the word "center" refers to horizontal alignment and the word "middle" refers to vertical alignment.

### Layout

Class | Description
----- | ------------
`clearfix` | Allows an element to stretch to accommodate floating elements
`border-box` | Make the box model of an element and its descendants include the padding and border within the defined width and height of an element
`content-box` | Make the box model of an element and its descendants add the padding and border to the defined width and height of an element
`responsive-width` | Sets a maximum width relative to the parent and auto scales the height
`responsive-height` | Sets a maximum height relative to the parent and auto scales the width (parent element must have a fixed height)
`flex-middle-center` | Should align children in the middle-center of the element using flexbox
`grid-middle-center` | Should align children in the middle-center of the element using grid
`flex-inline-middle-center` | Should align children in the middle-center of the element using inline flexbox
`flex-horizontal-stack` | Should stack children horizontally using flexbox
`flex-vertical-stack` | Should stack children vertically using flexbox

### Visibility

Class | Description
----- | ------------
`hidden` | Hide an element visually and from screen readers
`invisible` | Hide an element visually and from screen readers, but maintain layout
`transparent` | Hide an element visually, but still allow it to be accessible to screen readers, maintain layout, and allow pointer events
`offscreen` | Hide an element visually, but maintain its layout offscreen so that its width and height and still be accurately measured
`hidden-accessible` | Hide an element visually, but still allow it to be accessible to screen readers
`hidden-accessible-focusable` | Like `hidden-accessible`, but will be visible when it or a child element receives focus
`hidden-scrollbars` | Hide scrollbars on an element, while still allowing it to be scrollable
`hidden-touch` | Make an element hidden on touch devices
`hidden-non-touch` | Make an element hidden on non-touch devices

### Alignment

Class | Description
----- | ------------
`align-left` | Float an element left
`align-right` | Float an element right
`align-center` | Center an element horizontally
`align-middle` | Center an element vertically
`align-middle-center` | Center an element horizontally and vertically
`align-abs-top-left` | Align an absolutely positioned element to the top-left of its container
`align-abs-top-center` | Align an absolutely positioned element to the top-center of its container
`align-abs-top-right` | Align an absolutely positioned element to the top-right of its container
`align-abs-middle-left` | Align an absolutely positioned element to the middle-left of its container
`align-abs-middle-center` | Align an absolutely positioned element to the middle-center of its container
`align-abs-middle-right` | Align an absolutely positioned element to the middle-right of its container
`align-abs-bottom-left` | Align an absolutely positioned element to the bottom-left of its container
`align-abs-bottom-center` | Align an absolutely positioned element to the bottom-center of its container
`align-abs-bottom-right` | Align an absolutely positioned element to the bottom-right of its container
`align-self-top-left` | Align an element to the top-left within a flexbox or grid container
`align-self-top-center` | Align an element to the top-center within a flexbox or grid container
`align-self-top-right` | Align an element to the top-right within a flexbox or grid container
`align-self-middle-left` | Align an element to the middle-left within a flexbox or grid container
`align-self-middle-center` | Align an element to the middle-center within a flexbox or grid container
`align-self-middle-right` | Align an element to the middle-right within a flexbox or grid container
`align-self-bottom-left` | Align an element to the bottom-left within a flexbox or grid container
`align-self-bottom-center` | Align an element to the bottom-center within a flexbox or grid container
`align-self-bottom-right` | Align an element to the bottom-right within a flexbox or grid container

### Typography

Class | Description
----- | ------------
`antialiased` | Render text using grayscale antialiasing
`subpixel-antialiased` | Render text using subpixel antialiasing
`text-truncate` | Prevent text from wrapping and truncate with an ellipsis
`text-clip` | Prevent text from wrapping and truncate with a hard clip
`text-break` | Break words when their length exceeds the width of their container

### Media

Class | Description
----- | ------------
`hide-text` | Image replacement to provide a caption to an image that is only available to web crawlers and screen readers
`image-responsive` | Make an image responsive while maintaining aspect ratio
`image-contain` | Fit the image within the container while preserving its aspect ratio
`image-cover` | Fill the container with the image while preserving its aspect ratio

### User Experience

Class | Description
----- | ------------
`unselectable` | Prevent text selection
`disabled` | Prevent user interaction of any kind
`scroll-horizontal` | Make an element display only horizontal scrollbars
`scroll-vertical` | Make an element display only vertical scrollbars

## License

This project is dedicated to the public domain as described by the [Unlicense](http://unlicense.org/).

[project-url]: https://github.com/ryanmorr/util.css
[version-image]: https://img.shields.io/github/package-json/v/ryanmorr/util.css?color=blue&style=flat-square
[build-url]: https://travis-ci.com/github/ryanmorr/util.css
[build-image]: https://img.shields.io/travis/com/ryanmorr/util.css?style=flat-square
[license-image]: https://img.shields.io/github/license/ryanmorr/util.css?color=blue&style=flat-square
[license-url]: UNLICENSE