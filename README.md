# 📊 Olist E-Commerce Data Analytics

A comprehensive end-to-end Data Analytics project built using **Python** and **Machine Learning** on the Brazilian Olist E-Commerce dataset.

This project demonstrates the entire analytics workflow—from data cleaning and preprocessing to exploratory data analysis, feature engineering, RFM segmentation, cohort analysis, and predictive modeling.

---

## 🚀 Project Overview

The goal of this project is to analyze Olist's e-commerce data and uncover valuable business insights such as:

- 📦 Order Performance & Fulfillment
- 💰 Sales & Revenue Analysis
- 👥 Customer Behavior & Retention (RFM & Cohorts)
- ⭐ Review & Customer Satisfaction Drivers
- 🚚 Delivery Performance & Delay Analysis
- 📍 Regional & Geographic Sales Distribution
- 🤖 Predictive Modeling using Machine Learning

---

## 📂 Project Structure

```
├── data/
│   ├── olist_customers_dataset.csv
│   ├── olist_orders_dataset.csv
│   ├── olist_order_items_dataset.csv
│   ├── olist_order_payments_dataset.csv
│   ├── olist_order_reviews_dataset.csv
│   ├── olist_products_dataset.csv
│   ├── olist_sellers_dataset.csv
│   ├── olist_geolocation_dataset.csv
│   └── product_category_name_translation.csv
│
├── notebooks/
│   └── olist_analysis.ipynb
│
├── README.md
└── requirements.txt
```

---

## 📈 Key Analytics & Metrics Covered

- **Revenue Metrics**: Total Revenue, Average Order Value (AOV), Monthly Revenue Trends
- **Customer Metrics**: Unique Customers, Repeat Purchase Rate, Customer Retention Rate
- **Customer Segmentation**: RFM Analysis (Recency, Frequency, Monetary)
- **Cohort Analysis**: Tracking monthly customer acquisition and retention
- **Operational Metrics**: Delivery Delays, Estimated vs. Actual Delivery Time
- **Customer Satisfaction**: Review score distributions and correlation with delivery performance
- **Funnel Analysis**: Order status progression across lifecycle stages

---

## 🛠️ Technologies Used

- **Python**
- **Pandas** & **NumPy** for data manipulation and feature engineering
- **Matplotlib** & **Seaborn** for exploratory data visualization
- **Missingno** for missing data analysis
- **Scikit-learn** for machine learning workflows
- **Jupyter Notebook**

---

## 🤖 Machine Learning

The project includes predictive modeling (Decision Tree) to evaluate order outcomes and customer experience drivers.

### Workflow

- Data Cleaning & Missing Value Imputation
- Feature Engineering (Delivery Delay, Total Price, Order Timing)
- Categorical Encoding
- Train-Test Split
- Decision Tree Classifier / Regressor
- Model Evaluation (Accuracy, Classification Report, Confusion Matrix)

---

## 📉 Exploratory Data Analysis (EDA)

Performed detailed analysis on:

- Customer Distribution by State & City
- Top & Bottom Performing Product Categories
- Payment Method Distribution & Installment Patterns
- Order Status Breakdown
- Monthly Revenue Growth & Trends
- Delivery Time Variance across Brazilian Regions
- Review Scores and Impact of Late Delivery
- Seller Performance & Contribution

---

## ⚙️ Installation & Usage

1. **Clone the repository:**
   ```bash
   git clone https://github.com/yourusername/olist-ecommerce-analytics.git
   ```

2. **Move into the project folder:**
   ```bash
   cd olist-ecommerce-analytics
   ```

3. **Install dependencies:**
   ```bash
   pip install -r requirements.txt
   ```

4. **Launch Jupyter Notebook:**
   ```bash
   jupyter notebook notebooks/olist_analysis.ipynb
   ```

---

## 📁 Dataset

Dataset used: **Brazilian E-Commerce Public Dataset by Olist**

Relational tables included:
- Customers
- Orders
- Order Items
- Order Payments
- Order Reviews
- Products
- Sellers
- Geolocation
- Category Name Translation

---

## 🎯 Business Insights & Recommendations

- **Delivery Delays**: Significant negative correlation between delivery delay and review scores; delays are heavily concentrated in specific logistics routes.
- **Pareto Revenue Concentration**: High-value product categories and repeat buyers contribute disproportionately to total revenue.
- **Retention Strategy**: Targeted retention programs are recommended for high-scoring RFM segments to improve customer lifetime value.

---

## 📌 Future Improvements

- Sales forecasting using time-series models (ARIMA / Prophet)
- Advanced customer segmentation with K-Means clustering
- Product recommendation engine
- Deep learning / NLP models for review comment sentiment analysis

---

## 👨‍💻 Author

**Md Yasar**


---

## ⭐ If you like this project

Please consider giving it a ⭐ on GitHub!
