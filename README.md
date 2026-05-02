# COVID-19 Data Analysis and Visualization                                           ## Project Duration: October 2025
## Overview
This project analyzes the evolution of COVID-19 cases in India from **2020 to 2022**.  
The goal is to explore trends in confirmed, recovered, and death cases, perform data cleaning and preparation, and generate meaningful visualizations to understand the pandemic’s impact.

The project uses **Python**, leveraging libraries such as **Pandas**, **NumPy**, and **Matplotlib** for data handling and visualization. It provides a structured workflow from raw data cleaning to insightful visual plots.

---

## Dataset
The dataset includes COVID-19 statistics for India, covering:  
- Daily confirmed cases  
- Recovered cases  
- Death cases  
- Vaccination data (if available)  
- Regional/state-level information  

The raw dataset may contain missing values, duplicates, and inconsistencies, which are handled in the cleaning process.

---

## Project Structure
- `data/` : Folder containing raw COVID-19 datasets.  
- `cleaned_data/` : Folder for storing cleaned datasets after preprocessing.  
- `notebooks/` : Jupyter Notebook files for data cleaning and visualization.  
- `README.md` : Project documentation.  
- `requirements.txt` : List of Python dependencies.

---

## Data Cleaning
The data cleaning pipeline ensures the dataset is accurate and consistent. The key steps include:

1. **Load Data**: Read CSV files using Pandas and inspect the dataset structure.  
2. **Trim Whitespace**: Remove extra spaces in text columns for consistency.  
3. **Drop Empty Rows**: Remove rows where important columns like `iso_code`, `continent`, or `location` are missing.  
4. **Handle Missing Values**:  
   - Numeric columns are filled with `0`.  
   - Categorical columns are filled with the mode or `'Unknown'`.  
5. **Remove Duplicates**: Delete repeated rows to avoid bias.  
6. **Save Cleaned Data**: Export the cleaned dataset for further analysis.  
7. **Summarize**: Display information about the final dataset including shape, columns, and types.

This pipeline is implemented as a **reusable Python function** that can be executed for any similar dataset.

---

## Data Visualization
After cleaning, the dataset is visualized using **Matplotlib** to identify trends and patterns. The main objectives are:  

- Plot confirmed, recovered, and death cases over time (2020–2022).  
- Compare yearly and monthly trends to highlight peaks and declines.  
- Identify major COVID-19 waves, such as the Delta variant surge in 2021.  
- Observe recovery trends and the potential impact of vaccinations.  
- Generate clear line, bar, and area charts for easy interpretation.

---

## Tools and Libraries
- **Python 3.x** – Programming language for analysis.  
- **Pandas** – Data loading, cleaning, and manipulation.  
- **NumPy** – Handling numerical computations and missing values.  
- **Matplotlib** – Plotting and visualization of trends.  
- **Jupyter Notebook** – Interactive development and analysis environment.

---

## Key Insights
- **2020:** Initial outbreak of COVID-19 with rapid case increase.  
- **2021:** Major surge during the Delta wave, peak confirmed cases.  
- **2022:** Decline in new cases and higher recovery rates due to vaccination and public health measures.  
- Visualizations reveal temporal and regional patterns across India.  
- Cleaned and structured data enables accurate trend analysis and comparisons.

