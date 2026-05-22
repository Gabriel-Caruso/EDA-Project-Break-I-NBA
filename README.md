# EDA Project — Break I NBA

Análisis exploratorio de datos sobre la evolución del juego en la NBA,
centrado en la desaparición de los lanzamientos de media distancia y los jugadores
que desafían esta tendencia.

## Formato

**Introducción:** Imagen actual del estado de los lanzamientos en 2024-25.

**Notebook Carlos:** Por qué desapareció el mid-range. Datos, equipos y modas.

**Notebook Ramiro:** Los outliers. Quién se mantiene fuera de este sistema nuevo de lanzamientos. Jugadores destacables.


## Estructura

- **data/raw** — Datos originales de la NBA API
- **data/processed** — Datos limpios
- **notebooks/carlos** — Análisis del sistema/moda del lanzamiento y el por qué
- **notebooks/ramiro** — Análisis de los jugadores que desafían la tendencia
- **notebooks/general** — Notebook conjunto
- **reports/img** — Visualizaciones exportadas
- **reports/memoria** — Memorias de los dos estudios
- **reports/presentation** — Presentación ppt

## Setup

```bash
pip install -r requirements.txt
```

## Equipo

- **Carlos** — `feature/tendencias-de-lanzamiento`
- **Ramiro** — `feature/outliers`