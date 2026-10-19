# Dataset and code release gates

Status as of the initial Zenodo preparation: **NOT READY FOR PUBLICATION**.

## Gate 0 — Authority and scope

- [ ] Link all released results to the exact user-designated submission manuscript and supporting information; do not assume the latest numbered local Word file is the master.
- [ ] Document accepted temporal windows separately: global formal history through 2024, selected-country reconstruction 1750–2024, modern Kaya–LMDI 1990–2024.
- [ ] Check 2025 in source tables: if provisional/placeholder, exclude from the formal 1750–2024 Zenodo archive or document separately without implying observation.

## Gate 1 — Licensing, provenance and privacy

- [ ] Identify licenses for GCB-related inputs, WDI, UNSD AMA, IEA/EDGAR-based inputs, and all remaining third-party sources.
- [ ] Document redistribution permission for *each* file, not just each provider.
- [ ] Where redistribution is disallowed, publish a source accession/citation and legal access instructions instead.
- [ ] Exclude internal drafts, supervisor annotations, restricted attachments, personally identifying information and credentials.
- [ ] Confirm public-data authorship, permissions, author order and affiliations.

## Gate 2 — Physical and statistical validity

- [ ] Reconcile each published annual series, source sum and lifetime estimate to the formal accepted accounting boundary.
- [ ] Preserve separate CO2 vs CO2e columns and separate gross vs net fluxes.
- [ ] Preserve non-additive product-chain and MRIO quantities separately.
- [ ] Define uncertainty and simulation-based cumulative quantile procedures explicitly.
- [ ] Verify full 12-country historical coverage and evidence-status codes without converting missing to zero.
- [ ] Reconcile modern eight-factor Kaya equation and LMDI outputs with the submitted Methods.
- [ ] Disclose or resolve external diagnostic checks not meeting their pre-specified criteria; the local 161 README reports 8/9 met with one flaring-trend item requiring review.

## Gate 3 — Reproducibility

- [ ] Snapshot original-approved inputs and derived outputs with SHA-256 checksums.
- [ ] Record runtime/dependency locks, versioned parameters, random seed and execution order.
- [ ] Verify every published figure and table against the final manuscript and SI.
- [ ] Reproduce analyses in a controlled environment or document inaccessible licensed inputs.
- [ ] Include a release-level README with file inventory, formats, units, provenance and known limitations.

## Gate 4 — Zenodo and GitHub

- [ ] Prepare and publish the *dataset* in Zenodo only after the above checks.
- [ ] For software: connect the repository in Zenodo under the intended creator account.
- [ ] Do not trigger a GitHub Release tag that may be auto-archived while metadata are incomplete.
- [ ] Add `CITATION.cff` **or** `.zenodo.json` only after real creator metadata are confirmed; Zenodo prioritizes `.zenodo.json` if both exist.
- [ ] Record dataset DOI, software DOI, GitHub commit, exact tag and version-specific manuscript identity.
- [ ] Validate external DOI resolution and public file contents.

## Current known candidate-package QA (not public release certification)

- Package 138: locally reported 25/25 numeric and 104/104 programmatic visual checks.
- Package 159: locally reported 21/21 checks for direct CO2 LMDI.
- Package 160: locally reported 33/33 sensitivity checks.
- Package 161: includes simulation-first cumulative Monte Carlo quantile clarification; external/internal comparison is 8/9 with an unresolved diagnostic requiring review.

These local validations **do not** certify rights, manuscript matching, end-to-end reproduction or final public-release readiness.
