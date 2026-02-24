# MicroDSI · M2-S10 (Identificación de Procesos)

Mini-proyecto web estático para practicar:
- Inventario L1 (Verbo + Objeto)
- Priorización (Impacto/Esfuerzo/Riesgo)
- SIPOC (1 página)
- Export a Markdown (.md)

## Estructura
- `index.html`: portada
- `feed.html`: micro-lecciones por track (ITSM/HR/Procurement) con “marcados”
- `pista.html`: caso guiado por track con respuestas guardadas localmente
- `lab.html`: editor del entregable con export .md y guardado local
- `assets/styles.css`: estilos
- `assets/app.js`: lógica de track, feed, pistas, lab y export

## Uso
Abre `index.html` con cualquier navegador.
El estado se guarda en `localStorage` (no hay backend).

## Publicación en GitHub Pages
1. Sube los archivos al repo
2. Settings → Pages
3. Branch: `main` y folder `/root`
4. Save
5. La web quedará publicada con tu URL de Pages
