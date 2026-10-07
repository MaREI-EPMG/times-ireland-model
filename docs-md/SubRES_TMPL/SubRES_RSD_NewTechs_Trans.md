# SubRES_RSD_NewTechs_Trans.xlsx

## Purpose
This workbook supports the TIMES Ireland model as part of **Transport**. It is used to define, adjust, or parameterize scenario assumptions and model behavior for its domain.

## Functional role in the model workflow
- Serves as an input artifact consumed by the model data-preparation process.
- Encodes structured assumptions that can vary by scenario, policy case, or technology pathway.
- Organizes data so updates can be managed without changing model code.

## Workbook structure
- Total worksheets: **18**
- Worksheets are grouped below by their likely functional theme based on sheet naming and content cues.

### General input tables
- **Cover**
  - Content cues: TIMES-Ireland Model; Document type:; New Technologies - Transformation; Sector(s):
  - Likely use: stores structured assumptions or mappings used during scenario assembly and model execution.
- **LOG**
  - Content cues: Date; Name; Sheet Name; Cells
  - Likely use: stores structured assumptions or mappings used during scenario assembly and model execution.
- **Regions**
  - Content cues: IE; National; IE-CW; IE-D
  - Likely use: stores structured assumptions or mappings used during scenario assembly and model execution.
- **FillTable**
  - Content cues: Fill Table to capture Base-Year Availability; Update Table to capture Base-Year Efficiency; ~TFM_Fill-R: w=BY-RSD-SH_AF; Hcol=Region; ~TFM_Fill-R: w=BY-RSD-RF; Hcol=Region
  - Likely use: stores structured assumptions or mappings used during scenario assembly and model execution.
- **AF**
  - Content cues: AFA for RSD techs; ~TFM_INS; Attribute; PSet_PN
  - Likely use: stores structured assumptions or mappings used during scenario assembly and model execution.
- **EFF**
  - Content cues: EFF for RSD techs; ~TFM_UPD; Type; Fuel
  - Likely use: stores structured assumptions or mappings used during scenario assembly and model execution.
- **BY-RSD-WH_AF**
  - Content cues: scenario; attribute; process; commodity
  - Likely use: stores structured assumptions or mappings used during scenario assembly and model execution.
- **BY-RSD-SH_AF**
  - Content cues: scenario; attribute; process; commodity
  - Likely use: stores structured assumptions or mappings used during scenario assembly and model execution.
- **BY-RSD-EFF**
  - Content cues: scenario; attribute; process; commodity
  - Likely use: stores structured assumptions or mappings used during scenario assembly and model execution.
- **BY-RSD-DW**
  - Content cues: scenario; attribute; process; commodity
  - Likely use: stores structured assumptions or mappings used during scenario assembly and model execution.
- **BY-RSD-PF**
  - Content cues: scenario; attribute; process; commodity
  - Likely use: stores structured assumptions or mappings used during scenario assembly and model execution.
- **BY-RSD-CD**
  - Content cues: scenario; attribute; process; commodity
  - Likely use: stores structured assumptions or mappings used during scenario assembly and model execution.
- **BY-RSD-LT**
  - Content cues: scenario; attribute; process; commodity
  - Likely use: stores structured assumptions or mappings used during scenario assembly and model execution.
- **BY-RSD-CW**
  - Content cues: scenario; attribute; process; commodity
  - Likely use: stores structured assumptions or mappings used during scenario assembly and model execution.
- **BY-RSD-CK**
  - Content cues: scenario; attribute; process; commodity
  - Likely use: stores structured assumptions or mappings used during scenario assembly and model execution.
- **BY-RSD-RF**
  - Content cues: scenario; attribute; process; commodity
  - Likely use: stores structured assumptions or mappings used during scenario assembly and model execution.
- **BY-RSD-OE**
  - Content cues: scenario; attribute; process; commodity
  - Likely use: stores structured assumptions or mappings used during scenario assembly and model execution.

### Technology definitions and performance
- **TechSelection**
  - Content cues: ~TFM_AVA; PSET_SET; PSET_PN; PSET_PD
  - Likely use: stores structured assumptions or mappings used during scenario assembly and model execution.

## User constraints and bounds
- **Constraint name: RSDSC_Apt**
  - Attribute(s): AFC
  - Bound fields: allregions
  - Bound value range(s): allregions (0.181303 to 0.181303)
  - Source worksheet(s): AF
  - Processes limited:
    - R-HC_Apt_ELC_HPN*

- **Constraint name: RSDSC_Att**
  - Attribute(s): AFC
  - Bound fields: allregions
  - Bound value range(s): allregions (0.114043 to 0.114043)
  - Source worksheet(s): AF
  - Processes limited:
    - R-HC_Att_ELC_HPN*

- **Constraint name: RSDSC_Det**
  - Attribute(s): AFC
  - Bound fields: allregions
  - Bound value range(s): allregions (0.138319 to 0.138319)
  - Source worksheet(s): AF
  - Processes limited:
    - R-HC_Det_ELC_HPN*

- **Constraint name: RSDSH_Apt-AB,RSDSH_Apt-C,RSDSH_Apt-D,RSDSH_Apt-E,RSDSH_Apt-F,RSDSH_Apt-G**
  - Attribute(s): AFC
  - Bound fields: allregions
  - Bound value range(s): allregions (0.181303 to 0.181303)
  - Source worksheet(s): AF
  - Processes limited:
    - R-HC_Apt_ELC_HPN*

- **Constraint name: RSDSH_Apt-AB,RSDSH_Apt-C,RSDSH_Apt-D,RSDSH_Apt-E,RSDSH_Apt-F,RSDSH_Apt-G,RSDWH_Apt**
  - Attribute(s): *, NCAP_AFC
  - Bound fields: allregions
  - Bound value range(s): allregions (0.0139311 to 0.181303)
  - Source worksheet(s): AF
  - Processes limited:
    - -R-SC*
    - R-*_Apt*HPN*
    - R-S*_Apt_ELC_N1
    - R-SW*Apt_BDL*
    - R-SW*Apt_COA*
    - R-SW*Apt_ETH*
    - R-SW*Apt_GAS*
    - R-SW*Apt_HET*
    - R-SW*Apt_KER*
    - R-SW*Apt_LPG*
    - R-SW*Apt_PEA*
    - R-SW*Apt_SMF*
    - R-SW*Apt_WOO*

- **Constraint name: RSDSH_Att-AB,RSDSH_Att-C,RSDSH_Att-D,RSDSH_Att-E,RSDSH_Att-F,RSDSH_Att-G**
  - Attribute(s): AFC
  - Bound fields: allregions
  - Bound value range(s): allregions (0.114043 to 0.114043)
  - Source worksheet(s): AF
  - Processes limited:
    - R-HC_Att_ELC_HPN*

- **Constraint name: RSDSH_Att-AB,RSDSH_Att-C,RSDSH_Att-D,RSDSH_Att-E,RSDSH_Att-F,RSDSH_Att-G,RSDWH_Att**
  - Attribute(s): *, NCAP_AFC
  - Bound fields: allregions
  - Bound value range(s): allregions (0.0351564 to 0.309845)
  - Source worksheet(s): AF
  - Processes limited:
    - -R-SC*
    - R-*_Att*HPN*
    - R-S*_Att_ELC_N1
    - R-SW*Att_BDL*
    - R-SW*Att_COA*
    - R-SW*Att_ETH*
    - R-SW*Att_GAS*
    - R-SW*Att_HET*
    - R-SW*Att_KER*
    - R-SW*Att_LPG*
    - R-SW*Att_PEA*
    - R-SW*Att_SMF*
    - R-SW*Att_WOO*
    - R-SW_Att_FPL*
    - R-SW_Att_HVO*

- **Constraint name: RSDSH_Det-AB,RSDSH_Det-C,RSDSH_Det-D,RSDSH_Det-E,RSDSH_Det-F,RSDSH_Det-G**
  - Attribute(s): AFC
  - Bound fields: allregions
  - Bound value range(s): allregions (0.138319 to 0.138319)
  - Source worksheet(s): AF
  - Processes limited:
    - R-HC_Det_ELC_HPN*

- **Constraint name: RSDSH_Det-AB,RSDSH_Det-C,RSDSH_Det-D,RSDSH_Det-E,RSDSH_Det-F,RSDSH_Det-G,RSDWH_Det**
  - Attribute(s): *, NCAP_AFC
  - Bound fields: allregions
  - Bound value range(s): allregions (0.039672 to 0.464144)
  - Source worksheet(s): AF
  - Processes limited:
    - -R-SC*
    - R-*_Det*HPN*
    - R-S*_Det_ELC_N1
    - R-SW*Det_BDL*
    - R-SW*Det_COA*
    - R-SW*Det_ETH*
    - R-SW*Det_GAS*
    - R-SW*Det_HET*
    - R-SW*Det_KER*
    - R-SW*Det_LPG*
    - R-SW*Det_PEA*
    - R-SW*Det_SMF*
    - R-SW*Det_WOO*
    - R-SW_Det_FPL*
    - R-SW_Det_HVO*

## Notes
- This documentation intentionally describes purpose and functionality without listing spreadsheet cell ranges.
- Naming suggests this file is part of a larger linked input set; keep workbook names and paths stable when integrating updates.
