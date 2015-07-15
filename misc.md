---
layout: page
title: Misc.
permalink: /misc/
---

Stub page for Content misc posts

<table>
<tr colalign=center colspan=3><th>Links</th></tr>
<tr><td><a href=http://www.linux.com/ target=_blank>.</a></td><td><a href=http://www.linuxfoundation.org/ target=_blank>.</a></td><td><a href=http://www.debian.org/ target=_blank>.</a></td></tr>
<tr><td><a href=http://www.documentfoundation.org/ target=_blank>Open Document Foundation</a></td><td>.</td><td>.</td></tr>
</table>

<h2>Personal</h2>
<ul class="posts">
{% for post in site.posts %}
    {% if post.categories contains 'personal' %}
        <li><span>{{ post.date | date_to_string }}</span> &raquo; <a href="{{ BASE_PATH }}{{ post.url }}">{{ post.title }}</a></li>
    {% endif %}
{% endfor %}
</ul>
<h2>Site</h2>
<ul class="posts">
{% for post in site.posts %}
    {% if post.categories contains 'site' %}
        <li><span>{{ post.date | date_to_string }}</span> &raquo; <a href="{{ BASE_PATH }}{{ post.url }}">{{ post.title }}</a></li>
    {% endif %}
{% endfor %}
</ul>



