# Medical Insurance Cost Project ❤
This repository consists of files required to deploy a Machine Learning Web App created with Flask and deployed using Heroku platform.

## Problem Statement

We have predict the medical insurance cost based on certain feature available in the dataset.

## Technology used
- Python
- Machine Learning
- Pandas
- Numpy
- Scikit-learn
- Flask
- HTML
- CSS
- Pycharm
- Heroku

  
## Running Tests

To run app, run the following command

```bash
  python app.run
``
  
## Deployment

To deploy this project run following command in the project folder

```bash
  git bash open
```

Create .git file
```bash
  git init
```
Track all the files
```bash
  git add .
```
Cheacking file track or not
```bash
  git status
```
Store as separate version
```bash
  git commit -m 'message'
```
### Deployment on Heroku

Heroku login on git bash

```bash
  heroku login
```
Create new app

```bash
  heroku create
```
Push Code
```bash
  git remote -v
```
Push code to Master Branch
```bash
  git push heroku master
```

The HEALTH INSURANCE COST PREDICTION project focuses on predicting the cost of health insurance based on user-provided information. Using Python and machine learning techniques, the project aims to provide accurate cost estimates to individuals seeking health insurance coverage. The main tools employed in this project are the Random Forest Regressor and GradientBoostingRegressor.

The project begins with data analysis and pre-processing, where the provided dataset is examined and cleaned to ensure its quality and suitability for modeling. Relevant features are selected, missing values are handled, and any necessary transformations or encoding are applied to prepare the data for training the models.

Two regression models, namely the Random Forest Regressor and GradientBoostingRegressor, are trained on the pre-processed dataset. These models learn patterns and relationships in the data and are capable of predicting the cost of health insurance based on user inputs.

The impact of the project is highlighted by the achieved accuracy of 87% from the GradientBoostingRegressor model. This high level of accuracy demonstrates the project's effectiveness in predicting health insurance costs, providing valuable insights for individuals planning to purchase insurance coverage.

A demo version of the project is available, showcasing the functionality and accuracy of the implemented models. Users can input their information, and the system will predict the corresponding health insurance cost based on the trained models.

In summary, the HEALTH INSURANCE COST PREDICTION project utilizes Python and machine learning techniques to predict the cost of health insurance. By employing the Random Forest Regressor and GradientBoostingRegressor models, the project achieves an accuracy of 87% in estimating insurance costs. This project has the potential to assist individuals in making informed decisions regarding health insurance coverage, ensuring they have a clearer understanding of the associated costs.
