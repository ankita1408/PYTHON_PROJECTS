# python_projects

This repository contains exploratory data analysis (EDA), data cleaning, and web scraping. Below is an overview of each project.

---

## [1. Exploratory Data Analysis on World Population Trends](https://github.com/ankita1408/PYTHON_PROJECTS/tree/master/EDA%20IN%20PANDAS)

### Overview
This project involved analyzing a population dataset spanning from 1970 to 2022, segmented by countries and continents. The goal was to explore and validate trends in world population, with a focus on key patterns across different continents.

### Steps Taken:
- **Data Validation & Exploration**: 
  - Used `.info()`, `.describe()`, and `.nunique()` to assess the dataset's structure and completeness.
- **Data Cleaning**:
  - Handled missing values using `isnull()` to clean the data.
- **Continent-Wise Aggregation**:
  - Calculated average population growth trends from 1970 to 2022 to reveal significant patterns.
- **Visualization**:
  - Generated correlation heatmaps to explore relationships between numeric variables.
  - Created interactive visualizations using **Matplotlib** and **Seaborn**, including boxplots, heatmaps, and trendline charts.
- **Key Insights**:
  - Identified the top 10 countries by population in 2022.
  - Highlighted world population percentages by continent and significant trends in global population growth.

---

## 2. [Customer Call List Data Cleaning](https://github.com/ankita1408/PYTHON_PROJECTS/tree/master/DATA%20CLEANING%20IN%20PANDAS)

### Overview
In this project, the goal was to clean and preprocess a "Customer Call List" dataset to improve its quality and usefulness for further analysis.

### Steps Taken:
- **Removing Duplicates**: 
  - Eliminated duplicate entries to ensure data uniqueness.
- **Dropping Irrelevant Columns**:
  - Removed columns such as `Not_Useful_Column`.
- **Phone Number Standardization**:
  - Cleaned and formatted phone numbers to a consistent `XXX-XXX-XXXX` format.
- **Handling Missing Data**:
  - Replaced 'N/a' with empty strings and dropped rows with missing phone numbers.
- **Categorical Normalization**:
  - Standardized categorical columns such as `Paying Customer` and `Do_Not_Contact` to 'Y'/'N'.
- **Row Removal**:
  - Removed rows marked as "Do Not Contact" or missing phone numbers.
- **Resetting Index**:
  - Reset the index to ensure a continuous, sequential index after cleaning.

---

## 3. [India’s Largest Companies Web Scraping](https://github.com/ankita1408/PYTHON_PROJECTS/tree/master/web_scrapping)

### Overview
This project involves web scraping data from Wikipedia to gather information about India's largest companies. The data collected includes essential business details such as company name, revenue, profit, headquarters, and industry.

### Technologies Used:
- **Python**: Programming language used for scripting.
- **BeautifulSoup**: Library for parsing HTML and extracting relevant data.
- **Requests**: Used to make HTTP requests to Wikipedia pages.
- **Pandas**: Used to organize and display the scraped data in a tabular format.

### Key Information Scraped:
- **Company Name**
- **Revenue**
- **Revenue Growth**
- **Profit**
- **Headquarters**
- **Industry**

---

