# Washington State Certified Public Accountants Dataset

## Overview
This dataset contains records of Certified Public Accountants (CPAs) in Washington State, including their license details, geographic information, and status. It provides insights into active and expired licenses, regional distributions, and regulatory compliance.

## Code
This repository contains two Malloy code files:

    wacpa.malloy, sources all the data tables for the data analysis portion of this repository.
    cpa.malloynb, performs the analysis piece of the data provided by the Washington State Data Portal.

#### Malloy is an open source data language, and a decent alternative to pandas, ggplot, and SQL!

#### How see the analysis yourself

## Are you logged into github? Just press the period key right now. Then do the following:
1. Step 1 - Press allow 	
2. Step 2 - Click the Extension Blocks, search for Malloy, install 	
3. Step 3 - Click Trust 	
4. Step 4 - Click a .malloynb file 	
5. Step 5 - Press Run 	

## Dataset Information
- **Source:** Washington State CPA Licensing Board
- **Date of Extraction:** February 27, 2025
- **File Format:** CSV
- **Total Records:** 47,922
- **Columns:**

  | Column Name          | Description |
  |----------------------|-------------|
  | First Name          | First name of the CPA |
  | Middle Name         | Middle name of the CPA (if available) |
  | Last Name           | Last name of the CPA |
  | Suffix              | Suffix (e.g., Jr., Sr.) |
  | Preferred Name      | Preferred name, if provided |
  | City               | City of residence or practice |
  | State              | U.S. state of residence/practice |
  | Country            | Country of residence/practice |
  | License Number     | Unique CPA license identifier |
  | Original Issue Date | Date the CPA license was first issued |
  | Expiration Date    | Date the license is set to expire |
  | Status            | Current license status (Active, Lapsed, Expired) |
  | Last Updated      | Last recorded update (empty in this dataset) |
  | Board Order       | Disciplinary board order (if applicable) |

## Potential Use Cases
- **Regulatory Compliance**: Identifying active and expired licenses.
- **Geographic Analysis**: Understanding CPA distribution across regions.
- **License Trends**: Analyzing issuance and expiration trends over time.
- **Demographic Insights**: Common names and regional concentrations.

## Questions for Analysis
1. What percentage of CPAs have an active license?
2. How many CPAs have licenses that have expired or lapsed?
3. What is the distribution of CPAs across different states and countries?

<img src="./Images/percent.png" style="width: 300px">

4. Which cities have the highest concentration of CPAs?
5. What is the average duration between the license issue and expiration dates?
6. How many CPAs have disciplinary board orders?
7. What is the average duration of a CPA license compared to the average duration of a suspended or revoked license.

<img src="./Images/revoked.png" style="max-width:50%">

## Usage Instructions
- Load the dataset using a CSV-compatible tool (e.g., Excel, Pandas in Python).
- Perform filtering and grouping to analyze license trends.
- Use visualization tools like Matplotlib, Seaborn, or Tableau for graphical insights.

## License & Disclaimer
This dataset is for informational purposes only. It may not reflect real-time updates and should not be used for official verification. Please refer to the official Washington State CPA Licensing Board for the most up-to-date information. The files provided directly via data.wa.gov are, as government documents, now in the public domain. All other files have been generated by Darren Owsley for Gonzaga University Graduate School of Business as part of the MSBA-622-01 Data Science for Business (Spring 2025) course. This repository’s code is available under the MIT License terms.
