# 💰 Richest People Data Analysis (EDA)

This project performs an Exploratory Data Analysis (EDA) on a dataset of the richest individuals across the world using Python and visualization libraries.

## 📂 Files

- `rich.ipynb`: Jupyter Notebook containing the complete analysis and visualizations.
- `richest.csv`: Dataset used for the analysis.

## 🧰 Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib

## 📊 Project Overview

### 🧹 Data Cleaning:
- Removed unnecessary columns (`Unnamed: 7` to `Unnamed: 10`)
- Removed rows with null values
- Replaced inconsistent country names (e.g., `Canda` → `Canada`)
- Cleaned currency symbols and converted net worth to numeric format

### 🔍 Insights & Transformations:
- Analyzed `Total Net Worth`, `$ Last Change`, and `$ YTD Change` values
- Handled formatted strings (`$`, `K`, `M`, `B`) and converted them to numerical values

### 📈 Visualizations:
- Bar chart of richest people in **India**
- Total net worth by **Industry**
- Industry-wise wealth distribution for **India**
- Pie chart showing the **top 10 countries** by number of rich individuals
- Bar chart of **Last Change** in wealth for Indian individuals, color-coded by gain or loss

## 🇮🇳 Focused Analysis on India:
- Displayed all Indian billionaires
- Plotted industry distribution
- Highlighted net worth and wealth changes for Indian individuals

## 🔍 Sample Queries
- Who are the richest people in India?
- What are the most profitable industries?
- Which countries have the highest number of billionaires?
- How has wealth changed recently?


## 📬 How to Use

1. Clone the repository
2. Open `rich.ipynb` in Jupyter Notebook
3. Run the cells step by step

## 📑 License

This project is for educational purposes only.

---

