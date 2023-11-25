# Bootstrap

Descripción sobre las funcionalidades de Bootstrap 5

## Bootstrap

Framework CSS usado para desarrollar sitios adaptables (responsivos).

Un framework css es un conjunto de clases que nos permiten personalizar los estilos a los elementos en el archivo html de nuestro sitio web.

Adaptable (responsive): Se adapta a distintos dispositivos en base a su tamano y orientación (en desarrollo web). 

## Tres pilares que nos brinda Bootstrap

1- Grid: Permite definir como se estructuran y adaptan los elementos dependiendo a los dispositivos.

2- Componentes: Ejemplo de los componentes son el carrusel

3- Iconos: disernos utilizables para mejorar visiblemente tu sitio web.

## La Grid (Cuadrícula).

Es un conjunto de contenedores, filas y columnas que definen cómo se va a presentar y a `alinear` el contenido.

`Filas`: Cada fila esta dividida en 12 columnas.

### Clases especificas para la grid

- `.row`: Fila, indicamos que el elemento html se convierte en fila para bootstrap
- `.col-`: columna, col-(# columnas).
- `.col-sm-`: columna, col-(small) pequeno `Dimensiones:(>=576px)`
- `.col-md-`:columna, col-(mediano) `Dimensiones:(>=768px)`
- `.col-lg-`:columna, col-(large) `Dimensiones:(>=992px)`
- `.col-xs`:columna (extra-small) dispositivo muy pequeno `Dimensiones:(<576px)`  
- `xl` `Dimensiones:(>=1200px)`
- `xxl` `Dimensiones:(>=1400px)`

El ancho de la página web es el viewport.

## BreackPoints en Bootstrap

Dimensión (ancho) a partir de la cual podemos cambiar el estilo o la estructura de la página web

-Punto de quiebre que hace que el estilo se actualice.

-Bootstrap tiene breackpoints estructurados/ creados

Clases que pertenece el breackPoint

`xs` solo se utiliza col.
para los demas es col-(dimensión)

### Estructura de la Grid

Un `Contenedor` puede contener filas y cada fila contiene 12 columnas.

-Los elementos de una fila pueden ocupar varias columnas.  

## Contenedor en Boostrap
Elemento html que contiene todas las estructuras o elementos html, existen dos contenedores

`.container`: Crea un contenedor responsivo con un ancho maximo fijo que depende del tamano del dispositivo.


`.container-fluid`: Crea un contenedor responsivo, se estira para llenar el 100% del ancho de la pantalla.

 ### Contenedores Responsivos

 `.container-sm`:   
 `.container-md`:
 `.container-lg`:
 `.container-xl`:
 `.container-xxl`:

 ## Componentes de Bootstrap

 `Elemento html reutilizable` que ya viene con estilo predeterminado y que podemos utilizar en el sitio web.

## Iconos

Son figuras con nitides que se pueden utilizar desde `bootstrap icons`, la cual es una bilbioteca de iconos svg (gráficos que no se distorcional por el tamano).

`CDN` (Content Delivery Network).


## Flexbox

Permite que los elementos responsivos ubicados dentro de un contenedor se distribuyan automáticamente en base al tamano del dispositivo.

Bootstrap incluye clases predeterminadas que permiten trabajar con flexbox determinadamente.

Contenedor: se le llama contenedor Flex.

se le agrega la la clase `d-flex`

## Modelo y estructura de flexbox

`flex-direction`: Establece el eje principal del contenedor, puede tener los valores: row, row-reverse, colum, colum-reverse.

`justify-content`: Define cómo se distribuyen los elementos en el eje principal. Las alternativas pueden ser: flex-start, flex-end, center, space-between, space-around, space-evenly.

Ejemplo de clases predeterminadas de bootstrap:
`.justify-content-start`
`.justify-content-end`
`.justify-content-center`
`.justify-content-between`
`.justify-content-around`
`.justify-content-evenly`


`align-items`: propiedad que define los elementos en el `eje perpendicular` (ubicado a 90 grados del eje principal), si estamos en el eje vertical sera el eje horizintal

pueden ser: `flex-start`, `flex-end`, `center`, `baseline`, `strech`(estirar).


Ejemplo de clases predeterminadas de bootstrap:

`.align-items-start`
`.align-items-end`
`.align-items-center`
`.align-items-baseline`
`.align-items-strech`

## Flex-wrap

Determina si los elementos deben ser ajustados para que siempre estén en una misma línea o si se les permite distribuirse en varias líneas si es necesario.

`flex-wrap: no-wrap`: por defecto se asigna el valor wrap. nowrap ajusta los elementos en una misma linea