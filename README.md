# OCTO Loan Docs

Lender proposal package for GrnBit Miracle Lake TX Phase 1 senior secured term loan.

## Current package

**Lender PDFs (select-all copy):** [`loan/package/documents/`](loan/package/documents/)  
**Reference data:** [`loan/package/reference/`](loan/package/reference/)  
**Stage:** Revised (Verified-ready) · **Date:** 2026-07-06

### documents/ — send to lenders

| File | Purpose |
|------|---------|
| `Cover_Letter_Revised_2026-07-06.pdf` | Introductory letter |
| `Term_Sheet_Revised_2026-07-06.pdf` | Indicative balloon term sheet ($2M / $3M) |
| `Loan_Agreement_Form_Revised_2026-07-06.pdf` | Form loan agreement |
| `Simulation_Assumptions_Schedule.pdf` | OCTO digital-twin inputs |
| `Key_Risks_Schedule_D.pdf` | Facility-specific risks |
| `Changes_Memo.pdf` | Revision summary |

### reference/ — internal / data room

| File | Purpose |
|------|---------|
| `PACKAGE_GUIDE.md` | **Why this package exists** — audience, per-file purpose, send order |
| `capex-quotes.json` | Locked vendor CAPEX (Schedule C) |
| `manifest.json` | Package index and simulation metadata |

Pointer: [`loan/latest.json`](loan/latest.json)

## Regenerate

From [`octo-loan-tool`](../loan-tool):

```bash
npm run revised   # PDFs → loan/package/documents/ · JSON → reference/
```