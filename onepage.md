---

layout: default
custom_footer: true
container: doc full-width-doc  onepage-doc sticky_menu
preloader: false
right_sidebar: true
search: false
navbar:
    right_nav_tool: true
    type: dark_menu
custom_js:
- assets/prism/prism.js
- js/TweenMax.min.js
- js/jquery.parallax-scroll.js
- assets/font-size/js/rv-jquery-fontsize-2.0.3.min.js
- assets/mcustomscrollbar/jquery.mCustomScrollbar.concat.min.js
- js/anchor.js
- assets/bootstrap/js/bootstrap-select.min.js
- assets/magnify-pop/jquery.magnific-popup.min.js
- js/parallaxie.js
- assets/tooltipster/js/tooltipster.bundle.min.js
- assets/video/video.min.js
- assets/video/wistia.js
- js/onpage-menu.js
- assets/thdoan-magnify/js/jquery.magnify.js
- js/theme.js

custom_css:
- assets/prism/prism.css
- assets/prism/prism-coy.css
- assets/font-size/css/rvfs.css
- assets/magnify-pop/magnific-popup.css
- assets/thdoan-magnify/css/magnify.css
- assets/mcustomscrollbar/jquery.mCustomScrollbar.min.css
- assets/bootstrap/css/bootstrap-select.min.css
- assets/video/video-js.min.css
- assets/tooltipster/css/tooltipster.bundle.css
---

<section class="doc_documentation_area onepage_doc_area" id="sticky_doc">
    <div class="overlay_bg"></div>
    <div class="container-fluid pl-60 pr-60">
        <div class="row doc-container">
            <div class="col-lg-2 doc_mobile_menu doc-sidebar display_none">
                <aside class="doc_left_sidebarlist">
                    <h3 class="nav_title">Doc Navigation</h3>
                    <div class="scroll">
                        <ul class="list-unstyled nav-sidebar doc-nav">
                            <li class="nav-item active">
                                <a class="nav-link" href="#doc"><img src="{{"img/onepage-icon/smiles-icon.png" | relative_url}}" alt="">Getting Started</a>
                            </li>
                            <li class="nav-item">
                                <a class="nav-link" href="#shortcodes"><img src="{{"img/side-nav/briefcase.png" | relative_url}}" alt="briefcase">Shortcodes</a>
                                <ul class="list-unstyled dropdown_nav">
                                    <li class="nav-item">
                                        <a class="nav-link" href="#tabs-doc">Tab</a>
                                    </li>
                                    <li class="nav-item">
                                        <a class="nav-link" href="#accordian-doc">Accordian</a>
                                    </li>
                                    <li class="nav-item">
                                        <a class="nav-link" href="#notices-doc">Notices</a>
                                    </li>
                                    <li class="nav-item">
                                        <a class="nav-link" href="#tooltip-doc">Tooltip</a>
                                    </li>
                                    <li class="nav-item">
                                        <a class="nav-link" href="#table-doc">Table</a>
                                    </li>
                                    <li class="nav-item">
                                        <a class="nav-link" href="#lightbox-doc">Lightbox</a>
                                    </li>
                                    <li class="nav-item">
                                        <a class="nav-link" href="#footnote-doc">Footnote</a>
                                    </li>
                                    <li class="nav-item">
                                        <a class="nav-link" href="#can-use-doc">Can I Use</a>
                                    </li>
                                </ul>
                                <span class="icon">
                                    <i class="icon_plus"></i>
                                    <i class="icon_minus-06"></i>
                                </span>
                            </li>
                            <li class="nav-item">
                                <a class="nav-link" href="#tour-doc"><img src="{{"img/side-nav/chat1.png" | relative_url}}" alt="">Tour</a>
                                <span class="icon">
                                    <i class="icon_plus"></i>
                                    <i class="icon_minus-06"></i>
                                </span>
                                <ul class="list-unstyled dropdown_nav">
                                    <li class="nav-item">
                                        <a class="nav-link" href="#pointing">Image Hotspots</a>
                                    </li>
                                </ul>
                            </li>
                            <li class="nav-item">
                                <a class="nav-link" href="#typography-doc"><img src="{{"img/side-nav/document.png" | relative_url}}" alt="">Content</a>
                                <span class="icon">
                                    <i class="icon_plus"></i>
                                    <i class="icon_minus-06"></i>
                                </span>
                                <ul class="list-unstyled dropdown_nav">
                                    <li class="nav-item">
                                        <a class="nav-link" href="#code-doc">Code</a>
                                    </li>
                                    <li class="nav-item">
                                        <a class="nav-link" href="#img-doc">Image</a>
                                    </li>
                                    <li class="nav-item">
                                        <a class="nav-link" href="#video-doc">Video</a>
                                    </li>
                                </ul>
                            </li>
                            <li class="nav-item">
                                <a class="nav-link" href="#changelog-doc"><img src="{{"img/side-nav/clock.png" | relative_url}}" alt="">Change Log</a>
                            </li>
                            <li class="nav-item">
                                <a class="nav-link" href="#cheatsheet-doc"><img src="{{"img/side-nav/book.png" | relative_url}}" alt="">Cheatsheet</a>
                            </li>
                            <li class="nav-item">
                                <a class="nav-link" href="#ex1"><img src="{{"img/side-nav/chat.png" | relative_url}}" alt="">Example Item</a>
                            </li>
                            <li class="nav-item">
                                <a class="nav-link" href="#ex2"><img src="{{"img/side-nav/layout.png" | relative_url}}" alt="">Example Item 02</a>
                            </li>
                            <li class="nav-item">
                                <a class="nav-link" href="#ex3"><img src="{{"img/side-nav/support.png" | relative_url}}" alt="">Example Item 03</a>
                            </li>
                        </ul>
                    </div>
                </aside>
            </div>
            <div class="col-lg-8 col-md-8">
                <div class="documentation_info" id="post">
                    <!--doc-->
                    <article class="documentation_body doc-section pt-0" id="doc">
                        <div class="shortcode_title">
                            <h2>Documentation</h2>
                            <p>
                                <span>Welcome to Docy !</span>
                                Get familiar with the Stripe products and explore their features:</p>
                        </div>
                        <div class="row">
                            <div class="col-lg-4 col-sm-6">
                                <div class="media documentation_item">
                                    <div class="icon">
                                        <img alt="" src="{{"img/home_one/icon/folder.png" | relative_url}}">
                                    </div>
                                    <div class="media-body">
                                        <a href="#">
                                            <h5>Working with Docs</h5>
                                        </a>
                                        <p>He lost his bottle bubble and squeak knackered.!</p>
                                    </div>
                                </div>
                            </div>
                            <div class="col-lg-4 col-sm-6">
                                <div class="media documentation_item">
                                    <div class="icon">
                                        <img alt="" src="{{"img/home_one/icon/envelope.png" | relative_url}}">
                                    </div>
                                    <div class="media-body">
                                        <a href="#">
                                            <h5>Formatting Content</h5>
                                        </a>
                                        <p>He lost his bottle bubble and squeak knackered.!</p>
                                    </div>
                                </div>
                            </div>
                            <div class="col-lg-4 col-sm-6">
                                <div class="media documentation_item">
                                    <div class="icon">
                                        <img alt="" src="{{"img/home_one/icon/layout.png" | relative_url}}">
                                    </div>
                                    <div class="media-body">
                                        <a href="#">
                                            <h5>Development</h5>
                                        </a>
                                        <p>He lost his bottle bubble and squeak knackered.!</p>
                                    </div>
                                </div>
                            </div>
                            <div class="col-lg-4 col-sm-6">
                                <div class="media documentation_item">
                                    <div class="icon">
                                        <img alt="" src="{{"img/home_one/icon/smartphone.png" | relative_url}}">
                                    </div>
                                    <div class="media-body">
                                        <a href="#">
                                            <h5>Mobile App</h5>
                                        </a>
                                        <p>He lost his bottle bubble and squeak knackered.!</p>
                                    </div>
                                </div>
                            </div>
                            <div class="col-lg-4 col-sm-6">
                                <div class="media documentation_item">
                                    <div class="icon">
                                        <img alt="" src="{{"img/home_one/icon/management.png" | relative_url}}">
                                    </div>
                                    <div class="media-body">
                                        <a href="#">
                                            <h5>Account Management</h5>
                                        </a>
                                        <p>He lost his bottle bubble and squeak knackered.!</p>
                                    </div>
                                </div>
                            </div>
                            <div class="col-lg-4 col-sm-6">
                                <div class="media documentation_item">
                                    <div class="icon">
                                        <img alt="" src="{{"img/home_one/icon/briefcase.png" | relative_url}}">
                                    </div>
                                    <div class="media-body">
                                        <a href="#">
                                            <h5>Shortcodes</h5>
                                        </a>
                                        <p>He lost his bottle bubble and squeak knackered.!</p>
                                    </div>
                                </div>
                            </div>
                            <div class="col-lg-4 col-sm-6">
                                <div class="media documentation_item">
                                    <div class="icon">
                                        <img alt="" src="{{"img/home_one/icon/newspaper.png" | relative_url}}">
                                    </div>
                                    <div class="media-body">
                                        <a href="#">
                                            <h5>Productivity</h5>
                                        </a>
                                        <p>He lost his bottle bubble and squeak knackered.!</p>
                                    </div>
                                </div>
                            </div>
                            <div class="col-lg-4 col-sm-6">
                                <div class="media documentation_item">
                                    <div class="icon">
                                        <img alt="" src="{{"img/side-nav/issuin.png" | relative_url}}">
                                    </div>
                                    <div class="media-body">
                                        <a href="#">
                                            <h5>Issuing</h5>
                                        </a>
                                        <p>He lost his bottle bubble and squeak knackered.!</p>
                                    </div>
                                </div>
                            </div>
                            <div class="col-lg-4 col-sm-6">
                                <div class="media documentation_item">
                                    <div class="icon">
                                        <img alt="" src="{{"img/home_one/icon/color-palette.png" | relative_url}}">
                                    </div>
                                    <div class="media-body">
                                        <a href="#">
                                            <h5>Introduction</h5>
                                        </a>
                                        <p>He lost his bottle bubble and squeak knackered.!</p>
                                    </div>
                                </div>
                            </div>
                            <div class="col-lg-4 col-sm-6">
                                <div class="media documentation_item">
                                    <div class="icon">
                                        <img alt="" src="{{"img/side-nav/terminals.png" | relative_url}}">
                                    </div>
                                    <div class="media-body">
                                        <a href="#">
                                            <h5>Terminal</h5>
                                        </a>
                                        <p>He lost his bottle bubble and squeak knackered.!</p>
                                    </div>
                                </div>
                            </div>
                            <div class="col-lg-4 col-sm-6">
                                <div class="media documentation_item">
                                    <div class="icon">
                                        <img alt="" src="{{"img/home_one/icon/android.png" | relative_url}}">
                                    </div>
                                    <div class="media-body">
                                        <a href="#">
                                            <h5>Getting Started</h5>
                                        </a>
                                        <p>He lost his bottle bubble and squeak knackered.!</p>
                                    </div>
                                </div>
                            </div>
                            <div class="col-lg-4 col-sm-6">
                                <div class="media documentation_item">
                                    <div class="icon">
                                        <img alt="" src="{{"img/home_one/icon/lock.png" | relative_url}}">
                                    </div>
                                    <div class="media-body">
                                        <a href="#">
                                            <h5>This Document</h5>
                                        </a>
                                        <p>He lost his bottle bubble and squeak knackered.!</p>
                                    </div>
                                </div>
                            </div>
                        </div>
                        <div class="border_bottom"></div>
                    </article>
                    <!--shortcode-->
                    <article class="documentation_body shortcode_text doc-section" id="shortcodes">
                        <div class="shortcode_title">
                            <h2>Getting Started</h2>
                            <p>
                                <span>Welcome to Docy !</span>
                                Get familiar with the Stripe products and explore their features:</p>
                        </div>
                        <p>To use Docy WordPress theme you must have WordPress engine installed. We assume you have a working version of WordPress already up and running. We also encourage you to actively use the links below. These useful resources cover most of the general WordPress questions you may have:</p>
                        <ul class="ul">
                            <li>What is WordPress?&nbsp;<strong>
                                    <a href="https://en.wikipedia.org/wiki/WordPress" rel="noopener noreferrer" target="_blank">Wikipedia</a>
                                </strong>
                                and WordPress FAQ&nbsp;<strong>
                                    <a href="https://codex.wordpress.org/FAQ_New_To_WordPress" rel="noopener noreferrer" target="_blank">Read here!</a>
                                </strong>
                            </li>
                            <li>Tutorial on how to Install WordPress?&nbsp;<strong>
                                    <a href="https://www.youtube.com/watch?v=ell0SiTZyX8" rel="noopener noreferrer" target="_blank">Watch Video</a>
                                </strong>
                            </li>
                            <li>WordPress Lessons&nbsp;<strong>
                                    <a href="https://codex.wordpress.org/WordPress_Lessons" rel="noopener noreferrer" target="_blank">Visit Articles</a>
                                </strong>
                            </li>
                        </ul>
                        <h4 class="c_head" id="article">Articles</h4>
                        <ul class="list-unstyled article_list tag_list">
                            <li>
                                <a href="{{"docs/doc-element-tab" | relative_url}}">
                                    <i class="icon_document_alt"></i>Tabs</a>
                            </li>
                            <li>
                                <a href="{{"docs/doc-element-accordion" | relative_url}}">
                                    <i class="icon_document_alt"></i>Accordion</a>
                            </li>
                            <li>
                                <a href="{{"docs/doc-element-notice" | relative_url}}">
                                    <i class="icon_document_alt"></i>Notices</a>
                            </li>
                            <li>
                                <a href="{{"docs/doc-element-table" | relative_url}}">
                                    <i class="icon_document_alt"></i>Table</a>
                            </li>
                            <li>
                                <a href="{{"docs/doc-element-lightbox" | relative_url}}">
                                    <i class="icon_document_alt"></i>Image Lightbox</a>
                            </li>
                            <li>
                                <a href="{{"docs/doc-content-tooltip" | relative_url}}">
                                    <i class="icon_document_alt"></i>Tooltip</a>
                            </li>
                            <li>
                                <a href="{{"docs/doc-element-hotspots" | relative_url}}">
                                    <i class="icon_document_alt"></i>Image Hotspots</a>
                            </li>
                            <li>
                                <a href="{{"docs/doc-element-code" | relative_url}}">
                                    <i class="icon_document_alt"></i>Code</a>
                            </li>
                        </ul>
                        <div class="border_bottom"></div>
                        <div class="shortcode_info" id="tabs-doc">
                            {% include doc_tab.html %}
                        </div>
                        <!--accordian-->
                        <div class="shortcode_info" id="accordian-doc">
                            {% include doc_accordion.html %}
                        </div>
                        <!--accordian-->
                                                                                                                                                                                                                                                                                                                                                                                                        <!--notice-->
                        <div class="shortcode_info" id="notices-doc">
                            {% include doc_notice.html %}
                        </div>
                        <!--notice-->
                                                                                                                                                                                                                                                                                                                                                                                                        <!--tooltip-->
                        <div class="shortcode_info" id="tooltip-doc">
                            {% include doc_tooltip.html %}
                        </div>
                        <!--tooltip-->
                                                                                                                                                                                                                                                                                                                                                                                                        <!--table-->
                        <div class="shortcode_info" id="table-doc">
                            {% include doc_table.html %}
                        </div>
                        <!--table-->
                                                                                                                                                                                                                                                                                                                                                                                                        <!--lightbox-->
                        <div class="shortcode_info" id="lightbox-doc">
                            {% include doc_lightbox.html %}
                        </div>
                        <!--lightbox-->
                                                                                                                                                                                                                                                                                                                                                                                                        <!--footnote-->
                        <div class="shortcode_info" id="footnote-doc">
                            {% include doc_footnote.html %}
                        </div>
                        <!--footnote-->
                                                                                                                                                                                                                                                                                                                                                                                                        <!--can I use-->
                        <div class="shortcode_info" id="can-use-doc">
                            {% include doc_can_use.html %}
                        </div>
                        <!--can I use-->
                    </article>
                    <article class="documentation_body doc-section" id="tour-doc">
                        <div class="shortcode_title">
                            <h2>Welcome to Tour</h2>
                            <p>Documentation and examples for typography, including global settings, headings, body text, lists, and more.With your help, we're working together to build a library of detailed answers to every question about programming.</p>
                        </div>
                        <div class="border_bottom"></div>
                        <div class="tour_item">
                            <h4 class="c_head load-order-2" id="head">Ask questions, get answer no distractions</h4>
                            <div class="row align-items-center">
                                <div class="col-sm-5 tour_info_content">
                                    <p>This site is all about
                                        <b>getting answers.</b>
                                        It's not a discussion forum. There's no chit-chat.</p>
                                    <div class="just_question">
                                        <div class="just_text question_top">
                                            <p>Just questions....</p>
                                            <div class="arrow wow fadeInLeft" data-wow-delay="0.8s">
                                                <img alt="" src="{{"img/arrow_top.png" | relative_url}}">
                                            </div>
                                        </div>
                                        <div class="just_text answer_bottom">
                                            <p>Just questions....</p>
                                            <div class="arrow wow fadeInLeft" data-wow-delay="0.9s">
                                                <img alt="" src="{{"img/arrow_bottom.png" | relative_url}}">
                                            </div>
                                        </div>
                                    </div>
                                </div>
                                <div class="col-sm-7">
                                    <div class="tour_preview_img wow fadeInRight" data-wow-delay="0.3s">
                                        <img alt="" class="img-fluid" src="{{"img/tour_img1.png" | relative_url}}">
                                    </div>
                                </div>
                            </div>
                        </div>
                        <div class="border_bottom"></div>
                        <div class="tour_item">
                            <h4 class="c_head">Get answers to practical, detailed questions</h4>
                            <div class="row flex-row-reverse align-items-center tour_intro_item">
                                <div class="col-sm-7">
                                    <div class="tour_preview_img wow fadeInRight" data-wow-delay="0.3s">
                                        <img alt="" class="img-fluid" src="{{"img/tour_img2.png" | relative_url}}">
                                    </div>
                                </div>
                                <div class="col-sm-5 tour_info_content">
                                    <div class="arrow wow fadeInLeft" data-wow-delay="0.6s">
                                        <img alt="" src="{{"img/arrow_bottom.png" | relative_url}}">
                                    </div>
                                    <p>Focus on questions about an actual problem you have faced. Include details about what you have tried and exactly what you are trying to do.</p>
                                </div>
                            </div>
                            <div class="row align-items-center tour_intro_item">
                                <div class="col-sm-7">
                                    <div class="tour_preview_img wow fadeInLeft" data-wow-delay="0.7s">
                                        <img alt="" class="img-fluid" src="{{"img/tour_img3.png" | relative_url}}">
                                    </div>
                                </div>
                                <div class="col-sm-5 tour_info_content">
                                    <div class="arrow wow fadeInRight" data-wow-delay="0.9s">
                                        <img alt="" src="{{"img/arrow_3.png" | relative_url}}">
                                    </div>
                                    <p>Focus on questions about an actual problem you have faced. Include details about what you have tried and exactly what you are trying to do.</p>
                                </div>
                            </div>
                        </div>
                        <div class="border_bottom"></div>
                        <div class="tour_item">
                            <h4 class="c_head load-order-2">Tags make it easy to find interesting questions</h4>
                            <div class="row align-items-center">
                                <div class="col-sm-4 tour_info_content">
                                    <p>All questions are tagged with their subject areas. Each can have up to 5 tags, since a question might be related to several subjects.</p>
                                    <div class="arrow text-right wow fadeInLeft" data-wow-delay="0.6s">
                                        <img alt="" src="{{"img/arrow_bottom.png" | relative_url}}">
                                    </div>
                                </div>
                                <div class="col-sm-8">
                                    <div class="tour_preview_img wow fadeInRight" data-wow-delay="0.4s">
                                        <img alt="" class="img-fluid" src="{{"img/tour_img4.png" | relative_url}}">
                                    </div>
                                </div>
                            </div>
                        </div>
                        <div class="border_bottom"></div>
                        {% include doc_hotspots.html %}
                    </article>
                    <!--typography-->
                    <article class="shortcode_info documentation_body typography_content doc-section" id="typography-doc">
                        <div class="shortcode_title">
                            <h2>Typography</h2>
                            <p>
                                <span>Welcome to Docy !</span>
                                Documentation and examples for typography, including global settings, headings, body text, lists, and more.</p>
                        </div>
                        <h4 class="c_head load-order-2">Headings</h4>
                        <p>All HTML headings,
                            <code>&lt;h1&gt;</code>
                            through
                            <code>&lt;h6&gt;</code>, are available.</p>
                        <div class="code-preview">
                            <h1 class="h1">h1. Sample heading</h1>
                            <h2 class="h2">h2. Sample heading</h2>
                            <h3 class="h3">h3. Sample heading</h3>
                            <h4 class="h4">h4. Sample heading</h4>
                            <h5 class="h5">h5. Sample heading</h5>
                            <h6 class="h6">h6. Sample heading</h6>
                        </div>
                        <pre class="snippets">
                                    <code class="language-html" data-lang="html">
                                        &lt;h1&gt;h1. Sample heading&lt;h1&gt;
                                        &lt;h2&gt;h2. Sample heading&lt;h2&gt;
                                        &lt;h3&gt;h3. Sample heading&lt;h3&gt;
                                        &lt;h4&gt;h4. Sample heading&lt;h4&gt;
                                        &lt;h5&gt;h5. Sample heading&lt;h5&gt;
                                        &lt;h6&gt;h6. Sample heading&lt;h6&gt;
                                    </code>
                                </pre>
                        <p>
                            <code>.h1</code>
                            through
                            <code>.h6</code>
                            classes are also available, for when you want to match the font styling of a heading but cannot use the associated HTML element.</p>
                        <div class="code_item" id="code-doc">
                            <h4 class="c_head load-order-2" id="anchor">Anchor titles</h4>
                            <p>All HTML headings,
                                <code>&lt;h1&gt;</code>
                                through
                                <code>&lt;h6&gt;</code>, are available.</p>
                            <div class="code-preview">
                                <h5 id="header-name">Header Title<a class="anchor" href="#header-name"></a>
                                </h5>
                            </div>
                            <pre class="snippet">
                                        <code class="language-html" data-lang="html">
                                            &lt;h5 id="header-name"&gt;Header Title&lt;h5&gt;
                                        </code>
                                    </pre>
                        </div>
                        <div class="code_item">
                            <h4 class="c_head load-order-2" id="inline">Inline text elements</h4>
                            <p>Styling for common inline HTML5 elements.</p>
                            <div class="code-preview">
                                <p>You can use the mark tag to
                                    <mark>highlight</mark>
                                    text.</p>
                                <p>
                                    <del>This line of text is meant to be treated as deleted text.</del>
                                </p>
                                <p>
                                    <s>This line of text is meant to be treated as no longer accurate.</s>
                                </p>
                                <p>
                                    <ins>This line of text is meant to be treated as an addition to the document.</ins>
                                </p>
                                <p>
                                    <u>This line of text will render as underlined</u>
                                </p>
                                <p>
                                    <small>This line of text is meant to be treated as fine print.</small>
                                </p>
                                <p>
                                    <strong>This line rendered as bold text.</strong>
                                </p>
                                <p>
                                    <em>This line rendered as italicized text.</em>
                                </p>
                            </div>
                            <pre class="snippet">
                                        <code class="language-html" data-lang="html">
                                            &lt;p&gt;You can use the mark tag to &lt;mark&gt;highlight&lt;mark&gt; text.&lt;p&gt;
                                            &lt;p&gt;&lt;del&gt;This line of text is meant treated as deleted text.&lt;del&gt;&lt;p&gt;
                                            &lt;p&gt;&lt;s&gt;This line of text is meant treated as longer accurate.&lt;s&gt;&lt;p&gt;
                                            &lt;p&gt;&lt;ins&gt;This line text is meant treated addition document.&lt;ins&gt;&lt;p&gt;
                                            &lt;p&gt;&lt;u&gt;This line of text will render as underlined&lt;u&gt;&lt;p&gt;
                                            &lt;p&gt;&lt;small&gt;This line of text is meant to treated as fine.&lt;small&gt;&lt;p&gt;
                                            &lt;p&gt;&lt;strong&gt;This line rendered as bold text.&lt;strong&gt;&lt;p&gt;
                                            &lt;p&gt;&lt;em&gt;This line rendered as italicized text.&lt;em&gt;&lt;p&gt;
                                        </code>
                                    </pre>
                        </div>
                        <div class="code_item">
                            <h4 class="c_head load-order-2" id="list">Lists</h4>
                            <p>Display a list of items inside your content, rendered with a number, a bullet, or none.</p>
                            <div class="unorderlist">
                                <h4 class="c_head load-order-2">Unordered list</h4>
                                <code>&lt;ul&gt;</code>
                                <ul class="single_list">
                                    <li>Go to Theme Settings > Header Settings,</li>
                                    <li>Consectetur adipiscing elit</li>
                                    <li>Integer molestie lorem at massa</li>
                                    <li>Facilisis in pretium nisl aliquet</li>
                                </ul>
                            </div>
                            <div class="unorderlist">
                                <h4 class="c_head load-order-2">Ordered list</h4>
                                <code>&lt;ol&gt;</code>
                                <div class="steps-panel">
                                    <ol class="ordered-list">
                                        <li>Go to
                                            <span class="direction_steps">
                                                <span class="direction_step">Docy Settings</span>
                                                <span class="direction_step">Header</span>
                                                <span class="direction_step">Logo</span>
                                            </span>
                                        </li>
                                        <li>Consectetur adipiscing elit</li>
                                        <li>Integer molestie lorem at massa</li>
                                        <li>Facilisis in pretium nisl aliquet</li>
                                    </ol>
                                </div>
                            </div>
                        </div>
                        <div class="documentation_body typography_content" id="img-doc">
                            {% include doc_image.html %}
                        </div>
                        <div class="documentation_body typography_content" id="video-doc">
                            <div class="shortcode_title">
                                <h2>Video</h2>
                                <p>
                                    <span>Welcome to Docy !</span>Create responsive video or slideshow embeds based on the width of the parent by creating an intrinsic ratio that scales on any device.</p>
                            </div>
                            <h4 class="c_head load-order-2" id="about">About</h4>
                            <p>Rules are directly applied to
                                <code class="highlighter-rouge">&lt;iframe&gt;</code>,
                                <code class="highlighter-rouge">&lt;embed&gt;</code>,
                                <code class="highlighter-rouge">&lt;video&gt;</code>, and
                                <code class="highlighter-rouge">&lt;object&gt;</code>
                                elements; optionally use an explicit descendant class
                                <code class="highlighter-rouge">.embed-responsive-item</code>
                                when you want to match the styling for other attributes.</p>
                            <div class="code_item">
                                <h4 class="c_head load-order-2" id="example">Example</h4>
                                <p>Wrap any embed like an
                                    <code class="highlighter-rouge">&lt;iframe&gt;</code>
                                    in a parent element with
                                    <code class="highlighter-rouge">.embed-responsive</code>
                                    and an aspect ratio. The
                                    <code class="highlighter-rouge">.embed-responsive-item</code>
                                    isn’t strictly required, but we encourage it.</p>
                                <div class="code-preview">
                                    <div class="embed-responsive embed-responsive-16by9">
                                        <iframe allowfullscreen class="embed-responsive-item" src="https://www.youtube.com/embed/zpOULjyy-n8?rel=0"></iframe>
                                    </div>
                                </div>
                                <pre class="snippet">
                                            <code class="language-html" data-lang="html">
                                                &lt;div class="embed-responsive embed-responsive-16by9"&gt;
                                                    &lt;iframe class="embed-responsive-item" src="..." allowfullscreen&gt;&lt;iframe&gt;
                                                &lt;div&gt;
                                            </code>
                                        </pre>
                            </div>
                            <div class="code_item">
                                <h4 class="c_head load-order-2" id="ratio">Aspect ratios</h4>
                                <p>Aspect ratios can be customized with modifier classes.</p>
                                <pre class="snippet">
                                            <code class="language-html" data-lang="html">
                                                <!-- 21:9 aspect ratio -->
                                                &lt;div class="embed-responsive embed-responsive-21by9"&gt;
                                                  &lt;iframe class="embed-responsive-item" src="..."&gt;&lt;iframe&gt;
                                                &lt;div&gt;

                                                <!-- 16:9 aspect ratio -->
                                                &lt;div class="embed-responsive embed-responsive-16by9"&gt;
                                                  &lt;iframe class="embed-responsive-item" src="..."&gt;&lt;iframe&gt;
                                                &lt;div&gt;

                                                <!-- 4:3 aspect ratio -->
                                                &lt;div class="embed-responsive embed-responsive-4by3"&gt;
                                                  &lt;iframe class="embed-responsive-item" src="..."&gt;&lt;iframe&gt;
                                                &lt;div&gt;

                                                <!-- 1:1 aspect ratio -->
                                                &lt;div class="embed-responsive embed-responsive-1by1"&gt;
                                                  &lt;iframe class="embed-responsive-item" src="..."&gt;&lt;iframe&gt;
                                                &lt;div&gt;
                                            </code>
                                        </pre>
                            </div>
                            <div class="code_item">
                                <h4 class="c_head load-order-2" id="custom_video">Local Video</h4>
                                <p>While it's always better to host your videos on a video sharing website, but we provided a sample for you to include local videos in your pages.</p>
                                <div class="code-preview video_img" id="inline-popups">
                                    <img alt="" src="{{"img/blog-classic/single_post_img.jpg" | relative_url}}">
                                    <a class="popup-youtube video_icon" href="#vid2">
                                        <i class="arrow_triangle-right"></i>
                                    </a>
                                </div>
                            </div>
                        </div>
                    </article>
                    <div class="shortcode_info doc-section" id="changelog-doc">
                        {% include doc_changelog.html %}
                    </div>
                    <div class="shortcode_info doc-section" id="cheatsheet-doc">
                        {% include doc_cheatsheet.html %}
                    </div>
                </div>
            </div>
            <div class="col-lg-2 col-md-4 doc_right_mobile_menu">
                <div class="open_icon" id="right">
                    <i class="arrow_carrot-left"></i>
                    <i class="arrow_carrot-right"></i>
                </div>
                <div class="doc_rightsidebar scroll">
                    <div class="pageSideSection">
                        <select id="mySelect" name="os">
                            <option value="windows" data-content="<i class='fab fa-windows'></i> Windows">Windows
                            </option>
                            <option value="ios" data-content="<i class='fab fa-apple'></i> Ios">Ios</option>
                            <option value="linux" data-content="<i class='fab fa-linux'></i> Linux">Linux</option>
                        </select>
                        <div class="d-flex justify-content-between align-items-center" id="font-switcher">
                            <div class="fontsize-controllers group" id="rvfs-controllers"></div>
                            <a class="print" href="javascript:window.print()">
                                <i class="icon_printer"></i>
                            </a>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </div>
</section>

<footer class="simple_footer">
            <img class="leaf_right" src="{{"img/home_one/leaf_footter.png" | relative_url}}" alt="">
            <div class="container ">
                <div class="row">
                    <div class="col-lg-6">
                        <p>{{site.footer.copyright}}</p>
                    </div>
                    <div class="col-lg-6 text-right">
                        <ul class="list-unstyled f_social_icon">
                            <li><a href="{{site.social.facebook | relative_url}}"><i class="social_facebook"></i></a></li>
                            <li><a href="{{site.social.twitter | relative_url}}"><i class="social_twitter"></i></a></li>
                            <li><a href="{{site.social.vimeo | relative_url}}"><i class="social_vimeo"></i></a></li>
                            <li><a href="{{site.social.linkedin | relative_url}}"><i class="social_linkedin"></i></a></li>
                        </ul>
                    </div>
                </div>
            </div>
        </footer>