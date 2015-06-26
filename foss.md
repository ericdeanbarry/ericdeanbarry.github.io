---
layout: page
title: Free and Open Source Software
permalink: /foss/
---

Stub page for Content regarding Linux and Free/Open Source Software.

<h3>Links</h3>
* [Linux dot com](http://www.linux.com/)
* [The Linux Foundation](http://www.linuxfoundation.org/)
* [Debian dot org](http://www.debian.org/)
* [Open Document Foundation](https://www.documentfoundation.org/)

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