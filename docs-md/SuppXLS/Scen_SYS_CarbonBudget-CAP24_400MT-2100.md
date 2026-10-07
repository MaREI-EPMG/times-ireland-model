# Scen_SYS_CarbonBudget-CAP24_400MT-2100.xlsx

## Purpose
This workbook supports the TIMES Ireland model as part of **System and policy assumptions**. It is used to define, adjust, or parameterize scenario assumptions and model behavior for its domain.

## Functional role in the model workflow
- Serves as an input artifact consumed by the model data-preparation process.
- Encodes structured assumptions that can vary by scenario, policy case, or technology pathway.
- Organizes data so updates can be managed without changing model code.

## Workbook structure
- Total worksheets: **5**
- Worksheets are grouped below by their likely functional theme based on sheet naming and content cues.

### Controls and configuration
- **config**
  - Content cues: UC_N; UC_CB_400_Mt_2021-2100; UC_CB_274_Mt_2021-2030; UC_CB_126_Mt_2031-2050
  - Likely use: stores structured assumptions or mappings used during scenario assembly and model execution.

### Emissions and carbon constraints
- **negative_CO2**
  - Content cues: TFM_INS; TimeSlice; LimType; Attribute
  - Likely use: stores structured assumptions or mappings used during scenario assembly and model execution.

### General input tables
- **Cover**
  - Content cues: TIMES-Ireland Model; Document type:; Scenario; Sector(s):
  - Likely use: stores structured assumptions or mappings used during scenario assembly and model execution.
- **Regions**
  - Content cues: IE; 2; Development; National
  - Likely use: stores structured assumptions or mappings used during scenario assembly and model execution.
- **single**
  - Content cues: UC - Each Region/All Periods; ~UC_Sets: R_S:; ~UC_Sets: T_S:; ~UC_T
  - Likely use: stores structured assumptions or mappings used during scenario assembly and model execution.

## User constraints and bounds
- No explicit user constraints with process-level mappings were identified in this workbook.

## Notes
- This documentation intentionally describes purpose and functionality without listing spreadsheet cell ranges.
- Naming suggests this file is part of a larger linked input set; keep workbook names and paths stable when integrating updates.
