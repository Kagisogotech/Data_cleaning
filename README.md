# Data Cleaning 🧹

![Python](https://img.shields.io/badge/Python-3.x-blue)  
![Jupyter](https://img.shields.io/badge/Jupyter-Notebook-orange)  
![pandas](https://img.shields.io/badge/pandas-Data%20Analysis-yellowgreen)  

A simple but practical project for **cleaning and preprocessing raw datasets** into analysis-ready formats.  
This repository demonstrates typical data cleaning workflows using Python and Jupyter notebooks, with Excel input/output support.

---

## 📌 Project Overview

Working with raw data often means dealing with missing values, inconsistent formats, and outliers.  
This project provides reproducible examples of how to:

- Import raw datasets from Excel
- Explore and detect data quality issues
- Clean and transform the data
- Export cleaned datasets back to Excel

The aim is to serve as both a **reference** and a **starting point** for data analysts and learners.

---

## 📂 Repository Structure

├── clean_data.ipynb # Main notebook with data cleaning workflow
├── data_cleaning.ipynb # Additional exploratory cleaning steps
├── Book1.xlsx # Example raw dataset
├── Book1_cleaned.xlsx # Example cleaned dataset
└── README.md # Project documentation
---

## ⚙️ Getting Started

### 1. Clone the repo
```bash
git clone https://github.com/Kagisogotech/Data_cleaning.git
cd Data_cleaning
```
python -m venv venv
# Activate it
# On Windows:
venv\Scripts\activate
# On Mac/Linux:
source venv/bin/activate
pip install -r requirements.txt
(If you don’t have a requirements file yet, install manually: pip install pandas numpy openpyxl jupyter)
jupyter notebook

🚀 Usage

Open clean_data.ipynb in Jupyter Notebook

Step through the cells to:

Load the raw Excel dataset

Apply cleaning steps (missing values, renaming, filtering, etc.)

Export the cleaned dataset as Book1_cleaned.xlsx

You can adapt the notebook for your own datasets by replacing the input file path.
