# Neural_Network_Charity_Analysis

# Overview:

Beks has come a long way since her first day at that boot camp five years ago—and since earlier this week, when she started learning about neural networks! Now, she is finally ready to put her skills to work to help the foundation predict where to make investments.

With your knowledge of machine learning and neural networks, you’ll use the features in the provided dataset to help Beks create a binary classifier that is capable of predicting whether applicants will be successful if funded by Alphabet Soup.

From Alphabet Soup’s business team, Beks received a CSV containing more than 34,000 organizations that have received funding from Alphabet Soup over the years. Within this dataset are a number of columns that capture metadata about each organization, such as the following:

EIN and NAME—Identification columns
APPLICATION_TYPE—Alphabet Soup application type
AFFILIATION—Affiliated sector of industry
CLASSIFICATION—Government organization classification
USE_CASE—Use case for funding
ORGANIZATION—Organization type
STATUS—Active status
INCOME_AMT—Income classification
SPECIAL_CONSIDERATIONS—Special consideration for application
ASK_AMT—Funding amount requested
IS_SUCCESSFUL—Was the money used effectively

### This new assignment consists of three technical analysis deliverables and a written report. You will submit the following:

Deliverable 1: Preprocessing Data for a Neural Network Model

Deliverable 2: Compile, Train, and Evaluate the Model

Deliverable 3: Optimize the Model

Deliverable 4: A Written Report on the Neural Network Model (README.md)

# Result:

##Data Preprocessing

What variable(s) are considered the target(s) for your model?

- The target variable for the model created is the "IS_SUCCESSFUL" variable.

What variable(s) are considered to be the features for your model?

- The featured variables for the model are "APPLICATION_TYPE", "AFFILIATION", "CLASSIFICATION", "USE_CASE", "ORGANIZATION", "STATUS", "INCOME_AMT", "SPECIAL_CONSIDERATIONS", "ASK_AMT".

What variable(s) are neither targets nor features, and should be removed from the input data?

- The variables that are neither targets or features and were removed fromthe model were "NAME" and "EIN.

##Compiling, Training, and Evaluating the Model

How many neurons, layers, and activation functions did you select for your neural network model, and why?

- The total parameters for the neural network model original was 5981 
  - 2 hidden layers: one with 80 neurons, one with 30 neurons.
  - 1 output layer

Were you able to achieve the target model performance?

- I was not able to achieve the desired model performance sadly.

What steps did you take to try and increase model performance?

- For my optimization i did the following processes:
  - Binned INCOME_AMT and AFFILIATION column
  - Increasing the number of neurons per layer
    - First layer has 125
    - Second layer has 50
  - This creates 11,101 total parameters.
  
 # Summary:
  
- Sadly in the end i did not achieve the desired model performance. perhaps if i were to fine tune the model further i would add more neurons to my layers or perhaps add a third hidden layer to increase the scruteny on the model itself and have it run through more tests.
