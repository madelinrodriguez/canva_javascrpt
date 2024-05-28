# Juegos con HTML

## Elemento canvas

- E l elemento canvas, junto al lenguaje JS nos permite crear animaciones y juegos 2d en el navegador.

- En el navegador el codigo se interpreta de manera secuencial.

- para utilizar el codigo JS, debemos esperar a que todos los elemnetos HTML hayan sido creados antes de ser utilizados.

- Alternativas:
   - Colocar el script en la parte interior de la pagina.
   -utilizar un detector de eventos que nos indique cuandolos elementos han sido creados. (eventos desde el body o script).

- se crea una variable canvas por medio del indentificador de la etiqueta
-se verifica si la variable se creo correctamente
-en realidad se trabaja con el **contexto** de canvas 2d. se crea una variable **ctx** con la cual se manipula el canvas.
- se verifica que el contexto se haya creado de manera exitosa, dando la bienvenida por medio de un alert(), o advirtiendo un error 