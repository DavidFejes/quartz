**DEFINÍCIÓ:** Ha elvégzünk $n$-szer egy kísérletet, és ebbõl az $A$ esemény $k$-szor következik be, akkor az $A$ esemény relatív gyakorisága a $\frac{k}{n}$ hányados. 

**DEFINÍCIÓ:** Ha sokszor elvégzünk egy kísérletet, akkor megfigyelhetjük, hogy egy $A$ esemény relatív gyakorisága egy szám körül ingadozik. Ezt a számot nevezzük az $A$ esemény valószínûségének. Jele: $P(A)$. 

**DEFINÍCIÓ:** A valószínûség kiszámításának klasszikus modelljét akkor alkalmazhatjuk, ha egy kísérletnek véges sok kimenetele van és ezek valószínûsége egyenlõ. Ekkor az $A$ esemény valószínűsége: $P(A) = \frac{kedvező \;elemi\; események\; száma}{összes\; elemi\; esemény\; száma}$

### A valószínûség-számítás axiómái: 
• Tetszõleges A esemény esetén $0\leq P(A)\leq 1$. 
• Biztos esemény valószínûsége $1$, lehetetlen eseményé $0$.
• Ha $A$ és $B$ egymást kizáró események, akkor $P(A + B) = P(A) + P(B)$. 
• Ha $A$ és $B$ tetszõleges esemény, akkor $P(A + B) = P(A) + P(B) - P(A \cdot B)$. 
• $P(A) + P(\overline{A}) = 1$. 

**DEFINÍCIÓ:** Az A esemény B-re vonatkozó feltételes valószínûsége: $P(A|B)=\frac{P(A \cdot B)}{P(B)}$. Ez annak a valószínûsége, hogy az $A$ esemény bekövetkezik, feltéve, hogy a $B$ esemény be következik. 

**DEFINÍCIÓ:** Az $A$ és $B$ események egymástól függetlenek, ha $P(A | B) = P(A)$. Ekkor $P(A \cdot B) = P(A) \cdot P(B)$. 

**DEFINÍCIÓ:** Ha egy esemény elõfordulását geometriai alakzat (vonal, síkidom, test) mértékével jellemezzük, és az esemény bekövetkezésének valószínûségét ezek hányadosával fejezzük ki, akkor geometriai valószínûségrõl beszélünk.