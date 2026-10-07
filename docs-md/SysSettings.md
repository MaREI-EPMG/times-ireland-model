# SysSettings.xlsx

## Purpose
This workbook supports the TIMES Ireland model as part of **System and policy assumptions**. It is used to define, adjust, or parameterize scenario assumptions and model behavior for its domain.

## Functional role in the model workflow
- Serves as an input artifact consumed by the model data-preparation process.
- Encodes structured assumptions that can vary by scenario, policy case, or technology pathway.
- Organizes data so updates can be managed without changing model code.

## Workbook structure
- Total worksheets: **9**
- Worksheets are grouped below by their likely functional theme based on sheet naming and content cues.

### Controls and configuration
- **Import Settings**
  - Content cues: ~ImpSettings; Option; Value; Check #DIV/0 and #REF errors in Templates
  - Likely use: stores structured assumptions or mappings used during scenario assembly and model execution.

### General input tables
- **Cover**
  - Content cues: TIMES-Ireland Model; Document type:; System Settings; Sector(s):
  - Likely use: stores structured assumptions or mappings used during scenario assembly and model execution.
- **Regions**
  - Content cues: IE; National; IE-CW; IE-D
  - Likely use: stores structured assumptions or mappings used during scenario assembly and model execution.
- **Region Definition**
  - Content cues: ~BookRegions_Map; BookName; Region; IE
  - Likely use: stores structured assumptions or mappings used during scenario assembly and model execution.
- **TimePeriods**
  - Content cues: ~StartYear; 2018; ~ActivePDef; P15
  - Likely use: stores structured assumptions or mappings used during scenario assembly and model execution.
- **Interpol_Extrapol_Defaults**
  - Content cues: Dummy Imp Prices; ~TFM_UPD; TimeSlice; LimType
  - Likely use: stores structured assumptions or mappings used during scenario assembly and model execution.
- **Constants**
  - Content cues: * Discount rates, Timeslices, Exchange rates; ~TFM_INS; TimeSlice; CURR
  - Likely use: stores structured assumptions or mappings used during scenario assembly and model execution.
- **Defaults**
  - Content cues: ~Currencies; DefUnits; ~UnitConversion; Currency
  - Likely use: stores structured assumptions or mappings used during scenario assembly and model execution.
- **CPI**
  - Content cues: Euro inflation rate; € CPI; 2000; 100
  - Likely use: stores structured assumptions or mappings used during scenario assembly and model execution.

## User constraints and bounds
- **Constraint name: *HTH,*LTH,*MTH,*HET**
  - Attribute(s): *FLO_BND
  - Bound fields: allregions
  - Source worksheet(s): Interpol_Extrapol_Defaults
  - Processes limited:
    - IMP*Z

## Notes
- This documentation intentionally describes purpose and functionality without listing spreadsheet cell ranges.
- Naming suggests this file is part of a larger linked input set; keep workbook names and paths stable when integrating updates.
