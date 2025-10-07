# Logistics Cost Intelligence & Profitability Analysis

An end-to-end data science and business intelligence project that deconstructed $XMM in logistics spend, identified 60%+ cost-saving opportunities, and built a proactive forecasting model with 98%+ accuracy.

## 📊 Business Problem
Global specialty logistics costs showed high volatility, impacting P&L predictability. The business needed to:
- Understand root causes of cost variance
- Build accurate forecasting models
- Identify specific cost-saving opportunities

## 🛠️ Technical Approach
### Data Collection & Cleaning
- **Tools:** Python, SQL, Alteryx
- **Data Sources:** TMS (Transportation Management System) - 18 months of shipment data
- **Key Cleaning Steps:**
  - Handled anomalous service fees misclassified as freight charges
  - Created `Cleaned_Billable_Weight` feature to separate freight vs. service costs
  - Standardized lane definitions and service level categorizations

### Exploratory Data Analysis & Hypothesis Testing
```python

def analyze_cost_drivers(df):
    # Correlation analysis between cost/kg and potential drivers
    # Fuel prices, shipment weight, service levels, etc.
    return insights
