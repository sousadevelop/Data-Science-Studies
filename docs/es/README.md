# Data Science Labs

## Visión general

Este repositorio es un laboratorio central de estudios de análisis de datos, estadística, ciencia de datos y machine learning. Los materiales son labs de aprendizaje y ejercicios prácticos, no proyectos profesionales listos para producción.

El contenido de los notebooks existentes fue preservado sin modificaciones.

## Estructura

```text
notebooks/
├── pandas/
├── numpy/
├── statistics/
├── visualization/
├── machine-learning/
└── deep-learning/
datasets/
└── numpy/
```

## Estudios disponibles

### Pandas

[`notebooks/pandas/tratamento_enem_2019.ipynb`](../../notebooks/pandas/tratamento_enem_2019.ipynb) es un lab de tratamiento y exploración inicial de microdatos ENEM 2019 con pandas y NumPy.

El notebook depende del archivo externo `microdados_enem_2019_sp.csv`, que no está versionado en este repositorio.

### NumPy

[`datasets/numpy/`](../../datasets/numpy/) contiene datasets de apoyo para estudios de NumPy:

- `apples_ts.csv`
- `bytebank.csv`
- `citrus.csv`

Los archivos fueron reorganizados sin cambios de contenido.

### Áreas preparadas

Hay directorios preparados para futuros labs de estadística, visualización, machine learning y deep learning.

## Ejecución de los labs

```bash
pip install -r requirements.txt
jupyter notebook
```

Ejecuta los notebooks desde la raíz del repositorio y verifica si el lab requiere datasets externos.

## Directrices

- Clasifica los notebooks por su tema principal de aprendizaje.
- Conserva los notebooks como registros didácticos.
- No inventes resultados ni conclusiones.
- No versiones datasets sensibles, credenciales o archivos locales.
- Documenta las dependencias externas necesarias para reproducir un lab.
