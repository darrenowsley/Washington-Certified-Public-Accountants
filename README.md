# Washington State Certified Public Accountants Dataset

## Overview
This dataset contains records of Certified Public Accountants (CPAs) in Washington State, including their license details, geographic information, and status. It provides insights into active and expired licenses, regional distributions, and regulatory compliance.

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

## Use Cases
- **Regulatory Compliance**: Identifying active and expired licenses.
- **Geographic Analysis**: Understanding CPA distribution across regions.
- **License Trends**: Analyzing issuance and expiration trends over time.
- **Demographic Insights**: Common names and regional concentrations.

## Questions for Analysis
1. What percentage of CPAs have an active license?
2. How many CPAs have licenses that have expired or lapsed?
3. What is the distribution of CPAs across different states and countries?
4. Which cities have the highest concentration of CPAs?
5. What is the average duration between the license issue and expiration dates?
6. How many CPAs have disciplinary board orders?

## Usage Instructions
- Load the dataset using a CSV-compatible tool (e.g., Excel, Pandas in Python).
- Perform filtering and grouping to analyze license trends.
- Use visualization tools like Matplotlib, Seaborn, or Tableau for graphical insights.

## License & Disclaimer
This dataset is for informational purposes only. It may not reflect real-time updates and should not be used for official verification. Please refer to the official Washington State CPA Licensing Board for the most up-to-date information.
