# DataSpark

DataSpark focuses on Exploratory Data Analysis (EDA) to extract meaningful insights from diverse datasets, including customer demographics, product sales, store performance, and currency exchange rates. By leveraging Python, SQL, and Power BI, the project aims to transform raw data into actionable intelligence for decision-makers.

Data Preprocessing and Cleaning
Handling Missing Values – Imputing or removing missing data as needed.
Column Management – Renaming columns for clarity, dropping unnecessary fields.
Data Cleaning – Parsing dates, formatting numbers, and removing special characters.
The cleaned and preprocessed data is then loaded into MySQL. Some columns are dropped to ensure non-dependency and optimize the database structure.

Database Creation and Schema Design
The code automates the creation of MySQL database tables with appropriate data types for each column.
The Power BI workflow involves loading and transforming data from MySQL, followed by structuring it into a Star Schema.
Dimension and Fact tables are properly defined, with relationships established to ensure efficient data modeling and analysis.
