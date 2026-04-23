---
title: Gradient Banner
container: wide-container
right_sidebar: true
navbar:
 type: menu_purple
 right_nav_tool: true
category: layout
search: true
banner: false
tags: [ Gradient Banner, Process Tab,layout]
custom_js:
- assets/prism/prism.js
- js/jquery.parallax-scroll.js
- assets/font-size/js/rv-jquery-fontsize-2.0.3.min.js
- assets/mcustomscrollbar/jquery.mCustomScrollbar.concat.min.js
- js/anchor.js
- assets/bootstrap/js/bootstrap-select.min.js
- assets/magnify-pop/jquery.magnific-popup.min.js

custom_css:
- assets/prism/prism.css
- assets/font-size/css/rvfs.css
- assets/mcustomscrollbar/jquery.mCustomScrollbar.min.css
- assets/bootstrap/css/bootstrap-select.min.css
---

This page uses the **gradient banner** variant — the top banner renders with a purple gradient background instead of the default plain banner.

## How to enable it

Set `banner: banner_gradient` in your front matter. You can also switch the navbar to the purple theme:

```yaml
---
title: Your Page Title
banner: banner_gradient
navbar:
  type: menu_purple
  right_nav_tool: true
right_sidebar: true
---
```

The layout checks `page.banner` and includes `doc_banner_gradient.html` when it equals `banner_gradient`, otherwise falls back to the standard `doc_banner.html`.

## When to use it

- Section landing pages or high-level overview pages where you want visual hierarchy
- Pages that introduce a new topic or feature area