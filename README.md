# Sales-data-clean
This repository contains a cleaned version of a sales dataset originally collected in Excel format.

## Overview

The dataset includes transactional sales data like:
- Product ID
- Sale Date
- Sales Representative
- Region
- Category
- Sales Amount, Unit Cost, Unit Price
- Customer Type, Discount, Payment Method, etc.

## Data Cleaning Steps Performed

The following cleaning operations were applied:

- ✅ Removed *duplicate rows* based on key fields (Product ID, Sale Date, Sales Rep)
- ✅ Handled *blank cells*, especially in Sales Channel and other columns
- ✅ Trimmed *extra spaces* in text fields like Category and Sales Rep
- ✅ Ensured *consistent capitalization* using PROPER() formula
- ✅ Validated values in *Unit Cost, **Discount* and flagged outliers
- ✅ Verified consistency between duplicate columns like Sales Rep (if repeated)

## File Included

- Salesdata.xlsx: Cleaned Excel file after data preprocessing

## Tools Used

- Microsoft Excel
- Excel Formulas like TRIM(), PROPER(), IF(), COUNTIFS()



