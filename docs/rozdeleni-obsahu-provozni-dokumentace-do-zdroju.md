Vedení [[provozní dokumentace]] pro informační systémy je podřízeno její obsahovou strukturou ([[Struktura provozní dokumentace]]). Nicméně v souladu s ostatními povinnostmi orgánu veřejné správy jako [[správce ISVS]]  si [[technický správce IS]] může obsahdokumentace rozdělit do základních zdrojů:

## V architektuře

**V architektuře se jedná o tyto části obsahu:**

| Část obsahu dokumentace | Jak vést v architektuře |
|---|---|
| Popis architektury úřadu | EA v rozsahu potřebném pro daný systém |
| Vlivy působící na informační systém a z nich plynoucí předpokládané změny a cíle informačního systému | Na motivační vrstvě zakreslená motivační architektura s vazbou na systém v aplikační vrstvě, doplněno případně o další prvky na motivační vrstvě z EA úřadu |
| Požadavky kladené na informační systém při jeho vytvoření nebo rozvoji | Sada požadavků v rámci architektury jako requirementy, doplněná o tabulku/seznam/model všech požadavků |
| Popis architektury řešení | Celá solution architektura ve vazbě na EA architekturu úřadu |
| Přehled dekomponování informačního systému na komponenty |  Aplikační dekompozice na úrovni systému a jednotlivých komponent |
| Výčet komponent informačního systému, jejich vzájemných vazeb a vazeb na jiné informační systémy | Vazby mezi prvky na aplikační vrstvě, doplněno o základní aplikační prvky a jejich rozhraní u cizích systémů z EA architektury úřadu či z architektury řešení daného systému |
| Přehled dostupných funkcí a poskytovaných služeb informačního systému | Aplikační služby a aplikační funkce vázané na jednotlivé komponenty |
| Popis programových rozhraní | V aplikační architektuře zakreslená rozhraní a jejich vazba na jiná rozhraní, doplněno o dokumentaci těchto rozhraní |
| Výčet komponent a sdílených prvků technologické a komunikační infrastruktury, které jsou nutné pro provoz informačního systému | Technologická vrstva architektury s technologickými komponentami a dalšími prvky vrstvy ve vazbě na aplikační vrstvu |

## V Evidenci aplikací

**V evidenci aplikací jako master data systému o aplikacích se jedná o tyto části a znalosti**

- Základní údaje o aplikaci
    - Název informačního systému a jeho popis z charakteristiky 

    * Název a popis každé aplikační komponenty systému (musí se shodovat s architektonickými prvky komponent systému vázaných na daný IS)

    * Věcný správce informačního systému a Technický správce informačního systému (uvedení konkrétních osob)

    * Útvar věcného gestora za agendu či oblast

    * Garanti primárních aktiv a garanti podpůrných aktiv a garanti technických aktiv souvisejících se systémem (odkaz na konkrétní osoby u primárních aktiv, odkaz na evidenci systémů a komponent u podpůrných a technických aktiv)

    * odkaz na záznam v rejstříku informačních systémů veřejné správy a soukromoprávních systémů pro využívání údajů, v němž jsou údaje o informačním systému vedeny

- Další údaje o informačním systému

    * vyhodnocené bezpečnostní úrovně informačního systému a jeho jednotlivých komponent (ve vazbě na systém a jeho komponenty)

    * Uživatelské role, nebo odkaz na definici rolí jinde a popis jejich významu a oprávnění v daném systému

- Dokumentace

    * Odkaz na typový pis s provozní dokumentací do ESSL

    * Odkaz na bezpečnostní dokumentaci k systému podle legislativy ke kybernetické bezpečnosti

    * Odkaz na úložiště dokumentů s průběžně aktualizovanou provozní či další dokumentací k systému

    * Informace o aktualizacích provozní dokumentace

    * Provazba na systém pro přístup k systémovým, administrátorským logům a logům o operacích s daty v daném systému
