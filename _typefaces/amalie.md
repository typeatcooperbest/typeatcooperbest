---
layout: typeface_individual
title: amalie
typeface: Amalie
designer: Angy Che
permalink: /amalie/

sections:
  typefaceBlurb: This is the part about Amalie
  bio: Here's Angy's bio

website: yourwebsite
instagram: yourinstagram
twitter: yourtwitter
facebook: yourfacebook
linkedin: yourlinkedin


---

<div class="typeface__images">
{% for file in site.static_files %}
  {% if file.path contains 'img/amalie/' %}
    <img src="{{ file.path }}" />
  {% endif %}
{% endfor %}
</div>
