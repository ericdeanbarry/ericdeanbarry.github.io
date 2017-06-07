---
layout: page
title: Liberty
permalink: /liberty/
---

Stub for Links and List of Related Posts

### Links

### Liberty
<ul class="posts">
{% for post in site.posts %}
    {% if post.categories contains 'liberty' %}
        <li><span>{{ post.date | date_to_string }}</span> &raquo; <a href="{{ BASE_PATH }}{{ post.url }}">{{ post.title }}</a></li>
    {% endif %}
{% endfor %}
</ul>
### Economics
<ul class="posts">
{% for post in site.posts %}
    {% if post.categories contains 'economics' %}
        <li><span>{{ post.date | date_to_string }}</span> &raquo; <a href="{{ BASE_PATH }}{{ post.url }}">{{ post.title }}</a></li>
    {% endif %}
{% endfor %}
</ul>
### Libertarians
<ul class="posts">
{% for post in site.posts %}
    {% if post.categories contains 'libertarian' %}
        <li><span>{{ post.date | date_to_string }}</span> &raquo; <a href="{{ BASE_PATH }}{{ post.url }}">{{ post.title }}</a></li>
    {% endif %}
{% endfor %}
</ul>
