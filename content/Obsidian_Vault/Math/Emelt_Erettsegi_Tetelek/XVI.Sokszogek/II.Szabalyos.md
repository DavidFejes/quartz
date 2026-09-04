**DEFINÍCIÓ:** Egy ==sokszög szabályos==, ha minden oldala egyenlő hosszú és minden szöge egyenlő.

---
**TÉTEL:** Egy $n$ oldalú szabályos sokszög egy ==belső szöge== $\frac{(n-2) \cdot 180^{\circ}}{n}$.

**BIZONYÍTÁS:** A konvex sokszög belső szögeinek összege $(n-2) \cdot 180^{\circ}$, ami éppen $n$ darab egyenlő szög összege, mert a belső szögek egyenlők. Így egy belső szög nagysága ennek az $n$-ed része: $\frac{(n-2) \cdot 180^{\circ}}{n}$.

---

### Szimmetriák szabályos sokszögekben:  
**Tengelyes szimmetria**: egy szabályos $n$-szögnek $n$ darab szimmetriatengelye van. Különbséget kell tennünk a szimmetriatengelyek milyensége között: szimmetriatengely lehet oldalfelező merőleges, illetve szögfelező.

**Páros $n$ esetén ezek elkülönülnek:** a tengelyek fele, azaz $\frac{n}{2}$ darab tengely a szemköztes oldalak oldalfelező merőlegese; a tengelyek másik fele, azaz $\frac{n}{2}$ darab tengely a szemközti csúcsok szögfelező egyenese.
<p align="center">
  <img src="Pasted image 20260819141510.png" />
</p>

---
**Páratlan $n$ esetén** bármely szimmetriatengely az egyik oldal oldalfelezõ merõlegese és a szemköztes szög szögfelezõje is egyben.
<p align="center">
  <img src="Pasted image 20260819141549.png" />
</p>

---
A szimmetriatengelyek egy pontban metszik egymást, szabályos sokszögek esetében ez a pont a sokszög köré írható és a sokszögbe írható kör középpontja is. Mindezekbõl következik, hogy a ==szabályos sokszögek húrsokszögek és érintõsokszögek is== egyben. A körök középpontjából a szabályos $n$ szög $n$ darab egyenlõ szárú háromszögre bontható, amelynek alapja a sokszög oldala, szára a sokszög köré írható kör sugara, alaphoz tartozó magassága a sokszögbe írható kör sugara.
<p align="center">
  <img src="Pasted image 20260819141653.png" />
</p>

---
**Középpontos szimmetria:** a páros oldalszámú szabályos sokszögek középpontosan szimmetrikusak. A szimmetriaközéppont ==két szimmetriatengely metszéspontja==.
í
**Forgásszimmetria:** ==minden szabályos sokszög forgásszimmetrikus==. A forgatás középpontja a sokszög középpontja (a szimmetria tengelyek metszéspontja, páros oldalszám esetén a középpontos szimmetria középpontja is), a ==forgatás szöge== pedig lehet $k \cdot \frac{360^{\circ}}{n}$, ahol $k \in \mathbb{Z}$.

**TÉTEL:** Egy $n$ oldalú szabályos sokszög ==területe==: $T = n \cdot \frac{R^2 \cdot \sin\left(\frac{360^{\circ}}{n}\right)}{2}$, ahol $R$ a sokszög köré írt kör sugara.

**TÉTEL:** Egy $n$ oldalú szabályos sokszög ==kerülete==: $K = 2 \cdot n \cdot R \cdot \sin\left(\frac{180^{\circ}}{n}\right)$, ahol $R$ a sokszög köré írt kör sugara.

**TÉTEL:** Egy $n$ oldalú szabályos sokszög ==területe==: $T = \frac{r \cdot K}{2}$, ahol $r$ a sokszögbe írt kör sugara, $K$ a kerülete, ebből $T = \frac{r \cdot n \cdot a}{2}$, ahol $r$ a sokszögbe írt kör sugara, $a$ pedig az oldalhossza.
<p align="center">
  <img src="Pasted image 20260819141915.png" />
</p>
