# EvalPhoto

# versión HTML vanilla

Archivo autocontenido: **`index.html`** (CSS + JS + JSZip embebidos).

## Uso

1. Abre `index.html` en un navegador moderno (Chrome, Edge, Firefox).
2. Para cámara / micrófono hace falta **HTTPS** o `localhost` (con `file://` puede restringirse).

## Qué incluye

- Evaluaciones, planos, observaciones anidadas (3 niveles)
- Pan / zoom, pines arrastrables, árbol lateral
- Foto (archivo / cámara / sin foto), notas y audio
- Importar / exportar ZIP compatible con EvalPhoto (schema 1.1)
- Datos en IndexedDB (`evalphoto_html_db`, independiente de la app React)

## Nota

Esta base de datos **no comparte** datos con la app Vite/React (`evalphoto_db`). Puedes exportar ZIP en una e importarlo en la otra.

---

Enlace: https://skymaker.github.io/EvalPhoto/index.html
