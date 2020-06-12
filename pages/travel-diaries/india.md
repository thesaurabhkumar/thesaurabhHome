---
layout: page
show_meta: false
title: "India"
subheadline: "My Travel"
sidebar: right
comments: true
breadcrumb: true
header:
   image_fullwidth: "pages/travel-diaries/india/india-header.jpg"
permalink: "/travel-diaries/india/"
---
<ul>
    {% for post in site.tags.india %}
        {% include _page_entries.html %}
    {% endfor %}
</ul>