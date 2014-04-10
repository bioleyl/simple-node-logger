simple-node-logger
==================

A very simple multi-level logger for console and file inspired by Aaron Quint's [quirkey node-logger](http://github.com/quirkey/node-logger).  This logger is suited for simple command line type projects that may or may not go into production.  For a more compete production logger see the winson project.

- five levels: debug, info, warn, error and fatal levels
- default format: Level [ time ] message [, message, object, etc ]
- write to console, file or both

How to use
===
var log = require('simple-node-logger').createLogger();

or

var log = require('simple-node-logger).createLogger('project.log');

The first use will simply log to the console.  The second will log to the console and to the project.log file.

Default Format
===
The default format is LEVEL [ time ] message


License
===
Apache 2.0

- - -
<p><small><em>version 2014.04.09-21016</em></small></p>
