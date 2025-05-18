# Final Project – Predicting Power Outages Using Weather Event Data

This project was completed as part of the final assignment for **Course #3253 – Machine Learning** at the **University of Toronto School of Continuing Studies**, within the **Artificial Intelligence Certificate Program**.

## 📊 Objective

The goal of this project is to build a supervised machine learning model capable of predicting power outages based on historical weather event data in the U.S. The model aims to learn patterns in outage occurrences using a combination of weather features, location data, and engineered presence indicators.

---

## 🧱 Project Structure

### 1. 📥 Data Preparation
- Import and analyze the main dataset

### 2. 📈 Exploratory Data Analysis (EDA)
- Frequency analysis of weather events across the U.S.
- Distribution of weather events by year and state
- Total number of customers affected over time
- Top states and weather types by impact
- Correlation analysis between events and outage frequency

### 3. 🔧 Feature Engineering
- Create binary indicators for event presence (`event_presence`)
- Create binary indicators for outage presence (`outage_presence`)
- Match outages and weather events (direct and 3-day lagged overlap)

### 4. 🤖 Model Building
Trained and evaluated several regression models:
- Random Forest Regressor (with learning curve)
- Linear Regression (with and without scaling)
- XGBoost Regressor
- Ridge, Lasso, and Elastic Net Regression
- Support Vector Machines

Each model was evaluated using time-based train/test splits, with a focus on understanding generalization behavior using learning curves and scaled features.
