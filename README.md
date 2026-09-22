# EP1 DLY0100 · Clasificación de Fashion-MNIST con un MLP en Keras

Evaluación Parcial 1 de DLY0100 Deep Learning. Perceptrón multicapa (MLP) implementado en TensorFlow/Keras que clasifica imágenes de prendas del dataset Fashion-MNIST en 10 categorías.

El modelo final alcanza **89.95% de accuracy** y **F1 macro 0.899** en el conjunto de prueba, frente a 86.71% del modelo base.

## Contenido

- `notebooks/EP1_MLP_Nicolas_osses_keras_final.ipynb`: desarrollo completo, ya ejecutado. Incluye la exploración y el preprocesamiento de los datos, las funciones de activación, pérdida y salida programadas desde cero, el modelo base, los experimentos (épocas, learning rate, batch size, activación, pérdida, optimizador, regularización y arquitectura), el modelo final, la evaluación en test y las conclusiones.
- `images/`: gráficos generados por el cuaderno. El número al inicio de cada archivo indica la sección del cuaderno de donde viene.
- `requirements.txt`: librerías necesarias para ejecutarlo en local.

## Ejecución en Google Colab

1. Abrir el cuaderno en Colab: https://colab.research.google.com/github/TU_USUARIO/TU_REPO/blob/main/notebooks/EP1_MLP_Nicolas_osses_keras_final.ipynb
2. Activar la GPU en Entorno de ejecución > Cambiar tipo de entorno de ejecución > T4.
3. Ejecutar todo desde Entorno de ejecución > Ejecutar todas.

El dataset se descarga automáticamente con `keras.datasets`. Con GPU T4 la ejecución completa tarda unos 30 minutos. Fue probado con TensorFlow 2.20 y Keras 3.13.

## Ejecución local

Requiere Python 3.10, 3.11 o 3.12.

```
pip install -r requirements.txt
jupyter notebook notebooks/EP1_MLP_Nicolas_osses_keras_final.ipynb
```

Sin GPU la ejecución tarda bastante más que en Colab.

## Autor

- Nicolas Osses (TU_USUARIO)
