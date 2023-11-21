
# DataScience_Portfolio

![](datavizpreviewimage2.png)

# [Project_1: EDA datos siniestros viales CABA](https://github.com/Lapantufla/Data_Analysis/tree/CABA_Accident_EDA_project)

Los datos están relacionados con accidentes de siniestros viales en CABA. 
El objetivo es hacer un analisis exploratorio de los datos y plantear hipotesis.

[Link Presentacion en pdf](https://github.com/Lapantufla/Data_Analysis/blob/CABA_Accident_EDA_project/EDA%20Homicidios%20y%20accidentes%20viales.pdf)
[Link notebook](https://github.com/Lapantufla/Data_Analysis/blob/CABA_Accident_EDA_project/homicidios_%26_accidentes%20(1).ipynb)
[Link DataFrames](https://data.buenosaires.gob.ar/dataset/victimas-siniestros-viales)

Las tareas que se realizaron son: 

* Feature Engineering:
  * Limpieza de datos crudos.
  * Creacion de nuevos features.
  * Implementacion de expresiones regulares. 
  * Scraping Web para la obtenencion de Barrios a partir de coordenadas(beautifulsoup).
    
* Visualización del DataFrame: 
  * Gráficos de histogramas.
  * Gráficos de barras.
  * Graficos de puntos.
  * Graficos de lineas.
  * Graficos de supervivencia.

* Planteode hipotesis.

* Implementacion modelo estadistico (survival analysis).



# [Project_2: Bank Marketing](https://github.com/Lapantufla/Data_Analysis/blob/BankMarketing_project/BankMarketing_project.ipynb)

Los datos están relacionados con campañas de marketing (llamadas telefónicas) de una institución bancaria portuguesa. 
El objetivo de la clasificación es predecir si el cliente suscribirá o no a un depósito a plazo (variable y).

[Link DataFrame](https://www.kaggle.com/datasets/henriqueyamahata/bank-marketing?datasetId=30368&sortBy=voteCount)

Las tareas que se realizaron son: 

* Visualización del DataFrame: 
  * Gráficos de histogramas.
  * Gráficos de barras.

* Feature Engineering:
  * Discretizacion de variables.
  * Tratamiento de valores nulos.
  * Tratamiento de variables categóricas (con aprouch: Ordinal Encoding, Target Mean Encoding).
  
* Feature selection:
  * Features constantes y casi-constantes.
  * Features correlacionados.
  * Chi-square test.
  * Mutual information.
  * Random Forest importance.
  * Logistic Regression Coefficients.
  * Análisis de la performance de distintos aprouchs de selección.
 
* Creación y entrenamiento modelos de clasificación:
  * Declaración y entrenamiento de modelo de regresión logística, random forest y gradient boosting.
  * Análisis de la performance de los modelos.


# [Project_3: Analytics Employee Attrition & Performance](https://github.com/Lapantufla/Data_Analysis/blob/HumanResources_project/HumanResources_project.ipynb)

Descubra los factores que conducen a la deserción de los empleados, creando preguntas importantes y explorando posibles respuestas. 
Este es un conjunto de datos ficticio creado por científicos de datos de IBM.

[Link DataFrame](https://www.kaggle.com/datasets/pavansubhasht/ibm-hr-analytics-attrition-dataset?datasetId=1067&sortBy=voteCount)

Las tareas que se realizaron son: 

* Visualización del DataFrame: 
  * Gráficos de histogramas.
  * Gráficos de barras.
  * Gráficos de densidad.
  * Gráficos de cajas.
 
* Selección y tratamiento de features:
  * Tratamiento de variables categóricas ( con aprouch: Ordinal Encoding, Counting Encoding, Ordered Integer Encoding y Probability Ratio Encoding).
  * Analisis y tratamiento de cardinalidades y valores raros.
  * Seleccion de features.

* Creación y entrenamiento modelos de clasificación.
  * Escalado de datos.
  * Declaración y entrenamiento de modelo de regresión logística y random forest.
  * Análisis de la performance de los modelos.


# [Project_4: Credit Card Dataset for Clustering](https://github.com/Lapantufla/Data_Analysis/blob/Marketing_project/CreditCardClustering_project.ipynb)

Este caso requiere desarrollar una segmentación de clientes para definir la estrategia de marketing. 
El conjunto de datos de muestra el comportamiento de uso de tarjetas de crédito de aproximadamente 9000 titulares activos durante los últimos 6 meses.

[Link DataFrame](https://www.kaggle.com/datasets/arjunbhasin2013/ccdata)

Las tareas que se realizaron son: 

* Limpieza de los datos:
  * Tratamiento de valores nulos.

* Visualización del DataFrame: 
  * Gráficos de histogramas con estimación de densidad kernel.
  * Gráfico de correlaciones (matriz de correlación)

* Encontrar número óptimo de clusters.

* Aplicar el metodo K-means.
  * Visualizar los histogramas de cada columna pertinentes a cada cluster.

* Aplicación de análisis de componentes principales.

# [Project_5: Customer Retention](https://github.com/Lapantufla/Data_Analysis/blob/CustomerRetention_project/CustomerRetention_project.ipynb)

Prediga el comportamiento para retener a los clientes. Puede analizar todos los datos relevantes de los clientes y desarrollar programas específicos de retención de clientes. [Conjuntos de datos de muestra de IBM]

[Link DataFrame](https://www.kaggle.com/datasets/blastchar/telco-customer-churn)

Las tareas que se realizaron son: 

* Exploración del DataFrame:
  * Primeros acercamientos e hipótesis.
  * Gráficos de histogramas.
  * Gráficos de densidad.
  * Gráficos de barras.
  
* Selección y tratamiento de features.
   * Tratamiento variables categóricas:
      * Ordinal Encoding.
      * Ordered Integer Encoding.
      * Count Encoding.
      * Target Mean Encoding.
      * Weight of Evidence Encoding.
    
* Feature selection.
    
* Creación y entrenamiento modelos de clasificación.
  * Data Balancing.
  * Escalado de datos.
  * Declaración y entrenamiento de modelos (Regresión logística, Random forest y XGBClassifier).
  * Análisis de la performance de los modelos.

