# Stack Overflow Developer Survey 2025 — High Salary Analysis (CRISP-DM)

## Project Motivation
Analyze which factors are associated with higher annual compensation using the Stack Overflow Developer Survey 2025.

## Dataset
Stack Overflow Annual Developer Survey 2025 (`survey_results_public.csv`, `survey_results_schema.csv`).

## Files
- `analysis.ipynb`: notebook with full CRISP-DM workflow (EDA, cleaning, modeling, evaluation, scenario).
- `survey_results_schema.csv`: data dictionary (questions per column).

## Libraries
pandas, numpy, matplotlib, seaborn, scikit-learn

## Summary of Results
- Baseline Logistic Regression AUC ~ 0.689, accuracy ~ 0.63
- Key positive signals: senior roles, large org size
- Key negative signals: student status, very small org size, in-person work

## Blog Post
https://medium.com/@h.whitez/new-data-science-proyect-crisp-dm-what-predicts-a-high-salary-551bda444e80

## Data Source
This project uses the Stack Overflow Developer Survey 2025 dataset.

Download the data from the official source:
https://survey.stackoverflow.co/

Files needed:
- survey_results_public.csv
- survey_results_schema.csv

## How to run
1) Download the CSV files from the link above.
2) Place `survey_results_public.csv` and `survey_results_schema.csv` in the same folder as the notebook (or in a /data folder).
3) Run `analysis.ipynb`.

## Acknowledgements
Thanks to Stack Overflow for making the survey data publicly available.

## Note
survey_results_public.csv is not included in this repo due to GitHub size limits

