# Factorización de matrices para filtrado colaborativo
Autor: [Jorge Esteban Mendoza Ortiz](mailto:esteban.mendoza@ciencias.unam.mx) - Facultad de Ciencias. UNAM.

El presente proyecto tiene por objetivo mostrar cómo se puede utilizar la técnica de descomposición en valores singulares para implementar un sistema recomendador de filtrado colaborativo. 

La base de datos que utilizamos en este proyecto se llama `ml-latest-small`, y contiene calificaciones de entre 1 y 5 estrellas de una muestra del sitio [MovieLens](http://movielens.org), un servicio recomendador de películas administrado por el grupo _GroupLens_, un laboratorio de investigación de la Universidad de Minnesota. La base de datos contiene 100,836 calificaciones de 9,742 películas. Los datos fueron creados por 610 usuarios entre el 29 de marzo de 1996 y el 24 de septiembre de 2018.

## Reporte del proyecto

El reporte del proyecto puede encontrarse en [este documento PDF](https://github.com/esteban-mendoza/svd-recommender/blob/master/svd-recommender-report.pdf).

## Código interactivo

Para una versión interactiva del código refiérase a esta [_notebook_ en Google Colab](https://colab.research.google.com/github/esteban-mendoza/svd-recommender/blob/master/svd-recommender.ipynb).

## Versiones de software utilizadas

Python 3.9.6, con las siguientes:

| Dependencias         |
|----------------------|
| numpy==1.21.1        |
| pandas==1.3.1        |
| matplotlib==3.4.3    |
| scipy==1.7.1         |
| scikit-learn==0.24.2 |
| jupyter==1.0.0       |
