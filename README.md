 DATA ANALYTICS WITH TABLEAU FULL THEORY DOCUMENTATION
                                       
________________________________________
UNIT – I
Introduction to Business Intelligence (BI) & Tableau
1.1 Business Intelligence (BI)
Business Intelligence (BI) is a technology-driven process used to analyze data and present actionable information to help executives, managers, and organizations make informed business decisions.
BI transforms raw data into meaningful insights through reports, dashboards, and visualizations.
🔹 Importance of BI
•	Improves decision-making
•	Identifies business trends
•	Enhances operational efficiency
•	Increases profitability
•	Supports strategic planning
________________________________________
1.2 BI Process
The BI process generally includes:
1.	Data Collection – Collecting raw data from different sources like databases, Excel, cloud platforms.
2.	Data Integration – Combining data into a unified format.
3.	Data Processing – Cleaning, filtering, and transforming data.
4.	Data Analysis – Applying analytical methods.
5.	Data Presentation – Displaying results using dashboards and reports.
________________________________________
1.3 ETL (Extract, Transform, Load)
ETL is a key concept in BI systems.
🔹 Extract
Data is collected from multiple sources such as:
•	Databases
•	CSV files
•	Excel sheets
•	APIs
🔹 Transform
Data is cleaned and converted into required format:
•	Removing duplicates
•	Handling missing values
•	Standardizing formats
🔹 Load
Transformed data is loaded into:
•	Data warehouse
•	Data marts
•	BI tools
________________________________________
1.4 Types of Data Analytics
1️⃣ Descriptive Analytics
Answers: What happened?
Example: Monthly sales report.
2️⃣ Diagnostic Analytics
Answers: Why did it happen?
Example: Sales decreased due to price increase.
3️⃣ Predictive Analytics
Answers: What will happen?
Example: Forecast next month’s sales.
4️⃣ Prescriptive Analytics
Answers: What should be done?
Example: Recommend discount strategies.

________________________________________
Introduction to Tableau
1.5 What is Tableau?
Tableau Software is a leading data visualization and Business Intelligence tool used to analyze and present data visually.
It provides a user-friendly drag-and-drop interface to create interactive dashboards without heavy coding.
________________________________________
1.6 Features of Tableau
•	Drag-and-drop interface
•	Real-time data analysis
•	Multiple data source connections
•	Interactive dashboards
•	Advanced calculations
•	Storytelling capability
________________________________________
1.7 Connecting Tableau to Data Sources
Tableau supports various data sources:
•	Excel files (.xlsx)
•	CSV files
•	SQL databases
•	Cloud databases
•	PDFs
•	Google Sheets
Flat Files
Files like CSV and text files.
Spreadsheets
Excel files used for structured data.
________________________________________
1.8 Tableau Architecture
Tableau architecture consists of:
🔹 Data Layer
Where data is connected from external sources.
🔹 Application Layer
Handles data processing and calculations.
🔹 Presentation Layer
Displays visualizations and dashboards.
________________________________________
1.9 Live vs Extract Connection
Live Connection
•	Direct connection to database
•	Real-time data
•	Slower if database is large
Extract Connection
•	Snapshot of data
•	Faster performance
•	Stored locally
________________________________________
 UNIT – II
Data Visualization & Data Blending
2.1 Data Visualization
Data visualization represents data graphically to make patterns and trends easier to understand.
Importance:
•	Simplifies complex data
•	Helps quick decision-making
•	Improves communication
________________________________________
2.2 Types of Charts in Tableau
Bar Chart
Used to compare categories.
Line Chart
Shows trends over time.
Pie Chart
Shows proportion or percentage.
Histogram
Displays frequency distribution.
Scatter Plot
Shows relationship between two variables.
Heat Map
Displays intensity using colors.
Tree Map
Shows hierarchical data.
Maps
Used for geographical data analysis.
________________________________________
2.3 Effective Visualization Principles
•	Use correct chart type
•	Avoid unnecessary decorations
•	Maintain color consistency
•	Highlight key KPIs
•	Keep dashboards simple
________________________________________
2.4 Metadata in Tableau
Metadata means “data about data.”
Includes:
•	Field names
•	Data types
•	Default aggregation
•	Relationships
________________________________________
2.5 Joins in Tableau
Inner Join
Returns matching records from both tables.
Left Join
Returns all records from left table.
Right Join
Returns all records from right table.
Full Outer Join
Returns all records from both tables.
________________________________________
2.6 Union
Union combines rows from multiple tables with same structure.
________________________________________
2.7 Data Blending
Data blending is used when:
•	Data comes from different sources
•	No direct join exists
Primary and secondary sources are linked based on common fields.
________________________________________
 UNIT – III
Advanced Data Manipulations & Filters
3.1 Grouping
Grouping combines multiple dimension values into a single category.
Example: Combine cities into regions.
________________________________________
3.2 Sets
Sets are custom subsets of data used for comparison.
Example: Top 10 customers.
________________________________________
3.3 Bins
Bins group continuous data into ranges.
Example: Age groups (20–30, 30–40).
________________________________________
3.4 Hierarchies
Hierarchy allows drill-down analysis.
Example:
Country → State → City
________________________________________
3.5 Sorting
Types:
•	Manual sorting
•	Field-based sorting
•	Nested sorting
________________________________________
3.6 Filters in Tableau
Types of Filters:
•	Extract Filter
•	Data Source Filter
•	Context Filter
•	Dimension Filter
•	Measure Filter
•	Table Calculation Filter
________________________________________
3.7 Order of Execution
Tableau follows this filter order:
Extract → Data Source → Context → Dimension → Measure → Table Calculation
Understanding this is important for correct results.
________________________________________
3.8 Calculated Fields
Calculated fields allow creating custom formulas.
Example:
Profit Ratio = SUM(Profit) / SUM(Sales)
Types:
•	Arithmetic
•	Logical
•	Date
•	Aggregate
________________________________________
3.9 Parameters
Parameters allow user-defined input.
Used for:
•	Switching measures
•	Dynamic filtering
•	Changing chart type
________________________________________
3.10 Mapping in Tableau
•	Use Latitude and Longitude
•	Edit unknown locations
•	Create custom territories
•	Add background images
Maps help in regional business analysis.
________________________________________
UNIT – IV
Dashboards & Stories
4.1 Dashboards
A dashboard combines multiple worksheets in a single screen.
Components:
•	Sheets
•	Filters
•	Legends
•	Images
•	Text boxes
•	Containers
________________________________________
4.2 Dashboard Best Practices
•	Keep layout clean
•	Maintain alignment
•	Use limited colors
•	Highlight KPIs
•	Avoid overcrowding
________________________________________
4.3 Dashboard Actions
Filter Action
Filters data based on selection.
Highlight Action
Highlights related data.
URL Action
Redirects to external link.
________________________________________
4.4 Story Points
Story points are a sequence of dashboards used to present insights step by step.
Used for:
•	Business presentations
•	Executive meetings
•	Analytical reporting
________________________________________
Real-World Applications of Tableau
•	Retail – Sales performance analysis
•	Healthcare – Patient data analysis
•	Finance – Risk & investment analysis
•	Marketing – Campaign performance
•	Education – Student performance tracking
________________________________________
Career Opportunities
After learning Tableau, roles include:
•	Data Analyst
•	Business Intelligence Developer
•	Tableau Developer
•	Business Analyst
________________________________________ Conclusion
Data Analytics with Tableau provides strong knowledge in:
•	Business Intelligence concepts
•	Data visualization techniques
•	Advanced data manipulation
•	Dashboard creation
•	Storytelling using data
Mastering Tableau enables professionals to analyze data effectively and support data-driven decision-making in organizations.
