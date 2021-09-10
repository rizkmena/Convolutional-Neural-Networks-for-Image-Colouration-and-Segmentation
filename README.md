# Convolutional-Neural-Networks-for-Image-Colouration-and-Segmentation

In this project we  focus on the applications of convolutional neural networks in various image processing tasks. First, we train a convolutional neural network for a task known as image colourization. That is, given a greyscale image, we will predict the colour at each pixel. This a difficult problem for many reasons, one of which being that it is ill-posed: for a single greyscale image, there can be multiple, equally valid colourings. 

Second, we perform fine-tuning on a pre-trained semantic segmentation model. Semantic segmentation attempts to cluster the areas of an image which belongs to the same object (label), and treats each pixel as a classification problem. We will fine-tune a pre-trained convolutional neural network (CNN) featuring dilated convolution to segment flowers from the [Oxford17 flower dataset](http://www.robots.ox.ac.uk/~vgg/data/flowers/17/)
