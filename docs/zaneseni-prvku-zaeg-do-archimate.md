Export z modelu [[archimate-model-jaksecokresli]]

## Zanesení  prvků  na strategické vrstvě

* Schopnost zaneseme do architektury jako prvek typu Capability se stereotypem Obecná schopnost
## Zanesení prvků na byznysové vrstvě 

* Zákon zaneseme do architektury jako prvek typu Contract se stereotypem Právní předpis a pole Určuje nevyplňujeme
* Vyhlášku zaneseme do architektury jako prvek typu Contract se stereotypem Právní předpis a pole Určuje nevyplňujeme
* Předpis zaneseme do architektury jako prvek typu Contract se stereotypem Závazný předpis (pro obecně platné), nebo Vnitřní předpis (pro organizačně platné) a pokud jej určuje jiný předpis, uvedeme to do pole Určuje
* Agendu veřejné správy zaneseme do architektury jako prvek typu BusinessFunction se stereotypem Agenda a identifikátorem A1234. Do atributu Určuje zapíšeme: ohlášení v RPP
* Službu veřejné správy zaneseme do architektury jako prvek typu BusinessService se stereotypem Služba veřejné správy a identifikátorem S1234. Do atributu Určuje zapíšeme: Ohlášení v KSVS
* Rámcovou službu zaneseme do architektury jako prvek typu BusinessService se stereotypem Rámcová služba a pokud je určena ustanovením předpisu, zapíšeme to do pole Určuje
* Poskytovanou službu zaneseme do architektury jako prvek typu BusinessService se stereotypem Poskytovaná služba a případným určením do atributu Určuje
* Informační koncepci ČR zaneseme do architektury jako prvek typu Contract se stereotypem Závazný předpis a identifikátorem ikcr. Do atributu Určuje zapíšeme: § 5a zákona 365/2000 a UV 931 z 9.11.2022
* Informační koncepci úřadu zaneseme do architektury jako prvek typu Contract se stereotypem Vnitřní předpis a do atributu Určuje zapíšeme: § 5 odst. 2 zákona 365/2000
* Strategii úřadu zaneseme do architektury jako prvek typu Contract se stereotypem Vnitřní předpis a do atributu Určuje zapíšeme to, podle čeho strategie vzniká, pokud je předepsána.
* Subjekt  zaneseme do architektury jako prvek typu BusinessActor se stereotypem Subjekt a do pole Určuje zapíšeme předpis jež subjekt definuje či zakládá metamodelsubjekt. Do atributu Určuje zapíšeme: 
* Orgán veřejné moci zaneseme do architektury jako prvek typu BusinessActor se stereotypem OVM a do pole Určuje zapíšeme předpis a ustanovení jímž OVM zniká
* Organizaci zaneseme do architektury jako prvek typu BusinessActor se stereotypem Subjekt
* Organizační útvar zaneseme do architektury jako prvek typu BusinessActor se stereotypem Útvar
* Role osoby nebo útvaru v organizaci zaneseme do architektury jako prvek typu BusinessRole se stereotypem Vnitřní role a případným určením v atributu Určuje
* Rámcovou činnost zaneseme do architektury jako prvek typu BusinessFunction se stereotypem Rámcová činnost
* Proces zaneseme do architektury jako prvek typu BusinessProcess se stereotypem Vnitřní proces a do pole Určuje zapíšeme, který předpis jej definuje
* Roli zaneseme do architektury jako prvek typu BusinessRole se stereotypem Role organizace, Role OVM, nebo Klientská role  a do pole Určuje zapíšeme předpis a ustanovení jež roli definuje či určuje

## Zanesení prvků na aplikační vrstvě

* Informační systém veřejné správy zaneseme do architektury jako prvek typu ApplicationComponent se stereotypem ISVS a do atributu Určuje zapíšeme konkrétní předpis a ustanovení zakládající daný systém
* Komponentu systému zaneseme do architektury jako prvek typu ApplicationComponent se stereotypem Komponenta IS
* Rozhraní informačního systému  zaneseme do architektury jako prvek typu ApplicationInterface se stereotypem Rozhraní IS
* Aplikační služby jako funkcionalitu zaneseme do architektury jako prvek typu ApplicationService se stereotypem Služba uživatelské funkcionality
* Proces realizovaný v systému  zaneseme do architektury jako prvek typu ApplicationProcess se stereotypem Aplikační proces
* Platformní software zaneseme do architektury jako prvek typu ApplicationComponent se stereotypem Platformní SW
* Údaje a soubory údajů zaneseme do architektury jako prvek typu DataObject se stereotypem Soubor údajů, nebo Údaj
## Zanesení prvků na motivační vrstvě

* Stakeholdery jako zainteresované účastníky zaneseme do architektury jako prvek typu Stakeholder se stereotypem Zainteresovaný subjekt
* Potřebu nebo důvod motivace zaneseme do architektury jako prvek typu Driver se stereotypem Potřeba, nebo Důvod
* Povinnost z Mapy povinností zaneseme do architektury jako prvek typu Driver se stereotypem Povinnost a identifikátorem P1234 a do atributu Určuje zapíšeme ustanovení a předpis určující povinnost.
* Povinnost zaneseme do architektury jako prvek typu Driver se stereotypem Povinnost a do atributu Určuje zapíšeme ustanovení a předpis určující povinnost.
* Strategický cíl zaneseme do architektury jako prvek typu Goal se stereotypem Cíl rozvoje a do atributu Určuje zapíšeme předpis či dokument v němž je cíl definován
* Cíl rozvoje IT zaneseme do architektury jako prvek typu Goal se stereotypem Cíl rozvoje a do atributu Určuje zapíšeme předpis či dokument v němž je cíl definován
* Zásadu řízení zaneseme do architektury jako prvek typu Principle se stereotypem Zásada a do atributu Určuje zapíšeme předpis jež zásadu určuje
* Architektonický princip zaneseme do architektury jako prvek typu Principle se stereotypem Architektonický princip a do atributu Určuje zapíšeme předpis jež princip určuje
* Projektový cíl zaneseme do architektury jako prvek typu Goal se stereotypem Cíl
* Požadavek zaneseme do architektury jako prvek typu Requirement se stereotypem Požadavek a pokud je něčím definován, zapíšeme to do atributu Určuje
* Zhodnocení (Assesment) zaneseme do architektury jako prvek typu Assessment se stereotypem Výsledek vyhodnocení
* Omezení (Constraint) zaneseme do architektury jako prvek typu Constraint se stereotypem Omezení

## Zanesení prvků na implementační vrstvě

* Program zaneseme do architektury jako prvek typu WorkPackage se stereotypem Program
* Záměr nebo Projekt zaneseme do architektury jako prvek typu WorkPackage se stereotypem Projekt a do atributu Určuje zapíšeme vnitřní předpis jež projekt definuje
* Pracovní postup zaneseme do architektury jako prvek typu WorkPackage se stereotypem Postup
* Pracovní krok zaneseme do architektury jako prvek typu WorkPackage se stereotypem Krok
* Dodaný výstup (Deliverable) zaneseme do architektury jako prvek typu Deliverable se stereotypem Výstup
