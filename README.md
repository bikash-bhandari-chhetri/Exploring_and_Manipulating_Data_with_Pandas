# Exploring_and_Manipulating_Data_with_Pandas

**Objective:**
Here, I practiced my skills in data manipulation, cleaning, and analysis using
the Pandas library. The main focus was on reading, selecting, cleaning, manipulating, transforming
(melting and pivoting), visualizing, and analyzing data.

**Tasks:**
**_Data Importing and Inspection:_**
1. Import the necessary libraries (pandas, numpy, matplotlib.pyplot).
2. Load the Titanic dataset (you can download it from here) using pandas.
3. Use .head(), .info(), and .describe() methods to inspect the DataFrame.

**_Data Selection:_**
1. Select the 'Survived', 'Pclass', 'Sex', 'Age', and 'Fare' columns and save them in a new
DataFrame.
2. Select rows where 'Age' is greater than 30 using boolean indexing.

**_Data Cleaning:_**
1. Identify columns with missing values.
2. Handle missing values appropriately (e.g., drop them, fill them with mean/median/mode,
etc.).
3. Find any duplicate rows and remove them from the DataFrame.

**_Data Manipulation:_**
1. Add a new column 'Age_group' to the DataFrame which categorizes passengers as 'Child'
(age <= 18), 'Adult' (18 < age < 60), or 'Senior' (age >= 60).
2. Use the groupby() function to find the average 'Fare' and 'Age' for each 'Pclass'.
3. Merge this grouped data with the original DataFrame.

**_Data Transformation:_**
1. Create a pivot table showing the total 'Fare' collected for each 'Pclass', separated by 'Sex'.
2. Melt the DataFrame to have 'Pclass', 'Sex', 'Age_group', and 'Survived' as identifier variables
and 'Fare' as the value variable.

**_Data Visualization and Analysis:_**
1. Use the matplotlib library to plot histograms for 'Age' and 'Fare'.
2. Plot a bar chart showing survival count for each 'Pclass'.
3. Analyze the relationship between survival rate and other factors in the dataset (e.g., 'Sex',
'Pclass', 'Age_group').
