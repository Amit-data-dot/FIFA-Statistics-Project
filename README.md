# FIFA-Statistics-Project
---

# Project Description 
The objective of this project is to perform an end-to-end data analytics study using Python and Pandas, focusing on statistical methods to analyze distributions, detect anomalies, estimate population parameters, and validate statistical theorems. The project aims to provide actionable insights for stakeholders such as football scouts, team managers, and game developers by exploring relationships between player attributes and their market value, demographic trends, and performance distributions.

---

# About Data
**rows:** 18,207
**columns:** 88
**File used:** `Game.xlsx`
**Sheeet Name:** Game_data
---
##  Data Information
### *Key Columns*
**ID :** Unique player identifier
**Name:** Player name
**Age:** Player age
**Nationality:** Player's country of origin
**Overall:** Current performance rating
**Potential:** Potential performance rating
**Club:** Current club
**Wage:** Weekly wage (in €, with 'K' or 'M' suffixes)
**Weight:** Player weight (in lbs)
**Position:** Player's field position (e.g., ST, GK, CM)
**Additional Attributes:** Skills (e.g., Dribbling, Passing), physical metrics, and contract details
---
# Cleaning steps performed
- Converted **Wage** values from text (e.g., “€200K”, “€1M”) to numeric  
- Extracted numeric values from *Weight* (e.g., “150lbs”)  
- Standardized column formats  
- Removed or treated missing values  
- Converted text-based numeric fields into appropriate numeric types  
- Cleaned skill and physical attributes for consistent processing
  ---
  
  # Impurities removed
- Inconsistent financial formats resolved  
- Weight and Wage standardized into numeric values  
- Removed irrelevant characters from numerical columns  
- Fixed formatting inconsistencies in height, weight, and financial fields  
- Dropped or imputed missing/irrelevant values  

---
## Insights

- **Wage Outliers:** Only a small cluster of elite players dominate top wage brackets  
- **Potential Distribution:** Near-normal with slight left skew  
- **Correlation:** Strong positive correlation between Potential and Wage  
- **Age by Position:** Goalkeepers tend to be older; forwards are typically younger  
- **Top Nationalities:** Reflect strong football nations dominating professional leagues  
- **Skill Influence:** Finishing, Dribbling, and Passing strongly affect Overall and Potential  
- **Club-Level Wages:** High-wage clubs align with high-performance squads  
- **Potential Growth:** Younger players, especially forwards, show higher development capacity  
- **Hypothesis Result:** Players with higher International Reputation earn significantly more  
---

## Tools & Libraries Used
- **Python** – Core programming  
- **Pandas** – Data preprocessing & manipulation  
- **NumPy** – Numerical computations  
- **Matplotlib & Seaborn** – Visualization  
- **SciPy** – Statistical distributions & hypothesis testing  
- **Jupyter Notebook** - Analysis Environment






  
