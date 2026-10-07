# Scen_SYS_WAM2050_Emissions.xlsx

## Purpose
This workbook supports the TIMES Ireland model as part of **System and policy assumptions**. It is used to define, adjust, or parameterize scenario assumptions and model behavior for its domain.

## Functional role in the model workflow
- Serves as an input artifact consumed by the model data-preparation process.
- Encodes structured assumptions that can vary by scenario, policy case, or technology pathway.
- Organizes data so updates can be managed without changing model code.

## Workbook structure
- Total worksheets: **6**
- Worksheets are grouped below by their likely functional theme based on sheet naming and content cues.

### Controls and configuration
- **config**
  - Content cues: UC_N; UC_WAM_CO2_Emissions; UC_desc; WAM CO2 Emissions Bound
  - Likely use: stores structured assumptions or mappings used during scenario assembly and model execution.

### General input tables
- **Cover**
  - Content cues: TIMES-Ireland Model; Document type:; Scenario; Sector(s):
  - Likely use: stores structured assumptions or mappings used during scenario assembly and model execution.
- **Regions**
  - Content cues: IE; 2; Development; National
  - Likely use: stores structured assumptions or mappings used during scenario assembly and model execution.
- **single**
  - Content cues: UC - Each Region/All Periods; ~UC_Sets: R_E: IE; ~UC_Sets: T_E:; ~UC_T
  - Likely use: stores structured assumptions or mappings used during scenario assembly and model execution.
- **multi**
  - Content cues: UC - All Regions/Each Period; UC_N; Cset_CN; Cset_Set
  - Likely use: stores structured assumptions or mappings used during scenario assembly and model execution.
- **With Additional Measures**
  - Content cues: 2023-2050 GHG Emissions Projections (kt CO2 eq); 2022; 2023; 2024
  - Likely use: stores structured assumptions or mappings used during scenario assembly and model execution.

## User constraints and bounds
- **Constraint name: TOTCO2**
  - Source worksheet(s): multi
  - Processes limited:
    - T-A*INT*
    - T-NAV*

## Notes
- This documentation intentionally describes purpose and functionality without listing spreadsheet cell ranges.
- Naming suggests this file is part of a larger linked input set; keep workbook names and paths stable when integrating updates.
