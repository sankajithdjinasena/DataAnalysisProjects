# 🌤 Weather Data Analysis

This project analyzes a **time-series weather dataset** containing per-hour information about the weather conditions at a specific location.  
The dataset records **Temperature, Dew Point Temperature, Relative Humidity, Wind Speed, Visibility, Pressure, and Weather Conditions**.

Using **Python** and the **Pandas** library, we performed **data cleaning**, **exploration**, and answered a series of analytical questions.

---

## 📊 Dataset Overview

- **Format:** CSV
- **Frequency:** Hourly observations
- **Columns:**
  - **Date/Time:** Timestamp when the weather observation was recorded (M/D/YYYY H:MM).
  - **Temp_C:** Air temperature in °C.
  - **Dew Point Temp_C:** Temperature at which air becomes saturated (dew point) in °C.
  - **Rel Hum_%:** Relative humidity (%).
  - **Wind Speed_km/h:** Wind speed in kilometers per hour.
  - **Visibility_km:** Distance visible in kilometers.
  - **Press_kPa:** Atmospheric pressure in kilopascals.
  - **Weather:** Description of weather conditions (e.g., "Fog", "Rain", "Snow").

---

## 📝 Analysis Questions

We explored the dataset to answer the following:

1. Find all the unique **Wind Speed** values.
2. Count the number of times when the **Weather** is exactly "Clear".
3. Count the number of times when the **Wind Speed** was exactly `4 km/h`.
4. Identify all **Null Values** in the dataset.
5. Rename the column `Weather` to **Weather Condition**.
6. Find the **mean Visibility**.
7. Find the **Standard Deviation** of Pressure.
8. Find the **Variance** of Relative Humidity.
9. Find all instances when **Snow** was recorded.
10. Find all instances when **Wind Speed > 24 km/h** and **Visibility = 25 km**.
11. Find the **mean** value of each column for each Weather Condition.
12. Find the **minimum and maximum** value of each column for each Weather Condition.
13. Show all records where **Weather Condition** is Fog.
14. Find all instances when:
    - **Weather is Clear** OR **Visibility > 40 km**.
15. Find all instances when:
    - (Weather is Clear AND Relative Humidity > 50)  
      OR (Visibility > 40 km).

---

## 🛠 Tools & Libraries

- **Python**
- **Pandas** — Data cleaning and analysis
- **NumPy** — Numerical operations
- **Matplotlib / Seaborn** — Data visualization
- **Jupyter Notebook** — Interactive analysis

---

## 🚀 How to Run

1. Clone the repository:
   ```bash
   git clone https://github.com/sankajithdjinasena/DataAnalysisProjects.git
   ```
2. Navigate to the project folder:
   ```bash
   cd DataAnalysisProjects/WeatherDataAnalysis
   ```
3. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```
4. Open the notebook:
   ```bash
   jupyter notebook Weather_Data_Analysis.ipynb
   ```

---

## 📌 Sample Insights

- Identified seasonal trends in temperature and visibility.
- Found specific time periods with unusual wind speeds and pressure variations.
- Highlighted conditions such as fog and snow occurrences.

---

## 📜 License

This project is licensed under the [MIT License](LICENSE).

---
💡 *Data is like weather — ever-changing, but always telling a story.*
