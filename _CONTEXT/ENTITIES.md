# ENTITIES — people, organizations, accounts, identifiers

**As of:** 2026-08-12. The relationship map behind the documents.

## People

| Person | Role | Contact | Notes |
|---|---|---|---|
| **Anne Dekun** | Homeowner, insured, contracting party | — | Sole signatory on all contractual documents (per Charles 8/7 and project doctrine). Signed CO1/CO2 (12/11/25), CO3 (6/23/26). |
| **Daniel Minton** | Owner's representative | ohanadeveloper808@gmail.com | Written authority granted 2026-07-10 ("full decision power"). Coordinates, investigates, communicates; does NOT sign. |
| **Charles Cordova** | Dry1Out Director of Construction | charles@dry1out.com · (669) 232-4283 | Author of 8/5, 8/7, 8/12 messages; source of paint-narrowing claim (F-3) and wire non-receipt claims (F-4). |
| **Diego** (surname not in record) | Dry1Out project manager | via Dry1Out | Designated contractor-side point of contact 8/7; out until ~mid-week of 8/10; owes walkthrough windows (R-007). |
| **Austin Wells** | State Farm adjuster | 844-458-4300 ext. 60147 | Contact for reissue of the uncashed $7,274.77 check (R-014). |

## Organizations

| Entity | Identifiers | Notes |
|---|---|---|
| **Restoration Specialists, Inc. dba Dry1Out** | CSLB #993442 · 2536 Barrington Ct, Hayward CA 94545 · (888) 379-1688 · office@dry1out.com · www.dry1out.com | Corporation. License issued 06/06/2014, expires 06/30/2028. Status per 8/10/26 capture: **suspended — outstanding civil judgment** (F-1; effective date unknown, R-013). Entity name on every CO and email footer. |
| **State Farm** | Claim **05-80C1-98PC** (Fire or Lightning – Building) | Approved RCV $61,461.87. Estimate supplement dated 2025-09-30 (inside CO1). |
| **Umpqua Bank** | ISAOA/ATIMA co-payee | All three SF payments payable to `ANNE E. DEKUN & UMPQUA BANK ISAOA-ATIMA` — mortgagee-controlled proceeds. |
| **Escrow account** (institution not identified in record) | — | Source of the $32,000 check per Anne's 7/23 email. Possible source of the $17,200 1/27/26 payment — unconfirmed (R-012). |
| **Anne's other bank** ("BOA" per EXP-RECON) | — | Source of the $6,979.92 wire initiated 7/23. Printed wire record to be obtained. |
| **CSLB** | (800) 321-2752 | Source for certified license history with suspension effective dates (R-013). |

## Document identifiers

| Identifier | What | Where |
|---|---|---|
| Job **250033BC** | Dry1Out job number for the project | CO filenames, email subjects |
| Invoice **#7700131** | $115,428.98, dated 06/03/2025 — the statement's entire opening balance | STMT-1169 face; document itself not in repository (D-2, R-016) |
| Invoice **#6780972** | $39,917.96 (July) | MR §7; not in repository (R-016) |
| Statement **#1169** | 08/11/2026, $53,749.06 | STMT-1169 |
| SF payments **102742525J / 102759073J / 102938678J** | $6,960.28 / $54,187.10 / $7,274.77 | SFPAY-1/2/3 |
| Dry1Out ledger payment refs **#zelle, #Zelle, #6231805307, #96, #dd** | $3,500 / $2,000 / $17,200 / $32,000 / $6,979.92 | STMT-1169 |
| Estimate **CUSTOMER_UPGRADES** (2025-10-23) | Basis of CO2 | CO2 |
| **CO5** | Unsigned, unpriced, referenced only | EMAIL-0810 — do not sign (R-021) |

## Money flow (current understanding — allocation open per R-012)

```
State Farm ── 3 checks, $68,422.15 total ──► Anne + Umpqua (ISAOA/ATIMA)
                                              │   $6,960.28 cashed (asbestos-attributed, held SEPARATE)
                                              │   $54,187.10 cashed
                                              │   $7,274.77 UNCASHED (R-014)
                                              ▼
      escrow/mortgagee control ──?──► some Dry1Out payments (which ones: R-012)
Anne personal funds ──────────────► Zelles $5,500 (6/25)? · wire $6,979.92 (7/23)
                                              ▼
Dry1Out credited to date: $61,679.92 (STMT-1169) against invoice base $115,428.98
```
The escrow-vs-personal split of the $22,700 prior payments is the single fact that
re-allocates most of the asserted balance between insurance-funded and owner-funded scope.
