---
layout: typeface_individual
title: highground
typeface: Highground
designer: Winston Scully
permalink: /highground/

sections:
  typefaceBlurb: This is the part about Highground
  bio: Here's Winston's bio

website: yourwebsite
instagram: yourinstagram
twitter: yourtwitter
facebook: yourfacebook
linkedin: yourlinkedin


---

<div class="typeface__images">
{% for file in site.static_files %}
  {% if file.path contains 'img/highground/' %}
    <img src="{{ file.path }}" />
  {% endif %}
{% endfor %}
</div>
