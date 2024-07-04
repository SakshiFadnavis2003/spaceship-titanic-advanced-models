# Spaceship Titanic Advanced Models

## Overview

This repository contains an advanced machine learning solution for the [Spaceship Titanic Kaggle competition](https://www.kaggle.com/c/spaceship-titanic). The solution includes preprocessing steps, feature engineering, and the application of sophisticated models to predict passenger transport status.

## Table of Contents

- [Overview](#overview)
- [Features](#features)
- [Data](#data)
- [Preprocessing](#preprocessing)
- [Models](#models)
- [Hyperparameter Tuning](#hyperparameter-tuning)
- [Model Evaluation](#model-evaluation)
- [Submission](#submission)
- [Installation](#installation)
- [License](#license)
- [Contributing](#contributing)

## Features

- Advanced feature engineering including `Total_Spending`, `Age_Group`, and `Title` extraction.
- Preprocessing of missing values and encoding categorical features.
- Implementation of machine learning models including `RandomForestClassifier` and `XGBClassifier`.
- Hyperparameter tuning using `GridSearchCV` for optimizing the `RandomForestClassifier`.
- Stacking models with `VotingClassifier` for improved prediction accuracy.

## Data

The datasets used in this project are:
- `train.csv`: The training data used to build and validate models.
- `test.csv`: The test data for making predictions.
- `sample_submission.csv`: A sample submission file for formatting the predictions.

## Preprocessing

Data preprocessing steps include:
- Handling missing values for numerical and categorical features.
- Feature extraction and engineering.
- Encoding categorical variables.
- Splitting the data into training and validation sets.

## Models

- **RandomForestClassifier**: A versatile ensemble learning method for classification tasks.
- **XGBClassifier**: An efficient gradient boosting model for classification.
- **VotingClassifier**: A combination of `RandomForestClassifier` and `XGBClassifier` for enhanced performance.

## Hyperparameter Tuning

Performed grid search for hyperparameter tuning of the `RandomForestClassifier` to find the best combination of hyperparameters for improved model performance.

## Model Evaluation

Models were evaluated using accuracy score on the validation set. The best-performing model achieved a validation accuracy of `77%` before applying the Voting Classifier and `XGBClassifier` for stacking, which improved the performance.

## Submission

The predictions are saved in `submission.csv`, formatted according to the requirements of the competition.

## Installation

To run this project, clone the repository and install the required packages:

```bash
git clone https://github.com/SakshiFadnavis2003/spaceship-titanic-advanced-models.git
cd spaceship-titanic-advanced-models
pip install -r requirements.txt
```

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## Contributing

Feel free to open issues or submit pull requests to improve the project. 

**Happy coding!**

```
