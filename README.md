# Dog-Breed-Classifier-DeepLearning

### Project Overview

This project uses Convolutional Neural Networks (CNNs) and transfer learning in order to build a pipeline to process real-world, user-supplied images. Convolutional Neural Networks (CNNs) are commonly used to analyse image data. Transfer learning is a technique that allows to reuse a model across different tasks. The objective is that given an image of a dog, the algorithm will identify an estimate of the canine’s breed. If supplied an image of a human, the code will identify the resembling dog breed. If the algorithm can't identify the image as a human or dog, it will say so.

### Table of Contents

1. [Libraries](#libraries)
2. [File Descriptions](#files)
3. [Content](#contents)
4. [Findings](#findings)
5. [Blog_post](https://medium.com/how-austin-airbnb-hosts-can-earn-extra-from-public/dog-breed-classifier-deep-learning-85282fc8639d)
6. [Acknowledgements](#Acknowledgements)

### Libraries <a name="libraries"></a>

    Keras
    OpenCV
    Matplotlib
    Numpy
    TensorFlow

### File descriptions <a name="files"></a>

* dog_app.ipynb: Jupyter notebook containing the algorithm and process used to create it.
* dog_app.html: A copy of dog_app.ipynb in html format.
* Haarcascades folder: Xml file for use with the OpenCv face detector class.
* Various images: Images in jpg and jpeg format used to test the algorithm's predictions.
* run_keras_server: To start the Keras model as rest API
* simple_request.py: To submit requests to Keras server


### Contents <a name="contents"></a>

The project is organized along the following steps:

    Intro
    Step 0: Import Datasets
    Step 1: Detect Humans
    Step 2: Detect Dog
    Step 3: Create a CNN to Classify Dog Breeds (from Scratch)
    Step 4: Create a CNN to Classify Dog Breeds (using Transfer Learning)
    Step 5: Write Your Algorithm
    Step 6: Test Your Algorithm

### Conclusion <a name="findings"></a>

* The blog post discusses the walkthrough and outcome of each step in the project are in [here](https://medium.com/how-austin-airbnb-hosts-can-earn-extra-from-public/dog-breed-classifier-deep-learning-85282fc8639d)
* The model achieved a test accuracy of 81.22%, which is above the 60% established accuracy threshold.
* Based on the data being tested in this project, the algorithm has > 90% accuracy score when it comes to detect human faces. 
* The model predicted the same two or three breeds when identifying an image as human. Therefore more variety is needed concerning the type of breeds the model predicts for humans. 
* Some of the breeds have similar colors and shapes but differ in size, as is the case between a Beagle and a Pointer or American Foxhound. Therefore the model needs to pick up subtle differences between similar breeds. 
* The model could use some improvements on its ability to classify pictures with noise. This is probably due to the images it was trained on.


### Acknowledgements <a name = "Acknowledgements"> </a>

The bulk of this project has been taken from the lessons on the Udacity's Data Science Nanodegree program. I would like to thank the amazing professors and mentors working with Udacity to help me deliver the successful outcome for this capstone project. 


