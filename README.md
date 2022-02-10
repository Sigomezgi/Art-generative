
![](https://upload.wikimedia.org/wikipedia/commons/5/53/UNAL_Aplicaci%C3%B3n_Medell%C3%ADn.svg)

<center> <h1> Arte generativo a partir de métodos de aprendizaje estadístico y expresiones matemáticas </h1> </center>
<center> <h4> Juan Daniel Bula Isaza - Bryan Garcia Villa - Simón Gómez Giraldo - Carolina Quintero Osorio </h4> </center>
<center> <h5> 9 de Febrero de 2022 </h5> </center>

# Resumen

<p align = "justify"> Imagina que entras a una galería de arte, y en el fondo ves una pintura bastante llamativa, con colores y figuras bastante estéticas, después de contemplar dicha pieza artística por un lapso de tiempo, te diriges a la etiqueta de información y descubres que la pieza fue elaborada por un sistema computacional, es algo muy interesante... ¿No?. Pues esto es una pequeña parte de lo que es el arte generativo y es precisamente lo que encontrarás en este blog. </p>


<p align = "justify"> Es impresionante el potencial que puede llegar a tener la inteligencia artificial, tanto, como para desarrollar obras de arte, piezas músicales, videos, entre otras cosas más, que cada día se están explorando en este gigantezco mundo. El gran objetivo de este trabajo, es generar obras de arte a partir de técnicas en aprendizaje estadístico, distribuciones de probabilidad multivariada y expresiones matemáticas, con el fin de presentar una colección de imágenes artísticas para posteriormente ser expuestas y documentadas.   </p>


# Introducción

<p align = "justify"> Con el desarrollo vertiginoso en la última década del fenómeno del Big Data y el crecimiento exponencial de la inteligencia artificial (IA) tanto en el arte como en múltiples campos del saber, se logra divisar un cambio sutil pero bastante potente en el panorama del cambio contemporáneo: La irrupción de creadores no humanos. Una de las tareas de este trabajo, es demostrar por medio de obras de arte generativo, su gran potencial y capacidad para el desarrollo de obras llamativas. </p>

<p align = "justify">En este punto, el lector podrá preguntarse que será el machine learning o la inteligencia artificial y que relación tiene con el arte, la respuesta es, dado que las redes neuronales artificiales y los demás métodos de aprendizaje, empezaron a hacer parte de nuestro ecosistema, por supuesto, empezaron a impactar de manera radical el sistema del arte, las obras realizadas a  partir de estas tecnologías se están multiplicando de manera exponencial.</p>


<p align = "justify"> En definitiva, las obras generadas con estas tecnologías, están impactando no solo el panorama artístico, sino también, otros campos como la música, la arquitectura, el diseño de modas, entre otros. Se presenta a continuación el desarrollo para la generación de las imágenes, donde al final, se realiza una apreciación  artística de las mismas, generadas por parte del equipo. </p>


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

<p align = "justify"> Ahora, se procede con la exposición de arte generativo, donde como equipo, decisimos nombrar cada una de las obras segun lo que transmiten de forma abstracta. </p>



### Pieza 1: Tornado rojo

![primera](https://user-images.githubusercontent.com/94578395/153294293-d15d8e5c-2384-4821-9acf-8d32abe88db6.JPG)


<p align = "justify"> Hay las funciones geométricas y matemáticas de por medio que pueden llegar a formar vertices y angulos de trazos circulares, puede reflejar un reloj de arena, un aparato muy preciso en su forma, nos puede dar sensacion de tocar algun tema a como es la teoria de la relatividad , el sonido con sus puntos máximos y mínimos en las ondas producidas o a universos paralelos, se siente como estudios en ciencias exactas por su precision y semejanza </p>



### Pieza 2: Cardioide espacial 

![segunda](https://user-images.githubusercontent.com/94578395/153294327-6d9641a2-7190-493e-ba91-d834ebd1fd32.JPG)


<p align = "justify"> Puede ser alguna especie de escamas, un pez, la piel o el ojo de reptil por su forma y color, las ondas o mostañas circulares se van espandiendo hacial el centro, se ve armonioso por que formas semi circulares crean un circulo. En el centro, tambien se puede observar una especie de cardioide rotado hacia la derecha.</p>


### Pieza 3: Alas de mar 
![3](https://user-images.githubusercontent.com/94578395/153294349-0a9a4cdb-2d11-405e-9083-65fc417eb92e.JPG)


<p align = "justify"> El sentido de la escucha por que parecen orejas, parlantes, el reflejo de un instrumento de viento, música tranquila, tal vez alas, auroras boreales reflejadas en el fondo de un oceano, una bailarina con un delicado vestido, un murcielago en vuelo, muchas formas se pueden percibir de esta imagen pero hay una cosa en comun y es que va lento y con suavidad. </p>



### Pieza 4: Ojo astral 
![4](https://user-images.githubusercontent.com/94578395/153294363-11b5f98a-4cab-41ce-9d6a-9a380f4b30ce.JPG)


<p align = "justify"> Es caótico, se siente como el fin del mundo, parece un viaje en el tiempo, aunque frente a una mente menos dramática se podria descibir como un disco de vinilo o un universo donde alguna estrella que es centro de órbita, es la representacion del inicio o el fin. </p>


### Pieza 5: Agujero negro sobre superficie 
![5](https://user-images.githubusercontent.com/94578395/153294381-ed206f61-28b3-4e62-9709-feb59e50264c.JPG)


<p align = "justify"> Gráficos paralelos y semejantes, se pueden percibir olas de mar, aunque tambien pueden ser olas sobre la arena creadas por el viento en medio del desierto, una barrera entre dos mundos , un agujero que absorbe, una grieta hueca y sin fondo, transmite un pensamiento de curiosidad, ¿que habrá más alla? por que refleja algo infinito en una imagen con trazos finitos. </p>


### Pieza 6: Sombra en la oscuridad
![6](https://user-images.githubusercontent.com/94578395/153294406-89524043-13c9-49bf-bbbf-9e612128041f.JPG)


<p align = "justify"> si con esta imagen se pudiera decribir la personalidad de alguien, se describiría como rígido, estricto, alguien con el ego muy alto,una persona selectiva y directa, veo desaprobacion porque si le vemos otra cara se puede asemejar una letra "equis", algún pañuelo de seda o hasta puede reflejar sensillez en sus trazos y curvaturas</p>



### Pieza 7: El choque
![7](https://user-images.githubusercontent.com/94578395/153294439-95fd3459-239a-4aa0-b30c-3f9fd9086cbc.JPG)


<p align = "justify"> se siente que choca, sea tinta, un  brazo con los dedos empuñados, el impacto de una bala , refleja algún tipo de tragedia, es una obra que se percibe inmediata, algo que ocurre en un lapso muy pequeño de tiempo</p>


### Pieza 8: Tranquilidad floral
![8](https://user-images.githubusercontent.com/94578395/153294465-12a6edbf-80e0-42c5-a415-69253fcec031.JPG)



<p align = "justify"> Se pueden ver petalos de flores o mariposas, alguna especie de criatura fantástica haciendo una danza que refleja tranquilidad y libertad por su forma abierta; los trazos se sienten suaves, parece hecha por algun tipo de maquina por su precision y delicadeza</p>




### Pieza 9: Montes azules
![9](https://user-images.githubusercontent.com/94578395/153294501-3f555f29-4f27-4138-9f15-85eff41a40bb.JPG)


<p align = "justify"> Se puede ver de dos formas, en primera intancia se puede observar segun las curvaturas, dadas por funciones matetamticas, como si cayera, talvez como si algo se recuperara y volviera a tener estabilidad, quiza se asemeja a los signos vitales de una persona o alguna cascada que cae a un océano. </p>



### Pieza 10: Espiral gris
![10](https://user-images.githubusercontent.com/94578395/153294527-7b68f3f2-8c6b-4c71-bc57-3922a3c00a5b.JPG)


<p align = "justify"> Hay varias persepciones, se puede describir como un ojo, pez, caracol, un espiral de hojas, hay una cosa en lo que se puede tener concordancia y es que se siente infinito, la espiral da la sensación de movimiento y parece ser algun animal acuatico por fluido y por sus trazos tranquilos. </p>


















































## Referencias
  - James, G., Witten, D., Hastie, T., & Tibshirani, R. (2013). *An introduction to statistical learning (Vol. 112, p. 18). New York: springer.*
  - Stack Overflow - Where Developers Learn, Share, & Build Careers. (n.d.). Retrieved January 17, 2022, de: [Stackoverflow](https://stackoverflow.com/)
  - Hacia la ciencia de datos. (n.d.). Retrieved January 17, 2022, de: [Towards Data Science](https://towardsdatascience.com/)
  - FrikisparaGeeks | Un portal de informática para geeks. (n.d.). Retrieved January 17, 2022, de: [Geeks for geeks](https://www.geeksforgeeks.org/)
  - Red Generativa Antagónica (GAN) | IDIS. (n.d.). Retrieved February 9, 2022, from https://proyectoidis.org/red-generativa-antagonica-gan/
  - ARTE GENERATIVO 101: LA CONEXIÓN SORPRENDENTE ENTRE MATEMÁTICAS, ARTE Y NATURALEZA. (n.d.). Retrieved February 9, 2022, from https://pankow.us/generative_faq_es/
  

