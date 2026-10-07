# Scen_TRA_P_ModalShares_LED.xlsx

## Purpose
This workbook supports the TIMES Ireland model as part of **Transport**. It is used to define, adjust, or parameterize scenario assumptions and model behavior for its domain.

## Functional role in the model workflow
- Serves as an input artifact consumed by the model data-preparation process.
- Encodes structured assumptions that can vary by scenario, policy case, or technology pathway.
- Organizes data so updates can be managed without changing model code.

## Workbook structure
- Total worksheets: **7**
- Worksheets are grouped below by their likely functional theme based on sheet naming and content cues.

### General input tables
- **Cover**
  - Content cues: TIMES-Ireland Model; Document type:; Scenario; Sector(s):
  - Likely use: stores structured assumptions or mappings used during scenario assembly and model execution.
- **Regions**
  - Content cues: IE; National; IE-CW; IE-D
  - Likely use: stores structured assumptions or mappings used during scenario assembly and model execution.
- **ShortRange**
  - Content cues: User constraints for modal share in passenger transport; ~UC_Sets: R_E:AllRegions; ~UC_Sets: T_E:; ~UC_T:UC_COMPRD
  - Likely use: stores structured assumptions or mappings used during scenario assembly and model execution.
- **MediumRange**
  - Content cues: User constraints for modal share in passenger transport; ~UC_Sets: R_E:AllRegions; ~UC_Sets: T_E:; ~UC_T:UC_COMPRD
  - Likely use: stores structured assumptions or mappings used during scenario assembly and model execution.
- **LongRange**
  - Content cues: User constraints for modal share in passenger transport; ~UC_Sets: R_E:AllRegions; ~UC_Sets: T_E:; ~UC_T:UC_COMPRD
  - Likely use: stores structured assumptions or mappings used during scenario assembly and model execution.
- **TOPINS**
  - Content cues: ~TFM_TOPINS; TimeSlice; LimType; Attribute
  - Likely use: stores structured assumptions or mappings used during scenario assembly and model execution.
- **common**
  - Content cues: Vehicle type (Existing technologies); End-use technologies; Description; Passengers
  - Likely use: stores structured assumptions or mappings used during scenario assembly and model execution.

## User constraints and bounds
- **Constraint name: 0**
  - Attribute(s): 0, 2.1586268841599747E-3, 8.4181954391599476E-4
  - Source worksheet(s): LongRange, MediumRange, ShortRange
  - Processes limited:
    - 2-wheelers

- **Constraint name: 1.2024577456126329E-3**
  - Attribute(s): 8.4181954391599476E-4
  - Source worksheet(s): ShortRange
  - Processes limited:
    - 2-wheelers

- **Constraint name: 3.2739468688573266E-3**
  - Attribute(s): 2.1586268841599747E-3
  - Source worksheet(s): MediumRange
  - Processes limited:
    - 2-wheelers

- **Constraint name: TRAPL**
  - Source worksheet(s): LongRange
  - Processes limited:
    - T-BUS*
    - T-CAR*
    - T-HPT*
    - T-TAX*

- **Constraint name: TRAPM**
  - Source worksheet(s): MediumRange, TOPINS
  - Processes limited:
    - T-BUS*
    - T-CAR*
    - T-CYC_CYC
    - T-HPT*
    - T-LPT*
    - T-MOT*
    - T-TAX*

- **Constraint name: TRAPS**
  - Source worksheet(s): ShortRange
  - Processes limited:
    - T-BUS*
    - T-CAR*
    - T-CYC_CYC
    - T-LPT*
    - T-MOT*
    - T-TAX*
    - T-WLK_WLK

## Notes
- This documentation intentionally describes purpose and functionality without listing spreadsheet cell ranges.
- Naming suggests this file is part of a larger linked input set; keep workbook names and paths stable when integrating updates.
