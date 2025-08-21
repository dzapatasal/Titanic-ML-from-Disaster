# Titanic - Machine Learning from Disaster 🚢

Este proyecto aborda el clásico challenge de Kaggle utilizando un enfoque modular y reproducible. Está diseñado para facilitar la exploración, limpieza, modelado y evaluación de datos, con scripts reutilizables y documentación clara.

## Estructura
- `data/`: Datos crudos y procesados
- `notebooks/`: Análisis paso a paso
- `scripts/`: Funciones reutilizables
- `models/`: Modelos entrenados
- `artifacts/`: Resultados y archivos de envío

```
kaggle_titanic/
├── data/
│   ├── raw/              # Archivos originales descargados de Kaggle
│   ├── processed/        # Datos limpios y transformados
├── notebooks/
│   ├── 01_exploration.ipynb
│   ├── 02_cleaning.ipynb
│   ├── 03_modeling.ipynb
│   └── 04_evaluation.ipynb
├── models/
│   └── random_forest.pkl
├── scripts/
│   ├── utils_io.py       # Funciones para cargar/guardar objetos
│   └── preprocessing.py  # Funciones de limpieza y transformación
├── artifacts/
│   └── submission.csv    # Archivo para subir a Kaggle
├── README.md
└── requirements.txt
```

## Requisitos
Instala las dependencias con:

```bash
pip install -r requirements.txt
