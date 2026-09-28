# Asistio v0.2 PWA

Prototipo web de asistencia QR, pensado para PC, Android y iPhone.

## Publicación gratis en GitHub Pages
1. Crear un repositorio público llamado `asistio`.
2. Subir TODO el contenido de esta carpeta a la raíz del repositorio (index.html, manifest.webmanifest, service-worker.js, icons/).
3. Settings > Pages > Build and deployment > Source: Deploy from a branch.
4. Branch: main y carpeta /(root). Guardar.
5. Abrir la URL HTTPS indicada por GitHub Pages.

## Primera prueba
La primera carga debe hacerse con Internet porque las librerías de generación/lectura QR se obtienen de CDN y el service worker intenta guardarlas en caché. Después prueba modo avión.

Los datos de alumnos y asistencias NO están incluidos en el repositorio: se guardan en el almacenamiento local del navegador del dispositivo.

IMPORTANTE: usa datos ficticios durante el piloto público.
