# Dummy
=====
Dummy is a PHP toolkit for rapid front-end prototyping and QA. Originally conceived as a tool for simulating the high volume, rapidly changing content characteristics of online newspapers and magazines, it's generalized enough to benefit the early stage front-end development of any website or application with highly variable content.

### Dummy can…
+ Randomly select and insert strings of Lorem Ipsum of various lengths and in predefined formats, or easily roll your own formats.
+ Automagically crop and size high quality, news worthy, CC licensed placeholder images from a default pool – or from a specific folder or subset of folders that you provide.
+ Bring new life to your static code with friendly, human readable functions for controlling probability and building out if/else scenarios.
+ More. Not lots more. But a _bit_ more!

### You can…
+ See demos …coming soon.
+ See docs …coming soon.
+ Fork it on Github @ [https://github.com/kerns/dummy](https://github.com/kerns/dummy)
+ Give feedback …[this instant](http://twitter.com/kerns).

### Intro
Dummy is a content generation toolkit designed to make the development, testing and presentation of web prototypes less time consuming and more realistic. Whether you're meticulously crafting a fully responsive site with a myriad of CSS breakpoints, or just slapping together a half-baked idea – using Dummy should make it easier for you to visualize, test and present _at the very earliest stages of development_ something closer to what your actual front-end will become under a variety of different conditions.

It does so by helping you to populate your dummy with content and randomizing key aspects of it's layout, in this way simulating connectivity to a live database.

**Dummy is for the front-end web worker wondering…**

+ How does this layout hold up without an image – or – with a landscape (instead of a portrait) oriented image?
+ What is the maximum number of items that can appear in this list before it breaks the layout, or before it just stops looking good?
+ How does the columns balance as the content changes – and what's the longest word that can fit into this column without triggering unwanted overflow?
+ What is the easiest way to demo the signed-in and signed-out states of this page?
+ Do these breakpoints hold water?

### Why?
Using Dummy in the early stages of front-end development can give you a new perspective on your work every time your document is reloaded in the browser, shortening and improving your test cycle by more quickly exposing weak-points or trouble areas as you go about marking up a new design.

This is especially important for front-end code that should be delivered to another team for implementation as part of a phased hand-off. As any front-ender knows, the earlier you can catch a problem the easier and less painful it will be to debug.

### Requirements
You need a development environment running Apache + PHP and compiled with support for GD (this covers most of them). If you want to play with URL segments or other advanced techniques then you'll need to have mod_rewrite enabled, and you'll need to enable the .htaccess file (included in /dummy/docs/), but again, this probably covers most local development environments. If you're not developing locally, …why aren't you developing locally?

### TODO
+ Add demos and docs (I know).
+ Integrate a full-fledged Lorum Ipsum generator, together with some intuitive syntax for specifying parameters of the text you want generated.
+ Ability to call and define image crops from within CSS (i.e. being able to post image requests in the URL to dummy.php)
+ Optimize performance and memory usage.
+ Clean up the way errors and messages are formatted (i.e. abstract the HTML and style surrounding them)
+ It's probably a bad idea to ship this with a bandwidth hogging library of images in assets/images. It would make more sense to maintain separate asset packages for different types of projects (e.g. a commerce package with commerical product shots, a portfolio or gallery package with images that showcase art, architecture, or design). The image assets that ship with Dummy are very much geared toward editorial design.

### License
Dummy is released under a Creative Commons Attribution-Share Alike 3.0 United States license (http://creativecommons.org/licenses/by-sa/3.0/us/). Be a doll and let me know how you're using Dummy, or if you've used it to help build, test or demo anything interesting.