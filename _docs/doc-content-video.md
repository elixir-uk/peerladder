---
title: Video
container: wide-container
right_sidebar: true
full_width: true
search: true
banner: false
category: content
tags: [content,direction]
custom_js:
- assets/is-in-viewport/lib/isInViewport.js
- assets/prism/prism.js
- assets/video/video.min.js
- assets/video/wistia.js
- js/jquery.parallax-scroll.js
- assets/font-size/js/rv-jquery-fontsize-2.0.3.min.js
- assets/mcustomscrollbar/jquery.mCustomScrollbar.concat.min.js
- js/anchor.js
- assets/bootstrap/js/bootstrap-select.min.js
- assets/Youtube-Channels-Playlist/js/ycp.js
- assets/Youtube-Channels-Playlist/js/ycp.js
- assets/magnify-pop/jquery.magnific-popup.min.js

custom_css:
- assets/prism/prism.css
- assets/mcustomscrollbar/jquery.mCustomScrollbar.min.css
- assets/bootstrap/css/bootstrap-select.min.css
- assets/Youtube-Channels-Playlist/css/ycp.css
- assets/font-size/css/rvfs.css
- assets/video/video-js.min.css
- assets/magnify-pop/magnific-popup.css
---


## YouTube / Vimeo embed

Wrap any `<iframe>` in `.embed-responsive` to make it fluid. Replace the `src` with your video URL.

```html
<div class="embed-responsive embed-responsive-16by9">
    <iframe class="embed-responsive-item"
            src="https://www.youtube.com/embed/YOUR_VIDEO_ID?rel=0"
            allowfullscreen></iframe>
</div>
```

Available aspect ratio classes: `embed-responsive-16by9`, `embed-responsive-4by3`, `embed-responsive-1by1`

## Local video (HTML5)

Self-hosted video with native browser controls:

```html
<div class="local-video-container">
    <video controls muted>
        <source src="{{ 'assets/video/your-video.mp4' | relative_url }}" type="video/mp4">
        Your browser does not support the video tag.
    </video>
</div>
```

Add `autoplay loop` attributes if you want it to play automatically (keep `muted` — browsers block autoplay with audio).

## Video with lightbox popup

Show a thumbnail that opens the video in a popup (requires `jquery.magnific-popup.min.js`):

```html
<div class="code-preview" id="inline-popups">
    <img src="{{ 'img/your-thumbnail.jpg' | relative_url }}" alt="">
    <a class="popup-youtube video_icon" href="#myVideo">
        <i class="arrow_triangle-right"></i>
    </a>
</div>

<video class="video-js vjs-default-skin mfp-hide" id="myVideo" preload="auto">
    <source src="{{ 'assets/video/your-video.mp4' | relative_url }}" type="video/mp4">
</video>
```