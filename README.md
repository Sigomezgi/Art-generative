
![](https://upload.wikimedia.org/wikipedia/commons/5/53/UNAL_Aplicaci%C3%B3n_Medell%C3%ADn.svg)

<center> <h1> Arte generativo a partir de métodos de aprendizaje estadístico y expresiones matemáticas </h1> </center>
<center> <h4> Juan Daniel Bula Isaza - Bryan Garcia Villa - Simón Gómez Giraldo - Carolina Quintero Osorio </h4> </center>
<center> <h5> 9 de Febrero de 2022 </h5> </center>

# Resumen

<p align = "justify"> Imagina que entras a una galería de arte, y en el fondo ves una pintura bastante llamativa, con colores y figuras bastante estéticas, después de contemplar dicha pieza artística por un lapso de tiempo, te diriges a la etiqueta de información y descubres que la pieza fue elaborada por un sistema computacional, es algo muy interesante... ¿No?. Pues esto es una pequeña parte de lo que es el arte generativo y es precisamente lo que encontrarás en este blog. </p>


<p align = "justify"> Es impresionante el potencial que puede llegar a tener la inteligencia artificial, tanto, como para desarrollar obras de arte, piezas músicales, videos, entre otras cosas más, que cada día se están explorando en este gigantezco mundo. El gran objetivo de este trabajo, es generar obras de arte a partir de técnicas en aprendizaje estadístico, distribuciones de probabilidad multivariada y expresiones matemáticas, con el fin de presentar una colección de imágenes artísticas para posteriormente ser expuestas y documentadas en este blog.   </p>


# Introducción

<p align = "justify"> Con el desarrollo vertiginoso en la última década del fenómeno del Big Data y el crecimiento exponencial de la inteligencia artificial (IA) tanto en el arte como en múltiples campos del saber, se logra divisar un cambio sutil pero bastante potente en el panorama del cambio contemporáneo: La irrupción de creadores no humanos. Una de las tareas de este trabajo, es demostrar por medio de obras de arte generativo, su gran potencial y capacidad para el desarrollo de obras llamativas. </p>

<p align = "justify">En este punto, el lector podrá preguntarse que será el machine learning o la inteligencia artificial y que relación tiene con el arte, la respuesta es, dado que las redes neuronales artificiales y los demás métodos de aprendizaje, empezaron a hacer parte de nuestro ecosistema, por supuesto, empezaron a impactar de manera radical el sistema del arte, las obras realizadas a  partir de estas tecnologías se están multiplicando de manera exponencial.</p>


<p align = "justify"> En definitiva, las obras generadas con estas tecnologías, están impactando no solo el panorama artístico, sino también, otros campos como la música, la arquitectura, el diseño de modas, entre otros. Se presenta a continuación el desarrollo para la generación de las imágenes, donde al final, se realiza una apreciación  artística de las imágenes generadas por parte del equipo. </p>


# Generación de imágenes
Para la generación de imágenes se tuvieron en cuenta tres aspectos: Funciones hiperbólicas, distribuciones de probabilidad normal y modelos de aprendizaje estadístico.

## Pasos

- Se creó una malla de puntos de dos variables a partir de una distribución de probabilidad normal.
- Estos puntos fueron evaluados en una función hiperbólica compuesta. Z
- A partir de los datos creados y de la salida de la función, se evalua varios modelos que se aproximan a la variable respuesta, en este caso, el valor de Z.
- Se implementa unos de los modelos probados, la elección de este no se basó en su aproximación al target, sino que se probó con un modelo de libre elección. La idea de la creación de este modelo es agregar arte estadístico a las imágenes creadas por medio de perturbaciones de las funciones generadoras de imágenes.
- El procedimiento anterior se realiza en dos ocasiones para generar dos modelos que aporten arte a través del error.
- Los modelos creados fueron: Regresión Lasso y Elastic Net, respectivamente.
- Luego de creado los modelos, se crea una malla con una distribución normal para ser evaluadas en el modelo creado.
- A partir de la librería, Samila, se crean 10 imágenes cada una con un par de funciones trigonométricas hiperbólicas modificada por ambos modelos.



# Exposición artística.

<p align = "justify"> Ahora, se procede con la exposición de arte generativo: </p>





![primera](https://user-images.githubusercontent.com/94578395/153294293-d15d8e5c-2384-4821-9acf-8d32abe88db6.JPG)

### Pieza 1: Distribución de registros RUNT





![segunda](https://user-images.githubusercontent.com/94578395/153294327-6d9641a2-7190-493e-ba91-d834ebd1fd32.JPG)




![3](https://user-images.githubusercontent.com/94578395/153294349-0a9a4cdb-2d11-405e-9083-65fc417eb92e.JPG)




![4](https://user-images.githubusercontent.com/94578395/153294363-11b5f98a-4cab-41ce-9d6a-9a380f4b30ce.JPG)





![5](https://user-images.githubusercontent.com/94578395/153294381-ed206f61-28b3-4e62-9709-feb59e50264c.JPG)





![6](https://user-images.githubusercontent.com/94578395/153294406-89524043-13c9-49bf-bbbf-9e612128041f.JPG)






![7](https://user-images.githubusercontent.com/94578395/153294439-95fd3459-239a-4aa0-b30c-3f9fd9086cbc.JPG)





![8](https://user-images.githubusercontent.com/94578395/153294465-12a6edbf-80e0-42c5-a415-69253fcec031.JPG)





![9](https://user-images.githubusercontent.com/94578395/153294501-3f555f29-4f27-4138-9f15-85eff41a40bb.JPG)







![10](https://user-images.githubusercontent.com/94578395/153294527-7b68f3f2-8c6b-4c71-bc57-3922a3c00a5b.JPG)






















































## Referencias
  - James, G., Witten, D., Hastie, T., & Tibshirani, R. (2013). *An introduction to statistical learning (Vol. 112, p. 18). New York: springer.*
  - Stack Overflow - Where Developers Learn, Share, & Build Careers. (n.d.). Retrieved January 17, 2022, de: [Stackoverflow](https://stackoverflow.com/)
  - Hacia la ciencia de datos. (n.d.). Retrieved January 17, 2022, de: [Towards Data Science](https://towardsdatascience.com/)
  - FrikisparaGeeks | Un portal de informática para geeks. (n.d.). Retrieved January 17, 2022, de: [Geeks for geeks](https://www.geeksforgeeks.org/)
  

