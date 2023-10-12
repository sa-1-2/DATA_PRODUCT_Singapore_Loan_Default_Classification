# Singapore_Bank_Credit_Default_Classification

This project focuses on predicting defaulters for a Singapore-based bank's loan applications using machine learning classification models. The goal is to provide valuable insights to the bank for better decision-making and risk assessment.

## Table of Contents

- [Introduction](#introduction)
- [Project Overview](#project-overview)
- [Key Metrics](#key-metrics)
- [Project Structure](#project-structure)
- [Dataset](#dataset)
- [Model Development](#model-development)
- [Visualization and Dashboard](#visualization-and-dashboard)
- [Contributing](#contributing)
- [License](#license)
- [Contact](#contact)

## Introduction

In this project, we aimed to develop a classification model to predict loan defaulters for a Singapore bank based on a given dataset. The predictive models were built by following a structured approach involving exploratory data analysis (EDA), feature engineering, and model training using various splits of the dataset.

## Project Overview

- **Exploratory Data Analysis (EDA)**: Conducted detailed exploratory data analysis to understand the dataset's characteristics, distributions, and relationships between features.

- **Feature Engineering**: Engineered features to enhance the predictive power of the models and prepare the dataset for model training.

- **Model Training**: Utilized a machine learning classification approach with three different data splits (test splits of 0.2, 0.25, and 0.3) to develop models. The models were evaluated based on F1 score and balanced accuracy.

- **Prediction and Visualization**: Performed predictions on a separate dataset, concatenated the predictions with the original dataset, and utilized the actual test dataset for visualization using Power BI to create a dashboard.

## Key Metrics

- **Balanced Accuracy**: 73%
- **AUC Score**: 0.73
- **F1 Score**: 0.62

These metrics were chosen as the primary evaluation criteria to assess the model's performance.

## Project Structure

The project is structured as follows:

- `Datasets/`: Contains the dataset used for training and testing.
- `Model/`: Jupyter notebooks for exploratory data analysis, feature engineering, and model development & finalized model.
- `Power BI/`: Visualizations generated for the project.

## Dataset

The dataset used for this project contains information about loan applicants and whether they defaulted on their loans.

## Model Development

The models were developed using a classification approach, and the best model achieved a balanced accuracy of 73% and an F1 score of 0.62. Three different splits were used for training and testing.

## Visualization and Dashboard

We utilized the actual test dataset, predictions, and other insights to create an informative dashboard using Power BI. The dashboard provides an overview of loan default predictions, helping stakeholders make informed decisions.

![Singapore Credit Data visualization(LR)](https://github.com/sa-1-2/Singapore_loan_default_classification/assets/92681055/5c023a30-95dd-4267-a1c7-0f349a18a6e7)


## Contributing
Contributions to this project are welcome. If you find any issues or have suggestions for improvements, please feel free to create an issue or submit a pull request.

## License
This project is licensed under the MIT License.

## Contact
For any inquiries or further information regarding this project, please contact sanchitsingla1403@gmail.com
