#  Titanic Data Analysis with Pandas & NumPy

This project performs exploratory data analysis (EDA) on the famous Titanic dataset using **Python**, **Pandas**, **NumPy**, and **Matplotlib**.  
It focuses on cleaning missing data, summarizing passenger statistics, and visualizing relationships between variables such as age, fare, and passenger class.

---

##  Overview

The Titanic dataset contains passenger details such as name, age, class, gender, fare, and survival information.  
In this analysis, we:

- Loaded and inspected the dataset
- Cleaned missing and inconsistent data
- Explored numerical and categorical features
- Visualized distributions and relationships

---

##  Technologies Used

- **Python 3**
- **Pandas**
- **NumPy**
- **Matplotlib**
- **Jupyter Notebook**

---

##  Data Cleaning Steps

1. Removed rows with critical missing fields
2. Filled missing `Age` values with the **median**
3. Filled missing `Fare` values with the **mean**
4. Dropped the `Cabin` column (too many missing values)
5. Converted columns to proper numeric formats

---

## Key Visualizations

- **Age Distribution** (Histogram)
- **Fare Distribution** (Histogram)
- **Fare vs Age Scatter Plot**
- **Top 20 Most Frequent Ages** (Bar Chart)

These help reveal basic patterns in passenger demographics and fare structures.

---

##  Quick Start

### Clone and Run Locally

```bash
git clone https://github.com/<your-username>/titanic-analysis.git
cd titanic-analysis
pip install -r requirements.txt
jupyter notebook titanic.ipynb
