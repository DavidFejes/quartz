**TÉTEL:** $(a + b)^n = \dbinom{n}{0}a^n b^0 + \dbinom{n}{1}a^{n-1}b^1 + \dbinom{n}{2}a^{n-2}b^2 + \dots + \dbinom{n}{n-1}a^1 b^{n-1} + \dbinom{n}{n}a^0 b^n$.

A tételben szereplő $\dbinom{n}{k}$ együtthatókat ==binomiális együtthatóknak== nevezzük.

**BIZONYÍTÁS:** $(a + b)^n = (a + b)(a + b)(a + b)\dots(a + b)$.  
Bontsuk fel a jobb oldalon álló $n$ darab zárójelet: mindegyik összegből ki kell választani az egyik tagot, ezeket a tagokat össze kell szorozni, majd a kapott szorzatokat össze kell adni. Mindegyik kapott szorzat $n$ tényezőből áll, mindegyikben szerepel $a$ és $b$, mégpedig $a^{n-k} \cdot b^k$ alakban, mert a zárójelből vagy $a$-t, vagy $b$-t választunk, $a$-ból $n - k$ darabot, $b$-ből $k$ darabot.  
$\dbinom{n}{k}$-féleképpen lehet az $n$ darab tényezőből azt a $k$ darabot kiválasztani, amelyikből a $b$ szorzótényezőt vesszük. Tehát az $a^{n-k} \cdot b^k$ tagból $\dbinom{n}{k}$ darab van, tehát ez a tag együtthatója.

Így a szorzat a tételbeli alakba írható.
^binomalis-tetel
---
### A binomiális együtthatók tulajdonságai:

* $0!$ a definíció szerint $1$, ezért $\dbinom{n}{n} = 1$ és $\dbinom{n}{0} = 1$.
* Az $n$ elem közül ugyanannyiféleképpen lehet $k$ elemet kiválasztani, mint $n - k$ elemet otthagyni, így $\dbinom{n}{k} = \dbinom{n}{n-k}$.

### A binomiális tétel következménye:
Ha az összeg mindkét tagja $1$, akkor

$$2^n = (1 + 1)^n = \dbinom{n}{0} + \dbinom{n}{1} + \dbinom{n}{2} + \dots + \dbinom{n}{n-1} + \dbinom{n}{n}$$
### Pascal-háromszög: 
A háromszögben a sorok számozása nullával kezdõdik, a páratlan és a páros sorokban a számok el vannak csúsztatva egymáshoz képest. A háromszöget a következõ egyszerû módon lehet felírni: A nulladik sorban csak egy darab $1$-es van. A következõ sorok felírásánál a szabály a következõ: az új számot úgy kapjuk meg, ha összeadjuk a felette balra és felette jobbra található két számot. Ha az összeg valamelyik tagja hiányzik (sor széle), akkor nullának kell tekinteni. Például az $1$-es sor elsõ száma $0 + 1 = 1$, míg a $2$-es sor középsõ száma $1 + 1 = 2$. Ez a meghatározás Pascal képletén alapul, amely szerint az $n$-edik sor $k$-adik eleme a következõ képlettel számolható: $\binom{n}{k}=\binom{n-1}{k-1}+\binom{n-1}{k}$ bármely nem negatív egész $n$ és bármely $0$ és $n$ közötti $k$ egész esetében.

A Pascal-háromszög szimmetriája miatt is látható, hogy $\binom{n}{k}=\binom{n}{n-k}$ .
A meghatározásból látszik, hogy az $n$-edik sorban a kéttagú összeg $n$-edik hatványának együtthatói, azaz a binomiális együtthatók állnak.
<p align="center">
  <img src="Pasted image 20260821130629.png" />
</p>
