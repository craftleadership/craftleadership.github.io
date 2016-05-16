---
layout: default
---
{% include logo-big.html %}

<div class="landing-site-description">{{ site.description }}</div>

# Published thinking

{% for page in site.pages %}
  {% if page.category == "homepage"  %}
* **[{{ page.title }}]({{ page.url | prepend: site.baseurl }})** *{{ page.slug }}*
  {% endif %}
{% endfor %}

___

# Backlog*

## Leadership
* First time leadership advice from other first time leaders
* What happens when agile says managers don't get to tell us what to do anymore?

## Personal Craft development
* Dojos, katas, code camps
* Algorithms matter, now more than ever

## Professionalism
* Pressure and craftsmanship
* Elevating the craft as an individual contributor; holding your peers accountable

## Methods
* Agile is a conclusion more than it is a process

## Teamwork
* We are all impostors
* Empathy

&lowast; The backlog captures the articles we think would be cool to have on Craft, Leadership. And we would love your contributions on any of the backlog articles. Not ready to add an article? Help us grow and groom the backlog. [Fork us on Github](https://github.com/craftleadership/craftleadership.github.io) or send Michael Rice an email at [me@michaelrice.com](mailto:me@michaelrice.com)
