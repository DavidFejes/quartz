**TÉTEL**: Szorzat logaritmusa egyenlõ a tényezõk logaritmusának összegével: $$\log_a (x \cdot y) = \log_a x + \log_a y, \;ahol x, y > 0, a > 0, a \ne 1$$
**BIZONYÍTÁS**: A logaritmus definíciója alapján: $$x=a^{\log_a x} \;és\;  y=a^{\log_a y} \;, illetve\; x\cdot y=a^{\log_a ({x\cdot y)}}$$ Nézzük az állítás bal oldalát:$$\log_a(x\cdot y)=\log_a(a^{\log_a x}\cdot a^{\log_a y})=\log_a(a^{\log_a x+\log_a y})=\log_ax+\log_ay,$$az azonos alapú hatványok szorzása és a logaritmus definíciója miatt. Így a bizonyítandó állítás igaz. 

**TÉTEL**: Tört logaritmusa megegyezik a számláló és a nevezõ logaritmusának különbségével: $$\log_a\frac{x}{y}=\log_ax-\log_ay,\; ahol \;x,y>0,\;a>0,\; a\ne 0$$**TÉTEL**: Hatvány logaritmusa az alap logaritmusának és a kitevõnek a szorzata: $$\log_ax^k=k\cdot\log_ax,\; ahol\; x>0,\;a>0,\;a\ne1,\;k\in\mathbb{R}$$ 

**TÉTEL**: Áttérés más alapú logaritmusra:$$\log_ab=\frac{\log_cb}{\log_ca},\; ahol\; a,b,c>0,\; a,c\ne1$$

**BIZONYÍTÁS**: A logaritmus definíciója alapján: $b=a^{\log_ab}$. 
Írjuk fel: $\log_cb=\log_ca^{\log_ab}=\log_ab\cdot\log_ca$ , a logaritmus definíciója és a hatvány logaritmusa miatt. 
Kaptuk: $\log_cb=\log_ab\cdot\log_ca, \;\log_ca\ne0$ a feltételek miatt. 
Így: $\log_ab=\frac{\log_cb}{\log_ca}$. Ez a bizonyítandó állítás.