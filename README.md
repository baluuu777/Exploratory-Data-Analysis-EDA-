# 📊 Sample Superstore EDA

## 📌 Overview

This project performs an **Exploratory Data Analysis (EDA)** on the **Sample Superstore** dataset to uncover trends, patterns, anomalies, and relationships between various business metrics like **Sales**, **Profit**, **Discount**, and **Region**.

## 🎯 Objectives

* Clean the dataset by handling missing values, duplicates, and outliers.
* Perform statistical analysis to understand data distribution.
* Visualize relationships and patterns using plots.
* Identify key business insights from the dataset.

## 📂 Dataset

* **Source:** Sample Superstore (Retail Sales Data)
* **Key Columns:**

  * `Order Date`, `Ship Date`
  * `Region`, `Category`, `Sub-Category`
  * `Sales`, `Profit`, `Quantity`, `Discount`

## 🛠️ Steps Performed

1. **Data Cleaning**

   * Handled missing values (mean/mode imputation).
   * Removed duplicate records.
   * Detected and removed outliers using **IQR method**.

2. **Statistical Analysis**

   * Calculated mean, median, variance, standard deviation.
   * Computed correlation matrix between numerical variables.

3. **Data Visualization**

   * **Histograms** for numerical data distributions.
   * **Boxplots** for outlier detection.
   * **Heatmaps** for correlation analysis.

## 📈 Key Insights

* Discounts above certain thresholds negatively affect profit.
* Sales and profit show a moderate positive correlation.
* Specific regions and categories have higher sales volumes.

## 📷 Visual Outputs

* Histograms (`histograms.png`)
* Boxplots (`boxplots.png`)
* Correlation Heatmap (`heatmap.png`)

## 📦 Installation & Usage

```bash
# Clone this repository
git clone https://github.com/yourusername/sample-superstore-eda.git

# Install dependencies
pip install pandas numpy matplotlib seaborn

# Run the analysis
python eda_superstore.py
```

## 📜 Deliverables

* Cleaned dataset: `Sample_Superstore_Cleaned.csv`
* Visualizations (PNG files)
* Insights from EDA

## 📌 Author

**JAWALKAR BALAJI RAO**
