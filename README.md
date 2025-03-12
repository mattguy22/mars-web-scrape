# **Mars Web Scraping & Analysis**

Created by Matthew Guy, 2025  

## **Project Overview**  
This project involves web scraping, data cleaning, and analysis to extract insights from Mars news articles and weather data. Using **Splinter, BeautifulSoup, Pandas, and Matplotlib**, we scrape and analyze Mars-related information from multiple sources.

## **Table of Contents**  
- [Features](#features)  
- [Installation](#installation)  
- [Usage Instructions](#usage-instructions)  
- [Data Extraction](#data-extraction)  
- [Data Analysis & Visualization](#data-analysis--visualization)  
- [Results & Insights](#results--insights)  
- [Future Enhancements](#future-enhancements)  
- [About](#about)  
- [Resources](#resources)  

---

## **Features**  
- **Automated Web Scraping:** Extracts Mars news headlines, summaries, and weather data using BeautifulSoup & Splinter.  
- **Structured Data Storage:** Stores scraped data in structured Python lists and Pandas DataFrames.  
- **Data Analysis & Visualization:** Uses Pandas and Matplotlib to analyze weather trends on Mars.  
- **CSV Export:** Saves the processed data for further use or sharing.  

---

## **Installation**  

### **Requirements**  
- Python 3.x  
- Jupyter Notebook (or VS Code with Jupyter extension)  
- Chrome WebDriver  
- Required Libraries: `splinter`, `beautifulsoup4`, `pandas`, `matplotlib`  

### **Pre-Built Setup**  
Download the provided starter files, ensure dependencies are installed, and execute the Jupyter Notebooks in order.

---

## **Usage Instructions**  

### **1. Web Scraping**
- Open **`part_1_mars_news.ipynb`** to scrape Mars news articles.  
- Open **`part_2_mars_weather.ipynb`** to scrape and analyze Mars weather data.

### **2. Data Processing**
- The scraped data is cleaned and stored in Pandas DataFrames.  
- Column data types are converted for analysis.

### **3. Data Visualization**
- Bar charts illustrate **temperature** and **pressure trends** across months.  
- Line plots visualize **seasonal temperature variations** over time.

### **4. Exporting Data**
- The final dataset is exported as **`mars_weather_data.csv`** for further use.

---

## **Data Extraction**  

The project extracts data from the following sources:  

1. **Mars News**: Scrapes article titles and summaries from NASA’s Mars Exploration Program.  
2. **Mars Weather**: Extracts historical weather data from a structured HTML table.

Data is stored in **Pandas DataFrames** with structured column headers.

---

## **Data Analysis & Visualization**  

The project answers key questions using **data analysis & visualizations**:  

- **How many months exist on Mars?** → 12 months  
- **How many Martian days are in the dataset?** → 1,867 sols  
- **What are the coldest and warmest months on Mars?**  
  - Coldest: **Month 3 (~-83.3°C)**  
  - Warmest: **Month 8 (~-68.4°C)**  
- **What are the months with the lowest & highest atmospheric pressure?**  
  - Lowest Pressure: **Month 6 (~745 Pa)**  
  - Highest Pressure: **Month 9 (~913 Pa)**  
- **How many Earth days are in a Martian year?**  
  - Estimated ~**687 Earth days**  

Visualizations include **bar charts** and **line plots** to highlight trends.

---

## **Results & Insights**  

- **Temperature Trends:** Mars experiences significant seasonal variations.  
- **Pressure Variations:** Atmospheric pressure fluctuates due to seasonal changes.  
- **Martian Year:** Temperature cycles confirm Mars' year is **~687 Earth days** long.  

---

## **Future Enhancements**  

- **Automate Data Collection**: Schedule scraping for real-time data updates.  
- **Enhance Visualizations**: Use Seaborn for improved graph aesthetics.  
- **Expand Analysis**: Include wind speed & other environmental factors.  

---

## **About**  
This project was developed as part of a web scraping and data analysis challenge, leveraging **BeautifulSoup, Splinter, Pandas, and Matplotlib**.

---

## **Resources**  
- **NASA Mars Exploration Program** ([mars.nasa.gov](https://mars.nasa.gov/))  
- **BeautifulSoup Documentation** ([beautiful-soup-4.readthedocs.io](https://beautiful-soup-4.readthedocs.io/))  
- **Splinter WebDriver** ([splinter.readthedocs.io](https://splinter.readthedocs.io/))  
- **DU Bootcamp Module 11 Lessons** – Provided guidance web scrape, and soup coding syntax for some of the data analysis queries.
- **ChatGPT** – Assisted with refining plot coding syntax specifically in how to change the x axis so the months didnt define the order of the visualization. Also assisted with syntax errors in the for loops through text    elements.  