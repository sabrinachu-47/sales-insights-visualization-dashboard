# Sales Insights Visualization Dashboard

This project performs an end-to-end analysis of sales and customer data to uncover key insights, identify customer segments, and support data-driven decision-making. It includes exploratory analysis, visualizations, machine learning modeling, automated PDF report generation, and a Streamlit-based dashboard for interactive exploration.

---

## Table of Contents
1. [Objectives](#objectives)
2. [Methods](#methods)
3. [Results](#results)
4. [Limitations](#limitations)
5. [Installation](#installation)
6. [Usage](#usage)
7. [Dependencies](#dependencies)
8. [Configuration](#configuration)
9. [Troubleshooting](#troubleshooting)
10. [Contributors](#contributors)

---

## Objectives

- Clean and explore real-world sales and customer datasets.
- Identify high-value customer segments and key product categories.
- Analyze purchasing behavior and demographic patterns.
- Implement machine learning models for customer profiling.
- Generate automated PDF reports for business stakeholders.
- Provide an interactive Streamlit dashboard for real-time insights.

---

## Methods

### **Data Cleaning & Preprocessing**
- Handling missing values using median/mode imputation.
- Encoding categorical variables.
- Feature selection and transformation.

### **Exploratory Data Analysis**
- Descriptive statistics.
- Histograms, box plots, correlation heatmaps.

### **Visualization**
- Seaborn and Matplotlib visualizations.
- Streamlit dashboard for live data filtering and exploration.

### **Machine Learning**
- Predictive modeling for demographic insights.
- Performance evaluation using accuracy, precision, recall, and F1-score.

### **Automated PDF Reporting**
- Reports include charts, summaries, and insights.
- Generated using `FPDF` library.

---

## Results

### **Correlation Insights**
- **Price → Revenue correlation:** 0.80  
- **Quantity → Revenue correlation:** 0.45  

### **Customer Segmentation**
- **Low spenders:** 57.2%  
- **Medium spenders:** 33.5%  
- **High spenders:** 9.3%  

### **Machine Learning Findings**
- Gender prediction models performed poorly.
- Dataset lacks meaningful demographic predictor features.
- Highlights importance of feature relevance in modeling.

---

## Limitations

- Dataset lacks lifestyle and behavioral attributes needed for demographic prediction.
- Insights depend heavily on dataset completeness and accuracy.
- ML models were exploratory and not optimized for production use.

---

## Installation

### 1. Clone the repository
```bash
git clone https://github.com/sabrinachu-47/sales-insights-visualization-dashboard.git
cd sales-insights-visualization-dashboard
