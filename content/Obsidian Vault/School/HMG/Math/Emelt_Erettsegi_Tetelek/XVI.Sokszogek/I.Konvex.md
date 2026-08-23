**DEFINÍCIÓ:** Egy sokszög ==konvex==, ha bármely két belsõ pontját összekötõ szakasz minden pontja a sokszög belsõ pontja. 

---
**TÉTEL:** Egy $n$ oldalú konvex sokszög ==átlóinak száma==: $\frac{n\cdot (n-3)}{2}$

**BIZONYÍTÁS:** Az $n$ oldalú, vagyis $n$ csúcsú konvex sokszög minden csúcsából $n - 3$ darab átló húzható (nem húzható átló a két szomszédos csúcsba és saját magába). Így $n$ csúcsból $n\cdot (n-3)$ átló húzható. Ekkor viszont minden átlót kétszer számoltunk, mert figyelembe vettük a kezdõpontjánál és a végpontjánál is. Ezért az összes átló száma $\frac{n\cdot (n-3)}{2}$
<p align="center">
  <img src="School/HMG/Math/Emelt_Erettsegi_Tetelek/XVI.Sokszogek/Abrak/Pasted image 20260819140633.png" />
</p>

---
**TÉTEL:** Egy n oldalú konvex sokszög ==belsõ szögeinek összege== $(n-2)\cdot 180^\circ$ .

**BIZONYÍTÁS:** A konvex sokszög egy csúcsából $n - 3$ átló húzható (nem húzható átló a két szom szédos csúcsba és saját magába). Ez az $n - 3$ darab átló $n - 2$ darab háromszögre bontja a sokszöget. Egy háromszög belsõ szögeinek összege $180º$, így az $n - 2$ darab háromszög belsõ szögeinek összege $(n - 2) \cdot 180º$, ami éppen a sokszög belsõ szögeinek összegét adja.
<p align="center">
  <img src="School/HMG/Math/Emelt_Erettsegi_Tetelek/XVI.Sokszogek/Abrak/Pasted image 20260819140932.png" />
</p>

---
**DEFINÍCIÓ:** A konvex sokszög belsõ szögeinek mellékszögeit a sokszög ==külsõ szög==einek nevezzük.

---
**TÉTEL:** Egy $n$ oldalú konvex sokszög ==külsõ szögeinek összege== $360º$. 

**BIZONYÍTÁS:** A konvex sokszög egy belsõ szögének és a hozzá tartozó külsõ szögnek az összege $180º$, mert mellékszögpárt alkotnak. Így az $n$ csúcsnál levõ belsõ szög-külsõ szög párok öszszege $n \cdot 180º$. Ebbõl levonva a belsõ szögek összegét, megkapjuk a külsõ szögek összegét: $n \cdot 180º - (n - 2) \cdot 180º = (n - (n - 2)) \cdot 180º = 2 \cdot 180º = 360º$.