# Proyecto de Clasificación de Dígitos MNIST con Keras

Este proyecto implementa un modelo de clasificación de dígitos utilizando la biblioteca Keras sobre el conjunto de datos MNIST. El objetivo es construir y entrenar un modelo de red neuronal para clasificar dígitos escritos a mano en imágenes de 28x28 píxeles en sus correspondientes números del 0 al 9.

### Estructura del Repositorio

El repositorio está organizado de la siguiente manera:

mnist_classification.ipynb: Este es el cuaderno de Jupyter que contiene el código Python utilizado para cargar, preprocesar, construir, entrenar y evaluar el modelo de clasificación de dígitos MNIST.
README.md: Este archivo README que proporciona información sobre el proyecto y cómo ejecutar el código.

Requisitos
Para ejecutar el código en este proyecto, necesitarás tener instaladas las siguientes bibliotecas:

Python 3
TensorFlow
Keras
numpy
matplotlib
Puedes instalar las bibliotecas necesarias ejecutando el siguiente comando:
- pip install -r requirements.txt 

Uso
Para ejecutar el cuaderno de Jupyter, simplemente abre el archivo mnist_classification.ipynb en tu entorno de Jupyter Notebook y sigue las instrucciones paso a paso.

### Proceso y Resultados
El proceso de este proyecto implica los siguientes pasos:

- Carga de Datos: Se cargan los datos del conjunto de datos MNIST, que consta de imágenes de dígitos escritos a mano junto con sus etiquetas correspondientes.
- Preprocesamiento de Datos: Se realiza un preprocesamiento en los datos, que incluye normalización y aplanamiento de las imágenes.
- Construcción del Modelo: Se construye un modelo de red neuronal utilizando la biblioteca Keras, con capas densas y funciones de activación adecuadas.
- Entrenamiento del Modelo: El modelo se entrena utilizando los datos de entrenamiento y se evalúa utilizando los datos de prueba.
- Evaluación de Resultados: Se evalúan los resultados del modelo, incluida la precisión y la pérdida en los datos de entrenamiento y prueba.

Contribuciones
Las contribuciones son bienvenidas. Si deseas contribuir a este proyecto, no dudes en abrir un problema o enviar una solicitud de extracción.



