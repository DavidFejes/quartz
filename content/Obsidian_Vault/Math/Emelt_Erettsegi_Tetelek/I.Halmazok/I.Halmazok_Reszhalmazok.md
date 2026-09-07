
**A halmaz és a halmaz eleme alapfogalom**, ezeket a kifejezéseket nem definiáljuk. De a halmaz megadásának szigorú követelménye van: egy halmazt úgy kell megadnunk, hogy minden szóba jöhetõ dologról egyértelmûen eldönthetõ legyen, hogy az adott halmazhoz tartozik vagy sem. A halmazokat nyomtatott nagybetûvel, a halmaz elemeit kisbetûvel jelöljük a következõ módon: 
	$A = \{a; b; c\}$, ebben az esetben a $a \in A, x \notin A$
	**Halmaz megadási módjai**: 
		Elemeinek felsorolásával: $A = \{0; 2; 4; 6\}$ 
		Az elemeit egyértelmûen meghatározó utasítással: B = {egyjegyű páratlan számok} 
		Szimbólumokkal: $A = \{x | x^2 -x-6=0\},  B = \{x|x2 > 9\}$ 
		[Venn-diagrammal](Venn_Diagramm.png)
	
**DEFINÍCIÓ**: Két halmaz ==egyenlõ==, ha ugyanazokat az elemeket tartalmazzák. 
	
**DEFINÍCIÓ**: Az elem nélküli halmazt ==üres halmaz==nak nevezzük. Jele: { } vagy $\emptyset$. 
	
**DEFINÍCIÓ**: Az $A$ halmaz ==részhalmaz==a a $B$ halmaznak, ha $A$ minden eleme a $B$ halmaznak is eleme. Jele: $A\subseteq  B$. 
	
**DEFINÍCIÓ**: Az A halmaz ==valódi részhalmaz==a a B halmaznak, ha A részhalmaza a B-nek, de nem egyenlõ vele. Jele: $A\subset B$.

**Tulajdonságok:**
	•Az üres halmaz minden halmaznak részhalmaza: $\emptyset \subseteq A$. 
	•Minden halmaz önmaga részhalmaza: $A \subseteq A$. 
	•Ha $A \subseteq B$ és $B \subseteq A$, akkor A = B. 
	•Ha $A \subseteq B$ és $B \subseteq C$, akkor $A \subseteq C$

---
**TÉTEL**: Az $n$ elemû halmaz ==összes részhalmazainak száma==: $2^n$ ($n \in\mathbb{N}$). 
**BIZONYÍTÁS I**.: A bizonyítást teljes indukcióval végezzük, amelynek lényege, hogy elõször belátjuk egy konkrét $n$ esetére az állítást, majd azt mutatjuk meg, ha az állítás igaz egy tetszõleges $n$-re, akkor igaz az õt követõ ($n + 1$)-re is, azaz bizonyítjuk az állítás öröklõdését. Az üres halmaznak egyetlen részhalmaza van: önmaga ($2^0 = 1$). Egy egyelemû halmaznak $2$ részhalmaza van: az üres halmaz és önmaga ($2^1 = 2$). Egy kételemû halmaznak 4 részhalmaza van: az üres halmaz, $2$ egyelemû halmaz és önmaga ($2^2 = 4$). Tegyük fel, hogy egy $k$ elemû halmaznak $2^k$ db részhalmaza van. Bizonyítani kell, hogy ez öröklõdik, vagyis egy ($k + 1$) elemû halmaznak $2^{k+1}$ db részhalmaza van. Tekintsük az elõbbi $k$ elemû halmazt. Ekkor ha az eddigi elemek mellé egy ($k + 1$)-edik elemet teszünk a halmazba, akkor ezzel megkétszerezzük a lehetséges részhalmazok számát, hiszen az új elemet vagy kiválasztjuk az eddigi részhalmazokba, vagy nem. Vagyis a ($k + 1$) elemû halmaz részhalmazainak száma $2 * 2k = 2^{k + 1}$, amit bizonyítani kívántunk.

**BIZONYÍTÁS II.:**

Az $n$ elemű halmaznak $\binom{n}{0}$ db 0 elemű, $\binom{n}{1}$ db 1 elemű, $\binom{n}{2}$ db 2 elemű, …, $\binom{n}{n-1}$ db $(n-1)$ elemű, $\binom{n}{n}$ db $n$ elemű részhalmaza van, mert $n$ elemből $k$ db-ot $\binom{n}{k}$-féleképpen lehet kiválasztani.

Így az összes részhalmazok száma:

$$  
\binom{n}{0}+\binom{n}{1}+\binom{n}{2}+\ldots+\binom{n}{n-1}+\binom{n}{n}.  
$$

Vizsgáljuk meg $(2^n$)-t:

$$  
\begin{aligned}  
2^n  
&=(1+1)^n \  
&=\binom{n}{0}\cdot1^0\cdot1^n  
+\binom{n}{1}\cdot1^1\cdot1^{n-1}  
+\binom{n}{2}\cdot1^2\cdot1^{n-2}  
+\ldots \  
&\quad+\binom{n}{n-1}\cdot1^{n-1}\cdot1^1  
+\binom{n}{n}\cdot1^n1^0,  
\end{aligned}  
$$

ami egyenlő

$$  
\binom{n}{0}+\binom{n}{1}+\binom{n}{2}+\ldots+\binom{n}{n-1}+\binom{n}{n}  
$$

-nel a [[II.Binomalis_Tetel#^^binomalis-tetel|binomális tétel]] miatt.

---
