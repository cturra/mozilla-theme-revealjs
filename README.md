Mozilla reveal.js theme
=======================

Mozilla branded theme for [reveal.js](http://lab.hakim.se/reveal-js/) based on light blue/grey Firefox colors found at:

  [http://www.mozilla.org/en-US/styleguide/identity/firefox/color/](http://www.mozilla.org/en-US/styleguide/identity/firefox/color/)


Installation
------------

You can manually use the theme by placing the style sheet into the `<revealjs>/css/theme/` directory. Then in your reveal.js `index.html` file, update your theme style sheet call to:

    <link rel="stylesheet" href="css/theme/mozilla.css" id="theme">


Image borders
-------------

By default there are no borders around images. This was designed for logos with transparent backgrounds (such as Firefox or Marketplace) to look their best. If you want to have a border around your image, just call the `img_border` class:

    <img src="img/superAwesomeImageYo.png" class="img_border" />
