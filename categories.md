---
title: Categories
layout: default
---
<div class="row listrecent">
{% for category in site.categories %}
  <div class="section-title col-md-12 mt-4">
    <h2 id="split">Category <span class="text-capitalize">{{ category[0] }}</span></h2>
  </div>
  {% for keyboard in category[1] %}
    {% include postbox.html %}
  {% endfor %}
{% endfor %}
