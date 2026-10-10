# Supervivencia en el Titanic — Clasificación

Proyecto de ciencia de datos: predicción de supervivencia de pasajeros del Titanic usando Python y scikit-learn. Notebook listo para Google Colab.

## Abrir en Google Colab

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/DanyPreisz/titanic-supervivencia-clasificacion/blob/main/titanic_supervivencia_colab.ipynb)

## Cómo usarlo

1. Hacé clic en el badge de Colab de arriba.
2. O abrí el notebook en GitHub y elegí "Open in Colab".
3. Ejecutá todo el notebook (Runtime → Run all). No necesita GPU.

## Contenido del notebook

- Carga del dataset público
- Inspección y EDA (sexo, clase, edad, familia)
- Feature engineering (Title, FamilySize, IsAlone, HasCabin, Deck, FarePerPerson)
- Pipeline de preprocesamiento (imputación + encoding sin leakage)
- Comparación de modelos: Logistic Regression, Random Forest, Gradient Boosting
- Métricas completas (accuracy, precision, recall, F1, ROC-AUC)
- Importancia de variables
- Tuning rápido con GridSearchCV
- Ejemplo de predicción

**Rango esperado en test:** accuracy ~0.80–0.84 | ROC-AUC ~0.84–0.88

Dataset: https://raw.githubusercontent.com/datasciencedojo/datasets/master/titanic.csv
