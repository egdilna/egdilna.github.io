Publikující AIS je [[Agendový informační systém|agendový informační systém]], který poskytuje údaje své agendy ostatním agendám přes [[Propojený datový fond|propojený datový fond (PPDF)]]. Je technickou realizací povinnosti [[Poskytování agendových údajů|poskytování agendových údajů]]. Jeho protějškem je [[Čtenářský AIS|čtenářský AIS]], který údaje odebírá.

**Jak publikující AIS funguje**

Publikující AIS není samostatný systém – je to role, kterou plní existující AIS agendy. Komunikuje přes [[Informační systém sdílené služby|eGSB]], nikdy napřímo s čtenáři. Musí vystavit typizované služby:

- výdej údajů o konkrétní osobě nebo objektu podle [[Agendový identifikátor fyzické osoby|AIFO]] nebo jiného identifikátoru,
- notifikace o změnách údajů,
- výdej změněných údajů za období,
- případně hromadný výdej údajů.

Podrobný popis služeb je na stránce [[Typizované služby AIS: Služby k propojenému datovému fondu a údajům]] a postup napojení v [[Rámcový postup pro realizaci sdílení údajů v propojeném datovém fondu]].

👉 Příklad: AIS evidence řidičů vystaví přes eGSB službu, která na dotaz obecního úřadu vrátí, zda má osoba platné řidičské oprávnění. Úřad nemusí po občanovi chtít kopii řidičského průkazu.

**Odpovědnost správce**

- Správce publikujícího AIS odpovídá za správnost a aktuálnost poskytovaných údajů.
- Zajišťuje dostupnost služeb a jejich výkon i při zátěži od mnoha čtenářů.
- Poskytuje údaje jen těm, kdo k nim mají oprávnění podle RPP.
- Vede logy o poskytnutí údajů.

**Častá úskalí**

- Služby jsou navržené jen pro jednoho konkrétního odběratele, ne obecně pro všechny oprávněné čtenáře.
- Chybí notifikace o změnách, takže čtenáři musí údaje stále znovu dotazovat.
- Výkon systému nikdo nepočítal s dotazy z celé veřejné správy.
