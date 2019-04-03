
# RECONOCIMIENTO DE CARACTERES Y REPRODUCCION DE VOZ

<b>INTEGRANTES:</b><br>     VERÓNICA LUCENA (2152903)  
                            KARINA SEQUEDA (2152476)  
                            BRAYAN ÁLVAREZ (2151257)<br>
                            ÁNGEL GÓMEZ    (2130535)

 <b>DESCRIPCIÓN GENERAL:</b> El proyecto busca implementar los conocimientos adquiridos en la asignatura, respecto a
machine-learning, para lograr un reconocimiento de caracteres, mediante el ingreso de una
imagen(Fotografía) con texto, haciendo lectura de este a través de un reproductor de voz.

 <b>DIRECCIÓN DEL DATASET:</b> https://www.westernsydney.edu.au/bens/home/reproducible_research/emnist

 <b>METODOLOGÍA Y DESCRIPCIÓN DE DATOS CAPTURADOS:</b> En el proyecto se emplearán dos bases de datos, la primera es una base de datos llamada EMNIST que contiene un conjunto de etiquetas e imágenes de tamaño 28x28 pixeles. La segunda es una base de datos propia, creada con la colaboración de un grupo de estudiantes de ingeniería de Sistemas, a quienes se les pidió escribir el alfabeto (excluyendo la ñ) en mayúscula y minúscula. Se dará uso a la agrupación de letras con sus respectivas etiquetas e imágenes, empleando 62400 imágenes para el entrenamiento, 20800 imágenes para la prueba, dando un total de 83200 imágenes con sus respectivas etiquetas, siendo estos los valores correspondientes a la primera base de datos. La segunda base de datos cuenta con 884 imágenes y 884 etiquetas.
 
El proyecto se desarrolla en cuatro fases, cada una con sus respectivos gráficos, de manera que se pueda analizar el comportamiento obtenido en los clasificadores (DT,RF,GNB,SVM). En la primera fase se emplearán las imágenes de EMNIST para entrenar y evaluar el modelo.  En la segunda fase se empleará EMNIST para entrenamiento y la base de datos propia para test. En la tercera fase se combinarán las dos bases de datos tanto para entrenamiento como para test. En la cuarta fase se empleará la base de datos propia para entrenar y evaluar el modelo. 

Para profundizar un poco en la base de datos, consultar el siguiente pdf: https://arxiv.org/pdf/1702.05373.pdf

