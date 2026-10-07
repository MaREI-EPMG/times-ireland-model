# SubRES_SRV_DC_ExcessHeat.xlsx

## Purpose
This workbook supports the TIMES Ireland model as part of **Services and commercial buildings**. It is used to define, adjust, or parameterize scenario assumptions and model behavior for its domain.

## Functional role in the model workflow
- Serves as an input artifact consumed by the model data-preparation process.
- Encodes structured assumptions that can vary by scenario, policy case, or technology pathway.
- Organizes data so updates can be managed without changing model code.

## Workbook structure
- Total worksheets: **5**
- Worksheets are grouped below by their likely functional theme based on sheet naming and content cues.

### General input tables
- **Cover**
  - Content cues: TIMES-Ireland Model; Document type:; New Technologies; Sector(s):
  - Likely use: stores structured assumptions or mappings used during scenario assembly and model execution.
- **SRV_DC_Commodities**
  - Content cues: Fixed layout table; * Define the commodities used in this workbook; Commodities; ~FI_Comm
  - Likely use: stores structured assumptions or mappings used during scenario assembly and model execution.
- **HP_data**
  - Content cues: Source: Technology Data - Energy Plants for Electricity and District heating generation (V0009). Danish Energy Agency; Technology; Heat pumps utilizing industrial waste heat 3 MW; 2020
  - Likely use: stores structured assumptions or mappings used during scenario assembly and model execution.
- **HE_data**
  - Content cues: Source: Technology Data for heating installations (V0002). Danish Energy Agency; Technology; Indirect district heating substation - apartment complex - existing building; year
  - Likely use: stores structured assumptions or mappings used during scenario assembly and model execution.

### Technology definitions and performance
- **SRV_DC_Processes**
  - Content cues: ~FI_T; ~FI_Process; TechName; *TechDesc
  - Likely use: stores structured assumptions or mappings used during scenario assembly and model execution.

## User constraints and bounds
- No explicit user constraints with process-level mappings were identified in this workbook.

## Notes
- This documentation intentionally describes purpose and functionality without listing spreadsheet cell ranges.
- Naming suggests this file is part of a larger linked input set; keep workbook names and paths stable when integrating updates.
