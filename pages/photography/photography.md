---
layout: page
show_meta: false
title: "Photography"
subheadline: "My Photos"
sidebar: right
comments: true
breadcrumb: true
header:
   image_fullwidth: "posts/photography/header-general.png"
   title: "Photography"
permalink: "/photography/"
---
<ul>
    {% for post in site.categories.photos %}
        {% include _page_entries.html %}
    {% endfor %}
</ul>