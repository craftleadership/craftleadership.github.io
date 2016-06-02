---
layout: default
---

## {{ site.description }}

### Are You An Engineering Manager? Join Us

We're assembling a private network of engineering managers and directors of engineering. Right now, it's just a mailing list but look for future **happy hours and presentation opportunities** (hopefully starting Fall 2016). Membership is of course free, but we do want you to apply.

<div id="signup">
  <form action="https://formspree.io/me@michaelrice.com" method="post" id="form">
      <input type="text" name="name" placeholder="My name is..."><br>
      <input type="text" name="title" placeholder="My current title is..."><br>
      <input type="text" name="company" placeholder="I work for..."><br>
      <input type="text" name="city" placeholder="I work in a city named..."><br>
      <input type="email" name="email" placeholder="My email address for the list is..."><br>
      <input type="text" name="_gotcha" style="display:none" />
      <input type="submit" value="Join!">
  </form>
</div>

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

### Podcasting This Summer 2016 <i class="fa fa-volume-up" aria-hidden="true"></i>

Craft + Leadership will (if we can get enough love and content) be a podcast, blog, and library of useful information for software engineering managers.

Seems like the industry needs something like this, especially the full audio experience of a podcast.
