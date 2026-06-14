## Core MVP:
1. Upload survey PDF
2. Georeference it on a map
3. Trace property boundary + existing features
4. Store geometry in PostGIS
5. Draw proposed structure
6. Auto-check setbacks/septic/well/drainage buffers
7. Export permit site plan PDF

## Open-source stack:
Frontend: Vite + React/Lit + MapLibre GL JS
Desktop GIS: QGIS
Database: PostgreSQL + PostGIS
Backend: Node/Express or FastAPI
PDF/Image: pdf.js + OpenCV
Maps: county GIS / aerial imagery / OpenStreetMap
Export: Playwright or MapLibre print → PDF
