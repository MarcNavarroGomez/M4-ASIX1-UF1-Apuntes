# M4-ASIX1-UF1-Apuntes
Apuntes para la UF1 de M4
## Que es GITHUB?
GitHub constituye una aplicación en línea de carácter gratuito destinada a la creación de repositorios compartibles con diversas personas. Además, los proyectos quedan almacenados en la nube, garantizando así la preservación integral de la información.

Creación de un Repositorio
Al acceder a GitHub para establecer un nuevo repositorio, el primer paso consiste en asignar un nombre y, opcionalmente, proporcionar una breve descripción de la información contenida en el repositorio. La configuración de acceso se establece como pública para permitir la visualización por parte de otros usuarios, siendo crucial incluir el archivo README para brindar contexto y subir información relevante al repositorio.

Para disponer del repositorio en la unidad local (por ejemplo, disco C), se copia el enlace correspondiente y se abre una terminal desde el directorio local. El proceso implica clonar el repositorio mediante el comando en la terminal: "git clone "Enlace del repositorio". La creación del repositorio genera una carpeta local que puede ser editada utilizando un entorno visual.

Cuando se desea guardar la información editada en el repositorio de GitHub, se siguen una serie de comandos:

Iniciamos el repositorio local: (git init)
Añadimos todos los archivos al repositorio: (git add .) (el "." indica la inclusión de todos los archivos de la carpeta en la operación de carga a GitHub)
Realizamos un commit con un mensaje descriptivo, como por ejemplo: (git commit -m "Actualización")
Finalmente, subimos los cambios al repositorio principal: (git push origin main).

## Primer capítulo: MARKDOWN
Texto de prueba

Este texto esta en *cursiva*
Este texto esta en _cursiva_
Este texto esta en **negrita**
Este texto esta en __negrita__

Este texto esta en **_negrita y cursiva_**

1. Primera opción de menú
2. Segunda opción de menú
3. Tercera opción de menú 

* Primera opción de lista desordenada
* Segunda opción de lista desordenada
- Tercera opción de lista desordenada
    1. Primer Submenu
    2. Segundo Submenu
- Cuarta opción de lista desordenada
    * Primer Submenu
    * Segundo Submenu
+ Quinta opción de lista desordenada
+ Sexta opción de lista desordenada

```
<html>
    <head>
    </head>
    <body>
        <p>Esto es un párrafo</p>
    <body>
</html>
```
[Esto es un enlace](http://joan23.fje.edu "Enlace a la web del cole")

![Esto es una imagen en negro](https://github.com/MarcNavarroGomez/ASIX1-M4-UF1-A3Apuntes/blob/main/foto.jpg "Titulo opcional de la imagen")
|Primera Col.|Segunda Columna.|3 Col|
|----------------|:---------------:|-----------:|
Col 2 es|Centrada|35€|
Col 3 es |Derecha|134€|
|Estilo Cebra|Gris|Blanco|
|Clase|ASIX1|M4|

-[ ] Opción 1
-[X] Opción 2
-[ ] Opción 3 


<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
</head>
<body>

    06/10/2023

    <p> apertura
    </p> cierre
    <img> inserta imagen
    </br> negrita
    <Head> es la parte no visible por los visitantes, todo lo que es palabras clave
    <title ASIX1-PRUEBAdeTEXTO></title>
<h1>Título Principal</h1>
<h3>Primera Sección</h3>
<body>
<p>
        Lorem ipsum dolor sit amet,
         consectetur adipiscing elit. Vivamus rhoncus, neque sed tincidunt rhoncus,
         ligula lorem luctus nulla, ultricies ullamcorper ligula lectus sit amet orci. Phasellus pretium, 
         ligula ac accumsan pulvinar, metus sapien vestibulum massa, ut fringilla nulla mi a orci. 
         Aenean tristique commodo rhoncus. Praesent sed commodo ex. Fusce pharetra sit amet lacus vitae suscipit.
          Donec pulvinar urna at nunc dapibus tempus.
        </p>   
        <p>Sed convallis iaculis laoreet. Vestibulum scelerisque 
          molestie molestie. Curabitur fringilla lorem id vulputate viverra. Proin vulputate,
         sem at vestibulum malesuada, arcu nisl congue magna, in accumsan tortor massa ut mauris
        </p>
 </body>
      
 1. Primer elemento de nvl 1
  - Primer elemento de nivel 2
  - Segundo elemento de nivel 2
  - Tercer elemento de nivel 2
2. Segundo elemento de nvl 1
  1. Primer elemnto de nivel 2
  2. Segundo elemento de nivel 2
  3. Tercer elemento de nivel 2
3. Tercer elemento de nvl 1

<br/>
Ejemplo de enlaces
<hr/>
<a href="http://www.google.com"

<script src="https://kit.fontawesome.com/579bb334a0.js" crossorigin="anonymous"></script>

## Segundo Capitulo: HTML
HTML es el código que se utiliza para estructurar y desplegar una página web.
Para crear una página con HTML se debe tener esta estructura: un head y un body.
Escribiremos hmtl:5 y nos dara la estructura para inicar nuestro html:
    <!DOCTYPE html>
    <html lang="es">
    <head>
        <meta charset="UTF-8">
        <meta name="viewport" content="width=device-width, initial-scale=1.0">
        <script src="https://kit.fontawesome.com/02d480a03b.js" crossorigin="anonymous"></script>
        <link rel="icon" href="book-solid.ico">
        <title>Document</title>
    </head>
    <body>
        <h1>Titulo principal</h1>
        <h3>Primera seccion </h3> 
        <p>Fugit quas ea deserunt voluptatum voluptas qui! Esse voluptate molestiae reprehenderit laudantium id labore corporis repellat dolores laborum.Repellendus placeat nemo ipsum?</p>
        <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. </p>
        <p>Veritatis ex asperiores corporis vel molestiae distinctio sit at sapiente rerum cupiditate reiciendis.</p>
        <p>Beatae unde placeat accusantium nisi officiis voluptatum ipsum sed.</p>
        Lorem ipsum dolor sit, amet consectetur adipisicing elit. Sit iusto earum et molestias. Tempora voluptates minus, voluptatem possimus corrupti in fugiat deleniti at voluptate quam sapiente doloremque laborum fuga ea?
        <br/> Enter/Intro

        Ejemplo de enlace
        <a href="http://www.google.com" alt ="Por aqui se va a Google" Target="_blank"> Este es el enlace a google </a>
        <blockquote>Esto es un documento que </blockquote>

    </body>
Para crear listas usaremos estos codigos:
        <ol>Es una lista ordenada
            <li>Primer elemento</li>
            <ul>
                <li>Primer elemento</li>
                <li>Segunda elemento</li>
                <li>Tercer elemento</li> 
            </ul>
            <li>Segunda elemento</li>
            <ol>
                <li>Primer elemento</li>
                <li>Segunda elemento</li>
                <li>Tercer elemento</li> 
            </ol>
            <li>Tercer elemento</li>
        </ol>

        <ul>Es una lista desordenada
            <li>Primer elemento</li>
            <li>Segunda elemento</li>
            <li>Tercer elemento</li>
        </ul>
Para insertar imagenes:

Hay dos formas de introducir imágenes, una es sola y otra con una url para que te lleve a otra página web:

Solo imagen: Ahora pasamos a insertar imágenes que tenemos guardadas en nuestro ordenador con esta etiqueta <img src="" alt="" height ="">, ponemos la ubicación de la imágen entre comillas, como dice en la guía "./", en (alt="ponemos un texto alternativo") y si queremos ajustar un tamaño a la imagen ponemos height o weight y enter comillas en tamaño a disponer.

Enlace de una página web en imagen: La etiqueta se llama a<a href="https://www.urldelaimagen.com" alt="" target="blank">, en el href entre comillas va la direción de la página web, "alt" el texto alternativo y importante para que esa dirección web se habrá en otra página web se pone (target="blank").

Para hacer tablas usaremos estos codigos:
    <table border="1">
        <thead>
            <tr
                style="color: red;text-align: center;">
                <th>Puesto</th>
                <th>Atleta</th>
                <th>Tiempo</th>
            </tr>
        </thead>
        <tbody style="background-color: blueviolet;text-align: center; color: aliceblue;">
            <tr id="primerafila">
                <td>1r</td>
                <td>Paco Martinez</td>
                <td>14:25</td>
            </tr>
            <tr class="textoazul">
                <td>2r</td>
                <td>Pau Lopez</td>
                <td>14:50</td>
            </tr>
            <tr class="textoazul">
                <td>3r</td>
                <td>Joel Gallego</td>
                <td>15:30</td>
            </tr>
        </tbody>
        <tfoot>
            <tr>
                <th>Puesto</th>
                <th>Atleta</th>
                <th>Tiempo</th>
            </tr>
        </tfoot>
    </table>
Y para centrar/mover derecha o izquiera, o simplemente enmarcar cosas, usaremos 'div' que simplemente mete todo lo que tengas dentro de: <div>aaaaaaa</div> dentro de un recuadro que e puede mover y poner estilo,  eso lo veremos ahora con...

## TERCER CAPITULO CSS
El CSS es un lenguaje de programación que se utiliza para ordenar las intrucciones referentes a la apariencia de un archivo html y presentar su contenidos de forma atractiva.

El CSS se puede poner en el head de un html o en un archivo externo y hacer un link en el html del archivo CSS. Estructura:

<link rel="stylesheet" href="./styles.css" type="text/css"/>

Un ejemplo de como alinear un div al centro:

div{
    text-align: center;
}

Para cada etiqueta le puedes meter una gran variedad de cosas para darle estilo a tu pagina html.


## CUARTO CAPITULO: DISEÑO RESPONSIVE

La adaptación de diseño es una estrategia empleada en el diseño web que posibilita que un sitio web ajuste automáticamente su presentación al tamaño y resolución de la pantalla del dispositivo desde el cual se está visualizando. De esta manera, la página web se exhibe de manera nítida, legible y de fácil navegación.

El diseño adaptable utiliza CSS y HTML para modificar, ocultar, reducir o ampliar elementos HTML, asegurando su adaptabilidad a diversas pantallas de dispositivos.

Directrices para el Diseño de Páginas Web Adaptables:

En su mayoría, el diseño adaptable se implementa con etiquetas como div, también susceptibles de ser section o article.

El primer comando destacado es fundamental, ya que incide en la estructuración y construcción de bloques: el display.


h1 {
    display: flex;
}
Otro comando relevante es float, el cual sitúa elementos en el lado izquierdo o derecho de su contenedor, permitiendo que el texto y los elementos en línea se ajusten a su alrededor.


#left {
    float: left;
}
Asimismo, box-sizing se utiliza para recalcular las dimensiones del borde y el padding en relación con el tamaño de la información.


* {
    box-sizing: border-box;     
    font-weight: 600;
    font-style: normal;
}
Propiedades de Alineación:

Existen varios comandos para alinear elementos en una página web, destacando align-items, que controla la alineación de todos los elementos.


h2 {
    align-items: left;
}
Pasamos a la sección de flex-direction, indicando que el eje principal se orienta a lo largo de una fila horizontal, y la alineación del eje transversal desplaza los elementos hacia arriba o hacia abajo.


.ejemplo {
  display: flex;
  flex-direction: column;
  align-items: flex-start;
  width: 500px;
}
Otro comando relevante es justify-content, utilizado para justificar el contenido en una página web. Similar a lo anterior, pero con justify-content, se determina cómo el navegador distribuye el espacio entre y alrededor de los elementos a lo largo del eje principal de un contenedor flexible o el eje en línea de un contenedor de cuadrícula. Además, ofrece opciones como:


.box {
    justify-content: start;
}
"Start" se emplea para alinear los elementos justo al borde inicial del contenedor en el eje principal. Además, se puede sustituir "start" por otras opciones como "end", que alinea los elementos al borde final del contenedor, entre otras.

Uso de Imágenes:

Para que una imagen sea adaptable, se le pueden aplicar diversos formatos y estilos. Se asigna un valor a la propiedad de anchura, y la altura se ajusta automáticamente. Es crucial utilizar unidades relativas, como porcentaje, en lugar de absolutas, como píxeles.


header {
    height: 100vh;
    background-image: url(../img/brandon-burridge-4o7f9_Z73a4-unsplash.jpg);
    background-size: cover;
    background-position: center;
    background-attachment: fixed;
}
En esta sección, se destacan elementos esenciales para la implementación de imágenes. La propiedad background-image: url(./xxxx/xxxxx.png) establece una o más imágenes de fondo en un elemento, como en el fondo de la página, con la ubicación de la imagen proporcionada en la URL. La propiedad background-size: cover permite que la imagen se ajuste al espacio disponible, escalándola al tamaño más pequeño posible para llenar el contenedor sin dejar espacios vacíos. Además, background-position: center establece la posición relativa al centro del contenedor o de la página, y background-attachment: fixed fija la posición de una imagen de fondo en relación con la página web, incluso si hay desplazamiento, manteniendo el fondo estático.

Media Queries:

Las consultas de medios (Media queries) posibilitan la aplicación de estilos CSS según el tipo general de un dispositivo, basándose en factores como el tamaño de pantalla, la resolución o el ancho del viewport del navegador. Se ilustra con el siguiente ejemplo:


@media only screen and (max-width: 700px) {
    /* REGLAS */
    .column-3 {
        width: 100%;
    }
    .column-4 {
        width: 50%;
    }
}
