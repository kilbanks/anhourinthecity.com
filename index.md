---
layout: default
permalink: /
banner: portland
---
All your sad tears can stop flowing now because An Hour In The City has returned! A lot has changed since my last entry. I’ve gotten married, conquered my anxiety (for the most part), and moved to a different state!  Chris & I now live in Portland, OR and I thought what better way to embrace the rain than to walk in it for an hour!! 

If you read my last Hour In The City series, you know that I challenged myself to walk every day for an hour for thirty days. I’ve tweaked the Portland series a bit because I want to have more longevity with the concept, and also because frankly I’m too busy at this time in my life to do it every day. So join me as I learn all the hidden histories of my new city, complain about the rain, and hopefully drop a little weight!

<div class="tiles row">
  {% for post in site.categories.portland %}
    {% if post.published == true %}
      {% include tile.html post=post thumbnail_folder="portland" display="" %}
    {% endif %}
  {% endfor %}
</div>
