# Neural_Network_Charity_Analysis

<p align="center"><img class="centerImage" src="https://github.com/dalejandri/Neural_Network_Charity_Analysis/blob/main/Resources/1.PNG" /></p>

## Background
Bek’s come a long way since her first day at that boot camp five years ago—and since earlier this week, when she started learning about neural networks! Now, she is finally ready to put her skills to work to help the foundation predict where to make investments.

With your knowledge of machine learning and neural networks, you’ll use the features in the provided dataset to help Beks create a binary classifier that is capable of predicting whether applicants will be successful if funded by Alphabet Soup.

From Alphabet Soup’s business team, Beks received a CSV containing more than 34,000 organizations that have received funding from Alphabet Soup over the years. Within this dataset are a number of columns that capture metadata about each organization, such as the following:

- EIN and NAME—Identification columns
- APPLICATION_TYPE—Alphabet Soup application type
- AFFILIATION—Affiliated sector of industry
- CLASSIFICATION—Government organization classification
- USE_CASE—Use case for funding
- ORGANIZATION—Organization type
- STATUS—Active status
- INCOME_AMT—Income classification
- SPECIAL_CONSIDERATIONS—Special consideration for application
- ASK_AMT—Funding amount requested
- IS_SUCCESSFUL—Was the money used effectively

## Deliverable 1: Preprocessing Data for a Neural Network Model

Using  Pandas and the Scikit-Learn’s StandardScaler() to preprocess the dataset in order to compile, train, and evaluate the neural network model later in Deliverable 2

The following preprocessing steps have been performed:
The EIN and NAME columns have been dropped.
The columns with more than 10 unique values have been grouped together.
The categorical variables have been encoded using one-hot encoding.
The preprocessed data is split into features and target arrays.
The preprocessed data is split into training and testing datasets.
The numerical values have been standardized using the StandardScaler() module.

<p align="center"><img class="centerImage" src="https://github.com/dalejandri/Neural_Network_Charity_Analysis/blob/main/Resources/2.PNG" /></p>


## Deliverable 2: Compile, Train, and Evaluate the Model.

Using your knowledge of TensorFlow, you’ll design a neural network, or deep learning model, to create a binary classification model that can predict if an Alphabet Soup–funded organization will be successful based on the features in the dataset. You’ll need to think about how many inputs there are before determining the number of neurons and layers in your model. Once you’ve completed that step, you’ll compile, train, and evaluate your binary classification model to calculate the model’s loss and accuracy.

The neural network model using Tensorflow Keras contains working code that performs the following steps:

The number of layers, the number of neurons per layer, and activation function are defined.
An output layer with an activation function is created.
There is an output for the structure of the model.
There is an output of the model’s loss and accuracy.
The model's weights are saved every 5 epochs.

<p align="center"><img class="centerImage" src="https://github.com/dalejandri/Neural_Network_Charity_Analysis/blob/main/Resources/4.PNG" /></p>

The results are saved to an HDF5 file.


<p align="center"><img class="centerImage" src="https://github.com/dalejandri/Neural_Network_Charity_Analysis/blob/main/Resources/3.PNG" /></p>
