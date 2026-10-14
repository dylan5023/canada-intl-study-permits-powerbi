# Data sources

| File | Publisher | Description | Coverage | Downloaded |
|---|---|---|---|---|
| `EN_ODP-TR-Study-DLI_name_PT_Admin_type.xlsx` | Immigration, Refugees and Citizenship Canada (IRCC) | Post-secondary study permit holders by DLI name, province/territory and public/private status | Jan 2016 – Jul 2026 (data as of July 31, 2026; preliminary) | 2026-10-12 |
| `EN_ODP-TR-Study-DLI_name_PT_Inst_type.xlsx` | IRCC | Post-secondary study permit holders by DLI name, province/territory and institution type | Jan 2016 – Jul 2026 (as above) | 2026-10-12 |
| `3710001801_databaseLoadingData.csv` | Statistics Canada | Table 37-10-0018-01, postsecondary enrolments; selection: Canada, provinces and Territories; all institution types, registration statuses, fields of study and genders = Total; status of student in Canada = Total / Canadian / International / Not reported | 2016/2017 – 2024/2025 | 2026-10-13 |

Source pages:
- IRCC study permit data: Open Government Portal — https://open.canada.ca/data/en/dataset/90115b00-f9b8-49e8-afa3-b4cff8facaee
- Statistics Canada Table 37-10-0018-01 — https://www150.statcan.gc.ca/t1/tbl1/en/cv.action?pid=3710001801

## Notes
- Files are stored exactly as downloaded (no edits).
- IRCC shows values between 1 and 4 as `--`; other values are rounded to the nearest 5.
- The Statistics Canada CSV ends with blank lines; they are removed in Power Query.

## Licence
IRCC data: Open Government Licence – Canada (https://open.canada.ca/en/open-government-licence-canada).
Statistics Canada data: Statistics Canada Open Licence (https://www.statcan.gc.ca/en/reference/licence).
Adapted by the author; not endorsed by IRCC or Statistics Canada.
