#nsu 
Ispituje [Apsolutnu stabilnost](Kruzni%20kriterijum%20(apsolutna%20stabilnost))
# Restrikcije:
1) Nelinearnost pripada otvorenom sektoru (0,<mark style="background: #BBFABBA6;">k</mark>)
2) L(s) je u prostoru stanja:
   L(s)= $C(sI-A)^{-1}B +\frac{d}{s}$
   uz uslove:
   a) Matrica A je Hurvicova (svi polovi u LPR)
   b) (A,B) je kontrolabilna forma
   c) (A,C) je opservabilna forma
   d) d>0
Ekvivalentni uslovi za L(s) su da je minimalna stabilna realizacija, osim <mark style="background: #FFB8EBA6;">obaveznog</mark> astatizma

# Kriterijum:
Za $L(\omega) = R(\omega) + j I(\omega)$ 
Sistem <mark style="background: #FF5582A6;">zatvorene sprege</mark> je globalno <mark style="background: #FF5582A6;">asimptotski</mark> stabilan ako postoji realan broj r>0
	$inf Re\{(1+j\omega r)L(j\omega)\}+1/k>0,\omega \in R$ , <mark style="background: #BBFABBA6;">k</mark> je gornja granica sektora

## Geometrijska Interpretacija:
Realni deo izraza gore, $R(\omega)-\omega r I(\omega) > -1/k$.
Ako kroz tacku -1/k provucemo pravu sa nagibom 1/r, <mark style="background: #ADCCFFA6;">Kriva popova ce biti cela s desne strane ove prave!</mark> r moze biti proizvoljan pozitivan realan broj.

## Kriva Popova:
Ista kao Nyquistova kriva, ali njen imaginarni deo je pomnozen sa $\omega$ 

## Ekvivalentni uslov Popova:
$(\forall \omega) R(\omega)> r \omega I(\omega) -1/k$ 

