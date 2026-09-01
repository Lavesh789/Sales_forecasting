#Sales Forecasting & Business Insights Dashboard

An end-to-end Machine Learning web application designed to forecast product demand (units sold) and estimated revenue using transactional, seasonal, and marketing dataset features. The application packages predictions into actionable business insights for supply chain and inventory optimization.


#Project Overview

Accurate sales forecasting is critical for optimizing inventory management, preventing stockouts, and maximizing revenue. This project analyzes a dynamic dataset containing 3,000 sales records and 27 feature columns to predict sales volume. 

The finalized Machine Learning model is deployed as an interactive web dashboard via **Streamlit**, allowing stakeholders to simulate pricing strategies, seasonal shifts, and marketing expenditures in real time.

#Key Features

* Exploratory Data Analysis (EDA): Insights into pricing dynamics, seasonality trends, regional store performance, and promotional impacts.
* Feature Engineering: Extraction of date features (`Year`, `Month`, `Day`, `Day_of_Week`, `Is_Weekend`), encoding of categorical variables, and numerical scaling.
* Multiple Regression Models: Evaluated baseline models (Linear Regression, Ridge/Lasso) and ensemble methods (Random Forest, XGBoost).
* Interactive UI: Dynamic Streamlit dashboard with custom feature inputs (Price, Discount, Competitor Pricing, Marketing Spend, Season, Location).
* Supply Chain Decision-Making: Automated generation of safety stock buffers (15%), pricing sensitivity simulations, and revenue projections.

#Pipeline & Modeling Workflow

* Data Preprocessing & Cleaning
* Feature Encoding & Scaling
* Model Training & Evaluation
