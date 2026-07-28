# AFM 244 - Financial Data Analysis

A collection of Jupyter notebooks for AFM 244 coursework, focusing on financial data analysis and modeling using Python.

## 📚 Overview

This repository contains weekly assignments and class learning materials for AFM 244. The notebooks cover topics in financial analysis, data manipulation, and statistical modeling using Python libraries such as:

- **pandas** - Data manipulation and analysis
- **numpy** - Numerical computing
- **matplotlib** - Data visualization
- **statsmodels** - Statistical modeling and hypothesis testing

## 📁 Contents

### Week 11 - AFM_244_week_11.ipynb
An introduction to class learning with focus on:
- Loading and exploring quarterly sales data
- Filtering company data by ticker symbol
- Data type handling and conversion
- Preliminary data analysis and inspection

**Dataset**: Quarterly sales data (`qSales_2024.csv`) including:
- Company identifiers (gvkey, ticker, company name)
- Quarterly financial data spanning 2001-2024
- Sales figures (`saleq`) across multiple companies including Apple (AAPL) and Nintendo (NTDOY)

## 🛠️ Requirements

- Python 3.x
- pandas
- numpy
- matplotlib
- statsmodels

Install dependencies with:
```bash
pip install pandas numpy matplotlib statsmodels
```

## 📊 Key Variables

- **gvkey**: Global Company Key identifier
- **datadate**: Date of the report
- **fyearq**: Fiscal year (quarterly)
- **fqtr**: Fiscal quarter
- **tic**: Stock ticker symbol
- **conm**: Company name
- **saleq**: Quarterly sales
- **curcdq**: Currency code

## 🚀 Usage

1. Clone the repository:
```bash
git clone https://github.com/E7854/afm244.git
cd afm244
```

2. Open notebooks in Jupyter:
```bash
jupyter notebook
```

3. Run cells sequentially to execute the analysis

## 📝 Notes

- Notebooks are compatible with Google Colab
- Display settings are configured to show 2 decimal places for float values
- Data is loaded from CSV files in the repository

## 📧 Contact

For questions or feedback, please open an issue in this repository.
