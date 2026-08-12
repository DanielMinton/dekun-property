# Dekun Project 250033BC — Document Manifest

**Property:** 361 Arroyo Drive, South San Francisco, CA 94080
**Owner / insured:** Anne Dekun
**Contractor:** Restoration Specialists, Inc. dba Dry1Out — CSLB #993442, 2536 Barrington Ct, Hayward CA
**Contractor contact:** Charles Cordova, Director of Construction — charles@dry1out.com, (669) 232-4283
**Insurer:** State Farm, claim **05-80C1-98PC** (Fire or Lightning – Building)
**Owner's representative:** Daniel Minton (written authority granted 2026-07-10, "full decision power")

Naming convention: `YYYY-MM-DD_TYPE_descriptor_amount_status.ext`, dated by **document date**, not file date.

> **Revised 2026-08-12 (rev 2).** Figures below are reconciled to the project fact ledger,
> `_CONTEXT/FACTS.md`, which controls where any document disagrees. Files listed here now live
> in the reorganized tree — contracts, payments, billing, correspondence and regulatory captures
> under `01_EVIDENCE/`, analysis under `02_ANALYSIS/`, quarantine under `05_ARCHIVE/_removed/`;
> per-file locations in `_CONTEXT/DOCUMENT-MAP.md`. The pre-revision text of this manifest is
> preserved at git commit `cc95e52`.

---

## Contract & change orders

| File | Contents |
|---|---|
| `2025-11-28_CO1_code-upgrades_7012.90_signed-2025-12-11_with-SF-estimate.pdf` | Change Order #1, code upgrades, **$7,012.90**. Signed by Anne Dekun 2025-12-11 16:36 PST. 30 pp — **pages 2–30 are the full State Farm estimate 05-80C1-98PC** (supplement dated 2025-09-30). This is the source document for all paint-scope and covered-scope questions. |
| `2025-12-11_CO2_owner-upgrades_57817.97_signed-2025-12-11.pdf` | Change Order #2, owner-funded upgrades, **$57,817.97**. Marked "Customer out of pocket expense." References Dry1Out estimate `CUSTOMER_UPGRADES` dated 2025-10-23. Signed 2025-12-11 23:08 PST. 11 pp. Contains the $12,800 engineering line and the $4,310.50 "Hazardous Material Remediation" line. |
| `2026-06-16_CO3_plumbing-electrical-cabinets_4380.00_signed-2026-06-23.pdf` | Change Order #3, **$4,380.00** — refrigerator water line relocate $850, countertop pop-up outlets + fridge electrical $1,050, cabinet upgrades $2,480. Signed 2026-06-23. Completion date stated as **7/10/2026**. Pages 2–5 are Exhibit A-1 kitchen elevations. |

**Signed contract total: $123,659.84** = original $54,448.97 + CO1 + CO2 + CO3.
CO#5 referenced in correspondence is **unsigned and not in this set** — pricing never disclosed.

## State Farm payments

| File | Payment # | Issued | Amount | Status |
|---|---|---|---|---|
| `2025-04-10_SFPAY_102742525J_6960.28_cashed_asbestos.png` | 102742525J | 2025-04-10 | $6,960.28 | Cashed |
| `2025-05-02_SFPAY_102759073J_54187.10_cashed_main-estimate.png` | 102759073J | 2025-05-02 | $54,187.10 | Cashed |
| `2026-02-04_SFPAY_102938678J_7274.77_UNCASHED_code-upgrades.png` | 102938678J | 2026-02-04 | **$7,274.77** | **NOT CASHED** |

All three payable to `ANNE E. DEKUN & UMPQUA BANK ISAOA-ATIMA`. Each screenshot shows only
"Fire or Lightning – Building" on its face; the asbestos / main-estimate / code-upgrades labels
are **owner-side attributions, not text on the document**.

> The $7,274.77 check has been outstanding since 2026-02-04 and is the entire remaining
> insurance payment. Adjuster: Austin Wells, 844-458-4300 ext. 60147.

## Billing

| File | Contents |
|---|---|
| `2026-08-11_STMT_Dry1Out-1169_53749.06.pdf` | Dry1Out Statement **#1169**, dated 2026-08-11. Total due **$53,749.06**, entirely aged 90+ days. Ledger: Invoice #7700131 $115,428.98 (06/03/2025), less Zelle $3,500 + $2,000, payment #6231805307 $17,200, payment #96 $32,000 (07/24/2026), payment #dd $6,979.92 (08/11/2026). |

## License / regulatory

| File | Contents |
|---|---|
| `2026-08-10_CSLB_license-993442_SUSPENDED_civil-judgment.png` | CSLB Contractor's License Detail capture, retrieved **2026-08-10 13:04:02**. Recovered from a Messages attachment on 2026-08-12; original left in place, SHA-256 `bf38c71a…b66a8873`. **License Status: "License is under suspension for the following reasons: License is suspended for failure to comply with an outstanding civil judgment."** Business Information: RESTORATION SPECIALISTS INC dba DRY1OUT, 2536 Barrington Ct, Hayward CA 94545, phone (888) 379-1688. Entity: Corporation. Issue date 06/06/2014, expire date 06/30/2028. |

**What this capture establishes:** that as of 2026-08-10 the license held by the entity named on
every change order and email footer in this set was under suspension for an unsatisfied civil
judgment. Note the expire date is 2028 — this is a *suspension*, a distinct and more serious
status than a lapsed license.

**What it does not establish — read before relying on it:**

1. **The license number is not visible.** The capture is cropped to begin at the "Business
   Information" banner; CSLB renders the license number in a header above that. The document is
   tied to #993442 by exact business-name and address match, not on its own face. A re-pull
   showing the number in frame would be materially stronger.
2. **No suspension effective date.** Still the decisive missing fact — see open item 1.
3. **No Workers' Compensation panel.** The "code 9008 / Janitorial Services" assertion in
   `…findings-v1.0…` §1.1 remains unsupported by anything in this folder.

**Sequencing note:** this capture is timestamped 13:04 on 2026-08-10; Daniel's six-part financial
records demand in the retained email thread was sent at 13:41 the same day, 37 minutes later.

**Corroboration (added rev 2):** a second copy of this capture, exported from the claude.ai
project, was proven **pixel-identical** on 2026-08-12 (decoded image buffers hash-equal; byte
difference is PNG re-encoding only). Two independent storage paths, same image content. This
file remains the operative copy. Details: `_CONTEXT/FACTS.md` D-4.

## Correspondence

| File | Contents |
|---|---|
| `2026-08-10_EMAIL_thread-export_CO5-reminder_33pp.pdf` | Full thread export, 33 pp, generated 2026-08-10 12:35 PDT. Top message: Charles Cordova, 2026-08-05 22:19, "Re: Reminder: Waiting for you to sign Anne Dekun 250033BC Change order #5" — contains the "we have not yet received your bank wire" statement and the "city inspection corrections, scope changes, payment delays, and late material selections" delay attribution. |
| `2026-08-12_EMAIL_paint-selections-coordination_7pp.pdf` | "Re: Dekun Project : Paint Selections & Project Coordination," 7 pp, **landscape**. Top message Charles Cordova 2026-08-12 07:50 transmitting statement #1169. Thread runs 2026-08-06 → 2026-08-12 and contains: Daniel Minton's 8/6 takeover notice + five Sherwin-Williams paint selections; Charles' 8/7 08:30 paint-scope narrowing ("one color only" / "matched to the existing colors"); Daniel's 8/10 11:49 request for the approved scope document; Daniel's 8/10 13:41 six-part financial records request; Daniel's wire-trace reply. **This is the complete copy — verified page by page.** A portrait rendering of the same thread exists in `_removed/` and is defective (see below). |

## Analysis / work product — NOT source documents

| File | Contents |
|---|---|
| `2026-08-10_ANALYSIS_findings-v1.0_INTERNAL-DRAFT_3pp.pdf` | First-pass findings, 3 pp. **Internal draft — superseded in part.** Asserts CSLB #993442 suspension as established fact; v2.0 downgrades that to unverified. Contains the prioritized action list and the double-billing line-item detail not carried into v2.0. Uses adversarial framing ("documented deception") — not suitable for production or for sending to the contractor. |
| `2026-08-10_ANALYSIS_findings-v2.0_condensed_2pp.pdf` | Condensed review, 2 pp, measured tone, expressly "not legal advice." Ranks issues HIGH/MED/VERIFY and lists the five records that would resolve most open questions. This is the shareable version. |
| `2026-08-12_ANALYSIS_master-timeline.pdf` | Master timeline infographic, 1 p — money map, contract build-up, the four conflicting balance figures, and the $30,930.86 unexplained credit gap. |

## Key reconciliation

| Figure | Amount |
|---|---|
| Signed contract total | $123,659.84 |
| Insurance approved (RCV, 05-80C1-98PC) | $61,461.87 |
| Statement #1169 invoice base (Invoice #7700131, dated 06/03/2025) | $115,428.98 |
| Total payments credited on statement #1169 | $61,679.92 |
| — credited before 7/23/26 ($3,500 + $2,000 + $17,200) | $22,700.00 |
| — 7/23/26 payments as posted ($32,000 check + $6,979.92 wire) | $38,979.92 |
| Dry1Out asserted balance (statement #1169) | $53,749.06 |
| **Signed total not reflected in invoice base — unidentified, favors owner as invoiced** | **$8,230.86** |

Rev 1 of this table reported "$30,930.86 credits with no documented source." The statement
ledger identifies that figure exactly: $22,700.00 pre-July payments + $8,230.86 invoice-base
difference (`_CONTEXT/FACTS.md` D-1). The live questions are the composition and 06/03/2025
dating of invoice #7700131 (which predates every change order it must contain), the source of
the $22,700 (escrow vs. personal — owner records), and what the uninvoiced $8,230.86 is.

Four different balances asserted for the same debt in six weeks: $38,159.84 (Jun 30 demand) ·
$39,917.96 (invoice #6780972) · $31,098.99 (Dry1Out's own stated "50% of each change order" policy,
as computed) · $53,749.06 (statement of Aug 12).

## `_removed/` (now `05_ARCHIVE/_removed/`)

Quarantined, not deleted — delete the folder when you're satisfied.

| File | Reason | Verification |
|---|---|---|
| `DUP-byte-identical_Anne Dekun statement from Dry1Out.pdf` | Byte-identical to statement #1169. | SHA-256 match: `636daa2cfec82baa…3af7913`. Zero information loss. |
| `DEFECTIVE-right-margin-truncated_Re_Dekun-Project_portrait_7pp.pdf` | **Defective rendering — do not use.** Portrait print of the same thread; the right margin is clipped on every page carrying body text. | Compared page by page against the retained landscape copy. Clipped text includes, on the 8/7 Charles email, "matched to the ex—" (actual: "matched to the existing colors") and "if Anne i—" ("if Anne is interested"); on the 8/10 Daniel email, "send me the current o—" and "the $32,000 check and the—"; on the 8/7 email, "These communications shou—" and "Please advis—". Page breaks are identical in both, so the landscape copy loses nothing vertically. Kept only as a provenance artifact. |
| `DUP-format_Dekun_Project_Timeline.png` | Raster export of the retained timeline PDF. | 3840×11624 (1:3.027) vs PDF page 2880×8711 pt (1:3.025) — same graphic, uncropped. Header regions compared visually: identical layout and identical figures ($4,380.00 / $123,659.84 / $38,159.84 / $39,917.96 / $31,098.99 / $16,917.96). Not an earlier draft. |
| `DUP-format_Dekun_Project_Timeline_lossless.webp` | Raster export, same pixel dimensions as the PNG. | Same as above. The retained PDF is vector and fully text-searchable end to end, so it is strictly the superior copy. |
Three iPhone Settings screenshots (`IMG_0001–0003.PNG`, captured 2026-08-10 12:11–12:12) were
**deleted** on review. They showed VPN & Device Management and two About panes exposing the device
serial, IMEI and EID. Nothing project-related appeared on any of them; each was checked
specifically against the possibility that it was the missing CSLB record, and none was.

## Open items not resolved by anything in this folder

> **Rev 2:** the live register is `_CONTEXT/OPEN-ITEMS.md` (R-numbered, with closure history).
> The items below are preserved as written in rev 1; current statuses: item 1 remains open as
> to effective date (R-013); item 2 is reframed by the statement ledger into R-011 ($8,230.86)
> and R-016 (invoice #7700131); item 5 — the check posted 07/24/2026 as "Payment #96" on
> statement #1169, clearing evidence still open; items 3, 4, 6 unchanged (R-005, R-009/R-010,
> R-021).

1. **CSLB suspension effective date — still open, and still the decisive fact.**
   *Partially closed 2026-08-12:* the 8/10 capture cited by the timeline and findings v1.0 was
   located in a Messages attachment and is now filed as
   `2026-08-10_CSLB_license-993442_SUSPENDED_civil-judgment.png`. Suspension status as of 8/10/26
   is therefore documented, and `…findings-v2.0…`'s "VERIFY" flag is satisfied as to *current
   status* but **not** as to *effective date*.
   What remains: call CSLB at **(800) 321-2752** and obtain the date the suspension took effect.
   A status page shows only the state on the day it was pulled. The effective date is what
   determines whether the June 30 and July payment demands were made while the license was
   suspended — the question that governs whether B&P Code §7031 is engaged at all. Nothing in
   this folder answers it.
   Also worth pulling on the same call or re-capture: the **Workers' Compensation panel** (to
   support or retire the code 9008 assertion) and a capture showing the **license number in
   frame**. Ask whether CSLB will provide a certified license history — a certified record is
   what an attorney will want, not a screenshot.
2. Derivation of the $53,749.06 balance — no supporting invoices produced.
3. Scope-credit crosswalk: insurance-funded scope → owner-requested upgrade → credit applied → incremental charge.
4. Backup for the $12,800 engineering item and the $4,310.50 hazardous-material item.
5. Whether the $32,000 check (left at the house 2026-07-23) cleared — statement shows it posted 07/24/2026.
6. CO#5 — unsigned, priced, and absent from this set.
