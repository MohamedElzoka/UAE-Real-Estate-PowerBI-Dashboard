# UAE Real Estate Market Analysis Dashboard

## Overview

This project presents an end-to-end Business Intelligence solution developed in Power BI to analyze the UAE real estate rental market. The dashboard leverages more than 74,000 property listings to provide actionable insights into rental pricing, furnishing impact, geographic distribution, property characteristics, and market performance across major UAE cities.

The objective of this project is to transform raw real estate data into an interactive analytical platform that supports data-driven decision-making for investors, property managers, and business stakeholders.

---

## Business Objectives

* Analyze rental market performance across UAE cities and neighborhoods.
* Identify high-value and affordable rental markets.
* Evaluate the impact of furnishing status on rental prices.
* Assess market velocity using listing exposure and listing age.
* Compare rental trends across property types and bedroom counts.
* Support investment decisions through location-based insights.

---

## Dataset Information

The dataset contains more than 74,000 UAE property listings and includes:

* City
* Location
* Property Type
* Bedrooms
* Bathrooms
* Property Area (SqFt)
* Annual Rent
* Rent Per SqFt
* Furnishing Status
* Listing Age (Days on Market)
* Geographic Coordinates

---

## Dashboard Architecture

### Executive Summary

Provides a high-level overview of the UAE rental market through key performance indicators and summary visualizations.

Key Metrics:

* Total Listings
* Average Annual Rent
* Median Rent
* Furnished Property Percentage
* Median Days on Market

Visuals:

* Rental Distribution by Category
* Property Distribution by City
* Average Rent by Property Type

---

### Geographic Analysis

Analyzes regional rental market performance across UAE cities and neighborhoods.

Key Features:

* Interactive Geographic Map
* Location-Based Rental Analysis
* Neighborhood-Level Market Comparison
* Geographic Rental Distribution

---

### Property & Pricing Deep Dive

Explores rental pricing behavior across different property characteristics.

Key Features:

* Rent by Bedroom Count
* Furnished vs Unfurnished Analysis
* Rental Price Distribution
* City and Property Type Comparison Matrix

---

### Market Velocity & Opportunities

Evaluates market demand and identifies potential investment opportunities.

Key Features:

* Days on Market Analysis
* Furnished Rental Premium Analysis
* Slow-Moving Property Identification
* Investment Opportunity Scorecard

---

## Key Insights

* Dubai records the highest average rental prices across the UAE market.
* Furnished properties consistently command a rental premium compared to unfurnished units.
* Rental demand varies significantly across cities and neighborhoods.
* Property type and bedroom count have a strong influence on rental pricing.
* Several locations exhibit longer market exposure periods, highlighting potential pricing optimization opportunities.

---

## Technical Implementation

### Data Modeling

* Star-schema-inspired data structure
* Relationship management between summary and transaction tables
* Optimized analytical model for reporting performance

### DAX Measures

Key calculations include:

* Total Listings
* Average Annual Rent
* Median Rent
* Furnished Percentage
* Average Rent Per SqFt
* Furnished Premium Analysis
* Median Days on Market

### Power BI Features

* Interactive Slicers
* Dynamic Filtering
* Geographic Mapping
* KPI Cards
* Matrix Analysis
* Drill-Down Exploration
* Cross-Filtering Visualizations

---

## Tools & Technologies

* Power BI
* DAX
* Data Modeling
* Data Visualization
* Business Intelligence
* Geographic Analytics

---

## Dashboard Preview

### Executive Summary

![Executive Summary](screenshots/executive_summary.PNG)

### Geographic Analysis

![Geographic Analysis](screenshots/geographic_analysis.PNG)

### Property & Pricing Deep Dive

![Property & Pricing Deep Dive](screenshots/property_pricing.PNG)

### Market Velocity & Opportunities

![Market Velocity & Opportunities](screenshots/market_velocity.PNG)

---

## Project Structure

```text
UAE-Real-Estate-PowerBI-Dashboard
│
├── Dashboard.pbix
├── README.md
├── screenshots
│   ├── executive_summary.PNG
│   ├── geographic_analysis.PNG
│   ├── property_pricing.PNG
│   └── market_velocity.PNG
│
├── dataset
│   └── uae_properties_clean.csv
│
└── assets
    └── dashboard_overview.png
```

---

## Author

Mohamed Ayman Elzoka

Machine Learning Engineer | Data Analyst | Business Intelligence Enthusiast

GitHub: https://github.com/MohamedElzoka
