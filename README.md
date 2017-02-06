grunter
=======

[![Greenkeeper badge](https://badges.greenkeeper.io/johngeorgewright/grunter.svg)](https://greenkeeper.io/)

Grunt (&lt;0.4.0) that works in windows

Useage
------

Simply install grunter (instead of grunt) `npm i -g grunter` and replace all your `grunt` commands with `grunter`... done.

Why
---

Unfortunately, during the build of grunt &lt;0.4.0, it had been overlooked that Windows will first search the current path for a `.js` file when running a command. I.e. when running `grunt -h` the first thing that is found is the `grunt.js` file in the current directory. This, of course, breaks. Therefore, *grunter* simply renames the `grunt` cli.

