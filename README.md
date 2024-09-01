# Titanic-Passenger-Survival-Prediction

## **Objective**
The goal of this challenge is to predict the survival of Titanic passengers based on various features such as name, age, ticket price, etc. This is a binary classification problem where the task is to classify each passenger as either surviving (1) or not surviving (0).

## **WorkFlow**

**1 - Problem Definition  :** 
The challenge involves predicting the survival of passengers on the Titanic. The target variable, "Survived," indicates whether a passenger survived (1) or did not survive (0).

**2 - Data Wrangling, Preparation and Cleansing  :**
The data preprocessing steps include handling missing values, encoding categorical variables, and feature scaling. For detailed code, please check my Kaggle and GitHub repositories.

**3 - Exploratory Data Analysis  :**
  **Survival Rate:** In the training set, only 350 out of 891 passengers (38.4%) survived.<br>
  **Sex:** There were more men than women on the ship, but women had a significantly higher survival rate. Approximately 75% of women survived, compared to around 19% of men.<br>
  **Pclass:** Passengers in Pclass 1 had the highest survival rate. Survival rates were approximately 63% for Pclass 1, 48% for Pclass 2, and 25% for Pclass 3.<br>
  **Combined Analysis:** Survival rates varied significantly based on the combination of sex and class. For instance, women in upper-class (Pclass 1) had a survival rate of about 95-96%, whereas lower-class women had a higher survival rate compared to upper-class men.<br>
  **Feature Correlations:** <br>
    **~ Sex:** Positive correlation with survival (Pearson’s coefficient of 0.54). <br>
    **~ Pclass:** Negative correlation with survival (Pearson’s coefficient of -0.34). <br>
