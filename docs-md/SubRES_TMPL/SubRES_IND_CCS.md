# SubRES_IND_CCS.xlsx

## Purpose
This workbook supports the TIMES Ireland model as part of **Industry**. It is used to define, adjust, or parameterize scenario assumptions and model behavior for its domain.

## Functional role in the model workflow
- Serves as an input artifact consumed by the model data-preparation process.
- Encodes structured assumptions that can vary by scenario, policy case, or technology pathway.
- Organizes data so updates can be managed without changing model code.

## Workbook structure
- Total worksheets: **7**
- Worksheets are grouped below by their likely functional theme based on sheet naming and content cues.

### General input tables
- **Cover**
  - Content cues: TIMES-Ireland Model; Document type:; New Technologies; Sector(s):
  - Likely use: stores structured assumptions or mappings used during scenario assembly and model execution.
- **CCS**
  - Content cues: Old table: deactivated; FI_T: MEUR2010; ~FI_Process; TechName
  - Likely use: stores structured assumptions or mappings used during scenario assembly and model execution.
- **IND**
  - Content cues: 174; Cement; Chemicals; Food and Drink
  - Likely use: stores structured assumptions or mappings used during scenario assembly and model execution.
- **pivot_SEAI**
  - Content cues: Sum of Marginal capex (€/kWth); Column Labels; Row Labels; 10000
  - Likely use: stores structured assumptions or mappings used during scenario assembly and model execution.
- **data_SEAI**
  - Content cues: Filtered data from; ID; Technology; Year
  - Likely use: stores structured assumptions or mappings used during scenario assembly and model execution.

### Technology definitions and performance
- **IND_TECH**
  - Content cues: ~FI_T; ~FI_Process; TechName; *TechDesc
  - Likely use: stores structured assumptions or mappings used during scenario assembly and model execution.
- **techs**
  - Likely use: stores structured assumptions or mappings used during scenario assembly and model execution.

## User constraints and bounds
- No explicit user constraints with process-level mappings were identified in this workbook.

## Notes
- This documentation intentionally describes purpose and functionality without listing spreadsheet cell ranges.
- Naming suggests this file is part of a larger linked input set; keep workbook names and paths stable when integrating updates.
