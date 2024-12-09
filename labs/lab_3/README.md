## [Laboratorio 3 Notebook](lab_3.ipynb) 
### Econometría I

> [!NOTE]
> Este repositorio contiene el código y los resultados del Laboratorio 3 del curso **Econometría I**. En este laboratorio, se realiza un análisis de regresión utilizando un dataset proporcionado, con el objetivo de predecir el precio (`Price (in USD)`) como variable objetivo. 

## Objetivos del Laboratorio

1. **Exploración y análisis de variables**:
   - Clasificar las variables en numéricas continuas, numéricas categóricas y categóricas.
   - Realizar un análisis descriptivo y gráfico para comprender las relaciones entre las variables y el target.

2. **Entrenamiento de Modelos de Regresión**:
   - Separar el dataset en conjuntos de entrenamiento (85%) y prueba (15%).
   - Entrenar al menos 5 modelos de regresión distintos utilizando validación cruzada.
   - Seleccionar los dos mejores modelos según el RMSE promedio.

3. **Evaluación Final de Modelos**:
   - Reentrenar los dos mejores modelos con el conjunto de entrenamiento completo.
   - Evaluar los modelos reentrenados con el conjunto de prueba y calcular el RMSE.
   - Realizar visualizaciones como histogramas y scatter plots para analizar las predicciones y los valores reales.

## Contenido del Repositorio

- `Lab_3_Regresiones.ipynb`: Notebook de Jupyter con la implementación completa de los pasos requeridos en el laboratorio.
- `dataset.csv`: Dataset utilizado para el análisis y entrenamiento de los modelos.
- `resultados/`: Carpeta donde se almacenan gráficos, tablas y resultados del análisis.
- `README.md`: Este archivo, que proporciona una descripción del laboratorio y su contenido.

## Requisitos

Para ejecutar el código de este laboratorio, se recomienda instalar las siguientes bibliotecas de Python:
- `pandas`
- `numpy`
- `matplotlib`
- `seaborn`
- `scikit-learn`
- `statsmodels`

Puedes instalar estas dependencias ejecutando:
```bash
pip install -r requirements.txt
