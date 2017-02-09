---
layout: typeface_individual
title: hydraulis
typeface: Hydraulis
designer: Lauren Hostetter
permalink: /hydraulis/

sections:
  typefaceBlurb: Hydraulis is a not-so-subtle nod to the work of 17th-century punchcutter Miklós Tótfalusi Kis. It's an unusually narrow but eminently readable oldstyle serif typeface, ideal for bringing a vintage flavor to your designs. Hydraulis would be quite at home in a book of bawdy 17th-century humor or a catalogue of bizarre recipes from simpler, more desperate times (think 'fish custard').
  
  Hydraulis currently includes regular and Italic styles, both of which are still works in progress with ample room for expansion of the character set. Bold and bold Italic styles are forthcoming.
  bio: In some parallel universe, Lauren is an entomologist. But in this universe, she's a web-designer-by-day/illustrator-by-night with a bad case of wanderlust. Contact her if you'd like to discuss business opportunities or the many merits of moon moths.

website: laurenhostetter.com
instagram: annegwish33
twitter: hostetter33
linkedin: laurenhostetter


---

<div class="typeface__images">
{% for file in site.static_files %}
  {% if file.path contains 'img/hydraulis/' %}
    <img src="{{ file.path }}" />
  {% endif %}
{% endfor %}
</div>
