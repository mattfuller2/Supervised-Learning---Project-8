# Supervised-Learning---Project-8

# Beta Bank Customer Churn Prediction

### Description
This project is aimed at predicting customer churn for Beta Bank, which has been experiencing a gradual loss of clients. The goal is to develop a machine learning model that can accurately predict whether a customer is likely to leave the bank, helping the bank take preventive measures and retain clients.

### Project Structure
- **notebook.ipynb**: This notebook contains the analysis and model development for predicting customer churn.
- **/datasets/**: Contains the dataset used for training the model.
- **/output/**: Contains the output files such as predictions and model performance metrics.

### Objective
The objective of this project is to build a supervised learning model with the **maximum possible F1 score** to predict customer churn. The model must achieve a minimum F1 score of **0.59**, and the **AUC-ROC** metric is also used to evaluate and compare the model's performance.

### Data Description
The dataset contains various features related to customer behavior, demographic information, and account details. Key columns in the dataset include:
- **CustomerID**: Unique identifier for each customer.
- **Age**: The customer's age.
- **Balance**: The amount in the customer's account.
- **EstimatedSalary**: The customer's estimated salary.
- **Exited**: The target variable indicating whether the customer churned (1) or stayed (0).

### Installation
To run this project locally, follow these steps:

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/beta-bank-churn-prediction.git

2. Install the required dependencies
   pip install -r requirements.txt

