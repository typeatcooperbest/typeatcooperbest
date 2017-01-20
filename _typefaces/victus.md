---
layout: typeface_individual
title: victus
designer: Gen
permalink: /victus/

sections:
  typefaceBlurb: This is the part about Victus
  bio: Here's Gen's bio

instagram: genramirez
twitter: genramirez


---

<div class="typeface__images">
{% for file in site.static_files %}
  {% if file.path contains 'img/victus/' %}
    <img src="{{ file.path }}" />
  {% endif %}
{% endfor %}
</div>
