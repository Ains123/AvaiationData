# AvaiationData
Phase 1 Project: Aviation Accident Risk Analysis
README.md
Project Overview

This project analyzes historical aviation accident data to support safer aircraft acquisition and operational decision-making. By identifying accident trends, high-risk phases of flight, and lower-risk aircraft characteristics, the analysis provides actionable insights for aviation company stakeholders.

The goal is to help decision-makers reduce safety risks, financial losses, and reputational damage by using data-driven evidence rather than intuition alone.

Business Problem

Aviation companies face significant risk when acquiring and operating aircraft. Accidents can lead to loss of life, high financial costs, and long-term reputational harm.

Stakeholders:

Aviation company executives

Fleet and operations managers

Safety and risk management teams

Objective: Use historical accident data to identify patterns that inform safer aircraft acquisition and operational strategies.

Data Understanding

Data Source:

Global aviation accident records (1962–2023)

Key Features Used:

Aircraft type and model

Year of manufacture / accident year

Phase of flight

Fatalities and injuries

Why This Data is Suitable:

Covers a long historical period

Contains safety-critical variables

Directly relevant to aircraft risk assessment

Limitations:

Missing values in some records

Potential reporting bias across regions and years

Older records may be less detailed

Data Preparation

The dataset was cleaned and prepared to ensure accurate and reproducible analysis.

Preparation steps included:

Removing duplicate records

Handling missing values (numeric NaNs filled with 0 where appropriate)

Standardizing date formats

Cleaning and validating key columns used in analysis

All preparation steps are documented in the notebook and can be reproduced by running the code from top to bottom.

Data Analysis

The analysis focused on answering three key questions:

Which aircraft characteristics are associated with lower accident risk?

How does aircraft age relate to accident frequency?

Which phases of flight present the highest safety risk?

From these analyses, three core findings were produced and used to support business recommendations.

Key Findings

Certain aircraft models show consistently lower accident rates

Older aircraft are associated with higher accident risk

Takeoff and landing phases account for a disproportionate number of accidents

Recommendations

Prioritize acquisition of aircraft models with historically lower accident rates

Avoid acquiring significantly older aircraft where possible

Focus training, monitoring, and maintenance on high-risk phases of flight

These recommendations directly address the business problem of minimizing operational and acquisition risk.

Repository Structure
project-root/
│
├── data/
│   ├── raw/            # Original datasets
│   └── processed/      # Cleaned datasets
│
├── notebooks/          # Analysis notebooks
│
├── presentation/       # Slides and visuals
│
├── README.md
└── .gitignore
How to Run the Project

Clone the repository

Install required Python packages

Run the notebook from top to bottom

View cleaned data and visual outputs
