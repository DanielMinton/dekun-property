# Dekun Property — Project Repository Export

Exported 2026-08-12 from the claude.ai Project "Dekun Property".

Purpose: local, versioned copy of the project record for the Anne Dekun fire-restoration
reconstruction (361 Arroyo Dr, S. San Francisco; State Farm claim 05-80C1-98PC;
contractor Dry1Out Restoration & Construction, job 250033BC).

## Layout

- `PROJECT.md` — project description and working instructions (the analysis charter).
- `docs/` — analysis documents written during the project. Currently:
  - `2026-08-12 Reconciliation and draft reply to Charles.md` — reconciliation state,
    verified arithmetic, the $53,749.06 test, and the draft status-board reply to Charles.
- `files/images/` — original PNG uploads, byte-for-byte:
  - State Farm direct payment 1 (asbestos, $6,960.28)
  - State Farm direct payment 2 (main estimate, $54,187.10)
  - State Farm direct payment 3 (code upgrades, $7,274.77)
  - Screenshot 2026-08-10 1:04 PM
- `files/pdf-text-extracts/` — text layers extracted from the PDF uploads (`.txt`).
  These are NOT the original PDFs; see limitations below.

## Export limitations — read this

The claude.ai project export API returns original bytes for images but only the
extracted text layer for PDFs. Consequences:

1. No original PDF bytes are in this repo. The `.txt` files preserve the text
   content (verbatim, including some garbled control-character sequences from
   obfuscated form fonts) but not layout, signatures, or images.
2. Three PDFs are image-only scans with no text layer and therefore have
   NOTHING in this repo:
   - `Anne Dekun statement from Dry1Out.pdf` (the 8/12 statement asserting $53,749.06)
   - `Dry1Out ledger.pdf`
   - `Charles Correspondence 8_12_2026.pdf`

To complete this repository, download the original PDFs from the project's file
list on claude.ai (or from their original sources: email attachments, scans) and
place them in `files/originals/`. The three scan-only PDFs above are the priority,
since they are evidentiary documents with no representation here at all.

## Versioning convention

Commit any new or updated project document with a dated message
(e.g. `2026-08-15: add CO4, update reconciliation`). Never edit an evidentiary
file in place; add corrected or superseding versions alongside with a date suffix.
