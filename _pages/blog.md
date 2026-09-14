---
layout: page
title: Blog
include_in_header: true
---

<div class="blogList">
  {% if site.posts.size > 0 %}
    {% for post in site.posts %}
      <article class="blogCard">
        <p class="blogMeta">{{ post.date | date: "%b %-d, %Y" }}</p>
        <h3><a href="{{ post.url | relative_url }}">{{ post.title }}</a></h3>
        <p>{{ post.excerpt | strip_html | truncatewords: 30 }}</p>
        <a class="blogReadMore" href="{{ post.url | relative_url }}">Read article</a>
      </article>
    {% endfor %}
  {% endif %}
</div>
