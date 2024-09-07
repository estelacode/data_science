# Data Science

## Machine Learning Notebooks:

APRENDIZAJE SUPERVISADO

* 📄 **Notebook 1:** ML_Clasificacion.ipynb  
Objetivo: predecir si una persona cobra mas de 50000 dólares en un año.
Dataset: adult.csv

    * **Fase 1**. Análisis Exploratorio de los datos(EDA)
    * **Fase 2**. Prepocesamiento de los datos
      - Limpieza de los datos
      - Tratamiento de valores Nan
      - Detección de outliers
      - Extracción de características
      - Tranformación de los datos
      - Reducción de dimensionalidad
     
    * **Fase 3**. Entrenamiento de un modelo de Clasificación basado en Decision Tree
    * **Fase 4**. Análisis de resultados
        * Matriz de confusión
        * Métricas
        * Curva ROC
        * Conclusiones
    * **Fase 5**. Mejora del método
        * GridSearchCV
        * Metricas
        * Curva ROC
        * Conclusiones
    * **Fase 6**. Comparación con otros métodos
        * Naive Bayes
        * SVM
        * Logistic Regresion
    * **Fase 7**. Análisis de sesgos
        * Modelo para mujeres
        * Modelo para hombres
        * Conclusiones Finales

* 📄 **Notebook 2:** ML_Regression.ipynb
  Objetivo:  predecir un indicador de estabilidad (valor real) en base a una serie de características que se discretizaran para dar una salida categórica (estable/no estable)

    1. Cargar el corpus de trabajo y adecuarlo, si fuera necesario, a la tarea de regresión.
       * Normalizar los datos
       * Crear las particiones correspondientes
  
    2. Realizar un modelo de regresión lineal como caso base.
  
    3. Analizar las implicaciones de tres de las métricas de error típicamente utilizadas ($R^{2}$, MAE, MSE).
  
    4. Realizar la regresión con dos modelos no lineales diferentes ($k$NN, MLP).
  
    5. Estudiar los métodos de *bagging* y *boosting* para tratar de mejorar los resultados obtenidos.
       * Bagging
       * Boosting
  
    6. Evaluación de los métodos de *stacking* para regresión.

  
