---
layout: page
show_meta: false
title: "Trips & Planning"
subheadline: "My Travel"
sidebar: right
comments: true
breadcrumb: true
header:
   image_fullwidth: "headers/header-bus.jpg"
permalink: "/travel-diaries/"
---
<ul>
    {% for post in site.categories.travel-diaries %}
        {% include _page_entries.html %}
    {% endfor %}
</ul>