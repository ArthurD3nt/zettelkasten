> [...] you should prefer, in most of the cases, the initialization with var rather than writing the type explicitly.

![[Pasted image 20221025113928.png]]

## Null protection
**Null protection by default**, per bypassarla usare `late` keyword e sempre esplicitare il tipo:
![[Pasted image 20221025114154.png]]

## Final keyword for constants
Flutter usa `final` come keyword, modificare il suo valore successivamente da errore. 
![[Pasted image 20221025114350.png]]
[[type | Type]] inference automatica

## String concatenation
> The official Dart guidelines suggest to prefer using interpolation to compose strings, which is shorter and cleaner:
> ![[Pasted image 20221025152758.png]]

>Since strings are immutable, making too many concatenations with the + operator might be ineficfient. In such cases it’d be better if you used a StringBuffer which efficiently concatenates strings.
> ![[Pasted image 20221025152941.png]]

## Private
> Le variabili private iniziano con `_`
> You cannot have named optional parameters starting with an underscore.


---
#IUM #flutter 2022-10-25