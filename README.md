# 📊 COVID-19 and Its Impact on Indian Stock Markets (EDA)

## 📌 Project Overview
This project presents an in-depth Exploratory Data Analysis (EDA) on the impact of COVID-19 on the Indian stock market. It analyzes how pandemic-related factors such as confirmed cases, deaths, and recoveries influenced the movement of the NIFTY index over time.

The objective is to understand market behavior, volatility patterns, and recovery trends during the COVID-19 period using Python-based data analysis.

## 🛠️ Tools & Technologies Used
- Python 🐍  
- Pandas  
- NumPy  
- Matplotlib  
- Seaborn  
- Jupyter Notebook
- 
## 📂 Dataset Information
The dataset contains monthly COVID-19 statistics along with stock market data:
- Date  
- Confirmed Cases  
- Recovered Cases  
- Deaths  
- Active Cases  
- Trend (Increasing/Decreasing)  
- NIFTY Open, High, Low, Close  
- NIFTY Volume
- 
## 🔍 Project Workflow

### 1. Data Collection
Loaded dataset containing COVID-19 and stock market data.

### 2. Data Cleaning
- Checked missing values (no nulls found)
- Converted date column into datetime format
- Sorted data chronologically

### 3. Exploratory Data Analysis
- Statistical summary using `.describe()`
- Trend analysis of COVID vs market
- Volatility and returns calculation

### 4. Data Visualization
- Line plots for NIFTY trend
- COVID cases vs stock market comparison
- Correlation heatmap
- Distribution and trend analysis

## 📊 Key Visualizations
- COVID-19 cases vs NIFTY Close price trend  
- Deaths vs Market movement  
- Trend distribution (Increasing vs Decreasing)  
- Correlation heatmap between variables  
- Market returns and volatility analysis
- 
## 💡 Key Insights

- Sharp rise in COVID-19 cases led to a significant decline in the stock market  
- Highest volatility observed during the early pandemic phase  
- Market showed strong recovery after lockdown easing  
- Negative correlation observed between COVID cases and NIFTY index  
- Trading volume increased significantly during crisis periods
- 
## 📈 Conclusion
The analysis clearly shows that COVID-19 had a strong short-term negative impact on the Indian stock market. However, the market demonstrated resilience and recovered steadily over time, reflecting investor confidence and economic recovery.

## 🚀 Future Improvements
- Add interactive dashboards (Plotly / Power BI)  
- Include sector-wise stock analysis  
- Apply machine learning for market prediction  
