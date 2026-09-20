# Final QA

- Records: 1,500
- Columns: 31
- Duplicate rows: 0
- Duplicate Employee IDs: 0
- Missing source-data cells: 0
- Formula cells: 6,079
- Attrition count: 249
- Overall attrition: 16.6%
- Raw-data table range: A1:AE1501

The workbook includes an executive dashboard, formula-driven dashboard, segment analysis for department, job role, age, tenure, overtime, and income, plus an insights sheet. Findings are descriptive associations in synthetic data, not causal conclusions.

Before publishing, open the workbook in desktop Excel, allow formulas to recalculate, save, and reopen it once to confirm the displayed dashboard values.

The structural validation was performed with `openpyxl` against the workbook
file, while the data-quality totals were independently recomputed from the
employee records. Structural validation cannot replace an Excel desktop
recalculation check.
