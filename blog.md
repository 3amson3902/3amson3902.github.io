---
layout: default
title: Blog
permalink: /blog/
---

# Blog

{% if site.posts.size > 0 %}
{% for post in site.posts %}
### [{{ post.title }}]({{ post.url }})

{{ post.date | date: "%B %d, %Y" }}

{{ post.excerpt }}

---
{% endfor %}
{% else %}
*No posts yet — stay tuned!*
{% endif %}
