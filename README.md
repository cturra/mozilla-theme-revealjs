Mozilla reveal.js theme
======================

Mozilla branded theme for reveal.js based on light blue/grey Firefox colors found at:

  [http://www.mozilla.org/en-US/styleguide/identity/firefox/color/](http://www.mozilla.org/en-US/styleguide/identity/firefox/color/)


Installation
------------

### As Submodule

The easiest way is to add this as a submodule to your reveal.js presentation:

    $ cd ~/revealjs/location/ 
    $ git submodule add https://github.com/cturra/mozilla-theme-revealjs.git css/theme/mozilla


Then update your index.html to point to the mozilla theme style sheet!

    <link rel="stylesheet" href="css/theme/mozilla/mozilla.css" id="theme">


### Manually

You can also manuall use the theme by placing the style sheet into the [revealjs]/css/theme/ directory. Then in your reveal.js index.html file, update your theme style sheet call to:

    <link rel="stylesheet" href="css/theme/mozilla.css" id="theme">


Image usage
-----------

By default there are no borders around images. This is was designed for logos with transparent backgrounds, such as Firefox or Marketplace, to look their best. If you want to have a border around your image however, just call the 'img_border' class:

    <img src="img/superAwesomeImageYo.png" class="img_border" />
