# Directorio de Código

Este directorio contiene notebooks en Python y PySpark que implementan modelos de machine learning para el análisis del BoT-IoT Dataset. Los notebooks están organizados en dos categorías principales: **Python** y **PySpark**. A continuación se detalla el contenido de cada uno y la metodología utilizada.

## Contenido del Directorio

El directorio se estructura de la siguiente manera:

/codigo
│
├── /python
│ ├── Ridge_Classifier_Python.ipynb
│ ├── RandomForest_Classifier_Python.ipynb
│ ├── XGBoost_Classifier_Python.ipynb
│ ├── CrossValidation_Bootstrap_Python.ipynb
│ └── README.md
│
├── /pyspark
│ ├── Ridge_Classifier_PySpark.ipynb
│ ├── RandomForest_Classifier_PySpark.ipynb
│ ├── XGBoost_Classifier_PySpark.ipynb
│ ├── CrossValidation_Bootstrap_PySpark.ipynb
│ └── README.md
│

## Notebooks de Python

### 1. Ridge_Classifier_Python.ipynb

Este notebook implementa el modelo de **Ridge Classifier** utilizando `scikit-learn`. Se explora cómo ajustar el parámetro de regularización `alpha` para mejorar el rendimiento del modelo en la tarea de clasificación de tráfico de red.

**Tareas realizadas en este notebook**:
- Preparación de datos y preprocesamiento.
- Implementación del modelo Ridge Classifier.
- Evaluación del modelo utilizando técnicas de **Cross-Validation** y **Bootstrap**.

### 2. RandomForest_Classifier_Python.ipynb

Este notebook implementa el modelo de **Random Forest Classifier** con `scikit-learn`. Se exploran diferentes hiperparámetros, como el número de árboles y la profundidad máxima, para optimizar el modelo.

**Tareas realizadas en este notebook**:
- Preparación de datos y preprocesamiento.
- Implementación del modelo Random Forest Classifier.
- Evaluación del modelo utilizando **Cross-Validation** y **Bootstrap**.

### 3. XGBoost_Classifier_Python.ipynb

Este notebook implementa el modelo de **XGBoost Classifier** utilizando la biblioteca `xgboost`. Se ajustan parámetros como la tasa de aprendizaje y el número de árboles para maximizar el rendimiento del modelo.

**Tareas realizadas en este notebook**:
- Preparación de datos y preprocesamiento.
- Implementación del modelo XGBoost Classifier.
- Evaluación del modelo utilizando **Cross-Validation** y **Bootstrap**.

### 4. CrossValidation_Bootstrap_Python.ipynb

Este notebook proporciona una implementación de técnicas de evaluación **Cross-Validation** y **Bootstrap** aplicadas a los modelos de machine learning. Se comparan los resultados obtenidos con los diferentes métodos de evaluación.

**Tareas realizadas en este notebook**:
- Implementación de técnicas de **Cross-Validation**.
- Implementación de técnicas de **Bootstrap**.
- Comparación de resultados entre las diferentes técnicas de evaluación.

## Notebooks de PySpark

### 1. Ridge_Classifier_PySpark.ipynb

Este notebook implementa el modelo de **Ridge Classifier** utilizando PySpark y `pyspark.ml`. Se explora cómo ajustar el parámetro de regularización `regParam` para mejorar el rendimiento del modelo en la tarea de clasificación.

**Tareas realizadas en este notebook**:
- Preparación de datos utilizando RDDs y `DataFrames`.
- Implementación del modelo Ridge Classifier en PySpark.
- Evaluación del modelo utilizando técnicas de **Cross-Validation** y **Bootstrap**.

### 2. RandomForest_Classifier_PySpark.ipynb

Este notebook implementa el modelo de **Random Forest Classifier** utilizando PySpark y `pyspark.ml`. Se exploran diferentes hiperparámetros como el número de árboles y la profundidad máxima.

**Tareas realizadas en este notebook**:
- Preparación de datos utilizando RDDs y `DataFrames`.
- Implementación del modelo Random Forest Classifier en PySpark.
- Evaluación del modelo utilizando **Cross-Validation** y **Bootstrap**.

### 3. XGBoost_Classifier_PySpark.ipynb

Este notebook implementa el modelo de **XGBoost Classifier** en un entorno PySpark utilizando la biblioteca `sparkxgb`. Se ajustan parámetros como la tasa de aprendizaje y el número de árboles.

**Tareas realizadas en este notebook**:
- Preparación de datos utilizando RDDs y `DataFrames`.
- Implementación del modelo XGBoost Classifier en PySpark.
- Evaluación del modelo utilizando **Cross-Validation** y **Bootstrap**.

### 4. CrossValidation_Bootstrap_PySpark.ipynb

Este notebook proporciona una implementación de técnicas de evaluación **Cross-Validation** y **Bootstrap** en un entorno PySpark. Se comparan los resultados obtenidos con los diferentes métodos de evaluación.

**Tareas realizadas en este notebook**:
- Implementación de técnicas de **Cross-Validation** en PySpark.
- Implementación de técnicas de **Bootstrap** en PySpark.
- Comparación de resultados entre las diferentes técnicas de evaluación.

## Instalación

Para ejecutar los notebooks de Python, necesitas instalar las siguientes bibliotecas:

```bash
pip install pandas scikit-learn xgboost



### Detalles del contenido del `README.md`

- **Contenido del Directorio**: Estructura del directorio con los notebooks organizados en carpetas para Python y PySpark.
- **Notebooks de Python**: Descripción de los notebooks que utilizan `scikit-learn` para diferentes modelos y técnicas de evaluación.
- **Notebooks de PySpark**: Descripción de los notebooks que utilizan `pyspark` para diferentes modelos y técnicas de evaluación.
- **Instalación**: Instrucciones para instalar las bibliotecas necesarias para ejecutar los notebooks.
- **Ejecución de los Notebooks**: Pasos para clonar el repositorio, navegar al directorio de código, y abrir los notebooks.
- **Contribuciones**: Enlace a las directrices para contribuir al proyecto.
- **Licencia**: Información sobre la licencia del proyecto.
- **Contacto**: Información de contacto para más detalles.

Este `README.md` proporciona toda la información necesaria para que los usuarios entiendan los notebooks, instalen las dependencias y ejecuten el código. Si tienes más detalles específicos que quieras añadir, no dudes en decírmelo.
