#dos
Rotacioni faktor se koristi za [Diskretnu furijeovu transformaciju](Diskretna%20Furijeova%20Transformacija%20-%20DFT.md) u N tacaka.

Njegova formula je $W_N = e^{-\frac{j2\pi}{N}}$, i koristi se kao faktor za mnozenje u formuli za DFT

$X(k)=T\sum_{k=0}^{N-1}x(n)W_N^{kn}$ 

## Bitne osobine $W_N$ za DFT:
1) <mark style="background: #FFF3A3A6;">Konjugovano-kompleksna simetrija</mark> $W_N^{k(N-n)}=W_N^{-kn}=(W_N^{kn})*$  
2) Periodicnost po <mark style="background: #FF5582A6;">n</mark> i <mark style="background: #FFB86CA6;">k</mark>:
   $W_N^{kn}=W_N^{k(N+n)}=W_N^{n(N+k)}$ 
Obe osobine su posledica cinjenice da je $W_N^N = 1$ 