---
title: Public comments
layout: page
---

<ul class="post-list">
{%- for post in site.categories["public-comment"] -%}
  {% include post-summary.html post=post %}
{% endfor %}
</ul>
