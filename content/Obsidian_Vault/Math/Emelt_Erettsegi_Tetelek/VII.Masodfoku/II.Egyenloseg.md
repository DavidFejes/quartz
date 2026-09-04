**DEFINÍCIÓ:** ==Másodfokú egyismeretlenes egyenlet== $ax^2 + bx + c = 0$ alakra hozható, ahol $a, b, c \in\mathbb{R}$, $a \neq 0$. 
Megoldása lehetséges a megoldóképlettel, szorzattá alakítással, teljes négyzetté alakítással, Viète-formulával. Pl. $x^2 + 3x = 0$ vagy $x^2 + 6x + 9 = 0$

---
**TÉTEL:** Az $ax^2 + bx + c = 0$ $(a \neq 0)$ egyenlet **megoldóképlete:** $x_{1,2} = \frac{-b \pm \sqrt{b^2 - 4ac}}{2a}$ , ahol 
$b^2 - 4ac \ge 0$.

**BIZONYÍTÁS:**

$$
\begin{aligned}
ax^2 + bx + c &= 0 && / \cdot 4a \\
4a^2x^2 + 4abx + 4ac &= 0 &&
\end{aligned}
$$

teljes négyzetté alakítással:

$$
\begin{aligned}
(2ax + b)^2 - b^2 + 4ac &= 0 && / + b^2 - 4ac \\
(2ax + b)^2 &= b^2 - 4ac &&
\end{aligned}
$$

Mivel a bal oldalon négyzetszám van, ami nem lehet negatív, így $b^2 - 4ac$ sem lehet az. (Ha $b^2 - 4ac < 0$, akkor nincs megoldás). Ha $b^2 - 4ac \ge 0$, akkor vonjunk mindkét oldalból gyököt, figyelve, hogy elkerüljük a gyökvesztést:

$$
\begin{aligned}
|2ax + b| &= \sqrt{b^2 - 4ac} \\
2ax + b &= \pm\sqrt{b^2 - 4ac} \\
2ax &= -b \pm\sqrt{b^2 - 4ac} \\
x_{1,2} &= \frac{-b \pm \sqrt{b^2 - 4ac}}{2a}
\end{aligned}
$$

---
**DEFINÍCIÓ:** Az $ax^2 + bx + c = 0$ $(a \neq 0)$ másodfokú egyenlet ==diszkrimináns==a $D = b^2 - 4ac$.

*   Ha $D > 0$, akkor az egyenletnek **két különböző** valós gyöke van: $x_{1,2} = \frac{-b \pm \sqrt{b^2 - 4ac}}{2a}$ .
*   Ha $D = 0$, akkor az egyenletnek **két egymással egyenlő** gyöke, vagyis 1 valódi gyöke van:
    $x = -\frac{b}{2a}$ , ezt kétszeres gyöknek is nevezzük, mert $x_1 = x_2$.
*   Ha $D < 0$, akkor az egyenletnek **nincs** valós gyöke.

---
**TÉTEL:** A másodfokú egyenlet ==gyöktényezős alakja==:
Ha egy $ax^2 + bx + c = 0$ $(a \neq 0)$ egyenlet megoldható (azaz $D \ge 0$) és két gyöke van $x_1$ és $x_2$, akkor az $ax^2 + bx + c = a(x - x_1)(x - x_2)$ minden valós $x$-re igaz.

**TÉTEL: Viète-formulák:** másodfokú egyenlet gyökei és együtthatói közti összefüggések:
Az $ax^2 + bx + c = 0$ $(a \neq 0)$ alakban felírt ($D \ge 0$) másodfokú egyenlet gyökeire:
$$x_1 + x_2 = -\frac{b}{a}\quad és \quad x_1 \cdot x_2 = \frac{c}{a}$$

**Grafikus megoldás:** az $x \mapsto ax^2 + bx + c$ $(a \neq 0)$ függvény zérushelyei adják a megoldást. (Sőt $a > 0$ esetre törekszem!)

$$
x \mapsto ax^2 + bx + c = a\left(x^2 + \frac{b}{a}x\right) + c = a\left[\left(x + \frac{b}{2a}\right)^2 - \frac{b^2}{4a^2}\right] + c = a\left(x + \frac{b}{2a}\right)^2 + \frac{4ac - b^2}{4a}.
$$

Olyan parabola a kép, amelynek tengelypontja $T\left(-\frac{b}{2a}, \frac{4ac - b^2}{4a}\right)$.