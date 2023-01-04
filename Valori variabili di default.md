```js
var s = "Espresso";  
var n = null;  
var e = s || "Coffee";  // e is "Espresso"  
var f = n || "Coffee";  // f is "Coffee"  
var g = n || s;         // g is "Espresso"  
var h = 0 || n;         // h is null
```

Quando la varibile non è definita viene assegnato il valore di default

---
#TWEB #JS 2023-01-04