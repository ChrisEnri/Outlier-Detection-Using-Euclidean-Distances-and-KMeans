Clusterización y detección de atípicos en datos simulados

Autor: Christian Amaro 

Descripción del proyecto

Este proyecto muestra un flujo reproducible en R para identificar valores atípicos en un conjunto de datos simulados. El análisis está enfocado en producción agrícola (ejemplo: Nopal verdura) y se centra en el tratamiento de una variable univariada.

El procedimiento consiste en:

- Carga y preparación de datos desde un archivo Excel, filtrando un subconjunto de interés y reemplazando valores faltantes.

- Clusterización con k-means usando un único centroide como referencia para calcular distancias.

- Detección de outliers aplicando la regla de ±3 desviaciones estándar respecto al centroide.

- Visualización y tabulación de resultados con gráficos y tablas de frecuencias.

Este flujo refleja cómo abordar problemas de limpieza, análisis exploratorio y detección de anomalías en datos numéricos.

Tecnologías empleadas

Lenguaje: R

Paquetes:

- dplyr y tidyverse para manipulación de datos

- readxl para importar datos desde Excel

- ggplot2 para visualizaciones

- cluster, KMEANS.KNN, caTools como soporte adicional

Uso

Clona este repositorio.

Coloca el archivo Excel (ejemplo: captacion simulada act.xlsx) en la carpeta principal.

Ejecuta el script .Rmd en RStudio o R.

Se generará un reporte en formato HTML con los resultados del análisis.
