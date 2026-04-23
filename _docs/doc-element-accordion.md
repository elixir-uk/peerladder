---
title: Accordion
container: wide-container
category: element
right_sidebar: true
search: true
banner: false
navbar:
    right_nav_tool: true
tags: [content,element]
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


Accordion and toggle components let users expand and collapse sections of content. Both use Bootstrap's collapse plugin — no extra JS needed.

## Toggle (single)

A standalone collapsible panel. Multiple toggles on one page are independent of each other.

Copy the HTML from `_TEMPLATE.md` → **Accordion / Toggle → Toggle (single)** section.

Key points:
- Each toggle needs a unique `id` on the collapse target (e.g. `id="toggle1"`)
- The trigger `href` and `aria-controls` must match that `id`
- Add class `show` to the collapse `<div>` if you want it open by default

## Accordion (mutually exclusive)

Multiple panels where opening one closes the others. Wrap all panels in a parent `<div id="accordion">` and add `data-parent="#accordion"` to each collapse target.

Copy the HTML from `_TEMPLATE.md` → **Accordion / Toggle → Accordion** section.

Key points:
- The parent wrapper needs a unique `id` — use a different one if you have multiple accordions on the same page
- Add class `show` to the first panel's collapse `<div>` to start it open