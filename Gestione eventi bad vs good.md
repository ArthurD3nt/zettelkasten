## Bad 
```html
<!-- ./home.html -->
<button id="ok" onclick="okayClick();">OK</button>
<script>
	function okayClick() {
		alert("booyah");
	}
</script>
```

## Good
Possiamo direttamente manipolare il [[DOM]]
```html
<!-- ./home.html -->
<head>
	<script src="jsFileBelow.js" type="text/javascript"></script>
<head>
<body>
	<button id="ok">OK</button>
<body>
```
```js
// ./jsfileBelow.js
function okayClick() {
	alert("booyah");
}

//starts the event handlers when the DOM elements are ready
function pageLoad() { 
	document.getElementById("ok").onclick = okayClick;
}

window.onload = pageLoad;
```

> **NB**: gli eventi sono tutti minuscoli, non in camel case


---
#TWEB #JS 