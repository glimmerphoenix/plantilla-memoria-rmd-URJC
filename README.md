# Plantilla para memoria de proyecto URJC

Este proyecto de RStudio proporciona una plantilla para crear una memoria de TFG o TFM de la URJC, usando [R Makdown](https://rmarkdown.rstudio.com/) y [LaTeX](https://es.wikipedia.org/wiki/LaTeX). La misma plantilla puede ser fácilmente adaptada para la redacción y publicación de una tesis doctoral en URJC.

La base es una [plantilla para proyectos URJC con XeLaTeX](https://github.com/glimmerphoenix/plantilla-memoria-TFG-TFM) publicada en GitHub, así como en un repositorio del GitLab de la [OfiLibre URJC](https://ofilibre.gitlab.io/).

La principal ventaja que ofrece esta versión es que te permite trabajar directamente en R/RStudio para realizar, simultáneamente, la parte técnica de tu proyecto y la redacción de la memoria. Con eso se ahorra mucho tiempo y se evita duplicar esfuerzos (por ejemplo, guardando gráficas o resultados para incorporarlos al documento de la memoria, formatearlos, etc.). Mediante esta plantilla, todo el proceso queda automatizado a través de las funciones de R Markdown y el [paquete bookdown](https://pkgs.rstudio.com/bookdown/), entre otros. Esto también es posible gracias a [Pandoc](https://pandoc.org/), el conversor universal de documentos, que se encarga de todo el trabajo pesado de traducción del contenido Markdown a PDF.

Por favor, utiliza el sistema de seguimiento de errores del proyecto (*Issues* en el menú superior de esta página de proyecto), si quieres reportar algún error que hayas podido encontrar o solicitar nuevas funciones.
