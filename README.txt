# Gestión 360 PWA móvil

Esta versión está preparada para instalarse en celulares como app web progresiva (PWA).

## Archivos principales
- `index.html`: sistema Gestión 360.
- `manifest.webmanifest`: datos de instalación de la app.
- `sw.js`: service worker para instalación y caché básico.
- `icons/`: íconos de la app.

## Importante
Para que Android/iPhone permitan instalarla, súbela a un hosting con HTTPS, por ejemplo Firebase Hosting, Netlify, Vercel o tu hosting web.
No funcionará como PWA completa si la abres directamente con `file://` desde el computador.

## En Android
Abre la URL en Chrome y toca “Instalar app” o “Agregar a pantalla de inicio”.

## En iPhone/iPad
Abre la URL en Safari, toca Compartir y luego “Agregar a pantalla de inicio”.
