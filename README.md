# CODTECH-task-1
NAME:Rekha D
Company:CODTECH IT SO
ID:CTO8DS9846
Domain:DATA ANALYTICS
Duration:10th Nov 2024 to 10th Dec 2024
Mentor name:

OVERVIEW OF THE PROJECT

  ### Task 1: Exploratory Data Analysis (EDA) using Titanic Dataset

#### **Objectives**
1. **Understand the Dataset**:
   - Explore the structure and contents of the Titanic dataset.
   - Identify the key variables (e.g., survival status, passenger demographics, class) and their relationships.
   - Identify missing data, outliers, and any other data quality issues.

2. **Prepare the Data for Further Analysis**:
   - Clean the data by handling missing values, removing irrelevant columns, and correcting any inconsistencies.
   - Ensure the dataset is in a format suitable for visualization and modeling.

3. **Extract Meaningful Insights**:
   - Understand how different factors (like gender, age, class) influenced the survival of passengers.
   - Analyze distributions of key variables (age, fare, passenger class).
   - Detect patterns, trends, and relationships within the data.

4. **Report Findings**:
   - Summarize and present key insights that will inform future analysis or predictive modeling efforts.


#### **Key Activities**
1. **Load and Inspect the Data**:
   - Import the Titanic dataset and get an overview of its structure.
   - Understand the dataset's columns and types (e.g., categorical, numerical).
   - Check for missing values and examine the overall data quality.

2. **Data Cleaning**:
   - Handle missing data:
     - Impute missing values in numerical columns (e.g., `Age`) using an appropriate strategy like the median or mean.
     - Impute missing values in categorical columns (e.g., `Embarked`) using the most frequent category (mode).
     - Drop unnecessary or irrelevant columns (e.g., `PassengerId`, `Name`, `Ticket`, `Cabin`).
   - Ensure the data is consistent and in the right format for analysis.

3. **Univariate Analysis (Analyzing Individual Variables)**:
   - Analyze each individual feature:
     - For numerical features like `Age` and `Fare`, examine their distribution using summary statistics (e.g., mean, median) and visualizations (e.g., histograms, boxplots).
     - For categorical features like `Survived`, `Sex`, and `Pclass`, examine the frequency distribution using bar plots or count plots.

4. **Bivariate Analysis (Exploring Relationships Between Two Variables)**:
   - Investigate relationships between key variables and survival:
     - Analyze how survival rates differ by class (`Pclass`), gender (`Sex`), age (`Age`), and embarkation point (`Embarked`).
     - Use visualizations such as bar plots, box plots, and scatter plots to compare distributions and survival rates.

5. **Correlation Analysis**:
   - Examine correlations between numerical variables to identify potential relationships.
   - For example, check the correlation between `Age`, `Fare`, and `Pclass`, or between `Survived` and other numerical features.
   - Visualize the correlation matrix using a heatmap to easily identify strong or weak relationships.

6. **Outlier Detection**:
   - Identify outliers in numerical columns like `Fare` and `Age`.
   - Analyze if the outliers are valid (e.g., wealthy passengers with high fares) or if they need to be addressed (e.g., removal or capping).

7. **Summarize Insights**:
   - Based on your findings, summarize the insights. For example:
     - Gender had a significant impact on survival, with women having a higher survival rate.
     - Passengers in 1st class had the highest survival rate.
     - Age and Fare distributions showed that older passengers and passengers with very low fares had lower survival chances.

#### **Technologies Used**
1. **Programming Language**:
   - **Python**: For data analysis and visualization.

2. **Libraries**:
   - **Pandas**: For loading, cleaning, and manipulating the dataset.
   - **NumPy**: For handling numerical operations and calculations.
   - **Matplotlib**: For creating visualizations such as histograms and box plots.
   - **Seaborn**: For creating more advanced statistical visualizations, including heatmaps and pair plots.

3. **Tools**:
   - **Jupyter Notebook** or **Google Colab**: For writing and executing Python code in an interactive environment.
   - **GitHub**: To store and share the notebook or project.

#### **Expected Outcomes**
1. **Cleaned Dataset**:
   - A dataset with missing values handled, irrelevant columns removed, and data imputed or cleaned as necessary.

2. **Visualizations**:
   - Visualizations that highlight the distribution of key variables and the relationships between survival and other features:
     - Distribution of age, fare, and passenger class.
     - Survival rates by gender, class, and age.
     - Correlation matrix showing relationships between numerical variables.

3. **Key Insights**:
   - Insights about how survival was influenced by gender, class, and age.
   - Identification of important patterns that may guide future analysis or predictive modeling.
   - Understanding of data quality and necessary next steps for further analysis.
