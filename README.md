# Amoeba Core v2: Empirical Working Paper v0.1

This repository is the public announcement and paper-release companion for
Amoeba Core v2. It is intentionally separate from the private implementation
repository.

## Paper

**Equal Evidence, Different Outcomes: A Process-Isolated Study of Governed
External Reasoning Around a Small Language Model**

- [Read the paper online](https://headsoft.org/research/equal-evidence/)
- [Download the PDF](amoeba-equal-evidence-v0.1.pdf)
- [Canonical Zenodo record](https://doi.org/10.5281/zenodo.21367631)
- [HeadSoft research page](https://headsoft.org/research/)

## Headline result

In a frozen 48-case controlled task family, the same local model scored:

- raw proposals: `18/48`
- flat evidence injection: `14/48`
- governed route: `48/48`

The paper reports the controls, process-isolation checks, evidence ledger, and
negative results. The result is a bounded mechanism demonstration, not an
official benchmark claim or a claim of general superiority over retrieval,
frontier models, or autonomous science.

## Files

- `amoeba-equal-evidence-v0.1.pdf`: frozen public paper PDF.
- `amoeba-equal-evidence-v0.1-arxiv-source.zip`: clean-room arXiv source
  package, prepared but not yet submitted because of an account-verification
  issue.
- `CITATION.cff`: citation metadata.
- `PUBLIC_RELEASE_0_1.md`: release notes and claim boundaries.

The private Amoeba implementation and unreleased substrate data are not part
of this repository.
