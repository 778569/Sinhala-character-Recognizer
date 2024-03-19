# Sinhala-character-Recognizer
An interactive Sinhala character recognizer implemented using K-Nearest Neighbors (KNN) algorithm with a user-friendly Tkinter-based graphical user interface. Browse and classify Sinhala characters effortlessly. Check out the code on GitHub!

## Data and Target
in here we have images and if we draw a sinhala letter, model should predict it.<br>

![image](https://github.com/778569/Sinhala-character-Recognizer/assets/52319671/6ab1cf81-c038-4f88-9e15-fa5b9e5caf1f)

## Image Filtering

In here we are devide that images into pixels.<br>

![image](https://github.com/778569/Sinhala-character-Recognizer/assets/52319671/5de3da98-e92f-4509-b172-1c5fedb5af98)

## Split data 

in here I am split 20% data as a test and 80 for train.

![image](https://github.com/778569/Sinhala-character-Recognizer/assets/52319671/4b35f05f-fa39-4a03-90bb-7becad48c52a)

## Train the KNN Algorithm

![image](https://github.com/778569/Sinhala-character-Recognizer/assets/52319671/3cb24a93-cdd3-4803-b3bb-210b200c6359)

## Evaluating the Algorithm

![image](https://github.com/778569/Sinhala-character-Recognizer/assets/52319671/45349352-d590-4587-b0dd-c9db2993b367)

## Read Time Predictions

![image](https://github.com/778569/Sinhala-character-Recognizer/assets/52319671/da1d1bd8-3bd1-4f79-ab17-1a4399418955)

## K Nearest Neighbor Algorithm (Classifier)

* K Nearest Neighbor(KNN) is very simple, easy to understand, versatile and one of topmost machine recognition algorithms.
* KNN used in the variety of applications such as finance, healthcare, political science, handwriting detection, image recognition and video recognition.
* In credit ratings, financial institutes will predict the credit rating of customers.
* In loan desbursement, banking institutes will predict whether the lone is safe or risky, in political science, classifying potential voters in two classes will vote or wont vote
* KNN algorithm used for both classification and regression problems.KNN algorithm based on feature similarity approach.

## Training


![image](https://github.com/778569/Sinhala-character-Recognizer/assets/52319671/15543c02-523f-4642-8aab-10a0113a78dc)

* In the image, each data point likely represents a handwritten digit (0-9). The location of each dot on the graph could correspond to two features used by the KNN model to identify the digit. For instance, the features might be the pixel intensity at position (0, 1) and (1, 1) in the image.
* The KNN model would then classify new handwritten digits by finding the existing digits in the training data that are closest (most similar) to the new one based on the chosen features.

## Predicting

![image](https://github.com/778569/Sinhala-character-Recognizer/assets/52319671/174e9bc8-5f88-4737-987b-e0362477d1de)

<br>

* New digit arrives: When a new handwritten digit needs to be classified (represented by "Pixel 255" and "Pixel 1" on the left), the KNN model calculates the distance between this new digit and all the digits in the training set (represented by the points on the right).

* Find k nearest neighbors: The model then selects a predefined number of closest neighbors, denoted by "k". In the absence of information about the image, it's assumed k is 3 here.
* Majority vote wins: The model predicts the class (digit) that is most frequent among these k nearest neighbors. In the image, the 3 closest neighbors (based on an unknown distance metric) to the new digit are likely digits 3, 7, and 9. Since 7 appears most frequently among the 3 closest neighbors, the model predicts the new digit to be a "digit 7".

## Measurements

### How to Measure the Distance?
<br>


![image](https://github.com/778569/Sinhala-character-Recognizer/assets/52319671/92bc0003-f828-426d-927d-eaa8c4296f9d)


### Euclidean Distance How to deal when there are more than 2 Features


![image](https://github.com/778569/Sinhala-character-Recognizer/assets/52319671/0c5d61dc-a837-4278-bf63-e658fe154fc0)


### Euclidean Disance Example


![image](https://github.com/778569/Sinhala-character-Recognizer/assets/52319671/39ac949d-74e1-4d64-a44c-c5d8818e5f33)


![image](https://github.com/778569/Sinhala-character-Recognizer/assets/52319671/9d14286d-2828-40b7-8e84-b886c52ada64)



## Result 

![image](https://github.com/778569/Sinhala-character-Recognizer/assets/52319671/2e22ef6a-8a9b-4ef6-8c9a-1b7f041cdb29)















