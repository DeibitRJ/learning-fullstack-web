# Introducción a HTML 
**HTML (HyperText Markup Language)** es el lenguaje de marcado estándar que se usa para
crear páginas web. No es un lenguaje de programación, sino un lenguaje de **estructura**
que define el contenido de una página. 

- **HyperText (Hipertexto):**
    - Permite enlazar documentos entre sí mediante hipervínculos. 
    - Ejemplo: `<a href="https://www.google.com">Ir a Google</a>`

- **Markup Language (Lenguage de Marcado):**
    - Utiliza *etiquetas* (tags) para estructurar el contenido. 
    - Ejemplo: `<h1>Título</h1>` indica que es un encabezado.

--- 

## Etiquetas HTML esenciales

| Etiqueta | Descripción | 
|----------|----------|
|`<!DOCTYPE>`| Define el tipo de documento (HTML5 en este caso). | 
| `<html>` | Contenedor principal de todo el documento.            | 
| `<head>` | Información no visible: título, condifiación, etc. |
| `<title>` | Título de la pestaña del navegador. |
| `<meta>`| Metadatos como charset y descripción. |
| `<body>`| Contenido visible de la página. |
| `<h1>` a `<h6>` | Encabezados, de mayor `<h1>` a menor `<h6>`. |
| `<p>`| Parrafo. |
| `<a>`| Hipervínculo. |
| `<ul>`, `<ol>`, `<li>`| Listas no ordenadas y ordenadas. |
| `<div>`| Contenedor genérico para agrupar elementos. |
| `<span>`| Contenedor en línea para texto o contenido corto. |
| `<br>`| Salto de línea. |
| `<strong>`, `<em>`| Texto en negrita / énfasis (cursiva). |

--- 

## Estructura básica de un documento HTML 
```<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
</head>
<body>
    
</body>
</html>
```