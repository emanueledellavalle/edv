---
layout: page
title: courses
permalink: /courses/
description: A growing collection of my teaching efforts including courses, specialized lectures, and industrial training.
nav: false
nav_order: 3
display_categories: [streaming data analytics, artificial intelligence,digital project management, big data, data science, semantic web]
horizontal: false
---


<!-- pages/courses.md -->
<div class="projects">
{%- if site.enable_courses_categories and page.display_categories %}
  <!-- Display categorized course -->
  {%- for category in page.display_categories %}
  <h2 class="category">{{ category }}</h2>
  {%- assign categorized_courses = site.courses | where: "category", category -%}
  {%- assign sorted_courses = categorized_courses | sort: "year" |  reverse %}
  <!-- Generate cards for each course -->
  {% if page.horizontal -%}
  <div class="container">
    <div class="row row-cols-1">
    {%- for course in sorted_courses -%}
      {% include course_horizontal.liquid %}
    {%- endfor %}
    </div>
  </div>
  {%- else -%}
  <div class="grid">
    {%- for course in sorted_courses -%}
      {% include course.liquid %}
    {%- endfor %}
  </div>
  {%- endif -%}
  {% endfor %}

{%- else -%}
<!-- Display courses without categories -->
  {%- assign sorted_courses = site.courses | sort: "year" |  reverse-%}
  <!-- Generate cards for each course -->
  {% if page.horizontal -%}
  <div class="container">
    <div class="row row-cols-2">
    {%- for course in sorted_courses -%}
      {% include course_horizontal.liquid %}
    {%- endfor %}
    </div>
  </div>
  {%- else -%}
  <div class="grid">
    {%- for course in sorted_courses -%}
      {% include course.liquid %}
    {%- endfor %}
  </div>
  {%- endif -%}
{%- endif -%}
</div>