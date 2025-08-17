# **Bank Marketing Campaign Response Prediction**

This project predicts customer responses to a bank marketing campaign using classification models on a dataset of 45,211 records.

## **Project Overview**
- **Objective**: Identify customers likely to respond to a campaign using demographic and account data.
- **Dataset**: Contains features like age, job, marital status, education, balance, and campaign details.

## **Methodology**
- **EDA**: Conducted ANOVA and Chi-Square tests to identify key predictors (e.g., duration, balance) for campaign response.
- **Preprocessing**: Applied scaling, encoding (categorical variables), and outlier handling for robust data preparation.
- **Models**: Built and evaluated classification models, including XGBoost, for response prediction.

## **Results**
- **XGBoost Performance**: Achieved 91.4% test accuracy and 0.92 ROC-AUC, outperforming other models.
- **Key Metrics**: High precision and recall, with duration and previous contact as top predictors.

## **Recommendations**
- Deploy XGBoost for accurate campaign response prediction.
- Focus marketing on high-duration contacts and customers with prior engagement.
