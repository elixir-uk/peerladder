---
layout: default

search: true
navbar:
    type: menu_purple
    btnClass: not-tp-btn
    right_nav_tool: true
footer:
    class: bg-transparent
custom_js:
- js/jquery.parallax-scroll.js
- assets/mcustomscrollbar/jquery.mCustomScrollbar.concat.min.js
- assets/slick/slick.min.js
- assets/magnify-pop/jquery.magnific-popup.min.js
custom_css:
- assets/mcustomscrollbar/jquery.mCustomScrollbar.min.css
- assets/slick/slick.css
- assets/slick/slick-theme.css
---

{% include banner_one.html title="How can we help you?" subtitle="Search here to get answers to your questions" %}

{% include recommended_topic.html title="Recommended Topics" subtitle="Loaded with awesome features like Documentation,Knowledgebase,<br> Forum & more!" %}

{% include doc_testimonial.html %}
{% include doc_subscribe.html title="Great Customer <br>Relationships start here" %}

