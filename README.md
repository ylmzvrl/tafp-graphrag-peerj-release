# TAFP-GraphRAG PeerJ sanitized public release

Status: **PUBLIC SANITIZED RELEASE**

This package was assembled from hash-pinned canonical evidence under handoff snapshot `PEERJ_HANDOFF_20260821T034414Z`. It contains exact-source code, configurations, environment files, historical runners, and 31 aggregate supplementary CSV tables.

`historical_runners/` preserves exact evidence files. Some retain historical Colab/Drive paths and are not represented as turnkey commands. `run_all_v8.py` and its direct local dependencies were recovered from Git branch `migration/evidence-locked-20260619` and verified by Git blob SHA.

It intentionally excludes third-party dataset text, graph node/edge data derived from real datasets, retrieved contexts, raw answers, `relation_qa_details.csv`, `results_checkpoint.jsonl`, notebooks, credentials, Git history, model caches, historical backups, manuscript/submission packages, and archives.

Dataset users must obtain AGNews (`fancyzhx/ag_news`), CNN/DailyMail (`abisee/cnn_dailymail`, config `3.0.0` as recorded), IMDB (`stanfordnlp/imdb`), and PubMed summarization (`ccdv/pubmed-summarization`) from their original providers and construct graphs locally. Historical upstream dataset revisions and the historical `datasets` package version were not recorded. The historical PubMed configuration was not recovered and must not be inferred.

Project-authored software is provided under the MIT License; see `LICENSE`. This license does not grant redistribution rights for third-party datasets, which are not included.

The distributed package passed manifest membership, file-size, SHA-256, Python-syntax, restricted-file, forbidden-file-class, and static secret-pattern checks. A credential pattern previously observed in an excluded historical notebook is not included in this release; its account-level revocation status was not independently verified by this release audit.

Audit documents:

- `THIRD_PARTY_LICENSE_AUDIT.md`
- `REPRODUCIBILITY_AUDIT.md`
- `FINAL_RELEASE_GATE_REPORT.md`

`environment/requirements_peerj_reproduction.txt` provides unpinned current import coverage. It is not an exact reconstruction of the historical software environment.
