📘 E-commerce ETL & Analytics Pipeline

A complete end-to-end pipeline to extract, clean, transform, analyze, and model e-commerce data using Python.
(Project report reference: E-commerce Analysis PDF 

README

)

🚀 Overview

This project builds a real-world style ETL system that processes multi-table e-commerce data and generates analytical insights.
It includes data cleaning, feature engineering, visualization, SQLite storage, and a delivery-delay prediction model.

🎯 Features

ETL pipeline (Extract → Transform → Load)

Data quality checks & validation

Feature engineering for delivery performance

Exploratory data analysis & charts (monthly/weekly trends, category & state revenue)

Random Forest delivery delay prediction model

SHAP explainability

SQLite analytical database output

🛠 Tech Stack

Python, Pandas, NumPy

Matplotlib, Seaborn

Scikit-learn

SQLite

Google Colab / Jupyter

📁 Project Structure
ecommerce-etl-analytics-pipeline/
│── data/               # Raw & processed datasets
│── scripts/            # ETL pipeline Python script
│── outputs/            # Visuals, tables, QC reports
│── reports/            # Final PDF project report
│── README.md           # Documentation

▶️ How to Run
git clone https://github.com/your-username/ecommerce-etl-analytics-pipeline
cd ecommerce-etl-analytics-pipeline
pip install -r requirements.txt
python scripts/etl_pipeline.py


Outputs will be saved inside /outputs.

📊 Sample Outputs

From the PDF report (page 8–13) you’ll see:

Monthly revenue trend

Weekly revenue trend

Category & state revenue charts

Order status distribution


README

🤖 ML Component

Random Forest classifier

Predicts orders likely to be delayed

SHAP analysis for interpretability

Reports & confusion matrix saved to outputs

📄 Report

Full academic-style project report included in:
reports/E-commerce Analysis.pdf


README

👤 Author

Adhithyaraj P R
