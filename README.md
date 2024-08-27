# Binary Prediction of Poisonous Mushrooms - Submission accuracy: 98%

This repository contains the code and resources for the Kaggle competition [Playground Series - Season 4, Episode 8](https://www.kaggle.com/competitions/playground-series-s4e8/leaderboard). The goal of this competition is to build a binary classification model to predict whether a mushroom is poisonous or edible based on its features.

![img.png](img.png)

## Overview

In this project, we aim to develop a machine learning model to classify mushrooms as poisonous or edible. The dataset used for this project is provided by the Kaggle competition and includes various features of mushrooms such as cap shape, cap color, gill size, and more.

## Dataset

The dataset for this competition can be found on the [Kaggle competition page](https://www.kaggle.com/competitions/playground-series-s4e8/leaderboard). It consists of several features that describe the physical characteristics of mushrooms.

## Installation

To get started with this project, clone the repository and install the required dependencies:

```bash
git clone https://github.com/Geronimo-Basso/binary-prediction-of-poisonous-mushrooms.git
```

## Model

The model used in this project is a binary classification model built using various machine learning algorithms. The final model is selected based on its performance on the validation set.

### Feature Engineering

- **Data Cleaning**: Missing values were handled by imputing with the most frequent value for categorical features.
- **Encoding**: Categorical features were encoded using one-hot encoding to convert them into numerical format.
- **Feature Selection**: Features were selected based on their importance scores from a Random Forest model.

### Model Training

- **Algorithms Used**: Several algorithms were tested including Logistic Regression, Random Forest, and Gradient Boosting.
- **Hyperparameter Tuning**: Hyperparameters were tuned using GridSearchCV to find the optimal parameters for each model.
- **Cross-Validation**: A 5-fold cross-validation was used to evaluate the performance of the models.

### Model Evaluation

- **Metrics**: The models were evaluated using accuracy, precision, recall, and F1-score.
- **Final Model**: The Gradient Boosting model was selected as the final model due to its superior performance on the validation set.

## Results

The performance of the model is evaluated using metrics such as accuracy, precision, recall, and F1-score. The final results and the leaderboard standings can be found on the [Kaggle competition page](https://www.kaggle.com/competitions/playground-series-s4e8/leaderboard).

## Contributing

Contributions are welcome! If you have any suggestions or improvements, please create a pull request or open an issue.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for more details.

---

Feel free to add any more specific details or sections that you think are important! If you need further adjustments, just let me know.
