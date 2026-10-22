# Applying and Refining AI-Assisted SQL Workflows

Follow-up to *Foundations of Prompt Engineering for SQL Workflows*. This lab validates the earlier AI-generated SQL for a healthcare appointment scenario, identifies where it could mislead decision-makers, and improves it with a four-step prompt chain (clarify → generate → review → refine).

**Business question:** Which patients have 2+ missed appointments (`no_show` or `canceled`) in the reporting period, and which of them have not returned for a completed visit since their last miss, so outreach staff can contact them first?

## Files
- `ValidatedSQLWorkflow_Lab.ipynb`: the completed lab (Tasks 1–8): reliability criteria, validation checklist, review of the original SQL, issue log, prompt chain, revised SQL, validation report and reflection
- `healthcare_operations_validation.ipynb`: provided validation notebook
- `healthcare_operations.db`: SQLite database (patients, appointments, providers, clinics, reporting_context)
