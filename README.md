# WP2 — Track 1.2 Evidence Ledger

This **independent** evidence ledger is distinct from the frozen OPWS/Saleor source repositories.
Git tracks claim-ready summaries, file inventories, and SHA-256 provenance. Raw evidence stays
on local drives until separately reviewed for credentials, privacy, size and licensing.

## Milestone status (2026-10-27)
- M01D: Option B (`REUSE_NOT_PERMITTED`) sealed prospectively.
- Historical R7/R8: preserved; not new prospective comparisons.
- M02-Q: control qualification STOP; 0/27 fresh behavioral observations.
- M02-E: NOT_AUTHORIZED; 0/13 prospective comparator evaluations.
- Frozen plan: SHA256 `62ef73588d302553596b9eb6161f03df5a4fe0df4c131390a9b61138754ac401`.
- The last R7 retry passed frozen input preflight and WSL tree materialization,
  then STOPped on `ModuleNotFoundError: No module named 'scripts'` before JUnit.

## What this repository proves
Each row of `EVIDENCE_INDEX.csv` identifies original local evidence and a separately
verified backup with the same content hash. The index does **not** mean the raw file
is stored in GitHub. Git commit IDs identify the ledger version; SHA-256 identifies
original evidence bytes. Do not use these as substitutes for executing controls.

See `CLAIM_REGISTER.md`, `REPRODUCIBILITY_GATES.md` and `EVIDENCE_POLICY.md`.
