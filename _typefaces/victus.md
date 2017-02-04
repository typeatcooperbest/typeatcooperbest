---
layout: typeface_individual
title: victus
typeface: Victus
designer: Gen Ramirez
permalink: /victus/

sections:
  typefaceBlurb: This is the part about Victus
  bio: Here's Gen's bio

website: yourwebsite
instagram: yourinstagram
twitter: yourtwitter
facebook: yourfacebook
linkedin: yourlinkedin



---

<div class="typeface__images">
{% for file in site.static_files %}
  {% if file.path contains 'img/victus/' %}
    <img src="{{ file.path }}" />
  {% endif %}
{% endfor %}
</div>
