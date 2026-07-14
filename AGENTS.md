# Guía para IAs — Presentación Marco Jurídico de los Negocios

## Archivos

```
presentacion/
├── index.html        ← Presentación principal (Compliance, 26 slides)
├── img/              ← Imágenes (sare_diagram_*.png, sare_pag6_img*.png)
└── AGENTS.md         ← Este archivo
```

## Cambios realizados (sesión 14/07/2026)

### Limpieza
- Eliminados archivos `_sare_*` del directorio raíz `H:\Mi unidad\UCC\` (artefactos de exportación, ~63 archivos)
- Eliminado `presentacion_clase_muestra.html` (redundante con `index.html`)
- Movidas 8 imágenes PNG a `img/` subdirectorio
- Actualizadas rutas en `unidad6-compliance.html` → ahora es `index.html` (se renombró)

### Pantalla completa
- `padding` en slides: `3rem 5rem` → `1rem 1.5rem`
- `max-width` en slide-content: `1100px` → `100%`

### Navegación
- Barra inferior: `64px` → `32px`
- Timeline de progreso con títulos de slide (arriba de la barra inferior, `18px`)
- Flechas de navegación movidas de centro a parte superior (`top: 0.6rem`)
- Dots reducidos a `6px`

### Funcionalidades agregadas
- **Fullscreen**: botón `⛶` + tecla F
- **Alto contraste**: botón `☀/🌙` + tecla C
- **Zoom**: teclas +/-/0 + controles visuales esq. inferior derecha
- **Ir a slide**: tecla G (prompt)
- **Ayuda de atajos**: tecla `?` (overlay)
- **Timeline navegable**: barra con títulos, click para ir al slide

### Diseño de datos
- **Slide 8 (Beneficios SARE)**: tarjetas reemplazadas por barras horizontales animadas con gradientes
- **Slide 25 (Calendario Anual)**: tabla reemplazada por grid de 4 columnas agrupado por frecuencia (mensual/bimestral/semestral/anual) con códigos de color

### Estructura CSS
- `tl-bar`, `tl-seg` — timeline de progreso
- `bar-btn` — botones fullscreen/contraste
- `help-overlay`, `help-box`, `help-grid` — overlay de atajos
- `high-contrast` — modo alto contraste
- `zoom-controls`, `zoom-btn`, `zoom-level` — controles de zoom
- `bar-group`, `bar-row`, `bar-track`, `bar-fill`, `bar-sub` — gráficas de barras
- `cal-grid`, `cal-col`, `cal-items`, `cal-item` — grid de calendario

### Pendiente
- El visual companion (brainstorming) no funcionó en Windows (bash script incompatible)
