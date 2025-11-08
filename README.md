# Portafolio — Pedro Rodriguez

Sitio estático (HTML, CSS, JS) para GitHub Pages. Diseño minimalista con paleta personalizada y sección de proyectos modular.

## Estructura
- `index.html` — Contenido principal en una sola página (hero, proyectos, habilidades, experiencia, contacto).
- `styles.css` — Estilos responsivos, variables CSS con la paleta: `#05668d`, `#427aa1`, `#ebf2fa`, `#679436`, `#a5be00`.
- `script.js` — Lógica de navegación móvil, render de proyectos, filtros y *auto-fetch* opcional de GitHub.
- `projects.json` — Lista curada y fácil de editar de proyectos destacados.
- `assets/favicon.svg` — Ícono simple.

## Edición rápida de proyectos
1. Abre `projects.json` y duplica un objeto.
2. Cambia `title`, `description`, `year`, `urls`, `area` y `tags`.
3. (Opcional) Marca `"featured": true` para que aparezca primero.
4. En `script.js` puedes fijar `AUTO_FETCH_GITHUB=false` si quieres ignorar la API pública de GitHub.

## Despliegue en GitHub Pages
1. Crea el repo **username.github.io** (ej. `pedrorgz.github.io`) o habilita Pages en un repo existente.
2. Sube estos archivos a la rama `main`.
3. En **Settings → Pages**, selecciona la fuente `Deploy from a branch` y la carpeta raíz `/`.
4. Espera a que se compile; tu sitio quedará disponible en `https://username.github.io`.

## Personalización
- Modifica los links de contacto en `index.html` (sección Contacto).
- Cambia la variable `--brand` y compañia en `styles.css` si quieres ajustar la paleta.
- Agrega una sección de publicaciones o blog si lo deseas.

## Licencia
MIT para el contenido del template. El contenido personal del portafolio es tuyo.
