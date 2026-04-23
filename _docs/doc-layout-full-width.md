---
title: Full Width
container: wide-container
right_sidebar: true
full_width: true
banner: false
search: true
navbar:
    right_nav_tool: true
category: layout
tags: [layout,video]
custom_js:
- assets/is-in-viewport/lib/isInViewport.js
- assets/prism/prism.js
- assets/video/video.min.js
- assets/video/wistia.js
- js/jquery.parallax-scroll.js
- assets/font-size/js/rv-jquery-fontsize-2.0.3.min.js
- assets/mcustomscrollbar/jquery.mCustomScrollbar.concat.min.js
- js/anchor.js
- assets/bootstrap/js/bootstrap-select.min.js
- assets/Youtube-Channels-Playlist/js/ycp.js
- assets/Youtube-Channels-Playlist/js/ycp.js
- assets/magnify-pop/jquery.magnific-popup.min.js

custom_css:
- assets/prism/prism.css
- assets/mcustomscrollbar/jquery.mCustomScrollbar.min.css
- assets/bootstrap/css/bootstrap-select.min.css
- assets/Youtube-Channels-Playlist/css/ycp.css
- assets/font-size/css/rvfs.css
- assets/video/video-js.min.css
- assets/magnify-pop/magnific-popup.css
---

This page uses the **full-width layout** — the content column stretches edge to edge with no right sidebar.

## How to enable it

Add `full_width: true` and remove (or set to `false`) the `right_sidebar` key in your front matter:

```yaml
---
title: Your Page Title
full_width: true
right_sidebar: false
banner: true
---
```

The layout renders with `container-fluid pl-60 pr-60` instead of the fixed `custom_container`, giving the content more horizontal room. This is well suited to wide tables, video embeds, or data-heavy pages.

## When to use it

- Pages with wide tables or data grids
- Video or media-heavy pages
- Landing or overview pages where breathing room helps readability