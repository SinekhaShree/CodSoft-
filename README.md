## Fraudulent Credit Card Transaction Detection
## Overview
This project aims to detect fraudulent credit card transactions using machine learning algorithms. We implemented and compared Logistic Regression and Decision Tree models to classify transactions as fraudulent or legitimate.

## Dataset
The dataset used contains historical credit card transactions with features such as transaction amount, location, and merchant details. The target variable is is_fraud, indicating whether a transaction is fraudulent (1) or not (0).

## Key Features
trans_date_trans_time: Date and time of the transaction.
cc_num: Credit card number.
merchant: Merchant where the transaction occurred.
category: Merchant category.
amt: Transaction amount.
city: City of the transaction.
state: State of the transaction.
lat, long: Latitude and longitude of the transaction.
city_pop: Population of the city.
job: Job of the credit card holder.
dob: Date of birth of the credit card holder.
trans_num: Transaction number.
unix_time: Unix timestamp of the transaction.
merch_lat, merch_long: Latitude and longitude of the merchant.

## Models
Logistic Regression
Decision Tree

## Performance Metrics
## Logistic Regression
Accuracy: 99.60%
Precision: 36.54%
Recall: 4.46%
F1 Score: 7.95%

## Decision Tree
Accuracy: 99.75%
Precision: 68.94%
Recall: 64.08%
F1 Score: 66.42%

## Conclusion
The Decision Tree model outperformed Logistic Regression in detecting fraudulent transactions, exhibiting higher precision, recall, and F1 score. This project demonstrates the potential of machine learning in enhancing fraud detection systems.

## Future Work
Integrate additional features for better prediction.
Explore ensemble methods for improved accuracy.
Continuously update models to adapt to new fraud patterns.

## Installation
## 1)Clone the repository:
git clone https://github.com/yourusername/fraud-detection.git
## 2)Install the required packages:
pip install -r requirements.txt
## 3)Run the Jupyter notebook to see the analysis and model training:
jupyter notebook fraud_detection.ipynb

## License
This project is licensed under the MIT License.


