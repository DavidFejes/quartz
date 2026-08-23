A kombinatorika, a valószínûség-számítás és a matematikai statisztika a véletlen tömegjelenségek törvényszerûségével foglalkozik. A kombinatorika tárgyát képezik a sorba rendezési és a részhalmaz kiválasztási problémák, a kombinatorika rendszerint dolgok megszámlálásával foglalkozik. 

**DEFINÍCIÓ:** Legyen $n$ egymástól különbözõ elemünk. Ha ezekbõl $k$ ($k \leq n$) db-ot kiválasztunk minden lehetséges módon úgy, hogy a kiválasztott elemek sorrendjére nem vagyunk tekintettel, azaz $n$ elem $k$-ad osztályú ==ismétlés nélküli kombináció==ját kapjuk. 

---
**TÉTEL:** Az $n$ elem $k$-ad osztályú az ismétlés nélküli kombinációinak száma:
$$\frac{n \cdot (n - 1) \cdot (n - 2) \cdot \dots \cdot (n - k + 1)}{k \cdot (k - 1) \cdot \dots \cdot 2 \cdot 1} = \frac{n!}{k!(n - k)!} = \binom{n}{k}$$

**BIZONYÍTÁS:** A kiválasztást úgy képzelhetjük el, mintha először sorba állítanánk a $k$ db kiválasztott elemet. Az első helyre $n$ db-ból, a második helyre $(n - 1)$ db-ból, a $k$-adik helyre már csak a megmaradt $(n - k + 1)$ db-ból választhatunk, ezzel a lehetőségek száma $n \cdot (n - 1) \cdot (n - 2) \cdot \dots \cdot (n - k + 1)$. Majd a sorrendek számát a $k$ elem összes sorrendjével, $k!$-ral osztjuk, hiszen a sorrend nem számít.

$$\frac{n \cdot (n - 1) \cdot (n - 2) \cdot \dots \cdot (n - k + 1)}{k!} =$$

$$= \frac{n \cdot (n - 1) \cdot (n - 2) \cdot \dots \cdot (n - k + 1) \cdot (n - k) \cdot (n - k - 1) \cdot \dots \cdot 2 \cdot 1}{k! \cdot (n - k) \cdot (n - k - 1) \cdot \dots \cdot 2 \cdot 1} = \frac{n!}{k!(n - k)!}$$

Erre pedig bevezetjük az $\binom{n}{k}$ szimbólumot.

---

**DEFINÍCIÓ:** Ha $n$ különböző elemből kell $k$ elemet kiválasztani úgy, hogy a kiválasztás sorrendje nem számít és a már kiválasztott elemeket újra kiválaszthatjuk, akkor az $n$ elem $k$-ad osztályú ==ismétléses kombináció==ját kapjuk.

**TÉTEL:** Az  $n$ elem $k$-ad osztályú ismétléses kombinációjának száma: $\binom{n+k-1}{k}$.