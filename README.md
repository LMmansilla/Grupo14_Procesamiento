# Grupo14_Procesamiento
<h1 align="center"> Hoteles en Valencia </h1>

#### PROCESAMIENTO DE DATOS 
#### COHORTE 2022

#### TECNICATURA EN CIENCIAS DE DATOS E INTELIGENCIA ARTIFICIAL

**Colaboradores:**

- [Hanun Romina](https://github.com/RomiHanun) 
- [Kanneman Samuel](https://github.com/samuelkanneman)
- [Zelarayán Román ](https://github.com/romanzelararg)
- [Mansilla Leonardo Matias ](https://github.com/LMmansilla)
- [Lucero Carla](https://github.com/CarlaLucerocd)
- [Barea Silvana](https://github.com/recursosssbb)
![Hoteles Valencia  ](https://github.com/LMmansilla/Grupo14_Procesamiento/assets/108492765/aba9bc0b-a27e-48ed-bca2-02095a406890)

### Objetivos del Proyecto

En base al dataset elegido para éste proyecto que contiene datos extraídos de Booking sobre los precios medios de hoteles en la ciudad de Valencia en fin de semana, por habitación y por persona individual, que incluye información sobre variables como el número de comentarios, la valoración del hotel, el código postal o el distrito de éstos, los objetivos de éste trabajo son:
* Recolección y preparación de datos: Obtener o recolectar conjuntos de datos relevantes para el tema elegido. Realizar las tareas de limpieza, integración y transformación necesarias para preparar los datos para el análisis.

* Análisis exploratorio de datos: Aplicar técnicas de análisis exploratorio para comprender y explorar los datos en profundidad. Esto puede incluir la identificación de patrones, relaciones, valores atípicos y distribuciones de variables.

* Procesamiento y análisis de datos: Aplicar técnicas de procesamiento de datos para realizar tareas como filtrado, agregación, transformación y cálculo de métricas relevantes para el tema elegido. Utilizar herramientas de software y lenguajes de programación adecuados para llevar a cabo estas tareas.

* Visualización de datos: Utilizar técnicas y herramientas de visualización de datos para representar gráficamente la información obtenida. Se deben explorar diferentes técnicas de visualización, como gráficos de barras, gráficos de dispersión, diagramas de caja, mapas, entre otros. Además, aplicar técnicas de visualización de múltiples variables para identificar relaciones y patrones complejos en los datos.

* Comunicación efectiva de resultados: Generar reportes que presenten de manera clara y concisa los resultados obtenidos durante el procesamiento y análisis de datos.

### Origen de Datos para el Proyecto:

### Librerías utilizadas 📋

* pandas as pd :  Esta librería es ampliamente utilizada para el manejo y análisis de datos en Python.
                  Proporciona estructuras de datos y herramientas para manipular y analizar datos de manera eficiente.
  
* matplotlib.pyplot as plt:  Matplotlib es una librería de visualización de datos en Python.
                             pyplot es una interfaz para crear gráficos estáticos, como gráficos de líneas, barras, dispersión, etc.
  
* seaborn as sns: Seaborn es otra librería de visualización de datos en Python.
                  Proporciona una interfaz de alto nivel para crear gráficos atractivos y informativos.

* geopandas as gpd: Geopandas es una extensión de la librería pandas que agrega capacidades geoespaciales.
                    Es útil para trabajar con datos geográficos, como mapas y datos de ubicación.
  
* heapq: Es una librería estándar de Python que proporciona implementaciones eficientes de estructuras de datos de montículos (heap).
  
* matplotlib inline: Esta línea de código es comúnmente utilizada en Jupyter Notebook para mostrar gráficos en línea.


## Construido con 🛠️

* ((https://www.kaggle.com/datasets/igmoncan/hoteles-en-valencia?select=valenciahoteles.csv)) - Dataset usado


### Mediante el conocimiento del cursado de Procesamiento de datos TSCDIA, realizamos:

* Creación de repositorio en GitHub. https://github.com/LMmansilla/Grupo14_Procesamiento.git  
* Desde Visual Code realizamos la creación y programación de los archivos para el proyecto.
* Programamos incluyendo librerías para la obtención de datos de la pagina relacionada a los próximos 10 meses sobre los precios medios en fin de semana (por habitación privada y un individuo) de hoteles ubicados en la ciudad de Valencia (datos de Booking). Además, incluye también otras variables como son el número de comentarios, la valoración del hotel, el código postal o el distrito de éstos.  
* Una vez realizada la extracción de datos se exportan a csv laestructura adecuada, como un DataFrame en pandas.
* Se debe revisar la estructura del dataset: mostrar las primeras filas del DataFrame para obtener una vista previa de los datos.
* Usamos funciones como head(), info() y describe() para obtener información sobre las columnas, tipos de datos, estadísticas resumidas, etc
* Se realiza una limpieza inicial de los datos, que incluye eliminar columnas irrelevantes, manejar valores faltantes o duplicados, corregir errores en los datos, etc. 
* Se analiza cada variable por separado para comprender su distribución, identificar valores atípicos o anomalías, y obtener estadísticas descriptivas relevantes.
* Utilizamos gráficos como histogramas, gráficos de barras o diagramas de dispersión, gráficos de líneas, etc.
* Se examinan relaciones entre diferentes variables para identificar patrones o tendencias para visualizar dichas relaciones.
* Con técnicas estadísticas para obtener insights adicionales sobre los datos calculamos medidas de tendencia central, dispersión y correlación. Realizamos pruebas de hipótesis o análisis de varianza, si es relevante para el conjunto de datos.
* Con estas tecnicas encontramos gráficos y visualizaciones adecuadas para mostrar hallazgos de manera clara y concisa.
* Para realizar el procesamiento y análisis de datos en profundidad sobre el caso de precios medios de hoteles en Valencia utilizamos las herramientas de software y lenguajes de programación necesarios como
  -Python: Un lenguaje de programación ampliamente utilizado en el análisis de datos. Python proporciona una variedad de bibliotecas y herramientas para el procesamiento y análisis de datos, como pandas, NumPy, Matplotlib, Seaborn y scikit-learn.
  -Pandas: Una biblioteca de Python que ofrece estructuras de datos y herramientas para el manejo y análisis de datos. Permite realizar operaciones como filtrado, agregación, transformación y cálculo de métricas en los datos de forma eficiente.
  -NumPy: Una biblioteca de Python para el cálculo numérico. Proporciona una variedad de funciones y métodos para realizar operaciones matemáticas y estadísticas en los datos, como cálculos de promedio, desviación estándar y otras métricas.
  -Matplotlib y Seaborn: Bibliotecas de visualización de datos en Python. Estas herramientas permiten crear gráficos, diagramas y visualizaciones para explorar y comunicar los resultados del análisis de datos.
  -Jupyter Notebook: Una herramienta interactiva que permite combinar código, visualizaciones y texto explicativo en un entorno integrado. Es útil para realizar análisis exploratorios y documentar los pasos y resultados del análisis de datos.

## Conclusión

En este proyecto de análisis de precios medios de hoteles en Valencia, se aplicaron diversas técnicas de procesamiento y análisis de datos utilizando un conjunto de datos específico.
Se utilizó el lenguaje de programación Python como principal herramienta, aprovechando su amplia gama de bibliotecas y herramientas especializadas en el análisis de datos, como Pandas, NumPy, Matplotlib y otras.. Estas bibliotecas permitieron realizar tareas de filtrado, agregación, transformación y cálculo de métricas relevantes para comprender en profundidad los datos.  
Se aplicaron técnicas de análisis exploratorio de datos para identificar patrones, relaciones y distribuciones de variables clave, como la valoración del hotel, el número de comentarios y los precios. Esto ayudó a obtener insights valiosos sobre los precios medios de los hoteles en Valencia y cómo se relacionan con otras variables.obtener insights relevantes para comprender mejor el mercado hotelero en la ciudad. Estas técnicas y herramientas proporcionaron una base sólida para el análisis de datos y la toma de decisiones informadas en el ámbito de los precios de hoteles.
Además, se utilizaron técnicas de visualización de datos para representar gráficamente los resultados del análisis, lo que facilitó la comprensión y comunicación de los hallazgos.

glosario= "Insights" es un término utilizado en el análisis de datos y la investigación para referirse a las percepciones, conocimientos o entendimientos profundos que se obtienen a partir del análisis de los datos. Los insights son hallazgos valiosos y significativos que brindan una comprensión más profunda de un fenómeno o situación estudiada.
Los insights pueden surgir al descubrir patrones, relaciones o tendencias en los datos, al identificar factores clave que influyen en un resultado o al comprender el comportamiento de una variable en particular. Estos conocimientos aportan una perspectiva más informada y ayudan a tomar decisiones estratégicas, resolver problemas o desarrollar recomendaciones basadas en evidencia.
En el contexto de un proyecto de análisis de precios medios de hoteles en Valencia, los insights podrían incluir descubrimientos sobre los factores que influyen en los precios de los hoteles, como la ubicación, la valoración de los clientes o la disponibilidad de servicios adicionales. También podrían revelar patrones de demanda en función de la temporada o eventos especiales, o incluso identificar oportunidades de mejora en la estrategia de precios de los hoteles.

En resumen, los insights son los conocimientos valiosos y relevantes que se obtienen a partir del análisis de datos, y son fundamentales para tomar decisiones informadas y obtener una comprensión más completa de un problema o situación.

