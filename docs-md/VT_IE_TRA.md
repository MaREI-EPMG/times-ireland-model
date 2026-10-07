# VT_IE_TRA.xlsx

## Purpose
This workbook supports the TIMES Ireland model as part of **Transport**. It is used to define, adjust, or parameterize scenario assumptions and model behavior for its domain.

## Functional role in the model workflow
- Serves as an input artifact consumed by the model data-preparation process.
- Encodes structured assumptions that can vary by scenario, policy case, or technology pathway.
- Organizes data so updates can be managed without changing model code.

## Workbook structure
- Total worksheets: **14**
- Worksheets are grouped below by their likely functional theme based on sheet naming and content cues.

### Demand and activity assumptions
- **Demands**
  - Content cues: ~FI_T: Demand; CommName; *Unit; IE
  - Likely use: stores structured assumptions or mappings used during scenario assembly and model execution.

### General input tables
- **Cover**
  - Content cues: TIMES-Ireland Model; Document type:; Base Year Template; Sector(s):
  - Likely use: stores structured assumptions or mappings used during scenario assembly and model execution.
- **Intro**
  - Content cues: Table of contents; Sheet; Description; EB2018
  - Likely use: stores structured assumptions or mappings used during scenario assembly and model execution.
- **EB2018**
  - Content cues: 2018 Units = ktoe; NACE (Rev 2); Coal; Bituminous Coal
  - Likely use: stores structured assumptions or mappings used during scenario assembly and model execution.
- **Regions**
  - Content cues: IE; IE-CW; IE-D; IE-KE
  - Likely use: stores structured assumptions or mappings used during scenario assembly and model execution.
- **Commodities**
  - Content cues: Commodities; ~FI_Comm; Csets; Region
  - Likely use: stores structured assumptions or mappings used during scenario assembly and model execution.
- **FT**
  - Content cues: ~FI_T; Region; TechName; Comm-IN
  - Likely use: stores structured assumptions or mappings used during scenario assembly and model execution.
- **Stock**
  - Content cues: Passenger; Freight; ~FI_T: Stock~2018; Total available supply (Bpkm)
  - Likely use: stores structured assumptions or mappings used during scenario assembly and model execution.
- **ACT2FLO**
  - Content cues: Vehicle occupancy (passenger/tonnage per vehicle); ~FI_T: ACTFLO~2018; TechName; CommGrp
  - Likely use: stores structured assumptions or mappings used during scenario assembly and model execution.
- **Efficiency**
  - Content cues: TechName; *Unit; Attribute; IE
  - Likely use: stores structured assumptions or mappings used during scenario assembly and model execution.
- **AF**
  - Content cues: ~FI_T: AF~2018; TechName; *Unit; IE
  - Likely use: stores structured assumptions or mappings used during scenario assembly and model execution.
- **On-Road Fac.**
  - Content cues: On-road factor; Diesel; Petrol; All vehicle
  - Likely use: stores structured assumptions or mappings used during scenario assembly and model execution.
- **Conversions**
  - Content cues: Conversion factors - Energy; 1 ktoe; =; 4.1868000000000002E-2
  - Likely use: stores structured assumptions or mappings used during scenario assembly and model execution.

### Technology definitions and performance
- **Processes**
  - Content cues: ~FI_Process; Sets; Region; TechName
  - Likely use: stores structured assumptions or mappings used during scenario assembly and model execution.

## User constraints and bounds
- No explicit user constraints with process-level mappings were identified in this workbook.

## Notes
- This documentation intentionally describes purpose and functionality without listing spreadsheet cell ranges.
- Naming suggests this file is part of a larger linked input set; keep workbook names and paths stable when integrating updates.
