# Health Insurance Exploratory Data Analysis
### Overview
This project presents a comprehensive exploratory data analysis (EDA) of insurance charges using a healthcare dataset containing over 1,000 individual records. The analysis investigates the relationship between several demographic factors (age, gender, BMI, smoking status, etc) and insurance costs to identify key drivers of healthcare expenses.

### Objective
Determine what factors most significantly influence individual insurance charges and how this information can inform pricing strategies.

### Key Findings

- **Age as a predictor of cost**: Age has a statistically significant postive correlation with insurance cost. However, weak correlation coefficient (r) and r-squared values suggest that multiple interacting variables may influence the relationship between age and insurance cost.
- **Smoking is the greatest cost driver**: Smokers incur much higher average costs than non-smokers, and while age is a statistically significant factor for smokers and non-smokers, its predictive power is substantially stronger for non-smokers than smokers (39.4% v 13.6%, respectively). This highlights the profound impact of smoking on insurance risk and cost variability.
- **BMI category reveals complex cost relationship**: As BMI categories deviated from the "normal" range, there was a clear trend of higher baseline insurance costs. Additionally, the further we deviated the smaller r and r-squared values became, illustrating an increase in cost variance. This trend suggests that other health compications associated with a higher BMI might be more significant cost drivers than age alone outside of the "normal" BMI category.
- **Impact of children on cost**: Clients with children have $1,565.25 higher insurance costs on average than those without children. However, weak r and r-squared values suggest that the relationship between child status and age is a weak predictor of rising insurance costs.
- **Impact of gender on cost**: While gender does account for a significant difference in the average insurance cost, the rate that insurance costs accrued over time was not significantly different between genders. Weak r and r-squared values again suggest that while gender is an important driver of insurance cost, the relationship between gender and age is a poor predictor of increasing insurance costs over time.

#### Dataset
**Source**: Sample dataset created for analytical purposes.
**Size**: 1,338 records x 7 variables.
**Data Quality**: Complete with no missing values, minimal duplicates (1 record removed).
**Variables**:
  - Age: age of the insured individual (18-64 years)
  - Sex: gender (male/female)
  - BMI: body mass index
  - Children: number of children
  - Smoker: smoking status (yes/no)
  - Region: geographic region of United States
  - Charges: individual medical costs billed by insurance
