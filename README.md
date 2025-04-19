## Group E 
Marlis Tiefengraber, Clemens Herzig, Lorenz Duelli;

## Overview
The project involves building and evaluating an image classification model using ResNet50. 
It starts with dataset exploration and a train-test split. Models are trained from scratch and with transfer learning, comparing their performance over the first 10 epochs. 
Data augmentation techniques (zoom, crop, translation) are tested to improve results. The ResNet50 architecture is modified with additional layers, and earlier layers are frozen. 
Custom images are used to test the performance.

## Models
Since the models are quite large, we have not included them in the repository. Instead, you can download them from the following links:
https://drive.google.com/file/d/15FcmGEzxUPMNvL5hG9K_Cc-3r2xG9DIu/view?usp=drive_link

## Requirements
You can install the necessary dependencies using the following command:

```bash
pip install -r requirements.txt
```

Sources: 

https://www.tensorflow.org/guide/keras/transfer_learning

https://www.tensorflow.org/guide/keras/sequential_model

https://www.tensorflow.org/tutorials/images/data_augmentation#use_keras_preprocessing_layers

https://github.com/wannasleepforlong/ResNet-50-Implementation-for-Image-Classification/blob/main/image-classification-by-resnet-50.ipynb
