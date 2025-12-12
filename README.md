# Recetario Celíaco — Descripción y características técnicas

Esta página es un sitio estático que ofrece recetas 100% sin gluten destinadas a la comunidad celíaca. Presenta un recetario visual con fichas de recetas, modales con las preparaciones y un formulario de contacto (frontend).

**Características principales:**
- **Propósito:** Mostrar recetas aptas para personas con celiaquía; contenido educativo y práctico.
- **Arquitectura:** Sitio estático (un solo HTML principal) que puede desplegarse en GitHub Pages, Netlify u otro hosting estático.
- **Tecnologías:** HTML5, CSS (estilos embebidos + Bootstrap 5.3.2 vía CDN), JavaScript mínimo (Bootstrap bundle vía CDN para modales y navegación).
- **Responsive:** Meta viewport y diseño basado en Bootstrap para adaptarse a móviles y escritorio.
- **Interactividad:** Modales para ver recetas completas y un formulario de contacto del lado cliente (no hay backend implementado).
- **Dependencias externas:** Bootstrap CSS y JS cargados desde CDN (no hay gestor de paquetes ni build step).
- **Accesibilidad:** Estructura semántica básica (secciones, navegación, botones); sería recomendable añadir más atributos ARIA y validación de contraste si se desea mejorar accesibilidad.

**Archivos clave:**
- `index.html`: página principal con todas las recetas y el layout.
- `README.md`: este archivo, con descripción y características.

**Sugerencias de despliegue:**
- Hospedar en un servicio de hosting estático (GitHub Pages, Netlify, Vercel).
- Opcional: extraer estilos a un CSS separado y añadir optimización de imágenes para mejorar rendimiento.# celiac-4
