# Text Mining & Image Recognition
## Proyecto Final
### Darwin Josue Rojas Echeverría | 23008435

# Problema 1 
*(descarga el Train y el Test desde el archivo Train_Set_Test_Set.txt)*

Determine los 3 usuarios más populares dentro del dataset. Luego arme un corpus el cual contenga los siguientes elementos por cada usuario seleccionado:

Content: Tweet.
Metadata: ID, Timestamp, Length (este valor hay que calcularlo).

Posterior a tener sus 3 corpus creados, responda: A: ¿Razón por la que citan a ese usuario? para esto es necesario que extraiga el contexto de cada tweet y verifique cuales son las palabras que más rodean al nombre de usuario. Para extraer un contexto valido y debido a la naturaleza del tipo de datos que están disponibles en nuestro dataset le recomendamos seguir los siguientes pasos:

1. Remover stopwords.
2. Realizar stemming y lemmatización.
3. Mostrar un wordcloud con el top 10 para cada usuario.

# Problema 2 
*(descarga el dataset de el archivo Tweet Source.txt*

Desarrollar un modelo de clasificaci´on de im´agenes basado en redes neuronales convolucionales (CNNs) capaz de distinguir entre diferentes tipos de frutas y verduras, utilizando un conjunto de datos inicial centrado en im´agenes. El modelo deber´a ser robusto ante variaciones en tamaño, rotación y condiciones de iluminación de las imágenes.

## Parte 1
Deberá descargar el dataset de frutas disponible en este link de (Kaggle). Luego deber´a seleccionar al menos tres frutas y tres vegetales para desarrollar su proyecto.

* **Data Augmentation y Preprocesamiento:** Aplicar técnicas de aumento de datos para generar nuevas imágenes a partir de las existentes (rotación, escalado, flip horizontal, ruido entre otras.) adicionalmente debería considerar si resolverá el problema utilizando escala de grises o imágenes a color. Por ultimo deberá redimensionar las imágenes a un tamanño estándar para la entrada de la red neuronal convolucional así como normalizar los valores a valores entre 0 y 1, todo esto es posible realizarlo por medio de la función ImageDataGenerator y la función flow from directory de Keras

## Parte 2

* **Arquitectura:** Deberá considerar el número de capas convolucionales y de pooling, tipo de pooling, el tamaño de los filtros (kernels), la función de activación y el número de clases a clasificar, el numero de capas y neuronas artificiales, los parámetros de optimización y entrenamiento y demás parámetros para implementar su CNN. Deberá probar al menos 3 arquietcutas distintas para resolver el problema y validar cual de las 3 funciona mejor. y deberá contestar la pregunta Por qué cree que la CNN que seleccionó funciona mejor que otras?

* **Entrenamiento:** Deberá dividir el conjunto de datos en conjuntos de entrenamiento, validación y prueba para determinar la eficiencia de su algoritmo.

