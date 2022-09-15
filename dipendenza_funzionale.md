# Dipendenze funzionali
> Data una [[relazione]] $r(A)$, un [[sottoinsieme]] $X$ di [[attributi]] di $A(X\subseteq A)$, un altro [[sottoinsieme]] di [[attributi]] di $A(Y\subseteq A)$ il *vincolo di dipendenza funzionale* $X\rightarrow Y$ ($X$ determina $Y$) è soddisfatto se e solo se:
> $$\forall t_1,t_{2} \in r(t_{1}[X]= t_{2}[X] \Longrightarrow t_{1}[Y] = t_{2}[Y])$$

Sono quindi simili ai [[vincoli di integrità referenziale]].

Ad *esempio*:
![[Pasted image 20220828121259.png]]

Ogni progettista può vedere la realtà in modo diverso e formulare delle dipendenze funzionali diverse, per questo dobbiamo capire come fare l'[[equivalenza_delle_dipendenze_funzionali | equivalenza delle dipendenze funzionali]]

---
#DB 