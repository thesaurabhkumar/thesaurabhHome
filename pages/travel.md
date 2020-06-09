---
layout: page
show_meta: false
title: "Trips & Planning"
subheadline: "My Travel"
sidebar: right
comments: true
breadcrumb: true
header:
   image_fullwidth: "header-bus.jpg"
permalink: "/travel/"
---
<ul>
    {% for post in site.categories.travel %}
        {% include _page_entries.html %}
    {% endfor %}
</ul>