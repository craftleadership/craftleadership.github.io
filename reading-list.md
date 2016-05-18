---
layout: default
---

## Reading list

{% for post in site.categories["reading"] %}
  * [{{ post.title }}]({{ post.url }}) - {{post.excerpt}}
{% endfor %}
