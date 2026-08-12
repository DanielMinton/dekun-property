# FACTS — single source of truth for figures and established facts

**As of:** 2026-08-12. Every figure appears here once, with its evidence ID (see DOCUMENT-MAP.md)
and a classification (vocabulary from INT-RECON §17). Analysis documents should cite this file
rather than restating numbers. Where an older document disagrees, the Discrepancy Register (§8)
controls; the older document is left intact as a historical artifact.

---

## 1. Contract stack

| Instrument | Amount | Evidence | Classification |
|---|---:|---|---|
| Original contract (insurance restoration scope) | $54,448.97 | Amount attested in MANIFEST / INT-RECON / MR; **instrument itself not in repository** | CLAIMED–UNSUPPORTED as to document; amount corroborated by RCV equality (§2) — R-015 |
| CO1 — code upgrades (signed 2025-12-11 16:36) | $7,012.90 | CO1 | VERIFIED |
| CO2 — owner upgrades (signed 2025-12-11 23:08) | $57,817.97 | CO2 | VERIFIED (as instrument; line-item support open) |
| CO3 — plumbing/electrical/cabinets (signed 2026-06-23) | $4,380.00 | CO3 | VERIFIED |
| **Signed contract total through CO3** | **$123,659.84** | sum | VERIFIED arithmetic |
| Insurance-side subtotal (original + CO1) | $61,461.87 | sum | VERIFIED arithmetic |
| Owner-side gross (CO2 + CO3) | $62,197.97 | sum | VERIFIED arithmetic |
| CO5 | unknown | EMAIL-0810 (referenced, unsigned, unpriced) | UNPRICED / UNAUTHORIZED — not part of any total |

CO3 sub-items: fridge water-line relocate $850 · pop-up outlets + fridge electrical $1,050 ·
cabinet upgrades $2,480. Countertop upgrade expressly unpriced ("once obtained").
CO2 notable lines: engineering $12,800 (backup not produced — R-009) · Hazardous Material
Remediation $4,310.50 (backup not produced; do NOT equate with asbestos — R-010).

## 2. Insurance

| Item | Amount | Evidence | Classification |
|---|---:|---|---|
| SF approved RCV, claim 05-80C1-98PC | $61,461.87 | CO1 pp. 2–30 (SF estimate) | VERIFIED |
| SFPAY-1 issued 2025-04-10 (owner-attributed: asbestos) | $6,960.28 | SFPAY-1 | VERIFIED issuance; cashed; attribution owner-side only |
| SFPAY-2 issued 2025-05-02 (owner-attributed: main estimate) | $54,187.10 | SFPAY-2 | VERIFIED issuance; cashed |
| SFPAY-3 issued 2026-02-04 (owner-attributed: code upgrades) | $7,274.77 | SFPAY-3 | VERIFIED issuance; **UNCASHED, >6 months old** — R-014 |
| SF painting trade-summary total | $10,968.32 | CO1 (SF estimate) | VERIFIED |

Identity: **$54,187.10 + $7,274.77 = $61,461.87 = original + CO1**, to the penny. The dwelling
payments and the insurance-side contract reconcile exactly at aggregate level.
All three payments payable to `ANNE E. DEKUN & UMPQUA BANK ISAOA-ATIMA` — mortgagee-controlled.
The $6,960.28 asbestos payment is maintained SEPARATE; no contract credit assumed (INT-RECON §3).

## 3. Statement #1169 ledger — transcribed from the document face (read 2026-08-12)

Source: STMT-1169. Restoration Specialist Inc. dba Dry1out, dated 08/11/2026, TOTAL DUE $53,749.06.

| Date | Entry | Amount | Running balance |
|---|---|---:|---:|
| 06/02/2025 | Balance Forward | 0.00 | 0.00 |
| 06/03/2025 | Invoice #7700131 | 115,428.98 | 115,428.98 |
| 06/03/2025 | Payment #zelle | −3,500.00 | 111,928.98 |
| 06/09/2025 | Payment #Zelle | −2,000.00 | 109,928.98 |
| 01/27/2026 | Payment #6231805307 | −17,200.00 | 92,728.98 |
| 07/24/2026 | Payment #96 | −32,000.00 | 60,728.98 |
| 08/11/2026 | Payment #dd | −6,979.92 | **53,749.06** |

Aging row: entire $53,749.06 in "90+ Days Past Due"; all other buckets 0.00.

Derived (VERIFIED arithmetic on the statement face):

| Quantity | Amount |
|---|---:|
| Total payments credited by Dry1Out | **$61,679.92** |
| Payments predating 7/23/26 ($3,500 + $2,000 + $17,200) | **$22,700.00** |
| July 23 payments as posted (#96 $32,000 + #dd $6,979.92) | $38,979.92 |
| Invoice base (#7700131) | $115,428.98 |
| Signed contract total − invoice base ($123,659.84 − $115,428.98) | **$8,230.86** |

What the statement face does NOT establish: that $115,428.98 is the amount properly chargeable
(starting-balance rule, EXP-PROJECT); what invoice #7700131 comprises; why it is dated 06/03/2025
when CO1/CO2 were signed 12/11/2025 and CO3 on 6/23/2026 (see D-2); the source of each payment
(escrow vs. personal — R-012); why the 7/23-initiated wire posted 8/11 (see F-4).

## 4. Owner payments

| Payment | Amount | Owner evidence | Dry1Out posting (STMT-1169) | Classification |
|---|---:|---|---|---|
| Zelle | $3,500.00 | none in repository | 06/03/2025 "#zelle" | CLAIMED (by Dry1Out ledger) — owner-side confirmation open, R-012 |
| Zelle | $2,000.00 | none in repository | 06/09/2025 "#Zelle" | same |
| Payment #6231805307 | $17,200.00 | none in repository | 01/27/2026 | same — source (escrow draw?) unknown, R-012 |
| Check (escrow account, left at house 7/23) | $32,000.00 | Anne's 7/23 email (EMAIL-0812 thread) | 07/24/2026 "#96" | VERIFIED delivered + posted; negotiated-check image open (MANIFEST item 5) |
| Wire, initiated 7/23 | $6,979.92 | confirmation number in record (INT-RECON §5) | 08/11/2026 "#dd" | VERIFIED initiated + posted; final bank record to permanent file |

Delivered/cleared/credited are three separate facts (INT-RECON §5). The 7/23 pair is now
**credited** on Dry1Out's own statement; clearing evidence still open.

## 5. Balance-figure history (all figures are Dry1Out assertions unless noted)

| Date / context | Figure | Evidence |
|---|---:|---|
| 2026-06-30 initial demand | $38,159.84 | MANIFEST; Anne's 7/18 account (MR §7) |
| Anne's line-item reconstruction | $38,979.92 | MR §7 |
| Invoice #6780972 | $39,917.96 | MR §7; invoice not in repository (R-016) |
| 2026-07-07 "50% of each change order" policy, as computed | $31,098.99 | EXP-RECON; computation owner-side |
| 2026-08-11 Statement #1169 | **$53,749.06** | STMT-1169 — Dry1Out's number of record per Daniel's 8/10 framing |

## 6. Key non-financial facts

| ID | Fact | Evidence | Classification |
|---|---|---|---|
| F-1 | CSLB #993442 (Restoration Specialists Inc dba Dry1Out) shown suspended for failure to comply with an outstanding civil judgment, as of capture 2026-08-10 13:04 | CSLB-0810 | VERIFIED as to 8/10 status only. Effective date UNKNOWN — the decisive fact (R-013). License number not in frame. LEGAL REVIEW. |
| F-2 | Contractual completion date 7/10/2026 | CO3 | VERIFIED. Subsequent slips 7/31 → 9/11 per EXP-RECON; causation NOT reconciled (INT-RECON §15). |
| F-3 | Charles 8/7: paint scope "one color only" / "matched to existing" per "approved insurance scope" | EMAIL-0812 | CLAIMED–UNSUPPORTED. Framing not located in the SF estimate (FIND-2.0, INT-RECON §14). Scope document requested 8/10 — R-006. |
| F-4 | Charles asserted 8/5 and 8/7 that the 7/23 wire was not received; Dry1Out's own statement posts it 08/11 | EMAIL-0810, EMAIL-0812, STMT-1169 | VERIFIED tension on their paper. Whether "not received" was accurate when said (posting lag) vs. posted late is open — the 19-day initiation→posting gap is unexplained. |
| F-5 | 8/12 statement answered 1 of 6 items in Daniel's 8/10 records request | EMAIL-0812, STMT-1169 | VERIFIED — R-002…R-006 remain open. |
| F-6 | Daniel granted written owner-side authority 2026-07-10 | MANIFEST header | Anne retains all contractual signatures (EXP-PROJECT). |
| F-7 | CSLB capture (13:04) preceded Daniel's six-part records demand (13:41) by 37 minutes on 8/10 | MANIFEST sequencing note | Provenance/sequencing fact, preserved. |

## 7. Scope-overlap register (detail in INT-RECON §§9–14; status controlled here)

| Item | Figures | Classification |
|---|---|---|
| Fridge water line | CO2 plumbing $3,845 (incl. ice-maker rough-in) vs CO3 $850 relocate; not installed as of 7/19 per Anne | POTENTIAL OVERLAP — R-005 |
| Fridge/kitchen electrical | CO2 $950 vs CO3 $1,050 vs SF baseline kitchen electrical | POTENTIAL OVERLAP — crosswalk required, R-005 |
| Countertops | SF baseline countertop work vs CO3 unpriced upgrade | UNPRICED / UNAUTHORIZED — R-008 |
| Engineering | CO2 $12,800; Charles 7/20 stated he would also submit drawings supplement to SF | SUPPORT REQUIRED / possible future credit — R-009 |
| Hazardous material | CO2 $4,310.50; same estimate excludes asbestos/lead unless written | IDENTITY AND SUPPORT REQUIRED — R-010 |
| Paint | SF pays seal + finish by room, trade total $10,968.32 vs Charles's 8/7 narrowing | DOCUMENT REQUEST OPEN — R-006; Daniel's selections stand as working selections |

---

## 8. DISCREPANCY REGISTER — where documents in this repository disagree

### D-1 · The "$30,930.86 unexplained credit gap" is fully decomposed by STMT-1169's own face
**Recorded:** 2026-08-12, on line-by-line reading of STMT-1169.
**Carried by (all predate or omit the ledger reading):** MANIFEST "Key reconciliation" · INT-RECON §7, §21 · MR §6, §12 · TL-0812 · FIND-2.0 · EXP-RECON "$53,749.06 test."
**Decomposition:** the gap was computed as (contract $123,659.84 − balance $53,749.06) − 7/23
payments $38,979.92 = $30,930.86. The statement face supplies it exactly:
**$22,700.00** prior payments (6/3/25 Zelle $3,500 + 6/9/25 Zelle $2,000 + 1/27/26 #6231805307
$17,200 — omitted from the analyses, which treated 7/23 as the only owner payment)
**+ $8,230.86** invoice-base difference ($123,659.84 signed total − $115,428.98 invoice #7700131)
**= $30,930.86.**
**Effect:** "unexplained credit gap / UNRECONCILED $30,930.86" is a superseded characterization
wherever it appears. The live questions it collapses into: R-012 (confirm the $22,700 from owner
records and identify each source) and R-011 (what is the $8,230.86 invoice-base difference — note
it runs in Anne's FAVOR: Dry1Out has invoiced less than the signed total).
**Documents intentionally left unedited per project instruction 2026-08-12.**

### D-2 · Invoice #7700131 dated 06/03/2025 at $115,428.98 predates most of what it must contain
$115,428.98 exceeds the original contract ($54,448.97) by $60,980.01 and necessarily includes
CO1 + CO2 (signed 12/11/2025) and in whole or part CO3 (signed 6/23/2026). An invoice cannot have
issued in June 2025 at that amount for instruments executed 6–12 months later. Either the invoice
was restated in place under its original date (meaning Dry1Out's accounting does not preserve
history) or no 6/3/2025 invoice existed at that amount. Also explains D-3. → R-016.

### D-3 · Aging column is an artifact
Entire $53,749.06 shown "90+ Days Past Due," which follows mechanically from aging everything to
the 6/3/2025 invoice date. CO3 work (signed 6/23/26, completion 7/10/26) cannot be 90+ days past
due in August 2026. Harmless until late fees, interest, or collection posture attach to it. → R-017.

### D-4 · Two non-identical copies of the 8/10 CSLB capture — RESOLVED 2026-08-12
CSLB-0810 (118,523 B, hash BF38C71A…, matches MANIFEST's recorded hash) vs EXP-CSLB (109,299 B,
hash 5383EC6C…). **Resolved by pixel-level comparison:** both 1456×852, 144 DPI; decoded pixel
buffers are SHA-256 identical (`4B9C6C7B22B3314FFD5024D7209CA21418CA33E237E6A36E26E14D1935E9121E`).
The byte difference is PNG-container-only: the export pipeline decoded and re-encoded the image
(Apple `iDOT` chunk dropped, ICC profile 3149→355 B, XMP rewritten, IDAT stream recompressed).
The two files are the SAME capture with zero image-content difference — each corroborates the
other. CSLB-0810 remains the operative/best-evidence copy: it retains the native Apple chunk
signature (iDOT + full ICC + Apple-form eXIf) consistent with its Messages-attachment provenance.
Neither file embeds a capture timestamp; the 2026-08-10 13:04:02 time rests on the original
filename and MANIFEST's retrieval record, not on the image metadata. R-019 closed.

### D-5 · Findings v1.0 vs v2.0 on CSLB status
v1.0 asserts suspension as established fact; v2.0 downgrades to VERIFY. Current position: F-1
(status verified as of 8/10 capture only; effective date open). v1.0's workers'-comp "code 9008 /
Janitorial" assertion remains unsupported by anything in the repository (MANIFEST).

### D-6 · Export repo staleness
EXP-README and EXP-RECON state the statement PDF is unread/absent. STMT-1169 was obtained and
read 2026-08-12. Those statements are superseded; files left unedited.

### D-7 · Four balance figures in six weeks
$38,159.84 → $39,917.96 → ($31,098.99 computed) → $53,749.06 (§5). Not itself a contradiction on
Dry1Out's part until derivations are produced — but the derivation requests (R-002/R-003/R-004)
are what turns this from variance into either reconciliation or admission.
