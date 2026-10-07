# Scen_B_TRA_F_ModalShares.xlsx

## Purpose
This workbook supports the TIMES Ireland model as part of **Transport**. It is used to define, adjust, or parameterize scenario assumptions and model behavior for its domain.

## Functional role in the model workflow
- Serves as an input artifact consumed by the model data-preparation process.
- Encodes structured assumptions that can vary by scenario, policy case, or technology pathway.
- Organizes data so updates can be managed without changing model code.

## Workbook structure
- Total worksheets: **3**
- Worksheets are grouped below by their likely functional theme based on sheet naming and content cues.

### General input tables
- **Cover**
  - Content cues: TIMES-Ireland Model; Document type:; Scenario; Sector(s):
  - Likely use: stores structured assumptions or mappings used during scenario assembly and model execution.
- **Regions**
  - Content cues: IE; National; IE-CW; IE-D
  - Likely use: stores structured assumptions or mappings used during scenario assembly and model execution.
- **UC_ModalShares**
  - Content cues: User constraints for Goods Vehicles; UC - Each Region/Period; ~UC_Sets: R_E:AllRegions; ~UC_Sets: T_E:
  - Likely use: stores structured assumptions or mappings used during scenario assembly and model execution.

## User constraints and bounds
- **Constraint name: 1140**
  - Source worksheet(s): UC_ModalShares
  - Processes limited:
    - 5 - 10 tonnes

- **Constraint name: 292**
  - Source worksheet(s): UC_ModalShares
  - Processes limited:
    - 0 - 5 tonnes

- **Constraint name: TRAF**
  - Source worksheet(s): UC_ModalShares
  - Processes limited:
    - T-GTR*
    - T-HGT*
    - T-LGT*
    - T-MGT*

## Notes
- This documentation intentionally describes purpose and functionality without listing spreadsheet cell ranges.
- Naming suggests this file is part of a larger linked input set; keep workbook names and paths stable when integrating updates.
