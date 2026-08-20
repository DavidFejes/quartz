**Kidolgozás:**
	
**DEFINÍCIÓ**: A természetes számok halmaza ($\mathbb{N}$) a pozitív egész számokból és a 0-ból áll. A természetes számok halmaza zárt az összeadásra és a szorzásra nézve, azaz bármely két természetes szám összege és szorzata természetes szám. Ugyanakkor a kivonás és az osztás már nem végezhetõ el ezen a halmazon belül, ezek a mûveletek „kimutatnak” a halmazból. Pl. $3 - x = 5$ egyenlet megoldása.
	
**DEFINÍCIÓ:** Az egész számok halmaza ($\mathbb{Z}$) a természetes számokból és azok [ellentettjeibõl](Ellentett.md) áll. Az egész számok halmaza az összeadáson és a szorzáson kívül a kivonásra nézve is zárt, ugyanakkor az osztás kimutathat a halmazból. Pl. $2x + 3 = 4$ egyenlet megoldása.
	
**DEFINÍCIÓ:** A racionális számok halmaza ($\mathbb{Q}$) azokból a számokból áll, amelyek felírhatók két egész szám hányadosaként, azaz $\frac{a}{b}$ alakban, ahol $a, b \in\mathbb{Z}$, $b \neq 0$. A racionális számok halmaza mind a 4 alapmûveletre zárt (osztásra, ha az osztó nem 0), de itt is találunk olyan egyenletet, amelynek nincs megoldása ezen a halmazon. Pl.: $2x^2 - 3 = 0$.
	
**DEFINÍCIÓ**: Azokat a számokat, amelyek nem írhatók fel két egész szám hányadosaként, irracionális számoknak ($Q*$) nevezzük

---
**TÉTEL**: $\sqrt{2}$ irracionális szám.
**BIZONYÍTÁS**: A bizonyítást indirekt módon végezzük, lényege, hogy a bizonyítandó állítás tagadásáról bebizonyítjuk, hogy az hamis. Ez azt jelenti, hogy a bizonyítandó állítás igaz. Tegyük fel hogy $\sqrt{2}$ racionális szám, azaz felírható $a$ $b$ alakban, ahol $a, b \in\mathbb{Z}$, $b \neq 0$, $(a;b) = 1$. ([relatív prímek](III.Osztok#^relativ-primek)) 
Ekkor $\sqrt{2} = \frac{a}{b} \implies \; 2=\frac{a^2}{b^2} \implies \; 2*b^2 = a^2$.
Az egyenlet jobb oldalán szereplõ ($a^2$) szám [prímtényezõs felbontásában](Primtenyezos_Felbontas.md) a 2 mindenféleképpen páros kitevõn (akár a nulladikon) szerepel, míg a bal oldalon levõ szám ($2 * b^2$) prímtényezõs felbontásában a 2 kitevõje páratlan (legkevesebb 1). Ez azonban lehetetlen, hiszen a [számelmélet alaptétele](II.Primszamok_Osszetett_Szamok#^szamelmelet-alaptetele) szerint egy pozitív egész számnak nincs két lényegesen különbözõ felbontása. Tehát nem igaz az indirekt feltevésünk, vagyis igaz az eredeti állítás: $\sqrt{2}$ irracionális. 
**Tulajdonságok:**
	– Az irracionális számok halmaza nem zárt a 4 alapmûveletre $(\sqrt{2}+(-\sqrt{2})) = 0 \notin \mathbb{Q}*$
	− $\sqrt{2}*\sqrt{2} = 2 \notin \mathbb{Q}*,\; \sqrt{2}:\sqrt{2} = 1 \notin \mathbb{Q}*$.
	– Az irracionális számok tizedes tört alakja végtelen nem szakaszos tizedes tört.

---
**DEFINÍCIÓ**: A racionális és az irracionális számok halmaza [diszjunkt](II.Halmazmuveletek#^diszjunkt) halmazok ($\mathbb{Q} \cap \mathbb{Q}* = \emptyset$), a két halmaz egyesítése a valós számok halmaza: R = Q » Q*. A valós számok halmaza zárt a 4 alapmûveletre. [Valós számok és részhalmazai](Szamhalmazok.png)