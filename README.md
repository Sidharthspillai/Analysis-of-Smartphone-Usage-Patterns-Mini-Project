# Analysis-of-Smartphone-Usage-Patterns-Mini-Project
Analysis of Smartphone Usage Patterns

## Project overview

This mini project explores smartphone usage patterns, including app usage, screen-on time, battery consumption and mobile data usage. The prepared Excel workbook contains 700 records and 12 columns, including one newly added column.

## Dataset source

- Dataset: Mobile Device Usage and User Behavior Dataset
- Source: [Kaggle](https://www.kaggle.com/datasets/valakhorasani/mobile-device-usage-and-user-behavior-dataset)
- Original size: 700 rows and 11 columns
- Prepared workbook: Analysis of Smartphone Usage Patterns.xlsx
- The source data is simulated and is used for educational analysis.

## Work completed

1. **Added all borders:** Applied cell borders to make the table easier to read and distinguish rows and columns.
2. **Corrected alignment:** Adjusted the alignment of headings and data for a consistent appearance.
3. **Changed the font:** Used Times New Roman for the dataset's presentation.
4. **Added a new column:** Created `App Usage Hours` in column L to express daily app usage in hours.
5. **Formatted decimal places:** Formatted the new column to display two decimal places for readability.

## New column: App Usage Hours

The new column converts the existing `App Usage Time (min/day)` values into hours per day.

**Calculation:** App Usage Hours = App Usage Time (min/day) / 60

Example Excel formula in cell L2:

```excel
=D2/60
```
## Data quality notes

The earlier review of the original CSV found no missing values or exact duplicate rows, so no missing-value replacement or duplicate removal was necessary. Formatting changes improve presentation and do not change the original observations.
