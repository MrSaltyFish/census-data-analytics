# 📊 Maharashtra Workforce Census Comparison (2001 vs 2011)

This Jupyter Notebook presents a comparative analysis of workforce statistics in Maharashtra using Census of India data from the years **2001** and **2011**. The goal is to highlight structural changes in employment trends, gender disparity, rural-urban divide, and age-wise workforce participation over the decade.

---

## 📂 Overview

The notebook performs the following steps:

- 📥 Imports and cleans raw census data for 2001 and 2011
- 🧹 Fixes column headers, trims whitespace, and resets indices
- ⚠ Identifies and resolves data inconsistencies across census years
- 🔢 Merges and harmonizes workforce categories (e.g., handling marginal worker breakdown in 2011)
- ❌ Drops unnecessary columns and extra rows
- 🧼 Filters out 0-value entries and ensures no NULL values

---

## 📊 Visualizations and Insights

### 1. Total Workers in Maharashtra
A comparison of the total number of workers:
- **2001**: 41,130,816  
- **2011**: 49,248,188  
> 📈 An increase of ~8 million workers (~80 lakh), possibly due to population growth, better enumeration, or increased economic participation.

---

### 2. Workforce Composition (Stacked Bar)
Shows proportional distribution of:
- Main Workers
- Marginal Workers
- Non-Workers  
across 2001 and 2011.

---

### 3. Gender Disparity in Workforce (Grouped Bar)
Compares male vs. female participation in:
- Main Workers  
- Marginal Workers  
- Non-Workers  
for both years, revealing workforce gender gaps and trends.

---

### 4. Age Group Workforce Analysis (Line Plot)
Breaks down:
- Main Workers  
- Marginal Workers  
- Non-Workers  
by age groups for both census years to show age-specific participation trends.

---

### 5. Rural vs Urban Workforce Categories (2011)
Compares:
- Main Workers  
- Marginal Workers  
- Non-Workers  
- Non-Workers Seeking Work  
across rural and urban regions in 2011 to identify regional employment differences.

---

## 📁 Dataset Sources

- **Census of India 2001** and **2011** datasets on workforce classification by age, gender, and area.

---

## 🛠 Libraries Used

- `pandas`
- `matplotlib`
- `seaborn`
- `scikit-learn`
- `re`

To install them, run:
```bash
pip install pandas matplotlib seaborn numpy
````

---

## ▶ How to Run

1. Clone or download this repository.
2. Open the notebook with Jupyter:

   ```bash
   jupyter notebook Maharashtra_Comparison.ipynb
   ```
3. Execute the cells sequentially to view charts and analysis.

---

## 📌 Observations & Limitations

* **Data anomalies handled:** '\*' symbols, inconsistent category naming, missing distinctions in 2001 data (e.g., marginal worker subtypes).
* **Zero-values removed:** Treated as potential outliers in some columns.
* Analysis is **Maharashtra-specific**, but adaptable for other states with similar formatting; just provide a different State's data file for input.

---

## 📬 Contact

For feedback or collaboration:
**Anvesh Khode**
\[anveshkhode7588@gmail.com]
