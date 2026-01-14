# Weather ETL Pipeline

Este proyecto implementa un pipeline ETL en **PySpark** que consume datos de clima desde la API pública de [Open-Meteo](https://open-meteo.com/).

##  Objetivo
Construir un flujo ETL que:
1. **Extract:** consume datos de clima (temperatura y humedad) desde la API de Open-Meteo.
2. **Transform:** procesa los datos horarios, los convierte en métricas diarias y calcula promedios.
3. **Load:** guarda los resultados en formato Parquet, listos para análisis histórico.

##  Tecnologías
- Python
- PySpark
- Requests (para consumir la API)
- Formatos: JSON → Parquet

##  Resultados
- **Promedio de temperatura diaria** (°C).
- **Promedio de humedad diaria** (%).
- Dataset optimizado en Parquet para análisis de tendencias.
