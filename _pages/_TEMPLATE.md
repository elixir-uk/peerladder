---
published: false
---

# Component & Typography Reference

This file is never published (`published: false` + `_` prefix). Use it as a copy-paste reference
when building doc pages. Paste HTML blocks directly into any `.md` file — Kramdown renders
inline HTML alongside markdown without issue.

---

## Typography

### Headings

```html
<h1 class="h1 bold">Heading one</h1>
<h2 class="h2 bold">Heading two</h2>
<h3 class="h3 bold">Heading three</h3>
<h4 class="h4 bold">Heading four</h4>
<h5 class="h5 bold">Heading five</h5>
<h6 class="h6 bold">Heading six</h6>
```

Modifier classes: `bold`, `medium`, `regular`

### Highlight spans

```html
<span class="h_black">black highlight</span>
<span class="h_green">green highlight</span>
<span class="h_blue">blue highlight</span>
```

### Dropcap

```html
<!-- Big dropcap -->
<p><span>K</span>our content here...</p>

<!-- Rectangle dropcap -->
<p><span class="r_dropcap">A</span>your content here...</p>
```

### Blockquote

```html
<blockquote class="blockquote">
    <p class="mb-0">Your quote text here.</p>
</blockquote>

<!-- Single-line pull quote -->
<blockquote class="blockquote_two">
    <h5 class="mb-0 h5">
        <span class="quote_icon">,,</span>Your quote here.
    </h5>
</blockquote>
```

### Direction steps (breadcrumb path)

```html
<span class="direction_steps">
    <span class="direction_step">Settings</span>
    <span class="direction_step">Header</span>
    <span class="direction_step">Logo</span>
</span>
```

### Buttons

```html
<!-- Filled buttons -->
<a class="action_btn btn_small" href="#">Small</a>
<a class="action_btn btn_small_two" href="#">Medium</a>
<a class="action_btn btn_bg" href="#">Large</a>
<a class="action_btn btn_radious_none" href="#">No radius</a>
<a class="action_btn btn_radious_45" href="#">Pill</a>

<!-- Border buttons -->
<a class="doc_border_btn btn_small" href="#">Small</a>
<a class="doc_border_btn doc_border_btn_two" href="#">Medium</a>
<a class="doc_border_btn btn_bg" href="#">Large</a>

<!-- Icon buttons -->
<a class="nav_btn icon_btn" href="#"><i class="icon_profile"></i>Log In</a>
<a class="doc_border_btn arrow_btn_medium" href="#">View All Docs<i class="arrow_right"></i></a>
<a class="doc_border_btn arrow_btn_big" href="#">Live Chat Now<i class="icon_chat_alt"></i></a>
```

### Lists

```html
<!-- Unordered custom list -->
<ul class="list-unstyled unorderlist">
    <li><a href="#">Item one</a></li>
    <li><a href="#">Item two</a></li>
</ul>

<!-- Ordered steps panel -->
<div class="steps-panel">
    <ol class="ordered-list">
        <li>Go to <span class="direction_steps"><span class="direction_step">Settings</span></span></li>
        <li>Next step here</li>
    </ol>
</div>
```

---

## Accordion / Toggle

### Toggle (collapse)

Requires Bootstrap collapse JS. IDs must be unique per page.

```html
<a class="toggle_btn" data-toggle="collapse" href="#toggle1" role="button"
   aria-expanded="false" aria-controls="toggle1">Section Title</a>
<div class="collapse multi-collapse show" id="toggle1">
    <div class="card card-body toggle_body">
        Your content here.
    </div>
</div>

<a class="toggle_btn mt-3 collapsed" data-toggle="collapse" href="#toggle2" role="button"
   aria-expanded="false" aria-controls="toggle2">Another Section</a>
<div class="collapse multi-collapse" id="toggle2">
    <div class="card card-body toggle_body">
        Your content here.
    </div>
</div>
```

### Accordion (mutually exclusive panels)

Wrap multiple `.card.doc_accordion` blocks in a parent with `id="accordion"`.

```html
<div class="card doc_accordion">
    <div class="card-header" id="headingOne">
        <h5 class="mb-0">
            <button class="btn btn-link" data-toggle="collapse" data-target="#collapseOne"
                    aria-expanded="true" aria-controls="collapseOne">
                Panel Title
                <svg fill="none" height="15" viewBox="0 0 14 15" width="14" xmlns="http://www.w3.org/2000/svg">
                    <path d="M13 7.38812H1M7 1.38812V13.3881V1.38812Z" stroke-linecap="round" stroke-linejoin="round" stroke-width="2" stroke="#6b707f"/>
                </svg>
                <svg fill="none" height="3" viewBox="0 0 14 3" width="14" xmlns="http://www.w3.org/2000/svg">
                    <path d="M13 1.38812H1" stroke-linecap="round" stroke-linejoin="round" stroke-width="2" stroke="#6b707f"/>
                </svg>
            </button>
        </h5>
    </div>
    <div id="collapseOne" class="collapse show" aria-labelledby="headingOne" data-parent="#accordion">
        <div class="card-body toggle_body">
            Your content here.
        </div>
    </div>
</div>
```

---

## Tabs

Requires Bootstrap tab JS. IDs must be unique per page.

```html
<ul class="nav nav-tabs" id="myTab" role="tablist">
    <li class="nav-item">
        <a class="nav-link active" id="tab1-tab" data-toggle="tab" href="#tab1"
           role="tab" aria-controls="tab1" aria-selected="true">Tab One</a>
    </li>
    <li class="nav-item">
        <a class="nav-link" id="tab2-tab" data-toggle="tab" href="#tab2"
           role="tab" aria-controls="tab2" aria-selected="false">Tab Two</a>
    </li>
</ul>
<div class="tab-content" id="myTabContent">
    <div class="tab-pane fade show active" id="tab1" role="tabpanel" aria-labelledby="tab1-tab">
        Content for tab one.
    </div>
    <div class="tab-pane fade" id="tab2" role="tabpanel" aria-labelledby="tab2-tab">
        Content for tab two.
    </div>
</div>
```

### Vertical tabs

```html
<div class="row">
    <div class="col-3">
        <div class="nav flex-column nav-pills" id="v-pills-tab" role="tablist"
             aria-orientation="vertical">
            <a class="nav-link active" id="v-tab1-tab" data-toggle="pill" href="#v-tab1"
               role="tab">Tab One</a>
            <a class="nav-link" id="v-tab2-tab" data-toggle="pill" href="#v-tab2"
               role="tab">Tab Two</a>
        </div>
    </div>
    <div class="col-9">
        <div class="tab-content" id="v-pills-tabContent">
            <div class="tab-pane fade show active" id="v-tab1" role="tabpanel">Content one.</div>
            <div class="tab-pane fade" id="v-tab2" role="tabpanel">Content two.</div>
        </div>
    </div>
</div>
```

---

## Tables

### Standard Bootstrap table (markdown-compatible)

You can write simple tables in markdown — Jekyll renders them natively:

```markdown
| Column A | Column B | Column C |
|----------|----------|----------|
| Value    | Value    | Value    |
```

### Styled data table (HTML, requires DataTables JS if sortable)

```html
<div class="data_table_area table-responsive">
    <table class="table" id="myDataTable">
        <thead>
            <tr>
                <th>Name</th>
                <th>Role</th>
                <th>Location</th>
            </tr>
        </thead>
        <tbody>
            <tr>
                <td>Jane Smith</td>
                <td>Engineer</td>
                <td>London</td>
            </tr>
        </tbody>
    </table>
</div>
```

### Pricing / comparison table

```html
<div class="price_table_area">
    <div class="table-responsive">
        <table class="table price_table">
            <thead>
                <tr>
                    <th></th>
                    <th>Basic</th>
                    <th>Pro</th>
                </tr>
            </thead>
            <tbody>
                <tr>
                    <td>Feature one</td>
                    <td><i class="icon_check_alt2 c_check"></i></td>
                    <td><i class="icon_check_alt2 c_check"></i></td>
                </tr>
                <tr>
                    <td>Feature two</td>
                    <td><i class="icon_close_alt2 c_cross"></i></td>
                    <td><i class="icon_check_alt2 c_check"></i></td>
                </tr>
            </tbody>
        </table>
    </div>
</div>
```

---

## Image Hotspots

Clickable dot overlays on an image. Each numbered `<li>` pairs a trigger dot with a dropdown.

```html
<div class="pointing_img_container pointing_img_two">
    <div class="divs">
        <div class="cls1">1</div>
        <div class="cls2">2</div>
    </div>
    <img class="img-fluid" src="{{ 'img/your-image.jpg' | relative_url }}" alt="Hotspot image">
    <ul class="nav list">
        <li class="cls1">
            <div class="img_pointing one" data-toggle="dropdown" role="button"
                 aria-haspopup="true" aria-expanded="false">
                <div class="dot"></div>
            </div>
            <div class="dropdown-menu">
                <div class="text_part">
                    <div class="close_btn">
                        <img src="{{ 'img/svg/close.svg' | relative_url }}" alt="">
                    </div>
                    <h4>Hotspot Title <span>1/2</span></h4>
                    <p>Description for this hotspot.</p>
                </div>
                <div class="row">
                    <div class="col-3"><div class="prev">prev</div></div>
                    <div class="col-6">
                        <div class="bullets_pointing">
                            <ul class="nav justify-content-center"><li></li><li></li></ul>
                        </div>
                    </div>
                    <div class="col-3"><div class="next">next</div></div>
                </div>
            </div>
        </li>
    </ul>
</div>
```

---

## Lightbox

### Simple image lightbox

```html
<div class="lightbox_shortcode">
    <img src="{{ 'img/your-thumb.jpg' | relative_url }}" alt="Preview">
    <a href="{{ 'img/your-large.jpg' | relative_url }}" class="img_popup">
        <i class="icon_plus"></i>
    </a>
</div>
```

### Modal lightbox with hotspot dots

```html
<!-- Trigger -->
<a data-toggle="modal" data-target="#myLightboxModal" href="#">
    <img src="{{ 'img/your-thumb.jpg' | relative_url }}" alt="">
</a>

<!-- Modal -->
<div class="modal fade img_modal" id="myLightboxModal" tabindex="-1" role="dialog" aria-hidden="true">
    <button type="button" class="close" data-dismiss="modal" aria-label="Close">
        <i class="icon_close"></i>
    </button>
    <div class="modal-dialog pointing_img_container" role="document">
        <div class="modal-content">
            <img src="{{ 'img/your-large.jpg' | relative_url }}" alt="">
            <div class="img_pointing one tooltips" data-tooltip-content="#tip1">
                <div class="dot"></div>
            </div>
        </div>
    </div>
</div>

<!-- Tooltip content for the dot (hidden) -->
<div class="tooltip_templates d-none">
    <div class="tip_content" id="tip1">
        <div class="text">
            <p>Tooltip description here.</p>
        </div>
    </div>
</div>
```

---

## Code Blocks

Markdown fenced blocks work natively — prefer these over raw HTML:

````markdown
```html
<p>Your HTML here</p>
```

```javascript
const x = 1;
```

```css
body { color: red; }
```
````

### Styled highlight block (HTML, uses Prism.js)

```html
<div class="highlight">
    <pre>
        <code class="language-html" data-lang="html">
            &lt;p&gt;Your escaped HTML here&lt;/p&gt;
        </code>
    </pre>
</div>
```

### Inline code

Use standard markdown backticks: `` `code` `` renders as `<code>`.

---

## Interface Tour

A guided step-by-step walkthrough layout. Each `.tour_item` is one step.

```html
<div class="tour_content">
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

    <div class="border_bottom"></div>

    <div class="tour_item">
        <h4 class="c_head load-order-2">Next step title</h4>
        <div class="row align-items-center">
            <div class="col-sm-5 tour_info_content">
                <p>Description of this step.</p>
            </div>
            <div class="col-sm-7">
                <img src="{{ 'img/your-screenshot.jpg' | relative_url }}" alt="" class="img-fluid">
            </div>
        </div>
    </div>
</div>
```

---

## Footnotes

Footnote links in body text, with a numbered list at the bottom of the page.

```html
<!-- In body text: -->
<p>
    Your paragraph with a footnote reference
    <a class="footnotes-link tooltips" href="#note-name-a" id="note-link-1"
       data-tooltip-content="#note-link-a"></a>
    continuing after the reference.
</p>

<!-- At the bottom of the page: -->
<div class="footnotes margin-top-xl">
    <h4>Footnotes</h4>
    <ol>
        <li class="footnotes_item" id="note-name-a">
            <a class="back-article" href="#note-link-1" aria-label="Back to article">
                <ion-icon name="arrow-up"></ion-icon>
            </a>
            <strong>Source Name</strong><br>
            Full citation or description here.
        </li>
    </ol>
</div>

<!-- Tooltip preview content (hidden, shown on hover): -->
<div class="tooltip_templates d-none">
    <div class="tip_content" id="note-link-a">
        <div class="text">
            <p>Short preview of the footnote.</p>
        </div>
    </div>
</div>
```

---

## Tooltip (rich hover card)

Requires tooltipster or the custom tooltip JS already loaded on pages using `custom_js`.

```html
<!-- Trigger link -->
<a class="tooltips" href="#" data-tooltip-content="#myTooltip">Hover over me</a>

<!-- Tooltip content (hidden) -->
<div class="tooltip_templates d-none">
    <div class="tip_content" id="myTooltip">
        <img src="{{ 'img/your-image.jpg' | relative_url }}" alt="">
        <div class="text">
            <p>Tooltip body text here.</p>
            <h6>Related: <span>Link title</span></h6>
        </div>
    </div>
</div>
```

### Bootstrap tooltip (simple, title attribute)

```html
<span data-toggle="tooltip" data-placement="top" title="Tooltip text">Hover me</span>
```
