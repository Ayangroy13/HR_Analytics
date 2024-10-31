# HR_Analytics
## Description:

The HR Analytics Project offers a comprehensive view of workforce demographics and turnover patterns. It examines factors like age, gender, commute distance, and marital status to highlight diversity while analyzing attrition across departments, job roles, tenure, and income. These insights empower HR teams to make data-driven decisions, optimize retention, and enhance workforce planning.

**HR_Analytics Project**

**Demographic Analysis**  
It summarizes employee demographics, including age, gender, home distance, and marital status, providing insights into workforce diversity and commuting patterns.

**Turnover Analysis I**  
It analyzes employee attrition data by department, job role, business travel, and role tenure, supporting strategic HR planning and retention efforts.

**Turnover Analysis II**  
It consolidates attrition data by job level, overtime, performance ratings, and income, enabling data-driven HR strategies and informed decision-making.

**Employee Wellness** 
It consolidates turnover data on attrition by job level, overtime, performance ratings, income, and attrition trends, providing valuable insights for effective HR strategies and improved decision-making.

![WhatsApp Image 2024-10-30 at 18 26 15_298cb930](https://github.com/user-attachments/assets/6ca82703-2706-4bd4-b7bf-af6e82db3bd0)

## Data Cleaning:

### Data Cleaning and Transformation Process

This section outlines the data preparation steps applied to ensure the dataset's quality and relevance. Each transformation step helps make the data more usable and insightful for analysis.

#### 1. Deleting Redundant Columns
   - Identify and drop any columns that do not add value to the analysis.
   - Use `DataFrame.drop(columns=[...])` to remove these unnecessary columns.

#### 2. Renaming Columns
   - Improve readability by renaming columns for clarity.
   - Follow a consistent naming convention, like snake_case.
   - Use `DataFrame.rename(columns={...})` for this step.

#### 3. Dropping Duplicates
   - Remove duplicate records to avoid skewing results.
   - Use `DataFrame.drop_duplicates()` to keep only unique rows.

#### 4. Cleaning Individual Columns
   - Address issues in specific columns, such as:
     - **Whitespace Trimming:** Remove leading or trailing spaces.
     - **Standardize Text Cases:** Convert text to lower or upper case as needed.
     - **Handling Inconsistent Formats:** Correct inconsistencies within columns (e.g., date formats).
   - Apply functions like `str.strip()` and `str.lower()` to clean text.

#### 5. Removing NaN Values
   - Handle missing data by removing or imputing null values based on relevance.
   - Use `DataFrame.dropna()` to eliminate rows with missing values or `fillna()` for imputation.

#### 6. Additional Transformations
   - **Encoding Categorical Variables:** Convert categorical variables to numerical values (if required).
   - **Scaling/Normalizing:** Ensure that numerical values are on a comparable scale.
   - **Feature Engineering:** Derive new columns to capture essential data insights.
   - Perform these transformations based on the analysis requirements.

## Data Visualisation:

### Data Visualization Process in Power BI

This project’s data visualization phase is centered on analyzing employee data by exploring correlations and relationships among variables.

#### Steps in Data Visualization

1. **Data Import and Transformation**
   - Imported the dataset using the "Get Data" option in Power BI.
   - Used the "Transform" feature to clean the dataset, checking and handling any null values to prepare the data for accurate visualization.

2. **Analyzing Relationships Between Categorical and Numeric Variables**
   - Used bar charts, scatter plots, and stacked charts to analyze the relationship between categorical fields and key numeric fields.
   - Examined relationships between variables like **Overtime** and **Age** and looked at other demographic factors such as **Marital Status**, **Job Role**, **Department**, and **Business Travel**.

3. **Insight Generation**
   - Interpreted patterns from the correlation map and other visuals to derive insights regarding employee overtime, career progression, job satisfaction, and demographic influences.
![WhatsApp Image 2024-10-30 at 18 26 48_5884d10b](https://github.com/user-attachments/assets/8e86f46b-6556-41b5-8aae-ba0e5524d604)
![WhatsApp Image 2024-10-30 at 18 27 23_3461c76b](https://github.com/user-attachments/assets/ba7ab4f4-ac40-4d29-98f3-768768343c59)
![WhatsApp Image 2024-10-30 at 18 28 04_a86d02c1](https://github.com/user-attachments/assets/0e990cef-1371-4886-a8d8-064f26d86827)
![WhatsApp Image 2024-10-30 at 18 29 05_df512707](https://github.com/user-attachments/assets/5a8de174-1bff-4da2-a875-84ad0ed4cfc5)




