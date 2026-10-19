# Geological Carbon Release Since the Industrial Revolution

Data, code, and documentation for reconstructing anthropogenic release from geological carbon reservoirs, focusing on fossil fuels, carbonate minerals, accounting boundaries, historical changes, and socioeconomic drivers.

## Status

**Repository under preparation. This is not yet a verified reproduction package or a formal data release.** The current version contains documentation and templates. Manuscript-linked datasets and executable code will be uploaded only after version, provenance, licensing, and numerical consistency checks. No Zenodo DOI has yet been assigned. No repository-wide reuse license has yet been selected.

## Scientific scope

- Geological carbon sources: coal, oil, natural gas, limestone, dolomite, and their industrial uses.
- Research chain: geological carbon reservoirs → human extraction and use → anthropogenic release → socioeconomic drivers → temporal and spatial evolution → perturbation of the global carbon cycle.
- Long-term harmonization frame: 1750–2025. **Coverage does not imply observation** for every country–year; formal released results must state their actual temporal scope.

## Layered accounting principle

1. **Core boundary:** long-term directly released geological-carbon CO₂, with documented source-specific definitions and reconciliation.
2. **Extended boundary:** appropriately documented fugitive emissions, processing, transport, non-energy uses, end-of-life processes, and carbonation uptake.

Do not mechanically sum overlapping accounts. Clearly distinguish fossil-fuel extended lifecycle emissions, carbonate-mineral extended lifecycle net emissions, gross/net fluxes, direct/supply-chain emissions, production-/consumption-based responsibilities, and CO₂ versus CO₂e.

## Data governance

Use traceable country/region–year tables. Preserve original inputs and label observed values, official statistics, historical estimates, reconstructions, interpolated/extrapolated values, missing data, and not-applicable entries separately. **Missing ≠ 0.** Record units, source versions, dates, geographic mappings, model assumptions, and transformations. Modern data support mechanism analysis; historical reconstruction supports historical trajectory interpretation. Accounting decompositions do not, by themselves, identify causal effects.

## Directories

| Path | Purpose |
| --- | --- |
| `data/raw/` | Only original datasets legally approved for redistribution |
| `data/processed/` | Traceable harmonized inputs |
| `data/derived/` | Verified manuscript-linked derived data |
| `src/` | Tested processing and analysis code |
| `config/` | Versioned mapping files and parameters |
| `docs/` | Methods, sources, data dictionary, and release rules |
| `validation/` | Consistency, quality, and reproducibility checks |
| `results/` | Verified figure and table source data |

See [accounting boundaries](docs/accounting-boundaries.md), [reproducibility instructions](docs/reproducibility.md), and the [public release checklist](docs/release-checklist.md).

## Release and citation policy

Internal supervisor annotations, private correspondence, unverified results, restricted third-party source files, and credentials are not public release artifacts. Prior to a formal release, the team will select appropriate licenses for original code and releasable data, check external redistribution rights, establish version-specific input and output manifests, and archive a frozen snapshot via Zenodo. Do not cite a DOI until it has actually been minted.
