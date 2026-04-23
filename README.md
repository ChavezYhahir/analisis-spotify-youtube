# Análisis de Artistas en Spotify y YouTube 🎵

Proyecto personal de análisis de datos sobre el rendimiento de artistas y canciones
en Spotify y YouTube, utilizando Python y librerías de visualización.

## Descripción

Este proyecto analiza un dataset real con información de canciones en ambas plataformas,
explorando métricas como reproducciones, likes, comentarios y características musicales
como energía y bailabilidad.

## Análisis realizados

- **Limpieza de datos**: eliminación de columnas con más del 50% de valores nulos,
  imputación por mediana/moda y conversión de tipos de datos.
- **Análisis exploratorio (EDA)**: estadísticas descriptivas sobre Views, Likes,
  Streams y Comments, identificando canciones con más de 500M de visualizaciones.
- **Visualización de datos**: gráficos de líneas, mapas de calor y gráficos de barras
  para identificar patrones entre energía, bailabilidad y rendimiento por tipo de álbum.
- **Análisis por grupos**: identificación de los 3 artistas con mayor número de streams
  en el segmento de canciones con baja proporción de likes.

## Tecnologías utilizadas

- Python 3
- Pandas
- Matplotlib
- Seaborn
- Jupyter Notebook

## Dataset

El dataset utilizado es público y puede descargarse desde Kaggle:
[Spotify and Youtube Dataset](https://www.kaggle.com/datasets/salvatorerastelli/spotify-and-youtube)

## Cómo ejecutar el proyecto

1. Clona el repositorio
2. Descarga el dataset desde el link de Kaggle y colócalo en una carpeta `/datasets`
3. Abre `analisis_spotify_youtube.ipynb` en Jupyter Notebook o VS Code
4. Ejecuta las celdas en orden