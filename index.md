---
layout: default
---

## {{ site.description }}

### You're an Engineering Manager? Join Us

We're assembling a private network of engineering managers and directors of engineering. Right now, it's just a mailing list but look for future **happy hours and presentation opportunities** (hopefully starting Fall 2016).

Membership is of course free, but we're trying to keep the membership quality reasonably high with this registration form:

{% include formspree.html %}

### Engineering Management Research <i class="fa fa-bar-chart" aria-hidden="true"></i>

We're also currently running a survey on software engineering management practices covering tools, methods, culture. We hope you'll [click here](https://docs.google.com/a/michaelrice.com/forms/d/1mAYMiKK7DPD5KAyMQuX66gXwrTxgQl89Bwk302vBeI0/edit) to participate!

### Reading List <i class="fa fa-book" aria-hidden="true"></i>

{% for post in site.categories["reading"]  %}
  * {{post.excerpt}} - *[{{ post.title }}]({{ post.url }})*
{% endfor %}

### Get Involved <i class="fa fa-github" aria-hidden="true"></i> <i class="fa fa-twitter" aria-hidden="true"></i> <i class="fa fa-envelope-o" aria-hidden="true"></i>

Want to get involved? You can add your own articles or content or whatever by [forking us on Github](https://github.com/craftleadership/craftleadership.github.io).

We're on Twitter [@craftleadership <i class="fa fa-twitter" aria-hidden="true"></i>](https://twitter.com/craftleadership)

Want to join a conversation, suggest something for the reading list, or get an interview on a podcast? Send Michael an email at [me@michaelrice.com](mailto:me@michaelrice.com).

### Virtual Conference Planning <i class="fa fa-volume-up" aria-hidden="true"></i>

Seems like it would be a great idea to have more conferences or talks on this subject -- much like CalibrateSF did. Got ideas? Want to participate? Send Michael an email [me@michaelrice.com](mailto:me@michaelrice.com).
