commonjs-xml2js
===========

Description
-----------
Simple XML to JavaScript object converter. This fork is modified to run in any CommonJS environment (not just Node). Uses [sax-js](http://github.com/isaacs/sax-js/). 

Note:  If you're looking for a full DOM parser, you probably want [JSDom](http://github.com/tmpvar/jsdom).

Simple usage
-----------

    var xml2js = require('./xml2js');

    var parser = new xml2js.Parser(function(data) {
      console.log(JSON.stringify(data));
    });

    parser.parseString("<some xml>")



