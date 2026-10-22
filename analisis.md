# Fase de Análisis de perfiles

- **Abhishek Naidu (`@abhisheknaiidu`):** Un perfil muy moderno, enfocado en mostrar su personalidad de forma visual. Usa GIFs divertidos, muchos iconos de colores y tarjetas estáticas para que se vea atractivo sin ser muy pesado.
- **DenverCoder1 (`@DenverCoder1`):** Es un perfil bastante dinámico que parece un panel de control. Destaca por crear herramientas para GitHub, así que su perfil es una vitrina técnica llena de widgets en tiempo real, trofeos, rachas de commits, texto animado y hasta el juego de la serpiente en su historial.
- **Sindre Sorhus (`@sindresorhus`):** Empieza con un impacto visual fuertísimo usando banners y GIFs gigantes, y luego pasa a un enfoque técnico menos llamativo, fijando sus proyectos de mayor impacto en puro texto plano.

---

## Tabla comparativa de perfiles

| Criterio | Abhishek Naidu (`@abhisheknaiidu`) | DenverCoder1 (`@DenverCoder1`) | Sindre Sorhus (`@sindresorhus`) |
| :--- | :--- | :--- | :--- |
| **Presentación (primeros 10 s)** | Muy llamativa pero amigable. Ves un GIF saludando, su rol ("Full Stack Engineer") y te puedes hacer una idea de su personalidad. Se enfoca en presentarse él como persona. | Impacto técnico inmediato. Lo primero que ves es un texto escribiéndose solo (animación) y una avalancha de datos en tiempo real (trofeos, contribuciones, nivel). Queda claro que es alguien muy activo creando código. | Impacto visual ruidoso y directo. Te recibe con banners gigantes, texto animado parpadeante y GIFs coloridos (unicornios, código). |
| **Estructura** | Saludo > Estadísticas de GitHub > Tecnologías > Tarjetas de proyectos > Redes sociales. Es un orden bastante clásico. | Texto animado > Panel de trofeos > Estadísticas y rachas > Tecnologías > Proyectos > Animación de commits. Funciona como un dashboard o tablero de mando. | Bloque promocional gigante (GIFs de saludo, apps y blog) > Colección de proyectos fijados de altísimo impacto > Datos de patrocinadores. |
| **Habilidades** | Usa insignias clásicas de Shields.io e iconos de colores para cada tecnología. Todo muy ordenado visualmente. | En lugar de iconos estáticos, usa tarjetas automáticas que calculan qué lenguajes usa más basándose en su código real de GitHub. | No lista habilidades como tal. Su nivel se asume inmediatamente por la envergadura de los proyectos fijados y los lenguajes principales (TypeScript, Swift) que GitHub muestra en ellos. |
| **Proyectos** | Usa los repositorios fijados nativos y mete un par de tarjetas extra en el texto con estadísticas básicas de sus repositorios más populares. | Fija sus propios proyectos de widgets para GitHub (como el de rachas de commits) y los demuestra funcionando en vivo directamente dentro de su README. | Tiene fijados repositorios gigantescos (con miles de estrellas). Las descripciones son súper precisas y usa emojis al inicio de cada una para darles algo de personalidad. |
| **Contacto** | Una fila de iconos centrados al final (LinkedIn, Twitter, correo). Se encuentran fácil al hacer scroll hasta abajo. | Tiene badges pequeños y directos en la parte superior del perfil, justo debajo de su saludo, integrados casi como un subtítulo. | Todo se maneja a través de los canales laterales nativos de GitHub (página personal, Mastodon, panel de *Sponsors* y organizaciones a las que pertenece). |
| **Accesibilidad y móvil** | Tarda un poquito por las imágenes, pero lee bien. Algunas de sus tarjetas no se adaptan perfecto si cambias al tema oscuro del celular. | Al depender de tantos gráficos SVG interactivos que consultan servidores en tiempo real, la carga inicial es algo pesada, aunque los gráficos escalan perfecto en el móvil. | Los primeros segundos pueden ser un poco agresivos visualmente por los GIFs tan grandes. Sin embargo, como usa las herramientas nativas para el resto, carga rápido y se adapta bien al móvil. |

---

## Lista de verificación de repositorios fijados

| Característica evaluada | Repo 1: `github-readme-streak-stats` (DenverCoder1) | Repo 2: `ky` (Sindre Sorhus) |
| :--- | :--- | :--- |
| **Descripción corta, temas (topics) y enlaces** | Tiene una descripción clara, usa múltiples topics (`github-api`, `readme`, `stats`) y enlaza directamente a un sitio web de demostración para generar las tarjetas. | Descripción de una línea precisa ("Tiny & elegant JavaScript HTTP client"). Usa topics (`fetch`, `http`, `request`) pero no tiene demo en vivo, ya que es una librería. |
| **README: propósito, uso y capturas** | Excelente. Explica qué hace, muestra previsualizaciones visuales de las tarjetas, y detalla los parámetros de URL para personalizar la herramienta sin necesidad de instalar nada. | Muy técnico y directo. Va al grano con instrucciones de instalación vía npm, diferencias con otras herramientas y bloques de código con ejemplos de uso. No necesita capturas. |
| **Licencia y archivo `.gitignore`** | Cuenta con licencia MIT visible y un `.gitignore` configurado para excluir dependencias y archivos de entorno local. | Licencia MIT estándar y `.gitignore` optimizado para proyectos Node.js (ignorando `node_modules` y logs). |
| **Historial de commits** | Frecuente y detallado. Usa convenciones semánticas (`feat:`, `fix:`, `docs:`) lo que facilita entender la evolución de la herramienta. | Mensajes de commit directos y en modo imperativo. El historial es lineal, limpio y sin mensajes de prueba o vacíos. |
| **Gestión de Issues, PRs y Releases** | Uso intensivo de Issues para reportes de la comunidad, Pull Requests revisados y uso de *Releases* con notas de versión detalladas. | Estricto control de calidad. Las contribuciones se hacen por PRs y las versiones (*Releases*) se publican siguiendo el versionado semántico estricto. |
| **Estructura de carpetas** | Separación clara entre el código fuente (`src/`), las pruebas de interfaz y la documentación. | Muy limpia. El código principal está separado de la carpeta de pruebas (`test/`) y la documentación interna. |
