# FID SDK · Guía de color

Cómo se organiza, se nombra y se aplica el color en el SDK de FID: anatomía, marca del cliente, tokens, estados de interacción, accesibilidad y código.

**[Abrir la guía →](https://ricardofalcondev.github.io/fid-sdk-guia-color/)**

| Pestaña | Qué tiene |
|---|---|
| Resumen | Introducción, anatomía, capas, glosario, marca del cliente, nombres y grupos de tokens, estados de interacción, accesibilidad |
| Guías | Superficies, dónde va la marca, estados fijos, texto sobre color, siempre con tokens |
| Tokens | Referencia de los 71 tokens semánticos (con selector de marca) y los 98 primitivos |
| Código | Uso en CSS, aplicar la marca, la escala de marca y `tokens.json` |

Fuente de verdad: archivo de Figma "FID SDK — Variables". La documentación completa de personalización está en [fid-sdk-documentacion](https://ricardofalcondev.github.io/fid-sdk-documentacion/).

## Regenerar

Requiere el paquete `FID SDK - Assets` (CSS, `tokens.json` y `DESIGN.md`):

```bash
python3 fuente/build.py "ruta/a/FID SDK - Assets"
```
