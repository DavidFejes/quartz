A [2. azonosság](I.Pozitiv_Egesz_Kitevoju#^2-azonossag) segítségével a hatványozás fogalma kibõvíthetõ az egész számokra a következõ módon: 
	**DEFINÍCIÓ**: Tetszõleges $a \neq 0$ valós számra $a^0 = 1$. Minden nullától különbözõ valós számnak a nulladik hatványa $1$.
	$0^0$-t nem értelmezzük (nem lehet úgy értelmezni, hogy összhangban legyen a hatványozás értelmezéseivel: 
		• $0^0 = 0$ kellene, hogy legyen, mert 0 minden pozitív egész kitevõ hatványa $0$. 
		• $0^0 = 1$ kellene, hogy legyen, mert minden egyéb szám nulladik hatványa $1$.)
	 Bizonyítható, hogy ezzel az értelmezéssel a hatványozás azonosságai érvényben maradnak. Pl.$$ \left. \begin{array}{l} a^0 \cdot a^n = a^{0+n} = a^n \\ a^0 \cdot a^n = 1 \cdot a^n = a^n \end{array} \right\} $$

**DEFINÍCIÓ**: Tetszõleges $a \neq 0$valós szám és $n$ pozitív egész szám esetén $a^{-n}=\frac{1}{a^n}$ . Minden $0$-tól különbözõ valós szám negatív egész kitevõjû hatványa a szám megfelelõ pozitív kitevõjû hatványának a reciproka (vagy a szám reciprokának a megfelelõ pozitív kitevõjû hatványa). 

Bizonyítható, hogy ezzel az értelmezéssel a hatványozás azonosságai érvényben maradnak. Pl.$$ \left. \begin{array}{l} a^{-n} \cdot a^n = a^{-n+n} = a^0 = 1 \\ a^{-n} \cdot a^n = \frac{1}{a^n} \cdot a^n = \frac{a^n}{a^n} = 1 \end{array} \right\} $$
Ezzel a két definícióval a 2. azonosság igaz minden $n, m \in\mathbb{Z}$-re: Ha $n = m$, akkor $\frac{a^m}{a^n}=\frac{a^m}{a^m}=1$ . Ha $m < n$, akkor $m$ darab $a$-val egyszerûsítünk, a számlálóban $1$, a nevezõben pedig $n - m$ darab a szorzótényezõ marad, ami a hatvány definíciója miatt $\frac{1}{a^{n-m}}$ . Alkalmazva a negatív egész kitevõjû hatvány definícióját  $\frac{1}{a^{n-m}} = \frac{1}{a^-{m-n}}= a^{m-n}$. A hatványozás fogalmát ezután racionális kitevõre terjesztjük ki:

**DEFINÍCIÓ**: Az a pozitív valós szám $\frac{p}{q}$-adik hatványa az a pozitív valós szám, amelynek $q$-adik hatványa $a^p$, azaz $\left(a^{\frac{p}{q}}\right)^q= a^p$ .
A definícióból következik: $a^{\frac{p}{q}} = \sqrt[q]{a^p}$ .
Az alap csak pozitív szám lehet, mert például

$(-2)^{\frac{2}{4}} = \left[(-2)^2\right]^{\frac{1}{4}} = 4^{\frac{1}{4}} = 2^{\frac{2}{4}} = \sqrt{2}$ értelmes,

$(-2)^{\frac{2}{4}} = (-2)^{\frac{1}{2}} = \sqrt{-2}$ nem értelmezhető, pedig a két hatvány értékének (azonos alap, azonos kitevő) meg kell egyeznie.

Bizonyítható, hogy ezzel az értelmezéssel a hatványozás azonosságai érvényben maradnak.
Pl.

$$
\left.
\begin{array}{l}
\left( a^{\frac{k}{n}} \right)^n = a^{\frac{k}{n} \cdot n} = a^k \\
\left( a^{\frac{k}{n}} \right)^n = \left( \sqrt[n]{a^k} \right)^n = a^k
\end{array}
\right\}
$$

A hatványozást kiterjeszthetjük tetszőleges valós kitevőre. Ehhez az irracionális kitevőt kell értelmeznünk.

---
Az értelmezés azon alapul, hogy bármely irracionális szám tetszõlegesen közelíthetõ két oldalról racionális számokkal. Így ha pl.: $2^\sqrt{2}$ hatványt szeretnénk meghatározni, akkor ehhez a $\sqrt{2}$ értékét közelítjük nála kisebb, illetve nála nagyobb racionális számokkal, majd a közelítõ értékekre, mint kitevõre emeljük a $2$-t. Bizonyítható, hogy $2^\sqrt{2}$ értéke létezik, és ily módon tetszõlegesen közelít hetõ (rendõrelv). 

**DEFINÍCIÓ**: Az $a$ pozitív valós szám $\alpha$ irracionális kitevõjû hatványa, azaz $a^\alpha$ jelentse az $a^r$ sorozat határértékét, ahol $r$ egy racionális számsorozat tagjait jelöli és $r \rightarrow a$. Képlettel: $\underset{r\rightarrow\alpha}{\lim} a^r = a^\alpha$.
