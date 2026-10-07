# Scen_B_PWR_CCS.xlsx

## Purpose
This workbook supports the TIMES Ireland model as part of **Power and electricity**. It is used to define, adjust, or parameterize scenario assumptions and model behavior for its domain.

## Functional role in the model workflow
- Serves as an input artifact consumed by the model data-preparation process.
- Encodes structured assumptions that can vary by scenario, policy case, or technology pathway.
- Organizes data so updates can be managed without changing model code.

## Workbook structure
- Total worksheets: **4**
- Worksheets are grouped below by their likely functional theme based on sheet naming and content cues.

### Emissions and carbon constraints
- **FLO_EMIS**
  - Content cues: ~TFM_INS; TimeSlice; LimType; Attribute
  - Likely use: stores structured assumptions or mappings used during scenario assembly and model execution.

### General input tables
- **Cover**
  - Content cues: TIMES-Ireland Model; Document type:; Scenario; Sector(s):
  - Likely use: stores structured assumptions or mappings used during scenario assembly and model execution.
- **Regions**
  - Content cues: IE; National; IE-CW; IE-D
  - Likely use: stores structured assumptions or mappings used during scenario assembly and model execution.
- **UC_CCS**
  - Content cues: UC - Each Region/Period; ~UC_Sets: R_E: IE,National; ~UC_Sets: T_E:; ~UC_T
  - Likely use: stores structured assumptions or mappings used during scenario assembly and model execution.

## User constraints and bounds
- **Constraint name: PWRCO2N**
  - Attribute(s): FLO_EMIS
  - Source worksheet(s): FLO_EMIS
  - Processes limited:
    - P-*CCS*
    - P-TH*CCS*

- **Constraint name: PWRCO2S**
  - Attribute(s): FLO_EMIS
  - Source worksheet(s): FLO_EMIS
  - Processes limited:
    - P-*CCS*
    - P-TH*CCS*

## Notes
- This documentation intentionally describes purpose and functionality without listing spreadsheet cell ranges.
- Naming suggests this file is part of a larger linked input set; keep workbook names and paths stable when integrating updates.
