The notebook is structured as follows:

Sections Overview
Section 1: Title/Objective
The objective of the notebook is stated: "Crop and Fertilizer recommendation using machine learning".
Section 2: Library Imports
Key libraries like pandas, numpy, seaborn, and matplotlib are imported for data analysis and visualization.
Section 3: Dataset Loading
The dataset Crop_recommendation.csv is loaded into a pandas DataFrame.
Section 4 & 5: Previewing the Data
df.head(): Displays the first few rows of the dataset.
df.tail(): Displays the last few rows of the dataset.
Section 6: Dataset Information
df.info(): Shows information about the dataset, including column names, non-null counts, and data types.
Section 7: Statistical Summary
df.describe(): Provides a statistical summary of the numerical columns (mean, min, max, etc.).
Section 8: Missing Values
df.isnull().sum(): Checks for missing values in each column.
Section 9: Column Names
df.columns: Lists the column names in the dataset.
Section 10: Dataset Shape
df.shape: Displays the number of rows and columns in the dataset.
Section 11: Label Analysis
df['label'].value_counts(): Examines the distribution of labels in the dataset, likely representing different crops.
