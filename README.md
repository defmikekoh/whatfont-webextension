# WhatFont WebExtension

This is a WebExtension wrapper for Chengyin Liu's [WhatFont](http://www.chengyinliu.com/whatfont.html) script.
All icons, "whatfont_core.js", and "wf.css" were copied from his [GitHub repository](https://github.com/chengyin/WhatFont-Bookmarklet).

Tested working in Firefox 63.

## Build Instructions

To build the extension, run the following command from the `whatfont-webextension` directory:

```bash
rm -f whatfont.zip && zip whatfont.zip manifest.json jquery.js LICENSE wf.css whatfont_activate.js whatfont_button.js whatfont_core.js icons/*
```
