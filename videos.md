---
title: Videos
layout: page
---

<ul class="post-list">
{%- for post in site.categories["video"] -%}
  {% include post-summary.html post=post %}
{% endfor %}
</ul>
