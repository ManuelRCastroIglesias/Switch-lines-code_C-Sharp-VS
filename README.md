# Como usar SwitchComments

1. Inserta una línea nueva, antes de las líneas a modificar y añade  
_*<kbd style=font-size:1.05rem>//\*/</kbd>*_  
e inserta otra línea nueva, después de la última línea y vuelve a añadir otro  
_*<kbd style=font-size:1.05rem>//\*/</kbd>*_  
Esto hará que dicha sección aparezca comentada.  
Para descomentarla simplemente quita una _*<kbd style=font-size:1.05rem>/</kbd>*_ del  inicio de la primera y el bloque aparecerá descomentado,  
y vueve a añadirla para recomentarlo.  
Con ello ya no necesitas seleccionar el bloque y realizar las acciones de comentar o descomentar,  
ahorra mucho trabajo.

2. En el caso de que necesites alternar dos bloques.  
Añade antes de la segunda, otra línea con lo siguiente  
_*<kbd style=font-size:1.05rem>/\*/</kbd>*_  
y en medio de ambas el código alternativo.  
Esto hará que los bloques de código alternen su comportamiento.

EJEMPLO:

---
_`//*/`_ -> Observa que hay dos _*<kbd style=font-size:1.05rem>//</kbd>*_ al inicio  
_`boolean isEntranceEnable = true; //código comentado`_  
_`/*/`_  
_*<kbd style=font-size:1.05rem>boolean isEntranceEnable = false;</kbd>*_ _`//código descomentado`_  
_`//*/`_  

---
O bien

---
_`/*/`_ -> Observa que solo hay una _*<kbd style=font-size:1.05rem>/</kbd>*_ al inicio  
_*<kbd style=font-size:1.05rem>boolean isEntranceEnable = true;</kbd>*_ _`//código descomentado`_  
_`/*/`_  
_`boolean isEntranceEnable = false; //código comentado`_  
_`//*/`_  

---

## ¡IMPORTANTE!

NUNCA uses comentarios tipo bloque _*<kbd style=font-size:1.05rem>/\* ... \*/</kbd>*_ en el inetrior ya que no funcionan.

Es conveniente añadir un comentario precedido de dos _*<kbd style=font-size:1.05rem> // </kbd>*_ para indicar:
-  que se intenta hacer,  
- cual es el original y cual el alternativo, 
- quien es el autor de la modificación 
- y la fecha de la misma. 

las dos últimas son opcionales.

# Justificación

Para empezar hay que aclarar un punto importante.

### Nunca debemos subir a producción código comentado 
> Por lo que deberemos usar alguna extensión como Prettier o similar para limpiar nuestro código.

### Entonces ¿Para que sirve SwitchComment?
> SwitchComment sirve para comentar y descomentar rápidamete bloques de código mientras codificas  
y poder realizar variantes y probar cual se comporta mejor, o si dicha variante funciona sin alterar el código original.

> Debido a ello cuando estamos trabajando en colaboración, nos permite sugerir cambios o correcciones  
sin tener que modificar el código original,  
es muy molesto que alguien te modifique algo, ya que puede que la única solución para recordar lo que habías  
realizado con anterioridad sea la de revertir los cambios, y estos pueden ser realmente geniales o muy malos.  
Te pueden destruír la lógica de tu algoritmo, entre otras cosas.

> También te resultará muy útil si relizas videotutoriales para activar y desactivar código durante las explicaciónes.

# ¡ Feliz codificación!
