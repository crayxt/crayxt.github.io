---
layout: page
title: Hello World!
tagline: 
---
{% include JB/setup %}

My blog, baurzhan.info, moved to Github pages.

Below is the posts list.

<ul class="posts">
  {% for post in site.posts %}
    <li><span>{{ post.date | date_to_string }}</span> &raquo; <a href="{{ BASE_PATH }}{{ post.url }}">{{ post.title }}</a></li>
  {% endfor %}
</ul>


