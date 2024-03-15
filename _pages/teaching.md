---
layout: page
permalink: /teaching/
title: Teaching
nav: true
nav_order: 3
horizontal: false
reversed: true
---

<!-- Display courses without categories -->
<div class="courses">
{% assign sorted_courses = site.teaching | sort: "importance" %}

  <!-- Generate cards for each course -->

{% if page.horizontal %}

  <div class="container">
    <div class="row row-cols-2">
    {% for course in sorted_courses %}
      {% include teaching_horizontal.liquid %}
    {% endfor %}
    </div>
  </div>
{% else %}
  <div class="grid">
    {% for course in sorted_courses %}
      {% include teaching.liquid %}
    {% endfor %}
  </div>
{% endif %}

</div>