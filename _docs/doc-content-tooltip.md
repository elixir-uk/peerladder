---
title: Tooltips & Direction
container: wide-container
right_sidebar: true
category: content
search: true
banner: false
tags: [popover,content]
custom_js:
- js/jquery.parallax-scroll.js
- assets/font-size/js/rv-jquery-fontsize-2.0.3.min.js
- assets/mcustomscrollbar/jquery.mCustomScrollbar.concat.min.js
- js/anchor.js
- assets/bootstrap/js/bootstrap-select.min.js
- assets/magnify-pop/jquery.magnific-popup.min.js
- assets/tooltipster/js/tooltipster.bundle.min.js
custom_css:
- assets/font-size/css/rvfs.css
- assets/mcustomscrollbar/jquery.mCustomScrollbar.min.css
- assets/bootstrap/css/bootstrap-select.min.css
- assets/tooltipster/css/tooltipster.bundle.css
---


## Simple Bootstrap tooltip

The quickest option – no extra HTML needed. Add `data-toggle="tooltip"` and a `title` to any element. Bootstrap initialises these automatically.

```html
<span data-toggle="tooltip" data-placement="top" title="Tooltip text">Hover over me</span>
```

`data-placement` values: `top`, `bottom`, `left`, `right`

## Rich tooltip (hover card)

For tooltips with images, links, or formatted content. Requires `tooltipster` JS loaded in `custom_js`.

Two parts: the trigger link in the text, and a hidden content block anywhere on the page.

```html
<!-- 1. Trigger link in your text -->
<a class="tooltips" href="#" data-tooltip-content="#myTooltip">hover over this phrase</a>

<!-- 2. Hidden content block (place anywhere on the page) -->
<div class="tooltip_templates d-none">
    <div class="tip_content" id="myTooltip">
        <img src="{{ 'img/your-image.jpg' | relative_url }}" alt="">
        <div class="text">
            <p>Your tooltip body text here.</p>
            <h6>Related: <span>Link or reference title</span></h6>
        </div>
    </div>
</div>
```

## Navigation path tooltip

Use `.direction_steps` to show a clickpath inline in a sentence:

```html
<p>Go to
    <span class="direction_steps">
        <span class="direction_step">Settings</span>
        <span class="direction_step">Account</span>
        <span class="direction_step">Profile</span>
    </span>
    and update your details.
</p>
```