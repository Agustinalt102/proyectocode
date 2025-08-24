# Integración de consignas — Entrega avanzada (HTML/CSS + Git + GitHub Pages)

Este paquete agrega:
- `css/styles-advanced.css` (Grid + Flexbox, variables, tipografía fluida, modo oscuro, sin overflow-x).
- `js/main.js` (toggle de menú y tema).
- `partials/` con `header.html` y `footer.html` de ejemplo semántico.
- `README_integracion.md` con pasos y snippets.
- `.gitignore` y guía de `git` + `GitHub Pages`.

## Pasos rápidos
1. Asegurate de que **todas** tus páginas `<head>` tengan:
   ```html
   <meta charset="utf-8" />
   <meta name="viewport" content="width=device-width, initial-scale=1" />
   <link rel="stylesheet" href="css/styles-advanced.css" />
   ```
2. En el `<body>`, agregá al inicio:
   ```html
   <a class="skip-link" href="#contenido">Saltar al contenido</a>
   ```
3. Añadí las clases utilitarias `.container`, `.grid`, `.cards`, etc. en tus secciones.
4. Linkeá el JS antes de `</body>`:
   ```html
   <script src="js/main.js" defer></script>
   ```
5. Versioná con Git y publicá en GitHub Pages.
