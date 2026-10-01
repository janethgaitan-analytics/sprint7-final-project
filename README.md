# sprint7-final-project

## Objetivo del Proyecto
Analizar e integrar datos de clientes, planes y uso de ConnectaTel para identificar problemas de calidad, estandarizar la información, construir métricas de comportamiento por usuario, detectar valores atípicos y segmentar clientes según edad y nivel de uso.

El análisis busca transformar los datos en insights accionables que permitan comprender mejor el comportamiento de los clientes y apoyar decisiones comerciales sobre planes, segmentación y oportunidades de mejora.

## Objetivos específicos

- Integrar y limpiar datos provenientes de tres fuentes diferentes.
- Validar tipos de datos, valores faltantes, sentinels y fechas inconsistentes.
- Construir métricas de uso por cliente a partir de llamadas y mensajes.
- Analizar distribuciones y detectar outliers mediante métodos estadísticos y visuales.
- Segmentar clientes según edad y comportamiento de uso.
- Comparar patrones entre segmentos y tipos de plan.
- Generar conclusiones y recomendaciones comerciales basadas en los hallazgos.
- Documentar el análisis en un Jupyter Notebook reproducible y versionarlo en GitHub.


## Datasets utilizados

Se utilizaron los siguientes archivos:

- `plans.csv`: información de los planes disponibles.
- `users_latam.csv`: información de los usuarios.
- `usage.csv`: registros de llamadas y mensajes.

## Etapas del análisis

1. Carga y revisión inicial de los datasets.
2. Exploración de estructura, tipos de datos y valores nulos.
3. Detección y corrección de sentinels y fechas inválidas.
4. Análisis de valores faltantes.
5. Creación de métricas de uso por usuario.
6. Análisis estadístico de clientes y uso.
7. Visualización de distribuciones y detección de outliers.
8. Segmentación de clientes por edad y nivel de uso.
9. Elaboración de insights y recomendaciones de negocio.

## Principales hallazgos

- Se detectaron valores inválidos en `age`, `city` y `reg_date`.
- La mayoría de los clientes pertenece al segmento de uso medio.
- El grupo de edad predominante corresponde a adultos entre 30 y 59 años.
- Se detectaron outliers en mensajes, llamadas y minutos de llamada, pero se mantuvieron porque pueden representar usuarios con un uso real intensivo.
- El plan Básico representa la mayor proporción de clientes.

## Cómo ejecutar el notebook

1. Descargar o clonar este repositorio.
2. Abrir el archivo `.ipynb` en Jupyter Notebook o Google Colab.
3. Asegurarse de tener disponibles los datasets utilizados.
4. Ejecutar las celdas en orden desde el inicio.

## Reproducción del análisis

El análisis puede reproducirse ejecutando todas las celdas del notebook en orden.

En Jupyter:

`Run → Restart Kernel and Run All Cells`

En Google Colab:

`Runtime → Run all`

## Herramientas utilizadas

- Python
- pandas
- seaborn
- matplotlib
- Jupyter Notebook

## Autora

Janeth Gaitán
