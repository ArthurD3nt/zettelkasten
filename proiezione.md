# Proiezione
```sql
select SName, City from S;
```
> Mostra nome e città di tutti i fornitori

![[Pasted image 20220829091140.png]]

| Tipo                                        |                                         |
| ------------------------------------------- | --------------------------------------- |
| Calcolo du tuple con dichiarazione di range | $$\{s\text{.}(SName, City)\mid s(S)\}$$ |
| Algebra relazionale                         | $$\pi_{SName,City}(S)$$                 |

---
#DB #SQL 