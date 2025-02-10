---
title: Blog
---

{% for post in site.posts limit:3 %}
- **[{{post.title}}]({{post.url}})** - {{post.date | date: "%B %d, %Y"}}
{% endfor %}
