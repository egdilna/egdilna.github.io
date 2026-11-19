Konceptuální model specifikuje pojmy glosáře následujícím způsobem:

1)  S pojmy pracuje jako s typy, které klasifikuje do několika druhů:

* Pojem reprezentující osoby určitého druhu klasifikuje jako typ subjektu.
* Pojem reprezentující věci určitého druhu klasifikuje jako typ objektu.
* Pojem reprezentující určitou roli osob klasifikuje jako typ role.
* Pojem reprezentující určitou fázi osob klasifikuje jako typ fáze.
* Pojem reprezentující vztahy určitého druhu mezi osobami nebo mezi osobami a věcmi klasifikuje jako typ vztahu.
* Pojem reprezentující události určitého druhu klasifikuje jako typ události.
* Pojem reprezentující činnosti určitého druhu klasifikuje jako typ činnosti.
* Pojem reprezentující vlastnosti určitého druhu charakterizující osoby, věci, role, vztahy, události nebo činnosti klasifikuje jako typ vlastnosti.

| Pojem | Typ v konceptuálním modelu |
|---|---|
| silniční vozidlo| Typ objektu |
| vlastník vozidla| Typ role |
| vlastnictví vozidla| Typ vztahu |
| fyzická osoba (člověk)| Typ subjektu |
| technický průkaz| Typ objektu |
| příjmení fyzické osoby| Typ vlastnosti (subjektu) |
| číslo technického průkazu| Typ vlastnosti (objektu)|
| datum vydání technického průkazu| Typ vlastnosti (objektu) |
| datum pořízení vozidla| Typ vlastnosti (vazby) |
| havárie silničního vozidla| Typ události |
| zničené silniční vozidlo| Typ fáze (věci) |
| vyřazení silničního vozidla z provozu | Typ činnosti |

2) Doplňuje věcné (sémantické) souvislosti mezi pojmy.

* Přiřazuje typy vlastností k ostatním typům popsaným výše. Tím modeluje, jakými vlastnostmi mohou být charakterizovány jaké druhy osob, věcí, jaké role, atd.
* Přiřazuje k typům vztahů typy, které se vztahu účastní. Je možné následující přiřazení:
**  Typu vztahu se účastní pouze typy subjektů, rolí a fází. Tím modeluje vztahy mezi subjekty práva, příp. mezi subjekty práva v určitých rolích nebo fázích.
** Typu vztahu se účastní typ subjektu, role nebo fáze na jedné straně a typ objektu na druhé straně. Tím modeluje vztahy mezi subjekty práva na jedné straně a objekty práva na druhé straně.
* Přiřazuje typy subjektů, objektů, rolí, fází a vztahů k typům událostí a činností, které se jich týkají. Tím modeluje, že daná událost nebo činnost se během svého průběhu dotýká daných subjektů, objektů atd.
** subjekty, role nebo fáze jsou účastníky událostí či činností
** objekty jsou předměty událostí či činností
* Dále libovolně podle potřeb dané agendy propojuje typy subjektů, objektů, rolí a fází pomocí obecných pojmenovaných asociací. Tím modeluje souvislosti, které nejsou takového významu, aby byly modelovány jako typy vztahů
    * Obecná pojmenovaná asociace i typ vztahu modelují souvislosti. Zatímco ale typ vztahu je na stejné úrovni jako ostatní typy a může mít přiřazeny typy vlastností (tj. být charakterizován agendovými údaji), tak obecná pojmenovaná asociace je pouze prostým propojením bez jakékoliv možné charakteristiky agendovými údaji.
* Určuje specializační vazby, které modelují, že určitý typ je speciálnější než jiný typ (je jeho speciálním případem a každý prvek speciálního prvku je také prvkem specializovaného). Konkrétně specializuje:
    * Typy subjektů jinými typy subjektů nebo typy fází
    * Typy objektů jinými typy objektů nebo typy fází
    * Typy rolí jinými typy rolí
    * Typy fází jinými typy fází
    * Typy vztahů jinými typy vztahů
    * Typy událostí jinými typy událostí
    * Typy činností jinými typy činností
* Přiřazuje typy subjektů k typům rolí. Tím modeluje, že subjekty mohou vystupovat v rámci agendy v různých rolích.

Konceptuální model je vyjádřen v grafické podobě diagramu. Všechny typy kromě typů vlastností jsou zobrazeny jako obdélníky s názvem pojmu a s uvedením typu mezi symboly
<< >>. Typy vlastností přiřazené k typu jsou zobrazeny přímo jako součást příslušného obdélníku. Pozn.: Jedná se o notaci grafického jazyka UML diagramů tříd.
