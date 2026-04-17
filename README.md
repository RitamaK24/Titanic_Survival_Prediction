# Titanic Survival Analysis & Prediction

## Project Overview
This project performs data analysis, visualization, and machine learning on the Titanic dataset to understand survival patterns and predict whether a passenger survived or not.

### The workflow includes:
1. Data collection
2. Data cleaning and preprocessing
3. Exploratory Data Analysis (EDA)
4. Feature engineering
5. Data visualization
6. Building a Logistic Regression model for prediction

## Dataset
The dataset used is the Titanic Dataset, which contains information about passengers such as:
1. Age
2. Gender
3. Ticket class (pclass)
4. Fare
5. Family members (sibsp, parch)
6. Embarkation details
7. Survival status

## Technologies Used
Python
NumPy
Pandas
Matplotlib
Seaborn
Scikit-learn

## Data Visualization
The project includes multiple visualizations:
📌 Bar chart → Survival percentage
📌 Bar plot → Survival by gender
📌 Box plot → Fare distribution by class
📌 Histogram → Age distribution
📌 Histogram with hue → Age vs survival
📌 Pie chart → Survival ratio
📌 Scatter plot → Age vs Fare
📌 Heatmap → Confusion matrix

## Machine Learning Model
### Model Used:
#### Logistic Regression

##### Steps:
Split dataset into training and testing sets (80/20)
Trained model using LogisticRegression
Predicted survival on test data

## Results
### Key Insights:
Females had a significantly higher survival rate than males
First-class passengers paid higher fares and had better survival chances
Younger passengers and children had better survival trends
Family size had some influence on survival probability

### Model Performance:
##### Accuracy: ~80.48%
This indicates that the model performs reasonably well in predicting survival based on given features.

### Output Files
Cleaned Dataset.csv → Processed dataset after cleaning and feature engineering

## Conclusion

This project demonstrates how data analysis and machine learning can be applied to real-world datasets to extract insights and build predictive models.
It highlights the importance of:
1. Data preprocessing
2. Data Visualization
3. Feature engineering
4. Model evaluation
