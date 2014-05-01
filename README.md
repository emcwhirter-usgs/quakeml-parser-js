quakeml-parser-js
=================

Quakeml Parser for JavaScript

Getting Started
---------------

This parser is designed to support other projects. It is published in npm.

1. Install the package from npm.
  `npm install --save-dev quakeml-parser-js`

1. Configure the shim for the application and test environments in the
`index.js` files. Should look like something like this in your path object:
  `quakeml: 'quakeml-parser-js/src/quakeml'`

1. Import quakeml in the files where you want to use it. Should be something
like this at the top of the file:
  `define(['quakeml/Quakeml'], function (Quakeml) {});`
