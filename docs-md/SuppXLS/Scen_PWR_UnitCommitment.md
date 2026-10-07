# Scen_PWR_UnitCommitment.xlsx

## Purpose
This workbook supports the TIMES Ireland model as part of **Power and electricity**. It is used to define, adjust, or parameterize scenario assumptions and model behavior for its domain.

## Functional role in the model workflow
- Serves as an input artifact consumed by the model data-preparation process.
- Encodes structured assumptions that can vary by scenario, policy case, or technology pathway.
- Organizes data so updates can be managed without changing model code.

## Workbook structure
- Total worksheets: **11**
- Worksheets are grouped below by their likely functional theme based on sheet naming and content cues.

### General input tables
- **Cover**
  - Content cues: TIMES-Ireland Model; Document type:; Scenario; Sector(s):
  - Likely use: stores structured assumptions or mappings used during scenario assembly and model execution.
- **CSTSD**
  - Content cues: Start-up costs; ~TFM_INS; Pset_PN; Other_Indexes
  - Likely use: stores structured assumptions or mappings used during scenario assembly and model execution.
- **LOSSD**
  - Content cues: Fuel increase during Start-up and Shut-down phase; ~TFM_INS; Pset_PN; Other_Indexes
  - Likely use: stores structured assumptions or mappings used during scenario assembly and model execution.
- **SDTIME**
  - Content cues: Start-up and Shut-down time; ~TFM_INS; Pset_PN; Other_Indexes
  - Likely use: stores structured assumptions or mappings used during scenario assembly and model execution.
- **UPS**
  - Content cues: Ramp up/down rate (%capacity per hour); ~TFM_INS; Pset_PN; Other_Indexes
  - Likely use: stores structured assumptions or mappings used during scenario assembly and model execution.
- **LOSPL**
  - Content cues: proportional increase in specific fuel consumption at the minimum operating level; ~TFM_INS; Pset_PN; Other_Indexes
  - Likely use: stores structured assumptions or mappings used during scenario assembly and model execution.
- **MINLD**
  - Content cues: Minimum Statble load level (% Capacity); ~TFM_INS; Pset_PN; Other_Indexes
  - Likely use: stores structured assumptions or mappings used during scenario assembly and model execution.
- **TIME**
  - Content cues: Minimum up/downtime; ~TFM_INS; Pset_PN; Other_Indexes
  - Likely use: stores structured assumptions or mappings used during scenario assembly and model execution.
- **MAXON**
  - Content cues: Transition Boundary from HOT-WARM-COLD; ~TFM_INS; Pset_PN; Other_Indexes
  - Likely use: stores structured assumptions or mappings used during scenario assembly and model execution.
- **UC_SEM_PLEXOS**
  - Content cues: ~TFM_INS; Pset_PN; Other_Indexes; Attribute
  - Likely use: stores structured assumptions or mappings used during scenario assembly and model execution.
- **Data_SEM_PLEXOS**
  - Content cues: 1; 2; 3; 4
  - Likely use: stores structured assumptions or mappings used during scenario assembly and model execution.

## User constraints and bounds
- No explicit user constraints with process-level mappings were identified in this workbook.

## Notes
- This documentation intentionally describes purpose and functionality without listing spreadsheet cell ranges.
- Naming suggests this file is part of a larger linked input set; keep workbook names and paths stable when integrating updates.
