# TareaGit

## MARIO ORTIZ HIDALGO

Ahora mismo estoy editando un archivo desde la rama A para que Iraida, lo modifique desde la rama B

## Qué hice

1. **Creación de ramas**: Creé dos ramas, `ramaA` y `ramaB`. En la rama `ramaA`, yo realicé una modificación en el archivo `archivo.js`, y en la rama `ramaB`, Iraida hizo una modificación diferente en el mismo archivo.

2. **Modificación de archivos**:
   - **En `ramaA`**, yo añadí el siguiente código:
     ```js
     console.log("Hola soy Mario y estoy modificando el archivo desde la rama A")
     ```
   - **En `ramaB`**, Iraida añadió este otro código:
     ```js
     console.log("Hola soy Iraida y estoy modificando el archivo desde la rama B")
     ```

3. **Merge y conflicto**:
   Cuando intenté hacer un merge de la rama `ramaB` en `ramaA`, se generó un conflicto en el archivo `archivo.js`, ya que ambas ramas modificaron el mismo lugar del archivo.

## Qué error o conflicto surgió

El conflicto surgió porque ambos cambios se realizaron en la misma parte del archivo. El contenido del archivo quedó de la siguiente manera:
```js
<<<<<<< HEAD
console.log("Hola soy Mario y estoy modificando el archivo desde la rama A")
=======
console.log("Hola soy Iraida y estoy modificando el archivo desde la rama B")
>>>>>>> ramaB

El conflicto ocurrió porque ambos cambios se realizaron en la misma parte del archivo. El resultado en el archivo fue el siguiente:
```js
<<<<<<< HEAD
console.log("Hola soy Mario y estoy modificando el archivo desde la rama A")
=======
console.log("Hola soy Iraida y estoy modificando el archivo desde la rama B")
>>>>>>> ramaB