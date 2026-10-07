# VT_IE_SRV.xlsx

## Purpose
This workbook supports the TIMES Ireland model as part of **Services and commercial buildings**. It is used to define, adjust, or parameterize scenario assumptions and model behavior for its domain.

## Functional role in the model workflow
- Serves as an input artifact consumed by the model data-preparation process.
- Encodes structured assumptions that can vary by scenario, policy case, or technology pathway.
- Organizes data so updates can be managed without changing model code.

## Workbook structure
- Total worksheets: **17**
- Worksheets are grouped below by their likely functional theme based on sheet naming and content cues.

### Costs, prices, and economics
- **Fuel Techs**
  - Content cues: Fuel Techs/Distribution Infrastructure; ~FI_T; ~FI_Process; TechName
  - Likely use: stores structured assumptions or mappings used during scenario assembly and model execution.

### Emissions and carbon constraints
- **Emissions**
  - Content cues: Emission coefficients for Non-Residential sector; ~COMEMI; CommName; SRVCOA
  - Likely use: stores structured assumptions or mappings used during scenario assembly and model execution.

### General input tables
- **Cover**
  - Content cues: TIMES-Ireland Model; Document type:; Base Year Template; Sector(s):
  - Likely use: stores structured assumptions or mappings used during scenario assembly and model execution.
- **Legend**
  - Content cues: Ragion:; Ireland; IE; Sector:
  - Likely use: stores structured assumptions or mappings used during scenario assembly and model execution.
- **Regions**
  - Content cues: IE; National; IE-CW; IE-D
  - Likely use: stores structured assumptions or mappings used during scenario assembly and model execution.
- **EB_SRV**
  - Content cues: Energy Balance breakdown; Table 1; Energy Balance 2018 (ktoe); Coal
  - Likely use: stores structured assumptions or mappings used during scenario assembly and model execution.
- **Key Inputs**
  - Content cues: Key input assumptions and elaborations; Building stock; Source; Unit
  - Likely use: stores structured assumptions or mappings used during scenario assembly and model execution.
- **Commodities**
  - Content cues: Commodities definition; ~FI_Comm; Csets; Region
  - Likely use: stores structured assumptions or mappings used during scenario assembly and model execution.
- **Building stock**
  - Content cues: Characterization of Building stocks; ~FI_T; ~FI_Process; TechName
  - Likely use: stores structured assumptions or mappings used during scenario assembly and model execution.
- **EB2018**
  - Content cues: 2018 Units = ktoe; NACE (Rev 2); Coal; Bituminous Coal
  - Likely use: stores structured assumptions or mappings used during scenario assembly and model execution.
- **CSO data**
  - Content cues: Table 10 Average Floor Area by Type of Building and County (Non-Domestic) 2009-2018; Source: CSO; https://www.cso.ie/en/releasesandpublications/er/ndber/non-domesticbuildingenergyratingsq42018/; m2
  - Likely use: stores structured assumptions or mappings used during scenario assembly and model execution.
- **Public SEAI**
  - Content cues: Source:; SEAI Public Sector Annual Report 2019; URL:; https://www.seai.ie/publications/Public-Sector-Annual-Report-2019.pdf
  - Likely use: stores structured assumptions or mappings used during scenario assembly and model execution.

### Technology definitions and performance
- **TH_Techs**
  - Content cues: Characterization of thermal energy services; ~FI_T; ~FI_Process; Region
  - Likely use: stores structured assumptions or mappings used during scenario assembly and model execution.
- **CK_Techs**
  - Content cues: Characterization of Cooking technologies; ~FI_T; ~FI_Process; TechName
  - Likely use: stores structured assumptions or mappings used during scenario assembly and model execution.
- **EAP_Techs**
  - Content cues: Characterization of Electric appliances; ~FI_T; ~FI_Process; TechName
  - Likely use: stores structured assumptions or mappings used during scenario assembly and model execution.
- **PLIG_Techs**
  - Content cues: Characterization of Public lighting; ~FI_T; ~FI_Process; TechName
  - Likely use: stores structured assumptions or mappings used during scenario assembly and model execution.
- **DCE_Techs**
  - Content cues: Characterization of Data centers; ~FI_T; ~FI_Process; TechName
  - Likely use: stores structured assumptions or mappings used during scenario assembly and model execution.

## User constraints and bounds
- No explicit user constraints with process-level mappings were identified in this workbook.

## Notes
- This documentation intentionally describes purpose and functionality without listing spreadsheet cell ranges.
- Naming suggests this file is part of a larger linked input set; keep workbook names and paths stable when integrating updates.
