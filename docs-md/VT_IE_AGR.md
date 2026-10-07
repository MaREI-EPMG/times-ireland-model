# VT_IE_AGR.xlsx

## Purpose
This workbook supports the TIMES Ireland model as part of **Agriculture and land use**. It is used to define, adjust, or parameterize scenario assumptions and model behavior for its domain.

## Functional role in the model workflow
- Serves as an input artifact consumed by the model data-preparation process.
- Encodes structured assumptions that can vary by scenario, policy case, or technology pathway.
- Organizes data so updates can be managed without changing model code.

## Workbook structure
- Total worksheets: **17**
- Worksheets are grouped below by their likely functional theme based on sheet naming and content cues.

### Costs, prices, and economics
- **AGR_FuelTech**
  - Content cues: Fuel Techs - Sectoral infrastructure; ~FI_T; ~FI_Process; Region
  - Likely use: stores structured assumptions or mappings used during scenario assembly and model execution.

### Demand and activity assumptions
- **AGR_Demands**
  - Content cues: ~FI_T:COM_PROJ~2018; CommName; IE; National
  - Likely use: stores structured assumptions or mappings used during scenario assembly and model execution.
- **Demands**
  - Content cues: Process; Type; Demands; Unit
  - Likely use: stores structured assumptions or mappings used during scenario assembly and model execution.

### General input tables
- **Cover**
  - Content cues: TIMES-Ireland Model; Document type:; Base Year Template; Sector(s):
  - Likely use: stores structured assumptions or mappings used during scenario assembly and model execution.
- **Regions**
  - Content cues: IE; National; IE-CW; IE-D
  - Likely use: stores structured assumptions or mappings used during scenario assembly and model execution.
- **Commodities**
  - Content cues: ~FI_Comm; CSet; Region; CommName
  - Likely use: stores structured assumptions or mappings used during scenario assembly and model execution.
- **Emi**
  - Content cues: Emission - Dynamic coefficients; ~COMEMI; Region; CommName
  - Likely use: stores structured assumptions or mappings used during scenario assembly and model execution.
- **AGR_BY-Livestock**
  - Content cues: ~FI_T: MEUR2000; Region; TechName; *TechDesc
  - Likely use: stores structured assumptions or mappings used during scenario assembly and model execution.
- **AGR_New-Livestock**
  - Content cues: ~FI_T: MEUR2000; Region; TechName; *TechDesc
  - Likely use: stores structured assumptions or mappings used during scenario assembly and model execution.
- **AGR_Tillage**
  - Content cues: ~FI_T: MEUR2000; Region; TechName; *TechDesc
  - Likely use: stores structured assumptions or mappings used during scenario assembly and model execution.
- **AGR_Energy**
  - Content cues: ~FI_T: MEUR2000; Region; TechName; *TechDesc
  - Likely use: stores structured assumptions or mappings used during scenario assembly and model execution.
- **RES**
  - Content cues: `; PASCAT1; ADCAT (Milk); [Mha]
  - Likely use: stores structured assumptions or mappings used during scenario assembly and model execution.

### Supply, resources, and trade
- **AGR_Bioenergy**
  - Content cues: ~FI_T: MEUR2000; Region; TechName; *TechDesc
  - Likely use: stores structured assumptions or mappings used during scenario assembly and model execution.

### Technology definitions and performance
- **Processes**
  - Content cues: ~FI_Process; Sets; Region; TechName
  - Likely use: stores structured assumptions or mappings used during scenario assembly and model execution.
- **BY-Techs**
  - Content cues: Sector; Process; Type; TIMES Code
  - Likely use: stores structured assumptions or mappings used during scenario assembly and model execution.
- **New-Techs**
  - Content cues: Sector; Process; Type; TIMES Code
  - Likely use: stores structured assumptions or mappings used during scenario assembly and model execution.
- **BIO-Techs**
  - Content cues: Sector; Process; Type; TIMES Code
  - Likely use: stores structured assumptions or mappings used during scenario assembly and model execution.

## User constraints and bounds
- No explicit user constraints with process-level mappings were identified in this workbook.

## Notes
- This documentation intentionally describes purpose and functionality without listing spreadsheet cell ranges.
- Naming suggests this file is part of a larger linked input set; keep workbook names and paths stable when integrating updates.
