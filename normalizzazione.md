# Normalizzazione
Approccio complementare a quello dello [[schema E-R]].

![[Pasted image 20220828111226.png]]

Ha come obiettivo di rendere le relazioni:
- Meglio esprimibili
- Efficienti
- Leggibili

La relazione di cui sopra presenta vari generi di **anomalie**:
- [[anomalie_di_inserzione]] $\quad\longrightarrow$ esprimibilità
- [[anomalie_di_cancellazione]] $\quad\longrightarrow$ esprimibilità
- [[anomalie_di_update]] $\quad\longrightarrow$ esprimibilità e efficienza
- Sinonimie
- Omonimie

**Soluzione**:
- Per le varie anomalie si procede con la [[normalizzazione | normalizzazione]]
- Per le sinonimie e omonimie di procede con la [[Standardizzazione | standardizzazione]]

## Formalizzazione del problema
**Obbiettivo**: Buona progettazione
**Problemi**: [[anomalie_di_inserzione]], [[anomalie_di_cancellazione]], [[anomalie_di_update]]
**Formalizzazione adeguata**: [[dipendenza_funzionale]]

---
#DB