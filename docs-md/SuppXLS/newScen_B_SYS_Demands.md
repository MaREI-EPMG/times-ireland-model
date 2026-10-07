# newScen_B_SYS_Demands.xlsx

## Purpose
This workbook supports the TIMES Ireland model as part of **System and policy assumptions**. It is used to define, adjust, or parameterize scenario assumptions and model behavior for its domain.

## Functional role in the model workflow
- Serves as an input artifact consumed by the model data-preparation process.
- Encodes structured assumptions that can vary by scenario, policy case, or technology pathway.
- Organizes data so updates can be managed without changing model code.

## Workbook structure
- Total worksheets: **6**
- Worksheets are grouped below by their likely functional theme based on sheet naming and content cues.

### Demand and activity assumptions
- **BY-Demands**
  - Content cues: ~TFM_FILL; Operation_Sum_Avg_Count; Scenario Name; TimeSlice
  - Likely use: stores structured assumptions or mappings used during scenario assembly and model execution.
- **REG_TRA_DEMANDS**
  - Content cues: ~TFM_DINS; TimeSlice; LimType; Attribute
  - Likely use: stores structured assumptions or mappings used during scenario assembly and model execution.
- **DEMANDS**
  - Content cues: ~TFM_INS-TS; LimType; Attribute; Region
  - Likely use: stores structured assumptions or mappings used during scenario assembly and model execution.

### General input tables
- **Cover**
  - Content cues: TIMES-Ireland Model; Document type:; Scenario; Sector(s):
  - Likely use: stores structured assumptions or mappings used during scenario assembly and model execution.
- **Regions**
  - Content cues: IE; National; IE-CW; IE-D
  - Likely use: stores structured assumptions or mappings used during scenario assembly and model execution.
- **TRA-2021**
  - Content cues: Total fuel consumption (litre); 2018; 6,681,011,455; 2019
  - Likely use: stores structured assumptions or mappings used during scenario assembly and model execution.

## User constraints and bounds
- No explicit user constraints with process-level mappings were identified in this workbook.

## Notes
- This documentation intentionally describes purpose and functionality without listing spreadsheet cell ranges.
- Naming suggests this file is part of a larger linked input set; keep workbook names and paths stable when integrating updates.
