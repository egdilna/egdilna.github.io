# Přehled souladu informačního systému Systém pro evidenci žabiček s požadavky rámce GP

## Základní informace

- Název informačního systému: Systém pro evidenci žabiček
- Název správce: Úřad pro zelené žabičky
- Věcný správce: Odbor žabičkování
- Technický správce: Jan Pečlivý, odbor OIT
- Druh informačního systému: ISVS jež je AIS
- Datum verze zhodnocení: 1. červenec 2026
- Datum očekávaného plného souladu: 31. prosinec 2027
- Textové stručné shrnutí zhodnocení souladu: Musíme dořešit vazbu na další systémy, dodělat propojená na CMS2 a aktualizovat údaje v RPP. Dále musíme více dbát na plnění povinností věcného a technického správce a zaktualizovat provozní dokumentaci.


## Informace určující základní aspekty IS pro hodnocení

**Uvedení v IK OVS**

Informační systém Systém pro evidenci žabiček .

Tento IS a jeho rozvoj plní následující cíle a záméry uvedené v IK:

- Cíl: Řádně elektronicky evidovat všechny žabičky
- Záměr: Zlepšení procesů a služeb při evidenci žabiček

IK uvádí k požadovanému rozvoji systému Systém pro evidenci žabiček následující (shrnutí): Je uveden v klíčových systémech veŕejné správy a v zámérech se očekává jeho modernizace

Informace k systému byly v IK naposledy aktualizovány k datu 1. leden 2026


**Role a zodpovědnosti**

Věcným správcem je Odbor žabičkování a . Jeho činnost věcného správce upravují následující vnitřní předpisy: Organizační řád, Směrnice ke správě systémů, Směrnice k evidenci žabiček, Spisový a skartační řád

Technickým správcem je Jan Pečlivý, odbor OIT a . Jeho činnost věcného správce upravují následující vnitřní předpisy: Směrnice o správě systémů


**Očekávané změny informačního systému v následujících 2 letech**

I s ohledem na toto zhodnocení jsou plánovány následující významné změny informačního systému:





## Podrobné zhodnocení souladu s požadavky GP

Následuje tabulka všech požadavků a informací o souladu řešení AIS/ISVS s těmito požadavky:


| Požadavek | Soulad | Potřebné změny |
| --- | --- | --- |
| Požadavky k fungování AIS v kontextu EG |  |  |
| GP1 Vedení AIS v informační koncepci |  |  |
| ■ AIS je zařazen v informační koncepci úřadu a je v souladu s IKČR a navazujícími dokumenty. | Soulad: Máme v IK a v architektuře |  |
| ■ AIS je v souladu s IK ČR a navazujícími dokumenty | Částečně: Soulad s IKČR asi máme, musíme ale dořešit, aby byl přesně v souladu s NAP stran jednotlivých technických řešení. Musíme taky dořešit úplnou implementaci PPDF. | Prověřit NAP a PPDF. |
| GP2 Vedení provozní dokumentace AIS |  |  |
| ■ Provozní dokumentace obsahuje vše dle vyhlášky | Částečně: Nějakou dokumentaci máme, ale zjistili jsme, že není zcle kompletní a úplná podle vyhlášky. | Dovytvořit části Exit plánu, doplnit o projektovou a akceptační dokumentaci, doplnit některé kapitoly v procesech provozu, doplnit provozní řád. |
| GP3 Připojení na referenční rozhraní |  |  |
| ■ AIS je připojen na referenční rozhraní veřejné správy pro účely vazeb na AIS jiného orgánu veřejné správy. | Soulad |  |
| ■ Čerpá veškeré nezbytné údaje, které se potřebují pro vyřízení služeb poskytované AIS. | Částečně | Prověřit, zda nemůźeme čerpat ještě další údaje, které potŕebujeme ale nejsou zatím jako kontexty a projednat to s příslušnými ohlašovateli agend. |
| ■ Poskytuje veškeré vlastní (tedy nepřebírané) údaje, které v AIS vznikají pro potřeby ostatních AIS. Pro veškeré publikované údaje nabízí vyrozumění o změně v AIS-V. | Nesoulad | Neposkytujeme údaje, nikdo je po nás nechce. Nejsme si tím ale jisti, zaměřit se na to. |
| GP4 Využívání Národního bodu pro identifikaci a autentizaci |  |  |
| ■ AIS má zajištěnou identifikaci a autentizaci fyzických osob, u kterých se vyžaduje prokázání totožnosti pomocí kvalifikovaného systému | Nerelevantní: Do AIS se nepřihlašují klientské subjekty |  |
| ■ AIS nevyužívá žádné jiné proprietární způsoby identifikace a autentizace, nevyžaduje-li to specifická situace, jako např. přihlášení třetizemce. |  |  |
| GP5 Využívání centrálního místa služeb |  |  |
| ■ AIS má zajištěnou vazbu na AIS jiného orgánu veřejné správy prostřednictvím centrálního místa služeb. | Soulad: Jsme napojeni na CAAIS a naši zaměstnanci využívají CAAIS k přihlašování do systému. |  |
| GP6 Stanoviska OHA |  |  |
| ■ AIS má souhlasná stanoviska Hlavního architekta eGovernmentu DIA na projekty architektonických změn |  |  |
| ■ AIS má souhlasné stanovisko OHA k posouzení provozní dokumentace před uvedením služeb do provozu. |  |  |
| GP7 Vedení AIS v RPP |  |  |
| ■ AIS jako takový je veden v rejstříku ISVS se všemi údaji. |  |  |
| ■ Zároveň je také ohlášena agenda, kterou AIS vykonává se všemi nezbytnostmi k řádnému plnění činností v agendě. |  |  |
| GP8 Služby v katalogu služeb |  |  |
| ■ Všechny služby, které se v AIS řeší jsou ohlášeny v katalogu služeb veřejné správy. |  |  |
| ■ Kromě služeb je i známo, v jakých životních událostí je služba vyžadována a vyřizována. |  |  |
| GP9 Využívání Registru zastupování |  |  |
| ■ Pro digitální služby je možnost využít elektronického zastupování v Registru zastupování. |  |  |
| ■ Pro úřední osoby je pro autentizaci do systému využit CAAIS |  |  |
| Požadavky k AIS související s dlouhodobým řízením |  |  |
| GP11 Věcný správce stanoví požadavky na služby AIS a poskytování služeb AIS splňujících tyto požadavky |  |  |
| ■ Definuje byznysové/úřední požadavky na služby IS (funkce, parametry, kvalita). Slouží jako závazný vstup pro architekturu, zadání a SLA, aby ISVS podporoval výkon agendy a byl měřitelně řiditelný. |  |  |
| GP12 Věcný správce zajistí návrh a realizaci AIS z hlediska splňování |  |  |
| ■ 1. požadavků na služby informačního systému |  |  |
| ■ 2. požadavků na technické a programové prostředky kladených na ně právními předpisy upravujícími informační nebo komunikační technologie, informační koncepcí orgánu veřejné správy a provozní dokumentací, a jde-li o informační systém spravovaný orgánem veřejné správy, pro nějž jsou závazná usnesení vlády, rovněž informační koncepcí České republiky a jinými usneseními vlády týkajícími se informačních nebo komunikačních technologií. |  |  |
| GP13 Věcný správce identifikuje motivace k vytvoření nebo rozvoji AIS, porovná je se stávajícím stavem architektury orgánu veřejné správy a prostřednictvím aktualizace informační koncepce orgánu veřejné správy provede strategické naplánování vytvoření nebo rozvoje tohoto systému. |  |  |
| ■ Zajišťuje zdůvodnění a zasazení změny do architektury a plánů (IK OVS). Brání duplicitám a nesouladu portfolia IS; umožní řídit rozvoj ISVS dlouhodobě. |  |  |
| GP14 Věcný správce v návaznosti na plán v informační koncepci orgánu veřejné správy vypracuje a schválí investiční záměr a v případě určeného informačního systému obdrží souhlasné vyjádření Digitální a informační agentury. |  |  |
| GP15 Věcný správce stanoví cíle, kterých chce dosáhnout vytvořením nebo rozvojem AIS nebo se odkáže na platné strategické cíle orgánu veřejné správy nebo cíle České republiky, jejichž splnění bude podpořeno plánovaným AIS. |  |  |
| GP16 Věcný správce identifikuje a stanovuje požadavky na služby AIS, zpracování informací a bezpečnostní úrovně informačního systému. |  |  |
| GP17 Věcný správce vyhodnocuje a schvaluje řešení AIS podle předložených variant řešení informačního systému. |  |  |
| GP18 Věcný správce plánuje zajištění zdrojů potřebných pro plánování a přípravu vytvoření a rozvoje informačního systému. |  |  |
| GP19 Věcný správce identifikuje požadavky na zpracování datového výstupu určeného k dlouhodobému uchovávání. |  |  |
| GP20 Věcný správce schvaluje plán ukončení provozu informačního systému. |  |  |
| GP21 Věcný správce zajišťuje vypracování studie proveditelnosti k posouzení možných variant nebo zjištění podmínek pro realizovatelnost nových nebo významně měněných informačních systémů. |  |  |
| GP22 Technický správce zpracovává a předkládá varianty řešení informačního systému podle požadavku věcného správce, přičemž posuzuje možnost využití stávajících infomačních systémů. |  |  |
| GP23 Technický správce zpracovává architekturu informačního systému na úrovni podrobnosti metody architektury úřadu a metody architektury řešení a specifikace možných řešení. |  |  |
| GP24 Technický správce využívá výstupů provedených ověřovacích konceptů potřebných pro pořizování nebo změnu AIS. |  |  |
| GP25 Technický správce vytváří plán ukončení provozu AIS. |  |  |
| GP26 Technický správce vytváří plán uchovávání dat. |  |  |
| GP27 Věcný správce zajišťuje zdroje potřebné k realizaci vytvoření nebo rozvoji informačního systému. |  |  |
| GP28 Věcný správce stanovuje rozsah a formát datového výstupu k dlouhodobému uchovávání. |  |  |
| GP29 Věcný správce stanovuje uživatelské role, náplň vykonávaných činností a přístupová oprávnění. |  |  |
| GP30 Technický správce zajišťuje pořízení nebo technické zhodnocení AIS splňujícího požadavky kladené na jeho služby |  |  |
| GP31 Technický správce zajišťuje splnění požadavků kladených na provoz AIS |  |  |
| GP32 Technický správce zajišťuje zveřejnění zdrojového kódu vytvořeného během projektu v rozsahu, v jakém jej nemůže být zneužito k narušení nebo zničení AIS |  |  |
| GP33 Technický správce zajišťuje řízení změn AIS |  |  |
| GP34 Technický správce zajišťuje řízení kontinuity provozu AIS |  |  |
| GP35 Technický správce zajišťuje zřízení podpory uživatelům AIS |  |  |
| GP36 Technický správce zajistí aby projekt, jehož součástí je dodávka více než jedné komponenty, byl rozdělen na dílčí plnění obsahující dodávku jednotlivých komponent. Činí tak způsobem, aby bylo možné po dodávce každé komponenty projekt ukončit, pokud ztratil své původní opodstatnění. |  |  |
| GP37 Věcný správce zajišťuje zdroje potřebné k zajištění produkčního provozu informačního systému. |  |  |
| GP38 Věcný správce průběžně školí uživatele informačního systému. |  |  |
| GP39 Věcný správce zajišťuje příjem a evidenci požadavků na změny funkcí a služeb informačního systému od uživatelů informačního systému, |  |  |
| GP40 Věcný správce vyhodnocuje plnění stanovených požadavků na služby informačního systému. |  |  |
| GP41 Věcný správce stanovuje prioritu evidovaných požadavků na změny funkcí a služeb informačního systému. |  |  |
| GP42 Technický správce provozování produkčního prostředí |  |  |
| GP43 Technický správce provádí plánování a pravidelnou kontrolu dostupnosti a zajištění zdrojů potřebných k provozování AIS |  |  |
| GP44 Technický správce provádí pravidelnou kontrolu integrity dat |  |  |
| GP45 Technický správce provádí pravidelné zálohování a uchovávání dat bez přerušení provozu AIS |  |  |
| GP46 Technický správce provádí pravidelné testy obnovy všech funkcí, kódů a dat AIS do nového prostředí |  |  |
| GP47 Technický správce udržuje komponenty v provozuschopném a bezpečném stavu |  |  |
| GP48 Technický správce zajišťuje příjem a evidenci požadavků na změny funkcí a služeb AIS |  |  |
| GP49 Technický správce přijímá hlášení provozních událostí a vyhodnocuje závažnosti dopadu nalezených chyb, poruch a nedostatků AIS, vytváří a upřednostňuje servisní požadavky |  |  |
| GP50 Technický správce vyhledává škodlivé programové prostředky a škodlivé komunikace |  |  |
| GP51 Technický správce sleduje a analyzuje dopady provozních událostí |  |  |
| GP52 Technický správce nasazuje ověřené, funkční a formálně akceptované verze s předem otestovanou integrací bez ohrožení kvality a dostupnosti služeb AIS |  |  |
| GP53 Technický správce vytváří a předává datové výstupy k dlouhodobému uchovávání |  |  |
| GP54 Technický správce zajišťuje stanovenou úroveň kontinuity pro služby AIS, pro podporu služeb jiných AIS a pro provoz informačních systémů |  |  |
| GP55 řízení provozovatele AIS. |  |  |
| GP56 Věcný správce vyhodnocuje plnění stanovených požadavků na služby AIS |  |  |
| GP57 Věcný správce hodnotí přínosy služeb AIS |  |  |
| GP58 Věcný správce posuzuje ekonomickou výhodnost služeb AIS |  |  |
| GP59 Věcný správce kontroluje plnění cílů stanovených ve fázi strategického plánování vytvoření a rozvoje AIS. |  |  |
| GP60 Technický správce zajišťuje plnění věcným správcem stanovených požadavků na služby AIS |  |  |
| GP61 Technický správce zajišťuje bezpečnost AIS a aplikuje bezodkladně potřebná bezpečnostní opatření. |  |  |
| GP62 Technický správce zajistí transformaci údajů a export dat podle potřeb z AIS způsobem umožňujícím jejich dlouhodobé uchovávání nebo přenesení do informačního systému, který má původní AIS nahradit |  |  |
| GP63 Technický správce zajistí přenos aktuálních dat, kódů a prostředí v útlumovém režimu, je-li plánován. |  |  |
| GP64 Technický správce provádí export dat v rozsahu údajů, které AIS zpracovával k okamžiku ukončení jeho produkčního provozu s ověřením integrity dat. |  |  |
| GP65 Technický správce provádí export dat přednostně v otevřeném formátu. |  |  |
| GP66 Nastavuje governance útlumu: kdo a kdy může prostředí aktivovat, jak se udržuje, kdo má přístup a jak se data poskytují. Zajišťuje právní a provozní kontrolu. |  |  |

## Realizace potřebných změn
Musíme dořešit vazbu na další systémy, dodělat propojená na CMS2 a aktualizovat údaje v RPP. Dále musíme více dbát na plnění povinností věcného a technického správce a zaktualizovat provozní dokumentaci.


Odbor žabičkování jako věcný správce potvrzuje, že informace uvedené v tomto hodnocení jsou ke dni  platné, úplné a aktuální. Dále si uvědomuje výše popsaný nesoulad s některými požadavky a v termínu do 31. prosinec 2027 chce zajistit úplný soulad se všemi požadavky následujícími konkrétními kroky:



**Poznámky a doplnění**



