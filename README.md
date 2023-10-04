# HTML Style Guide 
Realiza las siguientes actividades y sube los cambios a tu repositorio.

## **1. Lee la guía de estilos para HTML propuesta por Google**
Lee los puntos 2 y 3 de la [guía de estilos de HTML propuesta por Google](https://google.github.io/styleguide/htmlcssguide.html#HTML).

Aquí te dejo algunos puntos a destacar:

* No usar tabulador, sino 2 espacios (en Python, por ejemplo,  son 4 espacios).
* Usar siempre minúscula.
* Elimina los espacios en blanco innecesario, sobre todo al final de las líneas.
* Usa UTF-8 (no BOM).
* Usa comentarios cuando sean necesarios (sin excederse).
* Incluye TODO con aquello que está pendiente de realizar.
* Usa los tags de HTML para lo que realmente son.
* Omite type para la carga de CSS y Javascript, salvo que sea necesario.
* Usa una línea nueva para cada bloque y utiliza la indentación.
* Es preferible usar comillas dobles a las simples cuando hay que incluir valores en las propiedades en HTML, pero usa comillas simples cuando uses CSS.

## **2. Detecta y corrige los errores de estilo en el código HTML del fichero index.html**

**A.  Declara siempre el tipo de documento**
* Usa siempre la declaración del tipo de documento en la primer línea. 

**B. Usa minúsculas para el nombre de los elementos**
* HTML permite mezclar mayúsculas y minúsulas pero no ayuda a la legibildad. 

**C. Cierra todos los elementos HTML**
* En HTML, no tienes porque cerrar todos los elementos (por ejemplo <p\>), aunque se recomienda encarecidamente.

**D. Usa nombre de atributos en minúsculas**
* Aunque HTML permite mayúsculas y minúsculas para los nombre de los atributos la legibilidad del código es mejor y además es más fácil escribir todo en minúsculas.

**E. Incluye siempre comillas dobles para los valores de los atributos**
* Aunque HTML permite incluir atributos sin comillas, se recomienda para mejorar la legibilidad y además para  los casos en que el valor del atributo contiene espacios. 

**F. Especifica siempre los atributos alt, width, y height para las imágenes.**
* El atributo alt es importante si la imagen por alguna razón no pudiera visualizarse. 
* Al indicar los atributos de height y width reducen el efecto de parpadeo al cargar la página ya que el navegador puede reservar el espacio para la carga de la imagen antes.

**G. No incluyas espacios alrededor del signo =.**
* HTML permite espacios alrededor del signo igual. Pero sin espacios es más fácil leer y agrupar entidades mejor. 

**H. Evita líneas de códigos muy largas**
* Cuando se usa un editor HTML, no es conveniente hacer scroll horizontal para poder leer el código HTML.

**I. Limita la indentación y líneas**
* No añadas líneas en blanco, espacios o indentación sin razón.

## **3. Detecta y corrige los errores de estilo en el código HTML del fichero contact.html**

**A. La etiqueta <title\> es requerida en HTML.**
* Indica el título de la página en el navegador.
* El valor del título es unas para el SEO (optimización del motor de búsqueda).
* Trata de definir un título lo más breve y significativo posible.

**B. No omitir las etiquetas <html\> <head\> o <body\>.**
* Aunque pueden ser renderizadas páginas sin estas etiquetas por los navegadores, pueden dar problemas si no se incluye.

**C. Cierra las etiquetas vacías.**
* En HTML es opcional cerrar las etiquetas vacías, no obstante son obligatorias en XML/XHTML, por lo tanto es aconsejable cerrarlas en caso de que algún software XML/XHTML use la página.

**D. Añade el atributo lang**
* Incluye siempre el atributo del lenguaje dentro de la etiqueta <html\> para declarar el lenguaje de la página ya que ayudará a los motores de búsqueda y navegadores.

**E. Incluye la etiqueta de metadatos para declarar la codificación de la página**
* Usa la etiqueta meta y su atributo charset.
* Debe ser declarado lo más pronto posible.

**F. Configura el Viewport**
* El viewport es el área visible de una página web.
* Esta área varía según el dispositivo.
* Se debe incluir la siguiente etiqueta de metadatos:
```
<meta name="viewport" content="width=device-width, initial-scale=1.0">
```
* De este modo se proporciona instrucciones de cómo controlar y escalar las dimensiones de la página.
* El atributo width=device-width dependerá de la anchura del dispositivo.
* La escala inicial establece el nivel de zoom cuando la página es cargada por el navegador.

**G. Comentarios en HTML**
* Escribe los comentarios cortos en una línea así:
```
<!-- Esto es un comentario corto -->
```
* Escribe los comentarios de más de una línea así:
```
<!--
  Esto es un ejemplo de un comentario largo que ocupa más de una línea y que
  debe escribirse así.
-->
```

**H. No incluyas el atributo type para incluir hojas de estilo o Javascript.**
* Solo si se va a usar otro tipo de código si es necesario, por defecto HTML5 ya toma los valores de CSS y Javascript por defecto.

**I. Usa minúsculas para los nombres de ficheros.**
* Algunos servidores son sensibles al uso de mayúsculas, por ello evita posibles problemas y manten todos los nombres de ficheros en minúsculas.

**J. Extensiones de ficheros.**
* Tus ficheros HTML deberán tener las extensiones .html o .html, ambas son permitidas.

## **4. Valida el código de ambas páginas.**
* Haz uso del validador de la W3C https://validator.w3.org/.
* ¿Hay algún error o "warning" detectado en alguna de las páginas que ya has corregido?
* Corrígelos y vuelve a validarlo.

## **Referencias:**

- [Guía de estilos de HTML propuesta por Google](https://google.github.io/styleguide/htmlcssguide.html#HTML) 

- [W3schools - HTML Style Guide and Coding Conventions](https://www.w3schools.com/html/html5_syntax.asp)
