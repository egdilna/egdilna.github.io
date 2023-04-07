---
layout: page
title: Projekt Mapa EG povinností
---


# Mapa eGovernmentích povinností

Povinnosti úřadů k digitalizaci hezky a přehledně na jednom místě. A to tak, aby se s nimi dalo opravdu vážně pracovat.

Mapu a vše kolem ní najdete vždy na adrese [egdilna.cz/mapapovinnosti](http://www.egdilna.cz/mapapovinnosti)

## O Mapě povinností

Mapa EG povinností je souborem povinností týkajících se ICT, eGovernmentu a architektury, které plynou z jednotlivých právních předpisů a dalších závazných předpisů a dokumentů. Postupně se tak buduje báze znalostí o povinnostech, které jednotlivé druhy subjektů mají. U každého úřadu tak může na základě těchto znalostí vznikat zhodnocení (assessment) naplňování povinností z jejich strany, tedy vyžaduje jí Tvorba assesmentu plnění povinností na základě mapy povinností. Mapu povinností může kdokoliv využít pro základní přehled toho, co musí obecně v rámci elektronizace a digitalizace plnit a podle jakého konkrétního právního předpisu takovou povinnost má. To jsou důležité znalosti, aby si úřad dokázal představit, jak bude dané obecné povinnosti plnit. A samozřejmě se to netýká jen úřadů či orgánů veřejné moci, ale všech skupin subjektů.




<h3>Příspěvky na webu týkající se projektu mapy povinností</h3>

<ul>
{% for post in site.posts %}
  {% if post.tags contains 'Projekt Mapa povinností' %}
    <li>
      <a href="{{ post.url }}">{{ post.title }}</a><br>{{ post.subtitle }}
    </li>
  {% endif %}
{% endfor %}
</ul>

