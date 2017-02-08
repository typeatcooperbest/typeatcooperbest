---
layout: default
title: typefaces
permalink: /typefaces/
---

<section class="content--main">
<ul class="list--typefaces">
{% for typeface in site.typefaces %}
    <li class="js-card list--typefaces__item">
      <a class="list--typefaces__link" href="{{ typeface.permalink }}">
      <img class="icon icon-main" src="/img/{{ typeface.title }}.svg" alt="{{ typeface.typeface }} by {{ typeface.designer }}" />
      <span class="list--typefaces__title">{{ typeface.typeface}} by {{ typeface.designer }}</span>
      </a>
    </li>
{% endfor %}
</ul>
</section>

<script>
  var cards = document.getElementsByClassName('js-card');
  for(var i = 0; i < cards.length; i++){
    var target = Math.floor(Math.random() * cards.length -1) + 1;
    var target2 = Math.floor(Math.random() * cards.length -1) +1;
    cards[target].parentNode.insertBefore(cards[target2], cards[target]);
}
</script>
