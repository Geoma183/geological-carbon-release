# Reproducibility guide

## Current status

This is a documentation scaffold. Executable commands and reproducibility claims will be supplied only after the actual analysis entry points, frozen inputs, parameter files, and environment have been verified against the submission manuscript.

## Publication-ready reproduction contract

1. **Snapshot:** state the manuscript version, repository commit hash, and eventual GitHub release and Zenodo DOI.
2. **Sources:** record provider, title, source version, access date, original units, temporal and geographic coverage, licensing and checksums.
3. **Transformations:** record cleaning, country mapping, unit conversion, missing-value status, source conflicts, and reconstruction/interpolation logic.
4. **Parameters:** identify fixed assumptions, model coefficients, scenario settings, randomness/seed, and uncertainty distributions.
5. **Environment:** provide a tested runtime, dependency/lock file, system requirements, and precise execution commands.
6. **Order:** show each verified input → processing step → output dependency and expected file path.
7. **Quality assurance:** publish numerical closure, source coverage, year and country eligibility, sensitivity, and figure/table consistency checks.
8. **Outputs:** provide an index mapping released CSVs and figures to the actual tables, panels, and claims in the manuscript.

## Required checks

- Country/region-year key validity and explicit historical polity mapping.
- Source, unit, and gas consistency (CO₂ versus CO₂e).
- Separate missing, zero, not-applicable, observed, official, and reconstructed values.
- Closure within properly defined, non-overlapping physical accounts.
- Consistent results across text, tables, figures, supplementary information, and machine-readable data.
- Clean-environment reproduction when input licensing permits; document any restricted inputs instead of implying a fully executable public pipeline.

## Interpretation

Kaya identities and LMDI decompositions quantify accounting contributions rather than independent causal effects. Modern empirical relationships must not be mechanically extrapolated across 1750–2024. State uncertainty and evidence limitations, especially for historical reconstruction.
