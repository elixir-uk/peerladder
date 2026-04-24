---
# ── Required for all post types ───────────────────────────────────────────────
title:        Post Title Here
category:     articles   # articles | news | events

# ── Author (articles and news) ────────────────────────────────────────────────
author:       Full Name
avatar:       img/avatars/firstname-lastname.webp   # shown on story card

# ── Events only — remove these lines for articles/news ───────────────────────
event_date:   2026-09-01        # YYYY-MM-DD — controls upcoming vs past sorting
event_location: Manchester, UK  # optional

# ── Card thumbnail ────────────────────────────────────────────────────────────
post_img:     img/posts/your-image.jpg

# ── Optional ──────────────────────────────────────────────────────────────────
timeToRead:   5 Min Read        # articles/news only
comments:     false
---

<!-- The image at the top of the full post page -->
[![Post image]({{ 'img/posts/your-image.jpg' | relative_url }})]({{ 'img/posts/your-image.jpg' | relative_url }})

<!-- excerpt-start -->
This is the excerpt that appears on the card. Keep it to 1–2 sentences — everything after this comment up to ~120 characters will be shown as the card preview.

Full post content continues here in Markdown. The excerpt-start comment above marks where the card snippet begins — everything before it is ignored in the card view.

## Section heading

Regular paragraph text. You can use all standard Markdown here — headings, lists, blockquotes, links, bold, italic.

- List item one
- List item two
- List item three

> Blockquote text here.
>
> — Attribution

More body content here.
