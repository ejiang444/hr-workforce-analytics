## HR Workforce Analytics
A data analytics project designed to explore workforce demographics, recruitment patterns, employee compensation, performance, and retention trends using HR data. The project combines SQL, Python, Excel, and Power BI to transform raw employee records into meaningful business insights and interactive visualizations.

### 🎯 Project Purpose
The HR Workforce Analytics project aims to help HR teams better understand workforce composition, recruitment effectiveness, and employee retention. By analyzing employee records, recruitment sources, departmental performance, and termination patterns, this project explores how data can support HR decision-making and workforce planning.

### 🔎 Quick Start
Follow these steps to get started:
1. Clone the repository.
```bash
git clone https://github.com/ejiang444/hr-workforce-analytics.git
cd hr-workforce-analytics
```
2. Install Python dependencies.
```bash
pip install -r requirements.txt
```
3. Download the dataset from Kaggle:
   - Human Resources Data Set (Version 14)
   - Extract the CSV file into the `data/` folder.
   - Refer to the original Kaggle dataset for its licensing and usage terms.
4. Explore the project files:
   - Data Cleaning and Preparation
   - Exploratory Data Analysis
   - SQL Analysis
   - Power BI Dashboard

### ⭐ Features
- HR data exploration and cleaning
- Employee demographics and workforce analysis
- Recruitment source analysis
- Department-level salary comparisons
- Employee performance and satisfaction analysis
- Employee retention and termination analysis
- Interactive Power BI dashboard
- Business insights and data-driven recommendations

### 🗃️ Data Analytics Workflow
The project is organized into five main stages:
1. Data Collection & Preparation
   - Import employee records from Kaggle
   - Inspect dataset structure and column types
   - Identify missing values, duplicates, and inconsistencies
   - Clean and prepare data for analysis
2. Exploratory Data Analysis (Python)
   - Analyze employee demographics and workforce composition
   - Examine salary distributions and departmental trends
   - Explore recruitment sources and termination patterns
   - Identify trends and relationships within the data
3. SQL Analysis
   - Query employee records using SQL
   - Calculate department-level employee metrics
   - Compare recruitment sources and employment outcomes
   - Analyze salary and employee tenure patterns
4. Power BI Dashboard
   - Develop interactive HR analytics visualizations
   - Display key workforce metrics and KPIs
   - Compare department and recruitment performance
   - Provide filters for exploring employee data
5. Business Insights & Recommendations
   - Summarize key analytical findings
   - Identify workforce trends and potential concerns
   - Develop recommendations to support HR decision-making

### 🏆 Key Performance Indicators (KPIs)
The dashboard will explore the following metrics:
- Total employee records
- Active employee count
- Terminated employee count
- Employee turnover rate
- Average employee salary
- Average employee tenure
- Employee distribution by department
- Employee distribution by recruitment source

### 💡 Business Questions
This project will explore several HR-related business questions:
1. Which departments have the highest employee turnover?
2. Which recruitment sources have the highest employee retention?
3. How does average salary vary across departments and positions?
4. What are the most common reasons for employee termination?
5. Are there relationships between employee satisfaction and performance scores?
6. How does employee tenure vary across departments?
7. Which departments have the highest number of active employees?

### 📈 Dashboard Highlights
The Power BI dashboard will include four analytical sections:
1. HR Overview
   - Workforce summary, including total employees, active employees, and terminated employees
   - Key HR metrics, including employee turnover rate and average salary
2. Recruitment Analysis
   - Employee distribution by recruitment source
   - Employee retention and termination outcomes by recruitment source
3. Department Analysis
   - Employee headcount and average salary across departments
   - Department-level turnover rates and employee distribution
4. Employee Performance & Retention
   - Employee performance scores and satisfaction levels across departments
   - Employee tenure, termination reasons, and retention patterns

### 🐍 Python Analysis
Python will be used for data cleaning, transformation, and exploratory data analysis.
Libraries:
- Pandas - Data manipulation and cleaning
- NumPy - Numerical operations
- Matplotlib - Data visualization
- Seaborn - Statistical visualization

### 🗄️ SQL Analysis
SQL will be used to investigate HR records and answer business questions.
Analysis will include:
- Filtering and aggregating employee records
- GROUP BY and JOIN operations
- CASE WHEN statements
- Subqueries and Common Table Expressions (CTEs)
- Window functions
- Department and recruitment source comparisons

### 📂 File Structure
```
hr-workforce-analytics/
│
├── app/                                        # HR analytics web application
│   ├── dashboard.py                            # Main Streamlit application
│   ├── data_upload.py                          # CSV and Excel uploads
│   ├── data_cleaning.py                        # Data validation and cleaning
│   ├── analytics.py                            # HR metrics and calculations
│   └── visualizations.py                       # Interactive charts
│
├── data/                                       # Original and cleaned HR datasets
│   ├── HRDataset_v14.csv                       # Original dataset downloaded from Kaggle
│   └── cleaned_hr_data.csv                     # Cleaned dataset used for analysis
│
├── python/                                     # Python data analysis files
│   └── exploratory_data_analysis.ipynb         # Data cleaning, exploration, and visualizations
│
├── sql/                                        # SQL queries for analyzing HR data
│   ├── data_exploration.sql                    # Initial data exploration and quality checks
│   ├── recruitment_analysis.sql                # Recruitment source and hiring trend analysis
│   └── employee_analysis.sql                   # Employee status, salary, and turnover analysis
│
├── dashboard/                                  # Power BI dashboard files
│   └── hr_workforce_dashboard.pbix             # Interactive HR workforce dashboard
│
├── screenshots/                                # Dashboard previews and project visuals
│   └── dashboard_preview.png                   # Screenshot of the completed dashboard
│
├── requirements.txt                            # Required Python libraries and dependencies
└── README.md                                   # Project overview, setup instructions, and findings
```

### 📊  Data Requirements
Dates are automatically parsed and standardized by the application.
- A sample HR dataset is included in the data folder
  - https://www.kaggle.com/datasets/rhuebner/human-resources-data-set/data
- Users can upload their own CSV or Excel HR data
- Uploaded files should include, at minimum:
  - Employee ID
  - Department
  - Position
  - Hire Date
  - Employment Status
- Additional columns are supported for more detailed analysis:
  - Salary
  - Termination Date
  - Recruitment Source
  - Performance Score
  - Employee Satisfaction
  - Employee Engagement
  - Termination Reason

Note: This dataset contains employee records rather than a complete applicant tracking system. Recruitment funnel conversion rates and applicant rejection rates cannot be directly calculated from the available data.

### ⬇️ Dependencies
Install the required Python packages:
```bash
pip install -r requirements.txt
```

### ⚙️ System Requirements
- Python 3.10+
- Microsoft Excel
- SQL database environment (PostgreSQL recommended)
- Power BI Desktop
- Git and GitHub

### 📄 Project Report
A detailed project report will be included upon completion, covering:

- Project Description and Business Objectives
- Dataset Overview and Data Preparation
- Analytical Methodology
- SQL Queries and Python Analysis
- Dashboard Design and Visualizations
- Key Findings and Business Recommendations
- Limitations and Future Improvements

### 📎 Acknowledgement
- Dataset provided through Kaggle by Dr. Rich Huebner.
- Thanks to the open-source Python community and Microsoft Power BI documentation for learning resources.

### 👥 Contributor(s)
Emily Jiang
