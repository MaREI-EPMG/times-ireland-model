# Scen_PWR_High_RNW.xlsx

## Purpose
This workbook supports the TIMES Ireland model as part of **Power and electricity**. It is used to define, adjust, or parameterize scenario assumptions and model behavior for its domain.

## Functional role in the model workflow
- Serves as an input artifact consumed by the model data-preparation process.
- Encodes structured assumptions that can vary by scenario, policy case, or technology pathway.
- Organizes data so updates can be managed without changing model code.

## Workbook structure
- Total worksheets: **4**
- Worksheets are grouped below by their likely functional theme based on sheet naming and content cues.

### General input tables
- **Regions**
  - Content cues: IE; National; IE-CW; IE-D
  - Likely use: stores structured assumptions or mappings used during scenario assembly and model execution.
- **Onshore**
  - Content cues: UC - Each Region/Period; ~UC_Sets: R_E: IE,National; ~UC_Sets: T_E:; ~UC_T
  - Likely use: stores structured assumptions or mappings used during scenario assembly and model execution.
- **Offshore**
  - Content cues: UC - Each Region/Period; ~UC_Sets: R_E: IE,National; ~UC_Sets: T_E:; ~UC_T
  - Likely use: stores structured assumptions or mappings used during scenario assembly and model execution.
- **Solar**
  - Content cues: UC - Each Region/Period; UC_N; Pset_Set; Pset_PN
  - Likely use: stores structured assumptions or mappings used during scenario assembly and model execution.

## User constraints and bounds
- **Constraint name: ELCC**
  - Source worksheet(s): Solar
  - Processes limited:
    - P-RNW-SOL*

- **Constraint name: FX**
  - Attribute(s): 1
  - Source worksheet(s): Solar
  - Processes limited:
    - P*SOL-PV*

- **Constraint name: LO**
  - Attribute(s): 1
  - Source worksheet(s): Solar
  - Processes limited:
    - P*SOL-PV*

- **Constraint name: UC_Max_PV_Cap**
  - Attribute(s): UC_RHSRTS
  - Bound fields: 2030, 2040
  - Bound value range(s): 2030 (16.8 to 16.8), 2040 (18 to 18)
  - Source worksheet(s): Solar
  - Processes limited:
    - P*SOL-PV*

- **Constraint name: UP**
  - Attribute(s): 1
  - Source worksheet(s): Solar
  - Processes limited:
    - P*SOL-PV*

## Notes
- This documentation intentionally describes purpose and functionality without listing spreadsheet cell ranges.
- Naming suggests this file is part of a larger linked input set; keep workbook names and paths stable when integrating updates.
