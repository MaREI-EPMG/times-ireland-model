# Scen_z_MACC-SRV-CAP-WEM.xlsx

## Purpose
This workbook supports the TIMES Ireland model as part of **Cross-sector scenarios and sensitivity cases**. It is used to define, adjust, or parameterize scenario assumptions and model behavior for its domain.

## Functional role in the model workflow
- Serves as an input artifact consumed by the model data-preparation process.
- Encodes structured assumptions that can vary by scenario, policy case, or technology pathway.
- Organizes data so updates can be managed without changing model code.

## Workbook structure
- Total worksheets: **1**
- Worksheets are grouped below by their likely functional theme based on sheet naming and content cues.

### General input tables
- **data**
  - Content cues: Sum of Pv; Period; Processset; Process
  - Likely use: stores structured assumptions or mappings used during scenario assembly and model execution.

## User constraints and bounds
- **Constraint name: SRVHET**
  - Bound fields: 2023, 2024, 2025, 2026, 2027, 2028, 2029, 2030, 2031, 2032, 2033, 2034, 2035, 2036, 2037, 2038, 2039, 2040
  - Bound value range(s): 2023 (0.01296 to 0.01296), 2024 (0.02016 to 0.02016), 2025 (0.02016 to 0.02016), 2026 (0.02016 to 0.02016), 2027 (0.02016 to 0.02016), 2028 (0.226858 to 0.226858), 2029 (0.433555 to 0.433555), 2030 (0.640253 to 0.640253), 2031 (1.35383 to 1.35383), 2032 (2.0674 to 2.0674), 2033 (2.78098 to 2.78098), 2034 (3.49455 to 3.49455), 2035 (4.20813 to 4.20813), 2036 (4.9217 to 4.9217), 2037 (5.63528 to 5.63528), 2038 (6.34885 to 6.34885), 2039 (7.06243 to 7.06243), 2040 (7.776 to 7.776)
  - Source worksheet(s): data
  - Processes limited:
    - FT-SRVHET

## Notes
- This documentation intentionally describes purpose and functionality without listing spreadsheet cell ranges.
- Naming suggests this file is part of a larger linked input set; keep workbook names and paths stable when integrating updates.
