# Airbnb Data Analysis & Visualization

An exploratory data analysis (EDA) project analyzing Airbnb listings in New York City. This repository contains a Jupyter Notebook demonstrating data preprocessing, cleaning, exploratory visualization, and analysis to uncover actionable insights into property types, pricing trends, host behaviors, and customer reviews.

## 📂 Repository Structure

*   **[AirBnb_Data_Analysis.ipynb](AirBnb_Data_Analysis.ipynb)**: The main Jupyter Notebook detailing the data importing, cleaning, and exploratory data analysis.
*   **[Basics_of_python_certi.pdf](Basics_of_python_certi.pdf)**: Professional certificate demonstrating foundational Python programming skills.
*   **[Data_visualization_certificate.pdf](Data_visualization_certificate.pdf)**: Professional certificate demonstrating data visualization techniques using Python.

---

## 🎯 Project Overview & Problem Statement

The objective of this analysis is to explore and understand the key factors impacting Airbnb property listings in an urban market, focusing on property type distribution, pricing patterns, host behaviors, and review trends. The goal is to uncover actionable insights that could improve listing performance, maximize occupancy, and enhance guest satisfaction within different neighborhoods.

---

## 🛠️ Data Preprocessing & Cleaning

The Jupyter Notebook executes a thorough data cleaning pipeline:
*   **Duplicate Removal**: Identifies and drops duplicate listing records.
*   **Missing Values Handling**: Drops features with extremely low fill rates (like `house_rules` and `license`).
*   **Data Type Standardization**:
    *   Cleans `price` and `service fee` columns by stripping currency symbols (`$`) and formatting characters (commas), converting them to numeric types.
    *   Mismatched or incorrect data types are cast to their correct format.
*   **Categorical Standardization**: Corrects misspelled entries, such as standardizing `brookln` to `brooklyn`.
*   **Outlier Treatment**: Addresses outliers and invalid ranges in host listing availability (`availability 365`).

---

## 📈 Key Analysis & Visualizations

The analysis addresses several key business questions:
1. **Listing Demographics**: Distribution of different room types and property listings.
2. **Geographical Density**: Finding which neighborhood groups have the highest volume of listings.
3. **Pricing by Location**: Determining which neighborhood groups command the highest average prices.
4. **Pricing Drivers**: Investigating correlation between listing prices and service fees, as well as property construction year.
5. **Host Dynamics**: Identifying the top 10 hosts by listing volume and looking at how host verification affects reviews.
6. **Guest Satisfaction**: Analyzing average review ratings across various room types and neighborhood groups.
7. **Availability vs. Listings**: Checking if hosts with larger listing portfolios maintain higher property availability.

---

## 📌 Key Findings & Conclusions

*   **Diverse Properties**: The dataset exhibits a diverse array of property types, accommodating a wide spectrum of guest preferences and travel requirements.
*   **Premium Neighborhoods**: The highest average listing prices are concentrated within select premium neighborhood groups, signifying localized demand for upscale accommodation options.
*   **Listing Volume Concentrated**: Certain neighborhood groups possess a disproportionately large share of listings, indicating their prominence as preferred travel destinations and reflecting a higher concentration of active hosts.
*   **Construction Year Correlation**: A moderate association is observed between the year of property construction and the listing price, suggesting that newer properties may command higher rates, though the trend is not uniformly consistent.
*   **High Engagement**: A substantial proportion of listings have accumulated over 100 reviews, demonstrating strong guest engagement and frequent booking activity.
*   **Professional Host Impact**: The top ten hosts, as determined by the number of active listings, are likely professional property managers or high-volume hosts, exerting a notable influence on overall market dynamics.
*   **Identity & Trust**: Hosts with verified identities tend to receive more favorable reviews, underscoring the significance of trust and transparency in fostering positive guest-host relationships.
*   **Service Fees & Price**: A discernible, albeit moderate, correlation exists between listing price and service fee, wherein higher-priced listings generally incur proportionally greater service charges.
*   **Review Ratings**: Average review ratings vary across neighborhoods and room types, suggesting that both geographic location and property characteristics influence guest satisfaction and overall experience.
*   **Portfolio Availability**: Hosts managing a larger portfolio of listings typically exhibit higher availability rates, likely attributable to professional management practices and optimized booking strategies.

---

## 🎓 Certificates & Credentials

This repository includes professional certificates showcasing expertise in Python programming and data visualization:
*   📜 **[Basics of Python Certificate](Basics_of_python_certi.pdf)**
*   📊 **[Data Visualization Certificate](Data_visualization_certificate.pdf)**
