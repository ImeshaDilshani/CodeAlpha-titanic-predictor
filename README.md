# CodeAlpha-sinking-titanic-predictor

## Overview
This project aims to predict whether a passenger aboard the Titanic survived the sinking disaster or not. The prediction is based on various features such as socio-economic status, age, gender, and more.

## Dataset
The dataset used for this project is the famous Titanic dataset, which contains information about passengers including features like:
- Passenger class (Pclass)
- Name
- Sex
- Age
- Number of siblings/spouses aboard (SibSp)
- Number of parents/children aboard (Parch)
- Ticket number
- Fare
- Cabin
- Port of embarkation (Embarked)

The dataset also includes a binary target variable indicating whether the passenger survived or not.

## Requirements
- Python 3.x
- pandas
- numpy



## Implementation Details
- The dataset is preprocessed by handling missing values, converting categorical variables into numerical ones, and scaling numerical features.
- A logistic regression model is trained on the preprocessed data to predict survival.
- Model performance is evaluated using accuracy.

## Future Work
- Explore other machine learning models such as decision trees, random forests, or neural networks for potentially better performance.
- Experiment with feature engineering techniques to improve model accuracy.
- Hyperparameter tuning to optimize the model's performance.

## Contributors
- [Imesha Dilshani](https://github.com/ImeshaDilshani)

## License
This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

