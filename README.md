# Workflow SVM en Orange

Este repositorio contiene un flujo de trabajo basado en **máquinas de soporte vectorial (SVM)** desarrollado con [Orange Data Mining](https://orangedatamining.com/). Este flujo de trabajo permite cargar, procesar, entrenar y evaluar modelos de clasificación utilizando SVM, acompañado de herramientas de análisis para interpretar los resultados.

## Descripción del Workflow

El flujo de trabajo incluye los siguientes pasos principales:

1. **File**: Carga los datos desde un archivo (por ejemplo, CSV, Excel).
2. **Data Table**: Visualiza y explora los datos cargados.
3. **Select Columns**: Selecciona las columnas relevantes para el análisis, como características y etiquetas.
4. **SVM**: Configura y entrena un modelo de máquinas de soporte vectorial.
5. **Test and Score**: Evalúa el rendimiento del modelo utilizando técnicas de validación cruzada o partición de datos.
6. **Predictions**: Genera predicciones a partir del modelo entrenado.
7. **Confusion Matrix**: Analiza el rendimiento del modelo a través de una matriz de confusión.
8. **ROC Analysis**: Evalúa la calidad del modelo mediante curvas ROC.
9. **Evaluation Results**: Muestra un resumen de las métricas de evaluación.


## Resultados Esperados

Al final del flujo, obtendrás:
- Métricas de rendimiento del modelo (precisión, F1-score, etc.).
- Visualización de predicciones.
- Análisis detallado mediante curvas ROC y matrices de confusión.
