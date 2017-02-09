---
layout: typeface_individual
title: florrence
typeface: Florrence
designer: Kim Rhee
permalink: /florrence/

sections:
  typefaceBlurb: A fresh and playful display face inspired by the high contrast of the modern Didot and Bodoni, and the familiarity of Baskerville. Florrence features high x-heights, tall ascenders, short descenders, and unique terminals.
  bio: Kim Rhee is a freelance designer and lettering artist living in San Francisco, CA.

website: kimberlyrhee.com
instagram: kimberlyrhee


---

<div class="typeface__images">
{% for file in site.static_files %}
  {% if file.path contains 'img/florrence/' %}
    <img src="{{ file.path }}" />
  {% endif %}
{% endfor %}
</div>
