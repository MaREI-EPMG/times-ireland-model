# Scen_B_TRA_NewCars_Retirement.xlsx

## Purpose
This workbook supports the TIMES Ireland model as part of **Transport**. It is used to define, adjust, or parameterize scenario assumptions and model behavior for its domain.

## Functional role in the model workflow
- Serves as an input artifact consumed by the model data-preparation process.
- Encodes structured assumptions that can vary by scenario, policy case, or technology pathway.
- Organizes data so updates can be managed without changing model code.

## Workbook structure
- Total worksheets: **9**
- Worksheets are grouped below by their likely functional theme based on sheet naming and content cues.

### General input tables
- **Cover**
  - Content cues: TIMES-Ireland Model; Document type:; Scenario; Sector(s):
  - Likely use: stores structured assumptions or mappings used during scenario assembly and model execution.
- **Regions**
  - Content cues: IE; National; IE-CW; IE-D
  - Likely use: stores structured assumptions or mappings used during scenario assembly and model execution.
- **INS**
  - Content cues: Scrappage profile for passenger vehicles: ICEs; ~TFM_INS; Attribute; Year
  - Likely use: stores structured assumptions or mappings used during scenario assembly and model execution.
- **Scrappage profile**
  - Content cues: Passenger vehicles; Freight vehicles; ICEs; EVs
  - Likely use: stores structured assumptions or mappings used during scenario assembly and model execution.
- **UPD**
  - Content cues: Trans - Update; ~TFM_UPD; TimeSlice; LimType
  - Likely use: stores structured assumptions or mappings used during scenario assembly and model execution.
- **UCT1**
  - Likely use: stores structured assumptions or mappings used during scenario assembly and model execution.
- **UCT2**
  - Content cues: UC - Each Region/All Periods; ~UC_Sets: R_E: AllRegions; ~UC_Sets: T_S:; ~UC_T
  - Likely use: stores structured assumptions or mappings used during scenario assembly and model execution.
- **UCT3**
  - Content cues: UC - All Regions/Each Period; ~UC_Sets: R_S: AllRegions; ~UC_Sets: T_E:; ~UC_T
  - Likely use: stores structured assumptions or mappings used during scenario assembly and model execution.
- **UCT4**
  - Content cues: UC - All Regions/Periods; ~UC_Sets: R_S: AllRegions; ~UC_Sets: T_S:; ~UC_T
  - Likely use: stores structured assumptions or mappings used during scenario assembly and model execution.

## User constraints and bounds
- No explicit user constraints with process-level mappings were identified in this workbook.

## Notes
- This documentation intentionally describes purpose and functionality without listing spreadsheet cell ranges.
- Naming suggests this file is part of a larger linked input set; keep workbook names and paths stable when integrating updates.
