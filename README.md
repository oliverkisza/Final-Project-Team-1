# Python Rutgers Bootcamp Challenge - Project Four - Heart Disease Understanding 

This activity is broken down into various pieces of code to understand the dynamics of heart disease and choose a model using various variables to note potential predictions for heart disease. 

<summary>Contents</summary>
  <ol>
    <li><a href="#desc">Description</a></li>
    <li><a href="#dpp">Data Preprocessing</a></li>
    <li><a href="#cte">Compiling, Training, & Evaluation</a></li>
    <li><a href="#optimize">Optimization</a></li>
    <li><a href="#results">Results</a></li>
    <li><a href="#Analysis">Report & Analysis</a></li>
  </ol>

<a name="desc"></a>

## Description

The purpose of this analysis is to ascertain possible models for the prediction of heart disease. Our group chose the [following dataset from Kaggle](https://www.kaggle.com/datasets/kamilpytlak/personal-key-indicators-of-heart-disease/) which was itself collected from the CDC's [Behavioral Risk Factor Surveillance System (BRFSS)](https://www.cdc.gov/brfss/index.html). Per the CDC, the BRFSS "completes more than 400,000 adult interviews each year, making it the largest continuously conducted health survey system in the world."

![Screenshot 2023-12-14 113319](https://github.com/oliverkisza/Final-Project-Team-1/assets/18508699/ca14849d-d5d9-4c1c-a943-cc6e848c27d0)


Due to the dataset being completed by the CDC and the ability to compare and contrast recent datasets of heart disease data (2020 and 2022 data), our group felt this could be a great way to predict potential heart disease across the American populace. 

<a name="dpp"></a>

## Step 1: Data Preprocessing<

In order to best understand and target variables to use in the model, the group sought a number of techniques and tools to understand both datasets. 
## Step 2: Compiling, Training, & Evaluation
<a name="cte"></a>

xxxxxxxxxxxxxxxxxxxxxxxxx

## Step 3: Optimize the Model
<a name="optimize"></a>

xxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxx
 
 ## Step 4: Results
<a name="results"></a>

xxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxx

 ## Step 5: Analysis
<a name="Analysis"></a>

xxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxx

The report should contain the following:

1. Overview of the analysis: Explain the purpose of this analysis.

2. Results: Using bulleted lists and images to support your answers, address the following questions:

  * Data Preprocessing
    * What variable(s) are the target(s) for your model?
    * What variable(s) are the features for your model?
    * What variable(s) should be removed from the input data because they are neither targets nor features?

  * Compiling, Training, and Evaluating the Model
    * How many neurons, layers, and activation functions did you select for your neural network model, and why?
    * Were you able to achieve the target model performance?
    * What steps did you take in your attempts to increase model performance?
   
3. Summary: Summarize the overall results of the deep learning model. Include a recommendation for how a different model could solve this classification problem, and then explain your recommendation.

 ## Final & Complete Written Report 

### Module 12 Report Template

### Overview of the Analysis

In this section, describe the analysis you completed for the machine learning models used in this Challenge. This might include:

* Explain the purpose of the analysis.

The purpose of this analysis to help a nonprofit foundation, Alphabet Soup, select the applicants for funding with the best chance of success in their ventures. 

From Alphabet Soup’s business team, you have received a CSV containing more than 34,000 organizations that have received funding from Alphabet Soup over the years. Within this dataset are a number of columns that capture metadata about each organization, such as application type, industry, use case, organization type, income, and if it was successful venture or not, amongst other variables. 

The model is attempting to predict which venture might be successful based on the variables. Two separate types of neural network models using a TensorFlow Keras sequential model were deployed to include: 

* Model 1: TensorFlow Keras sequential model, 2 hidden layers, using "relu" and "sigmoid" activations
* Model 2: TensorFlow Keras sequential model, 6 hidden layers, using "relu" and "sigmoid" activations 

The models were first binned to eliminate excessive variables in for both applications and classification. Categorical data was also changed to dummy variables for neural network modeling. 

### Results

* Data Preprocessing
    * What variable(s) are the target(s) for your model? xxxxxxxxxxxxxxxxxxxxxxxxx
    * What variable(s) are the features for your model? xxxxxxxxxxxxxxxxxxxxxxx
    * What variable(s) should be removed from the input data because they are neither targets nor features? xxxxxxxxxxxxxxxx

  * Compiling, Training, and Evaluating the Model
    * How many neurons, layers, and activation functions did you select for your neural network model, and why? xxxxxxxxxxxxxxxxxxxx
    * Were you able to achieve the target model performance? xxxxxxxxxxxxxxxxxxxxxxx
    * What steps did you take in your attempts to increase model performance? xxxxxxxxxxxxxxxxxxx


### Summary

xxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxx
 

## Dependencies

* Used IBM SPSS for regression analysis (optional)
* Using Python for cleaning of data and exporting clean CSV file
* Using Spark for model ingestion, low level analysis, and exporting file
* Using Google Collaboratory to do the coding and reading in the CSV file and Tensor Flow workloads 

## Installing

* No modifications needed to be made to files/folders

## Help

No help required. 
