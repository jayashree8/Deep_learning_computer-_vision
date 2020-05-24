# This repository contains deep learning models worked on unique datasets:

#### The concept of ImageGenerator is used where we do not explicitly label the images but the ImageGenerator will read the images from the subdirectories and automatically label them from the name of that subdirectory. 

## Dog breed classifier
The notebook classifies the the dog breeds 'husky' and 'poodle' using CNN(convolutional neural network). 
Thus it is a binary classfier. Data augmentation was applied to prevent overfitiing and automatic labelling was done using ImageGenerator.

The final outcome is as follows:

![](images/dog.png)

![](images/dog1.png)

See notebook [here](https://github.com/jayashree8/Deep_learning_computer_vision/blob/master/Husky%20and%20poodle%20dog%20breed%20classifier/husky_vs_poodle.ipynb)

# Flower multi class classifier

This is a multi class image classifier which classifier the 3 flower types rose, lotus and sunflower. The keras pre-trained model InceptionV3 will be used which is trained on ImageNet using CNN.

The final outcome is as follows:

![Results](images/flower.png)

See notebook [here](https://github.com/jayashree8/Deep_learning_computer_vision/blob/master/Flower%20multi%20class%20classifier/Flower%20classifier.ipynb)
