# Credit Card Fraud Detection using Machine Learning

## Table of Contents

- [Introduction](#introduction)
- [Features](#features)
- [Dataset](#dataset)
- [Installation](#installation)
- [Usage](#usage)
- [Model Training](#model-training)
- [Evaluation](#evaluation)
- [Results](#results)
- [Contributing](#contributing)
- [License](#license)
- [Acknowledgments](#acknowledgments)

## Introduction

Credit card fraud is a significant problem in the financial industry, causing substantial financial losses. This project aims to build a machine learning model to detect fraudulent credit card transactions. The model will help in identifying suspicious transactions and preventing fraud.

## Features

- Data preprocessing and feature engineering
- Machine learning algorithms for fraud detection
- Model evaluation and performance metrics
- Visualization of results
- Easy-to-use interface for making predictions

## Dataset

The dataset used for this project is the [Credit Card Fraud Detection dataset]((https://www.kaggle.com/datasets/kartik2112/fraud-detection)) from Kaggle. It contains  simulated credit card transaction dataset containing legitimate and fraud transactions from the duration 1st Jan 2019 - 31st Dec 2020. It covers credit cards of 1000 customers doing transactions with a pool of 800 merchants
To run this project, you need to have Python installed on your system. You can install the required packages using the following command:

```bash
pip install -r requirements.txt
```

## Usage

1. Clone this repository:

```bash
git clone https://github.com/your-Keeistu-Offical/CODSOFT.git
cd CODSOFT
```

2. Install the dependencies:

```bash
pip install -r requirements.txt
```

3. Run the Jupyter notebook to see the data preprocessing, model training, and evaluation:

```bash
jupyter notebook CREDIT_CARD_FRAUD_MODEL.ipynb
```

4. To make predictions on new data, use the `predict.py` script:

```bash
python predict.py --input-file path/to/input.csv --output-file path/to/output.csv
```

## Model Training

The following machine learning algorithms have been used for training the model:

- Decision Tree
- Logistic Regression

The training process involves:

1. Data preprocessing: Handling missing values, scaling features, and addressing class imbalance using techniques such as SMOTE.
2. Feature selection: Identifying the most relevant features for the model.
3. Model training: Training the Decision Tree and Logistic Regression models, and tuning hyperparameters using cross-validation.

## Evaluation

The models are evaluated based on the following metrics:

- Accuracy
- Precision
- Recall
- F1 Score
- Area Under the ROC Curve (AUC-ROC)

## Results

The performance of the models on the test set are as follows:

### Decision Tree
- Accuracy: 99.92%
- Precision: 87.50%
- Recall: 70.00%
- F1 Score: 77.78%
- AUC-ROC: 0.997

### Logistic Regression
- Accuracy: 99.93%
- Precision: 90.00%
- Recall: 75.00%
- F1 Score: 81.82%
- AUC-ROC: 0.998

## Contributing

Contributions are welcome! Please fork the repository and create a pull request with your changes. Make sure to follow the coding standards and include appropriate tests.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Acknowledgments

- The dataset used in this project is provided by [Kaggle](https://www.kaggle.com/datasets/kartik2112/fraud-detection).
- Special thanks to the machine learning community for providing valuable resources and support.

