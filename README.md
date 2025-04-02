### Introduce
Hi! I'm Thanh Vy, though you might also know me as Via or Vivian. I am a final-year student studying Management Information Systems with a major in Data Science. As a data science student, I'm passionate about working with data, particularly in data cleaning and visualization. Beyond data, I enjoy exploring nature, admiring beautiful landscapes and traveling.
These are some notable projects I have completed:
### Project
#### [1.Internship](https://github.com/ViaThanh/1-Profile/blob/058b87ddc67f5ba8d048d5dc754f7ef1cc7d2dfb/B%C3%A1o_C%C3%A1o_Th%E1%BB%B1c_T%E1%BA%ADp_Nguy%E1%BB%85n%20Thanh%20Vy.pdf)
TOOLs: SSMS (SQL Server Management Studio), Python + Jupyter Notebook, Power BI .
* **SQL:** SQL was used to analyze competitor data, leveraging Jupyter Notebook to optimize query speed and efficiently connect with Python. Key analyses performed included:
    + Evaluating financial performance by identifying leading companies in terms of ROE, ROA, ROS and growth.
    + Analyzing the highest growth rate and calculating the annual profit growth rate.
    + Identifying key financial ratios, the highest after-tax profit and accumulated profit over the years.
    + Analyzing the total accumulated capital by business segment.
    + Ranking companies by performance and identifying those with significant differences compared to the industry average.
* **Python:** Python was used to process and standardize project data collected from six different business offices. The processing steps included:
    + Data Integration: Aggregating data from 6 separate files into a single, unified dataset.
    + Data Cleaning: Removing invalid characters, standardizing data formats and correcting data entry errors.
    + Data Export: Storing the cleaned dataset in an Excel file for easy use in subsequent Power BI steps and sharing with other departments.
* **Power BI:** Power BI was used to build a visual reporting dashboard for project opportunities, based on data processed by Python. The implementation steps included:
    + Load and Transform Data: Importing data from the Excel file into Power BI and using Power Query Editor to format and transform data (e.g., replace values, split/merge columns, change data types).
    + Create Dimension Tables: Building tables containing unique values to facilitate easier data filtering and analysis.
    + Data Visualization: Creating a flexible dashboard capable of handling large datasets, with an easy-to-read and understand interface. This dashboard includes charts displaying project sales data in both aggregated (vertical) and monthly (horizontal) formats.
    + Utilizing Advanced Features: Applying unpivot columns to convert monthly sales data from a horizontal to a vertical format and using calculation groups to effectively manage key performance indicators (KPIs).
* **Dashboard**
![Report](https://github.com/ViaThanh/Project_Investment_Opportunity_Analysis_Vietnamese/blob/52ab957a1a861f6af67a521d6b4368a0918094bd/IOA_EDA.png)

#### [2.Superstore Sales Data Cleaning and Analysis with SQL](https://github.com/ViaThanh/2-Sales-Data-Cleaning-and-Analysis-with-SQL/blob/e2937726a540d61026bda0c486c1743b3e478a44/Store%20Sales%20Analysis%20with%20SQL.ipynb)
TOOLs: SSMS (SQL Server Management Studio) . 
This report outlines the data cleaning and analysis process performed on a superstore's sales data using SSMS, with the primary goal of gaining a deeper understanding of business performance by analyzing sales trends, customer behavior and the effectiveness of different product lines.
* **Data Cleaning:**
    + Utilized Stored Procedures to check for and handle NULL and empty values in the data columns.
    + Removed duplicate rows to ensure data uniqueness.
    + Eliminated rows containing an excessive number of missing values, which could potentially skew the analysis.
    + Standardized text data in columns such as ship mode, country, city and region to ensure consistency.
    + Imputed missing values in the sales column with appropriate average values based on other order attributes.
* **Data Analysis:**
    + Sales: Analyzed the Average Order Value (AOV) over time and across different regions, identified the states with the highest sales and tracked monthly and yearly Sales Growth Rate, as well as Purchase Frequency.
    + Customer Segmentation: Analyzed the Total Sales and Average Order Value (AOV) for each customer, identified the customer segments generating the highest sales and exhibiting the most frequent purchasing behavior. Assessed Customer Lifetime and Customer Lifetime Value (CLTV).
    + Products: Identified the top-selling products based on Total Sales and analyzed the Category Contribution to Sales over the years.
    + Customer Churn Rate: Calculated the Customer Churn Rate, identified high-value customers who have stopped making purchases, analyzed the churn rate across different customer segments and investigated potential factors related to customer churn, such as purchased product categories, ship mode and delivery time.

#### [3.Netflix Users Behaviours Analysis](https://github.com/ViaThanh/3-Netflix-Users-Behaviours-Analysis/blob/170d32d073eab24e74f3d7fbed8ba9419b924b83/Netflix_Users_Behaviour_Analysis.ipynb)
TOOLs: Python + Jupyter Notebook . 
This report outlines the data analysis process performed on a Netflix Users Behaviours dataset, with the primary goal of gaining actionable insights into user demographics, behavior and revenue generation.
* **Data Analysis:**
Demographic Analysis:
    + Analyzed user distribution across ages and age groups to identify the largest user segment.
    + Evaluated user distribution by country to determine regions with the most users.
    + Assessed gender balance and its variation across regions and age groups.
User Behavior Analysis:
    + Examined correlations between demographics and subscription types to uncover user preferences.
    + Analyzed device usage patterns across demographic groups to understand user experience trends.
    + Reviewed signup trends to identify peak periods for new user acquisition.
Revenue Analysis:
    + Calculated total and average revenue by age group to pinpoint high-value user segments.
    + Analyzed revenue distribution by country to highlight top-performing regions.
Plan Duration Analysis:
    + Investigated how subscription duration affects total revenue, identifying whether longer plans lead to higher earnings.

#### [4.Data Preprocessing and Investment Opportunity Analysis + EDA](https://github.com/ViaThanh/4-Data-Preprocessing-and-Investment-Opportunity-Analysis/blob/e2fc02d46ba2ce3b219b48873ac74ad7eb253f7c/EDA_PTTCDN.ipynb)
TOOLs: Python + Jupyter Notebook, Power BI .
The data consists of 03 files: rounds2.csv, mapping.csv and companies.txt.
* **Data Preprocessing and Analysis:**
    + Download and load the data into the program.
    + Carry out data preprocessing: cleaning, filling in missing data, merging datasets and correcting data discrepancies, etc.
    + Analyze the type of investment: compare typical investment amounts in venture, seed, angel, private equity rounds, etc.
    + Analyze by country: identify the countries that have received the most investments in the past.
    + Analyze by sector: analyze the investment distribution across eight main sectors (mapping.csv file).
*Note: The 'main sectors' are stored in mapping.csv. However, companies.txt and round2.csv contain many sub-sectors, so the mapping file was merged to integrate sub-sectors into main sectors.*
* **Conclusion:**
In this project, we conducted a study using Exploratory Data Analysis (EDA) to analyze the investment opportunity model across different sectors. Through meticulous analysis and the application of EDA techniques, we gained a understanding of the market structure and characteristics, thus identifying:
    + Type of Investment: The most suitable investment type identified through the analysis is Venture. This investment type has shown significant potential for returns and is the preferred choice in most funding rounds.
    + Country Analysis: The United States emerges as the leading country for investment activities, with the highest number of funding rounds and total investment amounts. 
    + Sector Analysis: The sectors with the most significant investment activities include 'Others,' 'Cleantech/Semiconductors,' and 'Social, Finance, Analytics and Advertising.'
* **Dashboard**
<img src="https://github.com/ViaThanh/Project_Investment_Opportunity_Analysis_Vietnamese/blob/52ab957a1a861f6af67a521d6b4368a0918094bd/IOA_EDA.png" width="400">


### Introduce
Hi! I'm Thanh Vy, also known as Via or Vivian. I am a final-year Management Information Systems student majoring in Data Science. I'm passionate about working with data, particularly in data cleaning and visualization. Beyond data, I enjoy exploring nature, admiring beautiful landscapes, and traveling.

### Project

- **[1. Internship](https://github.com/ViaThanh/1-Profile/blob/058b87ddc67f5ba8d048d5dc754f7ef1cc7d2dfb/B%C3%A1o_C%C3%A1o_Th%E1%BB%B1c_T%E1%BA%ADp_Nguy%E1%BB%85n%20Thanh%20Vy.pdf)**
  - **Tools:** SQL, Python, Power BI  
  - **SQL:**
    - Analyzed competitor data using Jupyter Notebook for optimized query speed.
    - Key metrics included ROE, ROA, ROS, and growth rate.
    - Ranked companies by performance and identified significant industry deviations.
  - **Python:**
    - Processed and standardized data from six business offices.
    - Steps included integration, cleaning invalid characters, standardizing formats, and exporting to Excel for further analysis.
  - **Power BI:**
    - Built a visual reporting dashboard for project opportunities.
    - Applied data transformation techniques and created flexible, intuitive charts for both aggregated and monthly sales data.

- **[2. Superstore Sales Data Analysis with SQL](https://github.com/ViaThanh/2-Sales-Data-Cleaning-and-Analysis-with-SQL/blob/e2937726a540d61026bda0c486c1743b3e478a44/Store%20Sales%20Analysis%20with%20SQL.ipynb)**
  - **Tools:** SQL (SSMS)  
  - **Data Cleaning:**
    - Used stored procedures to check for NULL values and removed duplicates to ensure data integrity.
    - Standardized text data in columns like ship mode, country, and region.
  - **Data Analysis:**
    - Analyzed Average Order Value (AOV), sales growth rate, and purchase frequency over time.
    - Segmented customers by lifetime value and purchasing behavior.
    - Identified top-selling products and calculated churn rate.

- **[3. Netflix Users Behavior Analysis](https://github.com/ViaThanh/3-Netflix-Users-Behaviours-Analysis/blob/170d32d073eab24e74f3d7fbed8ba9419b924b83/Netflix_Users_Behaviour_Analysis.ipynb)**
  - **Tools:** Python (Jupyter Notebook)  
  - **Demographic Analysis:**
    - Evaluated user distribution by age group and region.
    - Analyzed gender balance across demographics.
  - **User Behavior Analysis:**
    - Explored correlations between demographics and subscription types.
    - Assessed device usage patterns and signup trends.
  - **Revenue Analysis:**
    - Calculated total and average revenue by age group and region.
    - Analyzed how subscription duration impacts revenue.

- **[4. Investment Opportunity Analysis - EDA](https://github.com/ViaThanh/4-Data-Preprocessing-and-Investment-Opportunity-Analysis/blob/e2fc02d46ba2ce3b219b48873ac74ad7eb253f7c/EDA_PTTCDN.ipynb)**
  - **Tools:** Python, Power BI  
  - **Data Preprocessing:**
    - Cleaned, merged, and filled missing data from three datasets.
    - Addressed data discrepancies and standardized formats.
  - **Investment Analysis:**
    - Compared investment types, highlighting venture capital as the most profitable.
    - Identified the U.S. as the top destination for funding and analyzed sector-specific investment distribution.
  - **Dashboard:**
    - Created visual dashboards to illustrate market structure and key investment trends across sectors.

