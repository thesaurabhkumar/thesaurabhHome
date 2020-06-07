---
layout: page
show_meta: false
title: "Posts"
subheadline: "My Music"
header:
   image_fullwidth: "posts/lifestyle/music/chord-guitar-header.jpg"
permalink: "/lifestyle/music/"
---
<ul>
    {% for post in site.categories.music %}
    <li><a href="{{ site.url }}{{ site.baseurl }}{{ post.url }}">{{ post.title }} - {{post.subheadline}}</a></li>
    {% endfor %}
</ul>