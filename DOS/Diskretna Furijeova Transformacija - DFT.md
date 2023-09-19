#dos
Diskretna Furijeova transformacija je diskretni ekvivalent [Furijeove transformacije](Furijeova%20transformacija) 

<mark style="background: #BBFABBA6;">Formula za N vremenskih odbiraka sa N frekvencijskih izlaza glasi</mark>:
$X(k)=T\sum_{n=0}^{N-1}x(n)e^{-j\frac{2\pi}{N}kn}$, gde se obicno poslednji cinilac naziva [rotacionim faktorom](Rotacioni%20faktor) 

Inverzna DFT je:

$x(n) = \frac{1}{NT}\sum_{k=0}^{N-1}X(k)e^{j\frac{2\pi}{N}kn}$ 