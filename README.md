# Stack Overflow Developer Survey 2025 — High Salary Analysis (CRISP-DM)

## Project Motivation
Analyze which factors are associated with higher annual compensation using the Stack Overflow Developer Survey 2025.

## Dataset
Stack Overflow Annual Developer Survey 2025 (`survey_results_public.csv`, `survey_results_schema.csv`).

## Files
- `analysis.ipynb`: notebook with full CRISP-DM workflow (EDA, cleaning, modeling, evaluation, scenario).
- `survey_results_schema.csv`: data dictionary (questions per column).
- (Optional) `images/`: exported plots for README/blog.

## Libraries
pandas, numpy, matplotlib, seaborn, scikit-learn

## Summary of Results
- Baseline Logistic Regression AUC ~ 0.689, accuracy ~ 0.63
- Key positive signals: senior roles, large org size
- Key negative signals: student status, very small org size, in-person work

## Blog Post
<pon aquí el link a tu post>

## Acknowledgements
Thanks to Stack Overflow for making the survey data publicly available.
