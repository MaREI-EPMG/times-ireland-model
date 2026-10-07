# Scen_B_SUP_DomBioPot_SEAI.xlsx

## Purpose
This workbook supports the TIMES Ireland model as part of **Supply and fuels**. It is used to define, adjust, or parameterize scenario assumptions and model behavior for its domain.

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
- **SEAI**
  - Content cues: Source: SEAI, 2022. https://www.seai.ie/data-and-insights/national-heat-study/sustainable-bioenergy-for/; Worksheet Title: Resource availability data; Availability and price for resources where availability (Note: Does not change by scenario within the heat study); Bioenergy
  - Likely use: stores structured assumptions or mappings used during scenario assembly and model execution.
- **Conversions**
  - Content cues: ktoe to PJ; 4.1868000000000002E-2; toe to GJ; 41.868000000000002
  - Likely use: stores structured assumptions or mappings used during scenario assembly and model execution.

### Supply, resources, and trade
- **BioenergySupply-Baseline**
  - Content cues: Resource at low price; Low Price; Feedstock; Data Set
  - Likely use: stores structured assumptions or mappings used during scenario assembly and model execution.
- **BioenergySupply-EnhancedSupply**
  - Content cues: Resource at low price; Low Price; Feedstock; Data Set
  - Likely use: stores structured assumptions or mappings used during scenario assembly and model execution.

## User constraints and bounds
- No explicit user constraints with process-level mappings were identified in this workbook.

## Notes
- This documentation intentionally describes purpose and functionality without listing spreadsheet cell ranges.
- Naming suggests this file is part of a larger linked input set; keep workbook names and paths stable when integrating updates.
