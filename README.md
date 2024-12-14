# SCT_DS_03
# Customer Purchase Prediction Using Decision Tree Classifier

## Project Overview
This project builds a machine learning pipeline to predict customer purchasing behavior for products and services using a Decision Tree Classifier. The solution addresses class imbalance using SMOTE and provides an interactive interface for real-time predictions.

## Key Insights
- *Imbalanced Data Handling*: The dataset was balanced using SMOTE, improving the model's performance for underrepresented classes.
- *Feature Engineering*: A combined target variable (purchase) was created, encoding product, service, and no purchase scenarios.
- *Model Evaluation*: The model achieved an accuracy of 25.33%, evaluated using metrics like precision, recall, and F1-score.
- *Interactive Predictions*: A user-friendly interface predicts customer behavior based on real-time input.

## Technologies Used
- *Programming Language*: Python
- *Libraries*: 
  - Data Manipulation: pandas
  - Machine Learning: sklearn
  - Class Imbalance: imblearn
  
## Dataset
The dataset includes customer demographics, financial details, and campaign responses:
- *Input Features*: Age, job type, marital status, education level, account balance, campaign details, and past outcomes.
- *Target*: Purchase behavior (product, service, or none).

## Code Execution Steps
1. *Data Preprocessing*:
   - Load the dataset and display initial rows.
   - Encode categorical variables using LabelEncoder.
   - Handle class imbalance with SMOTE.
2. *Model Development*:
   - Train a Decision Tree Classifier using resampled data.
3. *Evaluation*:
   - Split the dataset into training and testing subsets (70:30).
   - Evaluate performance using accuracy and classification metrics.
4. *Interactive Predictions*:
   - Implement a function to accept user inputs and predict purchase behavior.

## Visualizations
The analysis focused on:
- Class imbalance representation before and after applying SMOTE.
- Performance metrics visualized using classification reports.

## Conclusions
- The model shows potential for predicting customer purchases but requires further improvements.
- Addressing class imbalance with SMOTE proved crucial for model fairness.
- Future work includes hyperparameter tuning and experimenting with advanced algorithms like Random Forest or XGBoost.

## Code Execution
1. Clone the repository:
   ```bash
   git clone https://github.com/prathvichavan/SCT_DS_03.git 
