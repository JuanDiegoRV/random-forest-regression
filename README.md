# Random Forest para regresión

Proyecto correspondiente al Tema 10 de la Sesión 13: `RandomForestRegressor` aplicado a la predicción de tarifas de taxi.

## Ejecución

Desde esta carpeta:

```bash
python -m pip install -r requirements.txt
jupyter notebook random_forest_regression.ipynb
```

En la primera ejecución el notebook carga `seaborn`'s `taxis`, guarda una copia en `data/taxis.csv` y después trabaja con esa copia local.

## Contenido

- Fundamento de árboles de decisión y Random Forest.
- Exploración y visualización del conjunto `taxis`.
- Pipeline para variables numéricas y categóricas.
- Comparación contra un árbol individual.
- Métricas MAE, RMSE y R².
- Importancia de variables.
- Ajuste básico de hiperparámetros con validación cruzada.
- Ventajas, desventajas y preguntas de discusión.
