# EDA Project — Break I NBA

Análisis exploratorio de datos sobre la evolución del juego en la NBA,
centrado en la desaparición del tiro de media distancia y los jugadores
que desafían la tendencia.

## Narrativa

**Inicio:** Comparativa visual de tiros en la NBA en 2000 y 2025-26. "El mid-range ha muerto"

**Rama Ramiro:** Por qué desapareció el mid-range. Datos, equipos y modas.

**Rama Carlos:** Los outliers. Jugadores, equipos y más. Quién se mantiene fuera de esta moda.

**Conclusión:** Conclusión de ambos estudios.

## Estructura

- **data/raw** — Datos originales de la NBA API
- **data/processed** — Datos limpios y listos para analizar
- **notebooks/ramiro** — Análisis del sistema y el por qué
- **notebooks/carlos** — Análisis de outliers
- **notebooks/general** — Notebooks conjuntos
- **src** — Funciones compartidas
- **reports/img** — Visualizaciones exportadas
- **docs** — Web y materiales de presentación

## Setup

```bash
pip install -r requirements.txt
```

## Equipo

- **Ramiro** — `feature/tendencias-de-tiro`
- **Carlos** — `feature/outliers`