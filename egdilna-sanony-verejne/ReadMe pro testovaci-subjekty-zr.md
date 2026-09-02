# Testovací subjekty základních registrů — README

Soubor **`testovaci-subjekty-zr.dkmdata`** je datový balík ve formátu **DKM JSON** obsahující testovací identity základních registrů ČR (ROB, ROS), doklady a číselník států — postavený na volně dostupných testovacích datech Digitální a informační agentury (SZR/DIA) a Znalostní báze [archi.gov.cz](https://archi.gov.cz/znalostni_baze:testovaci_identity).

## Jak otevřít

Balík otevře libovolný nástroj, který umí formát DKM JSON. Doporučený je **DKM (Dynamický správce znalostí)** — jednosouborová webová aplikace bez instalace, běží celá v prohlížeči:

- **Aplikace:** <https://nastroje.egdilna.cz/dkm>
- **Popis nástroje:** <https://nastroje.egdilna.cz/#dkm>

Otevři DKM, přetáhni na plochu soubor `testovaci-subjekty-zr.dkmdata` nebo použij *Načíst → Ze souboru*. Data se nikam neposílají, vše se zpracovává v prohlížeči.

## Co je uvnitř (aktuální verze 1.6)

| Typ | Počet | Popis |
|---|---:|---|
| 👤 Fyzická osoba | 52 | Osoby v ROB — 46 z SZR excelu + 6 fixních z archi.gov.cz |
| 🏢 Právnická osoba | 99 | PO i PFO v ROS — 94 z SZR excelu + 5 fixních z archi.gov.cz |
| 🪪 Doklad | 36 | Doklady s vazbou na FO (držitel) |
| 🌍 Stát | 280 | Kompletní číselník států |
| ℹ️ Informace | 2 | Popis vzorových dat + přehled nejlépe vyplněných entit |

**Číselníky:** Pohlaví, Rodinný stav / partnerství, Druh dokladu, Typ pobytu (AISEO), Právní forma (116 hodnot), Právní stav ROS, Typ datové schránky, Typ osoby v ROS.

**Vazby** jsou realizované jako atributy typu `relation` (Občanství, Stát narození, Držitel, Statutární zástupce, Podnikatel) a paralelně jako dvoustranné vazby *Má jednatele / Jednatel* a *Má podnikatele / Podniká jako*.

**Fixní identity** z archi.gov.cz jsou označené atributem *Fixní testovací identita = Ano* (15 FO, 5 PO).

Podrobný popis, statistiky vazeb a přehled vhodných identit pro demo najdeš přímo v šabloně — v inboxu jsou dvě entity typu *Informace*.

## Zdroje

- SZR — testovací data ROB: <https://www.szrcr.cz/cs/sluzby/spravci-a-vyvojari/vyvojari-agendovych-informacnich-systemu/testovaci-data-rob>
- SZR — testovací data ROS: <https://www.szrcr.cz/cs/sluzby/spravci-a-vyvojari/vyvojari-agendovych-informacnich-systemu/testovaci-data-ros>
- archi.gov.cz — Testovací identity: <https://archi.gov.cz/znalostni_baze:testovaci_identity>

## Licence a použití

Testovací data pocházejí z veřejných zdrojů SZR/DIA a jsou určena výhradně k testovacím a modelovacím účelům. Osoby a subjekty v datech jsou smyšlené.
