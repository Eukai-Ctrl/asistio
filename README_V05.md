# Asistio v0.5 Administración

Incluye:
- CRUD de usuarios
- cambio de contraseña por superadministrador/administrador autorizado
- edición de nombre, correo y perfil
- activar/desactivar y eliminar usuarios
- CRUD de alumnos
- matrícula alumno-curso
- QR corregido
- validación de matrícula al escanear asistencia
- mensajes de Edge Function más útiles

Implementación:
1. Ejecuta SUPABASE_V05.sql en Supabase SQL Editor.
2. Crea una nueva Edge Function llamada manage-user.
3. Copia supabase/functions/manage-user/index.ts y despliega.
4. Mantén la función create-user si quieres, aunque v0.5 ya usa manage-user.
5. En GitHub reemplaza index.html, service-worker.js, manifest.webmanifest y README si deseas.
6. NO reemplaces tu config.js actual.
7. Haz commit y luego Ctrl+F5.

Importante: no copies Secret Keys al navegador ni a GitHub.
