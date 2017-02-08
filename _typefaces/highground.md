---
layout: typeface_individual
title: highground
typeface: Highground
designer: Winston Scully
permalink: /highground/

sections:
  typefaceBlurb: Highground is a typeface that started as a revival of the Rotunda style and formed into display face for punk band posters. It is based on broad edge calligraphy and attempts to emit a feeling of anarchy.
  bio: Winston is a lettering artist and type designer from Baton Rouge, LA currently living in Oakland, CA. He dayjobs as a graphic designer and has pursued the letter arts for a little over 5 years. Loves punk bands and band poster design.

website: http://wscully.com
instagram: wscully
twitter: winstonscully


---

<div class="typeface__images">
{% for file in site.static_files %}
  {% if file.path contains 'img/highground/' %}
    <img src="{{ file.path }}" />
  {% endif %}
{% endfor %}
</div>
