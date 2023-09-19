#nsu #matematika 

[Rezultat harmonijske linearizacije](Harmonijska%20linearizacija)
## Recimo da imamo sistem sa povratnom spregom

Neka je ulaz u L(s) jednak U(s), izlaz iz N($\omega_0,E$).
Neka je, takodje, ova funkcija periodicna sa periodom $T = \frac{2\pi}{\omega_0}$.
Treca i konacna pretpostavka je da je L(s) NF filtar, i da su neosnovni harmonici potisnuti dovoljno da budu zanemareni.

Onda je ulaz u nelinearni sistem $e=-y=Asin(\omega_0t)$ 
Izlaz ce biti periodican za bezmemorijski NL sistem, a periodican signal se moze prikazati kao 
$\sum_{n=1}^{n=\infty}a_nsin(n\omega_0t)$ + $\sum_{n=1}^{n=\infty}b_ncos(n\omega_0t)$, ali u realnosti su bitni samo a1 i b1.

To je zato sto ce samo osnovni harmonik biti prenesen kroz L(s), te je jedino bitno pojacanje NL sistema na toj frekvenciji.


## Izracunavanje:

e(t)=E*sin($\omega_0t$) 
u(t)=$A_1sin(\omega_0t)+B_1cos(\omega_0t)$ + ostatak
$A_1 = 2/T\int_0^{\frac{2\pi}{\omega_0}} u(t)sin(\omega_0t)dt$ 
N = $A_1/E$ + j$\omega_0B1/E$ 







