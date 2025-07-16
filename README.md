# Proyecto de Análisis y Modelado de Datos

## DEAcore7 y ML_core7

Este proyecto consta de dos notebooks principales que abordan el análisis de eficiencia con el método DEA y el modelado predictivo utilizando técnicas de Machine Learning. Los archivos forman parte de un flujo de trabajo orientado al análisis y toma de decisiones basadas en datos de unidades productivas o entidades comparables.

---

## Archivos

- `DEAcore7.ipynb`: Análisis de eficiencia mediante el modelo DEA (Análisis Envolvente de Datos).
- `ML_core7.ipynb`: Modelado predictivo utilizando técnicas de Machine Learning (clasificación, regresión y validación).

---

##  Requisitos

- Python 3.8+
- Bibliotecas necesarias:
  ```bash
  pip install numpy pandas matplotlib seaborn scikit-learn pyDEA openpyxl
  ```

---

##  DEAcore7.ipynb

### Objetivo
Aplicar modelos DEA para medir la eficiencia relativa de un conjunto de unidades decisoras (DMUs), considerando múltiples entradas y salidas.

### Contenido

- Lectura y preprocesamiento de datos.
- Visualización descriptiva de variables.
- Aplicación del modelo DEA con enfoque de rendimientos constantes (CCR) y variables (BCC).
- Clasificación de unidades eficientes e ineficientes.
- Generación de reportes de eficiencia.

### Herramientas Usadas

- `pandas`, `numpy`: manejo de datos.
- `matplotlib`, `seaborn`: gráficos.
- `pyDEA`: cálculo de eficiencia técnica.

---

## ML_core7.ipynb

### Objetivo
Desarrollar modelos de aprendizaje automático para clasificar o predecir eficiencia utilizando etiquetas obtenidas del análisis DEA.

### Contenido

- Preparación de los datos etiquetados desde el modelo DEA.
- Aplicación de modelos:
  - Árboles de decisión (`DecisionTreeClassifier`)
  - Bosques aleatorios (`RandomForestClassifier`)
  - Regresores para predicción continua (`LinearRegression`, etc.)
- Validación cruzada y métricas de evaluación:
  - Precisión, exactitud, recall, F1-score.
- Matrices de confusión y curvas ROC.

### Herramientas Usadas

- `scikit-learn`: modelado, entrenamiento, validación.
- `pandas`, `numpy`: transformación de datos.
- `matplotlib`, `seaborn`: visualización de resultados.

---

## ▶ Ejecución

1. Clonar o descargar este repositorio.
2. Abrir los notebooks en JupyterLab o Google Colab.
3. Ejecutar celda por celda, asegurándose de que los archivos de datos estén en el mismo directorio o actualizando las rutas.

---

##  Notas

- El análisis DEA puede ser sensible a la escala y calidad de los datos. Se recomienda normalizar o estandarizar variables si es necesario.
- Las etiquetas de eficiencia generadas por DEA son insumo directo para el modelo de Machine Learning. La calidad de estas afecta directamente el rendimiento del modelo predictivo.

## Autora
- Marcela Rubio Briones - Machine Learning (b2b-sonda-ds-mayo-2025)

