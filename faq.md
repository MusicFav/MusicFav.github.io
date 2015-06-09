---
layout: page
title: FAQ
excerpt:
---

## FAQ

<ul class="post-list">
{% for post in site.categories.faq %}
  <li>
    <article>
      <a href="{{ site.url }}{{ post.url }}">
        {{ post.title }}
        {% if post.excerpt %} <span class="excerpt">{{ post.excerpt }}</span>{% endif %}
      </a>
    </article>
  </li>
{% endfor %}
</ul>
