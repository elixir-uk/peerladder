---
title: Tab
container: wide-container
right_sidebar: true
category: content
search: true
banner: false
navbar:
    right_nav_tool: true
tags: [ Tabs Widget, Process Tab,element]
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

Tab components let you organise content into switchable panels without leaving the page. Both horizontal and vertical layouts are available.

## Horizontal tabs

The default. Nav tabs sit above the content panels.

Copy the HTML from `_TEMPLATE.md` → **Tabs → Horizontal tabs** section.

Key points:
- Each `<li>` nav link's `href` must match its panel's `id` (e.g. `href="#tab1"` ↔ `id="tab1"`)
- `aria-controls` on the link and the `aria-labelledby` on the panel should also match
- Add `active` and `show` to the first panel and `active` + `aria-selected="true"` to its nav link

## Vertical tabs (pills)

Nav links stack in a left column beside the content.

Copy the HTML from `_TEMPLATE.md` → **Tabs → Vertical tabs** section.

Key points:
- Use `data-toggle="pill"` (not `"tab"`) on vertical nav links
- Adjust the `col-3` / `col-9` split to change the nav width ratio