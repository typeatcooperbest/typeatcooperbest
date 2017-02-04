---
layout: typeface_individual
title: newbohemianflare
typeface: New Bohemian Flare
designer: Damon Styer
permalink: /newbohemianflare/

sections:
  typefaceBlurb: This is the part about New Bohemia Flare
  bio: Here's Damon's bio

website: yourwebsite
instagram: yourinstagram
twitter: yourtwitter
facebook: yourfacebook
linkedin: yourlinkedin


---

<div class="typeface__images">
{% for file in site.static_files %}
  {% if file.path contains 'img/newbohemianflare/' %}
    <img src="{{ file.path }}" />
  {% endif %}
{% endfor %}
</div>
