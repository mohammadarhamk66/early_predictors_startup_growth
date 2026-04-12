# Early Predictors of Startup Growth

## Project Summary
This project investigates early-stage indicators of startup success using real-world funding data, with a focus on progression to a Series A funding round.

---

## Research Question
Which early-stage characteristics are associated with startup progression to a Series A funding round?

---

## Dataset
The analysis uses two datasets:
- Startup profile dataset  
- Funding events dataset  

These datasets were cleaned, standardized, and merged to create a unified dataset for analysis.

---

## Key Features
The following variables were engineered to represent early-stage characteristics:

- founders_count — number of founders per startup  
- num_funding_rounds — total number of funding rounds  
- early_total_funding — total early funding amount  
- unique_investors_count — number of unique investors  
- SeriesA_flag — indicates whether a startup reached Series A  

---

## Methods
- Data cleaning and preprocessing  
- Feature engineering  
- Exploratory data analysis  
- Comparative analysis of Series A vs non-Series A startups  

---

## Key Findings
- Startups with higher early funding are more likely to reach Series A  
- More funding rounds indicate stronger growth momentum  
- Higher investor count is associated with progression  
- Founding team size shows weaker impact  

---

## Project Structure

```
early_predictors_startup_growth/
├── data/
│   ├── Investors_DS1.csv
│   ├── Startups_funding_DS2.csv
│   └── startup_master_dataset.csv
│
├── notebooks/
│   └── early_predictors_startup_growth.ipynb
│
├── README.md
├── requirements.txt
└── .gitignore
```

3. Open the notebook:

notebooks/early_predictors_startup_growth.ipynb


---

## Tools Used
- Python  
- pandas  
- numpy  
- matplotlib  
- seaborn  
- Jupyter Notebook  

---

## Limitations
- Limited dataset size  
- Imbalanced outcome variable (few Series A cases)  
- Missing geographic data  
- Some variables are approximations of real-world factors  

---

## Conclusion
Early-stage funding activity and investor involvement are the strongest indicators 
