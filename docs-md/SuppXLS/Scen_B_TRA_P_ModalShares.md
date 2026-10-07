# Scen_B_TRA_P_ModalShares.xlsx

## Purpose
This workbook supports the TIMES Ireland model as part of **Transport**. It is used to define, adjust, or parameterize scenario assumptions and model behavior for its domain.

## Functional role in the model workflow
- Serves as an input artifact consumed by the model data-preparation process.
- Encodes structured assumptions that can vary by scenario, policy case, or technology pathway.
- Organizes data so updates can be managed without changing model code.

## Workbook structure
- Total worksheets: **3**
- Worksheets are grouped below by their likely functional theme based on sheet naming and content cues.

### General input tables
- **Cover**
  - Content cues: TIMES-Ireland Model; Document type:; Scenario; Sector(s):
  - Likely use: stores structured assumptions or mappings used during scenario assembly and model execution.
- **Regions**
  - Content cues: IE; National; IE-CW; IE-D
  - Likely use: stores structured assumptions or mappings used during scenario assembly and model execution.
- **UC_ModalShares**
  - Content cues: User constraints for modal share in passenger transport; UC - Each Region/Period; ~UC_Sets: R_E:AllRegions; ~UC_Sets: T_E:
  - Likely use: stores structured assumptions or mappings used during scenario assembly and model execution.

## User constraints and bounds
- **Constraint name: 0**
  - Attribute(s): 0
  - Source worksheet(s): UC_ModalShares
  - Processes limited:
    - 2.6917959872731177E-2
    - 2.9378320390882739E-2

- **Constraint name: 1.3237997918849932E-2**
  - Attribute(s): 1.1420057155050359E-2
  - Source worksheet(s): UC_ModalShares
  - Processes limited:
    - 4.6019564968395495E-2

- **Constraint name: 1.6941154698507114E-3**
  - Attribute(s): 3.2883004760979389E-3
  - Source worksheet(s): UC_ModalShares
  - Processes limited:
    - 4.1909857054726746E-3

- **Constraint name: 5.4309640711772487E-2**
  - Attribute(s): 5.216014948863501E-2
  - Source worksheet(s): UC_ModalShares
  - Processes limited:
    - 5.8279547941939784E-2

- **Constraint name: 6.2421004942624992E-4**
  - Attribute(s): 1.2422933671109623E-3
  - Source worksheet(s): UC_ModalShares
  - Processes limited:
    - 1.4316393209477573E-3

- **Constraint name: 7.3305854058422536E-3**
  - Attribute(s): 6.327365203104513E-3
  - Source worksheet(s): UC_ModalShares
  - Processes limited:
    - 2.5318479036608464E-2

- **Constraint name: 8.426286570298451E-2**
  - Attribute(s): 7.8971697728025606E-2
  - Source worksheet(s): UC_ModalShares
  - Processes limited:
    - 9.6900168790040125E-2

- **Constraint name: 9.942235039347571E-3**
  - Attribute(s): 8.7941712391293846E-3
  - Source worksheet(s): UC_ModalShares
  - Processes limited:
    - 3.2043055112662859E-2

- **Constraint name: IE-LS**
  - Attribute(s): IE-LD
  - Source worksheet(s): UC_ModalShares
  - Processes limited:
    - IE-D

- **Constraint name: TRAPL**
  - Source worksheet(s): UC_ModalShares
  - Processes limited:
    - T-BUS*
    - T-CAR*
    - T-HPT*
    - T-TAX*

- **Constraint name: TRAPM**
  - Source worksheet(s): UC_ModalShares
  - Processes limited:
    - T-BUS*
    - T-CAR*
    - T-LPT*
    - T-MOT*
    - T-TAX*

- **Constraint name: TRAPS**
  - Source worksheet(s): UC_ModalShares
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
