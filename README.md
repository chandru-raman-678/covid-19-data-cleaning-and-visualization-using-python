# COVID-19 Data Analysis and Visualization  
**📅 Project Duration: October 2025**

<p align="center">
  <img src="https://raw.githubusercontent.com/chandru-raman-678/covid-19-data-cleaning-and-visualization-using-python/main/Screenshot%202026-05-02%20172838.png" width="45%">
  <img src="https://raw.githubusercontent.com/chandru-raman-678/covid-19-data-cleaning-and-visualization-using-python/main/Screenshot%202026-05-02%20174620.png" width="45%">
</p>

<p align="center"><b>Proof of Project Work & Timeline</b></p>

---

## Overview  
This project presents a comprehensive analysis of the evolution of COVID-19 cases in India from **2020 to 2022**, developed during **October 2025**.  

The primary objective is to explore trends in confirmed, recovered, and death cases, perform thorough data cleaning, and generate meaningful visualizations to better understand the pandemic’s impact across the country.  

The project is implemented using **Python**, leveraging libraries such as **Pandas**, **NumPy**, and **Matplotlib**, and follows a structured workflow from raw data processing to insightful visual analysis.

---

## Dataset  
The dataset includes COVID-19 statistics for India, covering:  

- Daily confirmed cases  
- Recovered cases  
- Death cases  
- Vaccination data (if available)  
- Regional/state-level information  

The raw dataset may contain missing values, duplicates, and inconsistencies, which are handled during preprocessing.

---


---

## Data Cleaning  

A reusable data cleaning pipeline ensures the dataset is accurate and consistent:

1. **Load Data** – Read CSV files using Pandas and inspect structure  
2. **Trim Whitespace** – Standardize text columns  
3. **Drop Empty Rows** – Remove rows missing key fields (`iso_code`, `continent`, `location`)  
4. **Handle Missing Values**  
   - Numeric columns → fill with `0`  
   - Categorical columns → fill with mode or `'Unknown'`  
5. **Remove Duplicates** – Eliminate repeated records  
6. **Save Cleaned Data** – Export processed dataset  
7. **Summarize Dataset** – Display shape, columns, and data types  

---

## Data Visualization  

Visualizations were created using **Matplotlib** to uncover trends and patterns:

- Time-series plots of confirmed, recovered, and death cases (2020–2022)  
- Monthly and yearly comparisons to identify peaks and declines  
- Identification of major COVID-19 waves (e.g., Delta wave in 2021)  
- Analysis of recovery trends and vaccination impact  
- Use of line charts, bar graphs, and area plots for clear interpretation  

---

## Tools and Libraries  

- **Python 3.x**  
- **Pandas**  
- **NumPy**  
- **Matplotlib**  
- **Jupyter Notebook**  

---

## Key Insights  

- **2020:** Initial outbreak with rapid growth in cases  
- **2021:** Significant surge during the Delta wave with peak infections  
- **2022:** Decline in cases and improved recovery rates due to vaccination and public health measures  
- Visualizations highlight temporal and regional patterns across India  
- Clean and structured data enables accurate analysis  

---

## Conclusion  

This project demonstrates the importance of data cleaning, analysis, and visualization in understanding real-world scenarios like the COVID-19 pandemic. It provides a scalable and reusable workflow for similar data analysis projects.
