---
layout: page
title: Linux
permalink: /linux/
---

Stub for Links and List of Related Posts

### Links
[Linux.com](http://www.linux.com/) | [The Linux Foundation](http://www.linuxfoundation.org/) | [Free Software Foundation](http://www.fsf.org/) |
[Fedora](https://getfedora.org/) | [Gnome](https://www.gnome.org/) | [KDE](https://www.kde.org/) |

### Posts
<ul class="posts">
{% for post in site.posts %}
    {% if post.categories contains 'linux' %}
        <li><span>{{ post.date | date_to_string }}</span> &raquo; <a href="{{ BASE_PATH }}{{ post.url }}">{{ post.title }}</a></li>
    {% endif %}
{% endfor %}
</ul>
