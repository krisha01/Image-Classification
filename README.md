# Image-Classification

# Flower Species Image Classification
The primary purpose of this notebook is to perform Image classification from a public dataset called Flower Recognition dataset that has more than 4000 images of flowers of 5 different categories - Daisies, Dandelions, roses, sunflowers and tulips. To perform our image classification we use a Convolutional Neural network after preprocessing the image data to generate accurate results. The dataset contains 4242 images of flowers. The data collection is based on the data flicr, google images, yandex images. The pictures are divided into five classes: daisy, tulip, rose, sunflower, dandelion. For each class there are about 800 photos. Photos are not high resolution, about 320x240 pixels. Photos are not reduced to a single size, they have different proportions!
The baseline CNN model gave us the accuracy of 78.727%, after preprocessing the images and reshaping and resizing them we got better results. The only other model that shows the potential of doing better than our baseline model with some tweaking looks to be the model that uses the Sparse cross entropy loss function that gave us an accuracy score of 87% and loss of 0.3 after just 10 epochs. With more epochs and more tweaking, the model can perform better than our baseline model does. It can also be thought of as the substitute model for this particular problem. The other models with different network architectures, loss functions, cost functions, activation functions etc overfitted the data while the accuracy didn't increase. When working with neural networks and especially cnn, there are n amount of possibilities to make our model and evaluate its performance. In this notebook, I have demonstrated few of them.

To run the project and load the dataset, follow the below instructions -

•	Download the dataset from - https://www.kaggle.com/alxmamaev/flowers-recognition

•	Keep all the files provided and the downloaded dataset in either the current working directory, or change the working directory to any path you like in the Jupyter Notebook.

•	Open ‘Assignment-3-Deep_Learning’ and run it.

•	You will find all the steps from importing the libraries, image  preprocessing, network architecture etc for the classification there 
