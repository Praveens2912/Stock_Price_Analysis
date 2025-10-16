📈 Stock Price Analysis Project

![Python](https://img.shields.io/badge/Python-3.10-blue?logo=python)
![Jupyter](https://img.shields.io/badge/Jupyter-Notebook-orange?logo=jupyter)
![pandas](https://img.shields.io/badge/pandas-Data%20Analysis-yellow?logo=pandas)
![Matplotlib](https://img.shields.io/badge/Matplotlib-Visualization-green)
![Seaborn](https://img.shields.io/badge/Seaborn-Statistical%20Plots-blueviolet)
![Spyder](https://img.shields.io/badge/Spyder-IDE%20Dashboard%20Development-red?logo=spyderide)

![pexels-rdne-7947707](https://github.com/user-attachments/assets/70448b66-744d-4b23-8428-da32c085375d)



## 📁 Project Overview
This project explores **stock market price behavior** of major technology companies over time.  
The analysis focuses on understanding stock performance, trends, volatility, and correlations between major tech stocks — all executed in **Python using Spyder IDE**.

Data was collected from multiple stock CSV files and analyzed using **pandas**, **NumPy**, and **Matplotlib** to uncover meaningful patterns and insights.

---

## 📊 Interactive Dashboard

A fully interactive **Stock Price Analysis Dashboard** was developed using **Streamlit**.  
This dashboard provides an easy-to-navigate interface for exploring stock performance, trends, and correlations in real-time.  
Users can filter companies, adjust timeframes, and view analytical charts directly from their browser.

###  **Dashboard Features**
-  **Stock Price Trends** – Interactive line charts showing daily and cumulative price changes.  
-  **Moving Average Comparison** – Select between 7-day, 30-day, and 90-day moving averages to observe trend shifts.  
-  **Correlation Matrix** – Explore the relationships among major tech stocks (Apple, Amazon, Google, Microsoft).  
-  **Volatility & Daily Returns** – Visual breakdown of daily performance and risk levels.  
-  **Company Selection** – Choose specific stocks to visualize and compare side by side.  

---

### 🌐 **Dashboard Access**

Since Streamlit runs locally during development, you can launch the dashboard by executing the following command in your terminal:

```bash
streamlit run app.py
```
Once the server starts, open your browser and visit:

[http://localhost:8502/](http://localhost:8503/)

## 📊 Business Questions Solved

<br>

### 1️⃣ Data Collection  
Collected and combined multiple CSV files for **Apple, Google, Microsoft, and Amazon**.  
The data covers **five years of stock performance**, including daily open, close, high, and low prices.

---

<br>

### 2️⃣ What was the change in price of the stock over time?  
Plotted **closing prices over time** to identify **overall growth, volatility, and trend stability** for each company.

📊 **Visualization:**  
- Line charts showing stock price movements over the years.  
- Observed general upward trends with some volatility during major market events.

  <img width="934" height="562" alt="image" src="https://github.com/user-attachments/assets/2bcb1e7f-c65e-4759-b88a-99bc6f1adc48" />


---

<br>

### 3️⃣ What was the moving average of the various stocks?  
- Calculated **10-day, 20-day, and 50-day moving averages** to smooth out short-term fluctuations.  
- This helps in identifying **long-term trends** in stock performance.

<img width="917" height="600" alt="image" src="https://github.com/user-attachments/assets/f89f3911-b16e-4e9f-96e2-0309e1b6835d" />


---

<br>

### 4️⃣ Analyze closing price change in Apple stock  
- Focused analysis on **Apple (AAPL)** to study price fluctuations and growth trends.  
- Compared Apple’s performance against market peers.

<img width="1670" height="470" alt="image" src="https://github.com/user-attachments/assets/be890276-534b-49e4-bac3-23912d8be40a" />


<br>
<br>

**Insight:**  
Apple showed a **steady upward trend** with occasional dips, reflecting market corrections but overall strong investor confidence.

---

<br>

### 5️⃣ Performing resampling analysis of closing price  

- Used **resampling techniques** (`.resample()`) to aggregate daily data into **monthly and yearly averages**.  
- This provided a **high-level view** of how each company’s stock performed across time intervals.

---

<br>

### 6️⃣ Checking if the closing prices of these tech companies are correlated or not  
- Examined **correlation coefficients** between **Apple, Amazon, Google, and Microsoft**.  
- Created a **heatmap** to visualize the strength of relationships between their stock movements.

<img width="634" height="619" alt="image" src="https://github.com/user-attachments/assets/c5841a06-ea55-46fd-a145-856a553d2da6" />

<br>
<br>

**Insight:**  
Tech stocks are **strongly correlated**, indicating similar market movement patterns driven by macroeconomic factors.

<br>

<img width="507" height="404" alt="image" src="https://github.com/user-attachments/assets/83face84-732d-4a7b-a809-06ef9925f53b" />
<br>

---

<br>

7️⃣ Analyze whether daily change in closing price or daily returns of stocks are correlated or not  

- Calculated **daily returns** and analyzed their correlations across companies.  
- Compared with closing price correlation results to understand **short-term vs long-term relationships**.
  
<br>
<img width="653" height="617" alt="image" src="https://github.com/user-attachments/assets/eea92a9a-d05c-4cb8-ad53-507767fddb62" />

<br>

**Finding:**

Daily returns showed **moderate correlation**, suggesting each stock reacts differently to short-term events but aligns over time.

---

##  Tools & Libraries Used
- **Python**
- **Spyder IDE** – for scripting and visualization  
- **pandas** – data manipulation and time-series handling  
- **NumPy** – numerical calculations  
- **Matplotlib & Seaborn** – for data visualization  

---

## Key Insights

- Apple, Google, and Microsoft showed strong upward trends over the years.

- Amazon displayed higher volatility but also higher potential returns.

- All major tech stocks exhibited high correlation, suggesting market-wide movement.

- Daily returns correlations were moderate, indicating diverse short-term investor responses.

---

<br>
Developed By

 Praveen S<br>
 Chennai, India<br>
 GitHub Profile - https://github.com/Praveens2912<br>
 Portfolio - https://praveens2912.github.io/My_Portfolio/
