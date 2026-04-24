---
title: Documentation
right_sidebar: false
noDocBottom: true
noDocPaginate: true
relatedDocs: true
---

<div class="doc-home-intro">
  <h1>Documentation</h1>
  <p>Everything you need to run the PeerLadder peer-mentoring programme. Pick a category below to get started.</p>
</div>

<div class="doc-home-grid">

{% for section in site.data.navigation_docs %}
  {% unless section.title == "Home" or section.title == "Change log" %}
  <div class="doc-home-card">
    <h3 class="doc-home-card__title">{{ section.title }}</h3>
    <ul class="doc-home-card__list">
      {% for slug in section.docs %}
        {% assign doc_url = slug | prepend: "/docs/" | append: "/" %}
        {% assign p = site.docs | where: "url", doc_url | first %}
        {% if p %}
        <li><a href="{{ p.url | relative_url }}">{{ p.title }}</a></li>
        {% endif %}
      {% endfor %}
    </ul>
  </div>
  {% endunless %}
{% endfor %}

  <div class="doc-home-card doc-home-card--changelog">
    <h3 class="doc-home-card__title">Change log</h3>
    <p class="doc-home-card__desc">Release notes and version history.</p>
    <a href="{{ '/docs/doc-changelog/' | relative_url }}" class="learn_btn">View changelog <i class="arrow_right"></i></a>
  </div>

</div>
