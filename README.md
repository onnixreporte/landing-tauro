# Hospital Equino Maldonado & Asoc. — Landing

Sitio estático, sin paso de build. Exportado desde Claude Design ("Hospital Equino mejoras de diseño").

- `index.html`: la landing (template que renderiza `assets/dc-runtime.js` con React)
- `assets/`: runtime y React 18.3.1 servidos localmente
- `media/`: video del hero, fotos y logos
- `fonts/`: Open Sans (woff2)

## Deploy en Vercel
Proyecto `landing-tauro`, Framework Preset **Other**, sin Build Command ni Output Directory. Cada push a `main` publica en producción.
