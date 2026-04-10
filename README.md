# ARTI-308-lab6
# Ecommerce Customer Analysis - Linear Regression

This project utilizes **Linear Regression** to analyze customer data for an Ecommerce company. The goal is to provide a data-driven recommendation on whether the company should focus their development efforts on their **Mobile App** or their **Website**.

## Project Overview
The dataset contains information on customer behavior, including average session length, time spent on the app, time on the website, and the duration of their membership. We aim to predict the **Yearly Amount Spent** and determine which factors most significantly influence customer expenditure.

## Tech Stack
* **Language:** Python
* **Libraries:** * `pandas` for data manipulation
    * `numpy` for numerical analysis
    * `seaborn` & `matplotlib` for data visualization
    * `scikit-learn` for machine learning and model evaluation

## Key Findings
Based on the Linear Regression model, the following coefficients were observed:
* **Time on App:** ~38.59
* **Time on Website:** ~0.19
* **Length of Membership:** ~61.28

### Conclusion:
The model indicates that **Length of Membership** is the strongest predictor of spending. However, comparing the digital platforms, the **Mobile App** has a much higher correlation with revenue than the Website. 

**Recommendation:** The company should focus on enhancing the Mobile App experience and developing loyalty programs to increase membership length.

## Model Performance
The model was evaluated using standard regression metrics:
* **MAE:** ~7.23
* **MSE:** ~79.81
* **RMSE:** ~8.93 (Off by roughly $9 on average)
