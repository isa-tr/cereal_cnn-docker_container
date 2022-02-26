Bienvenido al Contenedor Docker 'cereal_cnn'

Explicación de los archivos incluídos en el contenedor:

* /notebooks
	*DataAnalysis.ipynb --> consiste en el análisis y visualización del dataset con el que se va a entrenar posteriormente
la red neuronal

	*DataAug_&_Preprocessing.ipynb --> contiene los pasos seguidos para realizar Data Augmentation y el preprocesamiento
de las imágenes

	*CNN_Cereal_Classification.ipynb --> contiene los resultados obtenidos después del entrenamiento de 4 modelos de redes
neuronales convolucionales basados en la arquitectura de AlexNet
	
--Nota-- Estos notebooks son solo para visualización ya que la base de datos no está almacenada en el contenedor Docker
por razones de tamaño del archivo

	*Predict_Cereal.ipynb --> notebook para probar el modelo de red neuronal escogido que obtuvo el mejor valor de accuracy 
con los datos de prueba

* /sample_images
Contiene 8 imágenes de prueba, 2 de cada clase para probar la red neuronal con el notebook Predict_Cereal.ipynb

* requirements.txt
Librerías y dependencias necesarias para el funcionamiento de la aplicación

* model4_95_64.h5
Archivo binario que contiene los pesos entrenados de la red neuronal
