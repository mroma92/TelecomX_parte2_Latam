# Telecom X - Parte 2 📊

Este proyecto forma parte de la serie **TelecomX**, cuyo objetivo es analizar y predecir la tasa de **churn (cancelación de clientes)** en una empresa de telecomunicaciones.  
En esta segunda parte se desarrollan **modelos de machine learning** para predecir qué clientes tienen mayor probabilidad de cancelar sus servicios.

## 🚀 Contenido del proyecto
- **Carga y limpieza de datos**: Importación del dataset `telecom_churn_analisis_limpio.csv`, depuración de valores nulos y eliminación de columnas irrelevantes.
- **Análisis exploratorio**: Distribución de clientes y proporción de churn.
- **Preprocesamiento**: Codificación de variables categóricas y normalización de datos.
- **Modelado predictivo**: Entrenamiento y evaluación de modelos de Machine Learning para predecir churn.
- **Evaluación**: Comparación de métricas de desempeño.

## 🛠️ Requisitos
- Python 3.8+
- Bibliotecas principales:
  - pandas
  - numpy
  - scikit-learn
  - matplotlib
  - seaborn

## 📂 Estructura
```
TelecomX_parte2_MR.ipynb   # Notebook principal
telecom_churn_analisis_limpio.csv   # Dataset (preprocesado en la Parte 1)
```

## ▶️ Uso
1. Clona el repositorio.
2. Instala los requisitos:
   ```bash
   pip install -r requirements.txt
   ```
3. Abre el notebook en Jupyter o VSCode:
   ```bash
   jupyter notebook TelecomX_parte2_MR.ipynb
   ```

## 📊 Resultados esperados
- Identificación de los clientes con mayor probabilidad de cancelar.
- Métricas de desempeño de los modelos aplicados (accuracy, precision, recall, f1-score).
- Insights clave para la retención de clientes.

## ✨ Próximos pasos
- Ajuste de hiperparámetros para optimizar modelos.
- Implementación de técnicas de balanceo de datos (SMOTE, undersampling).
- Creación de un dashboard interactivo con los resultados.
