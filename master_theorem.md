# Master theorem

## Relazione di ricorrenza
$$T(n)=a\cdot T(\frac{n}{b})+f(n)$$
- $n=$ dimensioni dell'input
- $a=$ numero di sottoproblemi (chiamate ricorsive)
- $b=$ fattore con il quale il sottoproblema di riduce ad ogni chiamata ricorsiva
- $f=$ $O,\space\Theta,\space\Omega$

## Caso 1
$$T(n)=8T\Big(\frac{n}{2}\Big)+1000n^2$$
applicando il **master theorem**:
$$a=8,\space b=2,\space f(n)=1000n^2$$
quindi:
$$f(n)=O(n^2),\text{ dove }c=2$$

## Caso 2
$$T(n)=2T\Big(\frac{n}{2}\Big)+10n$$
applicando il **master theorem**:
$$a=2,\space b=2,\space f(n)=10n$$
quindi:
$$f(n)=\Theta(n^{c}\log^{k}n)\text{ dove }c=1\text{ e }k=0$$
controlliamo se soddisfa il *caso 2*:
$$\log_{b}a=\log_{2}2=1,\text{ quindi }c=\log_{b}a$$
quindi segue il *secondo caso*:
$$T(n)=\Theta(n^{\log_{b}a}\log^{k+1}n)=\Theta(n^{1}\log^{1}n)=\Theta(n\log n)$$

---
#ASD 2022-08-29