# Experiment_No.14
## Aim: To study and implement data binning and data formatting techniques using Python libraries such as Pandas and NumPy.

## Theory:
# Data Binning:
Data binning is a preprocessing technique used to group continuous numerical values into discrete intervals or categories. It helps in simplifying data and improving analysis.
Performed using pd.cut() function
Converts numerical data into categorical data
# Data Formatting:
Data formatting involves modifying the structure, type, or appearance of data for better readability and processing.
It includes:
* Changing data types
* Formatting strings
* Sorting data
* Rounding values
  
## Function	Used:
pd.DataFrame() - Creates tabular data structure
pd.cut() - Performs binning
astype() - Changes data type
.str.upper() - Converts text to uppercase
.round() -	Rounds values
sort_values() - 	Sorts data
value_counts()	Counts categories
unique()	Finds unique values

Data binning simplifies complex data
Data formatting enhances readability
These techniques are essential in data preprocessing and analysis.

Data formatting is a crucial step in data preprocessing because raw data is often inconsistent, messy, and difficult to analyze. 
Proper formatting ensures that data is clean, structured, and ready for analysis using tools like Pandas.

1. Improves Data Quality
Raw data may contain:
Inconsistent formats (e.g., numbers stored as text)
Missing or incorrect values
Mixed data types
Therefore If not formatted properly, calculations may give errors or incorrect results.

2. Enables Accurate Analysis
Many operations like:
Mathematical calculations
Statistical analysis
Machine learning require properly formatted data. Formatting makes data computable and analyzable

3. Ensures Consistency
Data collected from different sources often has:
Different formats
Different naming conventions
 Formatting standardizes data into one format, avoiding confusion


