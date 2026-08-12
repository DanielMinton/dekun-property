# DOCUMENT-MAP — every file, its ID, status, and provenance

**As of:** 2026-08-12 (updated same day after reorganization). Paths relative to
`D:\DEKUN PROPERTY\`. Hashes in `HASHES.sha256`. IDs are semantic and stable — cite them from
FACTS.md, TIMELINE.md, OPEN-ITEMS.md.

## Repository structure (2026-08-12 reorganization — files moved, never edited; all hashes re-verified post-move)

```
D:\DEKUN PROPERTY\
├── _CONTEXT\           fact layer: this map, FACTS, TIMELINE, ENTITIES, OPEN-ITEMS, HASHES
├── 01_EVIDENCE\        source documents ONLY, never edited (see its README)
│   ├── contracts\  insurance-payments\  contractor-billing\
│   ├── correspondence\  regulatory\  owner-payments\ (collection targets, empty)
├── 02_ANALYSIS\        derived work product (findings v1/v2, timeline PDF)
├── 03_OUTBOUND\        sanitized deliverables staging — 4-point gate in its README
├── 04_COUNSEL\         attorney packet staging — checklist vs INT-RECON §20 in its README
├── 05_ARCHIVE\         _removed\ quarantine + dekun-property-export\ (stale claude.ai export)
├── INTERNAL ONLY\      tier document (unchanged)
├── MASTER RECORD\      tier document (unchanged)
└── MANIFEST.md         historical manifest (unchanged — see note in its row below)
```

## Evidentiary source documents — `01_EVIDENCE\`

Subfolder per row: contracts (CO1–CO3) · insurance-payments (SFPAY) · contractor-billing (STMT) ·
correspondence (EMAIL) · regulatory (CSLB).

| ID | File | What it is | Status / notes |
|---|---|---|---|
| **CO1** | `contracts\2025-11-28_CO1_code-upgrades_7012.90_signed-2025-12-11_with-SF-estimate.pdf` | Change Order #1, $7,012.90, signed 2025-12-11 16:36 PST. 30 pp. | VERIFIED signed instrument. **Pages 2–30 = full State Farm estimate 05-80C1-98PC (supplement 2025-09-30)** — the source for all paint-scope and covered-scope questions. Doubles as the SF-estimate evidence file. |
| **CO2** | `contracts\2025-12-11_CO2_owner-upgrades_57817.97_signed-2025-12-11.pdf` | Change Order #2, $57,817.97 owner-funded, signed 2025-12-11 23:08 PST. 11 pp. | VERIFIED signed instrument. Contains the $12,800 engineering line and $4,310.50 hazardous-material line (both CLAIMED–UNSUPPORTED as to backup). References Dry1Out estimate `CUSTOMER_UPGRADES` dated 2025-10-23. |
| **CO3** | `contracts\2026-06-16_CO3_plumbing-electrical-cabinets_4380.00_signed-2026-06-23.pdf` | Change Order #3, $4,380.00, signed 2026-06-23. Completion date 7/10/2026. | VERIFIED signed instrument. Pages 2–5 = Exhibit A-1 kitchen elevations. Countertop upgrade expressly unpriced ("once obtained"). |
| **SFPAY-1** | `insurance-payments\2025-04-10_SFPAY_102742525J_6960.28_cashed_asbestos.png` | SF payment 102742525J, $6,960.28, cashed. | VERIFIED as to issuance. "Asbestos" label is owner-side attribution, not on the document face. Byte-identical to export copy. |
| **SFPAY-2** | `insurance-payments\2025-05-02_SFPAY_102759073J_54187.10_cashed_main-estimate.png` | SF payment 102759073J, $54,187.10, cashed. | VERIFIED as to issuance. "Main estimate" is owner-side attribution. Byte-identical to export copy. |
| **SFPAY-3** | `insurance-payments\2026-02-04_SFPAY_102938678J_7274.77_UNCASHED_code-upgrades.png` | SF payment 102938678J, $7,274.77, **uncashed**. | VERIFIED as to issuance. Now >6 months old — stale-date risk (R-014). Byte-identical to export copy. |
| **STMT-1169** | `contractor-billing\2026-08-11_STMT_Dry1Out-1169_53749.06.pdf` | Dry1Out Statement #1169, dated 08/11/2026, total due $53,749.06. | VERIFIED as to what Dry1Out asserts. **Read line-by-line 2026-08-12 — full ledger transcribed in FACTS.md §3.** Supersedes the "statement PDF still unread" note in EXP-RECON. Byte-identical duplicate in `_removed/`. |
| **CSLB-0810** | `regulatory\2026-08-10_CSLB_license-993442_SUSPENDED_civil-judgment.png` | CSLB license-detail capture, retrieved 2026-08-10 13:04:02. Status: suspended, outstanding civil judgment. | VERIFIED as to status on 8/10/26 only. License number NOT in frame (tied to #993442 by name+address match). No effective date. No workers'-comp panel. Hash matches MANIFEST record. **Operative copy** — pixel-identical to EXP-CSLB (verified 2026-08-12, D-4 resolved); retains native Apple chunk signature consistent with Messages-attachment provenance. |
| **EMAIL-0810** | `correspondence\2026-08-10_EMAIL_thread-export_CO5-reminder_33pp.pdf` | Thread export, 33 pp, generated 2026-08-10 12:35 PDT. "Re: Reminder: Waiting for you to sign … Change order #5". | VERIFIED correspondence record. Contains Charles 8/5 22:19 "we have not yet received your bank wire" + delay attribution. |
| **EMAIL-0812** | `correspondence\2026-08-12_EMAIL_paint-selections-coordination_7pp.pdf` | "Re: Dekun Project: Paint Selections & Project Coordination," 7 pp, landscape, thread 8/6→8/12. | VERIFIED correspondence record; complete copy, verified page-by-page per MANIFEST. Defective portrait rendering quarantined (Q-PORTRAIT). |

## Analysis / work product — `02_ANALYSIS\` (NOT source documents)

| ID | File | Status / notes |
|---|---|---|
| **FIND-1.0** | `2026-08-10_ANALYSIS_findings-v1.0_INTERNAL-DRAFT_3pp.pdf` | SUPERSEDED IN PART by FIND-2.0 (CSLB downgraded to VERIFY) and by FACTS.md discrepancy D-1. Retains unique content: prioritized action list, double-billing line-item detail. Adversarial framing — internal historical artifact only. |
| **FIND-2.0** | `2026-08-10_ANALYSIS_findings-v2.0_condensed_2pp.pdf` | Measured-tone condensed review. Its "VERIFY" flag on CSLB status is satisfied as to 8/10 status (CSLB-0810), open as to effective date. Carries the $30,930.86 framing — see FACTS.md D-1. |
| **TL-0812** | `2026-08-12_ANALYSIS_master-timeline.pdf` | Timeline infographic. Carries the "$30,930.86 unexplained credit gap" — superseded on that point by FACTS.md D-1. Raster duplicates quarantined (Q-TL-PNG, Q-TL-WEBP). |
| **MANIFEST** | `MANIFEST.md` (root) | Document manifest. **Rev 2, 2026-08-12:** now pulls from FACTS.md — reconciliation table corrected (D-1 decomposition, $8,230.86 headline), location note added for the reorganized tree, CSLB pixel-identity corroboration added, open items handed off to OPEN-ITEMS.md with rev-1 text preserved. Rev 1 at git `cc95e52`. Its `_removed` verification notes remain the authoritative account of the quarantine decisions. |

## Tier documents

| ID | File | Status / notes |
|---|---|---|
| **INT-RECON** | `INTERNAL ONLY\DANIEL & ANNE'S ABSOLUTELY-NOT-FOR-DRY1OUT MASTER RECONCILIATION.md` | Internal analysis. **Rev 2, 2026-08-12:** pulls from FACTS.md — §7 rebuilt around the D-1 decomposition (rev-1 text preserved in place, marked superseded), §5 posting facts + F-4 wire observation, §6 caution on the $23,218.05 reference point, §8/§16/§21 updated, §18 hands the live register to OPEN-ITEMS.md. §17 classification vocabulary remains adopted project-wide. Rev 1 at git `cc95e52`. |
| **MR** | `MASTER RECORD\Dekun Property Master Record.md` | Sanitized consolidated record. **Rev 2, 2026-08-12:** now pulls from FACTS.md — §6 rebuilt around the statement #1169 ledger with the $30,930.86 identification recorded as a historical note per its own §13 rule; §5 posting facts, §11 statuses, §12 snapshot updated. Rev 1 at git `cc95e52`. |

## `03_OUTBOUND\` — deliverables

| ID | File | Status / notes |
|---|---|---|
| **OUT-DRAFT-1** | `2026-08-12_DRAFT_records-follow-up_Charles.md` | Records follow-up, Daniel's voice, reply-all on the paint-coordination thread. **DRAFT — staged, not sent.** Passed all four gate checks 2026-08-12 (review recorded below the cut line in the file). Recommended hold until R-012 (owner bank/escrow records); re-run gate check 1 if facts change before sending. Supersedes the archived rev-1 draft in EXP-RECON, which fails gate 1. |

## `05_ARCHIVE\_removed\` — quarantine (retained deliberately, provenance artifacts)

| ID | File | Reason |
|---|---|---|
| **Q-STMT-DUP** | `DUP-byte-identical_Anne Dekun statement from Dry1Out.pdf` | Byte-identical to STMT-1169 (hash 636DAA2C… matches — confirmed 2026-08-12). Zero information loss. |
| **Q-PORTRAIT** | `DEFECTIVE-right-margin-truncated_Re_Dekun-Project_portrait_7pp.pdf` | Defective portrait rendering of EMAIL-0812 thread; right margin clipped on every text page. Do not cite. Provenance only. |
| **Q-TL-PNG** | `DUP-format_Dekun_Project_Timeline.png` | Raster export of TL-0812 (PDF is vector + text-searchable, strictly superior). |
| **Q-TL-WEBP** | `DUP-format_Dekun_Project_Timeline_lossless.webp` | Same as above, webp. |

Also recorded in MANIFEST: three iPhone Settings screenshots (IMG_0001–0003.PNG, 8/10 12:11–12:12)
were **deleted** on review — device-identifier exposure, no project content. Deletion is documented
there; noted here so the record of the deletion survives any future MANIFEST revision.

## `05_ARCHIVE\dekun-property-export\` — claude.ai project export (partially stale)

Its own git history (one commit, the 2026-08-12 export) is preserved at `.git-archive\` —
renamed from `.git` on 2026-08-12 so the outer repository (initialized that day, root commit
`cc95e52`) tracks the export's files directly instead of holding an untracked embedded repo.

| ID | File | Status / notes |
|---|---|---|
| **EXP-PROJECT** | `PROJECT.md` | The analysis charter / working instructions. Current and adopted — this is the project's operating doctrine. |
| **EXP-README** | `README.md` | Export limitations. **Stale in one respect:** says the statement PDF is unread/absent — STMT-1169 has since been obtained and read (2026-08-12). |
| **EXP-RECON** | `docs\2026-08-12 Reconciliation and draft reply to Charles.md` | Thread chronology (absorbed into TIMELINE.md) + verified arithmetic + draft reply. **Stale in two respects:** "statement PDF itself still unread" — now read; and the $30,930.86 framing — superseded by FACTS.md D-1. The draft reply's request list predates the ledger reading. |
| **EXP-CSLB** | `files\images\Screenshot 20260810 at 1.04.02PM.png` | Second copy of the 8/10 CSLB capture. Not byte-identical to CSLB-0810, but **pixel-identical** (verified 2026-08-12: decoded buffers SHA-256 match; difference is export-pipeline re-encode of the PNG container only — R-019 closed, D-4). Corroborates CSLB-0810; cite CSLB-0810 as operative. |
| **EXP-SFPAY-1/2/3** | `files\images\State Farm direct payment *.png` | Byte-identical to SFPAY-1/2/3. Corroborates root copies' provenance (two independent paths, same bytes). |
| **EXP-TXT-\*** | `files\pdf-text-extracts\*.txt` | Text layers of CO1, CO2, CO3, findings 1.0/2.0. NOT originals — no layout/signatures/images. Useful for grep; cite the PDFs, not these. |
| — | `files\originals\` | Empty (`.gitkeep`). The export README's instruction to populate it is now partially satisfiable from root: STMT-1169 is in hand. |

## Missing documents (referenced by the record but not present anywhere in the repository)

| Missing item | Referenced by | Open item |
|---|---|---|
| **Original contract ($54,448.97)** — the base instrument for every total | MANIFEST, INT-RECON, MR, EXP-RECON | R-015 |
| Invoice #7700131 ($115,428.98, dated 06/03/2025) — the statement's entire opening balance | STMT-1169 face | R-016 |
| Invoice #6780972 ($39,917.96) | MANIFEST, MR §7 | R-016 |
| CO5 (unsigned, pricing undisclosed) | EMAIL-0810 | R-021 (do not sign) |
| `Dry1Out ledger.pdf` (image-only scan; existed in claude.ai project, no bytes here) | EXP-README | R-016 |
| `Charles Correspondence 8_12_2026.pdf` (same) | EXP-README | R-022 |
| Escrow / draw records; $32,000 negotiated-check image; final wire record | INT-RECON §5, §19 | R-012, MANIFEST item 5 |
| CSLB certified license history w/ suspension effective date | MANIFEST item 1 | R-013 |

## Non-substantive files

`._*` AppleDouble sidecars (root and hidden), `.__removed`, `desktop.ini`, `.gitkeep` — macOS/Windows
filesystem artifacts. Harmless; excluded from hashing. Their presence confirms this folder has moved
between macOS and Windows — see R-020 (confirm whether any uncontrolled cloud-sync copy exists).
The root `._*` sidecars were left in place during the reorganization; they are orphaned junk, not data.
`.idea\` — JetBrains IDE metadata, appeared 2026-08-12 ~14:00 when the folder was opened in an IDE.
Not project data; excluded from hashing.
