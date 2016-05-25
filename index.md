---
layout: default
---

## {{ site.description }}

### Coming Summer 2016 <i class="fa fa-volume-up" aria-hidden="true"></i>

Craft + Leadership will (if we can get enough love and content) be a podcast, blog, and library of useful information for software engineering managers.

Seems like the industry needs something like this, especially the full audio experience of a podcast.

### Participate In Our Research <i class="fa fa-bar-chart" aria-hidden="true"></i>

We're currently running a survey on software engineering management practices covering tools, methods, culture. We hope you'll [click here](https://docs.google.com/a/michaelrice.com/forms/d/1mAYMiKK7DPD5KAyMQuX66gXwrTxgQl89Bwk302vBeI0/edit) to participate!

### Reading list <i class="fa fa-book" aria-hidden="true"></i>

{% for post in site.categories["reading"]  %}
  * {{post.excerpt}} - *[{{ post.title }}]({{ post.url }})*
{% endfor %}

### Join Our Conversation <i class="fa fa-github" aria-hidden="true"></i> <i class="fa fa-twitter" aria-hidden="true"></i> <i class="fa fa-envelope-o" aria-hidden="true"></i>

Want to get involved? You can add your own articles or content or whatever by [forking us on Github](https://github.com/craftleadership/craftleadership.github.io).

We're now on Twitter [@craftleadership <i class="fa fa-twitter" aria-hidden="true"></i>](https://twitter.com/craftleadership)

Want to join a conversation / interview on a podcast? Send Michael an email at [me@michaelrice.com](mailto:me@michaelrice.com).
