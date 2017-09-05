---
layout: page
title: Blog
permalink: /blog/
---

``There is much pleasure to be gained from useless knowledge." -- Bertrand Russell

Much (if not all) of this Blog is a collection of useless stuff. A full listing of my blog posts follows.

### Notes

A collection of some of my notes. Some of them were written for teaching purposes, while others were written for entertainment. In case you find any blunders/errors/typos/grammatical mistakes (however small or big it might be), I would greatly appreciate if you could let me know.


<ul class="listing">
{% for post in site.posts %}
  {% capture y %}{{post.date | date:"%Y"}}{% endcapture %}
  {% if year != y %}
    {% assign year = y %}
    <li class="listing-seperator">{{ y }}</li>
  {% endif %}
  <li class="listing-item">
    <time datetime="{{ post.date | date:"%Y-%m-%d" }}">{{ post.date | date:"%Y-%m-%d" }}</time>
    <a href="{{ post.url }}" title="{{ post.title }}">{{ post.title }}</a>
  </li>
{% endfor %}
</ul>
