# DataAnalitics_Learning_Week-3

# CONCEPT DATA
"Data" refers to the information used by a computer program to perform operations, processing, and decision-making. Data can come in various types, such as numbers, text, boolean (true/false), objects, or more complex data structures.

In programming, data can be processed, manipulated, and stored in various ways according to the needs of the application being built. This enables programs to perform specific tasks, such as mathematical calculations, text manipulation, or user information management.

When working with data in programming, it's important to pay attention to the data types, formats, and validity to ensure the accuracy and consistency of program operations. Additionally, programmers often use data structures to organize and store data in a structured and efficient manner, such as arrays, lists, maps, or database tables.

# DATA CATEGORICAL
In Python, categorical data refers to a type of data that represents categories or groups. Categorical data can be either nominal or ordinal, where nominal data represents categories without any inherent order, while ordinal data represents categories with a meaningful order or hierarchy.

### Nominal
In Python, nominal data refers to categorical data where the categories do not have an inherent order or ranking. Nominal data represents distinct categories or groups without any numerical significance.

Examples of nominal data include:

- Colors (e.g., red, blue, green)
- Gender (e.g., male, female)
- Types of fruits (e.g., apple, banana, orange)
  
In Python, nominal data is typically represented using strings or categorical data types. When working with nominal data, it's important to handle it appropriately based on its categorical nature, such as using one-hot encoding or label encoding techniques for machine learning tasks.

More example:
![image](https://github.com/alnimashakiya/DataAnalitics_Learning_Week-3/assets/165742697/d7c37ac1-ad32-4e63-861a-ede798da3d40)

### Ordinal
In Python, ordinal data refers to categorical data where the categories have a natural order or ranking associated with them. Unlike nominal data, the categories in ordinal data have a meaningful sequence or hierarchy.

Examples of ordinal data include:

- Education level (e.g., elementary school < high school < bachelor's degree < master's degree < PhD)
- Rating scales (e.g., poor < fair < good < very good < excellent)
- Likert scales (e.g., strongly disagree < disagree < neutral < agree < strongly agree)
- Socio-economic status (e.g., low income < middle income < high income)
- Grades (e.g., F < D < C < B < A)
  
In Python, ordinal data can be represented using categorical data types with an explicit order or by encoding categories with numerical values that reflect their order. However, when using numerical encoding, it's important to ensure that the numerical values accurately reflect the underlying ordinal ranking of the categories.

More example:
![image](https://github.com/alnimashakiya/DataAnalitics_Learning_Week-3/assets/165742697/bf3be6eb-1ff0-4fa2-a650-b4122d3f76c3)

## DATA NUMERICAL
In Python, numerical data refers to data that consists of numbers and can be represented using numeric types such as integers or floating-point numbers. Numerical data is used to quantify variables and perform mathematical operations.

### Discrete
In Python, "diskrit" (discrete) data refers to data that consists of distinct and separate values, typically integers, with no values in between. Discrete data often represents counts or whole numbers, and it cannot take on any value within a range.

Example:
![image](https://github.com/alnimashakiya/DataAnalitics_Learning_Week-3/assets/165742697/199372a2-c255-4d2b-9941-17cf652f10e9)

### Continuous
In Python, "kontinue" (continuous) data refers to data that can take on any value within a given range. Continuous data is typically represented by real numbers and can include fractions or decimals. Unlike discrete data, continuous data can have an infinite number of possible values between any two points.

Example:
![image](https://github.com/alnimashakiya/DataAnalitics_Learning_Week-3/assets/165742697/1eb0d16e-eb53-46a1-8b38-337b70ce2d28)

### Boolean 
In Python, a boolean refers to a data type that can have one of two values: True or False. Booleans are used to represent logical states and are fundamental for controlling the flow of programs through conditional statements and boolean operations.

Example:
![image](https://github.com/alnimashakiya/DataAnalitics_Learning_Week-3/assets/165742697/c2b41fbe-ab38-45f8-9c65-d838f430a079)

## QUANTITATIVE DATA
In Python, quantitative data refers to numerical data that represents quantities or amounts. Quantitative data can be measured and expressed in numerical terms, allowing for mathematical operations and statistical analysis.

Example:
![image](https://github.com/alnimashakiya/DataAnalitics_Learning_Week-3/assets/165742697/c18b8ca8-5e81-4a37-ab0f-ecb0c2ccb1f7)

## QUALITATIVE DATA
Qualitative data in Python refers to the type of data that represents non-numeric attributes or characteristics of an object or phenomenon. This data is typically descriptive and cannot be measured numerically.

### Meta Data
"Metadata" is information that provides context or description about a particular piece of data. It can include descriptions of the data structure, data source, or information about how the data is generated or used. Metadata aids in understanding and managing data by providing additional information about the data itself.

For example, metadata for a music file might include the song title, artist name, album, release year, and music genre. For a database, metadata could include table names, column names, data types, and primary keys. Metadata is also used in the context of big data to provide information about the origin, size, structure, and characteristics of large and complex data.

Example:
![image](https://github.com/alnimashakiya/DataAnalitics_Learning_Week-3/assets/165742697/0497e771-9769-4129-a5de-7656c598c3ba)

### Big Data
"big data" refers to large and complex data sets that are difficult to manage, process, and analyze using traditional data processing methods. Big data often exhibits three main characteristics known as the "3V": volume (large), velocity (fast), and variety (diverse). This means data that is large in volume, arrives at high speed, and comes in various types and formats.

In managing big data, metadata is crucial as it helps in understanding and interpreting large and complex data. Metadata assists in identifying, organizing, and managing data, as well as ensuring that data can be effectively used for decision-making and analysis.

Examples of big data include:
- Customer survey data
- Records of user behavior within an application
- Sensor data
- Social media feeds
- Webpage content
- Surveillance data
- Audio recordings

# DATA CLEANSING
Data cleansing in Python refers to the process of identifying and correcting errors, inconsistencies, and inaccuracies in a dataset to improve its quality and reliability for analysis or other purposes. It involves various tasks such as handling missing values, removing duplicates, correcting inaccuracies, and standardizing formats.

## Handling Missing Data
Identifying and handling missing values in the dataset, either by removing them, imputing them with a suitable value, or using more advanced techniques like interpolation.

Example:
Remove
![image](https://github.com/alnimashakiya/DataAnalitics_Learning_Week-3/assets/165742697/8108c4dc-ec57-44e3-873d-380d3fe921ea)

![image](https://github.com/alnimashakiya/DataAnalitics_Learning_Week-3/assets/165742697/15d0299c-b237-4900-8126-f9ad777838f3)

_The data has cleaned_

# DATA MANIPULATION
Data manipulation in Python refers to the process of modifying, transforming, or cleaning data to prepare it for analysis or visualization. Python offers powerful libraries such as pandas, NumPy, and scikit-learn for data manipulation tasks.

## Pivot
In Python, you can create pivot tables using various libraries, but one of the most commonly used ones is pandas. Pandas is a powerful data manipulation library that provides easy-to-use data structures and data analysis tools.

Example:
![image](https://github.com/alnimashakiya/DataAnalitics_Learning_Week-3/assets/165742697/5a559699-4ec5-478d-acba-8ec3cbd2883c)

## Grouping
In Python, you can use the groupby() method from pandas to perform "group by" operations on your DataFrame. This allows you to group data based on certain values in one or more columns and then apply aggregation functions to each group.

Example:
![image](https://github.com/alnimashakiya/DataAnalitics_Learning_Week-3/assets/165742697/85e1b402-540a-44e4-b23d-7ed1fae5807b)

## Crosstab
In Python, you can use the crosstab() function from the pandas library to create a cross-tabulation table, also known as a contingency table. This function computes a simple cross-tabulation of two or more factors. It's particularly useful for analyzing categorical data and understanding the relationship between different variables.

Example:
![image](https://github.com/alnimashakiya/DataAnalitics_Learning_Week-3/assets/165742697/da3c579a-dad8-4ef4-8c0e-14471f557258)

## Dummies
Dummies or dummy variables are binary representations of a categorical variable in statistical analysis and machine learning. In Python, particularly using the pandas library, you can easily create dummy variables using the get_dummies() function. The result will be a new DataFrame with dummy variables for each unique value in a column. Dummy variables will have a value of 1 if the sample has the corresponding value in the category, and 0 if not. Dummy variables help introduce categorical variables into prediction models, especially in machine learning algorithms that require numerical input.

Example:
![image](https://github.com/alnimashakiya/DataAnalitics_Learning_Week-3/assets/165742697/5a7af3c9-03ec-4d7d-9abb-8d16b5b19ee0)

Creating dummy variables from the 'category' column of the DataFrame df, and the column names of the dummy variables will have the prefix 'sellable_online'. Dummy variables will have a value of 1 if the sample has the corresponding value in the category, and 0 if not.

True = 1 False = 0

## Sort
Sorting data in Python refers to arranging the elements of a data structure, such as lists, arrays, or DataFrames, in a specified order. This order can be ascending (from smallest to largest) or descending (from largest to smallest), depending on the requirements.

Example:
![image](https://github.com/alnimashakiya/DataAnalitics_Learning_Week-3/assets/165742697/41673878-9aa2-4d86-bde5-fa497ff47e8d)

## Rename
In Python, particularly when working with pandas DataFrames, you can use the rename() method to rename columns or indexes in your DataFrame.

Example:
![image](https://github.com/alnimashakiya/DataAnalitics_Learning_Week-3/assets/165742697/38adf9f2-678b-4f96-b27d-00ae324cc8db)

## Concat
In Python, particularly when working with pandas, the concat() function is used to concatenate two or more pandas objects along a particular axis (usually rows or columns). This function is useful for combining data from multiple sources into a single DataFrame.

Example:
![image](https://github.com/alnimashakiya/DataAnalitics_Learning_Week-3/assets/165742697/53d32313-ff1a-4fb8-aeab-7b182ecd9dd3)
![image](https://github.com/alnimashakiya/DataAnalitics_Learning_Week-3/assets/165742697/be9f8cef-9ac6-4024-9bc2-8e45be240894)

## Merge
In Python, particularly when working with pandas, the merge() function is used to combine two DataFrames by joining them on one or more keys. This function is similar to SQL join operations.

Example:
![image](https://github.com/alnimashakiya/DataAnalitics_Learning_Week-3/assets/165742697/efe1f0d4-9b8c-4ed0-9843-ad062c956a16)
![image](https://github.com/alnimashakiya/DataAnalitics_Learning_Week-3/assets/165742697/4e19c265-cc03-4e3c-99a2-b38d14eb0376)
