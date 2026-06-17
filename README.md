# Procesamiento Básico de Audio con Python

Este proyecto muestra cómo cargar, analizar y modificar un archivo de audio usando Python.

## ¿Qué hace?

- Carga un archivo de audio y muestra información básica: duración, frecuencia de muestreo y valores de la señal
- Grafica la señal de audio para visualizarla como una onda
- Modifica la velocidad de reproducción cambiando la frecuencia de muestreo
- Reduce la calidad del audio simulando una grabación de 8 bits
- Permite reproducir el audio original y las versiones modificadas directamente en el entorno

## Conceptos que se trabajan

- **Frecuencia de muestreo**: cuántas veces por segundo se toma una muestra del sonido
- **Duración**: se calcula dividiendo la cantidad de muestras por la frecuencia de muestreo
- **Canales**: un audio puede ser estéreo (2 canales) o mono (1 canal)
- **Cuantización**: la cantidad de niveles con los que se representa la amplitud de la señal

## Archivos necesarios

Colocar en la misma carpeta que el script:
- `output_16bit.wav` — señal procesada
- `AnalisisTextos.mp3` — audio original

## Librerías

- `librosa` — análisis de audio
- `soundfile` — lectura de archivos de audio
- `numpy` — operaciones numéricas
- `matplotlib` — visualización de la señal
- `IPython` — reproducción de audio en el entorno
