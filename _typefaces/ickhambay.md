---
layout: typeface_individual
title: ickhambay
typeface: Ickhambay
designer: Camille Sibucao
permalink: /ickhambay/

sections:
  typefaceBlurb: Ickhambay is a bold, display typeface made to be seen at big, large, and GINORMOUS sizes.  Feel free to use it for signage, packaging, or your hipster cocktail menus.  It is also available in light and italic light for use in your love letters and baby shower announcements.  The Ickhambay fam is based off 18th century roundhand script found in master writer and engraver George Bickham's penmanship books.  Why the name Ickhambay?  It's Bickham in pig latin because it kinda looks like Bickham's script, just a little <em>fucked up.</em>
  bio: Camille is a <strike> wannabe </strike> <strong> LEGIT! </strong>  type designer/graphic designer/illustrator/hand-letterer.  She is currently taking commissions. Only cool folks need apply though.  


instagram:  camillesibucao
twitter: craymille


---

<div class="typeface__images">
{% for file in site.static_files %}
  {% if file.path contains 'img/ickhambay/' %}
    <img src="{{ file.path }}" />
  {% endif %}
{% endfor %}
</div>
