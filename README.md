# Project Overview

This project explores the key variables influencing individual hourly wages and builds a predictive model to estimate wages based on demographic, occupational, and regional factors. The dataset contains 526 validated records of individuals in the U.S., including information on education, experience, tenure, number of dependents, industry, occupation, region, and more.

# Key Findings

Gender Gap: Males tend to earn more than females across most industries and regions. Wage disparity is also linked to differences in education levels and occupation types.

Education & Experience: Wage increases with education and experience, but effects are nonlinear and differ by gender. For males, more education and experience lead to higher wages; for females, the relationship is more complex.

Location & Industry: Metropolitan areas and Western regions show higher average wages. Professional occupations and "Other" industries generally pay more.

Modeling: A linear regression model using log-transformed wages achieved an adjusted R² of 0.556. The model includes interaction terms and polynomial features to capture nonlinear effects.

# Steps performed (please refer to the code attached)

•		Data cleaning and verification (16 rows removed)

•		Outlier investigation

•		Exploratory data analysis across key dimensions

•		Log transformation of the wage variable to correct skewness

•		Squared terms applied for education and experience

•		Model evaluation and interpretation

# Results

Education increases wages by ~5% per year for males; for females, higher education (edu²) matters more than basic years.

Experience positively impacts wages for both genders, with diminishing returns.

Metropolitan areas add ~15% wage premium; Western region adds ~9%.

Being in a professional occupation increases wages by ~16%; service roles reduce wages by ~10%.

Residuals for females show a modest non-uniform spread, suggesting that some variance in female wages may not be fully captured with currently available variables.

# Recommendations

### To enhance model performance and better explain wage variance, adding further information could be beneficial:

•		Include career level (e.g., junior, mid, senior roles)

•		Add years in current career (not just total experience or tenure)

•		Account for maternity or career breaks, especially for female population

•		Expand industry classifications 

•		Add age or birth year to improve demographic modeling

•		Include more granular location
