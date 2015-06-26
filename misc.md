---
layout: page
title: Misc.
permalink: /misc/
---

Stub page for Content misc posts

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



