---
layout: page
title: Free and Open Source Software
permalink: /foss/
---

Stub page for Content regarding Linux and Free/Open Source Software.

<table>
<tr colalign=center colspan=3><th>Links</th></tr>
<tr><td><a href=http://www.linux.com/ target=_blank>Linux dot com</a></td><td><a href=http://www.linuxfoundation.org/ target=_blank>The Linux Foundation</a></td><td><a href=http://www.debian.org/ target=_blank>Debian dot org</a></td></tr>
<tr><td><a href=http://www.documentfoundation.org/ target=_blank>Open Document Foundation</a></td><td>.</td><td>.</td></tr>
</table>

<h2>Linux</h2>
<ul class="posts">
{% for post in site.posts %}
    {% if post.categories contains 'linux' %}
        <li><span>{{ post.date | date_to_string }}</span> &raquo; <a href="{{ BASE_PATH }}{{ post.url }}">{{ post.title }}</a></li>
    {% endif %}
{% endfor %}
</ul>
<h2>FOSS</h2>
<ul class="posts">
{% for post in site.posts %}
    {% if post.categories contains 'foss' %}
        <li><span>{{ post.date | date_to_string }}</span> &raquo; <a href="{{ BASE_PATH }}{{ post.url }}">{{ post.title }}</a></li>
    {% endif %}
{% endfor %}
</ul>