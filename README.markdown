Bad Doggo
=========

This is a personal fork of [Bad Wolf](https://github.com/sjl/badwolf). A color scheme for Vim, originally pieced together by [Steve Losh](http://stevelosh.com/).


Screenshots
-----------

These screenshots may be out of date, but they'll at least give you a taste of
what you're in for.

### Python

![Screenshot](http://i.imgur.com/fQGGC.png)

### HTML (Django Templates)

![Screenshot](http://i.imgur.com/LgLar.png)

### Clojure

![Screenshot](http://i.imgur.com/THHz7.png)

### Markdown

![Screenshot](http://i.imgur.com/J56VS.png)

Configuration
-------------

There are a few settings you can use to tweak how Bad Doggo looks.

### g:baddoggo\_darkgutter

Determines whether the line number, sign column, and fold column are rendered
darker than the normal background, or the same.

    " Make the gutters the same color as the background.
    let g:baddoggo_lessdarkgutter = 1

Default: `0` (off, gutters are darker than the background)
 ### g:baddoggo\_folded

Determines the background color of folded lines.

Can be set to `0`, `1`, or `2`

    " Make folded lines darker than the background.
    let g:baddoggo_folded = 0

    " Make folded lines the same color as the background.
    let g:baddoggo_folded = 1

    " Make folded lines lighter than the background.
    let g:baddoggo_folded = 2

    " Make folded lines much lighter than the background.
    let g:baddoggo_folded = 3

Default: `1` (same color as the background)

### g:baddoggo\_tabline

Determines how light to render the background of the tab line (the line at the
top of the screen containing the various tabs (only in console mode)).

Can be set to `0`, `1`, `2`, or `3`.

    " Make the tab line darker than the background.
    let g:baddoggo_tabline = 0

    " Make the tab line the same color as the background.
    let g:baddoggo_tabline = 1

    " Make the tab line lighter than the background.
    let g:baddoggo_tabline = 2

    " Make the tab line much lighter than the background.
    let g:baddoggo_tabline = 3

Default: `1` (same color as the background)

### g:baddoggo\_html\_link\_underline

Determines whether text inside `a` tags in HTML files will be underlined.

    " Turn off HTML link underlining
    let g:baddoggo_html_link_underline = 0

Default: `1` (on)

### g:baddoggo\_css\_props\_highlight

Determines whether CSS properties should be highlighted.

    " Turn on CSS properties highlighting
    let g:baddoggo_css_props_highlight = 1

Default: `0` (off)

Contributing
------------

I'd love pull requests, but won't necessarily merge all of them.  Color schemes
are a very subjective topic -- we don't all have the same taste.

**If you're going to send a pull request that you want me to merge, please post
a comment in it with before/after screenshots!**
