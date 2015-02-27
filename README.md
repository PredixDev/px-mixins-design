# Mixins

The Predix Experience Mixins module is an extension of the inuitcss [Mixins](https://github.com/inuitcss/tools.mixins) Module and contains mixins for use across other Px modules.

## Dependency

Px's Mixins module depends on one other inuitcss module:

* [tools-mixins](https://github.com/inuitcss/tools.mixins)

## Upstream dependency

The Mixins module is also an upstream dependency in this meta kit:

* [px-starter-kit-design](https://github.sw.ge.com/pxc/px-starter-kit-design)

## Installation

Install this module and its dependency using bower:

    bower install --save https://github.sw.ge.com/pxc/px-mixins-design.git

Once installed, `@import` into your project's Sass file in its Tools layer:

    @import "px-mixins-design/sass/tools.mixins";

## Mixins provided

The following Sass mixins are provided:

* `font-face`: Generates webfont-friendly font families (can take the following parameters--`$font-family`, `$file-path`, `$weight`, and `$style`)
