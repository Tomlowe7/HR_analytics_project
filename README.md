# HR Analytics Final Project

![image](https://github.com/Tomlowe7/HR_analytics_project/assets/126796950/d7cbf6ee-aff0-4193-a1b2-32725597812a)


## Introduction
This repository contains the HR Analytics Final Project, an in-depth analysis of employee burnout and performance, particularly in the high-tech industry.

## Project Overview
The project aims to address the challenges faced by the global workforce, especially the talent shortage in the rapidly growing high-tech sector. We focus on understanding employee burnout, and its economic implications, and predicting employee attrition using various machine-learning models.

### Dataset
The analysis is based on the IBM HR Analytics Employee Attrition & Performance dataset, which includes 1470 entries with 35 variables of different types. This dataset provides a comprehensive view of employee satisfaction, performance, and turnover.

### Methods
- Data Preparation: Ensuring uniqueness and completeness of employee records.
- Exploratory Data Analysis (EDA): Investigating age segmentation, attrition levels, and relationships between quantitative variables.
- Predictive Modeling: Utilizing logistic regression and random forest classifier models to predict employee attrition.

## Requirements
- Python 3.0+
- Jupyter Notebook
- Libraries: pandas, numpy, sklearn, matplotlib, seaborn 

## Installation
Instructions to set up the project environment. For example:
```bash
git clone https://github.com/[your-username]/HR_Analytics_Final_Project.git
cd HR_Analytics_Final_Project
pip install -r requirements.txt


## Conclusions & Summary

A state of employee burnout has high costs for the company due to loss of knowledge and a high cost for training employees in their place. With the help of the data kept on employees, it is possible to get a forecast for employee burnout. It is necessary to take care of the balance of the data that train the model and that are used to test the model. There is no single factor that can predict employee burnout, rather, the parameters that correlate relatively highly with employee burnout are salary (of its types) and involvement and job satisfaction, which implies that when an employee shows signs of burnout, the company must not only look at the benefits and the salary, but it is necessary to ensure that the employee feels engaged and satisfied in his role in the company and in the team, to balance the factors and identify where the employee expresses dissatisfaction. Of course, in order to test the real feasibility of using models to identify attrition factors in high-tech employees, real data from many employees in the global industry must be used. When receiving a data model, it is important to look On the distribution of the data and its meaning, by correctly understanding the data, it is possible to eliminate irrelevant columns (such as unique data for each record or uniform data for all records), columns that provide information of the same meaning for each record, and it is also possible to create new columns that can provide us with additional information and help the model predict the results better.
