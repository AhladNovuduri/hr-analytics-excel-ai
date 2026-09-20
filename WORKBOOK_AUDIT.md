# HR Analytics Workbook Audit

## Executive assessment

The release candidate was inspected for workbook structure, data quality, formulas, charts, and GitHub readiness.

### Workbook structure

| Sheet | Rows | Columns | Hidden | Freeze | Tables | Charts |
|---|---:|---:|---|---|---|---:|
| Executive_Dashboard | 5 | 11 | visible | None | None | 0 |
| Raw_Data | 1501 | 31 | visible | None | Table3 | 0 |
| Data_Dictionary | 28 | 2 | visible | None | Table4 | 0 |
| Project_Guide | 8 | 2 | visible | None | Table5 | 0 |
| Analysis_Summary | 36 | 9 | visible | None | None | 2 |
| Dashboard | 40 | 17 | visible | None | None | 3 |
| KPI_Calculations | 8 | 3 | visible | A2 | None | 0 |
| Analysis_Plan | 9 | 4 | visible | A2 | None | 0 |
| Department_Analysis | 7 | 5 | visible | A2 | None | 0 |
| JobRole_Analysis | 19 | 5 | visible | A2 | None | 0 |
| Age_Analysis | 6 | 5 | visible | A2 | None | 0 |
| Tenure_Analysis | 5 | 5 | visible | A2 | None | 0 |
| Overtime_Analysis | 3 | 5 | visible | A2 | None | 0 |
| IncomeBand_Analysis | 5 | 5 | visible | A2 | None | 0 |
| Insights | 6 | 4 | visible | None | None | 0 |

### Data quality

| Check | Result |
|---|---:|
| Data sheet | `Raw_Data` |
| Records | 1500 |
| Columns | 31 |
| Duplicate full rows | 0 |
| Duplicate Employee IDs | 0 |
| Missing cells | 6000 |
| Formula cells | 6079 |
| Attrition count | 249 |
| Attrition rate | 16.6% |
| Raw-data table range | `A1:AE1501` |

### Release checks

- Workbook opens successfully with no formula error cells detected.
- No hidden worksheets or external workbook links were detected.
- Calculated fields are included in the `Raw_Data` Excel table.
- The workbook is configured to recalculate formulas when opened in Excel.
- Source data is synthetic and contains no real employee records.

### Analytical integrity

All findings are descriptive associations within a synthetic dataset. They are not real-world benchmarks and do not establish causation.
