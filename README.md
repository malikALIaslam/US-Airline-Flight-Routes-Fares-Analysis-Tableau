#  US Airline Flight Routes & Fares Analysis | Tableau Project

## 📌 Project Overview

This project is an end-to-end data analysis and visualization project built using Tableau and Microsoft Excel.

The project analyzes US airline flight routes and fare data from 1993 to 2024. The objective is to explore passenger volume, airline performance, fare trends, flight routes, distance patterns, and affordable airline options.

The raw dataset was analyzed and transformed into an interactive Tableau dashboard using calculated fields, KPIs, filters, and data visualizations.

---

# 🎯 Project Objectives

The main objectives of this project are:

* Analyze airline passenger volume
* Compare airline fare patterns
* Identify expensive flight routes
* Identify top airlines by passenger volume
* Analyze flight routes
* Explore the relationship between distance and fare
* Identify airlines offering lower fares
* Analyze passenger trends by quarter
* Build an interactive Tableau dashboard

---

# 📊 Dataset Information

| Feature            | Details                            |
| ------------------ | ---------------------------------- |
| Dataset            | US Airline Flight Routes and Fares |
| Time Period        | 1993–2024                          |
| Total Records      | 245,955                            |
| Total Columns      | 23                                 |
| Data Format        | Excel                              |
| Visualization Tool | Tableau                            |

---

# 🛠️ Tools & Technologies

The following tools were used in this project:

* Tableau
* Microsoft Excel
* Data Analysis
* Data Cleaning
* Data Visualization
* Calculated Fields
* Interactive Dashboard Design

---

# 📂 Project Workflow

The project was completed in the following phases:

## Phase 1: Data Connection & Data Understanding

* Connected the Excel dataset to Tableau
* Examined the dataset structure
* Checked data types
* Checked important columns
* Identified null values
* Reviewed the dataset before analysis

---

# 🧹 Phase 2: Data Preparation & Calculated Fields

Several calculated fields were created to improve the analysis.

## 1. Route

A route was created by combining the origin and destination cities.

```text
[city1] + " → " + [city2]
```

---

## 2. Fare Category

Flight fares were divided into categories.

```text
IF [fare] < 100 THEN "Low Fare"

ELSEIF [fare] < 200 THEN "Medium Fare"

ELSEIF [fare] < 300 THEN "High Fare"

ELSE "Very High Fare"

END
```

---

## 3. Distance Category

Flight distances were divided into categories.

```text
IF [nsmiles] < 500 THEN "Short Distance"

ELSEIF [nsmiles] < 1000 THEN "Medium Distance"

ELSEIF [nsmiles] < 2000 THEN "Long Distance"

ELSE "Very Long Distance"

END
```

---

## 4. Total Routes

```text
COUNTD([Route])
```

---

## 5. Total Airlines

```text
COUNTD([carrier_lg])
```

---

## 6. Average Fare

```text
AVG([fare])
```

---

## 7. Total Passengers

```text
SUM([passengers])
```

---

## 8. Average Distance

```text
AVG([nsmiles])
```

---

# 📈 Phase 3: Data Analysis & Visualizations

The following visualizations were created in Tableau.

---

## 1️⃣ Passenger Volume by Quarter

Analyzes passenger volume across different quarters.

### Analysis:

* Quarter 1
* Quarter 2
* Quarter 3
* Quarter 4

This visualization helps identify seasonal passenger patterns.

---

## 2️⃣ Average Fare by Airline

Compares the average fares of different airlines.

This helps analyze airline pricing patterns and fare differences.

---

## 3️⃣ Top 10 Most Expensive Routes

Identifies the flight routes with the highest average fares.

This visualization helps understand expensive travel routes.

---

## 4️⃣ Top Airlines by Passenger Volume

Identifies airlines with the highest passenger volume.

This helps compare airline performance and customer demand.

---

## 5️⃣ Fare vs Distance

Analyzes the relationship between flight distance and average fare.

This visualization helps understand whether longer flights generally have higher fares.

---

## 6️⃣ Airlines Offering Lowest Fares

Compares airlines based on affordable fare options.

This helps identify airlines offering lower-cost travel options.

---

# 📊 Dashboard KPIs

The final dashboard includes the following Key Performance Indicators.

| KPI              |      Value |
| ---------------- | ---------: |
| Total Passengers | 73,657,815 |
| Average Fare     |      219.0 |
| Total Routes     |      1,266 |
| Average Distance |      1,190 |
| Total Airlines   |         67 |

---

# 🎛️ Phase 4: Interactive Dashboard

An interactive Tableau dashboard was created to combine all important insights in one place.

## Dashboard Features

* Interactive KPI Cards
* Quarter Filter
* Average Fare Filter
* Passenger Analysis
* Airline Analysis
* Route Analysis
* Fare Analysis
* Distance Analysis
* Interactive Charts

---

# 📊 Dashboard Visualizations

The final dashboard includes:

* Passenger Volume by Quarter
* Average Fare by Airline
* Top 10 Expensive Routes
* Top Airlines by Passenger Volume
* Fare vs Distance
* Airlines Offering Lowest Fares

---

# 📷 Dashboard Preview

![US Airline Tableau Dashboard](Dashboard/US_Airline_Tableau_Dashboard.png)

---

# 🔍 Key Analysis Areas

## 👥 Passenger Analysis

Analyzed airline passenger volume to understand travel demand and airline performance.

---

## 💰 Fare Analysis

Compared average fares across airlines and flight routes to identify pricing patterns.

---

## ✈️ Route Analysis

Analyzed different flight routes to identify expensive and important routes.

---

## 🏢 Airline Analysis

Compared airlines based on passenger volume and fare performance.

---

## 📏 Distance Analysis

Analyzed the relationship between flight distance and average fare.

---

# 💡 Key Insights

The dashboard helps identify:

* Passenger demand patterns by quarter
* Airlines with high passenger volume
* Differences in airline fare pricing
* Expensive flight routes
* Affordable airline options
* The relationship between distance and fare
* Overall airline route performance

---

# 🎨 Dashboard Features

The dashboard was designed with:

* Clean layout
* KPI cards
* Interactive filters
* Bar charts
* Scatter plot
* Data-driven analysis
* Professional dashboard design

---

# 📁 Project Structure

```text
US-Airline-Flight-Routes-Fares-Analysis-Tableau
│
├── Data
│   └── US_Airline_Flight_Routes_and_Fares.xlsx
│
├── Dashboard
│   └── US_Airline_Tableau_Dashboard.png
│
├── Tableau
│   └── US_Airline_Flight_Routes_Analysis.twbx
│
├── README.md
│
└── LICENSE
```

---

# 🚀 Project Process

```text
Raw Excel Dataset
        ↓
Data Understanding
        ↓
Data Type Checking
        ↓
Data Preparation
        ↓
Calculated Fields
        ↓
Data Analysis
        ↓
Charts & Visualizations
        ↓
KPI Creation
        ↓
Interactive Dashboard
        ↓
Insights & Conclusions
```

---

# 📌 Conclusion

This project demonstrates an end-to-end Tableau data analysis workflow using a large US airline dataset.

The project transforms raw airline data into meaningful insights through calculated fields, KPIs, interactive filters, and professional visualizations.

The final dashboard provides insights into passenger volume, airline performance, fare patterns, expensive routes, affordable airlines, and the relationship between flight distance and fare.

---

# 🎯 Skills Demonstrated

* Data Analysis
* Data Visualization
* Tableau
* Microsoft Excel
* Dashboard Development
* Calculated Fields
* KPI Development
* Interactive Filters
* Business Insights
* Data Storytelling

---

# 👨‍💻 Author

**Muhammad Ali**

Aspiring Data Analyst

### Skills

Python | SQL | Excel | Power BI | Tableau | Data Analysis | Data Visualization | Machine Learning

⭐ If you found this project useful, feel free to star the repository!
