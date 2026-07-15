# Research Outreach Packet

Status: prepared for human review. This packet contains no private contact
details and does not claim endorsement, peer review, or official benchmark
standing.

## Short Announcement

I have released Amoeba Core v2, an experimental substrate for governed
external reasoning around language models. The first working paper reports a
process-isolated equal-evidence study in which a fixed local model scored
18/48 with raw proposals, 14/48 when given the same evidence as flat prose,
and 48/48 under the governed route. The result is supported by a frozen
evidence ledger, explicit controls, provider-process isolation, and 219
machine-checked integrity assertions. The paper also reports its limits:
retrieval tied the system on a synthetic transfer set, the small untouched
holdout was non-significant, and no official benchmark or broad superiority
claim is made.

Paper: https://headsoft.org/research/equal-evidence/
Canonical record: https://doi.org/10.5281/zenodo.21367631
Source and artifacts: https://github.com/headsoftsoftware/amoeba_core_v2/tree/aa8cd1c3be49455592ac96ab516e15b340f1e3b4

## Researcher Outreach Draft

Subject: Request for criticism of a governed external-reasoning study

Hello [Name],

I am an independent researcher working on Amoeba Core v2, an experimental
substrate that places deterministic records, evidence authority, selectors,
proof obligations, and process isolation around a language model. I have
released a working empirical report with a public DOI and machine-verifiable
artifacts.

The central result is deliberately narrow: with the same local model and
matched evidence, a governed route reached 48/48 on a frozen 48-case task
family, compared with 14/48 for flat evidence injection and 18/48 for raw
proposals. The report also includes negative and non-significant results and
does not claim official leaderboard standing or general superiority over RAG.

I would value a skeptical reading of the experimental design, especially the
equal-resource comparison, transfer boundary, and whether the evidence
supports more than well-instrumented retrieval and verification.

Paper: https://headsoft.org/research/equal-evidence/
DOI: https://doi.org/10.5281/zenodo.21367631

Best,
Richard T. Elmore

## Posting Policy

- Keep the Zenodo v0.1 record as the canonical citation.
- Link any later public copy back to the DOI and identify it as the same
  version.
- Upload the paper and declared public artifacts only; do not publish private
  substrate state, unreleased implementation, credentials, or internal logs.
- Do not describe a preprint-server posting as peer review or endorsement.
- Record any later version as a new release with changed hashes and an explicit
  change summary.
