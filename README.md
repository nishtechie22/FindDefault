# Credit Card Fraud Detection
## Overview
This repository contains a project focused on detecting fraudulent credit card transactions using a dataset of transactions made by European cardholders in September 2013. The dataset includes 284,807 transactions, with 492 classified as fraudulent, representing a significant class imbalance.

## Objectives
The primary goal of this project is to develop a classification model that accurately predicts whether a transaction is fraudulent. Key steps include:

1. Exploratory Data Analysis (EDA): Analyze the dataset to identify patterns and trends.

2. Data preprocessing: Handle duplicate, missing values and outliers.

3. Feature Engineering: Create and transform features for improved model performance.

4. Model training and evaluation: Choose the best model for classification. Split the dataset into training and testing sets. Balance the data and evaluate the model's performance on unseen data.

5. Hyperparameter tuning: Find the best hyperparameters using RandomSearchCV. Show the improvements for unseen data. 

## Dataset
The dataset consists of transactions over two days and is highly imbalanced, with fraud cases accounting for only 0.172% of total transactions. This imbalance presents unique challenges for model training and evaluation.

## Getting Started
### Prerequisites
Python 3.10.14
Required libraries (e.g., pandas, numpy, scikit-learn, matplotlib, seaborn)

### Installation
 1. Clone this repository:
    git clone https://github.com/nishtechie22/FindDefault.git
    cd FindDefault
 3. Install the required libraries:
    pip install -r requirements.txt

## Usage
 1. Load the dataset.
 2. Perform EDA to understand the data.
 3. Clean and preprocess the data.
 4. Balance the dataset and train the model.
 5. Tune the hyperparameters.

## Future work
While this project lays a solid foundation for credit card fraud detection, there are several areas for future improvement and exploration:
1. Advanced Models: Experiment with more sophisticated machine learning algorithms such as ensemble methods (e.g., Gradient Boosting) or deep learning techniques (e.g., neural networks) to potentially improve classification performance.
2. Integration with External Data: Incorporate external datasets, such as user behavior or location data, to enrich the model's context and improve prediction accuracy.
3. In this project, hyperparameter tuning improved the model's ability to generalize to unseen data, resulting in better precision and recall metrics. Future work will focus on further refining these hyperparameters and exploring automated tuning methods for even greater performance enhancements.

## Contributing
Contributions are welcome! Please open an issue or submit a pull request to propose changes or improvements.

## License
This project is licensed under the MIT License. See the LICENSE file for details.

## Acknowledgments
* Dataset sourced from (https://kh3-ls-storage.s3.us-east-1.amazonaws.com/DS%20Project%20Guide%20Data%20Set/creditcard.csv)


