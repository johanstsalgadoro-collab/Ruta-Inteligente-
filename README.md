# Ruta inteligente híbrida — Presentación web

Presentación de **20 diapositivas** para la asignatura Investigación, Desarrollo e Innovación II, Universidad ECCI (2026).

**Autores:** Santiago Nicolás López López y Johan Stwee Salgado Rodríguez.  
**Docente:** Luis Guillermo Barrera Gutiérrez.

## Abrir la presentación

Abre `index.html` con Chrome, Edge o Firefox. No requiere instalar Node, npm ni un servidor. Si no existe conexión, la presentación sigue funcionando; las fuentes tipográficas de Google se sustituyen automáticamente por una tipografía del sistema.

Navegación: flechas izquierda/derecha o barra espaciadora; `F` para pantalla completa, `G` para índice; `Home` y `End` para ir al principio y al final. Botones visibles en el pie de página.

## Publicar gratis en GitHub Pages

1. Crea un repositorio público en GitHub (por ejemplo, `ruta-inteligente-ecci`).
2. Sube **los archivos de esta carpeta a la raíz del repositorio**, no el ZIP como único archivo. También puedes utilizar **Add file → Upload files**, seleccionar `index.html`, `styles.css`, `script.js`, `.nojekyll` y `README.md` y confirmar los cambios.
3. Abre **Settings → Pages**.
4. En **Build and deployment**, selecciona **Deploy from a branch**. En **Branch** elige `main` y la carpeta `/ (root)`. Guarda.
5. GitHub mostrará la dirección pública del sitio, habitualmente `https://TU-USUARIO.github.io/ruta-inteligente-ecci/`.

## Estructura

- `index.html`: estructura y controles.
- `styles.css`: diseño adaptable y tipografía legible.
- `script.js`: contenido de diapositivas, diagramas y navegación.
- `.nojekyll`: evita procesamiento innecesario por Jekyll en Pages.

## Fuentes y estado de validación

El contenido está basado en el documento del grupo **Perfil de solución e ingeniería de requisitos v1.0** y en sus antecedentes: portafolio de alternativas, vigilancia tecnológica y estado del arte. Las mejoras y KPI son **metas propuestas**, no resultados de un estudio ejecutado. Los arquetipos de usuarios requieren validación en campo. El diagrama UML es una representación de presentación del modelo conceptual; antes de usarlo como artefacto formal de ingeniería, deben revisarse las direcciones y semántica de las relaciones `include` y `extend`.
