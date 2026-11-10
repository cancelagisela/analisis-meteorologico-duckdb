Análisis de Datos Meteorológicos con DuckDB y SQL

Este proyecto realiza un análisis exploratorio sobre un conjunto de datos meteorológicos utilizando **DuckDB** como motor de consultas SQL en memoria y de alto rendimiento.

## 🛠️ Tecnologías
- **Python 3** (Google Colab)
- **DuckDB**
- **Pandas**

## 📊 Datos Utilizados
Se utiliza el dataset público de clima de Seattle (`seattle-weather.csv`), el cual incluye registros diarios de:
- `date`: Fecha de la observación.
- `precipitation`: Precipitaciones.
- `temp_max`: Temperatura máxima.
- `temp_min`: Temperatura mínima.
- `wind`: Velocidad del viento.
- `weather`: Condición climática.

## 🔍 Consultas Realizadas
- **Promedios mensuales:** Cálculo de la temperatura máxima promedio por mes.
- **Valores extremos:** Registro de la temperatura máxima y mínima histórica.
- **Filtrado condicional:** Identificación de los días con temperaturas superiores a los 30 °C.

## 🚀 Cómo Ejecutar
1. Abrir el notebook `Análisis_de_Datos_Meteorológicos_con_DuckDB_e_SQL.ipynb` en **Google Colab**.
2. Ejecutar las celdas en orden para cargar los datos y correr las consultas SQL.
