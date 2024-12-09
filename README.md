# OU_Enrollment_Retention_Analysis

# Project Overview
This project analyzes student enrollment, retention, and graduation data from the University of Oklahoma using SQL for data extraction and Tableau for visual storytelling. The analysis aims to identify key trends and demographic factors influencing student success, providing actionable insights to inform institutional strategies.

## Objectives
- Understand trends in student enrollment, retention, and graduation outcomes.
- Identify demographic factors (age, gender, ethnicity) correlated with retention and success rates.
- Visualize findings through interactive Tableau dashboards for data-driven decision-making.
- Support institutional strategies aimed at enhancing student retention and graduation performance.

## Description
Key Steps:

- Data Preparation: Extracting raw data from PDF sources and transforming it into a database-ready format for SQL-based cleaning and analysis.
- Trend Analysis: Examining year-over-year changes in enrollment, retention, and graduation rates.
- Demographic Insights: Investigating how variables such as age, gender, and ethnicity correlate with academic outcomes.
- Interactive Visualization: Leveraging Tableau dashboards to present insights in a user-friendly, dynamic format tailored for stakeholders

This methodology ensures a robust understanding of institutional performance while uncovering actionable opportunities for improvement.

## Methodology
1. **Data Preparation**:

- Convert raw data from PDFs (2018–2023) into structured formats suitable for database integration.
- Build and populate a local SQL database for analysis.

2. **SQL Analysis**:

- Data Cleaning: Normalize and standardize tables to remove inconsistencies.
- Trend Analysis: Aggregate data to identify patterns in enrollment and graduation rates.
- Demographic Analysis: Use SQL queries to explore the impact of demographic factors on student outcomes.

3. **Visualization**:

Design Tableau dashboards to highlight trends and key metrics.
  - Include interactive elements (filters by year, demographics) for user exploration.
  - Visualize critical insights such as:
  - Retention rates by year.
  - Graduation outcomes segmented by demographic group.
  - Yearly enrollment comparisons.

4. **Insights and Recommendations**:

- Highlight actionable findings to improve retention rates.
- Provide data-driven recommendations for institutional policies and student success initiatives.

## Tools Used
- **SQL** For data extraction, cleaning, and performing trend/correlation analyses.
- **Tableau** To create dashboards that illustrate insights clearly and interactively.

## Prerequisites
- A local or cloud-hosted SQL database (e.g., MySQL, PostgreSQL) to store processed data.
- Structured tables derived from the PDF data with fields for year, demographic details, retention rates, and graduation outcomes.

## Environment Setup
- A SQL client (e.g., pgAdmin, MySQL Workbench) for querying and managing data.
- Tableau Desktop for visualization

## Usage
- Clone the repository to your local machine and navigate to the project folder.
  git clone https://github.com/your-username/OU_Enrollment_Retention_Analysis.git
cd OU_Enrollment_Retention_Analysis
- Set Up the Database
- Explore the SQL scripts to understand how data is retrieved and transformed.
- Open the provided Tableau files to view and interact with the visualizations.
- Modify the SQL queries and Tableau dashboards as needed to adapt the project to different datasets or analyses.

## License
This project is licensed under the Apache 2.0 License.

## Acknowledgements
Thanks to University of Oklahoma's Office of Institutional Research & Reporting provided access to the student data used in this project. 

