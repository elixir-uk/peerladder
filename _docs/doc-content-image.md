---
title: Image
container: wide-container
right_sidebar: true
search: true
banner: false
category: content
tags: [code,content]
custom_js:
- assets/prism/prism.js
- js/jquery.parallax-scroll.js
- assets/font-size/js/rv-jquery-fontsize-2.0.3.min.js
- assets/mcustomscrollbar/jquery.mCustomScrollbar.concat.min.js
- js/anchor.js
- assets/bootstrap/js/bootstrap-select.min.js
- assets/magnify-pop/jquery.magnific-popup.min.js
- assets/thdoan-magnify/js/jquery.magnify.js

custom_css:
- assets/prism/prism.css
- assets/mcustomscrollbar/jquery.mCustomScrollbar.min.css
- assets/bootstrap/css/bootstrap-select.min.css
- assets/thdoan-magnify/css/magnify.css
- assets/font-size/css/rvfs.css
---

## Markdown image

The simplest way to add an image — no HTML needed:

```markdown
![Alt text]({{ '/img/your-image.jpg' | relative_url }})
```

## Image with caption

Use a `<figure>` block when you need a caption below the image:

```html
<figure>
    <img src="{{ 'img/your-image.jpg' | relative_url }}" class="img-fluid" alt="Description">
    <figcaption>Caption text goes here.</figcaption>
</figure>
```

## Image shapes

Add a class to the `<img>` tag to change the shape:

```html
<!-- Rounded corners -->
<img src="{{ 'img/your-image.jpg' | relative_url }}" class="rounded" alt="">

<!-- Circle -->
<img src="{{ 'img/your-image.jpg' | relative_url }}" class="rounded-circle" alt="">

<!-- Responsive (scales with container) -->
<img src="{{ 'img/your-image.jpg' | relative_url }}" class="img-fluid" alt="">
```

## Zoomable image

Wrap the image in a link to enable click-to-magnify (requires `jquery.magnify.js` in `custom_js`):

```html
<a href="{{ 'img/your-large.jpg' | relative_url }}">
    <img src="{{ 'img/your-large.jpg' | relative_url }}" class="img-fluid zoom" alt="">
</a>
```

## Inline image grid

Use Bootstrap columns to place images side by side:

```html
<div class="row">
    <div class="col-md-6">
        <img src="{{ 'img/your-image-1.jpg' | relative_url }}" class="img-fluid" alt="">
    </div>
    <div class="col-md-6">
        <img src="{{ 'img/your-image-2.jpg' | relative_url }}" class="img-fluid" alt="">
    </div>
</div>
```