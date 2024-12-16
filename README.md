# OU_Enrollment_Retention_Analysis

## Project Overview
This project analyzes student enrollment, retention, and graduation data from the University of Oklahoma. By leveraging SQL for data transformation and Tableau for visualization, it identifies key trends and demographic factors influencing student success, providing insights that support institutional strategies to improve retention and graduation outcomes.

## Objectives
- Examine year-over-year enrollment, retention, and graduation rates.  
- Understand how demographics (age, gender, ethnicity) correlate with student success.  
- Present findings through interactive dashboards to guide decision-making.

## Key Features
- **Data Transformation:** Convert raw PDF data into a structured SQL database.  
- **Trend & Demographic Analysis:** Explore enrollment and retention patterns over time and by student attributes.  
- **Interactive Dashboards:** Use Tableau dashboards to visualize and filter key metrics dynamically.

## Technologies Used
- **SQL:** Data extraction, cleaning, and trend analysis.  
- **Tableau:** Interactive dashboards and visual storytelling.  
- **Git & GitHub:** Version control and project collaboration.

## Methodology
1. **Data Preparation:** Convert raw PDF data (2018–2023) into structured tables.  
2. **SQL Analysis:** Clean and normalize data, identify trends in enrollment/retention, and run demographic segmentation queries.  
3. **Visualization:** Design Tableau dashboards with filters and interactive elements to highlight retention and graduation metrics by demographic group.  
4. **Insights & Recommendations:** Translate analytical findings into actionable strategies for improving student success.

## Installation & Environment Setup
1. **Set Up Database:**  
   Import the structured data into your SQL database (MySQL, PostgreSQL, etc.).
   
2. **Clone the Repository:**  
   ```bash
   git clone https://github.com/your-username/OU_Enrollment_Retention_Analysis.git
   cd OU_Enrollment_Retention_Analysis
   ```

3. **Connect Tableau:**  
   Open the provided Tableau files and connect them to the SQL database. Ensure Tableau Desktop is installed.

## Usage
1. **Run SQL Queries:**  
   Use the included SQL scripts to retrieve and analyze data directly from the database.  
2. **Explore Dashboards:**  
   Open the Tableau workbooks in the `visualizations/` directory to interact with retention and graduation insights.
3. **Adjust Queries & Visualizations:**  
   Customize the queries or dashboard filters to focus on specific cohorts, time periods, or demographics.

## Project Structure
```
OU_Enrollment_Retention_Analysis/
├── data/                     # Source files (if included) 
├── sql/                      # SQL queries and scripts
├── visualizations/           # Tableau dashboards and visualizations
├── .gitignore                # Git ignore file
├── README.md                 # Project overview and instructions
```

## License
This project is licensed under the [Apache 2.0 License](LICENSE).

## Acknowledgements
Data provided by the University of Oklahoma’s Office of Institutional Research & Reporting.




