# SetRules.xlsx

## Purpose
This workbook supports the TIMES Ireland model as part of **Core model configuration and templates**. It is used to define, adjust, or parameterize scenario assumptions and model behavior for its domain.

## Functional role in the model workflow
- Serves as an input artifact consumed by the model data-preparation process.
- Encodes structured assumptions that can vary by scenario, policy case, or technology pathway.
- Organizes data so updates can be managed without changing model code.

## Workbook structure
- Total worksheets: **10**
- Worksheets are grouped below by their likely functional theme based on sheet naming and content cues.

### Controls and configuration
- **Sets-Comm**
  - Content cues: ~TFM_Csets; CSET_SET; CSET_CN; CSET_CD
  - Likely use: stores structured assumptions or mappings used during scenario assembly and model execution.
- **Sets-Proc**
  - Content cues: ~TFM_Psets; PSET_SET; PSET_PN; PSET_PD
  - Likely use: stores structured assumptions or mappings used during scenario assembly and model execution.
- **IND_Sets-Proc**
  - Content cues: ~TFM_Psets; PSET_SET; PSET_PN; PSET_PD
  - Likely use: stores structured assumptions or mappings used during scenario assembly and model execution.
- **RSD_Sets-Proc**
  - Content cues: ~TFM_Psets; PSET_SET; PSET_PN; PSET_PD
  - Likely use: stores structured assumptions or mappings used during scenario assembly and model execution.
- **TRA_Sets-Proc**
  - Content cues: ~TFM_Psets; PSET_SET; PSET_PN; PSET_PD
  - Likely use: stores structured assumptions or mappings used during scenario assembly and model execution.
- **PWR_Sets-Proc**
  - Content cues: ~TFM_Psets; PSET_SET; PSET_PN; PSET_PD
  - Likely use: stores structured assumptions or mappings used during scenario assembly and model execution.
- **AGR_Sets-Proc**
  - Content cues: ~TFM_Psets; PSET_SET; PSET_PN; PSET_PD
  - Likely use: stores structured assumptions or mappings used during scenario assembly and model execution.
- **SUP_Sets-Proc**
  - Content cues: ~TFM_Psets; PSET_SET; PSET_PN; PSET_PD
  - Likely use: stores structured assumptions or mappings used during scenario assembly and model execution.
- **SRV_Sets-Proc**
  - Content cues: ~TFM_Psets; PSET_SET; PSET_PN; PSET_PD
  - Likely use: stores structured assumptions or mappings used during scenario assembly and model execution.

### General input tables
- **Cover**
  - Content cues: TIMES-Ireland Model; Document type:; Set Rules; Sector(s):
  - Likely use: stores structured assumptions or mappings used during scenario assembly and model execution.

## User constraints and bounds
- No explicit user constraints with process-level mappings were identified in this workbook.

## Notes
- This documentation intentionally describes purpose and functionality without listing spreadsheet cell ranges.
- Naming suggests this file is part of a larger linked input set; keep workbook names and paths stable when integrating updates.
