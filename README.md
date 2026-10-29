# Somaliland Health Facilities SARA Survey Analysis

## Project Overview
An Excel-based descriptive analysis of a Somaliland health-facility dataset described in the project materials as SARA-related. The workbook explores facility distribution and selected service, ownership, location, and priority-needs fields.

## Tool
- Microsoft Excel

## Dataset and Source Status
The World Bank catalog includes a public dataset named [Somaliland — Health Facilities](https://datacatalog.worldbank.org/search/dataset/0066983/somaliland-health-facilities). Its catalog description says it contains point locations of health facilities collected by the SARA survey and the Government of Somaliland. This metadata **does not, by itself, verify the service-availability, ownership, or priority-needs variables in this repository's workbook**.

A separate Somaliland energy-sector report states that 348 health facilities were geotagged for its analysis using SARA data and Government of Somaliland information. That supports the provenance of a 348-facility geospatial compilation, but it does not validate every count or field in this workbook. The original workbook's exact source file, survey year, data dictionary, and version still need to be documented.

## Analysis Workflow
- Review field names, category labels, duplicates, and missing values
- Summarize facilities by region and facility type
- Review service-availability, ownership, location, priority-facility, and priority-needs fields where present
- State the denominator for each indicator and document missing-data handling

## Results and Verification Status
Figures previously listed in project notes—including regional counts, facility-type counts, service counts, ownership, priority needs, and population-served summaries—have not been independently recalculated in this README review. They are intentionally not presented as verified findings here. Recalculate them from the workbook and reconcile the reported 28-versus-29 district discrepancy before publishing numerical claims.

## Missing Data and Interpretation
- A blank cell is not proof that a facility does not provide a service. Keep No, Unknown, Not assessed, and Missing separate when the source allows it.
- Report both counts and denominators for service indicators; do not silently exclude missing records.
- Check for duplicate facilities and inconsistent region/district spellings.
- Do not generalize beyond the documented coverage or treat the workbook as a complete national facility registry without evidence.

## Project Files
- [Dashboard preview](<./Dashboard1%20.jpg>)
- [Excel data-cleaning workbook](<./data%20cleaning%20proj1.xlsx>)

## Limitations
The precise source/version, survey year, sampling/coverage approach, service definitions, and missing-data rules must be documented from the original dataset materials. The World Bank point-location metadata is not a substitute for the full source questionnaire or workbook codebook.

## Project Purpose
This project demonstrates Excel-based data validation, descriptive analysis, missing-data review, and communication of health-service data limitations.

## References
- World Bank Data Catalog. [Somaliland — Health Facilities](https://datacatalog.worldbank.org/search/dataset/0066983/somaliland-health-facilities).
- Government of Somaliland. [Energy sector report, section on health facilities](https://www.govsomaliland.org/uploads/files/2025/01/2025-01-20-12-57-20-52-1737377840.pdf).
