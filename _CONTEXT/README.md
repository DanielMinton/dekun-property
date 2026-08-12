# _CONTEXT — Navigation and Fact Layer

**Created:** 2026-08-12
**Content rule:** No pre-existing file has ever been edited by this layer's maintenance —
contents remain byte-identical (verifiable against `HASHES.sha256`).
**Reorganization, 2026-08-12 (later same day):** files were MOVED (not edited) into the
numbered tree below; all 32 hashes re-verified byte-identical at their new locations
immediately after the move. `MANIFEST.md`'s paths describe the pre-reorg layout and are
historical; `DOCUMENT-MAP.md` is authoritative for locations.

```
D:\DEKUN PROPERTY\
├── _CONTEXT\        this layer — the fact/navigation spine
├── 01_EVIDENCE\     source documents only (contracts, insurance-payments,
│                    contractor-billing, correspondence, regulatory, owner-payments)
├── 02_ANALYSIS\     derived work product
├── 03_OUTBOUND\     sanitized deliverables staging (gated — see its README)
├── 04_COUNSEL\      attorney packet staging (checklist — see its README)
├── 05_ARCHIVE\      _removed quarantine + dekun-property-export
├── INTERNAL ONLY\   tier document (unchanged)
├── MASTER RECORD\   tier document (unchanged)
└── MANIFEST.md      historical manifest (unchanged)
```

## What this layer is

The project record previously asserted the same figures in six places (MANIFEST, INTERNAL ONLY,
MASTER RECORD, findings v1.0, findings v2.0, timeline PDF, export-repo reconciliation), which
allowed one figure to drift or propagate wrong. This layer fixes that by declaration, not by
rewriting:

- **Source documents remain authoritative for what they say.** Nothing here replaces a PDF.
- **`FACTS.md` is authoritative for what the project currently holds to be established.**
  Where FACTS.md and an older analysis document disagree, FACTS.md states the current position
  and cites the reason; the older document is left intact as a historical artifact.
- New figures get entered in FACTS.md first, then propagated outward — never the reverse.

## Files

| File | Purpose |
|---|---|
| `HASHES.sha256` | SHA-256 of every substantive file in the repository as of 2026-08-12. Chain-of-custody baseline. |
| `DOCUMENT-MAP.md` | Every file: ID, location, status, provenance, known defects, duplicates. The index. |
| `FACTS.md` | Single source of truth for figures and established facts, each with evidence citation and classification. Includes the discrepancy register. |
| `TIMELINE.md` | Unified chronology, each entry citing its evidence ID. |
| `ENTITIES.md` | People, organizations, accounts, and identifiers, and how they connect. |
| `OPEN-ITEMS.md` | Consolidated open-items register (R-001 onward), merging the registers previously split across MANIFEST and the internal reconciliation. |

## Update discipline

1. New document arrives → hash it, append to `HASHES.sha256`, add a row to `DOCUMENT-MAP.md`.
2. New figure or fact → enter in `FACTS.md` with citation and classification (use the
   classification vocabulary from the internal reconciliation §17: VERIFIED / CONTRACTED–FIELD
   VERIFICATION PENDING / CLAIMED–UNSUPPORTED / POTENTIAL OVERLAP / POTENTIAL DUPLICATE /
   UNPRICED–UNAUTHORIZED / RECONCILIATION REQUIRED / LEGAL REVIEW).
3. Never edit an evidentiary file. Corrections to analysis happen as dated notes in FACTS.md's
   discrepancy register, or as new dated documents alongside the old.
4. Closed open item → mark closed in `OPEN-ITEMS.md` with date and the document that closed it.
   Do not delete rows.
