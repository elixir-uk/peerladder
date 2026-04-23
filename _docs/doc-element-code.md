---
title: Source Code
container: wide-container
right_sidebar: true
search: true
banner: false
navbar:
    right_nav_tool: true
category: element
tags: [code,source,customize,element]
custom_js:
- assets/prism/prism.js
- js/jquery.parallax-scroll.js
- assets/font-size/js/rv-jquery-fontsize-2.0.3.min.js
- assets/mcustomscrollbar/jquery.mCustomScrollbar.concat.min.js
- js/anchor.js
- assets/bootstrap/js/bootstrap-select.min.js
custom_css:
- assets/prism/prism.css
- assets/font-size/css/rvfs.css
- assets/mcustomscrollbar/jquery.mCustomScrollbar.min.css
- assets/bootstrap/css/bootstrap-select.min.css
---
## Fenced code blocks (markdown)

Prefer this over raw HTML — Kramdown renders fenced blocks natively and Prism.js adds syntax highlighting automatically.

````markdown
```html
<p>Your HTML here</p>
```

```javascript
const greeting = 'hello';
```

```css
body { color: #333; }
```

```bash
jekyll serve --livereload
```
````

Supported language identifiers include: `html`, `css`, `javascript`, `json`, `bash`, `ruby`, `python`, `php`, `yaml`, `markdown`.

## Inline code

Wrap with single backticks: `` `code` `` renders as `<code>code</code>`.

## Highlighted text

Use the HTML `<mark>` tag inline in any paragraph:

```html
This is <mark>highlighted text</mark> in a sentence.
```

## Styled highlight block (Prism.js)

For a more prominent code display with the theme's styling. Copy from `_TEMPLATE.md` → **Code Blocks → Styled highlight block**.

Note: the `code` tag `data-lang` attribute is for display only — it does not affect syntax highlighting. Use the correct `language-*` class for Prism.