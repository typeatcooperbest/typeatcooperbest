---
layout: default
title: typefaces
permalink: /typefaces/
---
<h1 class="title">Here they are</h1>

<ul class="list--typefaces">
{% for typeface in site.typefaces %}
    <li class="js-card list--typefaces__item"><a class="list--typefaces__link" href="{{ typeface.permalink }}">{{ typeface.title}} by {{ typeface.designer }}</a> </li>
{% endfor %}
</ul>


<script>
  var cards = document.getElementsByClassName('js-card');
  for(var i = 0; i < cards.length; i++){
    var target = Math.floor(Math.random() * cards.length -1) + 1;
    var target2 = Math.floor(Math.random() * cards.length -1) +1;
    cards[target].parentNode.insertBefore(cards[target2], cards[target]);
}
</script>
