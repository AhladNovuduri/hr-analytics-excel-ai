# AI Workflow 🤖

## Purpose

This document records how Generative AI was used as a productivity and analytical-assistance tool during the HR Analytics project.

The goal was not to replace analytical judgment. AI outputs were treated as suggestions and were expected to be checked against the workbook.

## Representative Prompts

### 1. Dataset design

> Generate a realistic employee-level HR dataset suitable for an Excel employee attrition analysis project. Include demographic, compensation, tenure, satisfaction, work-life balance, overtime, job-role, and attrition variables.

**AI contribution:** Dataset structure and synthetic data generation.

### 2. Business questions

> Act as an HR Data Analyst. Based on this dataset, propose business questions that HR leadership could answer using Excel.

**AI contribution:** Initial analytical-question ideation.

### 3. KPI design

> Suggest KPIs for an HR attrition dashboard and explain how each KPI should be calculated.

**AI contribution:** KPI brainstorming and calculation guidance.

### 4. Excel assistance

> Write an Excel formula to calculate employee attrition rate from an employee-level dataset where Attrition contains Yes/No values.

**AI contribution:** Formula assistance.

### 5. Dashboard planning

> Propose an executive HR analytics dashboard layout using KPI cards, PivotTables, charts, and slicers. Prioritize visuals that answer business questions.

**AI contribution:** Dashboard architecture and visualization suggestions.

### 6. Insight review

> Review these HR analytics findings. Separate descriptive findings from assumptions and avoid claiming causation where the data only shows association.

**AI contribution:** Analytical quality check and wording refinement.

## Human Validation

AI-generated suggestions were not treated as automatically correct.

The analyst should validate:

- Formula logic
- PivotTable calculations
- KPI definitions
- Data quality
- Chart interpretation
- Segment comparisons
- Business conclusions

## AI vs. Analyst Responsibility

| Activity | AI Assistance | Analyst Responsibility |
|---|---|---|
| Dataset generation | High | Define requirements and validate structure |
| Business questions | High | Select relevant questions |
| Excel formulas | Medium/High | Verify formulas and results |
| KPI design | High | Define final metric definitions |
| Dashboard layout | High | Choose final visuals and usability |
| Insight drafting | Medium/High | Validate evidence and wording |
| Final conclusions | Advisory | Own the analytical conclusion |

## Guiding Principle

**AI accelerates the workflow; the analyst owns the analysis.**
