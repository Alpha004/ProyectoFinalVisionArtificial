# VisionArtificial

## Acerca del Proyecto Final

El presente proyecto final es del curso de Vision Artificial en grupo donde los integrantes somos:

* Ing. Alpaca Rendon, Jesus A.
* Ing. del Carpio Maraza, Heberth E.
* Ing. Vargas Franco, Mauricio S.

El proyecto busca la implementacion de la solucion indicada en el paper "FV-ViT: Vision Transformer for
Finger Vein Recognition", utilizando otro dataset similar

## Descripcion

El proyecto consta de 2 codigos en Python utilizando diferentes librerias como TensorFlow, Keras, Numpy, etc, el cual lee las imagenes del dataset y se entrena el modelo utilizando ViT, la idea es poder identificar de cierta forma a una persona mediante imagenes de las venas en sus manos, de la cual varios estudios concuerdan que hay diferencias que permitirian de cierta forma identificar como una huella digital o ADN a las personas.

## Requerimientos del Sistema

Como requerimientos del sistema, principalmente la memoria RAM de 32 gbs y de mejor procesamiento una tarjeta de video NVIDIA.

1. Analisis de dedo x dedo

* Tensorflow2.15
* Python 3.10

2. Analisis de mano x mano

* Tensorflow2.10
* Python 3.7

El ambiente de ejecucion fue de Colab con GPU, por lo que los requerimientos de hardware mencionados anteriormente ya estaban cubiertos

## Intrucciones

### EJECUCION


1. Ingresamos a Colab y abrimos los archivos.
2. Ejecutamos en orden.
3. En caso se este usando de forma local, se tiene que instalar Cuda, TensorFlow, Keras, donde tenemos que analizar las versiones de cada uno.
4. La parte de entrenamiento dependera si se usa o no gpu, en caso si, sera mas rapido el entrenamiento, caso contrario podria demorar hasta hora y media.
5. Una vez hecho el entrenamiento podemos saber el accuracy y otros medidores que nos ayuden a validar que si se entreno de forma correcta el modelo
6. Para la parte de identificacion con las manos, veremos que obtendremos un array con valores proximos y mas cercanos a la posible persona a la que pertenecen, siendo valores normalizados entre 0 y 1.
