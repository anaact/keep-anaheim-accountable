---
title: Photos
layout: page
---

<ul class="post-list">
{%- for post in site.categories["photos"] -%}
  {% include post-summary.html post=post %}
{% endfor %}
</ul>
