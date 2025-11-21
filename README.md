# Titanic_survived

A predictive analytics project to determine which passengers survived the Titanic disaster.

## Overview

This project analyzes the famous Titanic dataset to predict passenger survival using a variety of machine learning algorithms. It explores data preprocessing, feature selection, model training, and evaluation.

## Dataset

The primary dataset used is the [Kaggle Titanic: Machine Learning from Disaster](https://www.kaggle.com/c/titanic/data) dataset, which contains information such as age, gender, passenger class, and survival status.

## Features Used

- PassengerId  
- Pclass (Ticket class)
- Name
- Sex
- Age
- SibSp (Number of siblings/spouses aboard)
- Parch (Number of parents/children aboard)
- Ticket
- Fare
- Cabin
- Embarked (Port of Embarkation)

## Project Structure

```
├── data/                    # Data files (train, test)
├── notebooks/               # Jupyter notebooks
├── src/                     # Python scripts for data processing and modeling
├── models/                  # Saved models
├── README.md
├── requirements.txt
└── Titanic_survived.ipynb
```

## Requirements

Install dependencies using:

```sh
pip install -r requirements.txt
```

## Usage

1. Clone the repository
2. Place the dataset in the `data/` folder
3. Run the notebook:
   - Open `Titanic_survived.ipynb` to explore the code and results
   - Or run the scripts in `src/` for specific tasks

## Approach

- **Exploratory Data Analysis (EDA):** Visualize and analyze dataset features.
- **Data Preprocessing:** Handle missing values, encode categorical variables, feature engineering.
- **Modeling:** Train models such as Logistic Regression, Random Forest, and XGBoost.
- **Evaluation:** Assess model performance using metrics like accuracy, precision, recall, and F1-score.
- **Prediction:** Generate predictions for the test set.

## Results

The final model achieves an accuracy of approximately XX% on the validation set. See the notebook for detailed metrics and analysis.

## Contributing

Pull requests are welcome! For major changes, open an issue first to discuss what you would like to change.

## License

[MIT License](LICENSE)

## References

- [Kaggle Titanic Competition](https://www.kaggle.com/c/titanic)
- [Titanic Dataset on Kaggle](https://www.kaggle.com/c/titanic/data)