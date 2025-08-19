# Luxury Housing Sales Analysis – Bengaluru

Luxury Housing Market Insights – Data Analysis & Visualization Project

## Project Description
This project analyzes luxury housing sales data in Bengaluru to provide insights into market trends, pricing patterns, buyer demographics, and regional demand. It involves data cleaning, preprocessing, and visualization of property sales to support real estate decision-making.

The goal is to reveal actionable business insights for developers, investors, and market researchers to understand Bengaluru’s luxury housing market dynamics

This project analyzes luxury housing sales data in Bengaluru to uncover insights into **market trends, pricing patterns, buyer demographics, and regional demand**.  
It involves **data cleaning, preprocessing, and visualization** of property sales information to support data-driven decision-making in the real estate sector.  

The goal is to reveal **actionable business insights** that can help **developers, investors, and market researchers** better understand Bengaluru’s luxury housing market dynamics.  
The analysis highlights **quarterly booking trends, builder performance, buyer segmentation (Local vs NRI), and the impact of amenities and connectivity** on sales.  

By combining **statistical techniques, visualization tools, and interactive dashboards**, the project delivers a comprehensive overview of how different factors influence housing sales.  
Ultimately, it provides valuable intelligence for **strategic planning, investment opportunities, and competitive benchmarking** in the luxury real estate market.  


## table of contents
- [project description](#project-description)
- [dataset insight](#dataset-insight)
- [tech stack](#tech-stack)
- [key features](#key-features)
- [documentation](#documentation)
- [dashboard](#dashboard)
- [project structure](#project-structure)
- [faqs](#faqs)


## Goal
The goal of this project is to analyze luxury housing sales in Bengaluru and generate market insights through EDA, visualization, and dashboards.

## Dataset Insight  

The dataset contains information about:  

- **Property ID** – Unique identifier for each property  
- **Project Name** – Name of the housing project  
- **Developer Name** – Builder/real estate developer  
- **Unit Size & Configuration** – e.g., 2BHK, 3BHK, 4BHK  
- **Ticket Price (in Crores)** – Property price in crores  
- **Micro-Market & Locality Scores** – Market segment and infrastructure quality  
- **Buyer Type** – Local vs NRI buyers  
- **Purchase Quarter** – Time of purchase (Q1, Q2, Q3, Q4)  
- **Sales Channel** – Mode of sales (direct, broker, etc.)  
- **Amenity Score** – Rating based on facilities provided  
- **Connectivity Score** – Rating based on transport & accessibility  


## tech stack  

- [**Python**](https://www.python.org/) – Data cleaning, analysis, and visualization  
- [**Pandas**](https://pandas.pydata.org/) – Data manipulation and wrangling  
- [**NumPy**](https://numpy.org/) – Numerical computations & preprocessing  
- [**SQL**](https://www.mysql.com/) – Data warehousing & querying  
- [**Power BI**](https://powerbi.microsoft.com/) – Interactive dashboards & business intelligence  
- [**Matplotlib**](https://matplotlib.org/) / [**Seaborn**](https://seaborn.pydata.org/) – Statistical data visualization  
- [**Excel**](https://www.microsoft.com/microsoft-365/excel) – Initial data exploration & reporting  


## Key Features

- Quarterly booking trend analysis across micro-markets
- Builder performance ranking by ticket sales & avg. ticket price
- Configuration demand (3BHK, 4BHK, etc.)
- Amenity score correlation with booking conversions
- Buyer segmentation (Local vs NRI buyers)
- Locality infrastructure & traffic time insights
- Dashboard with filters for quarter, micro-market, and configuration

## Dash Board  

- **Overview**

 
  ![dashboard overview](https://github.com/vinozzxx/Luxury-Housing-Sales-Analysis-Bengaluru/blob/b4ea0adbf766f36bf4c9baa2541baa0c82460e15/Home.png)  

- **Insights 1**

 
  ![insights 1](https://github.com/vinozzxx/Luxury-Housing-Sales-Analysis-Bengaluru/blob/b4064e372a59d245f782039ce9ce7f17dfbeab7b/insights_1.png)
  
- **Insights 2**

 
  ![insights 2](https://github.com/vinozzxx/Luxury-Housing-Sales-Analysis-Bengaluru/blob/954c0c24edfdd07c4745a30b08ce4a6be07e048b/overview.png) 
 
The dashboard includes the following insights:  

- **Line Chart** – Quarterly bookings by micro-market  
- **Bar Chart** – Builder performance comparison  
- **Scatter Plot** – Amenity score vs Booking success rate  
- **Stacked Column Chart** – Buyer type breakdown (NRI vs Local)  
- **KPI Cards** – Total sales, Average ticket size, Conversion rate  


## Project Structure
```
📁 Luxury-Housing-Sales-Analysis-Bengaluru/
│
├── 📂 data/                     # Raw and cleaned dataset
├── 📂 sql/                      # SQL queries
├── 📂 powerbi/                  # Power BI .pbix file
├── 📂 notebooks/                # Python EDA and preprocessing
├── 📂 docs/                     # Documentation, reports
├── 📄 README.md                 # Project overview
└── 📄 requirements.txt          # Python dependencies
```

FAQs

1. `What is this project about?`
A real estate analytics project that explores luxury housing sales in Bengaluru using Python, SQL, and Power BI.

2.` What insights are provided?`
Micro-market booking patterns
Builder ranking by sales & average price
Configuration demand trends
NRI vs Local buyer distribution
Correlation between amenities & sales

3. `What technologies are used?`
- [**Python**](https://www.python.org/) – Data extraction and processin  
- [**Pandas**](https://pandas.pydata.org/) – Data manipulation  
- [**NumPy**](https://numpy.org/) – Numerical computations 
- [**SQL**](https://www.mysql.com/) – Data analysis  
- [**Power BI**](https://powerbi.microsoft.com/) – Interactive dashboards & business intelligence  
- [**Matplotlib**](https://matplotlib.org/) / [**Seaborn**](https://seaborn.pydata.org/) – Statistical data visualization 

4.` How to run the project?`

```
git clone https://github.com/your-username/Luxury-Housing-Sales-Analysis-Bengaluru.git
cd Luxury-Housing-Sales-Analysis-Bengaluru
open PowerBI file OR run Python notebook
```
5. `Can I contribute?`
Yes! Fork the repo, make your changes, and raise a pull request. All contributions are welcome.













