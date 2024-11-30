# **AulaViva - Plataforma Educativa**

## Descripción

**AulaViva** es una plataforma educativa interactiva diseñada para ofrecer recursos y herramientas para el aprendizaje. La aplicación web proporciona acceso a cursos, ejercicios interactivos, mapas de ubicación de la academia, y un formulario de contacto para consultas. Este proyecto tiene como objetivo ofrecer una experiencia dinámica para estudiantes y profesores a través de contenido interactivo y fácil acceso a información.

## Características

- **Página principal** con navegación entre diferentes secciones de la plataforma.
- **Carrusel de imágenes** para mostrar contenido destacado o banners promocionales.
- **Interactividad con H5P**: Se incluyen ejercicios interactivos como cuestionarios y presentaciones.
- **Formulario de contacto** para que los usuarios puedan enviar sus preguntas o consultas.
- **Mapa interactivo** con Leaflet que muestra la ubicación de la academia.
- **Sección de categorías** con enlaces a los diferentes cursos disponibles en la plataforma.

## Tecnologías Utilizadas

- **HTML5**: Estructura básica de la página web.
- **CSS3**: Diseño y estilo visual de la página.
- **JavaScript**: Funcionalidad interactiva, como el carrusel de imágenes y la validación del formulario.
- **Leaflet.js**: Para la visualización del mapa interactivo con la ubicación de la academia.
- **H5P**: Para incrustar contenido interactivo y multimedia (ejercicios, cuestionarios, etc.).

## Estructura del Proyecto

```plaintext
AulaViva/
│
├── index.html            # Página principal
├── cursos.html           # Página de cursos
├── ejercicios.html       # Página de ejercicios
├── academia.html         # Página de la academia
├── contacto.html         # Página de contacto
├── assets/               # Carpeta con recursos multimedia (logos, banners, imágenes, etc.)
│   ├── logo/
│   ├── img/
│   └── redes/
├── css/                  # Estilos de la página
│   └── css.css
├── js/                   # Archivos JavaScript
│   ├── js.js             # Funcionalidades de la página principal
│   └── map.js            # Mapa interactivo
└── README.md             # Este archivo
