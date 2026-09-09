# Portfolio interactivo — Pilar Ramírez

Portfolio gamificado en formato "casa isométrica navegable", con paneles interactivos por sección, sonidos de interfaz y música de fondo opcional.

## Estructura

```
index.html          → la página completa (HTML + CSS + JS en un solo archivo)
images/house.jpg     → la ilustración de fondo
audio/               → carpeta para la música de fondo (ver audio/README.md)
```

## Cómo publicarlo en GitHub Pages

1. Crea un repositorio nuevo en GitHub y sube estos archivos manteniendo la misma estructura de carpetas.
2. Ve a Settings → Pages → Source, y selecciona la rama principal (`main`) y carpeta raíz (`/`).
3. En un par de minutos tu portfolio estará disponible en `https://tu-usuario.github.io/nombre-del-repo/`.

## Música de fondo

Ve a `audio/README.md` para las instrucciones — solo tienes que subir un archivo `ambient-music.mp3` a esa carpeta y el reproductor ya integrado lo detecta solo.

## Sonido

El botón redondo de la esquina superior derecha activa/desactiva tanto la música como los sonidos de interfaz (al pasar el cursor, abrir y cerrar secciones). Empieza silenciado por defecto — es la persona visitante quien decide activarlo.

## Pendiente

- Sustituir las 9 fichas de "Proyectos" (actualmente en modo "próximamente") por proyectos reales.
- Añadir `audio/ambient-music.mp3` si quieres música de fondo.
