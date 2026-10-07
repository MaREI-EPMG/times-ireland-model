# SubRES_IND_CCS_Trans.xlsx

## Purpose
This workbook supports the TIMES Ireland model as part of **Industry**. It is used to define, adjust, or parameterize scenario assumptions and model behavior for its domain.

## Functional role in the model workflow
- Serves as an input artifact consumed by the model data-preparation process.
- Encodes structured assumptions that can vary by scenario, policy case, or technology pathway.
- Organizes data so updates can be managed without changing model code.

## Workbook structure
- Total worksheets: **4**
- Worksheets are grouped below by their likely functional theme based on sheet naming and content cues.

### General input tables
- **Cover**
  - Content cues: TIMES-Ireland Model; Document type:; New Technologies - Transformation; Sector(s):
  - Likely use: stores structured assumptions or mappings used during scenario assembly and model execution.
- **Regions**
  - Content cues: IE; National; IE-CW; IE-D
  - Likely use: stores structured assumptions or mappings used during scenario assembly and model execution.
- **HTH_FLO**
  - Content cues: ~TFM_INS; PSET_PN; Attribute; CSET_CN
  - Likely use: stores structured assumptions or mappings used during scenario assembly and model execution.

### Technology definitions and performance
- **TechSelection**
  - Content cues: ~TFM_AVA; PSET_SET; PSET_PN; PSET_PD
  - Likely use: stores structured assumptions or mappings used during scenario assembly and model execution.

## User constraints and bounds
- **Constraint name: *Commodity name**
  - Attribute(s): *Attribute
  - Bound fields: allregions
  - Source worksheet(s): HTH_FLO
  - Processes limited:
    - *Technology Name

- **Constraint name: CAFHET**
  - Attribute(s): Share-O
  - Bound fields: allregions
  - Bound value range(s): allregions (0 to 3)
  - Source worksheet(s): HTH_FLO
  - Processes limited:
    - I*CAF*BLR*N
    - I*CAF*CHP*N
    - I*CAF*DRR*N
    - I*CAF*OVN*N

- **Constraint name: CAFHTH**
  - Attribute(s): Share-O
  - Bound fields: allregions
  - Bound value range(s): allregions (0 to 3)
  - Source worksheet(s): HTH_FLO
  - Processes limited:
    - I*CAF*BLR*N
    - I*CAF*CHP*N
    - I*CAF*DRR*N
    - I*CAF*OVN*N

- **Constraint name: CAFLTH**
  - Attribute(s): Share-O
  - Bound fields: allregions
  - Bound value range(s): allregions (0 to 3)
  - Source worksheet(s): HTH_FLO
  - Processes limited:
    - I*CAF*BLR*N
    - I*CAF*CHP*N
    - I*CAF*DRR*N
    - I*CAF*OVN*N

- **Constraint name: CAFMTH**
  - Attribute(s): Share-O
  - Bound fields: allregions
  - Bound value range(s): allregions (0 to 3)
  - Source worksheet(s): HTH_FLO
  - Processes limited:
    - I*CAF*BLR*N
    - I*CAF*CHP*N
    - I*CAF*DRR*N
    - I*CAF*OVN*N

- **Constraint name: CEMHET**
  - Attribute(s): Share-O
  - Bound fields: allregions
  - Bound value range(s): allregions (0 to 3)
  - Source worksheet(s): HTH_FLO
  - Processes limited:
    - I*CEM*DRR**N
    - I*CEM*KLN*N

- **Constraint name: CEMHTH**
  - Attribute(s): Share-O
  - Bound fields: allregions
  - Bound value range(s): allregions (0 to 3)
  - Source worksheet(s): HTH_FLO
  - Processes limited:
    - I*CEM*DRR**N
    - I*CEM*KLN*N

- **Constraint name: CEMLTH**
  - Attribute(s): Share-O
  - Bound fields: allregions
  - Bound value range(s): allregions (0 to 3)
  - Source worksheet(s): HTH_FLO
  - Processes limited:
    - I*CEM*DRR**N
    - I*CEM*KLN*N

- **Constraint name: CEMMTH**
  - Attribute(s): Share-O
  - Bound fields: allregions
  - Bound value range(s): allregions (0 to 3)
  - Source worksheet(s): HTH_FLO
  - Processes limited:
    - I*CEM*DRR**N
    - I*CEM*KLN*N

- **Constraint name: FAPHET**
  - Attribute(s): Share-O
  - Bound fields: allregions
  - Bound value range(s): allregions (0 to 3)
  - Source worksheet(s): HTH_FLO
  - Processes limited:
    - I*FAP*BLR*N
    - I*FAP*CHP*N
    - I*FAP*DRR*N
    - I*FAP*OVN*N

- **Constraint name: FAPHTH**
  - Attribute(s): Share-O
  - Bound fields: allregions
  - Bound value range(s): allregions (0 to 3)
  - Source worksheet(s): HTH_FLO
  - Processes limited:
    - I*FAP*BLR*N
    - I*FAP*CHP*N
    - I*FAP*DRR*N
    - I*FAP*OVN*N

- **Constraint name: FAPLTH**
  - Attribute(s): Share-O
  - Bound fields: allregions
  - Bound value range(s): allregions (0 to 3)
  - Source worksheet(s): HTH_FLO
  - Processes limited:
    - I*FAP*BLR*N
    - I*FAP*CHP*N
    - I*FAP*DRR*N
    - I*FAP*OVN*N

- **Constraint name: FAPMTH**
  - Attribute(s): Share-O
  - Bound fields: allregions
  - Bound value range(s): allregions (0 to 3)
  - Source worksheet(s): HTH_FLO
  - Processes limited:
    - I*FAP*BLR*N
    - I*FAP*CHP*N
    - I*FAP*DRR*N
    - I*FAP*OVN*N

- **Constraint name: LIMHET**
  - Attribute(s): Share-O
  - Bound fields: allregions
  - Bound value range(s): allregions (0 to 3)
  - Source worksheet(s): HTH_FLO
  - Processes limited:
    - I*LIM*FRN*N
    - I*LIM*KLN*N
    - I*LIM*OKL*N

- **Constraint name: LIMHTH**
  - Attribute(s): Share-O
  - Bound fields: allregions
  - Bound value range(s): allregions (1 to 3)
  - Source worksheet(s): HTH_FLO
  - Processes limited:
    - I*LIM*FRN*N
    - I*LIM*KLN*N
    - I*LIM*OKL*N

- **Constraint name: LIMLTH**
  - Attribute(s): Share-O
  - Bound fields: allregions
  - Bound value range(s): allregions (0 to 3)
  - Source worksheet(s): HTH_FLO
  - Processes limited:
    - I*LIM*FRN*N
    - I*LIM*KLN*N
    - I*LIM*OKL*N

- **Constraint name: LIMMTH**
  - Attribute(s): Share-O
  - Bound fields: allregions
  - Bound value range(s): allregions (0 to 3)
  - Source worksheet(s): HTH_FLO
  - Processes limited:
    - I*LIM*FRN*N
    - I*LIM*KLN*N
    - I*LIM*OKL*N

- **Constraint name: MAPHET**
  - Attribute(s): Share-O
  - Bound fields: allregions
  - Bound value range(s): allregions (0 to 3)
  - Source worksheet(s): HTH_FLO
  - Processes limited:
    - I*MAP*BLR*N
    - I*MAP*CHP*N
    - I*MAP*FRN*N

- **Constraint name: MAPHTH**
  - Attribute(s): Share-O
  - Bound fields: allregions
  - Bound value range(s): allregions (0 to 3)
  - Source worksheet(s): HTH_FLO
  - Processes limited:
    - I*MAP*BLR*N
    - I*MAP*CHP*N
    - I*MAP*FRN*N

- **Constraint name: MAPLTH**
  - Attribute(s): Share-O
  - Bound fields: allregions
  - Bound value range(s): allregions (0 to 3)
  - Source worksheet(s): HTH_FLO
  - Processes limited:
    - I*MAP*BLR*N
    - I*MAP*CHP*N
    - I*MAP*FRN*N

- **Constraint name: MAPMTH**
  - Attribute(s): Share-O
  - Bound fields: allregions
  - Bound value range(s): allregions (0 to 3)
  - Source worksheet(s): HTH_FLO
  - Processes limited:
    - I*MAP*BLR*N
    - I*MAP*CHP*N
    - I*MAP*FRN*N

- **Constraint name: OMAHET**
  - Attribute(s): Share-O
  - Bound fields: allregions
  - Bound value range(s): allregions (0 to 3)
  - Source worksheet(s): HTH_FLO
  - Processes limited:
    - I*OMA*BLR*N
    - I*OMA*CHP*N
    - I*OMA*DRR*N
    - I*OMA*FRN*N
    - I*OMA*OVN*N

- **Constraint name: OMAHTH**
  - Attribute(s): Share-O
  - Bound fields: allregions
  - Bound value range(s): allregions (0 to 3)
  - Source worksheet(s): HTH_FLO
  - Processes limited:
    - I*OMA*BLR*N
    - I*OMA*CHP*N
    - I*OMA*DRR*N
    - I*OMA*FRN*N
    - I*OMA*OVN*N

- **Constraint name: OMALTH**
  - Attribute(s): Share-O
  - Bound fields: allregions
  - Bound value range(s): allregions (0 to 3)
  - Source worksheet(s): HTH_FLO
  - Processes limited:
    - I*OMA*BLR*N
    - I*OMA*CHP*N
    - I*OMA*DRR*N
    - I*OMA*FRN*N
    - I*OMA*OVN*N

- **Constraint name: OMAMTH**
  - Attribute(s): Share-O
  - Bound fields: allregions
  - Bound value range(s): allregions (0 to 3)
  - Source worksheet(s): HTH_FLO
  - Processes limited:
    - I*OMA*BLR*N
    - I*OMA*CHP*N
    - I*OMA*DRR*N
    - I*OMA*FRN*N
    - I*OMA*OVN*N

- **Constraint name: ONMHET**
  - Attribute(s): Share-O
  - Bound fields: allregions
  - Bound value range(s): allregions (0 to 3)
  - Source worksheet(s): HTH_FLO
  - Processes limited:
    - I*ONM*BLR*N
    - I*ONM*DRR*N
    - I*ONM*OKL*N

- **Constraint name: ONMHTH**
  - Attribute(s): Share-O
  - Bound fields: allregions
  - Bound value range(s): allregions (0 to 3)
  - Source worksheet(s): HTH_FLO
  - Processes limited:
    - I*ONM*BLR*N
    - I*ONM*DRR*N
    - I*ONM*OKL*N

- **Constraint name: ONMLTH**
  - Attribute(s): Share-O
  - Bound fields: allregions
  - Bound value range(s): allregions (0 to 3)
  - Source worksheet(s): HTH_FLO
  - Processes limited:
    - I*ONM*BLR*N
    - I*ONM*DRR*N
    - I*ONM*OKL*N

- **Constraint name: ONMMTH**
  - Attribute(s): Share-O
  - Bound fields: allregions
  - Bound value range(s): allregions (0 to 3)
  - Source worksheet(s): HTH_FLO
  - Processes limited:
    - I*ONM*BLR*N
    - I*ONM*DRR*N
    - I*ONM*OKL*N

- **Constraint name: REFHET**
  - Attribute(s): Share-O
  - Bound fields: allregions
  - Bound value range(s): allregions (0 to 3)
  - Source worksheet(s): HTH_FLO
  - Processes limited:
    - \I:  I*REF*BLR*GAS**N
    - \I:  I*REF*CHP*GAS**N
    - \I:  I*REF*FRN*GAS**N

- **Constraint name: REFHTH**
  - Attribute(s): Share-O
  - Bound fields: allregions
  - Bound value range(s): allregions (0 to 3)
  - Source worksheet(s): HTH_FLO
  - Processes limited:
    - \I:  I*REF*BLR*GAS**N
    - \I:  I*REF*CHP*GAS**N
    - \I:  I*REF*FRN*GAS**N

- **Constraint name: REFLTH**
  - Attribute(s): Share-O
  - Bound fields: allregions
  - Bound value range(s): allregions (0 to 3)
  - Source worksheet(s): HTH_FLO
  - Processes limited:
    - \I:  I*REF*BLR*GAS**N
    - \I:  I*REF*CHP*GAS**N
    - \I:  I*REF*FRN*GAS**N

- **Constraint name: REFMTH**
  - Attribute(s): Share-O
  - Bound fields: allregions
  - Bound value range(s): allregions (1 to 3)
  - Source worksheet(s): HTH_FLO
  - Processes limited:
    - \I:  I*REF*BLR*GAS**N
    - \I:  I*REF*CHP*GAS**N
    - \I:  I*REF*FRN*GAS**N

- **Constraint name: WAPHET**
  - Attribute(s): Share-O
  - Bound fields: allregions
  - Bound value range(s): allregions (0 to 3)
  - Source worksheet(s): HTH_FLO
  - Processes limited:
    - I*WAP*BLR*N
    - I*WAP*DRR*N

- **Constraint name: WAPHTH**
  - Attribute(s): Share-O
  - Bound fields: allregions
  - Bound value range(s): allregions (0 to 3)
  - Source worksheet(s): HTH_FLO
  - Processes limited:
    - I*WAP*BLR*N
    - I*WAP*DRR*N

- **Constraint name: WAPLTH**
  - Attribute(s): Share-O
  - Bound fields: allregions
  - Bound value range(s): allregions (1 to 3)
  - Source worksheet(s): HTH_FLO
  - Processes limited:
    - I*WAP*BLR*N
    - I*WAP*DRR*N

- **Constraint name: WAPMTH**
  - Attribute(s): Share-O
  - Bound fields: allregions
  - Bound value range(s): allregions (0 to 3)
  - Source worksheet(s): HTH_FLO
  - Processes limited:
    - I*WAP*BLR*N
    - I*WAP*DRR*N

## Notes
- This documentation intentionally describes purpose and functionality without listing spreadsheet cell ranges.
- Naming suggests this file is part of a larger linked input set; keep workbook names and paths stable when integrating updates.
