# Identificación de Clientes en Riesgo de Abandono en Gimnasios

[Notebook de Análisis](./analysis.ipynb): Contiene el código y análisis detallado para este proyecto.

> [!NOTE]
> Este proyecto tiene como objetivo construir un modelo de clasificación que permita identificar clientes en riesgo de abandono en un gimnasio, utilizando datos demográficos, métricas físicas y hábitos de ejercicio. El análisis y desarrollo del modelo se realiza como parte del curso de Econometría I de la Maestría en Investigación de Operaciones.

## Autor
**Jonathan Amado**  
Carnet: 14002285

## Descripción del Proyecto
Este proyecto aborda un problema común en gimnasios: la retención de clientes. Mediante el uso de técnicas de minería de datos y aprendizaje de máquina, se busca identificar patrones que permitan clasificar a los miembros del gimnasio en diferentes niveles de frecuencia de asistencia:

- **Baja Frecuencia (Riesgo de Abandono):** Menos de 2 sesiones por semana.
- **Frecuencia Moderada:** Entre 2 y 4 sesiones por semana.
- **Frecuencia Alta:** Más de 4 sesiones por semana.

El análisis se enfoca en variables clave como duración de sesiones, frecuencia cardíaca, composición corporal, y hábitos de hidratación, entre otras.

## Archivos Principales
- **`dataset.csv`**: Archivo con los datos utilizados para el análisis.
- **`analysis.ipynb`**: Notebook que contiene el análisis exploratorio, visualizaciones y preparación de los datos.
- **`model.py`**: Código para la construcción y evaluación del modelo de clasificación.
- **`presentation.pdf`**: Presentación con los resultados y conclusiones del proyecto.

## Estructura del Repositorio
```
├── README.md               # Descripción del proyecto
├── dataset.csv             # Datos utilizados para el análisis
├── analysis.ipynb          # Análisis exploratorio y preparación de datos
├── results                 # Resultados y gráficas generadas
├── presentation.pdf        # Presentación final
└── requirements.txt        # Dependencias del proyecto
```

## Tecnologías Utilizadas
- **Python**: Lenguaje principal para el análisis y modelado.
- **Bibliotecas**:
  - `pandas`: Manipulación y limpieza de datos.
  - `numpy`: Operaciones matemáticas.
  - `matplotlib` y `seaborn`: Visualización de datos.
  - `scikit-learn`: Construcción y evaluación del modelo.

## Cómo Ejecutar el Proyecto
1. Clona el repositorio:
   ```bash
   git clone https://github.com/tu_usuario/riesgo_abandono_gimnasios.git
   ```
2. Instala las dependencias:
   ```bash
   pip install -r requirements.txt
   ```
3. Abre el notebook y ejecuta el análisis exploratorio:
   ```bash
   jupyter notebook analysis.ipynb
   ```
4. Corre el script del modelo:
   ```bash
   python model.py
   ```

## Resultados Esperados
- Un modelo de clasificación con métricas de evaluación claras (precisión, recall, F1-score).
- Visualizaciones que expliquen el impacto de las variables en la clasificación.
- Recomendaciones para estrategias de retención en gimnasios.

## Licencia
Este proyecto es desarrollado únicamente con fines educativos como parte del curso de Econometría I.

---
**Jonathan Amado**  
Universidad Galileo, Maestría en Investigación de Operaciones

