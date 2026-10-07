# Scen_B_SYS_Emis_ETS.xlsx

## Purpose
This workbook supports the TIMES Ireland model as part of **System and policy assumptions**. It is used to define, adjust, or parameterize scenario assumptions and model behavior for its domain.

## Functional role in the model workflow
- Serves as an input artifact consumed by the model data-preparation process.
- Encodes structured assumptions that can vary by scenario, policy case, or technology pathway.
- Organizes data so updates can be managed without changing model code.

## Workbook structure
- Total worksheets: **2**
- Worksheets are grouped below by their likely functional theme based on sheet naming and content cues.

### General input tables
- **INS**
  - Content cues: ~TFM_INS; TimeSlice; LimType; Attribute
  - Likely use: stores structured assumptions or mappings used during scenario assembly and model execution.
- **UPD**
  - Content cues: Trans - Update; ~TFM_UPD; TimeSlice; LimType
  - Likely use: stores structured assumptions or mappings used during scenario assembly and model execution.

## User constraints and bounds
- **Constraint name: ETSCO2**
  - Attribute(s): FLO_EMIS
  - Bound fields: allregions
  - Bound value range(s): allregions (56.9 to 116.7)
  - Source worksheet(s): INS
  - Processes limited:
    - -*NETS*
    - I*-ETS*

- **Constraint name: NOETSCO2**
  - Attribute(s): FLO_EMIS
  - Bound fields: allregions
  - Bound value range(s): allregions (56.9 to 116.7)
  - Source worksheet(s): INS
  - Processes limited:
    - I*-NETS*

## Notes
- This documentation intentionally describes purpose and functionality without listing spreadsheet cell ranges.
- Naming suggests this file is part of a larger linked input set; keep workbook names and paths stable when integrating updates.
