# Introducicón a CSS

**CSS - Cascading Style Sheets** es un lenguage de diseño gráfico utilizado para describir la 
presentación de un documento HTML. Permite controlar el estilo visual de las páginas web: 
colores, fuentes, márgenes, posiciones, animaciones y más. 

--- 

## Formas de aplicar CSS en HTML 
Css puede aplicarse a un documento HTML de **tres formas principales** : *inline*, *internal*, *external*. 
Cada una tiene usos y características específicas. 

1. **Inline (En línea):**
    - El estilo se pliaca directamente a un elemento HTML mediante el atributo `style`.
    - Ejemplo: 
        ```
        <p style="color: red; font-size:16px">Texto en rojo</p>
        ```
2. **Internal (Interno):** 
    - Se escribe dentro de una etiqueta `<style>` ubicada en `<head>` de documento HTML. 
    - Ejemplo: 
        ```
        ...
        <head>
            ...
            <style>
                p{
                    color: blue;
                    font-weight: bold;
                }
            </style>
        </head>
        <body>
        ...
        ```
3.  **External (Externo):** 
    - Se escribe en un archivo separado con extensión .css y se enlaza al HTML mediante `<link>`
    - Ejemplo: 
        ```
        ...
        <head>
            ...
            <link rel="stylesheet" href="estilos.css">
        </head>
        <body>
        ...
        ```

--- 

## Selectores
Los selectores permiten seleccionar y aplicar estilos a elementos HTML específicos. 

### Selectores Básicos
1. Selector de elemento (o tipo)
    -   Selecciona todos los elementos de ese tipo. 
        ```
        p{ 
            color: blue
        }
        ```
        - Cambia el color de todos los `<p>`

2. Selector de clase
    -   Selecciona elementos que tengan una clase específica. 
        ```
        .card{ 
            border: 1px solid black; 
        }
        ```
        - Aplica el borde a todos los elementos con `class="card"`

3. Selector de ID
    -   Selecciona un único elemento con un ID específico.
        ```
        #header{ 
            background-color: gray; 
        }
        ```
        - Se usa para estilos únicos (no debe repetirse el ID).

3. Selector de ID
    -   Selecciona un único elemento con un ID específico.
        ```
        #header{ 
            background-color: gray; 
        }
        ```
        - Se usa para estilos únicos (no debe repetirse el ID).

3. Selector de ID
    -   Selecciona un único elemento con un ID específico.
        ```
        #header{ 
            background-color: gray; 
        }
        ```
        - Se usa para estilos únicos (no debe repetirse el ID).