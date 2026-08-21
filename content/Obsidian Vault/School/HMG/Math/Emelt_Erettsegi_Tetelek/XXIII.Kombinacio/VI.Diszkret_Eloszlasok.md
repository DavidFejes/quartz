A kísérletek kimenetelei általában számokkal jellemezhetõk. Ezekre a mennyiségekre jellemzõ, hogy értékük a véletlentõl függ, és mindegyikük egy-egy eseményhez van hozzárendelve. 

**DEFINÍCIÓ:** A ==valószínûségi változó== az eseménytéren értelmezett valós értékû függvény. Jele: $\xi$. 

**DEFINÍCIÓ:** Ha a valószínûségi változó lehetséges értékeinek száma véges vagy megszámlálhatóan végtelen, akkor ==diszkrét== valószínûségi változóról beszélünk. 

**DEFINÍCIÓ:** A visszatevés nélküli mintavétel eloszlását ==hipergeometrikus eloszlásnak== nevezzük. 

---
**TÉTEL:** Hipergeometrikus eloszlásnál legyen $N$ db elemünk, amelybõl $M$ db elem rendelkezik egy adott A tulajdonsággal, $N - M$ db pedig nem. Kiválasztunk véletlenszerûen ==visszatevés nélkül== $n$ db-ot. Annak a valószínûsége, hogy a kihúzott $n$ db elem közül $k$ db rendelkezik az $A$ tulajdonsággal:
$$P(\xi = k) = \frac{\left( \begin{array}{c} M \\ k \end{array} \right) \cdot \left( \begin{array}{c} N-M \\ n-k \end{array} \right)}{\left( \begin{array}{c} N \\ n \end{array} \right)}, \text{ ahol } k \leq n.$$

**BIZONYÍTÁS:** A kérdés az, hogy mennyi a valószínűsége annak, hogy a kihúzott $n$ db elem között $k$ db $A$ tulajdonságú elem van.

A kombinatorikában tanultak szerint a kedvező esetek száma $\binom{M}{k} \cdot \binom{N-M}{n-k}$, mert $M$ db-ból kell $k$ db-ot kiválasztani, amit $\binom{M}{k}$-féleképpen tehetünk meg, és a maradék $N-M$ db-ból $n-k$ db-ot kell kiválasztanunk, amit $\binom{N-M}{n-k}$-féleképpen tehetünk meg.

Az összes esetek száma: $\binom{N}{n}$, mert $N$ db-ból kell $n$ db-ot választani.

Ezt felhasználva kapjuk: $P(\xi = k) = \frac{\binom{M}{k} \cdot \binom{N-M}{n-k}}{\binom{N}{n}}$.

---
**TÉTEL:** A hipergeometrikus eloszlásnál az $A$ tulajdonságú elemek számának várható értéke:

$$M(\xi) = n \cdot p = n \cdot \frac{M}{N}$$
