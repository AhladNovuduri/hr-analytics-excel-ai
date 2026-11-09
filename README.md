# HR Analytics — Excel & AI-Assisted Workforce Analysis

An Excel-based HR analytics portfolio project using synthetic employee records to demonstrate KPI design, workforce segmentation, dashboard development, and AI-assisted analytical workflows.

> **Data transparency:** The dataset is synthetic and is not representative of a real employer or workforce. Findings are descriptive associations within generated data, not causal conclusions or external HR benchmarks.

## Business Questions

- What are the overall workforce size and attrition rate in the synthetic dataset?
- How does attrition vary across departments and job roles?
- How do age, tenure, income, overtime, satisfaction, and work-life-balance segments compare?
- Which segments warrant further investigation in a hypothetical HR setting?

## Workbook & Deliverables

Open `HR_Analytics_Portfolio_Final.xlsx` in desktop Microsoft Excel.

| Workbook sheet / file | Purpose |
|---|---|
| `Executive_Dashboard` | Executive KPI summary |
| `Dashboard` | Formula-driven dashboard and selectors |
| `Raw_Data` | Synthetic employee-level records |
| `Data_Dictionary` | Field definitions |
| `KPI_Calculations` | KPI calculations |
| `Analysis_Plan` | Business questions and analysis plan |
| Segment analysis sheets | Department, job role, age, tenure, overtime, and income analysis |
| `Insights` | Descriptive observations and caveats |
| `AI_Workflow.md` | AI-assisted workflow and human validation |
| `DATASET_NOTES.md` | Synthetic data and dataset caveats |
| `WORKBOOK_AUDIT.md` | Structural and data-quality audit |
| `FINAL_QA.md` | Final QA summary |

## Dataset & Reported QA

The project documentation reports:

- 1,500 synthetic employee records.
- 31 columns.
- 249 records marked as attrition = Yes.
- A reported attrition rate of 16.6%.
- 6,079 formula cells.

These are figures reported in the project QA documents and should be rechecked against the workbook before being treated as independently reproduced.

### Audit discrepancy requiring resolution

`WORKBOOK_AUDIT.md` and `data_quality_audit.csv` report 6,000 missing cells, while `FINAL_QA.md` and `DATASET_NOTES.md` state that there are zero missing source-data cells. The distinction between source input cells, derived/formula cells, and blank worksheet/formula outputs must be reconciled. Do not describe the workbook as having zero missing cells until this is resolved.

## AI-Assisted Workflow

The documented workflow uses AI for ideation, dataset design, KPI suggestions, formula assistance, dashboard planning, and insight review. The analyst remains responsible for checking formulas, data quality, interpretations, and final conclusions.

See [AI_Workflow.md](AI_Workflow.md).

## Getting Started

1. Clone this repository.
2. Open `HR_Analytics_Portfolio_Final.xlsx` in desktop Excel.
3. Review `Executive_Dashboard`.
4. Explore the `Dashboard` sheet and its selectors.
5. Inspect the supporting analysis and audit documentation.
6. Allow Excel to recalculate formulas, save, close, and reopen the workbook as recommended by `FINAL_QA.md`.

## Limitations

- All employee records are synthetic.
- Results are not real-world benchmarks.
- Observational segment differences do not establish causation.
- Excel desktop recalculation remains a manual release check.
- The missing-cell audit discrepancy remains unresolved.

## License

See [LICENSE](LICENSE) for the applicable terms.

## Author

**Ahlad Novuduri** · [GitHub](https://github.com/AhladNovuduri)
