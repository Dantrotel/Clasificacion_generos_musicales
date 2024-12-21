# Clasificación de Géneros Musicales con Deep Learning

Este proyecto implementa un sistema de clasificación de géneros musicales utilizando técnicas de deep learning. El modelo está entrenado con el dataset GTZAN, que consiste en 1000 archivos de audio de 10 géneros diferentes. El objetivo es clasificar las canciones según su género utilizando características extraídas de las señales de audio.

## Tabla de Contenidos

- [Descripción](#descripción)
- [Dataset](#dataset)
- [Tecnologías](#tecnologías)
- [Características](#características)
- [Instalación](#instalación)
- [Uso](#uso)
- [Evaluación del Modelo](#evaluación-del-modelo)
- [Conclusión](#conclusión)
- [Agradecimientos](#agradecimientos)
- [Licencia](#licencia)

## Descripción

Este proyecto tiene como objetivo clasificar canciones en géneros musicales utilizando deep learning, específicamente redes neuronales convolucionales (CNNs) o redes neuronales recurrentes (RNNs). Se utiliza el dataset GTZAN, un dataset popular para clasificación de géneros musicales. Las características como los coeficientes cepstrales en frecuencia de Mel (MFCCs) se extraen de los archivos de audio y se alimentan al modelo para su clasificación.

## Dataset

El dataset utilizado en este proyecto es el **GTZAN Music Genre Dataset**, que consta de 1000 archivos de audio categorizados en 10 géneros:
- Blues
- Clásica
- Country
- Disco
- Hip-hop
- Jazz
- Metal
- Pop
- Reggae
- Rock

Cada pista tiene una duración de 30 segundos en formato WAV, y el dataset está disponible públicamente para fines de investigación. El dataset se puede descargar desde [GTZAN Music Genre Dataset](http://opihi.cs.uvic.ca/sound/genres.tar.gz).

## Tecnologías

- **Python 3.x**
- **TensorFlow** (para deep learning)
- **Keras** (para construir redes neuronales)
- **Librosa** (para procesamiento de audio y extracción de características)
- **NumPy** y **Pandas** (para manipulación de datos)
- **Matplotlib** y **Seaborn** (para visualización)
- **Scikit-learn** (para machine learning y métricas de evaluación)

## Características

- **Preprocesamiento de Audio**: Los datos de audio crudos se procesan extrayendo los MFCCs de los archivos de audio utilizando la librería Librosa.
- **Modelo de Deep Learning**: Se utiliza una red neuronal convolucional (CNN) o una red neuronal recurrente (RNN) para clasificar los géneros musicales.
- **Evaluación**: El rendimiento del modelo se evalúa utilizando métricas como precisión, recall, F1-score, y accuracy.
- **Visualización**: Las métricas de rendimiento se visualizan usando matrices de confusión y gráficos para una mejor interpretación.

## Instalación

### Requisitos
Antes de ejecutar el código, asegúrate de tener lo siguiente instalado:

1. Python 3.x
2. `pip` (gestor de paquetes de Python)

