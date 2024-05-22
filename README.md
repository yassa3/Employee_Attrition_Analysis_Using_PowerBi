# **Employee Attrition Analysis using Power BI: A Case Study**

## **Project Overview**

ABC Corporation, a multinational company, is experiencing challenges with employee attrition. To address this issue, a comprehensive analysis using Power BI has been implemented to understand the factors contributing to attrition and develop strategies for retention and talent management.

## **Project Objectives**

1. **Identify Key Drivers of Attrition**: Determine the primary factors influencing employee attrition within the organization.
2. **Segmentation Analysis**: Analyze attrition rates across different segments such as departments, job roles, genders, education levels, etc., to identify high-risk groups.
3. **Dashboard and Reporting**: Design an interactive dashboard to present insights and recommendations to stakeholders effectively.

## **Data Sources**

1. **Database Tables**:
    - **Employee_survey**: Contains responses from employees regarding their satisfaction, work-life balance, etc.
    - **Manager_survey**: Contains responses from managers regarding employee performance, etc.
    - **EmployeeInfo**: Includes demographic information, job role, etc.
2. **IN/OUT Times**:
    - Two sheets extracted from the Clock-In-Machine for the year 2015, including in/out times for all employees.

## **Methodology**

1. **Data Collection**: Import the data from various sources, including the database and CSV files.
2. **Data Preparation**: Reshape the data for analysis, such as pivoting, aggregating, or filtering.
3. **Data Model**: Build a dimensional model to integrate the data sources and facilitate the reporting phase.
4. **Visualization and Dashboarding**: Create an interactive dashboard using Power BI to communicate insights effectively.

## **Deliverables**

1. **Power BI Dashboard**: A .pbix file showcasing the analysis.
2. **Report**: A .docs file (maximum 2 pages) summarizing key findings, insights, and recommendations.


## **How to Use**

1. **Clone the Repository**:
    
    ```bash
    bashCopy code
    git clone https://github.com/yourusername/Employee-Attrition-Analysis.git
    cd Employee-Attrition-Analysis
    
    ```
    
2. **Data Preparation**:
    - Ensure the data files are placed in the **`data/`** directory.
    - Use the **`data_preparation_script.sql`** to reshape and prepare the data for analysis.
3. **Open the Power BI Dashboard**:
    - Open **`employee_attrition_analysis.pbix`** using Power BI Desktop to explore the interactive dashboard.
4. **Review the Report**:
    - The **`employee_attrition_summary_report.docs`** file contains a concise summary of key findings, insights, and recommendations.

## **Key Findings and Recommendations**

- **Key Drivers of Attrition**:
    - Highlight the primary factors such as job satisfaction, work-life balance, and managerial support influencing employee attrition.
- **Segmentation Analysis**:
    - Identify high-risk groups based on departments, job roles, gender, education levels, etc.
- **Recommendations**:
    - Provide actionable strategies for improving employee retention and talent management based on the insights gained from the analysis.

## **Contributing**

Feel free to submit issues or pull requests if you have suggestions or improvements.

## **License**

This project is licensed under the MIT License. See the **`LICENSE`** file for details.
