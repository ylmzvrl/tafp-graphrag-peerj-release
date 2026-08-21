# Final release gate report

Status: **HOLD — unpublished review candidate**

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
| Immutable public archive/DOI | NOT CREATED | External publication has not been authorized. |
| Public repository/data-availability statement | NOT READY | Must match an actually available, final, licensed release. |

No public release should occur until previously exposed credentials are rotated/revoked, a fresh scan passes, and the final publication target is authorized.
