# SubRES_SRV_NewTechs_Trans.xlsx

## Purpose
This workbook supports the TIMES Ireland model as part of **Transport**. It is used to define, adjust, or parameterize scenario assumptions and model behavior for its domain.

## Functional role in the model workflow
- Serves as an input artifact consumed by the model data-preparation process.
- Encodes structured assumptions that can vary by scenario, policy case, or technology pathway.
- Organizes data so updates can be managed without changing model code.

## Workbook structure
- Total worksheets: **11**
- Worksheets are grouped below by their likely functional theme based on sheet naming and content cues.

### General input tables
- **Cover**
  - Content cues: TIMES-Ireland Model; Document type:; New Technologies - Transformation; Sector(s):
  - Likely use: stores structured assumptions or mappings used during scenario assembly and model execution.
- **Legend**
  - Content cues: Sector:; Services; SRV; Tab colour legend
  - Likely use: stores structured assumptions or mappings used during scenario assembly and model execution.
- **AFA**
  - Content cues: AFA for SRV techs; ~TFM_INS; Attribute; PSET_PN
  - Likely use: stores structured assumptions or mappings used during scenario assembly and model execution.
- **EFF**
  - Content cues: EFF for SRV techs; ~TFM_UPD; Attribute; PSET_PN
  - Likely use: stores structured assumptions or mappings used during scenario assembly and model execution.
- **FillTable**
  - Content cues: Fill Table to capture Base-Year Efficiencies; ~TFM_Fill-R: w=BY_S-SH; Hcol=Region; Scenario; LimType
  - Likely use: stores structured assumptions or mappings used during scenario assembly and model execution.
- **Regions**
  - Content cues: IE; National; IE-CW; IE-D
  - Likely use: stores structured assumptions or mappings used during scenario assembly and model execution.
- **BY_S-SH**
  - Content cues: scenario; attribute; process; commodity
  - Likely use: stores structured assumptions or mappings used during scenario assembly and model execution.
- **BY_S-WH**
  - Content cues: scenario; attribute; process; commodity
  - Likely use: stores structured assumptions or mappings used during scenario assembly and model execution.
- **BY_S-SC**
  - Content cues: scenario; attribute; process; commodity
  - Likely use: stores structured assumptions or mappings used during scenario assembly and model execution.
- **BY_S-EAP**
  - Content cues: scenario; attribute; process; commodity
  - Likely use: stores structured assumptions or mappings used during scenario assembly and model execution.

### Technology definitions and performance
- **TechSelection**
  - Content cues: ~TFM_AVA; PSET_SET; PSET_PN; PSET_PD
  - Likely use: stores structured assumptions or mappings used during scenario assembly and model execution.

## User constraints and bounds
- **Constraint name: SRVSC-CS**
  - Attribute(s): AFC, CEFF
  - Bound fields: allregions
  - Bound value range(s): allregions (0.0342466 to 0.0342466)
  - Source worksheet(s): AFA, EFF
  - Processes limited:
    - S-SC-CS_ELC*
    - S-SH-CS_ELC*

- **Constraint name: SRVSC-PU**
  - Attribute(s): AFC, CEFF
  - Bound fields: allregions
  - Bound value range(s): allregions (0.0342466 to 0.0342466)
  - Source worksheet(s): AFA, EFF
  - Processes limited:
    - S-SC-PU_ELC*
    - S-SH-PU_ELC*

- **Constraint name: SRVSH-CS**
  - Attribute(s): *, AFC, CEFF
  - Bound fields: allregions
  - Bound value range(s): allregions (0.114155 to 0.116438)
  - Source worksheet(s): AFA, EFF
  - Processes limited:
    - -*N1
    - S-SH-CS_BIO*
    - S-SH-CS_COA*
    - S-SH-CS_ELC*
    - S-SH-CS_ELC*N1
    - S-SH-CS_GAS*
    - S-SH-CS_HET*
    - S-SH-CS_LPG*
    - S-SH-CS_OIL*

- **Constraint name: SRVSH-PU**
  - Attribute(s): *, AFC, CEFF
  - Bound fields: allregions
  - Bound value range(s): allregions (0.114155 to 0.114155)
  - Source worksheet(s): AFA, EFF
  - Processes limited:
    - -*N1
    - S-SH-PU_BIO*
    - S-SH-PU_COA*
    - S-SH-PU_ELC*
    - S-SH-PU_ELC*N1
    - S-SH-PU_GAS*
    - S-SH-PU_HET*
    - S-SH-PU_LPG*
    - S-SH-PU_OIL*

- **Constraint name: SRVWH-CS**
  - Attribute(s): *, AFC, CEFF
  - Bound fields: allregions
  - Bound value range(s): allregions (0.0228311 to 0.0232877)
  - Source worksheet(s): AFA, EFF
  - Processes limited:
    - S-SH-CS_BIO*
    - S-SH-CS_COA*
    - S-SH-CS_ELC*
    - S-SH-CS_GAS*
    - S-SH-CS_HET*
    - S-SH-CS_LPG*
    - S-SH-CS_OIL*
    - S-WH-CS_BIO*
    - S-WH-CS_COA*
    - S-WH-CS_ELC*
    - S-WH-CS_GAS*
    - S-WH-CS_LPG*
    - S-WH-CS_OIL*
    - S-WH-CS_SOL*

- **Constraint name: SRVWH-PU**
  - Attribute(s): *, AFC, CEFF
  - Bound fields: allregions
  - Bound value range(s): allregions (0.0228311 to 0.0228311)
  - Source worksheet(s): AFA, EFF
  - Processes limited:
    - S-SH-PU_BIO*
    - S-SH-PU_COA*
    - S-SH-PU_ELC*
    - S-SH-PU_GAS*
    - S-SH-PU_HET*
    - S-SH-PU_LPG*
    - S-SH-PU_OIL*
    - S-WH-PU_BIO*
    - S-WH-PU_COA*
    - S-WH-PU_ELC*
    - S-WH-PU_GAS*
    - S-WH-PU_LPG*
    - S-WH-PU_OIL*
    - S-WH-PU_SOL*

## Notes
- This documentation intentionally describes purpose and functionality without listing spreadsheet cell ranges.
- Naming suggests this file is part of a larger linked input set; keep workbook names and paths stable when integrating updates.
