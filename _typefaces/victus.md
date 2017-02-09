---
layout: typeface_individual
title: victus
typeface: Victus
designer: Gen Ramirez
permalink: /victus/

sections:
  typefaceBlurb: |
    Victus is a free interpretation of the aesthetic sense and functional purpose of  Bartolomeo Sanvito’s Renaissance manuscripts. Victus has formal features that identify it with the Venetian typographic model. The warmth of the carefully balanced calligraphic construction provides an evenness between the perception of the classic and modern visual standards. The family consists in four styles and twenty-two variants: Text and display, grouped in roman and italic with a range from thin to black.
  bio: |
    Gen Ramírez is a passionate calligrapher, lettering artist and type designer from Guadalajara, Mexico. He enjoys Salsa music almost as much as making letterforms, well, not so much. He is from Guadalajara, México
    
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
