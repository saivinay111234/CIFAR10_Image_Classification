# CIFAR10_Image_Classification

In this project we are going to look at how we are training a CNN model to classify images of 10 classes. The name of the dataset is CIFAR10. As the name suggest the dataset contains 10 different images in it.
After running the input data, we will observe that the:

Total dataset contains 60000 images. 50000 are Training images and 10000 is for testing the model.
10 class * 6000 images for each class= 60000 images.
(32 * 32 * 3) implies each image is 32*32 pixel matrix with 3 channels each (color resolution) (RGB)._

To build an image classifier we make use of tensorflow‘ s keras API to build our model. In order to build a model, it is recommended to have GPU support, or you may use the Google colab notebooks as well. I am using Google colab. You can use jupyter notebook as well.

Table of contents( Step by step procedure )
1. Importing the libraries
2. Importing CIFAR-10 Data
3. Checking for Null Values
4. Normalize the data
5. One-Hot encoding
6.Building CNN
7.Evaluate the Model
8.Data Augemtation to prevent Overfitting
9.Evalaute The Model after Data Augementation
10. Score Model
11. Confusion Matrix
12. Classification Report
13.Predicted vs Actual Images
14.Checking Wrongly predicted Images
15.Testing a Image
16.Save CNN Models and Weights
