# Scen_B_SYS_Historic_Bounds.xlsx

## Purpose
This workbook supports the TIMES Ireland model as part of **System and policy assumptions**. It is used to define, adjust, or parameterize scenario assumptions and model behavior for its domain.

## Functional role in the model workflow
- Serves as an input artifact consumed by the model data-preparation process.
- Encodes structured assumptions that can vary by scenario, policy case, or technology pathway.
- Organizes data so updates can be managed without changing model code.

## Workbook structure
- Total worksheets: **23**
- Worksheets are grouped below by their likely functional theme based on sheet naming and content cues.

### Controls and configuration
- **CO2-config**
  - Content cues: UC_N; UC_Emissions_CO2_2020; UC_desc; CO2 Emissions in 2020
  - Likely use: stores structured assumptions or mappings used during scenario assembly and model execution.

### Emissions and carbon constraints
- **CO2-NET-multi**
  - Content cues: UC - All Regions/Each Period; ~UC_Sets: R_S: National,IE-CW,IE-D,IE-KE,IE-KK,IE-LS,IE-LD,IE-LH,IE-MH,IE-OY,IE-WH,IE-WX,IE-WW,IE-CE,IE-CO,IE-KY,IE-LK,I; ~UC_Sets: T_S:; ~UC_T
  - Likely use: stores structured assumptions or mappings used during scenario assembly and model execution.
- **CO2-NET-single**
  - Content cues: UC - Each Region/All Periods; ~UC_Sets: R_E: IE; ~UC_Sets: T_S:; ~UC_T
  - Likely use: stores structured assumptions or mappings used during scenario assembly and model execution.

### General input tables
- **Cover**
  - Content cues: TIMES-Ireland Model; Document type:; Scenario; Sector(s):
  - Likely use: stores structured assumptions or mappings used during scenario assembly and model execution.
- **Regions**
  - Content cues: IE; National; IE-CW; IE-D
  - Likely use: stores structured assumptions or mappings used during scenario assembly and model execution.
- **SUP**
  - Content cues: UC - Each Region/All Periods; ~UC_Sets: R_E: IE,National; ~UC_Sets: T_S:; ~UC_T
  - Likely use: stores structured assumptions or mappings used during scenario assembly and model execution.
- **PWR**
  - Content cues: Calibration margin; 0.05; deact~TFM_INS-TS; ~TFM_INS-TS
  - Likely use: stores structured assumptions or mappings used during scenario assembly and model execution.
- **PWR-CAPs**
  - Content cues: ~UC_Sets: R_E: IE,National; ~UC_Sets: T_S:; ~UC_T; UC_N
  - Likely use: stores structured assumptions or mappings used during scenario assembly and model execution.
- **AGR**
  - Content cues: ~TFM_INS-TS; LimType; PSET_PN; Attribute
  - Likely use: stores structured assumptions or mappings used during scenario assembly and model execution.
- **IND**
  - Content cues: Calibration margin; 0.2; deact~TFM_INS-TS; ~TFM_INS-TS
  - Likely use: stores structured assumptions or mappings used during scenario assembly and model execution.
- **RSD**
  - Content cues: Calibration margin; 0.02; deact~TFM_INS-TS; ~TFM_INS-TS
  - Likely use: stores structured assumptions or mappings used during scenario assembly and model execution.
- **SRV**
  - Content cues: Calibration margin; 0.03; deact~TFM_INS-TS; ~TFM_INS-TS
  - Likely use: stores structured assumptions or mappings used during scenario assembly and model execution.
- **TRA**
  - Content cues: UC_T; UC_N; Cset_CN; Cset_Set
  - Likely use: stores structured assumptions or mappings used during scenario assembly and model execution.
- **TRA-CAPs**
  - Content cues: NCAP for new vehicles according to actual sales in 2019; Trans - Insert; ~TFM_INS; TimeSlice
  - Likely use: stores structured assumptions or mappings used during scenario assembly and model execution.
- **EB2018**
  - Content cues: 2018 Units = ktoe; NACE (Rev 2); Coal; Bituminous Coal
  - Likely use: stores structured assumptions or mappings used during scenario assembly and model execution.
- **EB2019**
  - Content cues: 2019 Units = ktoe; NACE (Rev 2); Coal; Bituminous Coal
  - Likely use: stores structured assumptions or mappings used during scenario assembly and model execution.
- **EB2020**
  - Content cues: 2020 Units = ktoe; NACE (Rev 2); Coal; Bituminous Coal
  - Likely use: stores structured assumptions or mappings used during scenario assembly and model execution.
- **EB2021**
  - Content cues: 2021 Units = ktoe; NACE (Rev 2); Coal; Bituminous Coal
  - Likely use: stores structured assumptions or mappings used during scenario assembly and model execution.
- **EB2022**
  - Content cues: 2022 Units = ktoe; NACE (Rev 2); Coal; Bituminous Coal
  - Likely use: stores structured assumptions or mappings used during scenario assembly and model execution.
- **EB2023**
  - Content cues: 2023 Units = ktoe; NACE (Rev 2); Coal; Bituminous Coal
  - Likely use: stores structured assumptions or mappings used during scenario assembly and model execution.
- **EB2024**
  - Content cues: 2024 Units = ktoe; NACE (Rev 2); Coal; Bituminous Coal
  - Likely use: stores structured assumptions or mappings used during scenario assembly and model execution.
- **Conversions**
  - Content cues: Conversion factors; 1 ktoe; 4.1868000000000002E-2; PJ
  - Likely use: stores structured assumptions or mappings used during scenario assembly and model execution.

### Technology definitions and performance
- **New vehicle sales**
  - Content cues: https://stats.beepbeep.ie/motorstats; Results based on search parameters: Year: 2020; Passenger Cars By Engine Type; Rank
  - Likely use: stores structured assumptions or mappings used during scenario assembly and model execution.

## User constraints and bounds
- **Constraint name: ELCC**
  - Source worksheet(s): SUP
  - Processes limited:
    - EXPELC*
    - IMPELC*
  - Bound setup:
    - LimType: FX
    - Year/value context: fixed at 2020 with RHS value 100

- **Constraint name: TOTCO2**
  - Source worksheet(s): CO2-NET-multi, CO2-NET-single
  - Processes limited:
    - T-A*INT*
    - T-NAV*
  - Bound setup:
    - LimType: LO
    - UC_FLO coefficient for listed processes: -1
    - RHS profile: 2018 = 0, with continuation flag set in subsequent row (value 1)

- **Constraint name: FT-TRABDL**
  - Source worksheet(s): TRA
  - Processes limited:
    - FT-TRABDL
  - Attribute limited: ACT_BND
  - Bound setup:
    - Upper trajectory values include approximately 5.6935 to 11.387

- **Constraint name: FT-TRACNG**
  - Source worksheet(s): TRA
  - Processes limited:
    - FT-TRACNG
  - Attribute limited: ACT_BND
  - Bound setup:
    - Upper trajectory values include approximately 0.72657 to 1.033707

- **Constraint name: FT-TRADST**
  - Source worksheet(s): TRA
  - Processes limited:
    - FT-TRADST
  - Attribute limited: ACT_BND
  - Bound setup:
    - Lower trajectory values include approximately 109.3345 to 136.9335

- **Constraint name: FT-TRAELC**
  - Source worksheet(s): TRA
  - Processes limited:
    - FT-TRAELC
  - Attribute limited: ACT_BND
  - Bound setup:
    - Lower trajectory values include approximately 0.369595 to 1.544

- **Constraint name: FT-TRAETH**
  - Source worksheet(s): TRA
  - Processes limited:
    - FT-TRAETH
  - Attribute limited: ACT_BND
  - Bound setup:
    - Trajectory values include approximately 0.8685 to 2.0265

- **Constraint name: FT-TRAGSL**
  - Source worksheet(s): TRA
  - Processes limited:
    - FT-TRAGSL
  - Attribute limited: ACT_BND
  - Bound setup:
    - Lower trajectory values include approximately 24.8005 to 33.196
    - Upper trajectory values include approximately 29.77695 to 36.846

- **Constraint name: FT-TRAKER**
  - Source worksheet(s): TRA
  - Processes limited:
    - FT-TRAKER
  - Attribute limited: ACT_BND
  - Bound setup:
    - Lower trajectory values include approximately 16.1155 to 45.162
    - Upper trajectory values include approximately 18.1195 to 54.5935

- **Additional TRA bounds present in same sheet**
  - FT-TRABJK (ACT_BND, UP; values include 0 to 2)
  - FT-TRABNG (ACT_BND, UP; values are 0)
  - FT-TRALNG (ACT_BND, UP; values are 0)

- **Interpretation note for TRA block**
  - In TRA rows, the explicit region field is IE; the constrained transport fuel/activity entities are represented directly by FT-TRA* names in the constraint/process columns.

## Notes
- This documentation intentionally describes purpose and functionality without listing spreadsheet cell ranges.
- Naming suggests this file is part of a larger linked input set; keep workbook names and paths stable when integrating updates.
