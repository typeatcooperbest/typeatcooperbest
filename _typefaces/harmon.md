---
layout: typeface_individual
title: harmon
typeface: Harmon
designer: Sonja Hernandez
permalink: /harmon/

sections:
  typefaceBlurb: This is the part about Harmon
  bio: Here's Sonja's bio

website: yourwebsite
instagram: yourinstagram
twitter: yourtwitter
facebook: yourfacebook
linkedin: yourlinkedin


---

<div class="typeface__images">
{% for file in site.static_files %}
  {% if file.path contains 'img/harmon/' %}
    <img src="{{ file.path }}" />
  {% endif %}
{% endfor %}
</div>
