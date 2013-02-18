mozilla-theme-revealjs
======================

Mozilla branded theme for reveal.js based on light blue/grey Firefox colors found at:

  [http://www.mozilla.org/en-US/styleguide/identity/firefox/color/](http://www.mozilla.org/en-US/styleguide/identity/firefox/color/)


Installation
------------

To install this theme, place the style sheet in the [revealjs]/css/theme/ directory. Then in your reveal.js index.html file, update your theme style sheet call to:

    <link rel="stylesheet" href="css/theme/mozilla.css" id="theme">


### Image usage

By default there are no borders around images. This is was designed for logos with transparent backgrounds, such as Firefox or Marketplace, to look their best. If you want to have a border around your image however, just call the 'img_border' class:

    <img src="img/superAwesomeImageYo.png" class="img_border" />
