# Linear Regression

**Linear Regression** is a statistical method used to determine the relationship between a dependent variable and one or more independent variables. In machine learning, this relationship helps predict an event's outcome based on the data points of the independent variables.
)

**Objective:** The primary goal of Linear Regression is to establish a relationship that can predict the value of a dependent variable (also called the target variable) based on the independent variables (also called features or predictor). The relation is usually a straight line that best fits the different data points as close as possible. The output is of a continuous form, i.e., numerical value
The linear regression model provides a sloped straight line representing the relationship between the variables. Consider the below image:
</br></br>
![image](https://github.com/user-attachments/assets/45579101-de0f-4d4a-a305-ef49992b5f46)
.

The line can be expressed using the equation:
$$𝑦 = mX + b$$
where:
- $y - \text{is the dependent variable (the value to be predicted),}$
- $X - \text{is the independent variable (the predictor),}$
- $m - \text{is the slope of the line (indicating the relationship strength),}$
- $b - \text{is the y-intercept (the value of $y$ when $X$ is zero).}$


## Types of Linear Regression

Linear regression can be further divided into two types of algorithms:

#### 1. Simple Linear Regression

Simple Linear Regression is used when there is only one independent variable to predict the value of a numerical dependent variable. The relationship between the independent variable (predictor) and the dependent variable (target) is modeled as a straight line.

#### 2. Multiple Linear Regression

Multiple Linear Regression is used when more than one independent variable is involved in predicting the value of a numerical dependent variable. This algorithm models the relationship between multiple predictors and a single target variable as a linear equation.

## House Price Prediction with Linear Regression

![](https://i.imgur.com/3sw1fY9.jpg)

In this project, we're going to predict the price of a house using information like its location, area, no. of rooms etc. We'll use the dataset from the [House Prices - Advanced Regression Techniques](https://www.kaggle.com/c/house-prices-advanced-regression-techniques) competition on [Kaggle](https://kaggle.com). We'll follow a step-by-step process to train our model:

1. Download and explore the data
2. Undertake exploratory analysis and preprocessing
3. Prepare the dataset for training
4. Train a linear regression model
5. Make predictions and evaluate the model