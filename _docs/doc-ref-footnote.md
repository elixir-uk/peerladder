---
title: Footnote
container: wide-container
category: reference
right_sidebar: true
search: true
banner: false
navbar:
    right_nav_tool: true
tags: [reference,note]
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

## How footnotes work

Three connected pieces: a superscript link in the body text, a hidden tooltip preview, and a numbered list at the bottom of the page. All three use matching IDs to link together.

## Usage

**1. In your body text** — add a footnote link wherever the reference belongs:

```html
<p>
    Your sentence with a reference
    <a class="footnotes-link tooltips" href="#note-name-a" id="note-link-1"
       data-tooltip-content="#note-link-a"></a>
    continuing after it.
</p>
```

**2. At the bottom of the page** — the numbered footnotes list:

```html
<div class="footnotes margin-top-xl">
    <h4>Footnotes</h4>
    <ol>
        <li class="footnotes_item" id="note-name-a">
            <a class="back-article" href="#note-link-1" aria-label="Back to article">
                <ion-icon name="arrow-up"></ion-icon>
            </a>
            <strong>Source Title</strong><br>
            Full citation or description text here.
        </li>
    </ol>
</div>
```

**3. The hover preview** (hidden, shown on hover via tooltipster):

```html
<div class="tooltip_templates d-none">
    <div class="tip_content" id="note-link-a">
        <div class="text">
            <p>Short preview of the footnote content.</p>
        </div>
    </div>
</div>
```

## ID naming convention

Keep IDs consistent so the three parts connect correctly:

| Body link `href` | Body link `id` | Tooltip `data-tooltip-content` | Tooltip `id` | Footnote `id` |
|---|---|---|---|---|
| `#note-name-a` | `note-link-1` | `#note-link-a` | `note-link-a` | `note-name-a` |
| `#note-name-b` | `note-link-2` | `#note-link-b` | `note-link-b` | `note-name-b` |