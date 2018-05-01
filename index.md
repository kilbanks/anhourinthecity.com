---
layout: default
permalink: /
banner: balance
---
I have curly hair...well I used to. All the hot tools I've used over the last year or two have totally destroyed every ringlet or wave that I had. Good bye Shirley Temple, hello Scarecrow - except instead of wishing for a brain, I'm wishing for gorgeous curls again.

Over the next month I'm going to set out on a journey to reclaim my goldilocks, and I'm going to share it with all of you! The good, the bad, and the bound to be ugly. For 31 days I won't even look twice at a hot tool, well maybe I'll look once and then quickly look away before I'm tempted, because I do love my curling iron. My hair is my crowning glory, (ba dum tss) and letting it have a mind of its own will be difficult, but I'm hoping that this May will bring not only flowers but also beautiful golden ringlets! 

Let the challenge begin. 

<div class="tiles row">
  {% for post in site.categories.hair %}
    {% if post.published == true %}
      {% include tile.html post=post display="" %}
    {% endif %}
  {% endfor %}
</div>
