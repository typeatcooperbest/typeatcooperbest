---
layout: default
title: typefaces
permalink: /typefaces/
---
<h1 class="title">Here they are</h1>

<ul class="list--typefaces">
{% for typeface in site.typefaces %}
    <li class="list--typefaces__item"><a class="list--typefaces__link" href="{{ typeface.permalink }}">{{ typeface.title}} by {{ typeface.designer }}</a> </li>
{% endfor %}
</ul>
