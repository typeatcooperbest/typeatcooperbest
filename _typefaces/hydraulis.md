---
layout: typeface_individual
title: hydraulis
typeface: Hydraulis
designer: Lauren Hostetter
permalink: /hydraulis/

sections:
  typefaceBlurb: This is the part about Hydraulis
  bio: Here's Lauren's bio

website: yourwebsite
instagram: yourinstagram
twitter: yourtwitter
facebook: yourfacebook
linkedin: yourlinkedin


---

<div class="typeface__images">
{% for file in site.static_files %}
  {% if file.path contains 'img/hydraulis/' %}
    <img src="{{ file.path }}" />
  {% endif %}
{% endfor %}
</div>
