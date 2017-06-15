---
layout: page
title: About
permalink: /about/
---

A little about me. I'm a life long member of the Church of Jesus Christ, of Latter-day Saints (Mormons). I am also a lover of liberty, meaning freedom from state regulatory control. How do these tie together? Simply put, LDS belief regarding the freedom to make choices and liberty align.

I'm also a Linux user and hope to be a contributor in the near future. First in a non-coding fashion and maybe even as a coder later.

I have many other interests, of which old cars is one, but this site is not really to lay bare my entire life. Just a part.

About this site:

This is the base Jekyll theme. You can find out more info about customizing your Jekyll theme, as well as basic Jekyll usage documentation at [jekyllrb.com](http://jekyllrb.com/)

You can find the source code for the Jekyll new theme at:
{% include icon-github.html username="jglovier" %} /
[jekyll-new](https://github.com/jglovier/jekyll-new)

You can find the source code for Jekyll at
{% include icon-github.html username="jekyll" %} /
[jekyll](https://github.com/jekyll/jekyll)

### Site Updates
<ul class="posts">
{% for post in site.posts %}
    {% if post.categories contains 'site' %}
        <li><span>{{ post.date | date_to_string }}</span> &raquo; <a href="{{ BASE_PATH }}{{ post.url }}">{{ post.title }}</a></li>
    {% endif %}
{% endfor %}
</ul>
