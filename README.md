Sales Insights Visualization Dashboard

A Data Storytelling, Machine Learning, and Interactive Dashboard Project

Overview

This project transforms raw sales and customer data into actionable business insights through data cleaning, exploratory analysis, predictive modeling, automated reporting, and a Streamlit-based interactive dashboard.

It demonstrates an end-to-end analytics workflow: from exploratory data analysis → model development → automated PDF reports → real-time visualization.
The goal is to help businesses better understand customer behavior, identify strategic opportunities, and maximize revenue.

Objectives
Data & Insights

Clean and preprocess real-world customer and transaction data.

Identify revenue-driving product categories and customer segments.

Analyze purchasing behavior, demographics, and spending trends.

Evaluate statistical relationships to inform business decisions.

Machine Learning

Build baseline models to classify or predict customer characteristics.

Evaluate model performance and interpret feature importance.

Investigate feasibility of demographic predictions (e.g., gender).

Visualization & Reporting

Generate automated PDF reports for business stakeholders.

Present insights with clear, data-driven storytelling.

Build an interactive dashboard that supports real-time exploration.

Methods and Techniques
Data Processing

Handling missing data with median/mode imputation

Outlier inspection and categorical encoding

Feature selection and transformation

Exploratory Data Analysis

Distribution analysis with histograms and box plots

Correlation heatmaps and scatterplots

Customer value segmentation

Machine Learning

Logistic Regression, Random Forest, Gradient Boosting

Metrics: accuracy, F1-score, confusion matrices

Model interpretation and understanding prediction limits

Visualization

Matplotlib and Seaborn for static visual analytics

Streamlit for interactive charts and filtering

Data storytelling principles for effective communication

Automated Reporting

PDF reports that include summary metrics, charts, and insights

Consistent formatting for business-readiness

Results
Revenue Insights

Electronics and Automotive categories generate the highest revenue and average order value.

Behavioral Patterns

Price shows a stronger correlation with revenue than quantity.

Price–Revenue correlation: 0.80

Quantity–Revenue correlation: 0.45

Customer Segmentation

Low spenders: 57.2%

Medium spenders: 33.5%

High spenders: 9.3%

Machine Learning Findings

Gender prediction models performed poorly, indicating the dataset lacks meaningful features for demographic prediction.

Demonstrates the importance of feature relevance in modeling.

Limitations

Dataset lacks additional behavioral or lifestyle attributes needed for demographic models.

Insights are limited by the completeness and accuracy of the data.

Models were exploratory and not tuned for production-level performance.

Installation
1. Clone the repository
git clone https://github.com/sabrinachu-47/sales-insights-visualization-dashboard.git
cd sales-insights-visualization-dashboard

2. Install core dependencies
pip install -r requirements.txt

Optional: Streamlit
pip install streamlit

Optional: PDF reporting
pip install fpdf

Usage
Run the Jupyter Notebook
jupyter notebook Sabrina114Project.ipynb

Generate an Automated PDF Report
Step 1: Ensure files are present

report_generator.py and sales_data.csv must be in the same folder.

Step 2: Install FPDF
pip install fpdf2

Step 3: Run the script
python report_generator.py

Launch the Streamlit Dashboard
streamlit run dash.py


(Replace dash.py with the correct filename if needed.)

Dependencies

pandas

numpy

matplotlib

seaborn

scikit-learn

streamlit

fpdf / fpdf2

jupyter

Configuration

Place sales_data.csv in the project root directory.

No additional setup is required for running the notebook, dashboard, or report generation.

Documentation

In-notebook explanations and markdown cells

PDF reports include summaries and visual insights

Dashboard code contains usage notes and inline guidance

requirements.txt contains all necessary libraries

Troubleshooting
Dataset not found

Ensure sales_data.csv is in the working directory.

PDF fails to generate

Install FPDF:

pip install fpdf

Streamlit dashboard not launching

Confirm installation and ensure port 8501 is available.

Contributors

Sabrina Chu

Puja Shah

Doreen Chang
