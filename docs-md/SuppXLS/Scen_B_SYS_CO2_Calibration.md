# Scen_B_SYS_CO2_Calibration.xlsx

## Purpose
This workbook supports the TIMES Ireland model as part of **System and policy assumptions**. It is used to define, adjust, or parameterize scenario assumptions and model behavior for its domain.

## Functional role in the model workflow
- Serves as an input artifact consumed by the model data-preparation process.
- Encodes structured assumptions that can vary by scenario, policy case, or technology pathway.
- Organizes data so updates can be managed without changing model code.

## Workbook structure
- Total worksheets: **2**
- Worksheets are grouped below by their likely functional theme based on sheet naming and content cues.

### Emissions and carbon constraints
- **EPA_Historical CO2 Emission**
  - Content cues: 1990-2021_Submission 2023 FINAL; 2015; 2016; 2017
  - Likely use: stores structured assumptions or mappings used during scenario assembly and model execution.

### General input tables
- **INS**
  - Content cues: Trans - Insert; ~TFM_INS; TimeSlice; LimType
  - Likely use: stores structured assumptions or mappings used during scenario assembly and model execution.

## User constraints and bounds
- No explicit user constraints with process-level mappings were identified in this workbook.

## Notes
- This documentation intentionally describes purpose and functionality without listing spreadsheet cell ranges.
- Naming suggests this file is part of a larger linked input set; keep workbook names and paths stable when integrating updates.
