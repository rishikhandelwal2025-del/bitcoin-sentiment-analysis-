# bitcoin-sentiment-analysis-
# 📈 Bitcoin Sentiment & Trader Performance Analysis

## 📌 Project Overview

This project analyzes the relationship between **Bitcoin market sentiment** (measured using the Crypto Fear & Greed Index) and **trader performance**. By combining historical trading data with daily sentiment data, the project investigates how market psychology influences trading profitability.

The analysis follows a complete data analytics workflow, including data integration, preprocessing, exploratory data analysis (EDA), and visualization.

---

## 🎯 Problem Statement

Cryptocurrency markets are highly driven by investor sentiment. Fear and greed can significantly impact trading behavior and market volatility.

The objective of this project is to answer the following questions:

* Does market sentiment affect trader profitability?
* During which sentiment phase do traders earn higher profits?
* How does trader performance vary between Fear, Neutral, and Greed market conditions?

---

## 📊 Dataset

The project uses two datasets:

### 1. Crypto Fear & Greed Index

Contains the daily market sentiment classification.

**Columns include:**

* Date
* Fear & Greed Value
* Sentiment Classification

### 2. Historical Trading Data

Contains executed cryptocurrency trades.

**Columns include:**

* Timestamp
* Closed PnL
* Trading Information

The datasets are merged using the **Date** column to perform comparative analysis.

---

## ⚙️ Workflow

```text
Load Datasets
      │
      ▼
Data Cleaning
      │
      ▼
Date Formatting
      │
      ▼
Merge Trading Data with Sentiment Data
      │
      ▼
Exploratory Data Analysis (EDA)
      │
      ▼
PnL Analysis
      │
      ▼
Visualization
      │
      ▼
Business Insights
```

---

## 🛠️ Technologies Used

* Python
* Google Colaboratory
* Pandas
* Matplotlib
* Seaborn

---

## 📂 Project Structure

```text
Bitcoin-Sentiment-Analysis/
│
├── bitcoin_analysis_final.ipynb
├── fear_greed_index.csv
├── historical_data.csv
├── README.md
└── images/
```

---

## 📈 Analysis Performed

The project includes:

* Loading sentiment and trading datasets
* Data cleaning and preprocessing
* Date conversion for proper merging
* Merging datasets using trading date
* Exploratory Data Analysis (EDA)
* PnL comparison across sentiment categories
* Boxplot visualization of trader performance

---

## 📊 Visualization

The notebook generates a **Box Plot** showing:

* X-axis → Market Sentiment Classification
* Y-axis → Closed Profit & Loss (PnL)

This visualization helps identify how trader profitability changes under different market sentiments.

---

## 💡 Key Insights

* Trader profitability varies across different market sentiment categories.
* Extreme Fear and Extreme Greed periods may exhibit higher volatility in trading outcomes.
* Sentiment data can provide additional context for evaluating trading performance.
* Combining market psychology with historical trading data enables more informed analysis.

---

## ▶️ How to Run

### 1. Clone the repository

```bash
git clone https://github.com/your-username/bitcoin-sentiment-analysis.git
```

### 2. Navigate to the project directory

```bash
cd bitcoin-sentiment-analysis
```

### 3. Install the required libraries

```bash
pip install pandas matplotlib seaborn
```

### 4. Launch Jupyter Notebook / Google Colaboratory

```bash
jupyter notebook
```

Open **bitcoin_analysis_final.ipynb** and run all cells.

---

## 📦 Requirements

```text
pandas
matplotlib
seaborn
jupyter
```

---

## 📸 Sample Output

The project produces:

* Merged dataset preview
* Profit & Loss analysis
* Sentiment-wise Box Plot
* Market sentiment insights

*(You can add screenshots of your notebook outputs inside an **`images/`** folder and embed them here.)*

---

## 🚀 Future Enhancements

* Interactive dashboard using Power BI or Streamlit
* Time-series analysis of sentiment and PnL
* Correlation analysis between sentiment score and returns
* Machine Learning model to predict trader performance
* Integration with live Crypto Fear & Greed Index API
* Automated daily sentiment reporting

---

## 👨‍💻 Author

**Rishi Khandelwal**

Aspiring Data Analyst | Python | SQL | Power BI | Excel | Data Visualization

---

## ⭐ Support

If you found this project useful, consider giving this repository a **⭐ Star** on GitHub.
  
