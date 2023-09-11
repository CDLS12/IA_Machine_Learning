# Estructura del repositorio
El repositorio actual esta conformado por tres partes esenciales, la primera parte es el README presente el cual sirve como presentacion del repositorio e introduccion a los dos proyectos o trabajos(con Framewrok y sin Framework) con datos generales del entregable, contexto del reto o problema a resolver y los modelos que se utilizaran para la solucion del mismo. La segunda parte es el archivo/reporte  Módulo 2 Implementación de una técnica de aprendizaje máquina sin el uso de un framework.ipynb el cual es el reporte explicado con codigo implementado y solucion de la problematica presente y la tercera parte es el archivo  Módulo 2 Portafolio de Implementacion con Framework el cual es el reporte explicado con codigo implementado , a continuacion en forma de lista se presentaran las tres partes de este repositorio para un mejor entendimiento y orden:

## -README: Introduccion y entendimiento del proyecto con contexto general de la problematica conformada por
  * Parte 1 de Implementacion: Módulo 2 Implementación de una técnica de aprendizaje máquina sin el uso de un framework.
     * Contexto del problema o trabajo
     * Dataset de Salary
     * Uso de Regresión Lineal en el Dataset de Salary
     * Módulo 2 Implementación de una técnica de aprendizaje máquina sin el uso de un framework.ipynb(Describe la informacion del reporte y codigo en general)
  * Parte 2 de Implementacion:  Módulo 2 Portafolio de Implementacion con Framework
     * Contexto del problema o trabajo
     * Dataset de Heart Disease
     * Uso de Regresión Logística en el Dataset de Heart Disease
     * Modulo 2 Portafolio de Implementacion con Framework.ipynb(Describe la informacion del reporte y codigo en general)
    
#  Parte 1 de Implementacion: Módulo 2 Implementación de una técnica de aprendizaje máquina sin el uso de un framework.

# Contexto del problema o trabajo
Este repositorio contiene el archivo de trabajo en el que se implemento machine learning a un set de datos para el entrenamiento, prueba y prediccion de los mismos datos
El modelo seleccionado para este trabajo fue regresion lineal:

La regresión lineal es un método estadístico utilizado para modelar la relación entre una variable dependiente (o respuesta) y una o más variables independientes (o predictores) mediante una ecuación lineal. Su objetivo es encontrar la mejor línea recta que se ajuste a los datos, lo que permite predecir o estimar la variable dependiente en función de las variables independientes. En resumen, la regresión lineal se utiliza para comprender y predecir relaciones lineales entre variables, lo que es útil en análisis de datos, pronósticos y toma de decisiones.

# Dataset de Salary:
Link del Dataset: https://www.kaggle.com/datasets/abhishek14398/salary-dataset-simple-linear-regression 

En este portafolio, implementaremos la técnica de aprendizaje automático conocida como regresión lineal de forma manual para predecir los salarios de las personas en función de la cantidad de años de experiencia laboral. Para este propósito, el conjunto de datos se divide en dos columnas principales: "Años de Experiencia" y "Salario".

# Uso de Regresión Lineal en el Dataset de Salary:

Para este trabajo, aplicaremos un modelo de regresión lineal que aprenderá de los datos de entrenamiento y prueba. El objetivo es utilizar este modelo entrenado para predecir con la mayor precisión posible el salario de una persona en función de la cantidad de años de experiencia proporcionada. Este proceso implica la aplicación de algoritmos matemáticos relacionados con la regresión lineal para lograr los objetivos establecidos en este informe.


## -Módulo 2 Implementación de una técnica de aprendizaje máquina sin el uso de un framework.ipynb: 
El archivo ipynb presente contiene el reporte en codigo con todos los resultados, documentacion y evidencia demandados, se pued observar la introduccion y descripcion del problema junto a los datos para seguir con la definicion de los datos de entrenamiento y prueba para implementar la regresion logistica y asi medir su desempeño y visualizar los resultados.

# Cambios implementados
Para esta ultima entrega se cambiaron y alteraron multiples parte del reporte a base de la retroalimentacion pasada,en general se cambio el 90% del codigo para mejorar el modelo y adaptarlo a los cambios mas destacados que se comentaran a continuacion:
  * Creacion de subset de datos de entrenamiento y prueba: En el anterior entregable no se hizo esto y ahora se aplico una division con x_train y x_test, etc. 
  * Metricas de Desempeño: Se agregaron nuevas metricas de desempeño para ver el rendimiento de las predicciones y valores resultantes de los valores de entrenamiento y prueba mayormente con los errores cuadraticos, R-cuadrado, MSE, etc.

# Parte 2 de Implementacion:  Módulo 2 Portafolio de Implementacion con Framework

# Contexto del problema o trabajo
Este repositorio contiene el archivo de trabajo en el que se implemento machine learning a un set de datos para el entrenamiento, prueba y prediccion de los mismos datos
El modelo seleccionado para este trabajo fue regresion logistica:

La regresión logística es un algoritmo de aprendizaje supervisado utilizado en estadísticas y aprendizaje automático para la clasificación de datos. A pesar de su nombre, la regresión logística se utiliza para problemas de clasificación binaria, donde el objetivo es predecir una de dos clases posibles (por ejemplo, sí/no, positivo/negativo, spam/no spam). La regresión logística utiliza la función logística (también conocida como función sigmoide) para modelar la probabilidad de que un ejemplo pertenezca a una de las dos clases.

La función logística toma una combinación lineal de características de entrada y la transforma en una probabilidad en el rango de 0 a 1. 

# Dataset de Heart Disease:
Link del Dataset:  https://www.kaggle.com/datasets/dileep070/heart-disease-prediction-using-logistic-regression 

El conjunto de datos de Heart Disease (Predicción de Enfermedades Cardíacas) es un conjunto de datos ampliamente utilizado en el campo de la ciencia de datos y el aprendizaje automático. Proporciona información sobre pacientes y diversas características médicas que se utilizan para predecir si un paciente tiene una enfermedad cardíaca o no. Algunas de las características incluyen la edad del paciente, el género, los niveles de colesterol, la presión arterial, los resultados de pruebas médicas y otros indicadores de salud.

El objetivo principal del conjunto de datos es entrenar modelos de aprendizaje automático para predecir la presencia o ausencia de enfermedades cardíacas en pacientes. Esto es crítico para ayudar en la detección temprana y el tratamiento de enfermedades cardíacas, que son una de las principales causas de muerte en todo el mundo.

El conjunto de datos de Heart Disease es un recurso valioso para la investigación médica y el desarrollo de algoritmos de aprendizaje automático para la predicción de enfermedades cardíacas. Los datos son utilizados para evaluar y mejorar la capacidad de los modelos de clasificación, como la regresión logística, para identificar a las personas en riesgo de enfermedades cardíacas.
La descripcion de cada variable o columna junto a sus atributos y caracteristicas como tamaño se encuentra mejor detallado en el reporte ipynb.

# Uso de Regresión Logística en el Dataset de Heart Disease:

La regresión logística se utiliza comúnmente en el conjunto de datos de predicción de enfermedades cardíacas (Heart Disease) para predecir si un paciente tiene o no una enfermedad cardíaca en función de diversas características médicas y de salud. Este uso se debe a la naturaleza binaria del problema (enfermedad cardíaca o no) y la capacidad de la regresión logística para modelar la probabilidad de pertenecer a una de las dos clases.



## -Modulo 2 Portafolio de Implementacion con Framework.ipynb
  * Parte 1: Módulo 2 Uso de framework o biblioteca de aprendizaje máquina para la implementación de una solución: La primera parte es el analisis previo a la base de datos de heart desease para su posterior 
    limpieza de datos e implementacion del modelo de machine learning regresion logistica y visualizacion de precision y rendimiento en relacion a los datos.
  * Parte 2: Esta parte dos estara presente en el segundo repositorio que seria la continuacion del proyecto con framework para refinar y analizar el rendimiento del modelo.
# Cambios implementados
Para este portafolio con framework no se hizo ningun cambio en especificio ya que todo cumplio con la retroalimentacion, los cambios se implementaron en el portafolio de analisis que es la continuacion de este portafolio con la aplicacion de sesgo varianza overfitting underfitting y tecnicas de regularizacion,etc.
