# Introducción

En este curso de HTML, exploraremos todos los aspectos esenciales para comenzar a crear nuestras propias páginas web desde cero.

En este curso **no solo se trata solo de escribir código**; se trata de escribirlo de la **manera correcta**. Aprenderemos [buenas prácticas](#buenas-prácticas) y metodologías para asegurarnos de que nuestro código sea **limpio, profesional y altamente legible**. La calidad del código es fundamental para el mantenimiento a largo plazo y para colaborar con otros desarrolladores en proyectos web.

Juntos, exploraremos cómo crear páginas web con una estructura lógica y semántica, lo que significa que nuestras páginas no solo se verán bien, sino que también estarán diseñadas de manera que los motores de búsqueda y las tecnologías de asistencia, como los lectores de pantalla, puedan interpretarlas de manera efectiva. Esto es esencial para garantizar que nuestros sitios web sean accesibles para una amplia audiencia.

Prepárate para embarcarte en un emocionante viaje de aprendizaje en el mundo del desarrollo web. Comenzaremos desde lo más básico, y a medida que avancemos en el curso, te introduciré a conceptos más avanzados. Al final de este curso, estarás listo para crear tus propias páginas web y comprender los fundamentos necesarios para seguir aprendiendo y creciendo como desarrollador web.

¡Vamos a comenzar a explorar el emocionante mundo de HTML juntos!

---

# Contenido

-   [¿Qué es HTML?](#¿qué-es-html-🤔)
-   [¿Qué no es HTML?](#¿qué-no-es-html-❌)
-   [Recomendaciones](#recomendaciones)
-   [Fundamentos de HTML](#fundamentos-de-html)
-   [Estructura básica](#estructura-básica)
-   [Etiquetas comunes](#etiquetas-comunes)
-   [Tablas](#tablas)
-   [Formularios](#formularios)
-   [Buenas prácticas](#buenas-prácticas)
-   [Fuentes y apoyo](#fuentes-y-apoyo)

---

# ¿Qué es HTML? 🤔

La **World Wide Web**, comúnmente conocida como la web, es uno de los avances más significativos en la historia de la tecnología de la información. Se ha convertido en un medio de comunicación global que permite a las personas acceder a una inmensa cantidad de información, interactuar en línea y compartir recursos en todo el mundo. La web es una red de documentos interconectados que se presentan en forma de páginas web y se pueden acceder a través de navegadores web, como Google Chrome, Mozilla Firefox o Microsoft Edge.

La base fundamental de la web es el **lenguaje de marcado** llamado HTML, siglas que significan "**Hypertext Markup Language**" en inglés, o "**Lenguaje de Marcado de Hipertexto**" en español. HTML es el lenguaje estándar utilizado para crear páginas web y definir su estructura y contenido. Fue desarrollado por Tim Berners-Lee en 1990 como parte del proyecto para crear la World Wide Web en el CERN (Organización Europea para la Investigación Nuclear). Desde entonces, ha evolucionado a través de varias versiones, y HTML5 es la versión más reciente, que ofrece una amplia gama de características y capacidades para la creación de contenido web.

> Básicamente, con HTML definimos la estructura y el contenido de nuestra página web

<p align="center" style="margin: 35px;" width="100%">
    <img width="15%" src="https://th.bing.com/th/id/R.339598c0752c3a7dfeaf4c96ac30c94d?rik=vfz9QSLVdZBcZw&riu=http%3a%2f%2flogos-download.com%2fwp-content%2fuploads%2f2017%2f07%2fHTML5_logo.png&ehk=7%2fEaxlDKEk6GHxynn9uBS5GrBqhTyhGdgeeN2EhmyoE%3d&risl=&pid=ImgRaw&r=0"> 
</p>

---

# ¿Qué no es HTML? ❌

Es importante entender las limitaciones y responsabilidades de HTML para trabajar de manera efectiva en el desarrollo web y para saber cuándo utilizar otros lenguajes y tecnologías complementarias, como CSS y JavaScript, para lograr funcionalidad y diseño más avanzados.

Es importante recalcar que _HTML no es un lenguaje de programación_.

| ✅ Responsabilidades de HTML                                                                                      | ❌ No es responsabilidad de HTML                                                  |
| ----------------------------------------------------------------------------------------------------------------- | --------------------------------------------------------------------------------- |
| Define la estructura básica de una página web.                                                                    | No controla el diseño visual o la presentación exacta. De eso se encarga CSS      |
| Proporciona la semántica de la página web, como títulos, encabezados y párrafos.                                  | No gestiona la interactividad avanzada de la página. De eso se encarga JavaScript |
| Permite la creación de enlaces y navegación mediante hipervínculos.                                               | No almacena datos o realiza procesamiento de formularios.                         |
| Facilita la incorporación de contenido multimedia, como imágenes y videos.                                        | No se encarga de la seguridad o la autenticación de usuarios.                     |
| Permite la creación de formularios para la recopilación de datos.                                                 | No maneja la lógica de negocios en aplicaciones web.                              |
| Es compatible con todos los navegadores y dispositivos.                                                           | No controla el diseño de impresión o la generación de documentos PDF.             |
| Ayuda en la accesibilidad web al proporcionar etiquetas semánticas para lectores de pantalla.                     | No realiza cálculos matemáticos ni procesamiento de datos en tiempo real.         |
| Define la estructura de datos tabulares utilizando tablas HTML.                                                   | No define el estilo visual, que es responsabilidad de CSS.                        |
| Es un lenguaje estático y no permite la creación de aplicaciones web interactivas por sí mismo.                   | No almacena ni recupera datos de una base de datos.                               |
| Es la base para el desarrollo web y se combina con CSS y JavaScript para lograr funcionalidad y diseño avanzados. | No controla la velocidad de carga de una página, que depende de varios factores.  |

---

## Analogía

-   HTML es como la estructura de una casa: define las paredes y habitaciones.
-   CSS es como la decoración y el diseño de la casa: colores, muebles y estilo.
-   JavaScript es como la funcionalidad de la casa: interruptores, calefacción y entretenimiento.

<p align="center" style="margin: 50px;" width="100%">
    <img width="30%" src="https://th.bing.com/th/id/OIG.cyN1N4ra9FQqg0WXMxWR?pid=ImgGn&w=1024&h=1024&rs=1"> 
</p>

---

# Recomendaciones

-   Editor de código ([Visual Studio Code](https://code.visualstudio.com/))
-   Visualizador de nuestra página ([Live Server](https://marketplace.visualstudio.com/items?itemName=ritwickdey.LiveServer&WT.mc_id=academic-77807-sagibbon))
-   Extensiones
    -   [Prettier - Code formatter](https://marketplace.visualstudio.com/items?itemName=esbenp.prettier-vscode)
    -   [HTML Snippets](https://marketplace.visualstudio.com/items?itemName=abusaidm.html-snippets)

---

# Fundamentos de HTML

## Elementos y etiquetas

-   **Elementos y Etiquetas:** En HTML, los elementos son los bloques de construcción básicos de una página web. Cada elemento se define mediante etiquetas, que son palabras clave rodeadas por signos de menor que (`<`) y mayor que (`>`). Por ejemplo, `<h1>` define un encabezado de nivel 1 y `<p>` define un párrafo.

```html
<h1>Hola, mundo</h1>
```

En este caso la etiqueta es el `h1` (aquí se podría hablar de **etiqueta de abertura** y **etiqueta de cierre**) y el elemento es todo el componente general `<h1>Hola, mundo</h1>`

---

## Anidación

-   **Anidación:** Los elementos HTML pueden anidarse unos dentro de otros. Esto significa que puedes tener elementos dentro de otros elementos para crear una estructura jerárquica. Por ejemplo:
    ```html
    <div>
        <h1>Título</h1>
        <p>Este es un párrafo.</p>
    </div>
    ```

---

## Atributos

-   **Atributos:** Los elementos HTML pueden tener atributos que proporcionan información adicional sobre el elemento. Los atributos se especifican dentro de la etiqueta de apertura y generalmente tienen un nombre y un valor. Por ejemplo:
    ```html
    <img src="imagen.jpg" alt="Descripción de la imagen" class="imagen" />
    ```

---

# Estructura básica

-   **Estructura Básica:** Una estructura básica de página HTML incluye las etiquetas `<html>`, `<head>`, y `<body>`. El contenido principal de la página se coloca en el `<body>`, mientras que el encabezado y otros metadatos se colocan en el `<head>`.
    ```html
    <!DOCTYPE html>
    <html>
        <head>
            <title>Título de la Página</title>
        </head>
        <body>
            <h1>Mi Primer Página Web</h1>
            <p>¡Hola, mundo!</p>
        </body>
    </html>
    ```

---

# Etiquetas comunes

Estas son solo algunas de las etiquetas HTML más comunes y ejemplos de cómo se utilizan. HTML proporciona una amplia gama de etiquetas que permiten estructurar y dar formato a las páginas web de diversas maneras.

---

1. **`<p>` - Párrafo:**

    ```html
    <p>Este es un párrafo de ejemplo.</p>
    ```

---

2. **`<h1>`, `<h2>`, `<h3>`, ... `<h6>` - Encabezados:**

    ```html
    <h1>Encabezado de nivel 1</h1>
    <h2>Encabezado de nivel 2</h2>
    <h3>Encabezado de nivel 3</h3>
    ```

---

3. **`<a>` - Enlace (hipervínculo):**

    ```html
    <a href="https://www.ejemplo.com">Visitar el sitio web de ejemplo</a>
    ```

---

4. **`<ul>` - Lista desordenada:**

    ```html
    <ul>
        <li>Elemento 1</li>
        <li>Elemento 2</li>
    </ul>
    ```

---

5. **`<ol>` - Lista ordenada:**

    ```html
    <ol>
        <li>Primer elemento</li>
        <li>Segundo elemento</li>
    </ol>
    ```

---

6. **`<img>` - Imagen:**

    ```html
    <img src="imagen.jpg" alt="Descripción de la imagen" />
    ```

---

7. **`<table>` - Tabla:**

    ```html
    <table>
        <tr>
            <th>Nombre</th>
            <th>Edad</th>
        </tr>
        <tr>
            <td>Juan</td>
            <td>25</td>
        </tr>
    </table>
    ```

---

8. **`<form>` - Formulario:**

    ```html
    <form action="/procesar.php" method="post">
        <input type="text" name="nombre" placeholder="Nombre" />
        <input type="submit" value="Enviar" />
    </form>
    ```

---

9. **`<input>` - Elemento de entrada:**

    ```html
    <input type="text" name="usuario" placeholder="Nombre de usuario" />
    ```

---

10. **`<textarea>` - Área de texto:**

    ```html
    <textarea name="comentario" rows="4" cols="50"></textarea>
    ```

---

11. **`<select>` - Lista desplegable:**

    ```html
    <select name="pais">
        <option value="usa">Estados Unidos</option>
        <option value="es">España</option>
        <option value="mx">México</option>
    </select>
    ```

---

## Etiquetas para agrupar

Las etiquetas que existen para agrupar contenido en nuestra pagina son:

-   header (Parte superior)
-   nav (Menu de navegación)
-   footer (Parte de hasta abajo)
-   main (Contenido principal)
-   section (Secciones que **se pueden usar multples veces**)
-   article (Noticias, articulos, entrada de blog)
-   aside (Barra lateral)
-   div (Divisiones)

![center|400](https://www.w3schools.com/html/img_sem_elements.gif)

---

## Ejemplos de estructuras de sitios

-   [deadmau5](https://deadmau5.com/)
-   [TecNM | Tecnológico Nacional de México](https://www.morelia.tecnm.mx/#/)
-   [Seguridad MAFER](http://www.seguridadmafer.com.mx/)
-   [HTML HyperText Markup Language MDN](https://developer.mozilla.org/en-US/docs/Web/HTML)

---

## Header común

```HTML
<header>
    <img src="" alt="">
    <nav>
        <ul>
            <li><a href=""></a></li>
            <li><a href=""></a></li>
            <li><a href=""></a></li>
            <li><a href=""></a></li>
        </ul>
    </nav>
</header>
```

Con ayuda de nuestra extención, podemos escribir nuestro header de esta otra forma más rápida (incluye nombres de clases):

```HTML
header.header>img.header__img+nav.header__nav>ul.header__ul>li.header__li*4>a.header__a
```

---

# Tablas

En este tema, aprenderemos a crear tablas en HTML. Las tablas se utilizan para organizar datos en filas y columnas de manera estructurada. Aquí tienes los pasos clave y ejemplos de código:

---

1. **Uso de la etiqueta `<table>`:**

    Para iniciar la creación de una tabla, utilizamos la etiqueta `<table>`. Esta etiqueta define el contenedor principal de la tabla y su estructura. Aquí tienes un ejemplo simple:

    ```html
    <table>
        <!-- Contenido de la tabla se agrega aquí -->
    </table>
    ```

---

2. **Filas y celdas en una tabla:**

    Para agregar filas a la tabla, utilizamos la etiqueta `<tr>`, que representa una fila. Dentro de las filas, utilizamos las etiquetas `<td>` (celdas de datos) para mostrar los datos en las columnas. Aquí hay un ejemplo de una tabla con dos filas y tres columnas:

    ```html
    <table>
        <tr>
            <td>Fila 1, Columna 1</td>
            <td>Fila 1, Columna 2</td>
            <td>Fila 1, Columna 3</td>
        </tr>
        <tr>
            <td>Fila 2, Columna 1</td>
            <td>Fila 2, Columna 2</td>
            <td>Fila 2, Columna 3</td>
        </tr>
    </table>
    ```

---

3. **Encabezados de tabla:**

    Para agregar encabezados a la tabla, podemos usar la etiqueta `<th>` en lugar de `<td>`. Los elementos `<th>` se utilizan comúnmente para etiquetar las columnas y se pueden colocar en la primera fila o la primera columna de la tabla:

    ```html
    <table>
        <tr>
            <th>Nombre</th>
            <th>Edad</th>
        </tr>
        <tr>
            <td>Juan</td>
            <td>25</td>
        </tr>
        <tr>
            <td>María</td>
            <td>30</td>
        </tr>
    </table>
    ```

---

# Formularios

En este tema, exploraremos cómo crear formularios en HTML para recopilar información de los usuarios. Aquí están los pasos clave y ejemplos de código:

---

1. **Uso de la etiqueta `<form>`:**

    Para crear un formulario, utilizamos la etiqueta `<form>`. Esta etiqueta envuelve todos los elementos del formulario y define cómo se manejarán los datos ingresados por el usuario. Aquí tienes un ejemplo:

    ```html
    <form action="/procesar.php" method="post">
        <!-- Elementos de entrada y botones se agregan aquí -->
    </form>
    ```

---

2. **Elementos de entrada (input, textarea, select):**

    Los elementos de entrada permiten a los usuarios interactuar con el formulario. Algunos ejemplos de elementos de entrada comunes son:

    - Campo de texto (`<input type="text">`):

        ```html
        <input type="text" name="nombre" placeholder="Nombre" />
        ```

    - Área de texto (`<textarea>`):

        ```html
        <textarea name="comentario" rows="4" cols="50"></textarea>
        ```

    - Lista desplegable (`<select>`):

        ```html
        <select name="pais">
            <option value="usa">Estados Unidos</option>
            <option value="es">España</option>
            <option value="mx">México</option>
        </select>
        ```

---

3. **Botones y envío de formularios:**

    Los formularios suelen incluir botones como `<input type="submit">` para enviar el formulario y `<input type="reset">` para restablecer los valores. También puedes utilizar JavaScript para realizar validación de datos antes de enviar el formulario al servidor:

    ```html
    <input type="submit" value="Enviar" />
    <input type="reset" value="Restablecer" />
    ```

---

## Inputs

Existen varios tipos de inputs como pueden ser:

-   checkbox
-   color
-   date
-   datetime-local
-   email
-   file
-   hidden
-   image
-   month
-   number
-   password
-   radio
-   reset
-   search
-   tel
-   text
-   time
-   url
-   week

---

## Placeholder

Se pueden complementar con un placeholder para especificar que se espera escribir en ese campo.

La sintaxis es la siguiente:

```html
<input type="text" placeholder="text" />
```

---

### Submit

Este es un boton el cual realiza la acción de "enviar".

```
<button type="submit" value="submit"></button>
```

---

# Buenas prácticas

Las buenas prácticas en HTML son fundamentales para escribir código limpio, mantenible y accesible.

Principales buenas prácticas en HTML:

1. **HTML Semántico:** Utiliza etiquetas HTML semánticas para una estructura significativa y accesible.

2. **Indentación y organización:** Mantén un código bien organizado y con una buena indentación.

3. **Uso de etiquetas semánticas:** Utiliza etiquetas semánticas para definir la estructura y el significado del contenido.

4. **Uso de comentarios:** Agrega comentarios para explicar el propósito y la estructura del código.

5. **Atributos "alt" en imágenes:** Proporciona atributos "alt" en imágenes para mejorar la accesibilidad.

6. **Evita estilos en línea:** Prefiere hojas de estilo externas en lugar de estilos en línea.

7. **Validación de formularios:** Valida datos de entrada en el lado del servidor para seguridad.

8. **Evita elementos obsoletos:** No utilices elementos obsoletos en HTML.

9. **Optimización de imágenes:** Comprime y optimiza imágenes para una carga más rápida.

10. **Pruebas cruzadas de navegadores:** Asegúrate de que tu código funcione en varios navegadores.

11. **Accesibilidad web:** Cumple con las pautas de accesibilidad web como WCAG.

12. **Mantenimiento regular:** Realiza un mantenimiento periódico del código para correcciones y actualizaciones.

---

# Fuentes y apoyo

-   [HTML: HyperText Markup Language | MDN (mozilla.org)](https://developer.mozilla.org/en-US/docs/Web/HTML)
-
