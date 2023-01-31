# Como usar SwitchComments

### Inserta antes del bloque o línea a comentar, una línea nueva y añade:  

---  
```java
... el código anterior ... // Código descomentado
//* código original (descomentado)/
... código ...
... código ... // Comentarios de línea no funcionan en el interior 
... código ...
... código ... // Comentario fin de línea
... código ...
/* código alternativo (comentado) es opcional/
... código ...
... código ... // Comentarios de línea no funcionan en el interior 
... código ...
... código ... // Comentario fin de línea
... código ...
//*/
... el resto del código ... // Código descomentado
```

Para descomentar el código, simplemente quita o pon una **barra oblicua** de la línea:  
```F#
//* código original (descomentado)/
```
```C++
/* código original (y alternarás los bloques comentados) /
```  
Con lo que puedes alternar los comentarios en bloques alternos con una sola tecla.  
Con ello ya no necesitas seleccionar el bloque y realizar las acciones de comentar o  
descomentar, con lo que te ahorraras mucho trabajo.  

**Recuerda: ** Borrar los comentarios cuando ya no los necesites.

EJEMPLO:

---
```C#
//* Observa que hay dos barras al inicio/
boolean isEntranceEnable = false; //código descomentado
/*/
boolean isEntranceEnable = true; //código comentado
//*/
```
---
- **Y para alternar entre ambos solo usas una tecla (o dos... 😎la división y 😎el retroceso ):**

---
```javascript
/* Observa que solo hay una barra al inicio/
boolean isEntranceEnable = false; //código comentado
/*/
boolean isEntranceEnable = true; //código descomentado
//*/
```
---

# Justificación

### Para empezar hay que aclarar un punto importante.
## **Nunca debemos subir a producción código comentado. **
* Por lo que deberemos usar alguna extensión como Prettier o similar para limpiar nuestro código.

>---
>
>### Entonces ¿Para qué sirve SwitchComment?
>- SwitchComment sirve para comentar y descomentar rápidamente bloques de código mientras codificas y poder realizar variantes y probar cuál de ellas se comporta mejor, o si dicha variante realmente funciona, y todo sin alterar el código original.
>- Debido a ello cuando estamos trabajando en colaboración, nos permite sugerir cambios o correcciones sin tener que modificar el código original, ya que es muy molesto que alguien te modifique algo, ya que la única solución para recordar lo que habías realizado con anterioridad es tener que revertir los cambios, y estos pueden ser realmente geniales o muy malos.
>- También te pueden destruir por completo toda la lógica de tu algoritmo, entre otras cosas.
> - Además, te resultará muy útil si realizas videotutoriales o presentaciones 
para activar y desactivar código durante las mismas. 
>---

# **¡** _Y ten una muy feliz codificación_ **! **

