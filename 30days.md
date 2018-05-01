---
layout: default
title: Walk This Way
permalink: /walkthisway
banner: walkthisway
---
# Walk This Way

Welcome! My name is Kayla and I’m flaky... but mostly when it comes to myself. How many times have we all promised to commit to ourselves be it working out, eating healthy, or learning an instrument, just to have it fall through? If you never have then join the X-men, because you’re a mutant. Now that I’m 27 I find myself wanting to commit to myself more and more, and actually stick with it. Novel concept, I know.

I invite you all to join me  on my birthday gift to myself, a commitment to walking an hour every day for 30 days & writing about what I see. I live in San Francisco, so an hour long walk is bound to be entertaining. Or maybe it won’t & I’ll be miserable, who knows. This commitment seems small in the grand scheme of things, but it’s mine & I like it. I hope you will too.

<div class="tiles row">
  {% for post in site.categories.walkthisway reversed %}
    {% if post.published == true %}
      {% include tile.html post=post display="" %}
    {% endif %}
  {% endfor %}
</div>
