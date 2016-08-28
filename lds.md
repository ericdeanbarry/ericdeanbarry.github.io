---
layout: page
title: Latter-Day Saints
permalink: /lds/
---

Stub page for Content regarding Mormonism and The Church of Jesus Christ, of Latter-Day Saints.

<table>
<tr><th>Links</th></tr>
<tr><td><a href=https://www.lds.org/ target=_blank>LDS Website</a></td><td><a href=http://www.mormon.org/ target=_blank>Mormon dot org</a></td><td><a http://www.mormonchannel.org/ target=_blank>The Mormon Channel</a></td></tr>
</table>

<h2>LDS</h2>
<ul class="posts">
{% for post in site.posts %}
    {% if post.categories contains 'lds' %}
        <li><span>{{ post.date | date_to_string }}</span> &raquo; <a href="{{ BASE_PATH }}{{ post.url }}">{{ post.title }}</a></li>
    {% endif %}
{% endfor %}
</ul>
