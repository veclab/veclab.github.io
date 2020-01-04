---
layout: page
show_meta: false
title: "Information and news!"
subheadline: "Information articles"
header:
   image_fullwidth: "header_unsplash_5.jpg"
permalink: "/information/"
---
<ul>
    {% for post in site.categories.information %}
    <li><a href="{{ site.url }}{{ post.url }}">{{ post.title }}</a></li>
    {% endfor %}
</ul>
