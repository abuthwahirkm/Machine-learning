# Heart Disease Exploratory Data Analysis (EDA)

## 📌 Project Overview
This project performs **Exploratory Data Analysis (EDA)** on the Heart Disease dataset to understand the data, identify patterns, detect outliers, and explore relationships between different features before building any Machine Learning model.

> **Note:** This project focuses only on EDA. No machine learning model is trained.

---

## 📂 Dataset
- **Dataset:** Heart Disease Dataset
- **Rows:** 918
- **Columns:** 12
- **Target Variable:** HeartDisease
  - 0 → No Heart Disease
  - 1 → Heart Disease

---

## 🛠️ Technologies Used
- Python 3.10
- Jupyter Notebook
- NumPy
- Pandas
- Matplotlib
- Seaborn
- SheryAnalysis (Basic EDA Report)

---

## 📊 EDA Steps Performed

- Imported required libraries
- Loaded the dataset
- Explored dataset structure
- Checked data types
- Checked missing values
- Checked duplicate records
- Generated statistical summary
- Visualized target variable distribution
- Plotted histograms with KDE
- Replaced invalid values (0) in Cholesterol and RestingBP
- Generated automatic EDA report using SheryAnalysis
- Created Count Plots
- Created Box Plots
- Created Violin Plot
- Generated Correlation Heatmap
- Drew observations from visualizations

---

## 📈 Visualizations
- Bar Plot
- Histogram
- Count Plot
- Box Plot
- Violin Plot
- Correlation Heatmap

---

## 🔍 Key Insights
- No missing values were found.
- No duplicate records were present.
- Invalid values in Cholesterol and RestingBP were replaced with their mean values.
- Male patients showed a higher number of heart disease cases.
- Certain chest pain types were more associated with heart disease.
- Correlation analysis helped identify relationships between numerical features.

---

## 📁 Project Structure

```
Heart-Disease-EDA/
│── ML2.ipynb
│── heart.csv
│── README.md
```

---

## ▶️ How to Run

1. Clone the repository
2. Install the required libraries

```bash
pip install numpy pandas matplotlib seaborn sheryanalysis
```

3. Open the notebook

```bash
jupyter notebook Heart.ipynb
```

4. Run all cells.

---
