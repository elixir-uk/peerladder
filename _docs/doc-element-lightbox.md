---
title: Image Lightbox
container: wide-container
category: element
search: true
right_sidebar: false
banner: false
tags: [image modal,element]
custom_js:
- assets/prism/prism.js
- js/jquery.parallax-scroll.js
- assets/font-size/js/rv-jquery-fontsize-2.0.3.min.js
- assets/mcustomscrollbar/jquery.mCustomScrollbar.concat.min.js
- js/anchor.js
- assets/bootstrap/js/bootstrap-select.min.js
- assets/magnify-pop/jquery.magnific-popup.min.js
- assets/tooltipster/js/tooltipster.bundle.min.js

custom_css:
- assets/prism/prism.css
- assets/font-size/css/rvfs.css
- assets/mcustomscrollbar/jquery.mCustomScrollbar.min.css
- assets/bootstrap/css/bootstrap-select.min.css
- assets/magnify-pop/magnific-popup.css
---

Two lightbox patterns are available: a simple click-to-enlarge image, and a modal popup with optional hotspot dots.

Both require `jquery.magnific-popup.min.js` in `custom_js`.

## Simple image lightbox

A thumbnail image with a `+` overlay. Clicking opens the full image.

Copy the HTML from `_TEMPLATE.md` → **Lightbox → Simple image lightbox**, then:
- Set the thumbnail `<img src>` to your preview image
- Set the `<a href>` to your full-size image

## Modal lightbox

Opens a full overlay modal with the image inside. Can include annotated hotspot dots.

Copy the HTML from `_TEMPLATE.md` → **Lightbox → Modal lightbox with hotspot dots**, then:
- Update the `data-target` on the trigger to match the modal `id`
- Replace both image paths (thumbnail and large)
- For each dot, update its `data-tooltip-content` and create a matching hidden `.tip_content` block

Key points:
- The modal `id` must be unique per page if you have multiple lightboxes
- Dots use the same `.tooltips` + `.tooltip_templates` pattern as the tooltip component