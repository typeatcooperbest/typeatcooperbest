---
layout: typeface_individual
title: riter
typeface: Riter
designer: Shannon Miwa
permalink: /riter/

sections:
  typefaceBlurb: |
    A friendly slab-ish serif typeface created for average people doing average things. Riter Basic is for composing friendly memos or basic inter-office communications. Riter Black is for memes and indicating warnings or danger. 

    The Riter Family excels at mundane tasks. If you are using Comic Sans, Arial or Times New Roman, you could be using Riter instead!
  bio: |
    Shannon Miwa is a product designer at Braintree&mdash;one of those tech companies&mdash;currently living in San Francisco, CA. She enjoys a variety of letter making and design activities, but she is still deciding what she wants to be when she grows up.

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
