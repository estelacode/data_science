# Data Science

## Machine Learning Notebooks:

APRENDIZAJE SUPERVISADO

* 📄 **Notebook 1:** ML_Clasificacion.ipynb  
Objetivo: predecir si una persona cobra mas de 50000 dólares en un año.
Dataset: adult.data

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
Dataset:  Data_for_UCI_named.csv

    * **Fase 0**. Descarga y Carga del conjunto de datos.
      
    * **Fase 1**. Análisis Exploratorio de los datos(EDA)
      
    * **Fase 2**. Entrenamiento del modelo de regresión lineal y estudio de la bondad del mismo.
      
         * Modelo 1 - Regressión Lineal Multivariante
         * Visualización de los residuos del modelo 1
         * Modelo 2 - Regressión Lineal Multivariante
         * Visualización de los residuos del modelo 2
         * Evaluación cuantitativa del modelo
            * Coeficiente de deteminación
            * MAE
            * MSE
              
    * **Fase 3**. Entrenamiento de modelos diferentes al método de regresión lineal
      
         * KNeighborsRegressor
         * Multi-layer Perceptron Regression
         * Predicciones:
            * LinearRegressor Predictions
            * KNeighborsRegressor Predictions
            * MLPRegressor Predictions
         * Evaluación Cualitativa de los modelos.
           
    * **Fase 4**. Entrenamiento con métodos de agregación: bagging y boosting
      
         * Bagging con estimadores (LinearRegression)
         * Bagging con estimadores (MLPRegressor)
         * Boosting con estimadores (LinearRegression)
         * Boosting con estimadores (MLPRegressor)
         * Métricas de Bondad
           
   * **Fase 5**. Métodos de stacking
     
         * Stacking con regresor lineal kNN y MLP
         * Stacking con regresor lineal y kNN
         * Stacking con regresor lineal y MLP
         * Stacking con regresor kNN y MLP
         * Métricas de Bondad
        
      

  

  
