---
layout: page
title: Liberty
permalink: /liberty/
---

I am an anarchist. Strictly speaking, anarchy means no rulers, not no rules. There are plenty of rules, though in an anarchist society they are created and impact only those that voluntarily agree to them. Most will not like this arrangement and will want some kind of central state to govern their lives for them. This is acceptable so long as it does not include those that do not want to be governed by said state.


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
