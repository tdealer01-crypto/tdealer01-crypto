# DSG ONE — ProofGate

Deterministic deploy evidence, GO / NO-GO release gates, and audit-ready proof trails for GitHub Actions.

## Featured repositories

### 1. DSG Secure Deploy Gate Action

Open-source GitHub Action for readiness checks, protected-route checks, PR comments, and deterministic proof hashes.

- Marketplace: https://github.com/marketplace/actions/dsg-secure-deploy-gate
- Source: https://github.com/tdealer01-crypto/dsg-secure-deploy-gate-action

### 2. DSG Gate Demo Next.js

Minimal demo showing strict-mode DSG Gate with:

- `/api/readiness` → HTTP 200
- `/api/private-audit` → HTTP 401
- GitHub Actions GO / NO-GO PR comment
- evidence hash, proof hash, chain hash
- uploaded evidence artifact

Demo repo: https://github.com/tdealer01-crypto/dsg-gate-demo-nextjs

### 3. DSG ProofGate Control Plane

Runtime governance control plane and landing page for DSG ProofGate.

- App: https://tdealer01-crypto-dsg-control-plane.vercel.app/
- ProofGate Action page: https://tdealer01-crypto-dsg-control-plane.vercel.app/proofgate-github-action
- Source: https://github.com/tdealer01-crypto/tdealer01-crypto-dsg-control-plane

## Launch note

DSG Secure Deploy Gate v1.1.0 is live.

It adds:

- readiness checks
- protected-route checks
- GO / NO-GO PR comments
- evidence hash
- policy hash
- proof hash
- chain hash
- evidence artifact support

## Boundary

DSG creates deployment evidence for governance workflows. It is not a legal certification or third-party audit by itself.
