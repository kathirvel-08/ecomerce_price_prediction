# Ecommerce Price Prediction Based on User Activity

This project demonstrates a **Linear Regression model** to predict the prices of products based on users' spending time on a website and an app. We use an ecommerce dataset and Python libraries like **Pandas**, **Seaborn**, **Matplotlib**, **Scikit-learn**, and **SciPy** for data manipulation, visualization, and model building.

---

## Table of Contents
- [Project Overview](#project-overview)
- [Dataset Description](#dataset-description)
- [Libraries Used](#libraries-used)
- [Steps Involved](#steps-involved)
- [Results](#results)
- [Future Work](#future-work)

---

## Project Overview

The goal of this project is to analyze how time spent on a website and mobile app influences product prices and predict product prices using **Linear Regression**. The insights can help ecommerce businesses optimize their platforms for better pricing strategies.

---

## Dataset Description

The dataset used in this project includes the following columns:
1. **UserID**: Unique identifier for each user.
2. **Time_on_Website**: Time spent on the website (in minutes).
3. **Time_on_App**: Time spent on the mobile app (in minutes).
4. **Length_of_Membership**: Duration of user membership (in years).
5. **Price**: Product price (target variable).

---

## Libraries Used

- **Pandas**: For data manipulation and cleaning.
- **Seaborn**: For creating attractive and informative statistical graphics.
- **Matplotlib**: For data visualization.
- **Scikit-learn**: For building the Linear Regression model.
- **SciPy**: For advanced statistical analysis.

---

## Steps Involved

1. **Data Exploration**:
   - Load and inspect the dataset using Pandas.
   - Analyze data distributions using Seaborn and Matplotlib.

2. **Data Preprocessing**:
   - Handle missing or inconsistent data.
   - Encode categorical data if present.

3. **Visualization**:
   - Explore relationships between variables using scatter plots, pair plots, and heatmaps.

4. **Feature Selection**:
   - Identify the most influential features using correlation analysis.

5. **Model Building**:
   - Split the data into training and testing sets.
   - Train a Linear Regression model using Scikit-learn.

6. **Model Evaluation**:
   - Evaluate the model using metrics like Mean Squared Error (MSE) and R² score.

7. **Inference**:
   - Use the trained model to predict prices based on new user data.

---

## Results

- **Key Findings**:
  - Users spending more time on the mobile app tend to buy higher-priced products.
  - Length of membership has a positive correlation with product price.

- **Model Performance**:
  - R² Score: `XX.XX`
  - MSE: `YY.YY`

---

## Future Work

- Explore nonlinear models for better performance.
- Include additional features like demographics, browsing history, and purchase frequency.
- Deploy the model as a web app using **Flask** or **Streamlit**.

---

## Author

**KATHIRVEL P**  
[LinkedIn](https://www.linkedin.com/in/kathirvel-p-4089a7296?utm_source=share&utm_campaign=share_via&utm_content=profile&utm_medium=android_app)  
Email: kathirvel15082k@gmail.com

---
