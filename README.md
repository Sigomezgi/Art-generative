
![](https://upload.wikimedia.org/wikipedia/commons/5/53/UNAL_Aplicaci%C3%B3n_Medell%C3%ADn.svg)

<center> <h1> Arte generativo a partir de métodos de aprendizaje estadístico y expreciones matemáticas </h1> </center>
<center> <h4> Juan Daniel Bula Isaza - Bryan Garcia Villa - Simón Gómez Giraldo - Carolina Quintero Osorio </h4> </center>
<center> <h5> 9 de Febrero de 2022 </h5> </center>

## Resumen
<p align = "justify"> Es impresionante el potencial que puede llegar a tener la inteligencia artificial, tanto, como para desarrollar obras de arte, piezas músicales, videos, entre otras cosas más, que cada día se están explorando en este gigantezco mundo.   </p>

<p align = "justify">El gran objetivo de este trabajo es la implementación de un modelo que permita predecir el número de vehículos registrados diariamente en el Registro Único Nacional de Tránsito (RUNT), utilizando como insumo principal la base de datos proporcionada para su elaboración, con el nombre de registros_autos, la cual incluye la fecha y el número de registros de vehículos en determinada fecha. </p>

## Introducción

<p align = "justify">  </p>

<p align = "justify"> </p>









# Art-generative
Se presenta a continuación el desarrollo para la generación de las imágenes. 
Al final se realiza una apreciación  artística de las imágenes generadas por parte del equipo.

# Generación de imágenes
Para la generación de imágenes se tuvieron en cuenta tres aspectos: Funciones hiperbólicas, distribuciones de probabilidad normal y modelos estadísticos.

# Pasos

- Se creó una malla de puntos de dos variables a partir de una distribución de probabilidad normal.
- Estos puntos fueron evaluados en una función hiperbólica compuesta. Z
- A partir de los datos creados y de la salida de la función, se evalua varios modelos que se aproximan a la variable respuesta, en este caso, el valor de Z.
- Se implementa unos de los modelos probados, la elección de este no se baso en su aproximación al target sino que se probo con un modelo de libre elección. La idea de la creación de este modelo es agregar arte estadística a las imágenes creadas por medio de perturbaciones de las funciones generadoras de imágenes.
- El procedimiento anterior se realiza en dos ocasiones para generar dos modelos que aporte arte a través del error.
- Los modelos creados fueron: Regresión Lasso y Elastic Net, respectivamente.
- Luego de creado los modelos, se crea una malla con una distribución normal para ser evaluadas en el modelo creado.
- A partir de la librería, Samila, se crean 10 imágenes cada una con un par de funciones trigonométricas hiperbólicas modificada por ambos modelos.



# Exposición artística.


![primera](https://user-images.githubusercontent.com/94578395/153294293-d15d8e5c-2384-4821-9acf-8d32abe88db6.JPG)

![segunda](https://user-images.githubusercontent.com/94578395/153294327-6d9641a2-7190-493e-ba91-d834ebd1fd32.JPG)

![3](https://user-images.githubusercontent.com/94578395/153294349-0a9a4cdb-2d11-405e-9083-65fc417eb92e.JPG)

![4](https://user-images.githubusercontent.com/94578395/153294363-11b5f98a-4cab-41ce-9d6a-9a380f4b30ce.JPG)

![5](https://user-images.githubusercontent.com/94578395/153294381-ed206f61-28b3-4e62-9709-feb59e50264c.JPG)

![6](https://user-images.githubusercontent.com/94578395/153294406-89524043-13c9-49bf-bbbf-9e612128041f.JPG)


![7](https://user-images.githubusercontent.com/94578395/153294439-95fd3459-239a-4aa0-b30c-3f9fd9086cbc.JPG)

![8](https://user-images.githubusercontent.com/94578395/153294465-12a6edbf-80e0-42c5-a415-69253fcec031.JPG)

![9](https://user-images.githubusercontent.com/94578395/153294501-3f555f29-4f27-4138-9f15-85eff41a40bb.JPG)

![10](https://user-images.githubusercontent.com/94578395/153294527-7b68f3f2-8c6b-4c71-bc57-3922a3c00a5b.JPG)





