# Publication readiness

## Current release class

`STAGING_ORIGINAL_FROZEN_CODE_PACKAGE_REQUIRED`

This repository preserves the locked 2024 aggregate performance results, paired differences, scientific claim boundaries, data-source documentation, and public-release safety tooling. The original complete model-development package has not been recovered into the public tree.

## Reproducibility boundary

The manuscript record describes a temporally locked design with 2017-2022 development/selection, 2023 calibration, and 2024 temporal evaluation, including archived preprocessing, fitted-model, prediction, bootstrap, and stage-receipt artifacts. Those original executable artifacts are not currently materialized here. New code has not been invented and labeled as the executed pipeline.

The endpoint is SINAN-recorded death during a treatment episode. It is not a validated fixed-horizon mortality endpoint and the 2024 evaluation is temporal internal evaluation rather than external or prospective validation.

## Publication safeguards

- Locked aggregate metrics and paired uncertainty results are retained under `results/`.
- Raw patient-level surveillance records are excluded.
- `tools/public_release_audit.py` and GitHub Actions enforce the public-tree safety policy.
- `CITATION.cff` does not claim a release version or DOI before a real immutable release exists.

## Remaining blockers to a complete code archive

1. Recover the original final model-development/validation package and verify its internal hashes/receipts.
2. Materialize publication-safe source, configuration, tests, environment information, model specification, and figure/table reproduction inputs without redistributing patient-level data.
3. Re-run the package's validation checks from a fresh extraction.
4. Select an explicit software license after ownership/upstream-license review.
5. Create an immutable release and preservation DOI only after steps 1-4 pass.

Until the exact executed package is recovered, this repository should be cited as a results/provenance staging deposit rather than a complete code reproducibility archive.
