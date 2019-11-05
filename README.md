		[Ejercicio de Evaluación final]


## HTML
Código estructurado e identado utilizando etiquetas semánticas según corresponde.

## Imágenes e iconos
Se encuentran en una carpeta específica dentro de **_src/assets** y se generan en la raíz de las carpetas **public/**.

## CSS
Se han añadido estilos css mediante el uso de **scss**. Para ello se ha dividido en parciales siguiendo el código. Además, se ha hecho uso de variables y anidaciones para los estilos.
Estos aplican a distintos tamaños y dispositivos, de modo que hay ligeras variaciones de unos a otros.

## Animaciones
Con el objetivo de hacer la web más dinámica a nivel visual, se han introducido transiciones y animaciones en los botones.

## Estructura
La estructura de carpetas que se ha seguido para trabajar es la siguiente:

|
`- _src
   |- assets
   |  |- icons
   |  |- images
   |  |- js
   |  `- scss--> **main.scss**
   |     |
   |     |- core--> _variables.scss
   |     |
   |	 |- layout
   |	 |	|--> _base.scss
   |     |      |--> _hero.scss
   |     |      |--> _header.scss
   |     |      |--> _firstSection.scss
   |     |      |--> _secondSection.scss
   |     |	`--> _footer.scss
   |     |
   |     |
   |     `- vendors--> _normalize.scss
   |	
   `- templates-->**index.html**

