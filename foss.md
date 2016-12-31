---
layout: page
title: Free and Open Source Software
permalink: /foss/
---

Stub page for Content regarding Linux and Free/Open Source Software.

### Links
[Linux.com](http://www.linux.com/) | [The Linux Foundation](http://www.linuxfoundation.org/) | [Free Software Foundation](http://www.fsf.org/)  
[Kubuntu](http://www.kubuntu.org/) | [KDE](https://www.kde.org/) | 

### Linux
<ul class="posts">
{% for post in site.posts %}
    {% if post.categories contains 'linux' %}
        <li><span>{{ post.date | date_to_string }}</span> &raquo; <a href="{{ BASE_PATH }}{{ post.url }}">{{ post.title }}</a></li>
    {% endif %}
{% endfor %}
</ul>
### FOSS
<ul class="posts">
{% for post in site.posts %}
    {% if post.categories contains 'foss' %}
        <li><span>{{ post.date | date_to_string }}</span> &raquo; <a href="{{ BASE_PATH }}{{ post.url }}">{{ post.title }}</a></li>
    {% endif %}
{% endfor %}
</ul>
