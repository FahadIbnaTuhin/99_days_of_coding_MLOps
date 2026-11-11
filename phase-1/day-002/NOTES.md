Things I learnt: 
1) How to connect with google drive.
2) How to upload and then use a file using pandas. Here we used pd.read_csv function.
3) data.head() -> returns the first 5 rows from 0 to 4 
4) data.tail() -> returns the last 5 rows 
5) data.shape -> returns the total rows and col number of the dataset. 
6) data.info() -> returns a concise summary of a DataFrame.
7) data.describe() provides a statistical summary of numerical columns in a DataFrame.
8) data.min(numeric_only=True)  # Returns minimum values of each numerical column
9) data.max(numeric_only=True)  # Returns maximum values of each numerical column
10) data['target'].unique()  # Returns all unique (distinct) values in the target column
11) data.hist(figsize=(20, 15))
plt.show() means: 

data.hist() – Creates histograms for all numerical columns in the DataFrame to visualize their distributions.
figsize=(20, 15) – Sets the overall figure size to 20 inches wide and 15 inches tall.
plt.show() – Displays all generated histograms.
