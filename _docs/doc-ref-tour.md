---
title: Interface Tour
container: wide-container
category: reference
right_sidebar: true
search: true
banner: false
navbar:
    right_nav_tool: true
tags: [reference,tour]
custom_js:
- js/jquery.parallax-scroll.js
- assets/font-size/js/rv-jquery-fontsize-2.0.3.min.js
- assets/mcustomscrollbar/jquery.mCustomScrollbar.concat.min.js
- js/anchor.js
- assets/bootstrap/js/bootstrap-select.min.js
- assets/magnify-pop/jquery.magnific-popup.min.js

custom_css:
- assets/font-size/css/rvfs.css
- assets/mcustomscrollbar/jquery.mCustomScrollbar.min.css
- assets/bootstrap/css/bootstrap-select.min.css
---

The interface tour layout presents a step-by-step walkthrough with alternating text and screenshot panels. It's well suited to onboarding flows or feature introductions.

## Usage

Copy the HTML from `_TEMPLATE.md` → **Interface Tour** section, then:

1. Replace each `<h4>` with your step title
2. Replace each `<p>` with your step description
3. Replace `img/your-screenshot.jpg` with your actual screenshot path
4. Add or remove `.tour_item` + `.border_bottom` pairs for more or fewer steps

## Structure

Each step is a `.tour_item` block separated by a `.border_bottom` divider:

```html
<div class="border_bottom"></div>

<div class="tour_item">
    <h4 class="c_head load-order-2">Step title</h4>
    <div class="row align-items-center">
        <div class="col-sm-5 tour_info_content">
            <p>Description of this step.</p>
        </div>
        <div class="col-sm-7">
            <img src="{{ 'img/your-screenshot.jpg' | relative_url }}" alt="" class="img-fluid">
        </div>
    </div>
</div>
```

Swap the column order (`col-sm-7` image first, then `col-sm-5` text) to alternate the layout between steps.