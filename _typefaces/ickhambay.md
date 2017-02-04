---
layout: typeface_individual
title: ickhambay
typeface: Ickhambay
designer: Camile Sibucao
permalink: /ickhambay/

sections:
  typefaceBlurb: This is the part about Ickhambay
  bio: Here's Camile's bio

website: yourwebsite
instagram: yourinstagram
twitter: yourtwitter
facebook: yourfacebook
linkedin: yourlinkedin


---

<div class="typeface__images">
{% for file in site.static_files %}
  {% if file.path contains 'img/ickhambay/' %}
    <img src="{{ file.path }}" />
  {% endif %}
{% endfor %}
</div>
