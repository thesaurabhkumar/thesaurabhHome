---
layout: page
show_meta: false
title: "Discussion Topics"
subheadline: "Technical Posts"
header:
   image_fullwidth: "header_unsplash_5.jpg"
permalink: "/technical/"
---
<ul>
    {% for post in site.categories.technical %}
    <li><a href="{{ site.url }}{{ site.baseurl }}{{ post.url }}">{{ post.title }}</a></li>
    {% endfor %}
</ul>