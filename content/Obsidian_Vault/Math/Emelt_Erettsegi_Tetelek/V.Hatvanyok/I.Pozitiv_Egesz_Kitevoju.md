**Kidolgozás:**
	A hatványozást ugyanaz az igény hívta létre, mint a szorzást. A szorzás az ismételt összeadást je lenti, a hatványozást azonos számok szorzására vezették be, késõbb kiterjesztették az értelmezését.

**DEFINÍCIÓ**: Ha $a$ tetszõleges valós szám és $n\; 1$-nél nagyobb természetes szám, akkor $a^n$ ==hatvány== azt az $n$ tényezõs szorzatot jelenti, amelynek minden tényezõje $a$. Ha $n = 1$, akkor $a^1 = a$. Az $a$ számot a hatvány ==alap==jának, az $n$ számot a hatvány ==kitevõ==jének nevezzük, ez utóbbi megmutatja, hogy a hatványalapot hányszor kell szorzótényezõül venni. 
A hatványozás azonosságai pozitív egész kitevõ esetén:  ($a, b \in\mathbb{R},\; m, n \in\mathbb{N}^+$) 

---
**TÉTEL**: Azonos alapú hatványokat úgy is szorozhatunk, hogy a közös alapot a kitevõk összegére emeljük:$$
a^m\cdot a^n = a^{m+n}$$
**BIZONYÍTÁS**:$$
a^m \cdot a^n \underset{\text{hatv. def.}}{=} \underbrace{a\cdot a\cdot \ldots \cdot a}_{\text{m db}}\cdot \underbrace{a\cdot a\cdot \ldots \cdot a}_{\text{n db}} \underset{\text{szorzás asszoc.}}{=} \underbrace{a\cdot a\cdot \ldots \cdot a}_{\text{m+n db}} \underset{\text{hatv. def.}}{=} a^{m+n}$$
^2-azonossag

---
**TÉTEL**: Azonos alapú hatványokat úgy is oszthatunk, hogy a közös alapot a kitevõk különbségére emeljük: $$ \frac{a^m}{a^n} = a^{m-n}, \quad \text{ha } a \neq 0, m > n. $$
**BIZONYÍTÁS:**$$ \frac{a^m}{a^n} \underset{\text{hatv. def.}}{=} \frac{\overbrace{a \cdot a \cdot \dots \cdot a}^{m \text{ db}}}{\underbrace{a \cdot a \cdot \dots \cdot a}_{n \text{ db}}} \underset{\substack{\text{egysze-} \\ \text{rűsítés}}}{\,=\,} \frac{\overbrace{a \cdot a \cdot \dots \cdot a}^{m - n \text{ db}}}{1} \underset{\text{hatv. def.}}{=} a^{m-n}. $$

---
**TÉTEL**: Szorzatot tényezõként is hatványozhatunk: ($a \cdot b)n = a^n \cdot b^n$ 
	Tétel „visszafele” olvasva: Azonos kitevõjû hatványokat úgy is szorozhatunk, hogy az alapok szorzatát a közös kitevõre emeljük.

**BIZONYÍTÁS**:
$$ (a \cdot b)^n \underset{\text{hatv. def.}}{=} \underbrace{(a \cdot b) \cdot (a \cdot b) \cdot \dots \cdot (a \cdot b)}_{n \text{ db}} \underset{\substack{\text{szorzás} \\ \text{asszoc.}}}{\,=\,} a \cdot b \cdot a \cdot b \cdot \dots \cdot a \cdot b \underset{\substack{\text{szorzás} \\ \text{kommut.}}}{\,=\,} $$
$$ = \underbrace{a \cdot a \cdot \dots \cdot a}_{n \text{ db}} \cdot \underbrace{b \cdot b \cdot \dots \cdot b}_{n \text{ db}} \underset{\text{hatv. def.}}{=} a^n \cdot b^n. $$
---
**TÉTEL**: Törtet úgy is hatványozhatunk, hogy a számlálót és a nevezõt külön-külön hatványozzuk és a kapott hatványoknak a kívánt sorrendben a hányadosát vesszük.$$
\left(\frac{a}{b}\right)^n = \frac{a^n}{b^n}, \; ha\; b \neq 0$$
	Tétel „visszafele” olvasva: Azonos kitevõjû hatványokat úgy is oszthatunk, hogy az alapok hányadosát a közös kitevõre emeljük.
**BIZONYÍTÁS**:$$ \left(\frac{a}{b}\right)^n \underset{\text{hatv. def.}}{=} \underbrace{\left(\frac{a}{b}\right) \cdot \left(\frac{a}{b}\right) \cdot \dots \cdot \left(\frac{a}{b}\right)}_{n \text{ db}} \underset{\substack{\text{törtek} \\ \text{szorzása}}}{\,=\,} \frac{\overbrace{a \cdot a \cdot \dots \cdot a}^{n \text{ db}}}{\underbrace{b \cdot b \cdot \dots \cdot b}_{n \text{ db}}} \underset{\text{hatv. def.}}{=} \frac{a^n}{b^n}. $$

---
**TÉTEL**: Hatványt úgy is hatványozhatunk, hogy az alapot a kitevõk szorzatára emeljük:$$
(a^n)^m = a^{n\cdot m}$$
**BIZONYÍTÁS:**$$ (a^n)^m \underset{m. \text{ hatv. def.}}{=} \underbrace{(a^n) \cdot (a^n) \cdot \ldots \cdot (a^n)}_{m \text{ db}} \underset{n. \text{ hatv. def.}}{=} \underbrace{\left(\underbrace{a \cdot a \cdot \ldots \cdot a}_{n \text{ db}}\right) \cdot \left(\underbrace{a \cdot a \cdot \ldots \cdot a}_{n \text{ db}}\right) \cdot \ldots \cdot \left(\underbrace{a \cdot a \cdot \ldots \cdot a}_{n \text{ db}}\right)}_{m \text{ db}} $$$$\underset{\substack{\text{szorzás} \\ \text{asszoc.}}}{\,=\,}  \underbrace{a \cdot a \cdot \dots \cdot a \cdot a \cdot a \cdot \dots \cdot a}_{m \cdot n \text{ db}} \underset{\text{hatv. def.}}{=} a^{m \cdot n}. $$
