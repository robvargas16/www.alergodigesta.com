# AlergoDigest — Sitio web

## Estructura
- `index.html` — página de inicio
- `servicios/` — páginas de cada servicio (usa `sibo.html` como plantilla para las 5 restantes: panel-igg-ige, microbiota, reto-oral, inmunoterapia, consulta)
- `blog/` — listado (`index.html`) + artículos individuales
- `css/style.css` — sistema de diseño completo (colores, tipografía, componentes)

## Pendientes antes de publicar
1. Reemplazar `593000000000` por tu número real de WhatsApp Business en todos los archivos (buscar "wa.me")
2. Crear las 5 páginas de servicio restantes copiando `servicios/sibo.html` y cambiando el contenido
3. Agregar fotos reales del consultorio/equipo en `img/`
4. Escribir los 2 artículos de blog restantes (mismo patrón que `blog/hinchazon-despues-de-comer.html`)

## Cómo publicarlo (con tu dominio ya comprado)

### Opción recomendada: Vercel o Netlify (gratis)
1. Sube esta carpeta a un repositorio de GitHub
2. Entra a vercel.com (o netlify.com), conecta tu cuenta de GitHub, selecciona el repo
3. Deploy automático — te da una URL tipo `alergodigest.vercel.app`
4. En el dashboard del proyecto, ve a "Domains" / "Dominios" y agrega tu dominio propio
5. Te van a mostrar registros DNS (normalmente un registro `A` apuntando a una IP, o un `CNAME`)
6. Entra al panel de tu proveedor de dominio (donde lo compraste) y agrega esos registros en la sección DNS
7. Espera la propagación (minutos a 48h) — Vercel/Netlify activan HTTPS automáticamente

### Alternativa sin GitHub
Netlify también permite arrastrar y soltar la carpeta directamente en netlify.com/drop para un deploy instantáneo, y luego conectar el dominio igual.
