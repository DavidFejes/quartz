
**DEFINÍCIÓ**: Azt a halmazt, amelynek a vizsgált halmazok részhalmazai, ==alaphalmaz==nak vagy ==univerzum==nak nevezzük. Jele: U vagy H. 
	
**DEFINÍCIÓ:** Egy A halmaz [komplementer halmazának](Komplementer_Halmaz.png) az alaphalmaz azon elemeinek halmazát nevezzük, amelyek az A halmaznak nem elemei. Jele: $\overline{A}$. (Fontos tulajdonság: $\overline{\overline{A}} = A$.)
	
**DEFINÍCIÓ**: Két vagy több halmaz [uniója](Unio.png) vagy egyesítése mindazon elemek halmaza, amelyek legalább az egyik halmaznak elemei. Jele: » $\cup$ 
	
**DEFINÍCIÓ**: Két vagy több halmaz [metszete](Metszet.png) vagy közös része pontosan azoknak az elemeknek a halmaza, amelyek mindegyik halmaznak elemei. Jele: « $\cap$

**DEFINÍCIÓ**: Két halmaz [diszjunkt](Diszjunkt.png), ha nincs közös elemük, vagyis a metszetük üres halmaz. $A \cap  B = \emptyset$. ^diszjunkt

**DEFINÍCIÓ**: Az A és B halmaz [különbsége](Kulonbseg.png) az A halmaz mindazon elemeinek halmaza, amelyek a B halmaznak nem elemei. Jele: $A \setminus B$. 
	
**DEFINÍCIÓ**: Az A és B halmaz [Descartes](Descartes)-féle szorzata az a halmaz, amelynek elemei az összes olyan rendezett (a; b) pár, amelynél  $a \in A \;és\; b \in B$. Jele: $A \times B$.

### Halmazműveletek tulajdonságai

| Tulajdonság                       | Unió                                                                                                                       | Metszet                                                                                                         |
| --------------------------------- | -------------------------------------------------------------------------------------------------------------------------- | --------------------------------------------------------------------------------------------------------------- |
| **Kommutatív (felcserélhető)**    | $A \cup B = B \cup A$                                                                                                      | $A \cap B = B \cap A$                                                                                           |
| **Asszociatív (csoportosítható)** | $(A \cup B) \cup C = A \cup (B \cup C)$                                                                                    | $(A \cap B) \cap C = A \cap (B \cap C)$                                                                         |
| **Disztributív (széttagolható)**  | $A \cup (B \cap C) = (A \cup B) \cap (A \cup C)$                                                                           | $A \cap (B \cup C) = (A \cap B) \cup (A \cap C)$                                                                |
| **De-Morgan azonosságok**         | $\overline{A \cup B} = \overline{A} \cap \overline{B}$                                                                     | $\overline{A \cap B} = \overline{A} \cup \overline{B}$                                                          |
| **További azonosságok**           | $A \cup \varnothing = A$<br>$A \cup A = A$<br>$A \cup \overline{A} = U$<br>$A \cup U = U$<br>$\overline{\overline{A}} = A$ | $A \cap \varnothing = \varnothing$<br>$A \cap {A} = A$<br>$A \cap \overline{A} = \varnothing$<br>$A \cap U = A$ |
