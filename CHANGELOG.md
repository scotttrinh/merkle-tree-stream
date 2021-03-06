## 2018-10-28, Version 0.8.0
### Commits
- [[`b6096eacff`](https://github.com/datrs/merkle-tree-stream/commit/b6096eacffc96765271307cbf30bd613b414b4af)] (cargo-release) version 0.8.0 (Yoshua Wuyts)
- [[`770347ec82`](https://github.com/datrs/merkle-tree-stream/commit/770347ec82cdd5bf5b207088be2535f76364576f)] Use NodeKind enum instead of Option for PartialNode data (#18) (Scott Trinh)
- [[`04b163a5d1`](https://github.com/datrs/merkle-tree-stream/commit/04b163a5d1ccb06f995576152280bde5241c0ef4)] Update changelog (Yoshua Wuyts)

### Stats
```diff
 CHANGELOG.md        | 25 +++++++++++++++++++++++++
 Cargo.toml          |  2 +-
 examples/main.rs    |  7 +++++--
 src/default_node.rs |  6 +++---
 src/lib.rs          | 24 +++++++++++++++---------
 src/partial_node.rs | 14 +++++++++++---
 tests/lib.rs        | 20 +++++++++++---------
 7 files changed, 71 insertions(+), 27 deletions(-)
```


## 2018-10-17, Version 0.7.0
### Commits
- [[`8fe517e043`](https://github.com/datrs/merkle-tree-stream/commit/8fe517e0432d35563c3f89956a7065ec3cbdb9ef)] (cargo-release) version 0.7.0 (Yoshua Wuyts)
- [[`3468de73e7`](https://github.com/datrs/merkle-tree-stream/commit/3468de73e7dc011838d762dc3be18e7cea026049)] Fix features (#17) (Yoshua Wuyts)
- [[`961426a0b4`](https://github.com/datrs/merkle-tree-stream/commit/961426a0b42cebdfafc75a6d6001a03f16929019)] Add doctest for MerkleTreeStream (#16) (Kuba)
- [[`42eb089703`](https://github.com/datrs/merkle-tree-stream/commit/42eb0897034fae63f443364b82c1115f15cc16aa)] Update rust_sodium requirement from 0.7.0 to 0.10.0 (#14) (dependabot[bot])
- [[`f2552f963f`](https://github.com/datrs/merkle-tree-stream/commit/f2552f963f4d29d7a9da5df59b66e579d19782b1)] Update quickcheck requirement from 0.6.2 to 0.7.1 (#15) (dependabot[bot])
- [[`2543672317`](https://github.com/datrs/merkle-tree-stream/commit/2543672317e82e3879fc7942cec74d6e83b49c37)]  Keep up with modern times in clippy invocation (#13) (Szabolcs Berecz)
- [[`bfe9fa5630`](https://github.com/datrs/merkle-tree-stream/commit/bfe9fa56307a8db8245abb6d32e8ecd944d1e980)] Update .github (Yoshua Wuyts)

### Stats
```diff
 .github/ISSUE_TEMPLATE.md                 |  40 +----------
 .github/ISSUE_TEMPLATE/bug_report.md      |  23 ++++++-
 .github/ISSUE_TEMPLATE/feature_request.md |  30 ++++++++-
 .github/ISSUE_TEMPLATE/question.md        |  18 +++++-
 .travis.yml                               |   5 +-
 Cargo.toml                                |   7 +--
 examples/main.rs                          |  43 ++++--------
 src/lib.rs                                | 113 +++++++++++++++++++++++++++++--
 tests/lib.rs                              |  41 ++++-------
 9 files changed, 221 insertions(+), 99 deletions(-)
```


