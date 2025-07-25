# British Airways Customer Experience Dashboard

## Overview

This project presents an interactive dashboard that visualizes British Airways (BA) passenger review data from 2016-2023. Leveraging approximately 10,000 rows of customer feedback, the dashboard is designed to surface key customer experience (CX) Key Performance Indicators (KPIs). Its minimalist "one-metric-at-a-time" design, driven by a single parameter and five global filters, ensures a low cognitive load for users while allowing them to slice data with ease. The primary goal is to provide data-driven insights into BA's service strengths and areas needing improvement.


## Why This Project is Relevant

In the highly competitive airline industry, understanding and responding to customer feedback is paramount for maintaining brand loyalty and operational excellence. This dashboard offers a direct and efficient way to:

Monitor CX Performance: Track specific customer experience metrics over time and across various dimensions.

Identify Strengths and Weaknesses: Clearly pinpoint areas where BA excels and where it falls short of customer expectations.

Inform Strategic Decisions: Provide actionable insights that can guide operational improvements, staff training, and resource allocation to enhance overall customer satisfaction and perceived value.

Facilitate Data Exploration: Enable stakeholders to independently explore complex review data in a user-friendly format.


## Research Objectives

This dashboard was developed with the following objectives:

To surface critical customer experience KPIs based on passenger review data.

To enable multi-dimensional analysis of customer feedback using various filters (Month, Traveller Type, Seat Type, Aircraft, Continent).

To visually represent monthly trends, geographical distribution, and aircraft-specific performance.

To highlight British Airways' key strengths (e.g., cabin staff, ground service) as perceived by customers.

To identify crucial areas of under-delivery (e.g., in-flight entertainment, perceived value) requiring attention.


## Methodology

This project employs a data visualization approach to transform raw passenger review data into actionable insights through an interactive dashboard.

Data Sources and Features
The dashboard draws upon approximately 10,000 rows of British Airways passenger review data collected between 2016 and 2023. Key features likely include:

Ratings: Scores for various service aspects (e.g., overall, cabin staff, ground service, in-flight entertainment, seat comfort, value for money).

Demographics/Travel Context: Traveller Type, Seat Type.

Flight Details: Aircraft type, Month of travel, Continent (derived from flight origin/destination or user location).

Review Text: (Implied, if qualitative insights are also derived, though not explicitly used in the listed visualizations).


## Data Pre-processing

Typical data pre-processing steps for such a dataset would involve:

Data Extraction & Cleaning: Extracting review data, handling missing values, standardizing categorical entries, and ensuring data consistency.

Feature Engineering: Deriving Continent from location data or adding time-based dimensions (e.g., year, quarter) for trend analysis.

Aggregation: Summarizing review scores to calculate average KPIs for different dimensions.


## Data Processing/Analysis/Methods Used

The core of this project is its interactive dashboard design, which facilitates analysis through:

Parameter Control: A "Pick a Metric" parameter allows users to dynamically select which KPI is displayed across all views, ensuring a "one-metric-at-a-time" focus.

Global Filters: Five interactive filters (Month, Traveller Type, Seat Type, Aircraft, Continent) enable granular data slicing and dicing.

Coordinated Views: The dashboard integrates four distinct but coordinated visualizations:

KPI Cards: Display current or selected values for the chosen metric.

Monthly Trend Line: Illustrates the chosen metric's performance over time.

Chloropleth Map: Visualizes geographical distribution of the chosen metric.

Aircraft Bar-Chart: Shows the chosen metric's performance across different aircraft types.

Exploratory Data Analysis (EDA): The interactive nature of the dashboard implicitly supports EDA, allowing users to discover patterns and anomalies by manipulating filters and parameters.


## Technologies Used

Tableau Public: The primary tool used to create the interactive dashboard, perform data visualization, and enable online sharing.

Microsoft Excel / CSV: Likely used for initial data storage, cleaning, and preparation before importing into Tableau.


## Key Findings

The analysis highlights clear areas of strength and areas needing improvement for British Airways:

Areas of Strength: BA consistently performs well in Cabin Staff service and Ground Service, indicating positive customer perception in these direct human interaction points.

Areas of Under-delivery: There are opportunities for improvement in In-Flight Entertainment offerings and enhancing the Perceived Value for Money among passengers.


## Opportunities for Improvement / Future Work

Tighten Data Quality: Further refine the raw passenger review data for improved accuracy and consistency.

Add Statistical Depth: Incorporate more advanced statistical analyses (e.g., significance testing, correlation analysis) directly into the dashboard or underlying data model.

Sharpen Narrative for Executives: Develop more concise, executive-level summaries and actionable recommendations directly from the dashboard's insights.

Sentiment Analysis: Integrate natural language processing (NLP) to analyze review text for deeper qualitative insights.



## How to View the Dashboard

The interactive dashboard is publicly available on Tableau Public.

You can access and interact with the dashboard here:

[British Airways Review Dashboard on Tableau Public](https://public.tableau.com/app/profile/anindya.swain4442/viz/BritishAirwaysReview_17486499776960/BritishAirwaysReview)

