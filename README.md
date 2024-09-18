# Exploratory Data Analysis

## Project Description
**Exploratory Data Analysis (EDA) on the employee remuneration and expense data for the City of Vancouver.**

## Project Title
**Exploratory Data Analysis: Employee Remuneration Data for the City of Vancouver**

## Objective
Perform an exploratory data analysis (EDA) to uncover trends, patterns, and insights in employee remuneration data. The analysis will focus on cleaning, understanding salary distributions, and visualizing key factors such as department salary averages, employee seniority, and other factors influencing pay.

## Dataset
The City of Vancouver Employee Remuneration and Expenses dataset contains information on the salaries and representation expenses of employees earning over $75,000 annually. It includes details such as:
- **Employee ID:** Unique identifier for each employee.
- **Department:** The department in which the employee works.
- **Gross Salary:** The total annual salary before deductions.
- **Representation Expenses:** Additional expenses reported by employees.
- **Start Date:** The date the employee started working in their current position.
  
![Visualization](https://github.com/ximenamz/data-analyst-ximena/blob/main/Picture5.png)

## Methodology
1. **Data Collection and Preparation:**
   - Download data from the official Vancouver Open Data portal.
   - Initial cleaning using Python's Pandas library.
     
![graphic bars](https://github.com/ximenamz/data-analyst-ximena/blob/main/Picture7.png)

2. **Descriptive Statistics:**
   - Calculate summary statistics, such as average salaries by department.

3. **Data Visualization:**
   - Create visualizations to illustrate key insights:
     - **Histograms and Boxplots:** Analyze the distribution of continuous variables such as *Gross Salary* and *Representation Expenses* to identify central tendencies and outliers across different departments.
     - **Bar Charts:** Display the average salary and expense distribution across various departments, helping to identify discrepancies and trends in compensation.
     - **Heatmaps:** Visualize correlations between numerical variables like *Gross Salary*, *Representation Expenses*, and *Years of Service* to uncover relationships between seniority and compensation.

![Visualization](https://github.com/ximenamz/data-analyst-ximena/blob/main/Picture15.png)

4. **Salary and Expense Analysis:**
   - Compare salary and expense patterns across various factors:
     - **By Department:** Analyze if there are significant differences in average salaries and expenses between departments, identifying high and low-paying departments.
     - **By Job Role:** Compare salaries and expenses across different job roles or levels within the organization to identify variations in compensation structures.

5. **Insights and Findings:**
   - Summarize the findings based on data visualizations and statistical analyses, highlighting notable trends and patterns in employee remuneration and expenses, including:
     - Departmental Differences
     - Representation Expenses
     - Gender or Role Differences

6. **Conclusion:**
   - Discuss the implications of the findings and suggest further analyses or data-driven decisions:
     - **Departmental Adjustments:** Recommend a review of compensation policies for departments with lower salaries to ensure fair remuneration.
     - **Expense Monitoring:** Suggest implementing stricter guidelines for representation expenses, particularly for higher salary groups.
     - **Further Analysis:** Explore the possibility of building predictive models to identify factors most strongly associated with higher salaries or higher expenses.
     - **Long-Term Strategy:** Recommend conducting a follow-up analysis to track changes in remuneration trends, particularly in the post-pandemic period.

## Tools and Technologies
- **Python (Pandas):** For tasks such as data loading, cleaning, and analysis, particularly working with the employee remuneration dataset.
- **AWS Services:**
  - **Amazon S3:** For storing the employee remuneration and expenses dataset.
  - **AWS Glue:** For creating and managing data pipelines, including ETL processes (Extract, Transform, Load).
  - **Amazon CloudWatch:** For monitoring the data pipeline and controlling costs.
  - **AWS CloudTrail:** For logging and security monitoring, tracking activities within your S3 bucket.
- **Jupyter Notebook:** Used for interactive data exploration and analysis.

## Deliverables
- A comprehensive Jupyter Notebook that documents all steps of the analysis, including code, data cleaning, visualizations, and narrative explanations of findings.
- Screenshots and documentation of the AWS services used, including S3, Glue, CloudWatch, and CloudTrail configurations.

---

# Descriptive Analysis

## Project Description
**Descriptive Analysis of Employee Remuneration and Expenses**

## Project Title
**Understanding Employee Salary and Expense Patterns at the City of Vancouver**

## Objective
The primary goal of this project is to conduct a descriptive analysis of the employee remuneration and expense data for the City of Vancouver. This analysis aims to summarize key characteristics of employee compensation and expense claims, identify trends, and provide insights that can guide decision-making for budgeting, compensation adjustments, and financial planning.

## Dataset
The dataset includes employee salary and expense data for the City of Vancouver, containing the following key features:
- **Employee ID:** Unique identifier for each employee.
- **Department:** Department in which the employee works.
- **Start Date:** The date the employee started working in their current position.
- **Gross Salary:** Total annual salary of the employee.
- **Representation Expenses:** Additional expenses claimed by employees for representation purposes.
- **Job Role:** Position or title of the employee.

## Methodology
1. **Data Collection and Preparation:**
   - Load the dataset from the AWS S3 bucket and clean the data using Pandas, removing duplicates and handling missing values.

2. **Descriptive Statistics:**
   - Calculate summary statistics for key variables, such as:
     - Average and median salary by department.
     - Total and average expenses claimed by department and job role.

3. **Data Visualization:**
   - Create visual representations to illustrate the findings:
     - **Bar Charts:** Display average salary and expense distribution by department and job role.
     - **Histograms:** Show the distribution of salaries and expenses to identify outliers or patterns.
     - **Heatmaps:** Highlight correlations between salary levels, expenses, and employee seniority.

4. **Employee Segmentation:**
   - Segment employees based on their compensation and expense behavior:
     - **By Salary Levels:** Group employees into salary tiers (e.g., high vs. low earners) to analyze differences in compensation patterns.
     - **By Department:** Analyze salary and expense trends across different departments to identify departmental compensation variations.
     - **By Job Role:** Examine differences in salary and expenses between management and non-management roles, highlighting distinct compensation structures.

5. **Insights and Findings:**
   - Summarize the insights derived from the analysis, highlighting key trends and patterns:
     - **Salary Distribution:** Identify departments with higher salary averages and compare them to departments with lower compensation.
     - **Expense Trends:** Review the relationship between higher salaries and representation expenses, identifying any noticeable patterns or outliers.
     - **Tenure Impact:** Highlight how years of service impact salary growth and expenses.
     - **Gender/Role Variations:** Detect any potential salary discrepancies based on gender or job role.

6. **Recommendations:**
   - Provide actionable recommendations based on the findings to inform decision-making:
     - **Compensation Adjustments:** Suggest reviewing and adjusting compensation for departments or roles where salary disparities exist.
     - **Expense Policy Review:** Recommend implementing or refining expense policies for higher earners to ensure efficient use of resources.
     - **Future Data Analysis:** Propose further investigation into potential factors influencing salary growth, such as performance metrics or external market comparisons.

## Tools and Technologies
- **Python (Pandas, Matplotlib, Seaborn):** Used for data analysis, including cleaning, transformation, and visualization of employee remuneration and expense data.
- **AWS Services (S3, Glue):** For data storage, ETL processes, and managing the data pipeline.
- **Data Visualization Tools (Matplotlib, Seaborn):** Used to create visualizations such as bar charts, histograms, and heatmaps for insights into salary and expense patterns.
- **Jupyter Notebook:** For interactive data exploration and documentation of analysis steps.

## Deliverables
- **Detailed Report:** Summarizing the methods, analysis process, findings, and recommendations based on the employee remuneration and expenses dataset.
- **Visualizations:** Including charts and graphs to clearly present salary distribution, expense trends, and other key insights.
- **Presentation:** A concise presentation for stakeholders outlining the main findings, visual insights, and actionable recommendations for further decision-making.

---

# Diagnostic Analysis

## Project Description
**Diagnostic Analysis of Data Pipeline and Salary Trends at the City of Vancouver**

## Project Title
**Investigating the Causes of Data Issues and Salary Discrepancies at the City of Vancouver**

## Objective
The primary goal of this project is to conduct a diagnostic analysis to identify the underlying causes of any data pipeline inefficiencies or discrepancies in salary and expenses across departments. By analyzing various data sources, the aim is to uncover the factors contributing to these issues and provide actionable insights for management to improve data processing and salary allocation.

## Background
Over the past several months, the data pipeline and salary processing system have experienced delays, resulting in inefficiencies in salary reporting and expense management. This analysis will help pinpoint contributing factors and recommend strategies to optimize the data pipeline and ensure equitable salary distribution.

## Dataset
The analysis will utilize multiple datasets, including:
- **Employee Salary Data:** Remuneration data for City of Vancouver employees, covering gross salary, department, and tenure.
- **Expense Data:** Detailed records of employee representation expenses.
- **Pipeline Logs:** Logs from AWS services such as S3, Glue, CloudWatch, and CloudTrail to monitor data flow and potential issues in the pipeline.
- **Employee Feedback:** (Optional) Any qualitative data regarding employee satisfaction with salary and expenses.
![Visualization](https://github.com/ximenamz/data-analyst-ximena/blob/main/2_Picture6.png)

## Methodology
1. **Data Collection and Preparation:**
   - Consolidate datasets from multiple AWS services (S3, Glue) to ensure accuracy and consistency.
   - Normalize data (e.g., salary and expense records) for comparative analysis.

2. **Trend Analysis:**
   - Analyze salary and expense trends over the past year to identify departments or roles where discrepancies or delays in payments are most significant.
   - Review pipeline performance over time to detect periods with data ingestion or processing delays.

3. **Correlation Analysis:**
   - Identify correlations between salary levels, expenses, and other variables such as tenure, department, and job role.
   - Use statistical methods (e.g., regression analysis) to measure the impact of these factors on salary disparities.

4. **Root Cause Analysis:**
   - Investigate the root causes of data pipeline delays by reviewing AWS CloudWatch and CloudTrail logs.
   - Use techniques like the "5 Whys" or Fishbone Diagram to systematically investigate potential causes of salary or data discrepancies.
![Visualization](https://github.com/ximenamz/data-analyst-ximena/blob/main/2_Picture7.png)

5. **Segmentation Analysis:**
   - Segment employees based on salary ranges, department, and tenure to analyze differing impacts on compensation and expense trends.

6. **Synthesis of Findings:**
   - Integrate quantitative (salary, expense) and qualitative data (feedback, logs) to uncover patterns and themes that indicate the most significant factors contributing to salary and data pipeline issues.

## Tools and Technologies
- **Data analysis tools (Python with Pandas, Scikit-learn, SQL):** Used for metrics calculations, correlation analysis, and diagnosing inefficiencies in salary trends and data pipeline performance.
- **AWS Services (CloudWatch, Glue, S3):** Employed to monitor, process, and store employee remuneration and expense data, as well as track potential data pipeline issues.
- **Visualization tools (Matplotlib, Seaborn, or Power BI):** Used to create visualizations and dashboards that present key findings and trends to stakeholders.

## Deliverables
- **Comprehensive Diagnostic Report:** Outlining the analysis process, findings, and root causes of data pipeline inefficiencies and salary discrepancies.
- **Visualizations and Dashboards:** Summarizing key metrics such as salary distribution, expense trends, and data pipeline performance over time.
- **Actionable Recommendations:** Providing specific strategies for management to address identified data issues, optimize salary distribution, and improve overall performance.

## Timeline
- **Expected completion:** 6 weeks from project kickoff, including regular check-ins with stakeholders to review findings and align recommendations.

---

# Data Wrangling

## Project Description
**Data Wrangling for Employee Remuneration and Expense Analysis at the City of Vancouver**

## Project Title
**Data Wrangling for Enhanced Salary and Expense Analytics at the City of Vancouver**

## Objective
The primary goal of this project is to perform comprehensive data wrangling to prepare a robust dataset for the analysis of employee remuneration and expenses at the City of Vancouver. By cleaning, transforming, and consolidating data from various sources, the project aims to enhance the accuracy and usability of employee data for subsequent analysis and reporting.

## Background
The City of Vancouver has accumulated employee salary and expense data over multiple periods, stored in various locations such as AWS S3 and other internal databases. This data is often inconsistent, incomplete, or fragmented, making it challenging to derive meaningful insights. Effective data wrangling will improve data quality and enable accurate analysis for budgeting and decision-making.

## Dataset
The data wrangling process will involve multiple datasets, including:
- **Employee Salary Data:** Records of employee gross salary, department, and tenure.
- **Expense Data:** Detailed records of employee representation expenses.
- **Pipeline Logs:** Logs from AWS services such as S3 and Glue related to data ingestion and processing.
![Visualization](https://github.com/ximenamz/data-analyst-ximena/blob/main/Picture8.png)

## Methodology
1. **Data Collection:**
   - Gather datasets from AWS S3 and internal sources, ensuring all relevant data is included for the analysis of salary and expenses.
   - Confirm the completeness of data for all employee departments and roles.

2. **Data Assessment:**
   - Conduct an initial assessment to identify issues such as missing values, duplicates, and inconsistencies across datasets.
   - Document data types, formats, and any observed discrepancies.

3. **Data Cleaning:**
   - Address missing values through imputation or exclusion based on the significance of the data.
   - Remove duplicate records and correct inconsistencies in formats (e.g., date formats, salary units).
   - Normalize categorical variables such as department names and job roles to ensure consistency.
![Visualization](https://github.com/ximenamz/data-analyst-ximena/blob/main/Picture10.png)

4. **Data Transformation:**
   - Convert data types to suitable formats for analysis (e.g., date fields for tenure, salary as numerical values).
   - Create new features to aid in analytics, such as tenure categories and average expenses per employee.
   - Aggregate data as necessary to align with the intended analysis (e.g., yearly salary and expense totals per employee).

5. **Data Consolidation:**
   - Merge datasets to create a unified view of employee salary and expenses, ensuring all data is accurately linked through unique identifiers (e.g., employee ID).
   - Combine different sources of data to provide a holistic view of employee compensation, expenses, and job roles.
![Visualization](https://github.com/ximenamz/data-analyst-ximena/blob/main/Picture11.png)

7. **Documentation and Validation:**
   - Document the data wrangling process, including data sources, cleaning steps, and transformations applied to the dataset.
   - Validate the final dataset through exploratory data analysis (EDA) to confirm its accuracy and completeness before moving to further analysis.

## Tools and Technologies
- **Python (using libraries like Pandas and NumPy):** Used for data manipulation, cleaning, and transforming employee remuneration and expense data.
- **SQL:** For extracting and assessing data from relational databases, ensuring data accuracy and consistency.
- **Jupyter Notebook:** Employed for interactive data wrangling, exploration, and documentation of the cleaning process.
- **Visualization tools (like Matplotlib or Seaborn):** To assist with exploratory data analysis (EDA) and to visualize quality checks during the wrangling process.

## Deliverables
- A cleaned and transformed **employee remuneration and expense dataset** ready for analysis, available in a suitable format (e.g., CSV or Excel).
- A **comprehensive report** documenting the data wrangling process, including any challenges encountered, the methods used for data cleaning and transformation, and the characteristics of the final dataset.
- **Visualizations** illustrating key insights and validating data quality checks, including distribution charts for salary and expense data, and correlation heatmaps for quality assessment.

## Timeline
- **Expected completion:** 6 weeks, including phases for data assessment, cleaning, transformation, validation, and documentation.

---

# Data Quality Control

## Project Description
**Data Quality Control Initiative for Employee Remuneration and Expense Data at the City of Vancouver**

## Project Title
**Implementation of Data Quality Control Measures for Employee Data at the City of Vancouver**

## Objective
The primary objective of this project is to establish a comprehensive Data Quality Control (DQC) framework for the City of Vancouver’s employee remuneration and expense data. This framework will ensure the accuracy, completeness, consistency, and reliability of the data, improving decision-making processes and enhancing overall operational efficiency.

## Background
As the City of Vancouver continues to process large volumes of employee salary and expense data, issues such as data inconsistencies, inaccuracies, and duplicate records have surfaced. These data quality issues can lead to inefficient resource management and hinder financial planning. This project aims to implement robust data quality control measures to mitigate these risks and ensure data integrity.

## Scope
The project will focus on the following key areas:
- **Data Profiling:** Assessing the current state of the employee salary and expense data to determine its quality.
- **Data Cleansing:** Developing processes to remove inaccuracies, duplicates, and inconsistent formats.
![Visualization](https://github.com/ximenamz/data-analyst-ximena/blob/main/3_Picture3.png)
- **Data Validation:** Establishing rules and validation checks to ensure data accuracy and consistency.
- **Monitoring and Reporting:** Creating dashboards to monitor data quality metrics and track performance over time.
![Visualization](https://github.com/ximenamz/data-analyst-ximena/blob/main/2_Picture6.png)
- **Training and Awareness:** Educating staff on best practices for data entry and quality control.

## Methodology

1. **Current State Assessment:**
   - Analyze existing data workflows and identify critical data quality challenges affecting employee remuneration and expense reporting.

2. **Data Profiling:**
   - Use profiling tools to assess the quality of datasets, focusing on completeness, uniqueness, validity, consistency, and accuracy.
   - Document areas requiring immediate improvement.

3. **Establish Data Quality Metrics:**
   - Define specific data quality metrics and key performance indicators (KPIs), such as error rates, duplicate records, and data format compliance.

4. **Data Cleansing Processes:**
   - Develop procedures to cleanse the dataset:
     - Remove duplicate records.
     - Standardize data formats (e.g., salary figures, dates).
     - Fill in missing values using imputation or exclusion techniques.

5. **Validation Rules and Procedures:**
   - Set up validation rules for new data entries to minimize poor-quality data entry.
   - Establish guidelines to ensure consistency and accuracy in data entry practices.

6. **Monitoring and Reporting:**
   - Implement dashboards that provide real-time data quality metrics, including alerts for deviations.
   - Regularly generate reports to review data quality trends and ensure adherence to established KPIs.

7. **Training and Best Practices:**
   - Develop training resources and workshops to educate staff on data quality principles, emphasizing the importance of accurate and consistent data entry.
   - Promote a culture of accountability where employees actively maintain high data quality standards.

8. **Feedback Mechanism:**
   - Establish a feedback loop to continuously assess and improve data quality based on user input and system performance.

## Tools and Technologies
- **Data quality tools (Informatica, Talend, or Trifacta):** For profiling and cleansing.
- **SQL or Python:** For data cleansing and automation of validation processes.
- **Visualization tools (Tableau, Power BI):** To monitor and report on data quality metrics in real time.

## Deliverables
- A **comprehensive Data Quality Control plan** detailing procedures, metrics, and responsibilities.
- **Documentation of data quality metrics and KPIs** being tracked.
- **Cleaned and validated datasets** ready for analysis and reporting.
- **Training resources, including workshops** designed to educate staff on maintaining data quality.
- A **monitoring dashboard** that visualizes data quality metrics in real time.

## Timeline
- **Expected completion of the project:** 8 weeks, including assessment, implementation, training, and monitoring setup.

---

This Data Quality Control initiative aims to improve the integrity and reliability of the City of Vancouver's employee data, ensuring accurate financial reporting and effective decision-making.
