# Time Series Forecasting and Unsupervised Learning

**Produced By:** Kaung Myat San (DAAA/FT/1B/03)  
**Date:** 13 January 2025  
**Institution:** Singapore Polytechnic

## Project Overview

This repository contains two comprehensive data science projects demonstrating advanced machine learning techniques, data analysis, and visualization skills using Python. The projects showcase time series forecasting and unsupervised learning methodologies applied to real-world datasets.

## Projects Included

### Part 1: Time Series Forecasting
**File:** `CA2_part-1.ipynb`

**Objective:** Forecast gas, electricity, and water consumption for the next 60 months using advanced time series analysis techniques.

**Key Features:**
- **Data Source:** CA2-Energy-Consumption-Data.csv
- **Time Series Analysis:** Comprehensive analysis including trend, seasonality, and residual components
- **Forecasting Models:** Implementation of multiple forecasting techniques including:
  - ARIMA (AutoRegressive Integrated Moving Average)
  - Exponential Smoothing (Holt-Winters)
  - Seasonal Decomposition
- **Model Evaluation:** Performance assessment using MSE, MAE, and MAPE metrics
- **Visualization:** Detailed plots showing historical data, decomposition, and forecasting results

**Libraries Used:**
- `pandas` - Data manipulation and analysis
- `numpy` - Numerical computing
- `matplotlib` - Data visualization
- `statsmodels` - Statistical modeling and time series analysis
- `sklearn` - Machine learning metrics

### Part 2: Unsupervised Learning - Customer Segmentation
**File:** `CA2_part-2.ipynb`

**Objective:** Implement unsupervised learning algorithms to segment customers into distinct groups for targeted marketing strategies.

**Key Features:**
- **Data Source:** CA2-Customer-Data.csv
- **Data Preprocessing:** 
  - Outlier detection and removal
  - Feature engineering (SpendingToIncomeRatio)
  - Data standardization (StandardScaler, MinMaxScaler)
  - PCA dimensionality reduction
- **Clustering Algorithms Tested:**
  - K-Means Clustering
  - DBSCAN
  - Gaussian Mixture Models (GMM)
  - Agglomerative Clustering
  - OPTICS
  - Spectral Clustering
- **Model Selection:** Comprehensive evaluation using Elbow Method and Silhouette Score
- **Final Model:** K-Means with 6 clusters (Silhouette Score: 0.437)

**Customer Segments Identified:**
1. **Young Poor High-Spender** - High spending despite lower income
2. **Careful Budgeters** - Conservative spending patterns
3. **Mature Moderate Spenders** - Balanced spending approach
4. **Young Moderate Spenders** - Average spending behavior
5. **Young Rich High-Spender** - Primary target group (highest revenue potential)
6. **Middle-Age Rich Low-Spenders** - High income but conservative spending

**Libraries Used:**
- `pandas`, `numpy` - Data manipulation
- `matplotlib` - Visualization
- `sklearn` - Machine learning algorithms and preprocessing
- `kneed` - Optimal cluster selection

## Technical Implementation

### Data Analysis Workflow
1. **Data Exploration** - Initial data understanding and quality assessment
2. **Data Preprocessing** - Cleaning, transformation, and feature engineering
3. **Model Development** - Implementation and comparison of multiple algorithms
4. **Model Evaluation** - Performance metrics and validation
5. **Visualization** - Comprehensive plots and charts for insights
6. **Business Insights** - Actionable recommendations

### Key Technical Skills Demonstrated
- **Time Series Analysis** - Forecasting future trends and patterns
- **Unsupervised Learning** - Customer segmentation using clustering
- **Data Preprocessing** - Handling outliers, scaling, and feature engineering
- **Model Selection** - Systematic evaluation and comparison
- **Data Visualization** - 2D and 3D plotting, statistical charts
- **Statistical Analysis** - PCA, variance analysis, correlation studies

## Key Results & Business Impact

### Time Series Forecasting
- Successfully developed forecasting models for 60-month energy consumption prediction
- Enables better resource planning and energy management
- Supports sustainability and cost optimization initiatives

### Unsupervised Learning - Customer Segmentation
- **Primary Target:** Young Rich High-Spenders (highest revenue potential)
  - Spend twice as much as other segments
  - Population equivalent to all other groups combined
  - Recommended products: Luxury gadgets, premium tech, exclusive items
- **Secondary Target:** Moderate Spenders (volume-based revenue)
  - Larger customer base
  - Value-for-money focused
  - Recommended products: Mid-range tech, affordable quality items

**Strategic Recommendations:**
- Focus premium marketing on high-value segments
- Develop targeted product portfolios for each segment
- Implement personalized pricing and promotional strategies

## How to Run the Projects

### Prerequisites
```bash
pip install pandas numpy matplotlib scikit-learn statsmodels kneed
```

### Execution Steps
1. Clone or download this repository
2. Ensure the following data files are in the project directory:
   - `CA2-Energy-Consumption-Data.csv`
   - `CA2-Customer-Data.csv`
3. Open the Jupyter notebooks in your preferred environment
4. Run the cells sequentially for complete analysis

### File Structure
```
├── CA2_part-1.ipynb          # Time Series Forecasting
├── CA2_part-2.ipynb          # Unsupervised Learning - Customer Segmentation
├── README.md                 # Project documentation
├── Slides.pdf               # Presentation slides
├── CA2-Energy-Consumption-Data.csv    # Energy dataset
└── CA2-Customer-Data.csv              # Customer dataset
```

## Project Highlights

- **Comprehensive Analysis:** Both projects include extensive exploratory data analysis
- **Multiple Algorithm Comparison:** Systematic evaluation of various machine learning approaches
- **Business-Oriented:** Results translated into actionable business strategies
- **Visualization-Rich:** Extensive use of plots and charts for insight communication
- **Professional Documentation:** Well-structured code with detailed explanations

## Learning Outcomes

This project demonstrates proficiency in:
- Advanced data science methodologies
- Time series forecasting techniques
- Unsupervised machine learning
- Statistical analysis and model validation
- Business intelligence and strategic thinking
- Python programming for data science

---

**Note:** This project was completed as part of the AIML course curriculum at Singapore Polytechnic, showcasing practical application of machine learning concepts in real-world business scenarios.