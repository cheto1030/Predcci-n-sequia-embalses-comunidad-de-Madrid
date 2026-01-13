# Predicción sequía embalses comunidad de Madrid
Este proyecto analiza datos históricos de agua embalsada en varios embalses de la Comunidad de Madrid (datasets CSV proporcionados) con el objetivo de detectar patrones, visualizar la evolución del volumen y generar una predicción de los próximos 12 meses para anticipar posibles escenarios de sequía.

## Qué se hace en el proyecto
- Ingesta automática de múltiples CSV en una sola ejecución.
- Limpieza y transformación de datos (ETL) para crear:
  - Un dataframe “global” con todos los embalses.
  - Dataframes individuales por embalse.
- Visualización con gráficos:
  - Barras por año (total y/o por embalse).
  - Dispersión comparando dos embalses a lo largo del tiempo.
  - Violin plot por año para observar distribución y variabilidad.
- Predicción de serie temporal usando **Prophet** para estimar el comportamiento en los próximos 12 meses.
- Creación de un dashboard en **Power BI** para responder preguntas como:
  - Qué embalse tiene más diferencia entre máximos y mínimos.
  - Cuándo se produce (o podría producirse) sequía y el nivel de confianza con los datos disponibles.

## Técnicas y herramientas
- Python para ingesta, ETL y análisis (dataframes).
- Visualización de datos (bar chart, scatter, violin plot).
- Forecasting de series temporales con Prophet.
- BI y storytelling con Power BI para presentar conclusiones.
