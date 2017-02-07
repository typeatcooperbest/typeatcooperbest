---
layout: typeface_individual
title: prospectus
typeface: Prospectus
designer: Dave Bailey
permalink: /prospectus/

sections:
  typefaceBlurb: Prospectus is a text typeface family with an amalgamation of influences. Inspiration for the Roman came from the proportions of the Imperial Roman Capitals, specifically the Trajan column, early Carolingian miniscules, as well as the works of Georg Trump. The italic style is inspired by the work of Czech type designer, letterer and calligrapher Oldrich Menhart. Both styles are unified by a push and pull of rounds versus facets.
  bio: Dave Bailey designs type at Delve Fonts, is a Filmotype revivalist, and a Lost Type Co-Op contributor. When not immersed in letters, Dave pairs well with bourbon or HARIBO.

website: bezierwrangler.com
instagram: bezierwrangler
twitter: bezierwrangler


---

<div class="typeface__images">
{% for file in site.static_files %}
  {% if file.path contains 'img/prospectus/' %}
    <img src="{{ file.path }}" />
  {% endif %}
{% endfor %}
</div>
