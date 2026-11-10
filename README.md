## Análisis de Datos Meteorológicos con DuckDB y SQL

Este proyecto realiza un análisis exploratorio sobre un conjunto de datos meteorológicos utilizando **DuckDB** como motor de consultas SQL en memoria y de alto rendimiento.

## 🛠️ Tecnologías
- **Python 3** (Google Colab)
- **DuckDB**
- **Pandas**

## 📊 Datos Utilizados
Se utiliza el dataset público de clima de Seattle (`seattle-weather.csv`), el cual incluye registros diarios de:
- `date`: Fecha de la observación.
- `precipitation`: Precipitaciones.
- `temp_max`: Temperatura máxima (°C).
- `temp_min`: Temperatura mínima (°C).
- `wind`: Velocidad del viento.
- `weather`: Condición climática.

## 🔍 Consultas y Resultados

### 1. Promedios mensuales de temperatura máxima
Cálculo de la temperatura máxima promedio para cada mes del año:
- **Enero (Mes 1):** ~8.23 °C
- **Febrero (Mes 2):** ~9.86 °C
- **Marzo (Mes 3):** ~12.39 °C
- **Abril (Mes 4):** ~15.02 °C
- **Mayo (Mes 5):** ~19.30 °C
- **Junio (Mes 6):** ~22.40 °C
- **Julio (Mes 7):** ~26.00 °C
- **Agosto (Mes 8):** ~26.11 °C
- **Septiembre (Mes 9):** ~21.92 °C
- **Octubre (Mes 10):** ~16.39 °C
- **Noviembre (Mes 11):** ~11.02 °C
- **Diciembre (Mes 12):** ~8.07 °C

### 2. Extremos históricos de temperatura
- **Temperatura máxima absoluta:** 35.6 °C
- **Temperatura mínima absoluta:** -7.1 °C

### 3. Días más calurosos (Temp. Máx. > 30 °C)
Se identificaron 14 días con registros térmicos superiores a los 30 °C entre 2012 y 2015, destacándose los siguientes máximos:
- **2014-08-11:** 35.6 °C (`sun`)
- **2015-07-01:** 34.4 °C (`sun`)
- **2015-07-02:** 33.9 °C (`sun`)
- **2013-09-11:** 33.9 °C (`sun`)
