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

## Version control (initialized 2026-08-12)

The whole record is a git repository as of commit `cc95e52` (branch `master`). Configuration
is evidence-grade: `core.autocrlf=false` and `* -text` in `.gitattributes` — git never rewrites
file content. `.gitignore` excludes only OS/IDE junk (`.idea/`, `desktop.ini`, AppleDouble
sidecars). The former nested repo at `05_ARCHIVE\dekun-property-export\.git` was renamed
`.git-archive` so its 2026-08-12 export history is preserved as tracked data inside this
repository (restorable by renaming back).

**Controlled copies (R-020 inventory):** (1) this working copy on the USB drive ("Work Infra",
exFAT); (2) private GitHub repository `DanielMinton/dekun-property`
(https://github.com/DanielMinton/dekun-property, visibility PRIVATE, created and first pushed
2026-08-12) — remote `origin`, access limited to the DanielMinton account. Push after every
commit so the off-site copy stays current. No other copies are known; if one is created,
list it here.

Commit convention (from the export repo's README, adopted project-wide): dated messages,
e.g. `2026-08-15: add CO4, update reconciliation`. Commit on every substantive change —
new evidence, register updates, record revisions. Never amend or rebase published history;
corrections are new commits. Git history now provides the tamper-evidence that HASHES.sha256
bootstrapped; keep both (the hash file travels with copies that leave git).

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
