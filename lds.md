---
layout: page
title: Latter-Day Saints
permalink: /lds/
---

Christian religion based on the universal atonement of Christ as the only way to return to the presence of God the Father predicated on our obedience to the Gospel of Christ. One of the core beliefs is that of agency, where one is free to make choices on how to live. This requires opposition, good and evil, so as to make informed choices. Continuing revelation is also a belief, which includes the existence of a prophet and apostles, who receive revelation for all of God's children and personal revelation to all who ask.

### Links
[LDS Website](https://www.lds.org/) | [If you are interested](http://www.mormon.org/) | [Church Media](http://www.mormonchannel.org/)

### Posts
<ul class="posts">
{% for post in site.posts %}
    {% if post.categories contains 'lds' %}
        <li><span>{{ post.date | date_to_string }}</span> &raquo; <a href="{{ BASE_PATH }}{{ post.url }}">{{ post.title }}</a></li>
    {% endif %}
{% endfor %}
</ul>
