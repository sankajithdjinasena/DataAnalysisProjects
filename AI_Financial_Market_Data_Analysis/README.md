# 🤖 AI Financial & Market Data Analysis

This project analyzes a **synthetic time-series financial dataset** of companies involved in Artificial Intelligence (AI), including **OpenAI, Google, and Meta**.  
The dataset captures **daily R&D spending, AI revenue, revenue growth, events, and stock impact** from **January 1, 2015, to December 31, 2024**.

Using **Python** and the **Pandas** library, we performed **data cleaning**, **exploration**, and derived insights about AI investments, revenue growth, and market reactions.

---

## 📊 Dataset Overview

- **Format:** CSV  
- **Frequency:** Daily observations  
- **Columns:**
  - **Date:** Specific calendar day for which data is recorded.
  - **Company:** Name of the company (OpenAI, Google, Meta).
  - **R&D_Spending_USD_Mn:** Research & Development spending in Millions of USD.
  - **AI_Revenue_USD_Mn:** Revenue generated from AI-related products/services in Millions of USD.
  - **AI_Revenue_Growth_%:** Daily percentage growth of AI revenue.
  - **Event:** Significant events that could impact stock performance (e.g., AI launches, partnerships, policy updates).
  - **Stock_Impact_%:** Daily percentage change in stock price in response to financial metrics or events.

---

## 📝 Analysis Questions

We explored the dataset to answer the following:

1. How much **R&D spending** was done by each company?  
2. How much **AI revenue** was earned by each company?  
3. What was the **date-wise impact on stock** performance?  
4. Identify **events with maximum stock impact**.  
5. Analyze **AI revenue growth trends** for each company.  
6. Compute **correlations** between columns.  
7. Compare **yearly expenditure vs revenue**.  
8. Perform **event impact analysis**.  
9. Track **changes in stock index** with respect to year and company.

---

## 📝 Visualization Questions

1. **R&D Spending vs AI Revenue**
    - Compare investments and returns over time for each company using line plots or bar charts.  
2. **Stock Impact Trends**
    - Plot Stock_Impact_% to see market reaction to events.  
3. **AI Revenue Growth**
    - Visualize percentage growth over time to identify trends.  
4. **Event Analysis**
    - Highlight events that had major positive or negative effects on stocks.  
5. **Expenditure vs Revenue Yearly**
    - Compare yearly R&D spending against AI revenue with stacked bar charts or scatter plots.

---

## 🛠 Tools & Libraries

- **Python**  
- **Pandas** — Data cleaning and analysis  
- **NumPy** — Numerical operations  
- **Matplotlib / Seaborn / Plotly** — Data visualization  
- **Jupyter Notebook** — Interactive analysis  

---

## 🚀 How to Run

1. Clone the repository:
   ```bash
   git clone https://github.com/sankajithdjinasena/DataAnalysisProjects.git
   ```
2. Navigate to the project folder:
   ```bash
   cd DataAnalysisProjects/AI_Financial_Market_Data_Analysis
   ```
3. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```
4. Open the notebook:
   ```bash
   jupyter notebook AI_Financial_Market_Data_Analysis.ipynb
   ```

---

## 📌 Sample Insights

- Identified periods of high R&D investment and corresponding revenue growth.  
- Detected key events (like AI product launches) that significantly impacted stock prices.  
- Compared AI revenue growth trends across OpenAI, Google, and Meta.  
- Explored correlations between R&D spending, revenue, and market performance.

---

## 📜 License

This project is licensed under the [MIT License](LICENSE).

---

💡 *AI investments today shape the market reactions of tomorrow.*
