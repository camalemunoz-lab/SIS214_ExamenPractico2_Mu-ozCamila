# 🚀 Portafolio Web Profesional - Ingeniería de Sistemas

Portafolio web personal desarrollado bajo estrictos estándares de accesibilidad, diseño adaptable (Mobile-First) y arquitectura modular en HTML5, CSS3 y JavaScript moderno (ES6+).

---

## 📋 Tabla de Contenidos
1. [Descripción del Proyecto](#-descripción-del-proyecto)
2. [Estructura del Proyecto y Páginas](#-estructura-del-proyecto-y-páginas)
3. [Características Principales](#-características-principales)
4. [Tecnologías y Stack Utilizado](#-tech-stack)
5. [Módulos de JavaScript (`main.js`)](#-módulos-de-javascript-mainjs)
6. [Instalación y Uso Local](#-instalación-y-uso-local)
7. [Autora](#-autora)

---

## 🎯 Descripción del Proyecto
Este sitio web funciona como un Currículum Vítae y portafolio interactivo para destacar la formación académica, experiencia práctica y proyectos de desarrollo de software en el ámbito de la Ingeniería de Sistemas. Cuenta con un sistema de navegación optimizado, control de temas (Claro/Oscuro), buscador en tiempo real, validación de formularios interactivos y consumo asíncrono de APIs REST.

---

## 🗂️ Estructura del Proyecto y Páginas
El sitio consta de múltiples vistas interconectadas mediante navegación semántica:
* `index.html` — Página de inicio y bienvenida general.
* `acerca_de_mi.html` — Biografía e intereses personales.
* `perfil_profesional.html` — Resumen de competencias como Ingeniera de Sistemas.
* `formacion_academica.html` — Historial educativo (Universidad Católica Boliviana y Colegio Inglés Católico).
* `experiencia_profesional.html` — Trayectoria en desarrollo de software.
* `habilidades.html` — Dominio de lenguajes (Java, C++, Python, JavaScript, PostgreSQL).
* `cursos.html` — Capacitaciones y certificaciones obtenidas.
* `idiomas.html` — Nivel de competencia lingüística (Español, Inglés, Ruso, Chino).
* `proyectos.html` — Módulo dinámico con repositorios sincronizados vía API REST.
* `portafolio.html` — Galería multimedia interactiva.
* `formulario.html` — Módulo de contacto con validación en tiempo real.

---

## ✨ Características Principales
* **Diseño Dual-Theme:** Conmutación dinámica entre Modo Claro y Modo Oscuro con persistencia de estado mediante `localStorage` y serialización JSON.
* **Mobile-First & Accesibilidad:** Navegación adaptativa con menú hamburguesa y atributos WAI-ARIA (`aria-expanded`, `aria-current`, `aria-label`).
* **Buscador Inteligente:** Tuberías funcionales inmutables (`.filter()` y `.map()`) para filtrar páginas por palabras clave y redirigir instantáneamente al hacer clic.
* **Formulario Interactivo:** Intercepción explícita del ciclo de vida del evento `submit` con `e.preventDefault()`, validación nativa `ValidityState` de HTML5 y retroalimentación visual en tiempo real mediante el evento `input`.

---

## 💻 Tech Stack
* **HTML5:** Estructuración semántica accesible (`<nav>`, `<header>`, `<main>`, `<dialog>`, `<aside>`).
* **CSS3:** Arquitectura modular, variables CSS personalizadas y diseño responsivo adaptado a múltiples dispositivos.
* **JavaScript (ES6+):** Manipulación del DOM, programación asíncrona (`async/await`, `try...catch`), manejo de eventos y funciones flecha.

---

## ⚙️ Módulos de JavaScript (`main.js`)

El archivo `jss/main.js` agrupa los siguientes bloques lógicos clave:
1. **Gestión de Tema:** Carga, serialización y almacenamiento de la preferencia de color del usuario.
2. **Modal Accesible:** Control automatizado del elemento nativo `<dialog>` con cierre inteligente por detección de *backdrop*.
3. **Menú Hamburguesa:** Control de estados móviles responsivos y accesibilidad mediante WAI-ARIA.
4. **Buscador de Páginas:** Filtrado funcional en tiempo real de la colección inmutable de rutas del sitio con redirección optimizada (`mousedown`).
5. **Validación de Formularios:** Verificación en tiempo real de campos obligatorios, longitudes mínimas y expresiones regulares (ej. números telefónicos).
6. **Módulo Asíncrono REST (Fetch API):** Consumo de la API pública de GitHub con manejo de bloques `try...catch`, evaluación estricta de códigos HTTP (`response.ok`, `400`, `404`, `500`) y renderizado transparente de los estados **cargando**, **éxito** y **error**.

---

## 🛠️ Instalación y Uso Local

1. Clona este repositorio o descarga los archivos en tu equipo local:
   ```bash
   git clone [https://github.com/camale/tu-repositorio.git](https://github.com/camale/tu-repositorio.git)