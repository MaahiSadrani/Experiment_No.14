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
# Dataset 2: Food Delivery Data
This dataset includes:
* Order value
* Delivery time
* Distance
Binning was applied to multiple features:
 Order Value Categorization
* Classifies order size into Low, Medium, High
 Delivery Speed Categorization
* Based on delivery time:
  * Fast
  * Medium
  * Slow
 Distance Categorization
* Groups distances into:
  * Short
  * Medium
  * Long
Shorter distances generally correspond to faster deliveries, while longer distances tend to align with slower delivery speeds, showing a practical relationship between variables.
 4. Data Types and Categorical Conversion
After binning, columns are converted into **categorical data types**.
Advantages:
* Reduced memory usage
* Better performance
* Efficient category-based analysis
 5. Data Formatting
Data formatting ensures consistency and correctness in the dataset.
 Data Type Conversion
* Integer values were converted to float where required to allow flexible numerical operations
 Text Standardization
* Text values were converted to uppercase to maintain uniformity and avoid duplication
 Rounding Values
* Numerical values were rounded for consistency and readability
 6. Sorting and Data Organization
Sorting improves readability and helps identify trends.
* Products were sorted based on price (descending)
* Orders were sorted based on order value (ascending)
This makes comparison and analysis more structured.

 7. Frequency Analysis
Frequency distribution helps understand how data is spread across categories.
* Most deliveries fall under the **Fast** category
* Distance distribution is concentrated in Medium and Long ranges
* Order categories are relatively balanced

 Commands Used & Explanation:
Data Binning
* `pd.cut()` → Converts continuous data into categorical bins
 Data Type Handling
* `df.dtypes` → Displays data types
* `astype()` → Converts data types
Data Formatting
* `str.upper()` → Standardizes text
* `round()` → Rounds numerical values
 Data Analysis
* `value_counts()` → Counts category frequency
* `unique()` → Displays unique values
 Data Sorting
* `sort_values()` → Sorts dataset based on a column

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

Conclusion:

