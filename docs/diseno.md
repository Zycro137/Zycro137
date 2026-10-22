# Fase 2: Planificación y Diseño del Perfil

## 1. Esquema del README.md (Estructura del Perfil)

1. **Encabezado (Presentación):** Saludo, nombre y Apodo.
2. **Sobre mí (About me):** Breve párrafo de enfoque y objetivos.
3. **Habilidades y tecnologías (Tech Stack):** Lista visual (insignias) agrupada por categorías.
4. **Proyectos destacados:** Fichas técnicas de los proyectos más relevantes.

---

## 2. Diseño de Contenido por Sección

### Sección: Presentación y Sobre mí
* **Qué incluir:** Un saludo cordial, mi nombre (Santiago Maldonado), apodo (Zycro) y estudiante de la ESPOL.
* **Qué evitar:** Descripciones demasiado largas o datos irrelevantes.
* **Formato:** Texto en Markdown simple y Typing SVG de DenverCode1 (https://readme-typing-svg.demolab.com/).

### Sección: Habilidades (Tech Stack)
* **Qué incluir:** Lenguajes (Java, C#, HTML/CSS), herramientas (Unity) y Bases de Datos (MySQL).
* **Qué evitar:** Listar tecnologías de las que solo conozco el nombre o no he usado en proyectos reales.
* **Formato:** Se usarán insignias estáticas (Badges de *Shields.io*) para darle color y separación visual rápida.

### Sección: Proyectos Destacados
* **Qué incluir:** Solo los dos proyectos seleccionados (Gestor de BD Frutalízate y Landing Page Cairo GYM).
* **Formato:** Se utilizará un formato estructurado (Fichas) usando títulos `h3` y listas de viñetas para facilitar la lectura. No se usarán tablas complejas para evitar problemas de visualización en móviles.

---

## 3. Fichas de Proyectos Destacados

Antes de redactarlas en el perfil, esta es la información técnica estructurada que llevará cada proyecto:

### Ficha Proyecto 1: Sistema de Gestión "Frutalízate"
* **Nombre:** Sistema de Gestión y BD "Frutalízate"
* **Problema que resuelve:** Control eficiente de inventario, registro de clientes, gestión de suscripciones recurrentes y reportes de ventas para un negocio de jugos.
* **Tecnologías utilizadas:** MySQL (Triggers, Vistas, Procedimientos Almacenados), CLI (Interfaz de línea de comandos).
* **Funcionalidades principales:** 
  * CRUD de clientes, pedidos y suscripciones.
  * Automatización de control de stock (prevención de stock negativo).
  * Reportes financieros y operativos generados dinámicamente.
* **Enlace al repositorio:** *`https://github.com/Zycro137/Proyecto-Frutalizate.git`*
* **Demostración:** Capturas de pantalla integradas en el README mostrando los reportes y menús de consola.

### Ficha Proyecto 2: Landing Page Comunitaria - "Cairo Gym"
* **Nombre:** Web Comunitaria "Cairo Gym"
* **Problema que resuelve:** Falta de visibilidad digital del gimnasio local, brindando a la comunidad información clara sobre horarios, estadísticas y servicios.
* **Tecnologías utilizadas:** HTML5, CSS3, Git/GitHub, Google Sheets (para análisis de datos).
* **Funcionalidades principales:** 
  * Diseño 100% responsivo para móviles y escritorio.
  * Arquitectura de navegación fluida en una sola página (One-page).
  * Exposición de estadísticas reales derivadas de encuestas.
* **Enlace al repositorio:** `https://github.com/Zycro137/Proyecto-2-DAWM`
* **Demostración:** *(Se agregará URL de GitHub Pages)*

---

## 4. Estrategia de Commits (Conventional Commits)

Para construir la versión final, no se subirá todo de golpe. Se aplicará desarrollo incremental utilizando el estándar de *Conventional Commits* para contar la historia del proyecto.

**Ejemplos de commits planificados:**
* `docs: inicializa estructura base del README`
* `feat: agrega seccion de presentacion y sobre mi`
* `feat: incorpora insignias de habilidades y tecnologias`
* `feat: agrega ficha del proyecto Frutalizate`
* `feat: agrega ficha del proyecto Cairo Gym`
* `fix: corrige errores gramaticales`
