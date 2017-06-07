---
layout: page
title: Latter-Day Saints
permalink: /lds/
---

Stub for Links and List of Related Posts

### Links
[LDS Website](https://www.lds.org/) | [If you are interested](http://www.mormon.org/) | [Church Media](http://www.mormonchannel.org/)

### Posts
<ul class="posts">
{% for post in site.posts %}
    {% if post.categories contains 'lds' %}
        <li><span>{{ post.date | date_to_string }}</span> &raquo; <a href="{{ BASE_PATH }}{{ post.url }}">{{ post.title }}</a></li>
    {% endif %}
{% endfor %}
</ul>
