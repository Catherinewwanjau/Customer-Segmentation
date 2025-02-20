# Customer Segmentation Using Machine Learning

# Overview
This project focuses on customer segmentation using machine learning techniques. Businesses can use customer segmentation to tailor marketing strategies, enhance customer experience, and optimize resource allocation. The model classifies customers based on key demographic and behavioral features, providing data-driven insights for better decision-making.

# Dataset

The dataset contains customer attributes such as:
* Gender
* Ever Married
* Age
* Graduate
* Profession
* Work Experience
* Spending Score
* Family Size
* Segmentation (Target Variable: A, B, C, D)

# Project Workflow

1. Data Preprocessing
* Handling missing values
* Encoding categorical variables
* Normalizing numerical features
* Merging train and test datasets for consistency
* 
2. Exploratory Data Analysis (EDA)
* Visualizing data distributions
* Analyzing feature correlations
* Identifying patterns in customer behavior

3. Model Development
* Trained and evaluated multiple classification models:
* Decision Tree Classifier
* Random Forest Classifier
* Gradient Boosting Classifier
* Neural Network
 
4. Model Evaluation
* Confusion Matrix: Analyzing correct and incorrect predictions
* Classification Report: Precision, Recall, and F1-score evaluation
* Feature Importance Analysis: Identifying key features affecting customer segmentation
* Hyperparameter Tuning: Optimizing model performance using GridSearchCV

# Key Findings
* Spending score, age, and profession significantly influence customer segmentation.
* The Gradient Boosting model achieved the best accuracy of 48.6%, indicating room for improvement with additional feature engineering.
* Segment D had the highest recall (67%), while segment B was the most challenging to classify correctly.

# Recommendations
* Businesses should develop targeted marketing strategies based on customer segments.
* Further data collection, including purchasing history and online engagement, can improve segmentation accuracy.
* Deploying the model within a CRM system can provide real-time insights for decision-making.

# Technologies Used
* Python
* Pandas, NumPy (Data Processing)
* Matplotlib, Seaborn (Data Visualization)
* Scikit-learn (Machine Learning Models)

# Future Improvements
* Incorporating deep learning techniques
* Experimenting with clustering algorithms such as K-Means
* Enhancing feature engineering with real-time customer data


