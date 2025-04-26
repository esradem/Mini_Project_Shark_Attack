
# Shark Attack Data Analysis

 Welcome to the **Shark Attack Data Analysis** project!

This project explores, cleans, and analyzes real-world shark attack records to uncover patterns, trends, and insights. It’s designed for practicing data wrangling and basic exploratory data analysis (EDA) techniques.

---

##  Project Overview

- Load shark attack incident data from an Excel file
- Understand the structure and contents of the dataset
- Identify missing values and data inconsistencies
- Filter and analyze fatal shark attacks
- Group and rank fatal attacks by country and activity
- Prepare the dataset for further analysis and visualization

---

##  Dataset

- **Source**: Global Shark Attack File (GSAF)
- **File**: `GSAF5.xls`
- **Description**: Records of shark attacks worldwide, with details like date, location, activity, species, and outcome.

---

##  Technologies Used

- **Python**
- **Libraries**:
  - pandas
  - numpy
  - re

---

##  Current Progress

- **Data loading and exploration**:
  - Viewed first and last entries
  - Checked data types, missing values, and basic statistics
- **Data filtering**:
  - Selected only fatal shark attacks (`Fatal == 'Y'`)
  - Excluded generic activities (`Activity != 'other'`)
- **Grouping and analysis**:
  - Grouped fatal attacks by `Country` and `Activity`
  - Counted and sorted the number of fatal attacks
- **Prepared dataset** for more detailed analysis and visualizations

---

## Future Plans

- Clean and preprocess the dataset further (e.g., standardize country and activity names)
- Create visualizations:
  - Top countries with the most fatal attacks
  - Activities most associated with fatal attacks
- Perform time series analysis (e.g., attacks over years)
- (Optional) Build predictive models


---

##  How to Run Locally

1. Clone this repository:
   ```bash
   git clone https://github.com/yourusername/shark-attack-analysis.git
   cd shark-attack-analysis
   ```

2. Install the required libraries:
   ```bash
   pip install pandas numpy openpyxl
   ```

3. Open the Jupyter Notebook:
   ```bash
   jupyter notebook shark_attack_pro.ipynb
   ```

---

##  License

This project is for educational purposes only.

---

## Acknowledgements

- Global Shark Attack File (GSAF) for providing the dataset.
