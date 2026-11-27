
# Day-013: Fake Job Postings Dataset

## What I Learned
- Loading and exploring a new dataset using Pandas.
- Checking missing values and duplicate records.
- Understanding numerical and categorical columns.
- Handling missing categorical values using `mode()` or `"Unknown"`.
- Performing Exploratory Data Analysis (EDA).
- Comparing genuine and fraudulent job postings using Seaborn `countplot()`.

## Seaborn Comparisons

Fixed comparison column: `fraudulent`

- `required_experience` vs `fraudulent`
- `employment_type` vs `fraudulent`
- `required_education` vs `fraudulent`
- `telecommuting` vs `fraudulent`

## Key Concept
- `fraudulent = 0`: Genuine job posting
- `fraudulent = 1`: Fraudulent job posting
- `mean()` is for numerical data.
- `mode()` is useful for filling missing categorical values.
- `countplot()` compares category counts using `hue`.
