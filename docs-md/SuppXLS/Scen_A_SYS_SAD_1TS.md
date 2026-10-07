# Scen_A_SYS_SAD_1TS.xlsx

## Purpose
This workbook supports the TIMES Ireland model as part of **System and policy assumptions**. It is used to define, adjust, or parameterize scenario assumptions and model behavior for its domain.

## Functional role in the model workflow
- Serves as an input artifact consumed by the model data-preparation process.
- Encodes structured assumptions that can vary by scenario, policy case, or technology pathway.
- Organizes data so updates can be managed without changing model code.

## Workbook structure
- Total worksheets: **13**
- Worksheets are grouped below by their likely functional theme based on sheet naming and content cues.

### General input tables
- **Cover**
  - Content cues: TIMES-Ireland Model; Document type:; Scenario; Sector(s):
  - Likely use: stores structured assumptions or mappings used during scenario assembly and model execution.
- **TS_Definition**
  - Content cues: ~TimeSlices; Season; Weekly; DayNite
  - Likely use: stores structured assumptions or mappings used during scenario assembly and model execution.
- **TimeSlices**
  - Content cues: ~TFM_INS; TimeSlice; Attribute; IE
  - Likely use: stores structured assumptions or mappings used during scenario assembly and model execution.
- **RSDSOL**
  - Content cues: ~TFM_INS; TimeSlice; Attribute; Year
  - Likely use: stores structured assumptions or mappings used during scenario assembly and model execution.
- **RSD_SH**
  - Content cues: ~TFM_INS; TimeSlice; Attribute; Year
  - Likely use: stores structured assumptions or mappings used during scenario assembly and model execution.
- **RSD_RTFT**
  - Content cues: ~TFM_INS; TimeSlice; Attribute; LimType
  - Likely use: stores structured assumptions or mappings used during scenario assembly and model execution.
- **RSD_OE_DEM**
  - Content cues: ~TFM_INS; TimeSlice; Attribute; Year
  - Likely use: stores structured assumptions or mappings used during scenario assembly and model execution.
- **PWR_AF**
  - Content cues: ~TFM_INS; TimeSlice; Attribute; Year
  - Likely use: stores structured assumptions or mappings used during scenario assembly and model execution.
- **TRA_DEM**
  - Content cues: ~TFM_INS; TimeSlice; Attribute; Year
  - Likely use: stores structured assumptions or mappings used during scenario assembly and model execution.
- **SRV_CS_DEM**
  - Content cues: ~TFM_INS; TimeSlice; Attribute; Year
  - Likely use: stores structured assumptions or mappings used during scenario assembly and model execution.
- **SRV_PU_DEM**
  - Content cues: ~TFM_INS; TimeSlice; Attribute; Year
  - Likely use: stores structured assumptions or mappings used during scenario assembly and model execution.
- **DCs**
  - Content cues: ~TFM_INS; TimeSlice; Attribute; Year
  - Likely use: stores structured assumptions or mappings used during scenario assembly and model execution.
- **SRVSOL**
  - Content cues: ~TFM_INS; TimeSlice; Attribute; Year
  - Likely use: stores structured assumptions or mappings used during scenario assembly and model execution.

## User constraints and bounds
- No explicit user constraints with process-level mappings were identified in this workbook.

## Notes
- This documentation intentionally describes purpose and functionality without listing spreadsheet cell ranges.
- Naming suggests this file is part of a larger linked input set; keep workbook names and paths stable when integrating updates.
