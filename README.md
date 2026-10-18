# 📄 Hoja de Vida Web Interactiva - Camila Muñoz

Bienvenido al repositorio oficial del **Sitio Web de Hoja de Vida y Portafolio Profesional de Camila Muñoz**.

Este proyecto consiste en una plataforma web modular, responsiva e interactiva estructurada en **HTML5 Semántico**, **CSS3 Arquitectónico (Modular y Basado en Tokens)** y **JavaScript Vainilla** para la gestión dinámica de componentes y temas.

---

## 🌟 Características Destacadas del Sitio Web

1. **Diseño Modular y Responsivo**:
   - Arquitectura CSS segmentada (`base`, `components`, `layout`, `variables`) que facilita el mantenimiento e integración de estilos globales.
   - Adaptabilidad fluida para dispositivos móviles, tabletas y monitores de alta resolución.

2. **Menú Hamburguesa Responsivo**:
   - Control dinámico de apertura y cierre optimizado para pantallas móviles y dispositivos adaptativos.
   - Gestión avanzada de accesibilidad mediante atributos WAI-ARIA (`aria-expanded` y `aria-label`) que mutan en tiempo real según el estado del menú, además de cierre automático al seleccionar cualquier enlace interno[cite: 1].

3. **Módulo Asíncrono de Repositorios (GitHub REST API)**:
   - Sincronización en tiempo real con la API pública de GitHub para el consumo y listado de repositorios[cite: 1].
   - Implementación estricta de `Fetch API` mediante `async/await`, encapsulamiento en bloques `try...catch`, evaluación de `response.ok` y manejo explícito de códigos de estado HTTP (200, 400, 404, 500)[cite: 1].
   - Renderizado dinámico reflejando de forma transparente los tres estados de la petición: **cargando** (con indicador visual y animación de giro), **éxito** (tarjetas detalladas con lenguajes, estrellas y fechas) y **error**[cite: 1].

4. **Interactividad en JavaScript Vainilla**:
   - Control dinámico de interfaz mediante `main.js`[cite: 1].
   - Implementación de componentes interactivos sin dependencia de librerías externas[cite: 1].

5. **Sección de Portafolio y Proyectos Enriquecida**:
   - Integración nativa de recursos multimedia (imágenes de proyectos, pistas de audio demostrativas y vídeos)[cite: 1].

6. **Navegación Estructurada y Multinivel**:
   - Módulos independientes para experiencia profesional, formación académica, proyectos, habilidades, idiomas y contacto[cite: 1].

---

## 📁 Estructura del Proyecto

```text
munoz-camila-hoja-de-vida/
├── index.html                   # Página Principal / Inicio[cite: 1]
├── acerca_de_mi.html            # Biografía y Descripción Personal[cite: 1]
├── perfil_profesional.html      # Resumen Ejecutivo y Perfil Profesional[cite: 1]
├── experiencia_profesional.html # Trayectoria Laboral y Experiencia[cite: 1]
├── formacion_academica.html     # Historial Académico y Certificaciones[cite: 1]
├── cursos.html                  # Cursos y Capacitaciones Complementarias[cite: 1]
├── proyectos.html               # Proyectos Destacados y Casos de Estudio (GitHub API)[cite: 1]
├── portafolio.html              # Muestras de Trabajo y Galería[cite: 1]
├── habilidades.html             # Habilidades Técnicas y Blandas[cite: 1]
├── idiomas.html                 # Competencias Lingüísticas[cite: 1]
├── formulario.html              # Formulario de Contacto Interactivo con Validación[cite: 1]
├── css/
│   ├── README.md                # Documentación de la Arquitectura CSS3[cite: 1]
│   ├── styles.css               # Archivo Principal de Estilos (Importador)[cite: 1]
│   ├── variables.css            # Tokens de Diseño, Colores y Tipografía[cite: 1]
│   ├── base.css                 # Estilos Base y Resets Tipográficos[cite: 1]
│   ├── layout.css               # Estructura Responsiva, Grids y Flexbox[cite: 1]
│   └── components.css           # Tarjetas, Botones, Tablas y Formularios[cite: 1]
├── jss/
│   ├── README.md                # Documentación de Scripts JavaScript[cite: 1]
│   └── main.js                  # Lógica Principal Interactiva (Tema, Menú, Fetch API)[cite: 1]
└── assets/
    ├── README.md                # Documentación de Recursos Multimedia[cite: 1]
    ├── audios/
    │   └── audioproyecto.mp3    # Archivo de Audio Promocional / Demostrativo[cite: 1]
    ├── images/
    │   ├── foto1.jpeg           # Fotografía de Perfil Principal[cite: 1]
    │   └── imagenproyecto.jpeg  # Captura / Recursos visuales de Proyectos[cite: 1]
    └── videos/
        └── videoproyecto.mp4    # Video de Demostración de Proyecto[cite: 1]
---

## 🎨 Arquitectura y Estilos (CSS)
Variables y Tokens (variables.css): Centralización de colores primarios, colores de acento, sombras, bordes y fuentes primarias (var(--font-primary))[cite: 1].

Componentes Reposicionables (components.css): Estilos aislados para tarjetas de contenido (.card), tablas (.languages-table), botones (.btn), etiquetas (.badge), contenedores multimedia (.video-wrapper) y estados visuales del consumo de APIs y formularios[cite: 1].

---

## 🚀 Instalación y Uso

1. Clona o descarga este repositorio en tu equipo local:
   ```bash
   git clone [https://github.com/tu-usuario/munoz-camila-hoja-de-vida.git](https://github.com/tu-usuario/munoz-camila-hoja-de-vida.git)
