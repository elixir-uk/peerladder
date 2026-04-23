---
title: Without Banner
container: wide-container
right_sidebar: true
navbar:
 right_nav_tool: true
 class: position-static
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


This page uses the **no-banner layout** — the page starts directly with the content, with no top banner section.

## How to enable it

Set `banner: false` in your front matter:

```yaml
---
title: Your Page Title
banner: false
navbar:
  right_nav_tool: true
  class: position-static
right_sidebar: true
---
```

Setting `navbar.class: position-static` prevents the navbar from sitting over the content when there's no banner to push it down.

## When to use it

- Deep reference pages where the banner would add visual noise
- Pages embedded inside multi-step flows
- Any page where you want maximum vertical space from the top