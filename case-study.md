![Bellabeat Logo](https://bellabeat.com/wp-content/uploads/2023/09/Bellabeat-logo.jpg)

## Introduction

Bellabeat is a high-tech company that manufactures health-focused smart products designed for women. Founded by Urška Sršen and Sando Mur, Bellabeat has quickly positioned itself as a tech-driven wellness company. The company's product line includes the Bellabeat app, Leaf wellness tracker, Time watch, and Spring water bottle. These products collect data on activity, sleep, stress, and reproductive health, empowering women with knowledge about their own health and habits. Bellabeat has expanded rapidly since its inception in 2013 and has invested in a variety of marketing channels, including digital marketing and traditional advertising.

## Ask

Bellabeat aims to enhance its market position by leveraging data analysis to understand smart device usage trends. The primary objective of this analysis is to discover actionable insights that can inform and optimize the company's marketing strategy. By examining data from non-Bellabeat smart devices, the analysis will focus on identifying trends in consumer behavior. The findings will help Bellabeat tailor its marketing efforts, improve product offerings, and ultimately drive business growth.

### Deliverables
- A clear summary of the business task
- A description of all data sources used
- Documentation of any cleaning or manipulation of data
- A summary of the analysis
- Supporting visualizations and key findings
- High-level recommendations based on the analysis

## Prepare

### Data Collection

1. **Source Data:**
   - Data was collected from two pivot tables. The first pivot table provides average total steps, and the second pivot table provides average total minutes asleep.

2. **Data Extraction:**
   - The IDs of interest were identified and extracted from both pivot tables. These IDs were selected based on specific criteria relevant to the analysis.

### Data Cleaning

1. **Handling Missing Data:**
   - Rows with missing information were removed to ensure the accuracy of the analysis. This was done by filtering out rows where critical columns were blank.

2. **Data Transformation:**
   - **Formatting Dates and Times:** The date and time formats were standardized to ensure consistency across datasets. This involved converting date and time data into a format compatible with analysis tools.
   - **Combining Data:** Data from the two pivot tables was merged based on common IDs. This integration involved aligning the datasets and consolidating information to provide a comprehensive view.

### Data Integration

1. **Merging Datasets:**
   - The cleaned datasets were merged into a single dataset using the common ID column. This was achieved using VLOOKUP to align corresponding values from each table into a unified format.

2. **Verification:**
   - After merging, the integrity of the combined data was verified to ensure that all relevant IDs were included and that the data was accurately aligned.

### Data Validation

1. **Cross-Checking:**
   - Random samples of the merged data were cross-checked against the original datasets to confirm accuracy and completeness.

2. **Consistency Checks:**
   - Ensured that there were no discrepancies or inconsistencies in the merged data by reviewing summary statistics and comparing them with expected values.

By following these steps, the dataset was prepared for analysis, ensuring that the data was clean, consistent, and ready for further examination.

