# Selezione
```sql
select SName, City from S where Status > 20;
```
> Mostra nome e città di tutti i fornitori che hanno status  maggiore di 20

![[Pasted image 20220829091140.png]]

| Tipo                                        |                                         |
| ------------------------------------------- | --------------------------------------- |
| Calcolo du tuple con dichiarazione di range | $$\{s\text{.}(SName, City)\mid s(S) \mid s.Status \}$$ |
| Algebra relazionale                         | $$\pi_{SName,City}(σ_{Status>20}(S))$$                 

---
#DB #SQL 