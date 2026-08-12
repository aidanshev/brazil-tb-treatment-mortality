# Brazil TB Treatment-Mortality Prediction

**Repository status:** `STAGING_ORIGINAL_FROZEN_CODE_PACKAGE_REQUIRED`

Treatment-initiation prediction of SINAN-recorded death during a TB treatment episode.

## Public-release policy

This repository is code/provenance-forward: raw patient-level surveillance data are excluded, third-party datasets are linked rather than mirrored, and image binaries are intentionally excluded. Source sites for visuals and data are recorded in `FIGURE_AND_IMAGE_PROVENANCE.md` and `DATA_SOURCES.md`.

Run before publishing:

```bash
python tools/public_release_audit.py
```

## Layout

- `code/` or `software/`: materialized analysis code
- `results/`: publication-safe aggregate results/receipts
- `manifests/`: identities and hashes without restricted raw data
- `docs/`: protocols/methods
- `REPOSITORY_STATUS.md`: completeness status

## Publication documentation

- `PUBLICATION_READINESS.md`: exact executable-package/reproducibility boundary
- `CODE_AVAILABILITY.md`: evidence-matched manuscript Code Availability language
- `RELEASE_CHECKLIST.md`: completed and remaining archival steps
- `results/`: locked aggregate performance and paired uncertainty results
- `CITATION.cff`: repository citation metadata

## Archival DOI

Do not describe this repository as the complete executable code release until the original final model-development/validation package is recovered and validated. After publication-safe materialization and fresh-extraction validation, create an immutable GitHub Release, archive it with Zenodo or an equivalent preservation service, and add the DOI to this README, `CITATION.cff`, and the manuscript.
