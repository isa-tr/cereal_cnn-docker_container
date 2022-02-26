# CNN for cereal classification containerized in Docker

Click this link to download Docker Container 'cereal_cnn': https://hub.docker.com/r/itr8399/cereal_cnn

Explanation of the files included in the container:

* **/notebooks:**
	* DataAnalysis.ipynb --> consists of the analysis and visualization of the dataset with which the neural network will be trained.
the neural network

	* DataAug_&_Preprocessing.ipynb --> contains the steps followed to perform Data Augmentation and preprocessing of the images.
of the images

	* CNN_Cereal_Classification.ipynb --> contains the results obtained after the training of 4 convolutional neural network models based on the
convolutional neural network models based on the AlexNet architecture.
	
	**--Note-- These notebooks are for visualization only as the database is not stored in the Docker container
for file size reasons**

	* Predict_Cereal.ipynb --> notebook to test the chosen neural network model that obtained the best accuracy value 
with the test data

* **/sample_images -->**
Contains 8 test images, 2 of each class to test the neural network with the Predict_Cereal.ipynb notebook.

* **requirements.txt -->**
Libraries and dependencies required for the application to work.

* **model4_95_64.h5 -->**
Binary file containing the trained weights of the neural network.

# Instructions to download Docker container

The instructions for running the Docker image are as follows:

1. Open the link https://hub.docker.com/r/itr8399/cereal_cnn
2. docker pull itr8399/cereal_cnn
3. docker run -p 8888:8888 itr8399/cereal_cnn
4. copy the link that appears in the console and paste it in the browser to open jupyter notebook, there you will find all the respective files.

IMPORTANT: Read the README to make it easier.
