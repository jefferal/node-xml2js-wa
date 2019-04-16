node-xml2js-wa
===========

Ever had the urge to parse XML? And wanted to access the data in some sane,
easy way? Don't want to compile a C parser, for whatever reason? Then xml2js-wa is
what you're looking for!

Description
===========

Simple XML to JavaScript object converter. It supports bi-directional conversion.
Uses [sax-js](https://github.com/isaacs/sax-js/) and
[xmlbuilder-js](https://github.com/oozcitak/xmlbuilder-js/).

Note: If you're looking for a full DOM parser, you probably want
[JSDom](https://github.com/tmpvar/jsdom).

Installation
============

Simplest way to install `xml2js-wa` is to use [npm](http://npmjs.org), just `npm
install xml2js-wa` which will download xml2js-wa and all dependencies.

### Note

This repository has been cloned from the original repository, based on version 0.0.4:

This workaround has been implemented to fix a version of the dependency
`xmlbuilder` to make it compatible with old versions of node.