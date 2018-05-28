Examen Regex
============

##### 1. El símbolo que denota cualquier caracter es:
- [ ] `*`
- [ ] `?`
- [x] `.`
- [ ] `x`

##### 2. Para usar un rango de caracteres (por ejemplo `0-9` o `a-g`) lo tenemos que delimitar en la expresión con:
- [x] `[]`
- [ ] `()`
- [ ] `{}`
- [ ] `<>`

##### 3. Si quisiera hacer que una expresión no distinga entre mayúsculas y minúsculas, debo agregarle la bandera:
- [ ] `/a`
- [ ] `/e`
- [ ] `/u`
- [x] `/i`

##### 4. El patrón `a.` significa exactamente:
- [ ] cero o sólo una `a`
- [x] una `a` y cualquier otro caracter
- [ ] una o más `a`
- [ ] cero o más `a`

##### 5. El patrón `a*` significa exactamente:
- [ ] cero o sólo una `a`
- [ ] una `a` y cualquier otro caracter
- [ ] una o más `a`
- [x] cero o más `a`

##### 6. El patrón `a?` significa exactamente:
- [x] cero o sólo una `a`
- [ ] una `a` y cualquier otro caracter
- [ ] una o más `a`
- [ ] cero o más `a`

##### 7. El patrón `a+` significa exactamente:
- [ ] cero o sólo una `a`
- [ ] una `a` y cualquier otro caracter
- [x] una o más `a`
- [ ] cero o más `a`

##### 8. La clase `\w` es equivalente a
- [x] `[a-zA-Z0-9]`
- [ ] `[a-z]`
- [ ] `[0-9]`
- [ ] `[:digits:]`

##### 9. Para delimitar el número de ocurrencias de alguna expresión (una, dos o tres, en este caso), el número de repeticiones buscadas se denota por…
- [ ] `[1,3]`
- [x] `{1,3}`
- [ ] `(1,3)`
- [ ] `<1,4>`

##### 10. Si quiero encontrar grupos de sólo 3 caracteres numéricos, cuál de las siguientes expresiones NO funciona
- [ ] `\d\d\d`
- [ ] `\d{3}`
- [x] `\d+..`
- [ ] `[0-9]{3}`

##### 11. ¿Cuál de las siguientes expresiones sería útil para encontrar palabras que empiecen con letra mayúscula?
- [ ] `/[A-Z]{1}/i`
- [ ] `/[A-Z]?\w/`
- [ ] `/[a-z]/i`
- [x] `/[A-Z][a-z]+/`

##### 12. El patrón `/(\d+?),.*/` qué _match_ tendría? (representando al match de la forma `[ab]`):
- [ ] [12,34,56,78]
- [ ] [12,34,56],78
- [x] [12],34,56,78
- [ ] [1]2,34,56,78

##### 13. Una expresión _greedy_ (`?`) significa que se intentará encontrar el patrón…
- [ ] tantas veces como sea posible
- [ ] sólo una vez
- [x] las menos veces que sea posible
- [ ] siempre

##### 14. La expresión `^1.*` encuentra:
- [x] una línea que empiece con `1`
- [ ] una línea que no empiece con `1`
- [ ] una palabra que no empiece con `1`
- [ ] cualquier palabra que empiece con `1`

##### 15. Para encontrar un punto (el caracter ".") usaríamos:
- [ ] `/./`
- [x] `/\./`
- [ ] `/(.)/`
- [ ] `/{.}/`

##### 16. El caracter que denota cualquier fin de línea es:
- [ ] `^`
- [ ] `\L`
- [x] `$`
- [ ] `\s`

##### 17. La expresión `[^rm][a-z]+` encontrará:
- [ ] Todas las palabras que empiecen con "r" o "m"
- [ ] Todas las líneas que empiecen con "r" o "m"
- [ ] Todas las líneas que NO empiecen con "r" o "m"
- [x] Todas las palabras que NO empiecen con "r" o "m"

##### 18. Cuál de las siguientes líneas NO hará match con la expresión `/^[\w\s]+$/`:
- [ ] 12345678
- [ ] hola como estás
- [x] 12,34,56,78
- [ ] Esto es una prueba

##### 19. Cuál de las siguientes líneas SÍ hará match con la expresión `/[a-z]{6,}@?gmail.com/`:
- [ ] hola_3@gmail.com
- [ ] adios@gmail.com
- [ ] nada@gmail.com
- [x] pruebagmail.com

##### 20. Supongamos que tenemos un archivo `csv` con códigos de producto, todos los códigos son dos caracteres seguidos por 8 a 10 dígitos, pero sólo queremos los productos que empiecen con _AB_ o _CD_, ¿qué expresión usarías?
- [x] `/[AC][DB]\d{8,10}/`
- [ ] `/[AB|CD]{2,2}\d{8|10}/`
- [ ] `/[ABCD]{2,2}\d{8,10}/`
- [ ] `/[AB][CD]{2,2}\d{8|10}/`

##### (joke) 21. Cuando tenemos un problema y lo planeamos solucionar con expresiones regulares, entonces
- [ ] las expresiones regulares son como santa claus: son los papás
- [ ] tenemos dos problemas
- [x] tardaremos un poco más en solucionarlo, pero tendremos una solución robusta y duradera
- [ ] tenemos una solución a medias que proveerá más problemas en el futuro
