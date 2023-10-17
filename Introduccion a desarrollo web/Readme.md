# INTRODUCCION A DESARROLLO WEB

## Introducción a HTML
[X] ¿Que es HTML?
[x] Etiquetas
[x] Encabezados y comentarios
[x] Lista de elementos -> <ol> (ordered list) -  <li> (list item) y <ul> (unordered lists) - <li> (list item)
[x] Ejercicio CV
[x] Imagenes y enlaces -> en <a> target="_blank se usa para aprir el enlace en otra pestaña.
[x] Tablas
[x] Optimizacion de imagenes:
   -  Imagenes:
      -  [https://tinypng.com/](TinyPNG): permit optimizar imagenes.
      -  [kraken.io](kraken.io)
      -  [remove.bg](remove.bg): eliminar fondo.
   - Atajos de teclado:
     - alt + click: coloca el cursor en varias lineas y permite editar en simultaneo.
     - shift + alt + |v : crea copias de una o  mas lineas de mandera simultanea, cortar y pegar en silmultaneo.
     - alt + |v o |^ : desplazar hacia arriba o hacia abajp una o mas lineas. 

## Introducción a CSS
CSS -> CascadingStyleSheets

[x]Selectores
   - Etiquetas: cuando se quiere cambiar todas las etiquetas de ese tipo.
   - . : cuando se quiere cambiar algunos elementos, en class.
   - #: como identificador, solo queremos cambiar un unico elemento.
   - *: es un selector CSS universal que aplica a todas las etiquetas.
[x] Modelos de caja
  - padding: es como un relleno interno, es siempre trasnparente.
  - border: todolos contenidos son como cajas
  - margin: asigna al lado derecho, inferior e izquierdo, un espaciado externo.
  - Modelo en cascada: si hay varias propiedades css a una etiqueta, prevalece la ultima regla.
[x] Colores
  - Hay 17 colores básicos definidos como palabras clave y 147 colores extendidos. Fuente: [https://www.w3.org/TR/css-color-3/](CSS color)
  - RGB significa red, green and blue,osea rojo, verde y azul, toman valores de 0 a 255.
  - RGB porcentual, similar al RGB pero en porcentaje del 0% al 100%(255).
  - RGB hexadecimal, se puede convertir a un valor hexadecimal.
[x] Tipografia
  - Se puede cambiar la tipografia, usando la propiedad **font-family**.
  - Unidades y tamaño usando **font-size**.
[x] Problemas con px
  - em y rem
    - em:La unidad “em” no siempre mide lo mismo, ya que su tamaño depende del tamaño del elemento padre. Por lo tanto, se trata de una unidad relativa. **Nota: 1em base mide 16px**
    - rem:La unidad rem(rootem) es relativa solo al tamaño del elemento raíz del elemento HTML tiene un tamaño de fuente de 16px(como es por defecto)entonces **1rem sería igual a 16px** sin importar el tamaño del elemento padre.
[x] Grosor y cursiva
  - font-weight: grosor de la letra.
  - font-style: estilo de la letra.
[x] Fondo
  - background-color: color de fondo.
  - background-image: imagen de fondo.
  - background-position: posicion del elemento de fondo.
  - background-repeat: indica si la imagen se repite o no.
  - background-size: tamaño de la imagen de fondo.
[x] Alineacion del texto
  - text-align: alineacion del texto.