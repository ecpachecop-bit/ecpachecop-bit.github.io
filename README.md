# Motors Passion

Motors Passion es una landing page responsiva creada con **HTML5 y CSS3**. El proyecto presenta un catálogo informativo de **carros, motos y aviones**, con fotografías, características básicas y precios de referencia.

## Objetivo

El objetivo del proyecto es aplicar los conceptos básicos vistos en clase:

- Estructura semántica con HTML5.
- Diseño visual con CSS3.
- Uso de Flexbox.
- Diseño responsive.
- Enfoque Mobile First.
- Formularios HTML.
- Uso de imágenes responsivas.

## Tecnologías utilizadas

- HTML5
- CSS3
- Flexbox
- Media Queries

No se utiliza JavaScript, frameworks, librerías externas ni backend.

## Secciones de la página

La página contiene las siguientes secciones:

1. **Header**
   - Nombre de la página.
   - Menú de navegación.
   - Enlaces a Inicio, Servicios, Nosotros y Contacto.

2. **Hero**
   - Título principal.
   - Descripción del proyecto.
   - Botón para ir a la sección de servicios.

3. **Servicios**
   - Carros.
   - Motos.
   - Aviones.

4. **Catálogo**
   - 6 carros.
   - 6 motos.
   - 6 aviones.
   - Total: 18 vehículos.

5. **Marcas**
   - Lista de fabricantes incluidos en el catálogo.

6. **Sobre nosotros**
   - Imagen representativa.
   - Descripción de Motors Passion.

7. **Testimonios**
   - Opiniones ficticias utilizadas únicamente como contenido de demostración.

8. **Contacto**
   - Nombre.
   - Correo electrónico.
   - Mensaje.
   - Botón de envío.

9. **Footer**
   - Nombre del proyecto.
   - Derechos reservados.
   - Enlaces de redes sociales de ejemplo.

## Diseño responsive

El proyecto utiliza un enfoque **Mobile First**.

### Celular

La página se muestra inicialmente en una sola columna para facilitar la lectura en pantallas pequeñas.

### Tableta

A partir de **600 px**, varios elementos se organizan en dos columnas.

```css
@media (min-width: 600px) {
    /* Estilos para tablet */
}
```

### Computador

A partir de **900 px**, el menú cambia a distribución horizontal y el catálogo puede mostrar tres elementos por fila.

```css
@media (min-width: 900px) {
    /* Estilos para computador */
}
```

## Estructura del proyecto

```text
motors_passion_proyecto1/
│
├── index.html
├── style.css
└── README.md
```

## Cómo abrir el proyecto

1. Descarga o copia la carpeta del proyecto.
2. Abre la carpeta en Visual Studio Code.
3. Verifica que `index.html` y `style.css` estén en la misma carpeta.
4. Abre `index.html` en un navegador.

También se puede abrir directamente haciendo doble clic sobre el archivo `index.html`.

## Uso en GitHub

Para guardar el proyecto en GitHub:

1. Crea un repositorio nuevo.
2. Sube `index.html`, `style.css` y `README.md`.
3. Realiza un commit con los archivos.
4. Si deseas publicar la página, activa GitHub Pages desde la configuración del repositorio.

## Imágenes

Las fotografías utilizadas en el catálogo se cargan desde fuentes externas, por lo que se necesita conexión a internet para visualizarlas.

Cada ficha conserva información sobre los créditos y la licencia de la imagen correspondiente.

## Formulario de contacto

El formulario es una demostración realizada únicamente con HTML y CSS. No envía información a un servidor porque el proyecto no utiliza backend ni JavaScript.

## Nota sobre los precios

Los precios mostrados son valores de referencia y pueden cambiar según el modelo, año, vendedor, disponibilidad y otras condiciones comerciales.

## Estado del proyecto

Proyecto académico terminado y preparado para visualizarse en:

- Celular.
- Tableta.
- Computador.
