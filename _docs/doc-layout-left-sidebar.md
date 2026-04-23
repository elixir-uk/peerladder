---
title: Left Sidebar
container: wide-container
right_sidebar: false
category: layout
search: true
banner: false
navbar:
    right_nav_tool: true
tags: [ hotspot, modal,layout]
custom_js:
- js/jquery.parallax-scroll.js
- assets/mcustomscrollbar/jquery.mCustomScrollbar.concat.min.js
- js/anchor.js
- assets/magnify-pop/jquery.magnific-popup.min.js
- js/theme.js
custom_css:
- assets/mcustomscrollbar/jquery.mCustomScrollbar.min.css
- assets/bootstrap/css/bootstrap-select.min.css
---
This page uses the **left-sidebar-only layout** — no right sidebar, giving the content column more width.

## How to enable it

Set `right_sidebar: false` in your front matter:

```yaml
---
title: Your Page Title
right_sidebar: false
banner: true
---
```

With `right_sidebar: false` the layout assigns `col-xl-9` to the content column (vs `col-lg-7` when the right sidebar is present), so the content area is noticeably wider.

## When to use it

- Long-form documentation pages where the right-sidebar table of contents would be redundant
- Pages with embedded media or wide content that benefits from extra horizontal space
- Any page where you want the font-size controls and ToC hidden