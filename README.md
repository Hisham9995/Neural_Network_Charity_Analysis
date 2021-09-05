# Neural_Network_Charity_Analysis
Processing and analyzing Data using TensorFlow and deep learning neural networks to classify the success of charitable donations.




# Overview of the analysis:
This Anaylsis is about   creating  a neural network model that is able to predicting whether applicants will be successful if funded by Alphabet Soup. The dataset includes more than 34,000 organizations that have received funding from Alphabet Soup over the years.


# Results 

# Data Preprocessing

variable(s) that are considered the target(s) for your model?

The variable we are targeting in this module is the IS_SUCCESSFUL column.

variable(s) that are considered to be the features for your model .?

The features that we are using are every column except the ones that we will drop.

What variable(s) are neither targets nor features were removed .?

First features we drop are the 'EIN' & 'NAME' because we expect both features to have little to do with our outcome.


# Compiling, Training, and Evaluating the Model


How many neurons, layers, and activation functions did you select for your neural network model

This model is made with an input features & two hidden layers. The first hidden layer has 20 neurons, the second has 12 , the third has 10 , the fourth has 8 , the fifth has 8, there is also an output layer. The activation function of hidden layers or output layers is changed from "relu" to "tanh"  & the output layer is "sigmoid".


![Hidden layers](https://user-images.githubusercontent.com/82621077/132142282-4418356d-1049-43da-9386-8ab2758db6c7.png)

Was the model able to achieve the target model performance?




Was the model able to achieve the target model performance?

Although we the target for the model was to be 75% or above, I was not able to reach the target.


What steps were taken to try and increase model performance?

The steps I took  were adding hidden layers, changing the activation type, I have tried changing the number of epochs but I put it back to 100  and changing the number of neurons in each layer  to try and make the model more accurate but unfortunatley I could not achieve 75% or above



# Summary


