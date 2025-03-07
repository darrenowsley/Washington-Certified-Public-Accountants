# Washington State Certified Public Accountants Dataset

## Overview
This dataset comprises records of Certified Public Accountants (CPAs) in Washington State, detailing their licensing information, personal identifiers, and geographic locations. It contains 47,922 entries, each representing an individual CPA with attributes such as first name, last name, middle name, suffix, preferred name, city, state, and country. Additionally, the dataset includes license-specific details such as license number, original issue date, expiration date, and status. Some records also contain board orders and other administrative annotations.

<table>
<tr>
<td><img src="./Images/summary.png" style="width: 400px"></td>
<td><img src="./Images/average.png" style="width: 400px"></td>
</tr>
<table>

The dataset presents a comprehensive view of CPA licensing trends across different regions, allowing for insights into license validity, geographical distribution, and professional status. While most records contain essential details, some fields have missing values, particularly in the middle name, state, and preferred name columns. This data set includes CPA licensed data from 1903 to 2025.

<img src="./Images/trend.png" style="width: 400px">

## Motivation Statement

The motivation behind analyzing this dataset is to gain insights into CPA licensing patterns, track active and lapsed licenses, and understand the geographical distribution of licensed professionals. By examining trends in licensing dates and statuses, stakeholders can identify regulatory compliance patterns, renewal frequencies, and potential areas of professional shortages or surpluses.

This dataset can serve as a valuable resource for regulatory boards, professional associations, and researchers interested in workforce analytics, credential verification, and the broader impact of licensing regulations on the accounting profession. Understanding these patterns can help improve policy decisions, streamline licensing processes, and ensure better oversight of CPA professionals.

## Code
This repository contains two Malloy code files:

    wacpa.malloy, sources all the data tables for the data analysis portion of this repository.
    cpa.malloynb, performs the analysis piece of the data provided by the Washington State Data Portal.

# How to Open a Shared GitHub File and Run Malloy Code
To explore the data and run the analyses:

Click on the ((https://github.com/darrenowsley/Washington-Certified-Public-Accountants.git) provided to access the shared repository or file. 

Once on Github, click Shift + period this will load the web editor. Then install the malloy extension. See images below for reference:
| **Step**   | **Image Preview** |
|--------|-----------|
| `Step 1 - Press allow` | <img src="./Images/step1.png" width="50%"> |
| `Step 2 - Click the Blocks, search for Malloy, install` | <img src="./Images/step2.png" width="50%"> |
| `Step 3 - Click Trust` | <img src="./Images/step3.png" width="50%"> |
| `Step 4 - Click a .malloynb file` | <img src="./Images/step4.png" width="50%"> |
| `Step 5 - Press Run` | <img src="./Images/step5.png" width="50%"> |

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
<img src="./Images/percent.png" style="width: 400px">

2. How many CPAs have licenses that have expired or lapsed?
3. What is the distribution of CPAs across different states and countries?
<img src="./Images/percent.png" style="width: 400px">

4. Which cities have the highest concentration of CPAs?
5. What is the average duration between the license issue and expiration dates?
6. How many CPAs have disciplinary board orders?
7. What is the average duration of a CPA license compared to the average duration of a suspended or revoked license.

<img src="./Images/revoked.png" style="width: 400px">

## License & Disclaimer
This dataset is for informational purposes only. It may not reflect real-time updates and should not be used for official verification. Please refer to the official Washington State CPA Licensing Board for the most up-to-date information. The files provided directly via data.wa.gov are, as government documents, now in the public domain. All other files have been generated by Darren Owsley for Gonzaga University Graduate School of Business as part of the MSBA-622-01 Data Science for Business (Spring 2025) course. This repository’s code is available under the MIT License terms.
