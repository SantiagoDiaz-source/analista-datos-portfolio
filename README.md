## Evaluación de Modelos predictivos en Machine Learning para la predicción de costos de viaje en UBER 

## Descripción
El objetivo principal fue analizar los factores que influyen en el costo de los viajes y construir modelos de Machine Learning capaces de predecir el valor de una reserva (Booking Value) a partir de variables temporales, distancia del recorrido y características del servicio.
Durante el proyecto se realizaron procesos de:

- Limpieza e imputación de datos
- Ingeniería de características
- Análisis de correlación
- Detección de patrones temporales
- Codificación de variables categóricas
- Entrenamiento y evaluación de modelos predictivos

## Tecnologías usadas
- Python 3
- pandas
- matplotlib / seaborn
- Google Colab
- XGBoost

## Dataset
- **Fuente:** https://www.kaggle.com/datasets/yashdevladdha/uber-ride-analytics-dashboard?utm_source 
- **Registros:** 150,000 filas
- **Variables analizadas:** Ride Distance,Booking Value,Vehicle Type, entre otras. 

## 🔍 Hallazgos principales
- Las variables temporales y la distancia del viaje tuvieron una alta influencia en la predicción del costo.
- La ingeniería de características mejoró significativamente el rendimiento de los modelos.
- XGBoost obtuvo el mejor desempeño general en las métricas de evaluación.

Se evaluaron con las siguientes metricas:
- MAE (Error Absoluto Medio)
- RMSE (Raíz del Error Cuadrático Medio)
- R² Score (Coeficiente de Determinación)

## Cómo ejecutar el proyecto
1. Abre el archivo `.ipynb` en Google Colab
2. Descarga el dataset desde el enlace de Kaggle
3. Ejecuta todas las celdas en orden

## Autor
**Brayan Santiago Díaz Caballero**  
[LinkedIn](https://www.linkedin.com/in/brayan-santiago-diaz/) | brayandiazsanty@gmail.com
