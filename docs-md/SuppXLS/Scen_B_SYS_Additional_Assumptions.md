# Scen_B_SYS_Additional_Assumptions.xlsx

## Purpose
This workbook supports the TIMES Ireland model as part of **System and policy assumptions**. It is used to define, adjust, or parameterize scenario assumptions and model behavior for its domain.

## Functional role in the model workflow
- Serves as an input artifact consumed by the model data-preparation process.
- Encodes structured assumptions that can vary by scenario, policy case, or technology pathway.
- Organizes data so updates can be managed without changing model code.

## Workbook structure
- Total worksheets: **8**
- Worksheets are grouped below by their likely functional theme based on sheet naming and content cues.

### General input tables
- **Cover**
  - Content cues: TIMES-Ireland Model; Document type:; Scenario; Sector(s):
  - Likely use: stores structured assumptions or mappings used during scenario assembly and model execution.
- **Regions**
  - Content cues: IE; National; IE-CW; IE-D
  - Likely use: stores structured assumptions or mappings used during scenario assembly and model execution.
- **PWR**
  - Content cues: ~UC_Sets: R_E:; ~UC_Sets: T_E:; ~UC_T; UC_N
  - Likely use: stores structured assumptions or mappings used during scenario assembly and model execution.
- **SYS**
  - Content cues: ~TFM_UPD; TimeSlice; LimType; Attribute
  - Likely use: stores structured assumptions or mappings used during scenario assembly and model execution.
- **RSD**
  - Content cues: ~UC_Sets: R_E:; ~UC_Sets: T_E:; ~UC_T; UC_N
  - Likely use: stores structured assumptions or mappings used during scenario assembly and model execution.
- **SUP**
  - Content cues: UC - Each Region/Period; ~UC_Sets: R_E: IE,National; ~UC_Sets: T_E:; ~UC_T
  - Likely use: stores structured assumptions or mappings used during scenario assembly and model execution.
- **SRV**
  - Content cues: ~TFM_INS; TimeSlice; LimType; Attribute
  - Likely use: stores structured assumptions or mappings used during scenario assembly and model execution.
- **TRA**
  - Content cues: ~TFM_UPD; TimeSlice; LimType; Attribute
  - Likely use: stores structured assumptions or mappings used during scenario assembly and model execution.

## User constraints and bounds
- **Constraint name: ***
  - Source worksheet(s): PWR
  - Processes limited:
    - *

- **Constraint name: ELCC**
  - Source worksheet(s): SUP
  - Processes limited:
    - EXPELC*
    - IMPELC*

- **Constraint name: RSDGAS**
  - Source worksheet(s): RSD
  - Processes limited:
    - FT-RSDGAS

- **Constraint name: RSDKER**
  - Source worksheet(s): RSD
  - Processes limited:
    - FT-RSDKER

## Notes
- This documentation intentionally describes purpose and functionality without listing spreadsheet cell ranges.
- Naming suggests this file is part of a larger linked input set; keep workbook names and paths stable when integrating updates.
