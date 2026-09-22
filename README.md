# Red Flores — El Camino a la Gloria

Esta versión está conectada a Supabase para que los equipos registrados puedan verse desde distintos dispositivos.

## Publicar
Sube `index.html` y la carpeta `assets` al repositorio de GitHub.
Activa GitHub Pages desde Settings > Pages > Deploy from a branch > main > /(root).

## Base de datos
La tabla esperada es `public.equipos` con:
- nombre_equipo
- responsable
- jugadores (text[])
- creado_en

El formulario exige de 5 a 10 jugadores.

## Nota del sorteo
Las inscripciones ya son compartidas mediante Supabase.
El resultado del sorteo de esta versión todavía se guarda en el navegador del administrador.
La siguiente mejora recomendada es guardar también el sorteo y el estado de inscripciones en Supabase con autenticación administrativa.
