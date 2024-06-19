## Comprehensive Analysis of NYC School Data using Pandas and NumPy

### Introduction
This report documents the analysis of a dataset containing information about schools in New York City. The analysis includes obtaining basic information about the dataset, verifying data constraints, filtering data, handling missing values, and identifying top-performing schools.

### Sections

#### 1. Basic Dataset Information
- **Objective**: Understand the structure and basic statistics of the dataset.
- **Methods**: 
  - Display the shape, columns, data types, and descriptive statistics.
  - Provide a summary of non-null values and the first few rows of the dataset.
- **Outcome**: A comprehensive understanding of the dataset's dimensions, column names, data types, and basic statistics.

#### 2. Verifying Score Constraints
- **Objective**: Ensure that the average math scores are within expected bounds.
- **Methods**: 
  - Check the minimum and maximum values of the `average_math` column.
- **Outcome**: Confirmed that average math scores are within the expected range.

#### 3. Filtering High-Performing Schools in Math
- **Objective**: Identify schools with high average math scores.
- **Methods**: 
  - Filter schools with average math scores above 80% of 800.
  - Display the top 5 schools based on average math scores.
- **Outcome**: A list of schools excelling in math, with their names and average math scores.

#### 4. Handling Missing Values
- **Objective**: Address missing values in the `percent_tested` column.
- **Methods**: 
  - Identify the number of missing values.
  - Fill missing values with the column's mean.
- **Outcome**: A dataset with no missing values in the `percent_tested` column, ensuring data completeness.

#### 5. Identifying Top 10 Performing Schools Based on SAT Scores
- **Objective**: Rank schools based on combined SAT scores.
- **Methods**: 
  - Calculate the total SAT score by summing `average_math`, `average_reading`, and `average_writing`.
  - Sort and display the top 10 schools based on total SAT scores.
- **Outcome**: A DataFrame named `top_10_schools` containing the names and total SAT scores of the top 10 schools.

#### 6. Analyzing Standard Deviation of SAT Scores by Borough
- **Objective**: Determine which NYC borough has the largest variation in SAT scores.
- **Methods**: 
  - Group data by borough and calculate the count, mean, and standard deviation of total SAT scores.
  - Identify the borough with the highest standard deviation.
- **Outcome**: Identification of the borough with the largest standard deviation in total SAT scores, indicating significant variation in school performance within that borough.

### Conclusion
This analysis provides insights into the performance of NYC schools, highlighting top performers and identifying areas with significant variability. The handling of missing data ensures the integrity of the analysis, and the identification of high-performing schools and boroughs with large score variations offers valuable information for further investigation and policy-making.

This structured approach to analyzing the NYC school dataset using Pandas and NumPy provides a clear methodology for extracting valuable insights from educational data.
