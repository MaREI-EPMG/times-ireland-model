# Scen_B_TRA_Stock_Retirement.xlsx

## Purpose
This workbook supports the TIMES Ireland model as part of **Transport**. It is used to define, adjust, or parameterize scenario assumptions and model behavior for its domain.

## Functional role in the model workflow
- Serves as an input artifact consumed by the model data-preparation process.
- Encodes structured assumptions that can vary by scenario, policy case, or technology pathway.
- Organizes data so updates can be managed without changing model code.

## Workbook structure
- Total worksheets: **10**
- Worksheets are grouped below by their likely functional theme based on sheet naming and content cues.

### Costs, prices, and economics
- **Taxis**
  - Content cues: Taxis (number); Year of Registration; IE; Carlow
  - Likely use: stores structured assumptions or mappings used during scenario assembly and model execution.

### General input tables
- **Cover**
  - Content cues: TIMES-Ireland Model; Document type:; Scenario; Sector(s):
  - Likely use: stores structured assumptions or mappings used during scenario assembly and model execution.
- **Regions**
  - Content cues: IE; IE-CW; IE-D; IE-KE
  - Likely use: stores structured assumptions or mappings used during scenario assembly and model execution.
- **Buses**
  - Content cues: Buses (number); Year of Registration; IE; Carlow
  - Likely use: stores structured assumptions or mappings used during scenario assembly and model execution.
- **Diesel Cars**
  - Content cues: Private Diesel Cars (number); Year of Registration; IE; Carlow
  - Likely use: stores structured assumptions or mappings used during scenario assembly and model execution.
- **Gasoline Cars**
  - Content cues: Private Gasoline Cars (number); Year of Registration; IE; Carlow
  - Likely use: stores structured assumptions or mappings used during scenario assembly and model execution.
- **Motors**
  - Content cues: Motorcycles (number); Year of Registration; IE; Carlow
  - Likely use: stores structured assumptions or mappings used during scenario assembly and model execution.
- **Stock retirement**
  - Content cues: Vehicle Stock in 2018; TechName; *Unit; Comm-IN
  - Likely use: stores structured assumptions or mappings used during scenario assembly and model execution.
- **Stock_CSO**
  - Content cues: Vehicle population in 2019; Region; Motor; T-TAX-ICE_GSL00
  - Likely use: stores structured assumptions or mappings used during scenario assembly and model execution.

### Technology definitions and performance
- **Goods Vehicle**
  - Content cues: Goods vehicle (number); Year of Registration; IE; Carlow
  - Likely use: stores structured assumptions or mappings used during scenario assembly and model execution.

## User constraints and bounds
- No explicit user constraints with process-level mappings were identified in this workbook.

## Notes
- This documentation intentionally describes purpose and functionality without listing spreadsheet cell ranges.
- Naming suggests this file is part of a larger linked input set; keep workbook names and paths stable when integrating updates.
