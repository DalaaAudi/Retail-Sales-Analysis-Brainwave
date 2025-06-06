# 🛒 Superstore Sales & Profit Analysis

This project is a comprehensive data analysis of a fictional superstore's sales dataset. It explores temporal trends, regional performance, shipping behavior, customer segmentation, and profitability patterns. It also includes predictive modeling using linear regression to forecast sales and profit based on several factors.
---

## 📁 Dataset

The dataset used is `SampleSuperstore.csv`, which contains records of customer orders including:

- Order and shipping dates
- Product information
- Customer segments
- Geographic location
- Discounts, sales, and profit
---

## 🔍 Project Goals

- Explore patterns in sales and profit across time, categories, and regions.
- Identify products and states that result in losses.
- Analyze customer segments and shipping delays.
- Build simple regression models to predict:
  - **Sales**
  - **Profit**

  
Based on features such as:
- Segment
- Product
- Region/State
- Shipping mode
- Discount
- Time features (from Order Date)
---

## 📊 Analysis Highlights

- Temporal trends of orders and profits.
- Profit distribution by category, sub-category, and region.
- Scatter plots showing relationships between profit and discount, sales, and quantity.
- Boxplots to visualize shipping delays and segment behavior.
- Count plots for products and states with losses.
---

## 🤖 Predictive Exploration (Linear Trends)

- Explored potential relationships between variables such as Discount, Quantity, and Sales with Profit using scatter plots.
- Visualized these patterns to understand if linear trends exist.
- While a full regression model was considered, the focus was kept on visual interpretation rather than full prediction.
---

## Tools Used
- Python (pandas, seaborn, matplotlib, plotly, scikit-learn)

> 🧠 This project was developed as a learning exercise with the assistance of AI tools, including ChatGPT. These tools supported code writing, data analysis, and documentation. Every step was carefully reviewed and understood to ensure genuine learning and comprehension.
---

## 🧪 How to Run

1. Clone the repository or download the project folder.
2. Install dependencies:
   ```bash
   pip install -r requirements.txt
---