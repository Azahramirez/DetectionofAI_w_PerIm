# DetectionofAI_w_PerIm

Using persistence images to detect topological differences between AI and human writing

---

# Indicaciones

1- p0 representa el preprocesamiento de los datos, donde se genera un arreglo aleatorio para evitar sesgo en las pruebas y se 
mezclan los datasets de IA vs No IA

2- En el notebook de p1 se generan los embeddings con el modelo preentrenado de GloVe


3- En p2 se calculan los diagramas de persistencia de cada vector de las respuestas y posteriormente se exportan las imágenes de persistencia

4- En p3 y p4 se muestra la arquitectura de cada modelo

5- En p5 se pueden hacer pruebas con nuevos textos

6- En p6 se realizan las 10 pruebas aleatorias por n tamaño de muestras para entrenamiento




GloVe preentrenado de 300 dimensiones (GloVe embeddings from SBWC, .vec format):

https://github.com/dccuchile/spanish-word-embeddings?tab=readme-ov-file#glove-embeddings-from-sbwc

Enlace a los datos (carpeta datos que se utiliza en los notebooks):


https://drive.google.com/file/d/1Y2JsjoDaS20TywQ2OcJ0XWOUI29GmGzF/view?usp=sharing
