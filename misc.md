---
layout: page
title: Misc.
permalink: /misc/
---

Stub page for Content misc posts

### Links

### Personal
<ul class="posts">
{% for post in site.posts %}
    {% if post.categories contains 'personal' %}
        <li><span>{{ post.date | date_to_string }}</span> &raquo; <a href="{{ BASE_PATH }}{{ post.url }}">{{ post.title }}</a></li>
    {% endif %}
{% endfor %}
</ul>

### Site
<ul class="posts">
{% for post in site.posts %}
    {% if post.categories contains 'site' %}
        <li><span>{{ post.date | date_to_string }}</span> &raquo; <a href="{{ BASE_PATH }}{{ post.url }}">{{ post.title }}</a></li>
    {% endif %}
{% endfor %}
</ul>



