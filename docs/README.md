# Predictive Analysis on Advertisement Clicks

## Objective
The primary goal of this project is to leverage machine learning algorithms to predict whether a user will click on an advertisement based on various user features. By analyzing the advertising data of a marketing agency, we aim to help companies target their advertisements more effectively, reducing costs and increasing ROI.

## Concepts Used
- **Exploratory Data Analysis (EDA)**: Conducted thorough analysis to understand the distribution and relationships among variables.
- **Data Preprocessing**: Handled categorical variables and split the data into training and testing sets.
- **Machine Learning**: Implemented and evaluated Logistic Regression and Decision Tree models to predict advertisement clicks.

## Tools Used
- **Python**: The project was entirely scripted in Python.
- **Pandas**: Used for data manipulation and analysis.
- **NumPy**: Employed for numerical computations.
- **Matplotlib & Seaborn**: Utilized for data visualization.

## Dataset
The dataset comprises 10 variables: Daily Time Spent on Site, Age, Area Income, Daily Internet Usage, Ad Topic Line, City, Male, Country, Timestamp, and Clicked on Ad. The primary variable of interest is 'Clicked on Ad', which is binary. The dataset is well-structured with no missing values, making it a robust foundation for building predictive models.

## Analysis and Insights
- The data revealed a normal distribution for the Age variable, which is beneficial for effective data processing.
- Younger users (age 20-40) tend to spend more time on the site, making them a prime target for advertising campaigns.
- A positive correlation was observed between Daily Time Spent on Site and Daily Internet Usage.
- The scatter matrix provided insights into the characteristics of users who are more likely to click on advertisements.

## Data Preprocessing
- Omitted 'Ad Topic Line' and 'City' columns due to high cardinality.
- Identified 'Country' as a potential categorical feature for analysis.

## Model Development and Evaluation
- Divided the dataset into training (67%) and testing (33%) sets.
- Implemented Logistic Regression and Decision Tree models.
- The Decision Tree model exhibited slightly better performance, showcasing the potential of machine learning in solving classification problems in marketing analytics.

## Conclusion
This project demonstrates the potential of machine learning in enhancing online advertising strategies. Both Logistic Regression and Decision Tree models proved to be effective in predicting user clicks on advertisements. However, there's room for improvement by exploring different data analysis approaches, feature engineering, and experimenting with other machine learning models.
