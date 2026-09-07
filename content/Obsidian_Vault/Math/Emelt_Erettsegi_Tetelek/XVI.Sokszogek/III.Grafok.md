A gráfok nagyon jól szemléltetik egy halmaz elemei közti kapcsolatokat. Gráfokkal szemléltethetõk pl. egy társaság ismeretségi viszonyai, vagy bármilyen hálózat kapcsolódási viszonyai. 

**DEFINÍCIÓ:** A ==gráf== pontokból és vonalakból áll. Minden vonal két (nem feltétlenül különbözõ) pontot köt össze. A pontok a gráf pontjai, a vonalak a gráf élei. 

**DEFINÍCIÓ:** A gráfokban elõfordulhat olyan él is, melynek mindkét végpontja ugyanaz a pont, az ilyen él neve ==hurokél==.

**DEFINÍCIÓ:** A gráf olyan pontját, amelybõl nem vezet él, ==izolált pont==nak nevezzük. 

**DEFINÍCIÓ:** Két csúcs között több élt is húzhatunk, ezek a ==többszörös él==ek. 

**DEFINÍCIÓ:** Egy gráfot ==egyszerû gráf==nak nevezünk, ha nincs benne sem hurokél, sem többszörös él.
<p align="center">
  <img src="Pasted image 20260819142147.png" />
</p>

**DEFINÍCIÓ:** Egy gráf egy pontjához illeszkedõ élvégek számát a pont ==fokszám==ának (fokának) nevezzük.

**TÉTEL:** A legalább $2$ csúcsú egyszerû gráfban van $2$ azonos fokú csúcs.
<p align="center">
  <img src="Pasted image 20260819142301.png" />
</p>

**TÉTEL:** A pontok ==fokszámösszege az élek számának kétszerese==. 

**TÉTEL:** Minden gráfban a pontok ==fokszámának összege páros== szám. 

**TÉTEL:** A páratlan fokszámú pontok halmaza páros (hiszen a páros fokszámú pontok fokszámának az összege páros, és ehhez hozzáadva a páratlan fokszámú pontok összegét, páros számot kell kapnunk). 

**DEFINÍCIÓ:** Egy gráf ==összefüggõ gráf==, ha bármely pontjából bármely másik pontjába élek mentén el lehet jutni.
<p align="center">
  <img src="Pasted image 20260819143436.png" />
</p>

**DEFINÍCIÓ:** Ha egy gráfnak $n$ pontja van ($n \in\mathbb{Z}^+$) és mindegyik pontból pontosan egy él vezet a többi ponthoz, akkor a gráfot $n$ pontú ==teljes gráf==nak nevezzük. 

**TÉTEL:** $n$ pontú teljes gráf ==éleinek a száma==: $\frac{n\cdot (n-1)}{2}$.

**TÉTEL:** $n$ pontú teljes gráfban a ==fokszámok összege==: $n \cdot (n - 1)$.
<p align="center">
  <img src="Pasted image 20260819143714.png" />
</p>

**DEFINÍCIÓ:** Az ==út== az élek olyan egymáshoz kapcsolódó sora, amely egyetlen ponton sem halad át egynél többször.
<p align="center">
  <img src="Pasted image 20260819143852.png" />
</p>

**DEFINÍCIÓ:** A ==vonal== a gráf csúcsainak és éleinek az a sora, amelyben az élek ezeket a pontokat kötik össze és az élek nem ismétlõdnek, **egy csúcs többször is elõfordulhat**. A vonal ==zárt, ha kezdõ és végpontja megegyezik, egyébként nyílt==.
<p align="center">
  <img src="Pasted image 20260819143934.png" />
</p>

**DEFINÍCIÓ:** A ==kör== olyan vonal, amelynek **kezdõ és végpontja megegyezi**k és a **pontok nem ismétlõdnek**. 

**DEFINÍCIÓ:** Az ==Euler-vonal== a gráf összes élét pontosan egyszer tartalmazó vonal. Lehet zárt és lehet nyílt Euler-vonal. Zárt Euler-vonalnak nincs kezdõ és végpontja, mert egybeesik, nyílt Euler-vonalnál két különbözõ pont van a vonal két végén. 

**TÉTEL:** ==Zárt== Euler vonala akkor és csak akkor van egy összefüggõ gráfnak, ha ==minden foka páros==.
<p align="center">
  <img src="Pasted image 20260819144041.png" />
</p>

**TÉTEL:** ==Nyílt== Euler vonala akkor és csak akkor van egy összefüggõ gráfnak, ha ==pontosan két páratlan fokú== pontja van.
<p align="center">
  <img src="Pasted image 20260819144305.png" />
</p>

**DEFINÍCIÓ:** Két gráfot ==izomorf==nak nevezünk, ha pontjaik és éleik kölcsönösen egyértelmûen és illeszkedéstartóan megfeleltethetõek egymásnak.
<p align="center">
  <img src="Pasted image 20260819144342.png" />
</p>

**DEFINÍCIÓ:** A ==fagráf== olyan összefüggõ gráf, amely **nem tartalmaz kört**. 

**TÉTEL:** A fagráf ==maximális körmentes== gráf (bármely két pontját összekötjük, amelyek között nem volt él, akkor a gráf már tartalmaz kört). 

**TÉTEL:** A fagráf ==minimális összefüggõ== gráf (bármely élet elhagyjuk, akkor a gráf már nem össze függõ). 

**TÉTEL:** A fagráf ==bármely két csúcsát egyetlen út köti össze== 

**TÉTEL:** Az $n$ csúcsú fagráfnak $n - 1$ éle van.
<p align="center">
  <img src="Pasted image 20260819144444.png" />
</p>

**TÉTEL:** Minden egynél több csúcsú fagráfnak van legalább 2 elsõfokú csúcsa.
