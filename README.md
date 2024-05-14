
<div align=center>
  
  ![Linear_Regression_in_Sckit-learn](https://github.com/BaraSedih11/Linear-Regression-in-scikit-learn/assets/98843912/ec4a6dcb-f8c6-4808-b159-bb75eaaf95ba)


   ![GitHub repo size](https://img.shields.io/github/repo-size/BaraSedih11/Linear-Regression-in-scikit-learn) ![GitHub repo file count (file type)](https://img.shields.io/github/directory-file-count/BaraSedih11/Linear-Regression-in-scikit-learn) [![Python Version](https://img.shields.io/badge/python-3.8-blue)](https://www.python.org/downloads/release/python-380/)
[![Pip Version](https://img.shields.io/badge/pip-21.0-orange)](https://pypi.org/project/pip/21.0/)
 ![GitHub last commit (branch)](https://img.shields.io/github/last-commit/BaraSedih11/Linear-Regression-in-scikit-learn/main)
[![Version](https://img.shields.io/badge/version-v1.0.0-blue)](https://github.com/BaraSedih/Linear-Regression-in-scikit-learn/releases/tag/v1.0.0)
[![Contributors](https://img.shields.io/github/contributors/BaraSedih11/Linear-Regression-in-scikit-learn)](https://github.com/BaraSedih11/Linear-Regression-in-scikit-learn/graphs/contributors)
![GitHub pull requests](https://img.shields.io/github/issues-pr-raw/BaraSedih11/Linear-Regression-in-scikit-learn)
  
</div>

This repository contains a simple implementation of linear regression using the scikit-learn library in Python.

## Overview
Linear regression is a fundamental technique in statistics and machine learning for modeling the relationship between a dependent variable and one or more independent variables. It assumes a linear relationship between the input variables (features) and the output variable (target).

In this repository, we demonstrate how to perform linear regression using the scikit-learn library, which is a powerful tool for machine learning in Python. We provide a simple example along with explanations to help you understand how to apply linear regression to your own datasets.

## Requirements
To run the code in the Jupyter Notebook, you need to have Python installed on your system along with the following libraries:

* NumPy
* pandas
* scikit-learn
* matplotlib
You can install these libraries using pip:

```bash
pip install numpy pandas scikit-learn matplotlib
```

## Working steps
In this quiz, you'll be working with data on the average life expectancy at birth and the average BMI for males across the world. The data comes from Gapminder(opens in a new tab).

The data file can be found under the "bmi_and_life_expectancy.csv" tab in the quiz below. It includes three columns, containing the following data:

Country – The country the person was born in.
Life expectancy – The average life expectancy at birth for a person in that country.
BMI – The mean BMI of males in that country.
You'll need to complete each of the following steps:
1. Load the data

The data is in the file called "bmi_and_life_expectancy.csv".
Use pandas read_csv(opens in a new tab) to load the data into a dataframe (don't forget to import pandas!)
Assign the dataframe to the variable bmi_life_data.
2. Build a linear regression model

Create a regression model using scikit-learn's LinearRegression(opens in a new tab) and assign it to bmi_life_model.
Fit the model to the data.
3. Predict using the model

Predict using a BMI of 21.07931 and assign it to the variable laos_life_exp.

## Acknowledgements

- [scikit-learn](https://scikit-learn.org/): The scikit-learn library for machine learning in Python.
- [NumPy](https://numpy.org/): The NumPy library for numerical computing in Python.
- [pandas](https://pandas.pydata.org/): The pandas library for data manipulation and analysis in Python.
- [matplotlib](https://matplotlib.org/): The matplotlib library for data visualization in Python.
