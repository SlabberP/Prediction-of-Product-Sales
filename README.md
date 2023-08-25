# Sales prediction for food items sold at various retail store outlets
## Food Item sales and the features that impact the sales.

**Author**: Pieter Slabber

![alt text](https://github.com/SlabberP/Prediction-of-Product-Sales/blob/main/data-scientist.jpg)

### Business problem:

The goal of this is to help the retailer understand the properties of products and outlets that play crucial roles in increasing sales.


### Data:
Data Source: https://datahack.analyticsvidhya.com/contest/practice-problem-big-mart-sales-iii/

### Data Dictionary
The data consists of columns containing information regarding different products and stores.
![alt text](https://github.com/SlabberP/Prediction-of-Product-Sales/blob/main/Data%20Dictionary.GIF)

The dataframe was found to have 8523 rows and 12 columns

## Methods
- Data preparation steps:
  - The data was cleaned using the normal removal of the duplicate values.
  - It was then checked for inconsistencies. The inconsistencies were fixed.
  - The "Item_Outlet_Sales" column or feature was then identified as the target or dependent column.
  - Check the data for null values or missing values. Imputing these values only happens after the train/test split.
  - Split the train and test data.
  - Preprossing:
     - Creating pipelines for encoding and scaling of Categorical, Ordinal and numeric features.
     - Fit the preprocessor to the traing data only
     - Transform the training and test data
  
  - Machine Learning:
    - The model was based on the dependency and dpendent feature which is a regression target.
     - Instantiate the Linear regression model:
     - Fit the model to the training data only.
     - Train the Model on the training data.
     - 
 with explanation and justification for choices
- Regression Metric Selection: Linear regression

Used to predict or explain the relationship between a dependent variable and one or more independent variables.It assumes a linear connection between these variables, represented by a straight line

Regression Metric Selection: Random Forest with GridSearchCV

Random Forest with GridSearchCV is a powerful combination of machine learning techniques used for building predictive models. Random Forest is an ensemble algorithm that combines multiple decision trees to make accurate predictions. GridSearchCV is a method for systematically tuning hyperparameters to find the best configuration for a model

## Results

### Here are examples of how to embed images from your sub-folder


#### Visual 1 Title
![alt text](https://github.com/SlabberP/Prediction-of-Product-Sales/blob/main/CountPlot.png)

> Sentence about visualization.

#### Visual 2 Title
![alt text](https://github.com/SlabberP/Prediction-of-Product-Sales/blob/main/Heatmap.png)

## Model

  Instantiate the Model:
  - The model was based on the dependency and dpendent feature which is a regression target.
    Instantiate the Linear regression model:
    - Fit the model to the training data only.
    - Train the Model on the training data.
 
Describe your final model

Report the most important metrics

Refer to the metrics to describe how well the model would solve the business problem

## Recommendations:

More of your own text here


## Limitations & Next Steps

More of your own text here


### For further information


For any additional questions, please contact **email**
