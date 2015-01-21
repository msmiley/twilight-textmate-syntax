# twilight-textmate-syntax theme

This package is an Atom Editor syntax theme which attempts to render as closely as possible to the way the Twilight theme actually renders on the TextMate 2 Beta.

In particular, various colors in this theme are not copied directly from Twilight.tmTheme because TextMate 2 (or OS X) renders them as lighter than they should be numerically. For example, the background is specified as `#181818` in Twilight.tmTheme, but color sampling the rendering on-screen yields `#202020`, a discernable difference.

Not all the colors have been re-sampled, it is a work in progress. I'm also attempting to replicate TextMate 2's spacing before the first line and after the last line.

![Screenshot](https://raw.github.com/msmiley/twilight-textmate-syntax/master/screenshot.png)
