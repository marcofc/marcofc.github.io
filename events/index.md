---
layout: default
---

{% for post in site.posts %}
  <h3>{{post.title}}</h3>
  {{ post.content }}
{% endfor %}
