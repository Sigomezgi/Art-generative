# Art-generative
Se presenta a continuación el desarrollo para la generación de las imágenes. 
Al final se realiza una apreciación  artística de las imágenes generadas por parte del equipo.

# Generación de imágenes
Para la generación de imágenes se tuvieron en cuenta tres aspectos: Funciones hiperbólicas, distribuciones de probabilidad normal y modelos estadísticos.

# Pasos

- Se generaron una malla de puntos de dos variables a partir de una distribución de probabilidad normal.
- Estos puntos fueron evaluados en una función hiperbólica compuesta. Z
- A partir de estos datos se creados y de la función se evalua los varios modelos que se aproximen a la variable respuesta, en este caso, el valor de la función.
- Se crea unos de los modelos probados, sin embargo la elección de este no se baso en su aproximación al target sino que se probo con un modelo de libre elección. La idea de la creación de este modelo es agregar arte estadística a las imágenes creadas por medio de perturbaciones de las funciones.
- El procedimiento anterior se realiza en dos ocasiones para generar dos modelos con arte estadística.
- Los modelos creados fueron: Regresión Lasso y Elastic Net, respectivamente.
- Luego de creado los modelos, se crea una malla con una distribución normal para ser evaluadas en el modelo creado.
- A partir de la librería, Samila, se crean 10 imágenes cada una con un par de funciones trigonométricas hiperbólicas modificada por ambos modelos.
