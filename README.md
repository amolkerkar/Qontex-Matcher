# Question Pair Intent Analysis

### This repository is for the project - "Question Pair Intent Analysis" 
The script uses machine learning techniques, feature engineering, and text analysis to predict whether pairs of questions are semantically similar or not

## Features
- Data Loading and Exploration: Uploads and explores a CSV file containing question pairs.
- Data Preprocessing: Cleans and preprocesses text data for analysis.
- Feature Engineering: Creates various features, including length-based, token-based, and fuzzy features.
- Data Visualization: Utilizes seaborn to create pair plots for visualizing feature relationships.
- Machine Learning Model: Trains a machine learning model (Random Forest and XGBoost) for predicting duplicate questions.
- Dimensionality Reduction and Visualization: Applies t-SNE for dimensionality reduction and visualizes the results in 2D and 3D.
- Text Vectorization and Model Training: Converts text data into numerical features and trains models on the engineered features.
- Model Deployment: Saves the trained model and CountVectorizer for future use.
- Example Queries: Demonstrates how to use the deployed model for real-time predictions.

## Usage
1. Upload the `train.csv` file containing question pairs.
2. Execute the script, following the provided instructions.
3. Explore the data, preprocess text, engineer features, and train machine learning models.
4. Save the trained model (`model.pkl`) and CountVectorizer (`cv.pkl`) for future use.
5. Utilize the provided example query to predict whether a new pair of questions are duplicates.

## Requirements
- Python 3 and above
- Libraries: numpy, pandas, seaborn, matplotlib, re, BeautifulSoup, warnings, google.colab, fuzzywuzzy, distance, nltk, sklearn, xgboost, plotly

## Output:
![image](https://github.com/amolkerkar/Question_pair_intent_analysis/assets/81116875/9b6faf90-668c-4c03-940e-2fd5ed20c35b)

