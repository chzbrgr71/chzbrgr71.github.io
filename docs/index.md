---
layout: libdoc/page
---

Welcome to the Azure Kubernetes Service (AKS) Engineering Blog. 

Blog posts:
<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url }}">{{ post.title }}</a>{{ post.description }}
    </li>
  {% endfor %}
</ul>