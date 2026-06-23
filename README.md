ConnectaTel - Análisis de Clientes y Patrones de Uso

Objetivo del proyecto

El objetivo de este proyecto es analizar el comportamiento de los clientes de ConnectaTel para identificar patrones de uso, detectar valores atípicos y segmentar a los usuarios según su nivel de consumo. Con base en estos hallazgos, se busca generar recomendaciones que permitan optimizar la oferta comercial y mejorar la experiencia de los clientes.

Datasets utilizados

El análisis se realizó utilizando tres conjuntos de datos:

plans.csv

Contiene la información de los planes ofrecidos por la empresa, incluyendo:

* Nombre del plan.
* Precio mensual.
* Minutos incluidos.
* Datos móviles incluidos.
* Costos adicionales por excedentes.

users_latam.csv

Contiene información demográfica y de contratación de los clientes:

* Identificador del usuario.
* Ciudad.
* Edad.
* Plan contratado.
* Fecha de registro.

usage.csv

Contiene el comportamiento real de uso de cada cliente:

* Número de llamadas.
* Duración de las llamadas.
* Mensajes enviados.
* Longitud de los mensajes.
* Tipo de interacción.

Etapas del análisis

El proyecto se desarrolló en las siguientes etapas:

1. Exploración inicial de los datos
    * Revisión de tipos de datos.
    * Identificación de valores faltantes y valores atípicos.
    * Obtención de estadísticas descriptivas.
2. Limpieza y preparación de datos
    * Conversión de tipos de datos.
    * Tratamiento de valores centinela.
    * Corrección de fechas fuera de rango.
    * Manejo de valores faltantes.
3. Construcción de variables agregadas
    * Total de mensajes por usuario.
    * Número de llamadas.
    * Minutos totales de llamadas.
4. Análisis exploratorio
    * Histogramas.
    * Boxplots.
    * Identificación de outliers mediante IQR.
    * Comparación entre planes.
5. Segmentación de clientes
    * Clasificación de usuarios en grupos de bajo, medio y alto uso.
6. Conclusiones y recomendaciones de negocio
    * Identificación de segmentos de mayor valor.
    * Propuestas para mejorar la oferta comercial.

Cómo ejecutar el proyecto

Opción 1: Google Colab

1. Descarga el archivo .ipynb.
2. Abre Google Colab.
3. Selecciona Archivo → Subir notebook.
4. Carga el archivo del proyecto.
5. Sube los archivos plans.csv, users_latam.csv y usage.csv.
6. Ejecuta las celdas en orden.

Guía de reproducción

Para reproducir el análisis:

1. Colocar los tres archivos .csv en el mismo directorio del notebook.
2. Ejecutar las celdas en el orden en que aparecen.
3. Revisar las visualizaciones y conclusiones obtenidas.
4. Comparar los resultados con las recomendaciones finales del proyecto.

Herramientas utilizadas

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Jupyter Notebook
* Google Colab
