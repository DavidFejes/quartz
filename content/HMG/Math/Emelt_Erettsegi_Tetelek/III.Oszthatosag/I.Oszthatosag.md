**Kidolgozás:**
	Az oszthatóság fogalmánál alaphalmaznak az egész számok halmazát tekintjük. Két egész szám hányadosa nem mindig egész szám, az oszthatóságnál azt vizsgáljuk, hogy egész számok osztásakor mikor lesz a hányados is egész szám, vagyis a maradék $0$. 
	
**DEFINÍCIÓ**: Egy $a$ egész szám osztója egy $b$ egész számnak, ha található olyan *c* egész szám, amelyre $a \cdot c = b$. Jelölés: $a|b$. (Természetesen $c|b$ is igaz). Ebben az esetben az is igaz, hogy $b$ osztható $a$-val és $c$-vel. Ekkor azt is mondhatjuk, hogy $b$ többszöröse $a$-nak. A $0$ szerepe a számelméletben: 
	• a $0$ minden nemnulla egész számnak többszöröse (0-szorosa), azaz $0$ minden nemnulla egész számmal osztható ugyanis $0 = 0 \cdot a;\; a|0$, ha $a \neq 0$. Ez azt is jelenti, hogy a $0$ páros szám. A $0$-nak egyetlen többszöröse van a 0, viszont a $0$ bármely egész számnak a többszöröse. 
	• a $0$ nem osztója egyetlen nemnulla egész számnak sem, ugyanis ha $0$ osztója lenne egy b nem nulla egész számnak, akkor létezne egy olyan c egész szám, amikre $b = c \cdot 0 = 0$ lenne, ami ellentmond azzal a feltétellel, hogy $b \neq 0$. Oszthatósági tételek: Ha $a, b, c \in\mathbb{Z}$, akkor 

---
**TÉTEL**: $1|a$, azaz az $1$ minden egész számnak osztója. 
**BIZONYÍTÁS**: $a = a \cdot 1$. 

---
**TÉTEL**: $a|a$, azaz minden egész szám osztója önmagának. 
**BIZONYÍTÁS**: $a = 1 \cdot a$. 

---
**TÉTEL**: $a|b\; és\; b|c \implies a|c$. 
**BIZONYÍTÁS**: Az $a|b$ feltétel azt jelenti, hogy van olyan $d$ egész szám, amire $b = a \cdot d,\; a\; b|c$ fel tétel azt jelenti, hogy van olyan e egész szám, amire $c = b \cdot e$. Ekkor $c = b \cdot e = (a \cdot d) \cdot e = a \cdot (d \cdot e)$ a szorzás asszociativitása miatt, ahol a $d \cdot e$ szorzat egész szám. Ez azt jelenti, hogy van olyan egész szám, aminek a-szorosa a c szám, vagyis $a|c$.

---
**TÉTEL**: $a|b \implies a|b \cdot c$, azaz ha egy egész szám osztója egy másik egész számnak, akkor a többszöröseinek is osztója. 
**BIZONYÍTÁS**: Az $a|b$ feltétel azt jelenti, hogy van olyan $d$ egész szám, hogy $b = a \cdot d$. Ekkor $b \cdot c = (a \cdot d) \cdot c = a \cdot (b \cdot c)$ a szorzás asszociativitása miatt. A ($b \cdot c$) szorzat egész, tehát találtunk megfelelõ egész számot, így $a|b \cdot c$. 

---
**TÉTEL**: $a|b$ és $a|c$ $\implies a|b \pm c$, azaz ha egy egész szám osztója két egész számnak, akkor összegüknek és különbségüknek is osztója. 
**BIZONYÍTÁS**: Az $a|b$ feltétel azt jelenti, hogy van olyan $d$ egész szám, hogy $b = a \cdot d$. Az $a|c$ feltétel azt jelenti, hogy van olyan $e$ egész szám, hogy $c = a \cdot e$. Ekkor $b \pm c = (a \cdot d) \pm (a \cdot e) \implies a \cdot (d \pm e)$ a disztributivitás miatt. A $(d \pm e)$ egész szám, tehát találtunk megfelelõ egész számot, így $a|b\; és\; a|c \implies a|b \pm c$. 

---
**TÉTEL**: $a|b$ és $a|b + c \implies a|c$, azaz ha egy egész szám osztója egy összegnek és az összeg egyik tagjának, akkor osztója a másik tagnak is. 
**BIZONYÍTÁS**: Az $a|b$ feltétel azt jelenti, hogy hogy van olyan $d$ egész szám, hogy $b = a \cdot d$. Az $a|c$ feltétel azt jelenti, hogy van olyan $e$ egész szám, hogy $c = a \cdot e$. Ekkor $b \pm c \implies (a \cdot d) \pm (a \cdot e) = a \cdot (d \pm e)$ a disztributivitás miatt. A $(d \pm e)$ egész szám, tehát találtunk megfelelõ egész számot, így $a|b$ és $a|c$ $\implies a|b \pm c$. Az oszthatóságot eddig az egész számokra értelmeztük, a továbbiakban leszûkítjük a természetes számokra, azaz a nemnegatív egész számokra. Egy adott problémánál tudjuk majd automatikusan alkalmazni az itt megfogalmazottakat az egész számokra. 

---
**TÉTEL**: Ha $a, b \in\mathbb{Z}^+$, és aΩb valamint $b|a \implies a = b$, azaz ha két pozitív egész szám egymásnak 
osztója, akkor a két szám egyenlõ. 
**BIZONYÍTÁS**: Az $a|b$ feltétel azt jelenti, hogy van olyan $d$ egész szám, amire $b = a \cdot d$, a $b|a$ fel tétel azt jelenti, hogy hogy van olyan $e$ egész szám, amire $a = b \cdot e$. Ekkor $b = a \cdot d = (b \cdot e) \cdot d = b \cdot (d \cdot e)$ a szorzás asszociativitása miatt. Osztva $b$-vel az egyenlet mindkét oldalát: $1 = b \cdot e$, aminek a pozitív egész számok halmazán csak a $d = e = 1$ a megoldása. Ekkor viszont $a = b \cdot 1 = b$.

---
**Oszthatósági szabályok**:
Egy $n$ egész szám osztható 
• $2$-vel, ha $n$ páros, vagyis utolsó jegye $\in{0; 2; 4; 6; 8}.$ 
• $3$-mal, ha a számjegyek összege osztható $3$-mal. 
• $4$-gyel, ha a két utolsó jegybõl képzett szám osztható $4$-gyel. 
• $5$-tel, ha utolsó jegye $\in{0; 5}$. 
• $6$-tal, ha $2$-vel és $3$-mal osztható. 
• $8$-cal, ha a három utolsó jegybõl képzett szám osztható $8$-cal. 
• $9$-cel, ha számjegyek összege osztható $9$-cel. 
• $10$-zel, ha utolsó jegye $0$.