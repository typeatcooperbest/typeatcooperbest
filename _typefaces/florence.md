---
layout: typeface_individual
title: florence
typeface: Florence
designer: Kim Rhee
permalink: /florence/

sections:
  typefaceBlurb: This is the part about Florence
  bio: Here's Kim's bio

website: yourwebsite
instagram: yourinstagram
twitter: yourtwitter
facebook: yourfacebook
linkedin: yourlinkedin


---

<div class="typeface__images">
{% for file in site.static_files %}
  {% if file.path contains 'img/florence/' %}
    <img src="{{ file.path }}" />
  {% endif %}
{% endfor %}
</div>
