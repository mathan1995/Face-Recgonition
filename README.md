# Facenet: Real-time face recognition using deep learning Tensorflow 
####@Author Mathangan Jeyakantharajah
This is completly based on deep learning nueral network and implented using Tensorflow framework. Here you will get how to implement fastly and you can find code at github and uses is demonstrated at YouTube.

## Installation Python Libraries:

- Tensorflow (1.4.0)
- Scipy (0.17.0)
- Scikit-learn (0.19.1)
- Opencv (2.4.9.1)

## IDE and Environment setting 

-usage anaconda navigator for setup the environment
-use spyder 3.06 and python 3.5 for the development environment

##Usage 

This readme File contains following key points:

Introduction of Facenet Implementation
Data collection
Data Pre-process.
Training of Model. 5. Real-time prediction test.

##Introduction of Facenet and implementation base: 
Well, implementation of FaceNet is published in Arxiv (FaceNet: A Unified Embedding for Face Recognition and Clustering). It contains the idea of two paper named as “A Discriminative Feature Learning Approach for Deep Face Recognition” and “Deep Face Recognition”.

##Data collection and pre-processing: 
In this part, we will prepare our code and data. We will start code from basic step i.e collection and arrangement of data in a proper format. For preparing online data, download the image from google. If you have your own image data-set of one or more person then arrange all images in the format as shown in below image.

After downloading the image from google image arrange all file and folder in the same directory structure.

##Data Pre-processing: 
Now for preprocessing all the image data-set, you have to run the file named as “preprocess.py” as python file. This file will crop the face of each face and label each face image with the folder name. And generate a text file “bounding_boxes_433.txt” where you see labeling of data.

This type of labeling can be accomplished with image labeling data. All the work will be done by the program automatically you only have to run this file. Python initializer.py

##Training of Model:
 After preprocessing of data we have to train model with a predefined model. Put pb file inside the folder named as “model”. And now run the training file “train_main.py” as python command. It will train model and also pkl file will be saved inside directory “Class”. Python classifier_train.py

##Testing Real-time Prediction:
Finally, this stage is active and you can test it with your own image or video data. For both types of code test, I have provided the code separately on Github. For image test run file “identify_face_image.py” in this file and change your own image at variable “img_path” at line number 15 and run the code. ex. img_path=’test_img/abc.jpg’.

##Applications of Real-time Face Recognition using FaceNet :

Security system
Self Learning
Visitor Analysis System
Face recognition system
Face verification System and many more

##Drawbacks of Face Recognition Using FaceNet: 
There are some major drawback or limitations of this model. It takes 30-40 per person images with good quality of frontal face.

##Our Further Approach:
For rectifying it we are continuously working on it and soon we will update complete process with implementation code.
So for updating this code stay tuned with us. For any type of customized use cases query and problem regarding this code,
you can contact us. We will feel more energetic with your feedback.


