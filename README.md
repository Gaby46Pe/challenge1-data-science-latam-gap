#**Challenge 1: Análisis de Datos de AluraStore Latam (challenge1-data-science-latam-gap)**

Este repositorio contiene el análisis de datos exploratorio (EDA) para poder realizar el challenge de Data Science de Alura Latam.

##**1. Propósito del Análisis**

El propósito de este proyecto es ayudar a un cliente, el Sr. Juan, a decidir qué tienda de su cadena Alura Store debe vender para iniciar un nuevo emprendimiento. Para ello, analizaremos los datos de ventas, rendimiento y reseñas de las cuatro tiendas de Alura Store (Tienda 1, Tienda 2, Tienda 3 y Tienda 4). El objetivo es identificar la tienda menos eficiente y presentar una recomendación final basada en los datos.
 
##**2. Estructura del Proyecto**

El proyecto está en un notebook de Jupyter: AluraStoreLatam.ipynb

y contiene todo el proceso de análisis, desde la importación y limpieza de datos hasta la generación de visualizaciones y la extracción de insights.

Dentro encontrarán el Informe Final donde basándonos en los datos trabajados, se presenta la recomendación final.

En este README.md econtrarán la Documentación del proyecto.

Los datos se cargan directamente desde URLs externas (archivos CSV) especificadas dentro del notebook.

##**3. Ejemplos de Gráficos e Insights Obtenidos**

Durante el análisis en el notebook, se generaron varias visualizaciones para comparar las tiendas:

<span style="color: purple;">Gráfico 1: Ingresos Totales por Tienda (Barras)</span>

Insight: La Tienda 1 lidera en ingresos totales, pero la Tienda 4 tiene los ingresos más bajos.

<span style="color: lightblue;">Gráfico 2: Distribución de Categorías (Barras Horizontales)</span>

Insight: Las categorías "Electrónicos" y "Muebles" dominan el volumen de ventas y los ingresos en las cuatro tiendas.

<span style="color: gold;">Gráfico 3: Distribución de Calificaciones (Líneas/Barras)</span>

Insight: Todas las tiendas tienen una mayoría de calificaciones de 5. Sin embargo, un cálculo del promedio revela que la Tienda 3 tiene la satisfacción promedio más alta (4.04), mientras que la Tienda 1 tiene la más baja (3.98).

<span style="color: pink;">Gráfico 4: Costo de Envío Promedio (Barras)</span>

Insight: La Tienda 4 ofrece los costos de envío más bajos, mientras que la Tienda 1 tiene los más altos.

##**4. Instrucciones para Ejecutar el Notebook**

Para ejecutar este análisis, siga estos pasos:

**Requisitos:**
Python 3.x
Jupyter Notebook o Google Colab
Bibliotecas de Python: pandas, matplotlib

**Instalación (si se ejecuta localmente):**

pip install pandas matplotlib jupyter

**Ejecución:**

Abrir AluraStoreLatam.ipynb en el entorno de Jupyter o subirlo a Google Colab.

Ejecuta las celdas en orden (o selecciona "Run All" / "Ejecutar todas").

El notebook cargará los datos automáticamente desde las URLs proporcionadas y generará las tablas y gráficos del análisis.
