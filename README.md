# Phase-1-Project
Aviation Accident Risk Analysis - README

1. Project Overview

The project analyzes aviation accident data to determine the lowest-risk aircraft for the company to consider investment in commercial and/or private aviation. The analysis includes data cleaning, exploration, visualization, and business recommendations based on accident trends and its severity.

2. Business Understanding

Problem Statement

The company is expanding into aviation but lacks knowledge of potential risks. 

Objective

To identify aircraft manufacturers with the lowest accident risk, enabling data-driven investment decisions.

Key Questions Addressed

Which aircraft manufacturers have the most and least accidents?

What are the main causes of accidents?

How severe are these accidents (fatalities, injuries)?

Are there any significant trends in aviation accidents over time?

Which aircraft models are the safest for investment?

3. Data Understanding

Dataset Source (["./data/Aviation_Data.csv"])

The dataset is from the National Transportation Safety Board (NTSB), covering civil aviation accidents from 1962 to 2023.

Data includes accident details such as aircraft type, manufacturer, accident severity, injuries, and causes.

Initial Observations

Missing values were present.

Manufacturer names had inconsistencies.

There were duplicate records that needed removal.

4. Data Cleaning & Processing

Steps Taken

Handled missing values

Injury-related missing values were replaced using median.

Standardized manufacturer names.

Removed duplicate records.

Ensured data integrity.

Extracted relevant date information.

Converted accident dates to extract month and year-wise trends.

5. Data Analysis & Visualizations

1. Top Manufacturers by Accident Frequency

Identified top 10 manufacturers with highest and lowest accident rates.

Used bar charts for visual representation.

2. Trend Analysis of Accidents Over Time

A line graph was created to visualize accident trends (1962-2023).

Findings: Accidents peaked in the 1980s and 1990s but declined after 2000.

6. Key Insights & Business Recommendations

1. Safest Manufacturers for Investment

Manufacturers with the lowest accident rates are recommended for investment.

Prioritize aircraft models with low historical accident occurrences.

2. Factors Affecting Accident Severity

Weather conditions and aircraft type significantly impact accident severity.

Investing in aircraft with enhanced safety features is crucial.

3. Business Decision Recommendations

Prioritize modern aircraft models with improved safety measures.

Monitor regulatory safety trends to ensure compliance.

Diversify aircraft investments based on severity trends and accident history.

7. Next Steps

Develop an interactive dashboard to monitor real-time aviation trends (Tableau Dashboard["https://public.tableau.com/views/Book1_17428418660370/SMARTAIRCRAFTINVESTMENTSRiskStrategy?:language=en-US&publish=yes&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link"]).

Expand the dataset to include more international accident records for a global perspective.

8. Final Deliverables

Jupyter Notebook with full analysis and visualizations.

Aviation_Modified CSV dataset with transformed data.

PowerPoint presentation summarizing findings.(["presentation.pdf"])

ReadMe document detailing the analysis and business recommendations.