# VedaTags.xlsx

## Purpose
This workbook supports the TIMES Ireland model as part of **Core model configuration and templates**. It is used to define, adjust, or parameterize scenario assumptions and model behavior for its domain.

## Functional role in the model workflow
- Serves as an input artifact consumed by the model data-preparation process.
- Encodes structured assumptions that can vary by scenario, policy case, or technology pathway.
- Organizes data so updates can be managed without changing model code.

## Workbook structure
- Total worksheets: **30**
- Worksheets are grouped below by their likely functional theme based on sheet naming and content cues.

### Controls and configuration
- **tfm_csets**
  - Content cues: ~TFM_CSETS; c_neg_andor; c_neg_andor_forsets; c_pos_andor
  - Likely use: stores structured assumptions or mappings used during scenario assembly and model execution.
- **tfm_psets**
  - Content cues: ~TFM_PSETS; comment; dimension_name; pset_ci
  - Likely use: stores structured assumptions or mappings used during scenario assembly and model execution.

### General input tables
- **currencies**
  - Content cues: ~CURRENCIES; currency
  - Likely use: stores structured assumptions or mappings used during scenario assembly and model execution.
- **defunits**
  - Content cues: ~DEFUNITS; <unit type>; <unit value>
  - Likely use: stores structured assumptions or mappings used during scenario assembly and model execution.
- **fi_comm**
  - Content cues: ~FI_COMM; commdesc; commname; csets
  - Likely use: stores structured assumptions or mappings used during scenario assembly and model execution.
- **fi_t**
  - Content cues: ~FI_T; attribute; comm-in; comm-in-a
  - Likely use: stores structured assumptions or mappings used during scenario assembly and model execution.
- **milestoneyears**
  - Content cues: ~MILESTONEYEARS; <def type>; <value>
  - Likely use: stores structured assumptions or mappings used during scenario assembly and model execution.
- **nopcol**
  - Content cues: ~NOPCOL; name
  - Likely use: stores structured assumptions or mappings used during scenario assembly and model execution.
- **tfm_ava**
  - Content cues: ~TFM_AVA; pset_ci; pset_co; pset_pd
  - Likely use: stores structured assumptions or mappings used during scenario assembly and model execution.
- **tfm_comgrp**
  - Content cues: ~TFM_COMGRP; cset_cd; cset_cn; cset_set
  - Likely use: stores structured assumptions or mappings used during scenario assembly and model execution.
- **tfm_dins**
  - Content cues: ~TFM_DINS; attribute; cset_cn; currency
  - Likely use: stores structured assumptions or mappings used during scenario assembly and model execution.
- **tfm_dins-at**
  - Content cues: ~TFM_DINS-AT; <attribute>; cset_cn; currency
  - Likely use: stores structured assumptions or mappings used during scenario assembly and model execution.
- **tfm_dins-ts**
  - Content cues: ~TFM_DINS-TS; <year>; attribute; cset_cn
  - Likely use: stores structured assumptions or mappings used during scenario assembly and model execution.
- **tfm_dins-tsl**
  - Content cues: ~TFM_DINS-TSL; <time_slice>; attribute; cset_cn
  - Likely use: stores structured assumptions or mappings used during scenario assembly and model execution.
- **tfm_fill**
  - Content cues: ~TFM_FILL; attrib_cond; attribute; avc_limtype
  - Likely use: stores structured assumptions or mappings used during scenario assembly and model execution.
- **tfm_ins**
  - Content cues: ~TFM_INS; attrib_cond; attribute; avc_limtype
  - Likely use: stores structured assumptions or mappings used during scenario assembly and model execution.
- **tfm_ins-at**
  - Content cues: ~TFM_INS-AT; <attribute>; attrib_cond; avc_limtype
  - Likely use: stores structured assumptions or mappings used during scenario assembly and model execution.
- **tfm_ins-ts**
  - Content cues: ~TFM_INS-TS; <year>; attrib_cond; attribute
  - Likely use: stores structured assumptions or mappings used during scenario assembly and model execution.
- **tfm_ins-tsl**
  - Content cues: ~TFM_INS-TSL; <time_slice>; attrib_cond; attribute
  - Likely use: stores structured assumptions or mappings used during scenario assembly and model execution.
- **tfm_mig**
  - Content cues: ~TFM_MIG; attrib_cond; attribute; attribute2
  - Likely use: stores structured assumptions or mappings used during scenario assembly and model execution.
- **tfm_topdins**
  - Content cues: ~TFM_TOPDINS; cset_cn; pset_pn; region
  - Likely use: stores structured assumptions or mappings used during scenario assembly and model execution.
- **tfm_topins**
  - Content cues: ~TFM_TOPINS; c_neg_andor; c_neg_andor_forsets; c_pos_andor
  - Likely use: stores structured assumptions or mappings used during scenario assembly and model execution.
- **tfm_upd**
  - Content cues: ~TFM_UPD; attrib_cond; attribute; avc_limtype
  - Likely use: stores structured assumptions or mappings used during scenario assembly and model execution.
- **tfm_upd-at**
  - Content cues: ~TFM_UPD-AT; <attribute>; attrib_cond; avc_limtype
  - Likely use: stores structured assumptions or mappings used during scenario assembly and model execution.
- **tfm_upd-ts**
  - Content cues: ~TFM_UPD-TS; <year>; attrib_cond; attribute
  - Likely use: stores structured assumptions or mappings used during scenario assembly and model execution.
- **timeperiods**
  - Content cues: ~TIMEPERIODS; <no. of years>
  - Likely use: stores structured assumptions or mappings used during scenario assembly and model execution.
- **uc_t**
  - Content cues: ~UC_T; attrib_cond; attribute; avc_limtype
  - Likely use: stores structured assumptions or mappings used during scenario assembly and model execution.
- **unitconversion**
  - Content cues: ~UNITCONVERSION; from_unit; multiplier; to_unit
  - Likely use: stores structured assumptions or mappings used during scenario assembly and model execution.

### Reference mappings and metadata
- **bookregions_map**
  - Content cues: ~BOOKREGIONS_MAP; <workbook name>; region
  - Likely use: stores structured assumptions or mappings used during scenario assembly and model execution.

### Technology definitions and performance
- **fi_process**
  - Content cues: ~FI_PROCESS; pcg; region; sets
  - Likely use: stores structured assumptions or mappings used during scenario assembly and model execution.

## User constraints and bounds
- No explicit user constraints with process-level mappings were identified in this workbook.

## Notes
- This documentation intentionally describes purpose and functionality without listing spreadsheet cell ranges.
- Naming suggests this file is part of a larger linked input set; keep workbook names and paths stable when integrating updates.
