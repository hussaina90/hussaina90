 # Training Exercises 

## _Done By_ 
_Hussain Alsamhan_


_Adam Almomtan_


## Introduction

In the rapidly evolving field of machine learning, the emergence of edge computing presents a transformative approach to data processing and model deployment. Edge ML leverages the computational power of local devices, enabling real-time, efficient, and autonomous decision-making without the latency and bandwidth constraints associated with cloud computing. This paradigm shift is particularly impactful in the domain of physical training and exercise, where immediate feedback and personalized training regimens can significantly enhance performance and user engagement.
This project explores the application of edge ML in developing a system that provides real-time feedback and guidance during training exercises. By processing data directly on edge devices such as smartphones and wearable technology, the system aims to deliver personalized exercise routines and corrective feedback instantly, thereby optimizing the training effectiveness and improving user adherence to physical fitness goals. 
 

## Objective

The primary goal of this project is to enhance the experience and effectiveness of personal training through the application of edge machine learning technologies. Specifically, the project aims to achieve the following objectives:
Develop an Edge-Optimized ML Model: Design and train a machine learning model that is optimized for performance on edge devices with limited computational capabilities. The model should be capable of processing real-time data from users during exercises to provide immediate feedback.
Implement Real-Time Data Processing: Utilize sensors and other data-capturing technologies to gather exercise-related data from users. This data will be processed directly on the user’s device, minimizing latency and ensuring that feedback is both timely and relevant.


## Material

Arduino nano 33 ble

Edge Impulse 


## Steps Involved

1- create account in Edge impulse 

2- Connect the Arduino nano 33 ble with Edge impulse 

 3-Make a new project in Edge impulse 

 4- Start to collect Data: Find a person to make exercises for biceps ,triceps and sholder 

 5- Analysis the data for each exercise 

 6-Classification: Edge Impulse is used to classify the Perfect Trining  data  into bad trinin

 7-Training: The data is trained to improve the accuracy of trining classification


## Feature explorer 

![ES Project - Classifier - Edge Impulse - Google Chrome 5_17_2024 3_57_30 PM](https://github.com/hussaina90/image-/assets/170102178/9eabc221-099c-45c0-b6d5-953569ab2a9a)

Blue points represent data samples tagged as "Biceps".
Orange points represent data samples tagged as "Shoulder".
Green points represent data samples tagged as "Triceps".
The plot helps in visualizing how well-separated these categories are, which is crucial for tasks like classification in machine learning. If the colors (categories) are well-separated, it indicates that the features used are effective in distinguishing between these different categories. If they overlap significantly, it might suggest that the current features are not sufficient for reliable classification and might require further refinement or the addition of other distinguishing features.
