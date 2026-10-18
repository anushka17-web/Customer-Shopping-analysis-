# Customer Shopping Behavior Analysis

## 1. Overview

This project analyzes customer shopping behavior to identify purchasing patterns, product preferences, customer segments, and key business insights.

The project follows an end-to-end data analytics workflow, from data loading and cleaning in Python to SQL-based analysis and interactive dashboard development in Power BI. A final report and presentation are prepared to communicate the findings and recommendations.

**Objective:** Transform raw customer shopping data into meaningful insights that can support data-driven business decisions.

## 2. Dataset

The project uses a customer shopping behavior dataset containing information about customer demographics, purchased products, purchase frequency, discounts, payment methods, shipping preferences, and customer reviews.

**Key attributes include:**
- Customer ID, age, and gender
- Item purchased and product category
- Purchase amount and review rating
- Frequency of purchases
- Discounts and previous purchases
- Payment method and shipping type
- Subscription status and customer location

*Note: Update this section with the original dataset source, number of records, and number of columns used in your final analysis.*

## 3. Tools and Technologies

| Tool | Purpose |
|---|---|
| Python | Data processing and analysis |
| Pandas | Data manipulation and cleaning |
| NumPy | Numerical operations |
| Matplotlib and Seaborn | Exploratory data analysis and visualization |
| Jupyter Notebook in VS Code | Code execution and documentation |
| SQL (MySQL / PostgreSQL / SQL Server) | Business queries and data analysis |
| Power BI | Interactive dashboard development |
| Gamma | Presentation creation |
| Git and GitHub | Version control and project documentation |

## 4. Project Workflow

### Step 1: Data Loading
- Imported the dataset into Python using Pandas.
- Inspected the dataset structure, dimensions, column names, and data types.

### Step 2: Exploratory Data Analysis (EDA)
- Analyzed numerical and categorical variables.
- Examined customer demographics and purchasing patterns.
- Identified missing values, potential outliers, and data inconsistencies.
- Used statistical summaries and visualizations to understand the data.

### Step 3: Data Cleaning and Preprocessing
- Handled missing values using appropriate imputation techniques.
- Checked for duplicate records and inconsistent values.
- Standardized column names and corrected data types where necessary.
- Prepared a clean dataset for further analysis.

### Step 4: SQL Analysis
- Loaded the cleaned data into a relational database.
- Wrote SQL queries to answer business-related questions.
- Used aggregations, filtering, grouping, sorting, and other SQL operations to analyze customer and product behavior.
- Identified trends in product ratings, purchasing patterns, and customer spending.

### Step 5: Power BI Dashboard
- Connected Power BI to the analyzed dataset.
- Created KPI cards and interactive visualizations.
- Designed charts to explore customer demographics, product performance, purchase amounts, and shopping preferences.
- Organized the visuals into a dashboard for easier interpretation.

### Step 6: Report and Presentation
- Summarized key findings and business insights in a report.
- Prepared a presentation using Gamma to communicate the project objective, methodology, findings, and recommendations.

## 5. Dashboard

The Power BI dashboard is designed to provide a clear overview of customer shopping behavior.

**Planned dashboard components:**
- Total number of customers
- Average review rating
- Average purchase amount
- Product and category performance
- Customer purchasing frequency
- Payment method preferences
- Discount and subscription analysis

*Add a screenshot of your completed dashboard here.*

Example:

`![Power BI Dashboard](images/dashboard.png)`

## 6. Key Results and Business Insights

The analysis is intended to answer questions such as:

- Which products receive the highest average customer ratings?
- Which product categories generate higher purchase amounts?
- What purchasing frequencies are common among customers?
- Which payment methods and shipping options are preferred?
- How do discounts and subscriptions relate to customer shopping behavior?
- Which customer groups may offer opportunities for improved engagement?

**Final findings:** Add the actual insights and numerical results obtained from your SQL queries and Power BI dashboard after completing the analysis.

## 7. Project Structure

```text
customer-shopping-behavior-analysis/
│
├── data/
│   └── customer_shopping_behavior.csv
│
├── notebooks/
│   └── customer_shopping_analysis.ipynb
│
├── sql/
│   └── customer_analysis_queries.sql
│
├── dashboard/
│   └── customer_shopping_dashboard.pbix
│
├── report/
│   └── project_report.pdf
│
├── presentation/
│   └── project_presentation.pdf
│
├── images/
│   └── dashboard.png
│
└── README.md
```

*Adjust the filenames and folders to match your actual repository.*

## 8. How to Run the Project

### Prerequisites
- Python 3.x
- VS Code with Python and Jupyter extensions
- MySQL, PostgreSQL, or SQL Server
- Power BI Desktop
- Required Python libraries

### Step 1: Clone the Repository

```bash
git clone <your-repository-url>
cd customer-shopping-behavior-analysis
```

### Step 2: Install Python Libraries

```bash
pip install pandas numpy matplotlib seaborn sqlalchemy pymysql
```

For PostgreSQL, install the appropriate PostgreSQL driver. For SQL Server, configure a compatible SQLAlchemy driver and database connection.

### Step 3: Load and Analyze the Dataset

- Open the Jupyter Notebook in VS Code.
- Update the dataset path if necessary.
- Run the notebook cells in sequence.
- Review the EDA, cleaning, and preprocessing outputs.

### Step 4: Configure the Database

- Start your database server.
- Create the project database.
- Configure the connection credentials securely.
- Load the cleaned dataset into the database.
- Execute the SQL scripts in your selected database environment.

### Step 5: Open the Power BI Dashboard

- Open the `.pbix` file in Power BI Desktop.
- Configure the database connection if prompted.
- Refresh the data and explore the dashboard.

### Step 6: Review the Deliverables

Open the final report and presentation to review the methodology, analysis, key findings, and recommendations.

## 9. Deliverables

- Python notebook containing EDA and data cleaning
- SQL scripts for business analysis
- Interactive Power BI dashboard
- Project report
- Gamma-generated presentation

## 10. Future Improvements

- Automate data ingestion and preprocessing.
- Add more customer segmentation analysis.
- Develop additional KPIs and drill-through dashboard features.
- Incorporate predictive analytics for purchasing behavior.
- Schedule automated dashboard refreshes.

## 11. Author

**Anushka B. Ghule**

Electronics and Telecommunication Engineering | Aspiring Data Analyst


---

*This project demonstrates practical skills in Python, SQL, data cleaning, exploratory data analysis, dashboard development, and business insight communication.*
