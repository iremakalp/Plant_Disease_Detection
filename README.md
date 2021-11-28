# Plant_Disease_Detection
#### *This repo contains the python codes of my final thesis "Analysis of leaf species and detection of diseases using image processing and machine learning methods".*
### Dataset
In this project used PlantVillage dataset.This dataset is recreated using offline augmentation from the original dataset. The original dataset can be found on [this github repo](https://github.com/spMohanty/PlantVillage-Dataset/tree/master/raw). This dataset consists of about 76K rgb images of healthy and diseased crop leaves which is categorized into 33 different classes.

### ImageDataGenerator
Data augmentation is used to increase the size of training set and to get more different image. Through Data augmentation we can prevent overfitting ,this refers to randomly changing the images in ways that shouldn’t impact their interpretation, such as horizontal flipping, zooming, and rotating
### Model
The model was trained using one of the machine learning methods CNN. Training was performed using  **VGG16, VGG19, AlexNet, InceptionV3 and ResNet50**. According to the results, the best model was selected.
#### CNN
A Convolutional Neural Network (ConvNet/CNN) is a Deep Learning algorithm which can take in an input image, assign importance (learnable weights and biases) to various aspects/objects in the image and be able to differentiate one from the other. The pre-processing required in a ConvNet is much lower as compared to other classification algorithms. While in primitive methods filters are hand-engineered, with enough training, ConvNets have the ability to learn these filters/characteristics.
