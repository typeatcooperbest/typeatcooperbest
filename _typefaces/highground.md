---
layout: typeface_individual
title: highground
typeface: Highground
designer: Winston Scully
permalink: /highground/

sections:
  typefaceBlurb: Highground is a typeface that started as a revival of the Rotunda style and formed into display face for punk band posters. It is based on broad edge calligraphy and attempts to emit a feeling of anarchy.
  bio: Winston is a lettering artist and type designer from Baton Rouge, LA currently living in Oakland, CA. His day job is a graphic designer for <a href="http://mybkr.com">bkr</a>. He has practiced lettering for a little over five years and type design for about one year. He loves punk bands, supporting your local scene, and band poster design. 

website: wscully.com
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
