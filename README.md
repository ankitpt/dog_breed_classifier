# Dog Breed Classifier

### Table of Contents

1. [Project Motivation](#motivation)
2. [File Descriptions](#filedescriptions)
2. [Results](#results)
4. [Licensing, Authors, and Acknowledgements](#licensing)

## Project Motivation<a name="motivation"></a>
This is my Capstone Project submission for Udacity Nanodegree. A dog breed image data was made available with 8352 images spread across 133 categories and the goal was to train a classifier for identifying breed of a dog in a given image. 

Following tasks were performed for the project:

- Create and train a CNN from scratch for dog breed classification 
- Use bottleneck features from pre-trained VGG model as input and train a fully connected network
- Use bottleneck features from pre-trained Resnet50 model as input and train a fully-connected network
- Use the network trained with Resnet50 features for testing on new images (not part of original dataset)


## Folder Descriptions <a name="filedescriptions"></a>
*images* folder consists of images for testing on trained models

*haarcascades* folder consists of pre-trained face detector based on haar feature

*requirements* folder consists of .yml and .txt files enlisting package requirements on different operating systems for running the jupyter notebook

*saved_models* folder consists of transfer learning models trained based on bottleneck features from VGG16 and Resnet50

## Results<a name="results"></a>
The main findings of this work can be found on my [Medium blog](https://ankit-patel03.medium.com/who-let-the-dogs-breed-out-who-who-convolutional-neural-network-a2815c586641)

## Licensing, Authors, Acknowledgements<a name="licensing"></a>
I would also like to acknowledge Udacity Data Scientist Nanodegree instructors for creating and teaching the Data Scientist Nanodegree program and thus providing a holistic overview of data science.  