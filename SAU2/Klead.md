#sau2 

# Klead kontroler

Ako zelimo da povecamo propusni opseg nekog sistema, na primer 
$G(s)=50\frac{s+1}{s(\frac{s}{0.1}+1)(\frac{s}{20}+1)}$ mozemo koristiti $K_{lead}$ kontroler, koji ima nulu pre pola.

![[gs1.jpg]]
Ovaj sistem je minimalno fazni i presecna ucestanost mu je  $\omega_0=5\frac{rad}{s}$.
	Ako zelimo da povecamo propusni opseg na $\omega_0^*=50\frac{rad}{s}$ i da nam [[Bodeovi parametri|pretek faze]] $\Phi_{pf}^*\geq45^{\circ}$
Onda moramo da isprojektujemo $K_{lead}=\frac{s/\omega_n+1}{s/\omega_p +1}$ **sa sledecim ogranicenjima**:
#### $a=\frac{\omega_p}{\omega_n}\in (1,10) \land a=\frac{1+sin(\Delta \Phi_{pf})}{1-sin(\Delta \Phi_{pf})}$
#### $\Delta \Phi_{pf} = \Phi_{pf}^* - \Phi_{pf}$
#### $\omega_1 = \sqrt{\omega_n \times \omega_p}$ = $\sqrt{a} \times \omega_n$ 


Nulu stavljamo na ucestanost $\omega_n << \omega_0$ da bi se maksimizovao prirastaj faze, a pol pozicioniramo tako da se nasteluje zeljena presecna ucestanost.

