A valószínûségszámítás a véletlen tömegjelenségek bekövetkezésének esélyének vizsgálatával fog lalkozik. 

**DEFINÍCIÓ:** Véletlen jelenségnek nevezzük azokat a jelenségeket, amelyeket a leírható körülmények nem határoznak meg egyértelmûen. Pl. egy dobókocka feldobása. 

**DEFINÍCIÓ:** Kísérletnek nevezzük a véletlen jelenség megfigyelését. 

**DEFINÍCIÓ:** Elemi eseménynek nevezzük a kísérlet során bekövetkezõ lehetséges kimeneteleket. Pl. a kocka dobásánál azt, hogy hányas számot dobunk. 

**DEFINÍCIÓ:** Az eseménytér az elemi események halmaza. Pl. a kocka dobásánál $\{1; 2; 3; 4; 5; 6\}$. 

**DEFINÍCIÓ:** Az elemi események egy halmazát, azaz az eseménytér egy részhalmazát eseménynek nevezzük. Pl. esemény kockadobásnál páros szám dobása. Az eseményeket nagybetûvel jelöljük. Pl. $A = {2; 4; 6}$ 

**DEFINÍCIÓ:** Az eseménytérhez tartozó azon esemény, amely biztosan bekövetkezik, a biztos esemény, amely semmiképpen sem következhet be, a lehetetlen esemény. A biztos esemény jele: $H$, a lehetetlen esemény jele: $\emptyset$. Pl. a kockadobásnál biztos esemény: $7$-nél kisebb számot dobunk, lehetetlen esemény: $8$-nál nagyobbat dobunk.

**DEFINÍCIÓ:** Ha elvégzünk $n$-szer egy kísérletet, és ebbõl az $A$ esemény $k$-szor következik be, akkor az $A$ esemény relatív gyakorisága a $\frac{k}{n}$ hányados. 

**DEFINÍCIÓ:** Ha sokszor elvégzünk egy kísérletet, akkor megfigyelhetjük, hogy egy $A$ esemény relatív gyakorisága egy szám körül ingadozik. Ezt a számot nevezzük az $A$ esemény való színûségének. Jele: $P(A)$. 

**DEFINÍCIÓ:** A valószínûség kiszámításának klasszikus modelljét akkor alkalmazhatjuk, ha egy kísérletnek véges sok kimenetele van és ezek valószínûsége egyenlõ. Ekkor az $A$ esemény valószínûsége: $PA = \frac{kedvezõ\; elemi\; események\; száma}{összes\; elemi\; esemény\; száma}$

### A valószínűség-számítás axiómái:

* Tetszőleges $A$ esemény esetén $0 \le P(A) \le 1$.
* Biztos esemény valószínűsége 1, lehetetlen eseményé 0.
* Ha $A$ és $B$ egymást kizáró események, akkor $P(A + B) = P(A) + P(B)$.
* Ha $A$ és $B$ tetszőleges esemény, akkor $P(A + B) = P(A) + P(B) - P(A \cdot B)$.
* $P(A) + P(\overline{A}) = 1$.

**DEFINÍCIÓ:** Az $A$ esemény $B$-re vonatkozó feltételes valószínűsége: $P(A \mid B) = \frac{P(A \cdot B)}{P(B)}$.  
Ez annak a valószínűsége, hogy az $A$ esemény bekövetkezik, feltéve, hogy a $B$ esemény bekövetkezik.

**DEFINÍCIÓ:** Az $A$ és $B$ események egymástól függetlenek, ha $P(A \mid B) = P(A)$.  
Ekkor $P(A \cdot B) = P(A) \cdot P(B)$.