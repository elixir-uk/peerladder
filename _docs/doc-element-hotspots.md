---
title: Image Hotspots
container: wide-container
right_sidebar: false
category: element
search: true
navbar:
    right_nav_tool: true
banner: false
tags: [ hotspot, modal,element]
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


Image hotspots let you place numbered, clickable dots over a photo. Each dot opens a popup with a title and description.

Copy the full HTML from `_TEMPLATE.md` → **Image Hotspots** section, then customise:

1. Replace `img/your-image.jpg` with your image path
2. Change the `.cls1`, `.cls2` etc. numbering to match how many hotspots you need
3. Update the `<h4>` title and `<p>` description inside each `.dropdown-menu`
4. The `<div class="divs">` block renders the numbered badges — add or remove `<div class="clsN">N</div>` entries to match your hotspot count

Key points:
- Each hotspot `<li>` needs a matching numbered class: `cls1`, `cls2`, `cls3`, `cls4`
- The CSS positions each dot using those classes — if you add more than 4, add corresponding CSS rules in your stylesheet
- Requires Bootstrap dropdown JS (already included globally)