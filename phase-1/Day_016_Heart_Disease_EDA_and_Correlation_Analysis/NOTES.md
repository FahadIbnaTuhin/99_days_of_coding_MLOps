# Day-016: Heart Disease EDA

## What I Learned

- Loading CSV files using `pd.read_csv()`.
- Exploring datasets using `head()`, `info()` and `describe()`.
- Checking missing values using `isnull().sum()`.
- Handling missing numerical values using `fillna()` with the mean.
- Understanding relationships using scatterplots.
- Keeping the X-axis fixed (`age`) while changing four Y-axis columns:
  - `trestbps`
  - `chol`
  - `thalch`
  - `oldpeak`
- Understanding the difference between `y` and `hue` in Seaborn:
  - `y` represents a numerical variable on the vertical axis.
  - `hue` separates data into groups using different colours.
- Observing positive/negative relationships, clusters and outliers.

## Dataset

Heart Disease Dataset (Kaggle).

## Notebook

`Day-016_Heart_Disease_EDA_and_Correlation_Analysis.ipynb`
