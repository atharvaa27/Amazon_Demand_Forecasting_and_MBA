# Real-Time Customer-Centric Supply Chain Optimization 🚀

This project leverages **Market Basket Analysis (MBA)** and **Demand Forecasting** to optimize supply chain management for Amazon products. The goal is to **predict future product demand** and **identify frequently bought-together items**, improving stock efficiency and cross-selling strategies to enhance customer satisfaction.

---

## 🚀 Key Features

### 📊 Demand Forecasting
- **Time-Series Sales Prediction**: Forecast product demand using historical sales data.
- **Seasonality & Trend Detection**: Identify demand fluctuations (e.g., holiday sales spikes).
- **Multi-Factor Demand Analysis**: Incorporates pricing, promotions, reviews, and ratings into forecasting.
- **Real-Time Demand Updates**: Uses Firebase for live demand tracking and updates.
- **AI-Based Stock Replenishment Alerts**: Notifies when stock levels are low based on predicted demand.

### 🛒 Market Basket Analysis
- **Frequent Itemset Mining (Apriori/FP-Growth)**: Finds commonly bought-together products.
- **Product Affinity Analysis**: Suggests complementary items for cross-selling strategies.
- **Personalized Product Bundling**: Recommends dynamic product combinations based on past purchases.
- **Dynamic Pricing for Bundles**: Adjusts discounts based on frequently bought-together patterns.

### 📊 Data Visualization & Insights
- **Interactive Tableau Dashboards**: Visualize demand trends, sales forecasts, and purchase patterns.
- **Real-Time Analytics Dashboard**: Built with Plotly/Dash to monitor stock, sales, and recommendations.
- **Customer Purchase Behavior Segmentation**: Clusters customers based on buying habits for targeted marketing.

---

## 🛠️ Technical Features
- **Backend API for Predictions**: Flask/FastAPI-based API to integrate forecasting and recommendations.
- **Machine Learning Models**: Implements XGBoost, LSTM, and Prophet for demand forecasting.
- **Scalable Cloud Storage**: Firebase/PostgreSQL to manage product and sales data.
- **Automated Model Retraining**: Dynamically adapts forecasting models to new sales data.
- **Streamlit Dashboards**: For user-friendly, interactive data visualization.

---

## Tech Stack

| **Category**          | **Technologies**                                                        |
|------------------------|------------------------------------------------------------------------|
| **Data Science**       | Python (Pandas, NumPy, Scikit-learn, TensorFlow, XGBoost)             |
| **Cloud Computing**    | Google Colab for model training                                       |
| **Database**           | Firebase, MySQL/PostgreSQL                                            |
| **Frontend Dashboard** | Streamlit for interactive dashboards                                  |
| **Data Visualization** | Tableau Public, Plotly/Dash                                           |
| **Experiment Tracking**| Mlflow for model training experiments                                 |

---

## 📥 Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/atharvaa27/Amazon_Demand_Forecasting_and_MBA.git

2. Navigate to the project directory:
   ```bash
   cd Amazon_Demand_Forecasting_and_MBA
3. Install dependencies:
   ```bash
   pip install -r requirements.txt

---
   
## 📊 Dataset
### Sources:
1. **[Instacart Market Basket Dataset](https://www.kaggle.com/c/instacart-market-basket-analysis)**  
   - Includes over 3 million grocery orders for market basket analysis.
   
2. **[Amazon Customer Reviews Dataset](https://registry.opendata.aws/amazon-reviews/)**  
   - Provides customer feedback and trends for product demand forecasting.

---

## 🎯 Project Goals

1. **Increase Customer Satisfaction**:
   - Ensure high-demand products are always in stock and deliveries are timely.
   
2. **Boost Cross-Selling Opportunities**:
   - Use data insights to recommend products frequently purchased together.
   
3. **Optimize Inventory Management**:
   - Reduce overstocking and stockouts through AI-driven forecasting.
