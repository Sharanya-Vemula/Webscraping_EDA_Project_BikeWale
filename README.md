# 🏍️ BikeWale Web Scraping & Exploratory Data Analysis (EDA)

## Project Overview
This project focuses on collecting motorcycle data from the **BikeWale website** using Python Web Scraping techniques and performing Exploratory Data Analysis (EDA) to identify useful insights about bike brands, pricing, mileage, engine capacity, and customer ratings.

The scraped data is cleaned, processed, and transformed into a structured dataset for further analysis and visualization.

## Project Objectives
- Extract motorcycle information from BikeWale using web scraping.
- Collect data across multiple motorcycle brands.
- Perform data cleaning and handle missing values and duplicates.
- Analyze pricing, mileage, engine capacity, and customer ratings.
- Identify patterns and relationships through data visualization.
- Generate meaningful business insights from the collected data.

## 🛠️ Technologies Used
- **Python**
- **Pandas & NumPy** – Data manipulation and preprocessing
- **BeautifulSoup** – Web scraping and HTML parsing
- **Requests** – Sending HTTP requests
- **Matplotlib & Seaborn** – Data visualization
- **Jupyter Notebook** – Development and analysis

## 📂 Project Files
| File Name | Description |
|---|---|
| `WebScraping Project(Bikes).ipynb` | Web scraping and data collection |
| `WebScraping_Project_Bikewale_EDA.ipynb` | Data cleaning, EDA and visualizations |
| `raw_bike_data.csv` | Original scraped dataset |
| `cleaned_bike_data.csv` | Processed dataset used for analysis |

## 🔄 Project Workflow
1. **Web Scraping:** Extracted motorcycle details from BikeWale across multiple brands.
2. **Data Collection:** Collected bike name, brand, price, mileage, engine capacity, transmission, kerb weight, fuel tank capacity, user rating, and fuel type.
3. **Data Cleaning:** Handled missing values, duplicates, and inconsistent data.
4. **Feature Engineering:** Created price, engine capacity, and mileage categories.
5. **Exploratory Data Analysis:** Performed univariate, bivariate, and multivariate analysis.
6. **Data Visualization:** Created charts and correlation heatmaps to understand patterns.
7. **Insights Generation:** Identified brand-level performance and pricing trends.

## 📊 Dataset Information
- **Source:** BikeWale
- **Total Records Scraped:** 1,032
- **Final Cleaned Records:** 612
- **Brands Covered:** 12
- **Analysis Focus:** Petrol motorcycles

## 🔍 Key Insights
- Ducati has the highest average bike price among the analyzed brands.
- Hero has the lowest average bike price and highest average mileage.
- The Ducati Panigale V4 Lamborghini is the most expensive bike in the analyzed dataset.
- Engine capacity has a positive correlation with price (**0.685**).
- Mileage has a negative correlation with price (**-0.499**).
- High-Performance is the most common engine category in the analyzed dataset.
- Luxury is the most represented price category.

## Future Scope
- Develop a bike price prediction model using Machine Learning.
- Build an interactive dashboard using Power BI or Streamlit.
- Create a bike recommendation system based on user preferences.
- Automate periodic data collection to monitor price changes.
- Extend the analysis to electric motorcycles.

## 👨‍💻 Conclusion
This project demonstrates an end-to-end data analytics workflow, starting from web scraping and data collection to data preprocessing, exploratory analysis, and business insights. It provides practical experience in Python, web scraping, data handling, and visualization while transforming raw website data into meaningful information.

---

**Project Domain:** Data Analytics | Web Scraping | Exploratory Data Analysis

**Data Source:** [BikeWale](https://www.bikewale.com/)
