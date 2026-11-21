# fitnessfacts-media

Vídeos y portadas **finales** de [@fitnessfacts.ia](https://www.instagram.com/fitnessfacts.ia/), listos para programar en Metricool.

Este repositorio es público a propósito: Metricool necesita una URL pública para descargar el vídeo y la portada. Aquí solo entra material que ya se va a publicar en Instagram. Guiones, proyectos, voces y notas viven en el vault privado.

## Estructura

```
AAAA/MM/DD/
├── AAAAMMDD_<slug>_reel_9x16_60fps_vN.mp4   # vídeo final (1080×1920, 60 fps, ≤ 20 MB)
└── AAAAMMDD_<slug>_portada_9x16_vN.jpg      # portada 9:16 (lo importante, dentro del recorte 3:4)
```

## Enlace directo que usa Metricool

```
https://raw.githubusercontent.com/albert0fernandez/fitnessfacts-media/main/AAAA/MM/DD/<archivo>
```

## Reglas

- Solo archivos finales y verificados (ffprobe, sonoridad y revisión visual).
- Nunca claves, tokens ni datos personales.
- Si una versión se descarta, se sustituye por la siguiente (`vN+1`); no se reescribe la historia.
