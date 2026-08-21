# Final release gate report

Status: **PUBLIC SANITIZED RELEASE — STATIC PACKAGE GATES PASSED**

| Gate | Result | Basis |
|---|---|---|
| Manifest membership, size, and SHA-256 | PASS after V5 rebuild | Every distributed file must be listed and reverified. |
| Python syntax | PASS | All included Python files parsed successfully. |
| Dependency import coverage | PASS WITH LIMITATION | Requirements cover external imports but are not historically pinned. |
| Restricted real-dataset row-level artifacts excluded | PASS | No raw dataset text, contexts, answers, `relation_qa_details.csv`, or `results_checkpoint.jsonl`. |
| Embedded archive, Git metadata, notebook, cache exclusion | PASS after clean ZIP rebuild | Distribution excludes these classes. |
| Candidate secret-pattern scan | PASS after clean ZIP rebuild | This does not replace rotation/revocation of the previously observed token before publication. |
| Third-party dependency license compatibility | PASS | Imported dependencies are permissively licensed and are not vendored. |
| Project repository license | PASS | Author approved MIT; `LICENSE` is included. |
| Exact historical environment | NOT RECOVERED | Must not be claimed. |
| Clean-room numerical reproduction | NOT RUN | No experiment was authorized or executed. |
| Public GitHub repository | PASS | Published at `ylmzvrl/tafp-graphrag-peerj-release`. |
| Immutable public archive/DOI | NOT CREATED | GitHub is public but is not an immutable DOI archive. |
| Manuscript data-availability statement | PENDING | Must use verified public and immutable archive URLs. |

The public sanitized package contains no detected credential pattern. Account-level revocation of the credential previously observed in an excluded historical notebook was not independently verified and remains a separate security action.
