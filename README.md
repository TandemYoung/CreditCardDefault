# Credit Card Default Prediction Tool

## Introduction
This project is developed to analyze and predict credit card defaults based on historical data from Taiwan during a significant financial crisis in 2006. The dataset used reflects the behavior of credit card holders and their repayment patterns amidst the cash and credit card debt challenges of that time.

## Purpose of the Tool
The primary goal of this tool is to provide financial institutions with insights into potential default risks by analyzing past credit card usage and repayment data. By understanding these patterns, banks can devise better strategies to mitigate risks associated with credit issuance.

## Dataset Overview
The dataset comprises several attributes related to repayment status, bill amounts, and payment amounts over six consecutive months in 2005. It includes:
- **Repayment Status:** Indicates whether payments were made on time or delayed for each month.
- **Bill Amount:** Monthly statement amounts for each credit card account.
- **Payment Amount:** How much was paid back each month by the cardholder.

## Features of the Tool
- **Data Cleaning:** Processes raw data to handle missing values and anomalies, making it suitable for analysis.
- **Data Visualization:** Generates charts and graphs to depict trends and patterns in the data.
- **Predictive Modeling:** Uses machine learning algorithms to predict the likelihood of default based on historical data.

## Installation and Setup
### Prerequisites
You need Python 3.6+ installed along with several libraries which include `pandas`, `numpy`, `matplotlib`, and `sklearn`. You can install these using pip:

pip install pandas numpy matplotlib sklearn

### Getting Started
- Clone this repository or download the project files to your local machine.
- Install the required Python libraries mentioned above.
- Ensure the dataset file is placed in the designated project directory or adjust the dataset path in the script accordingly.

## Usage
To run the analysis, navigate to the project directory and execute the main script:

python final_code.ipynb

This script will perform data cleaning, visualization, and predictive modeling automatically.

## Predictive Modeling Techniques
The tool applies a variety of machine learning algorithms to predict the likelihood of credit card defaults based on historical financial behaviors of cardholders. These algorithms include:

### Logistic Regression
This model calculates the probability of a binary outcome (default or no default) based on input features like bill amounts and repayment statuses. It is valued for its simplicity and the interpretive insights it offers into the influence of various predictors.

### Decision Trees
A non-linear model that represents decisions and their possible consequences as branches of a tree. Decision trees are intuitive and easy to visualize but can be sensitive to small data variations, leading to overfitting.

### Random Forest
An ensemble technique that creates multiple decision trees and integrates them to improve prediction accuracy and robustness. Random Forests help to mitigate the overfitting problem of individual decision trees and are effective for large datasets with many input variables.

### Gradient Boosting Machines (GBM)
GBM builds trees one at a time, where each new tree helps to correct errors made by previously trained trees. This technique is known for its high effectiveness in predictive accuracy, especially in complex datasets prone to overfitting.

### Support Vector Machines (SVM)
SVMs are particularly adept at classifying complex but small- or medium-sized datasets. They work by finding the best margin (distance between the line and the support vectors) that separates classes, enhancing the generalization abilities of the model.

## Considerations and Best Practices
- **Handling Imbalanced Data:** Techniques such as Synthetic Minority Over-sampling Technique (SMOTE) are used to balance the dataset, which typically has fewer instances of defaults than non-defaults.
- **Feature Engineering:** Critical to enhancing model performance, involving the creation of meaningful variables from raw data.
- **Hyperparameter Tuning:** Essential for optimizing model performance, involving adjustments to parameters that control the learning process.

## Contact
For further information or support, contact Tandem Young at [tyoung@walton.uark.edu](mailto:tyoung@walton.uark.edu).
