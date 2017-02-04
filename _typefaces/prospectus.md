---
layout: typeface_individual
title: prospectus
typeface: Prospectus
designer: Dave Bailey
permalink: /prospectus/

sections:
  typefaceBlurb: This is the part about Prospectus
  bio: Here's Dave's bio

website: yourwebsite
instagram: yourinstagram
twitter: yourtwitter
facebook: yourfacebook
linkedin: yourlinkedin


---

<div class="typeface__images">
{% for file in site.static_files %}
  {% if file.path contains 'img/prospectus/' %}
    <img src="{{ file.path }}" />
  {% endif %}
{% endfor %}
</div>
