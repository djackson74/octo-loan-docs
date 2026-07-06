# OCTO Loan Docs

Lender proposal package for GrnBit Miracle Lake TX Phase 1 senior secured term loan.

## Current package

**Folder:** [`loan/package/`](loan/package/)  
**Stage:** Revised (Verified-ready) · **Date:** 2026-07-06

| File | Purpose |
|------|---------|
| `Cover_Letter_Revised_2026-07-06.pdf` | Introductory letter to prospective lenders |
| `Term_Sheet_Revised_2026-07-06.pdf` | Indicative balloon term sheet ($2M / $3M) |
| `Loan_Agreement_Form_Revised_2026-07-06.pdf` | Form loan agreement (counsel to finalize) |
| `Simulation_Assumptions_Schedule.pdf` | Key OCTO-optimized digital-twin inputs |
| `Key_Risks_Schedule_D.pdf` | Facility-specific risks tied to covenants |
| `Changes_Memo.pdf` | Summary of revisions from prior draft |
| `capex-quotes.json` | Locked vendor CAPEX quotes (Schedule C) |
| `manifest.json` | Package metadata and file index |

Pointer: [`loan/latest.json`](loan/latest.json)

## Regenerate

From [`octo-loan-tool`](../loan-tool):

```bash
npm run publish   # fresh dashboard pull → markdown
npm run revised   # CHRITIC-revised PDFs → loan/package/
```

## OCTO on Pi?

Not required. Document generation runs on your dev machine (Node). The Pi workspace is for local OCTO Master Control, not lender doc export.