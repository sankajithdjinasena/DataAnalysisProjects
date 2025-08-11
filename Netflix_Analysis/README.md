# Netflix Dataset Analysis

## 📌 Overview
This project analyzes the **Netflix Dataset** which contains detailed information about Movies and TV Shows available on Netflix. The data was collected from **Flixable**, a third-party Netflix search engine.  
We explore patterns, trends, and answer analytical questions using Python and data visualization.

## 📂 Dataset Description
The dataset includes the following columns:

- **Show_Id**: Unique ID for each title
- **Category**: Movie or TV Show
- **Title**: Name of the movie/show
- **Director**: Director(s) of the title
- **Cast**: Main actors and actresses
- **Country**: Country of origin
- **Release_Date**: Date the content was made available on Netflix
- **Rating**: Maturity rating (e.g., TV-MA, PG-13, R)
- **Duration**: Movie length (in minutes) or number of seasons
- **Type**: Genre(s) of the title
- **Description**: Brief summary of the title

## 🎯 Questions Answered
1. For 'House of Cards', what is the Show Id and Who is the Director?
2. In which year were the highest number of TV Shows & Movies released? *(Bar Graph)*
3. How many Movies & TV Shows are in the dataset? *(Bar Graph)*
4. Show all the Movies released in year 2000.
5. Titles of all TV Shows released in India only.
6. Top 10 Directors with the most TV Shows & Movies on Netflix.
7. Records where *(Category is Movie and Type is Comedies)* or *(Country is United Kingdom)*.
8. How many movies/shows feature **Tom Cruise**?
9. Different Ratings defined by Netflix.
   - How many Movies got 'TV-14' rating in Canada?
   - How many TV Shows got 'R' rating after 2018?
10. Maximum duration of a Movie/Show on Netflix.
11. Country with the highest number of TV Shows.
12. Sort the dataset by Year.
13. Instances where *(Category is 'Movie' and Type is 'Dramas')* or *(Category is 'TV Show' and Type is 'Kids' TV')*.

## 🛠 Tools & Libraries Used
- **Python** (Pandas, NumPy)
- **Matplotlib** & **Seaborn** for visualization
- **Jupyter Notebook** for coding & exploration

## 📊 Project Workflow
1. **Data Loading & Cleaning** – Handling missing values, formatting dates, and correcting inconsistencies.
2. **Exploratory Data Analysis (EDA)** – Descriptive stats, filtering, grouping, and visualizing data.
3. **Question-Based Analysis** – Answering all the listed queries using Python.
4. **Data Visualization** – Creating bar charts, count plots, and more.

## 🚀 How to Run
1. Clone the repository:
   ```bash
   git clone https://github.com/sankajithdjinasena/DataAnalysisProjects.git
   ```
2. Navigate to the project folder:
   ```bash
   cd DataAnalysisProjects/Netflix_Analysis
   ```
3. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```
4. Open the Jupyter Notebook:
   ```bash
   jupyter notebook Netflix_Analysis.ipynb
   ```

## 📌 Source
Dataset sourced from Kaggle: *Netflix Movies and TV Shows* (via Flixable)

---
📌 **Author:** Sankajith D. Jinasena
