# Bike Buyers Analysis
 
Excel analysis of 1,000 customers to find which demographic and lifestyle factors are linked to buying a bike. The project covers data cleaning, age grouping, pivot tables, and an interactive dashboard.
 
## Dataset
 
- 1,000 customers, 12 variables, no missing values or duplicate IDs.
- Variables: marital status, gender, income, children, education, occupation, home ownership, cars, commute distance, region, age, and whether the customer purchased a bike.
## Objectives
 
- Clean and standardise the raw data.
- Group customers by age bracket.
- Identify the factors linked to bike purchases.
- Present the results in a dashboard.
## Method
 
1. **Data cleaning**: fixed inconsistent labels (for example `Marrid` to `Married`, `Famle` to `Female`) and checked for blanks and duplicates.
2. **Age brackets**: created with an `IF` formula: under 31, 31 to 54, and 55 and over.
3. **Pivot tables**: purchase rate by age, marital status, cars, commute distance, region, education, and income.
4. **Dashboard**: pivot charts with slicers to filter by region, gender, and other fields.
## Key Findings
 
Overall purchase rate: **48%**.
 
| Factor | Highest purchase rate | Lowest purchase rate |
|---|---|---|
| Age | Middle age (31-54): 55% | 55 and over: 31% |
| Marital status | Single: 54% | Married: 43% |
| Cars owned | No car: 61% | 4 cars: 36% |
| Commute distance | 2-5 miles: 59% | Over 10 miles: 30% |
| Region | Pacific: 59% | North America: 43% |
| Education | Bachelors: 55% | Partial high school: 26% |
 
- Gender makes almost no difference (49% of women and 47% of men purchased).
- Income has a weak link: buyers average 57,963 and non-buyers 54,875.
- <img width="1047" height="632" alt="image" src="https://github.com/user-attachments/assets/b357b112-7f1d-4793-926c-4803b9eacae9" />

## Conclusion
 
Bike buyers are most likely middle-aged, single, living close to work, and owning few or no cars. Marketing could focus on these groups, especially in the Pacific region.
 
These results are descriptive. No statistical significance tests were run.
 
## Future Work
 
- Test the differences with chi-square tests and logistic regression.
- Build a classification model (for example logistic regression or random forest) to predict purchases.
## Tools
 
Microsoft Excel: formulas, pivot tables, slicers, and dashboard.
 
## Files
 
- `Excel_Project_Dataset.xlsx`: raw data, working sheet, pivot tables, and dashboard.
