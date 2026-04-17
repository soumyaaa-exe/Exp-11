AIM
✦ To load and analyze the given dataset using Python’s Pandas library. ✦ To study the structure, statistical properties, and quality of data using various built-in functions. ✦ To identify missing values, duplicates, and gain meaningful insights from the dataset.

THEORY
Data analysis is a systematic process of examining, cleaning, transforming, and interpreting data to discover useful information and support decision-making.
In Python, the powerful Pandas library is widely used for handling structured data efficiently. The dataset is stored in a CSV (Comma Separated Values) format, which organizes data in a tabular form and can be easily loaded into a DataFrame — a two-dimensional structure consisting of rows and columns, similar to an Excel sheet.
To understand and explore the dataset, several essential functions are used:

🔹 Data Preview Functions

df.head() → Displays the first 5 records df.tail() → Displays the last 5 records df.sample() → Displays random records

🔹 Structural Analysis

df.shape → Returns number of rows and columns df.size → Returns total number of elements df.info() → Provides column names, data types, and non-null counts

🔹 Statistical Analysis

df.describe() → Generates summary statistics such as mean, minimum, maximum, and standard deviation

🔹 Data Quality Checks

df.isnull().sum() → Identifies missing values df.duplicated().sum() → Detects duplicate rows df.nunique() → Counts unique values in each column

CONCLUSION
✦ The dataset was successfully loaded and analyzed using the Pandas library. ✦ The structure, data types, and statistical features of the dataset were clearly understood. ✦ Missing values and duplicate entries were identified, emphasizing the need for data cleaning. ✦ Overall, the analysis provides a strong foundation for further data processing, visualization, and intelligent decision-making.
