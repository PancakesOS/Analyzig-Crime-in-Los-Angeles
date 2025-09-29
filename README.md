# LAPD Crime Data Analysis Project: Optimizing Resource Allocation 

##  Project Overview

This repository contains the full data analysis and storytelling conducted for the Los Angeles Police Department (LAPD) to identify critical patterns in criminal behavior.

The primary goal of this project is to leverage crime data to provide **actionable insights** for strategically deploying police resources, moving them from times and locations of low activity to areas of highest demonstrated need.

##  Key Questions Addressed

We focused on answering three core questions to guide the LAPD's operational planning:

1.  **Temporal Risk:** Which hour of the day has the highest frequency of reported crimes?
2.  **Geographical Hotspots:** Which area has the largest frequency of night crimes (10 PM – 3:59 AM)?
3.  **Demographic Risk:** Which victim age group faces the highest risk of victimization?

##  Key Findings & Insights

The analysis yielded clear, data-driven conclusions that should inform LAPD strategy:

* **Midday Peak:** Crime activity peaks sharply at **12:00 PM (noon)**, indicating that the highest risk aligns with maximum working and commercial activity.
* **Nighttime Concentration:** The **Central** and **Hollywood** divisions are the undisputed centers for nighttime crime, requiring specialized attention after 10 PM.
* **Target Profile:** The highest at-risk demographic for victimization is the **working-age group (26-44)**, primarily due to increased daily exposure.

## Actionable Recommendations

Based on these findings, we recommend the following strategic adjustments to optimize deployment and preventative efforts:

1.  **Shift Patrol Concentration:** **Heavily increase patrol presence and visibility between 10 AM and 7 PM** city-wide to maximize deterrence during peak exposure times.
2.  **Targeted Night Patrols:** Maintain dedicated units focused specifically on the **Central and Hollywood divisions** from 10 PM onwards to suppress disorder and property crimes in nightlife areas.
3.  **Community Focus:** Launch safety awareness campaigns targeting the highly exposed **working population (age 26-44)** on personal and property safety protocols.

## Repository Contents

| File | Description |
| :--- | :--- |
| `LAPD_Crime_Analysis.ipynb` | The main Jupyter Notebook containing all data cleaning, visualization, calculations, and the complete data storytelling narrative. |
| `README.md` | This overview document. |

## Getting Started

To view the full analysis, simply open the `LAPD_Crime_Analysis.ipynb` file in a Jupyter environment (such as VS Code, Google Colab, or Jupyter Notebook).

### Dependencies

This project requires the following Python libraries:

* `pandas`
* `seaborn`
* `matplotlib`
