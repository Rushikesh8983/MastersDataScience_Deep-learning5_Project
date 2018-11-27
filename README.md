# MastersDataScience_Deep-learning5_Project
Project on Image Classification
Image Classification
In this project, you'll classify images from the 
CIFAR-10 dataset
(https://www
.cs.toronto.edu/~kriz/cifar
.html)
. 
The dataset consists of airplanes, dogs, cats, and other
objects. Y
ou'll preprocess the images, then train a convolutional neural network on all the samples.
The images need to be normalized and the labels need to be one-hot encoded. 
You'll get to apply
what you learned and build a convolutional, max pooling, dropout, and fully connected layers. 
At the
end, you'll get to see your neural network's predictions on the sample images.
Get the Data
Run the following cell to download the 
CIFAR-10 dataset for python
(https://www
.cs.toronto.edu/~kriz/cifar-10-python.tar
.gz)
.
Data
CIFAR-10 
is an established computer-vision dataset used for object recognition. It is a subset of the
80 million tiny images dataset and consists of 60,000 32x32 color images containing one of 10
object classes, with 6000 images per class. It was collected by Alex Krizhevsky
, Vinod Nair
, and
Geoffrey Hinton.
Let's get the data by running the following function
