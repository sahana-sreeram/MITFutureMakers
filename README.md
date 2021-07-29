# MITFutureMakers

## Project 1: Decision Tree Using the Iris Dataset
  This program utilizes the Iris Dataset, which contains four features of three Iris flower species. Using the iris dataset, this program classifies the data as the correct species of flower through the decision tree model. The output is a PDF file containing a visualization of the decision tree, as well as the specific iris species sorted by color. 

## Project 2: Neural Network Classifier with Belgian Traffic Signs
  Following this tutorial (https://www.datacamp.com/community/tutorials/tensorflow-tutorial), I was able to create a neural network that classifies different Belgian Traffic Signs. Some steps in this process included normalizing the data and calculating accuracy and loss. End accuracy: 44.2%
  
## Project 3: Digit Recognizer using a Convolutional Neural Network
Tutorial: https://www.kaggle.com/kanncaa1/convolutional-neural-network-cnn-tutorial
- I was able to create a neural network that recognized digits from a handwritten digit dataset. The steps in the project were roughly split as follows: loading the data & examining the labels, normalizing the data, encoding the labels, creating the neural network, augmenting the data, fitting the model, validating it, and evaluating accuracy/loss with a graphic and confusion matrix.

## Project 4: Digit Recognizer Part 2
Tutorial: https://machinelearningmastery.com/how-to-develop-a-convolutional-neural-network-from-scratch-for-mnist-handwritten-digit-classification/
- To build on Project 3, I followed the tutorial to build a model evaluating the MNIST hanwriting dataset with function definitions and model evaluation to get a better sense of how the model worked and how it performed. I added 3 convolutional layers, which ended up increasing the models accuracy to 98.6%. The box plot and line graph in the summarize functions also helped visualize the accuracy and loss of the model.

## Project 5: Prediciting House Prices
Tutorial: https://hackernoon.com/build-your-first-neural-network-to-predict-house-prices-with-keras-3fb0839680f4
- I followed the tutorial with the popular house prices dataset to build a binary classification neural network to predict if the house was above or below the median value. The tutorial walked through the architecture of the model, and also taught a new aspect: minimizing overfitting through the use of regularization. I also added a section that displayed the predicted outputs for the first 10 columns of data, so that I could visualize the accuracy of the model myself. 

## Project 6: Gender classification of Facial Images
Tutorial: https://www.kaggle.com/thanaphatj/gender-classification-of-facial-images-cnn#Data-Visualization
- Used an image dataset with ages and ethnicities. Objective: classify image as male or female (binary classification). Accuracy after 10 epochs: 92%

## Project 7: Cats vs Dogs classifier
Tutorial: https://keras.io/examples/vision/image_classification_from_scratch/
- Modified instructions from the tutorial to build an image classifier model from scratch using the Microsoft Cats vs Dogs dataset

## Project 8: Minimizing Overfitting using the Twitter US Airline Sentiments
- Explored the three areas that can be used to minimize overfitting: reduce model complexity, apply regularization, and apply dropout layers
- Created a baseline overfitted model to compare with
- End accuracy on test set: 80.33%

## Project 9: Building a simple Autoencoder using Keras and the MNIST digit dataset
- Tutorial: https://blog.keras.io/building-autoencoders-in-keras.html
- Step 1: Building a simple base AE. End result: output a bit lossy
- Step 2: Build a deep AE by increasing layers
- Step 3: Build a ConvAE with Conv2D and UpSampling2D. End Result: less lossy, accuracy about 81%
- Step 4: Experiment with image denoising by adding 0.7 noise to dataset and removing it using AE
- Step 5: Build a generative AE using Variational Autoencoding

## Project 10: Sentiment Analysis of Text using Movie Review dataset
- Tutorial: https://www.tensorflow.org/tutorials/keras/text_classification
- Type: NLP Binary Classifier
- Built a simple ML model using NLP to predict if a movie review is positive or negative
- Exported the model to be able to read raw string data
- Added a Python loop to output "Positive" or "Negative" based on inputted string data
  
