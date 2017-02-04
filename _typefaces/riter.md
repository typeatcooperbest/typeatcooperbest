---
layout: typeface_individual
title: riter
typeface: Riter
designer: Shannon Miwa
permalink: /riter/

sections:
  typefaceBlurb: A friendly slab-ish serif typeface created for average people doing average things. Riter Basic is for composing friendly memos or basic inter-office communications. Riter Black is for memes and indicating warnings or danger. Have a look around at Riter, a typeface for mundane tasks.
  bio: Shannon Miwa is a person.

website: ampershann.com
instagram: ampershann
twitter: ampershann

---

<div class="typeface__images">
{% for file in site.static_files %}
  {% if file.path contains 'img/riter/' %}
    <img src="{{ file.path }}" />
  {% endif %}
{% endfor %}
</div>
