# CURSO_DESARROLLO_WEB_2018
Notas del Curso Platzi  Agosto 2018
> Fecha : 2018-08-16  
> Autor : Johan Ramirez

### HTML y su Estructura
```html
<html>
    <head>
        <title> </title>
    </head>
    <body>
        <h1> </h1>
        <h5>
            <a> </a>
        </h5>
    </body>
</html>
```

### Etiquetas, Atributos y Valores
Existes dos clases de elementos HTML.

1. Elementos de línea:
Un elemento de línea solo ocupa el espacio necesario para envolver a su contenido.  
```html 
<!-- Elemento de línea -->
`<a href="soy_enlace">`Texto que es un enlace</a>
```
2. Elementos de bloque:
Un elemento de bloque utiliza todo el espacio horizontal, aunque su contenido no lo     ocupe del todo.
```html
<!-- Elemento de bloque -->
<div>Soy una caja sin valor semántico</div>
```
Comando para abrir las herramientas de desarrollador en Google  Chrome:   
`Ctrl + Shift + I`

### Definiendo la Estructura del Sitio Web

`<html> </html>`Es la etiqueta raíz y en ella van ir sus ramas head y body.  
`<head> </head>` Representa una colección de metadatos acerca del documento, incluyendo enlaces a, o definiciones de, scripts y hojas de estilo.  
`<meta charset=“utf-8” />` Es etiqueta no habilita las tildes y símbolos del español. Esta etiqueta no se cierra como las otras, pero como dice Freddy “para los purista del cogido” agregan un / al final.
`<title> <title>` En ella se coloca el texto que aparecerá en nuestra pestaña del navegador.  
`<body> </body>` En esta etiqueta va nuestro contenido de la pagina.  

Dentro de nuestro header en este body tenemos las siguientes etiquetas:
`<header></header>` Aquí definimos el contenido de la cabecera de nuestra pagina.  
`<figure> </figure>` Esta etiqueta nos permite `tener agrupados nuestra imágenes, este caso la que utilizaremos en el header.  
`<img />` representa una imagen.  
<nav> </nav> Define una sección que solamente contiene enlaces de navegación (Ya que en nuestro header solo hay enlaces que nos llevaran a otra sección).
<ul> </ul> Esta etiqueta es para una lista desordenada.
<ol> </ol> Esta etiqueta es para una lista ordenada.
<li> </li> Esta etiqueta es para definir cada elemento de la lista.
<a> </a> Esta etiqueta va enlace a otro recurso.
<section> </section> Nos sirve para definir las secciones de nuestro documento.
<h1> </h1> Son los títulos que lleva nuestro documento. Hay seis niveles el h1 es el de mayor importancia y solo debe haber uno por documento, muy importante para los buscadores.
<article> </article> Lo utilizamos para elementos que se repiten como noticias, entrdas de blog etc.

Recuerden que podemos agregar comentarios con `<!-- “Mensaje” -->`

### Formas de los Estilo
Tenemos 3 formas de agregar los estilos : 

* __En Linea:__  Tenemos que agregar el estilo a cada etiqueta
Pero esto hace que nuestro archivo quede muy difícil de leer

* __Etiqueta:__ Creamos una etiqueta `<style>` que va dentro de nuestra etiqueta `<head>`
Hace el archivo muy extenso y complicado de leer a la hora de editarlo
Pero facilita la carga a la hora de pedir el archivo al servidor, logrando que cargue mas rápido.  

*__Archivo Externo:__ Creamos un archivo externo de tipo .css y lo enlazamos a nuestro html con la etiqueta
```<link rel=“stylesheet” href=“nombre-del-archivo.css” />```  
Tarda un poco mas en carga a la hora de pedirlo al servidor
Pero es mas fácil de leer a la hora de editarlo.
