A kísérletek kimenetelei általában számokkal jellemezhetõk. Ezekre a mennyiségekre jellemzõ, hogy értékük a véletlentõl függ, és mindegyikük egy-egy eseményhez van hozzárendelve. 

**DEFINÍCIÓ:** A ==valószínûségi változó== az eseménytéren értelmezett valós értékû függvény. **Jele**: $\xi$. 

**DEFINÍCIÓ:** Ha a valószínûségi változó lehetséges értékeinek száma véges vagy megszámlálhatóan végtelen, akkor ==diszkrét valószínûségi változó==ról beszélünk. 

**DEFINÍCIÓ:** A ==binomiális eloszlás== olyan kísérletnél fordul elõ, amelynek csak két kimenetele lehetséges: az $A$ esemény $p$ valószínûséggel bekövetkezik, vagy $1 - p$ valószínûséggel nem következik be. 

**TÉTEL:** Binomiális eloszlásnál ha a kísérletet $n$-szer ismételjük, akkor annak valószínûsége, hogy az $A$ esemény $k$-szor következik be, éppen $$P(\xi =k)\binom{n}{k}\cdot p^k\cdot(1-p)^{n-k}\quad,ahol\;k\leq n.$$(Binomiális eloszlásra vezetnek a visszatevéses mintavétel esetei, ahol $n$ elem közül $p$ valószínûséggel választunk valamilyen tulajdonsággal rendelkezõt oly módon, hogy a kivett elemet az újabb húzás elõtt visszatesszük.) 

**BIZONYÍTÁS:** Tegyük fel, hogy a ==visszatevéses mintavételeknél== $N$ db elem közül választunk ki $n$ db-ot. Legyen $M$ db elem $A$ tulajdonságú, $N - M$ db elem $A$ tulajdonságú. A visszatevéses mintavétel azt jelenti, hogy minden egyes húzás után visszatesszük a kihúzott elemet, így a húzások egymástól függetlenek lesznek. A kérdés az, hogy mennyi a valószínûsége annak, hogy a kihúzott $n$ db elem között $k$ db A tulajdonságú elem van. A kombinatorikában tanultak szerint a kedvezõ esetek száma $\binom{n}{k}\cdot M^k \cdot (N-M)^{n-k}$ , mert $k$-szor kell $M$ db golyóból választanunk, $n - k$-szor kell $N - M$ db golyó közül, és ez $\binom{n}{k}$ féleképpen fordulhat elõ aszerint, hogy hányadik húzás az $A$ tulajdonságú. Az összes esetek száma $N^n$, mert $n$-szer húzunk $N$ elembõl. Így$$P = \frac{\binom{n}{k} \cdot M^k \cdot (N - M)^{n-k}}{N^n} = \binom{n}{k} \cdot \frac{M^k}{N^k} \cdot \frac{(N - M)^{n-k}}{N^{n-k}} = \binom{n}{k} \cdot \left(\frac{M}{N}\right)^k \cdot \left(\frac{N - M}{N}\right)^{n-k}$$
Tudjuk, hogy annak az esélye, hogy $A$ tulajdonságút húzunk: $P(A) = \frac{M}{N} = p$, hogy nem $A$ tulajdonságút húzunk: $P(\overline{A}) = 1 - p = 1 - \frac{M}{N} = \frac{N-M}{N}$.

Ezt felhasználva kapjuk: $P(\xi = k) = \binom{n}{k} \cdot p^k \cdot (1 - p)^{n-k}$.

---
**TÉTEL:** A binomiális eloszlásnál az $A$ tulajdonságú elemek számának várható értéke:

$$M(\xi) = n \cdot p = n \cdot \frac{M}{N}$$
