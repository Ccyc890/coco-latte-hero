# coco latte — hero móvil

Hero de portada para móvil de **coco latte** (cafetería de especialidad, Bilbao).
Un único `index.html` con el CSS y el JS dentro: no hay build, no hay dependencias
salvo Google Fonts (Instrument Serif + Inter).

## Ver en local

```bash
python3 -m http.server 8912
# http://127.0.0.1:8912/index.html
```

## Publicar en Cloudflare Pages

1. Cloudflare Dashboard → **Workers & Pages** → **Create** → **Pages** → *Connect to Git*.
2. Elige `Ccyc890/coco-latte-hero`, rama `main`.
3. Build command: *(vacío)* — Framework preset: *None* — Build output directory: `/`.
4. Deploy. Cada `push` a `main` republica.

## Qué contiene

- Paleta blanco/negro: `#FBFAF7` y `#131210` (más neutros de apoyo).
- Logotipo tipográfico en Instrument Serif, banda de foto con paralaje suave,
  lema, reloj real de Europe/Madrid, horario de cocina y señal «desliza».
- Menú a pantalla completa en negro con enlaces en serif crema (Carta, Galería,
  Ubicación, Contacto).
- Sin ningún badge ni atribución de plantilla.
- Comprobado a 390×844, 834×1112 y 1280×900: la sección cabe sin recortes,
  sin desbordamiento horizontal, sin errores de consola, y con
  `prefers-reduced-motion` el movimiento se desactiva.
