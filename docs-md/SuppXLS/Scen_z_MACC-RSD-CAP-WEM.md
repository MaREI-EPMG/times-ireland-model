# Scen_z_MACC-RSD-CAP-WEM.xlsx

## Purpose
This workbook supports the TIMES Ireland model as part of **Cross-sector scenarios and sensitivity cases**. It is used to define, adjust, or parameterize scenario assumptions and model behavior for its domain.

## Functional role in the model workflow
- Serves as an input artifact consumed by the model data-preparation process.
- Encodes structured assumptions that can vary by scenario, policy case, or technology pathway.
- Organizes data so updates can be managed without changing model code.

## Workbook structure
- Total worksheets: **2**
- Worksheets are grouped below by their likely functional theme based on sheet naming and content cues.

### General input tables
- **data**
  - Content cues: 2019; 2020; 2021; 2022
  - Likely use: stores structured assumptions or mappings used during scenario assembly and model execution.
- **caps_data**
  - Content cues: Sum of Pv; Period; Processset; Process
  - Likely use: stores structured assumptions or mappings used during scenario assembly and model execution.

## User constraints and bounds
- **Constraint name: RSDHET**
  - Bound fields: 2024, 2025, 2026, 2027, 2028, 2029, 2030, 2031, 2032, 2033, 2034, 2035, 2036, 2037, 2038, 2039, 2040, 2041, 2042, 2043
  - Bound value range(s): 2024 (0.00504 to 0.00504), 2025 (0.00504 to 0.00504), 2026 (0.00504 to 0.00504), 2027 (0.00504 to 0.00504), 2028 (0.00504 to 0.0567144), 2029 (0.00504 to 0.108389), 2030 (0.00504 to 0.160063), 2031 (0.0567144 to 0.338457), 2032 (0.108389 to 0.516851), 2033 (0.160063 to 0.695244), 2034 (0.338457 to 0.873638), 2035 (0.516851 to 1.05203), 2036 (0.695244 to 1.23043), 2037 (0.873638 to 1.40882), 2038 (1.05203 to 1.58721), 2039 (1.23043 to 1.76561), 2040 (1.40882 to 1.944), 2041 (1.58721 to 1.58721), 2042 (1.76561 to 1.76561), 2043 (1.944 to 1.944)
  - Source worksheet(s): data
  - Processes limited:
    - FT-RSDHET

## Notes
- This documentation intentionally describes purpose and functionality without listing spreadsheet cell ranges.
- Naming suggests this file is part of a larger linked input set; keep workbook names and paths stable when integrating updates.
