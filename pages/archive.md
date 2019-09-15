---
layout: page
show_meta: false
title: "Archived Resources"
subheadline: "Articles, Devotions, & Sermons"
header:
   image_fullwidth: "header_unsplash_5.jpg"
permalink: "/archive/"
---
<ul>
    {% for post in site.categories.design %}
    <li><a href="{{ site.url }}{{ site.baseurl }}{{ post.url }}">{{ post.title }}</a></li>
    {% endfor %}
</ul>
