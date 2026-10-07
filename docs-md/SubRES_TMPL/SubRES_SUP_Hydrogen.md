# SubRES_SUP_Hydrogen.xlsx

## Purpose
This workbook supports the TIMES Ireland model as part of **Supply and fuels**. It is used to define, adjust, or parameterize scenario assumptions and model behavior for its domain.

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
- **SUP_H2Production**
  - Content cues: HYDROGEN centralized production (H2PC); Source: UK TIMES; ~FI_T; ~FI_Process
  - Likely use: stores structured assumptions or mappings used during scenario assembly and model execution.
- **SUP_H2Liquefaction**
  - Content cues: HYDROGEN liquefaction (H2L); Source: UK TIMES; ~FI_T; ~FI_Process
  - Likely use: stores structured assumptions or mappings used during scenario assembly and model execution.
- **SUP_H2Delivery**
  - Content cues: HYDROGEN delivery (H2D); Source: UK TIMES; ~FI_T: MEUR2010; ~FI_Process
  - Likely use: stores structured assumptions or mappings used during scenario assembly and model execution.

### Technology definitions and performance
- **SUP_H2Storage**
  - Content cues: HYDROGEN storage (H2S); Source: UK TIMES; ~FI_T; ~FI_Process
  - Likely use: stores structured assumptions or mappings used during scenario assembly and model execution.

## User constraints and bounds
- No explicit user constraints with process-level mappings were identified in this workbook.

## Notes
- This documentation intentionally describes purpose and functionality without listing spreadsheet cell ranges.
- Naming suggests this file is part of a larger linked input set; keep workbook names and paths stable when integrating updates.
