Subjekty, které v rámci své činnosti vyžadují předložení průkazu (např. občanského), mají **povinnost [[eDoklady]] akceptovat**. Pokud právní úprava nevyžaduje prokázání průkazem, povinnost akceptace se nevztahuje, ale subjekt může eDoklady akceptovat dobrovolně.

Pro ověřování eDokladů se musí **organizace zaregistrovat do systému eDokladů**. Orgány veřejné moci (OVM) se registrují přes **Identifikační systém pro veřejnou správu (IJSC)**. Správu uživatelských účtů a přiřazování rolí v IJSC provádí **lokální administrátor** organizace. Kromě přístupu přes IJSC lze využít i **lokální účet**, který je vhodnější pro soukromoprávní subjekty, ale OVM jej mohou také využít. Lokální účty zakládá a spravuje osoba s rolí správce v aplikaci Správa ověřovatelů.

V systému eDokladů pro ověřovatele existují **tři základní role**:

1.  **Správce:** Nejdůležitější role, obvykle přidělená lokálnímu administrátorovi IJSC nebo jiné pověřené osobě (např. informatikovi). Správce má přístup do aplikace **Správa ověřovatelů (spravadoklady.gov.cz)**, kde administruje nastavení přístupů (mobilní aplikace, webová čtečka), datových sad, přepážek, propojení systémů a kontroluje/ruší účty. Rolí správce může disponovat více osob. Přístup k roli Správce v IJSC musí být nastaven lokálním administrátorem. Lze založit i lokální účet s rolí správce.
2.  **Ověřovatel:** Tato role umožňuje přístup do ověřovacích aplikací (mobilní aplikace a webová čtečka). Přístup se uděluje buď přes IJSC (nastaví lokální administrátor ve správě dat) nebo přes lokální účet (založí správce v aplikaci Správa ověřovatelů). Ověřovatel se nepřihlašuje do aplikace Správa ověřovatelů.
3.  **Správce skupiny:** Role, která spravuje konkrétní skupinu (např. oddělení, pobočka) v rámci organizace. Má rozšířená oprávnění v rámci své skupiny (např. zakládat přepážky, přidělovat sady) bez nutnosti přístupu do hlavní aplikace Správa ověřovatelů. Vhodné pro organizace s širší organizační strukturou.

Ověřovat lze dvěma způsoby:

*   **Mobilní aplikace eDoklady (pro ověřovatele):**
    *   Ověřovatel stáhne aplikaci eDoklady (stejná jako pro občany).
    *   **Registrace** jako ověřovatel probíhá buď přes lokální účet, přes IJSC (nedoporučuje se pro všechny způsoby přihlášení IJSC, např. komerčním certifikátem), nebo pomocí **párovacího kódu** vygenerovaného správcem v aplikaci Správa ověřovatelů. Párovací kód má platnost 7 dní a slouží k registraci na konkrétním zařízení.
    *   Pro ověření musí mít ověřovatel i občan **zapnutý Bluetooth**.
    *   Ověřovatel si v aplikaci vybere **ověřovací sadu** (rozsah údajů, které požaduje).
    *   Ověřovatel **naskenuje QR kód** zobrazený v aplikaci občana.
    *   Občan ve své aplikaci **udělí souhlas** s předáním údajů kliknutím na "sdílet údaje".
    *   Údaje se zobrazí ověřovateli v jeho aplikaci.
    *   Tento způsob **funguje v offline režimu** (bez připojení k internetu) mezi oběma telefony. Je vhodný pro ověřování v terénu.
    *   Poskytnuté údaje lze v mobilní aplikaci stáhnout ve formátu PDF, pokud je datová sada nastavena i ke zpracování (nejen ke kontrole).
*   **Webová aplikace (čtečka.edoklady.gov.cz):**
    *   Ověřovatel se přihlásí do webové aplikace (odlišná adresa od Správy ověřovatelů). Přístup je přes IJSC nebo lokální účet s rolí Ověřovatel nebo Správce.
    *   K provozu je potřeba **počítač/notebook/tablet s připojením k internetu** a **displej nebo tiskárna pro zobrazení/vytisknutí QR kódu**.
    *   Ověřovatel se přihlásí k **přepážce**. Přepážky zakládá správce nebo správce skupiny. V jednu chvíli může být k jedné přepážce přihlášena jen jedna osoba.
    *   Přepážka musí mít **vygenerovaný QR kód**, který má platnost 30 dní a lze ho vytisknout nebo zobrazit na displeji. QR kód je navázaný na konkrétní přepážku. Pravidelná obměna QR kódu (každých 30 dní) je z bezpečnostních důvodů.
    *   Ověřovatel musí mít **nastavenou datovou sadu** (rozsah údajů, které požaduje). Datové sady pro organizaci nastavuje správce; lze zakázat používání vlastních nebo globálních sad a povolit jen sady organizace.
    * **Proces ověření:**
        *  Ověřovatel se přihlásí k přepážce a **vybere ověřovací sadu**.
        *  Ověřovatel **aktivuje proces ověření** kliknutím na "zkontrolovat" u vybrané sady. Toto je klíčové – bez aktivace proces neproběhne správně.
        *  Občan **naskenuje zobrazený QR kód** pomocí své aplikace eDoklady.
        *  Občan ve své aplikaci **udělí souhlas** s předáním údajů.
        *  Údaje se zobrazí ověřovateli ve webové aplikaci.
    *   Tento způsob **vyžaduje, aby občan měl svůj telefon připojený k internetu** (mobilní data, klientská Wi-Fi). Poskytování klientské Wi-Fi ověřovatelem není povinné ze zákona, ale doporučuje se pro proklientský přístup.
    *   Poskytnuté údaje lze v této aplikaci **dále zpracovávat** (stáhnout v PDF, zkopírovat, předat přes API), pokud je datová sada nastavena i ke zpracování.

**Nastavení datových sad** je klíčové. Lze je nastavit pouze **ke kontrole** (údaje se zobrazí, ale nelze je stáhnout/exportovat, po ukončení kontroly se smažou) nebo **ke zpracování** (lze je stáhnout/exportovat pro další evidenci/systémy). **Doporučuje se dbát na minimalizaci požadovaných údajů** z důvodů GDPR a lepší akceptace ze strany občana – žádat jen ty údaje, které jsou pro daný úkon skutečně potřeba.

Pro automatizaci předávání údajů do vlastních systémů lze využít **API integraci**. Jsou k dispozici tři možnosti: hromadné kopírování do schránky v prohlížeči, napojení na naši webovou čtečku přes API na pozadí, nebo implementace QR kódu přímo ve vlastním rozhraní s napojením na náš systém. Technická dokumentace je dostupná na webových stránkách eDokladů.

Ohledně **GDPR**, ověřující subjekt je **samostatným správcem osobních údajů**, jakmile je obdrží po ověření. Doba uchování údajů se řídí příslušnými právními předpisy souvisejícími s konkrétní agendou.

V případě jakýchkoli pochybností při ověřování eDokladu se doporučuje ověřit platnost průkazu v příslušné evidenci (např. Registr obyvatel), pokud k ní má ověřovatel přístup. Při každém ověření se v aplikaci zobrazuje fotografie prokazující osoby.

**Další specifické situace:**
*   **Neplatný eDoklad:** Pokud je digitální stejnopis starší 48 hodin nebo je neplatný z jiného důvodu (např. zneplatnění fyzického dokladu), ověřovatel může ověření odmítnout a žádat platný eDoklad nebo fyzický doklad.
*   **Ověřování v terénu:** Nejpraktičtější je mobilní aplikace kvůli offline režimu. Webovou čtečku lze použít na notebooku/tabletu s internetem.
*   **Více osob na jednom služebním telefonu:** V jedné mobilní aplikaci lze mít více registrací pro různé zaměstnance s vlastním PINem/biometrikou, nebo lze mít jednu registraci pro více osob (např. přes párovací kód s PINem známým všem uživatelům telefonu). Správce má přehled o registrovaných zařízeních a může registrace zrušit.
*   **Příspěvkové organizace obce (školy, knihovny, MP atd.):** Pokud mají vlastní datovou schránku nebo přístupy přes IJSC, mohou se registrovat pro ověřování eDokladů samy a ověřovat jménem svého subjektu. Pokud jsou organizační složkou obce bez vlastní právní subjektivity/datové schránky, přístupy jim nastavuje obec (lokální administrátor/správce) a ověřují jménem obce.
*   **Volby od 1. ledna 2025:** Okrskové volební komise budou mít povinnost akceptovat eDoklady. Obce by měly zajistit přípravu členů komisí, včetně nastavení přístupů a dostupnosti aplikací (mobilní i webové). Připravuje se metodika ve spolupráci s Ministerstvem vnitra.
*   **Externí zaměstnanci/firmy:** Pokud mají smluvní vztah s obcí, mohou ověřovat buď jménem svého subjektu (pokud jsou registrováni pro ověřování), nebo jménem obce, pokud jim obec udělí přístup (např. přes párovací kód pro mobilní aplikaci nebo lokální účet). Důležité je, že občan při ověření vidí, jaký subjekt ověřuje, což může ovlivnit jeho důvěru.
*   **Nezletilé osoby:** Mohou používat eDoklady, pokud splní podmínky – mají platný fyzický občanský průkaz a Identitu občana (např. aktivovaný Mobilní klíč eGovernmentu od 15 let).
*   **Cizinci:** V tuto chvíli nemohou eDoklady využívat, protože aplikace podporuje pouze digitální stejnopis českého občanského průkazu.
*   **Policie ČR:** Akceptuje eDoklady v terénu od 1. dubna 2024 a na služebnách od 1. července 2024.

Veškeré podrobné návody, průvodce pro obce a úřady, informace k nastavení přístupů, ověřování a technické dokumentace k API jsou dostupné na oficiálních stránkách **edokladovka.cz**. Pro dotazy a podporu jsou zřízeny e-mailové kontakty (věcné/metodické, technická podpora Portálu občana, technická podpora k API).

---
