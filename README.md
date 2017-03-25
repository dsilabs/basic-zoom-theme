
Basic Zoom Theme
====

A very simple bootstrap based theme for the [Zoom](https://github.com/dsilabs/zoom)
application framework.

This theme is built using pug and sass.  A great way to modify
this sort of theme is to use both pug and sass in watch mode
allowing you to make changes to the source files and with the
resulting .html and .css files being regenerated as you save
changes.

To do this, you'll need both [pug](https://pugjs.org/) and [Sass](http://sass-lang.com/) installed as well as [pug-cli](https://www.npmjs.com/package/pug-cli).  Then, in two separate terminal sessions, cd to the
theme directory and run the following commands in each window:

Do this in one terminal window

    pug -w --pretty src/pug/pages --out .
  
and this in the other terminal window.

    sass  --style expanded --sourcemap=none --watch src/sass:css

Adust parameters as you see fit.

Then start start editing the files in the /src directory.
