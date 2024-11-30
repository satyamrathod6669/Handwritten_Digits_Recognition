# Handwritten_Digits_Recognition

Handwritten Digits Recognition

Problem Statement

Task 1:-Prepare a complete data analysis report on the given data.

Task 2:- Classify a given image of a handwritten digit into one of the 10 classes representing integer values from 0 to 9.

Task3:- Compare between various models and find the classifier that works better.


Dataset Link:
MNIST ("Modified National Institute of Standards and Technology") is the de facto “hello world” dataset of computer vision. Since its release in 1999, this classic dataset of handwritten images has served as the basis for benchmarking classification algorithms. As new machine learning techniques emerge, MNIST remains a reliable resource for researchers and learners alike.
Your goal is to correctly identify digits from a dataset of tens of thousands of handwritten images. We encourage you to experiment with different algorithms to learn first-hand what works well and how techniques compare.
Practice Skills
●	Computer vision fundamentals including simple neural networks
●	Classification methods such as SVM and K-nearest neighbors
Domain: 
Link : https://d3ilbtxij3aepc.cloudfront.net/projects/CDS-Capstone-Projects/PRCP-1002-HandwrittenDigits.zip

The input feature contains images.
Output feature contains 10 classes (digits varying from 0 to 9)


To the get the date for this project please follow the below code:

from tensorflow.keras.datasets import mnist
(x_train, y_train), (x_test, y_test) = mnist.load_data()


