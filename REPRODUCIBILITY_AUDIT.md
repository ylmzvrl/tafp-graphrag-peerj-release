# Reproducibility audit

## Passed

- All included Python files parse successfully.
- The nine externally imported Python packages are represented in `environment/requirements_peerj_reproduction.txt`.
- Five recorded base configuration files are included.
- `run_all_v8.py` and its direct local dependencies are hash-pinned to recovered Git blobs.
- Thirty-one aggregate supplementary result tables are included and hash-manifested.
- No experiment was executed during package verification.

## Boundaries

- The reproduction requirements are unpinned current import coverage, not a recovered historical environment freeze.
- Historical upstream dataset revisions and the historical `datasets` package version were not recorded.
- The historical PubMed dataset configuration was not recovered and is not inferred.
- Real-dataset text and row-level derived artifacts are intentionally excluded for redistribution safety.
- Files under `historical_runners/` preserve evidence. Some contain historical Colab/Drive paths or expect excluded inputs and are not turnkey commands.
- A complete clean-room numerical reproduction has not been run from this sanitized package.

Conclusion: the package provides auditable source, configurations, dependency coverage, historical runners, and aggregate outputs, but it must not be described as an exact frozen or one-command reproduction environment.
