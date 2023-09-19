#nsu 
## Lokalna stabilnost:

##### Definicija lokalno-stabilnog ravnoteznog stanja po Ljapunovu:

Ravnotezno stanje je lokalno stabilno u $u=t_0$ ako za njegovu proizvoljnu okolinu $\epsilon$, postoji $\delta(\epsilon,t_0)$ takvo da

$||x(t_0) - X_e||<\delta \implies (\forall t > t_0)||x(t)-xe||<\epsilon$ 

## Kvadratna forma:
$V(x)=x^TPx$ <mark style="background: #FFB86CA6;">gde je P pozitvno semi-definitna simetricna matrica.</mark>


## Funkcija Ljapunova:
Kandidat za funkciju Ljapunova MORA ispuniti 4 uslova:
1) $V(x_1,x_2)=0; x=x_e$
2) $V(x_2,x_2) > 0 ; x \neq x_e$ 
3) $\dot{V}(x_1,x_2) = 0; x=x_e$ 
4) Jedan od sledeca 3:
   1) $\dot{V}(x_1,x_2) < 0; x \neq x_e$ Lokalno asimptotski stabilno R.S.
   2) $\dot{V}(x_1,x_2) \leq 0; x \neq x_e$ Lokalno stabilno R.S.
   3) $\dot{V}(x_1,x_2) > 0; x \neq x_e$ Lokalno nestabilno R.S.


## Indirektni metod Ljapunova:

Linearizacija, provera polova

## Direktni metod Ljapunova:

Funkcija Ljapujnova

## Vrste stabilnosti:
Globalna asimptotska
Globalna eksponencijalna
Lokalna asimptotska
