XKB layout explorer
===================

Interactive HTML table to explore layout data in xkeyboard-config ([source](https://gitlab.freedesktop.org/xkeyboard-config/xkeyboard-config/), [man page](https://manpages.debian.org/stable/xkb-data/xkeyboard-config.7.en.html#LAYOUTS)).

**[Browse to the table](https://hickford.github.io/xkb-layout-explorer/)**

Updating data
-----------

Current data from release [xkeyboard-config-2.36](https://gitlab.freedesktop.org/xkeyboard-config/xkeyboard-config/-/tags/xkeyboard-config-2.36)

Using xkbcli and [yq](https://github.com/mikefarah/yq/):

    xkbcli list | yq --output-format json

TODO: Filter to remove irrelevant non-layout data
