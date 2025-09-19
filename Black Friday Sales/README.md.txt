# Black Friday Sales — Exploratory Data Analysis


Repository: `black-friday-sales-analysis`


# Overview
This repository contains an exploratory data analysis (EDA) of a Black Friday sales dataset. The analysis focuses on customer demographics, product categories, and purchase behaviors using Python (Pandas, Matplotlib, Seaborn) inside a Jupyter Notebook.


Notebook: `notebooks/BlackFridaySales.ipynb`
Dataset: `data/BlackFriday.csv`


# Dataset (quick facts)
- Rows: 537,577
- Columns: 12
- Columns: `User_ID`, `Product_ID`, `Gender`, `Age`, `Occupation`, `City_Category`, `Stay_In_Current_City_Years`, `Marital_Status`, `Product_Category_1`, `Product_Category_2`, `Product_Category_3`, `Purchase`
- Missing values detected from notebook outputs:
- `Product_Category_2`: 370,591 non-null (missing **166,986**)
- `Product_Category_3`: 164,278 non-null (missing **373,299**)


---


## What I did
The notebook performs the following steps (section headings in the notebook):
- Import libraries & load data
- Getting the data
- Analyzing data
- Analyzing the Gender column
- Analysis on Age and Marital status
- Multi Column Analysis
- Occupation and Product Analysis
- Combining Gender and Marital Status Analysis


(Open `notebooks/BlackFridaySales.ipynb` for the full step-by-step analysis and plots.)*


---


# Key insights (short summary)
> Replace the placeholder bullets below with the exact numbers and insights from the notebook after reviewing visualizations.


- Customers are mainly distributed across age groups `XX-YY` and `...`.
- Gender-wise purchase behavior: (e.g., males purchased more frequently / average purchase higher for X).
- Product category 1 covers all entries; categories 2 and 3 have many missing values — treated with ... (explain your approach).
- Top occupations by total purchase: (list top 3 from notebook)


---


## How to run
1. Clone the repo
```bash
git clone https://github.com/yourusername/black-friday-sales-analysis.git
cd black-friday-sales-analysis
