**Traffic Light Protocol (TLP)** je standardizovaný informační klasifikační mechanismus používaný pro bezpečné sdílení citlivých informací, zejména v oblasti kybernetické bezpečnosti, incident response týmů a komunitních výměnných platforem. Jeho účelem je umožnit efektivní spolupráci mezi organizacemi a jednotlivci při současném řízení rizika spojeného s nežádoucím šířením informací. TLP definuje jednoduchou, barevně orientovanou sadu pravidel, která určují, komu je možné sdělené informace dále poskytovat a v jakém rozsahu.

## Jak funguje TLP

**Traffic Light Protocol (TLP)** je standardizovaný informační klasifikační mechanismus používaný pro bezpečné sdílení citlivých informací, zejména v oblasti kybernetické bezpečnosti, incident response týmů a komunitních výměnných platforem. Jeho účelem je umožnit efektivní spolupráci mezi organizacemi a jednotlivci při současném řízení rizika spojeného s nežádoucím šířením informací. TLP definuje jednoduchou, barevně orientovanou sadu pravidel, která určují, komu je možné sdělené informace dále poskytovat a v jakém rozsahu.

Protokol TLP se v současnosti řídí specifikací **FIRST TLP v2.0**, která zavedla jasné definice jednotlivých úrovní a odstranila dřívější nejasnosti. Každá úroveň je označena textovým klíčovým slovem a barvou: **TLP:CLEAR**, **TLP:GREEN**, **TLP:AMBER**, **TLP:AMBER+STRICT** a **TLP:RED**. Čím přísnější úroveň, tím užší okruh příjemců je oprávněn informace dále sdílet. Součástí standardu je rovněž jasné pravidlo, že označení TLP se vztahuje na konkrétní obsah, nikoliv na celou komunikaci nebo dokument, není-li to výslovně uvedeno.

**TLP:CLEAR** umožňuje volné šíření informací bez omezení; jde o obsah určený široké veřejnosti nebo již veřejně dostupný. **TLP:GREEN** povoluje sdílení v rámci širší komunity organizací, které mají legitimní zájem, avšak nikoli veřejně. **TLP:AMBER** omezuje šíření na interní použití příjemcovy organizace, zatímco **TLP:AMBER+STRICT** ještě více zužuje dosah na konkrétní osoby s přímou potřebou vědět. Nejrestriktivnější **TLP:RED** zakazuje další šíření mimo původně určené konkrétní osoby přítomné při předání informace.

Označení TLP je součástí metadat sdíleného obsahu a má být umístěno viditelně, obvykle v záhlaví dokumentu nebo komunikace. Při kombinaci více materiálů platí vždy nejpřísnější úroveň. TLP není právní klasifikační systém ani nástroj pro označování utajovaných informací; jde o dobrovolný koordinační mechanismus používaný v komunitě bezpečnostních profesionálů. Správná aplikace TLP přispívá ke snížení informačního rizika, usnadňuje řízené sdílení informací o hrozbách a podporuje důvěru mezi zúčastněnými subjekty.

TLP je normový standard:

  * [[Odkazy/PDF dokument Standard Traffic Light protocol (TLP) 2.0 v češtině|PDF dokument Standard Traffic Light protocol (TLP) 2.0 v češtině]]
  * [[Odkazy/Traffic light protocol standard and usage|Oficiální webová stránka standardu TLP]]

V rámci veřejné správy se TLP využívá dle doporučení NÚKIOB jako základní stupnice klasifikace bezpečnosti a důvěrnosti. Využije se všude tam, kde se realizuje [[Bezpečnostní klasifikace dokumentů]] a [[klasifikace údajů ve veřejné správě]].

## Základní přehled stavů dle TLP

TLP protokol má čtyři základní úrovně přístupu k informaci, které se pokud možno graficky odlišují barvou, což usnadňuje přehled pro běžné uživatele.

V následující tabulce je obecný popis všech úrovní semaforu TLP a jejich významu. V poznámce je dále uvedeno, jak by se taková informace měla uchovávat a jaké jsou technické požadavky na nástroje.

| TLP | Barva | Vysvětlení účelu | Poznámka |
|---|---|---|---|
| TLP:RED | červená | Nikomu dalšímu není informace určena | Informace se pokud možno nikam nezaznamená a není součástí formálního dokumentu či údaje. Pokud už formalizovaná je, neukládá se do nástroje, kde nelze technicky řídit přístup k informacím. |
| TLP:AMBER | oranžová | Informace je dostupná jen vybraným fyzickým osobám s řízením přístupu | Informace je uložena v systému, nebo nástroji, kde lze technicky zamezit ostatním uživatelům v přístupu k informaci a nebo i zjistit její existenci třeba vyhledáváním apod. |
| TLP:GREEN | zelená | Informace je určena uživatelům v rámci určité organizace a v jejím rámci může být k ní řízený přístup | Informace je uložena v daném systému, kde je buď přístupná všem uživatelům v organizaci, nebo je alespoň vyhledatelná její existence a je stanoveno, kdo se může s obsahem informace seznamovat. |
| TLP:CLEAR | (žádná) | Informace je veřejná, je pŕístupná komukoliv bez omezení | Informace je zveřejněna nějakou formou, třeba umístěním na internetových stránkách, na úřední desce a nebo kdekoliv jinde veřejně. |
