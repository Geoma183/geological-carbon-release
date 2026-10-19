# Zenodo and GitHub: archiving instructions

## Dataset DOI (data deposit)

Use Zenodo **New upload → Resource type: Dataset** for the actual approved data package; then add verified creators, publication metadata, permissions, licenses and links to the software archive. Save a draft until all checks pass. Zenodo can reserve a DOI ahead of publication, but **none has been reserved for this project**.

The draft metadata is in `dataset-record-draft.md`. This is **not** a deposit and does not mint a DOI.

## Software DOI (GitHub release archive)

1. Sign in to the intended Zenodo account.
2. Link the appropriate GitHub account to Zenodo if not already linked.
3. In Zenodo's profile menu choose **GitHub**, click **Sync now**, and enable `Geoma183/geological-carbon-release`.
4. Confirm final author metadata and licensing. Add validated citation metadata to the repository. Zenodo supports `CITATION.cff` and `.zenodo.json`, but when both exist it uses `.zenodo.json`.
5. Once scripts, parameters, environment, figure outputs and validation pass, create a versioned **GitHub Release** from the frozen commit. Do not create a release simply to archive today's scaffolding.
6. Verify the processed Zenodo Software record and record its issued DOI separately from the Dataset DOI.
7. Cross-link the two records and the eventual article DOI.

**Do not** claim the GitHub integration is activated or that a DOI exists until independently confirmed.

Official references:

- https://help.zenodo.org/docs/github/enable-repository/
- https://help.zenodo.org/docs/github/archive-software/github-upload/
- https://help.zenodo.org/docs/github/describe-software/
- https://help.zenodo.org/docs/deposit/create-new-upload/
- https://help.zenodo.org/docs/deposit/describe-records/reserve-doi/
