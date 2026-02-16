# My Excel Projects
This folder contains spreadsheets, pivot tables, and data cleaning examples using MS Excel.

## Project: Student Performance Data Cleaning

### Scenario
As a data analyst for a school district in Portugal, I cleaned a dataset containing student grades and background information to ensure accurate analysis of factors affecting academic performance.

### Data Cleaning Steps Performed:
1. **Sorting & Inspection:** Sorted data by `school` and `age` to identify outliers. Discovered students aged 20-22 in a high school dataset.
2. **Filtering:** Applied filters to remove 9 rows of incorrect data (students over 19 years old) based on business logic provided by the superintendent.
3. **Handling Missing Values:** Identified blank cells in the `reason` column. Used the "none_given" placeholder to ensure data completeness for future analysis.
4. **Data Transformation (Categorical to Numerical):**
   * Converted parental education levels (`Medu`, `Fedu`) from text to numeric codes (0-4) using **Find and Replace**.
   * This transformation prepares the data for statistical calculations and machine learning models.

### Tools Used:
*  MS Excel (Sorting, Filtering, Fill Handle, Find and Replace).

### Key Insight from Sorting:
* **Identification of Outliers:** By simply sorting the `age` column, I discovered a discrepancy between the data and the business context. In a high school setting, students aged 20-22 appeared as anomalies.
* **Context is King:** This step highlighted that data cleaning isn't just a technical task—it requires understanding the specific domain rules (in this case, the school district's age limits) to maintain **Data Integrity**.
