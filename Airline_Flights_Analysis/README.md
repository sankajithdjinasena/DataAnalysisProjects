# Airlines Flights Dataset Analysis

## 📌 Overview
The **Airlines Flights Dataset for Different Cities** contains structured, scraped data of flight travel details between Indian cities.  
It includes information such as airlines, source & destination cities, departure & arrival times, duration, ticket prices, and more.

This dataset is valuable for **airlines, travel companies, and data analysts** to understand trends in pricing, flight schedules, and booking behavior.

The dataset is available as a **CSV file** and is analyzed using Python’s **Pandas** library along with **Matplotlib** and **Seaborn** for data visualization.

---

## 📊 Dataset Features

| Column Name       | Description |
|-------------------|-------------|
| **Airline**       | Name of the airline company (categorical - 6 unique airlines). |
| **Flight**        | Flight code (categorical). |
| **Source City**   | City where the flight departs from (categorical - 6 cities). |
| **Departure Time**| Categorical label representing departure time periods (6 categories). |
| **Stops**         | Number of stops between source and destination (categorical - 3 values). |
| **Arrival Time**  | Categorical label representing arrival time periods (6 categories). |
| **Destination City** | City where the flight lands (categorical - 6 cities). |
| **Class**         | Type of seat (Business or Economy). |
| **Duration**      | Total travel time in hours (continuous). |
| **Days Left**     | Days left between booking and departure (continuous, derived). |
| **Price**         | Ticket price (target variable). |

---

## 📝 Project Questions & Analysis

1. **What are the airlines in the dataset, and their frequencies?**
2. **Bar Graph**: Departure Time distribution.
3. **Bar Graph**: Arrival Time distribution.
4. **Bar Graph**: Source City distribution.
5. **Bar Graph**: Destination City distribution.
6. Does ticket **price vary with airlines**?
7. Does ticket **price change based on departure & arrival times**?
8. How does **price change with Source & Destination**?
9. How is the price affected when tickets are bought **1–2 days before departure**?
10. How does the **ticket price vary between Economy and Business class**?
11. What is the **average price** of a **Vistara** flight from **Delhi to Hyderabad** in **Business Class**?

---

## 🛠 Tools & Libraries Used
- **Python**
- **Pandas** – Data manipulation and analysis
- **NumPy** – Numerical operations
- **Matplotlib** – Data visualization
- **Seaborn** – Statistical visualizations

---

## 📈 Example Visualizations
- **Bar Charts** for categorical variables (Airlines, Cities, Time periods)
- **Boxplots** for price comparisons across classes and airlines
- **Scatter plots** for price vs. duration
- **Heatmaps** for correlation analysis

---

## 🚀 How to Run
1. Clone the repository:
   ```bash
   git clone https://github.com/sankajithdjinasena/DataAnalysisProjects.git
   ```
2. Navigate to the project folder:
   ```bash
   cd DataAnalysisProjects/Airline_flight_Analysis
   ```
3. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```
4. Open the Jupyter Notebook:
   ```bash
   jupyter notebook Airline_Analysis.ipynb
   ```

## 📌 Source
This dataset was collected from a **famous Indian flight booking website** and structured for analysis.

---

## 📜 License
This dataset is for **educational and research purposes only**.  
Not intended for commercial use.

---
📌 **Author:** Sankajith D. Jinasena
