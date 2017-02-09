---
layout: typeface_individual
title: victus
typeface: Victus
designer: Gen Ramirez
permalink: /victus/

sections:
  typefaceBlurb: This is the part about Victus
  bio: Gen Ramírez is a passionate calligrapher, lettering artist and type designer from Guadalajara, Mexico. He enjoys Salsa music almost as much as making letterforms, well, not so much. He is from Guadalajara, México
website: http://genramirez.com/
instagram: genramirez
twitter: genramirez
facebook: genraro
linkedin: genramirez



---

<div class="typeface__images">
{% for file in site.static_files %}
  {% if file.path contains 'img/victus/' %}
    <img src="{{ file.path }}" />
  {% endif %}
{% endfor %}
</div>
