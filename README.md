ShadowFox Internship Projects --- Data Analytics
A collection of my Beginner, Intermediate, and Advanced Data Analytics
projects completed as part of my Data Analytics internship at Shadow
Fox. The projects demonstrate data cleaning, exploratory data
analysis, KPI development, dashboard design, and communicating insights
through reports and presentations.
Internship Details
- Student: Nitu Singh
- University: Osmania University
- Company: Shadow Fox
- Role: Data Analytics Intern
- Duration: October 1--31, 2026
- Mentor: Mr. Aakash
Projects at a Glance
  Level             Project           Tools             Focus
  Beginner          Superstore Orders Microsoft Excel   Sales, profit,
                    Analysis                            orders, markets,
                                                        categories and
                                                        discounts

  Intermediate      Online Retail II  Python, Pandas,   Transaction
                    --- Retail Sales  Google            cleaning, revenue
                    & Customer        Colab/Jupyter,    trends, products,
                    Analytics         Power BI          countries and
                                                        customer analysis

  Advanced          IBM HR Analytics  Power BI, Power   Workforce KPIs
                    --- Employee      Query, DAX        and employee
                    Attrition                           attrition
                Analysis                            patterns
1. Beginner --- Superstore Orders Analysis
Objective
Analyze superstore orders to understand sales, profit, product
categories, markets, customer segments, shipping priorities and discount
patterns, then present the results in an Excel dashboard.
Dataset
- Name: Superstore Orders
- Size: More than 52,000 rows
- Format used: CSV, analyzed in Excel
- Fields include: Order ID, Order Date, Ship Date, Ship Mode,
  Customer Name, Segment, State, Country, Market, Region, Product ID,
  Category, Subcategory, Product Name, Sales, Quantity, Discount,
  Profit, Shipping Cost, Order Priority and Year.
- Dataset link:[link](https://www.kaggle.com/datasets/laibaanwer/superstore-sales-dataset)
Microsoft Excel, data quality checks, duplicate checks, PivotTables, KPI
calculations, charts and dashboard design.
Data Preparation
- Checked for blank Sales values and blank Order IDs.
- Checked duplicate rows across the dataset fields; no exact duplicate
  rows were found in the workbook checks.
- Organized analysis and dashboard content in the workbook.
Key KPIs
  KPI                    Result
  Total Sales        12,642,905
  Total Profit        1,469,035
  Total Quantity        178,312
  Profit Margin          11.62%
Dashboard Coverage
- Yearly sales and profit performance
- Sales and profit by category
- Sales and profit by market
- Sales and profit by customer segment
- Order count by priority
- Order count by shipping mode
- Profit margin by discount
Key Findings
- Technology had the highest sales and profit among the three main
  categories in the analysis.
- APAC was the strongest market for both sales and profit.
- Orders with no discount had the strongest overall profit
  performance.
- In the analyzed pivot, negative profit began around the 20.20%
  discount level.
2. Intermediate --- Online Retail II: Retail Sales & Customer Analytics
Objective
Analyze retail transactions to identify revenue trends, product and
country performance, order-value patterns and customer segments. The
project combines Python-based data preparation and analysis with
dashboard reporting.
Dataset
- Exact dataset filename: Online_Retail_II.csv --- Roman numeral
  II, not digit 2.
- Original size: 1,067,371 rows × 8 columns
- Columns: Invoice, StockCode, Description, Quantity, InvoiceDate,
  Price, Customer ID and Country
- Dataset source:[link](https://www.kaggle.com/datasets/mashlyn/online-retail-ii-uci)
Tools and Methods
Python, Pandas, Google Colab/Jupyter, data-quality profiling, data
cleaning, exploratory data analysis (EDA), revenue calculations and
Power BI.
Data Preparation
- Removed 34,335 exact duplicate rows, leaving 1,033,036 rows.
- Profiled missing descriptions and missing Customer IDs.
- Checked negative/zero quantities, zero/negative prices, cancellation
  invoices and invalid invoice dates.
- Calculated revenue as Quantity × Price.
- Excluded cancellation invoices, non-positive quantities and
  non-positive prices from the sales-analysis dataset.
- Kept rows with missing Customer IDs for overall sales analysis, but
  excluded them from customer-level/RFM analysis.
Key Metrics
  Metric                                                           Result
  Total sales revenue in the                                20,476,260.45
  analyzed transaction dataset   

  Distinct invoices                                                40,077

  Customers with known Customer                                     5,878
  ID                             

  Average order value                                              469.98

  Median order value                                               303.04
  (customer-known orders)        

  Revenue from customer-known                               17,374,804.27
  transactions                   
  Customer-known orders                                            36,969
Metric note: Revenue and order metrics can differ depending on
whether transactions with missing Customer IDs are included. The project
distinguishes overall transaction analysis from customer-level analysis.
No currency symbol is shown because the source currency was not
independently confirmed.
Analysis Outputs
- Transaction-level sales
- RFM customer analysis
- Monthly and yearly revenue
- Product performance
- Country performance
- Customer segments
- Yearly product sales
- Top orders
Data Quality Considerations
The product PAPER CRAFT, LITTLE BIRDIE had a very large quantity
(80,995) and revenue of 168,469.60. It was flagged for validation as a
potential outlier rather than automatically removed as an error. The
years 2009 and 2011 are partial years, so comparisons should account for
incomplete periods.
3. Advanced --- IBM HR Analytics: Employee Attrition Analysis
Objective
Build a one-page Power BI dashboard to examine employee attrition by
department, job role, age group, job satisfaction, company tenure and
business travel.
Dataset
- File used: IBM_HR_Analytics_PowerBI.csv
- Size: 1,470 rows × 39 columns
- Data quality: No missing values or duplicate rows remained after
  the project's data checks.
- Source link:[link](https://www.kaggle.com/datasets/pavansubhasht/ibm-hr-analytics-attrition-dataset/data)
Tools and Methods
Power BI Desktop, Power Query, DAX measures, KPI cards, charts and
slicers.
Data Preparation and Metrics
- Created AttritionFlag: 0 = stayed, 1 = left.
- Employees who stayed: 1,233
- Employees who left: 237
- Total employees: 1,470
- Overall attrition rate: 16.12%
- Average monthly income of employees who left: ₹4,787.09 (the visual
  was filtered to employees with Attrition = Yes).
Dashboard KPIs
- Total Employees
- Employees Left
- Attrition Rate
- Average Monthly Income of Employees Who Left
Dashboard Visuals
1. Employees Who Left by Department
2. Attrition Rate by Department
3. Attrition Rate by Job Role
4. Attrition by Age Group
5. Attrition Over Time
6. Employees Who Left by Job Satisfaction
7. Employees Who Left by Company Tenure
8. Attrition Rate by Business Travel
Slicers: Department, Job Role, Business Travel, Age Group, Gender and
Marital Status.
Key Findings
- Overall attrition rate was 16.12%.
- Sales had 92 exits, Human Resources had 12, and Research &
  Development had 133.
- Sales Representatives had the highest attrition rate among the
  listed job roles (39.76%).
- Attrition was 24.91% for employees who travelled frequently,
  compared with 8.00% for Non-Travel and 14.96% for Travel_Rarely.
Skills Demonstrated
- Data cleaning and data-quality validation
- Exploratory data analysis
- KPI and business metric calculation
- Excel analysis and dashboarding
- Python and Pandas
- Power BI, Power Query and DAX
- Sales, product, market, customer and workforce analysis
- Communicating findings through reports and presentations
How to Review
1. Open the folder for the project level you want to review.
2. Read its report for the objective, workflow, findings and
   limitations.
3. Open the presentation for a concise walkthrough.
4. View the dashboard screenshot or open the workbook/Power BI file
   where supported.
5. Use the dataset links above to learn about the source data.
Acknowledgement
I thank Shadow Fox and my mentor Mr. Aakash for the opportunity
to complete these Data Analytics projects and strengthen my practical
skills in data preparation, analysis, visualization and reporting.
Author: Nitu Singh
Focus: Data Analytics | Excel | SQL | Python | Power BI
