# VT_IE_RSD.xlsx

## Purpose
This workbook supports the TIMES Ireland model as part of **Residential and buildings**. It is used to define, adjust, or parameterize scenario assumptions and model behavior for its domain.

## Functional role in the model workflow
- Serves as an input artifact consumed by the model data-preparation process.
- Encodes structured assumptions that can vary by scenario, policy case, or technology pathway.
- Organizes data so updates can be managed without changing model code.

## Workbook structure
- Total worksheets: **19**
- Worksheets are grouped below by their likely functional theme based on sheet naming and content cues.

### Controls and configuration
- **SETUP**
  - Content cues: Automatic Naming Convention; ( * = 0PJ, ie. unused commodity in BY ); TIMES; Description
  - Likely use: stores structured assumptions or mappings used during scenario assembly and model execution.

### Costs, prices, and economics
- **Fuel-Age_Adj**
  - Content cues: Summary without Fuels; E1055:; E1008; BER Database (Fuel-Age)
  - Likely use: stores structured assumptions or mappings used during scenario assembly and model execution.
- **Sector_Fuels**
  - Content cues: ~FI_T; ~FI_Process; Region; TechName
  - Likely use: stores structured assumptions or mappings used during scenario assembly and model execution.

### Demand and activity assumptions
- **ArchetypeDemand**
  - Content cues: Input data for TIMES-Ireland; Heating Energy; ~FI_T; SH Calibration
  - Likely use: stores structured assumptions or mappings used during scenario assembly and model execution.
- **Non-ArchetypeDemand**
  - Content cues: Cooking & Appliances; ~FI_T; ~FI_Process; Region
  - Likely use: stores structured assumptions or mappings used during scenario assembly and model execution.

### Emissions and carbon constraints
- **EMIS**
  - Content cues: Emission coefficients per unit of fuel consumed in the residential sector; ~COMEMI; Region; CommName
  - Likely use: stores structured assumptions or mappings used during scenario assembly and model execution.

### General input tables
- **Cover**
  - Content cues: TIMES-Ireland Model; Document type:; Base Year Template; Sector(s):
  - Likely use: stores structured assumptions or mappings used during scenario assembly and model execution.
- **Intro**
  - Content cues: Table of contents; Colour code; Sheet; Description
  - Likely use: stores structured assumptions or mappings used during scenario assembly and model execution.
- **Regions**
  - Content cues: IE; National; IE-CW; IE-D
  - Likely use: stores structured assumptions or mappings used during scenario assembly and model execution.
- **EB2018**
  - Content cues: 2018 Units = ktoe; NACE (Rev 2); Coal; Bituminous Coal
  - Likely use: stores structured assumptions or mappings used during scenario assembly and model execution.
- **RSD_Balance**
  - Content cues: ~Country; IE; SMF - Components; SHARE
  - Likely use: stores structured assumptions or mappings used during scenario assembly and model execution.
- **COMM**
  - Content cues: Commodities; ~FI_COMM; Csets; Region
  - Likely use: stores structured assumptions or mappings used during scenario assembly and model execution.
- **DwellingStocks**
  - Content cues: SEAI BER Database 2018 (filtered outliners as per M.Howley & corrected based on Census 2016, CSO); EnergyRating (group); DwellingTypeDescr -3 types; ApertureArea
  - Likely use: stores structured assumptions or mappings used during scenario assembly and model execution.
- **SHWLP-Apt**
  - Content cues: Apartment Heating, Lighting & Pumps&Fans; Input data for TIMES-Ireland; 1 kWh; 3.6E-9
  - Likely use: stores structured assumptions or mappings used during scenario assembly and model execution.
- **SHWLP-Att**
  - Content cues: Attached Heating, Lighting & Pumps&Fans; Input data for TIMES-Ireland; 1 kWh; 3.6E-9
  - Likely use: stores structured assumptions or mappings used during scenario assembly and model execution.
- **SHWLP-Det**
  - Content cues: Detached Heating, Lighting & Pumps&Fans; Input data for TIMES-Ireland; 1 kWh; 3.6E-9
  - Likely use: stores structured assumptions or mappings used during scenario assembly and model execution.
- **ApartmentEnergyData**
  - Content cues: Apartment -Energy Services Demand Data from SEAI BER Public Database and aggregated via Tableau; *ADDED; CountyName (group); EnergyRating (group)
  - Likely use: stores structured assumptions or mappings used during scenario assembly and model execution.
- **AttachedEnergyData**
  - Content cues: Attached -Energy Services Demand Data from SEAI BER Public Database and aggregated via Tableau; DwellingTypeDescr -3 types; *ADDED; Attached
  - Likely use: stores structured assumptions or mappings used during scenario assembly and model execution.
- **DettachedEnergyData**
  - Content cues: Dettached -Energy Services Demand Data from SEAI BER Public Database and aggregated via Tableau; DwellingTypeDescr -3 types; *ADDED; Detached
  - Likely use: stores structured assumptions or mappings used during scenario assembly and model execution.

## User constraints and bounds
- No explicit user constraints with process-level mappings were identified in this workbook.

## Notes
- This documentation intentionally describes purpose and functionality without listing spreadsheet cell ranges.
- Naming suggests this file is part of a larger linked input set; keep workbook names and paths stable when integrating updates.
