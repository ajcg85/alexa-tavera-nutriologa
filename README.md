# Alexa Tavera — Nutrióloga | Landing Page

Landing page de una sola página para la Nutrióloga Alexa Tavera.

## Contenido
- `index.html` — Página completa (HTML/CSS/JS, sin dependencias externas excepto la fuente Nunito de Google Fonts)
- `vercel.json` — Configuración para deploy estático en Vercel

## Cómo subir a GitHub

```bash
# Dentro de esta carpeta:
git init
git add .
git commit -m "Landing page Alexa Tavera - nutrióloga"
git branch -M main
git remote add origin https://github.com/TU_USUARIO/TU_REPO.git
git push -u origin main
```

Si ya tienes el repo creado en GitHub, solo reemplaza la URL de `origin` por la tuya.

## Cómo desplegar en Vercel

1. Entra a [vercel.com](https://vercel.com) → **Add New Project**
2. Selecciona el repositorio que acabas de subir
3. En **Framework Preset** elige **Other** (no es Next.js ni nada especial, es HTML estático)
4. Build Command: (dejar vacío)
5. Output Directory: `.` (la raíz)
6. Click **Deploy**

En unos segundos tendrás tu URL tipo `tu-repo.vercel.app`.

## Notas técnicas
- Las imágenes (banner y productos) están embebidas en base64 directamente en el HTML, por eso el archivo pesa ~800KB. Esto evita problemas de rutas rotas en Vercel, pero si más adelante quieres optimizar el peso, puedo extraerlas a archivos separados en una carpeta `/images`.
- El botón de WhatsApp flotante apunta a +52 433 935 6659.
- El toggle de idioma (ES/EN) funciona con JavaScript nativo, sin librerías.
- El número de WhatsApp y los textos en inglés/español están directamente en el HTML — para editarlos solo busca el texto en el archivo y modifícalo.
