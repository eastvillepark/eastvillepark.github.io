---
layout: page
---

{% for post in site.newsletters %}
    <a href="{{ post.url | absolute_url }}">
      {{ post.title }}
    </a>
{% endfor %}
