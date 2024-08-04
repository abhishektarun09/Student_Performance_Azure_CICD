# Student Performance Prediction

This project uses machine learning to predict student performance. The application is deployed using Docker and Microsoft Azure, with continuous integration and deployment (CI/CD) pipelines set up. The frontend is a web application built with HTML and Flask. The project also includes custom exception handling and logging.

## Table of Contents

- [Overview](#overview)
- [Features](#features)
- [Machine Learning Models](#machine-learning-models)
- [Technologies Used](#technologies-used)
- [Usage](#usage)
- [Deployment](#deployment)
- [Contributing](#contributing)

## Overview

The goal of this project is to predict student performance based on various input features using several machine learning models. The predictions are served via a web application with a user-friendly interface.

## Features

- Predicts student performance using multiple machine learning models.
- Web application interface built with HTML and Flask.
- Dockerized application for consistent and portable deployment.
- Deployed on Microsoft Azure with CI/CD pipelines.
- Custom exception handling and logging for better error tracking and debugging.

## Machine Learning Models

The following machine learning models are used in this project:

- Random Forest: `RandomForestRegressor()`
- Decision Tree: `DecisionTreeRegressor()`
- Gradient Boosting: `GradientBoostingRegressor()`
- Linear Regressor: `LinearRegression()`
- K-Neighbors Classifier: `KNeighborsRegressor()`
- XGBClassifier: `XGBRegressor()`
- CatBoosting Classifier: `CatBoostRegressor()`
- AdaBoost Classifier: `AdaBoostRegressor()`

## Technologies Used

- **Backend**: Flask, Python
- **Frontend**: HTML
- **Machine Learning**: scikit-learn, XGBoost, CatBoost
- **Containerization**: Docker
- **Cloud Platform**: Microsoft Azure
- **CI/CD**: GitHub Actions
- **Logging**: Python's `logging` module
- **Custom Exceptions**: Python's exception handling



## Usage

1. **Access the Web Application**:
   - Add `/predictdata` after the URL in the browser.
   - Enter the required input features for student performance prediction.
   - Click the "Predict" button to see the prediction results.

## Deployment

This project uses Microsoft Azure for deployment with a CI/CD pipeline set up using GitHub Actions.

1. **Continuous Integration**:
   - Automatically build and test the application on each push to the repository.

2. **Continuous Deployment**:
   - Automatically deploy the application to Azure on successful builds.

## Contributing

Contributions are welcome! Please fork the repository and submit a pull request for review.





---


