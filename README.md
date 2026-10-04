# AlergoDigesta — Sitio web

Sitio estático (HTML + CSS) publicado en Vercel: https://www.alergodigesta.com

## Estructura

- `index.html` — página de inicio
- Páginas de servicio: `consulta.html`, `sibo.html`, `prick-test.html`, `reto-oral.html`, `inmunoterapia.html`, `alergia-pediatrica.html`, `feno.html`, `endoscopia.html`, `ecoendoscopia.html`
- Blog: `blog.html` (listado) + un archivo `.html` por artículo
- `preguntas-frecuentes.html`, `privacidad.html`
- `style.css` — sistema de diseño (colores, tipografía, componentes)
- `img/` — logo (`logo-header.png`, transparente), íconos (`favicon-32.png`, `apple-touch-icon.png`, `icon-512.png`), imagen para redes (`og-image.jpg`) y fotos del equipo
- `sitemap.xml`, `robots.txt` — para Google

## Agregar una página nueva

1. Copiar una página de servicio existente (por ejemplo `reto-oral.html`).
2. Cambiar `<title>`, `<meta name="description">`, las etiquetas `og:` y `canonical`, y el contenido entre `</header>` y `<footer>`.
3. Agregarla al pie de página de todas las páginas si corresponde y a `sitemap.xml`.

## Publicar

Cada commit a `main` se publica automáticamente en Vercel.

WhatsApp de contacto: +593 99 536 8196. Los enlaces usan `?text=` con un mensaje prellenado y llaman a `gtag_report_conversion` (conversión de Google Ads).
