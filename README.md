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

## Step 1a: Data Preprocessing

In order to best understand and target variables to use in the model, the group sought a number of techniques and tools to understand both datasets. 

In an optional data evaluation, the group used [IBM's SPSS](https://www.ibm.com/spss) to do quick stepwise multiple regression analyses to ascertain the top variables to use in the model. 

![Screenshot 2023-12-14 121232](https://github.com/oliverkisza/Final-Project-Team-1/assets/18508699/224fcdbe-6538-49c2-925f-f341dd184ceb)

For the 2020 dataset set, **Heart Disease (Yes/No)** was used as primary dependent variable and all others were used as independent variables. Similar regression models were run with the 2022 data which ran two different dependent variables, **Heart Attack (Yes/No)** and **High Risk Last Year (Yes/No)**. 

![Screenshot 2023-12-14 121608](https://github.com/oliverkisza/Final-Project-Team-1/assets/18508699/5cbd3ffa-51f4-4e32-a898-7c62a1395cbf)

There were not large r2 or correlations in any of the analyses we saw, but it did give us some directions on the potential usage for variables in the models. 

The group also used Tableau to visually examine the data. You can examine the data yourself in the following public Tableau pages: 

* [Heart Disease in America - 2020](https://public.tableau.com/app/profile/christopher.manfredi/viz/HeartDiseaseInAmerica/HeartDiseaseinAmerica#1)
* [Heart Disease in America - 2022](https://public.tableau.com/app/profile/christopher.manfredi/viz/HeartAttackInAmerica-2022/HeartDiseaseinAmerica-2022?publish=yes)

![Screenshot 2023-12-14 133458](https://github.com/oliverkisza/Final-Project-Team-1/assets/18508699/a94bbf30-d73d-4284-bd96-868415b8b3b9)

![Screenshot 2023-12-14 133439](https://github.com/oliverkisza/Final-Project-Team-1/assets/18508699/31128b36-2c65-4920-8fa4-a1b66099ccc2)


## Step 1b: Data Cleaning

Data cleaning was completed using Python for both datasets. The following are breakdown of both data sets: 

**2020 Dataset** and [2020 cleaning code](https://github.com/oliverkisza/Final-Project-Team-1/blob/main/FA_data_cleaning_2020.ipynb)

- 17 feature columns (heart disease indicators)
- 1 target column (HeartDisease)
- ~320,000 rows
- Renamed columns to match identical columns in heart_2022 with slightly different names(ex: GenHealth:GeneralHealth; PhysicaHealth: PhysicalHealthDays; DiffWalking:DifficultyWalking,etc.)
- Renamed other columns for clarity such as SleepTime:HoursOfSleep
- Removed rows with ambiguous data: Diabetic (Yes, during pregnancy, No, borderline diabetes) to yield binary column
- Created dummy variables ideal for binary categories
- Mapped ordinal variables from least to greatest starting from 0 (GeneralHealth and AgeCategory)

**2022 Dataset** and [2022 cleaning code](https://github.com/oliverkisza/Final-Project-Team-1/blob/main/data_cleaning_2022.ipynb)

- 39 feature columns (heart disease indicators)
- 1 target column (“HadHeartAttack”)
- ~246,000 rows

- Removed columns (“State”, “HadDiabetes”, etc)
- Renamed other columns for clarity such as “SleepTime”: “HoursOfSleep”
- Removed NaN
- Created dummy variables ideal for binary categories (“Sex”, “PhysicalActivities”, “HadHeartAttack”, “HadAngina”, etc)
= Mapped ordinal variables from least to greatest starting from 0 (“GeneralHealth”, “AgeCategory”, “LastCheckupTime”, “RemovedTeeth”, “SmokerStatus”, and “ECigaretteUsage”)


<a name="cte"></a>

## Step 2: Compiling, Training, & Evaluation

xxxxxxxxxxxxxxxxxxxxxxxxx

<a name="optimize"></a>

## Step 3: Optimize the Model

xxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxx

 <a name="results"></a>
 ## Step 4: Results


xxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxx

<a name="Analysis"></a>

 ## Step 5: Analysis

xxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxx

## Dependencies

* Used IBM SPSS for regression analysis (optional)
* Using Python for cleaning of data and exporting clean CSV file
* Using Spark for model ingestion, low level analysis, and exporting file
* Using Google Collaboratory to do the coding and reading in the CSV file and Tensor Flow workloads 

## Installing

* No modifications needed to be made to files/folders

## Help

No help required. 
