# Scen_B_IND_Shares.xlsx

## Purpose
This workbook supports the TIMES Ireland model as part of **Industry**. It is used to define, adjust, or parameterize scenario assumptions and model behavior for its domain.

## Functional role in the model workflow
- Serves as an input artifact consumed by the model data-preparation process.
- Encodes structured assumptions that can vary by scenario, policy case, or technology pathway.
- Organizes data so updates can be managed without changing model code.

## Workbook structure
- Total worksheets: **3**
- Worksheets are grouped below by their likely functional theme based on sheet naming and content cues.

### General input tables
- **IND**
  - Content cues: UC_N; UC_ATTR; Pset_Set; Pset_PN
  - Likely use: stores structured assumptions or mappings used during scenario assembly and model execution.
- **msw**
  - Content cues: ~TFM_INS; TimeSlice; LimType; Attribute
  - Likely use: stores structured assumptions or mappings used during scenario assembly and model execution.
- **IND_UCs**
  - Content cues: ~UC_Sets: R_E: IE,National; ~UC_Sets: T_E:; UC_T:; UC_N
  - Likely use: stores structured assumptions or mappings used during scenario assembly and model execution.

## User constraints and bounds
- **Constraint name: *HTH**
  - Attribute(s): PRC_MARK
  - Source worksheet(s): msw
  - Processes limited:
    - -I*CEM*WS*
    - -I*DRR*RWS*
    - -I*LIM*WS*
    - I*CEM*NWS*
    - I*CEM*RWS*
    - I*WS*

- **Constraint name: CAFHET**
  - Source worksheet(s): IND_UCs
  - Processes limited:
    - I*CAF*NETS*

- **Constraint name: CAFHTH**
  - Source worksheet(s): IND_UCs
  - Processes limited:
    - I*CAF*NETS*

- **Constraint name: CAFLTH**
  - Source worksheet(s): IND_UCs
  - Processes limited:
    - I*CAF*NETS*

- **Constraint name: CAFMTH**
  - Source worksheet(s): IND_UCs
  - Processes limited:
    - I*CAF*NETS*

- **Constraint name: CEMHET**
  - Source worksheet(s): IND_UCs
  - Processes limited:
    - I*CEM*NETS*

- **Constraint name: CEMHTH**
  - Source worksheet(s): IND_UCs
  - Processes limited:
    - I*CEM*NETS*

- **Constraint name: CEMLTH**
  - Source worksheet(s): IND_UCs
  - Processes limited:
    - I*CEM*NETS*

- **Constraint name: CEMMTH**
  - Source worksheet(s): IND_UCs
  - Processes limited:
    - I*CEM*NETS*

- **Constraint name: FAPHET**
  - Source worksheet(s): IND_UCs
  - Processes limited:
    - I*FAP*NETS*

- **Constraint name: FAPHTH**
  - Source worksheet(s): IND_UCs
  - Processes limited:
    - I*FAP*NETS*

- **Constraint name: FAPLTH**
  - Source worksheet(s): IND_UCs
  - Processes limited:
    - I*FAP*NETS*

- **Constraint name: FAPMTH**
  - Source worksheet(s): IND_UCs
  - Processes limited:
    - I*FAP*NETS*

- **Constraint name: LIMHET**
  - Source worksheet(s): IND_UCs
  - Processes limited:
    - I*LIM*NETS*

- **Constraint name: LIMHTH**
  - Source worksheet(s): IND_UCs
  - Processes limited:
    - I*LIM*NETS*

- **Constraint name: LIMLTH**
  - Source worksheet(s): IND_UCs
  - Processes limited:
    - I*LIM*NETS*

- **Constraint name: LIMMTH**
  - Source worksheet(s): IND_UCs
  - Processes limited:
    - I*LIM*NETS*

- **Constraint name: MAPHET**
  - Source worksheet(s): IND_UCs
  - Processes limited:
    - I*MAP*NETS*

- **Constraint name: MAPHTH**
  - Source worksheet(s): IND_UCs
  - Processes limited:
    - I*MAP*NETS*

- **Constraint name: MAPLTH**
  - Source worksheet(s): IND_UCs
  - Processes limited:
    - I*MAP*NETS*

- **Constraint name: MAPMTH**
  - Source worksheet(s): IND_UCs
  - Processes limited:
    - I*MAP*NETS*

- **Constraint name: OMAHET**
  - Source worksheet(s): IND_UCs
  - Processes limited:
    - I*OMA*NETS*

- **Constraint name: OMAHTH**
  - Source worksheet(s): IND_UCs
  - Processes limited:
    - I*OMA*NETS*

- **Constraint name: OMALTH**
  - Source worksheet(s): IND_UCs
  - Processes limited:
    - I*OMA*NETS*

- **Constraint name: OMAMTH**
  - Source worksheet(s): IND_UCs
  - Processes limited:
    - I*OMA*NETS*

- **Constraint name: ONMHET**
  - Source worksheet(s): IND_UCs
  - Processes limited:
    - I*ONM*NETS*

- **Constraint name: ONMHTH**
  - Source worksheet(s): IND_UCs
  - Processes limited:
    - I*ONM*NETS*

- **Constraint name: ONMLTH**
  - Source worksheet(s): IND_UCs
  - Processes limited:
    - I*ONM*NETS*

- **Constraint name: ONMMTH**
  - Source worksheet(s): IND_UCs
  - Processes limited:
    - I*ONM*NETS*

- **Constraint name: WAPHET**
  - Source worksheet(s): IND_UCs
  - Processes limited:
    - I*WAP*NETS*

- **Constraint name: WAPHTH**
  - Source worksheet(s): IND_UCs
  - Processes limited:
    - I*WAP*NETS*

- **Constraint name: WAPLTH**
  - Source worksheet(s): IND_UCs
  - Processes limited:
    - I*WAP*NETS*

- **Constraint name: WAPMTH**
  - Source worksheet(s): IND_UCs
  - Processes limited:
    - I*WAP*NETS*

## Notes
- This documentation intentionally describes purpose and functionality without listing spreadsheet cell ranges.
- Naming suggests this file is part of a larger linked input set; keep workbook names and paths stable when integrating updates.
