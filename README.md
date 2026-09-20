# HR Analytics — AI-Assisted Excel Project

An end-to-end **HR Analytics and Employee Attrition** portfolio project built in Microsoft Excel with Generative AI assistance.

The project analyzes employee demographics, compensation, tenure, job satisfaction, overtime, work-life balance, job roles, departments, and attrition patterns through KPI analysis and an interactive Excel dashboard.

> **Transparency note:** Generative AI was used as an analytical co-pilot for parts of the project. The dataset is synthetic and created for educational/portfolio purposes. The final Excel workbook and analytical logic should be reviewed and validated by the project author.

## 🎯 Business Objective

The fictional HR leadership team wants to understand:

- Overall workforce size and attrition
- Where attrition is concentrated
- How attrition varies across departments and job roles
- Whether attrition is associated with tenure, compensation, overtime, satisfaction, and other employee characteristics
- Which workforce segments may warrant further HR investigation

## 📌 Key Analysis Areas

- Headcount
- Attrition count and attrition rate
- Department performance
- Job-role analysis
- Age and tenure segmentation
- Compensation analysis
- Overtime vs. attrition
- Job satisfaction
- Work-life balance
- Employee experience indicators

## 🛠️ Tools

- **Microsoft Excel**
  - Data cleaning
  - Formulas
  - Summary tables
  - KPI calculations
  - Charts
  - Dashboard
  - Formula-driven selectors
- **Generative AI / ChatGPT**
  - Dataset generation
  - Business-question ideation
  - KPI design
  - Excel formula assistance
  - Dashboard planning
  - Insight drafting
  - Project documentation

## 🤖 AI-Assisted Workflow

The project follows an **AI → Analyst → Excel → Validation** workflow.

1. **AI ideation** — Define business questions and analytical dimensions.
2. **AI-assisted dataset creation** — Generate synthetic employee-level data.
3. **Data preparation in Excel** — Inspect, clean, structure, and validate the data.
4. **Analysis design** — Define KPIs, calculated fields, PivotTables, and visualizations.
5. **AI-assisted interpretation** — Use AI to challenge and refine potential findings.
6. **Human validation** — Verify calculations, relationships, and dashboard outputs in Excel.
7. **Communication** — Convert validated findings into business-oriented insights.

See [`AI_Workflow.md`](AI_Workflow.md) for representative prompts and the role of AI at each stage.

## Repository Structure

```text
hr-analytics-excel-ai/
│
├── README.md
├── HR_Analytics_Portfolio_Final.xlsx
├── AI_Workflow.md
├── DATASET_NOTES.md
├── FINAL_QA.md
├── RELEASE_CHECKLIST.md
├── WORKBOOK_AUDIT.md
├── data_quality_audit.csv
├── workbook_audit.csv
├── .gitignore
└── LICENSE
```

## 📊 Dataset

The dataset contains synthetic employee-level records and HR attributes.

Important: **No real employee or confidential company data is used.**

The synthetic dataset is intended to demonstrate analytics methodology and Excel skills. Any observed relationship between variables should be treated as an analytical association in this synthetic dataset, **not as evidence of causation**.

## 💡 Example Business Questions

- Which departments have the highest observed attrition rate?
- Which job roles have elevated attrition?
- How does attrition vary by tenure?
- Is overtime associated with different attrition rates?
- How does average income differ between employees who stayed and those who left?
- How does job satisfaction vary across departments?
- Which employee segments should HR investigate further?

## Dashboard

Open `HR_Analytics_Portfolio_Final.xlsx` in Microsoft Excel and start on the
`Executive_Dashboard` sheet. The `Dashboard` sheet provides formula-driven
department and overtime selectors, KPI cards, supporting segment tables, and
charts. The workbook is designed for Excel desktop and should be recalculated
on open.

## Quick Start

1. Open `HR_Analytics_Portfolio_Final.xlsx` in desktop Excel.
2. Review the `Executive_Dashboard` for the headline KPIs.
3. Use the `Dashboard` sheet selectors to filter department and overtime.
4. Review the segment sheets and `Insights` for supporting evidence.
5. Recalculate and save the workbook after opening it.

## 📈 Portfolio Skills Demonstrated

- Data cleaning
- Exploratory data analysis
- KPI design
- Segmentation
- PivotTable analysis
- Data visualization
- Dashboard development
- Business insight generation
- AI-assisted analytics workflow
- Analytical validation

## ⚠️ Limitations

- The dataset is synthetic.
- Results are not representative of any real organization.
- Attrition relationships are observational associations within the generated data.
- The project is intended to demonstrate analytics workflow and Excel capability, not to support real HR decisions.

## Author

**Satya**

Data Analytics | Excel | AI-Assisted Analytics


## Workbook Contents

- `Executive_Dashboard` — executive KPI summary.
- `Dashboard` — interactive formula-driven dashboard.
- `Raw_Data` — 1,500 synthetic employee records and calculated fields.
- `KPI_Calculations` — transparent KPI definitions and Excel formulas.
- `Analysis_Plan` — business questions mapped to dimensions, metrics, and visual choices.
- Segment analysis sheets for department, job role, age, tenure, overtime, and income.
- `Insights` — evidence-based observations and cautions.

## License and Use

This project is provided for educational and portfolio purposes. The dataset is
synthetic and contains no real employee information. See `LICENSE` for the
repository terms.

## Validation

The included audit reports are generated from the current workbook. They verify
record counts, duplicate IDs, missing source-data cells, formula structure,
worksheet visibility, external links, and the calculated-field table range.
