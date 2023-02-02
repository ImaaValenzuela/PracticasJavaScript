# JavaScript Basico

## Explora las diferencias entre las palabras claves var y let
Var permite sobreescribir declaraciones con el mismo nombre.

```javascript
var camper = "James";
var camper = "David";
```
En el código anterior, la variable camper se declara originalmente como James, y se anula para ser David. La consola después muestra la cadena de texto David.

Una palabra clave llamada let fue introducida en ES6, una actualización importante para JavaScript, para resolver este problema potencial con la palabra clave var. Así que a diferencia de var, al usar let, una variable con el mismo nombre solo puede declararse una vez.


### Enunciado del ejercicio:
Actualiza el código para que solo utilice la palabra clave let.