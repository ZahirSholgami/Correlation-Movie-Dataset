# 🎬 Movie Dataset Correlation & Regression Analysis

Exploratory analysis of a movie dataset using Pandas, NumPy, Seaborn, and Matplotlib. Includes correlation matrix, regression plots, and insights into which features most affect gross earnings.

---

## 🧰 Frameworks & Libraries Used

The following Python libraries were used:

- **Pandas** – for data manipulation and handling missing values
- **NumPy** – for numerical operations and statistics
- **Seaborn** – for statistical data visualization (e.g., heatmaps, regression plots)
- **Matplotlib** – for customized plotting (`matplotlib.pyplot`, `matplotlib.mlab`, and configuration)
- `%matplotlib inline` – Jupyter magic to show plots within the notebook

---

## 📊 Project Highlights

- Identified missing values and cleaned the dataset
- Converted categorical columns to numeric using `.astype('category').cat.codes`
- Generated Pearson, Kendall, and Spearman correlation matrices
- Visualized correlations using a heatmap (`sns.heatmap`)
- Used regression plots (`sns.regplot`) to examine relationships between `budget`, `votes`, and `gross`
- Sorted correlation pairs to find and interpret the strongest predictors of gross revenue

---

## 🔍 Key Insights

- **Budget** showed the highest correlation with gross revenue (~0.74)
- **Votes** had a strong secondary correlation (~0.61)
- Linear regression confirmed that higher budgets and more audience engagement generally lead to better financial performance

---

## 🚀 How to Use

1. Clone the repository or download the `.ipynb` notebook
2. Install the required packages:
   ```bash
   pip install pandas numpy seaborn matplotlib
