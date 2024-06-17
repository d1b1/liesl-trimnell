---
title: Things to Know
layout: default
subtitle: There are a lot of details to work out to get your unit ready for guests and functioning well.
sitemap: true
---

{% include subStyles.css %}
{% include articleHeader.html %}

{% assign articles = site.articles | sort: "order" %}
{% for article in articles %}
  <div class="row">
    <div class="col-6">
      <h4>
        {{ article.title }}
      </h4>
    </div>
    <div class="col-6">
      {{ article.subtitle }}
      <a href="{{ article.url }}">read more...</a>
    </div>
  </div>
  <hr>
{% endfor %}

<div class="mt-5 mb-5 tech-note" style="margin-bottom: 200px;">
    <h5>
      Homeowner Tips
    </h5>
    <p>
        These articles are written to give first-time Airbnb
        hosts some context for different types of issues they
        will have as they get started.
    </p>
</div>

<style>
 hr { border: 1px solid #DFDFDF; }
</style>