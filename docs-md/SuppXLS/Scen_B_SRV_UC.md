# Scen_B_SRV_UC.xlsx

## Purpose
This workbook supports the TIMES Ireland model as part of **Services and commercial buildings**. It is used to define, adjust, or parameterize scenario assumptions and model behavior for its domain.

## Functional role in the model workflow
- Serves as an input artifact consumed by the model data-preparation process.
- Encodes structured assumptions that can vary by scenario, policy case, or technology pathway.
- Organizes data so updates can be managed without changing model code.

## Workbook structure
- Total worksheets: **5**
- Worksheets are grouped below by their likely functional theme based on sheet naming and content cues.

### General input tables
- **Cover**
  - Content cues: TIMES-Ireland Model; Document type:; Scenario; Sector(s):
  - Likely use: stores structured assumptions or mappings used during scenario assembly and model execution.
- **Legend**
  - Content cues: TIMES-Ireland Model (TIM); Document type:; Scenario file on User Constraints; Sector:
  - Likely use: stores structured assumptions or mappings used during scenario assembly and model execution.
- **Ambient Heat**
  - Content cues: Input to control ambient heat per unit of heat produced; ~TFM_INS-TS; PSET_PN; Attribute
  - Likely use: stores structured assumptions or mappings used during scenario assembly and model execution.
- **FillData**
  - Content cues: ~TFM_Fill-R: w=COP; Hcol=Region; Scenario; LimType; Attribute
  - Likely use: stores structured assumptions or mappings used during scenario assembly and model execution.
- **COP**
  - Content cues: scenario; attribute; process; commodity
  - Likely use: stores structured assumptions or mappings used during scenario assembly and model execution.

## User constraints and bounds
- **Constraint name: SRVAHT**
  - Attribute(s): FLO_SHAR
  - Bound fields: 2018, 2030, 2040, 2050
  - Bound value range(s): 2018 (0.0225624 to 0.5671), 2030 (0.148683 to 0.642857), 2040 (0.175287 to 0.68254), 2050 (0.175287 to 0.68254)
  - Source worksheet(s): Ambient Heat
  - Processes limited:
    - S-SH-CS_ELC_N2
    - S-SH-CS_ELC_N3
    - S-SH-CS_ELC_N4
    - S-SH-CS_ELC_N5
    - S-SH-CS_ELC_N6
    - S-SH-CS_ELC_N7
    - S-SH-CS_ELC_N8
    - S-SH-CS_ELC_N9
    - S-SH-CS_GAS_N5
    - S-SH-CS_GAS_N6
    - S-SH-PU_ELC_N2
    - S-SH-PU_ELC_N3
    - S-SH-PU_ELC_N4
    - S-SH-PU_ELC_N5
    - S-SH-PU_ELC_N6
    - S-SH-PU_ELC_N7
    - S-SH-PU_ELC_N8
    - S-SH-PU_ELC_N9
    - S-SH-PU_GAS_N5
    - S-SH-PU_GAS_N6

- **Constraint name: SRVAHT2**
  - Attribute(s): FLO_SHAR
  - Bound fields: 2018, 2030, 2040, 2050
  - Bound value range(s): 2018 (0 to 0.65618), 2030 (0 to 0.677596), 2040 (0 to 0.690785), 2050 (0 to 0.690785)
  - Source worksheet(s): Ambient Heat
  - Processes limited:
    - S-SH-CS_ELC_N5
    - S-SH-CS_ELC_N6
    - S-SH-CS_GAS_N5
    - S-SH-CS_GAS_N6
    - S-SH-PU_ELC_N5
    - S-SH-PU_ELC_N6
    - S-SH-PU_GAS_N5
    - S-SH-PU_GAS_N6


## Notes
- This documentation intentionally describes purpose and functionality without listing spreadsheet cell ranges.
- Naming suggests this file is part of a larger linked input set; keep workbook names and paths stable when integrating updates.
