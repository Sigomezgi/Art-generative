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
- El procedimiento anterior se realiza en dos ocasiones para generar dos modelos con arte estadística.
- Los modelos creados fueron: Regresión Lasso y Elastic Net, respectivamente.
- Luego de creado los modelos, se crea una malla con una distribución normal para ser evaluadas en el modelo creado.
- A partir de la librería, Samila, se crean 10 imágenes cada una con un par de funciones trigonométricas hiperbólicas modificada por ambos modelos.



# Bienvenida a la exposición artística.


