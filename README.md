# AV/10 Studio — Website

Sitio one-page de AV/10 Studio. `index.html` es un bundle autocontenido (React + Tailwind + Framer Motion, fuentes e imágenes embebidas en base64). No requiere build process — se deployea tal cual.

## Deploy

Conectado a Vercel. Cualquier push a `main` dispara un deploy automático.

## Estructura

- `index.html` — el sitio completo (HTML + JS + CSS + assets inline)

## Hacer cambios

Por ahora todo el sitio vive en un único archivo minificado. Para cambios puntuales se edita directamente con scripts de patching (no hay código fuente legible separado todavía). Si se necesita iterar mucho, conviene migrar a un proyecto Vite/React con assets separados.
