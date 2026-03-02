---
layout: default
title: Home
---

# Welcome

<!-- Short intro about yourself -->

---

## What I'm Working On

<!-- Current projects, interests, or focus areas -->

-
-
-

---

## Recent Posts

<!-- Jekyll will auto-list posts if you use the snippet below -->
{% for post in site.posts limit:5 %}
- [{{ post.title }}]({{ post.url }}) — {{ post.date | date: "%B %d, %Y" }}
{% endfor %}
