Ciencia de datos en el cuidado de la salud. Pronóstico básico y visualización GEO 

Resumen

Este ejercicio está dedicado a realizar un análisis básico de BigData sobre la propagación de COVID-19 en el mundo. Aprenderemos a hacer predicciones basadas en regresión lineal, obtener estadísticas y crear mapas interactivos que muestren la dinámica de propagación del virus. 

Introducción

Hoy en día, hay una gran cantidad de datos abiertos sobre la propagación de COVID-19 en el mundo. Sin embargo, se presentan pocas herramientas para predecir y visualizar estos procesos. Este trabajo de laboratorio le mostrará cómo puede descargar datos de fuentes abiertas, realizar análisis de datos preliminares, transformar y borrar datos, realizar análisis de correlación y retraso.

A continuación, consideraremos 2 enfoques matemáticos diferentes para el cálculo de un pronóstico basado en regresión lineal.

Para ello, se demostrará la división del DataSet en conjuntos de entrenamiento y de prueba. Se mostrará cómo construir modelos utilizando 2 marcos diferentes. Luego construiremos un pronóstico y analizaremos la precisión y adecuación de los modelos obtenidos.

Al final del trabajo de laboratorio, visualizaremos la dinámica de propagación de la infección por COVID-19 en mapas interactivos.

Materiales y métodos¶
En este laboratorio, aprenderemos los métodos básicos de pronóstico de series de tiempo y su visualización en mapas interactivos. El laboratorio consta de tres etapas:

Descarga y análisis preliminar de datos
Pronóstico
Mapas interactivos
La primera etapa le mostrará cómo descargar datos y prepararlos previamente para el análisis:

descargando datos
cambiar los tipos de datos de las columnas
agrupando datos
Transformación de conjunto de datos
eliminación de datos faltantes
En la etapa de pronóstico, nos ocuparemos de los métodos de construcción y ajuste de modelos, así como de la automatización del cálculo de la información estadística, en particular:

creación de hipótesis
dividir el DataSet en conjuntos de entrenamiento y prueba
construyendo modelos usando 2 marcos diferentes
cálculo de indicadores estadísticos básicos
pronosticar series de tiempo
En la etapa de mapas interactivos, mostraremos cómo mostrar información estadística en mapas interactivos:

transformación de datos para mapeo
descargar polígonos de mapas
construir mapas interactivos
Los datos estadísticos se obtienen de https://ourworldindata.org/coronavirus bajo la licencia Creative Commons BY. 

Requisitos Previos

Python,
Pandas,
SeaBorn,
Statistics,
Plotly

