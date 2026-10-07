# SubRES_PWR_NewTechs.xlsx

## Purpose
This workbook supports the TIMES Ireland model as part of **Power and electricity**. It is used to define, adjust, or parameterize scenario assumptions and model behavior for its domain.

## Functional role in the model workflow
- Serves as an input artifact consumed by the model data-preparation process.
- Encodes structured assumptions that can vary by scenario, policy case, or technology pathway.
- Organizes data so updates can be managed without changing model code.

## Workbook structure
- Total worksheets: **8**
- Worksheets are grouped below by their likely functional theme based on sheet naming and content cues.

### Costs, prices, and economics
- **WIN_ON_COST**
  - Content cues: fid; Merged_ID; Parcel; COUNTY - 1
  - Likely use: stores structured assumptions or mappings used during scenario assembly and model execution.
- **Win_ON_Cost_Data**
  - Content cues: fid; Merged_ID; Parcel; COUNTY - 1
  - Likely use: stores structured assumptions or mappings used during scenario assembly and model execution.
- **ETRI_Cost**
  - Content cues: Tsiropoulos I, Tarvydas, D, Zucker, A, Cost development of low carbon energy technologies - Scenario-based cost trajecto; Wind energy; Input assumptions on learning rate method for onshore wind energy; Unit
  - Likely use: stores structured assumptions or mappings used during scenario assembly and model execution.

### General input tables
- **Cover**
  - Content cues: TIMES-Ireland Model; Document type:; New Technologies; Sector(s):
  - Likely use: stores structured assumptions or mappings used during scenario assembly and model execution.
- **ELC_EGP**
  - Content cues: Electricity Generators Database; Source: ETRI 2014 (https://setis.ec.europa.eu/publications/jrc-setis-reports/etri-2014 ); ~FI_T: MEUR2015; ~FI_Process
  - Likely use: stores structured assumptions or mappings used during scenario assembly and model execution.
- **IMPEXP**
  - Content cues: Electricity Interconnector; ~FI_T: MEUR2014; ~FI_Process; Region
  - Likely use: stores structured assumptions or mappings used during scenario assembly and model execution.
- **ELC_WIN**
  - Content cues: ~FI_T: MEUR2024; ~FI_Process; TechName; *TechDesc
  - Likely use: stores structured assumptions or mappings used during scenario assembly and model execution.
- **ELC_CCS**
  - Content cues: Electricity Generators Database - CCS options; Sources:; Techno-economic data: ETRI 2014 (https://setis.ec.europa.eu/publications/jrc-setis-reports/etri-2014 ); Process options: Irish TIMES v1.0 (using Fionn's analysis)
  - Likely use: stores structured assumptions or mappings used during scenario assembly and model execution.

## User constraints and bounds
- No explicit user constraints with process-level mappings were identified in this workbook.

## Notes
- This documentation intentionally describes purpose and functionality without listing spreadsheet cell ranges.
- Naming suggests this file is part of a larger linked input set; keep workbook names and paths stable when integrating updates.
