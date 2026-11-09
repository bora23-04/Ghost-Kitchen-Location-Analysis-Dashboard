# Brazilian Restaurant Market Analysis | Power BI Dashboard

An interactive Power BI dashboard designed to analyze Brazil's restaurant market, understand competition across cities, and identify potential opportunities for ghost kitchen expansion.

## Project Overview

The food industry is highly competitive, and choosing the right location is an important factor in the success of a restaurant or ghost kitchen.

This project uses Brazilian restaurant data to explore market activity, customer ratings, review volumes, and competition across different locations.

Using Microsoft Power BI, I developed an interactive dashboard with custom Competition Score and Opportunity Score measures to help compare restaurant markets and identify locations with potential business opportunities.

## Business Problem

Expanding into a new market without understanding local competition and customer demand can lead to poor business decisions.

The objective of this project is to answer questions such as:

- Which cities have higher restaurant activity?
- Where is restaurant competition relatively high or low?
- Which locations show promising market opportunities?
- How do customer ratings and review volumes vary across cities?
- Which markets could be considered for potential ghost kitchen expansion?

## Project Objectives

1. Analyze restaurant distribution across Brazilian cities.
2. Evaluate customer ratings and review activity.
3. Compare competition levels across locations.
4. Develop custom metrics to evaluate market opportunities.
5. Present findings through an interactive Power BI dashboard.

## Dataset Description

The project uses a Brazilian restaurant dataset containing business-level information.

The dataset includes fields such as:

| Column | Description |
|---|---|
| business_id | Unique restaurant/business identifier |
| name | Restaurant name |
| address | Restaurant address |
| city | City where the restaurant operates |
| state | Brazilian state or region |
| postal_code | Postal code |
| latitude | Geographic latitude |
| longitude | Geographic longitude |
| stars | Average customer rating |
| review_count | Number of customer reviews |
| is_open | Business operating status |
| attributes | Additional business characteristics |
| categories | Restaurant/business categories |
| hours | Business operating hours |
| total_reviews | Aggregated review count, where available |

*Note: The exact dataset source, original field names and geographical coverage should be documented according to the dataset used in the project.*

## Data Preparation

Data preparation and transformation were performed using **Power Query in Power BI**.

The preparation process included:

- Reviewing the dataset structure and column types.
- Checking missing and inconsistent values.
- Cleaning and preparing relevant business information.
- Filtering records to focus on food-related businesses.
- Preparing city, rating and review fields for analysis.
- Organizing the data for dashboard calculations and visualizations.

## Data Modelling and DAX

DAX measures were created to support the analysis and calculate the project's key performance indicators.

### 1. Competition Score

A custom measure designed to evaluate the level of restaurant competition across locations.

It helps compare markets based on restaurant activity and other relevant business indicators.

### 2. Opportunity Score

A custom measure designed to highlight locations that may offer promising opportunities based on the project's selected demand and competition indicators.

These scores help make comparisons between cities easier.

*The scores are analytical indicators developed for this project. They should not be interpreted as guaranteed measures of profitability or business success.*

## Dashboard Features

### 1. Geographic Map Visualization

Displays restaurant locations and helps identify areas with concentrated restaurant activity.

### 2. City-Level Opportunity Ranking

Compares cities using the calculated Opportunity Score to highlight potentially attractive markets.

### 3. Competition Analysis

Helps compare competition levels across different locations.

### 4. Customer Rating Analysis

Explores restaurant ratings and review activity to understand differences in customer feedback.

### 5. Interactive Filters

The dashboard includes slicers for:

- City
- Restaurant rating
- Review count
- Restaurant name

### 6. Tooltips

Provides additional information about restaurants and locations when users interact with dashboard visuals.

## Key Business Insights

The analysis helps explore patterns such as:

- Cities with substantial review activity may indicate stronger customer engagement.
- High restaurant concentration can indicate a competitive market.
- Markets with relatively manageable competition may deserve further investigation.
- Higher restaurant ratings do not necessarily mean lower competition.
- Mid-sized cities may offer interesting opportunities compared with highly saturated markets.

These are analytical observations to investigate further, not universal conclusions about every Brazilian city.

## Tools and Technologies

| Tool | Purpose |
|---|---|
| Microsoft Power BI | Dashboard development and visualization |
| Power Query | Data cleaning and transformation |
| DAX | Calculated measures and analytical metrics |
| Data Modelling | Organizing data for analysis |

## Project Workflow

**Source Data → Power Query → Data Preparation → Data Modelling → DAX Measures → Interactive Power BI Dashboard → Business Insights**

## Dashboard Preview

<img width="1159" height="653" alt="image" src="https://github.com/user-attachments/assets/9c0818c7-5665-4b38-b6c1-f09b426eac93" />

### Dashboard Overview

<img width="1145" height="651" alt="image" src="https://github.com/user-attachments/assets/70bcee2d-fcec-4897-9b44-aaccb548d450" />


## Repository Contents

```text
Ghost-Kitchen-Location-Analysis-Dashboard/
│
├── README.md
│
├── dataset/
│   └── README.md
│
├── dashboard/
│   └── README.md
│
├── screenshots/
│   ├── dashboard-overview.png
│   ├── competition-analysis.png
│   └── opportunity-analysis.png
│
└── documentation/
    └── project-methodology.md
```

The dataset and Power BI file may be provided through external download links, depending on file size and sharing permissions.

## Project Files

**GitHub Repository:** This repository contains the project documentation, methodology and supporting resources.

**Power BI Dashboard:** https://drive.google.com/drive/folders/14Dyf0elsEbQuD4DDvQaKQObxDatNne0U?usp=sharing

**Portfolio:** https://anurawal-portfolio.lovable.app

## How to Explore the Dashboard

1. Download the Power BI `.pbix` file.
2. Open it using Power BI Desktop.
3. Explore the available city, rating and review filters.
4. Compare competition and opportunity scores.
5. Use the map and other visuals to explore market patterns.

## Business Value

This project demonstrates how raw restaurant data can be transformed into an interactive business intelligence solution.

It provides a structured way to compare locations, explore competition, understand customer feedback and support early-stage market research for potential ghost kitchen expansion.

---

**Project Focus:** Brazilian Restaurant Market Analysis

**Primary Tool:** Microsoft Power BI

**Skills Demonstrated:** Power Query, DAX, Data Cleaning, Data Modelling, Exploratory Data Analysis, Data Visualization and Business Intelligence.

### How to Use
1. Download the .pbix file
2. Open in Power BI Desktop
3. Use slicers to filter cities, ratings, and review counts
4. Analyze hot zones and opportunity rankings





