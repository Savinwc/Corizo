# Corizo
# Corizo Mini Project

Handwritten digit recognition using MNIST dataset is a  project made with the help of Neural Network. 
It basically detects the scanned images of handwritten digits. 

This  project is taken a step further where our handwritten digit recognition system not only detects scanned images of handwritten digits ,
but also allows writing digits on the screen with the help of an integrated GUI for recognition. 

We will approach this project by using a three-layered Neural Network. 

The input layer: It distributes the features of our examples to the next layer for calculation of activations of the next layer.

The hidden layer: They are made of hidden units called activations providing nonlinear ties for the network. 
                  A number of hidden layers can vary according to our requirements.
                  
The output layer: The nodes here are called output units. It provides us with the final prediction of the Neural Network on the basis of which 
                  final predictions can be made.
                  
Commit the file to your repository 
Install all File dependencies
And Run GUI.py
The Handwritten digits will convert to text interpreted images



# Corizo Major Project

Audio classification is an Application of machine learning where different sound is categorized in certain categories. 

In this project, we will build a complete music Genre classification project from scratch using a machine learning algorithm known as the K-Nearest Neighbors classification algorithm.

K-Nearest Neighbour ~ KNN is a machine learning algorithm used for regression, and classification. It is also known as the lazy learner algorithm. It simply uses a distance-based method o find the K number of similar neighbours to new data and the class in which the majority of neighbours lies, it results in that class as an output. Now let us get our system ready for project implementation.

Dataset Overview
The dataset used is named the GTZAN genre collection dataset which is a very popular audio collection dataset. It contains approximately 1000 audio files that belong to 10 different classes. Each audio file is in .wav format (extension). The classes to which audio files belong are Blues, Hip-hop, classical, pop, Disco, Country, Metal, Jazz, Reggae, and Rock.

Hands-on Implementation of Music Genre Classification Project :
1)Import required libraries
2)Define a function to calculate distance between feature vectors, and to find neighbours.
3)Identify the class of nearest neighbours
4)Model Evaluation
5)Feature Extraction
6)Train-test split the dataset
7)Calculate the distance between two instance
8)Training the Model and making predictions
9)Test the Classifier with the new Audio File

# This project is made using kaggle notebook and gitzan dataset.


The project begins with the initial setup and used MFCC to extract features from audio files. 
After that, we have built a KNN classifier from scratch that finds K number of nearest neighbour based on features and maximum neighbour belonging to particular class gives as an output.  
Approximately 70 per cent accuracy was achieved on the model.

# Major takeaways(Major Project)
1.The main thing to identify and divide the audio into different features is amplitude and frequency that changes within a short span of time.

2.We can visualize the audio frequency wave of amplitude and frequency with respect to time in form of a wave plot that can be easily plotted using librosa.

3.MFCCs total provides 39 features related to frequency and amplitude. In that 12 parameters are related to the amplitude of frequencies. It means it provides us with enough frequency channels to analyze audio and this is the reason MFCCs are used everywhere for feature extraction in audios.

4.The key working of MFCC is to remove vocal excitation (pitch information) by dividing audio into frames, make extracted features independent, adjust the loudness, and frequency of sound according to humans, and capture the context.
