# px-mixins-design

The Predix UI Mixins module is a fork of the inuitcss [Mixins](https://github.com/inuitcss/tools.mixins) Module and contains mixins for use across other Predix UI modules.

## Dependencies

The `px-mixins-design` module depends on one other Px module:

* [px-defaults-design](https://github.com/PredixDev/px-defaults-design)

## Installation

Install this module and its dependencies using bower:

    bower install --save px-mixins-design

Once installed, `@import` into your project's Sass file in its **Tools** layer:

    @import "px-mixins-design/_tools.mixins.scss";

## Mixins provided

The following Sass mixins are provided:

* `inuit-font-size`: Generates rem sized fonts with line height from pixel sizes (can take the following parameters--`$inuit-font-size` and `$inuit-line-height`)
* `border-right-left`: Swaps horizontal border placement if HTML direction switched to `dir=rtl` (can take the following parameters--`$inuit-border-position`, `$inuit-border-color`, `$inuit-border-width`, and `$inuit-border-style`)
* `font-face`: Generates webfont-friendly font families (can take the following parameters--`$font-family`, `$file-path`, `$weight`, and `$style`)

View the full API [here](http://predixdev.github.io/px-mixins-design/sassdoc/).
