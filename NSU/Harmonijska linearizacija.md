#nsu

### Nema veze sa stabilnoscu, niti rigoroznom matom!

Harmonijska linearizacija je postupak pravljenja **[opisne funkcije nelinearnosti](Opisna%20funkcija%20nelinearnosti.md)** N(E,$\omega$)


Forma jednacine nelinearnog sistema je:
$f(x_1, \dot x_1, \ddot x_1, x_2, ...x_n) = 0$
### Pretpostavke:
1) NL i L se mogu odvojiti u distinktne delove
2) L(s) je NF filtar
3) NL je centralno-simetricna u odnosu na e,u = (0,0)
![[Pasted image 20230808004031.png]]

### Nalazenje oscilacija:
Na ulaz od N(E,$\omega$) dolazi prostoperiodican signal 
e(t) = E$sin(\omega_0 t)$ 
Pitanje je koliko iznose E i $\omega_0$?
Nalaze se iz jednacine:
$1 +N(E,\omega_0)L(j\omega_0) = 0$
# STA JE N(E)?

### [Opisna f-ja nelinearnosti](Opisna%20funkcija%20nelinearnosti):
Ako je izlaz NL(e(t)) = A1sin($\omega_0t)$ + B1cos($\omega_0t$) + ..., onda N= U/E
$N(E,\omega_0) = \frac{A_1+B_1s/\omega_0}{E}$ (U(s) sveden na osnovni harmonik) 
N ~ 1/E

N(E) je efektivno pojacanje osnovnog harmonika.

### Izracunavanje:

Radi se Furijeov red. A1 je koef. uz sin() a B1 uz cos(). Dakle:
$A_1 = \frac{2}{T} \int_0^Tnelin[Esin(\omega_0t)]sin(\omega_0t)dt$

B1 = isto, samo cos

Iz ovoga se racuna jednacina pod Nalazenje Oscilacija