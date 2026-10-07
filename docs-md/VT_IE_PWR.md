# VT_IE_PWR.xlsx

## Purpose
This workbook supports the TIMES Ireland model as part of **Power and electricity**. It is used to define, adjust, or parameterize scenario assumptions and model behavior for its domain.

## Functional role in the model workflow
- Serves as an input artifact consumed by the model data-preparation process.
- Encodes structured assumptions that can vary by scenario, policy case, or technology pathway.
- Organizes data so updates can be managed without changing model code.

## Workbook structure
- Total worksheets: **16**
- Worksheets are grouped below by their likely functional theme based on sheet naming and content cues.

### Controls and configuration
- **SETUP**
  - Content cues: REGION CODE; REGION DESCRIPTION; SEM Fuel; TIMES Fuel
  - Likely use: stores structured assumptions or mappings used during scenario assembly and model execution.

### Costs, prices, and economics
- **ELC_FuelTech**
  - Content cues: Fuel Techs - Sectoral infrastructure; ~FI_T; ~FI_Process; Region
  - Likely use: stores structured assumptions or mappings used during scenario assembly and model execution.

### General input tables
- **Cover**
  - Content cues: TIMES-Ireland Model; Document type:; Base Year Template; Sector(s):
  - Likely use: stores structured assumptions or mappings used during scenario assembly and model execution.
- **Intro**
  - Content cues: Table of contents; Sheet; Description; SETUP
  - Likely use: stores structured assumptions or mappings used during scenario assembly and model execution.
- **Regions**
  - Content cues: IE; National; IE-CW; IE-D
  - Likely use: stores structured assumptions or mappings used during scenario assembly and model execution.
- **EB2018**
  - Content cues: 2018 Units = ktoe; NACE (Rev 2); Coal; Bituminous Coal
  - Likely use: stores structured assumptions or mappings used during scenario assembly and model execution.
- **CHP_data**
  - Content cues: CHP; Mwe; Max input (2017, PJ); Max output (PJ)
  - Likely use: stores structured assumptions or mappings used during scenario assembly and model execution.
- **SEM**
  - Content cues: Efficiencies are sourced from UCC 2030 EAI Study: Our Zero e_missions future. These are standard clustered average effic; Data Source:SEM-PLEXOS; TIMES ID; Efficiency
  - Likely use: stores structured assumptions or mappings used during scenario assembly and model execution.
- **WRI**
  - Content cues: TIMES Unit ID; country; country_long; name
  - Likely use: stores structured assumptions or mappings used during scenario assembly and model execution.
- **IWEA**
  - Content cues: ID; Wind Farm Name; CODE; County
  - Likely use: stores structured assumptions or mappings used during scenario assembly and model execution.
- **GCS**
  - Content cues: TIMES ID; ID; Fuel Type; Technology Category
  - Likely use: stores structured assumptions or mappings used during scenario assembly and model execution.
- **Heat**
  - Content cues: Unit Name; Max Capacity (MW); Capacity point 1 (MW); Capacity point 2 (MW)
  - Likely use: stores structured assumptions or mappings used during scenario assembly and model execution.
- **Data_Dispatch**
  - Content cues: Source; Manual; SEM; GSC
  - Likely use: stores structured assumptions or mappings used during scenario assembly and model execution.
- **Commodities**
  - Content cues: ~FI_Comm; Csets; Region; CommName
  - Likely use: stores structured assumptions or mappings used during scenario assembly and model execution.
- **Emi**
  - Content cues: Emission - Dynamic coefficients; ~COMEMI; Region; CommName
  - Likely use: stores structured assumptions or mappings used during scenario assembly and model execution.

### Technology definitions and performance
- **Processes**
  - Content cues: Transmission network; ~FI_Process; ~FI_T; Sets
  - Likely use: stores structured assumptions or mappings used during scenario assembly and model execution.

## User constraints and bounds
- No explicit user constraints with process-level mappings were identified in this workbook.

## Notes
- This documentation intentionally describes purpose and functionality without listing spreadsheet cell ranges.
- Naming suggests this file is part of a larger linked input set; keep workbook names and paths stable when integrating updates.
