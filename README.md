# utdt_introDS_2022
Curso de introducción a la ciencia de datos con R - UTDT 2022


### [Franco Galeano](https://tartagalensis.netlify.app/)
### [Angie Scetta](https://github.com/angiescetta)


# Formato:
- Encuentros semanales de máximo 2 horas.
- Sincrónicos.
- Día y horario: Lunes 19:00 hs.


- __CLASE 1__ Introducción a la ciencia de datos y a la programación en R

Docente: Angie Scetta

¿Qué es la ciencia de datos? Ejemplos aplicados al Gobierno. Introducción a R, el entorno para analizar, modelar, visualizar y comunicar con datos. Carga y exploración de un dataset con R base.

- __CLASE 2__ Análisis exploratorio y transformación de datos

Docente: Angie Scetta

Data wrangling: limpiando y ordenando datos. Funciones para la transformación de datos. Introducción al paquete tidyverse y sus funciones: select(), filter(), mutate(), arrange(), rename(), group_by(), summarise(). Concatenar funciones con “pipe” %>%.

- __CLASE 3__ Pre procesamiento de datos

Docente: Franco Galeano

Técnicas fundamentales para la transformación de datos. Cruce de fuentes de datos. Más funciones de tidyverse: bind_rows(), bind_cols(), _join(), gather(), pivot_longer(), spread(), pivot_wider().

- __CLASE 4__ Visualización de datos I

Docente: Angie Scetta

Narrando la ciudad con información. Cómo elegir la visualización adecuada para cada tipo de análisis. Relacionar variables numéricas: Gráfico de puntos con geom_point(). Relacionar variables numéricas y categóricas: Gráfico de barras con geom_bar(). Distribución de variable continua: Gráfico de histograma con geom_histogram().

- __CLASE 5__ Visualización de datos II

Docente: Franco Galeano

Representar datos numéricos a través de sus cuartiles: Gráfico de boxplot con geom_boxplot(). Representar proporciones: Gráfico de árbol con geom_treemap() y Gráfico de waffle con geom_waffle(). Ajustes estéticos: tipografía, paletas de colores. Nociones de graficación: forma, color, tamaño. Facetado de gráficos a partir de una variable.

- __CLASE 6__ Visualización de datos III

Docente: Franco Galeano

¿Cómo describir una base de datos? Uso del comando skimr::skim(). Media, mediana, moda, quintiles/deciles, correlación y análisis bivariados. Introducción a tablas con kable y kableextra.

- __CLASE 7__ Detección de patrones temporales
Docente Angie Scetta
Analizar datos registrados a través del tiempo. Introducción al paquete lubridate y a la manipulación de datos temporales. Análisis temporal de los datos: ymd(). Líneas de tiempo: geom_line().

- __CLASE 8__ Información geográfica y mapas
Docente Angie Scetta
Introducción a la temática Analítica Urbana. Big Data y Ciudad. Datos georreferenciados. Visualizando información geográfica. Capas y geometrías. Introducción al paquete sf. Analizar datos espaciales con geom_sf(). Unir dataset tradicional y dataset espacial con left_join().

- __CLASE 9__ Análisis y geoprocesamiento de datos
Docente Angie Scetta
Trabajando con información georreferenciada. Gráficos de densidad de puntos: geom_bin2d(). Cruzando datos en base a su posición: uniones espaciales con st_join(). Descarga de "mapas base" para agregar contexto. Repaso de sf e introducción a ggmap.

- __CLASE 10__ Descarga y análisis de datos espaciales
Docente Angie Scetta
Acceso a información urbana georeferenciada en repositorios online. Introducción al paquete osmdata. Descarga y análisis de datos espaciales publicados en OpenStreetMap: osmdata_sf(). Introducción al desarrollo de mapas interactivos: leaflet().

# Contenidos y materiales

- __Unidad 1.__ Introducción a R y Rstudio. 
¿Por qué R? Instalación de Programas. Introducción al lenguaje y a la ambiente integrado de desarrollo (IDE). Directorios de trabajo y Proyectos. Objetos, tipos de variables, operadores y funciones básicas. Formatos de archivo. Documentación del código. Cómo pedir ayuda en R.

- __Unidad 2.__ Paquetes y Librerias. 
Instalación de paquetes y activación de librerías. Importación y exportación de datos. Funciones exploratorias. Fuentes principales para descarga de datos. Formatos de datos abiertos y cerrados.

- __Unidad 3.__ Limpieza y transformación de datos. 
R base y Tidyverse. Carga de datos con tidyverse. Formato de datos “tidy”. operaciones básicas de dplyr para limpieza y transformación. Trabajo y manipulación de
dataframes.

- __Unidad 4.__ Visualización de datos I. 
Introducción a ggplot2. Tipos de gráficos más usuales y elementos básicos. Trabajo en capas: datos, aesthetics, geometrías, facetas, stats, coordenadas y temas. Relación entre un gráfico y los datos. Representación como concepto. Ejes y variables.

- __Unidad 5.__ Introducción a GIT y Github e Integración con RStudio. 
¿Qué es el control de versiones ¿Por qué GIT y Github? Crear una cuenta en Github. Crear y trabajar con repositorios. Repos públicos y privados. Commit, Push, Pull, Fork y Branchs: Para qué nos sirven. Proyectos en Github. Buenas prácticas de trabajo con git y R. Descarga de Paquetes en desarrollo con devtools.

- __Unidad 6.__ Limpieza y transformación de datos II. 
Limpieza y manejo de datasets avanzado. Normalización de datos. Expresiones regulares.

- __Unidad 7.__ Visualización de datos II. 
Introducción conceptual (Infografías vs. gráficos; ejemplos históricos. Joseph Minard, William Playfair, John Snow, Florence Nightingale, Harry Beck). Replicabilidad. Gramática de gráficos. Visualización y generación de gráficos en R: Nociones de graficación (forma, color, tamaño, color).

- __Unidad 8.__ Informes reproducibles. 
Introducción a RmD. Construcción de tablas en kable. 



# Clase 1. 
- [Slides - html](clase_1/clase_1_presentacion.html)
- [Script](clase_1/clase_1_practica.R)


# Clase 2. 
- [Slides - html](clase_2/clase_2_presentacion.html)
- [Data](clase_2/data)
- [Scripts](clase_2/script)


# Clase 3. 
- [Slides - html](clase_3/clase_3_presentacion.html)
- [Data](clase_3/data)
- [Scripts](clase_3/script)



# Bibliografía y sitios de consulta

- [AnalizaR datos políticos](https://arcruz0.github.io/libroadp/)

- [Ciencia de Datos para Gente Sociable](https://bitsandbricks.github.io/ciencia_de_datos_gente_sociable/)

- [Documento Técnico N°6: Ciencia de Datos para el Turismo](https://dnme-minturdep.github.io/DT6_ciencia_de_datos_turismo/index.html#documento-t%C3%A9cnico-n%C2%BA6---resumen)
