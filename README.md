# ✈️ Airline Pricing & Market Intelligence Dashboard

An interactive **Power BI project** designed to analyse airline ticket pricing, route performance, booking patterns, and fare differences across airlines, cabin classes, and departure timings.

The project transforms approximately **300,000 flight records** into actionable insights through data preparation, DAX calculations, interactive visualisations, and business-focused analysis.

---

## 📌 Project Overview

Airline ticket prices vary depending on several factors, including route, airline, cabin class, departure timing, flight duration, and booking window.

This project explores these pricing patterns to understand:

- Which routes have the highest average fares?
- How does the booking window influence ticket prices?
- How do Business and Economy fares differ?
- Which departure periods have higher average fares?
- Do longer flights necessarily have higher ticket prices?
- How do flight volumes and average fares vary across routes?

The dashboard provides an interactive view of airline pricing behaviour to support better pricing and market analysis.


## 🎯 Project Objectives

- Analyse airline pricing patterns across different routes.
- Compare average fares across airlines and cabin classes.
- Examine the relationship between flight duration and ticket prices.
- Understand fare variations across departure timings and stop categories.
- Identify high-fare and high-volume routes.
- Present findings through an interactive business intelligence dashboard.


## 🛠️ Tools & Technologies

| Tool | Purpose |
|---|---|
| Power BI | Dashboard development and visualisation |
| Power Query | Data cleaning and transformation |
| DAX | Measures and calculated columns |
| Excel | Dataset exploration and source data |


## 📊 Dataset Overview

The project uses a flight pricing dataset containing approximately **300,153 records** and 12 original columns.

Key attributes include:

- Airline
- Flight
- Source City
- Destination City
- Departure Time
- Arrival Time
- Stops
- Class
- Duration
- Days Left
- Price

The dataset provides information about flight characteristics, booking lead time, and ticket prices.

## 📈 Dashboard Structure

The report consists of two interactive pages.

### 1. Executive Overview

<em>Understanding the overall airline pricing landscape.</em>

Key visualisations:

- Total Flights, Average Price, Minimum Price, Average Duration, and Non-stop Percentage.
- Price trends across booking lead-time categories.
- Average fare comparison by airline.
- Flight distribution by stop category.
- Route-wise average fare matrix.
- Average fare comparison between Business and Economy classes.
- Average price by stop category.

**Purpose:** Provide a high-level overview of airline pricing patterns and the factors influencing fare variation.

### 2. Route & Booking Intelligence

<em>Exploring route-level pricing behaviour and market opportunities.</em>

Key visualisations:

- Top 10 routes by average fare.
- Flight duration versus average fare analysis.
- Average price by departure time.
- Route volume versus average fare analysis.
- Airline-wise Business and Economy fare comparison.
- Fare gap analysis.
- Dedicated business insights section.

**Purpose:** Identify premium routes, understand pricing differences, and explore the relationship between route demand, cabin class, and ticket prices.


## 💡 Key Business Insights

The dashboard highlights several important observations:

**1. Premium Route**  
Chennai → Bangalore emerges as the highest-fare route among the displayed top routes, with an average fare of approximately ₹25K.

**2. Duration vs Fare**  
Flight duration alone does not consistently explain fare differences. Route and cabin class also play important roles.

**3. Route-level Variation**  
High-volume routes show average fares across a broad range, approximately ₹18K–₹24K in the displayed analysis.

**4. Departure Timing**  
Night flights show higher average fares, while Late Night flights are considerably cheaper in the overall comparison.

**5. Cabin Class Premium**  
Business-class fares are substantially higher than Economy fares, indicating a distinct premium pricing segment.


## ⚙️ Data Preparation & Analysis

The project involved:

- Removing unnecessary identifier columns.
- Checking data quality and missing values.
- Cleaning and standardising categorical fields.
- Creating calculated categories for stops, booking lead time, and flight duration.
- Developing DAX measures for flight counts, average fares, minimum and maximum prices, average duration, and non-stop percentage.
- Building interactive visuals to compare pricing patterns across different dimensions.


## 🎨 Dashboard Design

The dashboard uses a dark aviation-inspired theme with blue, purple, and pink accents.

Design considerations include:

- Consistent colour palette across both pages.
- KPI cards for quick performance assessment.
- Interactive slicers for dynamic exploration.
- Clear visual hierarchy and organised layouts.
- Dedicated insights section to connect analysis with business decisions.


## 🚀 Skills Demonstrated

- Data Cleaning & Transformation
- Exploratory Data Analysis
- Power BI Dashboard Development
- DAX Calculations
- Data Visualisation
- Business Intelligence
- KPI Development
- Analytical Storytelling
- Business Insight Generation

---

⭐ If you find this project interesting, feel free to explore the repository and share your feedback!
