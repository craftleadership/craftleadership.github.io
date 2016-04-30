---
layout: default
---
{% include logo-big.html %}

<div class="landing-site-description">{{ site.description }}</div>

Teamwork
-------
{% for page in site.pages %}
  {% if page.category == "teamwork" %}
  * **[{{ page.title }}]({{ page.url | prepend: site.baseurl }})** *{{ page.slug }}*
  {% endif %}
{% endfor %}
