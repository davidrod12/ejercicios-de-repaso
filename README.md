====================================================
       PORTAFOLIO PERSONAL - OSCAR DAVID
====================================================

DESCRIPCIÓN
----------------------------------------------------

Este proyecto corresponde a una actividad práctica
de desarrollo web utilizando HTML5 y CSS3.

La página creada es un portafolio personal de un
estudiante de Desarrollo de Software.


OBJETIVO DEL PROYECTO
----------------------------------------------------

Crear una página web utilizando correctamente:

- HTML5 semántico.
- CSS3.
- Box Model.
- Flexbox.
- CSS Grid.
- Diseño Responsive.


ESTRUCTURA DEL PROYECTO
----------------------------------------------------

portfolio/
│
├── index.html
├── style.css
└── README.txt


ARCHIVO index.html
----------------------------------------------------

Contiene la estructura y el contenido de la página.

Se utilizaron elementos semánticos de HTML5 como:

<header>
<nav>
<main>
<section>
<article>
<footer>

La página contiene las siguientes secciones:

1. Inicio
2. Sobre mí
3. Habilidades
4. Proyectos
5. Contacto


ARCHIVO style.css
----------------------------------------------------

Contiene todos los estilos visuales de la página.

Se aplicaron diferentes conceptos de CSS3.


BOX MODEL
----------------------------------------------------

El Box Model se utiliza mediante:

- margin
- padding
- border
- width
- height
- box-sizing

Ejemplo:

.card {
    padding: 28px;
    border: 1px solid #e1e7ee;
    border-radius: 14px;
}


FLEXBOX
----------------------------------------------------

Se utilizó Flexbox para organizar diferentes
elementos de la página.

Ejemplos:

- Menú de navegación.
- Botones.
- Tarjetas.
- Footer.
- Sección de contacto.

Ejemplo:

display: flex;

justify-content: space-between;

align-items: center;


CSS GRID
----------------------------------------------------

Se utilizó CSS Grid para crear diferentes
distribuciones de contenido.

Ejemplos:

- Sección principal.
- Habilidades.
- Proyectos.

Ejemplo:

display: grid;

grid-template-columns: repeat(3, 1fr);


DISEÑO RESPONSIVE
----------------------------------------------------

La página está diseñada para adaptarse a diferentes
tamaños de pantalla:

- Computadores.
- Tablets.
- Celulares.

Se utilizaron Media Queries.

Ejemplo:

@media (max-width: 650px) {

    .skills-grid {
        grid-template-columns: 1fr;
    }

}


CÓMO EJECUTAR EL PROYECTO
----------------------------------------------------

1. Abrir Visual Studio Code.

2. Crear o abrir la carpeta "portfolio".

3. Colocar dentro los siguientes archivos:

   index.html
   style.css
   README.txt

4. Abrir el archivo index.html.

5. Ejecutarlo utilizando un navegador web.

También se puede utilizar la extensión
"Live Server" de Visual Studio Code.


TECNOLOGÍAS UTILIZADAS
----------------------------------------------------

HTML5
CSS3
Flexbox
CSS Grid
Responsive Design


AUTOR
----------------------------------------------------

Oscar David

Proyecto académico - Desarrollo de Software

Año: 2026# ejercicios-de-repaso