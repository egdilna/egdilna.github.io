| Typ | ID | Name | Format | Description | Flags | Sources | Notes |
|---|---|---|---|---|---|---|---|
| (Věc) | Zamer | Záměr |   | Definovaný záměr ICT zapsaný v Katalogu záměrů OVS a v Informační koncepci úřadu, může být ale posléze zapsán i do národního Katalogu záměrů Digitálního Česka |  |  |  |
| (Vlastnost) | Kod | Kód záměru | Text | Jednoznačný identifikátor v podobě volného kódu záměru, jímž je identifikován v daném úřadu. Kódy se vytvářejí v libovolné, ale jednoznačné struktuře srozumitelné pro úřadu. Podle tohoto jednoznačného kódu se záměr určuje a lze na něj tímto kódem i odkazovat odjinut. |  |  |  |
| (Vlastnost) | Nazev | Název záměru | Text | Jednoznačný a výstižný název záměru |  |  |  |
| (Vlastnost) | Popis | Stručný popis záměru | Memo | Popis záměru, z nějž je možné vyčíst o co jde a čeho se má dosáhnout. |  |  |  |
| (Vlastnost) | StavDC | Stav záměru | Value | Stav záměru podle metodiky k Digitálnímu Česku. Jde o závaznou hodnotu A, B, C, D, R, U, Z, jak je popsáno v příslušném modelu metodiky Katalogu záměrů DČ. |  | Číselník stavu záměru |  |
| (Vlastnost) | Stav | Stav realizace | Value | Stav v daném úřadu popisující prlběh realizace, je vhodné, aby byl shodný se stavy v rámci projektového řízení používaného v daném úřadu. |  | využije se číselník obvyklý v daném úřadu |  |
| (Vlastnost) | cile | Realizované cíle | Multivalue | Označení všech relevantních cílů, které záměr realizuje a na které je vázán, využije se standardizované označení (kupříkladu IKČR1.3, IKOVS2, apod.) |  | seznam cílů IKČR a cílů OVS |  |
| (Vlastnost) | plan-od | Plán od | Date | Plánované období - začátek |  |  |  |
| (Vlastnost) | plan-do | Plán do | Date | Plánované období - konec |  |  |  |
| (Vlastnost) | realne-od | Realizace od | Date | Skutečně realizováno - začátek |  |  |  |
| (Vlastnost) | realne-do | Realizace do | Date | Skutečně realizováno - konec |  |  |  |
| (Vlastnost) | utvar-zodpovedny | Zodpovědný útvar | Value | Útvar, jež po věcné stránce řídí realizaci záměru a je zodpovědný za jeho úspěšnou realizaci a dokončení, je hlavním editorem daného záměru v katalogu. |  | organizační struktura |  |
| (Vlastnost) | utvar-spolupracuji | Spolupracující útvary | Multivalue | Seznam všech aktivně spolupracujících útvarů, jejichž spolupráce je nezbytná pro splnění záměru |  | organizační struktura |  |
| (Vlastnost) | osoba-manazer | Manažer | Person | Konkrétní osoba v roli manažera koordinujícího realizaci záměru a za záměr také zodpovídá |  | seznam zaměstnanců |  |
| (Vlastnost) | osoba-dohled | Dohlížitel | Person | Konkrétní osoba, jež je součástí vedení úřadu, nebo boardu, která vedení odpovídá za daný záměr |  | seznam zaměstnanců |  |
| (Vlastnost) | prubeh | Informace o průběhu | Area | Zde se vedou popisné informace o faktické realizaci tedy postupu plnění daného záměru. Sleduje se zde průběh a proto jde o řadu po sobě jdoucích hodnot se záznamem historie. |  |  |  |
| (Vlastnost) | ik-od | V IK od | Number | Rok verze IK v níž byl záměr schválen |  |  |  |
| (Vlastnost) | ik-do | V IK do | Number | Rrok verze IK v níž proběhlo závěrečné vyhodnocení záměru |  |  |  |
| (Vlastnost) | ik-vyhodnoceni | Text do vyhodnocení IK | Memo | Text jež vedení poskytuje zhodnocení stavu při vyhodnocení plnění IK, v aktualizaci IK bude uveden u vyhodnocení záměru a sleduje se v čase |  |  |  |
