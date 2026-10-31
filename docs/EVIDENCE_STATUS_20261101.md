# DSG ONE — public evidence status and entry points

**Index written:** 2026-11-01 (Asia/Bangkok). **Latest supported public archival evidence date:** 2026-10-30 UTC. This is a *navigation and disclosure* update; it does **not** report a new production test, re-run the private model, or independently verify the complete system.

## Open the evidence (no account required for the public materials)

| Surface | Link | Evidence boundary |
|---|---|---|
| Public evidence site | https://dsg-public-evidence.shipstatic.com/ | TH/EN public-safe report; ShipStatic account lists the domain as live on 2026-11-01; this is not a new endpoint GET/agent E2E proof |
| Machine-readable evidence | https://dsg-public-evidence.shipstatic.com/evidence.json | Public empirical summary; not private raw receipts |
| Agent navigation | https://dsg-public-evidence.shipstatic.com/llms.txt | Public discovery index |
| GitHub release | https://github.com/tdealer01-crypto/doi/releases/tag/v1.2.0 | Public release tag |
| Zenodo v1.2.0 | https://zenodo.org/records/23796173 | Archived publication / DOI 10.5281/zenodo.23796173 |
| Publication verification | https://github.com/tdealer01-crypto/doi/blob/main/PUBLICATION_STATUS.md | Observed archival verification 2026-10-30T07:19:26.963979Z |
| Reproduction script | https://github.com/tdealer01-crypto/doi/blob/main/docs/VERIFY_RELEASE_V1_2_0.md | No-credential archive and GitHub tree comparison |
| Scoped production report | https://github.com/tdealer01-crypto/doi/blob/v1.2.0/docs/DSG_NVIDIA_PRODUCTION_PUBLIC_PROOF_20261030.md | Limited live acceptance, original records are restricted |
| Reproduction limits | https://github.com/tdealer01-crypto/doi/blob/main/docs/PUBLIC_REPRODUCTION_PROTOCOL_20261030.md | Public/restricted/unverified checks |

## Evidence ledger: do not combine separate proofs

| Check | Supported outcome | Time and lineage |
|---|---|---|
| Published archive checksum and 24 file blob comparisons | **VERIFIED (documented)** | 2026-10-30; release commit `1880eb4519e0d1b7cf6b7b598d710d34779647c7`; SHA-256 `ded472103bba0dbf5518f7eaf869bdf5f7c1e10df611be427fc30916ddd4465b` |
| Bounded read-only NVIDIA Nemotron API Workroom → browser read → Memory | **VERIFIED for a specified private-record-backed production slice, per dated public report** | 2026-10-30; image `sha256:94115f03476e93a8dbce43cbdcf37951c4a148d3c998ae87683c7185cd7a8f10` |
| Evidence chain reported valid with 532 records | **REPORTED VERIFIED AT SNAPSHOT; NOT A CURRENT LIVE COUNTER** | 2026-10-30 control-plane observation, not retested 2026-11-01 |
| Public third-party reproduction of Production E2E | **UNVERIFIED** | Private execution records are not downloadable anonymously |
| Original Ed25519 CI payload and public detached-signature verification | **NOT PUBLICLY REPLAYABLE** | Private original was reported internally verified; no new public signature is invented |
| Autonomous agent recovery, native-device E2E, arbitrary mutations, Kaggle 30B | **NOT ESTABLISHED BY THIS ARCHIVE** | Requires dedicated new live tests and primary receipts |
| New public evidence after 30 October 2026 | **NO NEW VERIFIED PACKAGE IDENTIFIED IN THE REVIEWED PUBLICATION STATUS** | Do not describe a newer PR, CI PASS, screenshot or website health as a fresh production proof |

## Release and UI integrity

The five ecosystem repository links in the GitHub profile were checked through the authenticated GitHub repository metadata on 2026-11-01 and returned `visibility: public`. That establishes the repositories exist; it does not establish the anonymous website rendering or every linked route is functioning end-to-end.

The `dsg-secure-deploy-gate-action@v1.1.0` tag was fetched and its `action.yml` input contract checked. A documented `@v2.0.0` example could not be resolved as a tag in this check and is **not** used in the profile Quick Start. A genuine GitHub Actions demo screenshot exists at `docs/media/demo-workflow-success.jpg`; it is not claimed to be a ten-second Production recording.

## Next valid evidence update

Publish a *new dated public record* only after capturing a fresh bounded, authorized E2E run with exact source/image, plan and route, real provider result, independent observation, evidence hash and replay/negative results as applicable. Sanitize sensitive details; preserve the original primary receipt privately and mark public-verification limits. Do not silently edit the immutable Zenodo v1.2.0 release.
