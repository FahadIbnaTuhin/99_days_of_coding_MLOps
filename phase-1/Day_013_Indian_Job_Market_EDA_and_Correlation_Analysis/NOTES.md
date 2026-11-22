# Day-013: Indian Job Market EDA

## What I Learned

- Reading Excel (`.xlsx`) files using `pd.read_excel()`.
- Understanding dataset columns and their meanings.
- Exploring job titles using `value_counts()`.
- Checking missing values using `isnull().sum()`.
- Understanding numerical data using `describe()` and `info()`.
- Handling missing numerical values using `fillna()` with the mean.
- Avoiding Pandas `FutureWarning` by assigning the result back to the column.
- Creating scatterplots using Seaborn.
- Analysing relationships between:
  - `minimumExperience` and `minimumSalary`
  - `minimumExperience` and `maximumSalary`
  - `minimumExperience` and `AggregateRating`
  - `minimumExperience` and `ReviewsCount`
- Identifying positive/negative relationships, clusters, outliers and data spread.

All four plots show how **required experience (**`minimumExperience`**) relates to other numerical columns**.

| Plot                         | What it tells you                                                                                            | What to notice                                         |
| ---------------------------- | ------------------------------------------------------------------------------------------------------------ | ------------------------------------------------------ |
| Experience vs Minimum Salary | Whether more experience is associated with higher minimum salary.                                            | Does salary increase as experience increases?          |
| Experience vs Maximum Salary | Whether more experience is associated with higher maximum salary.                                            | Do experienced jobs offer higher salary ceilings?      |
| Experience vs Company Rating | Whether companies advertising jobs with different experience requirements have different ratings.            | Are ratings concentrated around a particular value?    |
| Experience vs Reviews Count  | Whether companies advertising jobs with different experience requirements have different numbers of reviews. | Are most companies clustered around low review counts? |

### **Key things to notice in every scatterplot**

1. **Direction:** Positive (upward), negative (downward), or no clear relationship.
2. **Clusters:** Where most points are concentrated.
3. **Outliers:** Points unusually far from the others.
4. **Spread:** How widely the values are distributed.

**Remember:** A relationship doesn't prove that one variable causes another. Also, company ratings and review counts don't directly measure job quality or hiring demand.
