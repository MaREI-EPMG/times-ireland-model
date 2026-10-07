# Scen_Par-SYS_FF2price.xlsx

## Purpose
This workbook supports the TIMES Ireland model as part of **System and policy assumptions**. It is used to define, adjust, or parameterize scenario assumptions and model behavior for its domain.

## Functional role in the model workflow
- Serves as an input artifact consumed by the model data-preparation process.
- Encodes structured assumptions that can vary by scenario, policy case, or technology pathway.
- Organizes data so updates can be managed without changing model code.

## Workbook structure
- Total worksheets: **4**
- Worksheets are grouped below by their likely functional theme based on sheet naming and content cues.

### Controls and configuration
- **config**
  - Content cues: ~InputCell:1,4; 4; Case #; FF_price
  - Likely use: stores structured assumptions or mappings used during scenario assembly and model execution.

### Costs, prices, and economics
- **FF2price**
  - Content cues: ~TFM_UPD; TimeSlice; LimType; Attribute
  - Likely use: stores structured assumptions or mappings used during scenario assembly and model execution.

### General input tables
- **Cover**
  - Content cues: TIMES-Ireland Model; Document type:; Scenario - Parametric; Sector(s):
  - Likely use: stores structured assumptions or mappings used during scenario assembly and model execution.
- **Regions**
  - Content cues: IE; National; IE-CW; IE-D
  - Likely use: stores structured assumptions or mappings used during scenario assembly and model execution.

## User constraints and bounds
- No explicit user constraints with process-level mappings were identified in this workbook.

## Notes
- This documentation intentionally describes purpose and functionality without listing spreadsheet cell ranges.
- Naming suggests this file is part of a larger linked input set; keep workbook names and paths stable when integrating updates.
