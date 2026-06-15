# Esto No Debería Pasar — Línea de Tiempo de Impacto

Parte del proyecto **Colombia Sin Venda**.

## Qué es

Una PWA que toma como punto de partida un video viral (un menor con uniforme camuflado de un grupo armado ilegal hablando frente a cámara) y construye alrededor de él una **cronología de impacto**: qué dice la ley, qué cifras existen, qué grupos están detrás del reclutamiento de menores en Colombia y qué se puede hacer al respecto.

No se centra en quién subió el video ni en su narrativa política, sino en el hecho de fondo que el video documenta sin querer: **el reclutamiento forzado de niños, niñas y adolescentes sigue activo en Colombia.**

## Contenido

- **Contexto del video**: qué se ve y por qué constituye una infracción al Derecho Internacional Humanitario, independientemente del grupo o discurso.
- **Línea de tiempo**: desde el marco legal internacional (2000), el Acuerdo de Paz (2016), hasta las cifras de 2024, 2025 y el primer trimestre de 2026.
- **Cifras oficiales**: datos de la Defensoría del Pueblo (386 casos en 2025, 651 en 2024, 19 nuevos en el primer trimestre de 2026, distribución por grupo armado y población indígena).
- **Llamado a la acción**: línea ICBF 141 para reportes, y mensaje sobre no compartir el video sin contexto (riesgo de revictimización y propaganda).
- **Fuentes citadas**: Defensoría del Pueblo, Pulzo, LaFM, Infobae, International Crisis Group (todas de enero–abril 2026).

## Archivos

- `index.html` — App principal (todo en un solo archivo, HTML/CSS/JS)
- `manifest.json` — Manifest PWA
- `sw.js` — Service Worker (modo offline básico)
- `icon-192.png`, `icon-512.png` — Iconos de la app
- `og-image.png` — Imagen de previsualización para WhatsApp/redes

## Despliegue

Pensado para GitHub Pages, dentro del repositorio `colombia-sin-venda`, en una carpeta como `cronologia-impacto/`.

```
haroldco45.github.io/colombia-sin-venda/cronologia-impacto/
```

## Actualización de cifras

Las cifras de reclutamiento cambian cada trimestre según los reportes de la Defensoría del Pueblo (defensoria.gov.co). Se recomienda verificar y actualizar los datos de la sección "Cifras clave" cada vez que se publique un nuevo informe.

---

Desarrollada por **Vibras Positivas HM** — Derechos de Autor Reservados
