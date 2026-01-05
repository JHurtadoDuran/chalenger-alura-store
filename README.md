# Alura Store Latam — Análisis de Ventas 🛒📊

**Descripción**

Este repositorio contiene el análisis de ventas de 4 tiendas (Tienda 1–4) realizado como parte del Challenge Alura Store Latam. Incluye código en un notebook (`AluraStoreLatam.ipynb`) que calcula ingresos, ventas por categoría, calificaciones, productos más/menos vendidos, análisis geográfico y exporta visualizaciones e informes.

## Contenido del repositorio

- `AluraStoreLatam.ipynb` — Notebook principal con todo el análisis.
- `informe_final_sr_juan.md` — Informe final en Markdown generado desde el notebook.
- `resumen_metrics_tiendas.csv` — CSV resumen con métricas por tienda.
- `mapa_ventas_Tienda_*.html` — Mapas interactivos (generados si `folium` está disponible).
- Imágenes PNG generadas: `ingresos_totales.png`, `ingresos_distribucion_pie.png`, `top5_categorias.png`, `precio_vs_calificacion.png`, `ingresos_mensuales.png`, `evolucion_acumulada.png`.
- `alura_store_exports.zip` — ZIP con artefactos exportados (si fue generado).

## Requisitos ✅

- Python 3.8+ (recomendado)
- Recomendadas bibliotecas (instalar con pip):

```bash
pip install pandas matplotlib seaborn numpy jupyter folium
```

> Nota: `folium` es opcional; si no está disponible, el notebook aún ejecuta análisis estático y muestra un aviso cuando falta.

## Cómo ejecutar

1. Abrir el entorno (por ejemplo, `jupyter notebook` o `jupyter lab`).
2. Abrir `AluraStoreLatam.ipynb` y ejecutar las celdas en orden (o ejecutar todas de una vez).
3. Para generar los artefactos (PNG, CSV, informe y ZIP) asegúrate de ejecutar las celdas hacia el final del notebook donde se exportan gráficos y se crea `resumen_metrics_tiendas.csv` e `informe_final_sr_juan.md`.

## Salidas esperadas 🗂️

- Informe Markdown: `informe_final_sr_juan.md`
- CSV resumen: `resumen_metrics_tiendas.csv`
- Mapas HTML por tienda: `mapa_ventas_Tienda_*.html` (si `folium` está instalado)
- PNGs con visualizaciones (ver lista arriba)
- ZIP con artefactos: `alura_store_exports.zip`

## Buenas prácticas / Sugerencias 💡

- Si vas a compartir o desplegar, crea un `requirements.txt` con las versiones reales de las librerías.
- Para reproducibilidad, considera usar un entorno virtual (`venv` o `conda`).
- Añade datos o ejemplos de `env` si se requieren variables de entorno.

## Cómo contribuir

1. Haz un fork del repositorio.
2. Crea una rama con tu cambio: `git checkout -b feature/mi-cambio`.
3. Haz commits claros y envía un pull request.

## Licencia

Este proyecto puede compartirse bajo **MIT License** (ajústalo según prefieras).

