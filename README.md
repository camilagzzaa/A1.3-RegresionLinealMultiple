# A1.3-Regresión lineal múltiple (NASA)

## Índice
1. [Dataset](./A1.3%20NASA.csv)
2. [Notebook](./A1.3%20Regresión%20lineal%20múltiple.ipynb)
3. [Reporte HTML](./A1.3%20Regresión%20lineal%20múltiple.html)
4. [README](./README.md)

---

## Descripción
Este proyecto implementa un modelo de regresión lineal múltiple con datos de la NASA, cuyo objetivo es predecir la presión sonora a partir de cinco variables: frecuencia, ángulo, longitud, velocidad y espesor.

El código carga el dataset (`A1.3 NASA.csv`), divide los datos en entrenamiento (70%) y prueba (30%), entrena el modelo con **statsmodels**, muestra coeficientes y p-values para evaluar significancia, calcula métricas de desempeño (RSE y R²) en ambos conjuntos y finalmente genera una gráfica de valores reales vs predichos para el conjunto de validación.

Se utilizan las librerías: pandas, numpy, matplotlib, statsmodels y opcionalmente scikit-learn y seaborn.

