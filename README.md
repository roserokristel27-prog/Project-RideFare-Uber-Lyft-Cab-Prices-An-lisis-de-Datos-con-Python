# 🚕 Project RideFare – Uber & Lyft Cab Prices | Análisis de Datos con Python

Proyecto de análisis de datos enfocado en comprender los factores que influyen en el precio de los viajes en plataformas de transporte como Uber y Lyft.  
El análisis se realizó utilizando Python para explorar la estructura del dataset, evaluar la calidad de los datos y descubrir patrones relevantes relacionados con precios, distancia, horario y condiciones climáticas.

---

## 🎯 Objetivo del Proyecto

El objetivo de este proyecto es realizar un análisis exploratorio de datos (EDA) para comprender la estructura y calidad del dataset de viajes y analizar los factores que influyen en el precio de los servicios de transporte.

Este análisis busca:

- Comprender la estructura general del dataset.
- Identificar problemas de calidad de datos como valores nulos, duplicados u outliers.
- Analizar la distribución de las variables principales.
- Explorar relaciones entre diferentes variables del dataset.
- Identificar patrones relevantes en el comportamiento de los precios de los viajes.

---

## 🛠️ Herramientas utilizadas

- Python  
- Google Colab  
- Pandas  
- Matplotlib  
- Seaborn  

---

## 🔎 Proceso de análisis

El análisis se desarrolló en varias etapas principales.

### 1. Exploración inicial del dataset

Se cargó el dataset en Python utilizando la librería Pandas y se examinó su estructura general.

Durante esta etapa se analizaron:

- Dimensiones del dataset
- Número de filas y columnas
- Tipos de datos de cada variable
- Descripción general de la información disponible

---

### 2. Evaluación de calidad de datos

Se realizó una revisión de la calidad de los datos para identificar posibles problemas que puedan afectar el análisis.

En esta etapa se evaluaron:

- Registros duplicados
- Valores faltantes o nulos
- Distribución de variables numéricas
- Presencia de valores atípicos (outliers)

Este proceso permitió comprender mejor el estado del dataset y detectar posibles limitaciones en la información disponible.

---

### 3. Análisis exploratorio y visualización

Posteriormente se realizaron diversas visualizaciones para comprender el comportamiento de las variables principales.

Se desarrollaron gráficos como:

- Histogramas para analizar la distribución de variables
- Gráficos de dispersión para estudiar relaciones entre variables
- Visualizaciones por hora del día para analizar cambios en las tarifas
- Comparaciones entre diferentes tipos de servicio

Estas visualizaciones permitieron identificar patrones importantes dentro de los datos.

---

## 📊 Resultados obtenidos

A partir del análisis exploratorio se identificaron varios insights relevantes sobre el comportamiento de los precios de los viajes.

Entre los principales hallazgos se encuentran:

- Los precios de los viajes presentan incrementos durante las horas nocturnas, lo que sugiere una mayor demanda en ese horario.
- La distancia del viaje presenta una relación positiva con el precio, aunque no es el único factor que influye en la tarifa final.
- El tipo de servicio tiene un impacto importante en el precio, ya que los servicios premium presentan tarifas más altas que los servicios estándar.
- Los viajes cortos resultan proporcionalmente más costosos en comparación con los viajes largos.
- Las condiciones climáticas muestran una relación limitada con el precio de los viajes.
