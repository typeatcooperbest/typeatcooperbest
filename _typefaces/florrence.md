---
layout: typeface_individual
title: florrence
typeface: Florrence
designer: Kim Rhee
permalink: /florrence/

sections:
  typefaceBlurb: A fresh and playful display typeface inspired by the high contrast of the modern Didot and Bodoni as well as the familiarity of Baskerville, Florrence features high x-heights, tall ascenders, short descenders, and unique terminals, earning it the name “Bodoni with balls”. Currently a work in progress, Florrence originally started off as a much more conservative typeface, as seen in the regular and italic weights. As some explorations of more experimental elements came into play, Florrence took on much more playful and unique traits in its heavy weight. My goal is to expand character sets and create a seamless progression of weights and quirkiness, with its end uses being for wide variety of large-scale design purposes (30pt. and up).
  bio: Kim is currently a freelance designer in San Francisco with a focus in custom lettering and illustration. She enjoys all things Star Wars, the smell of dictionaries, and a nice, drawn out conversation about paper types.

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
