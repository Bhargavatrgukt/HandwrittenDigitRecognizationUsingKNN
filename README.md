# HandwrittenDigitRecognizationUsingKNN

 Description
 
This project aims to recognize handwritten digits using the K-Nearest Neighbors (KNN) algorithm. By leveraging the power of KNN, a supervised learning algorithm, we can classify input images of handwritten digits into one of the 10 possible classes (0 to 9).

#  Features:

Dataset Used: 

MNIST - A large database of handwritten digits that serves as the benchmark for this kind of classification task.
Model: 

Implements the K-Nearest Neighbors algorithm for classification.
Interactive UI: Provides a user-friendly interface for users to draw digits and see the model's predictions in real-time.

How It Works:
  Data Preprocessing: The MNIST dataset images are flattened into 1D arrays and normalized.
  Training the Model: The KNN classifier is trained on the processed data.
  Prediction: For a new handwritten digit image, the K-nearest training samples in the feature space are identified and a majority vote is taken to predict its class.
