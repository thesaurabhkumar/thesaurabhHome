---
layout: page
show_meta: false
title: "Trips & Planning"
subheadline: "My Travel"
header:
   image_fullwidth: "header-bus.jpg"
permalink: "/travel/"
---
<ul>
    {% for post in site.categories.travel %}
    <li><a href="{{ site.url }}{{ site.baseurl }}{{ post.url }}">{{ post.title }}</a></li>
    {% endfor %}
</ul>