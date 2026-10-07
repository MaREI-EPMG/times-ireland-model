# VT_IE_SUP.xlsx

## Purpose
This workbook supports the TIMES Ireland model as part of **Supply and fuels**. It is used to define, adjust, or parameterize scenario assumptions and model behavior for its domain.

## Functional role in the model workflow
- Serves as an input artifact consumed by the model data-preparation process.
- Encodes structured assumptions that can vary by scenario, policy case, or technology pathway.
- Organizes data so updates can be managed without changing model code.

## Workbook structure
- Total worksheets: **17**
- Worksheets are grouped below by their likely functional theme based on sheet naming and content cues.

### Costs, prices, and economics
- **SUP_FuelTech**
  - Content cues: Fuel Techs - Sectoral infrastructure; ~FI_T; Region; TechName
  - Likely use: stores structured assumptions or mappings used during scenario assembly and model execution.

### Emissions and carbon constraints
- **Import CO2**
  - Content cues: ~FI_Process; Sets; Region; TechName
  - Likely use: stores structured assumptions or mappings used during scenario assembly and model execution.

### General input tables
- **Cover**
  - Content cues: TIMES-Ireland Model; Document type:; Base Year Template; Sector(s):
  - Likely use: stores structured assumptions or mappings used during scenario assembly and model execution.
- **Regions**
  - Content cues: IE; National; IE-CW; IE-D
  - Likely use: stores structured assumptions or mappings used during scenario assembly and model execution.
- **EB2018**
  - Content cues: 2018 Units = ktoe; NACE (Rev 2); Coal; Bituminous Coal
  - Likely use: stores structured assumptions or mappings used during scenario assembly and model execution.
- **CONVENTIONS**
  - Content cues: Energy Commodities; Technologies - Convention for Naming; .; Emission Commodities
  - Likely use: stores structured assumptions or mappings used during scenario assembly and model execution.
- **Commodities**
  - Content cues: ~FI_Comm; Csets; CommName; CommDesc
  - Likely use: stores structured assumptions or mappings used during scenario assembly and model execution.
- **Domestic**
  - Content cues: Domestic fossil fuels reserves; ~FI_T: MEUR2000; Region; TechName
  - Likely use: stores structured assumptions or mappings used during scenario assembly and model execution.
- **Refinery**
  - Content cues: Base-year Flexible Refinery; ~FI_T: MEUR2000; Region; TechName
  - Likely use: stores structured assumptions or mappings used during scenario assembly and model execution.
- **Interconnector**
  - Content cues: Electricity Interconnector; ~FI_T: MEUR2014; Region; TechName
  - Likely use: stores structured assumptions or mappings used during scenario assembly and model execution.
- **Emi**
  - Content cues: Emission - Dynamic coefficients; ~COMEMI; CommName; SUPNGA
  - Likely use: stores structured assumptions or mappings used during scenario assembly and model execution.
- **Conversions**
  - Content cues: Conversion factors - Energy; 1 ktoe; =; 4.1868000000000002E-2
  - Likely use: stores structured assumptions or mappings used during scenario assembly and model execution.

### Supply, resources, and trade
- **Imports_Fossil**
  - Content cues: Fossil Fuels Import Prices; ~FI_T: IRE_PRICE; Region; TechName
  - Likely use: stores structured assumptions or mappings used during scenario assembly and model execution.
- **Imports_Bio**
  - Content cues: Imported Bioenergy costs (€/GJ); ~FI_T: MEUR2010; Region; TechName
  - Likely use: stores structured assumptions or mappings used during scenario assembly and model execution.
- **Domestic_Bio**
  - Content cues: Domestic Bioenergy; ~FI_T; Region; TechName
  - Likely use: stores structured assumptions or mappings used during scenario assembly and model execution.
- **SEAI-AEA_BioData**
  - Content cues: Source:; SEAI-AEA, Bioenergy Supply Curves for Ireland 2010 – 2030. October 2012, version 1.0; Conversion; Consumer Price Index (CPI) - CSO
  - Likely use: stores structured assumptions or mappings used during scenario assembly and model execution.

### Technology definitions and performance
- **Processes**
  - Content cues: Processes definition; ~FI_Process; Sets; Region
  - Likely use: stores structured assumptions or mappings used during scenario assembly and model execution.

## User constraints and bounds
- No explicit user constraints with process-level mappings were identified in this workbook.

## Notes
- This documentation intentionally describes purpose and functionality without listing spreadsheet cell ranges.
- Naming suggests this file is part of a larger linked input set; keep workbook names and paths stable when integrating updates.
