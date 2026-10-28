# Matematika Emelt Szintű Szóbeli Érettségi Témakörök (2023)

> [!info] Tudnivalók a vizsgázók számára
> A szóbeli vizsgán a tétel címében megjelölt téma kifejtését és a kitűzött feladat megoldását várják el a vizsgázóktól. A tételt logikusan, arányosan felépített, szabad előadásban, önállóan kell kifejteni.
> 
> **A feleletben feltétlenül szerepelniük kell az alábbi részleteknek:**
> - egy, a témához tartozó definíció pontos kimondása;
> - egy, a témához tartozó tétel pontos kimondása és bizonyítása;
> - a kitűzött feladat megoldása;
> - a téma matematikán belüli vagy azon kívüli alkalmazása, illetve matematikatörténeti vonatkozása.

---

## Tartalomjegyzék

1. [[#1. Halmazok, halmazműveletek. Nevezetes ponthalmazok a síkban és a térben]]
2. [[#2. Racionális és irracionális számok. Műveletek a racionális és irracionális számok halmazán. Közönséges és tizedes törtek. Halmazok számossága]]
3. [[#3. Oszthatóság, oszthatósági szabályok és tételek. Prímszámok. Számrendszerek]]
4. [[#4. A matematikai logika elemei. Logikai műveletek. Állítás és megfordítása, szükséges és elégséges feltételek]]
5. [[#5. Hatványozás, hatványfogalom kiterjesztése, a hatványozás azonosságai. Az n-edik gyök fogalma. Hatványfüggvények]]
6. [[#6. A logaritmus fogalma és azonosságai. Az exponenciális és a logaritmusfüggvény. Az inverzfüggvény]]
7. [[#7. Másodfokú egyenletek és egyenlőtlenségek. Másodfokúra visszavezethető egyenletek. Egyenletek ekvivalenciája]]
8. [[#8. A leíró statisztika jellemzői, diagramok. Nevezetes középértékek]]
9. [[#9. Függvénytani alapismeretek, függvények tulajdonságai, határérték, folytonosság. Számsorozatok. A számtani sorozat]]
10. [[#10. Mértani sorozat, az első n tag összege, végtelen mértani sor. Kamatszámítás, gyűjtőjáradék. Exponenciális folyamatok]]
11. [[#11. A differenciálhányados fogalma, deriválási szabályok. A differenciálszámítás alkalmazásai]]
12. [[#12. Derékszögű háromszögekre vonatkozó tételek. A hegyesszögek szögfüggvényei]]
13. [[#13. Háromszögek nevezetes vonalai, pontjai és körei]]
14. [[#14. Összefüggések az általános háromszögek oldalai között, szögei között, oldalai és szögei között]]
15. [[#15. Egybevágósági transzformációk, alakzatok egybevágósága. Szimmetria. Hasonlósági transzformációk]]
16. [[#16. Konvex sokszögek tulajdonságai. Szabályos sokszögek. Gráfok]]
17. [[#17. A kör és részei. Kerületi szög, középponti szög, látószög. Húrnégyszögek, érintőnégyszögek]]
18. [[#18. Vektorok, vektorműveletek. Vektorfelbontási tétel. Vektorok koordinátái. Skaláris szorzat]]
19. [[#19. Szakaszok és egyenesek a koordinátasíkon. Párhuzamos és merőleges egyenesek. Elsőfokú egyenlőtlenségek grafikus megoldása]]
20. [[#20. A kör és a parabola elemi úton és a koordinátasíkon. Másodfokú egyenlőtlenségek grafikus megoldása]]
21. [[#21. Térelemek távolsága és szöge. Térbeli alakzatok. Felszín- és térfogatszámítás]]
22. [[#22. Területszámítás elemi úton és az integrálszámítás felhasználásával]]
23. [[#23. Kombinációk. Binomiális tétel, a Pascal-háromszög. A valószínűség kiszámításának kombinatorikus modellje]]
24. [[#24. Permutációk, variációk. A binomiális eloszlás. A valószínűség kiszámításának geometriai modellje]]
25. [[#25. Bizonyítási módszerek és bemutatásuk tételek bizonyításában]]

---

# 1. Halmazok, halmazműveletek. Nevezetes ponthalmazok a síkban és a térben

## Vázlat
I. Halmazok, részhalmazok (n elemű halmaz részhalmazainak száma)
II. Halmazműveletek (komplementer, unió, metszet, különbség, Descartes-szorzat)
III. Nevezetes ponthalmazok: kör (gömb), párhuzamos egyenespár, szakaszfelező merőleges, szögfelező, parabola
IV. Egyéb ponthalmazok: ellipszis, hiperbola, látókörív
V. Alkalmazások, matematikatörténeti vonatkozások

## Kidolgozás

### I. Halmazok, részhalmazok
A **halmaz** és a halmaz **eleme** alapfogalom, ezeket nem definiáljuk. Jelölések: $a \in A, x \notin A$. Halmaz megadási módjai: elemek felsorolásával, utasítással, szimbólumokkal ($A = \{x \mid x^2 - x - 6 = 0\}$), Venn-diagrammal.

> [!info] DEFINÍCIÓ
> - **Két halmaz egyenlő**, ha ugyanazokat az elemeket tartalmazzák.
> - Az elem nélküli halmazt **üres halmaznak** nevezzük. Jele: $\emptyset$.
> - Az $A$ halmaz **részhalmaza** a $B$ halmaznak, ha $A$ minden eleme a $B$-nek is eleme. Jele: $A \subseteq B$.
> - Az $A$ halmaz **valódi részhalmaza** a $B$-nek, ha $A \subseteq B$, de $A \neq B$. Jele: $A \subset B$.

> [!tip] TÉTEL
> Az $n$ elemű halmaz összes részhalmazainak száma: $2^n$ ($n \in \mathbb{N}$).

> [!quote] BIZONYÍTÁS (Kombinatorikus)
> Az $n$ elemű halmaznak $\binom{n}{0}$ db 0 elemű, $\binom{n}{1}$ db 1 elemű, ..., $\binom{n}{n}$ db $n$ elemű részhalmaza van. 
> Az összes részhalmazok száma: $\binom{n}{0} + \binom{n}{1} + \dots + \binom{n}{n}$. 
> A binomiális tétel alapján: $(1+1)^n = \binom{n}{0}1^n + \binom{n}{1}1^{n-1}\cdot 1 + \dots = \sum_{k=0}^n \binom{n}{k} = 2^n$.

### II. Halmazműveletek
> [!info] DEFINÍCIÓK
> - **Alaphalmaz (Univerzum)**: az a halmaz ($U$), amelynek a vizsgált halmazok részhalmazai.
> - **Komplementer**: az $A$ halmaz komplementere ($A$ vagy $\overline{A}$) az alaphalmaz azon elemei, melyek nincsenek $A$-ban.
> - **Unió (Egyesítés)**: $A \cup B$, legalább az egyiknek eleme.
> - **Metszet (Közös rész)**: $A \cap B$, mindkettőnek eleme. Ha $A \cap B = \emptyset$, a két halmaz **diszjunkt**.
> - **Különbség**: $A \setminus B$, azon elemek, melyek $A$-nak elemei, de $B$-nek nem.
> - **Descartes-szorzat**: $A \times B = \{(a, b) \mid a \in A, b \in B\}$.

**Műveletek tulajdonságai**:
- *Kommutatív*: $A \cup B = B \cup A$, $A \cap B = B \cap A$
- *Asszociatív*: $(A \cup B) \cup C = A \cup (B \cup C)$
- *Disztributív*: $A \cup (B \cap C) = (A \cup B) \cap (A \cup C)$
- *De Morgan-azonosságok*: $\overline{A \cup B} = \overline{A} \cap \overline{B}$ és $\overline{A \cap B} = \overline{A} \cup \overline{B}$

### III. Nevezetes ponthalmazok
> [!info] DEFINÍCIÓ
> - **Kör (Gömb)**: Adott $O$ ponttól adott $r$ távolságra lévő pontok halmaza a síkban (térben).
> - **Szakaszfelező merőleges**: Két ponttól egyenlő távolságra lévő pontok halmaza a síkban.
> - **Szögfelező**: Két metsző egyenestől egyenlő távolságra lévő pontok halmaza (két egymásra merőleges egyenes).
> - **Parabola**: Egy egyenestől (direktrix) és egy rajta kívül lévő ponttól (fókusz) egyenlő távolságra lévő pontok halmaza a síkon.

> [!tip] TÉTEL
> A háromszög három oldalfelező merőlegese egy pontban metszi egymást, ez a **háromszög köré írt kör középpontja**.

### V. Alkalmazások & Matematikatörténet
- **Alkalmazások**: Rendszertan a biológiában, vércsoportok, koordináta-geometria (görbék egyenletei), parabolaantennák.
- **Matematikatörténet**: Euler és Venn diagramjai. A halmazelmélet megteremtője **Georg Cantor** (végtelen halmazok számossága, átlós eljárás).

---

# 2. Racionális és irracionális számok. Műveletek a racionális és irracionális számok halmazán. Közönséges és tizedes törtek. Halmazok számossága

## Kidolgozás

### I. Számhalmazok
- **$\mathbb{N}$ (Természetes számok)**: $\{0, 1, 2, \dots\}$. Zárt az összeadásra és szorzásra.
- **$\mathbb{Z}$ (Egész számok)**: $\{\dots, -2, -1, 0, 1, 2, \dots\}$. Zárt a kivonásra is.
- **$\mathbb{Q}$ (Racionális számok)**: Felírhatók $\frac{a}{b}$ alakban ($a, b \in \mathbb{Z}, b \neq 0$). Zárt a 4 alapműveletre (osztás 0-val kizárva).
- **$\mathbb{Q}^*$ (Irracionális számok)**: Nem írhatók fel két egész szám hányadosaként. (Pl. $\sqrt{2}, \pi, e$).
- **$\mathbb{R}$ (Valós számok)**: $\mathbb{Q} \cup \mathbb{Q}^*$. 

> [!tip] TÉTEL
> $\sqrt{2}$ irracionális szám.

> [!quote] BIZONYÍTÁS (Indirekt)
> Tegyük fel, hogy $\sqrt{2}$ racionális, azaz felírható $\frac{a}{b}$ alakban, ahol $a, b \in \mathbb{Z}$, $b \neq 0$, és $(a,b)=1$ (relatív prímek).
> $$ \sqrt{2} = \frac{a}{b} \implies 2 = \frac{a^2}{b^2} \implies 2b^2 = a^2 $$
> A bal oldalon a 2 prímtényező kitevője páratlan, míg a jobb oldalon ($a^2$-ben) páros. A számelmélet alaptétele szerint ez lehetetlen $\implies$ ellentmondás. Tehát $\sqrt{2}$ irracionális.

### V. Közönséges és tizedes törtek
A racionális számok tizedes tört alakja **véges** (ha a nevező prímfelbontása csak 2-t és 5-öt tartalmaz) vagy **végtelen szakaszos**. Az irracionális számok tizedestört alakja **végtelen nem szakaszos**.

### VI. Halmazok számossága
- **Véges halmaz**: elemeinek száma természetes szám.
- **Megszámlálhatóan végtelen**: sorba rendezhetők, bijekció létesíthető $\mathbb{N}$-nel (pl. $\mathbb{Z}, \mathbb{Q}$).
- **Kontinuum számosságú**: pl. $\mathbb{R}, \mathbb{Q}^*$, számegyenes pontjai.

> [!note] Matematikatörténeti vonatkozások
> - A mai arab/hindu számírást a XI. sz.-ban **al-Hvárizmi** írta le, Európába **Fibonacci** hozta be (XII. sz.).
> - A negatív számokat **Descartes** (1637) használta általánosan (hamis számok).
> - **Georg Cantor** bizonyította a végtelen halmazok különböző számosságát.

---

# 3. Oszthatóság, oszthatósági szabályok és tételek. Prímszámok. Számrendszerek

## Kidolgozás

### I. Oszthatóság
> [!info] DEFINÍCIÓ
> Egy $a \in \mathbb{Z}$ osztója $b \in \mathbb{Z}$-nek, ha létezik $c \in \mathbb{Z}$, melyre $a \cdot c = b$. Jele: $a \mid b$.
> - A $0$ minden nemnulla számnak többszöröse, de egyetlen számnak sem osztója.

**Tételek**:
- $a \mid b$ és $b \mid c \implies a \mid c$ (tranzitivitás)
- $a \mid b$ és $a \mid c \implies a \mid (b \pm c)$

**Oszthatósági szabályok (10-es számrendszerben)**:
- **2-vel**: utolsó számjegy páros.
- **3-mal / 9-cel**: számjegyek összege osztható 3-mal / 9-cel.
- **4-gyel**: utolsó két jegy osztható 4-gyel.

### II. Prímszámok, Számelmélet alaptétele
> [!info] DEFINÍCIÓ
> **Prímszám**: Pontosan két pozitív osztója van (1 és önmaga). (Az 1 nem prím).
> **Összetett szám**: 2-nél több pozitív osztója van.

> [!tip] TÉTEL
> Végtelen sok prímszám van.

> [!quote] BIZONYÍTÁS (Euklidész - Indirekt)
> Tegyük fel, hogy véges sok prím van: $p_1, p_2, \dots, p_n$. Képezzük az $A = p_1 p_2 \dots p_n + 1$ számot. $A$-t egyik $p_i$ sem osztja (maradék 1). Tehát $A$ vagy maga is új prím, vagy van egy új prímosztója $\implies$ ellentmondás, végtelen sok prím van.

> [!tip] A számelmélet alaptétele
> Minden összetett szám sorrendtől eltekintve egyértelműen felírható prímszámok szorzataként: $n = p_1^{\alpha_1} p_2^{\alpha_2} \dots p_k^{\alpha_k}$.
> **Osztók száma**: $(\alpha_1 + 1)(\alpha_2 + 1) \dots (\alpha_k + 1)$.

### IV. Számrendszerek
A helyi értékes ábrázolásban az $a$ alapú számrendszer helyi értékei: $1, a, a^2, a^3 \dots$
Használt számjegyek: $0, 1, \dots, a-1$. Informatika: kettes (bináris) és tizenhatos (hexadecimális) számrendszerek.

> [!note] Matematikatörténeti vonatkozások
> - **Eratoszthenész szitája** (Kr. e. 3. sz.) prímszámok keresésére.
> - A **60-as számrendszert** a sumérok, babilóniaiak használták (idő, szögmérés).
> - **Neumann János** nevéhez fűződik a kettes számrendszer kizárólagos alkalmazása a modern számítógépekben.

---

# 4. A matematikai logika elemei. Logikai műveletek. Állítás és megfordítása, szükséges és elégséges feltételek

## Kidolgozás

### II. Logikai műveletek
> [!info] DEFINÍCIÓ
> **Állítás (kijelentés)**: Olyan kijelentő mondat, amelyről egyértelműen eldönthető, hogy igaz (i/1) vagy hamis (h/0).

- **Negáció (Tagadás)**: $\neg A$ (vagy $\overline{A}$). Akkor igaz, ha $A$ hamis.
- **Diszjunkció (Vagy)**: $A \lor B$. Hamis, ha mindkettő hamis, különben igaz.
- **Konjunkció (És)**: $A \land B$. Igaz, ha mindkettő igaz, különben hamis.
- **Implikáció (Ha... akkor)**: $A \implies B$. Csak akkor hamis, ha $A$ igaz és $B$ hamis.
- **Ekvivalencia (Akkor és csak akkor)**: $A \iff B$. Igaz, ha $A$ és $B$ logikai értéke megegyezik.

> [!tip] De Morgan azonosságok
> $\overline{A \lor B} = \overline{A} \land \overline{B}$ és $\overline{A \land B} = \overline{A} \lor \overline{B}$.

> [!tip] TÉTEL
> $A \implies B \equiv \overline{A} \lor B$. (Igazságtáblával könnyen bizonyítható).

### III. Szükséges és elégséges feltétel
Ha $A \implies B$ igaz, akkor $A$ az **elégséges feltétele** $B$-nek (elég tudni $A$-t, hogy $B$ teljesüljön), és $B$ a **szükséges feltétele** $A$-nak.
Ha $A \iff B$ igaz, $A$ és $B$ egymás **szükséges és elégséges** feltételei.

*Példa*: $A$: egy szám osztható 4-gyel. $B$: egy szám osztható 2-vel. $A \implies B$ igaz, $B \implies A$ hamis.

> [!note] Matematikatörténeti vonatkozások
> - A logika az ókori görögöknél alakult ki.
> - **George Boole** (1815-1864) alkotta meg a Boole-algebrát.
> - **Claude Shannon** (1930-as évek) ismerte fel az elektromos áramkörök és a Boole-algebra közötti kapcsolatot.

---

# 5. Hatványozás, hatványfogalom kiterjesztése, a hatványozás azonosságai. Az n-edik gyök fogalma. Hatványfüggvények

## Kidolgozás

### I. Pozitív egész kitevőjű hatványok
$a^n = a \cdot a \dots a$ ($n$ tényező, $n \in \mathbb{N}^+$).

**Azonosságok**:
1. $a^m \cdot a^n = a^{m+n}$
2. $\frac{a^m}{a^n} = a^{m-n}$ ($a \neq 0$)
3. $(a \cdot b)^n = a^n \cdot b^n$
4. $(\frac{a}{b})^n = \frac{a^n}{b^n}$ ($b \neq 0$)
5. $(a^n)^m = a^{n \cdot m}$

### II-III. Permanenciaelv és kiterjesztés
A **permanenciaelv** kimondja, hogy a kiterjesztett fogalom (pl. nulla, negatív, tört kitevő) esetén a műveleti szabályok érvényben kell, hogy maradjanak.
- **Nulla kitevő**: $a^0 = 1$ ($a \neq 0$). 
- **Negatív egész kitevő**: $a^{-n} = \frac{1}{a^n}$ ($a \neq 0$).
- **Törtkitevő**: $a^{\frac{p}{q}} = \sqrt[q]{a^p}$ ($a > 0$).

### IV. Az n-edik gyök
> [!info] DEFINÍCIÓ
> - **Páratlan kitevő**: A $2k+1$-edik gyök az a valós szám, melynek $2k+1$-edik hatványa $a$.
> - **Páros kitevő**: Az $a \ge 0$ valós szám $2k$-adik gyökén azt a *nemnegatív* valós számot értjük, melynek $2k$-adik hatványa $a$. ($\sqrt[2k]{x^{2k}} = |x|$).

**Gyökvonás azonosságai**: 
$\sqrt{ab} = \sqrt{a}\sqrt{b}$ ($a, b \ge 0$). Bizonyítás: $(\sqrt{a}\sqrt{b})^2 = (\sqrt{a})^2 (\sqrt{b})^2 = ab$.

### VI-VII. Hatvány- és gyökfüggvények
- $f(x) = x^{2k}$: parabola jellegű, értékkészlet $\mathbb{R}_0^+$, páros, alulról konvex.
- $f(x) = x^{2k+1}$: origóra szimmetrikus (páratlan), szigorúan monoton nő, értékkészlete $\mathbb{R}$.
- $f(x) = \sqrt{x}$: az $x^2$ inverze ($x \ge 0$ szűkítésen). Értelmezési tartomány: $\mathbb{R}_0^+$, szigorúan monoton nő, alulról konkáv.

---

# 6. A logaritmus fogalma és azonosságai. Az exponenciális és a logaritmusfüggvény. Az inverzfüggvény

## Kidolgozás

### I. Logaritmus definíciója
> [!info] DEFINÍCIÓ
> A $\log_a b$ (a alapú logaritmus b) az az egyetlen valós kitevő, amelyre $a$-t emelve $b$-t kapunk: $a^{\log_a b} = b$. Feltételek: $a > 0, a \neq 1, b > 0$.

### II. Logaritmus azonosságai
> [!tip] TÉTELEK
> 1. $\log_a(x \cdot y) = \log_a x + \log_a y$
> 2. $\log_a(\frac{x}{y}) = \log_a x - \log_a y$
> 3. $\log_a(x^k) = k \cdot \log_a x$
> 4. **Alapcsere**: $\log_a b = \frac{\log_c b}{\log_c a}$

> [!quote] BIZONYÍTÁS (Szorzat logaritmusa)
> $x = a^{\log_a x}$ és $y = a^{\log_a y}$. 
> $\log_a(x \cdot y) = \log_a(a^{\log_a x} \cdot a^{\log_a y}) = \log_a(a^{\log_a x + \log_a y}) = \log_a x + \log_a y$.

### III-IV. Exponenciális és Logaritmus függvények
- **Exponenciális** $f(x) = a^x$:
  - É.T.: $\mathbb{R}$, É.K.: $\mathbb{R}^+$. 
  - Ha $a > 1$ monoton nő, ha $0 < a < 1$ monoton csökken. 
- **Logaritmus** $g(x) = \log_a x$:
  - É.T.: $\mathbb{R}^+$, É.K.: $\mathbb{R}$. (Az exponenciális inverze).
  - Grafikonja az $y=x$ egyenesre tükörképe az $a^x$-nek.

### V. Inverzfüggvény
Kölcsönösen egyértelmű (bijektív) függvényeknek van inverze. 
Az inverz előállítása: $y = f(x)$ egyenletből $x$-et fejezzük ki $y$ segítségével, majd felcseréljük a változókat. (pl. $y = 2x - 3 \implies x = \frac{y+3}{2} \implies f^{-1}(x) = \frac{x+3}{2}$).

> [!note] Matematikatörténet
> **John Napier** vezette be a logaritmust a 17. században a bonyolult csillagászati szorzások/osztások összeadásokra redukálása végett. Később logarléceket használtak.

---

# 7. Másodfokú egyenletek és egyenlőtlenségek. Másodfokúra visszavezethető egyenletek.

## Kidolgozás

### II. Másodfokú egyenlet
Alakja: $ax^2 + bx + c = 0$ ($a \neq 0$).

> [!tip] Megoldóképlet és Diszkrimináns
> $x_{1,2} = \frac{-b \pm \sqrt{b^2 - 4ac}}{2a}$
> A gyök alatti kifejezés a diszkrimináns: $D = b^2 - 4ac$.
> - Ha $D > 0$: két valós gyök.
> - Ha $D = 0$: egy valós (kétszeres) gyök.
> - Ha $D < 0$: nincs valós gyök.

> [!quote] BIZONYÍTÁS (Megoldóképlet)
> $ax^2 + bx + c = 0 \quad / \cdot 4a \implies 4a^2x^2 + 4abx + 4ac = 0$
> Teljes négyzetté alakítás: $(2ax + b)^2 - b^2 + 4ac = 0$
> $(2ax + b)^2 = b^2 - 4ac$
> Ha $b^2 - 4ac \ge 0$, gyököt vonunk: $|2ax + b| = \sqrt{b^2 - 4ac}$, amiből átrendezéssel adódik a képlet.

**Viète-formulák**: $x_1 + x_2 = -\frac{b}{a}$, $\quad x_1 \cdot x_2 = \frac{c}{a}$.

### V-VIII. Ekvivalencia, Gyökvesztés, Hamis gyök
- **Gyökvesztés** léphet fel, ha ismeretlent tartalmazó kifejezéssel osztunk (pl. $x(x-1) = x \implies x-1 = 1$, elvesztettük az $x=0$-t).
- **Hamis gyök** (gyöknyerés) léphet fel páros kitevőre emeléskor (pl. négyzetre emelés). Ezt ellenőrzéssel vagy értelmezési tartomány / értékkészlet szűkítéssel (ekvivalens átalakítás feltételeivel) küszöböljük ki.

---

# 8. A leíró statisztika jellemzői, diagramok. Nevezetes középértékek

## Kidolgozás

### II. Leíró statisztika
Célja a tömeges jelenségekből származó adatok összegyűjtése, rendszerezése.
- **Minta**: A vizsgált sokaság egy részhalmaza. Reprezentatív kell legyen.
- **Gyakoriság**: Hányszor fordul elő az adott érték.
- **Relatív gyakoriság**: Gyakoriság osztva az összes adatszámmal.

### III. Diagramok
- Oszlop-, sáv-, hisztogram, kördiagram, vonaldiagram (poligon).

### IV-V. Középértékek, Szóródás
> [!info] DEFINÍCIÓK
> - **Módusz**: A leggyakrabban előforduló adat.
> - **Medián**: Sorba rendezett adatok középső értéke (páros elemszám esetén a két középső átlaga).
> - **Számtani átlag**: $A = \frac{a_1 + \dots + a_n}{n}$
> - **Szórás**: Az átlagtól való eltérések négyzetátlagának gyöke: $\sigma = \sqrt{\frac{\sum (x_i - \bar{x})^2}{n}}$.

**Nevezetes középértékek** (pozitív számokra):
- Számtani ($A$), Mértani ($G = \sqrt[n]{a_1 \dots a_n}$), Harmonikus ($H$), Négyzetes ($Q$).
- **Egyenlőtlenség**: $H \le G \le A \le Q$. Egyenlőség pontosan akkor, ha $a_1 = a_2 = \dots = a_n$.

> [!quote] BIZONYÍTÁS ($G \le A$ két számra)
> $\sqrt{ab} \le \frac{a+b}{2}$. Pozitív számokra ekvivalens azzal, hogy $4ab \le (a+b)^2 \implies 0 \le a^2 - 2ab + b^2 \implies 0 \le (a-b)^2$, ami mindig igaz.

### VI. Alkalmazás szélsőérték-feladatokban
Ha az összeg állandó, a szorzat maximális, ha az elemek egyenlőek (pl. adott kerületű téglalapok közül a négyzet területe a legnagyobb).

---

# 9. Függvénytani alapismeretek, függvények tulajdonságai, határérték, folytonosság. Számsorozatok. A számtani sorozat

## Kidolgozás

### I-II. Függvény és tulajdonságai
> [!info] DEFINÍCIÓ
> Adott egy $A$ és $B$ halmaz. Ha $A$ minden eleméhez egyértelműen hozzárendeljük $B$ pontosan egy elemét, a leképezést függvénynek nevezzük. $A = D_f$ (értelmezési tartomány), a felvett értékek halmaza $R_f \subseteq B$ (értékkészlet).

**Lokális és Globális tulajdonságok**:
- Zérushely: $f(x)=0$.
- Monotonitás, Szélsőérték (lokális/globális maximum, minimum).
- Görbület (Konvex: húr a görbe felett; Konkáv: húr a görbe alatt). Inflexiós pont.
- Paritás: Páros ($f(-x) = f(x)$), Páratlan ($f(-x) = -f(x)$).
- Periodicitás: $f(x+p) = f(x)$.

### III-IV. Számsorozatok
A sorozat egy függvény: $\mathbb{N}^+ \to \mathbb{R}$. Jelölés: $a_n$.
Tulajdonságok: Monotonitás, korlátosság, határérték ($\lim_{n \to \infty} a_n = A$). Ha konvergens, akkor korlátos (de fordítva nem mindig igaz, kivéve ha monoton is).

### V. Számtani sorozat
> [!info] DEFINÍCIÓ
> A szomszédos tagok különbsége állandó: $a_{n+1} - a_n = d$.
> $n$-edik tag: $a_n = a_1 + (n-1)d$.

> [!tip] TÉTEL (Összegképlet)
> $S_n = \frac{a_1 + a_n}{2} \cdot n = \frac{2a_1 + (n-1)d}{2} \cdot n$.

> [!quote] BIZONYÍTÁS
> Írjuk fel az összeget kétszer:
> $S_n = a_1 + (a_1 + d) + \dots + (a_1 + (n-1)d)$
> $S_n = a_n + (a_n - d) + \dots + (a_n - (n-1)d)$
> Összeadva oszloponként a $d$-k kiesnek: $2S_n = (a_1 + a_n) \cdot n \implies S_n = \frac{a_1 + a_n}{2} n$.

---

# 10. Mértani sorozat, az első n tag összege, végtelen mértani sor. Kamatszámítás, gyűjtőjáradék, törlesztőrészlet

## Kidolgozás

### I. Mértani sorozat
> [!info] DEFINÍCIÓ
> A szomszédos tagok hányadosa állandó: $\frac{a_{n+1}}{a_n} = q$.
> $n$-edik tag: $a_n = a_1 \cdot q^{n-1}$.

> [!tip] TÉTEL (Összegképlet)
> $S_n = a_1 \frac{q^n - 1}{q - 1}$ (ha $q \neq 1$). (Ha $q=1$, $S_n = n \cdot a_1$).

> [!quote] BIZONYÍTÁS
> $S_n = a_1 + a_1 q + a_1 q^2 + \dots + a_1 q^{n-1}$
> Szorozzuk be $q$-val: $q S_n = a_1 q + a_1 q^2 + \dots + a_1 q^n$
> A másodikból kivonva az elsőt a belső tagok kiesnek: $q S_n - S_n = a_1 q^n - a_1 \implies S_n(q-1) = a_1(q^n - 1)$.

### II. Végtelen mértani sor
Ha $|q| < 1$, akkor a sorozat konvergens, és a végtelen sor összege $S = \frac{a_1}{1 - q}$. (Ha $|q| \ge 1$, divergens).

### III-V. Kamatszámítás és Pénzügyek
- **Kamatos kamat**: $a_n = a \left(1 + \frac{p}{100}\right)^n = a \cdot q^n$.
- **Gyűjtőjáradék**: Minden időszak elején beteszünk $a$-t. $S_n = a \cdot q \frac{q^n-1}{q-1}$.
- **Törlesztőrészlet**: Adósság törlesztése. $S_n \cdot q^n = a \frac{q^n-1}{q-1}$.

---

# 11. A differenciálhányados fogalma, deriválási szabályok. A differenciálszámítás alkalmazásai

## Kidolgozás

### II. Differenciálhányados (Derivált)
> [!info] DEFINÍCIÓ
> Az $f$ függvény $x_0$ pontbeli differenciálhányadosa a különbségi hányados határértéke:
> $$ f'(x_0) = \lim_{x \to x_0} \frac{f(x) - f(x_0)}{x - x_0} $$
> Geometriai jelentés: a grafikonhoz húzott **érintő meredeksége** az $x_0$ pontban. Az érintő egyenlete: $y = f'(x_0)(x - x_0) + f(x_0)$.

### III. Deriválási szabályok
- $(c)' = 0$
- $(c \cdot f(x))' = c \cdot f'(x)$
- $(f \pm g)' = f' \pm g'$
- Szorzat: $(f \cdot g)' = f'g + fg'$
- Hányados: $\left(\frac{f}{g}\right)' = \frac{f'g - fg'}{g^2}$
- Összetett: $(f(g(x)))' = f'(g(x)) \cdot g'(x)$

Elemi függvények: $(x^n)' = nx^{n-1}$, $(e^x)' = e^x$, $(\ln x)' = \frac{1}{x}$, $(\sin x)' = \cos x$, $(\cos x)' = -\sin x$.

### IV. Alkalmazások (Függvényvizsgálat)
- Ha $f'(x) > 0$, a függvény **szigorúan monoton nő**. Ha $f'(x) < 0$, **monoton csökken**.
- **Lokális szélsőérték** ott lehet, ahol $f'(x_0) = 0$. Ha itt $f'$ előjelet vált, ott szélsőérték van. (Vagy ha $f''(x_0) > 0 \implies$ min, $f''(x_0) < 0 \implies$ max).
- Ha $f''(x) > 0$, a függvény **konvex**; ha $f''(x) < 0$, **konkáv**. Ahol $f''(x_0)=0$ és előjelet vált, az **inflexiós pont**.

---

# 12. Derékszögű háromszögekre vonatkozó tételek. A hegyesszögek szögfüggvényei.

## Kidolgozás

### II. Tételek
> [!tip] Pitagorasz-tétel
> Derékszögű háromszögben a befogók négyzetösszege egyenlő az átfogó négyzetével: $a^2 + b^2 = c^2$.

> [!quote] BIZONYÍTÁS (Terület-összerakással)
> Két $a+b$ oldalú négyzetet rajzolunk. Az egyiket felosztjuk egy $a^2$ és egy $b^2$ területű négyzetre és 4 darab $a,b$ befogójú derékszögű háromszögre. A másikat egy $c^2$ területű (a háromszögek átfogóiból álló) négyzetre és szintén a 4 db háromszögre. A négy háromszöget elhagyva marad: $a^2 + b^2 = c^2$.

> [!tip] Magasságtétel és Befogótétel
> - $m = \sqrt{p \cdot q}$ (a magasság a befogók vetületeinek mértani közepe).
> - $a = \sqrt{c \cdot p}$, $b = \sqrt{c \cdot q}$.

### III-V. Szögfüggvények
Derékszögű háromszögben:
- $\sin \alpha = \frac{a}{c}$ (szemközti befogó / átfogó)
- $\cos \alpha = \frac{b}{c}$ (melletti befogó / átfogó)
- $\tan \alpha = \frac{a}{b}$, $\cot \alpha = \frac{b}{a}$

**Kiterjesztés**: Egységsugarú körben az $x$-tengely pozitív felével bezárt szög esetén a vektor végpontjának koordinátái $P(\cos\alpha, \sin\alpha)$.

> [!tip] Pitagoraszi azonosság
> $\sin^2\alpha + \cos^2\alpha = 1$. (A $\sin, \cos$ értékek egy egységkör pontjait adják).

---

# 13. Háromszögek nevezetes vonalai, pontjai és körei

## Kidolgozás

### I. Oldalfelező merőlegesek
> [!tip] TÉTEL
> A háromszög három oldalfelező merőlegese egy pontban metszik egymást. Ez a háromszög köré írt kör középpontja.
> **Bizonyítás**: Két oldalfelező metszéspontja ($O$) egyenlő távol van a 3 csúcstól. Tehát a 3. csúcstól és a 2.-tól is, azaz rajta van a harmadik oldalfelezőn is.

### II. Szögfelezők
A belső szögfelezők a háromszög **beírt körének középpontjában** metszik egymást (mivel a szögfelező pontjai a száraktól egyenlő távol vannak).

### III. Magasságvonalak
A magasságvonalak a **magasságpontban** (ortocentrum) metszik egymást.

### IV. Súlyvonalak
> [!tip] TÉTEL
> A súlyvonalak egy pontban metszik egymást (súlypont, $S$). A súlypont a súlyvonalakat 2:1 arányban osztja a csúcs felől.

### VI. Euler-egyenes
A magasságpont, a súlypont és a körülírt kör középpontja egy egyenesen van (Euler-egyenes). $S$ harmadolja a szakaszt.

---

# 14. Összefüggések az általános háromszögek oldalai között, szögei között, oldalai és szögei között

## Kidolgozás

### II. Háromszög-egyenlőtlenség
$a + b > c, a + c > b, b + c > a$.

### IV. Szinusztétel és Koszinusztétel

> [!tip] Szinusztétel
> Egy háromszögben két oldal aránya megegyezik a velük szemközti szögek szinuszának arányával: $\frac{a}{b} = \frac{\sin \alpha}{\sin \beta}$. A köré írt kör sugarával: $\frac{a}{\sin\alpha} = 2R$.

> [!tip] Koszinusztétel
> Bármely háromszögben $c^2 = a^2 + b^2 - 2ab \cos\gamma$.

> [!quote] BIZONYÍTÁS (Vektorokkal)
> Legyenek a háromszög vektorai: $\vec{c} = \vec{a} - \vec{b}$.
> Emeljük négyzetre skalárisan: $\vec{c}^2 = (\vec{a} - \vec{b})^2 = \vec{a}^2 - 2\vec{a}\vec{b} + \vec{b}^2$.
> A skaláris szorzat definíciója miatt $\vec{a}\vec{b} = |\vec{a}||\vec{b}|\cos\gamma = ab\cos\gamma$.
> Ezt behelyettesítve: $c^2 = a^2 + b^2 - 2ab\cos\gamma$.

---

# 15. Egybevágósági transzformációk, alakzatok egybevágósága. Szimmetria. Hasonlósági transzformációk

## Kidolgozás

### I. Egybevágósági transzformációk
Távolságtartó leképezések a síkon: Tengelyes tükrözés, Középpontos tükrözés, Elforgatás, Eltolás.
- Két alakzat egybevágó ($\cong$), ha egyik a másikba vihető egybevágósági transzformációval.
- Háromszögek egybevágóságának alapesetei: OOO (oldal-oldal-oldal), SZO (szög-oldal-szög), OSZ (oldal-szög-szög - a nagyobbal szemben), SZSZ (szög-szög-oldal).

### IV. Hasonlósági transzformációk
A középpontos hasonlóság ($O$ centrum, $\lambda \neq 0$ arány): $OP' = \lambda \cdot OP$. A transzformáció során a szögek tartósak, a távolságok $|\lambda|$-szorosára változnak.
Két alakzat hasonló ($\sim$), ha hasonlósági transzformációval egymásba vihetők.

> [!tip] TÉTEL (Terület és térfogat)
> Hasonló síkidomok területének aránya a hasonlósági arány négyzete ($T'/T = \lambda^2$). Hasonló testek térfogatának aránya a köbe ($V'/V = \lambda^3$).

### VIII. Alkalmazások
- **Középvonal tétel**: A háromszög középvonala párhuzamos az alappal és fele olyan hosszú (hasonlóság aránya 1:2).
- **Szögfelezőtétel**: A belső szögfelező a szemközti oldalt a szomszédos oldalak arányában osztja.

---

# 16. Konvex sokszögek tulajdonságai. Szabályos sokszögek. Gráfok

## Kidolgozás

### I-II. Konvex és Szabályos sokszögek
> [!tip] TÉTELEK
> - Egy $n$ oldalú konvex sokszög átlóinak száma: $\frac{n(n-3)}{2}$.
> - Belső szögek összege: $(n-2) \cdot 180^\circ$.
> - Egy szabályos $n$-szög egy belső szöge: $\frac{(n-2) \cdot 180^\circ}{n}$.

### III. Gráfok
Gráf: Pontok (csúcsok) és vonalak (élek) halmaza.
> [!tip] Fokszámtétel
> A pontok fokszámösszege az élek számának kétszerese. (Ebből: a páratlan fokszámú csúcsok száma mindig páros).

- **Teljes gráf**: Minden csúcs össze van kötve minden másikkal. Élek száma: $\frac{n(n-1)}{2}$.
- **Fa**: Körmentes összefüggő gráf. Élek száma egy $n$ csúcsú fában $n-1$.
- **Euler-vonal**: A gráf összes élét pontosan egyszer tartalmazó vonal. Zárt Euler-vonal akkor van, ha a gráf összefüggő és minden csúcs foka páros. Nyílt, ha pontosan 2 páratlan fokú csúcs van.

---

# 17. A kör és részei. Kerületi szög, középponti szög, látószög. Húrnégyszögek, érintőnégyszögek

## Kidolgozás

### I. Kör részei, területek
- Kör területe: $T = r^2\pi$, kerülete: $K = 2r\pi$.
- Körcikk területe (ha $\alpha$ a kp-i szög fokban): $T_{cikk} = \frac{r^2\pi}{360^\circ} \alpha$.

### II. Kerületi és középponti szögek
> [!tip] TÉTEL
> Adott körben adott ívhez tartozó bármely kerületi szög nagysága fele az ugyanazon ívhez tartozó középponti szög nagyságának: $\beta = \frac{\alpha}{2}$.
> **Következmény (Thalész-tétel)**: Félkörívhez tartozó kerületi szög derékszög.

### III. Húrnégyszög
> [!info] DEFINÍCIÓ ÉS TÉTEL
> Négyszög, melynek csúcsai egy körön vannak. Egy négyszög pontosan akkor húrnégyszög, ha **szemközti szögeinek összege $180^\circ$**.

### IV. Érintőnégyszög
> [!info] DEFINÍCIÓ ÉS TÉTEL
> Négyszög, melynek oldalait egy belső kör érinti. Egy konvex négyszög pontosan akkor érintőnégyszög, ha **szemközti oldalainak összege egyenlő**.

---

# 18. Vektorok, vektorműveletek. Vektorfelbontási tétel. Vektorok koordinátái. Skaláris szorzat

## Kidolgozás

### I-II. Vektor fogalma, Műveletek
- **Vektor**: Irányított szakasz, melyet hossza (abszolút értéke) és iránya jellemez.
- Összeadás (háromszög/paralelogramma szabály), Különbség, Skalárral való szorzás. Műveletek kommutatívak és asszociatívak.

### III. Vektorfelbontási tétel
> [!tip] TÉTEL
> Ha $\vec{a}$ és $\vec{b}$ nem párhuzamos (lineárisan független) vektorok a síkban, akkor bármely síkbeli $\vec{c}$ vektor egyértelműen előáll $\vec{c} = \alpha \vec{a} + \beta \vec{b}$ alakban ($\alpha, \beta \in \mathbb{R}$). Ezt lineáris kombinációnak hívjuk.

### V. Skaláris szorzat
> [!info] DEFINÍCIÓ
> $\vec{a} \cdot \vec{b} = |\vec{a}| |\vec{b}| \cos\alpha$, ahol $\alpha$ a két vektor által bezárt szög.
> Koordinátákkal: $\vec{a}(a_1, a_2), \vec{b}(b_1, b_2)$ esetén $\vec{a} \cdot \vec{b} = a_1 b_1 + a_2 b_2$.

> [!tip] Merőlegesség
> Két nemnulla vektor akkor és csak akkor merőleges, ha skaláris szorzatuk 0.

---

# 19. Szakaszok és egyenesek a koordinátasíkon. Párhuzamos és merőleges egyenesek. Elsőfokú egyenlőtlenségek, egyenletrendszerek grafikus megoldása

## Kidolgozás

### I. Szakaszok
- Két pont távolsága: $AB = \sqrt{(b_1 - a_1)^2 + (b_2 - a_2)^2}$.
- Felezőpont: $F\left(\frac{a_1+b_1}{2}, \frac{a_2+b_2}{2}\right)$.

### II-III. Egyenes egyenlete
- **Irányvektor** $\vec{v}(v_1, v_2)$: párhuzamos az egyenessel. 
- **Normálvektor** $\vec{n}(A, B)$: merőleges az egyenesre.
- **Normálvektoros egyenlet**: $Ax + By = Ax_0 + By_0$. (Bizonyítás: az egyenes tetszőleges $P(x,y)$ pontjára $\vec{P_0 P} \perp \vec{n}$, azaz $\vec{P_0 P} \cdot \vec{n} = 0 \implies (x-x_0)A + (y-y_0)B = 0$).
- **Iránytényezős egyenlet**: $y - y_0 = m(x - x_0)$, ahol $m = \tan\alpha = \frac{v_2}{v_1} = -\frac{A}{B}$.

### IV. Párhuzamosság és Merőlegesség
Két egyenes ($e$ és $f$)
- **Párhuzamos**, ha normálvektoraik (vagy irányvektoraik) egyirányúak (skalárszorosai egymásnak), azaz $\vec{n}_e = \lambda \vec{n}_f$, meredekségre: $m_e = m_f$.
- **Merőleges**, ha normálvektoraik merőlegesek ($\vec{n}_e \cdot \vec{n}_f = 0$), meredekségre: $m_e \cdot m_f = -1$.

---

# 20. A kör és a parabola elemi úton és a koordinátasíkon. Kör és egyenes, parabola és egyenes kölcsönös helyzete.

## Kidolgozás

### I. Kör egyenlete
> [!tip] TÉTEL
> A $C(u; v)$ középpontú, $r$ sugarú kör egyenlete $(x - u)^2 + (y - v)^2 = r^2$.
> Bizonyítása a két pont távolságképletéből azonnal adódik, négyzetre emelve.
> Kifejtve: $x^2 + y^2 + Ax + By + C = 0$, ami akkor kör, ha teljes négyzetté alakítás után a jobb oldal pozitív.

### II. Parabola egyenlete
Tengelypont: $T(0,0)$, fókuszpont $F(0, \frac{p}{2})$, vezéregyenes $y = -\frac{p}{2}$.
A parabola egyenlete: $y = \frac{1}{2p}x^2$. 
Általános helyzetben: $y = a x^2 + b x + c$.

### III-IV. Kölcsönös helyzet (Kör/Parabola és Egyenes)
Egyenletrendszert alkotunk az alakzatok egyenleteiből, amiből behelyettesítéssel másodfokú egyenletet kapunk:
- $D > 0$: két metszéspont (szelő).
- $D = 0$: egy közös pont (érintő).
- $D < 0$: nincs közös pont.

---

# 21. Térelemek távolsága és szöge. Térbeli alakzatok. Felszín- és térfogatszámítás

## Kidolgozás

### I. Térelemek (Sík és Tér)
- Két kitérő egyenes (nincsenek közös síkban) távolsága a **normáltranszverzálisuk** (mindkettőre merőleges egyenes) szakasza. Szögüket párhuzamos eltolással kapott metsző egyenesek szöge adja.
- **Egyenes és sík merőlegessége**: Egy egyenes merőleges a síkra, ha a sík minden egyenesére merőleges (elég két metsző egyenest vizsgálni).

### II-V. Testek
- **Poliéderek** (Szabályos testek: tetraéder, kocka, oktaéder, dodekaéder, ikozaéder).
- Felszínek ($A$) és Térfogatok ($V$) kiszámítása:
  - Hasáb: $V = T_{alap} \cdot m$.
  - Gúla: $V = \frac{T_{alap} \cdot m}{3}$.
  - Henger: $V = r^2\pi m$, $A = 2r\pi(r+m)$.
  - Kúp: $V = \frac{r^2\pi m}{3}$, $A = r\pi(r+a)$ (ahol $a$ az alkotó).
  - Gömb: $V = \frac{4r^3\pi}{3}$, $A = 4r^2\pi$.

> [!note] Matematikatörténeti vonatkozások
> - **Eukleidész** vizsgálta a szabályos testeket, bebizonyította, hogy csak 5 létezik.
> - **Arkhimédész** megmutatta, hogy a henger, a beleírt gömb és kúp térfogataránya 3:2:1.

---

# 22. Területszámítás elemi úton és az integrálszámítás felhasználásával

## Kidolgozás

### II. Síkidomok területe
- Háromszög: $T = \frac{a \cdot m_a}{2} = \frac{a b \sin\gamma}{2} = \sqrt{s(s-a)(s-b)(s-c)}$ (Heron).
- Négyszögek (speciálisak: téglalap $ab$, paralelogramma $a m_a$, trapéz $\frac{a+c}{2}m$).
- Bármely négyszög: $T = \frac{e f \sin\phi}{2}$ (átlók és szögük).

### III-IV. Integrálszámítás
> [!info] DEFINÍCIÓ
> A folytonos $f(x) \ge 0$ függvény görbéje, az $x$-tengely, valamint az $x=a$ és $x=b$ függőlegesek által bezárt terület a határozott integrál: 
> $$ T = \int_a^b f(x) dx $$

Két függvény $f(x) > g(x)$ közötti terület: $T = \int_a^b (f(x) - g(x)) dx$.
A határozott integrált a Newton-Leibniz formula segítségével számítjuk: $\int_a^b f(x) dx = F(b) - F(a)$, ahol $F$ a primitív függvény.

---

# 23. Kombinációk. Binomiális tétel, a Pascal-háromszög. A valószínűség kiszámításának kombinatorikus modellje.

## Kidolgozás

### I. Kombináció
- **Ismétlés nélküli**: $n$ elemből $k$ elem kiválasztása sorrend nélkül: $\binom{n}{k} = \frac{n!}{k!(n-k)!}$.
- **Ismétléses**: $n$ elemből $k$ elem kiválasztása, az elemek visszatehetők: $\binom{n+k-1}{k}$.

### II. Binomiális tétel és Pascal-háromszög
> [!tip] Binomiális tétel
> $$ (a+b)^n = \binom{n}{0}a^n b^0 + \binom{n}{1}a^{n-1}b^1 + \dots + \binom{n}{n}a^0 b^n = \sum_{k=0}^n \binom{n}{k} a^{n-k} b^k $$

A Pascal-háromszög sorai a binomiális együtthatókat tartalmazzák. Alapszabálya: $\binom{n}{k} + \binom{n}{k-1} = \binom{n+1}{k}$.

### V-VI. Valószínűségszámítás
**Klasszikus valószínűségi modell**: Ha az elemi események száma véges és egyenlő valószínűségűek.
$P(A) = \frac{\text{kedvező esetek száma}}{\text{összes eset száma}}$.

**Hipergeometrikus eloszlás** (visszatevés nélküli mintavétel):
$P(X=k) = \frac{\binom{M}{k} \binom{N-M}{n-k}}{\binom{N}{n}}$. (Várható érték: $n \frac{M}{N}$).

---

# 24. Permutációk, variációk. A binomiális eloszlás. A valószínűség kiszámításának geometriai modellje

## Kidolgozás

### I. Permutációk
$n$ elem sorbarendezései. 
- Ismétlés nélküli: $P_n = n!$
- Ismétléses ($k_1, k_2, \dots$ megegyező elemek): $P_n^{i} = \frac{n!}{k_1! k_2! \dots}$

### II. Variációk
$n$ elemből $k$ elem kiválasztása sorrend figyelembevételével.
- Ismétlés nélküli: $V_n^k = \frac{n!}{(n-k)!}$
- Ismétléses: $V_n^{k,i} = n^k$

### IV. Binomiális eloszlás
Olyan kísérletek (Bernoulli-kísérlet), melyeknek 2 kimenetele van ($p$ siker, $1-p$ kudarc), és $n$-szer megismételjük (visszatevéses modell).
Annak a valószínűsége, hogy $k$-szor lesz sikeres:
$$ P(X = k) = \binom{n}{k} p^k (1-p)^{n-k} $$

### V. Geometriai valószínűség
Ha az esemény bekövetkezése arányos a vizsgált tartomány (vonal, síkidom, test) geometriai mértékével (pl. terület).
$P(A) = \frac{m(A)}{m(\Omega)}$, ahol $\Omega$ a teljes tér (pl. célba dobás).

---

# 25. Bizonyítási módszerek és bemutatásuk tételek bizonyításában

## Kidolgozás

A matematikai logikára és axiómákra épül. A tételek állítások (legtöbbször implikációk).

### II. Direkt bizonyítás
A feltevésből logikai lépéseken keresztül levezetjük az állítást. Példa: Pitagorasz-tétel.

### III. Indirekt bizonyítás
Feltesszük a bizonyítandó állítás tagadását, majd logikai lépésekkel ellentmondásra (lehetetlen állításra) jutunk a feltételekkel, axiómákkal szemben. Mivel a tagadás hamis, az eredeti állítás igaz. 
Példa: $\sqrt{2}$ irracionális; végtelen sok prímszám van.

### IV. Teljes indukció
Állítások bizonyítása $\mathbb{N}^+$-ra.
1. Megmutatjuk, hogy igaz az első értékre (pl. $n=1$).
2. Feltesszük, hogy igaz $n=k$-ra (indukciós feltevés).
3. Bizonyítjuk, hogy a feltevésből következik, hogy $n=k+1$-re is igaz.
Példa: Az első $n$ természetes szám összege: $1 + 2 + \dots + n = \frac{n(n+1)}{2}$.

### V. Skatulyaelv (Skatulya elv / Dirichlet-elv)
Ha $n$ skatulyába $n$-nél több dolgot rakunk, akkor biztosan lesz olyan skatulya, amelybe legalább kettő kerül.
Példa: 37 fős társaságban biztosan van legalább 4 ember, aki ugyanabban a hónapban (csillagjegyben) született, mert $37 > 12 \cdot 3$.

> [!note] Matematikatörténet
> - **Eukleidész** alkalmazta elsőként mesterfokon az axiómatikus felépítést és a bizonyítási igényt az *Elemek* című művében.
> - **Dirichlet** (1805–1859) francia matematikus nevéhez kötődik a skatulyaelv rigorózus formalizálása.