# Timemap
## Simple Date formatter for javascript

A simple module for formatting dates in javascript should be familiar to
PHP date formatting

## Usage

    <script src="timemap.js"></script> 

or with Node.js just require it (depends on how it's installed)

from cloned repo probably something like

    var Timemap = require('./src/timemap');

or if isntalled via NPM

    var Timemap = require('timemap');

    var today = new Timemap(new Date());
    today.format('Y m d');
    var displayDate = today.format('D M ddth, Y'); // outputs format like: Thursday April 16th, 2015

Just give the format method a string that you want the date converted to

 - Y - 1997, 2000, 2015
 - y - 97, 01, 15
 - mm - 1, 4, 8, 11, 12
 - MM - 01, 04, 08, 11, 12
 - M - January, February, March, June
 - m - Jan, Feb, Mar, Jun
 - dd - 1, 4, 8, 12, 22, 26
 - DD - 01, 04, 08, 12, 22, 26
 - d - Mon, Tue, Fri
 - D - Monday, Tuesday, Friday

Time, hours, seconds, etc. not yet added
More features need to be added, but it needs to remain simple. Please use it and abuse.
Report and or help fix bugs, add features, make it better.

### Contribute

Right here on github


