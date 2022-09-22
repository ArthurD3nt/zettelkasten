# Ereditarietà
![[Pasted image 20220922112519.png]]

```java
class Finestra {
	Rettangolo r;
	void disegnaCornice();
	void disegnaContenuto();
}

class FinestraConTitolo extends Finestra() {
	//Rettangolo r; -> ereditato
	String titolo;
	//void disegnaCornice(); -> ereditato
	//void disegnaContenuto(); -> ereditato
	void disegnaTitolo();
}
```

Altrimenti dovrei riscrivere tutto [...]

L'**ereditarietà** viene controllata tramite due tipi di controlli:
- [[type_checking_statico | Contollo statico dei tipi]]
- [[type_checking_dinamico | Contollo dinamio dei tipi]]

## Sottotipi
[9]

## Singola
[10]

## Multipla
[11]

[[polimorfismo | Polimorfismo]]



---
#PROG3 2022-09-22