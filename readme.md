
# BMW Sales Data EDA Project (2010–2024)

## Project Overview
This project presents a full exploratory data analysis (EDA) of BMW automobile sales data from 2010 to 2024. The dataset contains sales records for 11 BMW models across 6 regions, with detailed attributes related to engine, fuel, price, and sales volumes.

---

## Dataset Details

- **File:** BMW-sales-data-2010-2024-1.csv
- **Rows:** 50,000
- **Columns:** 11
  - `Model`, `Year`, `Region`, `Color`, `Fuel_Type`, `Transmission`, `Engine_Size_L`, `Mileage_KM`, `Price_USD`, `Sales_Volume`, `Sales_Classification`

---

## EDA Steps Performed

1. **Overview & Data Audit:** Previewed dataset, data types, missing/duplicate checks.
2. **Quality Checks:** Verified date ranges, numeric validity, categorical consistency.
3. **Cleaning:** Duplicates removed, categories normalized.
4. **Statistics:** Summary for all numerical/qualitative columns.
5. **Transformation:** StandardScaler and LabelEncoder applied.
6. **Outlier Analysis:** IQR and Z-score methods used—no major outliers found.
7. **Visualization:** Bar, box, histogram, and time series charts for trends and insights.
8. **Export CSVs:** Sales by model, region, year, fuel type, price ranges, and grouped attributes.

---

## Key Findings

- 7 Series is the top-selling BMW model (23.8M units).
- Asian region is the leading market (43M units).
- Hybrid fuel type holds 25% share, showing electrification trends.
- Manual vs. automatic sales split is nearly 50/50.
- Price ranges from $30K to $120K, targeting all market segments.
- Data quality is excellent: no missing, duplicate, or erroneous values.
- Ready for machine learning applications (classification/regression).

---

## Visualizations

- Bar chart: Sales by Model
- Box plot: Price by Region
- Histogram: Pricing distribution
- Line/Area: Yearly sales volume
- CSV outputs for all summary trends

---

## Usage Guide

1. Install required libraries:
```

pip install pandas matplotlib seaborn scikit-learn

```
2. Run all cells in your Jupyter notebook or Python script.
3. Visualizations will appear inline; supporting CSV files are auto-generated.

---

## Submission Checklist

- [x] BMW-sales-data-2010-2024-1.csv (original data)
- [x] EDA_BMWSales.ipynb (notebook/script)
- [x] Exported trend/summarization CSVs
 - top_models_by_sales.csv
 - sales_by_region.csv
 - fuel_type_analysis.csv
 - yearly_sales_trends.csv
- [x] README.md (this file)
- [x] All visuals included in code/report

---

## Author

 Name:Akash Jaiswal
 Roll No:FM1132 
 MSc Computer Science


