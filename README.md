# Ontario-Builds-Construction-Analytics
A Power BI construction analytics project using Ontario's public infrastructure dataset to explore project status, categories, estimated budgets, funding indicators, regional distribution and target completion information.

# Ontario Builds: Construction Project Analytics Using Power BI

## Project Overview

This project analyses public infrastructure project information from the Government of Ontario, Canada, using Microsoft Power BI Desktop.

The objective is to transform raw construction project data into an informative business intelligence report that helps users explore project categories, status, estimated budgets, funding indicators, geographical distribution and target completion information.

## Dataset Source

**Dataset:** Ontario Builds – Key Infrastructure Projects

**Publisher:** Government of Ontario, Canada

**Official Source:**  
https://open.canada.ca/data/en/dataset/aefd72d3-f67c-44ed-b017-b74e7ecd9258

**Format:** CSV

The dataset contains project-level information such as project name, category, supporting ministry, community, status, estimated budget, funding indicators, region and geographical coordinates.

## Tools and Technologies

- Microsoft Power BI Desktop
- Power Query
- Data Analysis Expressions (DAX)
- CSV

## Data Preparation

Power Query was used to inspect, clean and transform the dataset.

Main activities included:

- Checking column quality, distribution and profiling.
- Reviewing missing values and unusual category entries.
- Correcting invalid latitude and longitude errors.
- Assigning suitable data types.
- Creating a standardised project status group.
- Extracting target completion year, month and day where possible.

## Dashboard Structure

The Power BI report contains two pages:

### Page 1 – Project Overview

Contains two cards and eight charts covering:

- Total construction projects.
- Total estimated project budget.
- Projects by status.
- Projects by construction category.
- Project status distribution.
- Funding source indicators.
- Projects by region.
- Estimated budget by construction category.
- Projects by target completion year.
- Projects by target completion month.

### Page 2 – Filters

Contains slicers for:

- Project Category.
- Project Status.

These slicers provide filtering options for exploring the dashboard.

## Key Findings and Evaluation

The report provides descriptive analysis of project distribution, status, estimated budgets, funding indicators and target completion information.

The evaluation also considers data quality, missing information, dashboard effectiveness and data model reliability.

## Limitations

- Some source columns contain missing values.
- Target completion dates have mixed formats.
- Estimated budgets do not represent actual expenditure.
- Funding fields are indicators and do not provide individual funding amounts.
- The map visual was not included because of an issue with map functionality in the current Power BI environment.
- Predictive analytics is discussed as a future improvement. No trained predictive model is included.

## Future Improvements

Possible improvements include:

- Integrating actual expenditure data.
- Adding historical project schedule updates.
- Developing project delay prediction models.
- Analysing labour and material requirements.
- Improving geographical analysis.

## Repository Structure

```text
Ontario-Builds-Construction-Analytics/
│
├── data/
├── power_bi/
├── screenshots/
├── report/
└── README.md
```

Each folder contains its own README file explaining its contents.

## How to Use This Project

1. Download or clone this repository.
2. Open the `power_bi` folder.
3. Open `Ontario_Builds_Dashboard.pbix` using Power BI Desktop.
4. If Power BI requests the source file location, reconnect it to the CSV inside the `data` folder.
5. Explore the report pages and use the slicers to filter project information.

## Project Outcome

This project demonstrates practical experience in public data sourcing, data preparation, Power Query transformations, DAX calculations and business intelligence reporting for construction analytics.

**Project Type:** Virtual Construction Business Intelligence Internship

**Analysis Type:** Descriptive Data Analysis and Dashboard Evaluation
