---
layout: default
permalink: /
banner: balance
---

<div class="tiles row">
  {% for post in site.categories.portland %}
    {% if post.published == true %}
      {% include tile.html post=post thumbnail_folder="portland" display="" %}
    {% endif %}
  {% endfor %}
</div>
