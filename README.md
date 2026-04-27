# Analysis of ROE Drivers for US Listed Companies (2018-2022)

## 1. Problem & User  
Analyze key factors influencing ROE of US public companies (2018-2022) for financial analysts and researchers.

## 2. Data  
Compustat Fundamentals Annual via WRDS (accessed June 2024); fields: total assets, long-term debt, revenue, net income, market value.

## 3. Methods  
- Connect to WRDS using `wrds` Python package  
- Extract and clean data (remove missing/non-positive values)  
- Calculate ROE and DuPont components (net profit margin, asset turnover, equity multiplier)  
- Conduct descriptive stats, correlation, and regression analysis.

## 4. Key Findings  
- ROE fluctuated with economic cycles during 2018-2022  
- Net profit margin and asset turnover strongly affect ROE  
- Equity multiplier has limited impact  
- Regression highlights net profit margin as the main ROE driver  
- Data cleaning improves result reliability.

## 5. How to run  
- Install dependencies: `pip install wrds pandas`  
- Run notebook/script to connect WRDS, fetch, process data, and analyze  
- Outputs saved in `financial_ratios_no_industry.csv`.

## 6. Product link / Demo  
No demo available; see full code and analysis in `notebooks/ACC102_ROE_Analysis.ipynb`.

## 7. Limitations & next steps  
- WRDS access required; public data alternatives needed for wider use  
- Equity multiplier excludes short-term debt  
- Industry-level analysis pending  
- Integration of macroeconomic factors and advanced models suggested.
