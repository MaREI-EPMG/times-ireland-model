# Scen_B_TRA_Emissions.xlsx

## Purpose
This workbook supports the TIMES Ireland model as part of **System and policy assumptions**. It is used to define, adjust, or parameterize scenario assumptions and model behavior for its domain.

## Functional role in the model workflow
- Serves as an input artifact consumed by the model data-preparation process.
- Encodes structured assumptions that can vary by scenario, policy case, or technology pathway.
- Organizes data so updates can be managed without changing model code.

## Workbook structure
- Total worksheets: **3**
- Worksheets are grouped below by their likely functional theme based on sheet naming and content cues.

### Emissions and carbon constraints
- **Emissions**
  - Content cues: Trans - Insert; ~TFM_INS; TimeSlice; LimType
  - Likely use: stores structured assumptions or mappings used during scenario assembly and model execution.

### General input tables
- **Cover**
  - Content cues: TIMES-Ireland Model; Document type:; Scenario; Sector(s):
  - Likely use: stores structured assumptions or mappings used during scenario assembly and model execution.
- **Regions**
  - Content cues: IE; IE-CW; IE-D; IE-KE
  - Likely use: stores structured assumptions or mappings used during scenario assembly and model execution.

## User constraints and bounds
- **Constraint name: TRACO2INT**
  - Attribute(s): FLO_EMIS
  - Source worksheet(s): Emissions
  - Processes limited:
    - T-A*INT*
    - T-NAV*

- **Constraint name: TRACO2N**
  - Attribute(s): FLO_EMIS
  - Source worksheet(s): Emissions
  - Processes limited:
    - -T-A*INT*
    - -T-NAV*
    - FT-TRADST
    - FT-TRAGSL

## Notes
- This documentation intentionally describes purpose and functionality without listing spreadsheet cell ranges.
- Naming suggests this file is part of a larger linked input set; keep workbook names and paths stable when integrating updates.
