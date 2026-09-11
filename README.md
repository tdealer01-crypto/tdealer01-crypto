# Thanawat Suparongsuwan — DSG ONE

Building **DSG Spacetime**: a governed execution boundary for AI agents that need to act on real systems without bypassing authorization, policy, approval, or evidence.

DSG is not another model wrapper. The goal is to let different agents and providers reason freely while keeping real execution inside a deterministic control boundary.

```text
User / Agent
    ↓
DSG Spacetime
    ↓
Plan → Route → policy / approval
    ↓
Tool / API / browser / provider
    ↓
Evidence → verification → replay
```

## What I am building now

- **DSG Spacetime** — plan-bound authorization, governed Routes, entitlements, approvals, execution evidence, and fail-closed runtime behavior.
- **Governed Remote Browser** — Spacetime → Cinema → Azure Chromium for browser tasks with task-level approval rather than approval on every click.
- **Agent interoperability** — the reasoning model is replaceable; the execution boundary stays the same.
- **Production evidence** — real provider responses, hashes, CI results, runtime state, and replayable audit evidence instead of mock success claims.

## Current verified direction

The current production architecture runs governed workloads on **Azure Container Apps**. The Remote Browser path has been exercised through DSG Spacetime and Cinema using Azure-hosted Chromium, including governed `type`, `click`, approved-artifact `upload`, and quarantined `download` flows with evidence verification.

The automation model is intentionally practical:

- approve the **task**, not every ordinary browser step;
- continue in-scope low-risk actions automatically;
- fail closed when the task crosses into a different risk boundary;
- never treat generated text as authority to bypass policy;
- never auto-execute downloaded files;
- never claim production success without execution evidence.

## Featured public repositories

### DSG Spacetime — Public Source
Customer-hosted governance and execution boundary for AI infrastructure.

https://github.com/tdealer01-crypto/DSG-Spacetime-Source

### DSG Cinema Proof Agent
Governed remote browser, plan/approval binding, execution proof, and agent-facing integration work.

https://github.com/tdealer01-crypto/DSG-Cinema-Proof-Agent

### DSG Secure Deploy Gate
Deterministic release checks, GO / NO-GO evidence, and proof artifacts for GitHub Actions.

https://github.com/tdealer01-crypto/dsg-secure-deploy-gate-action

### DSG ONE v1
Public application/runtime work around the DSG ONE product surface.

https://github.com/tdealer01-crypto/dsg-one-v1

## Engineering principles

```text
No direct model → external API bypass
No mock success in production claims
No silent policy downgrade
Fail closed on missing authority
Evidence after execution
Replay before trust
```

The private production runtime, commercial signing material, customer state, and secrets are intentionally not published in the public repositories.

DSG evidence is a technical governance mechanism. It is not, by itself, a legal certification or an independent third-party audit.

**Let AI build the system — not just the code.**
