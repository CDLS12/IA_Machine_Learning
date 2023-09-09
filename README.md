#  Módulo 2 Implementación de una técnica de aprendizaje máquina sin el uso de un framework.

# Contexto del problema o trabajo
Este repositorio contiene el archivo de trabajo en el que se implemento machine learning a un set de datos para el entrenamiento, prueba y prediccion de los mismos datos
El modelo seleccionado para este trabajo fue regresion lineal:

La regresión lineal es un método estadístico utilizado para modelar la relación entre una variable dependiente (o respuesta) y una o más variables independientes (o predictores) mediante una ecuación lineal. Su objetivo es encontrar la mejor línea recta que se ajuste a los datos, lo que permite predecir o estimar la variable dependiente en función de las variables independientes. En resumen, la regresión lineal se utiliza para comprender y predecir relaciones lineales entre variables, lo que es útil en análisis de datos, pronósticos y toma de decisiones.

# Dataset de Salary:
Link del Dataset: https://www.kaggle.com/datasets/abhishek14398/salary-dataset-simple-linear-regression 

En este portafolio, implementaremos la técnica de aprendizaje automático conocida como regresión lineal de forma manual para predecir los salarios de las personas en función de la cantidad de años de experiencia laboral. Para este propósito, el conjunto de datos se divide en dos columnas principales: "Años de Experiencia" y "Salario".

# Uso de Regresión Lineal en el Dataset de Salary:

Para este trabajo, aplicaremos un modelo de regresión lineal que aprenderá de los datos de entrenamiento y prueba. El objetivo es utilizar este modelo entrenado para predecir con la mayor precisión posible el salario de una persona en función de la cantidad de años de experiencia proporcionada. Este proceso implica la aplicación de algoritmos matemáticos relacionados con la regresión lineal para lograr los objetivos establecidos en este informe.

# Estructura del repositorio
El repositorio actual esta conformado por dos partes esenciales, la primera parte es el README presente el cual sirve como presentacion del repositorio e introduccion al proyecto con datos generales del entregable, contexto del reto o problema a resolver y los modelos que se utilizaran para la solucion del mismo. La segunda parte es el archivo/reporte  Módulo 2 Implementación de una técnica de aprendizaje máquina sin el uso de un framework.ipynb el cual es el reporte explicado con codigo implementado y solucion de la problematica presente, a continuacion en forma de lista se presentaran las dos partes de este repositorio para un mejor entendimiento y orden:

## -README: Introduccion y entendimiento del proyecto con contexto general de la problematica conformada por
  * Contexto del problema o trabajo
  * Dataset de Heart Salary
  * Uso de Regresión Lineal en el Dataset de Salary
  * Estructura del repositorio

## -Módulo 2 Implementación de una técnica de aprendizaje máquina sin el uso de un framework.ipynb: 
El archivo ipynb presente contiene el reporte en codigo con todos los resultados, documentacion y evidencia demandados, se pued observar la introduccion y descripcion del problema junto a los datos para seguir con la definicion de los datos de entrenamiento y prueba para implementar la regresion logistica y asi medir su desempeño y visualizar los resultados.

# Cambios implementados
Para esta ultima entrega se cambiaron y alteraron multiples parte del reporte a base de la retroalimentacion pasada,en general se cambio el 90% del codigo para mejorar el modelo y adaptarlo a los cambios mas destacados que se comentaran a continuacion:
  * Creacion de subset de datos de entrenamiento y prueba: En el anterior entregable no se hizo esto y ahora se aplico una division con x_train y x_test, etc. 
  * Metricas de Desempeño: Se agregaron nuevas metricas de desempeño para ver el rendimiento de las predicciones y valores resultantes de los valores de entrenamiento y prueba mayormente con los errores cuadraticos, R-cuadrado, MSE, etc.
