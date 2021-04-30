---
layout: page
show_meta: false
title: "Nepal"
subheadline: "My Photos"
sidebar: right
comments: true
breadcrumb: true
header:
   image_fullwidth: "posts/photography/header-general.png"
   title: Nepal
permalink: "/photography/nepal/"
---
<ul>
    {% for post in site.categories.nepal-photos %}
        {% include _page_entries.html %}
    {% endfor %}
</ul>