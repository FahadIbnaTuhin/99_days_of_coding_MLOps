Day-018: Fake Job Postings Dataset

Three Findings:
1. I compared job experience levels with fraudulent postings to see which experience categories had more fake and genuine jobs.
2. I compared employment types and observed how fraudulent and genuine postings were distributed across different job types.
3. I compared education requirements and remote-work availability to understand whether these features showed any noticeable differences between fake and genuine postings.

One Data Quality Issue:
The required_experience column contained missing values. Since it is a categorical column, I couldn't use mean() to fill them. I learned that I can use mode() or replace missing values with "Unknown".

Three-Line Reflection:
What I built: I built a simple EDA notebook and used four Seaborn countplots to compare genuine and fraudulent job postings.
What broke: I initially tried to fill missing values in required_experience using mean(), but it didn't work because the column contained text categories.
What I learned: I learned how to handle missing categorical values and use countplot() with hue to compare two groups across different categories.

