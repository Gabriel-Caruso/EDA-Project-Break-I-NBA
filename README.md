# EDA Project — Break I NBA

Análisis exploratorio de datos sobre la evolución del juego en la NBA,
centrado en la desaparición de los lanzamientos de media distancia y los jugadores
que desafían esta tendencia.

## Formato

**Introducción:** Comparativa visual de tiros en la NBA en 2000 y 2025-26. "El mid-range ha muerto"

**Rama Carlos:** Por qué desapareció el mid-range. Datos, equipos y modas.

**Rama Ramiro:** Los outliers. Quién se mantiene fuera de este sistema nuevo de lanzamientos. Jugadores, equipos y más.

**Conclusión:** Conclusión de ambos estudios.

## Estructura

- **data/raw** — Datos originales de la NBA API
- **data/processed** — Datos limpios
- **notebooks/carlos** — Análisis del sistema/moda del lanzamiento y el por qué
- **notebooks/ramiro** — Análisis de outliers
- **notebooks/general** — Notebooks conjuntos
- **src** — Funciones compartidas
- **reports/img** — Visualizaciones exportadas
- **docs** — Presentación y material de presentación

## Setup

```bash
pip install -r requirements.txt
```

## Equipo

- **Carlos** — `feature/tendencias-de-lanzamiento`
- **Ramiro** — `feature/outliers`