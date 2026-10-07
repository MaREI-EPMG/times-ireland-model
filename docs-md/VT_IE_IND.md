# VT_IE_IND.xlsx

## Purpose
This workbook supports the TIMES Ireland model as part of **Industry**. It is used to define, adjust, or parameterize scenario assumptions and model behavior for its domain.

## Functional role in the model workflow
- Serves as an input artifact consumed by the model data-preparation process.
- Encodes structured assumptions that can vary by scenario, policy case, or technology pathway.
- Organizes data so updates can be managed without changing model code.

## Workbook structure
- Total worksheets: **15**
- Worksheets are grouped below by their likely functional theme based on sheet naming and content cues.

### Demand and activity assumptions
- **Demands**
  - Content cues: ~FI_T:COM_PROJ~2018; CommName; IE; National
  - Likely use: stores structured assumptions or mappings used during scenario assembly and model execution.

### General input tables
- **Cover**
  - Content cues: TIMES-Ireland Model; Document type:; Base Year Template; Sector(s):
  - Likely use: stores structured assumptions or mappings used during scenario assembly and model execution.
- **Regions**
  - Content cues: IE; National; IE-CW; IE-D
  - Likely use: stores structured assumptions or mappings used during scenario assembly and model execution.
- **Commodities**
  - Content cues: ~FI_Comm; Csets; Region; CommName
  - Likely use: stores structured assumptions or mappings used during scenario assembly and model execution.
- **FT**
  - Content cues: ~FI_T; Region; TechName; *TechDesc
  - Likely use: stores structured assumptions or mappings used during scenario assembly and model execution.
- **DMD**
  - Content cues: ~FI_T; Region; TechName; *TechDesc
  - Likely use: stores structured assumptions or mappings used during scenario assembly and model execution.
- **EMI**
  - Content cues: ~COMEMI; Region; CommName; INDCOA
  - Likely use: stores structured assumptions or mappings used during scenario assembly and model execution.
- **NRG_shares**
  - Content cues: This sheet is used to calculate fuel shares in generating different heat levels in industry by specific subsectors; Heating demand, National Heat Study, SEAI; Subsector; Building type
  - Likely use: stores structured assumptions or mappings used during scenario assembly and model execution.
- **Conversions**
  - Content cues: Conversion factors; 1 ktoe; 4.1868000000000002E-2; PJ
  - Likely use: stores structured assumptions or mappings used during scenario assembly and model execution.
- **EB2018**
  - Content cues: 2018 Units = ktoe; NACE (Rev 2); Coal; Bituminous Coal
  - Likely use: stores structured assumptions or mappings used during scenario assembly and model execution.
- **EB2019**
  - Content cues: 2019 Units = ktoe; NACE (Rev 2); Coal; Bituminous Coal
  - Likely use: stores structured assumptions or mappings used during scenario assembly and model execution.
- **EB2020**
  - Content cues: 2020 Units = ktoe; NACE (Rev 2); Coal; Bituminous Coal
  - Likely use: stores structured assumptions or mappings used during scenario assembly and model execution.
- **EB2021**
  - Content cues: 2021 Units = ktoe; NACE (Rev 2); Coal; Bituminous Coal
  - Likely use: stores structured assumptions or mappings used during scenario assembly and model execution.

### Technology definitions and performance
- **Processes**
  - Content cues: ~FI_Process; Sets; Region; TechName
  - Likely use: stores structured assumptions or mappings used during scenario assembly and model execution.
- **Techs**
  - Content cues: Empty column; For definition of processes and commoditites; ~FI_T; TechName
  - Likely use: stores structured assumptions or mappings used during scenario assembly and model execution.

## User constraints and bounds
- **Constraint name: INDCO2N**
  - Attribute(s): FLO_EMIS
  - Bound fields: allregions
  - Bound value range(s): allregions (56.9 to 116.7)
  - Source worksheet(s): EMI
  - Processes limited:
    - I*

- **Constraint name: INDCO2P**
  - Attribute(s): ENV_ACT
  - Bound fields: allregions
  - Bound value range(s): allregions (197.872 to 197.872)
  - Source worksheet(s): EMI
  - Processes limited:
    - I-DMD-CEM-E0

## Notes
- This documentation intentionally describes purpose and functionality without listing spreadsheet cell ranges.
- Naming suggests this file is part of a larger linked input set; keep workbook names and paths stable when integrating updates.
