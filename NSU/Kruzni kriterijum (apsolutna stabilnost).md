#nsu 
Postavka problema blok-dijagramom je ista kao za [Harmonijsku linearizaciju](Harmonijska%20linearizacija.md) , s tim sto je nelinearni deo sistema predstavljen kao kontroler $\Phi(t,y)$ u povratnoj grani.

<mark style="background: #FF5582A6;">**Globalna eksponencijalna</mark> stabilnost se odredjuje na osnovu Sektora Nelinearnosti


Sektor nelinearnosti je ogranicen sa pravama koeficijenata a i b (a=K1,b=K2 ovde)

![[Pasted image 20230808004653.png]]
Krug-disk se crta na Nyquistovom dijagramu i to tako da mu je centar na negativno realnoj poluosi, a precnik odredjen tackama -1/a i -1//b

1) 0 < a < b : <mark style="background: #BBFABBA6;">ZA NESTABILNE DPR polove!!!</mark>
   Nikvistova kriva L(jw) ne dodiruje disk, i ostvaruje prirastaj $P\pi$ u odnosu na disk D, P-broj DPR polova
2) 0=a< b (Disk je beskonacan)
   Ako je realni deo nikvistove ose uvek > -1/b i sistem je striktno stabilan (P=0), eventualno sa cisto imaginarnim polovima
3) a<0< b 
   L(s) je striktno stabilan, i kriva je u potpunosti unutar diska D
4) a<b<0 :
	Primenjuje se 1) i 2) na sistem -L(s) i b' i a' odredjeni ovim postupkom se preobrazuju u a=-b' i b=-a' u originalnom sistemu.