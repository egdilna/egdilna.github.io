---
title: 👋
---

[mapa.egdilna.cz](http://mapa.egdilna.cz) [metodiky.egdilna.cz](http://metodiky.egdilna.cz)

Vítejte na webu EGdílny



![Ilustrační obrázek dílny se stolem a notebooky, knihami zákonů, nářadím a bordelem](dilna.jpg)



[Příspěvky](prispevky) vás asi budou zajímat nejvíce, tam najdete všechno přehledně ve formě článků a informací. A proč si rovnou nepřidat [náš RSS kanál s novinkami](feed.xml) aby vám nic neuteklo?

Přemýšlíte, kde jste se to ocitli a co to je EGdílna, tak si [o nás](about) něco přečtěte. V navigaci se můžete podívat na naše díla a hned je začít používat, zkouknout naše projekty a třeba se i zapojit a nebo se inspirovat tím, s čím a s kým a pro koho něco děláme.

> 🫂 Je vám to, co děláme, sympatické? Chcete nás nějak podpořit? Nejvíc nám pomůže, když nás a naši práci budete sdílet se svými kolegy, aby z ní mohl těžit opravdu každý, komu pomůže. Děkujeme předem.



#### Nepřehlédněte



<div>
{% for post in site.posts %}
  {% if post.tags contains 'Nepřehlédněte' %}

      <a href="{{ post.url }}">{{ post.title }}</a>
, 
  {% endif %}
{% endfor %}
</div>
