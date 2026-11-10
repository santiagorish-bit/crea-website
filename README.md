# crea-website

Web one-page de **CREA · Crea Contenidos y Publicidad**, productora audiovisual y estudio multimedia en Santa Rosa, La Pampa.

Todo está en `index.html` (HTML + CSS + JS, sin dependencias ni build). Solo carga Google Fonts (Anton, Inter e IBM Plex Mono) y el mapa embebido de Google Maps.

## Antes de publicar

Buscá en `index.html` los comentarios `REEMPLAZAR`, `CONFIRMAR` y `ACLARAR`.

Los archivos van en estas rutas, al lado de `index.html`. Las fotos y los videos se pasan a blanco y negro por CSS, así que podés subirlos en color.

Mientras falte una foto, la web muestra una foto de stock de `img/placeholder/` (Unsplash, ver `img/placeholder/CREDITOS.md`) con el epígrafe "Imagen ilustrativa". Cuando subís la tuya con el nombre de la tabla, reemplaza sola a la de stock y la etiqueta desaparece. No hace falta tocar el HTML.

| Archivo | Qué es |
| --- | --- |
| `video/hero-crea.mp4` | Video del hero, dentro de la píldora. MP4 H.264, 1920×1080, 6 a 12 s en loop, sin audio, menos de 4 MB. Mientras no esté, la píldora muestra 5 fotos de stock que cambian con la palabra rotativa |
| `img/hero-poster.jpg` | Primer cuadro de ese video |
| `img/estudio-croma-verde.jpg` | Estudio con croma verde (horizontal, 1600×1000) |
| `img/estudio-podcast.jpg` | Set de podcast (cuadrada, 1000×1000) |
| `img/estudio-youtube.jpg` | Set de YouTube (cuadrada) |
| `img/estudio-croma-azul.jpg` | Estudio con croma azul (cuadrada) |
| `img/estudio-fotos.jpg` | Sesión de fotos o producción (cuadrada) |
| `img/fiebre-de-mundial.jpg` | Foto de Fiebre de Mundial con pantalla y tribuna (panorámica 21:9) |
| `img/logo-vorterix-santa-rosa.svg` | Logo de Vorterix Santa Rosa en blanco |
| `img/logo-fuera-de-fase.svg` | Logo de Fuera de Fase en blanco |
| `img/og-crea.jpg` | Imagen para compartir en redes, 1200×630. Ya hay una provisoria hecha con el hero, pero tiene una foto de stock en la píldora: reemplazala cuando estén las fotos reales |

Además:

- Logo de CREA en SVG (en el nav), en lugar del logotipo hecho con texto y barras en CSS.
- Favicon definitivo.
- Embed del reel de Instagram de Fiebre de Mundial.
- Dominio real en `canonical`, Open Graph y schema (hoy dice `tudominio.com.ar`).
- Dirección exacta del estudio: en el mapa (`q=`), en el bloque de contacto y como `streetAddress` en el schema.
- Texto de Canal 922 y su relación con Sensa (@sensaok).
- Respuestas marcadas con `CONFIRMAR` en las preguntas frecuentes: mínimo de horas, equipos incluidos, plazos de entrega y cómo se contrata Starlink.

## Detalles

- Tocar el logo estando arriba de todo repite la intro del hero.
- El botón de pausa de la píldora frena el video, las luces y la palabra rotativa.
- Con "reducir movimiento" activado en el sistema, la página arranca en su estado final, sin animaciones.
