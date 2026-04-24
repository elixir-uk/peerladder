---
title: Notices
container: wide-container
right_sidebar: true
search: true
banner: false
category: element
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

## Alert messages

Five severity levels. Paste the block you need and fill in `title` and body text.

```html
<!-- Info (default) -->
<div class="alert media message_alert fade show" role="alert">
    <i class="icon_volume-low"></i>
    <div class="media-body">
        <h5>Your title here</h5>
        <p>Your message here.</p>
        <button type="button" class="close" data-dismiss="alert" aria-label="Close">
            <i class="icon_close"></i>
        </button>
    </div>
</div>

<!-- Danger -->
<div class="alert media message_alert alert-danger fade show" role="alert">
    <i class="icon_close_alt2"></i>
    <div class="media-body">
        <h5>Key Warning</h5>
        <p>Your warning message here.</p>
        <button type="button" class="close" data-dismiss="alert" aria-label="Close">
            <i class="icon_close"></i>
        </button>
    </div>
</div>

<!-- Success -->
<div class="alert media message_alert alert-success fade show" role="alert">
    <i class="icon_check_alt2"></i>
    <div class="media-body">
        <h5>Success</h5>
        <p>Your success message here.</p>
        <button type="button" class="close" data-dismiss="alert" aria-label="Close">
            <i class="icon_close"></i>
        </button>
    </div>
</div>

<!-- Warning -->
<div class="alert media message_alert alert-warning fade show" role="alert">
    <i class="icon_error-circle_alt"></i>
    <div class="media-body">
        <h5>Warning</h5>
        <p>Your warning message here.</p>
        <button type="button" class="close" data-dismiss="alert" aria-label="Close">
            <i class="icon_close"></i>
        </button>
    </div>
</div>

<!-- Info blue -->
<div class="alert media message_alert alert-info fade show" role="alert">
    <i class="icon_info_alt"></i>
    <div class="media-body">
        <h5>Information</h5>
        <p>Your info message here.</p>
        <button type="button" class="close" data-dismiss="alert" aria-label="Close">
            <i class="icon_close"></i>
        </button>
    </div>
</div>
```

## Notice blocks

Quieter than alerts – no dismiss button, sits inline with content. Three variants:

```html
<!-- Note (green) -->
<blockquote class="media notice notice-success">
    <i class="icon_menu-square_alt2"></i>
    <div class="media-body">
        <h5>Note</h5>
        <p>Your note text here.</p>
    </div>
</blockquote>

<!-- Warning (yellow) -->
<blockquote class="media notice notice-warning">
    <i class="icon_ribbon_alt"></i>
    <div class="media-body">
        <p><strong>Important:</strong> Your warning text here.</p>
    </div>
</blockquote>

<!-- Danger (red) -->
<blockquote class="media notice notice-danger">
    <i class="icon_ribbon_alt"></i>
    <div class="media-body">
        <p>Your danger notice here.</p>
    </div>
</blockquote>
```

## Explanation paragraph

For supplementary commentary visually set apart from the main flow:

```html
<p class="explanation expn-left">Your explanatory text here.</p>
```