---
layout: page
show_meta: false
title: "Music Main Page"
subheadline: "Music Subheadline"
header:
    title: Music
    background-color: "#BB218C;"
permalink: /music/

---

### All Related Blog Posts
{: .t60 }

{% include list-posts tag='header' %}

---

<ul>
    {% for post in site.categories.music %}
    <li><a href="{{ site.url }}{{ site.baseurl }}{{ post.url }}">{{ post.title }}</a></li>
    {% endfor %}
</ul>