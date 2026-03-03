# Challenge-ONE-Data-Science
Es mi primer archivo de data science
Análisis de Ingresos de Tiendas con Python
Este proyecto consiste en un análisis automatizado de ventas para cuatro tiendas distintas, procesando datos externos y generando métricas financieras clave mediante el uso de Pandas y visualizaciones estadísticas.

🚀 Contenido del Notebook
El análisis se divide en tres etapas técnicas principales:

1. Extracción y Carga de Datos
Fuentes Externas: Carga de archivos CSV directamente desde repositorios de GitHub mediante URLs en formato Raw.

Manejo de Errores: Resolución de conflictos de tokenización (ParserError) asegurando la integridad de la lectura de datos.

2. Procesamiento y Métricas
Ingreso Total: Cálculo de la suma acumulada de la columna Precio para cada conjunto de datos de las tiendas.

Análisis Estadístico: Obtención de promedios (mean) para entender el ticket medio por sucursal.

Automatización: Uso de bucles e enumerate para procesar múltiples DataFrames de forma eficiente.

3. Visualización de Datos
El proyecto genera tres tipos de gráficos distintos para interpretar los resultados:

Gráfico de Barras: Comparativa visual de los ingresos totales entre tiendas.

Gráfico de Pastel: Proporción y participación porcentual de cada tienda en el ingreso global.

Boxplot (Diagrama de Cajas): Análisis de la distribución de precios y detección de valores atípicos (outliers).

🛠️ Tecnologías Utilizadas
Google Colab: Entorno de ejecución en la nube.

Pandas: Manipulación y limpieza de estructuras de datos.

Matplotlib / Seaborn: Generación de gráficos estadísticos de alta calidad.

📋 Requisitos para Ejecución
Para replicar el análisis, asegúrate de contar con la columna denominada exactamente Precio en tus archivos de origen y ejecutar las celdas en orden secuencial.
