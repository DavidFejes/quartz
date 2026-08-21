**DEFINÍCIÓ:** Legyen $n$ db egymástól különbözõ elemünk. Ha ezekbõl $k$ ($k \leq n$) db-ot kiválasztunk minden lehetséges módon úgy, hogy a kiválasztott elemek sorrendje is számít, akkor az $n$ elem $k$-ad osztályú ismétlés nélküli variációját kapjuk. 

---
**TÉTEL:** Az $n$ elem $k$-ad osztályú ==ismétlés nélküli variációk száma==: $\frac{n!}{(n-k)!}$! 

**BIZONYÍTÁS:** Vegyünk egy $k$ rekeszes dobozt. Ebben helyezzünk el az $n$ elem közül $k$ db elemet minden lehetséges módon. Az elsõ rekeszbe az $n$ elem bármelyike tehetõ. A második rekeszbe már csak $(n - 1)$ elem közül választhatunk. Ez $(n - 1)$-féle kitöltést ad a 2. rekesz számára. Az elsõ két rekeszbe $n(n - 1)$-féleképpen tehetõk az elemek. Minden rekeszbe $1$-gyel kevesebb elem közül választhatunk, mint az előzőbe. A $k$-adik rekeszbe $n - (k - 1) = n - k + 1$ elem közül választhatunk.  
A doboz teljes kitöltésére összesen $n \cdot (n - 1) \cdot \ldots \cdot (n - k + 1)$ lehetőség adódik. Ha az eredményt $(n - k)!$-ral bővítjük, akkor

$$n \cdot (n - 1) \cdot \ldots \cdot (n - k + 1) = \frac{n \cdot (n - 1) \cdot \ldots \cdot (n - k + 1) \cdot (n - k) \cdot (n - k - 1) \cdot \ldots \cdot 2 \cdot 1}{(n - k)!} = \frac{n!}{(n - k)!}$$

---
**DEFINÍCIÓ:** Legyen $n$ db egymástól különböző elemünk. Ha ezekből kiválasztunk $k$ db-ot minden lehetséges módon úgy, hogy a kiválasztott elemek sorrendje is számít és ugyanazt az elemet többször is választhatjuk, akkor az $n$ elem $k$-ad osztályú ==ismétléses variációját== kapjuk.

**TÉTEL:** Az $n$ elem $k$-ad osztályú ismétléses variációk száma: $n^k$.