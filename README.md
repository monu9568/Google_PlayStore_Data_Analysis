# 📊 Google Play Store Data Analysis

## 🧠 Project Overview
This project presents a complete **end-to-end data analysis** of the Google Play Store dataset.  
It combines **Python (EDA, preprocessing, and model building)** with **Power BI visualization** to explore and analyze patterns in app ratings, installs, categories, and pricing strategies.

The goal of this project is to identify key factors that influence app success — such as reviews, app size, installs, and price — and to visualize the findings through an interactive dashboard.

---

## 🚀 Key Objectives
- Clean and preprocess raw Play Store data.
- Perform **Exploratory Data Analysis (EDA)** to uncover patterns and insights.
- Identify factors affecting app **ratings and installs**.
- Build a **Random Forest Regression model** to predict app ratings.
- Create a **Power BI Dashboard** for visual storytelling and insights.

---

## 🧹 Data Preprocessing
Performed in Python using **pandas** and **NumPy**:
- Removed duplicates and irrelevant records.
- Handled missing values strategically.
- Cleaned and standardized text features like `App`, `Category`, `Type`, `Genres`.
- Converted data types (`Reviews`, `Installs`, `Price`, `Size`) to numeric.
- Encoded categorical variables for machine learning.

---

## 📈 Exploratory Data Analysis (EDA)
Explored relationships between key features such as:
- **Category vs Installs**
- **Free vs Paid apps and their Ratings**
- **App Size vs Rating**
- **Price vs Rating**
- **Installs vs Rating**

Key observations:
- Most apps have ratings between **4.0 and 4.7**.
- **Free apps dominate** the store, but **paid apps** show slightly higher ratings.
- **Smaller-sized apps (under 10 MB)** are more common.
- Top categories include **Game, Communication, Tools, Productivity, and Social**.

---

## 🤖 Machine Learning Model
Used **Random Forest Regressor** to predict app ratings.

### Features used:
- `Reviews`
- `Size`
- `Installs`
- `Type` (Free/Paid)
- `Category`

### Model Results:
- **R² Score:** 0.12  
- **MAE:** 0.35  
- **RMSE:** 0.51  

> Interpretation: The model shows limited predictive power due to data imbalance and high variability in app behavior — which is expected for real-world data.

---

## 📊 Power BI Dashboard

A fully interactive **Power BI Dashboard** was created to visualize insights.  

### Dashboard Features:
- **Category-wise total installs**
- **Average rating comparison (Free vs Paid)**
- **Price vs Rating trends**
- **Category-wise app distribution**
- **Dynamic slicers** for Category, Type, and Rating filters

### Dashboard Preview:<img width="1061" height="598" alt="Playstore Apps Dashboard" src="https://github.com/user-attachments/assets/a6874be2-5e25-4a5a-b65b-4c8a1b1e26eb" />



---

## 🗂️ Project Structure

