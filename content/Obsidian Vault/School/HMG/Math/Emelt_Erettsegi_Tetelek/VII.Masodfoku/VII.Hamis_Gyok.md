Hamis gyököt kaphatunk, ==ha az egyenlet mindkét oldalát négyzetre emeljük, vagy mindkét oldalt az ismeretlent tartalmazó kifejezéssel szorozzuk==, vagy olyan átalakítást végzünk, ami bõvíti az értelmezési tartományt.

---
1. példa: $\sqrt{7-x} = 1-x \quad /()^2$ .  
Eredeti feltétel: $7-x \ge 0 \Rightarrow x \le 7 \Rightarrow D_f = \; ]-\infty, 7]$.  
A gyöknyerés kiküszöbölhető közbülső feltétellel: $1-x \ge 0 \Rightarrow x \le 1 \Rightarrow D_{f_{\text{új}}} = \; ]-\infty, 1]$.  
$7-x = (1-x)^2 \Rightarrow x^2-x-6=0 \Rightarrow x_1=3 \notin D_{f_{\text{új}}}, \; x_2=-2 \in D_{f_{\text{új}}}$

---
2. példa: $2x + \frac{1}{x-1} = 2 + \frac{1}{x-1} \quad / -\frac{1}{x-1} \Rightarrow 2x = 2 \Rightarrow x = 1.$  
A gyöknyerés ekkor is kiküszöbölhető, ha az eredeti egyenletre írunk $D_f$-et.

---
3. példa: $\sqrt{x+6} - \sqrt{x+2} = \sqrt{2x+8}$ .  
Eredeti feltételek: $x+6 \ge 0 \Rightarrow x \ge -6; \; x+2 \ge 0 \Rightarrow x \ge -2; \; 2x+8 \ge 0 \Rightarrow x \ge -4; \Rightarrow D_f = [-1; \infty[.$  
Ha az egyenletet először rendezzük úgy, hogy mindkét oldal nemnegatív legyen, négyzetre emeljük mindkét oldalt, rendezzük úgy, hogy a gyökös kifejezés az egyik oldalra kerüljön, a többi tag a másik oldalra, majd a négyzetre emelés előtt közbülső feltételt írunk, hogy a gyöknyerést kiküszöböljük:

$\sqrt{x+6} = \sqrt{x+2} + \sqrt{2x+8} \rightarrow \text{/négyzetre emelés}$  
$x+6 = x+2 + 2 \cdot \sqrt{x+2} \cdot \sqrt{2x+8} + 2x+8 \rightarrow \text{/rendezés}$  
$-2x-4 = 2 \cdot \sqrt{x+2} \cdot \sqrt{2x+8} \rightarrow \text{közbülső feltétel írása: a jobb oldal nemnegatív, a bal oldalnak}$  
$\text{is annak kell lennie, mivel egyenlők, azaz } -2x - 4 \ge 0 \Rightarrow x \le -2 \Rightarrow D_{f_{\text{új}}} = \{-2\}$. 
Ebben az esetben nem is kell elvégezni a négyzetre emelést, hiszen csak egy szám felel meg az értelmezésnek, ha van megoldás, akkor csak ez az egy szám lehet. Ennek ellenõrzésével eldönthetõ, hogy ez valóban megoldás-e. Akár a gyökvesztés, akár a hamis gyök elkerülhetõ, ha az egyenlet megoldása során mindig figyelünk az értelmezési tartomány változására, ha lehet, az értékkészletet is vizsgáljuk, mert így szûkíteni lehet az alaphalmazt.