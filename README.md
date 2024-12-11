# Abalone Age Prediction Usinf Machine Learning

## 1. Introduction

### Overview
The **Abalone Age Prediction** project aims to predict the age of abalones using physical and biological features, leveraging machine learning techniques to create accurate and interpretable models. The project addresses key challenges such as multicollinearity, heteroscedasticity, and influential data points. By implementing multiple linear regression and decision tree models, we explore data-driven approaches to automate age prediction, which traditionally requires time-consuming manual methods.

### Importance
Accurate age prediction is crucial for marine biologists and fisheries. Sustainable harvesting and conservation efforts depend on understanding the age distribution of abalone populations. This project contributes to the sustainable management of marine resources by automating age prediction.

---

## 2. Dataset Description

### Source
The dataset is obtained from the **UCI Machine Learning Repository**, containing **4,177 observations** and **9 features**.

### Features
- **Sex**: Categorical (F = Female, M = Male, I = Infant).
- **Length**: Continuous, longest shell measurement (in mm).
- **Diameter**: Continuous, perpendicular to length (in mm).
- **Height**: Continuous, shell height (in mm).
- **Whole_weight**: Continuous, whole abalone weight (in grams).
- **Shucked_weight**: Continuous, weight of meat (in grams).
- **Viscera_weight**: Continuous, gut weight after bleeding (in grams).
- **Shell_weight**: Continuous, shell weight after drying (in grams).
- **Rings**: Integer, number of shell rings (used to calculate age as `Age = Rings + 1.5`).
