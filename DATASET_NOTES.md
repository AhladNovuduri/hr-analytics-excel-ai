# Dataset Notes

## Dataset Type

**Synthetic / generated data**

This dataset was created for an educational and portfolio project. It does not contain real employee records.

## Grain

One row represents one employee.

## Main Outcome

`Attrition` indicates whether the employee left the fictional organization:

- `Yes` = employee left
- `No` = employee stayed

## Important Analytical Caveat

The data-generation process includes synthetic relationships between selected HR variables and attrition so that the workbook supports meaningful analytical exercises.

Therefore:

- Do not present findings as real-world HR benchmarks.
- Do not claim that one variable causes attrition.
- Describe relationships as **observed associations**.
- Treat all results as demonstrations of analytical technique.

## Derived Fields Included in the Workbook

The `Raw_Data` sheet includes these Excel-calculated columns:

- Age Group
- Tenure Group
- Income Band
- Attrition Flag
- Promotion Recency Band
- Satisfaction Category

## Validation Checks Performed

1. EmployeeID uniqueness
2. Blank/null checks
3. Duplicate-record review
4. Attrition value consistency
5. Numeric range checks
6. Date validity
7. Cross-field consistency checks

The current audit reports 1,500 records, 31 columns, no duplicate Employee IDs,
no duplicate full rows, and no missing source-data cells. Derived formula
columns are recalculated by Excel when the workbook is opened.
