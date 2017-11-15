---
layout: page
title: "Blog"
permalink: /blog/
---

{% for post in site.posts %}
 <li><a href="{{ post.url}}" class="blog-posts">{{post.title}}</a></li>
{% endfor %}