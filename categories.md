---
title: Categories
layout: default
---
<div class="row listrecent">
{% for category in site.categories %}
{% assign name = category[0] %}
  <div class="section-title col-md-12 mt-4">
    <h2 id="{{ name }}">Category <span class="text-capitalize">{{ name }}</span></h2>
  </div>
  {% for keyboard in category[1] %}
    {% include postbox.html %}
  {% endfor %}
{% endfor %}
