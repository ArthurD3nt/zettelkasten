# HTTP
> Hypertext Transfer Protocol
> Definisce l'insieme i comandi interpretati dal browser che usa quelle informazioni per fare una richiesta al server web ~~

Ad esempio alcuni comandi sono:
- `GET` = richiede un documento
- `POST` = invia delle informazioni (*es.* form)
- `PUT` = invia un documento

Simulando un'operazione usando telnet:
```bash
telnet www.cs.washington.edu 80
Trying 128.208.3.88... 
Connected to 128.208.3.88 (128.208.3.88).
Escape character is '^]'. 
GET /index.html 
<!DOCTYPE HTML PUBLIC "-//W3C//DTD HTML 4.0 ..."> 
<html>
...
```
## Errori
| Numero  | Significato                               |
| ------- | ----------------------------------------- |
| 200     | OK                                        |
| 301-303 | Page has moved (permanently or temporaly) |
| 403     | You are forbidden to access this page     |
| 404     | Page not found                            |
| 500     | Internal server error                     |

---
#TWEB 2022-09-20