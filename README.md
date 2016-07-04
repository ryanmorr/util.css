# util.css

> A collection of project agnostic, semantic, and modular CSS utility classes.

## Features

The library is composed of over 70 utility classes written in raw CSS (not a preprocessor such as Sass or Less). All the utilities are grouped into the following categories:

* [Layout](#layout)
* [Flexbox](#flexbox)
* [Visibility](#visibility)
* [Positioning](#positioning)
* [Text](#text)
* [Images](#images)
* [Transitions](#transitions)
* [State](#state)
* [Interaction](#interaction)
* [User Interface](#user-interface)

#### Layout

Name                | Description
------------------- | --------------------------------------------------------------------------------------------------------------------
`clearfix`          | Allows an element to stretch to accommodate floating elements.
`pull-left`         | Float an element left.
`pull-right`        | Float an element right.
`responsive-width`  | Sets a maximum width relative to the parent and auto scales the height.
`responsive-height` | Sets a maximum height relative to the parent and auto scales the widt (parent element must have a fixed height).
`border-box`        | Reset the box model so that it doesn't include the padding and border as part of the width and height of the element.

#### Flexbox

Name                          | Description
----------------------------- | --------------------------------------------------------------------------------------------------------
`flex`                        | Block element that lays out its content according to flexbox.
`inline-flex`                 | Inline element that lays out its content according to flexbox.
`flex-align-top`              | Place an item to the top of the container.
`flex-align-middle`           | Place an item to the bottom of the container.
`flex-align-bottom`           | Place an item to the bottom of the container.
`flex-align-left`             | Pack items toward the start line.
`flex-align-center`           | Items are centered along the line.
`flex-align-right`            | Pack items toward the end line.
`flex-align-justify`          | Items are evenly distributed on the line; first item is on the start line, last item on the end line.
`flex-align-even`             | Items are evenly distributed on the line with equal space between them.
`flex-align-lines-top`        | Lines are packed to the top of the container.
`flex-align-lines-middle`     | Lines are packed to the middle of the container.
`flex-align-lines-bottom`     | Lines are packed to the bottom of the container.
`flex-align-lines-justify`    | Lines are evenly distributed; the first line is at the top of the container, the last line is at the end.
`flex-align-lines-even`       | Lines are evenly distributed with equal space between them.
`flex-row`                    | Items are stacked horizontally, side-by-side.
`flex-col`                    | Items are stacked vertically, top-to-bottom.
`flex-nowrap`                 | Force items to be laid out on a single line.
`flex-wrap`                   | Allow items to break into multiple lines.

#### Visibility

Name                  | Description
--------------------- | --------------------------------------------------------------------------------------------------------------------------
`show`                | Show an element.
`hide`                | Hide an element visually and from screen readers.
`invisible`           | Hide an element visually and from screen readers, but maintain layout.
`transparent`         | Hide an element visually, but still allow it to be accessible to screen readers, maintain layout, and allow pointer events.
`hidden-accessible`   | Hide an element visually, but still allow it to be accessible to screen readers.
`focusable`           | Allows a `hidden-accessible` element to be focusable when navigated to via the keyboard.
`hidden-measurable`   | Hide an element visually, but maintain its layout offscreen so that its width and height and still be accurately measured.
`visible-extra-small` | Make an element visible only on extra small screens (less than 767px).
`hidden-extra-small`  | Make an element hidden only on extra small screens (less than 767px).
`visible-small`       | Make an element visible only on small screens (768px to 991px).
`hidden-small`        | Make an element hidden only on small screens (768px to 991px).
`visible-medium`      | Make an element visible only on medium-sized screens (992px to 1199px).
`hidden-medium`       | Make an element hidden only on medium-sized screens (992px to 1199px).
`visible-large`       | Make an element visible only on large screens (1200px and up).
`hidden-large`        | Make an element hidden only on large screens (1200px and up).
`visible-high-res`    | Make an element visible only on high resolution devices.
`hidden-high-res`     | Make an element hidden only on high resolution devices.

#### Positioning

Name                | Description
------------------- | -------------------------------------------------------------------------------------------------------
`center`            | Center an element horizontally (requires width).
 `middle`           | Center an element vertically.
`middle-center`     | Center an element horizontally and vertically
`abs-top-left`      | Align an absolutely positioned element to the top-left of its container.
`abs-top-center`    | Align an absolutely positioned element to the top-center of its container (requires width).
`abs-top-right`     | Align an absolutely positioned element to the top-right of its container.
`abs-middle-left`   | Align an absolutely positioned element to the middle-left of its container (requires height).
`abs-middle-center` | Align an absolutely positioned element to the middle-center of its container (requires width & height).
`abs-middle-right`  | Align an absolutely positioned element to the middle-right of its container (requires height).
`abs-bottom-left`   | Align an absolutely positioned element to the bottom-left of its container.
`abs-bottom-center` | Align an absolutely positioned element to the bottom-center of its container (requires width).
`abs-bottom-right`  | Align an absolutely positioned element to the bottom-right of its container.

#### Text

Name            | Description
--------------- | ---------------------------------------------------------------------
`antialiased`   | Enable antialiasing for a smoother font.
`kern`          | Enable font kerning for optimal character spacing.
`text-truncate` | Prevent text from wrapping and truncate with an ellipsis.
`text-break`    | Break strings when their length exceeds the width of their container.

#### Images

Name             | Description
---------------- | -------------------------------------------------------------------------------------------------------------
`hide-text`      | Image replacement to provide a caption to an image that is only available to web crawlers and screen readers.
`img-responsive` | Make an image responsive while maintaining aspect ratio.

#### Transitions

Name          | Description
------------- | -----------------------------------------------------------------------------------------------------------------
`transition`  | Allow an element to transition whenever a property changes.
`fadable`     | Provides a fade in/out effect to an element.
`collapsible` | Provides a collapse/expand effect to an element.
`accelerated` | Create a new stacking context (composite layer) in order to invoke hardware acceleration for smoother animations.

#### State

Name         | Description
------------ | ------------------------------------------------------------------
`disabled`   | Indicate than an element is disabled and prevent user interaction.
`loading`    | Indicate that an element is loading.
`help`       | Indicate that an element is a helpful resource.
`restricted` | Indicate that an element is restricted from interaction.

#### Interaction

Name                    | Description
----------------------- | -----------------------------------------------------------------------------------
`actionable`            | Indicate that an element is actionable (clickable).
`draggable`             | Add drag characteristics to an element.
`unselectable`          | Prevent text selection.
`unclickable`           | Prevent user interaction.
`prevent-callout`       | Prevent the callout menu appearing in iOS Safari when the user performs tap & hold.
`resizable`             | Make an element resizable on both axes.
`scrollable-vertical`   | Make an element vertically scrollable
`scrollable-horizontal` | Make an element horizontally scrollable

#### User Interface

Name        | Description
----------- | ---------------------------------------------------------------------------------------------------------------------------------------------
`container` | All-purpose wrapper for UI elements that allow child elements to position absolute relative to the container and automatically clears floats.
`overlay`   | General fixed overlay UI element

## Installation

Download the [development](http://github.com/ryanmorr/util.css/raw/master/util.css) or [minified](http://github.com/ryanmorr/util.css/raw/master/util.min.css) version, or install it in one of the following ways:

``` sh
npm install ryanmorr/util.css

bower install ryanmorr/util.css
```

## License

This project is dedicated to the public domain as described by the [Unlicense](http://unlicense.org/).