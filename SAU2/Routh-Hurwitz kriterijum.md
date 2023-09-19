#sau2 #control 

### Za kontinualne sisteme sa karakteristicnim monikom

Postoji algoritam cijim se pracenjem moze zakljuciti da li je sistem stabilan.
Algoritam se sastoji od unakrsnog mnozenja, oduzimanja i deljenja poslednjim elementom iz prve kolone.
Za $f(s)= a_n s^n + a_{n-1} s^{n-1}...+a_1s +a_0$ , napravicemo tabelu:

| $s^n$     | $a_n$     | $a_{n-2}$ | $a_{n-4}$ |     |
| --------- | --------- | --------- | --------- | --- |
| $s^{n-1}$ | $a_{n-1}$ | $a{n-3}$  | $a_{n-5}$ |     |
| $s^{n-2}$ | A         | B         | C         |     |
| ...       |     D      |  E         |           |     |
| $s^0$     |         |           |           |     |

## A=$\frac{a_{n-1}a_{n-2}-a_na_{n-3}}{a_{n-1}}$ 
## B =$\frac{a_{n-1}a_{n-4} -a_na_{n-5}}{a_{n-1}}$
## C= $\frac{a_{n-1}a_{n-6}-a_na_{n-7}}{a_{n-1}}$ 
## D = $\frac{Aa_{n-3}-a_{n-1}B}{A}$ 
## E = $\frac{Aa_{n-5}-a_{n-1}C}{A}$


# Brojanjem koliko puta se menja znak u prvoj koloni se pokazuje broj korenova u DPR
