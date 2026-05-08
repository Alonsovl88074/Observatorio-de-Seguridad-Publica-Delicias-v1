# Observatorio Delictivo V3

## Contenido del paquete
- index.html
- incidencias-normalizadas.json
- colonias.geojson
- centroides-normalizados.json
- quality-report.json
- catalogo-colonias.json

## Mejoras V3
- Catálogo maestro de colonias deduplicado.
- Polígonos consolidados por colonia.
- Centroides deduplicados por colonia.
- Modo de puntos reales desactivado automáticamente cuando la fuente no trae coordenadas.
- Todo funciona con archivos locales, ideal para GitHub Pages.

## Publicación en GitHub Pages
1. Descomprime el ZIP.
2. Sube todos los archivos a la raíz del repositorio.
3. En GitHub ve a Settings > Pages.
4. Selecciona Deploy from a branch.
5. Elige la rama principal y la carpeta /root.
6. Guarda y espera la publicación.

## Desarrollo local
python -m http.server 8000
