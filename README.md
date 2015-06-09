# Mixins

The Predix Experience Mixins module is a fork of the inuitcss [Mixins](https://github.com/inuitcss/tools.mixins) Module and contains mixins for use across other Px modules.

## Dependency

Px's Mixins module depends on one other PXd module:

* [px-defaults-design](https://github.build.ge.com/PXd/px-defaults-design)

## Upstream dependency

The Mixins module is also an upstream dependency in this meta kit:

* [px-starter-kit-design](https://github.build.ge.com/PXd/px-starter-kit-design)

## Installation

Install this module and its dependency using bower:

    bower install --save https://github.build.ge.com/PXd/px-mixins-design.git

Once installed, `@import` into your project's Sass file in its Tools layer:

    @import "../px-mixins-design/tools.mixins";

See [px-getting-started](https://github.build.ge.com/PXd/px-getting-started#a-note-about-relative-import-paths) for an explanation of the `../`

## Mixins provided

The following Sass mixins are provided:

* `inuit-font-size`: Generates rem sized fonts with line height from pixel sizes (can take the following parameters--`$inuit-font-size` and `$inuit-line-height`)
* `border-right-left`: Swaps horizontal border placement if HTML direction switched to `dir=rtl` (can take the following parameters--`$inuit-border-position`, `$inuit-border-color`, `$inuit-border-width`, and `$inuit-border-style`)
* `font-face`: Generates webfont-friendly font families (can take the following parameters--`$font-family`, `$file-path`, `$weight`, and `$style`)
