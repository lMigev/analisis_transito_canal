# Análisis de tránsito del canal

Este repositorio contiene el código, los datos y las visualizaciones utilizadas para el análisis del tránsito en el canal y la creación de modelos predictivos basados en factores climáticos históricos y características de las embarcaciones.

## Entorno de desarrollo: Google Colab

**Importante:** El notebook principal de este proyecto (`transito_canal.ipynb`) fue desarrollado íntegramente utilizando el entorno de **Google Colab**. 

Para garantizar la correcta ejecución del código, la compatibilidad de las librerías instaladas y replicar exactamente las mismas condiciones de desarrollo, **se recomienda abrir y ejecutar este notebook en Google Colab**.

## Estructura del repositorio

El repositorio está organizado de la siguiente manera:

* **`transito_canal.ipynb`**: Notebook principal del proyecto. Contiene el flujo completo de análisis:
  * **`Limpieza y preparación de datos (ETL)`**
  * **`Análisis exploratorio (EDA)`**
  * **`Entrenamiento y evaluación de modelos predictivos`**
  * **`Interpretación de resultados`**
* **`Resumen Modelos Predictivos.pbix`**: Archivo de Power BI que contiene los tableros interactivos (dashboards) y la visualización final de los resultados obtenidos por los modelos predictivos.
* **`Power Bi presentación`**: Dashboard final utilizado en la presentación del proyecto, donde se integran los principales hallazgos, métricas y visualizaciones relevantes.
* **`data/`**: Carpeta que almacena los conjuntos de datos requeridos por el notebook.
  * **`clima_total_2015_2024.csv`**: Archivo CSV que contiene el registro histórico de las variables climáticas (2015-2024), fundamentales para el análisis de impacto ambiental en el canal.
  * **`lock_visit.parquet`**: Datos estructurados sobre las visitas y operaciones en las diferentes esclusas del canal.
  * **`specs.parquet`**: Especificaciones técnicas, dimensiones y características de las embarcaciones analizadas.
  * **`transit.parquet`**: Registro detallado e histórico de los tránsitos realizados a través del canal.
* **`Documentación`**: Contiene los documentos académicos desarrollados durante el proyecto.
  * **`Anteproyecto`**: Documento en formato word que contiene información del anteproyecto con la formulación inicial del estudio.
  * **`Avances`**: Documento en formato word de avance que incluye desarrollo metodológico y primeros análisis.
* **`Recursos visuales`**: Carpeta que almacena las imágenes generadas durante el análisis exploratorio y el modelado predictivo, utilizadas como apoyo visual en la presentación. 

## Instrucciones de uso

### Para el análisis de datos y modelado (Python)
1. Descarga o clona los archivos de este repositorio.
2. Sube el archivo `transito_canal.ipynb` a tu entorno de Google Colab.
3. Asegúrate de cargar todo el contenido de la carpeta `data/` (tanto el CSV como los archivos Parquet) en el entorno de ejecución de Colab para que el código pueda leer los datos correctamente.

### Para la visualización de resultados (Power BI)
1. Debes tener instalado **Microsoft Power BI Desktop**.
2. Abre el archivo `Resumen Modelos Predictivos.pbix` para interactuar con los dashboards y visualizar los resultados de los modelos.

## Contribuyentes

Este proyecto fue desarrollado en equipo. A continuación, los miembros que contribuyeron al desarrollo del mismo:

* Katherine Batista
* Kely Feng
* Jeremías Herreras
* Victoria Rodríguez
* Miguel Valzania


## Agradecimientos

Queremos expresar un especial agradecimiento a nuestro profesor, el *Dr. Juan Marcos Castillo*, por su guía, apoyo y conocimientos compartidos, los que fueron fundamentales para la realización de este proyecto.
