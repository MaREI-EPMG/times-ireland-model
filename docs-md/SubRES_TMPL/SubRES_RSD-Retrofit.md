# SubRES_RSD-Retrofit.xlsx

## Purpose
This workbook supports the TIMES Ireland model as part of **Residential and buildings**. It is used to define, adjust, or parameterize scenario assumptions and model behavior for its domain.

## Functional role in the model workflow
- Serves as an input artifact consumed by the model data-preparation process.
- Encodes structured assumptions that can vary by scenario, policy case, or technology pathway.
- Organizes data so updates can be managed without changing model code.

## Workbook structure
- Total worksheets: **4**
- Worksheets are grouped below by their likely functional theme based on sheet naming and content cues.

### General input tables
- **Cover**
  - Content cues: TIMES-Ireland Model; Document type:; New Technology; Sector(s):
  - Likely use: stores structured assumptions or mappings used during scenario assembly and model execution.
- **Intro**
  - Content cues: Table of contents; Colour code; Sheet; Description
  - Likely use: stores structured assumptions or mappings used during scenario assembly and model execution.
- **Data**
  - Content cues: ArDEM Space Heat Adjustment; Space Heating Correction Factor; Average (kWh/m2/yr); Table 2: Indicative annual running costs for different properties and BERs
  - Likely use: stores structured assumptions or mappings used during scenario assembly and model execution.

### Technology definitions and performance
- **RSD_Retrofit**
  - Content cues: SubRes Residential buildings; Retrofit Technologies; ~FI_Process; ~FI_T
  - Likely use: stores structured assumptions or mappings used during scenario assembly and model execution.

## User constraints and bounds
- No explicit user constraints with process-level mappings were identified in this workbook.

## Notes
- This documentation intentionally describes purpose and functionality without listing spreadsheet cell ranges.
- Naming suggests this file is part of a larger linked input set; keep workbook names and paths stable when integrating updates.
