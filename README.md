### Introduce
Hi! I'm Thanh Vy, though you might also know me as Via or Vivian. I am a final-year student studying Management Information Systems with a major in Data Science. As a data science student, I'm passionate about working with data, particularly in data cleaning and visualization. Beyond data, I enjoy exploring nature, admiring beautiful landscapes and traveling.
These are some notable projects I have completed:
### Project
#### [1.Internship](https://github.com/ViaThanh/1-Profile/blob/058b87ddc67f5ba8d048d5dc754f7ef1cc7d2dfb/B%C3%A1o_C%C3%A1o_Th%E1%BB%B1c_T%E1%BA%ADp_Nguy%E1%BB%85n%20Thanh%20Vy.pdf)
TOOLs: SSMS (SQL Server Management Studio), Python - Jupyter Notebook, Power BI
* **SQL:**
SQL was used to analyze competitor data, leveraging Jupyter Notebook to optimize query speed and efficiently connect with Python. Key analyses performed included:
* Evaluating financial performance by identifying leading companies in terms of ROE, ROA, ROS and growth.
* Analyzing the highest growth rate and calculating the annual profit growth rate.
* Identifying key financial ratios, the highest after-tax profit and accumulated profit over the years.
* Analyzing the total accumulated capital by business segment.
* Ranking companies by performance and identifying those with significant differences compared to the industry average.
* **Python:**
Python was used to process and standardize project data collected from six different business offices. The processing steps included:
* Data Integration: Aggregating data from 6 separate files into a single, unified dataset.
* Data Cleaning: Removing invalid characters, standardizing data formats and correcting data entry errors.
* Data Export: Storing the cleaned dataset in an Excel file for easy use in subsequent Power BI steps and sharing with other departments.
* **Power BI:**
Power BI was used to build a visual reporting dashboard for project opportunities, based on data processed by Python. The implementation steps included:
* Load and Transform Data: Importing data from the Excel file into Power BI and using Power Query Editor to format and transform data (e.g., replace values, split/merge columns, change data types).
* Create Dimension Tables: Building tables containing unique values to facilitate easier data filtering and analysis.
* Data Visualization: Creating a flexible dashboard capable of handling large datasets, with an easy-to-read and understand interface. This dashboard includes charts displaying project sales data in both aggregated (vertical) and monthly (horizontal) formats.
* Utilizing Advanced Features: Applying unpivot columns to convert monthly sales data from a horizontal to a vertical format and using calculation groups to effectively manage key performance indicators (KPIs).
* **Dashboard**
![Report](https://github.com/ViaThanh/Project_Investment_Opportunity_Analysis_Vietnamese/blob/52ab957a1a861f6af67a521d6b4368a0918094bd/IOA_EDA.png)

#### [2.Superstore Sales Data Cleaning and Analysis with SQL](https://github.com/ViaThanh/2-Sales-Data-Cleaning-and-Analysis-with-SQL/blob/e2937726a540d61026bda0c486c1743b3e478a44/Store%20Sales%20Analysis%20with%20SQL.ipynb)
TOOLs: SSMS (SQL Server Management Studio)
This report outlines the data cleaning and analysis process performed on a superstore's sales data using SSMS, with the primary goal of gaining a deeper understanding of business performance by analyzing sales trends, customer behavior and the effectiveness of different product lines.
* **Data Cleaning:**
    * Utilized Stored Procedures to check for and handle NULL and empty values in the data columns.
    * Removed duplicate rows to ensure data uniqueness.
    * Eliminated rows containing an excessive number of missing values, which could potentially skew the analysis.
    * Standardized text data in columns such as ship mode, country, city and region to ensure consistency.
    * Imputed missing values in the sales column with appropriate average values based on other order attributes.
* **Data Analysis:**
    * Sales: Analyzed the Average Order Value (AOV) over time and across different regions, identified the states with the highest sales and tracked monthly and yearly Sales Growth Rate, as well as Purchase Frequency.
    * Customer Segmentation: Analyzed the Total Sales and Average Order Value (AOV) for each customer, identified the customer segments generating the highest sales and exhibiting the most frequent purchasing behavior. Assessed Customer Lifetime and Customer Lifetime Value (CLTV).
    * Products: Identified the top-selling products based on Total Sales and analyzed the Category Contribution to Sales over the years.
    * Customer Churn Rate: Calculated the Customer Churn Rate, identified high-value customers who have stopped making purchases, analyzed the churn rate across different customer segments and investigated potential factors related to customer churn, such as purchased product categories, ship mode and delivery time.

#### [3.Netflix Users Behaviours Analysis](https://github.com/ViaThanh/3-Netflix-Users-Behaviours-Analysis/blob/170d32d073eab24e74f3d7fbed8ba9419b924b83/Netflix_Users_Behaviour_Analysis.ipynb)
TOOLs: Python - Jupyter Notebook
This report outlines the data analysis process performed on a Netflix Users Behaviours dataset, with the primary goal of gaining actionable insights into user demographics, behavior and revenue generation.
* **Data Analysis:**
Demographic Analysis:
* Analyzed user distribution across ages and age groups to identify the largest user segment.
* Evaluated user distribution by country to determine regions with the most users.
* Assessed gender balance and its variation across regions and age groups.
User Behavior Analysis:
* Examined correlations between demographics and subscription types to uncover user preferences.
* Analyzed device usage patterns across demographic groups to understand user experience trends.
* Reviewed signup trends to identify peak periods for new user acquisition.
Revenue Analysis:
* Calculated total and average revenue by age group to pinpoint high-value user segments.
* Analyzed revenue distribution by country to highlight top-performing regions.
Plan Duration Analysis:
* Investigated how subscription duration affects total revenue, identifying whether longer plans lead to higher earnings.

#### [4.Data Preprocessing and Investment Opportunity Analysis - EDA](https://github.com/ViaThanh/4-Data-Preprocessing-and-Investment-Opportunity-Analysis/blob/e2fc02d46ba2ce3b219b48873ac74ad7eb253f7c/EDA_PTTCDN.ipynb)
TOOLs: Python - Jupyter Notebook, Power BI
- The data consists of 03 files: rounds2.csv, mapping.csv and companies.txt.
* **Data Preprocessing and Analysis:**
- Download and load the data into the program.
- Perform data statistics such as max, min, mean, etc.
- Carry out data preprocessing: cleaning, filling in missing data, merging datasets and correcting data discrepancies, etc.
- Analyze the type of investment: compare typical investment amounts in venture, seed, angel, private equity rounds, etc.
- Analyze by country: identify the countries that have received the most investments in the past.
- Analyze by sector: analyze the investment distribution across eight main sectors (mapping.csv file).
*Note: The 'main sectors' are stored in mapping.csv. However, companies.txt and round2.csv contain many sub-sectors, so the mapping file was merged to integrate sub-sectors into main sectors.*
* **Conclusion:**
In this project, we conducted a study using Exploratory Data Analysis (EDA) to analyze the investment opportunity model across different sectors. Through meticulous analysis and the application of EDA techniques, we gained a understanding of the market structure and characteristics, thus identifying:
+ Type of Investment: The most suitable investment type identified through the analysis is Venture. This investment type has shown significant potential for returns and is the preferred choice in most funding rounds.
+ Country Analysis: The United States emerges as the leading country for investment activities, with the highest number of funding rounds and total investment amounts. 
+ Sector Analysis: The sectors with the most significant investment activities include 'Others,' 'Cleantech/Semiconductors,' and 'Social, Finance, Analytics and Advertising.'
* **Dashboard**
![Report](https://github.com/ViaThanh/Project_Investment_Opportunity_Analysis_Vietnamese/blob/52ab957a1a861f6af67a521d6b4368a0918094bd/IOA_EDA.png)

### Introduce
Hi! I'm Thanh Vy, also known as Via or Vivian. I am a final-year student majoring in Data Science within the Management Information Systems program. I am passionate about leveraging data for insightful analysis, particularly in data cleaning and visualization. Beyond academics, I enjoy nature, landscapes, and travel. This portfolio showcases some of my key projects demonstrating my skills and experience.

### Project
#### [1.Internship](https://github.com/ViaThanh/1-Profile/blob/058b87ddc67f5ba8d048d5dc754f7ef1cc7d2dfb/B%C3%A1o_C%C3%A1o_Th%E1%BB%B1c_T%E1%BA%ADp_Nguy%E1%BB%85n%20Thanh%20Vy.pdf)
TOOLs: SSMS (SQL Server Management Studio), Python - Jupyter Notebook, Power BI
This internship project involved a comprehensive analysis of competitor data and internal project data using a combination of SQL, Python, and Power BI. 
* **SQL** was instrumental in dissecting competitor information, employing Jupyter Notebook for query optimization and seamless integration with Python. Key analyses included evaluating financial performance metrics (ROE, ROA, ROS, growth), analyzing growth rates, identifying critical financial ratios and profitability, examining capital distribution across segments, and ranking competitors based on performance and industry benchmarks. 
* **Python** facilitated the processing and standardization of project data from six business offices. This involved integrating disparate datasets into a unified whole, rigorous data cleaning (handling invalid characters, standardizing formats, correcting errors), and exporting the refined data for subsequent visualization. 
* **Power BI** was utilized to construct an interactive dashboard for project opportunity reporting, leveraging the Python-processed data. The implementation encompassed loading and transforming data, creating dimension tables for enhanced analysis, visualizing key metrics through flexible and user-friendly charts (aggregated and monthly sales data), and employing advanced features like unpivot columns and calculation groups for effective KPI management.
**Dashboard**
![Report](https://github.com/ViaThanh/Project_Investment_Opportunity_Analysis_Vietnamese/blob/52ab957a1a861f6af67a521d6b4368a0918094bd/IOA_EDA.png)

#### [2.Superstore Sales Data Cleaning and Analysis with SQL](https://github.com/ViaThanh/2-Sales-Data-Cleaning-and-Analysis-with-SQL/blob/e2937726a540d61026bda0c486c1743b3e478a44/Store%20Sales%20Analysis%20with%20SQL.ipynb)
TOOLs: SSMS (SQL Server Management Studio)
This project focused on cleaning and analyzing a superstore's sales data using SSMS to gain insights into business performance. The **data cleaning** phase involved utilizing stored procedures to manage NULL and empty values, removing duplicates and rows with excessive missing data, standardizing text fields (ship mode, location), and imputing missing sales values using appropriate averages. The **data analysis** explored various aspects of the business. 
* **Sales analysis** tracked Average Order Value (AOV), identified top-performing states, and monitored monthly and yearly sales growth and purchase frequency. 
* **Customer segmentation** involved analyzing total sales and AOV per customer, identifying key customer segments, and assessing Customer Lifetime Value (CLTV). 
* **Product analysis** identified top-selling products and analyzed category contribution to sales trends.
* **Customer churn rate** was calculated, high-value churned customers were identified, churn across segments was analyzed, and potential churn factors (product categories, ship mode, delivery time) were investigated.

#### [3.Netflix Users Behaviours Analysis](https://github.com/ViaThanh/3-Netflix-Users-Behaviours-Analysis/blob/170d32d073eab24e74f3d7fbed8ba9419b924b83/Netflix_Users_Behaviour_Analysis.ipynb)
TOOLs: Python - Jupyter Notebook
This project involved analyzing Netflix user behavior data using Python in Jupyter Notebook to extract actionable insights into user demographics, behavior, and revenue generation. 
* **Demographic analysis** focused on understanding user distribution across different ages and age groups to identify the largest segments, analyzing user distribution by country to pinpoint key regions, and assessing gender balance.
* * **User behavior analysis** examined subscription preferences in relation to demographics, analyzed device usage patterns across different user groups, and reviewed user signup trends over time.
* **Revenue analysis** calculated total and average revenue generated by different age groups to identify high-value segments and analyzed revenue distribution by country.
* **Plan duration analysis** investigated the relationship between subscription plan duration and total revenue, determining if longer plans correlate with higher earnings.

#### [4.Data Preprocessing and Investment Opportunity Analysis - EDA](https://github.com/ViaThanh/4-Data-Preprocessing-and-Investment-Opportunity-Analysis/blob/e2fc02d46ba2ce3b219b48873ac74ad7eb253f7c/EDA_PTTCDN.ipynb)
TOOLs: Python - Jupyter Notebook, Power BI
This project involved data preprocessing and exploratory data analysis (EDA) on investment opportunity data from three files: rounds2.csv, mapping.csv, and companies.txt. 
* **Data preprocessing and analysis** steps included downloading and loading the data, performing descriptive statistics, cleaning and handling missing data, merging datasets, and correcting inconsistencies. The analysis focused on understanding investment types (comparing typical amounts in venture, seed, angel, private equity rounds), analyzing investment distribution by country to identify top recipient nations, and examining investment distribution across eight main business sectors (using the mapping.csv file to categorize sub-sectors from companies.txt and round2.csv).
* **Conclusion:** The EDA revealed that Venture is the most prevalent investment type. The United States stands out as the leading country for investment activity. The 'Others,' 'Cleantech/Semiconductors,' and 'Social, Finance, Analytics and Advertising' sectors attract the most significant investment.
* **Dashboard**
![Report](https://github.com/ViaThanh/Project_Investment_Opportunity_Analysis_Vietnamese/blob/52ab957a1a861f6af67a521d6b4368a0918094bd/IOA_EDA.png)
