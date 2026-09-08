# Etiquetas HTML
Etiqueta | ¿Para qué sirve? | Sintaxis | Ejemplo
--- | --- | --- | ---
`<article>` | Representa una composición autónoma y reutilizable, como un post de blog o noticia. | `<article>...</article>` | `<article><h2>Título</h2><p>Contenido...</p></article>`
`<section>` | Define una sección genérica dentro de un documento, agrupando contenido relacionado. | `<section>...</section>` | `<section><h2>Servicios</h2></section>`
`<aside>` | Contenido relacionado indirectamente al principal, como barras laterales o notas. | `<aside>...</aside>` | `<aside>Publicidad relacionada</aside>`
`<header>` | Agrupa contenido introductorio o de navegación de una página o sección. | `<header>...</header>` | `<header><h1>Mi Sitio</h1></header>`
`<figure>` | Contiene contenido independiente (imagen, diagrama, código) que puede llevar un título. | `<figure>...</figure>` | `<figure><img src="foto.jpg"><figcaption>Pie de foto</figcaption></figure>`
`<figcaption>` | Define el título o leyenda de un elemento `<figure>`. | `<figcaption>...</figcaption>` | `<figcaption>Descripción de la imagen</figcaption>`
`<details>` | Crea un widget desplegable que muestra u oculta información adicional. | `<details>...</details>` | `<details><summary>Ver más</summary>Texto oculto</details>`
`<summary>` | Define el título visible de un elemento `<details>`, que al hacer clic lo expande o contrae. | `<summary>...</summary>` | `<summary>Haz clic aquí</summary>`
`<dialog>` | Representa un cuadro de diálogo o ventana modal interactiva. | `<dialog open>...</dialog>` | `<dialog open>Este es un mensaje</dialog>`
`<time>` | Representa una fecha u hora específica, opcionalmente en formato legible por máquina. | `<time datetime="valor">...</time>` | `<time datetime="2026-09-08">8 de septiembre</time>`
`<mark>` | Resalta o marca texto por su relevancia en un contexto determinado. | `<mark>...</mark>` | `<p>Este es un <mark>texto resaltado</mark>.</p>`
`<blockquote>` | Define una cita extensa proveniente de otra fuente, mostrada como bloque independiente. | `<blockquote cite="url">...</blockquote>` | `<blockquote>La vida es bella.</blockquote>`
`<q>` | Indica una cita corta en línea dentro de un párrafo. | `<q>...</q>` | `<p>Como dijo Einstein: <q>La imaginación es más importante que el conocimiento</q>.</p>`
`<abbr>` | Marca una abreviatura o acrónimo, pudiendo mostrar su significado completo con `title`. | `<abbr title="significado">...</abbr>` | `<abbr title="HyperText Markup Language">HTML</abbr>`
`<code>` | Muestra un fragmento de código informático, generalmente en fuente monoespaciada. | `<code>...</code>` | `<code>console.log('Hola');</code>`
`<pre>` | Muestra texto preformateado, respetando espacios y saltos de línea tal como están escritos. | `<pre>...</pre>` | `<pre>  línea 1\n  línea 2</pre>`
`<canvas>` | Permite dibujar gráficos dinámicos mediante JavaScript. | `<canvas id="id" width="n" height="n"></canvas>` | `<canvas id="grafico" width="300" height="150"></canvas>`
`<iframe>` | Incrusta otra página HTML dentro del documento actual. | `<iframe src="url"></iframe>` | `<iframe src="https://ejemplo.com"></iframe>`
`<picture>` | Contenedor que permite servir distintas versiones de una imagen según el dispositivo. | `<picture>...</picture>` | `<picture><source srcset="grande.jpg" media="(min-width:800px)"><img src="pequena.jpg"></picture>`
`<progress>` | Muestra visualmente el progreso de una tarea o proceso. | `<progress value="n" max="n">...</progress>` | `<progress value="70" max="100"></progress>`