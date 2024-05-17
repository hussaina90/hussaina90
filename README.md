 # Training Exercises 

## _Done By_ 
_Hussain Alsamhan_     221432883


_Adam Almomtan_        221423651


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


## Data explorer 

![ES Project - Classifier - Edge Impulse - Google Chrome 5_17_2024 3_54_58 PM](https://github.com/hussaina90/ii/assets/170102178/86a53c85-d0f6-4ff1-a00b-9542fb7b5780)

Green points represent correctly classified samples for each category:

Light green for "Biceps"

Medium green for "Shoulder"

Dark green for "Triceps"
Red points indicate incorrectly classified samples:

Light red for "Biceps"

Medium red for "Shoulder"

Dark red for "Triceps"

The plot is useful for identifying patterns in how data is being misclassified, which can help in refining the model or choosing more suitable features for classification. It also provides a visual measure of the model's performance on the full training set. The overlap of red and green points indicates areas where the classifier may struggle or where the features may not be distinct enough for accurate classification.
Additional metrics provided below the plot, such as the inference time (3 ms), peak RAM usage (1.8K), and flash usage (23.0K), are technical specifications important for deploying the model on a device, considering performance and resource constraints. The use of the EON™ Compiler suggests that the model is being optimized for efficient on-device performance


## DSP result

![ES Project - Classifier - Edge Impulse - Google Chrome 5_17_2024 3_57_18 PM](https://github.com/hussaina90/mm/assets/170102178/fe226653-71d7-4076-b9a0-7e73f15d2318)

DSP Result - After Filter:

This plot shows how a signal has been transformed after applying a certain filter. Three traces (probably representing different channels or features of the signal) are plotted over a series of samples.
The x-axis represents sample numbers, indicating the sequence of data points.
The y-axis represents values of the filtered signal, which could be any measure such as voltage, power, etc.
This plot helps in understanding the behavior of the signal post-filtering, particularly how it changes over time or in response to processing.

Spectral Power (log):

This plot displays the spectral power of the signal on a logarithmic scale, which helps in analyzing the power distribution across different frequency components.
The x-axis represents frequency in Hertz (Hz), showing the spectrum of frequencies analyzed.
The y-axis represents the logarithmic scale of energy, highlighting the power at each frequency.
This type of plot is useful for identifying dominant frequencies in the signal and understanding how energy is distributed across the spectrum.
Together, these plots are used in signal processing to analyze the characteristics of signals in both time and frequency domains. They are essential for applications like audio processing, telecommunications, and other fields where understanding signal behavior is crucial.


## Conclusion 

This project showcased the potential of using edge machine learning to enhance personal training by providing immediate feedback during exercises. Using the Arduino Nano 33 BLE, we processed exercise data in real time, which improved the training experience by making feedback timely and relevant.
Our analysis with Edge Impulse revealed some areas for improvement in data classification, but overall, the model was effective in identifying correct and incorrect exercise forms. Moving forward, we'll aim to refine the accuracy of the model and broaden its exercise detection capabilities to better support users in achieving their fitness goals
