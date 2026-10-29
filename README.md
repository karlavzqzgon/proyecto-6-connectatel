# proyecto-6-connectatel
Análisis estadístico del uso de servicios móviles de ConnectaTel
# Proyecto 6: Análisis de una empresa de telecomunicaciones

## Descripción del proyecto

Este proyecto analiza el comportamiento de los clientes de ConnectaTel, una empresa de telecomunicaciones con operaciones en México y Colombia. El objetivo es identificar patrones de uso de llamadas y mensajes, detectar valores atípicos y segmentar clientes para proponer oportunidades de mejora comercial.

## Objetivos

- Explorar y limpiar las fuentes de datos.
- Identificar valores faltantes, datos inconsistentes y fechas fuera de rango.
- Calcular estadísticas descriptivas del comportamiento de los usuarios.
- Visualizar distribuciones e identificar posibles valores atípicos.
- Segmentar clientes por edad y nivel de uso.
- Proponer recomendaciones comerciales basadas en los resultados.

## Datasets

El proyecto utiliza los siguientes archivos:

- `plans.csv`: información de los planes y sus tarifas.
- `users_latam.csv`: información demográfica y contractual de los clientes.
- `usage.csv`: registros de llamadas y mensajes.

Los archivos deben estar disponibles en las rutas especificadas en el notebook o adaptarse a la ubicación correspondiente.

## Herramientas utilizadas

- Python
- Pandas y NumPy para la manipulación y limpieza de datos.
- Matplotlib y Seaborn para la visualización.
- Jupyter Notebook para el análisis exploratorio.

## Etapas del análisis

1. Exploración inicial de los datasets y revisión de tipos de datos.
2. Diagnóstico de valores faltantes e inconsistencias.
3. Limpieza de valores centinela y fechas fuera de rango.
4. Agregación de métricas de uso por usuario.
5. Análisis estadístico y visualización de distribuciones.
6. Identificación de valores atípicos mediante el método IQR.
7. Segmentación de clientes por nivel de uso y edad.
8. Elaboración de conclusiones y recomendaciones comerciales.

## Hallazgos y criterios de análisis

El análisis contempla la distribución de mensajes, llamadas y minutos de uso, así como las diferencias entre los grupos de clientes.

Los valores atípicos se identifican mediante el método del rango intercuartílico (IQR). Se evalúa su proporción respecto de los valores válidos antes de decidir si requieren revisión adicional.

Los valores faltantes se analizan considerando su significado y su relación con otras variables. No se imputan ni eliminan automáticamente cuando podrían representar características reales del servicio.

Las conclusiones y recomendaciones finales se presentan en el notebook a partir de los resultados obtenidos.

## Cómo reproducir el análisis

1. Descarga el archivo `S7 Version-Estudiante-Project-ConnectaTel.ipynb` desde este repositorio.
2. Abre Google Colab o Jupyter Notebook.
3. Carga el notebook.
4. Asegúrate de que los archivos CSV estén disponibles en las rutas utilizadas por el código.
5. Ejecuta las celdas en orden, desde el inicio hasta el final.
6. Revisa las tablas, visualizaciones y conclusiones generadas.

## Archivo principal

`S7 Version-Estudiante-Project-ConnectaTel.ipynb`

Contiene el código, el análisis exploratorio, las visualizaciones, la segmentación de clientes y las conclusiones del proyecto.
