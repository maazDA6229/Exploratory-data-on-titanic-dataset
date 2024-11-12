 Titanic Data Analysis - Data Science Project

This repository contains a beginner-friendly data science project focused on analyzing the Titanic dataset. The goal is to explore and analyze the data to understand the factors influencing the survival of passengers on the Titanic.

In this project, we will:
1. Load the Titanic dataset from a CSV file.
2. Clean the data by handling missing values and converting categorical data into numeric values.
3. Perform exploratory data analysis to identify patterns and insights from the dataset.
4. Visualize the results using various charts and graphs.

The project focuses on:
- Data preprocessing
- Univariate, bivariate, and correlation analysis
- Data visualization techniques

Dataset

The Titanic dataset contains information about the passengers aboard the Titanic, including their demographics, ticket class, survival status, and more. This dataset is publicly available on [Kaggle](https://www.kaggle.com/c/titanic/data).

1. Data Loading:
   - The Titanic dataset is loaded into a pandas DataFrame for analysis.
   
2. Data Cleaning:
   - Missing Values: 
     - The 'Age' column is filled with the mean age value.
     - The 'Embarked' column is filled with the most frequent embarkation port (mode).
   - Dropping Unnecessary Columns: 
     - Columns such as 'Name', 'Ticket', and 'Cabin' are dropped since they aren't useful for the analysis.
   - Converting Categorical Data: 
     - The 'Sex' and 'Embarked' columns are converted to numerical codes to enable analysis.

3. Exploratory Data Analysis:
   - Visualizing the distribution of 'Age'.
   - Comparing survival rates by gender and class.
   - Analyzing the relationship between age and fare.
   - Generating a correlation matrix to identify relationships between numerical variables.

4. Data Visualization:
   - Used matplotlib and seaborn to create visualizations like histograms, count plots, and scatter plots.

 Tools and Libraries Used

- Python: The primary programming language for data analysis.
- Pandas: For data manipulation and cleaning.
- NumPy: For numerical operations.
- Matplotlib: For data visualization.
- Seaborn: For advanced statistical visualizations.

