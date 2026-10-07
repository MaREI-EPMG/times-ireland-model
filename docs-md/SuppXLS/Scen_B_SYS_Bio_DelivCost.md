# Scen_B_SYS_Bio_DelivCost.xlsx

## Purpose
This workbook supports the TIMES Ireland model as part of **Supply and fuels**. It is used to define, adjust, or parameterize scenario assumptions and model behavior for its domain.

## Functional role in the model workflow
- Serves as an input artifact consumed by the model data-preparation process.
- Encodes structured assumptions that can vary by scenario, policy case, or technology pathway.
- Organizes data so updates can be managed without changing model code.

## Workbook structure
- Total worksheets: **3**
- Worksheets are grouped below by their likely functional theme based on sheet naming and content cues.

### Costs, prices, and economics
- **Delivery cost**
  - Content cues: Bioenergy delivery costs (€/GJ); Energy crops - Delivery Cost; Source: Clancy et al., The economic viability of biomass crops versus conventional agricultural systems and its potentia; ~TFM_INS-TS
  - Likely use: stores structured assumptions or mappings used during scenario assembly and model execution.

### General input tables
- **Cover**
  - Content cues: TIMES-Ireland Model; Document type:; Scenario; Sector(s):
  - Likely use: stores structured assumptions or mappings used during scenario assembly and model execution.
- **Conversions**
  - Content cues: ktoe to PJ; 4.1868000000000002E-2; toe to GJ; 41.868000000000002
  - Likely use: stores structured assumptions or mappings used during scenario assembly and model execution.

## User constraints and bounds
- **Constraint name: 6.7**
  - Attribute(s): 8.6999999999999993
  - Bound fields: 2010, 2015
  - Bound value range(s): 2010 (13 to 13), 2015 (15.2252 to 15.2252)
  - Source worksheet(s): Delivery cost
  - Processes limited:
    - Natural Gas - EU

- **Constraint name: 61**
  - Attribute(s): 108
  - Bound fields: 2010, 2015
  - Bound value range(s): 2010 (88 to 88), 2015 (96.8 to 96.8)
  - Source worksheet(s): Delivery cost
  - Processes limited:
    - Steam coal - EU

- **Constraint name: BIOCATW**
  - Attribute(s): FLO_DELIV
  - Bound fields: 2010, 2015, 2020, 2025, 2030, 2035, 2040, 2045, 2050
  - Bound value range(s): 2010 (4.14712 to 4.14712), 2015 (3.79485 to 3.79485), 2020 (3.48285 to 3.48285), 2025 (3.69421 to 3.69421), 2030 (3.80744 to 3.80744), 2035 (3.92066 to 3.92066), 2040 (4.01124 to 4.01124), 2045 (4.01124 to 4.01124), 2050 (4.01124 to 4.01124)
  - Source worksheet(s): Delivery cost
  - Processes limited:
    - MINBIOCATW*

- **Constraint name: BIOGRA**
  - Attribute(s): FLO_DELIV
  - Bound fields: 2010, 2015, 2020, 2025, 2030, 2035, 2040, 2045, 2050
  - Bound value range(s): 2010 (3.77011 to 3.77011), 2015 (3.44987 to 3.44987), 2020 (3.16623 to 3.16623), 2025 (3.35837 to 3.35837), 2030 (3.4613 to 3.4613), 2035 (3.56424 to 3.56424), 2040 (3.64659 to 3.64659), 2045 (3.64659 to 3.64659), 2050 (3.64659 to 3.64659)
  - Source worksheet(s): Delivery cost
  - Processes limited:
    - ABIOGAS1*

- **Constraint name: BIOINDF**
  - Attribute(s): FLO_DELIV
  - Bound fields: 2010, 2015, 2020, 2025, 2030, 2035, 2040, 2045, 2050
  - Bound value range(s): 2010 (4.14712 to 4.14712), 2015 (3.79485 to 3.79485), 2020 (3.48285 to 3.48285), 2025 (3.69421 to 3.69421), 2030 (3.80744 to 3.80744), 2035 (3.92066 to 3.92066), 2040 (4.01124 to 4.01124), 2045 (4.01124 to 4.01124), 2050 (4.01124 to 4.01124)
  - Source worksheet(s): Delivery cost
  - Processes limited:
    - MINBIOINDF*

- **Constraint name: BIOMSW1**
  - Attribute(s): FLO_DELIV
  - Bound fields: 2010, 2015, 2020, 2025, 2030, 2035, 2040, 2045, 2050
  - Bound value range(s): 2010 (0 to 0), 2015 (0 to 0), 2020 (0 to 0), 2025 (0 to 0), 2030 (0 to 0), 2035 (0 to 0), 2040 (0 to 0), 2045 (0 to 0), 2050 (0 to 0)
  - Source worksheet(s): Delivery cost
  - Processes limited:
    - MINBIOMSW1*

- **Constraint name: BIOMSW2**
  - Attribute(s): FLO_DELIV
  - Bound fields: 2010, 2015, 2020, 2025, 2030, 2035, 2040, 2045, 2050
  - Bound value range(s): 2010 (0 to 0), 2015 (0 to 0), 2020 (0 to 0), 2025 (0 to 0), 2030 (0 to 0), 2035 (0 to 0), 2040 (0 to 0), 2045 (0 to 0), 2050 (0 to 0)
  - Source worksheet(s): Delivery cost
  - Processes limited:
    - MINBIOMSW2*

- **Constraint name: BIOOSR**
  - Attribute(s): FLO_DELIV
  - Bound fields: 2010, 2015, 2020, 2025, 2030, 2035, 2040, 2045, 2050
  - Bound value range(s): 2010 (0 to 0), 2015 (0 to 0), 2020 (0 to 0), 2025 (0 to 0), 2030 (0 to 0), 2035 (0 to 0), 2040 (0 to 0), 2045 (0 to 0), 2050 (0 to 0)
  - Source worksheet(s): Delivery cost
  - Processes limited:
    - ABIOCRP2*

- **Constraint name: BIOPIGW**
  - Attribute(s): FLO_DELIV
  - Bound fields: 2010, 2015, 2020, 2025, 2030, 2035, 2040, 2045, 2050
  - Bound value range(s): 2010 (4.14712 to 4.14712), 2015 (3.79485 to 3.79485), 2020 (3.48285 to 3.48285), 2025 (3.69421 to 3.69421), 2030 (3.80744 to 3.80744), 2035 (3.92066 to 3.92066), 2040 (4.01124 to 4.01124), 2045 (4.01124 to 4.01124), 2050 (4.01124 to 4.01124)
  - Source worksheet(s): Delivery cost
  - Processes limited:
    - MINBIOPIGW*

- **Constraint name: BIORVO**
  - Attribute(s): FLO_DELIV
  - Bound fields: 2010, 2015, 2020, 2025, 2030, 2035, 2040, 2045, 2050
  - Bound value range(s): 2010 (0 to 0), 2015 (0 to 0), 2020 (0 to 0), 2025 (0 to 0), 2030 (0 to 0), 2035 (0 to 0), 2040 (0 to 0), 2045 (0 to 0), 2050 (0 to 0)
  - Source worksheet(s): Delivery cost
  - Processes limited:
    - MINBIORVO*

- **Constraint name: BIOTLW**
  - Attribute(s): FLO_DELIV
  - Bound fields: 2010, 2015, 2020, 2025, 2030, 2035, 2040, 2045, 2050
  - Bound value range(s): 2010 (4.14712 to 4.14712), 2015 (3.79485 to 3.79485), 2020 (3.48285 to 3.48285), 2025 (3.69421 to 3.69421), 2030 (3.80744 to 3.80744), 2035 (3.92066 to 3.92066), 2040 (4.01124 to 4.01124), 2045 (4.01124 to 4.01124), 2050 (4.01124 to 4.01124)
  - Source worksheet(s): Delivery cost
  - Processes limited:
    - MINBIOTLW*

- **Constraint name: BIOWHE**
  - Attribute(s): FLO_DELIV
  - Bound fields: 2010, 2015, 2020, 2025, 2030, 2035, 2040, 2045, 2050
  - Bound value range(s): 2010 (0 to 0), 2015 (0 to 0), 2020 (0 to 0), 2025 (0 to 0), 2030 (0 to 0), 2035 (0 to 0), 2040 (0 to 0), 2045 (0 to 0), 2050 (0 to 0)
  - Source worksheet(s): Delivery cost
  - Processes limited:
    - ABIOCRP1*

- **Constraint name: BIOWOO**
  - Attribute(s): FLO_DELIV
  - Bound fields: 2010, 2015, 2020, 2025, 2030, 2035, 2040, 2045, 2050
  - Bound value range(s): 2010 (3.77011 to 4.52413), 2015 (3.44987 to 4.13984), 2020 (3.16623 to 3.79947), 2025 (3.35837 to 4.03005), 2030 (3.4613 to 4.15357), 2035 (3.56424 to 4.27709), 2040 (3.64659 to 4.3759), 2045 (3.64659 to 4.3759), 2050 (3.64659 to 4.3759)
  - Source worksheet(s): Delivery cost
  - Processes limited:
    - ABIOCRP3*
    - ABIOCRP4*
    - ABIOFRSR*

- **Constraint name: BIOWOO1**
  - Attribute(s): FLO_DELIV
  - Bound fields: 2010, 2015, 2020, 2025, 2030, 2035, 2040, 2045, 2050
  - Bound value range(s): 2010 (4.14712 to 4.14712), 2015 (3.79485 to 3.79485), 2020 (3.48285 to 3.48285), 2025 (3.69421 to 3.69421), 2030 (3.80744 to 3.80744), 2035 (3.92066 to 3.92066), 2040 (4.01124 to 4.01124), 2045 (4.01124 to 4.01124), 2050 (4.01124 to 4.01124)
  - Source worksheet(s): Delivery cost
  - Processes limited:
    - MINBIOWOO1*

- **Constraint name: BIOWOO2**
  - Attribute(s): FLO_DELIV
  - Bound fields: 2010, 2015, 2020, 2025, 2030, 2035, 2040, 2045, 2050
  - Bound value range(s): 2010 (4.14712 to 4.14712), 2015 (3.79485 to 3.79485), 2020 (3.48285 to 3.48285), 2025 (3.69421 to 3.69421), 2030 (3.80744 to 3.80744), 2035 (3.92066 to 3.92066), 2040 (4.01124 to 4.01124), 2045 (4.01124 to 4.01124), 2050 (4.01124 to 4.01124)
  - Source worksheet(s): Delivery cost
  - Processes limited:
    - MINBIOWOO2*

- **Constraint name: BIOWOO3**
  - Attribute(s): FLO_DELIV
  - Bound fields: 2010, 2015, 2020, 2025, 2030, 2035, 2040, 2045, 2050
  - Bound value range(s): 2010 (4.14712 to 4.14712), 2015 (3.79485 to 3.79485), 2020 (3.48285 to 3.48285), 2025 (3.69421 to 3.69421), 2030 (3.80744 to 3.80744), 2035 (3.92066 to 3.92066), 2040 (4.01124 to 4.01124), 2045 (4.01124 to 4.01124), 2050 (4.01124 to 4.01124)
  - Source worksheet(s): Delivery cost
  - Processes limited:
    - MINBIOWOO3*

## Notes
- This documentation intentionally describes purpose and functionality without listing spreadsheet cell ranges.
- Naming suggests this file is part of a larger linked input set; keep workbook names and paths stable when integrating updates.
