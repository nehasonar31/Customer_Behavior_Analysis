# Customer Shopping Behavior Analysis

## Overview
This project analyzes customer shopping patterns to uncover insights such as product popularity, revenue trends, customer segments, and subscription behavior. The workflow includes data processing in Python, analytical querying in MS SQL, and visualization through Power BI.

## Dataset
- 3,900 rows
- 18 columns
- Contains customer demographics, product details, purchase amounts, shipping type, review ratings, and behavioral indicators
- Source: Included in project repository

## Tools & Technologies
- Python (pandas, numpy) — data loading & cleaning
- MS SQL Server — analytical SQL queries
- SQL Server Management Studio (SSMS) — database inspection & execution
- Power BI — dashboard visualization
- Git / GitHub — version control

## Steps Performed
### 1. Data Loading & Inspection (Python)
Imported dataset using pandas  
Reviewed structure with df.info() and df.describe()  
Checked and handled missing data  

2. Data Cleaning & Feature Engineering
Imputed missing review ratings
Standardized column names to snake_case
Created age_group segmentation
Organized purchase frequency and repeat buyer indicators

3. Database Integration
Loaded the cleaned dataset into MS SQL Server from Python
Utilized Windows authentication connection
Created SQL table for customer data

4. SQL Analysis (Business Queries)
Revenue by gender
Top rated products
Subscription vs spending
Discount-dependent products
Age-group revenue contribution
Repeat customers & loyalty behavior

5. Dashboard in Power BI
Built interactive dashboard with:
Revenue by category
Spend by shipping type
Customer segmentation
Average review scores
Subscription breakdown

<img width="1199" height="550" alt="Dashboard" src="https://github.com/user-attachments/assets/39f95941-f877-4b3c-a638-2a3d2ad792e7" />


## Results & Insights
- Subscribers show higher overall spend behavior
- Some discount-driven products consistently perform well
- Certain age groups contribute significantly more revenue
- Express shipping correlates with higher purchase amounts
- Highest-rated products cluster strongly in specific categories


## How to Run
### Prerequisites
- Python 3.11+
- MS SQL Server & SSMS
- Power BI Desktop

## Steps
- Clone this repository
- Install required Python packages
- pip install -r requirements.txt
- Open dataset in Python and run notebook for EDA
- Load cleaned data into MS SQL via provided script
- Execute SQL queries in SSMS
- Open Power BI file to view final dashboard

## Author
#### Neha Sonar
Data Analyst | Python | SQL | Power BI
