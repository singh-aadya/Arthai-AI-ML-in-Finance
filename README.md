# 📈 Sales Forecasting with AI-Powered Insights
> Predict tomorrow’s sales today — and never overstock again.

> Team Members:
Aadya Singh
Arya Patekhede
Srushti Bartakke


![Dashboard Screenshot](/dashboard.png) 

## 🚀 Project Overview

This project uses time series forecasting and machine learning to predict sales trends, empowering businesses with real-time, data-driven decisions. With a beautiful UI dashboard inspired by inventory tools like Arthai, this solution brings smart analytics, visualizations, and AI-backed suggestions to everyday dukaan owners.

---

## 🧠 Problem Statement

Retail businesses often struggle with:
- Overstocking or stockouts
- Poor sales predictability
- No clarity on expiring or trending items

**Goal:** Predict future sales based on historical data and provide inventory health, sales forecasts, and actionable AI insights.

---

## 💡 Solution Overview

- 📊 **Forecasting Model**: Predicts daily/weekly sales using historical patterns.
- 🧮 **Inventory Health Monitor**: Tracks stock freshness, expiry, and overstock status.
- 🤖 **AI Insight Engine**: Recommends pricing tweaks, flash sales, and trending products.
- 📈 **Sales Dashboard**: Real-time KPIs (Sales, Orders, Low Stock, Expiring Soon).

---

## 🧾 Dataset

- Source: [Kaggle - Sales Forecasting Dataset](https://www.kaggle.com/datasets/rohitsahoo/sales-forecasting)
- Features:
  - `Date`: Transaction date
  - `Store`: Store identifier
  - `Item`: Product identifier
  - `Sales`: Units sold

---

## 🔧 Data Preprocessing

- ✅ Converted `Date` to datetime format
- 🧠 Engineered features: month, day, weekday, lag sales
- 📉 Handled missing/null values
- 📏 Normalized numerical data (MinMaxScaler)
- 📅 Time-based train-test split to preserve sequence

---

## 🖥️ Key Features & Demo

- ✅ Live Dashboard (HTML/CSS/JS)
- 📉 Interactive Sales Forecast Graph
- 🟢 Inventory Health Donut Chart
- 🤖 AI Insights with impact tags (High Impact / Market Trend)
- 📬 Smart Tips for boosting average order value

---

## ⚠️ Challenges Faced

- Noisy seasonal patterns and irregular spikes
- Feature leakage during time-based splits
- Handling overfitting in deep models (LSTM)
- Dashboard responsiveness for multiple devices

---

## 🔮 Future Scope

- Integration with real-time POS systems (e.g. Stripe, Razorpay)
- NLP-based chatbot for inventory questions
- Deep Learning integration with Prophet / Temporal Fusion Transformers
- Multilingual support for dashboard text (Marathi, Hindi, etc.)
- Forecast at category-level (seasonal items, region-based trends)

---

## 🛠️ Tech Stack

- **Frontend**: Next.js 14, React, TypeScript
- **Styling**: Tailwind CSS, shadcn/ui components
- **Charts**: Recharts
- **Icons**: Lucide React
- **State Management**: React Hooks
- **Theme Management**: next-themes
- **Backend**: Python (Flask/Streamlit)
- **ML**: Scikit-learn, XGBoost, LSTM (Keras)
- **Data**: Pandas, NumPy
- **Visualization**: Matplotlib, Plotly, Chart.js

---
## 📋 Prerequisites

- Node.js 18.x or higher
- npm or yarn

## 🛠️ Installation

1. Clone the repository:

```bash
git clone https://github.com/singh-aadya/Arthai-AI-ML-in-Finance.git
cd arthai-dashboard


