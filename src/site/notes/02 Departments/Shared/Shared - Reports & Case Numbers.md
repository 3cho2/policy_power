---
{"dg-publish":true,"permalink":"/02-departments/shared/shared-reports-and-case-numbers/","dgPassFrontmatter":true}
---

# 02 Departments/Shared/Shared - Reports & Case Numbers
---
server: Policy Power
type: shared_policy
---

## Standard Case Number Format (Combination Model)
> [!note]
> Shared required core + department optional add-ons. Sequence is **continuous per department**.

### Required Core (ALL reports)
`PP-YYYYMMDD-<DEPT>-####`

- PP = Policy Power
- YYYYMMDD = report date
- DEPT = SAHP / LSPD / SSCE / CIV / ADM
- #### = continuous sequence per department (does not reset)

Examples:
- `PP-20260217-LSPD-0142`
- `PP-20260217-SSCE-0068`
- `PP-20260217-SAHP-0231`

### Optional Add-Ons (department may append)
`-<TYPE>-<UNIT>`

TYPE examples: TRAFFIC, FELONY, MISD, WARRANT, AAR  
UNIT examples: ADAM-21, 2A-12, SS-310

Example:
- `PP-20260217-LSPD-0142-FELONY-ADAM-21`

### Continuous numbering rule
- Each department maintains its own running #### counter.
- If CAD/MDT auto-generates, CAD/MDT is the source of truth.
