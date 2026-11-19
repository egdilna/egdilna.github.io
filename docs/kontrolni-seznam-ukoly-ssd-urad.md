Verze 1.1

Zpracováno jako výstup projektu egdilna.cz a partnerů v rámci EG konkrétních postupů

## Úvod

Toto je kontrolní seznam a postup zejména využitelný pro architekty a odborníky pro ICT v úřadech. Udává podrobnosti a návody, jak postupovat v jednotlivé oblasti.

Tento postup se týká toho, jak postupovat při staovování jednotlivých úkolů s cílem splnit požadavky opatření ze Strategie správy dat VS.

Postup najdete vždy v rámci [sekce Postupy na webu metodiky.egdilna.cz](https://metodiky.egdilna.cz/postupy/eg-postupy)

Aktuální verze je na adrese

[https://metodiky.egdilna.cz/postupy/kontrolni-seznam-implementace-ssd](https://metodiky.egdilna.cz/postupy/kontrolni-seznam--implementace-ssd)

## Strategie správy dat veřejné správy

Strategie správy dat veřejné správy (označovaná jako SSD nebo SSDVS) je základním strategickým i implementačním rámcem pro nastavení správné správy dat veřejné správy s ohledem na plnění základních architektonických principů a to zejména architektonického principu č. 22 IKČR Datová suverenita a nezávislost.

Kromě řady konkrétních opatření a úkolů pro stát formou úkolů pro Vládu a Digitální a informační agenturu, přináší také povinně realizovatelná opatření pro jednotlivé úřady (pokud jsou správci dat či datových oblastí). Tento dokument udává rozpad opatření do konkrétních úkolů, kterými lze tato opatření splnit v úřadu.

## Jak postupovat při rozpadu opatření a plnění souvisejících úkolů v úřadu

###   Opatření 1.1.1 Stanovit odpovědnost za data úřadu a jejich správu
Úkol 1.  Jmenovat Manažera správy dat: zástupce nejvyššího nebo vyššího vedení úřadu v roli, která je celkově manažersky odpovědná za fungování a rozvoj správy dat v celém úřadu

Úkol 2. Jmenovat Hlavního datového architekta: zástupce úřadu v roli, která drží a rozvíjí celkový přehled o datech úřadu a znalostně podporuje výkon ostatních zde uvedených rolí

Úkol 3. Na úrovni jednotlivých věcných oblastí dat

Úkol 4. Pro jednotlivé oblasti určit věcné gestory také jako vlastníky dat: zástupci vedení úřadu v roli, která je manažersky a věcně odpovědná za data v konkrétní věcné oblasti („vlastníci dat“)

Úkol 5. Na úrovni jednotlivých oblastí a systémů určit správce dat: zástupci úřadu v roli, která je věcně odpovědná za data v konkrétní věcné oblasti a na každodenní bázi vykonává činnosti související s jejich věcnou správou, např. kontrolu jejich správnosti a úplnosti („věcní správci dat“)

Úkol 6. Pro jednotlivé oblasti a systémy určit technické správce také jako technické správce dat: zástupci úřadu v roli, která je technicky odpovědná za data v konkrétní věcné oblasti a na každodenní bázi vykonává činnosti související s jejich technickou správou, např. zajištění dostupnosti dat pro naplnění datových potřeb („techničtí správci dat“)

VÝSLEDEK:  V úřadu existují role, které mají explicitně přidělenou odpovědnost za data a jejich správu.
###   Opatření 1.1.2 Vydat a v praxi uplatňovat interní pravidla pro správu dat
Úkol 1.  Vytvořit vnitřní předpis či předpisy stanovující role a zodpovědnosti ve správě dat v celé organizaci, postupy a procesy správy dat a kvality dat

Úkol 2. Do vnitřních předpisů týkajících se kvality zahrnout i oblast kvality dat a řízení kvality u vlastních dat a sledování kvality u využívaných dat

Úkol 3. Do vnitřních předpisů týkajících se informačních systémů včetně ISVS zahrnout i oblast správy dat a související úkoly pro věcné správce a technické správce

Úkol 4. Do vnitřních předpisů týkajících se kybernetické bezpečnosti zahrnout postupy pro zachování bezpečnosti a integrity dat a procesy v rámci správy dat týkající se kybernetické bezpečnosti

Úkol 5. Do vnitřních předpisů v celé organizaci zahrnout problematiku klasifikací dat

VÝSLEDEK:  Platné vnitřní řídicí dokumenty úřadu obsahují pravidla související s dobrou správou dat, minimálně: vymezení rolí odpovědných za data (viz opatření 1.1.1), jimi vykonávaných činností a procesů souvisejících se správou dat, základní pravidla, která budou systematicky uplatňována např. pro popis dat (viz dále specifický cíl 1.3), řízení změn informačních systémů (viz dále opatření 1.4.2), řízení kvality a rizik souvisejících s daty
###   Opatření 1.2.1 Zmapovat a prioritizovat věcné oblasti dat
Úkol 1.  Vyjasnit si na úrovni vedení organizace a Hlavního datového architekta, jak se budou určovat oblasti pro správu dat, popřípadě zda a jaké oblasti organizace adoptuje z národní úrovně

Úkol 2. Zmapovat základní datové potřeby úřadu a rozdělit je na vlastní data, data využívána z jiných úřadů a data poskytnutá jinými subjekty (třeba klienty)

Úkol 3. Určit datové oblasti a u věcných gestorů je určit jako vlastníky dat

Úkol 4. Do architektury zanést datové oblasti a případné vazby na zodpovědnosti, oblasti činností a informační systémy

Úkol 5. Určit, které datové oblasti jsou pro úřad Prioritní datové oblasti (s daty se musí pracovat lépe a ve větší prioritě než z ostatními)

Úkol 6. Do informační koncepce OVS zanést Prioritní datové oblasti a zodpovědné věcné gestory a správce dat

VÝSLEDEK:  Existuje a je udržováno aktuální vymezení věcných oblastí dat úřadu a jejich priority
###   Opatření 1.2.2 Stanovit a řídit datové potřeby v prioritních oblastech
Úkol 1.  Vytvořit alespoň jednoduchou systematickou evidenci příležitostí a potřeb správy dat alespoň pro prioritní oblasti dat

Úkol 2. Nastavit procesy sběru a správy požadavků na data, potřeb a příležitostí správy dat

Úkol 3. Vyjasnit si, jak budou požadavky a potřeby a příležitosti pro data naplňovány jak v úřadu, tak i v součinnosti s ostatními úřady

Úkol 4. U zmapovaných datových potřeb určit, o jaká data jde, v jaké struktuře a granularitě jsou, z jakého zdroje se mají brát a případně komu je poskytovat

Úkol 5. Kategorizovat potřeby dle druhů dat, přitom využít kategorizace dle vyhlášky 360/2023

*  Podle zdroje a formy využívání: údaje ze základních registrů, údaje z jiných agend, vlastní agendové údaje, provozní údaje, statistické údaje
*  Podle způsobu jejich sdílení na údaje veřejně přístupné, údaje poskytované na žádost, údaje zpřístupňované pro výkon agendy.

Úkol 6. Aktivně řešit potřeby sdílení dat zejména v rámci agend a výkonu veřejné správy a činností úřadu

Úkol 7. Průběžně projednávat stav realizace potřeb na architektonickém boardu a na vedení a aktualizovat příslušné evidence

Úkol 8. Potřeby dat, pro které není připraven poskytovatel, či neexistuje známý relevantní zdroj dat, konzultovat také s DIA

VÝSLEDEK:  Úřad systematicky identifikuje, popisuje a eviduje příležitosti související s daty a datové potřeby uživatelů, minimálně v prioritních oblastech
###   Opatření 1.2.3 Formulovat v rámci Informační koncepce úřadu strategii v oblasti správy dat
Úkol 1.  Do informační koncepce OVS doplnit oblast správy dat jako jednu z klíčových oblastí fungování a efektivity

Úkol 2. Při vyhodnocování souladu s principy IKČR ve své informační koncepci správně vyhodnotit i architektonický princip 22 Datová nezávislost

Úkol 3. Nezapomenout jako jednu z předpisových motivací či byznysových kontraktů uvést ve své informační koncepci i Strategii správy dat VS

Úkol 4. Ve své informační koncepci v přehledech zhodnocení vytvořit zhodnocení a naplnění příslušných opatření ze Strategie správy dat VS

Úkol 5. Ve své informační koncepci uvést jak bude implementován architektonický princip IKČR č 22 Datová nezávislost a suverenita

Úkol 6. Adoptovat cíle a opatření ze Strategie správy dat VS a k principu IKČR č. 22 a případně doplnit vlastními cíly a principy ke správě dat a datovým analýzám

Úkol 7. Do záměrů ve své informační koncepci a do Katalogu záměrů zanést a sledovat záměry týkající se správné správy dat a plnění Strategie správy dat VS

VÝSLEDEK:  V Informační koncepci úřadu jsou zohledněny střednědobé a dlouhodobé datové potřeby v prioritních oblastech a zahrnuty strategické aktivity směřující ke kvalitní správě dat úřadu
###   Opatření 1.3.1 Popsat data a definovat jejich význam
Úkol 1.  Nastudovat konceptuální datové modelování jako schopnost a určit zodpovědné osoby a edukovat je ke tvorbě slovníků a KDM

Úkol 2. Zavést jednotnou systematickou evidenci pro datové slovníky a základy konceptuálního modelování (nemusí být plnohodnotný modelovací nástroj)

Úkol 3. Pro prioritní oblasti si vytvořit základní datový slovník zejména pro data a údaje vedené v informačních systémech úřadu

Úkol 4. Zavést nástroj pro plnohodnotné konceptuální modely

Úkol 5. Zjistit si a získat centrálně vydané KDM pro již modelované agendy a oblasti a navázat na ně ve svých modelech KDM

Úkol 6. Nejlépe formou odkazů provázat údaje datového slovníku a KDM s datovou architekturou daného informačního systému
###   Opatření 1.3.2 Vytvořit a využívat lokální katalog dat a předávat jeho obsah do národního katalogu dat
Úkol 1.  Zavést nástroj pro datový katalog, buď rovnou i jako lokální katalog otevřených dat, či na něj v budoucnu napojený. Lze využít rozšíření evidence pro datové modelování

Úkol 2. Doplnit podstatné údaje (třeba o zdroji a získávání) k jednotlivým datům v prioritních oblastech dat úřadu do lokálního katalogu

Úkol 3. Zajistit obousměrnou výměnu údajů z budoucího Národního katalogu dat do lokálního katalogu

*  pro datové modely publikované DIA směrem do lokálního katalogu jako povinně přebíranou součást KDM
*  svoje KDM směrem do národního katalogu pro posouzení a publikaci ostatním

Úkol 4. Rozlišit v rámci LKD část pro interní potřebu a část pro specifikaci metadat publikovaných otevřených dat (LKOD)

Úkol 5. Napojit LKOD na NKOD způsobem pokud možno obousměrné vazby - tedy předávání metadat z LKOD do NKOD rozhraním a naopak možnost získání metadat o cizích datových sadách z NKOD do LKOD a do části pro interní datový katalog
###   Opatření 1.3.3 Rozlišit kategorie dat a přizpůsobit procesy správy dat jejich specifikům
Úkol 1.  Kategorizovat v každé datové oblasti jednotlivá data dle druhů dat, přitom využít kategorizace dle vyhlášky 360/2023

*  Podle zdroje a formy využívání: údaje ze základních registrů, údaje z jiných agend, vlastní agendové údaje, provozní údaje, statistické údaje
*  Podle způsobu jejich sdílení na údaje veřejně přístupné, údaje poskytované na žádost, údaje zpřístupňované pro výkon agendy

Úkol 2. Zvážit zavedení úplné klasifikace dat alespoň pro klíčová data v prioritních oblastech, lze využít vzorové klasifikační schéma
###   Opatření 1.4.1 Vytvořit v úřadu podmínky pro poskytnutí dat jiným úřadům
Úkol 1.  Zmapovat v rámci datových potřeb také potřeby jiných agend a úřadů v rámci výměny v propojeném datovém fondu

Úkol 2. Reagovat rychle a správně na potřeby cizích agend a úřadů související s vámi spravovanými údaji

Úkol 3. S DIA řešit kontexty pro sdílení a poskytování údajů v rámci propojeného datového fondu

Úkol 4. Každý informační systém publikující údaje v propojeném datovém fondu upravit tak, aby poskytoval správně údaje přes EGSB a kontexty

ins

###   Opatření 1.5.1 Zavést v úřadu základní postupy pro zajištění kvality dat

Úkol 1.  Zahrnout kvalitu dat do procesů řízení kvality v úřadu

Úkol 2. Stanovení kritérií kvality dat podle druhů datových potřeb a prioritních oblastí dat

Úkol 3. Evidence nedostatků ve kvalitě dat jako součást QM

###   Opatření 1.5.2 Zavést v úřadu základní řízení rizik v oblasti dat

Úkol 1.  Stanovit rizika v rámci datových potřeb úřadu

Úkol 2. Zahrnutí nejzávažnějších rizik plynoucích z datových potřeb do formálního řízení rizik

Úkol 3. Evidence řešení rizik plynoucích z datových potřeb a správy dat

/ins

###   Opatření 1.4.2 Zohledňovat při zadávání a řešení změn IS dopady na data a jejich správu
Úkol 1.  Zpracovat a uplatňovat základní vnitřní metodiku řešení správy dat a datových potřeb v informačních systémech a pro přípravu jejich změn

Úkol 2. Při tvorbě záměru na změnu IS v souladu s fází Strategického plánování a Plánování změny IS do dokumentu zahrnout také oblast dat a jejich správy a potřeb

Úkol 3. Při přípravě pořízení či každé změny informačního systému jeho věcný a technický správce

*  identifikuje dopady změn na data a zapojuje do řešení datové role (viz opatření 1.1.1) z dotčených oblastí
*  zohledňuje i potřeby případných analytických uživatelů dat
*  ·       zajišťuje svou datovou suverenitu a nezávislost na dodavatelích
*  ·       definuje požadavky na datovou architekturu a dodávané popisy/modely dat
*  ·       definuje požadavky na otevírání dat nebo jejich sdílení v rámci propojeného datového fondu
*  ·       zajišťuje připravenost řešení na kontrolu kvality dat a zajištění kvality dat
*  ·       zajišťuje připravenost řešení na trvalou archivaci dat při ukončení provozu systému

Úkol 4. Zpracovat a striktně ve smluvních vztazích uplatňovat požadavky související s daty na dodavatele

Úkol 5. Požadavky na migrace dat a související zahrnout do smluvních vztahů pro exit strategie s dodavateli stávajících řešení

Úkol 6. Do současných smluvních vztahů se stávajícími dodavateli doplnit požadavky na popis dat, datovou architekturu, datové modely a požadavky související s daty i do provozní dokumentace

Úkol 7. Do provozní dokumentace doplnit věci k datům v systému a jejich datovým popisům či modelům
###   Opatření 4.1.1 Publikovat veřejná data úřadu ve formě otevřených dat
Úkol 1.  Zmapovat a zavést evidenci, jaké veřejné informace zveřejňované způsobem umožňujícím dálkový přístup, úřad vede a jak je publikovat jako otevřená data

*  Pro údaje exaktně vyjmenované jako otevřená data v konkrétním národním či evropském předpisu
*  Pro všechny veřejné rejstříky, seznamy a evidence vedené úřadem a zveřejňované způsobem umožňujícím dálkový přístup
*  Pro relevantní informace uvedené ve vyhlášce 515/2020
*  a samozřejmě pro metadata datových sad

Úkol 2. Jmenovat zodpovědné role a to zejména Kurátora otevřených dat v úřadu a správce jednotlivých datových sad

Úkol 3. Pravidelně aktualizovat Publikační plán s požadavky a potřebami publikace dat dle zákonných povinností

Úkol 4. Jelikož tomu nebrání právní předpis, zveřejňovat publikační plán a evidenci připravovaných publikovaných dat

VÝSLEDEK:  Jsou naplněny existující zákonné povinnosti v oblasti publikace otevřených dat (vyplývající především z relevantních částí zákona č. 106/1999 Sb., o svobodném přístupu k informacím), tzn. minimálně všechny zákonem předepsané informace jsou zveřejněny formou otevřených dat.
###   Opatření 4.1.2 Monitorovat plnění povinností v oblasti otevřených dat
Úkol 1.  Upravit vnitřními předpisy mechanismus pravidelného ročního vyhodnocování plnění povinností a potřeb publikování otevřených dat úřadem a stanovit způsob projednání vedením

Úkol 2. Upravit vnitřními předpisy mechanismus pravidelného ročního přezkumu využívání jinými poskytovateli publikovaných otevřených dat pro činnosti úřadu

Úkol 3. Jednou ročně vypracovat základní informaci o výsledku zhodnocení plnění povinností k publikaci otevřených dat

Úkol 4. Roční zhodnocení zaslat DIA, a pokud existuje taková povinnost, tak také Vládě ČR či Evropské komisi

Úkol 5. Plnění povinností a posunu v publikaci otevřených dat, stejně jako plnění souvisejících opatření zahrnout do vyhodnocení při pravidelném vyhodnocování plnění informační koncepce OVS

Úkol 6. Problémy při řešení publikace otevřených dat a plnění souvisejících povinností konzultovat s DIA a využít jejich znalostí a zkušeností z praxe

VÝSLEDEK:  Je nastaven pravidelný každoroční monitoring stavu plnění povinností dle opatření 4.1.1. a jeho následné vyhodnocování vč. reportování dílčích bodů vládě ČR, Evropské komisi a dalším mezinárodním institucím.
###   Opatření 4.3.2 Formulovat v rámci Informační koncepce úřadu strategii analytické práce s daty
Úkol 1.  Do informační koncepce OVS doplnit do části B kapitolu Potřeby analytické práce s daty

Úkol 2. Stanovit si cíle pro datové analýzy a související záměry a uvést je ve své informační koncepci OVS

Úkol 3. Při vyhodnocování plnění informační koncepce OVS vyhodnocovat také cíle a záměry týkající se datových analýz a analytické práce s daty

VÝSLEDEK:  V Informační koncepci úřadu jsou zohledněny střednědobé a dlouhodobé potřeby úřadu v oblasti datových analýz a zahrnuty strategické aktivity směřující k vybudování koncepčního řešení těchto potřeb.
