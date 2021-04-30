---
layout: page
show_meta: false
title: "India"
subheadline: "My Photos"
sidebar: right
comments: true
breadcrumb: true
header:
   image_fullwidth: "posts/photography/header-general.png"
   title: India
permalink: "/photography/india/"
---
<ul>
    {% for post in site.categories.india-photos %}
        {% include _page_entries.html %}
    {% endfor %}
</ul>