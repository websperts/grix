# Grix

> A basic flexbox-based grid

[![Build Status](https://travis-ci.org/websperts/grix.svg)](https://travis-ci.org/websperts/grix)

<img src="https://cdn.rawgit.com/websperts/grix/master/logo.svg" alt="Grix" width="150" height="150">

- There is a default build (autoprefixed + minified) included in this repository (`dist/grix.css`)
- All customizable SCSS sources are included in this repository as well (`src`)
- All SCSS variables and mixins are namespaced using the prefix `grix`
- Everything is a SCSS mixin (allowing you to re-use grid styles within your own style definitions)

## Download

To get going with Grix you can:

- [Download the latest release](https://github.com/websperts/grix/archive/master.zip)
- [Install with npm](https://www.npmjs.com/): `npm install grix`
- [Install with Bower](https://bower.io/): `bower install grix`

## Usage

Depending on your needs you may include the default build within your Web site or Web application. If you’re using a build tool (like [Grunt](http://gruntjs.com/) or [gulp](http://gulpjs.com/)), you may concatenate Grix and your own style definitions and minify the whole thing into a single file in order to reduce the amount of requests.

However, in most cases you may want to customize Grix to your design specifications or re-use its grid styles within your own style definitions. In order to do so, you can overwrite any of the [variables](https://github.com/websperts/grix/blob/master/src/_variables.scss) used by Grix and include any [mixin](https://github.com/websperts/grix/blob/master/src/_mixins.scss).

## Changelog

* 0.0.1
  * Initial version

## TODO

- Documentation
- Tests

## License

Copyright (c) 2016 [websperts](http://websperts.com/)  
Licensed under the MIT license.

See LICENSE for more info.
