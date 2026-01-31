# Bike Sales Dashboard (Excel Project)

## 📌 Project Overview  
This Excel project focuses on analyzing bike buyer data to understand customer patterns and purchasing behavior. The objective is to convert raw data into a clear and interactive dashboard that helps identify the most valuable customer segments.

## 📂 Dataset Description  
The dataset contains information related to customer demographics, income, education level, and commute distance.  
* **Source:** Excel Data Analysis Tutorial (Alex The Analyst)  
* **File Structure:**  
    * `bike_buyers` – Raw dataset containing original records.  
    * `working_sheet` – Cleaned and formatted data used for analysis.  
    * `pivot_table` – Pivot tables created for summarizing data.  
    * `Dashboard` – Final dashboard with interactive charts and slicers.  

## 🛠️ Process & Methodology  
### 1. Data Cleaning  
Several steps were performed to improve data quality:  
* **Duplicate Removal:** Deleted repeated records to avoid incorrect insights.  
* **Value Standardization:** Updated short forms like M/F into full values (Male/Female, Married/Single).  
* **Income Formatting:** Converted income values into proper currency format.  

### 2. Feature Engineering  
* **Age Groups:** A new column `Age Group` was created using conditional formulas:  
    * **Adolescent:** (<31)  
    * **Middle:** (31–65)  
    * **Old:** (65+)  
    * *Purpose:* Grouping ages makes trend analysis easier and more meaningful.  

### 3. Analysis & Visualization  
Pivot Tables and charts were used to build the dashboard:  
* **Income vs Purchase:** Compared average income based on gender and purchase decision.  
* **Age Group vs Purchase:** Identified which age range buys the most bikes.  
* **Commute Distance Analysis:** Studied how travel distance affects bike purchases.  

## 📊 Key Insights  
* **Middle-Aged Customers Lead:** The middle-aged segment shows the highest number of bike purchases.  
* **Short Distance Buyers:** Customers with 0–1 mile commute distance show the highest purchase rate.  
* **Income Difference:** Male customers have slightly higher average income compared to female customers.  

## 🧰 Tools Used  
* **Microsoft Excel:**  
    * Pivot Tables  
    * Charts  
    * Slicers  
    * Data Cleaning  
    * IF and Nested IF formulas  
    * Dashboard Design  

---

*Created by [Rohithreddy26]*
