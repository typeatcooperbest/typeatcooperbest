---
layout: typeface_individual
title: amalie
typeface: Amalie
designer: Angy Che
permalink: /amalie/

sections:
  typefaceBlurb: Amalie was initially modeled after the forms, proportions, and construction of Didot. Through the development process, it began to take on its own unique characteristics. Amalie currently comes in both text and display weights. The family will continue to be expanded and refined until the cows come home.
  bio: |
    Angy Che is a Portland based designer and illustrator. She’s spent the last several years in San Francisco working on a variety of projects, from illustration and lettering, to identity design and ad campaigns. Type design is a newly acquired skill that she’s excited to integrate into her other work. 
    
    She’s originally from Los Angeles, where she graduated from ArtCenter College of Design with a degree in illustration.

website: www.angyche.com
instagram: thatsoktoo
linkedin: angy-che-7052033


---

<div class="typeface__images">
{% for file in site.static_files %}
  {% if file.path contains 'img/amalie/' %}
    <img src="{{ file.path }}" />
  {% endif %}
{% endfor %}
</div>
