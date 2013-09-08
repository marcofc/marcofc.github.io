---
layout: default
---

{% for post in site.tags.event %}
  Posted {{ post.date | date: "%B %e, %Y" }}
  <h3>{{ post.title }}</h3>
  {{ post.content }}
{% endfor %}
