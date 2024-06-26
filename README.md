# deep-learning-challenge

## Purpose

The nonprofit foundation Alphabet Soup wants a tool that can help it select the applicants for funding with the best chance of success in their ventures. With your knowledge of machine learning and neural networks, you’ll use the features in the provided dataset to create a binary classifier that can predict whether applicants will be successful if funded by Alphabet Soup.

From Alphabet Soup’s business team, you have received a CSV containing more than 34,000 organizations that have received funding from Alphabet Soup over the years. Within this dataset are a number of columns that capture metadata about each organization, such as:

EIN and NAME—Identification columns
APPLICATION_TYPE—Alphabet Soup application type
AFFILIATION—Affiliated sector of industry
CLASSIFICATION—Government organization classification
USE_CASE—Use case for funding
ORGANIZATION—Organization type
STATUS—Active status
INCOME_AMT—Income classification
SPECIAL_CONSIDERATIONS—Special considerations for application
ASK_AMT—Funding amount requested
IS_SUCCESSFUL—Was the money used effectively

## Steps

- Step 1: Preprocess the Data

  Using your knowledge of Pandas and scikit-learn’s StandardScaler(), you’ll need to preprocess the dataset.
  Read in the charity_data.csv to a Pandas DataFrame,
  Drop the EIN and NAME columns.

- Step 2: Compile, Train, and Evaluate the Model

  Using your knowledge of TensorFlow, you’ll design a neural network, or deep learning model, to create a binary classification model that can predict if an Alphabet Soup-funded organization will be successful based on the features in the     dataset. You’ll need to think about how many inputs there are before determining the number of neurons and layers in your model.

- Step 3: Optimize the Model

  Using your knowledge of TensorFlow, optimize your model to achieve a target predictive accuracy higher than 75%.

  - Step 4: Write a Report on the Neural Network Model

    The report should contain the following:

    Overview of the analysis: Explain the purpose of this analysis.

    Results: Using bulleted lists and images to support your answers, address the following questions:

    Data Preprocessing

    What variable(s) are the target(s) for your model?
    What variable(s) are the features for your model?
    What variable(s) should be removed from the input data because they are neither targets nor features?
    Compiling, Training, and Evaluating the Model

    How many neurons, layers, and activation functions did you select for your neural network model, and why?
    Were you able to achieve the target model performance?
    What steps did you take in your attempts to increase model performance?
    Summary: Summarize the overall results of the deep learning model. Include a recommendation for how a different model could solve this classification problem, and then explain your recommendation.

    
