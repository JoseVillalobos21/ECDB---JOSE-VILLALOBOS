# Extracción del conocimiento de Base de Datos - Prácticas

## Información del Alumno

- **Nombre del Alumno:** Jose Manuel Lara Villalobos
- **Materia:** Extracción del conocimiento de Base de Datos
- **Cuatrimestre:** 9no Cuatrimestre

## Descripción General

Este repositorio contiene un conjunto de prácticas (Labs) enfocadas en la manipulación, limpieza y análisis de datos utilizando Python. A través del uso de la librería Pandas, se explora cómo transformar datos crudos y sucios en formatos útiles para la posterior extracción de conocimiento y toma de decisiones.

## Objetivo

El objetivo principal de estas prácticas es adquirir habilidades sólidas en el Análisis Exploratorio de Datos (EDA), limpieza de datasets, manejo de valores nulos y estructuración de información, sentando las bases para el modelado y la minería de datos.

## Datasets Utilizados

- `netflix_titles.csv` - Dataset con información sobre películas y series de Netflix, útil para explorar distribuciones y análisis de texto.
- `Data_Limpio_Factura.csv` - Datos de facturación previamente procesados, usados para analizar patrones de ventas.
- `ventas-por-factura.csv` - Dataset transaccional que permite la agregación de métricas de negocio.
- `dataset_sucio_practica.csv` - Un conjunto de datos con inconsistencias diseñado específicamente para poner a prueba las técnicas de limpieza (data cleaning).
- `test.csv` - Dataset secundario para pruebas rápidas de lectura y formateo.

## Herramientas Utilizadas

- **Python**: Lenguaje de programación principal.
- **Jupyter Notebook**: Entorno interactivo para la ejecución del código y visualización.
- **Pandas**: Librería clave para la manipulación y análisis de estructuras de datos (DataFrames).
- **GitHub**: Control de versiones y organización del proyecto.

## Instrucciones de Ejecución General

1. Clonar el repositorio: `git clone https://github.com/JoseVillalobos21/ECDB---JOSE-VILLALOBOS.git`
2. Navegar a la carpeta del proyecto.
3. Asegurarse de tener instalado Python y las dependencias necesarias ejecutando: `pip install pandas jupyter`
4. Abrir los archivos de la carpeta `Notebooks/` utilizando Jupyter Notebook o Visual Studio Code.
5. Los archivos de datos se encuentran en la carpeta `DataSet/`. Los notebooks ya están configurados con la ruta relativa correcta (`../DataSet/`).
6. Ejecutar las celdas secuencialmente para observar la carga, transformación y resultados de los datos.

## Capturas o Imágenes de los Análisis

A lo largo de los notebooks, se visualizan múltiples salidas de tablas (DataFrames) que muestran:

1. La estructura inicial de los datos (`df.head()`).
2. Resúmenes estadísticos (`df.describe()`).
3. El estado de la limpieza y la información de los tipos de datos (`df.info()`).
   _(Nota: Las salidas visuales están renderizadas nativamente en las celdas de los archivos .ipynb)_

## Conclusiones Generales

A partir de la realización de estos laboratorios, queda en evidencia que la mayor parte del tiempo en un proyecto de datos se invierte en la recolección, entendimiento y limpieza de la información. La librería Pandas ha demostrado ser sumamente potente para automatizar la limpieza de nulos, formatear columnas y hacer consultas complejas. Lograr un dataset íntegro y estructurado es el paso más crítico antes de poder extraer cualquier tipo de conocimiento de valor.
