---
layout: page
title: Latter-Day Saints
permalink: /lds/
---

Stub page for Content regarding Mormonism and The Church of Jesus Christ, of Latter-Day Saints.

<h3>Links</h3>
* [LDS Website](https://www.lds.org/)
* [Mormon dot org](http://www.mormon.org/)
* [The Mormon Channel](http://www.mormonchannel.org/)

<h2>LDS</h2>
<ul class="posts">
{% for post in site.posts %}
    {% if post.categories contains 'lds' %}
        <li><span>{{ post.date | date_to_string }}</span> &raquo; <a href="{{ BASE_PATH }}{{ post.url }}">{{ post.title }}</a></li>
    {% endif %}
{% endfor %}
</ul>