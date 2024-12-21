# Identificación de Clientes en Riesgo de Abandono en Gimnasios

[Notebook de Análisis](./analysis.ipynb): Contiene el código y análisis detallado para este proyecto.

> [!NOTE]
> Este proyecto tiene como objetivo construir un modelo de clasificación que permita identificar clientes en riesgo de abandono en un gimnasio, utilizando datos demográficos, métricas físicas y hábitos de ejercicio. El análisis y desarrollo del modelo se realiza como parte del curso de Econometría I de la Maestría en Investigación de Operaciones.

---

## Descripción General

Se implementaron tres modelos principales:
1. **Random Forest Base:** Modelo inicial para capturar relaciones no lineales.
2. **Random Forest con SMOTE:** Ajustado para balancear clases subrepresentadas.
3. **Gradient Boosting:** Modelo iterativo para corregir errores de clasificación.

El objetivo fue clasificar a los clientes en tres categorías de frecuencia de asistencia semanal:
- **Baja:** 2 o menos sesiones por semana.
- **Media:** De 2 a 4 sesiones por semana.
- **Alta:** Más de 4 sesiones por semana.

---

## Estructura del Repositorio

Este repositorio contiene los siguientes archivos:

- **[analysis.ipynb](analysis.ipynb):** Notebook con el análisis exploratorio, preprocesamiento de datos, implementación de los modelos y evaluación de resultados.
- **[report.pdf](report.pdf):** Informe final del proyecto con descripciones detalladas, resultados y recomendaciones.
- **[dataset.csv](dataset.csv):** Dataset utilizado para entrenar y evaluar los modelos.
- **[Presentación en YouTube](https://www.youtube.com/watch?v=XXXXXXXXXX):** Video con la presentación final del proyecto.

---

## Resultados Principales

| **Modelo**            | **Precisión Global** | **Precisión (Alta)** | **Recall (Alta)** | **Precisión (Baja)** | **Recall (Baja)** | **Precisión (Media)** | **Recall (Media)** |
|------------------------|----------------------|-----------------------|-------------------|-----------------------|-------------------|-----------------------|--------------------|
| Random Forest (Base)  | 70%                 | 61%                  | 45%              | 51%                  | 29%              | 74%                  | 87%               |
| Random Forest (SMOTE) | 63%                 | 46%                  | 58%              | 42%                  | 40%              | 74%                  | 72%               |
| Gradient Boosting     | 61%                 | 46%                  | 55%              | 38%                  | 43%              | 73%                  | 67%               |

---

## Conclusiones

1. El modelo **Random Forest Base** se destaca por su mejor precisión global y recall en la clase predominante (Media).
2. **Random Forest con SMOTE** mejora significativamente en las clases subrepresentadas (Alta y Baja), aunque sacrifica algo de precisión global.
3. **Gradient Boosting** ofrece un balance razonable entre todas las clases, aunque su precisión global es menor.

---

## Recomendaciones

1. Incrementar el volumen de datos para las clases menos representadas (Alta y Baja).
2. Implementar **Random Forest Base** para escenarios donde la precisión global sea la prioridad.
3. Considerar **Gradient Boosting** si se busca un balance entre todas las clases.
4. Ajustar hiperparámetros de los modelos seleccionados para mejorar el desempeño.
5. Evaluar el modelo en un entorno real para confirmar su efectividad.

---

## Autor
**Jonathan Amado**  
Carnet: 14002285

## Licencia
Este proyecto es desarrollado únicamente con fines educativos como parte del curso de Econometría I.

---
**Jonathan Amado**  
Universidad Galileo, Maestría en Investigación de Operaciones

