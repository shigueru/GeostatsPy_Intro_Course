# Traducción de los Jupyter Notebooks del curso

## Sección del traductor

Esta carpeta contendra una traducción al idioma español de los Jupyter Notebook del curso. La traducción tendra las siguientes características:

* Se traduciran las celdas de texto.
* Se traduciran los comentarios dentro de las celdas de código.
* No se traduciran textos escritos mediante sentencias print dentro de las celdas de código.
* No se traduciran los nombres de variables dentro de las celdas de código ni sus referencias en las celdas de texto.
* No se traducira la sección de información del autor original. Con la intención de mantener la intención del autor totalmente intacta evitar molestias al autor original por un error de traducción.

Si existiera alguna situación especial no comprendidad en la lista anterior se usara un formato de **Nota de traductor** en una celda de texto para dar mas detalle de las acciones tomadas.

Dentro del repositorio tambien se encuentra una carpeta con diapositivas. Este material no sera traducido porque no se tiene acceso a las imagenes originales usadas. Y usar capturas de pantalla de las imagenes reduciria la calidad de la información transmitida.

### **Sobre el traductor**

Shigueru Nagata, maestro en Ciencias con mención en Física por la Universidad Nacional de Ingeniería. Investigador en ciencia de materiales en el área de métodos computacionales para modelamiento de nanomateriales. Con experiencia en el uso de los softwares de simulación Quantum ESPRESSO y LAMMPS. Y aplicación del lenguaje de programación Python para el procesamiento de datos obtenidos de simulaciones computacionales.

## Traducción del Readme original

# Análisis de Datos Espaciales de Código Abierto en Python con [GeostatsPy](https://github.com/GeostatsGuy/GeostatsPy), Curso Corto

## Por Michael Pyrcz, Profesor Asociado de la Universidad de Texas en Austin

Este curso provee una introducción a GeostatsPy, un paquete de Python de código abierto para el análisis de datos espaciales/Sub-Superficie y geoestadística, con los conceptos fundamentales del análisis de datos espaciales en clases acompañadas por demostraciones o ejercicios interactivos y ejemplos de flujos de trabajo mas completos y mejor documentados.

### Antes de empezar el curso porfavor instala lo siguiente:

1 Anaconda 3.*
2 El paquete GeostatsPy

Para mas detalles ver abajo.

Yo he incluido en este repositorio todo el contenido del curso:

1 Las clases como PDF en la carpeta [Lectures](https://github.com/shigueru/GeostatsPy_Intro_Course/tree/master/Lectures)

2 Demostraciones de flujos de trabajo en Python interactivos y bien documentados en la carpeta [Workflows](https://github.com/shigueru/GeostatsPy_Intro_Course/tree/master/Workflows)

3 Conjuntos de datos necesarios para los flujos de trabajo en la carpeta [Datasets](https://github.com/shigueru/GeostatsPy_Intro_Course/tree/master/DataSets)

### Objetivos del curso

Tú ganaras

* Conocimiento sobre el uso basico del paquete GeostatsPy para el analisis de datos espaciales y de sub-superficie además de geoestadística en Python.
* Experiencia practica en varios flujos de trabajo en Python sobre geoestadística y analisis de datos geoespaciales.

### Agenda del curso

El curso corto esta separado en cinco secciones, que incluyen:

1 **Introducción**: Objetivos y plan.
2 **Calculo de variograma**: Quantificar la continuidad espacial.
3 **Modelamiento de variograma**: Formulación de modelos validos de continuidad espacial.
4 **Kriging**: Estimación espacial.
5 **Conclusiones**: Resumen y retroalimentación.

### Comenzemos

Estos son los pasos para poder instalar localmente Anaconda con Python 3.*, paquetes comunes de Python, Jupyter Notebooks y el paquete GeostatsPy.

1 Instala [Anaconda 3](https://www.anaconda.com/products/individual)
2 Desde Anaconda Navigator (Dentro del grupo Anaconda) ve a la pestaña de *enviorement* (entorno), clic en la flecha verde de **base** (root) y abre una terminal.
3 En la terminal tipea: pip install geostatspy
4 Abre Jupyter Notebook y en el primer bloque empieza copiando y pegando el bloque de código de bajo, para empezar a usar la funcionalidad de GeostatsPy desde el Jupyter Notebook.

```python
import geostatspy.GSLIB as GSLIB
import geostatspy.geostats as geostats
```
para mas información sobre el paquete GeostatsPy revisa la [documentacion](https://github.com/GeostatsGuy/GeostatsPy) y el [código](https://github.com/GeostatsGuy/GeostatsPy/tree/master/geostatspy)

Tú necesitas copiar estos archivos de datos a tu directorio de trabajo. Estos estan disponibles en la carpeta [Datasets](https://github.com/shigueru/GeostatsPy_Intro_Course/tree/master/DataSets)

* [sample_data_MV_biased,csv](https://github.com/shigueru/GeostatsPy_Intro_Course/blob/master/DataSets/sample_data_MV_biased.csv)
* [sample_data_biased.csv](https://github.com/shigueru/GeostatsPy_Intro_Course/blob/master/DataSets/sample_data_biased.csv)

#### The Instructor:

### Michael Pyrcz, Associate Professor, University of Texas at Austin 
*Novel Data Analytics, Geostatistics and Machine Learning Subsurface Solutions*

With over 17 years of experience in subsurface consulting, research and development, Michael has returned to academia driven by his passion for teaching and enthusiasm for enhancing engineers' and geoscientists' impact in subsurface resource development. 

For more about Michael check out these links:

#### [Twitter](https://twitter.com/geostatsguy) | [GitHub](https://github.com/GeostatsGuy) | [Website](http://michaelpyrcz.com) | [GoogleScholar](https://scholar.google.com/citations?user=QVZ20eQAAAAJ&hl=en&oi=ao) | [Book](https://www.amazon.com/Geostatistical-Reservoir-Modeling-Michael-Pyrcz/dp/0199731446) | [YouTube](https://www.youtube.com/channel/UCLqEr-xV-ceHdXXXrTId5ig)  | [LinkedIn](https://www.linkedin.com/in/michael-pyrcz-61a648a1)

#### Want to Work Together?

I hope that this is helpful to those that want to learn more about subsurface modeling, data analytics and machine learning. Students and working professionals are welcome to participate.

* Want to invite me to visit your company for training, mentoring, project review, workflow design and consulting, I'd be happy to drop by and work with you! 

* Interested in partnering, supporting my graduate student research or my Subsurface Data Analytics and Machine Learning consortium (co-PIs including Profs. Foster, Torres-Verdin and van Oort)? My research combines data analytics, stochastic modeling and machine learning theory with practice to develop novel methods and workflows to add value. We are solving challenging subsurface problems!

* I can be reached at mpyrcz@austin.utexas.edu.

I'm always happy to discuss,

*Michael*

Michael Pyrcz, Ph.D., P.Eng. Associate Professor The Hildebrand Department of Petroleum and Geosystems Engineering, Bureau of Economic Geology, The Jackson School of Geosciences, The University of Texas at Austin

#### More Resources Available at: [Twitter](https://twitter.com/geostatsguy) | [GitHub](https://github.com/GeostatsGuy) | [Website](http://michaelpyrcz.com) | [GoogleScholar](https://scholar.google.com/citations?user=QVZ20eQAAAAJ&hl=en&oi=ao) | [Book](https://www.amazon.com/Geostatistical-Reservoir-Modeling-Michael-Pyrcz/dp/0199731446) | [YouTube](https://www.youtube.com/channel/UCLqEr-xV-ceHdXXXrTId5ig)  | [LinkedIn](https://www.linkedin.com/in/michael-pyrcz-61a648a1)
