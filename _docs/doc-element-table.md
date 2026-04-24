---
title: Table
container: wide-container
right_sidebar: false
category: element
search: true
banner: false
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
## Markdown table

The simplest option – native markdown, no HTML required:

```markdown
| Column A     | Column B     | Column C     |
|--------------|--------------|--------------|
| Row 1 value  | Row 1 value  | Row 1 value  |
| Row 2 value  | Row 2 value  | Row 2 value  |
```

Column alignment with `:`:

```markdown
| Left  | Centre | Right  |
|:------|:------:|-------:|
| text  | text   | text   |
```

## Styled data table

For tables that need the theme's custom styling. Copy the HTML from `_TEMPLATE.md` → **Tables → Styled data table**.

Key points:
- Wrap in `.table-responsive` so it scrolls horizontally on small screens
- Add `id="myDataTable"` if you want DataTables sorting/filtering (requires DataTables JS in `custom_js`)

## Comparison / pricing table

A fixed-layout table suited to feature comparisons. Use `.icon_check_alt2.c_check` for ticks and `.icon_close_alt2.c_cross` for crosses.

Copy the HTML from `_TEMPLATE.md` → **Tables → Pricing / comparison table**.