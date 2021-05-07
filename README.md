# Visualización 
Miércoles de 18 a 21 hs - 9 al 30 de Junio de 2021

Facultad de Medicina - Universidad de Buenos Aires

----------
## Docentes

_Dra. Maria Florencia D'Andrea - [INTA - CONICET](https://flor14.github.io/online-cv-es/)_ - 
<a href="https://twitter.com/cantoflor_87" class="twitter-follow-button" data-show-count="false">Twitter</a>

_Micaela Zapata_ - _Fmed - UBA_ - 
<a href="https://twitter.com/" class="twitter-follow-button" data-show-count="false">Twitter</a>

----------

## ¡Hola!

Agradeceriamos si puedes completar nuestra [encuesta inicial]()

----------

## Nuestra propuesta

El módulo de visualización presenta herramientas para graficar en R utilizando bases de datos relevantes para las ciencias de la salud. Nuestra prioridad es acompañar al estudiante en sus primeros pasos en el rol de científic@ de datos con R. Todo el curso esta enfocado en brindar los conceptos teóricos esenciales para reconocer y evitar las complicaciones típicas que suelen aparecer al escribir el código de los gráficos, haciendo énfasis en la práctica. 

En el transcurso de las cuatro clases propuestas será evidente la versatilidad que brinda R para visualización; en pocas líneas de código generaremos desde gráficos reproducibles con calidad de publicación así como visualizaciones interactivas que facilitan la comunicación de nuestros resultados para un público amplio.

----------

## Programa

#### Clase 1 - **Introducción a la visualización de datos en R y al paquete `ggplot2`** - Miércoles 9 de junio 
* ¿Qué es el `tidyverse` y por qué es importante conocerlo? 
* Introducción a `ggplot2` ¿Cómo nos ayuda que este paquete utilice la "gramática de gráficos"?
* Presentación de algunos de los tipos de gráficos más comunes. Funciones `geom_*()` y `aes()`.

*Objetivo*: Que los estudiantes creen un gráfico básico usando `ggplot()` y comprendan los fundamentos téoricos necesarios para evitar errores comunes que pueden aparecer ligados a (1) mapear tres variables (función `aes()`) y (2) la creación de gráficos en capas.

#### Clase 2 - **El desafío de graficar tus datos** - Miércoles 16 de junio 
* Preparando mi base de datos para graficar: tipos de datos y formato de tablas `long` y `wide` en relación a los tipos de gráficos.
* Control, alta y baja: el paquete `forcats` nos ayuda a trabajar con categorias.
* ¿Existe alguna alternativa al clásico gráfico de barras? Reflexionando sobre algunas visualizaciones comunes en el campo de las ciencias de la salud.

*Objetivo*: Que los estudiantes puedan realizar modificaciones en las bases de datos en relación a (1) el tipo de dato de las columnas que representan sus variables de interes, (2) el formato ancho o largo de la tabla y (3) distintas formas de exprear factores. Se pretende que el estudiante reconozca para el gráfico objetivo las transformaciones necesarias de realizar a sus datos de base.

#### Clase 3 - **Escalas, Gráficos interactivos y Reproducibilidad** - Miércoles 23 de junio 
* Selección de una paleta de colores adecuada (divergente, secuencial o cualitativa). Transformaciones en los ejes. Funciones `scale_*()` y `coord_*()`.
* ¿Cómo puede salvarte tiempo la reproducibilidad?. Comunicación efectiva de resultados. Funciones `theme_*()` y `ggsave()`.
* Gráficos interactivos en `plotly` y nociones sobre el concepto de sintaxis en programación que pueden evitarte dolores de cabeza.

*Objetivo*: Que los estudiantes puedan (1) elegir una paleta de colores en relación a la función `scale_*()` de forma apropiada, (2) que aseguren la reproducibilidad y calidad de sus gráficos (3) que empleen la función `ggplotly()` para obtener gráficos interactivos.
 
#### Clase 4 - **Aplicaciones web con `Shiny` / dashboards** - Miércoles 30 de junio 
* Introduccion al paquete `Shiny`. Diferencias con un dashboard. 
* Reactividad: uniendo la interfaz de usuari@ con el servidor.
* Deploy de la app en shinyapps.io. Otros tipo de deploy.
Cierre del curso 

*Objetivo*: Que los estudiantes puedan realizar una shiny app básica que permita al usuari@ modificar de forma interactiva variables de alguno de los gráficos que se desarrollaron durante el curso.

----------

## Material del curso
#### ¿Cómo instalar R y RStudio? 
 Para una mejor experiencia sugerimos acercarse con una computadora personal con R y RStudio instalados (pero esto no es excluyente). Información en este [Link](https://github.com/pachamaltese/tutoriales/blob/master/2019-04-24-instalar-r.md) para distintos sistemas operativos.
 
#### Filminas

[Filminas introductorias](https://flor14.github.io/intro_r/intro_r.html) 

[Filminas visualizacion](https://flor14.github.io/visualizacion_2020/visualizacion#1) 

[Práctica visualización](https://flor14.github.io/Curso_r_unne_2020/practica_vis_funciona.html)

[Resueltos Práctica de visualización / Práctica RMarkdown](https://github.com/flor14/Curso_r_unne_2020/blob/master/practica_vis_funciona.Rmd)

[Manejando archivos con purrr](https://docs.google.com/presentation/d/10grHphosFSbLWmF29tS1kiCguiisBvb0RrsnQu1omGs/edit?usp=sharing)

[Práctica Purrr](https://drive.google.com/open?id=1_Ej1bQCWNOZaSX31vVhFBt8gPlTtugeP)

Parte práctica [![Binder](https://mybinder.org/badge_logo.svg)]()

<a rel="license" href="https://creativecommons.org/licenses/by-sa/4.0/deed.es_ES"><img alt="Creative Commons License" style="border-width:0" src="https://i.creativecommons.org/l/by-sa/4.0/88x31.png" /></a><br /> Las filminas y código asociado se encuentran bajo licencia <a rel="license" href="https://creativecommons.org/licenses/by-sa/4.0/deed.es_ES">Creative Commons Attribution-ShareAlike 4.0 International License</a>.

#### Referencias principales

* [Gandrud, C. (2016). Investigación reproducible con R y R studio. Chapman y Hall / CRC](https://github.com/christophergandrud/Rep-Res-Book)
* [Ismay C, Kim A. (2019) Moderndive. Statistical Inference via Data Science. A moderndive into R and the tidyverse.](https://moderndive.com/)
* [Marwick B.,  Boettiger C. & Mullen L. (2018) Packaging Data  Analytical Work Reproducibly Using R (and Friends), The American Statistician, 72:1, 80-88](https://www.tandfonline.com/doi/full/10.1080/00031305.2017.1375986)
* [Thieme, N. (2018). R generation. Significance, 15(4), 14–19. 
](https://rss.onlinelibrary.wiley.com/doi/10.1111/j.1740-9713.2018.01169.x)
* [Xie, Y., Allaire, J. J., & Grolemund, G. (2018). R markdown: The definitive guide. Chapman and Hall/CRC.](https://bookdown.org/yihui/rmarkdown/)
* [Wickham, H. (2015). R packages: organize, test, document, and share your code. " O'Reilly Media, Inc.".](http://r-pkgs.had.co.nz)
* [Wickham, H., & Grolemund, G. (2016). R for data science: import, tidy, transform, visualize, and model data. " O'Reilly Media, Inc.". (EN ESPAÑOL)](https://es.r4ds.hadley.nz/)

#### Sitios de consulta

* [Machetes de RStudio](https://www.rstudio.com/resources/cheatsheets/)
* [Data to Viz. Consejos para generar gráficos con código R](https://www.data-to-viz.com/) 
* [R Cook Book BBC. Gráficos al estilo de la BBC](https://bbc.github.io/rcookbook) 
* [R Graph Gallery. Ejemplos para generar gráficos con código R](https://www.r-graph-gallery.com/) 
* [Guía para chequear estilos de gráficos](https://datavizchecklist.stephanieevergreen.com/assets/DataVizChecklist_Feb2018.pdf)
* [Paquete DataSaurus](https://cran.r-project.org/web/packages/datasauRus/vignettes/Datasaurus.html) 
* [Guía de estilo de código](https://style.tidyverse.org/)
* [Happy Git and GitHub for the useR - Jenny Bryan, the STAT 545 TAs, Jim Hester](https://happygitwithr.com/)
* [What they forgot to teach you about R - Jenny Bryan](https://whattheyforgot.org/)
* [Git for Humans](https://speakerdeck.com/alicebartlett/git-for-humans)

##### Visualización

* [Winston Chang R Graphics Cookbook](http://www.cookbook-r.com/)
* [Fundamentals of Data Visualization de Claus O. Wilke](https://serialmentor.com/dataviz/)
* [Socviz de Kieran Healy](https://socviz.co/)
* [Highcharter: graficos interactivos](http://jkunst.com/highcharter/)
* [Cowplot: ordenando graficos en grillas](https://wilkelab.org/cowplot/articles/plot_grid.html)

#### Material en español
* [Ciencia de datos para curiosos - Martín Montané](https://bookdown.org/martinmontaneb/CienciaDeDatos/)
* [Fundamentos de la Programación Estadística y Data Science en R - Versión tidyverse - German Rosati](https://github.com/gefero/tidy_fund_prog_r)
* [Ciencia de datos para gente sociable - Vazquez Brust](https://bitsandbricks.github.io/ciencia_de_datos_gente_sociable/)
* [El arte de programar en R - Julio Sergio Santana & Efraín Mateos Farfán [español]](http://bit.ly/2N2Y1Y8)
* [Introducción a tidyr: Datos ordenados en R (Rpubs) [español]](http://bit.ly/2AaWV9T)
* [Visualización estática e interactiva con ggplot2 y plotly [español]]( http://bit.ly/2xI2dqH)
* [Curso de R para procesamiento de datos de la Encuesta Permanente de Hogares - Diego y Natsu](https://diegokoz.github.io/Curso_R_EPH_clases/)

## Comunidades
 
 * [R-Ladies Global](https://rladies.org/) 
 * [R-Ladies Buenos Aires (twitter)](https://twitter.com/rladiesba?lang=es) 
 * [R-Ladies Rcia-Ctes (twitter)](https://twitter.com/RLadies_rciacte) 
 * [R-Spatial en español (grupo de Telegram)](https://web.telegram.org/#/im?p=@rspatial_es)
 * [R en Buenos Aires](https://renbaires.github.io/)
 * [ROpenSci](https://ropensci.org/)
 * [R4DS en Español (twitter)](https://twitter.com/r4ds_es?lang=es)
 * [The Carpentries](https://carpentries.org/)
 





