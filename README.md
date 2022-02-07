# 🍋 Ejercicios del Máster Frontend de Lemoncode 🍋

## Laboratorio Módulo 01 - Layout

**Contenido del Módulo 01**
- Conceptos básicos HTML5 + CSS 3/4
- Maquetación responsiva
- SASS
- Concepto de diseño web para desarrolladores

**Descripción de los ejercicios**

1. Ejercicio: Crear una paleta de colores dinámica.

    - Usar el lenguaje SASS para crear distintos temas de paletas de colores.

    - La idea es partir de un color base, y a partir de ese color generar 4 colores más oscuros de manera gradual, y cuatro colores más claros de manera gradual.

    - Para comprobar que todo esta funcionando como se espera utilizar el siguiente html:  

    ```
        <div class="container-1">
        <div class="box darken-4"><span class="color-box-text">Darken 4</span></div>
        <div class="box darken-3"><span class="color-box-text">Darken 3</span></div>
        <div class="box darken-2"><span class="color-box-text">Darken 2</span></div>
        <div class="box darken-1"><span class="color-box-text">Darken 1</span></div>
        <div class="box base-color"><span class="color-box-text">Base color</span></div>
        <div class="box lighten-1"><span class="color-box-text">Lighten 1</span></div>
        <div class="box lighten-2"><span class="color-box-text">Lighten 2</span></div>
        <div class="box lighten-3"><span class="color-box-text">Lighten 3</span></div>
        <div class="box lighten-4"><span class="color-box-text">Lighten 4</span></div>
        </div>
    ```

2. Ejercicio: Crear dos temas distintos y mostrar los resultados en una página. Para visualizar los cambios debería ser suficiente importar un tema u otro en el fichero de estilos principal. Los cambios en el tema afectan a las siguientes características:

    - Color, Fuente, Border radius, Shadow box

3. Ejercicio: Crear la barra de navegación de la imagen usando flexbox.

    - El html es abierto completamente, es decir crear las estructuras necesarias que se crean convenientes.

    - La barra de navegación responde a distintas resoluciones. Utilizar media queries para conseguir este resultado.

4. Ejercicio: Crearemos un elemento de tipo card con Grid CSS.

    - Las alineaciones deberán hacerse con esta característica, pero el html es totalmente abierto.

**Guía de inicio**
1. Descarga o clona el repositorio
2. Instala las dependencias locales con `npm install`
3. Ejecuta `npx parcel src/index.html` para generar la carpeta dist y arrancar el servidor.
