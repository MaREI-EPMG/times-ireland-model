# SubRES_RSD_NewTechs.xlsx

## Purpose
This workbook supports the TIMES Ireland model as part of **Residential and buildings**. It is used to define, adjust, or parameterize scenario assumptions and model behavior for its domain.

## Functional role in the model workflow
- Serves as an input artifact consumed by the model data-preparation process.
- Encodes structured assumptions that can vary by scenario, policy case, or technology pathway.
- Organizes data so updates can be managed without changing model code.

## Workbook structure
- Total worksheets: **9**
- Worksheets are grouped below by their likely functional theme based on sheet naming and content cues.

### General input tables
- **Cover**
  - Content cues: TIMES-Ireland Model; Document type:; New Technologies; Sector(s):
  - Likely use: stores structured assumptions or mappings used during scenario assembly and model execution.
- **Intro**
  - Content cues: Table of contents; Colour code; Sheet; Description
  - Likely use: stores structured assumptions or mappings used during scenario assembly and model execution.
- **RSD_Building**
  - Content cues: ~FI_T; ASSUMPTIONS ON PRICE FORECAST; TechName; *TechDesc
  - Likely use: stores structured assumptions or mappings used during scenario assembly and model execution.
- **RSD_Heating**
  - Content cues: ~FI_T; TechName; *TechDesc; Comm-IN
  - Likely use: stores structured assumptions or mappings used during scenario assembly and model execution.
- **RSD_Cook+App**
  - Content cues: ~FI_T; TechName; *TechDesc; Comm-IN
  - Likely use: stores structured assumptions or mappings used during scenario assembly and model execution.
- **RSD_Light+Pumps+Fans**
  - Content cues: ~FI_T; TechName; *TechDesc; Comm-IN
  - Likely use: stores structured assumptions or mappings used during scenario assembly and model execution.
- **JRC_Data**
  - Content cues: Heating/Cooling technology database; 100; price indexes; EE
  - Likely use: stores structured assumptions or mappings used during scenario assembly and model execution.
- **DistrictHeating**
  - Content cues: Member State; Excess Heat Available (PJ); Excess Heat Available (TWh); Total
  - Likely use: stores structured assumptions or mappings used during scenario assembly and model execution.

### Technology definitions and performance
- **DanishTechnolgy**
  - Content cues: Danish Technology Data for Heating Installations; Data: https://ens.dk/en/our-services/projections-and-models/technology-data; Building; Name of technology
  - Likely use: stores structured assumptions or mappings used during scenario assembly and model execution.

## User constraints and bounds
- No explicit user constraints with process-level mappings were identified in this workbook.

## Notes
- This documentation intentionally describes purpose and functionality without listing spreadsheet cell ranges.
- Naming suggests this file is part of a larger linked input set; keep workbook names and paths stable when integrating updates.
