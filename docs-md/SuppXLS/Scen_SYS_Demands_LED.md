# Scen_SYS_Demands_LED.xlsx

## Purpose
This workbook supports the TIMES Ireland model as part of **System and policy assumptions**. It is used to define, adjust, or parameterize scenario assumptions and model behavior for its domain.

## Functional role in the model workflow
- Serves as an input artifact consumed by the model data-preparation process.
- Encodes structured assumptions that can vary by scenario, policy case, or technology pathway.
- Organizes data so updates can be managed without changing model code.

## Workbook structure
- Total worksheets: **9**
- Worksheets are grouped below by their likely functional theme based on sheet naming and content cues.

### Demand and activity assumptions
- **BY-Demands**
  - Content cues: ~TFM_FILL; Operation_Sum_Avg_Count; Scenario Name; TimeSlice
  - Likely use: stores structured assumptions or mappings used during scenario assembly and model execution.
- **REG_TRA_DEMANDS**
  - Content cues: ~TFM_DINS; TimeSlice; LimType; Attribute
  - Likely use: stores structured assumptions or mappings used during scenario assembly and model execution.
- **DEMANDS**
  - Content cues: ~TFM_INS-TS; LimType; Region; Attribute
  - Likely use: stores structured assumptions or mappings used during scenario assembly and model execution.

### General input tables
- **Regions**
  - Content cues: IE; National; IE-CW; IE-D
  - Likely use: stores structured assumptions or mappings used during scenario assembly and model execution.
- **Residential**
  - Content cues: ~TFM_INS; TimeSlice; LimType; Attribute
  - Likely use: stores structured assumptions or mappings used during scenario assembly and model execution.
- **Inputs_RSD**
  - Content cues: scenario; attribute; process; commodity
  - Likely use: stores structured assumptions or mappings used during scenario assembly and model execution.
- **Fill_data**
  - Content cues: deact~TFM_Fill-R: w=Inputs_RSD; Hcol=Region; deact~TFM_Fill-R: w=Inputs_SRV; Hcol=Region; Scenario; LimType
  - Likely use: stores structured assumptions or mappings used during scenario assembly and model execution.
- **Services**
  - Content cues: ~TFM_INS; TimeSlice; LimType; Attribute
  - Likely use: stores structured assumptions or mappings used during scenario assembly and model execution.
- **Inputs_SRV**
  - Content cues: scenario; attribute; process; commodity
  - Likely use: stores structured assumptions or mappings used during scenario assembly and model execution.

## User constraints and bounds
- **Constraint name: RSDLT***
  - Attribute(s): INPUT
  - Bound fields: allregions
  - Bound value range(s): allregions (1 to 1)
  - Source worksheet(s): Fill_data
  - Processes limited:
    - *N1
    - -*N1

- **Constraint name: RSDLT_Apt**
  - Attribute(s): INPUT
  - Source worksheet(s): Residential
  - Processes limited:
    - R-BLD_AptN1
    - R-BLD_Apt_A
    - R-BLD_Apt_B1
    - R-BLD_Apt_B2
    - R-BLD_Apt_B3
    - R-BLD_Apt_C
    - R-BLD_Apt_D
    - R-BLD_Apt_E
    - R-BLD_Apt_F
    - R-BLD_Apt_G

- **Constraint name: RSDLT_Att**
  - Attribute(s): INPUT
  - Source worksheet(s): Residential
  - Processes limited:
    - R-BLD_Att-N1
    - R-BLD_Att_A
    - R-BLD_Att_B1
    - R-BLD_Att_B2
    - R-BLD_Att_B3
    - R-BLD_Att_C
    - R-BLD_Att_D
    - R-BLD_Att_E
    - R-BLD_Att_F
    - R-BLD_Att_G

- **Constraint name: RSDLT_Det**
  - Attribute(s): INPUT
  - Source worksheet(s): Residential
  - Processes limited:
    - R-BLD_Det-N1
    - R-BLD_Det_A
    - R-BLD_Det_B1
    - R-BLD_Det_B2
    - R-BLD_Det_B3
    - R-BLD_Det_C
    - R-BLD_Det_D
    - R-BLD_Det_E
    - R-BLD_Det_F
    - R-BLD_Det_G

- **Constraint name: RSDPF***
  - Attribute(s): INPUT
  - Bound fields: allregions
  - Bound value range(s): allregions (1 to 1)
  - Source worksheet(s): Fill_data
  - Processes limited:
    - *N1
    - -*N1

- **Constraint name: RSDPF_Apt**
  - Attribute(s): INPUT
  - Source worksheet(s): Residential
  - Processes limited:
    - R-BLD_AptN1
    - R-BLD_Apt_A
    - R-BLD_Apt_B1
    - R-BLD_Apt_B2
    - R-BLD_Apt_B3
    - R-BLD_Apt_C
    - R-BLD_Apt_D
    - R-BLD_Apt_E
    - R-BLD_Apt_F
    - R-BLD_Apt_G

- **Constraint name: RSDPF_Att**
  - Attribute(s): INPUT
  - Source worksheet(s): Residential
  - Processes limited:
    - R-BLD_Att-N1
    - R-BLD_Att_A
    - R-BLD_Att_B1
    - R-BLD_Att_B2
    - R-BLD_Att_B3
    - R-BLD_Att_C
    - R-BLD_Att_D
    - R-BLD_Att_E
    - R-BLD_Att_F
    - R-BLD_Att_G

- **Constraint name: RSDPF_Det**
  - Attribute(s): INPUT
  - Source worksheet(s): Residential
  - Processes limited:
    - R-BLD_Det-N1
    - R-BLD_Det_A
    - R-BLD_Det_B1
    - R-BLD_Det_B2
    - R-BLD_Det_B3
    - R-BLD_Det_C
    - R-BLD_Det_D
    - R-BLD_Det_E
    - R-BLD_Det_F
    - R-BLD_Det_G

- **Constraint name: RSDSC***
  - Attribute(s): INPUT
  - Bound fields: allregions
  - Bound value range(s): allregions (1 to 1)
  - Source worksheet(s): Fill_data
  - Processes limited:
    - *N1
    - -*N1

- **Constraint name: RSDSC_Apt**
  - Attribute(s): INPUT
  - Source worksheet(s): Residential
  - Processes limited:
    - R-BLD_AptN1

- **Constraint name: RSDSC_Att**
  - Attribute(s): INPUT
  - Source worksheet(s): Residential
  - Processes limited:
    - R-BLD_Att-N1

- **Constraint name: RSDSC_Det**
  - Attribute(s): INPUT
  - Source worksheet(s): Residential
  - Processes limited:
    - R-BLD_Det-N1

- **Constraint name: RSDSH***
  - Attribute(s): INPUT
  - Bound fields: allregions
  - Bound value range(s): allregions (1 to 1)
  - Source worksheet(s): Fill_data
  - Processes limited:
    - *N1
    - -*N1

- **Constraint name: RSDSH_Apt-AB**
  - Attribute(s): INPUT
  - Source worksheet(s): Residential
  - Processes limited:
    - R-BLD_AptN1
    - R-BLD_Apt_A
    - R-BLD_Apt_B1
    - R-BLD_Apt_B2
    - R-BLD_Apt_B3

- **Constraint name: RSDSH_Apt-C**
  - Attribute(s): INPUT
  - Source worksheet(s): Residential
  - Processes limited:
    - R-BLD_Apt_C

- **Constraint name: RSDSH_Apt-D**
  - Attribute(s): INPUT
  - Source worksheet(s): Residential
  - Processes limited:
    - R-BLD_Apt_D

- **Constraint name: RSDSH_Apt-E**
  - Attribute(s): INPUT
  - Source worksheet(s): Residential
  - Processes limited:
    - R-BLD_Apt_E

- **Constraint name: RSDSH_Apt-F**
  - Attribute(s): INPUT
  - Source worksheet(s): Residential
  - Processes limited:
    - R-BLD_Apt_F

- **Constraint name: RSDSH_Apt-G**
  - Attribute(s): INPUT
  - Source worksheet(s): Residential
  - Processes limited:
    - R-BLD_Apt_G

- **Constraint name: RSDSH_Att-AB**
  - Attribute(s): INPUT
  - Source worksheet(s): Residential
  - Processes limited:
    - R-BLD_Att-N1
    - R-BLD_Att_A
    - R-BLD_Att_B1
    - R-BLD_Att_B2
    - R-BLD_Att_B3

- **Constraint name: RSDSH_Att-C**
  - Attribute(s): INPUT
  - Source worksheet(s): Residential
  - Processes limited:
    - R-BLD_Att_C

- **Constraint name: RSDSH_Att-D**
  - Attribute(s): INPUT
  - Source worksheet(s): Residential
  - Processes limited:
    - R-BLD_Att_D

- **Constraint name: RSDSH_Att-E**
  - Attribute(s): INPUT
  - Source worksheet(s): Residential
  - Processes limited:
    - R-BLD_Att_E

- **Constraint name: RSDSH_Att-F**
  - Attribute(s): INPUT
  - Source worksheet(s): Residential
  - Processes limited:
    - R-BLD_Att_F

- **Constraint name: RSDSH_Att-G**
  - Attribute(s): INPUT
  - Source worksheet(s): Residential
  - Processes limited:
    - R-BLD_Att_G

- **Constraint name: RSDSH_Det-AB**
  - Attribute(s): INPUT
  - Source worksheet(s): Residential
  - Processes limited:
    - R-BLD_Det-N1
    - R-BLD_Det_A
    - R-BLD_Det_B1
    - R-BLD_Det_B2
    - R-BLD_Det_B3

- **Constraint name: RSDSH_Det-C**
  - Attribute(s): INPUT
  - Source worksheet(s): Residential
  - Processes limited:
    - R-BLD_Det_C

- **Constraint name: RSDSH_Det-D**
  - Attribute(s): INPUT
  - Source worksheet(s): Residential
  - Processes limited:
    - R-BLD_Det_D

- **Constraint name: RSDSH_Det-E**
  - Attribute(s): INPUT
  - Source worksheet(s): Residential
  - Processes limited:
    - R-BLD_Det_E

- **Constraint name: RSDSH_Det-F**
  - Attribute(s): INPUT
  - Source worksheet(s): Residential
  - Processes limited:
    - R-BLD_Det_F

- **Constraint name: RSDSH_Det-G**
  - Attribute(s): INPUT
  - Source worksheet(s): Residential
  - Processes limited:
    - R-BLD_Det_G

- **Constraint name: RSDWH***
  - Attribute(s): INPUT
  - Bound fields: allregions
  - Bound value range(s): allregions (1 to 1)
  - Source worksheet(s): Fill_data
  - Processes limited:
    - *N1
    - -*N1

- **Constraint name: RSDWH_Apt**
  - Attribute(s): INPUT
  - Source worksheet(s): Residential
  - Processes limited:
    - R-BLD_AptN1
    - R-BLD_Apt_A
    - R-BLD_Apt_B1
    - R-BLD_Apt_B2
    - R-BLD_Apt_B3
    - R-BLD_Apt_C
    - R-BLD_Apt_D
    - R-BLD_Apt_E
    - R-BLD_Apt_F
    - R-BLD_Apt_G

- **Constraint name: RSDWH_Att**
  - Attribute(s): INPUT
  - Source worksheet(s): Residential
  - Processes limited:
    - R-BLD_Att-N1
    - R-BLD_Att_A
    - R-BLD_Att_B1
    - R-BLD_Att_B2
    - R-BLD_Att_B3
    - R-BLD_Att_C
    - R-BLD_Att_D
    - R-BLD_Att_E
    - R-BLD_Att_F
    - R-BLD_Att_G

- **Constraint name: RSDWH_Det**
  - Attribute(s): INPUT
  - Source worksheet(s): Residential
  - Processes limited:
    - R-BLD_Det-N1
    - R-BLD_Det_A
    - R-BLD_Det_B1
    - R-BLD_Det_B2
    - R-BLD_Det_B3
    - R-BLD_Det_C
    - R-BLD_Det_D
    - R-BLD_Det_E
    - R-BLD_Det_F
    - R-BLD_Det_G

## Notes
- This documentation intentionally describes purpose and functionality without listing spreadsheet cell ranges.
- Naming suggests this file is part of a larger linked input set; keep workbook names and paths stable when integrating updates.
