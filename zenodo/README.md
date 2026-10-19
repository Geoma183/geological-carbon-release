# Zenodo deposit preparation — NOT YET PUBLISHED

This directory prepares a citable research-data archive paired with a separately archived GitHub software release. **It is not a Zenodo draft record, published dataset, DOI, or verified reproduction package.**

## Two complementary records

1. **Zenodo Dataset (manual deposition):** a frozen, checksum-verified collection of the accepted data tables, model outputs, figure data and necessary documentation linked to the final manuscript version.
2. **Zenodo Software (GitHub integration):** an archived tagged GitHub Release with tested scripts, environment/configuration and citation metadata after licensing and creator approval.

Do not rely solely on the GitHub software archive to satisfy a journal data-deposition expectation. External original datasets may need to be linked and cited rather than redistributed.

## Contents of this preparation directory

- `dataset-record-draft.md` — proposed metadata, with unknown author/rights details **left blank intentionally**.
- `data-release-manifest.csv` — candidate local outputs identified from the research workspace; **no rows indicate completed upload**.
- `source-license-register.csv` — third-party source review starting list, not licensing determinations.
- `release-gates.md` — required steps to move from local candidate to a publishable dataset.
- `github-integration.md` — Zenodo account linkage and archive workflow.

## Current scope

The relevant local work packages currently identify a 12-country 1750–2024 lifecycle reconstruction, a 1990–2024 eight-factor Kaya–LMDI decomposition of direct geological CO2, and global lifecycle uncertainty/sensitivity work. Some archived local global tables also contain **provisional 2025 entries** and must be filtered or appropriately flagged before release. The actual submitted main manuscript remains the authority for which claims and figures may be released.

## Local archival policy

Keep received original attachments, earlier variants and internal reviewer/supervisor material in the existing private local workspace. The public package should contain only explicitly approved and documented material. Do not mirror the entire working directory to GitHub or Zenodo.

## References

- Zenodo: https://help.zenodo.org/docs/deposit/create-new-upload/
- Zenodo GitHub integration: https://help.zenodo.org/docs/github/enable-repository/
- GitHub archiving: https://help.zenodo.org/docs/github/archive-software/github-upload/
