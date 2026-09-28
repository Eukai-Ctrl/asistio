# Asistio v0.4 Full

1. Mantén tu config.js actual con Project URL + Publishable Key.
2. Ejecuta SUPABASE_V04.sql una sola vez en Supabase SQL Editor.
3. Crea/deploya la Edge Function `create-user` usando `supabase/functions/create-user/index.ts`.
4. Sube index.html, manifest, service-worker, icons y config.js a GitHub Pages.
5. Prueba login, colegios, usuarios, cursos, asignaturas, alumnos, QR, asistencia e historial.

IMPORTANTE:
- Nunca publiques service_role ni contraseña PostgreSQL.
- La Edge Function usa los secretos internos de Supabase.
- Para cerrar asistencia con ausentes, primero deben existir matrículas en enrollments.
