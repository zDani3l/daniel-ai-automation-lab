# HTML Cheatsheet

Una referencia simple para recordar las etiquetas HTML mas importantes.

## Etiquetas Principales

| Etiqueta | Que significa | Para que sirve | Ejemplo |
|---|---|---|---|
| `<!DOCTYPE html>` | Tipo de documento | Le dice al navegador que use HTML moderno | `<!DOCTYPE html>` |
| `<html>` | Pagina completa | Envuelve toda la pagina | `<html>...</html>` |
| `<head>` | Configuracion | Contiene cosas que no se ven directamente | `<head>...</head>` |
| `<title>` | Titulo de pestana | Texto que aparece en la pestana del navegador | `<title>Mi pagina</title>` |
| `<style>` | CSS interno | Sirve para escribir estilos dentro del HTML | `<style> body { color: white; } </style>` |
| `<body>` | Cuerpo visible | Todo lo que el usuario ve en la pagina | `<body>...</body>` |
| `<main>` | Contenido principal | Encierra la parte principal de la pagina | `<main>...</main>` |
| `<nav>` | Navegacion | Menu o barra de links | `<nav><a href="#home">Home</a></nav>` |
| `<section>` | Seccion | Divide la pagina en bloques importantes | `<section><h2>Mission</h2></section>` |
| `<div>` | Caja generica | Agrupa elementos; no tiene significado especial | `<div class="card">...</div>` |
| `<h1>` | Titulo principal | El titulo mas importante de la pagina | `<h1>Daniel AI Lab</h1>` |
| `<h2>` | Subtitulo | Titulo de una seccion | `<h2>Current Focus</h2>` |
| `<h3>` | Subtitulo menor | Titulo dentro de una seccion | `<h3>Python</h3>` |
| `<p>` | Parrafo | Texto normal | `<p>Estoy aprendiendo HTML.</p>` |
| `<a>` | Link | Enlace a otra pagina o seccion | `<a href="https://github.com">GitHub</a>` |
| `<ul>` | Lista desordenada | Lista con puntitos | `<ul><li>Python</li></ul>` |
| `<ol>` | Lista ordenada | Lista numerada | `<ol><li>Paso uno</li></ol>` |
| `<li>` | Elemento de lista | Cada punto dentro de `ul` u `ol` | `<li>Aprender APIs</li>` |
| `<strong>` | Importante/negrita | Marca texto importante | `<strong>Python</strong>` |
| `<em>` | Enfasis/cursiva | Marca texto enfatizado | `<em>muy importante</em>` |
| `<img>` | Imagen | Muestra una imagen | `<img src="foto.png" alt="Foto">` |
| `<button>` | Boton | Boton para acciones | `<button>Enviar</button>` |
| `<input>` | Entrada | Campo para escribir datos | `<input type="text">` |
| `<form>` | Formulario | Agrupa inputs para enviar datos | `<form>...</form>` |
| `<br>` | Salto de linea | Baja a la siguiente linea | `Hola<br>Daniel` |
| `<hr>` | Linea divisoria | Dibuja una separacion horizontal | `<hr>` |

## Mapa Mental

| Tipo | Etiquetas |
|---|---|
| Estructura base | `html`, `head`, `body`, `main` |
| Organizacion | `nav`, `section`, `div` |
| Texto | `h1`, `h2`, `h3`, `p`, `strong`, `em` |
| Links y media | `a`, `img` |
| Listas | `ul`, `ol`, `li` |
| Formularios | `form`, `input`, `button` |
| Separadores | `br`, `hr` |

## Lo Mas Importante Para Este Proyecto

```html
<head>     configuracion
<style>    CSS
<body>     lo visible
<nav>      menu
<section>  bloque de pagina
<div>      caja generica
<h1>       titulo principal
<h2>       subtitulo
<p>        parrafo
<a>        enlace
<ul>       lista
<li>       elemento de lista
```

## Regla De Oro

```text
Si es contenido visible, casi siempre esta en body.
Si es diseno o configuracion, casi siempre esta en head.
Si quieres agrupar cosas, usa div o section.
Si quieres texto normal, usa p.
Si quieres link, usa a.
Si quieres titulo, usa h1/h2/h3.
```

## Conexion Entre HTML Y CSS

HTML crea las piezas:

```html
<div class="tag">Daniel + Pixel Lab</div>
```

CSS les da estilo:

```css
.tag {
  color: #22c55e;
  font-weight: 700;
}
```

Idea clave:

```text
class="tag" en HTML se conecta con .tag en CSS.
El punto en CSS significa "clase".
```
