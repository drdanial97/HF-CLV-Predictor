# Customer Lifetime Value (CLV) Prediction for HelloFresh

## **Project Overview**

HelloFresh operates a subscription-based meal kit service, where **understanding customer behavior is key** to driving retention, personalization, and revenue growth. This project demonstrates how **Machine Learning (ML) can predict CLV**, helping businesses make **data-driven marketing and product decisions**.

## **Business Objective**

The goal of this project is to:

- Forecast **Customer Lifetime Value (CLV)** to identify high-value customers.
- Understand key factors influencing **customer retention & engagement**.
- Optimize **personalization & targeted marketing** using ML predictions.

## **Dataset**

The dataset contains **100,000 customer records** with:

- **Demographics** (Age, Household Size, Location)
- **Purchase Behavior** (Order Frequency, Total Orders, Avg Order Value)
- **Subscription Data** (Subscription Length, Pauses, Cancellations)
- **Marketing Engagement** (Email Open Rate, Click-Through Rate)
- **Customer Support Interactions**

## **Methodology**

1. **Exploratory Data Analysis (EDA)** – Understanding key trends in customer behavior.
2. **Feature Engineering** – Creating meaningful predictors of CLV.
3. **Model Selection & Training** – Using **RandomForest, XGBoost** to predict CLV.
4. **Model Evaluation** – Using **Mean Absolute Error (MAE), R² score** to measure accuracy.

## **Key Insights & Business Impact**

- **Order frequency & subscription length are top predictors** of CLV.
- Customers with **high email engagement & lower pauses** tend to stay longer.
- **Marketing efforts can be optimized** by targeting customers with high CLV scores.

## **Next Steps**

- **Enhancing Personalization** – Using CLV scores to suggest **tailored meal plans**.
- **Churn Prevention** – Identifying customers at risk of canceling.
- **Dynamic Pricing Models** – Adjusting discounts based on predicted CLV.

## **How to Use This Project**

1. Run `clv_prediction.ipynb` to **train and test the model**.
2. Explore the **CLV analysis report** (`CLV Analysis.pdf`).
3. Use `CLV Prediction Features Presentation.pptx` for business discussions.

---
