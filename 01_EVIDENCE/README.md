# 01_EVIDENCE — source documents only

Rule: nothing in this tree is edited, ever. Corrections and interpretations happen in
`_CONTEXT/FACTS.md`; superseded analysis lives in `02_ANALYSIS/`. Every file here is
hash-recorded in `_CONTEXT/HASHES.sha256` and mapped with provenance in
`_CONTEXT/DOCUMENT-MAP.md`.

| Folder | Contents | IDs |
|---|---|---|
| `contracts/` | Signed instruments. CO1 pp. 2–30 double as the full State Farm estimate (05-80C1-98PC) — the covered-scope source document. | CO1, CO2, CO3 |
| `insurance-payments/` | State Farm payment captures. | SFPAY-1, SFPAY-2, SFPAY-3 |
| `contractor-billing/` | Dry1Out statements and (when produced) invoices #7700131, #6780972, ledger. | STMT-1169 |
| `correspondence/` | Email thread exports. | EMAIL-0810, EMAIL-0812 |
| `regulatory/` | CSLB captures; certified license history when obtained (R-013). | CSLB-0810 |
| `owner-payments/` | Empty pending collection — see its README. | — |

Missing source documents this tree should eventually hold: original contract ($54,448.97, R-015),
invoices #7700131 / #6780972 (R-016), `Charles Correspondence 8_12_2026.pdf` (R-022), CO5 if ever
priced/signed (R-021 — currently DO NOT SIGN).

Naming convention: `YYYY-MM-DD_TYPE_descriptor_amount_status.ext`, dated by document date.
New arrivals: hash first, then file here, then row in DOCUMENT-MAP.
