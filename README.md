# Music Genre Classification using Convolutional Neural Networks (CNNs)

Este proyecto implementa una red neuronal convolucional (CNN) para clasificar música por género a través de espectrogramas generados a partir de archivos de audio. Utiliza varias bibliotecas de Python, incluyendo `librosa` para el procesamiento de audio, `numpy` para las operaciones numéricas, y `tensorflow` para construir y entrenar el modelo de la CNN.

## Descripción del Proyecto

### Objetivo
El objetivo de este proyecto es crear un modelo de aprendizaje profundo que pueda clasificar automáticamente el género musical de un archivo de audio. Utilizamos espectrogramas mel como representación visual de las frecuencias del audio a lo largo del tiempo para entrenar nuestra red neuronal.

### Arquitectura del Proyecto
1. **Extracción de Espectrogramas**: Utilizamos `librosa` para cargar archivos de audio y generar espectrogramas mel, los cuales se transforman a una escala logarítmica para su interpretación.
2. **Carga y Preprocesamiento de Datos**: Desarrollamos funciones para cargar datos desde el conjunto de datos GTZAN, redimensionar y preparar los espectrogramas para el entrenamiento.
3. **Construcción del Modelo**: Usamos `tensorflow` para construir una red neuronal convolucional adecuada para la clasificación de imágenes (espectrogramas).
4. **Entrenamiento y Evaluación**: Entrenamos la CNN con los datos preprocesados y evaluamos su desempeño.

## Requisitos

Para ejecutar este proyecto necesitarás instalar las siguientes bibliotecas:

- `numpy`
- `librosa`
- `tensorflow`
- `sklearn`

Puedes instalar estas bibliotecas utilizando pip:

```sh
pip install numpy librosa tensorflow sklearn
